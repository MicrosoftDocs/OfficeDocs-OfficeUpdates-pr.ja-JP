---
title: 2020 年の毎月のチャネル リリースのリリース ノート
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Microsoft 365 Apps 用の 2020 年の月次チャネル リリースのリリース ノートを IT 担当者に提供します
ms.openlocfilehash: 5580335c0736379ad74b9487954d21d98824c2be
ms.sourcegitcommit: bb2e1868f43693fe085ba9080401e6f8137c8a9e
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/27/2020
ms.locfileid: "43907923"
---
# <a name="release-notes-for-monthly-channel-releases-in-2020"></a><span data-ttu-id="e2dc3-103">2020 年の毎月のチャネル リリースのリリース ノート</span><span class="sxs-lookup"><span data-stu-id="e2dc3-103">Release notes for Monthly Channel releases in 2020</span></span>

<span data-ttu-id="e2dc3-104">このリリース ノートには、2020 年の月次チャネルの更新プログラムに含まれる新機能と、セキュリティ以外の更新プログラムに関する情報が記載されています。対象となるのは、Microsoft 365 Apps for enterprise、Microsoft 365 Apps for business、および Project と Visio のデスクトップ アプリのサブスクリプション版です。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-104">These release notes provide information about new features and non-security updates that are included in Monthly Channel updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

 > [!NOTE]
>
>- <span data-ttu-id="e2dc3-105">Microsoft では多くの場合、一定期間にわたって毎月、機能 (および場合によっては修正プログラム) を展開します。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-105">We often roll out features (and sometimes even fixes) to Monthly over a period of time.</span></span>  <span data-ttu-id="e2dc3-106">ここで説明した内容がすぐに表示されない場合は、間もなく利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-106">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="e2dc3-107">詳細情報</span><span class="sxs-lookup"><span data-stu-id="e2dc3-107">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)




[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-april-15"></a><span data-ttu-id="e2dc3-110">バージョン 2003: 4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="e2dc3-110">Version 2003: April 15</span></span>
<span data-ttu-id="e2dc3-111">*バージョン 2003 (ビルド 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="e2dc3-111">*Version 2003 (Build 12624.20466)*</span></span>
* <span data-ttu-id="e2dc3-112">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-112">Various bugs and performance fixes.</span></span>

## <a name="version-2003-april-14"></a><span data-ttu-id="e2dc3-113">バージョン 2003: 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="e2dc3-113">Version 2003: April 14</span></span>
<span data-ttu-id="e2dc3-114">*バージョン 2003 (ビルド 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="e2dc3-114">*Version 2003 (Build 12624.20442)*</span></span>

<span data-ttu-id="e2dc3-115">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="e2dc3-115">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="e2dc3-117">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="e2dc3-117">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="e2dc3-118">Excel</span><span class="sxs-lookup"><span data-stu-id="e2dc3-118">Excel</span></span>

- <span data-ttu-id="e2dc3-119">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-119">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="e2dc3-120">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2dc3-120">Outlook</span></span>

- <span data-ttu-id="e2dc3-121">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-121">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="e2dc3-122">Project</span><span class="sxs-lookup"><span data-stu-id="e2dc3-122">Project</span></span>

- <span data-ttu-id="e2dc3-123">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-123">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

### <a name="word"></a><span data-ttu-id="e2dc3-124">Word</span><span class="sxs-lookup"><span data-stu-id="e2dc3-124">Word</span></span>

- <span data-ttu-id="e2dc3-125">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-125">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-31"></a><span data-ttu-id="e2dc3-127">バージョン 2003: 3 月 31 日</span><span class="sxs-lookup"><span data-stu-id="e2dc3-127">Version 2003: March 31</span></span>
<span data-ttu-id="e2dc3-128">*バージョン 2003 (ビルド 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="e2dc3-128">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="e2dc3-130">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="e2dc3-130">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="e2dc3-131">OneNote</span><span class="sxs-lookup"><span data-stu-id="e2dc3-131">OneNote</span></span>

- <span data-ttu-id="e2dc3-132">ごみ箱へのページの移動を一時的に無効にすることにより、同期とサーバーの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-132">Improved sync and server stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="e2dc3-133">代わりに、ページを削除するユーザーにはページを完全に削除するかどうかを確認するダイアログが表示されます。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-133">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>

- <span data-ttu-id="e2dc3-134">全世界でサービス使用量が高まった際に、同期とサービスの可用性を改善できる、Microsoft OneNote の一時的な調整に関して、情報バーを介してユーザーに通知します。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-134">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

- <span data-ttu-id="e2dc3-135">ページのバージョン履歴を作成する頻度を一時的に変更することで、同期およびサービスの安定性が改善されます。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-135">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>

### <a name="project"></a><span data-ttu-id="e2dc3-136">Project</span><span class="sxs-lookup"><span data-stu-id="e2dc3-136">Project</span></span>

- <span data-ttu-id="e2dc3-137">実績作業時間の保護設定を有効にしているときに、ユーザーがタイムフェーズの基準作業時間を入力できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-137">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-25"></a><span data-ttu-id="e2dc3-139">バージョン 2003: 3 月 25 日</span><span class="sxs-lookup"><span data-stu-id="e2dc3-139">Version 2003: March 25</span></span>
<span data-ttu-id="e2dc3-140">*バージョン 2003 (ビルド 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="e2dc3-140">*Version 2003 (Build 12624.20320)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="e2dc3-142">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="e2dc3-142">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="e2dc3-143">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2dc3-143">Outlook</span></span>

- <span data-ttu-id="e2dc3-144">**所有しているグループにメールをドラッグ:** メッセージや会話を受信トレイからドラッグして移動し、コピーします。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-144">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="e2dc3-145">ドラッグしたメッセージは、すべてのグループ メンバーと共有されます。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-145">Messages you drag will be shared with all group members.</span></span>

- <span data-ttu-id="e2dc3-146">**キャプティブ WiFi ネットワークの新しいエクスペリエンス**: サインインに Web ページを必要とする WiFi ネットワークに参加したことはありませんか ?</span><span class="sxs-lookup"><span data-stu-id="e2dc3-146">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="e2dc3-147">Outlook はこれを検出し、接続を支援します。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-147">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="e2dc3-148">Word</span><span class="sxs-lookup"><span data-stu-id="e2dc3-148">Word</span></span>

- <span data-ttu-id="e2dc3-149">**他のユーザーがすばやく変更を確認する:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-149">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="e2dc3-150">Office スイート</span><span class="sxs-lookup"><span data-stu-id="e2dc3-150">Office Suite</span></span>

- <span data-ttu-id="e2dc3-151">**秘密度ラベル:** カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-151">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="e2dc3-154">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="e2dc3-154">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="e2dc3-155">Excel</span><span class="sxs-lookup"><span data-stu-id="e2dc3-155">Excel</span></span>

- <span data-ttu-id="e2dc3-156">Word または PowerPoint に埋め込まれたブックをもう一度開くと、場合によっては Excel がクラッシュする可能性があります。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-156">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="e2dc3-157">ソース ブックが閉じていると、外部リンクが塗りつぶし時に更新されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-157">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="e2dc3-158">テンプレートからグラフを作成するときに発生するパフォーマンスの問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-158">Addressed a performance issue when creating charts from templates.</span></span>

### <a name="onenote"></a><span data-ttu-id="e2dc3-159">OneNote</span><span class="sxs-lookup"><span data-stu-id="e2dc3-159">OneNote</span></span>

- <span data-ttu-id="e2dc3-160">新しい埋め込み添付ファイルの最大許容サイズを一時的に 50 MB に削減することにより、同期とサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-160">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB.</span></span> <span data-ttu-id="e2dc3-161">この制限を超えるファイルの場合、ユーザーは OneDrive にファイルをアップロードして、OneNote にリンクを挿入することができます。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-161">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="e2dc3-162">OneNote 2016 でアプリ内動画のレコーディングを一時的に無効にすることで、同期およびサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-162">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="e2dc3-163">ローカルのノートブックはこの影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-163">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="e2dc3-164">OneNote 2016 で同期頻度を一時的に調整することで、同期およびサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-164">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

### <a name="outlook"></a><span data-ttu-id="e2dc3-165">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2dc3-165">Outlook</span></span>

- <span data-ttu-id="e2dc3-166">終了後にタスク マネージャーに Outlook プロセスが残っているという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-166">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e2dc3-167">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2dc3-167">PowerPoint</span></span>

- <span data-ttu-id="e2dc3-168">コピーと貼り付けのシナリオを改善しました。PowerPoint スライドでの図形のコピーと、ループ内の他のスライドへの貼り付けが例外で失敗する場合があります。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-168">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="e2dc3-169">Project</span><span class="sxs-lookup"><span data-stu-id="e2dc3-169">Project</span></span>

- <span data-ttu-id="e2dc3-170">[無効化] ボタンを介してタスクが非アクティブ化/アクティブ化された場合に、ProjectBeforeTaskChange イベントが検出しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-170">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="e2dc3-171">以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-171">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="e2dc3-172">タスクを完了とマークした後に、タスクの達成率が 100% 完了より小さい値に誤って変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-172">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="e2dc3-173">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-173">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-march-10"></a><span data-ttu-id="e2dc3-175">バージョン 2002: 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="e2dc3-175">Version 2002: March 10</span></span>
<span data-ttu-id="e2dc3-176">*バージョン 2002 (ビルド 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="e2dc3-176">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="e2dc3-177">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="e2dc3-177">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="e2dc3-179">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="e2dc3-179">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="e2dc3-180">Project</span><span class="sxs-lookup"><span data-stu-id="e2dc3-180">Project</span></span>

- <div><span data-ttu-id="e2dc3-181"><span style="display:inline !important;">OnUndoOrRedo イベントが、&nbsp;</span><span style="box-sizing:border-box;font-size:13.3333px;display:inline !important;">OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span></span><span class="sxs-lookup"><span data-stu-id="e2dc3-181"><span style="display:inline !important;">Fixed an issue where the OnUndoOrRedo event doesn't fire&nbsp;</span><span style="box-sizing:border-box;font-size:13.3333px;display:inline !important;">without first running the OpenUndoTransaction method.</span></span></span><br></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-march-01"></a><span data-ttu-id="e2dc3-183">バージョン 2002: 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="e2dc3-183">Version 2002: March 01</span></span>
<span data-ttu-id="e2dc3-184">*バージョン 2002 (ビルド 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="e2dc3-184">*Version 2002 (Build 12527.20242)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="e2dc3-186">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="e2dc3-186">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="e2dc3-187">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2dc3-187">Outlook</span></span>

- <div><span data-ttu-id="e2dc3-188">サードパーティ製アプリケーションがメールを送信できない原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-188">Addresses an issue that caused third party applications to be unable to send email.</span></span></div>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2002-february-25"></a><span data-ttu-id="e2dc3-190">バージョン 2002: 2 月 25 日</span><span class="sxs-lookup"><span data-stu-id="e2dc3-190">Version 2002: February 25</span></span>
<span data-ttu-id="e2dc3-191">*バージョン 2002 (ビルド 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="e2dc3-191">*Version 2002 (Build 12527.20194)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="e2dc3-193">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="e2dc3-193">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="e2dc3-194">Excel</span><span class="sxs-lookup"><span data-stu-id="e2dc3-194">Excel</span></span>

- <span data-ttu-id="e2dc3-195">**ユーザーは Word および Excel のオブジェクトを SVG として保存できるようになりました:** ユーザーはグラフ、図形、インク、アイコン、画像などのオブジェクトを SVG として保存できます [詳細情報](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)</span><span class="sxs-lookup"><span data-stu-id="e2dc3-195">**Users now have the ability to save objects in Word and Excel as an SVG:** Users can save objects such as charts, shapes, ink, icons, pictures and more as an SVG. [Learn more](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)</span></span>

- <span data-ttu-id="e2dc3-196">**ブックの統計情報:** セル、数式、グラフ、テーブル...これらをお客様に代わってカウントします。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-196">**Workbook Statistics:** Cells, formulas, charts, tables... We count them so you don't have to.</span></span>

- <span data-ttu-id="e2dc3-197">**クエリ エディターでのデータ プロファイリング**: 列のデータを一目で分析し、エラーと空の値を識別し、配布ヒストグラムなどを確認します。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-197">**Data Profiling in Query Editor:** Get at-a-glance analysis of the data in your columns, identify error and empty values, see distribution histograms and more.</span></span>

### <a name="word"></a><span data-ttu-id="e2dc3-198">Word</span><span class="sxs-lookup"><span data-stu-id="e2dc3-198">Word</span></span>

- <span data-ttu-id="e2dc3-199">**ユーザーは Word および Excel のオブジェクトを SVG として保存できるようになりました:** ユーザーはグラフ、図形、インク、アイコン、画像などのオブジェクトを SVG として保存できます [詳細情報](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)</span><span class="sxs-lookup"><span data-stu-id="e2dc3-199">**Users now have the ability to save objects in Word and Excel as an SVG:** Users can save objects such as charts, shapes, ink, icons, pictures and more as an SVG. [Learn more](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)</span></span>



[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="e2dc3-202">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="e2dc3-202">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="e2dc3-203">Excel</span><span class="sxs-lookup"><span data-stu-id="e2dc3-203">Excel</span></span>

- <span data-ttu-id="e2dc3-204">CUBEVALUE 関数が間違った結果を返すことがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-204">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="e2dc3-205">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2dc3-205">Outlook</span></span>

- <span data-ttu-id="e2dc3-206">会議の [場所] フィールドにあるコンマがセミコロンになる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-206">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="e2dc3-207">複数のウィンドウで同じアイテムを表示するとクラッシュする場合がある問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-207">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="e2dc3-208">フラグ付きアイテムの強調表示を無効にするオプションが一部のシナリオで無視される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-208">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="e2dc3-209">同期のスライダーが小さい設定に設定されている場合でも、Outlook で予期せずすべてのメールが同期される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-209">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>


- <span data-ttu-id="e2dc3-210">黒のテーマを持つユーザーが [&quot;差出人&quot;] ドロップダウンを表示すると、白色の背景に白いテキストが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-210">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span>


- <span data-ttu-id="e2dc3-211">この変更により、メッセージ ヘッダーに複数行の件名を表示できる機能が復元されます。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-211">This change restores the ability to view multi-line subjects in the message header.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2001-february-19"></a><span data-ttu-id="e2dc3-213">バージョン 2001: 2 月 19 日</span><span class="sxs-lookup"><span data-stu-id="e2dc3-213">Version 2001: February 19</span></span>
<span data-ttu-id="e2dc3-214">*バージョン 2001 (ビルド 12430.20288)*</span><span class="sxs-lookup"><span data-stu-id="e2dc3-214">*Version 2001 (Build 12430.20288)*</span></span>
* <span data-ttu-id="e2dc3-215">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-215">Various bugs and performance fixes.</span></span>

## <a name="version-2001-february-11"></a><span data-ttu-id="e2dc3-216">バージョン 2001: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="e2dc3-216">Version 2001: February 11</span></span>
<span data-ttu-id="e2dc3-217">*バージョン 2001 (ビルド 12430.20264)*</span><span class="sxs-lookup"><span data-stu-id="e2dc3-217">*Version 2001 (Build 12430.20264)*</span></span>

<span data-ttu-id="e2dc3-218">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="e2dc3-218">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="e2dc3-220">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="e2dc3-220">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="e2dc3-221">Access</span><span class="sxs-lookup"><span data-stu-id="e2dc3-221">Access</span></span>

- <span data-ttu-id="e2dc3-222">Access テンプレートは、データベース内の添付ファイル列のエラーを発生させることがなくなりました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-222">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="e2dc3-223">テンプレートのインスタンス化後に、データベースに添付ファイル フィールドを追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-223">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="e2dc3-224">Excel</span><span class="sxs-lookup"><span data-stu-id="e2dc3-224">Excel</span></span>

- <span data-ttu-id="e2dc3-225">コンテキスト メニューのコメント コマンドが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-225">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="e2dc3-226">スピル配列が含まれるセルで区切り位置を指定するとクラッシュが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-226">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


### <a name="outlook"></a><span data-ttu-id="e2dc3-227">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2dc3-227">Outlook</span></span>

- <span data-ttu-id="e2dc3-228">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-228">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="e2dc3-229">ユーザーがアカウントのセットアップをキャンセルするときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-229">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>


### <a name="project"></a><span data-ttu-id="e2dc3-230">Project</span><span class="sxs-lookup"><span data-stu-id="e2dc3-230">Project</span></span>

- <span data-ttu-id="e2dc3-231">作業時間固定タイプの達成率 100% のタスクで、達成率が誤って 100% 未満に計算される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-231">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="office-suite"></a><span data-ttu-id="e2dc3-232">Office スイート</span><span class="sxs-lookup"><span data-stu-id="e2dc3-232">Office Suite</span></span>

- <span data-ttu-id="e2dc3-233">この変更では、Intel Integrated GPU を使用するグラフィック アダプターに関して報告された問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-233">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2001-january-30"></a><span data-ttu-id="e2dc3-235">バージョン 2001: 1 月 30 日</span><span class="sxs-lookup"><span data-stu-id="e2dc3-235">Version 2001: January 30</span></span>
<span data-ttu-id="e2dc3-236">*バージョン 2001 (ビルド 12430.20184)*</span><span class="sxs-lookup"><span data-stu-id="e2dc3-236">*Version 2001 (Build 12430.20184)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="e2dc3-238">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="e2dc3-238">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="e2dc3-239">Excel</span><span class="sxs-lookup"><span data-stu-id="e2dc3-239">Excel</span></span>

- <span data-ttu-id="e2dc3-240">**すぐに読んで返信する**: ブックを開かずに、メールからコメントやメンションに直接返信します。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-240">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="e2dc3-241">**左を見て、右を見て... XLOOKUP をご利用いただけます!** XLOOKUP を使えば、表や範囲内で必要なものは何でも見つけられます。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-241">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="e2dc3-242">詳細情報</span><span class="sxs-lookup"><span data-stu-id="e2dc3-242">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)

### <a name="outlook"></a><span data-ttu-id="e2dc3-243">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2dc3-243">Outlook</span></span>

- <span data-ttu-id="e2dc3-244">**高度なグループ メールの設定:** この機能は、グループ ユーザーが受信トレイで受信/フォローするメールまたはイベントを、カスタマイズするのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-244">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="e2dc3-245">**グループの名前付けポリシー**: グループの名前付けポリシーを使用すると、IT 管理者は組織内のユーザーが作成するグループの名前の標準化と管理を行えます。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-245">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="e2dc3-246">管理者は、グループが作成される際に特定のプレフィックスとサフィックスをグループ名に追加することを要求できます。また、特定の単語の使用を禁止できます。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-246">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="e2dc3-247">これにより、グループ名での不適切な単語の使用を最小限に抑えられる他、ディレクトリ内のグループ名の記載を IT 管理者が管理できます。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-247">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="e2dc3-248">また、名前付けポリシーを使用することで、チーム サイトを展開する組織は、チーム サイトを部署ごとに分類できるようにもなります。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-248">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="word"></a><span data-ttu-id="e2dc3-249">Word</span><span class="sxs-lookup"><span data-stu-id="e2dc3-249">Word</span></span>

- <span data-ttu-id="e2dc3-250">**より安全なビデオ エクスペリエンス:** セキュリティの強化は、より安全なオンライン ビデオ エクスペリエンスを意味します。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-250">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="e2dc3-251">詳細情報</span><span class="sxs-lookup"><span data-stu-id="e2dc3-251">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="e2dc3-252">**インクのなげなわ:** [描画] タブのなげなわツールを使用すると、インクで描かれたオブジェクトを選択できます。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-252">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="e2dc3-253">個別のストロークまたは文字全体を選択できます。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-253">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="e2dc3-254">詳細情報</span><span class="sxs-lookup"><span data-stu-id="e2dc3-254">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="e2dc3-255">**図形を画像として保存する:** 簡単なクリック操作で図形、アイコン、その他のオブジェクトを画像ファイルとして保存し、別の場所で再利用することができます。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-255">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="e2dc3-256">詳細情報</span><span class="sxs-lookup"><span data-stu-id="e2dc3-256">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)




[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="e2dc3-259">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="e2dc3-259">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="e2dc3-260">Access</span><span class="sxs-lookup"><span data-stu-id="e2dc3-260">Access</span></span>

- <div><span data-ttu-id="e2dc3-261"><span style="display:inline !important;">この更新は、ADODB を使用する問題を修正します。 VB コードのレコーダー オブジェクトでエラーが誤って報告される場合があります。&nbsp;</span></span><span class="sxs-lookup"><span data-stu-id="e2dc3-261"><span style="display:inline !important;">This update fixes an issue where using an ADODB. Recorder object in VB code may incorrectly report an error.&nbsp;</span></span></span><br></div>


- <div style="box-sizing:border-box;"><span data-ttu-id="e2dc3-262"><span style="box-sizing:border-box;"><span style="background-color:rgba(255, 255, 255, 1);box-sizing:border-box;display:inline;">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span></span></span><span class="sxs-lookup"><span data-stu-id="e2dc3-262"><span style="box-sizing:border-box;"><span style="background-color:rgba(255, 255, 255, 1);box-sizing:border-box;display:inline;">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly</span></span></span></span></div>


### <a name="excel"></a><span data-ttu-id="e2dc3-263">Excel</span><span class="sxs-lookup"><span data-stu-id="e2dc3-263">Excel</span></span>

- <div><span data-ttu-id="e2dc3-264">署名の名前を変更したときにクラッシュする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-264">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span></div>


### <a name="outlook"></a><span data-ttu-id="e2dc3-265">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2dc3-265">Outlook</span></span>

- <div><span data-ttu-id="e2dc3-266">署名の名前を変更したときにクラッシュする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-266">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span></div>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1912-january-22"></a><span data-ttu-id="e2dc3-268">バージョン 1912: 1 月 22 日</span><span class="sxs-lookup"><span data-stu-id="e2dc3-268">Version 1912: January 22</span></span>
<span data-ttu-id="e2dc3-269">*バージョン 1912 (ビルド 12325.20344)*</span><span class="sxs-lookup"><span data-stu-id="e2dc3-269">*Version 1912 (Build 12325.20344)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="e2dc3-271">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="e2dc3-271">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="e2dc3-272">Access</span><span class="sxs-lookup"><span data-stu-id="e2dc3-272">Access</span></span>

- <div><span data-ttu-id="e2dc3-273">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-273">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly</span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1912-january-14"></a><span data-ttu-id="e2dc3-275">バージョン 1912: 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="e2dc3-275">Version 1912: January 14</span></span>
<span data-ttu-id="e2dc3-276">*バージョン 1912 (ビルド 12325.20298)*</span><span class="sxs-lookup"><span data-stu-id="e2dc3-276">*Version 1912 (Build 12325.20298)*</span></span>

<span data-ttu-id="e2dc3-277">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="e2dc3-277">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

## <a name="version-1912-january-08"></a><span data-ttu-id="e2dc3-278">バージョン 1912: 1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="e2dc3-278">Version 1912: January 08</span></span>
<span data-ttu-id="e2dc3-279">*バージョン 1912 (ビルド 12325.20288)*</span><span class="sxs-lookup"><span data-stu-id="e2dc3-279">*Version 1912 (Build 12325.20288)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="e2dc3-281">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="e2dc3-281">Feature updates</span></span>

### <a name="outlook"></a><span data-ttu-id="e2dc3-282">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2dc3-282">Outlook</span></span>

- <span data-ttu-id="e2dc3-283">**アクセシビリティ対応のメールを最も必要としている人に送信する:** Outlook では、メールのヒントが表示され、アクセシビリティ対応のコンテンツを必要とするユーザーに送信するときに、コンテンツがアクセシビリティ対応であることを確認できます</span><span class="sxs-lookup"><span data-stu-id="e2dc3-283">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e2dc3-284">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2dc3-284">PowerPoint</span></span>

- <span data-ttu-id="e2dc3-285">**プレゼンテーションの最適化:** アクセシビリティ チェックを使用すると、スクリーン リーダーを考慮に入れて、スライド上のオブジェクトを配置することができます。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-285">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="e2dc3-286">**簡単な GIF:** 1 つのスライド、1 つのフレーム。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-286">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="e2dc3-287">PowerPoint でループ GIF を簡単に作成できます。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-287">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="e2dc3-288">詳細情報</span><span class="sxs-lookup"><span data-stu-id="e2dc3-288">Learn more</span></span>](https://support.office.com/ja-JP/article/a598753e-92de-4f1b-8393-714db4d334b4)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="e2dc3-291">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="e2dc3-291">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="e2dc3-292">Excel</span><span class="sxs-lookup"><span data-stu-id="e2dc3-292">Excel</span></span>

- <span data-ttu-id="e2dc3-293">この変更は、ソフトウェア レンダリングを活用することにより、特定の Intel グラフィック ドライバーの問題を回避します。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-293">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

### <a name="outlook"></a><span data-ttu-id="e2dc3-294">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2dc3-294">Outlook</span></span>

- <span data-ttu-id="e2dc3-295">会議をクリアした後、会議の場所が予期せずに会議に追加される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-295">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="e2dc3-296">キーボード ショートカットを使用してメールボックス フォルダーを操作すると、ユーザーに顕著な遅延が発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-296">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="e2dc3-297">状況によっては、表示された SMTP アドレスと一致しないアドレスに送信されたメールがユーザーに表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-297">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="e2dc3-298">ユーザーがクラウド設定を取得する際に Outlook がフリーズする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-298">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

### <a name="word"></a><span data-ttu-id="e2dc3-299">Word</span><span class="sxs-lookup"><span data-stu-id="e2dc3-299">Word</span></span>

- <span data-ttu-id="e2dc3-300">文書パーツ オーガナイザーに無効なアラートが表示される場合があります。&quot;スタイル、文書パーツを変更しました。&quot;</span><span class="sxs-lookup"><span data-stu-id="e2dc3-300">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>

### <a name="office-suite"></a><span data-ttu-id="e2dc3-301">Office スイート</span><span class="sxs-lookup"><span data-stu-id="e2dc3-301">Office Suite</span></span>

- <span data-ttu-id="e2dc3-302">Office の更新プログラムが、意図したソース (ローカル共有、ネットワーク共有、構成マネージャー
で提供される場所など) からではなく、予期せずに Office CDN からファイルをダウンロードする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-302">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

> [!NOTE]
> <span data-ttu-id="e2dc3-304">Office の使用で問題がある場合は、[Microsoft の回答フォーラム](https://answers.microsoft.com/)に関するページまたは「[Microsoft Tech Community](https://techcommunity.microsoft.com/)」に質問を投稿するか、[サポート](https://support.microsoft.com/contactus)に問い合わせてサポートを受けることができます。</span><span class="sxs-lookup"><span data-stu-id="e2dc3-304">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
