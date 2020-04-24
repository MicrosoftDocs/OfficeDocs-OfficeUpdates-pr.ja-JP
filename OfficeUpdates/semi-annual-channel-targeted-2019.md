---
title: 2019 年の半期チャネル (対象指定) リリースのリリース ノート
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Office 365 ProPlus 用の 2019 年の半期チャネル (対象指定) リリースのリリース ノートを IT プロフェッショナルに提供します
ms.openlocfilehash: 750a20da1fc38b216957f13260bd504530b897fe
ms.sourcegitcommit: 4df4bbfe9328d36fdf801081598aadde77af8a9c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/23/2020
ms.locfileid: "43796123"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2019"></a><span data-ttu-id="8ae84-103">2019 年の半期チャネル (対象指定) リリースのリリース ノート</span><span class="sxs-lookup"><span data-stu-id="8ae84-103">Release notes for Semi-Annual Channel (Targeted) releases in 2019</span></span>

<span data-ttu-id="8ae84-104">これらのリリースノートには、Visio Pro for Office 365、Project Online Desktop Client、および Office 365 Business を含む、2019 年の Office 365 ProPlus の半期チャネル (対象指定) の更新プログラムに含まれる新機能およびセキュリティ以外の更新に関する情報が記載されています。</span><span class="sxs-lookup"><span data-stu-id="8ae84-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Channel (Targeted) updates to Office 365 ProPlus in 2019, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

> [!NOTE]
> - <span data-ttu-id="8ae84-105">多くの場合、機能 (場合によっては修正プログラムも) は、特定の期間にわたって半期チャネル (対象指定) にロールアウトされます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-105">We often roll out features (and sometimes even fixes) to Semi-Annual Channel (Targeted) over a period of time.</span></span> <span data-ttu-id="8ae84-106">ここで説明される内容がすぐに確認できなくても、間もなく利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="8ae84-106">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="8ae84-107">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-107">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
> - <span data-ttu-id="8ae84-108">Microsoft Teams は、バージョン 1902 以降の半期チャネル (対象指定) の新規インストールに含まれています。</span><span class="sxs-lookup"><span data-stu-id="8ae84-108">Microsoft Teams is included in new installations of Semi-Annual Channel(Targeted), starting with Version 1902.</span></span> <span data-ttu-id="8ae84-109">Teams は、バージョン 1908以降に更新されると、半期チャネル (対象指定) の既存のインストールに追加されます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-109">Teams will be added to existing installations of Semi-Annual Channel(Targeted) when those are updated to Version 1908 or later.</span></span> <span data-ttu-id="8ae84-110">詳細については、「[Office 365 ProPlus で Microsoft Teams を展開する](https://docs.microsoft.com/DeployOffice/teams-install)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="8ae84-110">For more information, see [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/teams-install).</span></span>

## <a name="version-1908-december-10"></a><span data-ttu-id="8ae84-111">バージョン 1908: 12 月 10 日</span><span class="sxs-lookup"><span data-stu-id="8ae84-111">Version 1908: December 10</span></span>
<span data-ttu-id="8ae84-112">*バージョン 1908 (ビルド 11929.20516)*</span><span class="sxs-lookup"><span data-stu-id="8ae84-112">*Version 1908 (Build 11929.20516)*</span></span>

<span data-ttu-id="8ae84-113">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8ae84-113">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="8ae84-115">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="8ae84-115">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="8ae84-116">Access</span><span class="sxs-lookup"><span data-stu-id="8ae84-116">Access</span></span>

- <span data-ttu-id="8ae84-117">リモート テーブル (SQL Server テーブルなど) への参照を含むユニオン クエリにより Access が閉じて再起動する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-117">Fixed an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="8ae84-118">Sum などの集計が結果を整数値に切り捨てる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-118">Fixed an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

### <a name="excel"></a><span data-ttu-id="8ae84-119">Excel</span><span class="sxs-lookup"><span data-stu-id="8ae84-119">Excel</span></span>

- <span data-ttu-id="8ae84-120">スクロール後にセルを選択すると間違ったセルが選択されることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-120">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="8ae84-121">OLAP ピボットテーブルのフィルターがキューブから削除された値に設定された場合の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-121">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="8ae84-122">この変更は、ソフトウェア レンダリングを活用することにより、特定の Intel グラフィック ドライバーの問題を回避します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-122">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="8ae84-123">Lookup 関数がエラーを返す問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-123">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="8ae84-124">結合されたセルで列を削除するパフォーマンスが大幅に改善されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-124">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="8ae84-125">最小化されたウィンドウをアクティブにするマクロ実行時エラーの原因となる問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-125">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

### <a name="outlook"></a><span data-ttu-id="8ae84-126">Outlook</span><span class="sxs-lookup"><span data-stu-id="8ae84-126">Outlook</span></span>

- <span data-ttu-id="8ae84-127">SMIME アルゴリズムの選択に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-127">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="8ae84-128">ユーザーが [ルール] ダイアログを開くと、「&quot;このコンピューターのルールは、Microsoft Exchange のルールと異なります&quot;」というメッセージが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-128">Addressed an issue that caused users to see a &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="8ae84-129">Web アドインがデジタル著作権管理 (DRM) メッセージにアクセスするべきではないときにアクセスする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-129">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

### <a name="word"></a><span data-ttu-id="8ae84-130">Word</span><span class="sxs-lookup"><span data-stu-id="8ae84-130">Word</span></span>

- <span data-ttu-id="8ae84-131">無限ループになることがあるトラック変更の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-131">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8ae84-132">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8ae84-132">Office Suite</span></span>

- <span data-ttu-id="8ae84-133">PowerPoint の垂直テキストボックスで半角カタカナ文字が適切に回転しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-133">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="8ae84-134">Office の更新プログラムが、意図したソース (ローカル共有、ネットワーク共有、構成マネージャー
で提供される場所など) からではなく、予期せずに Office CDN からファイルをダウンロードする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-134">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="8ae84-135">Office ユーザーのセキュリティを保護するために、Microsoft Office の更新プログラムは SHA-2 アルゴリズムのみを使用して署名されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-135">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-november-22"></a><span data-ttu-id="8ae84-137">バージョン 1908: 11 月 22 日</span><span class="sxs-lookup"><span data-stu-id="8ae84-137">Version 1908: November 22</span></span>
<span data-ttu-id="8ae84-138">*バージョン 1908 (ビルド 11929.20494)*</span><span class="sxs-lookup"><span data-stu-id="8ae84-138">*Version 1908 (Build 11929.20494)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="8ae84-140">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="8ae84-140">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="8ae84-141">Access</span><span class="sxs-lookup"><span data-stu-id="8ae84-141">Access</span></span>

- <span data-ttu-id="8ae84-142">更新クエリを実行すると "クエリが破損しています" という誤ったエラー メッセージが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-142">Fixed an issue where running an Update query would incorrectly give an error message: "Query is corrupt".</span></span>

### <a name="excel"></a><span data-ttu-id="8ae84-143">Excel</span><span class="sxs-lookup"><span data-stu-id="8ae84-143">Excel</span></span>

- <span data-ttu-id="8ae84-144">ファイルに広範な条件付き書式が設定されている場合に、[フォントの色] ボタンをクリックするとパフォーマンスが低下する問題。</span><span class="sxs-lookup"><span data-stu-id="8ae84-144">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="8ae84-145">印刷プレビューの印刷範囲が正しくないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-145">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="8ae84-146">信頼されていないネットワーク共有から保護されたファイルを編集する際に、Excel にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="8ae84-146">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="8ae84-147">ブックが開かれていない状態で最近使用したファイルを検索する際にクラッシュが発生する可能性がある問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-147">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

### <a name="outlook"></a><span data-ttu-id="8ae84-148">Outlook</span><span class="sxs-lookup"><span data-stu-id="8ae84-148">Outlook</span></span>

- <span data-ttu-id="8ae84-149">アカウント作成コンテキストからサポートに連絡しようとすると、ユーザーに [&quot;OK&quot;] ボタンのある空のメッセージ ボックスが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-149">Addressed an issue that caused users to see an empty message box with an &quot;OK&quot; button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="8ae84-150">UPN 経由で自動検出の認証プロンプトに提供される電子メール アカウントの方を選択するために、ポリシーを管理者が有効にできるよう変更が行われました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-150">Made a change that allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="8ae84-151">既定では、使用可能な場合に、自動検出ではアカウント UPN の方が選択されます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-151">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="8ae84-152">最新のグループに対し、検索の失敗がユーザーに表示される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-152">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="8ae84-153">&quot;不在着信した会話&quot; メッセージのルールを作成しようとするときに、クラッシュを発生させる原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-153">Addressed an issue that caused users to experience a crash when attempting to create a rule from a &quot;Missed Conversation&quot; message.</span></span>

- <span data-ttu-id="8ae84-154">最新のグループに対し、検索の失敗がユーザーに表示される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-154">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

### <a name="word"></a><span data-ttu-id="8ae84-155">Word</span><span class="sxs-lookup"><span data-stu-id="8ae84-155">Word</span></span>

- <span data-ttu-id="8ae84-156">Deskjet プリンターへの印刷時にスケーリングの問題を引き起こす可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-156">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8ae84-157">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8ae84-157">Office Suite</span></span>

- <span data-ttu-id="8ae84-158">オンライン プレゼンテーションを行おうとするときに、PowerPoint ユーザーにエラーが発生しないように問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-158">Fixed an issue to prevent PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="8ae84-159">レジストリ整合性に関する Office 更新プロセスの信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-159">Improved reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="8ae84-160">従量制課金ネットワークで更新プログラムが予期せずブロックされる可能性があるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-160">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="8ae84-161">相対期限が初めて設定されるときのみ機能するところの ODT と GPO の更新期限の設定に関する問題が修正されました。修正により、2 回目以降の更新プログラムに相対期限を使用することができます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-161">Fixed an issue in ODT and GPO Updae Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-november-12"></a><span data-ttu-id="8ae84-163">バージョン 1908: 11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="8ae84-163">Version 1908: November 12</span></span>
<span data-ttu-id="8ae84-164">*バージョン 1908 (ビルド 11929.20436)*</span><span class="sxs-lookup"><span data-stu-id="8ae84-164">*Version 1908 (Build 11929.20436)*</span></span>

<span data-ttu-id="8ae84-165">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8ae84-165">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="8ae84-167">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="8ae84-167">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="8ae84-168">Excel</span><span class="sxs-lookup"><span data-stu-id="8ae84-168">Excel</span></span>

- <span data-ttu-id="8ae84-169">グラフ テンプレートを使用してグラフを挿入する場合に、プレビューで正しい色が使用されるよう修正します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-169">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>
- <span data-ttu-id="8ae84-170">シリーズ コレクションを変更するときに、散布図が適切にレンダリングされない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-170">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>
- <span data-ttu-id="8ae84-171">実行中のマクロでカスタム プロパティを変更すると、共同編集の中断を引き起こす問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-171">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>
- <span data-ttu-id="8ae84-172">非同期のユーザー定義関数が同期して実行されるパフォーマンスの問題を解決ました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-172">We resolved an performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>
- <span data-ttu-id="8ae84-173">色によるフィルタリングのパフォーマンスが大幅に向上しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-173">We have significantly improved the performance of filtering by color.</span></span>
- <span data-ttu-id="8ae84-174">Office 現在のバージョンで開いた場合に Excel の停止を引き起こす可能性がある、Office の以前のバージョンで作成されるブックの問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-174">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>
- <span data-ttu-id="8ae84-175">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-175">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

### <a name="outlook"></a><span data-ttu-id="8ae84-176">Outlook</span><span class="sxs-lookup"><span data-stu-id="8ae84-176">Outlook</span></span>

- <span data-ttu-id="8ae84-177">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-177">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>
- <span data-ttu-id="8ae84-178">プライマリ予定表からグループ予定表にアイテムをコピーするときに、ユーザーに権限エラーが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-178">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>
- <span data-ttu-id="8ae84-179">非常に長い Outlook セッションでメモリ リークが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-179">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>
- <span data-ttu-id="8ae84-180">特定のセーフリンクを操作すると、Outlook でユーザーにエラーが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-180">Addressed an issue that would cause users to experience a failure in Outlook when interacting with certain safelinks.</span></span>
- <span data-ttu-id="8ae84-181">一部の AutoDiscover の応答の処理中にユーザーにエラーが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-181">Addressed an issue that caused users to experience a failure when processing some AutoDiscover responses.</span></span>
- <span data-ttu-id="8ae84-182">一部のユーザーに、セカンダリ Exchange アカウントを追加するときに作成された重複した特別なフォルダーが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-182">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>
- <span data-ttu-id="8ae84-183">検索に関するフィードバックのエクスペリエンスでハングアップする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-183">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8ae84-184">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8ae84-184">PowerPoint</span></span>

- <span data-ttu-id="8ae84-185">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-185">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span></div>
- <span data-ttu-id="8ae84-186">信頼性の修正: サード パーティのアドインが PowerPoint を失敗させることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-186">Reliability fix: Fixed an issue where third party add-in might cause PowerPoint to fail.</span></span>

### <a name="project"></a><span data-ttu-id="8ae84-187">Project</span><span class="sxs-lookup"><span data-stu-id="8ae84-187">Project</span></span>

- <span data-ttu-id="8ae84-188">[すべて平準化] コマンドがリソースの割り当て超過を適切に解決していなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-188">Fixed an issue where the Level All command wasn't properly resolving a resource overallocation.</span></span>
- <span data-ttu-id="8ae84-189">タスクの作業がゼロの割り当てがある場合、タスクに完了のマークを付けることができず、常に 99％ で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-189">Fixed an issue where if you have an assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>
- <span data-ttu-id="8ae84-190">読み取り専用のプロジェクトを開いたときに複数のメッセージを取得する可能性があるという問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-190">Identified an issue where users could get several messages when opening a read-only project.</span></span>

### <a name="word"></a><span data-ttu-id="8ae84-191">Word</span><span class="sxs-lookup"><span data-stu-id="8ae84-191">Word</span></span>

- <span data-ttu-id="8ae84-192">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-192">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>
- <span data-ttu-id="8ae84-193">シャットダウン時にアプリがハングアップすることがあるさまざまな問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-193">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="8ae84-194">特定のアドインに関連する問題も修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-194">Also fixed certain add-in related failures.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8ae84-195">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8ae84-195">Office Suite</span></span>

- <span data-ttu-id="8ae84-196">サード パーティ製プラグインのテキスト ボックスと図形の AutoFit に関連する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-196">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="october-15"></a><span data-ttu-id="8ae84-198">10 月 15 日</span><span class="sxs-lookup"><span data-stu-id="8ae84-198">October 15</span></span>

### <a name="non-security-updates"></a><span data-ttu-id="8ae84-199">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-199">Non-security updates</span></span>

### <a name="office-suite"></a><span data-ttu-id="8ae84-200">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8ae84-200">Office Suite</span></span>
- <span data-ttu-id="8ae84-201">16.0.11929.20396 よりも古いビルドで 2019 年 10 月 14 日に投稿された保存の問題を解決するために、一時的に [クラウド保存] ダイアログを無効にしました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-201">We have temporarily disabled the Cloud Save dialog to address the saving issue we posted on October 14, 2019 for builds older than 16.0.11929.20396.</span></span> <span data-ttu-id="8ae84-202">この機能は、まもなく有効になります。</span><span class="sxs-lookup"><span data-stu-id="8ae84-202">This feature will be re-enabled soon.</span></span>

## <a name="version-1908-october-14"></a><span data-ttu-id="8ae84-203">バージョン 1908: 10 月 14 日</span><span class="sxs-lookup"><span data-stu-id="8ae84-203">Version 1908: October 14</span></span>
<span data-ttu-id="8ae84-204">*バージョン 1908 (ビルド 11929.20396)*</span><span class="sxs-lookup"><span data-stu-id="8ae84-204">*Version 1908 (Build 11929.20396)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="8ae84-206">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-206">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="8ae84-207">Excel</span><span class="sxs-lookup"><span data-stu-id="8ae84-207">Excel</span></span>

- <div><span data-ttu-id="8ae84-208">最初の項目を検索した後に、ダイアログでフォーカスが位置づけられていた場所を変更する検索と置換についての問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-208">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span></div>

### <a name="office-suite"></a><span data-ttu-id="8ae84-209">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8ae84-209">Office Suite</span></span>

- <span data-ttu-id="8ae84-210">16.0.11929.20396 よりも古いビルドでユーザーが Word、Excel、および PowerPoint 2019 のドキュメントを保存できなくなるという問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-210">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint 2019 documents for builds older than 16.0.11929.20396.</span></span>  <span data-ttu-id="8ae84-211">この問題は、[保存] アイコンをクリックしたり Ctrl キーを押しながら S キーを押したりした後に、新しいファイルを作成して [名前を付けて保存] ダイアログを表示するユーザーに影響を与えます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-211">This issue affects users that create a new file and bring up the “Save As” dialog after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="8ae84-212">特定の状況で、更新後に Office ショートカットが消えてしまう場合があるという問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-212">Resolved an issue where in certain circumstances, Office shortcuts may disappear following an update.</span></span>  <span data-ttu-id="8ae84-213">この更新プログラムでは、Office ショートカットを公開するときの信頼性を向上します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-213">This update improves reliability when publishing of Office shortcuts.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-october-08"></a><span data-ttu-id="8ae84-215">バージョン 1908: 10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="8ae84-215">Version 1908: October 08</span></span>
<span data-ttu-id="8ae84-216">*バージョン 1908 (ビルド 11929.20388)*</span><span class="sxs-lookup"><span data-stu-id="8ae84-216">*Version 1908 (Build 11929.20388)*</span></span>

<span data-ttu-id="8ae84-217">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8ae84-217">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="8ae84-219">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-219">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="8ae84-220">Excel</span><span class="sxs-lookup"><span data-stu-id="8ae84-220">Excel</span></span>

- <span data-ttu-id="8ae84-221">一部の保護されたシートにハイパーリンクが貼り付けられない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-221">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="8ae84-222">アドイン マネジャーで参照するときに、16 個以上のアドインを表示できる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-222">Fixed an issue to enable more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="8ae84-223">Win32 クライアントの [アイデア] ボタンをクリックしてアドインを読み込むときにエラーが発生するという Excel のアイデア機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-223">Fixed issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="8ae84-224">Outlook</span><span class="sxs-lookup"><span data-stu-id="8ae84-224">Outlook</span></span>

- <span data-ttu-id="8ae84-225">一部の safelinks に対して簡易的なホバーの URL が正しく表示されなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-225">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="8ae84-226">Python による添付ファイルもブロックされるよう、Outlook の添付ファイルのブロック ロジックを更新しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-226">Updated the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="8ae84-227">ユーザーが Outlook プロセスでメモリ リークを観測する原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-227">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8ae84-228">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8ae84-228">PowerPoint</span></span>

- <span data-ttu-id="8ae84-229">PowerPoint での共同編集とオフライン編集の両方を含むセッションでデータの損失を引き起こす可能性のある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-229">Fixed an issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8ae84-230">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8ae84-230">Office Suite</span></span>

- <span data-ttu-id="8ae84-231">ユーザーがファイルを開くときに発生する可能性のあるクラッシュの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-231">Fixed an issue for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="8ae84-232">Backstage の Info Place のスラブにアクセシビリティ情報が表示されていない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-232">Fixed an issue where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="8ae84-233">以前に中断された可能性のあるダウンロードを再開することにより、Office の更新プログラムをダウンロードするときの信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-233">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="8ae84-234">Office ユーザーのセキュリティを保護するために、Microsoft Office の更新プログラムは SHA-2 アルゴリズムのみを使用して署名されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-234">To protect Office customer’s security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-september-10"></a><span data-ttu-id="8ae84-236">バージョン 1908: 9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="8ae84-236">Version 1908: September 10</span></span>
<span data-ttu-id="8ae84-237">*バージョン 1908 (ビルド 11929.20300)*</span><span class="sxs-lookup"><span data-stu-id="8ae84-237">*Version 1908 (Build 11929.20300)*</span></span>

<span data-ttu-id="8ae84-238">セキュリティ更新プログラムのリストは[こちら](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8ae84-238">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="8ae84-240">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-240">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="8ae84-241">Access</span><span class="sxs-lookup"><span data-stu-id="8ae84-241">Access</span></span>

- <span data-ttu-id="8ae84-242">**より大きい [ズーム] ボックス:** [ズーム] ボックスがより大きく表示され、そこでフォントを変更することができます。変更内容はすべて [ズーム] ボックス内に記憶されます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-242">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="8ae84-243">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-243">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

- <span data-ttu-id="8ae84-244">**データベース オブジェクトをタブで管理する:** アクティブなタブが分かりやすく表示され、簡単にタブをドラッグして再配置し、ワンクリックでデータベース オブジェクトを閉じることができます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-244">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="8ae84-245">**シームレスに切り替える:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用のアカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-245">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="8ae84-246">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-246">Switching between them has never been easier.</span></span> [<span data-ttu-id="8ae84-247">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-247">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="excel"></a><span data-ttu-id="8ae84-248">Excel</span><span class="sxs-lookup"><span data-stu-id="8ae84-248">Excel</span></span>

- <span data-ttu-id="8ae84-249">**データの詳細を検出する:** 新しいアイデア ボタンは、データのパターンを探し、それを使用してインテリジェントな個人向けの提案を作成します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-249">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions.</span></span> [<span data-ttu-id="8ae84-250">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-250">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- <span data-ttu-id="8ae84-251">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="8ae84-251">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="8ae84-252">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-252">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="8ae84-253">**コンテンツのリーチを拡大する:** プレゼンテーションのアクセシビリティを高める必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="8ae84-253">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="8ae84-254">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-254">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="8ae84-255">[校閲]>[アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-255">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="8ae84-256">**シームレスに切り替える:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用のアカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-256">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="8ae84-257">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-257">Switching between them has never been easier.</span></span> [<span data-ttu-id="8ae84-258">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-258">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="8ae84-259">**ワークシートに生気を吹き込む:** アニメーション 3D グラフィックスを挿入して、鼓動する心臓、周回する惑星、暴れまわるティラノサウルスをワークブックに表示できます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-259">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="8ae84-260">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-260">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="8ae84-261">**共同作業がさらに簡単に:** 共同編集の改善とは、条件付き書式、セルのスタイルなどを使用して作業しているときに、ユーザーによる変更がシームレスに共同作業者の変更と統合されるということです。</span><span class="sxs-lookup"><span data-stu-id="8ae84-261">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="8ae84-262">**類似列のテーブルを結合する:** 取得と変換 (Power Query) では、テーブルを統合するために列を比較するときに、近似文字列マッチング ロジック (あいまい一致とも呼ばれる) が使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-262">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="8ae84-263">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-263">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="8ae84-264">**Power Query の機能強化を使用して素早くコーディングする:** オートコンプリートと構文の色分けを使用して、素早くコーディングを完了できます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-264">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="8ae84-265">関数、列、パラメーターも簡単に見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-265">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="8ae84-266">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-266">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="8ae84-267">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="8ae84-267">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="8ae84-268">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-268">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="8ae84-269">Outlook</span><span class="sxs-lookup"><span data-stu-id="8ae84-269">Outlook</span></span>

- <span data-ttu-id="8ae84-270">**メッセージの移動中も作業が可能:** Outlook では、メッセージの移動がバックグラウンドで行われるようになったため、フォルダー間で多数のメッセージの移動が行われている間も作業を続けることができます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-270">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="8ae84-271">**連続する会議の合間に時間を組み込む:** 既定で 5 分から 10 分早く会議を終了するように設定することで、出席者に休憩時間や場所の移動時間を与えることができます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-271">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="8ae84-p118">**ミームが表示される:** テキストまたは静的イメージだけでは十分ではない場合、アニメーション GIF を使用して要点を示すことができます。[詳細情報](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="8ae84-p118">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="8ae84-274">**Outlook のユーザー エクスペリエンスを更新しました:** 以前にプレビューを行い近日公開予定とされていたシンプルなエクスペリエンスで、最も重要な作業に集中できるように設計されています。</span><span class="sxs-lookup"><span data-stu-id="8ae84-274">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="8ae84-275">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-275">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="8ae84-276">**ゆったりとしたレイアウト、まとまったレイアウト? 自由に決めましょう:** 狭いスペースでアイテム間の間隔を広くするか、レイアウトの間隔を狭くして表示量を増やすことができます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-276">**Relaxed or tighter layout? You choose:** Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

- <span data-ttu-id="8ae84-277">**シンプルになったリボンでカスタマイズも可能:** 最もよく使うボタンが 1 行にまとめられ、使いやすくなりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-277">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="8ae84-278">簡単に従来のビューとシンプルなビューを切り替えたり、コマンドを固定または固定解除できます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-278">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="8ae84-279">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-279">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="8ae84-280">**より簡単なアカウントの追加方法:** アカウント設定の改善により、2 要素認証を使用する Outlook.com と Gmail のアカウントの Outlook への追加が以前よりも簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-280">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="8ae84-281">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-281">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="8ae84-282">**お気に入りのアクションを選びましょう：** フラグや、削除機能を使いますか？</span><span class="sxs-lookup"><span data-stu-id="8ae84-282">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="8ae84-283">アーカイブまたは既読に​​しますか?</span><span class="sxs-lookup"><span data-stu-id="8ae84-283">How about Archive or Mark as Read?</span></span> <span data-ttu-id="8ae84-284">よく使うコマンドでクイック操作メニューをカスタマイズします。</span><span class="sxs-lookup"><span data-stu-id="8ae84-284">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="8ae84-285">**同期制限にさよならしましょう:** Outlook の改善によりフォルダーの制限が解消され、そのまま共有メールボックスが同期されます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-285">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="8ae84-286">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-286">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="8ae84-287">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="8ae84-287">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="8ae84-288">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-288">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="8ae84-289">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8ae84-289">PowerPoint</span></span>

- <span data-ttu-id="8ae84-p124">**ユーザーへのテストやアンケート:** テストやアンケートをスライドに配置します。Office で応答が自動的に収集され、保存されます。[詳細情報](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="8ae84-p124">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="8ae84-293">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="8ae84-293">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="8ae84-294">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-294">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="8ae84-295">**コンテンツのリーチを拡大する:** プレゼンテーションのアクセシビリティを高める必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="8ae84-295">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="8ae84-296">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-296">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="8ae84-297">[校閲]>[アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-297">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="8ae84-298">**変更時に変更内容を保存する:** すべての更新が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="8ae84-298">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="8ae84-299">**これまで以上に簡単にオンライン ビデオを挿入できるようになりました:** Vimeo または YouTube からビデオをスライドに挿入する場合は、</span><span class="sxs-lookup"><span data-stu-id="8ae84-299">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide?</span></span> <span data-ttu-id="8ae84-300">ビデオ ページへのリンクがあれば簡単に行えます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-300">The video page link is all you need.</span></span> [<span data-ttu-id="8ae84-301">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-301">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="8ae84-302">**よりよい変形操作:** 図形に名前を付けると、変形するときにより細かく制御できます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-302">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="8ae84-303">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-303">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="8ae84-304">**シームレスに切り替える:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用のアカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-304">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="8ae84-305">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-305">Switching between them has never been easier.</span></span> [<span data-ttu-id="8ae84-306">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-306">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="8ae84-307">**オンライン ビデオの新しい保存場所:** Microsoft Stream にビデオを保存すれば、組織内のすべてのユーザーが視聴できます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-307">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="8ae84-308">ビデオのリンクを挿入すれば、小さなファイル サイズでマルチメディア プレゼンテーションをご利用いただけます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-308">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="8ae84-309">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-309">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="8ae84-310">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-310">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="8ae84-311">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="8ae84-311">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="8ae84-312">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-312">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="8ae84-313">Project</span><span class="sxs-lookup"><span data-stu-id="8ae84-313">Project</span></span>

- <span data-ttu-id="8ae84-314">**シームレスに切り替える:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用のアカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-314">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="8ae84-315">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-315">Switching between them has never been easier.</span></span> [<span data-ttu-id="8ae84-316">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-316">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="8ae84-317">Visio</span><span class="sxs-lookup"><span data-stu-id="8ae84-317">Visio</span></span>

- <span data-ttu-id="8ae84-p133">**壊れた Excel リンクの問題を解消:** データ ビジュアライザーの図にリンクされているはずの Excel ブックが見つかりませんか? 再リンクして、すぐに業務を再開できます。[詳細情報](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="8ae84-p133">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="8ae84-321">**Azure ステンシルが組み込まれました:** 豊富な Azure ステンシルを使用してクラウド アプリを設計したりアーキテクチャを計画したりしましょう。</span><span class="sxs-lookup"><span data-stu-id="8ae84-321">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="8ae84-322">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-322">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="8ae84-323">**はっとするようなデータ フローチャート:** データ ビジュアライザーのフローチャートの見事な新しいレイアウトがすっきり、はっきり、わかりやすくなりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-323">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="8ae84-324">オプションの [デザイン] タブをクリックします。</span><span class="sxs-lookup"><span data-stu-id="8ae84-324">Click the Design tab for options.</span></span>

- <span data-ttu-id="8ae84-325">**シームレスに切り替える:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用のアカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-325">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="8ae84-326">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-326">Switching between them has never been easier.</span></span> [<span data-ttu-id="8ae84-327">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-327">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="8ae84-328">**プロセス図を Word にエクスポート:** Word 文書に図形やメタデータなどのグラフ コンテンツを自動的に追加します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-328">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="8ae84-329">その後に、文書をカスタマイズしてプロセスに関するガイドラインや操作マニュアルを作成できます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-329">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="8ae84-330">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-330">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="8ae84-331">**Power BI から Visio ビジュアルをエクスポートする:** Power BI レポートを PDF、PowerPoint などのファイルとしてエクスポートするときに、Power BI 用の Visio ビジュアルが正しく表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-331">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="8ae84-332">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-332">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="8ae84-333">Word</span><span class="sxs-lookup"><span data-stu-id="8ae84-333">Word</span></span>

- <span data-ttu-id="8ae84-p139">**インク エディターを使った自然な編集:** ペンを使って 1 ストローク描くだけで、単語の分割や結合、新しい線の追加、単語の挿入などができます。[詳細情報](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="8ae84-p139">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="8ae84-p140">**静的なドキュメントから魅力的なドキュメントへの変換:** ドキュメントを、すべてのデバイスに対応する対話型の使いやすい Web ページに変換します。[詳細情報](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="8ae84-p140">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="8ae84-338">**\@メンションを使用してユーザーの注意を引く:** コメントで @メンションを使うと、他のユーザーによる入力が必要な場合にそのユーザーに知らせることができます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-338">**Get Their Attention with \@Mentions:** Use @mentions in comments to let others know when you need their input.</span></span> [<span data-ttu-id="8ae84-339">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-339">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="8ae84-p142">**行フォーカスによる読解力の向上:** ドキュメント内で行ごとの移動をスムーズに行います。一度に 1 行か、3 行か、5 行かを表示するようフォーカスを調整できます。[詳細情報](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="8ae84-p142">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="8ae84-343">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="8ae84-343">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="8ae84-344">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-344">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="8ae84-345">**変更時に変更内容を保存する:** すべての更新が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="8ae84-345">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="8ae84-346">**コンテンツのリーチを拡大する:** ドキュメントのアクセシビリティを高める必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="8ae84-346">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="8ae84-347">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-347">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="8ae84-348">[校閲]>[アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-348">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="8ae84-349">**[学習ツール] モードで、ページで使用できる色が増えました:** Word の学習ツールでは、より多くのページ テーマ色が追加され、ページの背景色を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-349">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="8ae84-350">すべて白またはすべて黒の背景だと読みにくいと感じるユーザーは少なくないため、PC と Mac の Word で色の選択肢を拡大しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-350">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="8ae84-351">**シームレスに切り替える:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用のアカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-351">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="8ae84-352">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-352">Switching between them has never been easier.</span></span> [<span data-ttu-id="8ae84-353">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-353">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)


- <span data-ttu-id="8ae84-354">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-354">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="8ae84-355">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="8ae84-355">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="8ae84-356">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-356">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="8ae84-357">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8ae84-357">Office Suite</span></span>

- <span data-ttu-id="8ae84-358">**Microsoft Teams のインストール**: Teams は、Office 365 ProPlus の既存のインストールに追加されます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-358">**Installation of Microsoft Teams:** Teams is added to existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="8ae84-359">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-359">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

- <span data-ttu-id="8ae84-360">**変更が発生したときに変更内容を自動的に保存する:** 変更が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="8ae84-360">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="8ae84-361">**プライバシー制御**: 診断データとコネクテッド エクスペリエンス用に新しく更新されて、改善された制御。</span><span class="sxs-lookup"><span data-stu-id="8ae84-361">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="8ae84-362">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-362">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="8ae84-363">**新しい外観を備えた Office のアイコン:** シンプルかつ高性能で、インテリジェントな Office のエクスペリエンスを反映するように、Office のアイコンがリニューアルされました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-363">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="8ae84-364">**Microsoft Teams のインストール:** Microsoft Teams は、Office 365 ProPlus の既存のインストールに既定でインストールされています。</span><span class="sxs-lookup"><span data-stu-id="8ae84-364">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="8ae84-365">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-365">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="8ae84-368">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-368">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="8ae84-369">Excel</span><span class="sxs-lookup"><span data-stu-id="8ae84-369">Excel</span></span>

- <span data-ttu-id="8ae84-370">図形やフォーム コントロールに割り当てられているマクロが間違ったエラー メッセージとして表示される、または間違った対象範囲で動作する問題が Excel で修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-370">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="8ae84-371">ピボットテーブルの並べ替え方法を変更し、他のユーザーとの共同編集セッション中にエラーを発生させる可能性のある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-371">Fixed an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could cause it to fail.</span></span>

- <span data-ttu-id="8ae84-372">セルが挿入または削除されたときに、ウォーターフォール図とじょうごグラフがテーブルと同期しなくなる原因となっていた問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-372">Fixed an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="8ae84-373">Excel では、ユーザーが変更を取得するためにブックを再び開くよう要求される結果となるマージ競合の問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-373">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="8ae84-374">テーブルの横にある切り取りと貼り付けの操作を、他のユーザーと共同編集しているときに失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-374">Fixed an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

### <a name="outlook"></a><span data-ttu-id="8ae84-375">Outlook</span><span class="sxs-lookup"><span data-stu-id="8ae84-375">Outlook</span></span>

- <span data-ttu-id="8ae84-376">メールボックスを基本認証から最新認証にアップグレードしたユーザーが、Outlook プロファイルに関連付けられた正しくないアカウントで終了する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-376">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="8ae84-377">設定に関係なく、POP3 ユーザーの一部がプレーンテキストで書式設定されたすべてのメールを表示する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-377">Fixed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="8ae84-378">この修正プログラムでは、HTML 形式のメッセージの表示が復元されます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-378">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="8ae84-379">スクリーン リーダーからユーザーが保管場所の候補にアクセスできない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-379">Fixed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="8ae84-380">一部のユーザーが Outlook のクラウド設定を取得しようとすると、認証エラーが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-380">Fixed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="8ae84-381">代理人が特定の会議出席依頼に既に返信したかどうかに関係なく、管理者が不明瞭になる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-381">Fixed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="8ae84-382">Outlook ユーザーが特定のシナリオで "パスワードを要求している" 状態で停止する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-382">Fixed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="8ae84-383">現在のフォルダー検索で断続的な失敗を引き起こす問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-383">Fixed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="8ae84-384">会議室の空き時間外に発生した会議のために会議室がユーザーに提案されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-384">Fixed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="8ae84-385">ユーザーにエラー "このファイルが見つかりません" が表示される一時的なサービスに関する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-385">Fixed temporary service issue that caused users to see the error "Cannot find this file.</span></span> <span data-ttu-id="8ae84-386">クラウドの添付ファイルを使用している場合は、パスとファイル名が正しいことを確認します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-386">Verify the path and file name are correct" when using cloud attachments.</span></span> [<span data-ttu-id="8ae84-387">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-387">Learn More</span></span>](https://support.office.com/article/outlook-unable-to-attach-onedrive-or-sharepoint-files-to-emails-136951bb-60dc-478a-b916-6ee39e62c37a)

- <span data-ttu-id="8ae84-388">ユーザーに Outlook から OneDrive または Sharepoint にアップロードしたファイルが表示される問題が修正されました。ファイル名が変更され、複数の文字が下線で置き換えられました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-388">Fixed an issue that caused users to see uploaded files from Outlook to OneDrive or Sharepoint have the file name changed where several characters replaced by underscores.</span></span>

- <span data-ttu-id="8ae84-389">メールの件名が非常に小さくなる英語以外の言語を使用するユーザーの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-389">Fixed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8ae84-390">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8ae84-390">PowerPoint</span></span>

- <span data-ttu-id="8ae84-391">一部のアドインがグラフの図形に対して予期しないエラーをスローさせる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-391">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="8ae84-392">PowerPoint ビデオ コントロールのアクセシビリティの高い名前を復元する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-392">Fixed an issue to restore the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="8ae84-393">一部のアニメーションが開始されないことがある問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="8ae84-393">Fixed an issue which could prevent some animations from starting</span></span>

### <a name="project"></a><span data-ttu-id="8ae84-394">Project</span><span class="sxs-lookup"><span data-stu-id="8ae84-394">Project</span></span>

- <span data-ttu-id="8ae84-395">Windows 7 のユーザーが Project Web App および SharePoint サイトからプロジェクトを開くことができるように問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-395">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>


### <a name="visio"></a><span data-ttu-id="8ae84-396">Visio</span><span class="sxs-lookup"><span data-stu-id="8ae84-396">Visio</span></span>

- <span data-ttu-id="8ae84-397">Visio から SVG へのエクスポートは、さまざまな図形に対しては機能しませんでした。</span><span class="sxs-lookup"><span data-stu-id="8ae84-397">Export to SVG from Visio was not working for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="8ae84-398">Word</span><span class="sxs-lookup"><span data-stu-id="8ae84-398">Word</span></span>

- <span data-ttu-id="8ae84-399">ユーザーが Word ドキュメントで他のユーザーと共同作業しているときに、エラー メッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-399">Fixed an issue where users would get error messages while collaborating with others on a Word document.</span></span>

- <span data-ttu-id="8ae84-400">SharePoint 2016 に保存されているファイルを共有しようとすると、"申し訳ございません。何かがこのファイルの共有を妨げています。" というメッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-400">Fixed an issue which caused users to get the message "Sorry, something is preventing us from sharing this"  when trying to share files stored on SharePoint 2016.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8ae84-401">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8ae84-401">Office Suite</span></span>

- <span data-ttu-id="8ae84-402">同期エンジンでバックアップされた sharepoint ファイルに '保存済み' と表示されますが、場合によっては実際に変更が保存されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-402">Fixed an issue where in some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes.</span></span>

- <span data-ttu-id="8ae84-403">大きなツリー ビューにエラーが発生していた問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-403">Fixed an issue where large tree views were failing.</span></span>

- <span data-ttu-id="8ae84-404">新元号の「Reiwa」のひらがなと漢字をスペルミスまたは間違った文法として誤って識別していた問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-404">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1902-august-13"></a><span data-ttu-id="8ae84-406">バージョン 1902: 8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="8ae84-406">Version 1902: August 13</span></span>
<span data-ttu-id="8ae84-407">*バージョン 1902 (ビルド 11328.20392)*</span><span class="sxs-lookup"><span data-stu-id="8ae84-407">*Version 1902 (Build 11328.20392)*</span></span>

<span data-ttu-id="8ae84-408">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8ae84-408">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="8ae84-409">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-409">Excel: Non-security updates</span></span>
- <span data-ttu-id="8ae84-410">テーブルのフィルター処理ありのスライサーとフィルター処理なしのスライサーの両方に、[フィルターのクリア] アイコンが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-410">Fixed an issue where the clear filter icon was shown for both filtered and unfiltered Slicers in tables.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="8ae84-411">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-411">Outlook: Non-security updates</span></span>
- <span data-ttu-id="8ae84-412">ユーザーがメールボックスを基本認証から最新認証にアップグレードすると、関連付けられた正しくないアカウントで終了する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8ae84-412">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="8ae84-413">PowerPoint: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-413">PowerPoint: Non-security updates</span></span>
- <span data-ttu-id="8ae84-414">他のユーザーとドキュメントの共同作業を行っている間に、アプリケーションが予期せず終了する可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-414">Fixed an issue where the application could unexpectedly terminate while collaborating on a document with other users.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="8ae84-415">Word: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-415">Word: Non-security updates</span></span>
- <span data-ttu-id="8ae84-416">VBA のフィールド更新が遅い問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-416">Fixed an issue which VBA updating fields were slow.</span></span>
- <span data-ttu-id="8ae84-417">一部の DOC ファイルを開くと、破損していると表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-417">Fixed in issue when opening some DOC file, it says it is corrupt.</span></span>
- <span data-ttu-id="8ae84-418">他のユーザーとドキュメントの共同作業を行っている間に、アプリケーションが予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-418">Fixed an issue where the application could unexpectedly terminate while collaborating on a document with other users.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="8ae84-419">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-419">Office Suite: Non-security updates</span></span>
- <span data-ttu-id="8ae84-420">特定のシナリオで Office JavaScript ライブラリ の Setting API が機能しなくなる問題を修正しました ([詳細情報](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551))</span><span class="sxs-lookup"><span data-stu-id="8ae84-420">Fixed an issue in which Setting API doesn't work in the Office JavaScript library in certain scenarios [Learn More](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span></span>

## <a name="version-1902-july-09"></a><span data-ttu-id="8ae84-421">バージョン 1902: 7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="8ae84-421">Version 1902: July 09</span></span>
<span data-ttu-id="8ae84-422">*バージョン 1902 (ビルド 11328.20368)*</span><span class="sxs-lookup"><span data-stu-id="8ae84-422">*Version 1902 (Build 11328.20368)*</span></span>

<span data-ttu-id="8ae84-423">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="8ae84-423">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>


### <a name="excel-non-security-updates"></a><span data-ttu-id="8ae84-424">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-424">Excel: Non-security updates</span></span>
- <span data-ttu-id="8ae84-425">フィルター処理された Excel 行を削除するときの動作が極端に遅くなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-425">Fixed extreme slowness Issue in deleting filtered excel rows.</span></span>
- <span data-ttu-id="8ae84-426">2 本の指でスクロールするとワークシート上にグレーの四角形が描かれて Excel がハングアップするという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-426">Fixed two finger scrolling causes grey rectangles to be drawn over worksheet and Excel to hang.</span></span>


### <a name="outlook-non-security-updates"></a><span data-ttu-id="8ae84-427">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-427">Outlook: Non-security updates</span></span>
- <span data-ttu-id="8ae84-428">Outlook で、中国語の単語を選ぶ IME 候補ウィンドウが開いたままになる代わりに、英語の PinYin 文字が挿入される場合があるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-428">Addresses an issue that caused users to occasionally see Outlook inserting English pinyin letters rather than keeping the IME candidate window open to allow the selection of Chinese words.</span></span>
- <span data-ttu-id="8ae84-429">会議室の空き時間外にスケジュールされた会議のためにその会議室がユーザーに提案されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-429">Addresses an issue that caused users to see rooms being suggested for meetings that were scheduled outside of that room's availability.</span></span>
- <span data-ttu-id="8ae84-430">会議シリーズの例外を開こうとしたときに代わりにマスター シリーズが開くという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-430">Addresses an issue that caused users attempting to open an exception to a meeting series to instead open the master series.</span></span>
- <span data-ttu-id="8ae84-431">[削除済みアイテム] フォルダー内のアイテムの有効期限日が誤って計算されて表示されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-431">Addresses an issue that caused users to see expiry dates being calculated incorrectly for items in Deleted Items folder.</span></span>


### <a name="teams-non-security-updates"></a><span data-ttu-id="8ae84-432">Teams: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-432">Teams: Non-security updates</span></span>

- <span data-ttu-id="8ae84-433">Teams インストーラーで、インストール完了後の自動起動をオフにするポリシーが使用可能になりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-433">Teams installer has now available Policy to turn off auto-launch after installation is completed.</span></span>


### <a name="visio-non-security-updates"></a><span data-ttu-id="8ae84-434">Visio: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-434">Visio: Non-security updates</span></span>

- <span data-ttu-id="8ae84-435">Visio 用の ActiveX ソリューションが Office 365 と連動しないことに関連する問題に対処します。この問題は、「riched20.dll が見つからない」というエラー メッセージとして出現します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-435">Addresses issue related to ActiveX solutions for Visio not working with Office 365, expressed as an error message stating that riched20.dll can't be found.</span></span>


### <a name="word--non-security-updates"></a><span data-ttu-id="8ae84-436">Word: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-436">Word:  Non-security updates</span></span>

- <span data-ttu-id="8ae84-437">テンプレート検索バーを無効にする GPO 設定を修正しました</span><span class="sxs-lookup"><span data-stu-id="8ae84-437">Fixed GPO setting to disable template search bar</span></span>
- <span data-ttu-id="8ae84-438">オフラインになった後、サーバーのみのドキュメントをユーザーが編集すると変更内容の一部が失われることがあるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-438">Fixed an issue where users could lose some of their changes after being offline and editing a document that was server-only.</span></span>
- <span data-ttu-id="8ae84-439">文書のクイックパーツ プロパティを有効にしたときのパフォーマンスが向上しました</span><span class="sxs-lookup"><span data-stu-id="8ae84-439">Improved performance when enabling Quick Parts for Document properties</span></span>
- <span data-ttu-id="8ae84-440">サーバーからの初回ダウンロード リビジョンが失敗する場合があるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8ae84-440">Fixed an issue where first download revision from the server might fail</span></span>


### <a name="office-suite--non-security-updates"></a><span data-ttu-id="8ae84-441">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-441">Office Suite:  Non-security updates</span></span>

- <span data-ttu-id="8ae84-442">追加の Office 製品や言語パックをインストールすると、共有コンピューターのライセンス認証を使用しているデバイスが、予期せずユーザーベースのライセンス認証に戻ることがあるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-442">Addressed an issue where devices using shared computer activation may unexpectedly revert to user-based activation upon installation of additional Office products or language packs.</span></span>
- <span data-ttu-id="8ae84-443">プロキシ認証がシステムとして実行されたときに Office の更新プログラムがブロックされるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-443">Fixed an issue that blocked Office Updates when proxy authentication runs as SYSTEM.</span></span>
- <span data-ttu-id="8ae84-444">ユーザー プロファイルの変更によって Office アドインが表示されなくなる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-444">Fixes to address Office add-ins disappearing on user profile changes.</span></span>


## <a name="version-1902-june-11"></a><span data-ttu-id="8ae84-445">バージョン 1902: 6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="8ae84-445">Version 1902: June 11</span></span>
<span data-ttu-id="8ae84-446">*バージョン 1902 (ビルド 11328.20318)*</span><span class="sxs-lookup"><span data-stu-id="8ae84-446">*Version 1902 (Build 11328.20318)*</span></span>
<br/><span data-ttu-id="8ae84-447">[こちら](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)にセキュリティ更新プログラムが記載されています</span><span class="sxs-lookup"><span data-stu-id="8ae84-447">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="8ae84-448">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-448">Excel: Non-security updates</span></span>
 - <span data-ttu-id="8ae84-449">PDF にマッピングする XML を含むファイルを保存するときにクラッシュの原因となっていた問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-449">Resolved an issue that caused a crash when saving a file containing an XML map to PDF.</span></span>
 - <span data-ttu-id="8ae84-450">無効なシート名を含むブックを読み込むときに外部リンクが削除される原因となっていた問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-450">Resolved an issue that caused external links to be removed when workbooks containing invalid sheet names are loaded.</span></span>
 - <span data-ttu-id="8ae84-451">Excel でカメラ ツールを使用するとスプレッドシートが終了する原因となっていた問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-451">Fixed an issue where using the Camera tool in Excel could cause the spreadsheet to hang.</span></span>
 - <span data-ttu-id="8ae84-452">セルが挿入または削除されたときに、ウォーターフォール図とじょうごグラフがテーブルと同期しなくなる原因となっていた問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-452">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>
 - <span data-ttu-id="8ae84-453">テーブルに依存する別のシートで配列計算を用いて Worksheet Calculate を動作させている間に、データ テーブルが再計算されるとクラッシュする問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-453">Resolved a crash when a data table is recalculated during Worksheet Calculate with an array formula on another sheet depending on the table.</span></span> 
 - <span data-ttu-id="8ae84-454">最初にファイルをチェックアウトしないと、パスワードで保護されたブックを SharePoint から開けなかった問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-454">Resolved an issue that prevented password protected workbooks from being opened from SharePoint without checking out file first.</span></span>
 - <span data-ttu-id="8ae84-455">自動保存の共有または切り替えが行われているときに BeforeSave イベントの処理を確保する変更が行われました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-455">A change was made to ensure the BeforeSave event is handled when sharing or toggling AutoSave.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="8ae84-456">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-456">Outlook: Non-security updates</span></span>
 - <span data-ttu-id="8ae84-457">"Group by" に 2 番目の条件を追加するとお客様に表示するタスクが表示されなくなる原因となっていた問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-457">Addressed an issue that caused customers to see their tasks seem to disappear when adding a 2nd condition to "Group by".</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="8ae84-458">Word: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-458">Word: Non-security updates</span></span>
 - <span data-ttu-id="8ae84-459">.asd 拡張子が含まれる添付ファイルを生成するドキュメントとして現在共同作成しているドキュメントの共有を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-459">Fixed when sharing a document which is currently being collaborated upon the document produces attachment with .asd extension.</span></span>
 - <span data-ttu-id="8ae84-460">ランダムな作成者に起因したコメントに関する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-460">Fixed an issue with comments get attributed to random authors.</span></span>
 - <span data-ttu-id="8ae84-461">ドキュメントをチェックアウトするときに発生する署名の削除の問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-461">Fixed an issue in the remove signature when checking out a document.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="8ae84-462">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-462">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="8ae84-463">"元に戻す" 操作の後に VBA が不正確な図形の塗り潰しのステータスを報告する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-463">This fixed a bug in VBA reporting incorrect shape fill state after an "undo" action.</span></span>


## <a name="version-1902-may-14"></a><span data-ttu-id="8ae84-464">バージョン 1902: 5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="8ae84-464">Version 1902: May 14</span></span>
<span data-ttu-id="8ae84-465">*バージョン 1902 (ビルド 11328.20286)*</span><span class="sxs-lookup"><span data-stu-id="8ae84-465">*Version 1902 (Build 11328.20286)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="8ae84-466">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-466">Excel: Non-security updates</span></span>
 -  <span data-ttu-id="8ae84-467">Excel でカメラ ツールを使用するとスプレッドシートが終了する原因となっていた問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-467">Fixed an issue where using the Camera tool in Excel could cause the spreadsheet to hang.</span></span>
 - <span data-ttu-id="8ae84-468">グラフ シートのある非アクティブ ウィンドウでマウス スクロール ホイールを使用するとクラッシュする問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-468">An issue that caused a crash when using the mouse scroll wheel on an in-active window with a chart sheet was fixed.</span></span>
 - <span data-ttu-id="8ae84-469">SharePoint でスプレッドシートをインポートするときに「予期しないエラー」メッセージが表示される問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-469">A problem that caused an "Unexpected Error" message to appear when importing a spreadsheet in SharePoint has been resolved.</span></span>
 - <span data-ttu-id="8ae84-470">ルールの名前を使用する条件付き書式を含むブックを開くときに、Excel がクラッシュし、ユーザー設定のビューが適用される問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-470">A problem that caused Excel to crash when opening a workbook containing conditional formatting that uses a Name for its rule and a custom view is applied has been resolved.</span></span>
 - <span data-ttu-id="8ae84-471">255 文字より長い数式でマクロがデータの入力規則を使用すると、実行時エラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="8ae84-471">Macros using data validation with formulas longer than 255 characters may have produced run-time errors.</span></span> <span data-ttu-id="8ae84-472">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-472">This issue has now been corrected.</span></span>
 - <span data-ttu-id="8ae84-473">他のブックにリンクされているピボットテーブルを含むファイルの読み込み速度が低下する問題。</span><span class="sxs-lookup"><span data-stu-id="8ae84-473">A problem which caused files containing PivotTables linked to other workbooks to load slowly.</span></span> <span data-ttu-id="8ae84-474">この問題は解決されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-474">This issue has been resolved.</span></span>
 - <span data-ttu-id="8ae84-475">HTML ファイルを開くと「ファイル形式と拡張子が一致しない」というエラーが発生する問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-475">An issue with opening HTML files and receiving a "file format and extension do not match" error has been resolved.</span></span>
 - <span data-ttu-id="8ae84-476">非アクティブのウィンドウでのマウス ホイール スクロールによる問題を解決するために変更が行われました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-476">A change has been made to resolve issues with mouse-wheel scrolling on inactive windows.</span></span>  

### <a name="outlook-non-security-updates"></a><span data-ttu-id="8ae84-477">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-477">Outlook: Non-security updates</span></span>
 - <span data-ttu-id="8ae84-478">移行されたアイテムの一部のフィールドを顧客が編集できない問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-478">Addresses an issue that caused customers to be unable to edit some fields on items that had been migrated.</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="8ae84-479">PowerPoint: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-479">PowerPoint: Non-Security updates</span></span>
- <span data-ttu-id="8ae84-480">PowerPoint がクラウドへのユーザー変更のアップロードを停止することがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-480">Fixed an issue that PowerPoint stops uploading user changes to the cloud in rare situations.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="8ae84-481">Skype for Business: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-481">Skype for Business: Non-security updates</span></span>
 - <span data-ttu-id="8ae84-482">Lync (Skype for Business) で、参加者が 7 人以上のオンライン ミーティングのミーティング ウィンドウが表示されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-482">Fixed an issue in Lync (Skype for Business) where for any online meeting with more 7+ participants, the meeting window can disappear.</span></span>
 - <span data-ttu-id="8ae84-483">別の Office アプリケーションにサインインするために使用された資格情報で Skype for Business にサインインします。</span><span class="sxs-lookup"><span data-stu-id="8ae84-483">Sign into Skype for Business with credentials used to sign into another Office application.</span></span>
 - <span data-ttu-id="8ae84-484">共有コンピューターのライセンス認証でインストールした場合は、Skype for Business アプリを正しくライセンス認証します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-484">Properly activate the Skype for Business app when installed with shared computer activation.</span></span>

### <a name="visio-non-security-updates"></a><span data-ttu-id="8ae84-485">Visio: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-485">Visio: Non-security updates</span></span>
 - <span data-ttu-id="8ae84-486">動的 DPI 機能を無効にして Visio を拡張するサードパーティ ソリューションで、ウィンドウ階層が壊れる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-486">Fixed an issue which was causing broken window hierarchy issues for 3rd party solutions extending Visio by disabling Dynamic DPI feature.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="8ae84-487">Word: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-487">Word: Non-Security updates</span></span>
 - <span data-ttu-id="8ae84-488">SharePoint によって追加された関係者を編集する際にクラッシュする場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-488">Fixed an issue where editing a Related Person added by SharePoint could crash.</span></span>
 - <span data-ttu-id="8ae84-489">Word の起動時に [リソースを読み込めませんでした] ダイアログが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-489">Fixed where the "Failed to load resource" dialog when Word launches.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="8ae84-490">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-490">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="8ae84-491">これは、ファイルを Apache WebDAV フォルダーに保存できない問題の修正プログラムです。</span><span class="sxs-lookup"><span data-stu-id="8ae84-491">This is a fix for an issue where files cannot be saved to Apache WebDAV folders.</span></span>
 - <span data-ttu-id="8ae84-492">ユーザーがクラウドに保存したファイルを開くと、Office が突然終了する問題の修正です。</span><span class="sxs-lookup"><span data-stu-id="8ae84-492">Fixes an issue where Office closes abruptly when customers open some cloud-stored files.</span></span>
 - <span data-ttu-id="8ae84-493">新時代の名前である「Reiwa」のひらがなと漢字をスペルミスまたは間違った文法として誤って識別していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-493">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>
 - <span data-ttu-id="8ae84-494">Windows 10 の多くのユーザーに対して最近のファイル リストがクリアされているように見えた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-494">Fixed an issue where the recent files list appeared to have been cleared for many users on Windows 10.</span></span>
 - <span data-ttu-id="8ae84-495">管理者による更新が進行中であっても、エンドユーザーに Office Update のビジネス バーが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-495">Fixed an issue that caused an end-user to see an Office Update business bar, even though there is an Admin-triggered update in progress.</span></span>
 - <span data-ttu-id="8ae84-496">断続的な空白のサインインプロンプトに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-496">Fixed an issues related to intermittent blank sign-in prompts.</span></span>
 

## <a name="version-1902-april-9"></a><span data-ttu-id="8ae84-497">バージョン 1902:4月9日</span><span class="sxs-lookup"><span data-stu-id="8ae84-497">Version 1902: April 9</span></span>
<span data-ttu-id="8ae84-498">*バージョン 1902 (ビルド 11328.20230)*</span><span class="sxs-lookup"><span data-stu-id="8ae84-498">*Version 1902 (Build 11328.20230)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="8ae84-499">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-499">Excel: Non-Security updates</span></span>

- <span data-ttu-id="8ae84-500">定義された名前で終わる数式が含まれるセルにいる場合、Tab キーを押しても次のセルに移動できないという問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-500">Resolved an issue where pressing the Tab key would not move to the next cell when in a cell containing a formula ending in a defined name.</span></span>
- <span data-ttu-id="8ae84-501">セルの書式設定が原因でファイルのサイズが必要以上に大きくなるという問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-501">Resolved an issue where cell formatting was causing the file size to grow unnecessarily.</span></span>
- <span data-ttu-id="8ae84-502">ブック間でピボットテーブルをカット アンド ペーストすると、共同作業している他のユーザーのピボットテーブルを含まずにデータが貼り付けられるという問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-502">Resolved an issue where cutting and pasting a PivotTable between workbooks may result in the data being pasted, without a PivotTable for others you are collaborating with.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="8ae84-503">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-503">Outlook: Non-Security updates</span></span>

- <span data-ttu-id="8ae84-504">システムタスクバーを画面の左または上に置いたときにウィンドウが正しい場所に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-504">Fixed an issue in which windows would not appear in the correct location when the system task bar was kept at the left or top of the screen.</span></span>
- <span data-ttu-id="8ae84-505">顧客の連絡先カード上の画像の読み込み中にクラッシュが発生する原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-505">Addresses an issue that caused customers to experience a crash when loading pictures on the contact card.</span></span>
- <span data-ttu-id="8ae84-506">一部の顧客がOffice アプリケーションの起動時にクラッシュするという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-506">Addresses an issue that caused some customers to experience crashes when starting office applications.</span></span>
- <span data-ttu-id="8ae84-507">システムタスクバーを画面の左または上に置いたときにウィンドウが正しい場所に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-507">Fixed an issue in which windows would not appear in the correct location when the system task bar was kept at the left or top of the screen.</span></span>
- <span data-ttu-id="8ae84-508">移行されたアイテムの一部のフィールドを顧客が編集できない問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-508">Addresses an issue that caused customers to be unable to edit some fields on items that had been migrated.</span></span>

### <a name="visio-non-security-updates"></a><span data-ttu-id="8ae84-509">Visio: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-509">Visio: Non-Security updates</span></span>

- <span data-ttu-id="8ae84-510">動的 DPI 機能を無効して Visio を拡張するサードパーティ ソリューションで、ウィンドウ階層が壊れる原因となっていた問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-510">Fixed an issue which was causing broken window hierarchy issues for 3rd party solutions extending Visio by disabling the Dynamic DPI feature.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="8ae84-511">Word: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-511">Word: Non-Security updates</span></span>

- <span data-ttu-id="8ae84-512">ファイルが読み取り専用モードで開かれているときに[情報]枠から[名前を付けて保存]をクリックすると、保存UIが表示されるように問題が修正されています。</span><span class="sxs-lookup"><span data-stu-id="8ae84-512">If a file is opened in read-only mode and you click 'Save As' from the 'Info' pane, fixes issue so that the save UI is displayed.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="8ae84-513">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-513">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="8ae84-514">Office の更新プログラムの一部で配信の最適化のピア キャッシュを使用しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-514">Fixed an issue where parts of an Office update do not use Delivery Optimization peer caching.</span></span> [<span data-ttu-id="8ae84-515">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-515">Learn more</span></span>](https://docs.microsoft.com/windows/deployment/update/waas-delivery-optimization)
- <span data-ttu-id="8ae84-516">Office が Office 展開ツールを使用してインストールされ、大文字/小文字が一致しない場合、製品が削除されたり、アクティブ化されなかったりする可能性があるバグが修正されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-516">Fix to a bug that could lead to products being removed or not activated if Office was installed using the Office Deployment Tool and there was a case mis-match.</span></span>
- <span data-ttu-id="8ae84-517">Windows 10（バージョン1803以降）のデバイスで過剰なサインインプロンプトを引き起こしていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-517">Fixed an issue which was causing excessive sign-in prompts on Windows 10 (version 1803 or later) devices.</span></span>
- <span data-ttu-id="8ae84-518">リンクされた写真をダウンロードするときにハングする原因となる退行を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-518">Fixed regression that causes hangs when downloading linked pictures.</span></span>
- <span data-ttu-id="8ae84-519">Word、Excel、PowerPointに貼り付けられた大きなEMFファイルのぼやけを修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-519">Fixed blurriness of large EMF files pasted in Word, Excel, PowerPoint.</span></span>
- <span data-ttu-id="8ae84-520">バージョン履歴の解析ロジックで、ドキュメントが読み取り専用で開かれることがあったケースを修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-520">Fixed the bug in version history parsing logic that in few cases caused the documents to be opened in read-only.</span></span>

## <a name="version-1902-march-12"></a><span data-ttu-id="8ae84-521">バージョン 1902: 3 月 12 日</span><span class="sxs-lookup"><span data-stu-id="8ae84-521">Version 1902: March 12</span></span>
<span data-ttu-id="8ae84-522">*バージョン 1902 (ビルド 11328.20158)*</span><span class="sxs-lookup"><span data-stu-id="8ae84-522">*Version 1902 (Build 11328.20158)*</span></span>

### <a name="access-feature-updates"></a><span data-ttu-id="8ae84-523">Access: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8ae84-523">Access: Feature updates</span></span>

- <span data-ttu-id="8ae84-524">**リンク テーブルを更新、再リンク、または削除する:** 更新されたリンク テーブル マネージャーで、すべてのデータ ソースとリンク テーブルを管理できます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-524">**Refresh, relink, or remove linked tables:** The updated Linked Table Manager is the location for managing all data sources and linked tables.</span></span> [<span data-ttu-id="8ae84-525">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-525">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)
- <span data-ttu-id="8ae84-p157">**黒にペイントする、灰色にペイントする:** アクセスの外観を好きなだけ変更します。次の 4 つのテーマを選択: カラフル、濃い灰色、黒、白のいずれか。[詳細情報](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)</span><span class="sxs-lookup"><span data-stu-id="8ae84-p157">**Paint it black, paint it gray:** Change the look of Access as often as you like. Four themes to choose from: Colorful, Dark Gray, Black, or White. [Learn more](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)</span></span>
- <span data-ttu-id="8ae84-529">**Office の外観が新しくなる:** Office アプリに、よりシンプルでアクセスしやすい最新のアイコンが加わり、リボンの外観が、Office アプリで使用可能な豊富なコラボレーション機能を強調するように更新されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-529">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="8ae84-530">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8ae84-530">Excel: Feature updates</span></span>

- <span data-ttu-id="8ae84-531">\*\*すばやく始めましょう \*\*新しくデザインされたスタートページは、最近開いたドキュメントを前面と中央に配置します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-531">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="8ae84-532">以前より少ないクリック数でファイルにアクセスし、そこからすぐアカウント設定またはオプションを開きます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-532">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="8ae84-533">**コメントを利用して共同作業を行う:** 返信ボックスが組み込まれているので、スプレッドシートで直接会話を続けることができます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-533">**Collaborate with comments:** Keep the conversation going right in your spreadsheet with the built-in reply box.</span></span> [<span data-ttu-id="8ae84-534">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-534">Learn more</span></span>](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)
- <span data-ttu-id="8ae84-535">**新しい見た目のリボン アイコン:** 機能に変化はないので、心配はいりません。</span><span class="sxs-lookup"><span data-stu-id="8ae84-535">**Your ribbon icons have a new look:** Don’t worry, everything works the same.</span></span> <span data-ttu-id="8ae84-536">さらに、どのサイズの画面でも、見た目がきれいです。</span><span class="sxs-lookup"><span data-stu-id="8ae84-536">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="8ae84-537">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-537">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="8ae84-538">**フィルターが適用された SVG を挿入する機能:** Office ユーザーは、フィルターが適用された SVG を挿入できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-538">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them.</span></span> [<span data-ttu-id="8ae84-539">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-539">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- <span data-ttu-id="8ae84-p162">**画像の背後を見えるようにする:** ワークシートに画像を挿入し、既定の設定から選択して、透明度の変化を確認するだけです。[詳細情報](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="8ae84-p162">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="8ae84-543">**データの取得と変換をご利用の皆様:** データの取得と変換をよく利用していただいているユーザーの皆様に、サンプルからの列の機能が改善されたことをお知らせします。</span><span class="sxs-lookup"><span data-stu-id="8ae84-543">**Calling all Get & Transform fans:** If you use Get & Transform a lot, you'll be happy to know that the Column From Example feature has been improved.</span></span> <span data-ttu-id="8ae84-544">また、多くのコネクタも強化されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-544">And, many connectors have been improved as well.</span></span> [<span data-ttu-id="8ae84-545">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-545">Learn more</span></span>](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)
- <span data-ttu-id="8ae84-546">**改善された高解像度ディスプレイのサポート:** 複数のモニター、またはドッキングでラップトップを使用する場合、各ディスプレイの倍率設定が異なっていても Office アプリがすべてのディスプレイで鮮明に表示されるようになります。</span><span class="sxs-lookup"><span data-stu-id="8ae84-546">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="8ae84-547">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-547">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- <span data-ttu-id="8ae84-548">**迅速な検索:** VLOOKUP、HLOOKUP、および MATCH の計算が高速化されたので、より迅速に回答を得られるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-548">**Speedy Lookup** We've turbo-charged your VLOOKUP, HLOOKUP, and MATCH calculations so you can get answers faster.</span></span> [<span data-ttu-id="8ae84-549">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-549">Learn more</span></span>](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)

### <a name="outlook-feature-updates"></a><span data-ttu-id="8ae84-550">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8ae84-550">Outlook: Feature updates</span></span>

- <span data-ttu-id="8ae84-551">**音声読み上げを使用してメールの内容を聞く:** Outlook では、メールのテキストを読み上げながら強調表示することができます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-551">**Use Read Aloud to listen to your email:** Outlook can read your email aloud, highlighting text as it's read.</span></span> <span data-ttu-id="8ae84-552">読み上げ機能をオンにするには、[簡単操作] の設定に移動します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-552">To turn on Read Aloud, go to the Ease of Access settings.</span></span> [<span data-ttu-id="8ae84-553">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-553">Learn more</span></span>](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)
- <span data-ttu-id="8ae84-554">**ハンズフリーで入力:** マイクは用意しましたか。</span><span class="sxs-lookup"><span data-stu-id="8ae84-554">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="8ae84-555">[ディクテーション] をクリックして、発話すると Outlook によって入力されるのを確認してください。</span><span class="sxs-lookup"><span data-stu-id="8ae84-555">Click Dictate and watch Outlook type while you talk.</span></span> [<span data-ttu-id="8ae84-556">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-556">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="8ae84-557">**新しい見た目のリボン アイコン:** 機能に変化はないので、心配はいりません。</span><span class="sxs-lookup"><span data-stu-id="8ae84-557">**Your ribbon icons have a new look:** Don’t worry, everything works the same.</span></span> <span data-ttu-id="8ae84-558">さらに、どのサイズの画面でも、見た目がきれいです。</span><span class="sxs-lookup"><span data-stu-id="8ae84-558">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="8ae84-559">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-559">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="8ae84-560">**SMIME の暗号化および署名されたメールでは、既定で外部コンテンツのダウンロードをブロック:** SMIME プロトコルに脆弱性があるため、Outlook が SMIME の暗号化または署名されたメッセージへの外部コンテンツのダウンロードをブロックします。</span><span class="sxs-lookup"><span data-stu-id="8ae84-560">**Block download of external content by default in SMIME encrypted and signed emails:** Due to a vulnerability in the SMIME protocol - Outlook will block download of external content on messages that have been encrypted or signed over SMIME.</span></span> <span data-ttu-id="8ae84-561">セキュリティの脆弱性から保護するため、ユーザーは Outlook UI を通じて外部コンテンツをワンクリックでダウンロードすることはできません。</span><span class="sxs-lookup"><span data-stu-id="8ae84-561">Users will not be able to single-click download external content through Outlook UI to protect from the security vulnerability.</span></span> <span data-ttu-id="8ae84-562">[オプション] ダイアログには、ユーザーが以前の動作に戻すことができる新しいオプションが用意されています。</span><span class="sxs-lookup"><span data-stu-id="8ae84-562">There is a new option in the Options dialog to allow for users to revert to old behavior.</span></span>
- <span data-ttu-id="8ae84-563">**会議の転送を無効にする:** 出席者が会議を他のユーザーに転送できないようにします。</span><span class="sxs-lookup"><span data-stu-id="8ae84-563">**Turn off forwarding for a meeting:** Prevent attendees from forwarding your meeting to others.</span></span> <span data-ttu-id="8ae84-564">リボンに移動して、[応答オプション] をクリックするだけです。</span><span class="sxs-lookup"><span data-stu-id="8ae84-564">Just go to the ribbon and click Response Options.</span></span> [<span data-ttu-id="8ae84-565">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-565">Learn more</span></span>](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)
- <span data-ttu-id="8ae84-p171">**スケジュール アシスタントでの候補ユーザーの表示:** 会議のスケジュールを設定するときに、追加する出席者の候補が表示されます。スケジュール アシスタントと [宛先] 行を何度も切り替える必要はありません。[詳細情報](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)</span><span class="sxs-lookup"><span data-stu-id="8ae84-p171">**People suggestions in the Scheduling Assistant:** See recommendations for attendees to add when you schedule a meeting. No more switching back and forth between the Scheduling Assistant and the To line. [Learn more](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)</span></span>
- <span data-ttu-id="8ae84-569">**会議室の予約がさらに簡単に:** 複数の会議室のリストを使用して、会議室を検索します。選択した会議室を失うことなく、リストを切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-569">**Reserving a room just got easier:** Look for a conference room using more than one room list - and switch lists without losing rooms you've selected.</span></span>
- <span data-ttu-id="8ae84-570">**期間の新しい既定値:** [定期的なアイテム] ダイアログでは、期間に [終了日未定] の既定値が使われていました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-570">**New default for range of recurrence:** For the Recurrence dialog, the range of recurrence used to default for "No end date".</span></span> <span data-ttu-id="8ae84-571">これにより、長期間実行される定期的なアイテムが作成され、時間と共に破損する可能性がありました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-571">This facilitated the creation of long-running recurring series, which can become corrupted over time.</span></span> <span data-ttu-id="8ae84-572">既定値が予定表作成の推奨されるベスト プラクティスに一致するように、[定期的なアイテム] ダイアログ ボックスの既定値を [終了日] に更新します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-572">We are updating the default for the Recurrence dialog to "End by", such that our default value matches recommended best practices for calendaring.</span></span>
- <span data-ttu-id="8ae84-p173">**Outlook のアラーム ダイアログから Teams 会議に参加する:** Outlook が今後の会議についてユーザーに通知する際、会議が Teams のオンライン会議の場合には、[オンラインで参加] ボタンが表示されます。これは、Outlook のアラート ダイアログから Skype for Business 会議に参加する場合に似ています。</span><span class="sxs-lookup"><span data-stu-id="8ae84-p173">**Join Teams meetings from the Outlook Reminders dialog:** When Outlook reminds users of an upcoming meeting, it will show a Join Online button if the upcoming meeting is a Teams online meeting. This is similar to the experience of joining a Skype for Business meeting from the Outlook Reminders dialog.</span></span>
- <span data-ttu-id="8ae84-575">**過去のイベントのリマインダーの表示を停止:** 終了したイベントのリマインダーを自動的に破棄するようにカレンダーを設定することができます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-575">**Stop seeing reminders for past events:** You can set your calendar to automatically dismiss reminders for events after they've ended.</span></span> [<span data-ttu-id="8ae84-576">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-576">Learn more</span></span>](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- <span data-ttu-id="8ae84-577">**安全なリンクの背後にある URL を表示する:** 安全なリンクは、メールで受け取った悪意のある URL からユーザーを保護しますが、元の URL は非表示になります。</span><span class="sxs-lookup"><span data-stu-id="8ae84-577">**See the URL behind Safe Links:** Safe Links protects you from malicious URLS received in email but they hide the original URL.</span></span> <span data-ttu-id="8ae84-578">元の URL を確認するには、URL をマウスでポイントします。</span><span class="sxs-lookup"><span data-stu-id="8ae84-578">To see the original, hover your mouse over the URL.</span></span> <span data-ttu-id="8ae84-579">Advanced Threat Protection のライセンスが必要です。</span><span class="sxs-lookup"><span data-stu-id="8ae84-579">Requires an Advanced Threat Protection license.</span></span> [<span data-ttu-id="8ae84-580">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-580">Learn more</span></span>](https://products.office.com/exchange/advance-threat-protection)
- <span data-ttu-id="8ae84-581">**ズームとスティック:** メッセージを表示するたびにズームを調整するのではなく、すべてのメッセージに使用する既定値を選択します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-581">**Zoom and stick:** Instead of adjusting Zoom each time you read a message, choose a default to use for all your messages.</span></span> [<span data-ttu-id="8ae84-582">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-582">Learn more</span></span>](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)
- <span data-ttu-id="8ae84-583">**メッセージ暗号化: 暗号化のみ IRM ポリシー:** 新しい暗号化のみオプションは、Office 365 Message Encryption ユーザーの [オプション] > [アクセス許可] に表示されます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-583">**Message Encryption: encrypt-only IRM policy:** New encrypt-only option appears in the Options > Permissions menu for Office 365 Message Encryption users.</span></span> <span data-ttu-id="8ae84-584">このオプションを使用すると、メッセージを暗号化して、組織の内外のユーザーに送信できます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-584">This option allows you to encrypt a message and send it to anyone, inside or outside your organization.</span></span>
- <span data-ttu-id="8ae84-585">**BCC で受け取った場合の警告:** ブラインド カーボン コピーで受け取ったメールに対し、誤って全員に返信する前に、BCC のヒントで警告されます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-585">**Warning when you've been BCC'ed:** The BCC infotip will warn you before you accidentally reply all to a mail that you've been blind carbon copied on.</span></span>
- <span data-ttu-id="8ae84-586">**洗練された [宛先] 行:** メッセージの宛先を指定するために [宛先] 行をクリックすると、選択されそうな受信者の候補が表示されます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-586">**A smarter To: line:** When you click the To: line to address a message, we suggest recipients you're likely to choose.</span></span> <span data-ttu-id="8ae84-587">さらに、ユーザーの画像が表示されるので、正しいユーザーに送信しようとしていることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-587">Plus, you can see their picture, so you know yo’re sending to the right person.</span></span> [<span data-ttu-id="8ae84-588">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-588">Learn more</span></span>](https://support.office.com/article/147208AF-CA8E-4CDF-B71F-77BA81A54069)
- <span data-ttu-id="8ae84-589">**フィルターが適用された SVG を挿入する機能:** Office ユーザーは、フィルターが適用された SVG を挿入できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-589">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them.</span></span> [<span data-ttu-id="8ae84-590">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-590">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- <span data-ttu-id="8ae84-591">**改善された高解像度ディスプレイのサポート:** 複数のモニター、またはドッキングでラップトップを使用する場合、各ディスプレイの倍率設定が異なっていても Office アプリがすべてのディスプレイで鮮明に表示されるようになります。</span><span class="sxs-lookup"><span data-stu-id="8ae84-591">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="8ae84-592">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-592">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="8ae84-593">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8ae84-593">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="8ae84-594">\*\*すばやく始めましょう \*\*新しくデザインされたスタートページは、最近開いたドキュメントを前面と中央に配置します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-594">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="8ae84-595">以前より少ないクリック数でファイルにアクセスし、そこからすぐアカウント設定またはオプションを開きます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-595">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="8ae84-596">**ハンズフリーで入力:** マイクは用意しましたか？</span><span class="sxs-lookup"><span data-stu-id="8ae84-596">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="8ae84-597">[ディクテーション] をクリックして、発話すると PowerPoint によって入力されるのを確認してください。</span><span class="sxs-lookup"><span data-stu-id="8ae84-597">Click Dictate and watch PowerPoint type while you talk.</span></span> [<span data-ttu-id="8ae84-598">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-598">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="8ae84-599">**新しい見た目のリボン アイコン:** 機能に変化はないので、心配はいりません。</span><span class="sxs-lookup"><span data-stu-id="8ae84-599">**Your ribbon icons have a new look:** Don’t worry, everything works the same.</span></span> <span data-ttu-id="8ae84-600">さらに、どのサイズの画面でも、見た目がきれいです。</span><span class="sxs-lookup"><span data-stu-id="8ae84-600">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="8ae84-601">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-601">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="8ae84-602">**改善された高解像度ディスプレイのサポート:** 複数のモニター、またはドッキングでラップトップを使用する場合、各ディスプレイの倍率設定が異なっていても Office アプリがすべてのディスプレイで鮮明に表示されるようになります。</span><span class="sxs-lookup"><span data-stu-id="8ae84-602">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="8ae84-603">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-603">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- <span data-ttu-id="8ae84-604">**ハイパーリンクの色の設定:** ハイパーリンクの色は青だけではなくなりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-604">**Hyperlinks in living color:** Hyperlinks aren't just blue anymore.</span></span> <span data-ttu-id="8ae84-605">お好みのフォント色を適用してください。</span><span class="sxs-lookup"><span data-stu-id="8ae84-605">Apply any font color you like.</span></span> [<span data-ttu-id="8ae84-606">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-606">Learn more</span></span>](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)
- <span data-ttu-id="8ae84-607">**スライドを活気づかせる:** アニメーション 3D グラフィックスを挿入して、鼓動する心臓、周回する惑星、暴れ回るティラノサウルスを画面上に表示できます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-607">**Watch your slides come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage across the screen.</span></span> [<span data-ttu-id="8ae84-608">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-608">Learn more</span></span>](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- <span data-ttu-id="8ae84-p187">**スケッチするだけで自動的に洗練される:** 手書きのテキストや図形が洗練された図表に変更されます。インク ストロークを選ぶだけで機能を利用できます。[詳細情報](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="8ae84-p187">**You sketch, we polish:** We change hand-drawn text and shapes into refined diagrams. Just select your ink strokes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>
- <span data-ttu-id="8ae84-p188">**画像の背後を見えるようにする:** ワークシートに画像を挿入し、既定の設定から選択して、透明度の変化を確認するだけです。[詳細情報](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="8ae84-p188">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="8ae84-615">**Microsoft Stream に公開:** Microsoft Stream を使用して、組織内でより安全にビデオとプレゼンテーションを共有できます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-615">**Publish to Microsoft Stream:** Share a presentation as a video more securely within your organization by using Microsoft Stream.</span></span> [<span data-ttu-id="8ae84-616">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-616">Learn more</span></span>](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- <span data-ttu-id="8ae84-617">**4K ビデオにエクスポート:** プレゼンテーションをビデオにエクスポートするときに、4K の解像度がオプションになりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-617">**Export to 4K video:** When you export a presentation to video, 4K resolution is now an option.</span></span>  [<span data-ttu-id="8ae84-618">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-618">Learn more</span></span>](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- <span data-ttu-id="8ae84-619">**フィルターが適用された SVG を挿入する機能:** Office ユーザーは、フィルターが適用された SVG を挿入できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-619">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them.</span></span> [<span data-ttu-id="8ae84-620">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-620">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- <span data-ttu-id="8ae84-621">**大きなファイルがより速く開くようになりました:** OneDrive または SharePoint に保存されているファイルを開くと、画像、ビデオ、およびその他の大きな要素がバックグラウンドでダウンロードされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-621">**Large files now open faster:** Images, videos, and other large elements now download in the background when opening files stored on OneDrive or SharePoint.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="8ae84-622">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8ae84-622">Word: Feature updates</span></span>

- <span data-ttu-id="8ae84-623">\*\*すばやく始めましょう \*\*新しくデザインされたスタートページは、最近開いたドキュメントを前面と中央に配置します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-623">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="8ae84-624">以前より少ないクリック数でファイルにアクセスし、そこからすぐアカウント設定またはオプションを開きます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-624">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="8ae84-625">**ハンズフリーで入力:** マイクは用意しましたか。</span><span class="sxs-lookup"><span data-stu-id="8ae84-625">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="8ae84-626">[ディクテーション] をクリックして、発話すると Word によって入力されるのを確認してください。</span><span class="sxs-lookup"><span data-stu-id="8ae84-626">Click Dictate and watch Word type while you talk.</span></span> [<span data-ttu-id="8ae84-627">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-627">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="8ae84-p194">**文書を活気づかせる:** アニメーション 3D グラフィックスを挿入して、鼓動する心臓、周回する惑星、暴れ回るティラノサウルスをページ上に表示できます。[詳細情報](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span><span class="sxs-lookup"><span data-stu-id="8ae84-p194">**Watch your documents come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage across the page. [Learn more](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span></span>
- <span data-ttu-id="8ae84-630">**新しい見た目のリボン アイコン:** 機能に変化はないので、心配はいりません。</span><span class="sxs-lookup"><span data-stu-id="8ae84-630">**Your ribbon icons have a new look:** Don’t worry, everything works the same.</span></span> <span data-ttu-id="8ae84-631">さらに、どのサイズの画面でも、見た目がきれいです。</span><span class="sxs-lookup"><span data-stu-id="8ae84-631">Plus, they look great on screens of all sizes.</span></span> [<span data-ttu-id="8ae84-632">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-632">Learn more</span></span>](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- <span data-ttu-id="8ae84-p196">**画像の背後を見えるようにする:** ワークシートに画像を挿入し、既定の設定から選択して、透明度の変化を確認するだけです。[詳細情報](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="8ae84-p196">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="8ae84-636">**フィルターが適用された SVG を挿入する機能:** Office ユーザーは、フィルターが適用された SVG を挿入できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-636">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them.</span></span> [<span data-ttu-id="8ae84-637">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-637">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- <span data-ttu-id="8ae84-638">**改善された高解像度ディスプレイのサポート:** 複数のモニター、またはドッキングでラップトップを使用する場合、各ディスプレイの倍率設定が異なっていても Office アプリがすべてのディスプレイで鮮明に表示されるようになります。</span><span class="sxs-lookup"><span data-stu-id="8ae84-638">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="8ae84-639">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-639">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- <span data-ttu-id="8ae84-p199">**LinkedIn を活用して、最適な履歴書または CV を作成します:** 履歴書アシスタントを使用して、特定の役割に関する職歴、提案されているスキルなどを表示できます。 [詳細情報](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)</span><span class="sxs-lookup"><span data-stu-id="8ae84-p199">**Write your best resume or CV with help from LinkedIn:** With Resume Assistant, see work experiences, suggested skills, and more for a given role. [Learn more](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="8ae84-642">Project: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8ae84-642">Project: Feature updates</span></span>

- <span data-ttu-id="8ae84-643">**タスク ボード カードに詳細を表示する:** タイトルだけでは内容が伝わらない場合は、最も重要な詳細がすべて表示されるようにタスク ボード カードをカスタマイズできます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-643">**See more info on Task Board cards:** When the title alone doesn’t tell the story, customize your Task Board cards to show all the most important details.</span></span> [<span data-ttu-id="8ae84-644">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-644">Learn more</span></span>](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)
- <span data-ttu-id="8ae84-645">**Office の外観が新しくなる:** Office アプリに、よりシンプルでアクセスしやすい最新のアイコンが加わり、リボンの外観が、Office アプリで使用可能な豊富なコラボレーション機能を強調するように更新されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-645">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="publisher-feature-updates"></a><span data-ttu-id="8ae84-646">Publisher: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8ae84-646">Publisher: Feature updates</span></span>

- <span data-ttu-id="8ae84-647">**Office の外観が新しくなる:** Office アプリに、よりシンプルでアクセスしやすい最新のアイコンが加わり、リボンの外観が、Office アプリで使用可能な豊富なコラボレーション機能を強調するように更新されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-647">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="8ae84-648">Visio: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8ae84-648">Visio: Feature updates</span></span>

- <span data-ttu-id="8ae84-649">**新しい図面でアイコンを楽しむ:** 分析、アート、お祝い、顔文字、スポーツなどのアイコンが含まれる 26 種類の新しいステンシルから選択できます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-649">**Enjoy an iconic moment in your next diagram:** Pick from 26 new stencils with icons for analytics, arts, celebration, faces, sports, and more.</span></span>
- <span data-ttu-id="8ae84-650">**Office の外観が新しくなる:** Office アプリに、よりシンプルでアクセスしやすい最新のアイコンが加わり、リボンの外観が、Office アプリで使用可能な豊富なコラボレーション機能を強調するように更新されました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-650">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="office-suite-feature-updates"></a><span data-ttu-id="8ae84-651">Office スイート: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8ae84-651">Office Suite: Feature updates</span></span>

- <span data-ttu-id="8ae84-p201">**Office のサード パーティ アプリケーションでは office.js api を使用した SVG の挿入をサポート:** Office アドインとも呼ばれるサード パーティ アプリケーションで SVG を挿入できるようになりました。ユーザーは、個人の SVG コレクションを Office に結び付けることができます。開発者は、Office.js API を使用してこの機能を利用できます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-p201">**Office 3rd Party Applications now have insert SVG support using the office.js api:** 3rd party applications also known as add-ins in Office now have the ability to insert SVG's. Users can now connect their personal collection of SVG's to Office. Developers can use this feature by using the Office.js API.</span></span>
- <span data-ttu-id="8ae84-655">**Microsoft Teams のインストール:** Microsoft Teams は、Office 365 ProPlus の既存のインストールに既定でインストールされています。</span><span class="sxs-lookup"><span data-stu-id="8ae84-655">**Installation of Microsoft Teams:**  Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="8ae84-656">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-656">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

### <a name="skype-for-business-feature-updates"></a><span data-ttu-id="8ae84-657">Skype for Business: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8ae84-657">Skype for Business: Feature updates</span></span>

- <span data-ttu-id="8ae84-658">**改善された高解像度ディスプレイのサポート:** 複数のモニター、またはドッキングでラップトップを使用する場合、各ディスプレイの倍率設定が異なっていても Office アプリがすべてのディスプレイで鮮明に表示されるようになります。</span><span class="sxs-lookup"><span data-stu-id="8ae84-658">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="8ae84-659">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-659">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="teams-feature-updates"></a><span data-ttu-id="8ae84-660">Access: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8ae84-660">Teams: Feature updates</span></span>

- <span data-ttu-id="8ae84-661">**改善された高解像度ディスプレイのサポート:** 複数のモニター、またはドッキングでラップトップを使用する場合、各ディスプレイの倍率設定が異なっていても Office アプリがすべてのディスプレイで鮮明に表示されるようになります。</span><span class="sxs-lookup"><span data-stu-id="8ae84-661">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings.</span></span> [<span data-ttu-id="8ae84-662">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8ae84-662">Learn more</span></span>](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

## <a name="version-1808-february-12"></a><span data-ttu-id="8ae84-663">バージョン 1808: 2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="8ae84-663">Version 1808: February 12</span></span>
<span data-ttu-id="8ae84-664">*バージョン 1808 (ビルド 10730.20280)*</span><span class="sxs-lookup"><span data-stu-id="8ae84-664">*Version 1808 (Build 10730.20280)*</span></span> 

### <a name="access-non-security-updates"></a><span data-ttu-id="8ae84-665">Access: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-665">Access: Non-Security updates</span></span> 

- <span data-ttu-id="8ae84-666">この更新プログラムでは、Access に日本の新元号のサポートを追加します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-666">This update adds support for new Japanese eras to Access.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="8ae84-667">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-667">Outlook: Non-Security updates</span></span> 

- <span data-ttu-id="8ae84-668">存在しなくなったフォルダーを参照するルールで、ルールを管理しようとしたときにエラーが表示される問題と、クライアント側のルールの実行に失敗する問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-668">Addresses an issue that caused users with rules that refer to a folder that no longer exist to see an error when trying to manage rules and to see client-side rules fail to run.</span></span>
- <span data-ttu-id="8ae84-669">キャッシュされた代理メールボックスが予測不可能な間隔で頻繁にハングする問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-669">Addresses an issue that caused users with cached delegate mailboxes to encounter frequent hangs at unpredictable intervals.</span></span>
- <span data-ttu-id="8ae84-670">会議の終了時間が翌日の午前 0 時に設定されていると、いくつかのビューで「終日会議」が意図したものよりも 1 日長く表示される問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-670">Addresses an issue that caused All Day Meetings to appear to span one more day than intended in some views due to the end time of the meeting being set to midnight of the following day.</span></span>
- <span data-ttu-id="8ae84-671">日本の元号を参照する新しい予約または会議を作成するとハングする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-671">Fixed a hang when creating new appointments or meetings that reference Japanese eras.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="8ae84-672">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-672">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="8ae84-673">[Office 365 の一元展開](https://docs.microsoft.com/office/dev/add-ins/publish/centralized-deployment)を使用して展開したアドインが機能停止して使用できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-673">Fixed issue where Add-ins, deployed using [O365 Office centralized deployment](https://docs.microsoft.com/office/dev/add-ins/publish/centralized-deployment), were freezing and unusable.</span></span>


## <a name="version-1808-january-8"></a><span data-ttu-id="8ae84-674">バージョン 1808: 1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="8ae84-674">Version 1808: January 8</span></span>
<span data-ttu-id="8ae84-675">*バージョン 1808 (ビルド 10730.20264)*</span><span class="sxs-lookup"><span data-stu-id="8ae84-675">*Version 1808 (Build 10730.20264)*</span></span> 

### <a name="outlook-non-security-updates"></a><span data-ttu-id="8ae84-676">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-676">Outlook: Non-security updates</span></span> 

- <span data-ttu-id="8ae84-677">空き時間検索でエラーの原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8ae84-677">Fixed an issue that caused users to experience calendar synchronization errors.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="8ae84-678">Word: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8ae84-678">Word: Non-security updates</span></span>

- <span data-ttu-id="8ae84-679">オープン パフォーマンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="8ae84-679">Improve open performance.</span></span>


> [!NOTE]
> <span data-ttu-id="8ae84-680">Office の使用で問題がある場合は、[Microsoft の回答フォーラム](https://answers.microsoft.com/)に関するページまたは「[Microsoft Tech Community](https://techcommunity.microsoft.com/)」に質問を投稿するか、[サポート](https://support.microsoft.com/contactus)に問い合わせてサポートを受けることができます。</span><span class="sxs-lookup"><span data-stu-id="8ae84-680">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
