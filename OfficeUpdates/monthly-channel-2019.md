---
title: 2019 年の毎月のチャネル リリースのリリース ノート
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Office 365 ProPlus 用の 2019 年の毎月のチャネル リリースのリリース ノートを IT プロフェッショナルに提供します
ms.openlocfilehash: 4d5c623be109cc8a0b21b3c90e91ca981ca2c2e8
ms.sourcegitcommit: 519689175e202f7059ab9e49d70ea0ce6d23075e
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/18/2019
ms.locfileid: "40302976"
---
# <a name="release-notes-for-monthly-channel-releases-in-2019"></a><span data-ttu-id="66f29-103">2019 年の毎月のチャネル リリースのリリース ノート</span><span class="sxs-lookup"><span data-stu-id="66f29-103">Release notes for Monthly Channel releases in 2019</span></span>

<span data-ttu-id="66f29-104">これらのリリースノートには、2019 年の Office 365 ProPlus、Visio Pro for Office 365、Project Online デスクトップ クライアント、および Office 365 Business の毎月の更新プログラム チャンネルに含まれる新機能およびセキュリティ以外の更新に関する情報が記載されています。</span><span class="sxs-lookup"><span data-stu-id="66f29-104">These release notes provide information about new features and non-security updates that are included in Monthly Channel updates to Office 365 ProPlus in 2019, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

 > [!NOTE]
>- <span data-ttu-id="66f29-105">Microsoft では多くの場合、一定期間にわたって毎月、機能 (および場合によっては修正プログラム) を展開します。</span><span class="sxs-lookup"><span data-stu-id="66f29-105">We often roll out features (and sometimes even fixes) to Monthly over a period of time.</span></span>  <span data-ttu-id="66f29-106">ここで説明した内容がすぐに表示されない場合は、間もなく利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="66f29-106">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="66f29-107">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-107">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
>- <span data-ttu-id="66f29-108">Microsoft Teams の Office 365 ProPlus の既存のインストールについて: 7月の上旬から、Office 365 ProPlus (および Office 365 Business) の更新に Microsoft Teams が含まれます。</span><span class="sxs-lookup"><span data-stu-id="66f29-108">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in early July, updates to Office 365 ProPlus (and Office 365 Business) will include Microsoft Teams.</span></span>  <span data-ttu-id="66f29-109">Teams が追加される日付は、使用している更新プログラム チャネルによって異なります。</span><span class="sxs-lookup"><span data-stu-id="66f29-109">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="66f29-110">追加情報については、「[Office 365 ProPlus と同時に Microsoft Teams を展開する](https://docs.microsoft.com/DeployOffice/teams-install)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="66f29-110">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/teams-install) for additional information.</span></span>

## <a name="version-1911-december-10"></a><span data-ttu-id="66f29-111">バージョン 1911: 12 月 10 日</span><span class="sxs-lookup"><span data-stu-id="66f29-111">Version 1911: December 10</span></span>
<span data-ttu-id="66f29-112">*バージョン 1911 (ビルド 12228.20364)*</span><span class="sxs-lookup"><span data-stu-id="66f29-112">*Version 1911 (Build 12228.20364)*</span></span>

<span data-ttu-id="66f29-113">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="66f29-113">Security updates listed [here](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="66f29-115">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="66f29-115">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="66f29-116">Excel</span><span class="sxs-lookup"><span data-stu-id="66f29-116">Excel</span></span>

- <span data-ttu-id="66f29-117">この変更は、ソフトウェア レンダリングを活用することにより、特定の Intel グラフィック ドライバーの問題を回避します。</span><span class="sxs-lookup"><span data-stu-id="66f29-117">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="66f29-118">ピボット グラフの右クリック メニューを修正して、[詳細の表示] オプションを有効にしました。</span><span class="sxs-lookup"><span data-stu-id="66f29-118">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

### <a name="outlook"></a><span data-ttu-id="66f29-119">Outlook</span><span class="sxs-lookup"><span data-stu-id="66f29-119">Outlook</span></span>

- <span data-ttu-id="66f29-120">Web アドインがデジタル著作権管理 (DRM) メッセージにアクセスする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="66f29-120">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1911-december-03"></a><span data-ttu-id="66f29-122">バージョン 1911: 12 月 3 日</span><span class="sxs-lookup"><span data-stu-id="66f29-122">Version 1911: December 03</span></span>
<span data-ttu-id="66f29-123">*バージョン 1911 (ビルド 12228.20332)*</span><span class="sxs-lookup"><span data-stu-id="66f29-123">*Version 1911 (Build 12228.20332)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="66f29-125">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-125">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="66f29-126">Excel</span><span class="sxs-lookup"><span data-stu-id="66f29-126">Excel</span></span>

- <span data-ttu-id="66f29-127">**複数の値を返す式を入力する:** 複数の値を返す式を素早く入力できるようになりました。隣接するセルに自動的に入力されます。</span><span class="sxs-lookup"><span data-stu-id="66f29-127">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="66f29-128">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-128">Learn more</span></span>](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)

- <span data-ttu-id="66f29-129">**6 つの強力な機能:** スプレッドシートを強化する 6 つの新しい関数が追加されました。FILTER、SORT、SORTBY、UNIQUE、SEQUENCE、RANDARRAY です。</span><span class="sxs-lookup"><span data-stu-id="66f29-129">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span> [<span data-ttu-id="66f29-130">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-130">Learn more</span></span>](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- <span data-ttu-id="66f29-131">**データ ビジュアライザー アドイン:** Excel から Visio フローチャートをすばやく作成します。</span><span class="sxs-lookup"><span data-stu-id="66f29-131">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="66f29-132">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-132">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="66f29-133">Word</span><span class="sxs-lookup"><span data-stu-id="66f29-133">Word</span></span>

- <span data-ttu-id="66f29-134">**共同編集の改善:** コンテンツの変更をリアルタイムでユーザーが受け取れるようにすることで、共同編集のエクスペリエンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-134">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="66f29-137">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="66f29-137">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="66f29-138">Access</span><span class="sxs-lookup"><span data-stu-id="66f29-138">Access</span></span>

- <span data-ttu-id="66f29-139">更新クエリが実行されるか、SQL で UPDATE ステートメントが使用されるときに「&quot;クエリは破損しています&quot;」というエラーを発生させる場合のある Microsoft Access の問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-139">Fixed an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="66f29-140">Excel</span><span class="sxs-lookup"><span data-stu-id="66f29-140">Excel</span></span>

- <span data-ttu-id="66f29-141">信頼されていないネットワーク共有から保護されたファイルを編集する際に、Excel にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="66f29-141">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="66f29-142">ブックが開かれていない状態で最近使用したファイルを検索する際にクラッシュが発生する可能性がある問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-142">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

### <a name="outlook"></a><span data-ttu-id="66f29-143">Outlook</span><span class="sxs-lookup"><span data-stu-id="66f29-143">Outlook</span></span>

- <span data-ttu-id="66f29-144">アカウント作成コンテキストからサポートに連絡しようとすると、ユーザーに [&quot;OK&quot;] ボタンのある空のメッセージ ボックスが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-144">Addressed an issue that caused users to see an empty message box with an &quot;OK&quot; button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="66f29-145">2019 年に ブラジル タイム ゾーンを使用している場合、2020 年の定期的な会議や予定が間違った時間帯に表示されます。</span><span class="sxs-lookup"><span data-stu-id="66f29-145">When using the Brazilia time zone in the year 2019, recurring meetings and appointments are displayed in the wrong timeslot for the year 2020.</span></span> <span data-ttu-id="66f29-146">この変更は、ブラジル タイム ゾーンに設定されているクライアントまたは同タイム ゾーンで設定された会議や予定に影響を与えます。</span><span class="sxs-lookup"><span data-stu-id="66f29-146">This change is relevant for clients set in the Brazilia time zone or for meetings and appointments set in that time zone.</span></span> 

- <span data-ttu-id="66f29-147">ユーザーが [ルール] ダイアログを開くと、「&quot;このコンピューターのルールは、Microsoft Exchange のルールと異なります&quot;」というメッセージが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-147">Addressed an issue that caused users to see a &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="66f29-148">SMIME アルゴリズムの選択に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-148">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="66f29-149">会議の [場所] フィールドが予期せず更新される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-149">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="66f29-150">Office スイート</span><span class="sxs-lookup"><span data-stu-id="66f29-150">Office Suite</span></span>

- <span data-ttu-id="66f29-151">Office の更新プログラムが、意図したソース (ローカル共有、ネットワーク共有、構成マネージャー
で提供される場所など) からではなく、予期せずに Office CDN からファイルをダウンロードする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-151">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="66f29-152">ODT と GPO の更新期限設定で、相対期限の設定後、初回のみしか機能しない問題が修正されました。修正により、2 回目以降の更新プログラムで相対期限を使用きるようになりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-152">Fixed an issue in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-november-22"></a><span data-ttu-id="66f29-154">バージョン 1910: 11 月 22 日</span><span class="sxs-lookup"><span data-stu-id="66f29-154">Version 1910: November 22</span></span>
<span data-ttu-id="66f29-155">*バージョン 1910 (ビルド 12130.20410)*</span><span class="sxs-lookup"><span data-stu-id="66f29-155">*Version 1910 (Build 12130.20410)*</span></span>
* <span data-ttu-id="66f29-156">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="66f29-156">Various bugs and performance fixes.</span></span>

## <a name="version-1910-november-18"></a><span data-ttu-id="66f29-157">バージョン 1910: 11 月 18 日</span><span class="sxs-lookup"><span data-stu-id="66f29-157">Version 1910: November 18</span></span>
<span data-ttu-id="66f29-158">*バージョン 1910 (ビルド 12130.20390)*</span><span class="sxs-lookup"><span data-stu-id="66f29-158">*Version 1910 (Build 12130.20390)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="66f29-160">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="66f29-160">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="66f29-161">Access</span><span class="sxs-lookup"><span data-stu-id="66f29-161">Access</span></span>

- <span data-ttu-id="66f29-162">更新クエリを実行すると "クエリが破損しています" という誤ったエラー メッセージが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-162">Fixed an issue where running an Update query would incorrectly give an error message: "Query is corrupt".</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-november-12"></a><span data-ttu-id="66f29-164">バージョン 1910: 11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="66f29-164">Version 1910: November 12</span></span>
<span data-ttu-id="66f29-165">*バージョン 1910 (ビルド 12130.20344)*</span><span class="sxs-lookup"><span data-stu-id="66f29-165">*Version 1910 (Build 12130.20344)*</span></span>

<span data-ttu-id="66f29-166">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="66f29-166">Security updates listed [here](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="66f29-168">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="66f29-168">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="66f29-169">Outlook</span><span class="sxs-lookup"><span data-stu-id="66f29-169">Outlook</span></span>

- <span data-ttu-id="66f29-170">会議の場所フィールドが予期せず変更される原因となる問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-170">Addressed an issue that caused users to see the location field in meetings change unexpectedly.</span></span>

- <span data-ttu-id="66f29-171">アカウント作成コンテキストからサポートに連絡しようとすると、ユーザーに [&quot;OK&quot;] ボタンのある空のメッセージ ボックスが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-171">Addressed an issue that caused users to see an empty message box with an &quot;OK&quot; button when trying to contact support from the Account Creation context.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-october-30"></a><span data-ttu-id="66f29-173">バージョン 1910: 10 月 30 日</span><span class="sxs-lookup"><span data-stu-id="66f29-173">Version 1910: October 30</span></span>
<span data-ttu-id="66f29-174">*バージョン 1910 (ビルド 12130.20272)*</span><span class="sxs-lookup"><span data-stu-id="66f29-174">*Version 1910 (Build 12130.20272)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="66f29-175">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="66f29-175">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="66f29-176">Outlook</span><span class="sxs-lookup"><span data-stu-id="66f29-176">Outlook</span></span>

- <span data-ttu-id="66f29-177">検索に関するフィードバックのエクスペリエンスでハングアップする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-177">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="66f29-179">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-179">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="66f29-180">Excel</span><span class="sxs-lookup"><span data-stu-id="66f29-180">Excel</span></span>

- <span data-ttu-id="66f29-181">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="66f29-181">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="66f29-182">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-182">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="66f29-183">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="66f29-183">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="66f29-184">**ドキュメントとメールに秘密度ラベルを適用する:** ファイルとメールに秘密度ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="66f29-184">**Apply sensitivity labels to your documents and emails:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span> [<span data-ttu-id="66f29-185">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-185">Learn more</span></span>](https://aka.ms/officemipdocs)

### <a name="outlook"></a><span data-ttu-id="66f29-186">Outlook</span><span class="sxs-lookup"><span data-stu-id="66f29-186">Outlook</span></span>

- <span data-ttu-id="66f29-187">**ドキュメントとメールに秘密度ラベルを適用する:** ファイルとメールに秘密度ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="66f29-187">**Apply sensitivity labels to your documents and emails:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span> [<span data-ttu-id="66f29-188">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-188">Learn more</span></span>](https://aka.ms/officemipdocs)

### <a name="powerpoint"></a><span data-ttu-id="66f29-189">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="66f29-189">PowerPoint</span></span>

- <span data-ttu-id="66f29-190">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="66f29-190">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="66f29-191">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-191">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="66f29-192">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="66f29-192">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="66f29-193">**ドキュメントとメールに秘密度ラベルを適用する:** ファイルとメールに秘密度ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="66f29-193">**Apply sensitivity labels to your documents and emails:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span> [<span data-ttu-id="66f29-194">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-194">Learn more</span></span>](https://aka.ms/officemipdocs)

### <a name="word"></a><span data-ttu-id="66f29-195">Word</span><span class="sxs-lookup"><span data-stu-id="66f29-195">Word</span></span>

- <span data-ttu-id="66f29-196">**共同編集の改善**: 変更を追跡したドキュメントで共同編集を行う際の Word のパフォーマンスが改善されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-196">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="66f29-197">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="66f29-197">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="66f29-198">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-198">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="66f29-199">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="66f29-199">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="66f29-200">**3D オブジェクトのマージによって引き起こされるドキュメント破損の問題を修正しました。:** 3D オブジェクトのマージによって引き起こされるドキュメント破損の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-200">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="66f29-201">**ドキュメントとメールに秘密度ラベルを適用する:** ファイルとメールに秘密度ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="66f29-201">**Apply sensitivity labels to your documents and emails:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span> [<span data-ttu-id="66f29-202">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-202">Learn more</span></span>](https://aka.ms/officemipdocs)

### <a name="office-suite"></a><span data-ttu-id="66f29-203">Office スイート</span><span class="sxs-lookup"><span data-stu-id="66f29-203">Office Suite</span></span>

- <span data-ttu-id="66f29-204">**Office 365 ProPlus の既存のインストールに Microsoft Teams をインストールする:** 6 月下旬から、Microsoft Teams は、これらのインストールの更新時に、Office 365 ProPlus (および Office 365 Business) の既存のインストールに含まれます。</span><span class="sxs-lookup"><span data-stu-id="66f29-204">**Install Microsoft Teams on existing installations of Office 365 ProPlus:** Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="66f29-205">Teams が追加される日にちは、使用している更新プログラム チャネルによって異なります。</span><span class="sxs-lookup"><span data-stu-id="66f29-205">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="66f29-206">追加情報については、「Office 365 ProPlus と同時に Microsoft Teams を展開する」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="66f29-206">Please refer to Deploy Microsoft Teams with Office 365 ProPlus for additional information.</span></span> [<span data-ttu-id="66f29-207">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-207">Learn More</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1909-october-22"></a><span data-ttu-id="66f29-209">バージョン 1909: 10 月 22 日</span><span class="sxs-lookup"><span data-stu-id="66f29-209">Version 1909: October 22</span></span>
<span data-ttu-id="66f29-210">*バージョン 1909 (ビルド 12026.20344)*</span><span class="sxs-lookup"><span data-stu-id="66f29-210">*Version 1909 (Build 12026.20344)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="66f29-212">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-212">Non-security updates</span></span>
### <a name="project"></a><span data-ttu-id="66f29-213">Project</span><span class="sxs-lookup"><span data-stu-id="66f29-213">Project</span></span>
- <span data-ttu-id="66f29-214">読み取り専用のプロジェクトを開いたときに多数のメッセージを受けることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-214">Resolved an issue where users could get several messages when opening a read-only project.</span></span>

### <a name="office-suite"></a><span data-ttu-id="66f29-215">Office スイート</span><span class="sxs-lookup"><span data-stu-id="66f29-215">Office Suite</span></span>

- <span data-ttu-id="66f29-216">Office ユーザーのセキュリティを保護するために、Microsoft Office の更新プログラムは SHA-2 アルゴリズムのみを使用して署名されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-216">To protect Office customers’ security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span><br></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="october-15"></a><span data-ttu-id="66f29-218">10 月 15 日</span><span class="sxs-lookup"><span data-stu-id="66f29-218">October 15</span></span>

### <a name="non-security-updates"></a><span data-ttu-id="66f29-219">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-219">Non-security updates</span></span>

### <a name="office-suite"></a><span data-ttu-id="66f29-220">Office スイート</span><span class="sxs-lookup"><span data-stu-id="66f29-220">Office Suite</span></span>
- <span data-ttu-id="66f29-221">12130.20184 よりも古いビルドで 2019 年 10 月 14 日に投稿された保存の問題を解決するために、一時的に [クラウド保存] ダイアログを無効にしました。</span><span class="sxs-lookup"><span data-stu-id="66f29-221">We have temporarily disabled the Cloud Save dialog to address the saving issue we posted on October 14, 2019 for builds older than 12130.20184.</span></span> <span data-ttu-id="66f29-222">この機能は、まもなく有効になります。</span><span class="sxs-lookup"><span data-stu-id="66f29-222">This feature will be re-enabled soon.</span></span>


## <a name="version-1909-october-14"></a><span data-ttu-id="66f29-223">バージョン 1909: 10 月 14 日</span><span class="sxs-lookup"><span data-stu-id="66f29-223">Version 1909: October 14</span></span>
<span data-ttu-id="66f29-224">*バージョン 1909 (ビルド 12026.20334)*</span><span class="sxs-lookup"><span data-stu-id="66f29-224">*Version 1909 (Build 12026.20334)*</span></span>

### <a name="non-security-updates"></a><span data-ttu-id="66f29-225">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-225">Non-security updates</span></span>

### <a name="office-suite"></a><span data-ttu-id="66f29-226">Office スイート</span><span class="sxs-lookup"><span data-stu-id="66f29-226">Office Suite</span></span>

- <span data-ttu-id="66f29-227">12130.20184 よりも古いビルドでユーザーが Word、Excel、および PowerPoint 2019 のドキュメントを保存できなくなるという問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-227">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint 2019 documents for builds older than 12130.20184.</span></span>  <span data-ttu-id="66f29-228">この問題は、[保存] アイコンをクリックしたり Ctrl キーを押しながら S キーを押したりした後に、新しいファイルを作成して [名前を付けて保存] ダイアログを表示するユーザーに影響を与えます。</span><span class="sxs-lookup"><span data-stu-id="66f29-228">This issue affects users that create a new file and bring up the “Save As” dialog after clicking on the Save icon or pressing Ctrl + S.</span></span>


## <a name="version-1909-october-08"></a><span data-ttu-id="66f29-229">バージョン 1909: 10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="66f29-229">Version 1909: October 08</span></span>
<span data-ttu-id="66f29-230">*バージョン 1909 (ビルド 12026.20320)*</span><span class="sxs-lookup"><span data-stu-id="66f29-230">*Version 1909 (Build 12026.20320)*</span></span>

<span data-ttu-id="66f29-231">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="66f29-231">Security updates listed [here](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="66f29-233">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-233">Non-security updates</span></span>

### <a name="outlook"></a><span data-ttu-id="66f29-234">Outlook</span><span class="sxs-lookup"><span data-stu-id="66f29-234">Outlook</span></span>

- <span data-ttu-id="66f29-235">Outlook の添付ファイルのブロック ロジックが Python による添付ファイルもブロックする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-235">Fixed an issue with attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="66f29-236">ユーザーが定期的な予定表の一部のインスタンスを開けない原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-236">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="66f29-237">ユーザーが Outlook プロセスでメモリ リークを観測する原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-237">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="66f29-238">ユーザーがプロフィールの作成中にクラッシュを発生させる原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-238">Addressed an issue that caused users to experience a crash during profile creation.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1909-september-30"></a><span data-ttu-id="66f29-240">バージョン 1909: 9 月 30 日</span><span class="sxs-lookup"><span data-stu-id="66f29-240">Version 1909: September 30</span></span>
<span data-ttu-id="66f29-241">*バージョン 1909 (ビルド 12026.20264)*</span><span class="sxs-lookup"><span data-stu-id="66f29-241">*Version 1909 (Build 12026.20264)*</span></span>
* <span data-ttu-id="66f29-242">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="66f29-242">Various bugs and performance fixes.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="66f29-244">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-244">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="66f29-245">Access</span><span class="sxs-lookup"><span data-stu-id="66f29-245">Access</span></span>

- <span data-ttu-id="66f29-246">**リンク テーブルをすばやく見つける:** 新しい検索ボックスを使用すると、リンク テーブルを簡単に見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="66f29-246">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="66f29-247">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-247">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="66f29-248">Excel</span><span class="sxs-lookup"><span data-stu-id="66f29-248">Excel</span></span>

- <span data-ttu-id="66f29-249">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="66f29-249">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="outlook"></a><span data-ttu-id="66f29-250">Outlook</span><span class="sxs-lookup"><span data-stu-id="66f29-250">Outlook</span></span>

- <span data-ttu-id="66f29-251">**テナント管理者によって定義されたアクセス許可を使用して、Outlook の [リンクの挿入] メニューでリンクを挿入する:** Outlook で最近使用されたリンクの挿入 (MRU) のリンクでは、既にそれに対するアクセス許可を持つユーザーのみに動作したリンクが挿入されます。</span><span class="sxs-lookup"><span data-stu-id="66f29-251">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="66f29-252">これは、ドキュメントへのアクセス権の付与を求めるユーザー間でのメールの行き来をしばしば引き起こします。</span><span class="sxs-lookup"><span data-stu-id="66f29-252">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="66f29-253">このエクスペリエンスが更新されましたので、テナント管理者によって設定される既定のアクセス許可を使用し、リンクを挿入できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-253">We've updated this experience so now the link is inserted with the default permission set by the tenant admin.</span></span>

- <span data-ttu-id="66f29-254">**Outlook の外観の更新:** これは、Outlook で核となるエクスペリエンスの外観の更新の一部であり、閲覧ウィンドウとインスペクターに含まれるメール メッセージのレイアウトを更新しています。</span><span class="sxs-lookup"><span data-stu-id="66f29-254">**Outlook visual refresh:** This is part of the visual refresh of core experiences in Outlook, updating how mail messages layout in the reading pane and inspector.</span></span>

- <span data-ttu-id="66f29-255">**より高速化した共有カレンダーの更新**: Office 365 の共有カレンダーの場合、Outlook では REST API を使用してこれらのカレンダーを更新します。</span><span class="sxs-lookup"><span data-stu-id="66f29-255">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="66f29-256">共有カレンダーのより高速で信頼性の高い更新を行うには、プレビューを有効にします。</span><span class="sxs-lookup"><span data-stu-id="66f29-256">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="66f29-257">**検索結果で関連メッセージを確認する:** Outlook では検索条件を分析し、最も関連性の高いメール メッセージを検索結果の上部に表示します。</span><span class="sxs-lookup"><span data-stu-id="66f29-257">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="66f29-258">また、[上位の結果] セクションには、すべての結果が日付順に表示されます。</span><span class="sxs-lookup"><span data-stu-id="66f29-258">You'll also see all results sorted by date in the Top Results section.</span></span>

- <span data-ttu-id="66f29-259">**適切なユーザーにメールを送信する:** [宛先] 行をクリックして、連絡先候補から選択するだけです。</span><span class="sxs-lookup"><span data-stu-id="66f29-259">**Send the mail to the right person:** Just click the To: line and choose from suggested contacts.</span></span> <span data-ttu-id="66f29-260">画像とプレゼンス インジケーターにより、適切なユーザーを選択することができます。</span><span class="sxs-lookup"><span data-stu-id="66f29-260">A picture and presence indicator helps you choose the right person.</span></span>

- <span data-ttu-id="66f29-261">**攻撃に対する高度な保護:** Office 365 Advanced Threat Protection を用いると、メールの件名、添付メッセージ、署名されたメッセージ、ネットワーク パスなどの範囲内のハイパーリンクを利用した攻撃から保護されます。</span><span class="sxs-lookup"><span data-stu-id="66f29-261">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="66f29-262">**異なる明るさでメッセージを表示する:** [太陽] または [月] のボタンを使用して、閲覧ウィンドウの明るい背景と暗い背景を切り替えます。</span><span class="sxs-lookup"><span data-stu-id="66f29-262">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="66f29-263">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-263">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

### <a name="powerpoint"></a><span data-ttu-id="66f29-264">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="66f29-264">PowerPoint</span></span>

- <span data-ttu-id="66f29-265">**図を SVG として保存する:** グラフ、図形、その他の図を、サイズ変更しても画質が低下しないスケーラブル ベクター グラフィックとして保存できます。</span><span class="sxs-lookup"><span data-stu-id="66f29-265">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="66f29-266">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-266">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="66f29-267">**インクを瞬時に再生:** インク描画にアニメーション効果を適用して、スライド ショーの間中、それが進んだり戻ったりして再生されるようにします。</span><span class="sxs-lookup"><span data-stu-id="66f29-267">**Ink-stant replay:** Animate an ink drawing so that it replays forward or backward during your slide show.</span></span> [<span data-ttu-id="66f29-268">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-268">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="66f29-269">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="66f29-269">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="visio"></a><span data-ttu-id="66f29-270">Visio</span><span class="sxs-lookup"><span data-stu-id="66f29-270">Visio</span></span>

- <span data-ttu-id="66f29-271">**Microsoft Flow と Visio を使用したビジネス ワークフローの設計と自動化:** Visio を使用してワークフロー図を設計し、Microsoft Flow にエクスポートして自動化します。</span><span class="sxs-lookup"><span data-stu-id="66f29-271">**Design and automate business workflows using Microsoft Flow and Visio:** Use Visio to design workflow diagram and export it to Microsoft Flow to automate.</span></span>

### <a name="word"></a><span data-ttu-id="66f29-272">Word</span><span class="sxs-lookup"><span data-stu-id="66f29-272">Word</span></span>

- <span data-ttu-id="66f29-273">**別の言葉で伝える:** 別の言葉で伝えたいときに、[書き換え] でお助けします。</span><span class="sxs-lookup"><span data-stu-id="66f29-273">**Say it another way:** When you want to say it differently, Rewrite is there to help.</span></span> <span data-ttu-id="66f29-274">[書き換え] では、フレーズを洗練させるための別の言葉遣いを提供します。</span><span class="sxs-lookup"><span data-stu-id="66f29-274">Rewrite offers alternatives for finessing your phrases.</span></span>

- <span data-ttu-id="66f29-275">**共同編集の改善:** 共同編集時の信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-275">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="66f29-276">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="66f29-276">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="66f29-277">**他のユーザーがすばやく変更を確認:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="66f29-277">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="66f29-280">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-280">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="66f29-281">Excel</span><span class="sxs-lookup"><span data-stu-id="66f29-281">Excel</span></span>

- <div><span data-ttu-id="66f29-282"><span style="background-color:rgb(255, 255, 255);display:inline !important;">一部の保護されたシートにハイパーリンクが貼り付けられない問題が解決されました。</span></span><span class="sxs-lookup"><span data-stu-id="66f29-282"><span style="background-color:rgb(255, 255, 255);display:inline !important;">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span></span><br></div>


- <div><span data-ttu-id="66f29-283">&nbsp;<span style="font-size:13.3333px;background-color:rgb(255, 255, 255);display:inline !important;">アドイン マネジャーで参照するときに</span>、16 個以上のアドインを表示できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-283">Enabled more than 16 add-ins to show&nbsp;<span style="font-size:13.3333px;background-color:rgb(255, 255, 255);display:inline !important;">when browsing in the add-in manager.</span></span></span></div>
- <div><span data-ttu-id="66f29-284">Win32 クライアントの [アイデア] ボタンをクリックしてアドインを読み込むときにエラーが発生するという Excel のアイデア機能の問題を修正します。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="66f29-284">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.&nbsp;</span></span></div>

### <a name="outlook"></a><span data-ttu-id="66f29-285">Outlook</span><span class="sxs-lookup"><span data-stu-id="66f29-285">Outlook</span></span>

- <div><span data-ttu-id="66f29-286">一部の safelinks に対して簡易的なホバーの URL が正しく表示されなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-286">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span></div>


- <span data-ttu-id="66f29-287"><span style="background-color:rgb(255, 255, 255);display:inline !important;">Python による添付ファイルもブロックされるよう、Outlook の添付ファイルのブロック ロジックが更新されました。</span></span><span class="sxs-lookup"><span data-stu-id="66f29-287"><span style="background-color:rgb(255, 255, 255);display:inline !important;">Updated the attachment blocking logic in Outlook to also block python attachments.</span></span></span>


- <span data-ttu-id="66f29-288"><span style="background-color:rgb(255, 255, 255);display:inline !important;">ユーザーによって確認される Outlook のプロセスのメモリ リークを引き起こす問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="66f29-288"><span style="background-color:rgb(255, 255, 255);display:inline !important;">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span></span>

- <span data-ttu-id="66f29-289">WebDAV の場所にファイルを保存できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-289">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>


### <a name="office-suite"></a><span data-ttu-id="66f29-290">Office スイート</span><span class="sxs-lookup"><span data-stu-id="66f29-290">Office Suite</span></span>

- <div><p style="margin:0in 0in 0.0001pt;font-size:11pt;font-family:Calibri, sans-serif;"><span data-ttu-id="66f29-291">ファイルを開くときにユーザーが直面していた問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-291">We fixed an issue users were hitting when opening a file.</span></span></p></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-september-10"></a><span data-ttu-id="66f29-293">バージョン 1908: 9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="66f29-293">Version 1908: September 10</span></span>
<span data-ttu-id="66f29-294">*バージョン 1908 (ビルド 11929.20300)*</span><span class="sxs-lookup"><span data-stu-id="66f29-294">*Version 1908 (Build 11929.20300)*</span></span>

<span data-ttu-id="66f29-295">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="66f29-295">Security updates listed [here](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="66f29-297">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-297">Non-security updates</span></span>
### <a name="outlook"></a><span data-ttu-id="66f29-298">Outlook</span><span class="sxs-lookup"><span data-stu-id="66f29-298">Outlook</span></span>

- <span data-ttu-id="66f29-299">スクリーン リーダーからユーザーが場所の候補にアクセスできない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-299">Fixed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="66f29-300">一部のユーザーが Outlook のクラウド設定を取得しようとすると、認証エラーが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-300">Fixed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="66f29-301">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="66f29-301">PowerPoint</span></span>

- <span data-ttu-id="66f29-302">PowerPoint ビデオ コントロールのアクセス可能な名前を復元する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-302">Fixed an issue to restore the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="66f29-303">一部のアニメーションが開始できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-303">Fixed an issue which could prevent some animations from starting.</span></span>

### <a name="word"></a><span data-ttu-id="66f29-304">Word</span><span class="sxs-lookup"><span data-stu-id="66f29-304">Word</span></span>

- <span data-ttu-id="66f29-305">SharePoint 2016 に保存されているファイルを共有しようとすると、"申し訳ございません。何かがこのファイルの共有を妨げています。" というメッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-305">Fixed an issue which caused users to get the message "Sorry, something is preventing us from sharing this"  when trying to share files stored on SharePoint 2016.</span></span>

### <a name="office-suite"></a><span data-ttu-id="66f29-306">Office スイート</span><span class="sxs-lookup"><span data-stu-id="66f29-306">Office Suite</span></span>

- <span data-ttu-id="66f29-307">大きなツリー ビューの表示に失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-307">Fixed an issue where large tree views were failing.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-august-26"></a><span data-ttu-id="66f29-309">バージョン 1908: 8 月 26 日</span><span class="sxs-lookup"><span data-stu-id="66f29-309">Version 1908: August 26</span></span>
<span data-ttu-id="66f29-310">*バージョン 1908 (ビルド 11929.20254)*</span><span class="sxs-lookup"><span data-stu-id="66f29-310">*Version 1908 (Build 11929.20254)*</span></span>
* <span data-ttu-id="66f29-311">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="66f29-311">Various bugs and performance fixes.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="66f29-312">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-312">Excel: Feature updates</span></span>

- <span data-ttu-id="66f29-313">**あらましを描く:** ブック内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="66f29-313">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="66f29-314">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-314">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="66f29-315">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-315">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="66f29-316">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="66f29-316">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="66f29-317">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-317">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

- <span data-ttu-id="66f29-318">**残っている作業に集中する:** [解決] を選択して、コメントを折りたたみ、開いているアイテムを目立たせます。</span><span class="sxs-lookup"><span data-stu-id="66f29-318">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

### <a name="office-suite-feature-updates"></a><span data-ttu-id="66f29-319">Office スイート: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-319">Office Suite: Feature updates</span></span>

- <span data-ttu-id="66f29-320">**新しい外観を備えた Office のアイコン:** シンプルかつ高性能で、インテリジェントな Office のエクスペリエンスを反映するように、Office のアイコンがリニューアルされました。</span><span class="sxs-lookup"><span data-stu-id="66f29-320">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="66f29-321">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-321">Outlook: Feature updates</span></span>

- <span data-ttu-id="66f29-322">**場所の候補を取得する:** 予定や会議をスケジュールするときに、[場所] に入力すると、会議室、住所、およびその他の最新の場所が提示されます。</span><span class="sxs-lookup"><span data-stu-id="66f29-322">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="66f29-323">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-323">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="66f29-324">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-324">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="66f29-325">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="66f29-325">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="66f29-326">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-326">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="66f29-327">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-327">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="66f29-328">**あらましを描く:** プレゼンテーション内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="66f29-328">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="66f29-329">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-329">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="66f29-330">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-330">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="66f29-331">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="66f29-331">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="66f29-332">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-332">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="word-feature-updates"></a><span data-ttu-id="66f29-333">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-333">Word: Feature updates</span></span>

- <span data-ttu-id="66f29-334">**あらましを描く:** ドキュメント内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="66f29-334">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="66f29-335">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-335">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="66f29-336">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-336">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="66f29-337">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="66f29-337">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="66f29-338">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-338">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

## <a name="version-1907-august-13"></a><span data-ttu-id="66f29-339">バージョン 1907: 8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="66f29-339">Version 1907: August 13</span></span>
<span data-ttu-id="66f29-340">*バージョン 1907 (ビルド 11901.20218)*</span><span class="sxs-lookup"><span data-stu-id="66f29-340">*Version 1907 (Build 11901.20218)*</span></span>

<span data-ttu-id="66f29-341">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="66f29-341">Security updates listed [here](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="66f29-342">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-342">Excel: Non-security updates</span></span>

- <span data-ttu-id="66f29-343">ピボットテーブルの並べ替え方法を変更し、他のユーザーとの共同編集セッション中にそれを更新する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-343">Fixed an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="66f29-344">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-344">Outlook: Non-security updates</span></span>

- <span data-ttu-id="66f29-345">メールボックスを基本認証から最新認証にアップグレードしたユーザーが、Outlook プロファイルに関連付けられた正しくないアカウントで終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-345">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

## <a name="version-1907-july-29"></a><span data-ttu-id="66f29-346">バージョン 1907: (7 月 29 日)</span><span class="sxs-lookup"><span data-stu-id="66f29-346">Version 1907: July 29</span></span>

<span data-ttu-id="66f29-347">*バージョン 1907 (ビルド 11901.20176)*</span><span class="sxs-lookup"><span data-stu-id="66f29-347">*Version 1907 (Build 11901.20176)*</span></span>
* <span data-ttu-id="66f29-348">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="66f29-348">Various bugs and performance fixes.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="66f29-349">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-349">Excel: Feature updates</span></span>

- <span data-ttu-id="66f29-350">**ブラウザーへのバウンスは不要:** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定することができます。</span><span class="sxs-lookup"><span data-stu-id="66f29-350">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="66f29-351">**Power Query の機能強化を使用して素早くコーディングする:** オートコンプリートおよび構文の色分けによって素早くコーディングを完了できます。</span><span class="sxs-lookup"><span data-stu-id="66f29-351">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="66f29-352">関数、列、パラメーターも簡単に見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="66f29-352">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="66f29-353">**マップ グラフを作成する:** この機能は、Excel の地理データ型を使用して、塗り分けされたマップ グラフにプロットするユーザーのための機能強化です。</span><span class="sxs-lookup"><span data-stu-id="66f29-353">**Create a Map chart:** This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="66f29-354">エンドユーザーにとっては、機能とエンドユーザーがマップする領域の精度向上とがより高度に統合されたことが利点です。</span><span class="sxs-lookup"><span data-stu-id="66f29-354">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="66f29-355">さらに、ポリゴンで都市をマッピングする機能も含まれてます。</span><span class="sxs-lookup"><span data-stu-id="66f29-355">Additional benefits include - ability to map city polygons.</span></span> [<span data-ttu-id="66f29-356">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-356">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="66f29-357">**類似列のテーブルを結合する:** 取得と変換 (Power Query) では、テーブルを統合するために列を比較するときに、近似文字列マッチング ロジック (あいまい一致とも呼ばれる) が使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-357">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="66f29-358">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-358">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

### <a name="outlook-feature-updates"></a><span data-ttu-id="66f29-359">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-359">Outlook: Feature updates</span></span>

- <span data-ttu-id="66f29-360">**あなたが人を検索するときに電子メールの提案を得ます:** [検索]ボックスにその人の名前を入力すると、最も関連性の高い電子メールメッセージが検索結果に含まれます。</span><span class="sxs-lookup"><span data-stu-id="66f29-360">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="66f29-361">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-361">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="66f29-362">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-362">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="66f29-363">**ブラウザーへのバウンスは不要:** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定することができます。</span><span class="sxs-lookup"><span data-stu-id="66f29-363">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="66f29-364">**オンライン ビデオの新しい保存場所:** Microsoft Stream にビデオを保存すれば、組織内のすべてのユーザーが視聴できます。</span><span class="sxs-lookup"><span data-stu-id="66f29-364">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="66f29-365">ビデオのリンクを挿入すれば、小さなファイル サイズでマルチメディア プレゼンテーションをご利用いただけます。</span><span class="sxs-lookup"><span data-stu-id="66f29-365">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="66f29-366">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-366">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="66f29-367">**マップ グラフを作成する:** この機能は、Excel の地理データ型を使用して、塗り分けされたマップ グラフにプロットするユーザーのための機能強化です。</span><span class="sxs-lookup"><span data-stu-id="66f29-367">**Create a Map chart:** This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="66f29-368">エンドユーザーにとっては、機能とエンドユーザーがマップする領域の精度向上とがより高度に統合されたことが利点です。</span><span class="sxs-lookup"><span data-stu-id="66f29-368">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="66f29-369">さらに、ポリゴンで都市をマッピングする機能も含まれてます。</span><span class="sxs-lookup"><span data-stu-id="66f29-369">Additional benefits include - ability to map city polygons.</span></span> [<span data-ttu-id="66f29-370">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-370">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="66f29-371">**スライドのタイトルを追加してプレゼンテーションをアクセス可能にする:** アクセシビリティ チェックは、不足しているスライドのタイトルを見つけて修正するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="66f29-371">**Add Slide Titles to make your presentations accessible:** Accessibility Checker helps you find and fix missing slide titles.</span></span> [<span data-ttu-id="66f29-372">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-372">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="66f29-373">**アクセスを容易にするため、[印刷] メニューに [配布資料にスライド番号を印刷する] を移動しました:** 配布資料を指定したら、[印刷]、[印刷レイアウト] ドロップダウンの順にクリックすれば見つかります。</span><span class="sxs-lookup"><span data-stu-id="66f29-373">**The setting to Print Slide Numbers in Handouts has been moved to the Print Menu for easier access:**  Find it in the Print > Print Layout dropdown when a Handout layout is selected.</span></span> <span data-ttu-id="66f29-374">これにより、プレゼンテーションごとに簡単に設定を切り替えることもできます。</span><span class="sxs-lookup"><span data-stu-id="66f29-374">This also allows the setting to be easily toggled per presentation.</span></span> [<span data-ttu-id="66f29-375">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-375">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

### <a name="word-feature-updates"></a><span data-ttu-id="66f29-376">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-376">Word: Feature updates</span></span>

- <span data-ttu-id="66f29-377">**作業の邪魔をするものにさよならしましょう:** Mac のお気に入りの機能が Windows にも登場します。</span><span class="sxs-lookup"><span data-stu-id="66f29-377">**Say goodbye to distractions:** A favorite Mac feature comes to Windows.</span></span> <span data-ttu-id="66f29-378">気を散らさずに作業に集中するには、[表示]メニューの[フォーカス]に切り替えます。</span><span class="sxs-lookup"><span data-stu-id="66f29-378">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> [<span data-ttu-id="66f29-379">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-379">Learn more</span></span>](https://support.office.com/article/51af2fb2-194f-424b-ab7e-b65de9ec9292)

- <span data-ttu-id="66f29-380">**ブラウザーへのバウンスは不要:** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定することができます。</span><span class="sxs-lookup"><span data-stu-id="66f29-380">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="66f29-381">**マップ グラフを作成する:** この機能は、Excel の地理データ型を使用して、塗り分けされたマップ グラフにプロットするユーザーのための機能強化です。</span><span class="sxs-lookup"><span data-stu-id="66f29-381">**Create a Map chart:** This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="66f29-382">エンドユーザーにとっては、機能とエンドユーザーがマップする領域の精度向上とがより高度に統合されたことが利点です。</span><span class="sxs-lookup"><span data-stu-id="66f29-382">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="66f29-383">さらに、ポリゴンで都市をマッピングする機能も含まれてます。</span><span class="sxs-lookup"><span data-stu-id="66f29-383">Additional benefits include - ability to map city polygons.</span></span> [<span data-ttu-id="66f29-384">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-384">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="66f29-385">**精度による消去:** 手描き入力の小さな不備を修正するのに、2 つのサイズの消しゴムから選択できます。</span><span class="sxs-lookup"><span data-stu-id="66f29-385">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="66f29-386">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-386">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

## <a name="version-1906-july-09"></a><span data-ttu-id="66f29-387">バージョン 1906: 7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="66f29-387">Version 1906: July 09</span></span>
<span data-ttu-id="66f29-388">*バージョン 1906 (ビルド 11727.20244)*</span><span class="sxs-lookup"><span data-stu-id="66f29-388">*Version 1906 (Build 11727.20244)*</span></span>

<span data-ttu-id="66f29-389">セキュリティ更新プログラムの一覧は「[こちら](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)」</span><span class="sxs-lookup"><span data-stu-id="66f29-389">Security updates listed [here](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="66f29-390">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-390">Outlook: Non-security updates</span></span>

- <span data-ttu-id="66f29-391">現在のフォルダー検索で断続的な失敗を引き起こす問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="66f29-391">Addresses an issue that caused current folder search to intermittently fail.</span></span>

## <a name="version-1906-june-27"></a><span data-ttu-id="66f29-392">バージョン 1906: 6 月 27 日</span><span class="sxs-lookup"><span data-stu-id="66f29-392">Version 1906: June 27</span></span>
<span data-ttu-id="66f29-393">*バージョン 1906 (ビルド 11727.20230)*</span><span class="sxs-lookup"><span data-stu-id="66f29-393">*Version 1906 (Build 11727.20230)*</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="66f29-394">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-394">Outlook: Non-security updates</span></span>

- <span data-ttu-id="66f29-395">設定に関係なく、POP3 ユーザーの一部がプレーンテキストで書式設定されたすべてのメールを表示する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="66f29-395">Addresses an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span>  <span data-ttu-id="66f29-396">この修正プログラムでは、HTML 形式のメッセージの表示が復元されます。</span><span class="sxs-lookup"><span data-stu-id="66f29-396">This fix will restore the view of the HTML formatted messages.</span></span>

## <a name="version-1906-june-26"></a><span data-ttu-id="66f29-397">バージョン 1906: 6 月 26 日</span><span class="sxs-lookup"><span data-stu-id="66f29-397">Version 1906: June 26</span></span>
<span data-ttu-id="66f29-398">*バージョン 1906 (ビルド 11727.20224)*</span><span class="sxs-lookup"><span data-stu-id="66f29-398">*Version 1906 (Build 11727.20224)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="66f29-399">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-399">Excel: Non-security updates</span></span>

- <span data-ttu-id="66f29-400">図形やフォームコントロールに割り当てられているマクロが間違ったエラーメッセージとして表示される、または間違った対象範囲で動作する問題が Excel で修正されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-400">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>
- <span data-ttu-id="66f29-401">テーブルの横にある切り取りと貼り付けの操作を、他のユーザーと共同編集しているときに失敗する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-401">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="66f29-402">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-402">Outlook: Non-security updates</span></span>

- <span data-ttu-id="66f29-403">代理人が特定の会議出席依頼に既に返信したかどうかに関係なく、管理者が不明瞭になる問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="66f29-403">Addresses an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

## <a name="version-1906-june-24"></a><span data-ttu-id="66f29-404">バージョン 1906: 6 月24 日</span><span class="sxs-lookup"><span data-stu-id="66f29-404">Version 1906: June 24</span></span>
<span data-ttu-id="66f29-405">*バージョン 1906 (ビルド 11727.20210)*</span><span class="sxs-lookup"><span data-stu-id="66f29-405">*Version 1906 (Build 11727.20210)*</span></span>
* <span data-ttu-id="66f29-406">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="66f29-406">Various bugs and performance fixes.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="66f29-407">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-407">Excel: Feature updates</span></span>

- <span data-ttu-id="66f29-408">**ワークシートが生まれ変わりました：** ワークブックを使ってアニメーション 3D グラフィックスを挿入し、心臓の鼓動、惑星軌道、そして T-Rex の大暴れを見ることができます。</span><span class="sxs-lookup"><span data-stu-id="66f29-408">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="66f29-409">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-409">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

### <a name="outlook-feature-updates"></a><span data-ttu-id="66f29-410">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-410">Outlook: Feature updates</span></span>

- <span data-ttu-id="66f29-411">**カスタマイズも可能、シンプルになったリボン：** 最もよく使うボタンが単一行にまとめられ、使いやすくなりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-411">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="66f29-412">簡単に従来のビューとシンプルなビューを切り替えたり、コマンドを固定または固定解除できます。</span><span class="sxs-lookup"><span data-stu-id="66f29-412">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="66f29-413">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-413">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="66f29-414">**お気に入りのアクションを選びましょう：** フラグや、削除機能を使いますか？</span><span class="sxs-lookup"><span data-stu-id="66f29-414">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="66f29-415">アーカイブまたは既読に​​しますか?</span><span class="sxs-lookup"><span data-stu-id="66f29-415">How about Archive or Mark as Read?</span></span> <span data-ttu-id="66f29-416">クイック操作メニューをカスタマイズしてよく使うコマンドを追加できます。</span><span class="sxs-lookup"><span data-stu-id="66f29-416">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="66f29-417">**多数のフォルダを持つメールボックスの共有フォルダ同期の向上：** 共有メールボックスを同期するとき、Outlook は長年にわたって最大 500 個のフォルダに制限されていました。</span><span class="sxs-lookup"><span data-stu-id="66f29-417">**Improved shared folder synchronization for mailboxes with many folders:** For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="66f29-418">この変更により Outlook の改善が行われ、同期をする際の 500 フォルダーの制限がなくなりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-418">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

- <span data-ttu-id="66f29-419">**集中受信トレイの設定がデバイス間で変わらなくなります：** 集中受信トレイの設定はクラウドに保存されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-419">**Focused Inbox settings remain the same across devices:** Your Focused Inbox preferences are now stored in the cloud.</span></span> <span data-ttu-id="66f29-420">どのコンピューターの Windows 版 Outlook や Outlook on the web でも、同じ機能をご利用いただけます。</span><span class="sxs-lookup"><span data-stu-id="66f29-420">Enjoy the same experience when you use Outlook for Windows on any computer and Outlook on the web.</span></span> [<span data-ttu-id="66f29-421">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-421">Learn more</span></span>](https://support.office.com/article/d77a442e-a86c-4bf8-b3dd-5571ae556986)

- <span data-ttu-id="66f29-422">**ゆったりとしたレイアウト、まとめたレイアウト？自由に決めましょう：** 狭い間隔で、アイテム間の間隔をより広くしたり、レイアウトを狭くして表示量をより多くできます。</span><span class="sxs-lookup"><span data-stu-id="66f29-422">**Relaxed or tighter layout? You choose:** Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

- <span data-ttu-id="66f29-423">\*\* Outlook のユーザー エクスペリエンスを更新しました：\*\* これまで Coming Soon でプレビューできていた、最も重要なことに集中できるようにするためのシンプルな操作性です。</span><span class="sxs-lookup"><span data-stu-id="66f29-423">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="66f29-424">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-424">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="66f29-425">**自分で描いて表現しましょう:** 画像の上に走り書きするか、描画キャンバスを追加して、インクを用いて自分の考えを送信します。</span><span class="sxs-lookup"><span data-stu-id="66f29-425">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="66f29-426">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-426">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

### <a name="word-feature-updates"></a><span data-ttu-id="66f29-427">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-427">Word: Feature updates</span></span>

- <span data-ttu-id="66f29-428">\*\* 共同編集：\*\* マクロを使用したドキュメントから締め出されるのにうんざりしていませんか。</span><span class="sxs-lookup"><span data-stu-id="66f29-428">**CoAuthoring:** Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="66f29-429">これで OneDrive for Business 上の docm ファイルで複数の作成者による同時編集が可能になります。</span><span class="sxs-lookup"><span data-stu-id="66f29-429">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="66f29-430">Skype for Business: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-430">Skype for Business: Non-security updates</span></span> 

 - <span data-ttu-id="66f29-431">モニタの倍率が 100 ％を超えたときに、会議で Polycom CX5500 および関連デバイスからのすべてのカメラストリームを表示するように修正しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-431">Fix to display all camera streams from Polycom CX5500 and related devices in a meeting when your monitor is scaled more than 100%</span></span>

- <span data-ttu-id="66f29-432">[会議のビデオをトリミングして中央揃えにする] 設定が有効になっている場合、4Kモニタで会議のビデオを正しくトリミングします</span><span class="sxs-lookup"><span data-stu-id="66f29-432">Correctly crop video in a meeting on a 4K monitor when the "Crop and Center my video in meetings" setting is enabled</span></span>

- <span data-ttu-id="66f29-433">複数のネットワークアダプタを備えた Windows 10 コンピュータから従来の Office Communicator クライアントへのファイル転送を許可します。</span><span class="sxs-lookup"><span data-stu-id="66f29-433">Allow transferring files to legacy Office Communicator clients from a Windows 10 computer with multiple network adapters.</span></span> [<span data-ttu-id="66f29-434">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-434">Learn more</span></span>](help/4508477)

- <span data-ttu-id="66f29-435">Skype for Business と Microsoft Teams の参加者間のコミュニケーションのしやすさが向上</span><span class="sxs-lookup"><span data-stu-id="66f29-435">Improved experience for communication between Skype for Business and Microsoft Teams participants</span></span>


## <a name="version-1905-june-11"></a><span data-ttu-id="66f29-436">バージョン 1905: 6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="66f29-436">Version 1905: June 11</span></span>
<span data-ttu-id="66f29-437">*バージョン 1905 (ビルド 11629.20246)*</span><span class="sxs-lookup"><span data-stu-id="66f29-437">*Version 1905 (Build 11629.20246)*</span></span>
<br/><span data-ttu-id="66f29-438">[こちら](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)にセキュリティ更新プログラムが記載されています</span><span class="sxs-lookup"><span data-stu-id="66f29-438">Security updates listed [here](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="66f29-439">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-439">Excel: Non-security updates</span></span>

- <span data-ttu-id="66f29-440">セルが挿入または削除されたときに、ウォーターフォール図とじょうごグラフがテーブルと同期しなくなる原因となっていた問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-440">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="66f29-441">PowerPoint: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-441">PowerPoint: Non-security updates</span></span>

- <span data-ttu-id="66f29-442">一部のアドインがグラフの図形に対して予期しないエラーをスローさせる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-442">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

### <a name="visio-non-security-updates"></a><span data-ttu-id="66f29-443">Visio: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-443">Visio: Non-security updates</span></span>

- <span data-ttu-id="66f29-444">Visio から SVG へのエクスポートは、さまざまな図形に対して機能しませんでした。</span><span class="sxs-lookup"><span data-stu-id="66f29-444">Export to SVG from Visio was not working for a variety of shapes.</span></span>

## <a name="version-1905-june-3"></a><span data-ttu-id="66f29-445">バージョン 1905: 6 月 3 日</span><span class="sxs-lookup"><span data-stu-id="66f29-445">Version 1905: June 3</span></span>
<span data-ttu-id="66f29-446">*バージョン 1905 (ビルド 11629.20214)*</span><span class="sxs-lookup"><span data-stu-id="66f29-446">*Version 1905 (Build 11629.20214)*</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="66f29-447">PowerPoint: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-447">PowerPoint: Non-security updates</span></span>

- <span data-ttu-id="66f29-448">一部のアドインがグラフの図形に対して予期しないエラーをスローさせる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-448">Fixed an issue where some addins would throw unexpected errors around shapes in charts.</span></span>

## <a name="version-1905-may-29"></a><span data-ttu-id="66f29-449">バージョン 1905: 5 月 29 日</span><span class="sxs-lookup"><span data-stu-id="66f29-449">Version 1905: May 29</span></span>
<span data-ttu-id="66f29-450">*バージョン 1905 (ビルド 11629.20196)*</span><span class="sxs-lookup"><span data-stu-id="66f29-450">*Version 1905 (Build 11629.20196)*</span></span>

### <a name="access-feature-updates"></a><span data-ttu-id="66f29-451">Access: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-451">Access: Feature updates</span></span>

- <span data-ttu-id="66f29-452">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="66f29-452">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="66f29-453">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-453">Switching between them has never been easier.</span></span> [<span data-ttu-id="66f29-454">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-454">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="excel-feature-updates"></a><span data-ttu-id="66f29-455">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-455">Excel: Feature updates</span></span>

- <span data-ttu-id="66f29-456">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="66f29-456">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="66f29-457">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-457">Switching between them has never been easier.</span></span> [<span data-ttu-id="66f29-458">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-458">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="66f29-459">**近日公開予定:** 近日公開予定の Office に対する魅力あふれる変更点を確認してお試しいただき、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="66f29-459">**Coming Soon:** See what exciting changes are Coming Soon to Office, try them out and give us feedback.</span></span> [<span data-ttu-id="66f29-460">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-460">Learn more</span></span>](https://support.office.com/article/7800e0cf0-812f-475a-80aa-d47376e076f2)

- <span data-ttu-id="66f29-461">**コメント内で @メンションを使用してより効率的に共同作業を行う:** 共同作業がとても簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-461">**Collaborate more effectively with @Mentions in Comments:** Collaboration just became a whole lot easier!</span></span> <span data-ttu-id="66f29-462">ドキュメントのコメント内でチームメートを @メンションできるようになりました。ドキュメントに案内するメール通知が自動的にチームメートに送られます。</span><span class="sxs-lookup"><span data-stu-id="66f29-462">Now you can @mention teammates in document comments and they will automatically receive an email notification drawing them into the document.</span></span>

- <span data-ttu-id="66f29-463">**共同編集の結合の改善:** 条件付き書式、セルのスタイル、範囲の保護、グリッド線の表示、シート間の切り取り/貼り付けを使用する際に、共同編集での結合の成功率が改善されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-463">**Coauthoring merge improvements:** Coauthoring has improved the merge success rate when working with conditional formatting, cell styles, range protection, view gridlines, and cross-sheet cut/paste.</span></span> 

### <a name="outlook"></a><span data-ttu-id="66f29-464">Outlook</span><span class="sxs-lookup"><span data-stu-id="66f29-464">Outlook</span></span>

- <span data-ttu-id="66f29-465">**より簡単なアカウントの追加方法:** アカウントのセットアップの改善により、2 要素認証を使用する Outlook.com と Gmail のアカウントを Outlook に追加することが以前よりも簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-465">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="66f29-466">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-466">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="66f29-467">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-467">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="66f29-468">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="66f29-468">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="66f29-469">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-469">Switching between them has never been easier.</span></span> [<span data-ttu-id="66f29-470">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-470">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="66f29-471">**ライブ キャプションと字幕:** 発表者の言葉が、キャプションまたは選択した言語での字幕として自動的に画面に表示されます。</span><span class="sxs-lookup"><span data-stu-id="66f29-471">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="66f29-472">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-472">Learn more</span></span>](https://support.office.com/article/d68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="66f29-473">**近日公開予定:** 近日公開予定の Office に対する魅力あふれる変更点を確認してお試しいただき、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="66f29-473">**Coming Soon:** See what exciting changes are Coming Soon to Office, try them out and give us feedback.</span></span> [<span data-ttu-id="66f29-474">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-474">Learn more</span></span>](https://support.office.com/article/7800e0cf0-812f-475a-80aa-d47376e076f2)

- <span data-ttu-id="66f29-475">**コメント内で @メンションを使用してより効率的に共同作業を行う:** 共同作業がとても簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-475">**Collaborate more effectively with @Mentions in Comments:** Collaboration just became a whole lot easier!</span></span> <span data-ttu-id="66f29-476">ドキュメントのコメント内でチームメートを @メンションできるようになりました。ドキュメントに案内するメール通知が自動的にチームメートに送られます。</span><span class="sxs-lookup"><span data-stu-id="66f29-476">Now you can @mention teammates in document comments and they will automatically receive an email notification drawing them into the document.</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="66f29-477">Project: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-477">Project: Feature updates</span></span>

- <span data-ttu-id="66f29-478">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="66f29-478">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="66f29-479">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-479">Switching between them has never been easier.</span></span> [<span data-ttu-id="66f29-480">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-480">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio-feature-updates"></a><span data-ttu-id="66f29-481">Visio: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-481">Visio: Feature updates</span></span>

- <span data-ttu-id="66f29-482">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="66f29-482">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="66f29-483">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-483">Switching between them has never been easier.</span></span> [<span data-ttu-id="66f29-484">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-484">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="66f29-485">**PDF または PPT にエクスポートされた、またはメール サブスクリプションをセットアップした Power BI レポートで、Visio Visual もサポートされるようになりました:** Power BI レポートを PDF または PPT にエクスポート、またはメール サブスクリプションにセットアップした場合、Visio Visual はこれらのエクスポート先の形式でシームレスにレンダリングされます。</span><span class="sxs-lookup"><span data-stu-id="66f29-485">**Power BI reports exported to PDF, PPT or set up for email subscription will now feature Visio Visual as well:** If you export your Power BI reports to PDF, PPT or set up an email subscription for them, Visio Visual will render in these exported formats seamlessly.</span></span> [<span data-ttu-id="66f29-486">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-486">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word-feature-updates"></a><span data-ttu-id="66f29-487">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-487">Word: Feature updates</span></span>  

- <span data-ttu-id="66f29-488">**コメント内で @メンションを使用してより効率的に共同作業を行う:** 共同作業がとても簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-488">**Collaborate more effectively with @Mentions in Comments:** Collaboration just became a whole lot easier!</span></span> <span data-ttu-id="66f29-489">ドキュメントのコメント内でチームメートを @メンションできるようになりました。ドキュメントに案内するメール通知が自動的にチームメートに送られます。</span><span class="sxs-lookup"><span data-stu-id="66f29-489">Now you can @mention teammates in document comments and they will automatically receive an email notification drawing them into the document.</span></span>

- <span data-ttu-id="66f29-490">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="66f29-490">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="66f29-491">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-491">Switching between them has never been easier.</span></span> [<span data-ttu-id="66f29-492">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-492">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="66f29-493">**[学習ツール] モードで、ページで使用できる色が増えました:** Word の学習ツールでは、より多くのページ テーマ色が追加され、ページの背景色を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-493">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="66f29-494">すべて白またはすべて黒の背景だと読みにくいと感じるユーザーは少なくないため、PC と Mac の Word で色の選択肢を拡大しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-494">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="66f29-495">**近日公開予定:** 近日公開予定の Office に対する魅力あふれる変更点を確認してお試しいただき、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="66f29-495">**Coming Soon:** See what exciting changes are Coming Soon to Office, try them out and give us feedback.</span></span> [<span data-ttu-id="66f29-496">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-496">Learn more</span></span>](https://support.office.com/article/7800e0cf0-812f-475a-80aa-d47376e076f2)

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="66f29-497">Skype for Business: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-497">Skype for Business: Non-security updates</span></span>

- <span data-ttu-id="66f29-498">"ユーザーに自分を知ってもらうのに役立つ、写真の追加" コンテキストのヒントを無効にするオプションを Skype for Business Online ユーザーに提供します。</span><span class="sxs-lookup"><span data-stu-id="66f29-498">Provides the option to Skype for Business Online users to disable the "Add your photo - it'll help people get to know you" contextual tip.</span></span> <span data-ttu-id="66f29-499">この修正を有効にするには、[詳細情報](https://support.microsoft.com/help/4503469)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="66f29-499">To enable this fix, you can [Learn more](https://support.microsoft.com/help/4503469).</span></span>

- <span data-ttu-id="66f29-500">Skype for Business の再起動後に、セカンダリ呼び出しの設定が常に有効になるのを防ぎます。</span><span class="sxs-lookup"><span data-stu-id="66f29-500">Prevents secondary ringer setting from always being enabled after restarting Skype for Business.</span></span> <span data-ttu-id="66f29-501">この修正を有効にするには、[詳細情報](https://support.microsoft.com/help/4503470)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="66f29-501">To enable this fix, you can [Learn more](https://support.microsoft.com/help/4503470).</span></span>

 - <span data-ttu-id="66f29-502">Lync SDK ベースのアプリケーションを使用しながら、大規模な会議に参加するときに Skype for Business の応答を停止させる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="66f29-502">Fix for an issue that made Skype for Business stop responding when joining a large meeting while also using a Lync SDK-based application.</span></span> <span data-ttu-id="66f29-503">この修正を有効にするには、[詳細情報](https://support.microsoft.com/help/4503472)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="66f29-503">To enable this fix, you can [Learn more](https://support.microsoft.com/help/4503472).</span></span>

## <a name="version-1904-may-22"></a><span data-ttu-id="66f29-504">バージョン 1904: 5 月 22 日</span><span class="sxs-lookup"><span data-stu-id="66f29-504">Version 1904: May 22</span></span>
<span data-ttu-id="66f29-505">*バージョン 1904 (ビルド 11601.20230)*</span><span class="sxs-lookup"><span data-stu-id="66f29-505">*Version 1904 (Build 11601.20230)*</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="66f29-506">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-506">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="66f29-507">これにより、ユーザーがプライバシー レベルを選択して確認した後も、アプリケーションが起動される度に新しいプライバシー プロンプトが表示される問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="66f29-507">This addresses an issue where users see the new Privacy Prompt on every application launch even after selecting and committing a choice for their privacy level.</span></span>

## <a name="version-1904-may-14"></a><span data-ttu-id="66f29-508">バージョン 1904: 5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="66f29-508">Version 1904: May 14</span></span> 
<span data-ttu-id="66f29-509">*バージョン 1904 (ビルド 11601.20204)*</span><span class="sxs-lookup"><span data-stu-id="66f29-509">*Version 1904 (Build 11601.20204)*</span></span>

- <span data-ttu-id="66f29-510">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="66f29-510">Security updates listed [here](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)</span></span>

## <a name="version-1904-may-8"></a><span data-ttu-id="66f29-511">バージョン 1904: 5 月 8 日</span><span class="sxs-lookup"><span data-stu-id="66f29-511">Version 1904: May 8</span></span>
<span data-ttu-id="66f29-512">*バージョン 1904 (ビルド 11601.20178)*</span><span class="sxs-lookup"><span data-stu-id="66f29-512">*Version 1904 (Build 11601.20178)*</span></span>

- <span data-ttu-id="66f29-513">さまざまなバグやパフォーマンスが修正されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-513">Various bugs and performances fixes.</span></span>

## <a name="version-1904-april-29"></a><span data-ttu-id="66f29-514">バージョン 1904: 4 月 29 日</span><span class="sxs-lookup"><span data-stu-id="66f29-514">Version 1904: April 29</span></span>
<span data-ttu-id="66f29-515">*バージョン 1904 (ビルド 11601.20144)*</span><span class="sxs-lookup"><span data-stu-id="66f29-515">*Version 1904 (Build 11601.20144)*</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="66f29-516">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-516">Excel: Feature updates</span></span>

- <span data-ttu-id="66f29-517">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="66f29-517">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="66f29-518">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="66f29-518">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="66f29-519">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-519">Outlook: Feature updates</span></span>

- <span data-ttu-id="66f29-520">\*\* Outlook に LinkedIn ネットワークを接続する:\*\* LinkedIn アカウントを Microsoft アカウントに安全に接続して、LinkedIn プロファイルからの情報を [連絡先カード] に直接表示できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-520">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="66f29-521">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-521">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="66f29-522">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-522">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="66f29-523">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="66f29-523">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="66f29-524">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="66f29-524">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="66f29-525">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-525">Word: Feature updates</span></span>

- <span data-ttu-id="66f29-526">**色の変更履歴、コメントとリアルタイムの共同作業の同期:** 当社の製品での、コメント、変更履歴と共同作業者のカーソルが同じ色で表示されることについての修正箇所を確認しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-526">**Colors for Track Changes, Comments and Real-Time Collaboration in Sync:** Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

- <span data-ttu-id="66f29-527">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="66f29-527">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="66f29-528">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="66f29-528">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="66f29-529">Visio: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-529">Visio: Feature updates</span></span>

- <span data-ttu-id="66f29-530">**プロセス図を Word にエクスポート:** Word 文書に図形やメタデータなどのグラフ コンテンツを自動的に追加します。</span><span class="sxs-lookup"><span data-stu-id="66f29-530">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="66f29-531">その後に、文書をカスタマイズしてプロセスに関するガイドラインや操作マニュアルを作成できます。</span><span class="sxs-lookup"><span data-stu-id="66f29-531">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="66f29-532">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-532">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

### <a name="office-suite-feature-updates"></a><span data-ttu-id="66f29-533">Office スイート: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-533">Office Suite: Feature updates</span></span>

- <span data-ttu-id="66f29-534">**新しいアイコン:** フィードバックに基づいて、300 を超える新しいアイコンが追加されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-534">**New icons:** We've added over 300 new icons based on your feedback.</span></span> <span data-ttu-id="66f29-535">[アイコン] ボタンを使用して、リボンの [挿入] タブに表示されます。</span><span class="sxs-lookup"><span data-stu-id="66f29-535">You'll find them using the Icons button on the Insert tab of the ribbon.</span></span>

- <span data-ttu-id="66f29-536">**プライバシー制御**: 診断データおよび関連するエクスペリエンスに関する新しく更新されて改善された制御。</span><span class="sxs-lookup"><span data-stu-id="66f29-536">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="66f29-537">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-537">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

### <a name="outlook-non-security-updates"></a><span data-ttu-id="66f29-538">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-538">Outlook: Non-security updates</span></span>

- <span data-ttu-id="66f29-539">件名が極端に小さくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-539">Fixed an issue causing the subject to show extremely small.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="66f29-540">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-540">Office Suite: Non-security updates</span></span>
- <span data-ttu-id="66f29-541">新時代の名前である「Reiwa」のひらがなと漢字をスペルミスまたは間違った文法として誤って識別していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-541">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="66f29-542">プロキシ認証がシステムとして実行されたときに Office の更新プログラムがブロックされるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="66f29-542">Fixed an issue that blocked Office Updates when proxy authentication runs as SYSTEM.</span></span>

## <a name="version-1903-april-23"></a><span data-ttu-id="66f29-543">バージョン 1903: 4 月 23 日</span><span class="sxs-lookup"><span data-stu-id="66f29-543">Version 1903: April 23</span></span>
<span data-ttu-id="66f29-544">*バージョン 1903 (ビルド 11425.20244)*</span><span class="sxs-lookup"><span data-stu-id="66f29-544">*Version 1903 (Build 11425.20244)*</span></span>

- <span data-ttu-id="66f29-545">さまざまなバグやパフォーマンスが修正されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-545">Various bugs and performances fixes.</span></span>

## <a name="version-1903-april-17"></a><span data-ttu-id="66f29-546">バージョン 1903: 4 月 17 日</span><span class="sxs-lookup"><span data-stu-id="66f29-546">Version 1903: April 17</span></span>
<span data-ttu-id="66f29-547">*バージョン 1903 (ビルド 11425.20228)*</span><span class="sxs-lookup"><span data-stu-id="66f29-547">*Version 1903 (Build 11425.20228)*</span></span>

- <span data-ttu-id="66f29-548">さまざまなバグやパフォーマンスが修正されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-548">Various bugs and performances fixes.</span></span>

## <a name="version-1903-april-16"></a><span data-ttu-id="66f29-549">バージョン 1903: 4 月 16 日</span><span class="sxs-lookup"><span data-stu-id="66f29-549">Version 1903: April 16</span></span>
<span data-ttu-id="66f29-550">*バージョン 1903 (ビルド 11425.20218)*</span><span class="sxs-lookup"><span data-stu-id="66f29-550">*Version 1903 (Build 11425.20218)*</span></span>

- <span data-ttu-id="66f29-551">さまざまなバグやパフォーマンスが修正されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-551">Various bugs and performances fixes.</span></span>

## <a name="version-1903-april-9"></a><span data-ttu-id="66f29-552">バージョン 1903: 4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="66f29-552">Version 1903: April 9</span></span>
<span data-ttu-id="66f29-553">*バージョン 1903 (ビルド 11425.20204)*</span><span class="sxs-lookup"><span data-stu-id="66f29-553">*Version 1903 (Build 11425.20204)*</span></span> 

- <span data-ttu-id="66f29-554">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="66f29-554">Security updates listed [here](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="66f29-555">Skype for Business: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-555">Skype for Business: Non-security updates</span></span>
- <span data-ttu-id="66f29-556">Lync (Skype for Business) で、参加者が 7 人以上のオンライン ミーティングのミーティング ウィンドウが表示されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-556">Fixed an issue in Lync (Skype for Business) where for any online meeting with more 7+ participants, the meeting window can disappear.</span></span>

## <a name="version-1903-april-01"></a><span data-ttu-id="66f29-557">バージョン 1903: 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="66f29-557">Version 1903: April 01</span></span>
<span data-ttu-id="66f29-558">*Version 1903 (Build 11425.20202)*</span><span class="sxs-lookup"><span data-stu-id="66f29-558">*Version 1903 (Build 11425.20202)*</span></span> 

### <a name="excel-feature-updates"></a><span data-ttu-id="66f29-559">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-559">Excel: Feature updates</span></span>

- <span data-ttu-id="66f29-560">**Excel のインサイト:** インサイトには、ユーザーの範囲に値が用意されています。</span><span class="sxs-lookup"><span data-stu-id="66f29-560">**Insights in Excel:** Insights provides value to a range of users.</span></span> <span data-ttu-id="66f29-561">インサイトは、データ分析にソフトなアプローチを提供し、データに他からの違う視点を提供します。</span><span class="sxs-lookup"><span data-stu-id="66f29-561">Insights provides a softer approach to data analysis and for others it provides a different perspective to your data.</span></span> [<span data-ttu-id="66f29-562">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-562">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)


- <span data-ttu-id="66f29-563">**コンテンツのリーチを拡大:** アクセシビリティの高いスプレッドシートを作成する必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="66f29-563">**Increase the reach of your content:**  Need to make your spreadsheets accessible?</span></span> <span data-ttu-id="66f29-564">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="66f29-564">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="66f29-565">[校閲] > [アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="66f29-565">Try it by clicking Review > Check Accessibility and we’ll tell you when we find something you need to look at in the status bar.</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="66f29-566">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-566">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="66f29-567">**よりよい変形操作:** 図形に名前を付けると、変形するときにより細かく制御できます。</span><span class="sxs-lookup"><span data-stu-id="66f29-567">**Better shapeshifting:**  Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="66f29-568">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-568">Learn more</span></span>](https://support.office.com/article/9bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="66f29-569">**コンテンツのリーチを拡大:** アクセシビリティの高いプレゼンテーションを作成する必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="66f29-569">**Increase the reach of your content:**  Need to make your presentations accessible?</span></span> <span data-ttu-id="66f29-570">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="66f29-570">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="66f29-571">[校閲]>[アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="66f29-571">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="66f29-572">**再利用できる場合、新たに作成し直しますか?**</span><span class="sxs-lookup"><span data-stu-id="66f29-572">**Why reinvent when you can re-use?**</span></span>  <span data-ttu-id="66f29-573">作成した、または他のユーザーと共有しているスライドを再利用して時間を節約します。</span><span class="sxs-lookup"><span data-stu-id="66f29-573">Save time by re-using slides that you created or that others have shared with you.</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="66f29-574">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-574">Excel: Non-security updates</span></span>

- <span data-ttu-id="66f29-575">Excel では、ユーザーが変更を取得するためにブックを再び開くよう要求される結果となるマージ競合の問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-575">Fixed a merge conflict issue in Excel  that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="66f29-576">Skype for Business: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-576">Skype for Business: Non-security updates</span></span>

- <span data-ttu-id="66f29-577">サード パーティの SfB/Lync SDK アプリが存在する場合に、Skype for Business のチャット通知への応答が停止される原因となった問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="66f29-577">Fix for issue that caused Skype for Business to stop responding when responding to chat notifications if 3rd party SfB/Lync SDK app present.</span></span>
- <span data-ttu-id="66f29-578">チャットに特定のクリップボードの内容を貼り付けるときにアプリがクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="66f29-578">Fix for app crash when specific clipboard content is pasted into a chat.</span></span>
- <span data-ttu-id="66f29-579">いずれかの通話エージェントが受信した呼び出しキューの呼び出しの "受け入れ担当者" 情報が表示されるのを妨げている問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="66f29-579">Fix for issue that prevented display of the "accepted by" information for a Call Queue call that's picked up by one of the call agents.</span></span>
- <span data-ttu-id="66f29-580">Teams のユーザーが Skype for Business 会議に参加したときに通話アイコンが非表示になる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-580">Fixed issue that hid call icons when a Teams user joins a Skype for Business meeting.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="66f29-581">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-581">Word: Feature updates</span></span>

- <span data-ttu-id="66f29-582">**コンテンツのリーチを拡大:** アクセシビリティの高いドキュメントを作成する必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="66f29-582">**Increase the reach of your content:**  Need to make your documents accessible?</span></span> <span data-ttu-id="66f29-583">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="66f29-583">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="66f29-584">[校閲]>[アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="66f29-584">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

## <a name="version-1902-march-25"></a><span data-ttu-id="66f29-585">バージョン 1902: 3 月 25 日</span><span class="sxs-lookup"><span data-stu-id="66f29-585">Version 1902: March 25</span></span>
<span data-ttu-id="66f29-586">*バージョン 1902 (ビルド 11328.20222)*</span><span class="sxs-lookup"><span data-stu-id="66f29-586">*Version 1902 (Build 11328.20222)*</span></span>

- <span data-ttu-id="66f29-587">さまざまなバグやパフォーマンスが修正されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-587">Various bugs and performances fixes.</span></span>

## <a name="version-1902-march-12"></a><span data-ttu-id="66f29-588">バージョン 1902: 3 月 12 日</span><span class="sxs-lookup"><span data-stu-id="66f29-588">Version 1902: March 12</span></span>
<span data-ttu-id="66f29-589">*バージョン 1902 (ビルド 11328.20158)*</span><span class="sxs-lookup"><span data-stu-id="66f29-589">*Version 1902 (Build 11328.20158)*</span></span> 

- <span data-ttu-id="66f29-590">さまざまなバグやパフォーマンスが修正されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-590">Various bugs and performances fixes.</span></span>

## <a name="version-1902-march-4"></a><span data-ttu-id="66f29-591">バージョン 1902: 3 月 4 日</span><span class="sxs-lookup"><span data-stu-id="66f29-591">Version 1902: March 4</span></span>
<span data-ttu-id="66f29-592">*バージョン 1902 (ビルド 11328.20146)*</span><span class="sxs-lookup"><span data-stu-id="66f29-592">*Version 1902 (Build 11328.20146)*</span></span> 

### <a name="access-feature-updates"></a><span data-ttu-id="66f29-593">Access: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-593">Access: Feature updates</span></span>

- <span data-ttu-id="66f29-594">**データベース オブジェクトをタブで管理する:** アクティブなタブが分かりやすく表示され、簡単にタブをドラッグして再配置し、ワンクリックでデータベース オブジェクトを閉じることができます。</span><span class="sxs-lookup"><span data-stu-id="66f29-594">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>
- <span data-ttu-id="66f29-595">**より大きい [ズーム] ボックス:** [ズーム] ボックスがより大きく表示され、そこでフォントを変更することができます。変更内容はすべて [ズーム] ボックス内に記憶されます。</span><span class="sxs-lookup"><span data-stu-id="66f29-595">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="66f29-596">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-596">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel-feature-updates"></a><span data-ttu-id="66f29-597">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-597">Excel: Feature updates</span></span>

- <span data-ttu-id="66f29-598">**\@メンションを使用してユーザーの注意を引く:** コメントで @メンションを使うと、仕事仲間による入力が必要な場合にそのユーザーに知らせることができます。</span><span class="sxs-lookup"><span data-stu-id="66f29-598">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="66f29-599">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-599">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)
- <span data-ttu-id="66f29-600">**データの詳細を検出する:** 新しいアイデア ボタンは、データのパターンを探し、それを使用してインテリジェントな個人向けの提案を作成します。</span><span class="sxs-lookup"><span data-stu-id="66f29-600">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions.</span></span> [<span data-ttu-id="66f29-601">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-601">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)
- <span data-ttu-id="66f29-602">**変更が発生したときに変更内容を自動的に保存する:** 変更が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="66f29-602">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>
- <span data-ttu-id="66f29-603">**フィルターが適用された SVG を挿入する機能:** Office ユーザーは、フィルターが適用された SVG を挿入できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-603">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them.</span></span> [<span data-ttu-id="66f29-604">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-604">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook-feature-updates"></a><span data-ttu-id="66f29-605">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-605">Outlook: Feature updates</span></span>

- <span data-ttu-id="66f29-606">**連続する会議の合間に時間を組み込む:** 既定で 5 分から 10 分早く会議を終了するように設定することで、出席者に休憩時間や場所の移動時間を与えることができます。</span><span class="sxs-lookup"><span data-stu-id="66f29-606">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span> [<span data-ttu-id="66f29-607">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-607">Learn more</span></span>](https://support.office.com/article/Schedule-a-meeting-with-other-people-5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F#BKMK_endmeetingsearly)
- <span data-ttu-id="66f29-608">**音声読み上げを使用してメールの内容を聞く:** Outlook では、メールのテキストを読み上げながら強調表示することができます。</span><span class="sxs-lookup"><span data-stu-id="66f29-608">**Use Read Aloud to listen to your email:** Outlook can read your email aloud, highlighting text as it's read.</span></span> <span data-ttu-id="66f29-609">読み上げ機能をオンにするには、[簡単操作] の設定に移動します。</span><span class="sxs-lookup"><span data-stu-id="66f29-609">To turn on Read Aloud, go to the Ease of Access settings.</span></span> [<span data-ttu-id="66f29-610">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-610">Learn more</span></span>](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)
- <span data-ttu-id="66f29-611">**フィルターが適用された SVG を挿入する機能:** Office ユーザーは、フィルターが適用された SVG を挿入できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-611">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them.</span></span> [<span data-ttu-id="66f29-612">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-612">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="66f29-613">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-613">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="66f29-614">**これまで以上に簡単にオンライン ビデオを挿入できるようになりました:** Vimeo または YouTube からビデオをスライドに挿入する場合は、</span><span class="sxs-lookup"><span data-stu-id="66f29-614">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide?</span></span> <span data-ttu-id="66f29-615">ビデオ ページへのリンクがあれば簡単に行えます。</span><span class="sxs-lookup"><span data-stu-id="66f29-615">The video page link is all you need.</span></span> [<span data-ttu-id="66f29-616">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-616">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)
- <span data-ttu-id="66f29-617">**手書きの数式の自動書式設定:** 手書きの数式を標準の文字に変換することができます。</span><span class="sxs-lookup"><span data-stu-id="66f29-617">**You compute, we format:** We change hand-drawn math expressions into standard characters.</span></span> <span data-ttu-id="66f29-618">変換を開始するには、[インクから数式] を選択して、手書きのメモを選択します。</span><span class="sxs-lookup"><span data-stu-id="66f29-618">Just choose Ink to Math and select your handwritten notes to get started.</span></span> [<span data-ttu-id="66f29-619">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-619">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- <span data-ttu-id="66f29-620">**変更が発生したときに変更内容を自動的に保存する:** 変更が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="66f29-620">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>
- <span data-ttu-id="66f29-621">**フィルターが適用された SVG を挿入する機能:** Office ユーザーは、フィルターが適用された SVG を挿入できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-621">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them.</span></span> [<span data-ttu-id="66f29-622">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-622">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- <span data-ttu-id="66f29-623">**大きなファイルがより速く開くようになりました:** OneDrive または SharePoint に保存されているファイルを開くと、画像、ビデオ、およびその他の大きな要素がバックグラウンドでダウンロードされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-623">**Large files now open faster:** Images, videos, and other large elements now download in the background when opening files stored on OneDrive or SharePoint.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="66f29-624">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-624">Word: Feature updates</span></span>

- <span data-ttu-id="66f29-625">**変更が発生したときに変更内容を自動的に保存する:** 変更が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="66f29-625">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>
- <span data-ttu-id="66f29-626">**自動保存がオンになっていない理由を確認する**</span><span class="sxs-lookup"><span data-stu-id="66f29-626">**Find out why AutoSave isn't on!**</span></span> <span data-ttu-id="66f29-627">自動保存がオフになっているときに自動保存トグルをクリックすると、吹き出しが表示されるようになりました。自動保存がオフになっている理由も示されます。</span><span class="sxs-lookup"><span data-stu-id="66f29-627">Clicking on the AutoSave toggle when it's off will now either display a helpful callout with reasons why AutoSave might be off.</span></span> <span data-ttu-id="66f29-628">ドキュメントが OneDrive または SharePoint 上に存在しないという理由で自動保存ができない場合でも、1 つのボタンをクリックするだけでドキュメントを移動することができるようになります。</span><span class="sxs-lookup"><span data-stu-id="66f29-628">In the case where the only reason preventing AutoSave is the fact that the document is not on OneDrive or SharePoint, we will offer to move the document conveniently with one button click!</span></span>
- <span data-ttu-id="66f29-629">**フィルターが適用された SVG を挿入する機能:** Office ユーザーは、フィルターが適用された SVG を挿入できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="66f29-629">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them.</span></span> [<span data-ttu-id="66f29-630">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-630">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
 
### <a name="office-suite-feature-updates"></a><span data-ttu-id="66f29-631">Office スイート: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-631">Office Suite: Feature updates</span></span>

- <span data-ttu-id="66f29-632">**Microsoft Teams のインストール:** Microsoft Teams は、Office 365 ProPlus の新規インストール用に既定でインストールされています。</span><span class="sxs-lookup"><span data-stu-id="66f29-632">**Installation of Microsoft Teams:**  Microsoft Teams is installed by default for new installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="66f29-633">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-633">Learn More</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

## <a name="version-1901-february-12"></a><span data-ttu-id="66f29-634">バージョン 1901: 2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="66f29-634">Version 1901: February 12</span></span>
<span data-ttu-id="66f29-635">*バージョン 1901 (ビルド 11231.20174)*</span><span class="sxs-lookup"><span data-stu-id="66f29-635">*Version 1901 (Build 11231.20174)*</span></span> 

<span data-ttu-id="66f29-636">セキュリティ更新プログラムの一覧は[こちら](office365-proplus-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="66f29-636">Security updates listed [here](office365-proplus-security-updates.md)</span></span>

## <a name="version-1901-january-31"></a><span data-ttu-id="66f29-637">バージョン 1901: 1 月 31 日</span><span class="sxs-lookup"><span data-stu-id="66f29-637">Version 1901: January 31</span></span>
<span data-ttu-id="66f29-638">*バージョン 1901 (ビルド 11231.20130)*</span><span class="sxs-lookup"><span data-stu-id="66f29-638">*Version 1901 (Build 11231.20130)*</span></span> 

### <a name="excel-feature-updates"></a><span data-ttu-id="66f29-639">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-639">Excel: Feature updates</span></span>

- <span data-ttu-id="66f29-p200">**コメントを利用して共同作業を行う:** 返信ボックスが組み込まれているので、スプレッドシートで直接会話を続けることができます。[詳細情報](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)</span><span class="sxs-lookup"><span data-stu-id="66f29-p200">**Collaborate with comments:** Keep the conversation going right in your spreadsheet with the built-in reply box. [Learn more](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="66f29-642">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-642">Outlook: Feature updates</span></span>

- <span data-ttu-id="66f29-p201">**ミームが表示される:** テキストまたは静的イメージだけでは十分ではない場合、アニメーション GIF を使用して要点を示すことができます。[詳細情報](https://support.office.com/article/114BB251-861F-41CD-B20F-7E7289630C5B)</span><span class="sxs-lookup"><span data-stu-id="66f29-p201">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114BB251-861F-41CD-B20F-7E7289630C5B)</span></span>
 
### <a name="visio-feature-updates"></a><span data-ttu-id="66f29-645">Visio: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-645">Visio: Feature updates</span></span>

- <span data-ttu-id="66f29-646">**ダブル テイク オン データ フローチャート:** データ ビジュアライザーのフローチャート用の新しいレイアウトは、きれいで鮮明でとても分かりやすいです。</span><span class="sxs-lookup"><span data-stu-id="66f29-646">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> [<span data-ttu-id="66f29-647">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-647">Learn more</span></span>](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)

- <span data-ttu-id="66f29-648">**Azure ステンシルが組み込まれました:** 豊富な Azure ステンシルを使用してクラウド アプリの設計やアーキテクチャの計画を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="66f29-648">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="66f29-649">詳細情報</span><span class="sxs-lookup"><span data-stu-id="66f29-649">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word-feature-updates"></a><span data-ttu-id="66f29-650">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-650">Word: Feature updates</span></span>

- <span data-ttu-id="66f29-p204">**静的なドキュメントから魅力的なドキュメントへの変換:** ドキュメントを、すべてのデバイスに対応する対話型の使いやすい Web ページに変換します。[詳細情報](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="66f29-p204">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

### <a name="office-suite-feature-updates"></a><span data-ttu-id="66f29-653">Office スイート: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-653">Office Suite: Feature updates</span></span>

- <span data-ttu-id="66f29-p205">**Office のサード パーティ アプリケーションでは office.js api を使用した SVG の挿入をサポート:** Office アドインとも呼ばれるサード パーティ アプリケーションで SVG を挿入できるようになりました。ユーザーは、個人の SVG コレクションを Office に結び付けることができます。開発者は、Office.js API を使用してこの機能を利用できます。</span><span class="sxs-lookup"><span data-stu-id="66f29-p205">**Office 3rd Party Applications now have insert SVG support using the office.js api:** 3rd party applications also known as add-ins in Office now have the ability to insert SVG's. Users can now connect their personal collection of SVG's to Office. Developers can use this feature by using the Office.js API.</span></span>


## <a name="version-1812-january-14"></a><span data-ttu-id="66f29-657">バージョン 1812: 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="66f29-657">Version 1812: January 14</span></span>
<span data-ttu-id="66f29-658">*バージョン 1812 (ビルド 11126.20266)*</span><span class="sxs-lookup"><span data-stu-id="66f29-658">*Version 1812 (Build 11126.20266)*</span></span> 

<span data-ttu-id="66f29-659">パフォーマンス上の問題に対処するセキュリティ関連ではない更新プログラムのみ。</span><span class="sxs-lookup"><span data-stu-id="66f29-659">Non-security updates only, addressing performance issues.</span></span>

## <a name="version-1812-january-8"></a><span data-ttu-id="66f29-660">バージョン 1812: 1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="66f29-660">Version 1812: January 8</span></span>
<span data-ttu-id="66f29-661">*バージョン 1812 (ビルド 11126.20196)*</span><span class="sxs-lookup"><span data-stu-id="66f29-661">*Version 1812 (Build 11126.20196)*</span></span> 

### <a name="project-non-security-updates"></a><span data-ttu-id="66f29-662">Project: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="66f29-662">Project: Non-security updates</span></span>
- <span data-ttu-id="66f29-663">ガント チャートの [クリティカル]、[遅延]、[余裕期間] バー スタイルをオンにした後でオフにできない問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="66f29-663">Fixed an issue where you couldn't uncheck the Critical, Late and Slack bar styles for the Gantt chart after you checked one.</span></span>

## <a name="version-1812-january-3"></a><span data-ttu-id="66f29-664">バージョン 1812: 1 月 3 日</span><span class="sxs-lookup"><span data-stu-id="66f29-664">Version 1812: January 3</span></span>
<span data-ttu-id="66f29-665">*バージョン 1812 (ビルド 11126.20188)*</span><span class="sxs-lookup"><span data-stu-id="66f29-665">*Version 1812 (Build 11126.20188)*</span></span> 

### <a name="excel-feature-updates"></a><span data-ttu-id="66f29-666">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-666">Excel: Feature updates</span></span>

- <span data-ttu-id="66f29-p206">**作業中にアクセシビリティ チェックを実行したままにする:** アクセシビリティ チェックを常に開いたままにしなくても、ドキュメントのアクセシビリティの問題を追跡できます。スペルチェックの場合のように、ステータス バーのインジケーターを介して、作業中に見つかったアクセシビリティの問題に Excel が自動的にフラグを付けます。</span><span class="sxs-lookup"><span data-stu-id="66f29-p206">**Keep accessibility checker running while you work:** Keep track of accessibility issues in your document without needing the accessibility checker always open. Via an indicator in the status bar, much like spellcheck, Excel flags found accessibility issues while you are working.</span></span> 

### <a name="outlook-feature-updates"></a><span data-ttu-id="66f29-669">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-669">Outlook: Feature updates</span></span>

- <span data-ttu-id="66f29-p207">**すべての暗号化オプションを 1 か所に集約:** [オプション] > [暗号化] の順に移動するだけで、電子メール メッセージを保護する方法を選択できます。[詳細情報](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="66f29-p207">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="66f29-672">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-672">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="66f29-p208">**インクで素晴らしいスライドを作成:** インクを標準的な図形とテキストに変換し、PowerPoint デザイナーからスマートなスライド デザイン アイデアを入手します。[詳細情報](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)</span><span class="sxs-lookup"><span data-stu-id="66f29-p208">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer. [Learn more](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)</span></span>
- <span data-ttu-id="66f29-p209">**作業中にアクセシビリティ チェックを実行したままにする:** アクセシビリティ チェックを常に開いたままにしなくても、ドキュメントのアクセシビリティの問題を追跡できます。スペルチェックの場合のように、ステータス バーのインジケーターを介して、作業中に見つかったアクセシビリティの問題に PowerPoint が自動的にフラグを付けます。</span><span class="sxs-lookup"><span data-stu-id="66f29-p209">**Keep accessibility checker running while you work:** Keep track of accessibility issues in your document without needing the accessibility checker always open. Via an indicator in the status bar, much like spellcheck, PowerPoint flags found accessibility issues while you are working.</span></span> 

### <a name="word-feature-updates"></a><span data-ttu-id="66f29-677">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-677">Word: Feature updates</span></span>

- <span data-ttu-id="66f29-p210">**行フォーカスによる読解力の向上:** ドキュメント内で行ごとの移動をスムーズに行います。一度に 1 行か、3 行か、5 行かを表示するようフォーカスを調整できます。[詳細情報](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="66f29-p210">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>
- <span data-ttu-id="66f29-p211">**作業中にアクセシビリティ チェックを実行したままにする:** アクセシビリティ チェックを常に開いたままにしなくても、ドキュメントのアクセシビリティの問題を追跡できます。スペルチェックの場合のように、ステータス バーのインジケーターを介して、作業中に見つかったアクセシビリティの問題に Word が自動的にフラグを付けます。</span><span class="sxs-lookup"><span data-stu-id="66f29-p211">**Keep accessibility checker running while you work:** Keep track of accessibility issues in your document without needing the accessibility checker always open. Via an indicator in the status bar, much like spellcheck, Word flags found accessibility issues while you are working.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="66f29-683">Visio: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-683">Visio: Feature updates</span></span>

- <span data-ttu-id="66f29-p212">**壊れた Excel リンクの問題を解消:** データ ビジュアライザーの図にリンクされているはずの Excel ブックが見つかりませんか? 再リンクして、すぐに業務を再開できます。[詳細情報](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="66f29-p212">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

### <a name="office-suite-feature-updates"></a><span data-ttu-id="66f29-687">Office スイート: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="66f29-687">Office Suite: Feature updates</span></span>

- <span data-ttu-id="66f29-688">**[新機能] ウィンドウ:** [新機能] はヘルプ ウィンドウに移行しました。そのため、最新の更新プログラムにより簡単にアクセスして最新情報を入手できます。</span><span class="sxs-lookup"><span data-stu-id="66f29-688">**What's New Pane:** The What's New experience has moved to the Help Pane, so you can more easily access and stay up to date with our latest updates.</span></span>

> [!NOTE]
> <span data-ttu-id="66f29-689">Office の使用で問題がある場合は、[Microsoft の回答フォーラム](https://answers.microsoft.com/)に関するページまたは「[Microsoft Tech Community](https://techcommunity.microsoft.com/)」に質問を投稿するか、[サポート](https://support.microsoft.com/contactus)に問い合わせてサポートを受けることができます。</span><span class="sxs-lookup"><span data-stu-id="66f29-689">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
