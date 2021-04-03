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
ms.openlocfilehash: 78d200b4d33693aa0092fe9a7c768fef67e6721e
ms.sourcegitcommit: 5863f79973406ef27d5904509c0aef059e25c17b
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/02/2021
ms.locfileid: "51506784"
---
# <a name="release-notes-for-beta-channel"></a><span data-ttu-id="40624-103">ベータ チャネルのリリース ノート</span><span class="sxs-lookup"><span data-stu-id="40624-103">Release Notes for Beta Channel</span></span>

<span data-ttu-id="40624-104">この記事には、Windows デスクトップ向け Word、Excel、PowerPoint、Outlook、Access、Project のベータ チャネル ビルドのリリース ノートが含まれています。</span><span class="sxs-lookup"><span data-stu-id="40624-104">This article contains release notes for Beta Channel builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="40624-105">Microsoft では、毎週、皆様にお知らせしたい魅力的な新機能、重要な修正プログラム、重大な問題に関する情報を提供しています。</span><span class="sxs-lookup"><span data-stu-id="40624-105">Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="40624-106">多くの場合、機能 (場合によっては修正プログラムも) は、特定の期間にわたってベータ チャネルにロールアウトされます。</span><span class="sxs-lookup"><span data-stu-id="40624-106">Note that we often roll out features (and sometimes even fixes) to Beta Channel over a period of time.</span></span> <span data-ttu-id="40624-107">これにより、Microsoft では、より広範な対象ユーザーに機能をリリースする前に、作業がスムーズに行われていることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="40624-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="40624-108">以下に示すものが表示されない場合でも、最終的には入手できますのでご安心ください。</span><span class="sxs-lookup"><span data-stu-id="40624-108">So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="40624-109">現在、Microsoft 365 Apps の更新プログラム チャネルに、新しい更新プログラム チャネル (月次エンタープライズ チャネル) の追加や既存の更新プログラム チャネル名の変更など、いくつかの変更を進めています。</span><span class="sxs-lookup"><span data-stu-id="40624-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="40624-110">詳細については、[こちらの記事](/DeployOffice/update-channels-changes)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="40624-110">To learn more, [read this article](/DeployOffice/update-channels-changes).</span></span>

> [!NOTE]
> - <span data-ttu-id="40624-111">リリース ノートは毎週投稿され、場合により複数のビルドのコンパイルになります。</span><span class="sxs-lookup"><span data-stu-id="40624-111">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="40624-112">リリースノートの発行日は実際のビルドのリリース日と一致しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="40624-112">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (削除しないでください)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

## <a name="version-2104-april-02"></a><span data-ttu-id="40624-115">バージョン 2104: 4 月 2 日</span><span class="sxs-lookup"><span data-stu-id="40624-115">Version 2104: April 02</span></span>
<span data-ttu-id="40624-116">*バージョン 2104 (ビルド 13929.20016)*</span><span class="sxs-lookup"><span data-stu-id="40624-116">*Version 2104 (Build 13929.20016)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-118">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-118">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-119">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-119">Outlook</span></span>

- <span data-ttu-id="40624-120">**Outlook for Windows での自動応答の候補:** 短い返信メッセージで返信できるメール メッセージを受信した場合、Outlook は 3 つの返信を提案し、ユーザーはその中から選ぶだけでわずか数クリックで返信できます。</span><span class="sxs-lookup"><span data-stu-id="40624-120">**Suggested Replies in Outlook for Windows:** When you receive an email message that can be answered by a short response, Outlook can suggest three responses you can use to reply with just a couple of clicks.</span></span>

- <span data-ttu-id="40624-121">**共有カレンダーの更新を有効にする**: Office 365 の共有カレンダーの場合、Outlook では REST API を使用してこれらのカレンダーを更新します。</span><span class="sxs-lookup"><span data-stu-id="40624-121">**Turn on shared calendar improvements:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="40624-122">共有カレンダーのより高速で信頼性の高い更新を行うには、プレビューを有効にします。</span><span class="sxs-lookup"><span data-stu-id="40624-122">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-125">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-125">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="40624-126">Access</span><span class="sxs-lookup"><span data-stu-id="40624-126">Access</span></span>

- <span data-ttu-id="40624-127">外部アプリケーションがアクセシビリティ インターフェイスを要求した場合、そのインターフェイスが参照を解放するまでシャットダウンできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-127">We fixed an issue when an external application requests an accessibility interface, it will prevent us from shutting down until they release their reference.</span></span>


### <a name="word"></a><span data-ttu-id="40624-128">Word</span><span class="sxs-lookup"><span data-stu-id="40624-128">Word</span></span>

- <span data-ttu-id="40624-129">このバグでは、特定のポリシーは Office によって適用されません (テンプレートのグループが無効になっているはずのホーム ページに表示されています)。</span><span class="sxs-lookup"><span data-stu-id="40624-129">In this bug, specific policies weren't being honored by Office (a group of templates were being shown on the Home Page when they should have been disabled).</span></span> <span data-ttu-id="40624-130">この修正により、ポリシーが適用されます。</span><span class="sxs-lookup"><span data-stu-id="40624-130">With this fix, the policies are being honored.</span></span>


- <span data-ttu-id="40624-131">自動保存の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-131">We fixed an issue in auto save.</span></span>


- <span data-ttu-id="40624-132">Application.OnTime で修正を行いましたが、正しくトリガーされない可能性があります。</span><span class="sxs-lookup"><span data-stu-id="40624-132">We made a fix in Application.OnTime where it might not trigger correctly.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2104-march-26"></a><span data-ttu-id="40624-134">バージョン 2104: 3 月 26 日</span><span class="sxs-lookup"><span data-stu-id="40624-134">Version 2104: March 26</span></span>
<span data-ttu-id="40624-135">*バージョン 2104 (ビルド 13919.20002)*</span><span class="sxs-lookup"><span data-stu-id="40624-135">*Version 2104 (Build 13919.20002)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-137">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-137">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-138">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-138">Outlook</span></span>

- <span data-ttu-id="40624-139">フォルダー階層の変更を同期するときに、Outlook が予期せず終了するという一部のユーザーの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-139">We fixed an issue that caused some users to experience Outlook to close unexpectedly when syncing folder hierarchy changes.</span></span>


### <a name="word"></a><span data-ttu-id="40624-140">Word</span><span class="sxs-lookup"><span data-stu-id="40624-140">Word</span></span>

- <span data-ttu-id="40624-141">貼り付けたテキストで、コピーと貼り付けのスタイルが同じにならない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-141">We fixed an issue which copy and paste styles may not be same in pasted text.</span></span>


### <a name="office-suite"></a><span data-ttu-id="40624-142">Office スイート</span><span class="sxs-lookup"><span data-stu-id="40624-142">Office Suite</span></span>

- <span data-ttu-id="40624-143">テキストの反復に関連するパフォーマンスの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-143">Fixed a performance issue related to iteration of text.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2104-march-19"></a><span data-ttu-id="40624-145">バージョン 2104: 3 月 19 日</span><span class="sxs-lookup"><span data-stu-id="40624-145">Version 2104: March 19</span></span>
<span data-ttu-id="40624-146">*バージョン 2104 (ビルド 13913.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-146">*Version 2104 (Build 13913.20000)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-148">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-148">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="40624-149">Access</span><span class="sxs-lookup"><span data-stu-id="40624-149">Access</span></span>

- <span data-ttu-id="40624-150">SQL Server パススルー クエリを実行すると、"無効なカーソル状態" があったことを示すエラー メッセージが表示されることがある問題がこの変更により修正されます。</span><span class="sxs-lookup"><span data-stu-id="40624-150">This change fixes an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="40624-151">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-151">Excel</span></span>

- <span data-ttu-id="40624-152">保護されたシートに数式として貼り付けることができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-152">We fixed a problem that was preventing the ability to paste as formulas on a protected sheet.</span></span>


### <a name="project"></a><span data-ttu-id="40624-153">Project</span><span class="sxs-lookup"><span data-stu-id="40624-153">Project</span></span>

- <span data-ttu-id="40624-154">日付の形式が W4/4 の場合、日付の選択に間違った日と年が表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-154">Fixed an issue where if the date format is W4/4, the date picker may show the wrong day and year.</span></span>


### <a name="office-suite"></a><span data-ttu-id="40624-155">Office スイート</span><span class="sxs-lookup"><span data-stu-id="40624-155">Office Suite</span></span>

- <span data-ttu-id="40624-156">Office での GDI + LineJoinMiterClipped のサポートに関する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="40624-156">Fixes an issue with support of GDI+ LineJoinMiterClipped in Office.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2104-march-12"></a><span data-ttu-id="40624-158">バージョン 2104: 3 月 12 日</span><span class="sxs-lookup"><span data-stu-id="40624-158">Version 2104: March 12</span></span>
<span data-ttu-id="40624-159">*バージョン 2104 (ビルド 13906.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-159">*Version 2104 (Build 13906.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-161">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-161">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="40624-162">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-162">PowerPoint</span></span>

- <span data-ttu-id="40624-163">**PowerPoint に Flipgrid ビデオを挿入する:** PowerPoint は、スライドへの Flipgrid ビデオの挿入をサポートするようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-163">**Insert Flipgrid videos in PowerPoint:** PowerPoint will now support insertion of Flipgrid videos in slides.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-166">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-166">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-167">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-167">Excel</span></span>

- <span data-ttu-id="40624-168">ファイルを PDF ドキュメントとして保存すると、HYPERLINK 関数を使用して作成したハイパーリンクが機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-168">We fixed an issue in which hyperlinks created using the HYPERLINK function would not work if the file was saved as a PDF document.</span></span>


### <a name="word"></a><span data-ttu-id="40624-169">Word</span><span class="sxs-lookup"><span data-stu-id="40624-169">Word</span></span>

- <span data-ttu-id="40624-170">共同編集中のコメントの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-170">We fixed an issue with comments during coauthoring.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2103-march-05"></a><span data-ttu-id="40624-172">バージョン 2103: 3 月 5 日</span><span class="sxs-lookup"><span data-stu-id="40624-172">Version 2103: March 05</span></span>
<span data-ttu-id="40624-173">*バージョン 2103 (ビルド 13901.20036)*</span><span class="sxs-lookup"><span data-stu-id="40624-173">*Version 2103 (Build 13901.20036)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-175">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-175">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="40624-176">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-176">Excel</span></span>

- <span data-ttu-id="40624-177">**機密性の高い暗号化されたドキュメントの自動保存と共同編集:** 生産性とセキュリティをトレードオフしないでください。</span><span class="sxs-lookup"><span data-stu-id="40624-177">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="40624-178">Microsoft Information Protection により、秘密度ラベルで暗号化されたドキュメントを、暗号化されていないドキュメントと同じように、自動保存して他のユーザーとリアル タイムで共同編集できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-178">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="40624-179">テナントのオプトインが必要です (詳細: https://aka.ms/mipcoauth)。</span><span class="sxs-lookup"><span data-stu-id="40624-179">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-180">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-180">PowerPoint</span></span>

- <span data-ttu-id="40624-181">**機密性の高い暗号化されたドキュメントの自動保存と共同編集:** 生産性とセキュリティをトレードオフしないでください。</span><span class="sxs-lookup"><span data-stu-id="40624-181">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="40624-182">Microsoft Information Protection により、秘密度ラベルで暗号化されたドキュメントを、暗号化されていないドキュメントと同じように、自動保存して他のユーザーとリアル タイムで共同編集できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-182">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="40624-183">テナントのオプトインが必要です (詳細: https://aka.ms/mipcoauth)。</span><span class="sxs-lookup"><span data-stu-id="40624-183">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="word"></a><span data-ttu-id="40624-184">Word</span><span class="sxs-lookup"><span data-stu-id="40624-184">Word</span></span>

- <span data-ttu-id="40624-185">**機密性の高い暗号化されたドキュメントの自動保存と共同編集:** 生産性とセキュリティをトレードオフしないでください。</span><span class="sxs-lookup"><span data-stu-id="40624-185">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="40624-186">Microsoft Information Protection により、秘密度ラベルで暗号化されたドキュメントを、暗号化されていないドキュメントと同じように、自動保存して他のユーザーとリアル タイムで共同編集できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-186">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="40624-187">テナントのオプトインが必要です (詳細: https://aka.ms/mipcoauth)。</span><span class="sxs-lookup"><span data-stu-id="40624-187">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-190">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-190">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-191">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-191">Excel</span></span>

- <span data-ttu-id="40624-192">日本語フォントで乗算または除算記号を使用すると、フォントが予期せず変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-192">Corrected an issue where the font would change unexpectedly when using a multiplication or divide sign with a Japanese font.</span></span> <span data-ttu-id="40624-193">文字をサポートしている場合は、引き続き同じフォントを使用します。</span><span class="sxs-lookup"><span data-stu-id="40624-193">We now continue to use the same font if it supports the character.</span></span>


- <span data-ttu-id="40624-194">.xls または .xlt 形式で保存するときに、一部のピボットテーブル形式でブックが破損する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-194">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


- <span data-ttu-id="40624-195">ブックを開いたときに予期せずメモが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-195">We fixed an issue where some notes were unexpectedly shown when opening a workbook.</span></span>


### <a name="outlook"></a><span data-ttu-id="40624-196">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-196">Outlook</span></span>

- <span data-ttu-id="40624-197">CSV にエクスポートするときに非 ASCII 文字が正しくエクスポートされない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-197">We fixed an issue that caused non-ASCII characters to export incorrectly when exporting to CSV.</span></span>


- <span data-ttu-id="40624-198">メールを作成するときに、ユーザーが [名前の確認] で連絡先グループを検索できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-198">We fixed an issue that caused users to be unable to look up a contact group with Check Names  when composing mail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="40624-199">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-199">PowerPoint</span></span>

- <span data-ttu-id="40624-200">PowerPoint スライドショー モードで折れ線グラフの矢印が期待どおりに表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-200">We fixed an issue where arrows in line charts were not appearing as expected in PowerPoint slideshow mode.</span></span>


### <a name="word"></a><span data-ttu-id="40624-201">Word</span><span class="sxs-lookup"><span data-stu-id="40624-201">Word</span></span>

- <span data-ttu-id="40624-202">Microsoft Information Protection (MIP) ラベルで保護されたファイルを開くとき、MIP で保護されたラベルにアクセスできる ID にユーザーがサインインしていない場合、無期限にハングする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-202">We fixed an issue where opening a file protected with a Microsoft Information Protection (MIP) label can hang indefinitely if the user is not signed in to an identity that has access to the MIP protected label.</span></span> <span data-ttu-id="40624-203">ユーザーは、サインイン プロンプトを表示するためにオープンをキャンセルする必要があり、オープンはその時点以降にのみ成功します。</span><span class="sxs-lookup"><span data-stu-id="40624-203">The user is forced to cancel the open to show the sign-in prompt, and the open only succeeds after that point.</span></span> <span data-ttu-id="40624-204">開く/ダウンロード中にサインイン プロンプトを表示できるようにすることで、この問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="40624-204">Fixing this issue by allowing the sign-in prompt to be shown during open/download.</span></span>


- <span data-ttu-id="40624-205">新しい単語コメントでディクテーションを使用する際の問題を修正しました。コメント カードのディクテーション ボタンが正しくオンとオフを切り替えるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-205">We fixed an issue when using Dictation in the new Word Commenting, the Dictation button in the Comment card now correctly toggles on and off.</span></span>


- <span data-ttu-id="40624-206">ユーザーがドキュメントにディクテーションしたときに単語の間にスペースが挿入されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-206">Fixed an issue where there was no space being inserted between words when users dictated into their document.</span></span>


- <span data-ttu-id="40624-207">RTL で入力された複数行のコメントを投稿すると、2 行目以降が右ではなく左に配置される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-207">We fixed an issue when posting multi-line comments typed in RTL caused the 2nd and onward lines to be aligned to the left instead of the right.</span></span>


- <span data-ttu-id="40624-208">スペル チェックが 2 つの異なるスペル修正コンテキスト メニュー間で切り替わる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-208">We fixed an issue where spell check switched between two different spelling correction context menus.</span></span>


- <span data-ttu-id="40624-209">列のテキストが重複する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-209">We fixed an issue where columns might have overlapping text.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2103-february-26"></a><span data-ttu-id="40624-211">バージョン 2103: 2 月 26 日</span><span class="sxs-lookup"><span data-stu-id="40624-211">Version 2103: February 26</span></span>
<span data-ttu-id="40624-212">*バージョン 2103 (ビルド 13819.20006)*</span><span class="sxs-lookup"><span data-stu-id="40624-212">*Version 2103 (Build 13819.20006)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-214">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-214">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-215">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-215">Excel</span></span>

- <span data-ttu-id="40624-216">ユーザーが Excel ブックを PDF にエクスポートできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-216">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="40624-217">共同編集中にシートをコピーした際、一部の書式設定が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-217">We fixed an issue where some formatting could be lost when copying a sheet while coauthoring.</span></span>


### <a name="outlook"></a><span data-ttu-id="40624-218">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-218">Outlook</span></span>

- <span data-ttu-id="40624-219">DRM 保護を削除すると、添付ファイルが重複して表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-219">We fixed an issue that caused users to see attachments getting duplicated when removing DRM protection.</span></span>


### <a name="project"></a><span data-ttu-id="40624-220">プロジェクト</span><span class="sxs-lookup"><span data-stu-id="40624-220">Project</span></span>

- <span data-ttu-id="40624-221">Project Web App からローカル ファイルにプロジェクトを保存するときに、タスクの分割が誤って作成される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-221">Fixed an issue where task splits may be wrongly created when saving a project from Project web app to a local file.</span></span> <span data-ttu-id="40624-222">これは、非標準の作業時間のタスク カレンダーが使用されていた場合に発生します。</span><span class="sxs-lookup"><span data-stu-id="40624-222">This would happen if a task calendar with non-standard working times was being used.</span></span>


- <span data-ttu-id="40624-223">インジケーター列が最初の列スポットにない場合、「サマリー タスクを切り取ると、サブタスクも削除されます」という警告が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-223">Fixed an issue where if the indicator column is not in the first column spot, when you cut a summary task you aren't warned that the subtasks will also be removed.</span></span>


- <span data-ttu-id="40624-224">ユーザーがタイムシートで [タスクに自分自身を追加] 機能を選択した場合に、作成された割り当てで適切なリソース利用可能時間の単位が使用されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-224">Fixed an issue where if a user selected the Add Yourself to a Task function on their Timesheet, the correctly resource availability units may not be used on the created assignment.</span></span>


### <a name="word"></a><span data-ttu-id="40624-225">Word</span><span class="sxs-lookup"><span data-stu-id="40624-225">Word</span></span>

- <span data-ttu-id="40624-226">複数のコメントの配置に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-226">We fixed an issue with alignment of multiple comments.</span></span>


- <span data-ttu-id="40624-227">[音声読み上げ] 作業ウィンドウの、キーボード ショートカットの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-227">We fixed an issue in Read Aloud task pane keyboard shortcuts.</span></span>


### <a name="office-suite"></a><span data-ttu-id="40624-228">Office スイート</span><span class="sxs-lookup"><span data-stu-id="40624-228">Office Suite</span></span>

- <span data-ttu-id="40624-229">OneDrive の場所は、グループ ポリシー設定に応じて適切にフィルター処理されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-229">OneDrive places are now filtered out as appropriate per the group policy setting.</span></span>


- <span data-ttu-id="40624-230">EMF 画像の読み込み時に発生する可能性がある無応答に関連した問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-230">Fixes an issue related to unresponsiveness that may occur when loading EMF images.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2103-february-19"></a><span data-ttu-id="40624-232">バージョン 2103: 2 月 19 日</span><span class="sxs-lookup"><span data-stu-id="40624-232">Version 2103: February 19</span></span>
<span data-ttu-id="40624-233">*バージョン 2103 (ビルド 13811.20002)*</span><span class="sxs-lookup"><span data-stu-id="40624-233">*Version 2103 (Build 13811.20002)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-235">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-235">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-236">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-236">Outlook</span></span>

- <span data-ttu-id="40624-237">DRM 保護を削除すると、添付ファイルが重複して表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-237">We fixed an issue that caused users to see attachments getting duplicated when removing DRM protection.</span></span>


### <a name="project"></a><span data-ttu-id="40624-238">プロジェクト</span><span class="sxs-lookup"><span data-stu-id="40624-238">Project</span></span>

- <span data-ttu-id="40624-239">インジケーター列が最初の列スポットにない場合、「サマリー タスクを切り取ると、サブタスクも削除されます」という警告が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-239">Fixed an issue where if the indicator column is not in the first column spot, when you cut a summary task you aren't warned that the subtasks will also be removed.</span></span>


- <span data-ttu-id="40624-240">ユーザーがタイムシートで [タスクに自分自身を追加] 機能を選択した場合に、作成された割り当てで適切なリソース利用可能時間の単位が使用されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-240">Fixed an issue where if a user selected the Add Yourself to a Task function on their Timesheet, the correctly resource availability units may not be used on the created assignment.</span></span>


### <a name="word"></a><span data-ttu-id="40624-241">Word</span><span class="sxs-lookup"><span data-stu-id="40624-241">Word</span></span>

- <span data-ttu-id="40624-242">[音声読み上げ] 作業ウィンドウの、キーボード ショートカットの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-242">We fixed an issue in Read Aloud task pane keyboard shortcuts.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2103-february-12"></a><span data-ttu-id="40624-244">バージョン 2103: 2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="40624-244">Version 2103: February 12</span></span>
<span data-ttu-id="40624-245">*バージョン 2103 (ビルド 13806.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-245">*Version 2103 (Build 13806.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-247">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-247">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-248">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-248">Outlook</span></span>

- <span data-ttu-id="40624-249">**Microsoft Search を利用した作成 (To\CC\BCC) の提案:** To\CC 行へのユーザーの追加は、Microsoft Search を利用するようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-249">**Microsoft Search powered compose (To\CC\BCC) suggestions:** Adding people to the To\CC line is now powered by Microsoft Search.</span></span>

- <span data-ttu-id="40624-250">**ディクテーションはより多くの言語で利用できます:** ディクテーションは 7 つの新しい言語をサポートするようになりました: ヒンディー語、ロシア語、ポーランド語、ポルトガル語 (ポルトガル)、韓国語、タイ語、中国語 (台湾)</span><span class="sxs-lookup"><span data-stu-id="40624-250">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>

### <a name="word"></a><span data-ttu-id="40624-251">Word</span><span class="sxs-lookup"><span data-stu-id="40624-251">Word</span></span>

- <span data-ttu-id="40624-252">**ディクテーションはより多くの言語で利用できます:** ディクテーションは 7 つの新しい言語をサポートするようになりました: ヒンディー語、ロシア語、ポーランド語、ポルトガル語 (ポルトガル)、韓国語、タイ語、中国語 (台湾)</span><span class="sxs-lookup"><span data-stu-id="40624-252">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-255">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-255">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-256">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-256">Excel</span></span>

- <span data-ttu-id="40624-257">画像を取得できないためにデータ型カードを表示しようとすると、Excel が予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-257">Fixed an issue where Excel would sometimes close unexpectedly when trying to show the Data Types card due to a not being able to retrieve an image.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-258">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-258">PowerPoint</span></span>

- <span data-ttu-id="40624-259">アニメーションおよびオーディオ ブックマークのループの問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="40624-259">Fixes an issue with looping animations and audio bookmarks.</span></span>

### <a name="project"></a><span data-ttu-id="40624-260">Project</span><span class="sxs-lookup"><span data-stu-id="40624-260">Project</span></span>

- <span data-ttu-id="40624-261">100% 完了したタスクが 99% 完了に戻る問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-261">Fixed an issue where a task that are 100% complete may revert back to 99% complete.</span></span>

- <span data-ttu-id="40624-262">JAWS を実行しているときにタスク情報ダイアログに移動すると、Project が予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-262">Fixed an issue where Project may close unexpectedly if you are running JAWS and go to the task information dialog.</span></span>

### <a name="word"></a><span data-ttu-id="40624-263">Word</span><span class="sxs-lookup"><span data-stu-id="40624-263">Word</span></span>

- <span data-ttu-id="40624-264">自動保存の問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="40624-264">We fixed an issue in AutoSave.</span></span>


- <span data-ttu-id="40624-265">共同編集中の競合を解決する際の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-265">We fixed an issue in resolving conflicts while in coauthoring.</span></span>




[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2102-february-05"></a><span data-ttu-id="40624-267">バージョン 2102: 2 月 5 日</span><span class="sxs-lookup"><span data-stu-id="40624-267">Version 2102: February 05</span></span>
<span data-ttu-id="40624-268">*バージョン 2102 (ビルド 13801.20004)*</span><span class="sxs-lookup"><span data-stu-id="40624-268">*Version 2102 (Build 13801.20004)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-270">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-270">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="40624-271">Access</span><span class="sxs-lookup"><span data-stu-id="40624-271">Access</span></span>

- <span data-ttu-id="40624-272">Access で選択したタブがよりはっきりと表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-272">You will now see selected tabs clearer in Access.</span></span>


### <a name="excel"></a><span data-ttu-id="40624-273">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-273">Excel</span></span>

- <span data-ttu-id="40624-274">グラフでデータ系列を選択した後に Excel が応答を停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-274">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="40624-275">Android で特定のキーボードを使用して Enter キーを押すと、次のセルに移動するのではなく、新しい行が追加される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-275">We fixed an issue where pressing Enter with certain keyboards on Android would add a new line rather than moving to the next cell.</span></span>


- <span data-ttu-id="40624-276">トリミング操作中に画像のアスペクト比が保持されることに関連する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-276">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="outlook"></a><span data-ttu-id="40624-277">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-277">Outlook</span></span>

- <span data-ttu-id="40624-278">デジタル署名のオプションのチェックを外した後も、メールがデジタル署名されたものとして送信される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-278">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="40624-279">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-279">PowerPoint</span></span>

- <span data-ttu-id="40624-280">トリミング操作中に画像のアスペクト比が保持されることに関連する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-280">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="word"></a><span data-ttu-id="40624-281">Word</span><span class="sxs-lookup"><span data-stu-id="40624-281">Word</span></span>

- <span data-ttu-id="40624-282">トリミング操作中に画像のアスペクト比が保持されることに関連する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-282">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


- <span data-ttu-id="40624-283">コメントがリンクで切り捨てられる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-283">We fixed an issue which the comment may be truncated with links.</span></span>


- <span data-ttu-id="40624-284">共同編集時に競合モードになる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-284">We fixed an issue with conflict mode when coauthoring.</span></span>


- <span data-ttu-id="40624-285">SharePoint Online に保存する際に発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="40624-285">We fixed an issue in saving to SharePoint Online</span></span>


- <span data-ttu-id="40624-286">Word 文書を PDF にエクスポートする際の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-286">We fixed an issue in exporting Word document to PDF.</span></span>


### <a name="office-suite"></a><span data-ttu-id="40624-287">Office スイート</span><span class="sxs-lookup"><span data-stu-id="40624-287">Office Suite</span></span>

- <span data-ttu-id="40624-288">あるサインイン アカウントの機密ラベルを表示する必要があるときに、特定の状況で Office が別のサインイン アカウントの機密ラベルを表示する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-288">Fixed an issue where Office would in some circumstances present sensitivity labels for one signed-in account when it should present sensitivity labels for a different signed-in account.</span></span>




[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2102-january-29"></a><span data-ttu-id="40624-290">バージョン 2102: 1 月 29 日</span><span class="sxs-lookup"><span data-stu-id="40624-290">Version 2102: January 29</span></span>
<span data-ttu-id="40624-291">*バージョン 2102 (ビルド 13721.20008)*</span><span class="sxs-lookup"><span data-stu-id="40624-291">*Version 2102 (Build 13721.20008)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-293">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-293">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-294">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-294">Excel</span></span>

- <span data-ttu-id="40624-295">[名前の定義] ダイアログで名前を追加したときに Excel が予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-295">We fixed a problem where Excel would unexpectedly quit when you added a Name in the Define Name dialog.</span></span>


### <a name="outlook"></a><span data-ttu-id="40624-296">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-296">Outlook</span></span>

- <span data-ttu-id="40624-297">[暗号化のみ] オプションを使用して送信された電子メールの暗号化アイコンが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-297">We fixed an issue that caused the encryption icon to fail to display for emails sent using the Encrypt Only option.</span></span>

### <a name="project"></a><span data-ttu-id="40624-298">Project</span><span class="sxs-lookup"><span data-stu-id="40624-298">Project</span></span>

- <span data-ttu-id="40624-299">キリル文字の長い名前のプロジェクトをプロジェクト センターから開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-299">Fixed an issue where projects with long Cyrillic names could not be opened through Project Center.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2102-january-22"></a><span data-ttu-id="40624-301">バージョン 2102: 1 月 22 日</span><span class="sxs-lookup"><span data-stu-id="40624-301">Version 2102: January 22</span></span>
<span data-ttu-id="40624-302">*バージョン 2102 (ビルド 13714.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-302">*Version 2102 (Build 13714.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-304">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-304">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="40624-305">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-305">Excel</span></span>

- <span data-ttu-id="40624-306">**政府機関のお客様: ドキュメントおよびメールに秘密度ラベルを適用する:** GCC および GCC-H 環境のお客様は、秘密度のラベル付け機能を利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-306">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="40624-307">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-307">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a><span data-ttu-id="40624-308">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-308">Outlook</span></span>

- <span data-ttu-id="40624-309">**政府機関のお客様: ドキュメントおよびメールに秘密度ラベルを適用する:** GCC および GCC-H 環境のお客様は、秘密度のラベル付け機能を利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-309">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="40624-310">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-310">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="powerpoint"></a><span data-ttu-id="40624-311">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-311">PowerPoint</span></span>

- <span data-ttu-id="40624-312">**政府機関のお客様: ドキュメントおよびメールに秘密度ラベルを適用する:** GCC および GCC-H 環境のお客様は、秘密度のラベル付け機能を利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-312">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="40624-313">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-313">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="word"></a><span data-ttu-id="40624-314">Word</span><span class="sxs-lookup"><span data-stu-id="40624-314">Word</span></span>

- <span data-ttu-id="40624-315">**政府機関のお客様: ドキュメントおよびメールに秘密度ラベルを適用する:** GCC および GCC-H 環境のお客様は、秘密度のラベル付け機能を利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-315">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="40624-316">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-316">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-319">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-319">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-320">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-320">Excel</span></span>

- <span data-ttu-id="40624-321">ファイルを再度開いたときに、セルの連続していない範囲を使用する特定のグラフが読み込まれない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="40624-321">Fixes issue where certain charts using discontinuous ranges of cells would not load when files are re-opened.</span></span>


- <span data-ttu-id="40624-322">特定の Windows セキュリティのエクスプロイト保護設定 (SimExec、CallerCheck) を使用している場合に、Excel の起動に失敗したり、予期せずクラッシュしたりしてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-322">Fixes an issue where Excel would fail to launch or crash unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="40624-323">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-323">PowerPoint</span></span>

- <span data-ttu-id="40624-324">色付きの絵文字を表示すると発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-324">Fixed an issue related to displaying emojis with color.</span></span>


### <a name="word"></a><span data-ttu-id="40624-325">Word</span><span class="sxs-lookup"><span data-stu-id="40624-325">Word</span></span>


- <span data-ttu-id="40624-326">これにより、インターネット接続が一定期間失われた後、リアルタイムの入力とプレゼンスが復元されない問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="40624-326">This fixes an issue that prevented real-time typing and presence from being restored after loosing internet connectivity for a period of time.</span></span>


- <span data-ttu-id="40624-327">共同編集の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-327">We fixed an issue with coauthoring.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2102-january-15"></a><span data-ttu-id="40624-329">バージョン 2102: 1 月 15 日</span><span class="sxs-lookup"><span data-stu-id="40624-329">Version 2102: January 15</span></span>
<span data-ttu-id="40624-330">*バージョン 2102 (ビルド 13707.20008)*</span><span class="sxs-lookup"><span data-stu-id="40624-330">*Version 2102 (Build 13707.20008)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-332">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-332">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-333">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-333">Outlook</span></span>

- <span data-ttu-id="40624-334">**Teamsと共有:** Outlook からのメールや会話を Teams のユーザーまたはチャネルと共有します。</span><span class="sxs-lookup"><span data-stu-id="40624-334">**Share to Teams:** Share an email or a conversation from Outlook to a person or channel in Teams.</span></span>

### <a name="visio"></a><span data-ttu-id="40624-335">Visio</span><span class="sxs-lookup"><span data-stu-id="40624-335">Visio</span></span>

- <span data-ttu-id="40624-336">**図に適した既製のグラフィック:** アイコン、株の写真画像、ユーザーの切り抜き、ステッカーの大きなライブラリから選び、Visio 図面に追加できます。</span><span class="sxs-lookup"><span data-stu-id="40624-336">**Ready-made graphics for your diagrams:** Choose from a large library of icons, stock photo images, cutout people, and stickers that you can add to your Visio drawings.</span></span> [<span data-ttu-id="40624-337">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-337">Learn more</span></span>](https://support.office.com/article/0ab844a5-289b-47f2-ba92-eeda168bc381)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-340">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-340">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="40624-341">Project</span><span class="sxs-lookup"><span data-stu-id="40624-341">Project</span></span>

- <span data-ttu-id="40624-342">コスト型リソースがマイルストーン タスクに割り当てられたとき、基準コストが正しくロールアップされないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-342">Fixed an issue where when a cost resource was assigned to a milestone task, baseline cost didn't rollup correctly.</span></span>


### <a name="word"></a><span data-ttu-id="40624-343">Word</span><span class="sxs-lookup"><span data-stu-id="40624-343">Word</span></span>

- <span data-ttu-id="40624-344">VBA マクロ実行中に ExportAsFixedFormat2 が、"プレゼンテーション (不明のメンバー) の不正な値" というエラーが表示され失敗する問題を修正しています。</span><span class="sxs-lookup"><span data-stu-id="40624-344">Fixing a failure when running the VBA macro ExportAsFixedFormat2 fails with an error stating "Presentation (unknown member) illegal value".</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2102-january-08"></a><span data-ttu-id="40624-346">バージョン 2102: 1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="40624-346">Version 2102: January 08</span></span>
<span data-ttu-id="40624-347">*バージョン 2102 (ビルド 13704.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-347">*Version 2102 (Build 13704.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-349">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-349">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-350">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-350">Outlook</span></span>

- <span data-ttu-id="40624-351">**ディクテーションが改善されました:** 新しい [ディクテーション] ツールバー、[音声コマンド]、および [自動句読点のサポート] を使用して、音声でのコンテンツ作成がさらに簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="40624-351">**Dictation just got better:** It's now easier to create content with your voice with the new dictation toolbar, voice commands, and auto-punctuation support</span></span>

### <a name="word"></a><span data-ttu-id="40624-352">Word</span><span class="sxs-lookup"><span data-stu-id="40624-352">Word</span></span>

- <span data-ttu-id="40624-353">**ディクテーションが改善されました:** 新しい [ディクテーション] ツールバー、[音声コマンド]、および [自動句読点のサポート] を使用して、音声でのコンテンツ作成がさらに簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="40624-353">**Dictation just got better:** It's now easier to create content with your voice with the new dictation toolbar, voice commands, and auto-punctuation support</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-356">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-356">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-357">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-357">Excel</span></span>

- <span data-ttu-id="40624-358">PowerPoint での埋め込まれた Excel の範囲のプレビューでサイズが正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-358">We have fixed an issue where Preview of embedded Excel range in PowerPoint shows incorrect size.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2101-january-01"></a><span data-ttu-id="40624-360">バージョン 2101: 1 月 1 日</span><span class="sxs-lookup"><span data-stu-id="40624-360">Version 2101: January 01</span></span>
<span data-ttu-id="40624-361">*バージョン 2101 (ビルド 13624.20002)*</span><span class="sxs-lookup"><span data-stu-id="40624-361">*Version 2101 (Build 13624.20002)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-363">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-363">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="40624-364">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-364">Excel</span></span>

- <span data-ttu-id="40624-365">**必須のラベル付け:** 必須のラベル付けポリシーが設定されているユーザーについては、管理者がユーザーのドキュメントやメールにラベル付けを行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="40624-365">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-366">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-366">PowerPoint</span></span>

- <span data-ttu-id="40624-367">**必須のラベル付け:** 必須のラベル付けポリシーが設定されているユーザーについては、管理者がユーザーのドキュメントやメールにラベル付けを行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="40624-367">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="word"></a><span data-ttu-id="40624-368">Word</span><span class="sxs-lookup"><span data-stu-id="40624-368">Word</span></span>

- <span data-ttu-id="40624-369">**必須のラベル付け:** 必須のラベル付けポリシーが設定されているユーザーについては、管理者がユーザーのドキュメントやメールにラベル付けを行う必要があります。</span><span class="sxs-lookup"><span data-stu-id="40624-369">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-372">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-372">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="40624-373">OneNote</span><span class="sxs-lookup"><span data-stu-id="40624-373">OneNote</span></span>

- <span data-ttu-id="40624-374">この変更により、OneNote に影響を与えるレンダリングの問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-374">This change addresses a rendering issue affecting OneNote.</span></span>


### <a name="outlook"></a><span data-ttu-id="40624-375">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-375">Outlook</span></span>

- <span data-ttu-id="40624-376">この変更により、エンド ユーザーに対して Exchange Online アーカイブ メールボックスを表示しないようにする Exchange サーバーの設定を Outlook で利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="40624-376">This change enables Outlook to take advantage of an Exchange server setting that suppresses the display of the Exchange Online Archive Mailbox to end users.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="40624-377">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-377">PowerPoint</span></span>

- <span data-ttu-id="40624-378">この変更により、図形の結合がテキストを操作するときに発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-378">This change addresses an issue with Merge Shapes working with text.</span></span>


### <a name="word"></a><span data-ttu-id="40624-379">Word</span><span class="sxs-lookup"><span data-stu-id="40624-379">Word</span></span>

- <span data-ttu-id="40624-380">最新コメントをより堅牢なものにするための修正を行いました。</span><span class="sxs-lookup"><span data-stu-id="40624-380">Fix to make Modern comments more robust.</span></span>


- <span data-ttu-id="40624-381">@Mention を含むコメント投稿を編集するときに発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-381">Fixed an issue when editing commenting post with @mention.</span></span>


- <span data-ttu-id="40624-382">新しい Word インスタンスを作成すると、コメントの下書きが消えます。</span><span class="sxs-lookup"><span data-stu-id="40624-382">Comment drafts disappears when creating a new Word instance.</span></span>


- <span data-ttu-id="40624-383">修正と、コメント ウィンドウ内のネストされたスクロール バーに関する問題。</span><span class="sxs-lookup"><span data-stu-id="40624-383">Fix and issue with nested scrollbars in the comments pane.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2101-december-25"></a><span data-ttu-id="40624-385">バージョン 2101: 12 月 25 日</span><span class="sxs-lookup"><span data-stu-id="40624-385">Version 2101: December 25</span></span>
<span data-ttu-id="40624-386">*バージョン 2101 (ビルド 13617.20002)*</span><span class="sxs-lookup"><span data-stu-id="40624-386">*Version 2101 (Build 13617.20002)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-388">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-388">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-389">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-389">Excel</span></span>

- <span data-ttu-id="40624-390">Excel からグラフをコピーして Word に貼り付けるときに、10 進数と桁区切りの記号の設定を継承するように更新しました</span><span class="sxs-lookup"><span data-stu-id="40624-390">Update so that decimal and thousands separators settings carryover when copying a chart from Excel and pasting into Word</span></span>


- <span data-ttu-id="40624-391">無効なファイル属性 (作成時刻、修正時刻など) を持つ UNC ファイルを開くと、Excel が予期せず終了してしまう可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-391">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="40624-392">この変更では、SVG 画像の枠線の色の変更に関する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="40624-392">This change addresses an issue related to changing outline colors of SVG images.</span></span>


### <a name="outlook"></a><span data-ttu-id="40624-393">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-393">Outlook</span></span>

- <span data-ttu-id="40624-394">Word から差し込み印刷を開始するときに、ユーザーがアクセスを許可する時間の長さを指定できず、ユーザーに対して余分なプロンプトが表示されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-394">We fixed an issue that caused users to be unable to specify how long they wanted to allow access for when starting a mail merge from Word, resulting in them getting excess prompts.</span></span>


- <span data-ttu-id="40624-395">引き換えベースのアドインのユーザーの Outlook が予期せず終了してしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-395">We fixed an issue that caused a Outlook to close unexpectedly for users of Redemption based Add-ins.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="40624-396">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-396">PowerPoint</span></span>

- <span data-ttu-id="40624-397">この変更では、SVG 画像の枠線の色の変更に関する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="40624-397">This change addresses an issue related to changing outline colors of SVG images.</span></span>


### <a name="word"></a><span data-ttu-id="40624-398">Word</span><span class="sxs-lookup"><span data-stu-id="40624-398">Word</span></span>

- <span data-ttu-id="40624-399">この変更では、SVG 画像の枠線の色の変更に関する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="40624-399">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="40624-400">コメント カードの返信ボックスが画面に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-400">Fixes an issue where the reply box on a comment card is off the screen.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2101-december-18"></a><span data-ttu-id="40624-402">バージョン 2101: 12 月 18 日</span><span class="sxs-lookup"><span data-stu-id="40624-402">Version 2101: December 18</span></span>
<span data-ttu-id="40624-403">*バージョン 2101 (ビルド 13610.20002)*</span><span class="sxs-lookup"><span data-stu-id="40624-403">*Version 2101 (Build 13610.20002)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-405">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-405">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="40624-406">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-406">Excel</span></span>

- <span data-ttu-id="40624-407">**M365 の管理者に機密度ラベルに関する監査データを送信する** : ユーザーがドキュメントやメールに機密度ラベルを適用、変更、または削除したときに、Office は M365 監査バックエンドに監査データを送信し管理者の目に入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="40624-407">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="40624-408">これは、管理者のためのサイレント機能 (UI なし) です。</span><span class="sxs-lookup"><span data-stu-id="40624-408">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-409">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-409">Outlook</span></span>

- <span data-ttu-id="40624-410">**M365 の管理者に機密度ラベルに関する監査データを送信する** : ユーザーがドキュメントやメールに機密度ラベルを適用、変更、または削除したときに、Office は M365 監査バックエンドに監査データを送信し管理者の目に入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="40624-410">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="40624-411">これは、管理者のためのサイレント機能 (UI なし) です。</span><span class="sxs-lookup"><span data-stu-id="40624-411">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-412">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-412">PowerPoint</span></span>

- <span data-ttu-id="40624-413">**M365 の管理者に機密度ラベルに関する監査データを送信する** : ユーザーがドキュメントやメールに機密度ラベルを適用、変更、または削除したときに、Office は M365 監査バックエンドに監査データを送信し管理者の目に入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="40624-413">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="40624-414">これは、管理者のためのサイレント機能 (UI なし) です。</span><span class="sxs-lookup"><span data-stu-id="40624-414">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="word"></a><span data-ttu-id="40624-415">Word</span><span class="sxs-lookup"><span data-stu-id="40624-415">Word</span></span>

- <span data-ttu-id="40624-416">**M365 の管理者に機密度ラベルに関する監査データを送信する** : ユーザーがドキュメントやメールに機密度ラベルを適用、変更、または削除したときに、Office は M365 監査バックエンドに監査データを送信し管理者の目に入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="40624-416">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="40624-417">これは、管理者のためのサイレント機能 (UI なし) です。</span><span class="sxs-lookup"><span data-stu-id="40624-417">This is a silent functionality (no UI) for administrator benefit.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-420">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-420">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-421">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-421">Excel</span></span>

- <span data-ttu-id="40624-422">ピボット テーブルに書式設定スタイルを適用するときのパフォーマンスが向上しました。</span><span class="sxs-lookup"><span data-stu-id="40624-422">Made a performance improvement when applying formatting styles to pivot tables.</span></span>


### <a name="outlook"></a><span data-ttu-id="40624-423">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-423">Outlook</span></span>

- <span data-ttu-id="40624-424">ユーザーが検索対象のカテゴリを複数選ぶことができなかった原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="40624-424">We fixed and issue that caused users to be unable to select more than one category to search.</span></span>


- <span data-ttu-id="40624-425">イベントが別の予定からコピーされたときに、一部の予定表アイテムの開始時刻が予期せず変更される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-425">We fixed an issue that caused the start time of some calendar items to change unexpectedly when the event is copied from another appointment.</span></span>


### <a name="project"></a><span data-ttu-id="40624-426">Project</span><span class="sxs-lookup"><span data-stu-id="40624-426">Project</span></span>

- <span data-ttu-id="40624-427">更新された情報が保存されているはずのプロジェクトをユーザーが開いた際に、更新された情報が見つからないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-427">We fixed an issue where users open projects which have supposedly been saved with updated information, but find the updates are is missing.</span></span>


### <a name="word"></a><span data-ttu-id="40624-428">Word</span><span class="sxs-lookup"><span data-stu-id="40624-428">Word</span></span>

- <span data-ttu-id="40624-429">コメント カードの下部に入力するときのアニメーションを修正します。</span><span class="sxs-lookup"><span data-stu-id="40624-429">Fix animation when typing on the bottom of a comment card.</span></span>


- <span data-ttu-id="40624-430">文書を隠し文字で PDF に保存する際に、Word が固まる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-430">We fixed an issue where Word hangs when saving document to PDF with hidden text.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2101-december-11"></a><span data-ttu-id="40624-432">バージョン 2101: 12 月 11 日</span><span class="sxs-lookup"><span data-stu-id="40624-432">Version 2101: December 11</span></span>
<span data-ttu-id="40624-433">*バージョン 2101 (ビルド 13604.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-433">*Version 2101 (Build 13604.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-435">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-435">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-436">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-436">Outlook</span></span>

- <span data-ttu-id="40624-437">**クラウドでの Outlook の設定** [自動応答]、[優先受信トレイ]、[プライバシー] などの Outlook for Windows の設定を選択し、任意の PC でアクセスできるようにします。</span><span class="sxs-lookup"><span data-stu-id="40624-437">**Your Outlook settings in the cloud:** Choose your Outlook for Windows settings like Automatic Replies, Focused Inbox, and Privacy, and get to them on any PC.</span></span>

### <a name="word"></a><span data-ttu-id="40624-438">Word</span><span class="sxs-lookup"><span data-stu-id="40624-438">Word</span></span>

- <span data-ttu-id="40624-439">**最新のコメントによる共同作業の向上:** オブジェクトにコメントを追加したり、同僚に @mention したり、コメント スレッドを解決して共同作業を効率化できます。</span><span class="sxs-lookup"><span data-stu-id="40624-439">**Better collaboration with modern comments:** Add comments to objects, @mention colleagues, and resolve comment threads for a better collaboration experience.</span></span> [<span data-ttu-id="40624-440">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-440">Learn more</span></span>](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)<br /><span data-ttu-id="40624-441">[ブログの投稿](https://insider.office.com/ja-JP/blog/modern-commenting-in-word)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="40624-441">See details in [blog post](https://insider.office.com/ja-JP/blog/modern-commenting-in-word)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-444">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-444">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-445">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-445">Excel</span></span>

- <span data-ttu-id="40624-446">Excel によってファイルの新しいバージョンが使用可能であることを示すメッセージバーが誤って表示され、ブックのコピーに変更内容を保存するか、変更内容を破棄するように強制する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-446">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="40624-447">Selection.Parent.Copy コールの後に区切り文字の切り替えに関連する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-447">Fixed an issue with switching separators after a Selection.Parent.Copy call.</span></span>


### <a name="outlook"></a><span data-ttu-id="40624-448">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-448">Outlook</span></span>

- <span data-ttu-id="40624-449">送信時にプレーン テキストの S/MIME メッセージが正しく表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="40624-449">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="40624-450">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-450">PowerPoint</span></span>

- <span data-ttu-id="40624-451">この変更により、スライドショーでバックグラウンドビデオ再生がループする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-451">This change addresses an issue with looping background videos playback in Slide Show.</span></span>


- <span data-ttu-id="40624-452">QAT で [フォントサイズ] コマンドが追加されたのに、更新すると最近定義されたフォント サイズにオート コンプリートするという問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-452">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


### <a name="word"></a><span data-ttu-id="40624-453">Word</span><span class="sxs-lookup"><span data-stu-id="40624-453">Word</span></span>

- <span data-ttu-id="40624-454">編集不可とマークされているコンテンツ コントロールでの最新のコメントの削除に関する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-454">We fixed an issue around deleting modern comments in a content control that is marked as not editable.</span></span>



[//]: # ( BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-december-04"></a><span data-ttu-id="40624-456">バージョン 2012: 12 月 4 日</span><span class="sxs-lookup"><span data-stu-id="40624-456">Version 2012: December 04</span></span>
<span data-ttu-id="40624-457">*バージョン 2012 (ビルド 13530.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-457">*Version 2012 (Build 13530.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-459">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-459">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-460">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-460">Outlook</span></span>

- <span data-ttu-id="40624-461">**連続する会議の合間に時間を組み込む:** 既定で 5 分から 10 分遅く会議を開始するように設定することで、出席者に休憩時間や場所の移動時間を与えることができます。</span><span class="sxs-lookup"><span data-stu-id="40624-461">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default.</span></span> [<span data-ttu-id="40624-462">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-462">Learn more</span></span>](https://support.office.com/article/be84396a-0903-4e25-b31c-1c99ce0dacf2)

### <a name="visio"></a><span data-ttu-id="40624-463">Visio</span><span class="sxs-lookup"><span data-stu-id="40624-463">Visio</span></span>

- <span data-ttu-id="40624-464">**新しい Azure ステンシルと図形:** 最新の Azure 図を作成するために、多くのステンシルを追加しました。</span><span class="sxs-lookup"><span data-stu-id="40624-464">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="40624-465">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-465">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-468">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-468">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-469">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-469">Excel</span></span>

- <span data-ttu-id="40624-470">上書きモードでの編集時に、IME を使用する必要がある言語での編集がうまくいかない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-470">Fixed an issue where editing in languages that require use of IME would behave poorly when editing in overwrite mode.</span></span>


- <span data-ttu-id="40624-471">自動保存が無効になっている場合に、通知のヘルプ記事へのハイパーリンクが破損していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-471">Fixed a broken hyperlink to a help article in an alert in case Autosave becomes disabled.</span></span>


- <span data-ttu-id="40624-472">数式ビューでデータをコピーして貼り付けると、Excel が予期せず終了する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-472">Fixed an issue where Excel would close unexpectedly when copying and pasting data in formula view.</span></span>


### <a name="outlook"></a><span data-ttu-id="40624-473">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-473">Outlook</span></span>

- <span data-ttu-id="40624-474">下書きに保存したときに SmartLinks の書式設定が失われるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-474">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


### <a name="project"></a><span data-ttu-id="40624-475">Project</span><span class="sxs-lookup"><span data-stu-id="40624-475">Project</span></span>

- <span data-ttu-id="40624-476">沢山のリソースが付いたプロジェクトを開くのに、長い時間かかっているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-476">Fixed an issue where opening a project with a lot of resources was taking a long time.</span></span>


- <span data-ttu-id="40624-477">ロードの特定の部分でプロジェクト ファイルに問題がある場合に、特定のプロジェクトを開くことができるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-477">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="word"></a><span data-ttu-id="40624-478">Word</span><span class="sxs-lookup"><span data-stu-id="40624-478">Word</span></span>

- <span data-ttu-id="40624-479">リッチ テキストとして貼り付けるより、通常のテキストとして貼り付けることが推奨されます。</span><span class="sxs-lookup"><span data-stu-id="40624-479">Paste as plain text is often preferred to pasting as rich text.</span></span> <span data-ttu-id="40624-480">このコンテキスト メニューの修正プログラムでは、テキストとして貼り付けることができます。</span><span class="sxs-lookup"><span data-stu-id="40624-480">This context menu fix allows the user to paste as plain text.</span></span> <span data-ttu-id="40624-481">それ以外の場合、ユーザーはメモ帳などのプレーンテキスト エディターにコピーして、メモ帳から目的のターゲット アプリにコピーする必要があります。</span><span class="sxs-lookup"><span data-stu-id="40624-481">Else the user would have to copy into a plain-text editor like Notepad and then copy from Notepad into the desired target app</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-november-27"></a><span data-ttu-id="40624-483">バージョン 2012: 11 月 27 日</span><span class="sxs-lookup"><span data-stu-id="40624-483">Version 2012: November 27</span></span>
<span data-ttu-id="40624-484">*バージョン 2012 (ビルド 13519.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-484">*Version 2012 (Build 13519.20000)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-486">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-486">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-487">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-487">Excel</span></span>

- <span data-ttu-id="40624-488">これにより、Power Pivot がタブ区切りのテキストファイルを正しくインポートできない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-488">This fixes an issue where Power Pivot wasn't able to correctly import a tab-delimited text file.</span></span>


### <a name="outlook"></a><span data-ttu-id="40624-489">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-489">Outlook</span></span>

- <span data-ttu-id="40624-490">Outlook 以外のアプリケーションから Outlook メールを送信するときに、ユーザーに問題が発生しているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-490">We fixed an issue that was causing users to experience some issues when sending Outlook mail from applications other than Outlook.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="40624-491">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-491">PowerPoint</span></span>

- <span data-ttu-id="40624-492">この変更により、インク分析中のタイムアウトに関連する問題が解決します。</span><span class="sxs-lookup"><span data-stu-id="40624-492">This change addresses an issue related to timeouts experienced during ink analysis.</span></span>


- <span data-ttu-id="40624-493">この変更は、アニメーション GIF ユーザー インターフェイスの作成に関する文法エラーに対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-493">This change addresses a grammatical error in the Create an Animated GIF user interface.</span></span>


- <span data-ttu-id="40624-494">ドキュメントの修復操作の後であっても、一部の破損した PowerPoint ファイルを正常に開くことができないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-494">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="40624-495">Project</span><span class="sxs-lookup"><span data-stu-id="40624-495">Project</span></span>

- <span data-ttu-id="40624-496">タスクに関連付して、割り当てられていない割り当てが複数存在するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-496">Fixed an issue where users may see multiple unassigned assignments associated with a task.</span></span>


- <span data-ttu-id="40624-497">大規模なプロジェクトでは、タスク名の入力に非常に時間がかかることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-497">Fixed an issue where in large projects it can be very slow to enter a task name.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-november-20"></a><span data-ttu-id="40624-499">バージョン 2012: 11 月 20 日</span><span class="sxs-lookup"><span data-stu-id="40624-499">Version 2012: November 20</span></span>
<span data-ttu-id="40624-500">*バージョン 2012 (ビルド 13512.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-500">*Version 2012 (Build 13512.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-502">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-502">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-503">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-503">Outlook</span></span>

- <span data-ttu-id="40624-504">**会議はすべてオンラインで:** 新しい設定により、オンライン会議のスケジュールを簡単に立てれるため、既定ですべての会議をオンラインにできます。</span><span class="sxs-lookup"><span data-stu-id="40624-504">**Every meeting online:** Make it easier to schedule online meetings with a new setting to make all your meetings online by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-505">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-505">PowerPoint</span></span>

- <span data-ttu-id="40624-506">**ビデオ ライブラリ:** アプリ内で利用可能な、質の良い無料のビデオ フッテージのライブラリを使用してドキュメントの質を高めます。</span><span class="sxs-lookup"><span data-stu-id="40624-506">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-509">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-509">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="40624-510">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-510">PowerPoint</span></span>

- <span data-ttu-id="40624-511">共同編集者の詳細情報が有効になった際に、不明だった共同編集者のプレゼンス インジケーターを完全に更新できなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-511">Fixed an issue where the presence indicator for an unknown coauthor does not get completely refreshed, once more information about the coauthor is available.</span></span>


### <a name="word"></a><span data-ttu-id="40624-512">Word</span><span class="sxs-lookup"><span data-stu-id="40624-512">Word</span></span>

- <span data-ttu-id="40624-513">文書を隠し文字で PDF に保存する際に、Word が固まる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-513">We fixed an issue where Word hangs when saving document to PDF with hidden text.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-november-13"></a><span data-ttu-id="40624-515">バージョン 2012: 11 月 13 日</span><span class="sxs-lookup"><span data-stu-id="40624-515">Version 2012: November 13</span></span>
<span data-ttu-id="40624-516">*バージョン 2012 (ビルド 13510.20004)*</span><span class="sxs-lookup"><span data-stu-id="40624-516">*Version 2012 (Build 13510.20004)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-518">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-518">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-519">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-519">Excel</span></span>

- <span data-ttu-id="40624-520">OneDrive のローカル同期フォルダーからファイルを挿入する際に、「オブジェクトの挿入」コマンドにおいて正しいアイコンが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-520">We fixed an issue where the Insert Object command does not show the correct icon when inserting a file from OneDrive local sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="40624-521">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-521">Outlook</span></span>

- <span data-ttu-id="40624-522">タスク進捗レポートの [宛先] フィールドが空白になってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-522">We fixed an issue that caused the To: field to be blank in task status reports.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="40624-523">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-523">PowerPoint</span></span>

- <span data-ttu-id="40624-524">Slide.Shapes.AddMediaObject2 が従来のビデオ形式 (.MPG-1、Mpeg-2) でクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-524">We fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


### <a name="project"></a><span data-ttu-id="40624-525">Project</span><span class="sxs-lookup"><span data-stu-id="40624-525">Project</span></span>

- <span data-ttu-id="40624-526">成果物が関連付けられていた SharePoint サイトが存在しなくなった場合に、成果物の依存関係を削除できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-526">We fixed an issue where you couldn't delete dependencies on the deliverables if the SharePoint site the deliverable was associated with no longer existed.</span></span>


- <span data-ttu-id="40624-527">更新された情報が保存されているはずのプロジェクトをユーザーが開いた際に、更新された情報が見つからないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-527">We fixed an issue where users open projects which have supposedly been saved with updated information, but find the updates are is missing.</span></span>


### <a name="word"></a><span data-ttu-id="40624-528">Word</span><span class="sxs-lookup"><span data-stu-id="40624-528">Word</span></span>

- <span data-ttu-id="40624-529">ズーム中に写真がぼやけてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-529">We fixed an issue related to pictures becoming blurry while zooming.</span></span>


- <span data-ttu-id="40624-530">長いハイパーリンクが一部省略されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-530">We fixed an issue where long hyperlinks were getting truncated.</span></span>



[//]: # (BUGDETAILS コンテンツ エンドを削除しないでください。終了)

## <a name="version-2012-november-06"></a><span data-ttu-id="40624-532">バージョン 2012: 11 月 6 日</span><span class="sxs-lookup"><span data-stu-id="40624-532">Version 2012: November 06</span></span>
<span data-ttu-id="40624-533">*バージョン 2012 (ビルド 13430.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-533">*Version 2012 (Build 13430.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-535">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-535">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="40624-536">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-536">Excel</span></span>

- <span data-ttu-id="40624-537">**複数のシートを同時に再表示する:** 一度に再表示できるのが、1枚のシートだけではなくなりました。一度に複数の非表示シートを表示します。</span><span class="sxs-lookup"><span data-stu-id="40624-537">**Unhide many sheets at the same time:** No need to unhide one sheet at a time anymore -- unhide multiple hidden sheets at once.</span></span> [<span data-ttu-id="40624-538">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-538">Learn more</span></span>](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)

### <a name="outlook"></a><span data-ttu-id="40624-539">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-539">Outlook</span></span>

- <span data-ttu-id="40624-540">**同じ署名、すべてのデバイス:** 署名をクラウドに保存し ます。</span><span class="sxs-lookup"><span data-stu-id="40624-540">**Same signature, all devices:** Your signature is stored in the cloud.</span></span> <span data-ttu-id="40624-541">一度作成して、Outlook を使用するすべての場所で使用します。</span><span class="sxs-lookup"><span data-stu-id="40624-541">Create it once and use it everywhere you use Outlook.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-544">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-544">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-545">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-545">Excel</span></span>

- <span data-ttu-id="40624-546">一部のリボン要素が簡体字中国語でローカライズされていないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-546">We fixed an issue where some Ribbon elements were not localized in Simplified Chinese.</span></span>


- <span data-ttu-id="40624-547">更新時に Excel が予期せず終了する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-547">We fixed an issue where Excel terminated unexpectedly when updating.</span></span>


### <a name="outlook"></a><span data-ttu-id="40624-548">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-548">Outlook</span></span>

- <span data-ttu-id="40624-549">Zip ファイルから開いたメッセージに添付ファイルを追加するときに問題が発生するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-549">We fixed and issue where adding an attachment to a message opened from a zip file would fail.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-october-30"></a><span data-ttu-id="40624-551">バージョン 2011: 10 月 30 日</span><span class="sxs-lookup"><span data-stu-id="40624-551">Version 2011: October 30</span></span>
<span data-ttu-id="40624-552">*バージョン 2011 (ビルド 13426.20004)*</span><span class="sxs-lookup"><span data-stu-id="40624-552">*Version 2011 (Build 13426.20004)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-554">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-554">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="40624-555">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-555">Excel</span></span>

- <span data-ttu-id="40624-556">**改善された条件付き書式ダイアログ**: 条件付き書式ダイアログのサイズが変更可能になり、シングルクリックでルールを複製できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-556">**Improved Conditional Formatting dialogs:** Conditional Formatting dialogs are now resizable, and now you can duplicate the rule with a single click.</span></span> [<span data-ttu-id="40624-557">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-557">Learn more</span></span>](https://support.office.com/article/fed60dfa-1d3f-4e13-9ecb-f1951ff89d7f)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-560">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-560">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="40624-561">Access</span><span class="sxs-lookup"><span data-stu-id="40624-561">Access</span></span>

- <span data-ttu-id="40624-562">Office 以外のアプリケーションから DAO を使用すると、アプリケーションが予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-562">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="excel"></a><span data-ttu-id="40624-563">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-563">Excel</span></span>

- <span data-ttu-id="40624-564">Oracle データベースへの接続を使用する際の Power Pivot の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-564">Fixed a problem with Power Pivot when using a connection to an Oracle database.</span></span>


- <span data-ttu-id="40624-565">MTR 計算およびグループ ポリシー オブジェクトの更新 (リモート グループ ポリシーの更新など) のプロセスがトリガーされたときに Excel が予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-565">We fixed an issue where Excel terminated unexpectedly when the process of MTR calc and Group Policy Object update (e.g. via Remote Group Policy Refresh) was triggered.</span></span>


- <span data-ttu-id="40624-566">この変更により、atomsvc ファイルを読み込もうとすると Excel でエラーが発生するバグが修正されます。</span><span class="sxs-lookup"><span data-stu-id="40624-566">This change fixes a bug, which causes a failure in Excel on attempt to load an atomsvc file.</span></span>


- <span data-ttu-id="40624-567">Excel ブック を Word 文書に挿入すると Word がハングアップするように見える問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-567">We fixed an issue which Word appears to hang when insert Excel workbook into Word document.</span></span>


### <a name="outlook"></a><span data-ttu-id="40624-568">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-568">Outlook</span></span>

- <span data-ttu-id="40624-569">オプションがグレー表示され、メールボックスの所有者が自分のカレンダーの共有権限を管理できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-569">We fixed an issue where a mailbox owner wasn't able to manage Shared permission for their own Calendar as the option was greyed out.</span></span>


- <span data-ttu-id="40624-570">メールテンプレートを .OFT として保存すると、中国語の文字が疑問符に変わる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-570">We fixed an issue where saving email templates as .OFT changed Chinese characters to question marks.</span></span>


- <span data-ttu-id="40624-571">Outlook が制限付きのアクセス許可でメッセージを作成できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-571">We fixed an issue where Outlook was not able to create a message with restricted permission.</span></span>


- <span data-ttu-id="40624-572">添付ファイルを追加または保存するときに Outlook が散発的に機能しなくなる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="40624-572">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="40624-573">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-573">PowerPoint</span></span>

- <span data-ttu-id="40624-574">デザインウィンドウを閉じるときにグリッド線がスライドからずれてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-574">We fixed an issue where grid lines were getting shifted from slides when closing design pane.</span></span>


- <span data-ttu-id="40624-575">選択ウィンドウを開いた状態で画面の記録を停止した後、スライドのスクロールバーが自動的に調整を開始する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-575">We fixed an issue where the scroll bar in the slide starts adjusting itself after stopping screen recording with selection pane opened.</span></span>


### <a name="project"></a><span data-ttu-id="40624-576">Project</span><span class="sxs-lookup"><span data-stu-id="40624-576">Project</span></span>

- <span data-ttu-id="40624-577">プロジェクトを PWA からローカル mpp ファイルに保存すると、ユーザーが実際に変更していないデータに対して ProjectBeforeTaskChangeEvent が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-577">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="40624-578">リソースエンゲージメントが GUID ではなく名前でリソースを検索する問題を修正しました。同じ名前のリソースが複数ある場合に問題が発生していました。</span><span class="sxs-lookup"><span data-stu-id="40624-578">Fixed an issue where resource engagements searched for a resource by name instead of GUID which would cause issues if there were multiple resources with the same name.</span></span>


### <a name="word"></a><span data-ttu-id="40624-579">Word</span><span class="sxs-lookup"><span data-stu-id="40624-579">Word</span></span>

- <span data-ttu-id="40624-580">コメントヒントをクリックしてもズームアウトしてコメントカードが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-580">We fixed an issue where clicking comment hint didn't zoom out to show comment card in view.</span></span>


- <span data-ttu-id="40624-581">列間の線がずれている場合があるレイアウトの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-581">We fixed a layout issue which the line between columns might have shifted.</span></span>


- <span data-ttu-id="40624-582">Excel ブック を Word 文書に挿入すると Word がハングアップするように見える問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-582">We fixed an issue which Word appears to hang when insert Excel workbook into Word document.</span></span>


### <a name="office-suite"></a><span data-ttu-id="40624-583">Office スイート</span><span class="sxs-lookup"><span data-stu-id="40624-583">Office Suite</span></span>

- <span data-ttu-id="40624-584">Office 2007 の "Microsoft アプリケーション エラー報告" 製品が存在する状態で RemoveMSI 機能を使用すると、Office 展開ツールで構成に失敗してしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-584">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>



[//]: # (BUGDETAILS コンテンツ エンドを削除しないでください。終了)

## <a name="version-2011-october-23"></a><span data-ttu-id="40624-586">バージョン 2011: 10 月 23 日</span><span class="sxs-lookup"><span data-stu-id="40624-586">Version 2011: October 23</span></span>
<span data-ttu-id="40624-587">*バージョン 2011 (ビルド 13415.20002)*</span><span class="sxs-lookup"><span data-stu-id="40624-587">*Version 2011 (Build 13415.20002)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-589">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-589">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="40624-590">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-590">PowerPoint</span></span>

- <span data-ttu-id="40624-591">**プレゼンター コーチでプレゼンテーションのリハーサルを行う:** 話す速度、ピッチ、つなぎ語、機微な表現など、聴衆の関心を引きつけておくのに役立つ内容についてフィードバックを受けます。</span><span class="sxs-lookup"><span data-stu-id="40624-591">**Rehearse your presentation with Presenter Coach:** Get feedback on the things that help keep an audience engaged — like pacing, pitch, filler words, sensitive phrases, and more.</span></span> [<span data-ttu-id="40624-592">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-592">Learn more</span></span>](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-595">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-595">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="40624-596">Access</span><span class="sxs-lookup"><span data-stu-id="40624-596">Access</span></span>

- <span data-ttu-id="40624-597">同期済みの OneDrive フォルダーからクエリをエクスポートしようとしたときに、一部のユーザーに "システム リソースの超過" というエラーが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-597">We fixed an issue where some users were seeing the "system resource exceeded" error when they tried to export a query from their synced OneDrive folder.</span></span>

- <span data-ttu-id="40624-598">フォーム ウィンドウ間で別のフォームに切り替える場合の「自動」切り替えの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-598">We fixed an issue where 'auto'-switching between form windows was switching to another form.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-599">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-599">Outlook</span></span>

- <span data-ttu-id="40624-600">会議の場所からコピーした URL をブラウザーなどの別の場所に貼り付けると、URL の末尾にセミコロンが含まれる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-600">We fixed an issue when pasting a URL copied from meeting location to somewhere else (such as a browser), the URL contains a semicolon at the end.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-601">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-601">PowerPoint</span></span>

- <span data-ttu-id="40624-602">スライドショーを 2 台目のモニターに複製する場合、そのスライドショーが他のウィンドウの背面で非表示になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-602">We fixed an issue when duplicating slideshow to secondary monitor, the slideshow may hide behind other window.</span></span>

### <a name="project"></a><span data-ttu-id="40624-603">Project</span><span class="sxs-lookup"><span data-stu-id="40624-603">Project</span></span>

- <span data-ttu-id="40624-604">リソースの配分状況が特定の方法で指定されている場合に、Project が予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-604">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>

### <a name="word"></a><span data-ttu-id="40624-605">Word</span><span class="sxs-lookup"><span data-stu-id="40624-605">Word</span></span>

- <span data-ttu-id="40624-606">Word 文書を開くと、エラー ダイアログが表示されることがある変更履歴の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-606">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>

- <span data-ttu-id="40624-607">機密度ラベルに透かしが適用される場合がある印刷の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-607">We fixed a print issue when sensitivity label with watermarks are applied.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-october-16"></a><span data-ttu-id="40624-609">バージョン 2011: 10 月 16 日</span><span class="sxs-lookup"><span data-stu-id="40624-609">Version 2011: October 16</span></span>
<span data-ttu-id="40624-610">*バージョン 2011 (ビルド 13408.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-610">*Version 2011 (Build 13408.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-612">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-612">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="40624-613">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-613">Excel</span></span>

- <span data-ttu-id="40624-614">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-614">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="40624-615">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-615">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a><span data-ttu-id="40624-616">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-616">Outlook</span></span>

- <span data-ttu-id="40624-617">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-617">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="40624-618">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-618">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a><span data-ttu-id="40624-619">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-619">PowerPoint</span></span>

- <span data-ttu-id="40624-620">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-620">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="40624-621">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-621">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="word"></a><span data-ttu-id="40624-622">Word</span><span class="sxs-lookup"><span data-stu-id="40624-622">Word</span></span>

- <span data-ttu-id="40624-623">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-623">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="40624-624">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-624">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-627">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-627">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-628">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-628">Outlook</span></span>

- <span data-ttu-id="40624-629">ユーザーが基本認証で Microsoft 365 グループの予定表の予定を削除できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-629">We fixed an issue where users were unable to delete appointments in Calendar of Microsoft 365 Groups in Basic Auth.</span></span>


- <span data-ttu-id="40624-630">ニックネーム キャッシュの読み込み中に Outlook の起動に失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-630">We fixed an issue where starting Outlook failed while loading nickname cache.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="40624-631">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-631">PowerPoint</span></span>

- <span data-ttu-id="40624-632">画像の横のコンテンツ プレースホルダー アイコンにツールヒントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-632">We fixed an issue where in content placeholder icon next to Pictures didn't have a tooltip.</span></span>


- <span data-ttu-id="40624-633">pptsx ファイルで表示されるスライド ショーの保護されたビューで、IRM で保護されたドキュメントの画面キャプチャが許可される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-633">We have fixed an issue where Protected view of slide show, shown by pptsx file, allows screen capture of IRM protected document.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-october-09"></a><span data-ttu-id="40624-635">バージョン 2011: 10 月 09 日</span><span class="sxs-lookup"><span data-stu-id="40624-635">Version 2011: October 09</span></span>
<span data-ttu-id="40624-636">*バージョン 2011 (ビルド 13406.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-636">*Version 2011 (Build 13406.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-638">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-638">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="40624-639">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-639">Excel</span></span>

- <span data-ttu-id="40624-640">**クエリから Powe rPlatform データフローを作成する**: 新しい Powe rPlatform データフローの作成に使用できる Power Query テンプレートにクエリをエクスポートできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-640">**Create Power Platform dataflows from queries:** You can now export your queries into Power Query templates that can be used to create new Power Platform dataflows</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-641">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-641">PowerPoint</span></span>

- <span data-ttu-id="40624-642">**アニメーション GIF を範囲内でエクスポートする**: アニメーション GIF にエクスポートするときにスライドの範囲を選択します</span><span class="sxs-lookup"><span data-stu-id="40624-642">**Export animated GIF in a range:** Select a range of slides when exporting to animated GIF</span></span>

- <span data-ttu-id="40624-643">**透過背景の GIF を作成する**: アニメーション GIF にエクスポートする場合、新しいオプションを使用して背景を透明にすることができます。</span><span class="sxs-lookup"><span data-stu-id="40624-643">**Create GIFs with Transparent Backgrounds:** When exporting to an Animated GIF, a new option will allow you to make the background transparent.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-646">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-646">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-647">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-647">Excel</span></span>

- <span data-ttu-id="40624-648">COM アドインを有効にして SaveAs 操作を行った後、ファイル名が変更されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-648">We fixed an issue where  Filename was not changing after a SaveAs operation with COM add-ins enabled.</span></span>


- <span data-ttu-id="40624-649">Excel データモデルに不適切なメジャー定義がある場合に、自動保存が誤った、または誤解を招くエラーメッセージを表示して失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-649">We fixed an issue when Auto-Save fails with incorrect/misleading error message when there's a bad measure definition in the Excel data model.</span></span>


- <span data-ttu-id="40624-650">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-650">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


### <a name="outlook"></a><span data-ttu-id="40624-651">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-651">Outlook</span></span>

- <span data-ttu-id="40624-652">画像の添付ファイルをクイック印刷すると、以下のエラーが発生する問題を修正しました。「Windows がこの画像を見つけることができません。</span><span class="sxs-lookup"><span data-stu-id="40624-652">We fixed an issue where quick print for image attachments resulted in error, "Windows can't find this picture.</span></span> <span data-ttu-id="40624-653">場所を確認してから、もう一度お試しください」。</span><span class="sxs-lookup"><span data-stu-id="40624-653">Check the location, and then try again".</span></span>


- <span data-ttu-id="40624-654">オンラインで作業するように手動で選択するまで Outlook がオフライン状態で開始されるという問題が一部のユーザーに発生していましたが、この問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-654">Fixes an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="40624-655">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-655">PowerPoint</span></span>

- <span data-ttu-id="40624-656">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-656">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


### <a name="project"></a><span data-ttu-id="40624-657">Project</span><span class="sxs-lookup"><span data-stu-id="40624-657">Project</span></span>

- <span data-ttu-id="40624-658">タスクフォームタイプビュー内でラグが変更された場合、ProjectBeforeTaskChagne イベントの NewVal に正しい値がない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-658">Fixed an issue where the NewVal in the ProjectBeforeTaskChagne event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="40624-659">プロジェクトサイトにタスクリストがあり、タスクリストをグループ化すると、タスクリストをすばやく編集できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-659">Fixed an issue where if you have a task list in a project site and group the task list, you will not be able to quick edit the task list.</span></span>


- <span data-ttu-id="40624-660">CSOM を介してエンタープライズリソースを更新すると、リソースの最大単位数が失われることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-660">Fixed an issue where if you update an enterprise resource via CSOM, resource max units may be lost.</span></span>


### <a name="word"></a><span data-ttu-id="40624-661">Word</span><span class="sxs-lookup"><span data-stu-id="40624-661">Word</span></span>

- <span data-ttu-id="40624-662">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-662">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


### <a name="office-suite"></a><span data-ttu-id="40624-663">Office スイート</span><span class="sxs-lookup"><span data-stu-id="40624-663">Office Suite</span></span>

- <span data-ttu-id="40624-664">SSO API インタラクティブ サインインがエラー コードを返す問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-664">We fixed an issue where SSO API interactive Sign-In was returning an error code.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-october-02"></a><span data-ttu-id="40624-666">バージョン 2010: 10 月 2 日</span><span class="sxs-lookup"><span data-stu-id="40624-666">Version 2010: October 02</span></span>
<span data-ttu-id="40624-667">*バージョン 2010 (ビルド 13328.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-667">*Version 2010 (Build 13328.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-669">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-669">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="40624-670">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-670">Excel</span></span>

- <span data-ttu-id="40624-671">**[詳細] ダイアログ ボックスを使用してデータ型を作成する:** [詳細] ダイアログ ボックスでは、作成するデータ型を組み合わせる列を手動で選択できます。</span><span class="sxs-lookup"><span data-stu-id="40624-671">**Use the Advanced Dialog to Create Data Types:** The Advanced Dialog allows you to manually select the columns which combine the Data Type you are creating.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-674">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-674">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="40624-675">OneNote</span><span class="sxs-lookup"><span data-stu-id="40624-675">OneNote</span></span>

- <span data-ttu-id="40624-676">ユーザーが OutSpace で [ファイル]、[情報] に移動してテキスト ボックスからノートブックの URL を選択してコピーできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-676">We fixed an issue where a user was unable to select and copy notebook URL from textbox in OutSpace File > Info.</span></span>


### <a name="outlook"></a><span data-ttu-id="40624-677">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-677">Outlook</span></span>

- <span data-ttu-id="40624-678">件名が空白の場合、自動的に生成されたメールの本文が空で送信される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-678">Addresses an issue that caused automatically generated emails to be sent with a blank body when the subject is blank.</span></span>


- <span data-ttu-id="40624-679">間違ったフォルダー GUID がフォルダーにキャッシュされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-679">We fixed an issue where the wrong folder guid is cached for folders.</span></span>


- <span data-ttu-id="40624-680">ユーザーが、表示名を持つ受信者フィールドにメールアドレスをコピーアンドペーストしたとき、メールアドレスが正常に解析されず、無効なメールアドレスに関する警告が表示される場合がありました。</span><span class="sxs-lookup"><span data-stu-id="40624-680">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="40624-681">この問題は修正され、名前とメールアドレスは正しく解析され、警告は表示されなくなりました。</span><span class="sxs-lookup"><span data-stu-id="40624-681">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


- <span data-ttu-id="40624-682">オンライン共有フォルダーが親フォルダー名を返さない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-682">We fixed an issue where online shared folders did not return parent folder name.</span></span> <span data-ttu-id="40624-683">失敗する代わりに、プライマリ アカウントに誤って送信された空のパスを返しました。</span><span class="sxs-lookup"><span data-stu-id="40624-683">Intsead of failing, it returned an empty path which incorrectly went to the primary account.</span></span>


- <span data-ttu-id="40624-684">読み取り専のプレビュー ウィンドウから下書きを再開した後、トラックの変更がオンになる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-684">We fixed an issue where track changes turned on after reopening draft from read-only preview pane.</span></span>


- <span data-ttu-id="40624-685">[名前を付けて保存] オプションが従来の添付ファイルで使用できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-685">We fixed an issue where the Save As option was not available for classic attachments.</span></span>


- <span data-ttu-id="40624-686">ポリシーを上書きするときに正当化テキストをカスタマイズする方法をユーザーに提供する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-686">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="40624-687">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-687">PowerPoint</span></span>

- <span data-ttu-id="40624-688">PDF へのエクスポート中に PowerPoint が長方形の箇条書きをエクスポートしなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-688">We fixed an issue where PowerPoint was not exporting rectangle bullet points while exporting to PDF.</span></span>


- <span data-ttu-id="40624-689">最後のスライドを表示していて、[セッションの終了] を押した後、概要が表示される前に次のスライドにスワイプすると、[セッションの終了] ダイアログ ボックスが概要ページにも表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-689">We fixed an issue that If you are on the last slide and if you swipe to the next slide after pressing 'End Session' and before the summary shows up, the End-Session dialog is visible on the summary page as well.</span></span>


### <a name="project"></a><span data-ttu-id="40624-690">Project</span><span class="sxs-lookup"><span data-stu-id="40624-690">Project</span></span>

- <span data-ttu-id="40624-691">リソース配分状況ビューまたはシート ビューにグループ化を適用してから列を挿入すると、Project がクラッシュする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-691">Fixed an issue where Project may crash if you apply a group by to the Resource Usage or Sheet view and then insert a column.</span></span>


- <span data-ttu-id="40624-692">数式を使用してカスタム フィールドを作成し、取得した値を使用している場合、表示の切り替えやプロジェクト/タスクの詳細を開く際にパフォーマンスの遅延が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-692">Fixed an issue where if you have custom fields with formulas and are using earned value, you may notice performance delays switching views and opening project/task details.</span></span>


- <span data-ttu-id="40624-693">同じプロジェクトを複数回追加しようとして AttachToSources が false に設定されている場合、ConsolidateProjects VBA メソッドがファイルすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-693">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="40624-694">イベント コードの実行中に、[タスク フォーム] ビューから変更を加えようとするときに、[OK] ボタンをクリックしても変更が反映されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-694">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-september-25"></a><span data-ttu-id="40624-696">バージョン 2010: 9 月 25 日</span><span class="sxs-lookup"><span data-stu-id="40624-696">Version 2010: September 25</span></span>
<span data-ttu-id="40624-697">*バージョン 2010 (ビルド 13318.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-697">*Version 2010 (Build 13318.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-699">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-699">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="40624-700">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-700">Excel</span></span>

- <span data-ttu-id="40624-701">**Power Query を使用してデータ型を作成する: Power Query を使用してあらゆるデータ ソースから豊富なデータ型を作成します**</span><span class="sxs-lookup"><span data-stu-id="40624-701">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-702">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-702">Outlook</span></span>

- <span data-ttu-id="40624-703">**タスクのユーザー エクスペリエンスの更新:** タスク アイテムの視覚的な更新</span><span class="sxs-lookup"><span data-stu-id="40624-703">**User Experience Updates for Tasks:** A visual refresh of task items</span></span>

- <span data-ttu-id="40624-704">**メッセージの作成にかかる時間を節約:** Outlook は、メッセージをすばやく作成するのに役立つ提案を作成することを示します。</span><span class="sxs-lookup"><span data-stu-id="40624-704">**Save time while composing messages:** Outlook shows you writing suggestions that help you compose messages quickly.</span></span> <span data-ttu-id="40624-705">提案を受け入れるには、Tab キーを使用するだけです。</span><span class="sxs-lookup"><span data-stu-id="40624-705">To accept the suggestion, just use the Tab key.</span></span>

### <a name="word"></a><span data-ttu-id="40624-706">Word</span><span class="sxs-lookup"><span data-stu-id="40624-706">Word</span></span>

- <span data-ttu-id="40624-707">**Microsoft エディター ウィンドウにデスクトップ用の Word の更新が表示される:** デスクトップ クライアント用の Word エディター ウィンドウの現在のエクスペリエンスをアップグレードしました。</span><span class="sxs-lookup"><span data-stu-id="40624-707">**Microsoft Editor pane gets an update in Word for desktop:** We have upgraded the current experience with the Editor pane in Word for desktop clients.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-710">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-710">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="40624-711">Access</span><span class="sxs-lookup"><span data-stu-id="40624-711">Access</span></span>

- <span data-ttu-id="40624-712">スクロール中に保存されたクエリ/リレーションシップ ウィンドウを読み込むときに、スクロールバーの位置が正しく設定されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-712">We fixed an issue where scrollbar position was not set correctly when loading query/relationship window saved while scrolled.</span></span>


- <span data-ttu-id="40624-713">[テーブルを追加する] 作業ウィンドウに「&」を含む名前が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-713">We fixed an issue where Add Table Task Pane was not displaying names containing '&' correctly.</span></span>


### <a name="excel"></a><span data-ttu-id="40624-714">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-714">Excel</span></span>

- <span data-ttu-id="40624-715">マルチレベル カテゴリの手動間隔がグラフで機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-715">We fixed an issue where multi-level category manual interval was not working in charts.</span></span>


- <span data-ttu-id="40624-716">OLAP ピボットテーブルを更新するときにハングする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-716">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="40624-717">データ検証に使用されるテーブルに追加しても、ブック内のすべてのシートのオプションが更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-717">We fixed an issue where adding to a table used for Data Validation did not update options for all sheets in the workbook.</span></span>


### <a name="onenote"></a><span data-ttu-id="40624-718">OneNote</span><span class="sxs-lookup"><span data-stu-id="40624-718">OneNote</span></span>

- <span data-ttu-id="40624-719">OneNote がカスタム テーマのキャンバスのハイ コントラスト カラーを尊重しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-719">We fixed an issue where OneNote didn't honor High Contrast colors in the canvas for custom themes.</span></span>


- <span data-ttu-id="40624-720">ノートブックのカラー セレクターで緑色にカーソルを合わせると、ポップアップに「赤チョーク」と表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-720">We fixed an issue when you hover over green color in notebook color selector, the pop up reads "red chalk".</span></span>


### <a name="powerpoint"></a><span data-ttu-id="40624-721">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-721">PowerPoint</span></span>

- <span data-ttu-id="40624-722">ユーザーがソース パスをローカルの OneDrive フォルダーに変更すると、リンクされた Excel グラフが誤って Excel シートに変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-722">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


### <a name="word"></a><span data-ttu-id="40624-723">Word</span><span class="sxs-lookup"><span data-stu-id="40624-723">Word</span></span>

- <span data-ttu-id="40624-724">ワークフロー対応ファイルへのリンクが期待どおりに開かない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-724">We fixed an issue where links to workflow enabled files were not opening as expected.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-september-18"></a><span data-ttu-id="40624-726">バージョン 2010: 9 月 18 日</span><span class="sxs-lookup"><span data-stu-id="40624-726">Version 2010: September 18</span></span>
<span data-ttu-id="40624-727">*バージョン 2010 (ビルド 13312.20006)*</span><span class="sxs-lookup"><span data-stu-id="40624-727">*Version 2010 (Build 13312.20006)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-729">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-729">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-730">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-730">Outlook</span></span>

- <span data-ttu-id="40624-731">**エディターによるメッセージの校正:** Outlook 64 ビットのユーザーのメールで、文法や他のスタイル修正候補が提供されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-731">**Proofread your messages with Editor:** You can now get grammar and other style suggestions in your emails for Outlook 64-bit users.</span></span> <span data-ttu-id="40624-732">下線が引かれた単語には、文章を洗練させるための修正候補がエディターから提示されます。</span><span class="sxs-lookup"><span data-stu-id="40624-732">Look for underlined words to see Editor’s suggestions to refine your writing.</span></span>

- <span data-ttu-id="40624-733">**組み込みの翻訳機能を使用して、言語の壁を取り除く:** 翻訳用のアドインは必要なくなりました。</span><span class="sxs-lookup"><span data-stu-id="40624-733">**Break the language barrier with a built-in translator:** Add-ins for translation aren't required anymore!</span></span> <span data-ttu-id="40624-734">メッセージを右クリックすると、特定の単語、語句、またはメッセージ全体を翻訳できます。</span><span class="sxs-lookup"><span data-stu-id="40624-734">In a message, right-click to translate specific words, phrases, or the whole message.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-737">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-737">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-738">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-738">Excel</span></span>

- <span data-ttu-id="40624-739">VBA を使用した、シリーズの最大値、中間値、最小値の色の設定が機能しないという 2D マップ グラフの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-739">Fixed an issue with 2D Map Charts where using VBA to set the colors for the max, mid, and min values for a series was not working.</span></span>


- <span data-ttu-id="40624-740">Office の言語がスペイン語に設定されているときに、データ検証リストにすべてのアイテムが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-740">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="40624-741">「Excel で 1 つまたは複数の数式を計算しようとする際にリソース不足になりました」というエラーが生じる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-741">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="40624-742">数式バーに数式を入力したときに、ChartSheet がクラッシュする場合があるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-742">Fixed an issue where ChartSheet crashed in some cases when a formula is entered through formula bar.</span></span>


### <a name="outlook"></a><span data-ttu-id="40624-743">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-743">Outlook</span></span>

- <span data-ttu-id="40624-744">ユーザーが、表示名を持つ受信者フィールドにメールアドレスをコピーアンドペーストしたとき、メールアドレスが正常に解析されず、無効なメールアドレスに関する警告が表示される場合がありました。</span><span class="sxs-lookup"><span data-stu-id="40624-744">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="40624-745">この問題は修正され、名前とメールアドレスは正しく解析され、警告は表示されなくなりました。</span><span class="sxs-lookup"><span data-stu-id="40624-745">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


### <a name="word"></a><span data-ttu-id="40624-746">Word</span><span class="sxs-lookup"><span data-stu-id="40624-746">Word</span></span>

- <span data-ttu-id="40624-747">変更履歴 (挿入/削除) をユーザーがタップすると、コメントがポップアップ表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-747">Fixed an issue where a user tapping on a tracked change (insertion/deletion) would bring up a comment pop-out.</span></span>


- <span data-ttu-id="40624-748">Word でコメントの吹き出しを削除するときの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-748">We fixed an issue with deleting comment callouts in Word.</span></span>


- <span data-ttu-id="40624-749">Outlook でメッセージが [転送不可] に設定される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-749">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="40624-750">引用と数式を含む Word 文書を保存するときの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-750">We fixed an issue with saving Word document that contains citation and equation.</span></span>



[//]: # (BUGDETAILS を削除しないでください 終了)

## <a name="version-2010-september-11"></a><span data-ttu-id="40624-752">バージョン 2010: 9 月 11 日</span><span class="sxs-lookup"><span data-stu-id="40624-752">Version 2010: September 11</span></span>
<span data-ttu-id="40624-753">*バージョン 2010 (ビルド 13304.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-753">*Version 2010 (Build 13304.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-755">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-755">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="40624-756">Access</span><span class="sxs-lookup"><span data-stu-id="40624-756">Access</span></span>

- <span data-ttu-id="40624-757">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="40624-757">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="40624-758">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="40624-758">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="excel"></a><span data-ttu-id="40624-759">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-759">Excel</span></span>

- <span data-ttu-id="40624-760">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="40624-760">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="40624-761">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="40624-761">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="onenote"></a><span data-ttu-id="40624-762">OneNote</span><span class="sxs-lookup"><span data-stu-id="40624-762">OneNote</span></span>

- <span data-ttu-id="40624-763">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="40624-763">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="40624-764">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="40624-764">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-765">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-765">Outlook</span></span>

- <span data-ttu-id="40624-766">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="40624-766">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="40624-767">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="40624-767">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-768">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-768">PowerPoint</span></span>

- <span data-ttu-id="40624-769">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="40624-769">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="40624-770">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="40624-770">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="project"></a><span data-ttu-id="40624-771">Project</span><span class="sxs-lookup"><span data-stu-id="40624-771">Project</span></span>

- <span data-ttu-id="40624-772">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="40624-772">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="40624-773">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="40624-773">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="publisher"></a><span data-ttu-id="40624-774">Publisher</span><span class="sxs-lookup"><span data-stu-id="40624-774">Publisher</span></span>

- <span data-ttu-id="40624-775">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="40624-775">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="40624-776">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="40624-776">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="visio"></a><span data-ttu-id="40624-777">Visio</span><span class="sxs-lookup"><span data-stu-id="40624-777">Visio</span></span>

- <span data-ttu-id="40624-778">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="40624-778">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="40624-779">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="40624-779">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

### <a name="word"></a><span data-ttu-id="40624-780">Word</span><span class="sxs-lookup"><span data-stu-id="40624-780">Word</span></span>

- <span data-ttu-id="40624-781">**Office で Windows 10 のダーク モード設定が反映されるようになりました:** Windows 10 でダーク モードで使用している場合、</span><span class="sxs-lookup"><span data-stu-id="40624-781">**Office can follow your Windows 10 Dark Mode setting:** Using Windows 10 in Dark Mode?</span></span> <span data-ttu-id="40624-782">Office でテーマが自動的に切り替えられて、Windows のテーマとマッチするようになりました。マッチさせるには、Office テーマとして [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="40624-782">Office can now switch themes to match automatically - just choose "Use system setting" as your Office Theme.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-785">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-785">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-786">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-786">Excel</span></span>

- <span data-ttu-id="40624-787">[改ページ プレビュー] が有効になっているときに、大量のデータが含まれているワークシート間を切り替える際に顕著な遅延が発生する場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-787">Fixed an issue where there could be a noticeable delay when switching between worksheets with large amounts of data when 'Page Break Preview' was enabled.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-788">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-788">Outlook</span></span>

- <span data-ttu-id="40624-789">優先受信トレイをオフにして並べ替えを行った後に、メールが非表示になるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-789">We fixed an issue with emails being hidden after turning Focused Inbox off and doing a sort.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-790">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-790">PowerPoint</span></span>

- <span data-ttu-id="40624-791">エディターとスライド ショーで GIF のアニメーションが1 回だけしか再生されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-791">We fixed an issue where GIF's would animate only once in the editor and slide shows.</span></span>

[//]: # (BUGDETAILS を削除しないでください 終了)

## <a name="version-2010-september-04"></a><span data-ttu-id="40624-793">バージョン 2010: 9 月 4 日</span><span class="sxs-lookup"><span data-stu-id="40624-793">Version 2010: September 04</span></span>
<span data-ttu-id="40624-794">*バージョン 2010 (ビルド 13301.20004)*</span><span class="sxs-lookup"><span data-stu-id="40624-794">*Version 2010 (Build 13301.20004)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-796">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-796">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-797">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-797">Outlook</span></span>

- <span data-ttu-id="40624-798">**メールのピン留め:** この機能を使うことで、他のユーザーに返信する必要があるメールを追跡したり、忘れないようにそれらのメールをメッセージ一覧の一番上に固定したりできます。</span><span class="sxs-lookup"><span data-stu-id="40624-798">**Pinning email:** This feature helps users keep track of mails they need to go back to you or have as a reminder by keeping them at the top of the message list.</span></span>

- <span data-ttu-id="40624-799">**ユーザーで検索するときにメールの候補を受信する:** Outlook に検索キーワードを入力すると、関連性が最も高いメールが候補に表示されます。</span><span class="sxs-lookup"><span data-stu-id="40624-799">**Receive email suggestions when searching by person:** As you type your search terms in Outlook, you'll receive the most relevant emails surfaced in the suggestions.</span></span>

- <span data-ttu-id="40624-800">**ユーザーで検索するときにメールの候補を受信する:** Outlook に検索キーワードを入力すると、関連性が最も高いメールが候補に表示されます。</span><span class="sxs-lookup"><span data-stu-id="40624-800">**Receive email suggestions when searching by person:** As you type your search terms in Outlook, you'll receive the most relevant emails surfaced in the suggestions.</span></span>

- <span data-ttu-id="40624-801">**Microsoft エディターが Word と Outlook のデスクトップ クライアント向けにアップグレードされました:** エディターのスペルチェック、文章校正、および詳細なスタイルの修正候補で、新しい、クリックによるレビュー モデルが導入されました。</span><span class="sxs-lookup"><span data-stu-id="40624-801">**Microsoft Editor gets an upgrade for Word and Outlook desktop clients:** We are introducing a new click-to-review model for Editor's spelling ,grammar and advanced style suggestions.</span></span> <span data-ttu-id="40624-802">この変更には、候補をレビューするために表示される専用のカードも含まれています。</span><span class="sxs-lookup"><span data-stu-id="40624-802">This change also includes a new dedicated card surface for reviewing the suggestions.</span></span>

### <a name="word"></a><span data-ttu-id="40624-803">Word</span><span class="sxs-lookup"><span data-stu-id="40624-803">Word</span></span>

- <span data-ttu-id="40624-804">**Microsoft エディターが Word と Outlook のデスクトップ クライアント向けにアップグレードされました:** エディターのスペルチェック、文章校正、および詳細なスタイルの修正候補で、新しい、クリックによるレビュー モデルが導入されました。</span><span class="sxs-lookup"><span data-stu-id="40624-804">**Microsoft Editor gets an upgrade for Word and Outlook desktop clients:** We are introducing a new click-to-review model for Editor's spelling ,grammar and advanced style suggestions.</span></span> <span data-ttu-id="40624-805">この変更には、候補をレビューするために表示される専用のカードも含まれています。</span><span class="sxs-lookup"><span data-stu-id="40624-805">This change also includes a new dedicated card surface for reviewing the suggestions.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-808">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-808">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-809">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-809">Excel</span></span>

- <span data-ttu-id="40624-810">LET 関数が含まれているファイルを開くと、以下の警告が表示される問題が修正されました: "ファイル名.xlsx" のコンテンツに問題が見つかりました。</span><span class="sxs-lookup"><span data-stu-id="40624-810">We fixed an issue where if you opened a file containing the LET function, it would display the alert:  "We found a problem with content in "your file.xlsx".</span></span> <span data-ttu-id="40624-811">できるだけ多くの内容の復元を試みますか?</span><span class="sxs-lookup"><span data-stu-id="40624-811">Do you want us to try to recover as much as we can?</span></span> <span data-ttu-id="40624-812">このブックの発行元が信頼できる場合は、[はい] をクリックしてください。</span><span class="sxs-lookup"><span data-stu-id="40624-812">If you trust the source of this workbook, click Yes".</span></span>
- <span data-ttu-id="40624-813">XLAM アドインの参照と名前付き範囲に関連するクラッシュが修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-813">We fixed a crash related to XLAM add-in references and named ranges.</span></span>
- <span data-ttu-id="40624-814">Analysis Services データベースに既に存在しない値に設定されているために、ユーザーがピボットテーブル フィルターを変更できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-814">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>
- <span data-ttu-id="40624-815">ユーザーが動的配列にカスタム スタイルを適用すると、"配列の一部を変更することはできません" というエラーが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-815">We fixed an issue where if a user applied a custom style to a dynamic array, they would get the error: "You can't change part of an array".</span></span> <span data-ttu-id="40624-816">これは以前に存在していた制約でしたが、現在は削除されています。</span><span class="sxs-lookup"><span data-stu-id="40624-816">This was a legacy restriction that has been removed.</span></span>
- <span data-ttu-id="40624-817">デバイスへの接続が失われると (リモート セッションが接続されたり接続が解除されたり、モニターでの変更があった場合など) Excel の関数バーが完全に描画されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-817">We fixed an issue where the Excel formula bar would not render completely after connection to a device was lost, such as a remote session connect/disconnect or a monitor change.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-818">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-818">Outlook</span></span>

- <span data-ttu-id="40624-819">問題が修正され、グループ ポリシー経由で既定のログ記録オプションを有効または無効にするための柔軟性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="40624-819">We fixed an issue which provides more flexibility in enabling / disabling the default logging options via Group Policy.</span></span>
- <span data-ttu-id="40624-820">アシスタントのアクセス許可があるメールボックスと管理者のアクセス許可があるメールボックスの間でメールの下書きを移動した後も、メール送信者の従来のドメイン名が維持されて表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-820">We fixed an issue where the Legacy Domain Name for an email sender was preserved and displayed after a draft of the email was moved between mailboxes with assistant permissions and manager permissions.</span></span>
- <span data-ttu-id="40624-821">オンラインで作業するように手動で選択するまで Outlook がオフライン状態で開始されるという問題が一部のユーザーに発生していましたが、この問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-821">We fixed an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>
- <span data-ttu-id="40624-822">1 行リボン (SLR) を有効にした後に VBA コード ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") を実行すると実行時エラーが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-822">We fixed an issue where running the VBA code ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") after enabling the Single Line Ribbon (SLR) would result in a runtime error.</span></span>
- <span data-ttu-id="40624-823">高解像度 (1750 x 1920 など) と大きなテキストサイズ (175% など) が同時に使用された場合に、[自動応答] ダイアログの [OK] ボタンと [キャンセル] ボタンが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-823">We fixed an issue where the 'OK' and 'Cancel' buttons on the Automatic Replies dialog would not be visible on a system with a high resolution (such as 1750 x 1920) combined with a large text size (such as 175%).</span></span>
- <span data-ttu-id="40624-824">会議出席依頼を空の連絡先グループから別の連絡先グループに送信するとクラッシュする状態が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-824">We fixed a condition where sending a meeting request from an empty contact group to another contact group would result in a crash.</span></span>
- <span data-ttu-id="40624-825">サイズが非常に大きい特定のメールを開くとクラッシュが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-825">We fixed an issue that caused users to experience a crash when opening certain very large emails.</span></span>
- <span data-ttu-id="40624-826">アドインが常に有効になっていることがグループ ポリシーで要求される場合に、ユーザーがアドインを無効にすることを防ぐためにアドインの監視が使用できなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-826">We fixed an issue where if Group Policy requires an Add-in to be always enabled, then monitoring add-in's becomes unavailable in order to prevent users from disabling the Add-in.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-827">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-827">PowerPoint</span></span>

- <span data-ttu-id="40624-828">ビデオがスライドショーで自動的に再生されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-828">We fixed an issue where videos were not playing automatically in slideshows.</span></span>
- <span data-ttu-id="40624-829">PowerPoint を起動後にスライドを挿入してコメント ウィンドウを開いて閉じると、縮小版ウィンドウ内のスライドが重なって表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-829">We fixed an issue where after booting PowerPoint, inserting a slide and opening and closing the comments pane, the slides in the thumbnail pane displayed as being overlapped.</span></span>

### <a name="project"></a><span data-ttu-id="40624-830">Project</span><span class="sxs-lookup"><span data-stu-id="40624-830">Project</span></span>

- <span data-ttu-id="40624-831">リソースに複数のコスト単価テーブルが含まれている場合、残りのコストが正確に計算されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-831">We fixed an issue where if a resource has multiple cost rate tables, the remaining cost may not be calculated correctly.</span></span>
- <span data-ttu-id="40624-832">SharePoint のタスク リストに接続されているプロジェクトでプロジェクト終了日が更新されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-832">We fixed an issue where the Project finish date wasn't getting updated for projects connected to SharePoint tasks list.</span></span>

### <a name="word"></a><span data-ttu-id="40624-833">Word</span><span class="sxs-lookup"><span data-stu-id="40624-833">Word</span></span>

- <span data-ttu-id="40624-834">ユーザーがコメントをクリックした場合に、コメント カードでコメントのテキストの周囲に枠線が表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-834">We fixed an issue where the Comment card would display a border around the comment text if the user clicked on the comment.</span></span>
- <span data-ttu-id="40624-835">ドキュメントの拡大率が 160% より大きく設定され、コメント ウィンドウが表示されていない場合に、フォーカスがコメント ウィンドウに移動しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-835">We fixed an issue where the focus would not go to the comment pane if the document was zoomed to 160% or more and the comment pane was not visible.</span></span>
- <span data-ttu-id="40624-836">開いている複数のドキュメントの間で切り替えを行うと、あるドキュメントのコメントが、開かれている別のドキュメントに表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-836">We fixed an issue where the comments on one document would be displayed on other open documents after switching between the multiple open documents.</span></span>
- <span data-ttu-id="40624-837">ユーザーがコメントの下書きを作成して、解決済みのコメントが既に含まれている行にアンカーすると、サイドトラックでは解決済みのコメントに対して正しくない順番で下書きが並べ替えられる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-837">We fixed an issue where if a user created a comment draft anchored to a line already containing committed comments, then the draft was arranged in the wrong order relative to the committed comment in the SideTrack.</span></span>
- <span data-ttu-id="40624-838">ドキュメントを HTML 形式に保存するときに、長いリンクが折り返されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-838">We fixed an issue where long links were not being wrapped when saving a document to HTML format.</span></span>
- <span data-ttu-id="40624-839">AutoOpen が AutoExec. より前に実行されるというマクロの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-839">We fixed an issue with macros in which AutoOpen runs before AutoExec.</span></span>

[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2009-august-28"></a><span data-ttu-id="40624-841">バージョン 2009: 8 月 28 日</span><span class="sxs-lookup"><span data-stu-id="40624-841">Version 2009: August 28</span></span>
<span data-ttu-id="40624-842">*バージョン 2009 (ビルド 13219.20004)*</span><span class="sxs-lookup"><span data-stu-id="40624-842">*Version 2009 (Build 13219.20004)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-844">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-844">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-845">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-845">Outlook</span></span>

- <span data-ttu-id="40624-846">1 つ以上のメッセージを選択した場合に、OneNote に "転送不可" ポリシーが適用されているメール コンテンツを送信することができるようになっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="40624-846">Addresses an issue that caused users to be able to send email content that had a "Do Not Forward" policy applied to OneNote when selecting more than one message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-847">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-847">PowerPoint</span></span>

- <span data-ttu-id="40624-848">ビデオを挿入する機能が無効になってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-848">We fixed an issue where the functionality to insert a video was disabled.</span></span>

### <a name="word"></a><span data-ttu-id="40624-849">Word</span><span class="sxs-lookup"><span data-stu-id="40624-849">Word</span></span>

- <span data-ttu-id="40624-850">コメントの選択時に、ヘッダー/フッターを閉じることができないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-850">We fixed an issue where the user could not exit the Header/Footer when selecting a comment.</span></span>
- <span data-ttu-id="40624-851">サイドトラックのスクロールが機能しないため、サイドトラックの境界を超えたコメントのスレッドが表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-851">We fixed an issue that prevented users from seeing comment threads that exceeded the sidetrack boundary because scrolling through the sidetrack was not working.</span></span>
- <span data-ttu-id="40624-852">サイドトラック ウィンドウで解決済みのコメントを検索できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-852">We fixed an issue where searching for resolved comments in the sidetrack pane was not working.</span></span>

### <a name="office-suite"></a><span data-ttu-id="40624-853">Office スイート</span><span class="sxs-lookup"><span data-stu-id="40624-853">Office Suite</span></span>

- <span data-ttu-id="40624-854">Office 2007 の "Microsoft アプリケーション エラー報告" 製品が存在する状態で RemoveMSI 機能を使用すると、Office 展開ツールで構成に失敗してしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-854">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>
- <span data-ttu-id="40624-855">[図の圧縮] ダイアログで、ユーザーが選択した一部の DPI 設定が保持されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-855">We fixed an issue in the Compress Picture dialog where some user-selected DPI settings are not retained.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-august-21"></a><span data-ttu-id="40624-857">バージョン 2009: 8 月 21 日</span><span class="sxs-lookup"><span data-stu-id="40624-857">Version 2009: August 21</span></span>
<span data-ttu-id="40624-858">*バージョン 2009 (ビルド 13212.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-858">*Version 2009 (Build 13212.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-860">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-860">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="40624-861">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-861">Excel</span></span>

- <span data-ttu-id="40624-862">**Excel のアクション ペン:** ペン ツールを使用すると、データを手書きしてすばやく編集できます</span><span class="sxs-lookup"><span data-stu-id="40624-862">**Action Pen in Excel:** Pen Tool to help you handwrite and make quick edits to your data</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-863">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-863">Outlook</span></span>

- <span data-ttu-id="40624-864">**メッセージの所有者として会話を削除する:** この機能を使用すると、メッセージの所有者による会話を削除できます。</span><span class="sxs-lookup"><span data-stu-id="40624-864">**Delete conversation by message owner:** This feature allows you to delete a conversation by message owner.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-867">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-867">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="40624-868">Access</span><span class="sxs-lookup"><span data-stu-id="40624-868">Access</span></span>

- <span data-ttu-id="40624-869">ODBC データベースへの接続がサードパーティ製アプリケーションで機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-869">We fixed an issue where connections to an ODBC database were not working with third party applications.</span></span>

### <a name="excel"></a><span data-ttu-id="40624-870">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-870">Excel</span></span>

- <span data-ttu-id="40624-871">マクロを使用して、範囲の FormulaR1C1 プロパティを設定する問題を修正しました。グラフ シートがアクティブ シートである場合、セル参照が正しくありませんでした。</span><span class="sxs-lookup"><span data-stu-id="40624-871">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>
- <span data-ttu-id="40624-872">手描き入力で Excel が応答しなくなる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-872">We fixed an issue where inking could cause Excel to become unresponsive.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-873">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-873">Outlook</span></span>

- <span data-ttu-id="40624-874">Outlook の IRM (Information Rights Management) を他の Office アプリケーションで無効にすることなく無効にできる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-874">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>

### <a name="word"></a><span data-ttu-id="40624-875">Word</span><span class="sxs-lookup"><span data-stu-id="40624-875">Word</span></span>

- <span data-ttu-id="40624-876">コメントが削除された後に Word がクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-876">We fixed an issue where Word could crash after comments were deleted.</span></span>
- <span data-ttu-id="40624-877">メールで箇条書きが正しく表示されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-877">We fixed an issue where in some cases, bullets are not displaying correctly in email.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-august-14"></a><span data-ttu-id="40624-879">バージョン 2009: 8 月 14 日</span><span class="sxs-lookup"><span data-stu-id="40624-879">Version 2009: August 14</span></span>
<span data-ttu-id="40624-880">*バージョン 2009 (ビルド 13205.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-880">*Version 2009 (Build 13205.20000)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-882">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-882">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-883">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-883">Excel</span></span>

- <span data-ttu-id="40624-884">ユーザーがかっこを含む数式名を入力し、F1 を介してヘルプを呼び出した場合、その数式に固有のヘルプ トピックが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-884">We fixed an issue where if a user typed a formula name including the parenthesis and invoked help via F1, the help topic specific to that formula would not be displayed.</span></span>
- <span data-ttu-id="40624-885">古いバージョンのファイルを復元した後、ボタンに割り当てられたマクロが壊れる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-885">Fixed an issue where macros assigned to buttons were broken after restoring an older version of the file.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-886">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-886">Outlook</span></span>

- <span data-ttu-id="40624-887">この変更により、ユーザーがタブを会議ページからスケジュール アシスタント ページに切り替えた後も会議ページが引き続き表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="40624-887">This change fixes an issue where the Meeting page would continue to be displayed after the user switched tabs from the Meeting page to the Scheduling Assistant page.</span></span>

### <a name="word"></a><span data-ttu-id="40624-888">Word</span><span class="sxs-lookup"><span data-stu-id="40624-888">Word</span></span>

- <span data-ttu-id="40624-889">箇条書きのアイコンが正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-889">We fixed an issue where the bullet picture icon didn't display correctly.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-august-07"></a><span data-ttu-id="40624-891">バージョン 2009: 8 月 7 日</span><span class="sxs-lookup"><span data-stu-id="40624-891">Version 2009: August 07</span></span>
<span data-ttu-id="40624-892">*バージョン 2009 (ビルド 13130.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-892">*Version 2009 (Build 13130.20000)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-894">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-894">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-895">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-895">Outlook</span></span>

- <span data-ttu-id="40624-896">Active Directory の "otherTelephone" および "otherHomePhone" のユーザー アカウント属性が、対応する Outlook LDAP 属性にマッピングされていないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-896">We fixed an issue where the user account attributes in Active Directory for "otherTelephone" and "otherHomePhone" were not mapped to the corresponding Outlook LDAP attributes.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-897">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-897">PowerPoint</span></span>

- <span data-ttu-id="40624-898">特定の条件下でリボンまたはタイトル バーが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-898">We fixed an issue where users were seeing the ribbon/title bar not being displayed under certain conditions.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-july-31"></a><span data-ttu-id="40624-900">バージョン 2008: 7 月 31 日</span><span class="sxs-lookup"><span data-stu-id="40624-900">Version 2008: July 31</span></span>
<span data-ttu-id="40624-901">*バージョン 2008 (ビルド 13127.20002)*</span><span class="sxs-lookup"><span data-stu-id="40624-901">*Version 2008 (Build 13127.20002)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-903">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-903">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="40624-904">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-904">Excel</span></span>

- <span data-ttu-id="40624-905">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="40624-905">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="40624-906">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="40624-906">No conversion required.</span></span><br /><span data-ttu-id="40624-907">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="40624-907">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-908">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-908">Outlook</span></span>

- <span data-ttu-id="40624-909">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="40624-909">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="40624-910">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="40624-910">No conversion required.</span></span><br /><span data-ttu-id="40624-911">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="40624-911">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-912">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-912">PowerPoint</span></span>

- <span data-ttu-id="40624-913">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="40624-913">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="40624-914">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="40624-914">No conversion required.</span></span><br /><span data-ttu-id="40624-915">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="40624-915">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="word"></a><span data-ttu-id="40624-916">Word</span><span class="sxs-lookup"><span data-stu-id="40624-916">Word</span></span>

- <span data-ttu-id="40624-917">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="40624-917">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="40624-918">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="40624-918">No conversion required.</span></span><br /><span data-ttu-id="40624-919">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="40624-919">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-922">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-922">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="40624-923">Access</span><span class="sxs-lookup"><span data-stu-id="40624-923">Access</span></span>

- <span data-ttu-id="40624-924">この修正プログラムでは、特定のクエリを実行しようとすると、"クエリが複雑すぎます" というエラーメッセージが表示される問題に対処しています。</span><span class="sxs-lookup"><span data-stu-id="40624-924">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex.'</span></span>

### <a name="excel"></a><span data-ttu-id="40624-925">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-925">Excel</span></span>

- <span data-ttu-id="40624-926">グラフ系列の順序を変更した場合、系列に並んだチェックボックスが系列に沿って並び替えられない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-926">We fixed an issue where if the order of a chart series was changed, the corresponding checkbox aligned with the series was not reordered along with the series.</span></span>
- <span data-ttu-id="40624-927">放射状グラデーションによる塗りつぶしを適用した画像のコピーが元の画像と一致しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-927">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-928">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-928">Outlook</span></span>

- <span data-ttu-id="40624-929">この修正プログラムでは、ユーザーが返信メッセージの所有者アクセス許可を持っていない場合、[インスペクタ] ウィンドウから権限がデジタル管理されたメッセージに返信するときに、ユーザーが署名を追加できないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-929">This fix addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user did not have Owner permissions on the message being replied to.</span></span>
- <span data-ttu-id="40624-930">この修正プログラムでは、Outlook のMarkdown コンテンツでは改行が正常に表示されない問題に対処しています。</span><span class="sxs-lookup"><span data-stu-id="40624-930">This fix addresses an issue that was causing Outlook to fail to display line breaks properly in markdown content.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-931">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-931">PowerPoint</span></span>

- <span data-ttu-id="40624-932">放射状グラデーションによる塗りつぶしを適用した画像のコピーが元の画像と一致しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-932">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>
- <span data-ttu-id="40624-933">Office ストアへのアクセスが許可されていない場合に、PowerPoint の [フォーム] ボタンでフォームを作成できないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-933">We fixed an issue where the Forms button in PowerPoint did not allow the creation of Forms when access to the Office Store was not permitted.</span></span>

### <a name="project"></a><span data-ttu-id="40624-934">Project</span><span class="sxs-lookup"><span data-stu-id="40624-934">Project</span></span>

- <span data-ttu-id="40624-935">SharePoint のタスクリストで、2番目のタブにあるリボン ボタンが無効になる場合がある問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="40624-935">We fixed an issue where for a SharePoint tasks list, the ribbon buttons on the second tab may be disabled.</span></span>

### <a name="word"></a><span data-ttu-id="40624-936">Word</span><span class="sxs-lookup"><span data-stu-id="40624-936">Word</span></span>

- <span data-ttu-id="40624-937">放射状グラデーションによる塗りつぶしを適用した画像のコピーが元の画像と一致しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-937">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>
- <span data-ttu-id="40624-938">変更を追跡するコメントが追加された場合に、[変更履歴] ウィンドウが予期せず開かれる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-938">We fixed an issue where if a comment was added to track a change, the revisions pane would unexpectedly open.</span></span>
- <span data-ttu-id="40624-939">[挿入]、[リンク] ドロップダウンを通して、ドキュメントへのリンクがコメントボックスに挿入されなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-939">We fixed an issue where links to documents were not being inserted to the comments box via the Insert -> Link dropdown.</span></span>
- <span data-ttu-id="40624-940">ハイパーリンクを含む画像を追加した後に、VBA のハイパーリンク コレクションにあるハイパーリンク数が正しく指定されなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-940">We fixed an issue where the hyperlink count in the VBA hyperlinks collection was not iterating correctly after adding an image containing a hyperlink.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-july-24"></a><span data-ttu-id="40624-942">バージョン 2008: 7 月 24 日</span><span class="sxs-lookup"><span data-stu-id="40624-942">Version 2008: July 24</span></span>
<span data-ttu-id="40624-943">*バージョン 2008 (ビルド 13117.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-943">*Version 2008 (Build 13117.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-945">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-945">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="40624-946">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-946">Excel</span></span>

- <span data-ttu-id="40624-947">**Excel で洗練された Visio 図を作成する:** ワークシートにデータを入力して、フロー チャートまたは組織図を作成します。</span><span class="sxs-lookup"><span data-stu-id="40624-947">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="40624-948">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-948">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-951">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-951">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="40624-952">OneNote</span><span class="sxs-lookup"><span data-stu-id="40624-952">OneNote</span></span>

- <span data-ttu-id="40624-953">アプリケーションウィンドウを小さいサイズに変更すると、検索編集ボックスのプレースホルダーテキストがオーバーフローする問題を修正しました。　</span><span class="sxs-lookup"><span data-stu-id="40624-953">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

### <a name="word"></a><span data-ttu-id="40624-954">Word</span><span class="sxs-lookup"><span data-stu-id="40624-954">Word</span></span>

- <span data-ttu-id="40624-955">アプリケーションウィンドウを小さいサイズに変更すると、検索編集ボックスのプレースホルダーテキストがオーバーフローする問題を修正しました。　</span><span class="sxs-lookup"><span data-stu-id="40624-955">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>
- <span data-ttu-id="40624-956">変更履歴の記録の[特定のユーザー]オプションが無効になっている問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-956">We fixed an issue where the 'Specific People' option for Track Changes was disabled.</span></span>
- <span data-ttu-id="40624-957">HTML ファイルを開くときに、時々切断される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-957">We fixed an occasional hang while opening HTML files.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-july-17"></a><span data-ttu-id="40624-959">バージョン 2008: 7 月 17 日</span><span class="sxs-lookup"><span data-stu-id="40624-959">Version 2008: July 17</span></span>
<span data-ttu-id="40624-960">*バージョン 2008 (ビルド 13115.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-960">*Version 2008 (Build 13115.20000)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-962">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-962">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-963">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-963">Excel</span></span>

- <span data-ttu-id="40624-964">引き出し線が非表示のピボット グラーフが保存されて再度開かれると、引き出し線が表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-964">We fixed an issue where any time a pivot chart with hidden leader lines was saved and reopened, the leader lines would become visible.</span></span>

- <span data-ttu-id="40624-965">ブックの VBA を介して「ForceFullCalculation」が有効になっていると、グラフが常に期待どおりに更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-965">We fixed an issue where charts were not always updated as expected when 'ForceFullCalculation' was enabled via VBA for the workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-966">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-966">Outlook</span></span>

- <span data-ttu-id="40624-967">Outlook で同じメール ドメインから複数のプロファイルを作成することに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-967">We fixed an issue around creating multiple profiles in Outlook from the same email domain.</span></span>
- <span data-ttu-id="40624-968">S/MIME 暗号化メッセージのヘッダーにロック アイコンが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="40624-968">Addresses an issue that caused the lock icon to fail to display in the header of S/MIME encrypted messages.</span></span>
- <span data-ttu-id="40624-969">暗号化されずに送信されたときに添付ファイルが S/MIME メッセージから削除される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="40624-969">Addresses an issue that caused attachments to get stripped from S/MIME messages when sent unencrypted.</span></span>
- <span data-ttu-id="40624-970">送信時にプレーン テキストの S/MIME メッセージが文字化けする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="40624-970">Addresses an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>
- <span data-ttu-id="40624-971">暗号化されていない S/MIME メールを送信すると添付ファイルが破損する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="40624-971">Addresses an issue that caused attachments to become corrupted when sending an S/MIME email unencrypted.</span></span>
- <span data-ttu-id="40624-972">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカル コンピューターに保存できない原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-972">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the 'Save' option on the security dialog.</span></span>
- <span data-ttu-id="40624-973">送信者から名前を付けて保存のアクセス許可が付与されている場合でも、受信者が権利保護されたメッセージを保存できなくなる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-973">Addresses an issue that caused recipients to be unable to save rights protected messages even when the save as permission was granted by the sender.</span></span>
- <span data-ttu-id="40624-974">一部の言語で一部の高度な検索のオプションのラベルが切り捨てられる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-974">Addresses an issue that caused the labels for some Advanced Search options to be truncated in some languages.</span></span>

### <a name="project"></a><span data-ttu-id="40624-975">Project</span><span class="sxs-lookup"><span data-stu-id="40624-975">Project</span></span>

- <span data-ttu-id="40624-976">[タスク ボード] ビューに一覧表示されているタスクが [リソースの割り当て] ダイアログのタスクと同期していない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-976">We fixed an issue where tasks listed in the Task Board view were not in sync with those in the Assign Resources dialog.</span></span>
- <span data-ttu-id="40624-977">複数の依存関係があるタスクをコピーして貼り付けると、すべての依存関係が正しくコピーされるわけではない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-977">We fixed an issue where if you copied and pasted a task that had multiple dependencies, not all dependencies were copied correctly.</span></span>

### <a name="word"></a><span data-ttu-id="40624-978">Word</span><span class="sxs-lookup"><span data-stu-id="40624-978">Word</span></span>

- <span data-ttu-id="40624-979">フォーカスがコメント テキスト ボックスにあるときに「エディター」コマンドが無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-979">We fixed an issue where the 'Editor' command was disabled when the focus was in a comment text box.</span></span>
- <span data-ttu-id="40624-980">フォーカスがコメント テキスト ボックスにあるときに「変更履歴と​​コメントの表示」コマンドが無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-980">We fixed an issue where the 'Show Markup' command was disabled when the focus was in a comment text box.</span></span>
- <span data-ttu-id="40624-981">ドキュメントを開くとコメントの状態が失われる可能性があるカスタム XML の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-981">We fixed an issue in custom XML where the state of comments may be lost when opening the document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="40624-982">Office スイート</span><span class="sxs-lookup"><span data-stu-id="40624-982">Office Suite</span></span>

- <span data-ttu-id="40624-983">ユーザーがタスクバーから新しいアプリ ウィンドウを開いて新しい空白のドキュメントを作成した後、追加のファイルが作成される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-983">We fixed an issue where after the user opened a new app window from the taskbar and created a new blank document, additional files were created.</span></span>
- <span data-ttu-id="40624-984">ユーザーがドキュメントを編集していて権限を失っていた場合、再認証が必要であることをユーザーに通知しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-984">We fixed an issue where if a user was editing a document but had lost permissions, we were not notifying the user that they had to re-authenticate.</span></span>

[//]: # (バグの詳細コンテンツを削除しないでください。終了)

## <a name="version-2008-july-10"></a><span data-ttu-id="40624-986">バージョン 2008: 7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="40624-986">Version 2008: July 10</span></span>
<span data-ttu-id="40624-987">*バージョン 2008 (ビルド 13102.20002)*</span><span class="sxs-lookup"><span data-stu-id="40624-987">*Version 2008 (Build 13102.20002)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-989">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-989">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-990">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-990">Outlook</span></span>

- <span data-ttu-id="40624-991">[共有フォルダーのダウンロード] がチェックされていない場合、共有の予定表の会議の [返信オプション] に [転送を許可する] オプションが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-991">We fixed an issue where the Allow Forwarding option was missing from the shared calendar meeting "Response Options" if Download shared folder was NOT checked.</span></span>
- <span data-ttu-id="40624-992">ユーザーが適切な印刷権限を持っていても、印刷ボタンが無効な状態で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-992">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

### <a name="project"></a><span data-ttu-id="40624-993">Project</span><span class="sxs-lookup"><span data-stu-id="40624-993">Project</span></span>

- <span data-ttu-id="40624-994">Project から SharePoint ドキュメント ライブラリに PDF/XPS を保存しようとしても、何も起こらない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-994">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

### <a name="word"></a><span data-ttu-id="40624-995">Word</span><span class="sxs-lookup"><span data-stu-id="40624-995">Word</span></span>

- <span data-ttu-id="40624-996">テキストとの画像をコメントボックスに貼り付けると Word が応答を停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-996">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>
- <span data-ttu-id="40624-997">最後のコメントを削除すると [新しいコメント] ボタンが無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-997">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-july-03"></a><span data-ttu-id="40624-999">バージョン 2007: 7 月 3 日</span><span class="sxs-lookup"><span data-stu-id="40624-999">Version 2007: July 03</span></span>
<span data-ttu-id="40624-1000">*バージョン 2007 (ビルド 13029.20006)*</span><span class="sxs-lookup"><span data-stu-id="40624-1000">*Version 2007 (Build 13029.20006)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-1002">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-1002">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-1003">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1003">Outlook</span></span>

- <span data-ttu-id="40624-1004">**クイック投票を使用して、Outlook で投票を作成:** 簡単に投票を作成し、票を収集して、メールに結果を表示します [詳細情報](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="40624-1004">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="40624-1005">**新しい会議室の検索機能:** これまでと違うさまざまな機能で会議室を検索できます。</span><span class="sxs-lookup"><span data-stu-id="40624-1005">**New room finder:** Search for conference rooms by different capabilities.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-1008">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-1008">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-1009">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-1009">Excel</span></span>

- <span data-ttu-id="40624-1010">テーブルに関連付けられたクエリが編集されていない場合でも、特定のバージョンの Excel で作成したデータ モデル テーブルが [テーブル プレビュー] に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1010">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>
- <span data-ttu-id="40624-1011">[名前の定義] \ [名前の適用] ダイアログで [相対/絶対を無視] 参照を無効にすると数式が機能しなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1011">We fixed an issue where disabling 'Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>
- <span data-ttu-id="40624-1012">高度なデータ フィルターをクリアするとテーブルの書式設定が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1012">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>
- <span data-ttu-id="40624-1013">埋め込まれた PDF 文書のフル パスがファイル名だけでなく文書の標題に表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1013">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>
- <span data-ttu-id="40624-1014">Wolfram クラウド コネクターを無効にしてから、Excel ブックを保存してもう一度開くとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1014">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>
- <span data-ttu-id="40624-1015">ソルバー アドインを有効にして Excel を起動するとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1015">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-1016">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1016">Outlook</span></span>

- <span data-ttu-id="40624-1017">「To」行に 130 人を超える受信者がいる場合に Outlook がハングする問題を修正し、テキストのレンダリングのパフォーマンスも改善しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1017">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>
- <span data-ttu-id="40624-1018">2 日を超えるイベントはそれ以降のすべての日に同じ終了時刻を表示するという「To Do バー」の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1018">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>
- <span data-ttu-id="40624-1019">Outlook のユーザーが共有の予定表を使用した後、メッセージ一覧の更新が数分間停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1019">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-1020">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-1020">PowerPoint</span></span>

- <span data-ttu-id="40624-1021">スライドのテキスト領域に HTML を貼り付けると、代わりにスライドの上部に作成されたテキスト ボックスに貼り付けられる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1021">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>
- <span data-ttu-id="40624-1022">発表者ビューですべてのスライドを選択し、Alt + Tabを使用して発表者ビューを終了し、スライド ショーに戻って [ショーの終了] をクリックすると、未処理の例外が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1022">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>

### <a name="project"></a><span data-ttu-id="40624-1023">Project</span><span class="sxs-lookup"><span data-stu-id="40624-1023">Project</span></span>

- <span data-ttu-id="40624-1024">特定の XML ファイルを開くと、Project がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1024">We fixed an issue where Project may crash when opening certain XML files.</span></span>
- <span data-ttu-id="40624-1025">ライブラリがモダン モードの場合、SharePoint ドキュメント ライブラリから Project ファイルを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1025">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>
- <span data-ttu-id="40624-1026">URL が「.com」で終了している場合に、Project Web App から Project デスクトップ クライアントでプロジェクトを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1026">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>

### <a name="word"></a><span data-ttu-id="40624-1027">Word</span><span class="sxs-lookup"><span data-stu-id="40624-1027">Word</span></span>

- <span data-ttu-id="40624-1028">マージの競合があり、ユーザーが既に変更を破棄することを選択している場合の共同編集モード中の問題を修正し、変更を保存または破棄するオプションを表示しなくなりました。</span><span class="sxs-lookup"><span data-stu-id="40624-1028">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>
- <span data-ttu-id="40624-1029">マクロを含むファイルを新しい名前で保存しようとすると、拡張子が .docx に指定され、ユーザーがどんな名前を入力しても「WRO0004.docx」というファイル名で保存されるため、その文書を使用できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1029">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-june-26"></a><span data-ttu-id="40624-1031">バージョン 2007: 6月 26 日</span><span class="sxs-lookup"><span data-stu-id="40624-1031">Version 2007: June 26</span></span>
<span data-ttu-id="40624-1032">*バージョン 2007 (ビルド 13020.20004)*</span><span class="sxs-lookup"><span data-stu-id="40624-1032">*Version 2007 (Build 13020.20004)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-1034">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-1034">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="40624-1035">Access</span><span class="sxs-lookup"><span data-stu-id="40624-1035">Access</span></span>

- <span data-ttu-id="40624-1036">リンクされた SQL テーブルが更新された場合、リンクされたテーブル マネージャーが主キーを要求する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1036">We fixed an issue where the linked table manager would prompt for a primary key if a linked SQL table was refreshed.</span></span>
- <span data-ttu-id="40624-1037">クエリ エディターのクエリがスクロールして表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1037">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>
- <span data-ttu-id="40624-1038">クエリの実行に予想よりも約 2 倍の時間がかかっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1038">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-1039">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1039">Outlook</span></span>

- <span data-ttu-id="40624-1040">ユーザーが配布リストの「送信」または「代理送信」ができなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1040">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>
- <span data-ttu-id="40624-1041">メッセージに画像をインラインで挿入し、メッセージを下書きとして保存すると画像のサイズが変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1041">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>
- <span data-ttu-id="40624-1042">件名を編集した後、NDR メッセージの本文が Unicode から ASCII に変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1042">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

### <a name="project"></a><span data-ttu-id="40624-1043">Project</span><span class="sxs-lookup"><span data-stu-id="40624-1043">Project</span></span>

- <span data-ttu-id="40624-1044">政府機関向けコミュニティのクラウド環境でプロジェクト プランナのリンクが無効になっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1044">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>

### <a name="office-suite"></a><span data-ttu-id="40624-1045">Office スイート</span><span class="sxs-lookup"><span data-stu-id="40624-1045">Office Suite</span></span>

- <span data-ttu-id="40624-1046">スケーラブル ベクター グラフィックス （SVG）に挿入されたテキストを、Word、Excel、または PowerPoint ファイルに挿入し、ファイルを保存して閉じ、再度開いた後、判読できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1046">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-june-19"></a><span data-ttu-id="40624-1048">バージョン 2007: 6月 19 日</span><span class="sxs-lookup"><span data-stu-id="40624-1048">Version 2007: June 19</span></span>
<span data-ttu-id="40624-1049">*バージョン 2007 (ビルド 13012.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-1049">*Version 2007 (Build 13012.20000)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-1051">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-1051">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-1052">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-1052">Excel</span></span>

- <span data-ttu-id="40624-1053">SharePoint/OneDriveにブックを保存すると、ユーザー設定のリボンタブの CustomUI XML が削除される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1053">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>
- <span data-ttu-id="40624-1054">ファイルが読み取り専用である場合にのみ、ブックが読み取り専用であった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1054">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-1055">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1055">Outlook</span></span>

- <span data-ttu-id="40624-1056">解像度の異なる複数のモニターを使用している場合に、Input Method Editor (IME) ウィンドウで入力されたテキストが重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1056">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="40624-1057">以前に保存した予定を閉じると、次のエラーが表示される問題を修正しました。「別のユーザーまたは別のウィンドウで変更されたため、アイテムを保存できません。</span><span class="sxs-lookup"><span data-stu-id="40624-1057">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved: "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="40624-1058">アイテムの既定のフォルダーにコピーしますか? 」</span><span class="sxs-lookup"><span data-stu-id="40624-1058">Do you want to make a copy in the default folder for the item?"</span></span>
- <span data-ttu-id="40624-1059">日本のユーザーに対してミニ カレンダーの日付が太字で表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1059">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>
- <span data-ttu-id="40624-1060">予定表のリマインダーで、1 週間以内に行われる会議の正確な時刻が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1060">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-1061">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-1061">PowerPoint</span></span>

- <span data-ttu-id="40624-1062">ライブの共同編集セッション中に共同編集ギャラリーでユーザーのプレゼンス カラー インジケーターが更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1062">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>

### <a name="project"></a><span data-ttu-id="40624-1063">Project</span><span class="sxs-lookup"><span data-stu-id="40624-1063">Project</span></span>

- <span data-ttu-id="40624-1064">固定期間タスクが 100% 完了しているが、実際の完了が指定されていない場合、タスク完了率が 100% 未満として表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1064">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

### <a name="word"></a><span data-ttu-id="40624-1065">Word</span><span class="sxs-lookup"><span data-stu-id="40624-1065">Word</span></span>

- <span data-ttu-id="40624-1066">HTML ハイパーリンクの色が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1066">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="40624-1067">Office スイート</span><span class="sxs-lookup"><span data-stu-id="40624-1067">Office Suite</span></span>

- <span data-ttu-id="40624-1068">http または https ベースではない URL が最近使用したリストに表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1068">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-june-12"></a><span data-ttu-id="40624-1070">バージョン 2007: 6月 12 日</span><span class="sxs-lookup"><span data-stu-id="40624-1070">Version 2007: June 12</span></span>
<span data-ttu-id="40624-1071">*バージョン 2007 (ビルド 13006.20002)*</span><span class="sxs-lookup"><span data-stu-id="40624-1071">*Version 2007 (Build 13006.20002)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-1073">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-1073">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="40624-1074">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-1074">Excel</span></span>

- <span data-ttu-id="40624-1075">**Power BI からデータ型を使用して組織データを取得する:** Power BI からの Excel データ型が Office 365 E5/A5 または Microsoft 365 E5/A5 を使用する組織の Insider にロールアウトされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-1075">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="40624-1076">必要な情報を入手し、簡単に更新することは、多くの日常のワークフローに欠かせません。</span><span class="sxs-lookup"><span data-stu-id="40624-1076">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="40624-1077">Excel のデータ型として、Power BI から会社または組織の情報へのアクセスを提供し、スプレッドシートにリンクされた情報を取り込む機能を拡張します。</span><span class="sxs-lookup"><span data-stu-id="40624-1077">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="40624-1078">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-1078">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="40624-1079">[ブログの投稿](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="40624-1079">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-1082">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-1082">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="40624-1083">Access</span><span class="sxs-lookup"><span data-stu-id="40624-1083">Access</span></span>

- <span data-ttu-id="40624-1084">Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できず、行が削除されたと誤って報告される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1084">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="40624-1085">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-1085">Excel</span></span>

- <span data-ttu-id="40624-1086">レーダーチャートの主要な目盛線が正しく書式設定されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1086">We fixed an issue where the major grid lines of radar charts could not be formatted correctly.</span></span>

### <a name="project"></a><span data-ttu-id="40624-1087">Project</span><span class="sxs-lookup"><span data-stu-id="40624-1087">Project</span></span>

- <span data-ttu-id="40624-1088">プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1088">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>
- <span data-ttu-id="40624-1089">ベースラインのリセットまたは更新により、時間単位の予算コスト/作業リソースが変更され、ベースラインが誤った予算値を反映する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1089">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>

### <a name="word"></a><span data-ttu-id="40624-1090">Word</span><span class="sxs-lookup"><span data-stu-id="40624-1090">Word</span></span>

- <span data-ttu-id="40624-1091">Office リボンの [書式のクリア] ボタンを使用して、[コメント] ウィンドウ内の書式設定をクリアする機能が動作しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1091">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>
- <span data-ttu-id="40624-1092">ルーラーが表示されていないときにテーブルのサイズを変更すると、バックグラウンドで実行されている他のアプリケーションが点滅し始める問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1092">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>
- <span data-ttu-id="40624-1093">共同編集モードで、コメントの返信がコメント ウィンドウに表示されず、変更履歴ウィンドウに表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1093">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>
- <span data-ttu-id="40624-1094">Wordに 50 を超える頻繁に開かれる文書のリストがある場合、文書を保存して開いた後、その文書に変更が加えられていなくても、変更履歴が表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1094">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-june-05"></a><span data-ttu-id="40624-1096">バージョン 2006: 6 月 5 日</span><span class="sxs-lookup"><span data-stu-id="40624-1096">Version 2006: June 05</span></span>
<span data-ttu-id="40624-1097">*バージョン 2006 (ビルド 13001.20002)*</span><span class="sxs-lookup"><span data-stu-id="40624-1097">*Version 2006 (Build 13001.20002)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-1099">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-1099">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="40624-1100">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-1100">Excel</span></span>

- <span data-ttu-id="40624-1101">**Excel での共同作業中の並べ替え/フィルター処理:** Excel ファイルの並べ替えとフィルター処理を他のユーザーと行うことができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-1101">**Sort/filter while collaborating in Excel:** You can now sort and filter your Excel file while collaborating with others.</span></span> <span data-ttu-id="40624-1102">この新機能により、文書を共同編集しているときに、他のユーザーの並べ替えやフィルター処理による影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="40624-1102">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span>

- <span data-ttu-id="40624-1103">**Excel で Power BI のデータセットからピボットテーブルを作成する:** Power BI に保存されているデータセットに接続されている Excel のピボットテーブルを数回のクリックで作成できます。</span><span class="sxs-lookup"><span data-stu-id="40624-1103">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="40624-1104">これにより、ピボットテーブルと Power BI の両方を最大限に活用できます。</span><span class="sxs-lookup"><span data-stu-id="40624-1104">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="40624-1105">セキュリティで保護された Power BI データセットからピボットテーブルを使って、データの計算、集計、分析を行います。</span><span class="sxs-lookup"><span data-stu-id="40624-1105">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="40624-1106">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-1106">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a><span data-ttu-id="40624-1107">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1107">Outlook</span></span>

- <span data-ttu-id="40624-1108">**以前のセッションからアイテムを素早く再開する:** 以前の Outlook セッションからアイテムを素早く再開するためのオプションが追加されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1108">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="40624-1109">Outlook がクラッシュした場合でも、または終了した場合でも、アプリを再び開くと、すばやくアイテムを再起動することができます。</span><span class="sxs-lookup"><span data-stu-id="40624-1109">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="40624-1110">この機能は既定でオンになっています。</span><span class="sxs-lookup"><span data-stu-id="40624-1110">This feature is on by default.</span></span> <span data-ttu-id="40624-1111">オフにするには、[オプション] > [一般] > [開始オプション] に移動します。</span><span class="sxs-lookup"><span data-stu-id="40624-1111">To turn it off, go to Options > General > Start up Options.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-1114">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-1114">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-1115">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-1115">Excel</span></span>

- <span data-ttu-id="40624-1116">グラフの軸にカスタム値が正しく適用されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1116">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>
- <span data-ttu-id="40624-1117">定義された名前を持つ複数の数式を含むワークシートがファイルを保存するときに時間がかかる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1117">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-1118">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1118">Outlook</span></span>

- <span data-ttu-id="40624-1119">解像度の異なる複数のモニターを使用している場合に、IME(Input Method Editor)ウィンドウで入力されたテキストが重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1119">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="40624-1120">新しいメール メッセージの作成時にテンプレートを表示するとクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1120">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>
- <span data-ttu-id="40624-1121">Outlook バージョン1911以降、ユーザーが Exchange 2010のパブリック フォルダーを使用できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1121">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>
- <span data-ttu-id="40624-1122">Office リボンのグループ予定表の [分類] ボタンが無効になっている問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1122">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="40624-1123">競合する連絡先を持つユーザーが Outlook でクラッシュする原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1123">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>
- <span data-ttu-id="40624-1124">高 DPI のモニターを使用しているユーザーに対して、フォルダー プロパティの [オンライン アーカイブ] ドロップダウンが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1124">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>
- <span data-ttu-id="40624-1125">テキスト形式のメールでハイパーリンクを使用して作業しているときに、Outlook でクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1125">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>
- <span data-ttu-id="40624-1126">RFC2231 でエンコードされた長いファイル名を Outlook が解析できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1126">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>
- <span data-ttu-id="40624-1127">スクリーン リーダーを使用すると、Outlook ユーザーに断続的なハングが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1127">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-1128">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-1128">PowerPoint</span></span>

- <span data-ttu-id="40624-1129">サーバ構成のファイルをフォームベースの認証で開くときに発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1129">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>
- <span data-ttu-id="40624-1130">グラフまたはブックが埋め込まれた PowerPoint ファイルの保存時にエラーが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1130">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>
- <span data-ttu-id="40624-1131">ユーザーによって終了されたコメント ウィンドウが自動的に再起動する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1131">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>
- <span data-ttu-id="40624-1132">1つのスライドからのスライド エディタが次のスライドに重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1132">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="40624-1133">Project</span><span class="sxs-lookup"><span data-stu-id="40624-1133">Project</span></span>

- <span data-ttu-id="40624-1134">親計画が削除された後、孤立したタスクの削除や再割り当てができなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1134">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="word"></a><span data-ttu-id="40624-1135">Word</span><span class="sxs-lookup"><span data-stu-id="40624-1135">Word</span></span>

- <span data-ttu-id="40624-1136">コメント ウィンドウのタイムスタンプがシステム ロケールの時間に基づいていなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1136">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>
- <span data-ttu-id="40624-1137">Web アプリとデスクトップ アプリケーションの間のコメントが同期していなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1137">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version-2006-may-29"></a><span data-ttu-id="40624-1139">バージョン 2006: 5 月 29 日</span><span class="sxs-lookup"><span data-stu-id="40624-1139">Version 2006: May 29</span></span>
<span data-ttu-id="40624-1140">*バージョン 2006 (ビルド 12920.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-1140">*Version 2006 (Build 12920.20000)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="40624-1141">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-1141">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-1142">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1142">Outlook</span></span>

- <span data-ttu-id="40624-1143">**Outlook トースト通知に追加されたその他のボタン:** Outlook for Windows 10で Outlook を実行しているときに Outlook トースト通知にクイック アクション ボタンが表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-1143">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-1144">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-1144">PowerPoint</span></span>

- <span data-ttu-id="40624-1145">**PowerPoint でのストリーム ビデオのパフォーマンス向上:** ビデオの読み込み時間を最小限に抑え快適な表示を実現するために Microsoft Stream ビデオの再生パフォーマンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1145">**Improved Stream video performance in PowerPoint:** We've made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span>  <span data-ttu-id="40624-1146">お客様の社内ビデオを使用して、Microsoft Stream でより適切なプレゼンテーションを作成します。</span><span class="sxs-lookup"><span data-stu-id="40624-1146">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-1149">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-1149">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="40624-1150">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-1150">Excel</span></span>

- <span data-ttu-id="40624-1151">OneDrive を起動すると Excel がシャットダウンすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1151">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>
- <span data-ttu-id="40624-1152">同じブック内でブックマークされたハイパーリンクをクリックすると、ブックが非表示になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1152">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>
- <span data-ttu-id="40624-1153">コピー & ペーストされたグラフのリンクの一部で、ユニバーサル アドレスではなくマップされたドライブ アドレスが使用されていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1153">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>
- <span data-ttu-id="40624-1154">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押してスクロールした後、Excel が応答しなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1154">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-1155">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-1155">PowerPoint</span></span>

- <span data-ttu-id="40624-1156">マウス ホイールを使用して拡大した後、スライドが中央に配置されていない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1156">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

### <a name="word"></a><span data-ttu-id="40624-1157">Word</span><span class="sxs-lookup"><span data-stu-id="40624-1157">Word</span></span>

- <span data-ttu-id="40624-1158">テキストのコピーと貼り付けがコメント ウィンドウに表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1158">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>
- <span data-ttu-id="40624-1159">100% ズームでコメント ヒントの吹き出しがぼやけて見える問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1159">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>
- <span data-ttu-id="40624-1160">ポリシー Word 2007 以降のバイナリ文書とテンプレートを有効にすると、一部の共同編集で失敗することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1160">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>
- <span data-ttu-id="40624-1161">長いパス名 (32K を超える) のファイルが開かず、適切なエラー メッセージが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1161">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version-2006-may-22"></a><span data-ttu-id="40624-1163">バージョン 2006: 5 月 22 日</span><span class="sxs-lookup"><span data-stu-id="40624-1163">Version 2006: May 22</span></span>
<span data-ttu-id="40624-1164">*バージョン 2006 (ビルド 12914.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-1164">*Version 2006 (Build 12914.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-1166">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-1166">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="40624-1167">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-1167">Excel</span></span>

- <span data-ttu-id="40624-1168">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="40624-1168">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="40624-1169">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="40624-1169">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="40624-1170">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="40624-1170">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="40624-1171">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="40624-1171">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="40624-1172">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="40624-1172">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-1173">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-1173">PowerPoint</span></span>

- <span data-ttu-id="40624-1174">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="40624-1174">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="40624-1175">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="40624-1175">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="40624-1176">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="40624-1176">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="40624-1177">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="40624-1177">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="40624-1178">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="40624-1178">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="40624-1179">Word</span><span class="sxs-lookup"><span data-stu-id="40624-1179">Word</span></span>

- <span data-ttu-id="40624-1180">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="40624-1180">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="40624-1181">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="40624-1181">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="40624-1182">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="40624-1182">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="40624-1183">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="40624-1183">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="40624-1184">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="40624-1184">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-1187">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-1187">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-1188">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-1188">Excel</span></span>

- <span data-ttu-id="40624-1189">アドインは、ユーザーが指定した順番ではなくアルファベット順に読み込まれていたため、「このブックは現在別のユーザーに参照されており、閉じることができません」というエラー メッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1189">We fixed an issue where the error message: “This workbook is currently referenced by another and cannot be closed” would appear because Add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>
- <span data-ttu-id="40624-1190">Excelとサード パーティの支援技術アプリケーションの一部との間でフォントを管理する際にメモリが破損していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1190">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>
- <span data-ttu-id="40624-1191">選択ロックがない図形を含むワークシート上で、アドインがホスト アイテムを要求すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1191">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-1192">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1192">Outlook</span></span>

- <span data-ttu-id="40624-1193">ユーザーがフォルダー間でアイテムを移動したときに、Folder.BeforeItemMove イベントが正常に起動しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1193">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>
- <span data-ttu-id="40624-1194">予定表のアイテムが午前 0 時のしきい値にまたがっていると、終日イベントとして表示されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1194">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>
- <span data-ttu-id="40624-1195">2 つのアドインがリボンの同じグループにボタンを追加したときに Outlook がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1195">We fixed an issue where Outlook crashed when two Add-ins added a button to the same group in the ribbon.</span></span>
- <span data-ttu-id="40624-1196">ユーザーが予定表をゲスト ユーザーと共有できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1196">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-1197">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-1197">PowerPoint</span></span>

- <span data-ttu-id="40624-1198">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1198">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

### <a name="project"></a><span data-ttu-id="40624-1199">Project</span><span class="sxs-lookup"><span data-stu-id="40624-1199">Project</span></span>

- <span data-ttu-id="40624-1200">オプションをクリックすると Project がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1200">We fixed an issue where Project would crash after clicking on Options.</span></span>

### <a name="word"></a><span data-ttu-id="40624-1201">Word</span><span class="sxs-lookup"><span data-stu-id="40624-1201">Word</span></span>

- <span data-ttu-id="40624-1202">コメント内のハイパーリンクが機能しなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1202">We fixed an issue where hyperlinks in comments weren’t working.</span></span>
- <span data-ttu-id="40624-1203">プレゼンテーション領域を拡大したり縮小したりすると、拡大した選択マーキーとマウスポインタの間に隙間ができてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1203">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>
- <span data-ttu-id="40624-1204">予定表用の WordMail に HTML を貼り付けできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1204">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>
- <span data-ttu-id="40624-1205">共同編集セッションのコメントに返信すると、Word がフリーズすることがあった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1205">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-may-15"></a><span data-ttu-id="40624-1207">バージョン 2006: 5 月 15 日</span><span class="sxs-lookup"><span data-stu-id="40624-1207">Version 2006: May 15</span></span>
<span data-ttu-id="40624-1208">*バージョン 2006 (ビルド 12905.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-1208">*Version 2006 (Build 12905.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-1210">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-1210">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="40624-1211">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-1211">Excel</span></span>

- <span data-ttu-id="40624-1212">**PDF に接続:** PDF からデータに接続、インポート、更新します。</span><span class="sxs-lookup"><span data-stu-id="40624-1212">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="40624-1213">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-1213">Learn more</span></span>](https://support.office.com/article/9967afd8-85ee-4df3-aa06-753bcc1a2724)

- <span data-ttu-id="40624-1214">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="40624-1214">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-1215">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1215">Outlook</span></span>

- <span data-ttu-id="40624-1216">**必要なものだけを見つける:** フォルダー、送信者、日付、添付ファイル情報などのオプションで検索を絞り込みます。</span><span class="sxs-lookup"><span data-stu-id="40624-1216">**Find just what you need:** Narrow your search with options like folder, sender, date, attachment info, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-1217">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-1217">PowerPoint</span></span>

- <span data-ttu-id="40624-1218">**クリッカーは不要: イヤホンでカバー:** Surface Earbuds を使用して、PowerPoint プレゼンテーションを制御します。</span><span class="sxs-lookup"><span data-stu-id="40624-1218">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="40624-1219">重要: ジェスチャーを使用してプレゼンテーションを制御するには、Windows 10 の Surface Audio アプリで Surface Earbuds をペアリングする必要があります。</span><span class="sxs-lookup"><span data-stu-id="40624-1219">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="40624-1220">Windows 10 で Surface Audio アプリを使い始める方法については、こちらをご覧ください。</span><span class="sxs-lookup"><span data-stu-id="40624-1220">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="40624-1221">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-1221">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="40624-1222">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="40624-1222">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="40624-1223">Word</span><span class="sxs-lookup"><span data-stu-id="40624-1223">Word</span></span>

- <span data-ttu-id="40624-1224">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="40624-1224">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-1227">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-1227">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="40624-1228">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-1228">Excel</span></span>
- <span data-ttu-id="40624-1229">ユーザーがマージされた列を削除したときのパフォーマンス時間が向上する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1229">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>
- <div><span data-ttu-id="40624-1230">使用可能なプリンターのリストでプリンター名が重複する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1230">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="40624-1231">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-1231">PowerPoint</span></span>
- <span data-ttu-id="40624-1232">英語スイス (QWERTZ) キーボードを使用すると、キーボード ショートカットとスペル チェックが期待どおりに機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1232">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

### <a name="word"></a><span data-ttu-id="40624-1233">Word</span><span class="sxs-lookup"><span data-stu-id="40624-1233">Word</span></span>
- <span data-ttu-id="40624-1234">空白のドキュメントに新しいコメントを追加しても何も発生しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1234">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>
- <span data-ttu-id="40624-1235">100 個を超えるエントリを含むドキュメントにインデックスを挿入または更新すると、アプリケーションがクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1235">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>
- <span data-ttu-id="40624-1236">カスタム xml 値を含むファイルを開くのが非常に遅い問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1236">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="40624-1237">Office スイート</span><span class="sxs-lookup"><span data-stu-id="40624-1237">Office Suite</span></span>
- <span data-ttu-id="40624-1238">Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1238">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-may-08"></a><span data-ttu-id="40624-1241">バージョン 2006: 5 月 8 日</span><span class="sxs-lookup"><span data-stu-id="40624-1241">Version 2006: May 08</span></span>
<span data-ttu-id="40624-1242">*バージョン 2006 (ビルド 12829.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-1242">*Version 2006 (Build 12829.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-1244">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-1244">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="40624-1245">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-1245">Excel</span></span>

- <span data-ttu-id="40624-1246">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-1246">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-1247">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1247">Outlook</span></span>

- <span data-ttu-id="40624-1248">**より迅速かつ適切な結果:** 検索機能が更新され、よりスマート、迅速、かつ信頼性が高くなりました。</span><span class="sxs-lookup"><span data-stu-id="40624-1248">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="40624-1249">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-1249">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="40624-1250">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-1250">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-1251">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-1251">PowerPoint</span></span>

- <span data-ttu-id="40624-1252">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-1252">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span> [<span data-ttu-id="40624-1253">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-1253">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="40624-1254">Word</span><span class="sxs-lookup"><span data-stu-id="40624-1254">Word</span></span>

- <span data-ttu-id="40624-1255">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-1255">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-1258">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-1258">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="40624-1259">Office スイート</span><span class="sxs-lookup"><span data-stu-id="40624-1259">Office Suite</span></span>

- <span data-ttu-id="40624-1260">OS のシャットダウン後、InTune を介した Office 365 ProPlus の展開が停止する問題を調査し、解決しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1260">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-may-01"></a><span data-ttu-id="40624-1262">バージョン 2005: 5 月 1 日</span><span class="sxs-lookup"><span data-stu-id="40624-1262">Version 2005: May 01</span></span>
<span data-ttu-id="40624-1263">*バージョン 2005 (ビルド 12827.20030)*</span><span class="sxs-lookup"><span data-stu-id="40624-1263">*Version 2005 (Build 12827.20030)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-1265">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-1265">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-1266">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1266">Outlook</span></span>

- <span data-ttu-id="40624-1267">**メール内のリンクの改善:** ファイルへのリンクを含めると、ファイル名が URL に置き換わります。</span><span class="sxs-lookup"><span data-stu-id="40624-1267">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="40624-1268">アクセス許可を変更して、すべての受信者がアクセスできるようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="40624-1268">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="40624-1269">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-1269">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-1272">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-1272">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-1273">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-1273">Excel</span></span>

- <span data-ttu-id="40624-1274">グラフのデータ テーブルの日付軸の値が正しく表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1274">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>
- <span data-ttu-id="40624-1275">[ページ レイアウト] または [改ページ プレビュー] に移動した後に、改ページを無効にできなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1275">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>
- <span data-ttu-id="40624-1276">系列のデータを含む列を非表示にしてから非表示を解除すると、グラフの線のスタイルが失われる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1276">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>
- <span data-ttu-id="40624-1277">フィルター処理されたリストに列を挿入すると、通常よりも時間がかかっていました。</span><span class="sxs-lookup"><span data-stu-id="40624-1277">Inserting a column in a filtered list would take longer than expected.</span></span>
- <span data-ttu-id="40624-1278">従来の "共有ブック" モードを使用して、ブックの新しいシートに変更を一覧表示しようとすると、クラッシュが発生する場合がありました。</span><span class="sxs-lookup"><span data-stu-id="40624-1278">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>
- <span data-ttu-id="40624-1279">[Invert if negative]\(負の値を反転する\) オプションが有効になっていると、ピボット グラフのカスタム書式設定が保存されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1279">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>
- <span data-ttu-id="40624-1280">[Invert if negative]\(負の値を反転する\) オプションが選択されていると、ピボット グラフの単一のデータ ポイントに対するカスタム書式設定が保存されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1280">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>
- <span data-ttu-id="40624-1281">この変更により、CSV ファイルで "@" 文字をアップロードすると、その "@" 文字以降の文字列が数式に変換される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1281">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>
- <span data-ttu-id="40624-1282">SEQUENCE 関数で小数点以下が正しく四捨五入されなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1282">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-1283">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1283">Outlook</span></span>

- <span data-ttu-id="40624-1284">Outlook デスクトップ クライアントで、ユーザーがクリックした非常に長いセーフリンクが、切り捨てにより読み込みに失敗する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-1284">Addresses an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>
- <span data-ttu-id="40624-1285">DBCS (2 バイト文字セット) 文字を含む名前が付けられた Outlook フォルダーが、サーバーと同期するときに断続的に表示されなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1285">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="40624-1286">この問題が発生する場合は、Outlook を IMAP アカウントを使用して構成し、ロケールが日本語に設定されたシステム上で実行する必要がありました。</span><span class="sxs-lookup"><span data-stu-id="40624-1286">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-1287">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-1287">PowerPoint</span></span>

- <span data-ttu-id="40624-1288">ユーザーがコメントを作成したのに投稿せずにそのコメント ウィンドウを閉じ、新しいウィンドウを開いて、複数のスライドを移動してからそのウィンドウを閉じ、最後に、元のプレゼンテーションでコメント ウィンドウをもう一度開くと、下書きのコメントが利用できなくなっている問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1288">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

### <a name="project"></a><span data-ttu-id="40624-1289">Project</span><span class="sxs-lookup"><span data-stu-id="40624-1289">Project</span></span>

- <span data-ttu-id="40624-1290">Project が Project Web App に接続されていて、小数点の記号がカンマの場合、タイム ラグを追加する際に TaskDependencies Add メソッドが失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1290">Fixed an issue where if Project is connected to the Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>

### <a name="word"></a><span data-ttu-id="40624-1291">Word</span><span class="sxs-lookup"><span data-stu-id="40624-1291">Word</span></span>

- <span data-ttu-id="40624-1292">コラボレーション モードのドキュメントにコメントを挿入しても正常に動作しない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1292">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>
- <span data-ttu-id="40624-1293">この変更により、@メンションがクリックされると連絡先カードが点滅する問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1293">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>
- <span data-ttu-id="40624-1294">下書きのコメントを含むドキュメントを閉じようとすると、その下書きのコメントを保存せずにドキュメントを閉じてもよいかユーザーに確認を求める問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1294">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="40624-1295">このプロンプトをキャンセルすると、ドキュメントが開いたままになるのではなく、閉じられていました。</span><span class="sxs-lookup"><span data-stu-id="40624-1295">Cancelling the prompt would close the document rather than leaving it open.</span></span>
- <span data-ttu-id="40624-1296">投稿されたコメントを翻訳しようとすると、"Inserting translated text failed" (翻訳されたテキストの挿入に失敗しました) エラーが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1296">Fixed an issue where translating a posted comment would result in the error "Inserting translated text failed".</span></span>
- <span data-ttu-id="40624-1297">Web ビュー/イマーシブ リーダーでヒントをクリックすると、ヒントが既に表示されている場合でも一番上までスクロールしていました。</span><span class="sxs-lookup"><span data-stu-id="40624-1297">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="40624-1298">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1298">This has been fixed.</span></span>
- <span data-ttu-id="40624-1299">マクロを含むファイルを新しい名前で保存しようとすると、拡張子が .docx に指定され、ユーザーがどんな名前を入力しても WRO0004.docx というファイル名で保存されるため、そのドキュメントを使用できなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1299">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version-2005-april-24"></a><span data-ttu-id="40624-1301">バージョン 2005: 4 月 24 日</span><span class="sxs-lookup"><span data-stu-id="40624-1301">Version 2005: April 24</span></span>
<span data-ttu-id="40624-1302">*バージョン 2005 (ビルド 12816.20006)*</span><span class="sxs-lookup"><span data-stu-id="40624-1302">*Version 2005 (Build 12816.20006)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-1304">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-1304">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-1305">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-1305">Excel</span></span>
- <span data-ttu-id="40624-1306">この変更により、LINEST 関数が正しい値を返すにもかかわらず (強制的な y 切片のケースの) グラフの近似曲線の R-2 乗値が正しくないという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1306">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>
- <span data-ttu-id="40624-1307">この変更により、カスタマイズされたグラフの近似曲線の書式設定が保存されないことがあるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1307">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-1308">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1308">Outlook</span></span>
- <span data-ttu-id="40624-1309">Office リボンのグループ予定表の [分類] ボタンが無効になっているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1309">Fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="40624-1310">グループ フォルダーを実装していないまたは動作させていないエンタープライズ ユーザーに、Outlook で "応答なし" というメッセージが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1310">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-1311">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-1311">PowerPoint</span></span>
- <span data-ttu-id="40624-1312">アスタリスク (\*) 記号の上にポインターを移動しても、最後にドキュメントを更新した人のユーザー名と日付が表示されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1312">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="word"></a><span data-ttu-id="40624-1313">Word</span><span class="sxs-lookup"><span data-stu-id="40624-1313">Word</span></span>
- <span data-ttu-id="40624-1314">[ブックマークの表示] オプションを有効にしても、ブックマークが表示されませんでした。</span><span class="sxs-lookup"><span data-stu-id="40624-1314">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="40624-1315">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1315">This has been fixed.</span></span>
- <span data-ttu-id="40624-1316">この変更により、[値の代わりにフィールド コードを表示する] オプションが有効になっている場合に、ハイパーリンク付きのテキストが表示されないという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1316">This change fixes an issue where text with hyperlinks may not display if the option "Show field codes instead of their values" was enabled.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version-2005-april-17"></a><span data-ttu-id="40624-1318">バージョン 2005: 4 月 17 日</span><span class="sxs-lookup"><span data-stu-id="40624-1318">Version 2005: April 17</span></span>
<span data-ttu-id="40624-1319">*バージョン 2005 (ビルド 12810.20002)*</span><span class="sxs-lookup"><span data-stu-id="40624-1319">*Version 2005 (Build 12810.20002)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-1321">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-1321">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-1322">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-1322">Excel</span></span>
- <span data-ttu-id="40624-1323">グラフと共に使用される [ユーザー設定の誤差範囲] ダイアログでセル参照エディット コントロールのサイズが大きくなります。</span><span class="sxs-lookup"><span data-stu-id="40624-1323">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>
- <span data-ttu-id="40624-1324">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="40624-1324">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>
- <span data-ttu-id="40624-1325">印刷時にフォーム コントロールのチェックボックスが拡大縮小されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1325">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>
- <span data-ttu-id="40624-1326">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="40624-1326">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>
- <span data-ttu-id="40624-1327">この変更により、条件付き書式 (CF) 情報が .XLSB ファイルに正常に保存されなかった問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1327">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="40624-1328">OneNote</span><span class="sxs-lookup"><span data-stu-id="40624-1328">OneNote</span></span>
- <span data-ttu-id="40624-1329">改行が垂直タブとして保存されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1329">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-1330">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1330">Outlook</span></span>
- <span data-ttu-id="40624-1331">ユーザーが個人用連絡先グループを会議の出席者として追加できなくなった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-1331">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>
- <span data-ttu-id="40624-1332">スケジュール アシスタントで 2 か月以上離れた会議が会議の件名が表示されないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-1332">Addresses an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>
- <span data-ttu-id="40624-1333">大きな HTML メッセージを転送するとき、ユーザーにメッセージ本文の全体が表示されないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-1333">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>
- <span data-ttu-id="40624-1334">グループ ポリシーを使用して S/MIME の既定の署名構成を適用する機能が追加された。</span><span class="sxs-lookup"><span data-stu-id="40624-1334">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>
- <span data-ttu-id="40624-1335">ユーザーのプライマリ メールボックス以外のメールボックスに対して作成された削除ルールが無効になるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-1335">Addresses an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>
- <span data-ttu-id="40624-1336">暗号化されたメッセージを転送するときに添付ファイルが削除されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-1336">Addresses an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

### <a name="project"></a><span data-ttu-id="40624-1337">Project</span><span class="sxs-lookup"><span data-stu-id="40624-1337">Project</span></span>
- <span data-ttu-id="40624-1338">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="40624-1338">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>
- <span data-ttu-id="40624-1339">SharePoint タスク リストに接続されているプロジェクトのボードの状態フィールドを変更すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1339">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>
- <span data-ttu-id="40624-1340">以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1340">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version-2004-april-10"></a><span data-ttu-id="40624-1342">バージョン 2004: 4 月 10 日</span><span class="sxs-lookup"><span data-stu-id="40624-1342">Version 2004: April 10</span></span>
<span data-ttu-id="40624-1343">*バージョン 2004 (ビルド 12730.20024)*</span><span class="sxs-lookup"><span data-stu-id="40624-1343">*Version 2004 (Build 12730.20024)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-1345">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-1345">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="40624-1346">Access</span><span class="sxs-lookup"><span data-stu-id="40624-1346">Access</span></span>

- <span data-ttu-id="40624-1347">**[テーブルの表示] ダイアログ ボックスをバイパスし、作業ウィンドウに直接移動して、テーブルを効率よくリレーションシップやクエリに追加します。:** 4 つのタブをクリックして、名前を複数選択して、テキストで検索し、作業中に開いたままの作業ウィンドウからドラッグして、テーブルやクエリを追加 ます。</span><span class="sxs-lookup"><span data-stu-id="40624-1347">**Bypass the Show Table dialog box, go directly to a task pane, and streamline adding tables to relationships and queries.:** Add tables and queries by clicking four tabs, multi-selecting names, searching by text, and dragging from a task pane that stays open while you work.</span></span>

### <a name="excel"></a><span data-ttu-id="40624-1348">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-1348">Excel</span></span>

- <span data-ttu-id="40624-1349">**M365 Premium Content Picker:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="40624-1349">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="40624-1350">1000 件のロイヤリティフリーのストック画像、アイコン、ステッカーを詳しく見る [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="40624-1350">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-1351">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1351">Outlook</span></span>

- <span data-ttu-id="40624-1352">**M365 Premium Content Picker:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="40624-1352">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="40624-1353">1000 件のロイヤリティフリーのストック画像、アイコン、ステッカーを詳しく見る [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="40624-1353">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="40624-1354">**メールの一部として画像を送信するときに、画像を高品質に維持する:** メールの内容の一部として画像を送信するときに、画像の圧縮を制限するための新しい Outlook の設定を使用できます。</span><span class="sxs-lookup"><span data-stu-id="40624-1354">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-1355">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-1355">PowerPoint</span></span>

- <span data-ttu-id="40624-1356">**M365 Premium Content Picker:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="40624-1356">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="40624-1357">1000 件のロイヤリティフリーのストック画像、アイコン、ステッカーを詳しく見る [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="40624-1357">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="40624-1358">**プレゼンテーション中に変更を同期する:** プレゼンテーションがスライド ショー モードであれば、いつでも変更を同期できます。</span><span class="sxs-lookup"><span data-stu-id="40624-1358">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="40624-1359">Word</span><span class="sxs-lookup"><span data-stu-id="40624-1359">Word</span></span>

- <span data-ttu-id="40624-1360">**M365 Premium Content Picker:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="40624-1360">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="40624-1361">1000 件のロイヤリティフリーのストック画像、アイコン、ステッカーを詳しく見る [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="40624-1361">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="40624-1362">**個人用コピーに注釈を付ける:** 共有ドキュメントの個人用コピーを作成し、自分用の手書きノートを作成します。</span><span class="sxs-lookup"><span data-stu-id="40624-1362">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="40624-1363">[表示] > [個人用コピーの作成] に移動して開始します。</span><span class="sxs-lookup"><span data-stu-id="40624-1363">Go to View > Create a Private Copy to get started.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-1366">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-1366">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="40624-1367">Access</span><span class="sxs-lookup"><span data-stu-id="40624-1367">Access</span></span>

- <span data-ttu-id="40624-1368">作業ウィンドウのテーブルのサイズ変更と更新に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1368">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

### <a name="excel"></a><span data-ttu-id="40624-1369">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-1369">Excel</span></span>

- <span data-ttu-id="40624-1370">シートのセル範囲を選択すると、1 つのセルが選択されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1370">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="40624-1371">X 軸の範囲に合わせてグラフのサイズを小さくすると、Excel が応答を停止する可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1371">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="40624-1372">ユーザー定義のグラフ テンプレートを既定として挿入すると、縦棒グラフとして保存されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1372">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="40624-1373">基になるデータ セルにタイトルがない場合に、グラフのデータ ラベルが空白として表示されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1373">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="40624-1374">R1C1 セルの参照が有効になっている Excel シートが共同編集/共有される場合に、R1C1 モードでユーザー プレゼンス アイコンの上にカーソルを移動すると、アクティブセル参照が表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1374">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-1375">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1375">Outlook</span></span>

- <span data-ttu-id="40624-1376">メール メッセージからカテゴリが消えることがあるという問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="40624-1376">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="40624-1377">共有メールボックスに対して、異なるコンピューター上の別のフォルダー階層が代理人に表示されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-1377">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="40624-1378">ユーザーが組織フォームのプロパティを表示とするときにクラッシュするという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-1378">Addresses an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="40624-1379">コンピューターのタイムゾーンを変更するときに、一部のリマインダーが発生しないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-1379">Addresses an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-1380">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-1380">PowerPoint</span></span>

- <span data-ttu-id="40624-1381">この変更により、PowerPoint または Word に OLE オブジェクトとして埋め込まれたレガシ Excel グラフを表示するとき、グラフ タイトルが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1381">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="40624-1382">Excel から PowerPoint にテキストをコピーするときに、書式設定が変更される場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1382">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="40624-1383">この変更により、[完全に一致する単語だけを検索する] を使用して特殊文字を検索するときに、想定どおりに動作しない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1383">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="40624-1384">Project</span><span class="sxs-lookup"><span data-stu-id="40624-1384">Project</span></span>

- <span data-ttu-id="40624-1385">実績作業時間の保護設定を有効にしているときに、ユーザーがタイムフェーズの基準作業時間を入力できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1385">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="40624-1386">Word</span><span class="sxs-lookup"><span data-stu-id="40624-1386">Word</span></span>

- <span data-ttu-id="40624-1387">この変更により、ヒントの上にカーソルを移動してもカードが強調表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1387">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="40624-1388">この変更により、なげなわ選択ツールを使用するとき、グループ化された図形のテキストが一時的に非表示になる場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1388">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="40624-1389">この変更により、PowerPoint または Word に OLE オブジェクトとして埋め込まれたレガシ Excel グラフを表示するとき、グラフ タイトルが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1389">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="40624-1390">この変更により、コメントを作成するとき、コメント アンカーが表示されない場合があるという 2 ページ表示の問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1390">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="40624-1391">スタイルがリストにリンクされている祖先のスタイルである段落の場合、そのリストの番号が失われる場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1391">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-march-27"></a><span data-ttu-id="40624-1393">バージョン 2004: 3 月 27 日</span><span class="sxs-lookup"><span data-stu-id="40624-1393">Version 2004: March 27</span></span>
<span data-ttu-id="40624-1394">*バージョン 2004 (ビルド 12718.20010)*</span><span class="sxs-lookup"><span data-stu-id="40624-1394">*Version 2004 (Build 12718.20010)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-1396">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-1396">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-1397">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1397">Outlook</span></span>

- <span data-ttu-id="40624-1398">**メール作成時の @ メンションの候補表示を無効にするオプションが追加されました。** メンション ピッカーが便利どころか迷惑だと感じていますか?</span><span class="sxs-lookup"><span data-stu-id="40624-1398">**New option to disable @ mention suggestions when composing mail:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="40624-1399">今後は、必要に応じてオフにすることができます。</span><span class="sxs-lookup"><span data-stu-id="40624-1399">Now you can turn it off if you prefer.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-1402">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-1402">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-1403">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1403">Outlook</span></span>
- <span data-ttu-id="40624-1404">[添付ファイル ​​ツール] に [クラウドに保存] ボタンが表示されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-1404">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>
- <span data-ttu-id="40624-1405">ユーザーが返信メッセージの所有者アクセス許可を持っていない場合、[インスペクタ] ウィンドウから権限がデジタル管理されたメッセージに返信するときに、ユーザーが署名を追加できないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-1405">Addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>
- <span data-ttu-id="40624-1406">以前作成した会議に、Web 上の場所から追加の添付ファイルを追加できないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-1406">Addresses an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-1407">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-1407">PowerPoint</span></span>
- <span data-ttu-id="40624-1408">この変更により、絵文字を含む PowerPoint ファイルを保存する場合に失敗する可能性があるエラーが修正されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1408">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

### <a name="project"></a><span data-ttu-id="40624-1409">Project</span><span class="sxs-lookup"><span data-stu-id="40624-1409">Project</span></span>
- <span data-ttu-id="40624-1410">CustomFieldValueListGetItem が実行され、ユーザー設定フィールドの参照テーブルが存在しない場合、誤って空の参照テーブルが作成される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1410">Fixed an issue where if 'CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

### <a name="word"></a><span data-ttu-id="40624-1411">Word</span><span class="sxs-lookup"><span data-stu-id="40624-1411">Word</span></span>
- <span data-ttu-id="40624-1412">この変更により、 [表示] メニューから複数のページを選択すると、[コメント] ウィンドウが空白で表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1412">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-march-20"></a><span data-ttu-id="40624-1414">バージョン 2004: 3 月 20 日</span><span class="sxs-lookup"><span data-stu-id="40624-1414">Version 2004: March 20</span></span>
<span data-ttu-id="40624-1415">*バージョン 2004 (ビルド 12711.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-1415">*Version 2004 (Build 12711.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-1417">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-1417">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-1418">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1418">Outlook</span></span>

- <span data-ttu-id="40624-1419">**予定表デザインの更新:** 昨年、Microsoft ではメール エクスペリエンスを更新しました。今年は予定表のデザインを更新します!</span><span class="sxs-lookup"><span data-stu-id="40624-1419">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar's turn to get a facelift!</span></span> <span data-ttu-id="40624-1420">更新されていますが使い慣れた製品ですので、経験豊富な Outlook ユーザーとして、すぐに使いこなして生産性を高めることができます。</span><span class="sxs-lookup"><span data-stu-id="40624-1420">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

- <span data-ttu-id="40624-1421">**グループ内のデータを保護:** グループを作成するときに選択する秘密度ラベルがグループ メール、ドキュメント、チーム サイトに適用されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1421">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-1422">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-1422">PowerPoint</span></span>

- <span data-ttu-id="40624-1423">**スライド ショーの実行中にスライドを更新する:** プレゼンテーション中に他の作成者が変更したスライドを更新します。</span><span class="sxs-lookup"><span data-stu-id="40624-1423">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-1426">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-1426">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-1427">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-1427">Excel</span></span>

- <span data-ttu-id="40624-1428">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1428">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-1429">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1429">Outlook</span></span>

- <span data-ttu-id="40624-1430">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1430">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="40624-1431">この変更により、下書きメールに対する最新の変更が更新されなかった問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1431">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="40624-1432">ファイルを右クリックして [送信] を使用しても機能しなかった問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1432">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="40624-1433">ユーザーがアドレス帳の検索パスをカスタマイズしていた場合に、Outlook の名前解決範囲がグローバル アドレス一覧 (GAL) ではなく、カスタマイズしたパスに制限されていた問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1433">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="40624-1434">返された一連の検索結果の中で、結果をカテゴリ別に並べ替えると、カテゴリ カラーが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1434">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

### <a name="project"></a><span data-ttu-id="40624-1435">Project</span><span class="sxs-lookup"><span data-stu-id="40624-1435">Project</span></span>

- <span data-ttu-id="40624-1436">ユーザーがスケジュール グループ内の [タスク] リボンにある「無効化」ボタンをクリックしたときに 'ProjectBeforeTaskChange' という Visual Basic Applications (VBA) イベントが発生しなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1436">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the "Inactivate" button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="40624-1437">[フォームの種類] ビュー内から先行タスクまたは後続タスクの詳細を設定した場合に、ProjectBeforeTaskChange という Visual Basic Applications (VBA) イベントが変更をキャプチャしないことがありました。</span><span class="sxs-lookup"><span data-stu-id="40624-1437">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="40624-1438">たとえば、依存関係を削除し、フォームで [OK] をクリックした場合に、イベントが発生しませんでした。</span><span class="sxs-lookup"><span data-stu-id="40624-1438">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="40624-1439">この動作が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1439">This behavior has been fixed.</span></span>

- <span data-ttu-id="40624-1440">日付の変更などの変更を加えた後に、終了した作業時間の実績コスト (ACWP) の最新の値が表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1440">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="40624-1441">[最近使用した項目 (MRU)] メニューを使用してプロジェクトを開くと、読み取り/書き込みアクセス権を伴ってプロジェクト ファイルが開かれる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1441">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="40624-1442">この変更によって、開始日時を指定した (しかし期間を指定しない) 手動タスクを作成した場合に、タイムライン上に間違った時刻が表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1442">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="40624-1443">イスラム暦予定表を使用してタイムラインを印刷すると、[印刷] ビューで、1 か月スキップされるか、または重複する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1443">Fixed an issue where printing a timeline using Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="40624-1444">この変更により、GDI オブジェクトを使用して Team Planner を操作するときに、GDI オブジェクトの割り当てが過剰になり、メモリ不足状態が発生する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1444">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

### <a name="word"></a><span data-ttu-id="40624-1445">Word</span><span class="sxs-lookup"><span data-stu-id="40624-1445">Word</span></span>

- <span data-ttu-id="40624-1446">コメントを投稿する機能が無効になる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1446">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="40624-1447">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1447">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="40624-1448">この変更により、アカウント マネージャーがサードパーティのアプリケーションを使用してメッセージを送ろうとすると、ハングしてディスパッチできないという問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1448">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="40624-1449">この変更により、文書に記載されていない見出しスタイルで目次が更新されるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1449">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="40624-1450">Word 文書をメール送信するときに、文書に保存されていたデジタル署名が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="40624-1450">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-march-13"></a><span data-ttu-id="40624-1452">バージョン 2004: 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="40624-1452">Version 2004: March 13</span></span>
<span data-ttu-id="40624-1453">*バージョン 2004 (ビルド 12703.20010)*</span><span class="sxs-lookup"><span data-stu-id="40624-1453">*Version 2004 (Build 12703.20010)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-1455">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-1455">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="40624-1456">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-1456">Excel</span></span>
- <span data-ttu-id="40624-1457">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-1457">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="40624-1458">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-1458">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="40624-1459">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-1459">PowerPoint</span></span>
- <span data-ttu-id="40624-1460">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-1460">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="40624-1461">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-1461">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="40624-1462">Word</span><span class="sxs-lookup"><span data-stu-id="40624-1462">Word</span></span>
- <span data-ttu-id="40624-1463">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="40624-1463">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="40624-1464">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-1464">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-1467">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-1467">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="40624-1468">Access</span><span class="sxs-lookup"><span data-stu-id="40624-1468">Access</span></span>
- <span data-ttu-id="40624-1469">Access のインターナショナル バージョンにおいて、ユーザー インターフェイスに英語の文字列が表示されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1469">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="40624-1470">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-1470">Excel</span></span>
- <span data-ttu-id="40624-1471">プログラムを使って大きいセル範囲を編集するときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1471">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>
- <span data-ttu-id="40624-1472">日本語の環境で CSV ファイルを開くときに発生するパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1472">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-1473">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1473">Outlook</span></span>
- <span data-ttu-id="40624-1474">(メニューからではなく) ドラッグ アンド ドロップでメールに添付ファイルを追加したり、メールから添付ファイルを保存したりすると、ファイルの「最終更新日」が更新される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-1474">Addresses an issue that caused the "Last Modified"; date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>
- <span data-ttu-id="40624-1475">展開された [検索] ウィンドウで Enter キーを押しても検索が開始されず、代わりにユーザーが [検索] ボタンをクリックしなければならないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-1475">Addresses an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>
- <span data-ttu-id="40624-1476">[利用可能な場合はユーザーの写真を表示する] オプションがオフになっている場合、検索結果にユーザーに関する情報が表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1476">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>

### <a name="project"></a><span data-ttu-id="40624-1477">Project</span><span class="sxs-lookup"><span data-stu-id="40624-1477">Project</span></span>
- <span data-ttu-id="40624-1478">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1478">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>
- <span data-ttu-id="40624-1479">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1479">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="40624-1480">Word</span><span class="sxs-lookup"><span data-stu-id="40624-1480">Word</span></span>
- <span data-ttu-id="40624-1481">コメントを入力または編集し、Ctrl キーを押しながら A キーを押したときに、コメント カード内のテキストが選択されるのではなく、キャンバスのテキストが選択されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1481">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>
- <span data-ttu-id="40624-1482">クイック印刷を使用して印刷した後に編集しようとしたときに、ドキュメント内の単語の配置が乱れてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1482">We fixed an issue in which the alignment of words in a document gets scrambled when tried to edit after printing using Quick Print.</span></span>
- <span data-ttu-id="40624-1483">2 つのドキュメントを 1 つのドキュメントに結合するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1483">We fixed an issue when merging two documents into one document.</span></span>
- <span data-ttu-id="40624-1484">数式を含む変更履歴をマークすると、ファイルを保存するときにエラーが発生するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1484">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-06"></a><span data-ttu-id="40624-1486">バージョン 2003: 3 月 6 日</span><span class="sxs-lookup"><span data-stu-id="40624-1486">Version 2003: March 06</span></span>
<span data-ttu-id="40624-1487">*バージョン 2003 (ビルド 12624.20086)*</span><span class="sxs-lookup"><span data-stu-id="40624-1487">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-1489">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-1489">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-1490">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1490">Outlook</span></span>

- <span data-ttu-id="40624-1491">Outlook Web Access を使用してルールを作成しても Exchange サーバーに保存されず競合が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1491">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="40624-1492">ダーク モードの Outlook の [差出人] フィールドにドロップダウン リストが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1492">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="40624-1493">ファイルが別のアプリケーションで開かれているときに、ユーザーがエクスプローラーでファイルをメール メッセージに添付できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1493">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-1494">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-1494">PowerPoint</span></span>

- <span data-ttu-id="40624-1495">サムネイルの上にマウスポインターを置くと推奨されるサムネイルが点滅する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1495">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="40624-1496">場合によっては、これにより PowerPoint がクラッシュしてしまう可能性があります。</span><span class="sxs-lookup"><span data-stu-id="40624-1496">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="40624-1497">Word</span><span class="sxs-lookup"><span data-stu-id="40624-1497">Word</span></span>

- <span data-ttu-id="40624-1498">編集用に保護されたドキュメントの比較機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1498">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="40624-1499">Office スイート</span><span class="sxs-lookup"><span data-stu-id="40624-1499">Office Suite</span></span>

- <span data-ttu-id="40624-1500">ユーザー プリンシパル名 (UPN) の大文字と小文字が区別されなくなり、SharePoint でファイルを操作するときにはエラーが少なくなるという Word/Excel/PowerPoint の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1500">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="40624-1501">機能に影響はないものの、[ファイル]、[オプション] の順で進んだ後のダイアログの [OK] ボタンが灰色で表示されていた外観上の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1501">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

## <a name="version-2003-february-28"></a><span data-ttu-id="40624-1504">バージョン 2003: 2 月 28 日</span><span class="sxs-lookup"><span data-stu-id="40624-1504">Version 2003: February 28</span></span>
<span data-ttu-id="40624-1505">*バージョン 2003 (ビルド 12619.20002)*</span><span class="sxs-lookup"><span data-stu-id="40624-1505">*Version 2003 (Build 12619.20002)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-1507">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-1507">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-1508">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1508">Outlook</span></span>

- <span data-ttu-id="40624-1509">**IT 管理者向けのインシデント通知:** Microsoft 365 テナントのグローバル管理者および Office Apps 管理者は、Outlook for Windows の新しい右側のパネル通知により、ユーザーに影響する Outlook および O365 Exchange インシデントについて通知されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1509">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="40624-1510">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-1510">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

### <a name="powerpoint"></a><span data-ttu-id="40624-1511">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-1511">PowerPoint</span></span>

- <span data-ttu-id="40624-1512">**インクを図形に変換する作図エクスペリエンスの向上:** より良い図を描いて変換し、Office オブジェクトを操作できるようにします。[詳細情報](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="40624-1512">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-1515">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-1515">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="40624-1516">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-1516">Excel</span></span>

- <span data-ttu-id="40624-1517">[印刷プレビュー] でスライサーのテキストが適切に拡大または縮小されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1517">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-1518">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1518">Outlook</span></span>

- <span data-ttu-id="40624-1519">(メニューからではなく) ドラッグ アンド ドロップでメールに添付ファイルを追加したり、メールから添付ファイルを保存したりすると、ファイルの「最終更新日」が更新される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-1519">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="40624-1520">Word</span><span class="sxs-lookup"><span data-stu-id="40624-1520">Word</span></span>

- <span data-ttu-id="40624-1521">コメント カードでタブすると、コメント編集ボックスにフォーカスが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1521">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="40624-1522">コントロール (テキスト コンテンツ コントロールなど) を数式に挿入し、ファイルを保存して開くと、読み取り不可能なコンテンツ エラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="40624-1522">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="40624-1523">以前にパスワードで保護されたファイルをクラウド ストレージに保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1523">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="40624-1524">Office スイート</span><span class="sxs-lookup"><span data-stu-id="40624-1524">Office Suite</span></span>

- <span data-ttu-id="40624-1525">同じ SharePoint ライブラリから Word/Excel/PowerPoint で複数のドキュメントが開かれている場合、最初に開いたドキュメントのみがポリシー コンプライアンスでスキャンされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1525">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-february-21"></a><span data-ttu-id="40624-1527">バージョン 2003: 2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="40624-1527">Version 2003: February 21</span></span>
<span data-ttu-id="40624-1528">*バージョン 2003 (ビルド 12615.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-1528">*Version 2003 (Build 12615.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-1530">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-1530">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="40624-1531">Office スイート</span><span class="sxs-lookup"><span data-stu-id="40624-1531">Office Suite</span></span>

- <span data-ttu-id="40624-1532">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキスト ハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="40624-1532">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-1535">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-1535">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="40624-1536">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-1536">Excel</span></span>
- <span data-ttu-id="40624-1537">ピボット テーブルのメジャーの名前を変更するときにユーザーが経験する可能性のある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1537">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="40624-1538">VBA マクロを使用して範囲の内容をクリアするときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1538">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="40624-1539">ユーザーがリボンを操作するマクロを実行したときに UI が点滅する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1539">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="40624-1540">ファイルの最初の単語が TABLE である場合に CSV ファイルが誤ってロードされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1540">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="40624-1541">ズーム レベルが異なる 2 つのブックを切り替える際にユーザーがクラッシュを経験する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1541">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-1542">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1542">Outlook</span></span>
- <span data-ttu-id="40624-1543">Outlook を夜間に実行したままにしておくと、ユーザーがパブリック フォルダー メッセージを開けなくなる問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1543">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="40624-1544">Gmail アカウントを追加する認証ワークフロー中に、[アクセス許可] ページの [許可] および [拒否] ボタンが無効になる競合状態を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1544">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="40624-1545">一部のシナリオで、ログがオフになっている場合でも Outlook が予期せずログ出力を生成する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1545">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="40624-1546">Word</span><span class="sxs-lookup"><span data-stu-id="40624-1546">Word</span></span>
- <span data-ttu-id="40624-1547">マウス ポインターをコメント カードの上に置いたときに、コメント カードが常に強調表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1547">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="40624-1548">アクティブなドキュメントの共同編集セッション中に、画像をコメント カードに直接追加すると、タグが追加されている場合があります。</span><span class="sxs-lookup"><span data-stu-id="40624-1548">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="40624-1549">この問題は修正されています。</span><span class="sxs-lookup"><span data-stu-id="40624-1549">This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="40624-1550">Office スイート</span><span class="sxs-lookup"><span data-stu-id="40624-1550">Office Suite</span></span>
- <span data-ttu-id="40624-1551">Word/Excel/PowerPoint ドキュメントで Multichoice/Lookup/Managed-metadata プロパティを使用し、SharePoint ドキュメント ライブラリに保存する場合、これらのプロパティは以前は 255 文字に制限されていました。</span><span class="sxs-lookup"><span data-stu-id="40624-1551">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="40624-1552">これらのプロパティが 255 文字を超えると、そういったドキュメントは保存することができませんでした。</span><span class="sxs-lookup"><span data-stu-id="40624-1552">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="40624-1553">この変更により、この制限は 2048 文字に増加しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1553">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-february-14"></a><span data-ttu-id="40624-1555">バージョン 2003: 2 月 14 日</span><span class="sxs-lookup"><span data-stu-id="40624-1555">Version 2003: February 14</span></span>
<span data-ttu-id="40624-1556">*バージョン 2003 (ビルド 12607.20000)*</span><span class="sxs-lookup"><span data-stu-id="40624-1556">*Version 2003 (Build 12607.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-1558">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-1558">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-1559">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1559">Outlook</span></span>

- <span data-ttu-id="40624-1560">**キャプティブ WiFi ネットワークの新しいエクスペリエンス**: サインインに Web ページを必要とする WiFi ネットワークに参加したことはありませんか ?</span><span class="sxs-lookup"><span data-stu-id="40624-1560">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="40624-1561">Outlook はこれを検出し、接続を支援します。</span><span class="sxs-lookup"><span data-stu-id="40624-1561">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="40624-1562">Word</span><span class="sxs-lookup"><span data-stu-id="40624-1562">Word</span></span>

- <span data-ttu-id="40624-1563">**描画ツールボックスでインク エディターを見つける**: [描画] を選択し、[インク エディター] ペンを選択して、指またはデジタル ペンでドキュメントを編集します。</span><span class="sxs-lookup"><span data-stu-id="40624-1563">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="40624-1564">詳細情報</span><span class="sxs-lookup"><span data-stu-id="40624-1564">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="40624-1565">Office スイート</span><span class="sxs-lookup"><span data-stu-id="40624-1565">Office Suite</span></span>

- <span data-ttu-id="40624-1566">**明瞭になったステータス バー アイコン:** ステータス バーのアイコンが見やすくなりました</span><span class="sxs-lookup"><span data-stu-id="40624-1566">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-1569">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-1569">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="40624-1570">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1570">Outlook</span></span>

- <span data-ttu-id="40624-1571">ユーザーが「空き時間情報オプション」予定表のアクセス許可ダイアログにアクセスできなくなる問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1571">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="40624-1572">異なるタイム ゾーンから送信された定期的な会議インスタンスを開くときに「申し訳ございません、このアイテムを開くことができません」というアラートが発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1572">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="40624-1573">メッセージから添付ファイルをドラッグ アンド ドロップした後、ユーザーが .msg ファイルを再度開くことができない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1573">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="40624-1574">Outlook から OneDrive に添付ファイルをアップロードした後、添付ファイルの名前にかっこが含まれているとファイル名が変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1574">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-1575">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-1575">PowerPoint</span></span>

- <span data-ttu-id="40624-1576">Excel グラフを含む PowerPoint または Word でドキュメントを保存できないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1576">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="40624-1577">Word</span><span class="sxs-lookup"><span data-stu-id="40624-1577">Word</span></span>

- <span data-ttu-id="40624-1578">ドキュメントを PDF にエクスポートすると、画像の透明性が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1578">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-february-07"></a><span data-ttu-id="40624-1580">バージョン 2002: 2 月 7 日</span><span class="sxs-lookup"><span data-stu-id="40624-1580">Version 2002: February 07</span></span>
<span data-ttu-id="40624-1581">*バージョン 2002 (ビルド 12527.20040)*</span><span class="sxs-lookup"><span data-stu-id="40624-1581">*Version 2002 (Build 12527.20040)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="40624-1583">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="40624-1583">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="40624-1584">Access</span><span class="sxs-lookup"><span data-stu-id="40624-1584">Access</span></span>

- <span data-ttu-id="40624-1585">**クエリ デザイナー、SQL ビュー、およびリレーションシップ ウィンドウでの作業効率の向上:** テーブルを右クリックして、テーブルを開き、デザインし、サイズを変更し、非表示にします。</span><span class="sxs-lookup"><span data-stu-id="40624-1585">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="40624-1586">SQL ビューでテキストを検索および置換します。</span><span class="sxs-lookup"><span data-stu-id="40624-1586">Search and replace text in SQL View.</span></span> <span data-ttu-id="40624-1587">リレーションシップ ウィンドウ内の複数のテーブルを選択します。</span><span class="sxs-lookup"><span data-stu-id="40624-1587">Select multiple tables in the Relationships window.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="40624-1590">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="40624-1590">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="40624-1591">Access</span><span class="sxs-lookup"><span data-stu-id="40624-1591">Access</span></span>

- <span data-ttu-id="40624-1592">この更新プログラムでは、ADODB を使用する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="40624-1592">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="40624-1593">VB コードのれコーター オブジェクトがエラーを誤って報告することがあります。</span><span class="sxs-lookup"><span data-stu-id="40624-1593">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="40624-1594">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1594">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="40624-1595">Excel</span><span class="sxs-lookup"><span data-stu-id="40624-1595">Excel</span></span>

- <span data-ttu-id="40624-1596">動的配列で [区切り位置] を使用すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1596">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="40624-1597">Outlook</span><span class="sxs-lookup"><span data-stu-id="40624-1597">Outlook</span></span>

- <span data-ttu-id="40624-1598">月ビューで予定表をスクロールしても以前の予定表のイベントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1598">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="40624-1599">Citrix 環境で 30 件を超える予定表を表示したときにクラッシュする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="40624-1599">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="40624-1600">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="40624-1600">PowerPoint</span></span>

- <span data-ttu-id="40624-1601">ファイルを閉じた後、実行中のイベント ハンドラーがある場合、PowerPoint がファイルを Presentations コレクションからすぐに削除しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1601">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="40624-1602">したがって、オブジェクト モデルによって報告される開いているプレゼンテーションの数は正しくなく、PowerPoint のシャットダウンは防止されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1602">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="40624-1603">蛍光ペンの問題を修正しました。暗い蛍光ペン色の白いテキストはグレースケールで黒として印刷されます。</span><span class="sxs-lookup"><span data-stu-id="40624-1603">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="40624-1604">Word</span><span class="sxs-lookup"><span data-stu-id="40624-1604">Word</span></span>

- <span data-ttu-id="40624-1605">目次を更新してスクロールすると、ドキュメント上に灰色の領域が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="40624-1605">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="40624-1606">ドキュメントが共同編集されている場合、ルート コメントのドラフト バージョンが保持されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1606">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="40624-1607">コメント カード間を行き来すると、最初に選択されたコメントが選択の強調表示で表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1607">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="40624-1608">コメントが書き込まれたが投稿されず、ユーザーがファイルを保存しようとした場合、「参照」を使用してファイルを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1608">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="40624-1609">SlideTrack を有効にしてコメント ウィンドウを閉じると、Ctrl + Alt + M でコメント ウィンドウが開かない場合があります。</span><span class="sxs-lookup"><span data-stu-id="40624-1609">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="40624-1610">@メンションをテーブルに追加すると、「このドキュメントのテーブルが破損しました」というエラー メッセージが生成される場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="40624-1610">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="40624-1611">Office スイート</span><span class="sxs-lookup"><span data-stu-id="40624-1611">Office Suite</span></span>

- <span data-ttu-id="40624-1612">Norway Nynorsk (nn-no) 校正ツール パッケージが正しくインストールされなかった場合がある問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="40624-1612">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


[//]: # (管理センターのメタデータのコンテンツを変更しないでください。開始)
[//]: # (|Win32|DevMain|Insiders| |16.0.13929.20016|version-2104-april-02|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13919.20002|version-2104-march-26|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13913.20000|version-2104-march-19|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13906.20000|version-2104-march-12|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13901.20036|version-2103-march-05|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13819.20006|version-2103-february-26|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13811.20002|version-2103-february-19|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13806.20000|version-2103-february-12|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13801.20004|version-2102-february-05|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13721.20008|version-2102-january-29|)
[//]: # (管理センターのメタデータのコンテンツ エンドを変更しないでください)