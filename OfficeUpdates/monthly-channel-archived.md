---
title: 月次チャネル リリースのアーカイブ リリース ノート
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Office 365 ProPlus 用の月次チャネル リリースのリリース ノートを IT プロフェッショナルに提供する
ms.openlocfilehash: 985bb8ffff81cc0300487c14629e9fe9c5ba25a8
ms.sourcegitcommit: 5f72a0e94cda2cb64636380605806c29bbcdc53f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/26/2021
ms.locfileid: "52026362"
---
# <a name="archived-release-notes-for-monthly-channel"></a><span data-ttu-id="7c7f2-103">月次チャネルのアーカイブ リリース ノート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-103">Archived Release notes for Monthly Channel</span></span>
<span data-ttu-id="7c7f2-104">これらのリリース ノートには、Office 365 ProPlus、Visio Pro for Office 365、Project Online デスクトップ クライアント、および Office 365 Business の月次チャネルの更新プログラムに含まれる新機能およびセキュリティ以外の更新に関する情報が記載されています。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-104">These release notes provide information about new features and non-security updates that are included in Monthly Channel updates to Office 365 ProPlus, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

 > [!NOTE]
>- <span data-ttu-id="7c7f2-105">Microsoft では多くの場合、一定期間にわたって毎月、機能 (および場合によっては修正プログラム) を展開します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-105">We often roll out features (and sometimes even fixes) to Monthly over a period of time.</span></span>  <span data-ttu-id="7c7f2-106">ここで説明した内容がすぐに表示されない場合は、間もなく利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-106">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="7c7f2-107">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-107">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
>- <span data-ttu-id="7c7f2-108">Microsoft Teams の Office 365 ProPlus の既存のインストールについて: 7月の上旬から、Office 365 ProPlus (および Office 365 Business) の更新に Microsoft Teams が含まれます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-108">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in early July, updates to Office 365 ProPlus (and Office 365 Business) will include Microsoft Teams.</span></span>  <span data-ttu-id="7c7f2-109">Teams が追加される日付は、使用している更新プログラム チャネルによって異なります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-109">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="7c7f2-110">追加情報については、「[Office 365 ProPlus と同時に Microsoft Teams を展開する](/deployoffice/teams-install)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-110">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](/deployoffice/teams-install) for additional information.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-december-21"></a><span data-ttu-id="7c7f2-112">バージョン 2011: 12 月 21 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-112">Version 2011: December 21</span></span>
<span data-ttu-id="7c7f2-113">*バージョン 2011 (ビルド 13426.20404)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-113">*Version 2011 (Build 13426.20404)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-115">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-115">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7c7f2-116">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-116">Excel</span></span>

- <span data-ttu-id="7c7f2-117">Excel によってファイルの新しいバージョンが使用可能であることを示すメッセージバーが誤って表示され、ブックのコピーに変更内容を保存するか、変更内容を破棄するように強制する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-117">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="7c7f2-118">Excel 4.0 マクロを含む Excel アドイン ファイルを開いたときにプロンプトが表示されずに Excel がマクロを無効のままにしてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-118">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7c7f2-119">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-119">Office Suite</span></span>

- <span data-ttu-id="7c7f2-120">キャッシュからの URL と OneDrive からの URL が一致しない場合に、ファイルが NOT SyncBacked として開かれる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-120">Fixed an issue of file would be opened as NOT SyncBacked when url from cache and url from OneDrive does NOT match.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-december-08"></a><span data-ttu-id="7c7f2-122">バージョン 2011: 12 月 08 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-122">Version 2011: December 08</span></span>
<span data-ttu-id="7c7f2-123">*バージョン 2011 (ビルド 13426.20332)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-123">*Version 2011 (Build 13426.20332)*</span></span>

<span data-ttu-id="7c7f2-124">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-124">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-126">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-126">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="7c7f2-127">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-127">Office Suite</span></span>

- <span data-ttu-id="7c7f2-128">SaveRequestManagerCam が原因で、エラーが返される代わりにアプリケーションが閉じられる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-128">We fixed an issue where SaveRequestManagerCam was causing the application to close instead of returning an error.</span></span> 




[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-december-02"></a><span data-ttu-id="7c7f2-130">バージョン 2011: 12 月 2 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-130">Version 2011: December 02</span></span>
<span data-ttu-id="7c7f2-131">*バージョン 2011 (ビルド 13426.20308)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-131">*Version 2011 (Build 13426.20308)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-133">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-133">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7c7f2-134">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-134">Outlook</span></span>

- <span data-ttu-id="7c7f2-135">他の出席者が会議を転送すると、会議の元の出席者の一部がキャンセルを受信するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-135">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="7c7f2-136">1 つ以上の署名が構成されているにもかかわらず、ユーザーの署名が署名ドロップダウンに表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-136">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


### <a name="project"></a><span data-ttu-id="7c7f2-137">Project</span><span class="sxs-lookup"><span data-stu-id="7c7f2-137">Project</span></span>

- <span data-ttu-id="7c7f2-138">ロードの特定の部分でプロジェクト ファイルに問題がある場合に、特定のプロジェクトを開くことができるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-138">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7c7f2-139">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-139">Office Suite</span></span>

- <span data-ttu-id="7c7f2-140">Office スイートでは、新しいバージョンの Office を特定の古いバージョンの Office の上からインストールすると、レジストリ エントリが存在していないために機能が低下する(Power Query を使用できないなど) という問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-140">Office Suite Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-november-30"></a><span data-ttu-id="7c7f2-142">バージョン 2011: 11 月 30 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-142">Version 2011: November 30</span></span>
<span data-ttu-id="7c7f2-143">*バージョン 2011 (ビルド 13426.20294)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-143">*Version 2011 (Build 13426.20294)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-145">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-145">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="7c7f2-146">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-146">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-147">Word から Powerpoint への数式のコピー/貼り付けに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-147">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


### <a name="word"></a><span data-ttu-id="7c7f2-148">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-148">Word</span></span>

- <span data-ttu-id="7c7f2-149">Word から Powerpoint への数式のコピー/貼り付けに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-149">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="7c7f2-150">文書のスタイルがテンプレートとは別のスタイルに置き換わる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-150">We fixed an issue which document styles are replaced with other styles from the template.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-november-23"></a><span data-ttu-id="7c7f2-152">バージョン 2011: 11 月 23 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-152">Version 2011: November 23</span></span>
<span data-ttu-id="7c7f2-153">*バージョン 2011 (ビルド 13426.20274)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-153">*Version 2011 (Build 13426.20274)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7c7f2-155">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-155">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="7c7f2-156">Access</span><span class="sxs-lookup"><span data-stu-id="7c7f2-156">Access</span></span>

- <span data-ttu-id="7c7f2-157">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-157">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="7c7f2-158">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-158">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="7c7f2-159">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-159">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a><span data-ttu-id="7c7f2-160">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-160">Excel</span></span>

- <span data-ttu-id="7c7f2-161">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-161">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="7c7f2-162">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-162">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="7c7f2-163">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-163">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="7c7f2-164">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-164">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="7c7f2-165">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-165">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

- <span data-ttu-id="7c7f2-166">**ソース クエリを基に新しいシートに名前を付ける:** データが新しいシートに読み込まれると、シートはソース クエリの名前に基づいて名付けられます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-166">**Name the new sheet after the source query:** When the data is loaded into the new sheet, the sheet will be named based on the name of the source query.</span></span>

- <span data-ttu-id="7c7f2-167">**[詳細] ダイアログ ボックスを使用してデータ型を作成する:** [詳細] ダイアログ ボックスでは、作成するデータ型を組み合わせる列を手動で選択できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-167">**Use the Advanced Dialog to Create Data Types:** The Advanced Dialog allows you to manually select the columns which combine the Data Type you are creating.</span></span>

### <a name="onenote"></a><span data-ttu-id="7c7f2-168">OneNote</span><span class="sxs-lookup"><span data-stu-id="7c7f2-168">OneNote</span></span>

- <span data-ttu-id="7c7f2-169">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-169">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="7c7f2-170">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-170">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="7c7f2-171">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-171">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a><span data-ttu-id="7c7f2-172">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-172">Outlook</span></span>

- <span data-ttu-id="7c7f2-173">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-173">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="7c7f2-174">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-174">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="7c7f2-175">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-175">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="7c7f2-176">[ファイル] > [Office アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-176">Go to File > Office Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="7c7f2-177">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-177">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

- <span data-ttu-id="7c7f2-178">**タスクのユーザー エクスペリエンスの更新:** タスク アイテムの視覚的な更新。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-178">**User Experience Updates for Tasks:** A visual refresh of task items.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7c7f2-179">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-179">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-180">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-180">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="7c7f2-181">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-181">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br /><span data-ttu-id="7c7f2-182">[ブログの投稿](https://insider.office.com/en-us/blog/svg-content-office-third-party-apps)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7c7f2-182">See details in [blog post](https://insider.office.com/en-us/blog/svg-content-office-third-party-apps)</span></span>

- <span data-ttu-id="7c7f2-183">**透過背景の GIF を作成する**: アニメーション GIF にエクスポートする場合、新しいオプションを使用して背景を透明にすることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-183">**Create GIFs with Transparent Backgrounds:** When exporting to an Animated GIF, a new option will allow you to make the background transparent.</span></span><br /><span data-ttu-id="7c7f2-184">[ブログの投稿](https://insider.office.com/en-us/blog/export-animated-gifs-transparent-backgrounds)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7c7f2-184">See details in [blog post](https://insider.office.com/en-us/blog/export-animated-gifs-transparent-backgrounds)</span></span>

- <span data-ttu-id="7c7f2-185">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-185">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="7c7f2-186">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-186">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="7c7f2-187">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-187">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

- <span data-ttu-id="7c7f2-188">**アニメーション GIF を範囲内でエクスポートする**: アニメーション GIF にエクスポートするときにスライドの範囲を選択します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-188">**Export animated GIF in a range:** Select a range of slides when exporting to animated GIF.</span></span>

- <span data-ttu-id="7c7f2-189">**ビデオ ライブラリ:** アプリ内で利用可能な、質の良い無料のビデオ ライブラリを使用してドキュメントの質を高めます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-189">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app</span></span>

### <a name="project"></a><span data-ttu-id="7c7f2-190">Project</span><span class="sxs-lookup"><span data-stu-id="7c7f2-190">Project</span></span>

- <span data-ttu-id="7c7f2-191">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-191">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="7c7f2-192">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-192">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="7c7f2-193">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-193">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a><span data-ttu-id="7c7f2-194">発行者</span><span class="sxs-lookup"><span data-stu-id="7c7f2-194">Publisher</span></span>

- <span data-ttu-id="7c7f2-195">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-195">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="7c7f2-196">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-196">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="7c7f2-197">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-197">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a><span data-ttu-id="7c7f2-198">Visio</span><span class="sxs-lookup"><span data-stu-id="7c7f2-198">Visio</span></span>

- <span data-ttu-id="7c7f2-199">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-199">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="7c7f2-200">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-200">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="7c7f2-201">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-201">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a><span data-ttu-id="7c7f2-202">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-202">Word</span></span>

- <span data-ttu-id="7c7f2-203">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-203">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="7c7f2-204">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-204">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="7c7f2-205">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-205">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="7c7f2-206">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-206">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="7c7f2-207">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-207">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-210">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-210">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7c7f2-211">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-211">Outlook</span></span>

- <span data-ttu-id="7c7f2-212">タスクの進捗レポートを送信するときに、[宛先] フィールドが空白になる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-212">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


- <span data-ttu-id="7c7f2-213">MailItem.BeforeAttachmentAdd イベントの破損原因となった問題が修正されました。 </span><span class="sxs-lookup"><span data-stu-id="7c7f2-213">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="7c7f2-214">IDataObject 操作 (つまりクリップボードのドラッグやドロップ) で、ユーザーが添付ファイルに対して filetime の付加を無効にできるように、regkey を追加しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-214">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="7c7f2-215">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="7c7f2-215">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span> <span data-ttu-id="7c7f2-216">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="7c7f2-216">REG_DWORD IncludeFileTimesInDataObject.</span></span> <span data-ttu-id="7c7f2-217">0 = filetimes は除外されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-217">0 = filetimes are excluded.</span></span> <span data-ttu-id="7c7f2-218">1 = (既定) filetimes が含まれます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-218">1 = (default) filetimes are included.</span></span>


- <span data-ttu-id="7c7f2-219">Azure Information Protection の保護ラベルを使用してメッセージに返信するときに、インライン画像が消えるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-219">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7c7f2-220">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-220">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-221">Slide.Shapes.AddMediaObject2 が従来のビデオ形式 (.MPG-1、Mpeg-2) でクラッシュする VBA の問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-221">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="7c7f2-222">新たに録音したオーディオを含むスライドを複製した後にファイルを保存するときにエラーが発生するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-222">We fixed an issue where there is an error when saving the file after duplicating a slide that contains a newly recorded audio.</span></span>


- <span data-ttu-id="7c7f2-223">ドキュメントの修復操作の後であっても、一部の破損した PowerPoint ファイルを正常に開くことができないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-223">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="word"></a><span data-ttu-id="7c7f2-224">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-224">Word</span></span>

- <span data-ttu-id="7c7f2-225">最適化されたゲートがWord に影響を与えるアサート バグが修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-225">Fixed an assert bug exposed by optimized gates affecting Word.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-november-17"></a><span data-ttu-id="7c7f2-227">バージョン 2010: 11 月 17 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-227">Version 2010: November 17</span></span>
<span data-ttu-id="7c7f2-228">*バージョン 2010 (ビルド 13328.20408)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-228">*Version 2010 (Build 13328.20408)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-230">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-230">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7c7f2-231">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-231">Outlook</span></span>

- <span data-ttu-id="7c7f2-232">MailItem.BeforeAttachmentAdd イベントの破損原因となった問題が修正されました。 </span><span class="sxs-lookup"><span data-stu-id="7c7f2-232">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="7c7f2-233">IDataObject 操作 (つまりクリップボードのドラッグやドロップ) で、ユーザーが添付ファイルに対して filetime の付加を無効にできるように、regkey を追加しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-233">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="7c7f2-234">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="7c7f2-234">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span>  <span data-ttu-id="7c7f2-235">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="7c7f2-235">REG_DWORD IncludeFileTimesInDataObject.</span></span>  <span data-ttu-id="7c7f2-236">0 = filetimes は除外されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-236">0 = filetimes are excluded.</span></span>  <span data-ttu-id="7c7f2-237">1 = (既定) filetimes が含まれます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-237">1 = (default) filetimes are included.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7c7f2-238">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-238">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-239">マージ中に IRM 保護されたドキュメントを使用しているときに発生する問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-239">Fix to address a an issue when using IRM/protected documents during a merge error.</span></span>


### <a name="visio"></a><span data-ttu-id="7c7f2-240">Visio</span><span class="sxs-lookup"><span data-stu-id="7c7f2-240">Visio</span></span>

- <span data-ttu-id="7c7f2-241">問題を解決したので、ユーザーが Visio for Office 365 のコネクタを使用して、ユーザー設定の Visio ステンシルと組み込みのテンプレートの両方で直線を作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-241">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7c7f2-242">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-242">Office Suite</span></span>

- <span data-ttu-id="7c7f2-243">特定のシナリオで、[名前を付けて保存] の実行に失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-243">Fixed an issue where trying to do a SaveAs would fail in certain scenarios.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-november-10"></a><span data-ttu-id="7c7f2-245">バージョン 2010: 11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-245">Version 2010: November 10</span></span>
<span data-ttu-id="7c7f2-246">*バージョン 2010 (ビルド 13328.20356)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-246">*Version 2010 (Build 13328.20356)*</span></span>

<span data-ttu-id="7c7f2-247">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-247">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-249">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-249">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7c7f2-250">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-250">Outlook</span></span>

- <span data-ttu-id="7c7f2-251">ユーザーが代理人に編集者権限を付与できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-251">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7c7f2-252">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-252">Office Suite</span></span>

- <span data-ttu-id="7c7f2-253">同期バックからサーバーのみに移行したファイルを保存しようとすると失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-253">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-october-27"></a><span data-ttu-id="7c7f2-255">バージョン 2010: 10 月 27 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-255">Version 2010: October 27</span></span>
<span data-ttu-id="7c7f2-256">*バージョン 2010 (ビルド 13328.20292)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-256">*Version 2010 (Build 13328.20292)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7c7f2-258">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-258">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="7c7f2-259">Access</span><span class="sxs-lookup"><span data-stu-id="7c7f2-259">Access</span></span>

- <span data-ttu-id="7c7f2-260">**時代に追いつきましょう! 日付/時刻の拡張データ型では、より精度が高くなります。:** 改良されたデータ型をご紹介します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-260">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span> <span data-ttu-id="7c7f2-261">SQL との構文の互換性を高め、日付と時刻を含むレコードの精度と詳細レベルを向上させるため、Access に DateTime2 データ型を実装しています。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-261">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="7c7f2-262">この追加の日付および時間のデータ型には、より大きい日付範囲 (0001-01-01 ～ 9999-12-31) が含まれます。これにより、指定された時間の精度 (秒単位ではなくナノ秒) で提供され、計算を実行できるようになります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-262">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="7c7f2-263">有効にするには、[新しいフィールド] > [日付と時間の拡張] を選択します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-263">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="7c7f2-264">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-264">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="7c7f2-265">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-265">Excel</span></span>

- <span data-ttu-id="7c7f2-266">**Power Query を使用してデータ型を作成する:** Power Query を使用してあらゆるデータ ソースから豊富なデータ型を作成します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-266">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source.</span></span> [<span data-ttu-id="7c7f2-267">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-267">Learn more</span></span>](https://support.office.com/article/a465a3b7-3d37-4eb1-a59c-bd3163315308)<br /><span data-ttu-id="7c7f2-268">[ブログの投稿](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7c7f2-268">See details in [blog post](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)</span></span>

- <span data-ttu-id="7c7f2-269">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-269">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="7c7f2-270">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-270">No conversion required.</span></span><br /><span data-ttu-id="7c7f2-271">[ブログの投稿](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7c7f2-271">See details in [blog post](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="7c7f2-272">**アクション ペンを使用してすばやく編集する:** アクション ペンを使用すると、セルに直接手書きで書き込み、自動的に Excel データに変換されるインクでデータを書き留めることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-272">**Make quick edits using the action pen:** With the action pen, you can write by hand directly in the cells, jot down data with ink that gets automatically converted to Excel data.</span></span>

### <a name="outlook"></a><span data-ttu-id="7c7f2-273">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-273">Outlook</span></span>

- <span data-ttu-id="7c7f2-274">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-274">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="7c7f2-275">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-275">No conversion required.</span></span><br /><span data-ttu-id="7c7f2-276">[ブログの投稿](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7c7f2-276">See details in [blog post](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="7c7f2-277">**文章校正による支援:** Outlook では、入力中に文章校正のエラーが表示されます。シングル クリックで候補を適用できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-277">**Grammar checking's got your back:** Outlook marks grammar errors as you type, so you can apply suggestions with a single click.</span></span> [<span data-ttu-id="7c7f2-278">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-278">Learn more</span></span>](https://support.office.com/article/ddbadc42-4637-451d-b3f4-ecf295036fa9)<br /><span data-ttu-id="7c7f2-279">[ブログの投稿](https://insider.office.com/en-us/blog/grammar-and-style-suggestions-available-in-outlook)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7c7f2-279">See details in [blog post](https://insider.office.com/en-us/blog/grammar-and-style-suggestions-available-in-outlook)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7c7f2-280">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-280">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-281">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-281">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="7c7f2-282">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-282">No conversion required.</span></span><br /><span data-ttu-id="7c7f2-283">[ブログの投稿](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7c7f2-283">See details in [blog post](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="teams"></a><span data-ttu-id="7c7f2-284">Teams</span><span class="sxs-lookup"><span data-stu-id="7c7f2-284">Teams</span></span>

- <span data-ttu-id="7c7f2-285">**Microsoft Teams のテンプレート:** Teams のテンプレートを使用すると、ユーザーは新しいチームを作成するときにさまざまなカスタマイズ可能なテンプレートから選択できるため、すばやく開始できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-285">**Templates in Microsoft Teams:** With Templates in Teams, users can choose from a variety of customizable templates when creating a new team, helping them get started quickly.</span></span> <span data-ttu-id="7c7f2-286">IT 担当者は、組織の新しいカスタム テンプレートを作成して、チーム構造を標準化し、関連するアプリを表示し、ベスト プラクティスを拡張することもできます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-286">IT professionals can also create new custom templates for their organization, allowing them to standardize team structures, surface relevant apps, and scale best practices.</span></span>

- <span data-ttu-id="7c7f2-287">**ピン留めされた投稿:** この機能を使用すると、ユーザーはチャネル内のメッセージをチャネル情報ペインに「ピン留め」して、チャネルのすべてのメンバーに表示させることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-287">**Pinned Posts:** This feature allows users to "pin" any message in a channel to the channel info pane for all members of the channel to see.</span></span> <span data-ttu-id="7c7f2-288">チャネルにアクセスできるメンバーは誰でも、ピン留めされたメッセージを見ることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-288">Any members who have access to the channel will be able to see pinned messages.</span></span> <span data-ttu-id="7c7f2-289">チャネルのすべてのメンバーは、(チャネルのモデレート設定でオフにされていない限り) 任意のメッセージをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-289">Any member of a channel will be able to pin any message (unless turned off via channel moderation settings).</span></span>

- <span data-ttu-id="7c7f2-290">**アプリ カタログに送信:** この画面の左下に [アプリ カタログに送信] リンクが表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-290">**Submit to app catalog:** You’ll see a Submit to app catalog link on the lower left of this screen.</span></span> <span data-ttu-id="7c7f2-291">App Studio と Visual Studio に加えて、承認のためにアプリを送信できるもう 1 つの場所です。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-291">In addition to App Studio and Visual Studio, it’s another place where you can submit apps for approval.</span></span>

- <span data-ttu-id="7c7f2-292">**InVision によるフリーハンドを使用して、ポップアウトされた会議エクスペリエンスでホワイトボードを作成する:** InVision によるフリーハンド アプリを使用して、ポップアウトされた会議エクスペリエンスでホワイトボードを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-292">**Use Freehand by Invision to whiteboard in the popped out meeting experience:** You can now use the Freehand by Invision app to whiteboard in any meeting you take in the popped out meeting experience.</span></span> <span data-ttu-id="7c7f2-293">共有コンテンツ トレイからフリーハンド アプリを選択してインストールし、同僚とのホワイトボード セッションを開始することで、シームレスにブレーンストーミングを開始できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-293">Seamlessly start brainstorming by selecting the Freehand app from the share content tray and, installing it, and starting the whiteboarding session with your colleagues!</span></span>

### <a name="word"></a><span data-ttu-id="7c7f2-294">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-294">Word</span></span>

- <span data-ttu-id="7c7f2-295">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-295">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="7c7f2-296">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-296">No conversion required.</span></span><br /><span data-ttu-id="7c7f2-297">[ブログの投稿](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7c7f2-297">See details in [blog post](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-300">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-300">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7c7f2-301">Access</span><span class="sxs-lookup"><span data-stu-id="7c7f2-301">Access</span></span>

- <span data-ttu-id="7c7f2-302">Office 以外のアプリケーションから DAO を使用すると、アプリケーションが予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-302">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="outlook"></a><span data-ttu-id="7c7f2-303">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-303">Outlook</span></span>

- <span data-ttu-id="7c7f2-304">返信または転送時に中国語メッセージのヘッダーが読み取れなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-304">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="7c7f2-305">OFT ファイルとして保存するときに中国語の文字が疑問符に変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-305">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="7c7f2-306">クラウド設定を有効にしているユーザーに対して、2つ目の空白の署名を作成するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-306">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


- <span data-ttu-id="7c7f2-307">ユーザーに対してクラウド設定が既定でオンにならない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-307">We fixed a n issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="7c7f2-308">ユーザーの署名への変更が保存できない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-308">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7c7f2-309">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-309">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-310">これは、PresentationBeforeClose イベントを聞き、イベント ハンドラーの一部として Presentation.Saved プロパティをチェックするアドインがある場合、ドキュメントを閉じるときに保存プロンプトがループで表示される問題の修正です。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-310">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


### <a name="project"></a><span data-ttu-id="7c7f2-311">Project</span><span class="sxs-lookup"><span data-stu-id="7c7f2-311">Project</span></span>

- <span data-ttu-id="7c7f2-312">プロジェクトを PWA からローカル mpp ファイルに保存すると、ユーザーが実際に変更していないデータに対して ProjectBeforeTaskChangeEvent が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-312">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="7c7f2-313">リソースの配分状況が特定の方法で指定されているファイルを開くと、Project が予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-313">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="7c7f2-314">プロジェクトを PWA からローカル mpp ファイルに保存すると、ユーザーが実際に変更していないデータに対して ProjectBeforeTaskChangeEvent が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-314">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="7c7f2-315">タスクフォームタイプビュー内でラグが変更された場合、ProjectBeforeTaskChagne イベントの NewVal に正しい値がない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-315">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7c7f2-316">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-316">Office Suite</span></span>

- <span data-ttu-id="7c7f2-317">Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-317">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="7c7f2-318">このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-318">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>

- <span data-ttu-id="7c7f2-319">Microsoft 365 エンドポイントのデータ損失防止が、ディスク上の Office ドキュメントを分類できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-319">Fixed an issue where Microsoft 365 Endpoint data loss prevention was unable to classify Office documents on disk.</span></span>


[//]: # (BUGDETAILS コンテンツ エンドを削除しないでください。終了)

## <a name="version-2009-october-21"></a><span data-ttu-id="7c7f2-321">バージョン 2009 : 10 月 21 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-321">Version 2009: October 21</span></span>
<span data-ttu-id="7c7f2-322">*バージョン 2009 (ビルド 13231.20418)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-322">*Version 2009 (Build 13231.20418)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-324">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-324">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7c7f2-325">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-325">Outlook</span></span>

- <span data-ttu-id="7c7f2-326">ユーザーが代理人に編集者権限を付与できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-326">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="7c7f2-327">ユーザーが検索結果を選択したときにアプリケーションが予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-327">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="7c7f2-328">返信または転送時に中国語メッセージのヘッダーが読み取れなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-328">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7c7f2-329">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-329">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-330">ユーザーが別のスライドをクリックして表示するまで、Forms コンテンツ アドインが挿入後にレンダリングされない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-330">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-october-13"></a><span data-ttu-id="7c7f2-332">バージョン2009: 10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-332">Version 2009: October 13</span></span>
<span data-ttu-id="7c7f2-333">*バージョン2009 (ビルド 13231.20390)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-333">*Version 2009 (Build 13231.20390)*</span></span>

<span data-ttu-id="7c7f2-334">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-334">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-336">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-336">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="7c7f2-337">Project</span><span class="sxs-lookup"><span data-stu-id="7c7f2-337">Project</span></span>

- <span data-ttu-id="7c7f2-338">リソースの配分状況が特定の方法で指定されている場合に、Project がクラッシュすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-338">Fixed an issue where Project may crash on opening files where resource contours were specified in a certain manner.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-october-08"></a><span data-ttu-id="7c7f2-340">バージョン 2009: 10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-340">Version 2009: October 08</span></span>
<span data-ttu-id="7c7f2-341">*バージョン 2009 (ビルド 13231.20368)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-341">*Version 2009 (Build 13231.20368)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-343">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-343">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7c7f2-344">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-344">Outlook</span></span>

- <span data-ttu-id="7c7f2-345">キャッシュされていない共有の予定表を検索するときに、結果が返されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-345">Addresses an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="7c7f2-346">一部のユーザーの環境で、Outlook がオフラインの状態で予期せず起動する原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-346">Addresses an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="7c7f2-347">代理人が別のメールボックスで共有フォルダーを開くと、断続的にエラーが表示される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-347">Addresses an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7c7f2-348">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-348">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-349">セキュリティ修正プログラムを適用して、保護ビューで PowerPoint ファイルを開くと、 IRM による保護が無効になる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-349">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7c7f2-350">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-350">Office Suite</span></span>

- <span data-ttu-id="7c7f2-351">Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-351">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="7c7f2-352">このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-352">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-september-28"></a><span data-ttu-id="7c7f2-354">バージョン 2009: 9 月 28 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-354">Version 2009: September 28</span></span>
<span data-ttu-id="7c7f2-355">*バージョン 2009 (ビルド13231.20262)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-355">*Version 2009 (Build 13231.20262)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7c7f2-357">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-357">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7c7f2-358">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-358">Excel</span></span>

- <span data-ttu-id="7c7f2-359">**図形を画像として保存する:** 簡単なクリック操作で図形、アイコン、その他のオブジェクトを画像ファイルとして保存し、別の場所で再利用することができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-359">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="7c7f2-360">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-360">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="7c7f2-361">**データ型を使用して Power BI から組織データを取得する:** Power BI からの Excel データ型が Office 365、Microsoft 365、Power BI Pro サービス プランを使用する組織の Insider に展開されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-361">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 / Microsoft 365 and the Power BI Pro service plan.</span></span> <span data-ttu-id="7c7f2-362">必要な情報を入手し、簡単に更新することは、多くの日常のワークフローに欠かせません。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-362">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="7c7f2-363">Excel のデータ型として、Power BI から会社または組織の情報へのアクセスを提供し、スプレッドシートにリンクされた情報を取り込む機能を拡張します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-363">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="7c7f2-364">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-364">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="7c7f2-365">[ブログの投稿](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7c7f2-365">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="7c7f2-366">**数式で使用する変数を作成する:** LET 関数を使用してパフォーマンス、読みやすさ、および構成性を向上させます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-366">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="7c7f2-367">この関数では、新規または既存の数式に名前付き変数を作成することができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-367">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="7c7f2-368">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-368">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="7c7f2-369">[ブログの投稿](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7c7f2-369">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="7c7f2-370">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-370">Outlook</span></span>

- <span data-ttu-id="7c7f2-371">**自動拡張オンライン アーカイブ検索:** 自動拡張オンライン アーカイブ検索を有効にします</span><span class="sxs-lookup"><span data-stu-id="7c7f2-371">**Auto-Expanding Online Archive Search:** Enabling auto-expanding Online Archive Search</span></span>

- <span data-ttu-id="7c7f2-372">**Outlook の新しいプロファイル カード:** Outlook の新しいプロファイル カードは、組織ビューの詳細を含み、Outlook Web のカード スタイルに一致します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-372">**New profile card for Outlook:** New profile card for Outlook including a better Organization view and matches the card style of Outlook Web.</span></span>

### <a name="teams"></a><span data-ttu-id="7c7f2-373">Teams</span><span class="sxs-lookup"><span data-stu-id="7c7f2-373">Teams</span></span>

- <span data-ttu-id="7c7f2-374">**Microsoft Teams でファイルを共有:** [詳細情報](/MicrosoftTeams/sharing-files-in-teams)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-374">**Sharing files in Microsoft Teams:** [Learn more](/MicrosoftTeams/sharing-files-in-teams)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-377">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-377">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7c7f2-378">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-378">Outlook</span></span>

- <span data-ttu-id="7c7f2-379">件名が空白の場合、一部の自動的に生成されたメールの本文が空で送信される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-379">Addresses an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7c7f2-380">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-380">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-381">特定のデータ オブジェクト タイプ (E2o) を大量に含むファイルの共同編集が遅くなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-381">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>


### <a name="project"></a><span data-ttu-id="7c7f2-382">Project</span><span class="sxs-lookup"><span data-stu-id="7c7f2-382">Project</span></span>

- <span data-ttu-id="7c7f2-383">イベント コードの実行中に、[タスク フォーム] ビューから変更を加えようとするときに、[OK] ボタンをクリックしても変更が反映されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-383">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


### <a name="word"></a><span data-ttu-id="7c7f2-384">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-384">Word</span></span>

- <span data-ttu-id="7c7f2-385">スタイル ギャラリー ダイアログの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-385">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7c7f2-386">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-386">Office Suite</span></span>

- <span data-ttu-id="7c7f2-387">この変更により、[エクスポート] ボタンをクリックしてもエクスポートされないという [アニメーション GIF にエクスポート] 機能の問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-387">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="7c7f2-388">この変更では、[図の圧縮] ダイアログで一部のユーザー設定が保持されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-388">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-september-22"></a><span data-ttu-id="7c7f2-390">バージョン 2008: 9 月 22 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-390">Version 2008: September 22</span></span>
<span data-ttu-id="7c7f2-391">*バージョン 2008 (ビルド 13127.20508)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-391">*Version 2008 (Build 13127.20508)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-393">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-393">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7c7f2-394">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-394">Excel</span></span>

- <span data-ttu-id="7c7f2-395">シートの一番上の行を固定した後にクイック分析を使用すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-395">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="7c7f2-396">IFNA () を使用する数式が含まれている場合、破損したワークブックに関する警告を発する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-396">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="7c7f2-397">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-397">Outlook</span></span>

- <span data-ttu-id="7c7f2-398">隅にある [X] をクリックして共有の予定表を閉じることができない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-398">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="7c7f2-399">添付ファイルのアップロードのパフォーマンスの問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-399">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7c7f2-400">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-400">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-401">PowerPoint アプリのクラッシュの原因となった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-401">We have fixed an issue which was causing the crash in PowerPoint app.</span></span>


### <a name="visio"></a><span data-ttu-id="7c7f2-402">Visio</span><span class="sxs-lookup"><span data-stu-id="7c7f2-402">Visio</span></span>

- <span data-ttu-id="7c7f2-403">テキストを配置するとリアルタイムのプレビューがクラッシュする問題がお客様から報告されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-403">Live preview crashes on text alignment reported by customers.</span></span> <span data-ttu-id="7c7f2-404">7 月のフォークで最も多く報告されているクラッシュ。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-404">Top hitting crash of July fork.</span></span>


### <a name="word"></a><span data-ttu-id="7c7f2-405">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-405">Word</span></span>

- <span data-ttu-id="7c7f2-406">スタイル ギャラリー ダイアログの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-406">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7c7f2-407">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-407">Office Suite</span></span>

- <span data-ttu-id="7c7f2-408">GIF/アニメーション model3D を使用したアイドル時の高い CPU 使用率を修正</span><span class="sxs-lookup"><span data-stu-id="7c7f2-408">Fixes high CPU usage on idle with GIF/animated model3D</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-september-09"></a><span data-ttu-id="7c7f2-410">バージョン 2008: 9 月 9 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-410">Version 2008: September 09</span></span>
<span data-ttu-id="7c7f2-411">*バージョン 2008(ビルド13127.20408)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-411">*Version 2008 (Build 13127.20408)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-413">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-413">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7c7f2-414">Access</span><span class="sxs-lookup"><span data-stu-id="7c7f2-414">Access</span></span>

- <span data-ttu-id="7c7f2-415">テキストを編集するため [ズーム] ボックスを起動する (Shift + F2) ときに、Access がクラッシュする可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-415">This change fixes an issue that could cause Access to crash when launching the Zoom box (Shift + F2) to edit text.</span></span>


### <a name="excel"></a><span data-ttu-id="7c7f2-416">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-416">Excel</span></span>

- <span data-ttu-id="7c7f2-417">Format Painter を使用すると、特定の状況で Excel がクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-417">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>


### <a name="word"></a><span data-ttu-id="7c7f2-418">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-418">Word</span></span>

- <span data-ttu-id="7c7f2-419">図形のサイズを変更すると、ユーザーのコンテンツが失われる場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-419">We fixed an issue where the user might lose content when resize a shape.</span></span>


- <span data-ttu-id="7c7f2-420">基本スタイルが標準スタイルで更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-420">We fixed an issue which the base styles are not updated with Normal style.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7c7f2-421">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-421">Office Suite</span></span>

- <span data-ttu-id="7c7f2-422">この変更では、[図の圧縮] ダイアログで一部のユーザー設定が保持されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-422">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-august-31"></a><span data-ttu-id="7c7f2-424">バージョン 2008: 8 月 31 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-424">Version 2008: August 31</span></span>
<span data-ttu-id="7c7f2-425">*バージョン 2008 (ビルド 13127.20296)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-425">*Version 2008 (Build 13127.20296)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7c7f2-427">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-427">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7c7f2-428">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-428">Excel</span></span>

- <span data-ttu-id="7c7f2-429">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-429">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="7c7f2-430">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-430">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="7c7f2-431">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-431">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="7c7f2-432">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-432">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="7c7f2-433">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-433">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="7c7f2-434">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7c7f2-434">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="7c7f2-435">**Excel で洗練された Visio 図を作成する:** ワークシートにデータを入力して、フロー チャートまたは組織図を作成します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-435">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="7c7f2-436">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-436">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a><span data-ttu-id="7c7f2-437">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-437">Outlook</span></span>

- <span data-ttu-id="7c7f2-438">**メール内のリンクの改善:** ファイルへのリンクを含めると、ファイル名が URL に置き換わります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-438">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="7c7f2-439">アクセス許可を変更して、すべての受信者がアクセスできるようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-439">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="7c7f2-440">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-440">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="7c7f2-441">[ブログの投稿](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7c7f2-441">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>



### <a name="powerpoint"></a><span data-ttu-id="7c7f2-442">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-442">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-443">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-443">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="7c7f2-444">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-444">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="7c7f2-445">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-445">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="7c7f2-446">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-446">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="7c7f2-447">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-447">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="7c7f2-448">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7c7f2-448">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="teams"></a><span data-ttu-id="7c7f2-449">Teams</span><span class="sxs-lookup"><span data-stu-id="7c7f2-449">Teams</span></span>

- <span data-ttu-id="7c7f2-450">**コールマージ:** コールマージにより、エンドユーザーは、アクティブな保持された 1 対 1 の 通話を別の1 対 1 の通話または別のグループ通話に結合できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-450">**Call Merge:** Call Merge gives end users the capability to merge their active unheld 1-1 call into another 1-1 call or another group call.</span></span> <span data-ttu-id="7c7f2-451">これは、Teams の VOIP 通話と PSTN 通話に適用されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-451">This applies to Teams VOIP calls and PSTN calls.</span></span>

- <span data-ttu-id="7c7f2-452">**管理者は、Firstline ワーカーの出席状況をシフトベース (オンシフト、オフシフト) で構成できます:** 管理者は、シフト中、ビジー (シフト中に切り替えることができます)、シフト外といったシフトベースの出席状況を表示できるように Firstline ワーカーを構成できます。

</span><span class="sxs-lookup"><span data-stu-id="7c7f2-452">**Admins can configure shift-based presence (On shift, Off shift) for their Firstline workers:** Admins can configure their firstline workers to have shift-based presence states: On shift, Busy (can be toggled when on shift), and Off shift.</span></span>

- <span data-ttu-id="7c7f2-453">**Teams の Cortana 音声スキル:** Teams モバイルアプリの Cortana 音声スキルにより、ユーザーは自然な話し言葉を使用して、会議、コミュニケーション、コラボレーションといったタスクを簡単に実行できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-453">**Cortana voice skills in Teams:** Cortana voice skills in Teams mobile app help users perform meeting, communication and collaboration tasks simply using spoken natural language.</span></span> <span data-ttu-id="7c7f2-454">ユーザーは、家事を色々こなしたり、犬の散歩をしたり、外出先で誰かと連絡する必要がある場合、Teams アプリのマイクボタンをクリックして Cortana に話しかけ、「ミーガンに電話する」や「次の会議にメッセージを送信する」といったリクエストを行うことができます。

</span><span class="sxs-lookup"><span data-stu-id="7c7f2-454">Users can speak to Cortana by clicking on the microphone button in Teams app and make requests like “Call Megan” or “Send a message to my next meeting” if they need to connect with someone while juggling household chores or walking the dog or generally on the go.</span></span> <span data-ttu-id="7c7f2-455">ユーザーは「次の会議に参加する」と言うだけで会議に参加したり、「午前中の予定を教えて」と質問してカレンダーを確認したりできます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-455">Users can join meetings simply by saying “Join my next meeting” or check their calendar by asking “what do I have this morning”.</span></span> <span data-ttu-id="7c7f2-456">会議または通話に入ると、会議ステージのオーバーフローメニューから Cortana を呼び出して、名前または番号によるメンバーの追加 (「通話にミーガンを追加」)、デッキプレゼンテーション (「プレゼンテーション 四半期レビューデッキ」) またはスライドの紹介 (「付録スライドを紹介」) といった、一般的な会議のタスクを実行したりできます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-456">Once in a meeting or a call, they can invoke Cortana from the overflow menu in the meeting stage and perform typical in-meeting tasks like adding people by name or number (“Add Megan to the call”), deck presentation (“present the quarterly review deck”) or navigating slides (“Go to the appendix slide”).</span></span> <span data-ttu-id="7c7f2-457">この機能がサポートするその他の機能としては、ファイルの検索と共有、検索、およびTeamsアプリ内での一般的な移動 (「Johnとのチャットを開く、未読のアクティビティに移動する、メンションに移動する」など) があります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-457">Other things that the feature supports are finding and sharing files, search, and generally navigating within the Teams app (“Open my chat with John, Go to my unread activity, Go to my mentions etc.).</span></span> <span data-ttu-id="7c7f2-458">チーム内の Cortana は、[オンラインサービス規約 (OST) ](https://www.microsoft.com/licensing/product-licensing/products)に反映されているように、Cortana エンタープライズサービスと同じエンタープライズレベルのプライバシー、セキュリティ、およびコンプライアンスの約束を満たしています。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-458">Cortana in Teams meets the same enterprise-level privacy, security, and compliance promises for Cortana enterprise services, as reflected in the [Online Services Terms (OST)](https://www.microsoft.com/licensing/product-licensing/products).</span></span>

- <span data-ttu-id="7c7f2-459">**グループチャットの拡大:** Teams で 250 人がグループチャットに参加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-459">**Group chat increase:** Teams added the ability to now have 250 participants in a group chat.</span></span>

- <span data-ttu-id="7c7f2-460">**シフトによるタグ付け:** この機能を使用すると、 Teams の [シフトアプリ](https://support.microsoft.com/office/get-started-in-shifts-5f3e30d8-1821-4904-be26-c3cd25a497d6#bkmk_openshiftsappdesktop)で、スケジュールとシフトグループ名に一致するタグが自動的に割り当てられます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-460">**Tagging by Shift:** With this feature, people are automatically assigned tags that match their schedule and shift group name in the [Shifts app](https://support.microsoft.com/office/get-started-in-shifts-5f3e30d8-1821-4904-be26-c3cd25a497d6#bkmk_openshiftsappdesktop) in Teams.</span></span>

### <a name="word"></a><span data-ttu-id="7c7f2-461">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-461">Word</span></span>

- <span data-ttu-id="7c7f2-462">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-462">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="7c7f2-463">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-463">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="7c7f2-464">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-464">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="7c7f2-465">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-465">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="7c7f2-466">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-466">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="7c7f2-467">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7c7f2-467">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="7c7f2-468">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-468">Office Suite</span></span>

- <span data-ttu-id="7c7f2-469">**タブ付きのウィンドウ**: アプリの右側にあるタブ UI を使用して、複数のウィンドウ間を切り替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-469">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="7c7f2-470">UI は、2 つ以上のウィンドウが開かれている場合にのみ表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-470">The UI will only be visible when you have 2+ panes open.</span></span><br /><span data-ttu-id="7c7f2-471">[ブログの投稿](https://blog-insider.office.com/2020/02/20/improved-pane-management/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7c7f2-471">See details in [blog post](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-474">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-474">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7c7f2-475">Access</span><span class="sxs-lookup"><span data-stu-id="7c7f2-475">Access</span></span>

- <span data-ttu-id="7c7f2-476">この問題は解決されました。これで、Office のクイック実行アプリケーション以外でも ODBC ドライバーを使用できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-476">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>


### <a name="outlook"></a><span data-ttu-id="7c7f2-477">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-477">Outlook</span></span>

- <span data-ttu-id="7c7f2-478">プロファイルに追加されたサブ アカウントから会議出席依頼を作成しようとした場合に、ユーザーのメール アドレスの代わりに空欄の From: フィールドが表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-478">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="7c7f2-479">共有メールボックスを追加した後に、ユーザーがパブリック フォルダーに接続できない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-479">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="7c7f2-480">特定の状況で代理人が会議を辞退したときに、マネージャーのカレンダーから削除されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-480">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="7c7f2-481">共有カレンダーの改善機能を使用している一部のユーザーが、新しく追加された共有カレンダーを表示できない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-481">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="7c7f2-482">クラウドの添付ファイルを操作するときに、ユーザーに時折クラッシュが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-482">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="7c7f2-483">SharePoint ファイルに Smart Link を追加すると、一部の文字セットのユーザーにファイル名が正しく表示されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-483">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="7c7f2-484">新しいメールに返信、または新しいメールを作成するときにユーザーにクラッシュが発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-484">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="7c7f2-485">[ヘッダーのみダウンロード] オプションが選択されている POP アカウントから 4 件以上のメールを削除しようとするとクラッシュするという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-485">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="7c7f2-486">一部のユーザーにスケジュール アシスタント ページが表示されない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-486">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="7c7f2-487">これにより、受信者を編集しているときに不定期にクラッシュする問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-487">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="7c7f2-488">コンパクト ビューを使用するときに異常が表示される原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-488">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="7c7f2-489">右クリックのコンテキストメニューが検索コントロールに表示されない問題の原因を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-489">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="7c7f2-490">ユーザーが新しいメールに返信または作成するときに次のエラーを受け取る原因となった問題に対処します。「この Web ページのファイルの一部が予期された場所にありません。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-490">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="7c7f2-491">この Web ページをダウンロードする必要がありますか? </span><span class="sxs-lookup"><span data-stu-id="7c7f2-491">Do you want to download them anyway?</span></span> <span data-ttu-id="7c7f2-492">Web ページが信頼できるソースからのものであることを確認したら、[はい] をクリックします。」</span><span class="sxs-lookup"><span data-stu-id="7c7f2-492">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


### <a name="project"></a><span data-ttu-id="7c7f2-493">Project</span><span class="sxs-lookup"><span data-stu-id="7c7f2-493">Project</span></span>

- <span data-ttu-id="7c7f2-494">SharePoint タスクリストに接続されているプロジェクトのプロジェクト終了日が更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-494">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="7c7f2-495">リソースに複数のコスト単価表が定義されている場合に、残りのコストが正しく計算されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-495">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

### <a name="skype"></a><span data-ttu-id="7c7f2-496">Skype</span><span class="sxs-lookup"><span data-stu-id="7c7f2-496">Skype</span></span>

- <span data-ttu-id="7c7f2-497">ダンス絵文字の肌の色を中間色に変更しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-497">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="7c7f2-498">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-498">Word</span></span>

- <span data-ttu-id="7c7f2-499">この変更により、以前の共同編集セッションの後に Office アプリケーションがサイレントな保存の失敗状態に陥ることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-499">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="7c7f2-500">マクロ AutoOpen が AutoExec の前に実行されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-500">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-august-25"></a><span data-ttu-id="7c7f2-502">バージョン 2007: 8 月 25 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-502">Version 2007: August 25</span></span>
<span data-ttu-id="7c7f2-503">*バージョン 2007 (ビルド 13029.20460)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-503">*Version 2007 (Build 13029.20460)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-505">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-505">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7c7f2-506">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-506">Excel</span></span>

- <span data-ttu-id="7c7f2-507">LET () 関数を使用して、数式を含むファイルを保存しようとすると、エラーが発生することがあります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-507">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>


### <a name="outlook"></a><span data-ttu-id="7c7f2-508">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-508">Outlook</span></span>

- <span data-ttu-id="7c7f2-509">SharePoint ファイルに Smart Link を追加すると、一部の文字セットのユーザーにファイル名が正しく表示されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-509">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="7c7f2-510">Outlook ユーザーにコンパクト ビューでのナビゲーションの問題が表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-510">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7c7f2-511">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-511">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-512">PowerPoint アプリでクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-512">We have fixed a crash issue with PowerPoint app.</span></span>


### <a name="word"></a><span data-ttu-id="7c7f2-513">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-513">Word</span></span>

- <span data-ttu-id="7c7f2-514">新しいメールに返信または作成するときにユーザーにクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-514">Addresses an issue that caused users to experience a crash when replying to or composing new mail.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7c7f2-515">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-515">Office Suite</span></span>

- <span data-ttu-id="7c7f2-516">以前の Web サービス ベースの [共有] ウィンドウで、[共有] ウィンドウが開いているときに文書を閉じるとクラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-516">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="7c7f2-517">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-517">This is now fixed.</span></span>


- <span data-ttu-id="7c7f2-518">特定の状況下で UI 要素またはコンテンツが表示されない問題を修正しました。特に、発表者ツールのオン/オフ、または複数のモニターの使用に関して発生しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-518">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-august-11"></a><span data-ttu-id="7c7f2-520">バージョン 2007: 8 月 11 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-520">Version 2007: August 11</span></span>
<span data-ttu-id="7c7f2-521">*バージョン 2007 (ビルド 13029.20344)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-521">*Version 2007 (Build 13029.20344)*</span></span>

<span data-ttu-id="7c7f2-522">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-522">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-524">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-524">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7c7f2-525">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-525">Outlook</span></span>

- <span data-ttu-id="7c7f2-526">Outlook で検索候補を取得できない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-526">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="7c7f2-527">ユーザーがペルソナ情報を取得しようとしたときにクラッシュする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-527">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


### <a name="project"></a><span data-ttu-id="7c7f2-528">Project</span><span class="sxs-lookup"><span data-stu-id="7c7f2-528">Project</span></span>

- <span data-ttu-id="7c7f2-529">正常ではない状態になったプロジェクトを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-529">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-july-30"></a><span data-ttu-id="7c7f2-531">バージョン 2007: 7 月 30 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-531">Version 2007: July 30</span></span>
<span data-ttu-id="7c7f2-532">*バージョン 2007 (ビルド 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-532">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7c7f2-534">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-534">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7c7f2-535">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-535">Excel</span></span>

- <span data-ttu-id="7c7f2-536">**PDF に接続:** PDF からデータに接続、インポート、更新します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-536">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="7c7f2-537">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-537">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="7c7f2-538">**他のユーザーを混乱させずに、フィルター処理して並べ替える:**、Sheet View で他のユーザーとの共同作業を行いながら Excel ファイルの並べ替えやフィルター処理ができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-538">**Filter and sort without disrupting others:** You can now sort and filter your Excel file while collaborating with others with Sheet View.</span></span> <span data-ttu-id="7c7f2-539">この新機能により、文書を共同編集しているときに、他のユーザーの並べ替えやフィルター処理による影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-539">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span> [<span data-ttu-id="7c7f2-540">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-540">Learn more</span></span>](https://support.office.com/article/0eea3dc5-d7d1-44c5-a953-25ebfbd6c1a6)

- <span data-ttu-id="7c7f2-541">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-541">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

- <span data-ttu-id="7c7f2-542">**Excel で Power BI のデータセットからピボットテーブルを作成する:** Power BI に保存されているデータセットに接続されている Excel のピボットテーブルを数回のクリックで作成できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-542">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="7c7f2-543">これにより、ピボットテーブルと Power BI の両方を最大限に活用できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-543">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="7c7f2-544">セキュリティで保護された Power BI データセットからピボットテーブルを使って、データの計算、集計、分析を行います。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-544">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="7c7f2-545">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-545">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="7c7f2-546">[ブログの投稿](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7c7f2-546">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="7c7f2-547">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-547">Outlook</span></span>

- <span data-ttu-id="7c7f2-548">**クイック投票を使用して、Outlook で投票を作成:** 簡単に投票を作成し、票を収集して、メールに結果を表示します。[詳細情報](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-548">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="7c7f2-549">**メールの一部として画像を送信するときに、画像を高品質に維持する:** メールの内容の一部として画像を送信するときに、画像の圧縮を制限するための新しい Outlook の設定を使用できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-549">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

- <span data-ttu-id="7c7f2-550">**以前のセッションからアイテムを素早く再開する:** 以前の Outlook セッションからアイテムを素早く再開するためのオプションが追加されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-550">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="7c7f2-551">Outlook がクラッシュした場合でも、または終了した場合でも、アプリを再び開くと、すばやくアイテムを再起動することができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-551">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="7c7f2-552">この機能は既定でオンになっています。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-552">This feature is on by default.</span></span> <span data-ttu-id="7c7f2-553">オフにするには、[オプション] > [一般] > [開始オプション] に移動します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-553">To turn it off, go to Options > General > Start up Options.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7c7f2-554">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-554">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-555">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-555">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="teams"></a><span data-ttu-id="7c7f2-556">Teams</span><span class="sxs-lookup"><span data-stu-id="7c7f2-556">Teams</span></span>

- <span data-ttu-id="7c7f2-557">**簡素化された新しい通知設定:** 機能が強化され、やり方がより簡素化された通知設定をユーザーが管理できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-557">**New simplified notification settings:** Users can now manage their notifications settings in a more simplified manner with enhanced functionalities.</span></span>

- <span data-ttu-id="7c7f2-558">**Teams でWindows ネイティブ通知をサポート:** ユーザーはバナーに組み込まれた Teams、または Windows のネイティブ バナーのいずれかを使用して、通知配信の優先手段を選択できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-558">**Windows Native Notification are now Supported on Teams:** Users can now select their preferred means of notification delivery, either through teams built in banners or the windows native banners.</span></span>

- <span data-ttu-id="7c7f2-559">**[チャンネル情報] ウィンドウ:** チャンネルヘッダーの "チャンネル情報" アイコンを選択したときに、[チャンネルの説明]、[最近の寄稿者]、[メンバー] に加えて、システム メッセージの新しいホームを含むチャンネル情報の概要を表示するウィンドウが開きます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-559">**Channel Info Pane:** When selecting on the "Channel info" icon in the channel header, a pane will open where you will see a summary of channel information including the channel description, a list of recent contributors and members, as well as the new home for system messages.</span></span>

- <span data-ttu-id="7c7f2-560">**チャット通知のプレビューをオフにする:**、ユーザーは設定を変更したり、チャット通知トーストのプレビューを管理したりすることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-560">**Turn off previews for your chat notifications:** Users can change settings and manage previews for their chat notification toasts.</span></span>

- <span data-ttu-id="7c7f2-561">**返信の候補:** Teams ユーザーに、自分の会話への返信の候補を提案する機能が追加されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-561">**Suggested replies:** We added the ability for Teams users to have a suggested reply to their conversations.</span></span> <span data-ttu-id="7c7f2-562">これらの候補が有効になっている場合は、チャット メッセージの下部に表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-562">These suggestions will appear at the bottom of a chat message if they are enabled.</span></span> <span data-ttu-id="7c7f2-563">メッセージへの返信をすばやく簡単に作成できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-563">They make replying to messages quick and easy!</span></span>

### <a name="word"></a><span data-ttu-id="7c7f2-564">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-564">Word</span></span>

- <span data-ttu-id="7c7f2-565">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-565">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

- <span data-ttu-id="7c7f2-566">**テキストをベクター内で保持:** 地図やグラフ、その他の SVG ベクターを Excel、Word、PowerPoint で変換する場合、それらのオブジェクトの中にテキストを保持できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-566">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-569">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-569">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7c7f2-570">Access</span><span class="sxs-lookup"><span data-stu-id="7c7f2-570">Access</span></span>

- <span data-ttu-id="7c7f2-571">この修正プログラムでは、特定のクエリを実行しようとすると、"クエリが複雑すぎます" というエラーメッセージが表示される問題に対処しています。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-571">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex".</span></span>

### <a name="excel"></a><span data-ttu-id="7c7f2-572">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-572">Excel</span></span>

- <span data-ttu-id="7c7f2-573">改ページ プレビューで複数のシートを含むブックを読み込むときにエラーやハングが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-573">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>


### <a name="outlook"></a><span data-ttu-id="7c7f2-574">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-574">Outlook</span></span>

- <span data-ttu-id="7c7f2-575">保護されたコンテキストから保護されていないコンテキストに返信するとき、送信元アドレスを切り替えると、CLP のユーザーにクラッシュが発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-575">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="7c7f2-576">[共有フォルダーのダウンロード] がチェックされていない場合、共有された予定表の会議の [返信オプション] に [転送を許可する] オプションが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-576">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="7c7f2-577">管理者のカレンダー上で既存のカレンダーの予定を編集するときに代理人がエラーを受け取る問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-577">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="7c7f2-578">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカルコンピューターに保存できない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-578">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="7c7f2-579">スケジュール アシスタント ページが表示されない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-579">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="7c7f2-580">インシデント通知アラートのフォーマットの問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-580">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

### <a name="project"></a><span data-ttu-id="7c7f2-581">Project</span><span class="sxs-lookup"><span data-stu-id="7c7f2-581">Project</span></span>

- <span data-ttu-id="7c7f2-582">[リソースの割り当て] ダイアログ ボックスで選択されているタスクが、[タスク ボード] ビューで選択したタスクと異なる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-582">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="7c7f2-583">複数の依存関係があるタスクを貼り付けると、すべての依存関係が正しくコピーされるわけではない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-583">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="7c7f2-584">Project から SharePoint ドキュメント ライブラリに PDF/XPS を保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-584">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7c7f2-585">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-585">Office Suite</span></span>

- <span data-ttu-id="7c7f2-586">製品版への移行が完了した場合でも、ランタイムメッセージが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-586">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="7c7f2-587">この問題の修正では、サービスが追加された製品を適切に計算するようにしました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-587">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="7c7f2-588">新たに追加された製品をフィルターで除外し (新しい構成に存在することも確認)、既存の製品リリース ID の最後に追加しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-588">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-july-28"></a><span data-ttu-id="7c7f2-590">バージョン 2006: 7 月 28 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-590">Version 2006: July 28</span></span>
<span data-ttu-id="7c7f2-591">*バージョン 2006 (ビルド 13001.20498)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-591">*Version 2006 (Build 13001.20498)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-593">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-593">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7c7f2-594">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-594">Excel</span></span>

- <span data-ttu-id="7c7f2-595">改ページ プレビューで複数のシートを含むブックを読み込むときにエラーやハングが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-595">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>


### <a name="outlook"></a><span data-ttu-id="7c7f2-596">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-596">Outlook</span></span>

- <span data-ttu-id="7c7f2-597">SVG 画像のコピーと貼り付けの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-597">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="word"></a><span data-ttu-id="7c7f2-598">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-598">Word</span></span>

- <span data-ttu-id="7c7f2-599">SVG 画像のコピーと貼り付けの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-599">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7c7f2-600">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-600">Office Suite</span></span>

- <span data-ttu-id="7c7f2-601">タイミングの問題で、Office ファイルを閉じるときにクラッシュすることがあります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-601">A timing issue could cause a crash when closing office files.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-july-14"></a><span data-ttu-id="7c7f2-603">バージョン 2006: 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-603">Version 2006: July 14</span></span>
<span data-ttu-id="7c7f2-604">*バージョン 2006 (ビルド 13001.20384)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-604">*Version 2006 (Build 13001.20384)*</span></span>

<span data-ttu-id="7c7f2-605">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-605">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-607">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-607">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7c7f2-608">アクセス</span><span class="sxs-lookup"><span data-stu-id="7c7f2-608">Access</span></span>

- <span data-ttu-id="7c7f2-609">ID (オートナンバーなど) フィールドが含まれるリンク付きの SQL 表を挿入する場合についての問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-609">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

### <a name="excel"></a><span data-ttu-id="7c7f2-610">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-610">Excel</span></span>

- <span data-ttu-id="7c7f2-611">読み取り専用モードのブックに対して、ドキュメント分類を自動的に行った可能性があります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-611">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="7c7f2-612">アカウントからサインアウトした場合にデータ接続を作成しようとすると発生する可能性があるクラッシュを修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-612">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="onenote"></a><span data-ttu-id="7c7f2-613">OneNote</span><span class="sxs-lookup"><span data-stu-id="7c7f2-613">OneNote</span></span>

- <span data-ttu-id="7c7f2-614">リソースの使用率を低下させて、共同編集状態の検出機能を改善します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-614">Improve detection of co-authoring status to reduce resource utilization.</span></span>

### <a name="outlook"></a><span data-ttu-id="7c7f2-615">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-615">Outlook</span></span>

- <span data-ttu-id="7c7f2-616">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカルコンピューターに保存できない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-616">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7c7f2-617">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-617">Office Suite</span></span>

- <span data-ttu-id="7c7f2-618">以前の AppV51 の回帰を修正するために、新しい AppV51 drop をバックポートします。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-618">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="7c7f2-619">レジストリ TabProcGrowth の値がREG_SZ型でアドインがアクティブ化されている場合に、Windows の Office ホストがクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-619">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-june-30"></a><span data-ttu-id="7c7f2-621">バージョン 2006: 6 月 30 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-621">Version 2006: June 30</span></span>
<span data-ttu-id="7c7f2-622">*バージョン 2006 (ビルド 13001.20266)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-622">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7c7f2-624">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-624">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7c7f2-625">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-625">Excel</span></span>

- <span data-ttu-id="7c7f2-626">**長いファイル名**: Windows デスクトップ版の Excel は、名前とパスが最大400文字の OneDrive/SharePoint ファイルをサポートするようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-626">**Longer file names:** Excel for Windows desktop now supports OneDrive/SharePoint files with names and paths of up to 400 characters.</span></span>

- <span data-ttu-id="7c7f2-627">**Realtimedata (RTD) の改善:** Office 365 バージョン 2002 の月間チャネル以降、ExcelのRealTimeData (RTD) 関数は、Excel 2010 のスプレッドシートのデータ計算よりもはるかに高速になります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-627">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="7c7f2-628">基盤となるメモリとデータ構造のボトルネックを取り除き、マルチスレッド再計算  (MTR) の使用可能なすべてのスレッドで計算できるようにスレッドセーフにしました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-628">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="7c7f2-629">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-629">Outlook</span></span>

- <span data-ttu-id="7c7f2-630">**Outlook でのメール作成時の @ メンションの候補表示を無効にするオプションが追加されました。**@ メンション ピッカーが便利どころか迷惑だと感じていますか?</span><span class="sxs-lookup"><span data-stu-id="7c7f2-630">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="7c7f2-631">今後は、必要に応じてオフにすることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-631">Now you can turn it off if you prefer.</span></span><br /><span data-ttu-id="7c7f2-632">[ブログの投稿](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7c7f2-632">See details in [blog post](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)</span></span>

- <span data-ttu-id="7c7f2-633">**IT 管理者向けのインシデント通知:** Microsoft 365 テナントのグローバル管理者および Office Apps 管理者は、Outlook for Windows の新しい右側のパネル通知により、ユーザーに影響する Outlook および O365 Exchange インシデントについて通知されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-633">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="7c7f2-634">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-634">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- <span data-ttu-id="7c7f2-635">**Outlook トースト通知に追加されたその他のボタン:** Outlook for Windows 10で Outlook を実行しているときに Outlook トースト通知にクイック アクション ボタンが表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-635">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7c7f2-636">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-636">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-637">**PowerPoint でのストリーム ビデオのパフォーマンス向上:**、ビデオの読み込み時間を最小限に抑え、快適な表示を実現するために Microsoft Stream ビデオの再生パフォーマンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-637">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="7c7f2-638">お客様の社内ビデオを使用して、Microsoft Stream でより適切なプレゼンテーションを作成します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-638">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="teams"></a><span data-ttu-id="7c7f2-639">Teams</span><span class="sxs-lookup"><span data-stu-id="7c7f2-639">Teams</span></span>

- <span data-ttu-id="7c7f2-640">**PSTN の参加者の電話番号は、外部ユーザーからマスクされます**。Teams 会議でオーディオ会議を有効にしているお客様は、組織の外部から参加しているユーザーに PSTN 参加者の電話番号をマスクします。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-640">**PSTN participant phone numbers are masked from external users:** For customers with Audio Conferencing enabled for their Teams meetings, we will mask the PSTN participant's phone number to users who have joined from outside of your organization.</span></span>

- <span data-ttu-id="7c7f2-641">**チャネル通知の設定を管理する簡単な方法:** チームやチャネルのリストを通して、またはチャネル ヘッダーから、ワンクリックで、またはユーザー設定によって、ユーザーはすべてのアクティビティのオンとオフを切り替えることで、お好きな順序を設定できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-641">**Simplified way to manage your channel notification settings:** Through the teams and channels list or from the channel header, the users can quickly manage their notification settings by turning all activity on or off with a single click or diving deep into custom to set their preferred permutations.</span></span>

- <span data-ttu-id="7c7f2-642">**Walkie Talkie :** プッシュツートークを使用した、インスタント音声コミュニケーション。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-642">**Walkie Talkie:** Instant voice communication using push-to-talk.</span></span>

### <a name="word"></a><span data-ttu-id="7c7f2-643">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-643">Word</span></span>

- <span data-ttu-id="7c7f2-644">**スクリーン リーダーでの操作の確認:** 操作の確認は、重要なアクセシビリティ要件です。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-644">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="7c7f2-645">Windows からの新しい通知 API の導入により、操作の成功をスクリーン リーダーのユーザーに通知できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-645">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="7c7f2-646">切り取り、コピー、貼り付け、太字、斜体、下線、元に戻す、やり直し、自動修正、および自動大文字化が、Win32 Word のナレーター ユーザーにすべて通知されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-646">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="7c7f2-647">この機能を有効にするには、Windows + Ctrl + Enter キーを押してナレーターをオンにします。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-647">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-650">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-650">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7c7f2-651">Access</span><span class="sxs-lookup"><span data-stu-id="7c7f2-651">Access</span></span>

- <span data-ttu-id="7c7f2-652">クエリの実行に予想よりも約2倍の時間がかかっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-652">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>


### <a name="excel"></a><span data-ttu-id="7c7f2-653">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-653">Excel</span></span>

- <span data-ttu-id="7c7f2-654">SharePoint/OneDrive に保存すると、ユーザー設定のリボンタブの CustomUI XML が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-654">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>


### <a name="outlook"></a><span data-ttu-id="7c7f2-655">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-655">Outlook</span></span>

- <span data-ttu-id="7c7f2-656">ドラッグ アンド ドロップによってファイル システムにコピーされた添付ファイルの作成日が、4501年1月1日に設定された問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-656">Addressed an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>

- <span data-ttu-id="7c7f2-657">共有された予定表の改良版のユーザーに予定表のエラーが表示される問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-657">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="7c7f2-658">Outlook で、受信トレイ修復ツールを実行するように促す表示が継続的に発生していた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-658">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="7c7f2-659">クラウド設定が有効になっているときに、Ctrl キーを押しながらクリックすると動作が停止する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-659">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>


- <span data-ttu-id="7c7f2-660">Suggest a Feature で機能を検索しても結果が返されず、ユーザーが新しい機能のアイデアを提出するオプションがないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-660">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


### <a name="project"></a><span data-ttu-id="7c7f2-661">Project</span><span class="sxs-lookup"><span data-stu-id="7c7f2-661">Project</span></span>

- <span data-ttu-id="7c7f2-662">URL が .com で終了している場合に、Project Web App からプロジェクト デスクトップ クライアントでプロジェクトを開くことができない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-662">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="7c7f2-663">プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-663">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>


- <span data-ttu-id="7c7f2-664">100% 完了とマークされているタスクが、100% 未満のタスクに間違って変更されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-664">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="7c7f2-665">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-665">Word</span></span>

- <span data-ttu-id="7c7f2-666">URL にクエリ コンポーネントが含まれている場合にカスタム ドキュメント配信 (aspx) から Word ドキュメントを開く問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-666">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2005-june-24"></a><span data-ttu-id="7c7f2-668">バージョン 2005: 6 月 24 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-668">Version 2005: June 24</span></span>
<span data-ttu-id="7c7f2-669">*バージョン 2005 (ビルド 12827.20470)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-669">*Version 2005 (Build 12827.20470)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-671">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-671">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7c7f2-672">Access</span><span class="sxs-lookup"><span data-stu-id="7c7f2-672">Access</span></span>

- <span data-ttu-id="7c7f2-673">このバグは修正されました。アプリケーションのクラッシュを発生させずに、コードに日付/時刻の拡張データ型を呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-673">This bug has now been fixed; you should be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span> <span data-ttu-id="7c7f2-674">問題が発生した場合は、チームにお知らせください。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-674">Please let the team know if you encounter further issues.</span></span>


- <span data-ttu-id="7c7f2-675">この問題は修正されました。これで、最新の Access バージョンに戻すことができるようになりました。さらに、DAO/VBA を使用して10進数データ型を管理および編集することができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-675">This issue has now been fixed; you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span> <span data-ttu-id="7c7f2-676">データ型を使用して問題が発生した場合は、Access チームにお知らせください。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-676">Please let the Access team know if you encounter any further issues with using our data type.</span></span>


### <a name="excel"></a><span data-ttu-id="7c7f2-677">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-677">Excel</span></span>

- <span data-ttu-id="7c7f2-678">SharePoint/OneDrive に保存すると、ユーザー設定のリボンタブの CustomUI XML が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-678">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>





### <a name="outlook"></a><span data-ttu-id="7c7f2-679">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-679">Outlook</span></span>

- <span data-ttu-id="7c7f2-680">M365 Business Plus プランのサービスを利用していたユーザーがデータ損失防止の保護ポリシー ヒントを有効にできない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-680">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>


- <span data-ttu-id="7c7f2-681">ドラッグ アンド ドロップによってファイル システムにコピーされた添付ファイルの作成日が、4501年1月1日に設定された問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-681">Addressed an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="7c7f2-682">ユーザーがOutlook ルールを更新すると、「&quot;このコンピューターのルールは、Microsoft Exchange のルールと異なります&quot;」 と表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-682">Addressed an issue that caused users to see the &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; message when updating their rules in Outlook.</span></span>


- <span data-ttu-id="7c7f2-683">共有された予定表の改良版のユーザーに予定表のエラーが表示される問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-683">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="7c7f2-684">一部のシナリオで、断続的なハングやクラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-684">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>


- <span data-ttu-id="7c7f2-685">Outlook で、受信トレイ修復ツールを実行するように促す表示が継続的に発生していた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-685">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="7c7f2-686">Suggest a Feature で機能を検索しても結果が返されず、ユーザーが新しい機能のアイデアを提出するオプションがないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-686">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="7c7f2-687">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-687">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-688">提案ウィンドウでクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-688">We have fixed a crash issue with suggestion pane.</span></span>


### <a name="project"></a><span data-ttu-id="7c7f2-689">Project</span><span class="sxs-lookup"><span data-stu-id="7c7f2-689">Project</span></span>

- <span data-ttu-id="7c7f2-690">100% 完了とマークされているタスクが、100% 未満のタスクに間違って変更されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-690">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="7c7f2-691">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-691">Word</span></span>

- <span data-ttu-id="7c7f2-692">一部のアプリケーションからコンテンツをドラッグしたときにクラッシュする問題の原因となっていた可能性がある問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-692">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7c7f2-693">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-693">Office Suite</span></span>

- <span data-ttu-id="7c7f2-694">この変更により、Gif や3D モデルなどのアニメーション コンテンツを読み込んだり、再生したりするときに、ハングする可能性があります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-694">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>




[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-june-09"></a><span data-ttu-id="7c7f2-696">バージョン 2005: 6月 9 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-696">Version 2005: June 09</span></span>
<span data-ttu-id="7c7f2-697">*バージョン 2005 (ビルド 12827.20336)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-697">*Version 2005 (Build 12827.20336)*</span></span>

<span data-ttu-id="7c7f2-698">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-698">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="feature-updates"></a><span data-ttu-id="7c7f2-699">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-699">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7c7f2-700">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-700">Excel</span></span>

- <span data-ttu-id="7c7f2-701">**[描画] の [ツール] ボックスのなげなわと消しゴム:** 描画ツールを使用しているときに、[描画] の [ツール] ボックスでなげなわと消しゴムを使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-701">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7c7f2-702">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-702">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-703">**[描画] の [ツール] ボックスのなげなわと消しゴム:** 描画ツールを使用しているときに、[描画] の [ツール] ボックスでなげなわと消しゴムを使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-703">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>

### <a name="word"></a><span data-ttu-id="7c7f2-704">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-704">Word</span></span>

- <span data-ttu-id="7c7f2-705">**[描画] の [ツール] ボックスのなげなわと消しゴム:** 描画ツールを使用しているときに、[描画] の [ツール] ボックスでなげなわと消しゴムを使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-705">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>




[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-708">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-708">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7c7f2-709">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-709">Excel</span></span>

- <span data-ttu-id="7c7f2-710">ピボットテーブルをチャート シートに挿入しようとしたときに Excel がクラッシュする場合がある問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-710">Addresses an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7c7f2-711">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-711">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-712">これにより、ユーザーがファイルに対してモダンおよびレガシのコメントを持っていて、コメントの更新をトリガーすると、クラッシュが修正されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-712">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

### <a name="project"></a><span data-ttu-id="7c7f2-713">Project</span><span class="sxs-lookup"><span data-stu-id="7c7f2-713">Project</span></span>

- <span data-ttu-id="7c7f2-714">プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-714">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7c7f2-715">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-715">Office Suite</span></span>

- <span data-ttu-id="7c7f2-716">Bing アドオンのインストール検証を既定で true に設定し、MSI のリターン成功をインストール成功とみなすことで、ValidateInstall のエラー率の問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-716">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2005-june-02"></a><span data-ttu-id="7c7f2-718">バージョン 2005: 6 月 2 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-718">Version 2005: June 02</span></span>
<span data-ttu-id="7c7f2-719">*バージョン 2005 (ビルド 12827.20268)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-719">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7c7f2-721">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-721">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7c7f2-722">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-722">Excel</span></span>

- <span data-ttu-id="7c7f2-723">**新しいデータ型を自動的に使用する :** 可能性のある株式や地理的な場所に似たデータ値を入力すると、Excel は、関連付けられた該当する株価や地理といったデータ型に変換することを提案します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-723">**Automatically use new data types:** When you type a data value that resembles a stock or a geographic location, Excel offers to convert it to the right connected data type - Stocks or Geography.</span></span> [<span data-ttu-id="7c7f2-724">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-724">Learn more</span></span>](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- <span data-ttu-id="7c7f2-725">**アニメーション Gif を使用してストーリーを伝える :** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-725">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>

### <a name="outlook"></a><span data-ttu-id="7c7f2-726">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-726">Outlook</span></span>

- <span data-ttu-id="7c7f2-727">**グループ内のデータを保護:** グループを作成するときに選択する秘密度ラベルがグループ メール、ドキュメント、チーム サイトに適用されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-727">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

- <span data-ttu-id="7c7f2-728">**より迅速かつ適切な結果:** 検索機能が更新され、よりスマート、迅速、かつ信頼性が高くなりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-728">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="7c7f2-729">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-729">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="7c7f2-730">**アニメーション Gif を使用してストーリーを伝える :** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-730">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>

- <span data-ttu-id="7c7f2-731">**予定表が一新されます:** 予定表を簡単に読みやすくなるビジュアル アップデートをご覧ください。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-731">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="7c7f2-732">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-732">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="7c7f2-733">[ブログの投稿](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7c7f2-733">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7c7f2-734">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-734">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-735">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。[詳細については、こちらを参照してください。](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-735">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier [Learn more](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span></span>

- <span data-ttu-id="7c7f2-736">**プレゼンテーション中に変更を同期する:** プレゼンテーションがスライド ショー モードであれば、いつでも変更を同期できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-736">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="7c7f2-737">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-737">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="7c7f2-738">[ブログの投稿](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="7c7f2-738">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="7c7f2-739">**クリッカーは不要: イヤホンでカバー:** Surface Earbuds を使用して、PowerPoint プレゼンテーションを制御します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-739">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="7c7f2-740">機能のしくみ: ペアリングすると、PowerPoint の機能を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-740">How it works:  Once paired, you'll need to enable the feature in PowerPoint.</span></span> <span data-ttu-id="7c7f2-741">F5 キーを押すか、[スライド ショー] > [最初から] を選択してプレゼンテーションを開始します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-741">Start a presentation by pressing F5 or selecting Slide Show > From Beginning.</span></span>  <span data-ttu-id="7c7f2-742">スライドショーでは、スライドを右クリックし、Surface Earbuds の設定で、[ジェスチャを使用してプレゼンテーションを制御] を選択します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-742">In Slide Show, right click on the slide and under Surface Earbuds Settings choose Use Gestures to Control Presentation.</span></span>  <span data-ttu-id="7c7f2-743">この設定は、今後作成するすべてのプレゼンテーションに記録されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-743">This setting will be remembered for all future presentations.</span></span> <span data-ttu-id="7c7f2-744">スライド ショー モードで左イヤホンを使用して前後にスワイプし、プレゼンテーションをナビゲートできます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-744">You can now can swipe forward and backward on the left earbud to navigate your presentations in Slide Show mode.</span></span>  <span data-ttu-id="7c7f2-745">ダブルタップして、埋め込まれたビデオを再生または一時停止します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-745">Double tap to play or pause embedded videos.</span></span>  <span data-ttu-id="7c7f2-746">重要: ジェスチャーを使用してプレゼンテーションを制御するには、Windows 10 の Surface Audio アプリで Surface Earbuds をペアリングする必要があります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-746">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="7c7f2-747">Windows 10 で Surface Audio アプリを使い始める方法については、こちらをご覧ください。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-747">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="7c7f2-748">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-748">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="teams"></a><span data-ttu-id="7c7f2-749">Teams</span><span class="sxs-lookup"><span data-stu-id="7c7f2-749">Teams</span></span>

- <span data-ttu-id="7c7f2-750">**Teams 会議でのビデオ レイアウトの変更:** 近日中に、Teams 会議中に同時に表示できる参加者の数は、4名から9名に増加します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-750">**Changes to video layout in Teams meetings:** Soon, the number of participants that can be viewed simultaneously during a Teams meeting will increase from 4 to 9.</span></span>

- <span data-ttu-id="7c7f2-751">**[ライブイベント] にシステム オーディオを含める**: ライブ イベントの発表者やプロデューサーは、ライブ イベント中にデスクトップまたはウィンドウ画面を共有するときに、システム オーディオを含めることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-751">**Include system audio in live events:** Presenters and producers in live events can now include system audio when sharing a desktop or window screen during the live event.</span></span> <span data-ttu-id="7c7f2-752">これにより、共有するコンテンツのオーディオ部分をユーザーが聞くことができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-752">This will allow your users to hear any audio part of the content you are sharing.</span></span>

- <span data-ttu-id="7c7f2-753">[**ダイヤルイン ユーザーによるロビーのバイパスを許可する :**] この設定では、スマートフォンでダイヤル インするユーザーが会議に直接参加するのか、[ユーザーの参加を自動的に許可する] の設定に関わらずロビーで待機するのかを制御します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-753">**Enable organizers to change lobby settings for dial-in participants:** This setting controls whether people who dial in by phone join the meeting directly or wait in the lobby regardless of the Automatically admit people setting.</span></span>

- <span data-ttu-id="7c7f2-754">**会議で挙手しましょう:** ユーザーは会議で仮想の手を上げることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-754">**Raise Your Hand in Meetings:** Users can now raise a virtual hand in a meeting!</span></span> <span data-ttu-id="7c7f2-755">他のユーザーは、会議のステージで参加者名簿の自分の名前の横で挙手しているのが表示されるのを見ることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-755">Other participants will see your raised hand next to your name in the meeting stage and next to your name in the roster.</span></span>

- <span data-ttu-id="7c7f2-756">**ビデオ会議の背景をカスタマイズ:** ビデオ会議を実施しているときに、使用する静的な背景画像を選択できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-756">**Customize meeting video backgrounds:** When you are meeting with video, you now have the choice of different static background images to use.</span></span> <span data-ttu-id="7c7f2-757">この操作により、実際に座っている場所の背景ではない、選択した画像が表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-757">This will let you show this image and not the actual background of where you are sitting.</span></span>

- <span data-ttu-id="7c7f2-758">**チャットにユーザーを追加する:**、最大350人のユーザーを1つのチャットスレッドに追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-758">**Add more people to chat:** We made it possible to now add up to 350 people to a single chat thread.</span></span>

- <span data-ttu-id="7c7f2-759">**アクティビティ フィードの設定ギア**: ユーザーは、[設定] ギアを使用して、フィードの左側のレールから、アクティビティ フィードと通知の設定に直接アクセスできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-759">**Settings Gear on your Activity Feed:** Users can now directly access activity feed and notification setting from the feed left rail by the means of a settings gear.</span></span>

- <span data-ttu-id="7c7f2-760">**進行中の Teams 会議内から会議のオプションに簡単にアクセス可能:** 会議の開催者は、参加者ウィンドウに直接アクセスできるリンクを提供することで、会議の開催者が発表者やロビーの設定をすばやく簡単に変更することができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-760">**Easily access meeting options from within a Teams meeting in progress:** We are making it easier for meeting organizers to quickly and easily change their presenter and lobby settings once a Teams meeting starts by providing an easy to access link directly in the participants pane.</span></span> <span data-ttu-id="7c7f2-761">この新機能は、予定されている、または 「今から会議」 の会議に使用できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-761">This new functionality will be present for both scheduled and “Meet Now” meetings.</span></span>

- <span data-ttu-id="7c7f2-762">**チームとチャネルの分析 :** チームの分析に加えて、チャネル レベルのメトリックスやインサイトを表示することもできます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-762">**Team and channel analytics:** In addition to team analytics, now you can also view channel level metrics and insights.</span></span> <span data-ttu-id="7c7f2-763">また、より長期間にわたってデータを分析できるように、期間が90日に延長されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-763">We've also enhanced the time period to 90 days so you can analyze data for longer periods.</span></span> <span data-ttu-id="7c7f2-764">それ以外に、このリリースには、チームやチャネルの投稿、返信、会議の数についての新しいメトリックスやグラフも含まれます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-764">Apart from that, this release also includes new metrics and charts around count of posts, replies and meetings for a team or channel.</span></span>

- <span data-ttu-id="7c7f2-765">**入退場のアナウンス:** 会議の開催者が会議の入退場アナウンスのオン / オフを切り替えできる機能を追加しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-765">**Entry/exit announcements:** We added this feature that lets meeting organizers have the ability to turn on or off entry and exit announcements for a meeting.</span></span>

### <a name="word"></a><span data-ttu-id="7c7f2-766">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-766">Word</span></span>

- <span data-ttu-id="7c7f2-767">**Wordを終了せずに頭字語をデコードする:** Word で頭字語が見つかった場合、他のユーザーによるその使用方法に基づいく定義が示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-767">**Decode acronyms without leaving Word:** When you encounter an acronym, Word will try to define it based on how others use it.</span></span>

- <span data-ttu-id="7c7f2-768">**アニメーション Gif を使用してストーリーを伝える :** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-768">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-771">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-771">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="7c7f2-772">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-772">Excel</span></span>

- <span data-ttu-id="7c7f2-773">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-773">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="7c7f2-774">同じブック内の場所へのハイパーリンクをクリックすると、ブックが非表示になることがあります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-774">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

### <a name="outlook"></a><span data-ttu-id="7c7f2-775">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-775">Outlook</span></span>

- <span data-ttu-id="7c7f2-776">CLP の監査イベントで、返信/転送ラベルの問題に対応しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-776">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="7c7f2-777">Windows 10 サーバー バージョンのユーザーに「アンチウイルスの状態が無効です」という警告が表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-777">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid".</span></span> <span data-ttu-id="7c7f2-778">このバージョンの Windows はウイルス検出をサポートしていますが、ウイルス対策が正常にインストールされてもウイルス対策ソフトウェアが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-778">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="7c7f2-779">ユーザーが管理者通知からフィードバックを送信する場合にクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-779">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

### <a name="skype"></a><span data-ttu-id="7c7f2-780">Skype</span><span class="sxs-lookup"><span data-stu-id="7c7f2-780">Skype</span></span>

- <span data-ttu-id="7c7f2-781">ユーザーが Teams Only に移動するポリシーを与えられた場合は、Skype for Business Outlook アドインを使用して会議をスケジュールできます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-781">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="7c7f2-782">この更新プログラムを適用すると、クライアントは Teams Only を対象としていることを示すポリシーをユーザーが読んでから会議参加のみのモードに入った後に、Skype for Business 会議のスケジュールを設定できなくなります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-782">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="7c7f2-783">また、skype for business Outlook アドインは、Skype for business クライアントが 「会議の参加のみ」 モードであることを確認した場合に起動した場合、自動的にアクティブ化されることはありません。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-783">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7c7f2-784">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-784">Office Suite</span></span>

- <span data-ttu-id="7c7f2-785">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-785">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="7c7f2-786">この更新プログラムでは、Microsoft Office で PATH 環境変数で指定した場所を検索することによって参照される可能性がある Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA ランタイムエラーが発生するという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-786">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="7c7f2-787">HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth のレジストリ キーが0に設定されている場合、アドインがアクティブになり、Windows で Office ホストがクラッシュしました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-787">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="7c7f2-788">この変更により、この問題は修正されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-788">This change would fix this issue.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2004-may-21"></a><span data-ttu-id="7c7f2-790">バージョン 2004: 5 月 21 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-790">Version 2004: May 21</span></span>
<span data-ttu-id="7c7f2-791">*バージョン 2004 (ビルド 12730.20352)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-791">*Version 2004 (Build 12730.20352)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-793">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-793">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7c7f2-794">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-794">Excel</span></span>

- <span data-ttu-id="7c7f2-795">ファイル パスが長すぎる場合にファイルをもう一度開くと、外部リンクが機能しなくなった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-795">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>


### <a name="outlook"></a><span data-ttu-id="7c7f2-796">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-796">Outlook</span></span>

- <span data-ttu-id="7c7f2-797">ユーザーが管理者通知からフィードバックを送信する場合にクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-797">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7c7f2-798">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-798">Office Suite</span></span>

- <span data-ttu-id="7c7f2-799">クイック実行に関する問題が修正され、最新のビルドへの更新プログラムに失敗することがあった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-799">Fixed a Click-to-Run issue which was resulting in occasional update failures to the latest builds.</span></span>

- <span data-ttu-id="7c7f2-800">Microsoft Office で、PATH 環境変数で指定した場所を検索すれば見つかるはずの参照を含む Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA のランタイム エラーになる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-800">Fixed an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2004-may-12"></a><span data-ttu-id="7c7f2-802">バージョン 2004: 5 月 12 月</span><span class="sxs-lookup"><span data-stu-id="7c7f2-802">Version 2004: May 12</span></span>
<span data-ttu-id="7c7f2-803">*バージョン 2004 (ビルド 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-803">*Version 2004 (Build 12730.20270)*</span></span>

<span data-ttu-id="7c7f2-804">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-804">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-806">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-806">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7c7f2-807">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-807">Outlook</span></span>

- <span data-ttu-id="7c7f2-808">ユーザーがトースト通知を表示するときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-808">Addresses an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-may-04"></a><span data-ttu-id="7c7f2-810">バージョン 2004: 5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-810">Version 2004: May 04</span></span>
<span data-ttu-id="7c7f2-811">*バージョン 2004 (ビルド 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-811">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-813">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-813">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="7c7f2-814">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-814">Office Suite</span></span>

- <span data-ttu-id="7c7f2-815">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-815">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-april-29"></a><span data-ttu-id="7c7f2-817">バージョン 2004: 4 月 29 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-817">Version 2004: April 29</span></span>
<span data-ttu-id="7c7f2-818">*バージョン 2004 (ビルド 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-818">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7c7f2-820">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-820">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="7c7f2-821">Access</span><span class="sxs-lookup"><span data-stu-id="7c7f2-821">Access</span></span>

- <span data-ttu-id="7c7f2-822">**クエリ デザイナー、SQL ビュー、およびリレーションシップ ウィンドウでの作業効率の向上:** テーブルを右クリックして、テーブルを開き、デザインし、サイズを変更し、非表示にします。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-822">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="7c7f2-823">SQL ビューでテキストを検索および置換します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-823">Search and replace text in SQL View.</span></span> <span data-ttu-id="7c7f2-824">リレーションシップ ウィンドウ内の複数のテーブルを選択します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-824">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="7c7f2-825">**数回クリックするだけで表を追加する:** [テーブルの追加] 作業ウィンドウを使用すると、作業中も開いたまま、リレーションシップやクエリにテーブルを追加できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-825">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="7c7f2-826">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-826">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)


### <a name="excel"></a><span data-ttu-id="7c7f2-827">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-827">Excel</span></span>

- <span data-ttu-id="7c7f2-828">**Facebook コネクタのサポート終了:** 2020 年 4 月以降、Excel では Facebook コネクタを使用する外部データ接続がサポートされなくなります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-828">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

- <span data-ttu-id="7c7f2-829">**質問がある場合のExcel への質問:** Excel のアイデアを使用すると、データについて質問をすることができます。数式の記述に時間を費やす必要はありません(英語のみ使用可能)。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-829">**Have a question? Ask Excel:** Now Excel Ideas allows you to ask questions about your data - no need to spend time writing formulas (available in English only).</span></span> [<span data-ttu-id="7c7f2-830">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-830">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- <span data-ttu-id="7c7f2-831">**ブックの見映えを良くする新しい画像:** 何千ものロイヤリティフリーの画像、アイコン、ステッカーが用意されており、これらをブックで使用できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-831">**New images to bring your workbooks to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your workbooks.</span></span> <span data-ttu-id="7c7f2-832">開始するには、[挿入] > [画像] > [ストック画像] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-832">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="7c7f2-833">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-833">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="outlook"></a><span data-ttu-id="7c7f2-834">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-834">Outlook</span></span>

- <span data-ttu-id="7c7f2-835">**受信トレイを離れずに会議に参加する:** オンライン会議に参加するために、予定表に切り替える必要はありません。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-835">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="7c7f2-836">[To Do] ウィンドウに固定された予定表を使用して、ワンクリックで任意の会議に参加します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-836">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span> [<span data-ttu-id="7c7f2-837">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-837">Learn more</span></span>](https://support.office.com/article/d8baa9d5-0645-41b8-9f36-b498a6c36064 )

- <span data-ttu-id="7c7f2-838">**メッセージの見映えを良くする新しい画像:** 何千ものロイヤリティフリーの画像、アイコン、ステッカーが用意されており、これらをメール メッセージで使用できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-838">**New images to bring your messages to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your email messages.</span></span> <span data-ttu-id="7c7f2-839">開始するには、[挿入] > [画像] > [ストック画像] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-839">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="7c7f2-840">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-840">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

- <span data-ttu-id="7c7f2-841">**定期的な会議の場所の提案サポート:** 定期的な会議のスケジュールで会議室を検索します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-841">**Location suggestion support for recurring meeting:** Search for conference rooms with scheduling recurring meetings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7c7f2-842">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-842">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-843">**スライド ショーの実行中にスライドを更新する:** プレゼンテーション中に他の作成者が変更したスライドを更新します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-843">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

- <span data-ttu-id="7c7f2-844">**スライドの見映えを良くする新しい画像:** 何千ものロイヤリティフリーの画像、アイコン、ステッカーが用意されており、これらをプレゼンテーションで使用できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-844">**New images to bring your slides to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your presentations.</span></span> <span data-ttu-id="7c7f2-845">開始するには、[挿入] > [画像] > [ストック画像] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-845">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="7c7f2-846">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-846">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="teams"></a><span data-ttu-id="7c7f2-847">Teams</span><span class="sxs-lookup"><span data-stu-id="7c7f2-847">Teams</span></span>

- <span data-ttu-id="7c7f2-848">**Teams の予定表の改善:** 予定表の項目を右クリックすると、出欠確認のオプションを表示したり、会議の参加者とのチャットを開始したり、会議開始時にすぐにその会議に参加したりすることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-848">**Improvements to the Teams calendar:** Right-click an item in your calendar to pull up RSVP options, start a chat with meeting participants, or quickly join a meeting when it starts.</span></span> <span data-ttu-id="7c7f2-849">また、イベントのスケジュール設定のフォームも改善されています。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-849">We've also made improvements to the event scheduling form.</span></span>

- <span data-ttu-id="7c7f2-850">**ユーザーへのタグ付け:** タグを作成してユーザーに割り当てて、グループ、役割、部署などに @mention を付けることができます。チームの所有者はぜひお試しください。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-850">**Tag, you're it!:** Create tags and assign people to them so you can @mention a group, role, department, etc. Team owners, try it out for yourselves.</span></span> <span data-ttu-id="7c7f2-851">チームに移動し、[その他のオプション]、[タグの管理] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-851">Go to a team, select More options, Manage tags.</span></span>

### <a name="word"></a><span data-ttu-id="7c7f2-852">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-852">Word</span></span>

- <span data-ttu-id="7c7f2-853">**ツールの使いやすさを維持:** [描画] ツールボックスには、テキストにインク ジェスチャを追加できるインテリジェント ペンが用意されています。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-853">**Keep your tools handy:** In your drawing toolbox, find the intelligent pen that allows you to add ink gestures to text.</span></span> [<span data-ttu-id="7c7f2-854">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-854">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- <span data-ttu-id="7c7f2-855">**ドキュメントの見映えを良くする新しい画像:** 何千ものロイヤリティフリーの画像、アイコン、ステッカーが用意されており、これらをドキュメントで使用できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-855">**New images to bring your documents to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your documents.</span></span> <span data-ttu-id="7c7f2-856">開始するには、[挿入] > [画像] > [ストック画像] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-856">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="7c7f2-857">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-857">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-860">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-860">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7c7f2-861">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-861">Excel</span></span>

- <span data-ttu-id="7c7f2-862">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-862">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="7c7f2-863">ピボットテーブルを含むシートをコピーした後、Excel がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-863">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="7c7f2-864">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-864">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="7c7f2-865">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-865">Outlook</span></span>

- <span data-ttu-id="7c7f2-866">フォルダー ウィンドウの幅が予期せず変更される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-866">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>


- <span data-ttu-id="7c7f2-867">Windows の一部のビルドで Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-867">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>


- <span data-ttu-id="7c7f2-868">Windows の更新後に、ローカルに保存された .msg または .oft ファイルを開くと Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-868">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>


- <span data-ttu-id="7c7f2-869">Windows の一部のビルドで Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-869">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>


- <span data-ttu-id="7c7f2-870">Outlook の終了中に応答が停止するする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-870">Addressed an issue that caused users to experience a hang while exiting Outlook.</span></span>


### <a name="project"></a><span data-ttu-id="7c7f2-871">Project</span><span class="sxs-lookup"><span data-stu-id="7c7f2-871">Project</span></span>

- <span data-ttu-id="7c7f2-872">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-872">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>


- <span data-ttu-id="7c7f2-873">Project Web App に接続されている Project を使用していて小数点の記号がカンマの場合に、依存関係のタイム ラグを生じさせようとすると TaskDependencies Add メソッドが失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-873">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7c7f2-874">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-874">Office Suite</span></span>

- <span data-ttu-id="7c7f2-875">アクセスの制限と、パスワードによるファイルの保護が同時に行えないというエラーを解決しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-875">Resolved an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-april-15"></a><span data-ttu-id="7c7f2-877">バージョン 2003: 4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-877">Version 2003: April 15</span></span>
<span data-ttu-id="7c7f2-878">*バージョン 2003 (ビルド 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-878">*Version 2003 (Build 12624.20466)*</span></span>
* <span data-ttu-id="7c7f2-879">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-879">Various bugs and performance fixes.</span></span>

## <a name="version-2003-april-14"></a><span data-ttu-id="7c7f2-880">バージョン 2003: 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-880">Version 2003: April 14</span></span>
<span data-ttu-id="7c7f2-881">*バージョン 2003 (ビルド 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-881">*Version 2003 (Build 12624.20442)*</span></span>

<span data-ttu-id="7c7f2-882">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-882">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-884">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-884">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7c7f2-885">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-885">Excel</span></span>

- <span data-ttu-id="7c7f2-886">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-886">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="7c7f2-887">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-887">Outlook</span></span>

- <span data-ttu-id="7c7f2-888">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-888">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="7c7f2-889">Project</span><span class="sxs-lookup"><span data-stu-id="7c7f2-889">Project</span></span>

- <span data-ttu-id="7c7f2-890">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-890">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

### <a name="word"></a><span data-ttu-id="7c7f2-891">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-891">Word</span></span>

- <span data-ttu-id="7c7f2-892">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-892">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-31"></a><span data-ttu-id="7c7f2-894">バージョン 2003: 3 月 31 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-894">Version 2003: March 31</span></span>
<span data-ttu-id="7c7f2-895">*バージョン 2003 (ビルド 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-895">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-897">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-897">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="7c7f2-898">OneNote</span><span class="sxs-lookup"><span data-stu-id="7c7f2-898">OneNote</span></span>

- <span data-ttu-id="7c7f2-899">全世界でサービス使用量が高まった際に、同期とサービスの可用性を改善できる、Microsoft OneNote の一時的な調整に関して、情報バーを介してユーザーに通知します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-899">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

### <a name="project"></a><span data-ttu-id="7c7f2-900">Project</span><span class="sxs-lookup"><span data-stu-id="7c7f2-900">Project</span></span>

- <span data-ttu-id="7c7f2-901">実績作業時間の保護設定を有効にしているときに、ユーザーがタイムフェーズの基準作業時間を入力できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-901">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-25"></a><span data-ttu-id="7c7f2-903">バージョン 2003: 3 月 25 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-903">Version 2003: March 25</span></span>
<span data-ttu-id="7c7f2-904">*バージョン 2003 (ビルド 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-904">*Version 2003 (Build 12624.20320)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7c7f2-906">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-906">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7c7f2-907">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-907">Excel</span></span>

- <span data-ttu-id="7c7f2-908">**お気に入りの Excel 関数が速くなりました：** SUMIFS、AVERAGEIFS、COUNTIFS、MAXIFS、および MINIFS 関数がこれまでよりもはるかに高速になりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-908">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="7c7f2-909">もっと素早く一番下に移動します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-909">Get to the bottom line more quickly.</span></span> <span data-ttu-id="7c7f2-910">今すぐお試しください。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-910">Try one now.</span></span>

### <a name="outlook"></a><span data-ttu-id="7c7f2-911">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-911">Outlook</span></span>

- <span data-ttu-id="7c7f2-912">**所有しているグループにメールをドラッグ:** メッセージや会話を受信トレイからドラッグして移動し、コピーします。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-912">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="7c7f2-913">ドラッグしたメッセージは、すべてのグループ メンバーと共有されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-913">Messages you drag will be shared with all group members.</span></span>

- <span data-ttu-id="7c7f2-914">**キャプティブ WiFi ネットワークの新しいエクスペリエンス**: サインインに Web ページを必要とする WiFi ネットワークに参加したことはありませんか ?</span><span class="sxs-lookup"><span data-stu-id="7c7f2-914">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="7c7f2-915">Outlook はこれを検出し、接続を支援します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-915">Outlook now detects this and helps you get connected.</span></span>

###<a name="powerpoint"></a><span data-ttu-id="7c7f2-916">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-916">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-917">**コメント:** PowerPoint の新しいコメント機能により、ドキュメントにコメントをすばやく簡単に見つけて追加できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-917">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="7c7f2-918">コメントの固定、解決、タスク、改善された通知などの新機能を使用して、コラボレーションワークフローを最新のものにします。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-918">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span>

### <a name="word"></a><span data-ttu-id="7c7f2-919">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-919">Word</span></span>

- <span data-ttu-id="7c7f2-920">**他のユーザーがすばやく変更を確認する:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-920">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7c7f2-921">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-921">Office Suite</span></span>

- <span data-ttu-id="7c7f2-922">**秘密度ラベル:** カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-922">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-925">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-925">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7c7f2-926">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-926">Excel</span></span>

- <span data-ttu-id="7c7f2-927">Word または PowerPoint に埋め込まれたブックをもう一度開くと、場合によっては Excel がクラッシュする可能性があります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-927">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="7c7f2-928">ソース ブックが閉じていると、外部リンクが塗りつぶし時に更新されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-928">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="7c7f2-929">テンプレートからグラフを作成するときに発生するパフォーマンスの問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-929">Addressed a performance issue when creating charts from templates.</span></span>

### <a name="onenote"></a><span data-ttu-id="7c7f2-930">OneNote</span><span class="sxs-lookup"><span data-stu-id="7c7f2-930">OneNote</span></span>

- <span data-ttu-id="7c7f2-931">新しい埋め込み添付ファイルの最大許容サイズを一時的に 50 MB に削減することにより、同期とサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-931">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB.</span></span> <span data-ttu-id="7c7f2-932">この制限を超えるファイルの場合、ユーザーは OneDrive にファイルをアップロードして、OneNote にリンクを挿入することができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-932">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="7c7f2-933">OneNote 2016 で同期頻度を一時的に調整することで、同期およびサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-933">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

### <a name="outlook"></a><span data-ttu-id="7c7f2-934">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-934">Outlook</span></span>

- <span data-ttu-id="7c7f2-935">終了後にタスク マネージャーに Outlook プロセスが残っているという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-935">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7c7f2-936">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-936">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-937">コピーと貼り付けのシナリオを改善しました。PowerPoint スライドでの図形のコピーと、ループ内の他のスライドへの貼り付けが例外で失敗する場合があります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-937">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="7c7f2-938">Project</span><span class="sxs-lookup"><span data-stu-id="7c7f2-938">Project</span></span>

- <span data-ttu-id="7c7f2-939">[無効化] ボタンを介してタスクが非アクティブ化/アクティブ化された場合に、ProjectBeforeTaskChange イベントが検出しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-939">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="7c7f2-940">以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-940">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="7c7f2-941">タスクを完了とマークした後に、タスクの達成率が 100% 完了より小さい値に誤って変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-941">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="7c7f2-942">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-942">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-march-10"></a><span data-ttu-id="7c7f2-944">バージョン 2002: 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-944">Version 2002: March 10</span></span>
<span data-ttu-id="7c7f2-945">*バージョン 2002 (ビルド 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-945">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="7c7f2-946">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-946">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7c7f2-948">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-948">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="7c7f2-949">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-949">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-950">**スライドへのリンク:** 同僚にスライド デッキへの投稿を依頼し、ヘルプが必要なスライド上で直接開始します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-950">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-953">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-953">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="7c7f2-954">Project</span><span class="sxs-lookup"><span data-stu-id="7c7f2-954">Project</span></span>

- <span data-ttu-id="7c7f2-955">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-955">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2002-march-01"></a><span data-ttu-id="7c7f2-957">バージョン 2002: 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-957">Version 2002: March 01</span></span>
<span data-ttu-id="7c7f2-958">*バージョン 2002 (ビルド 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-958">*Version 2002 (Build 12527.20242)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-960">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-960">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7c7f2-961">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-961">Outlook</span></span>

- <span data-ttu-id="7c7f2-962">サードパーティ製アプリケーションがメールを送信できない原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-962">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2002-february-25"></a><span data-ttu-id="7c7f2-964">バージョン 2002: 2 月 25 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-964">Version 2002: February 25</span></span>
<span data-ttu-id="7c7f2-965">*バージョン 2002 (ビルド 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-965">*Version 2002 (Build 12527.20194)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7c7f2-967">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-967">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7c7f2-968">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-968">Excel</span></span>

- <span data-ttu-id="7c7f2-969">**ブックの統計情報:** セル、数式、グラフ、テーブル...これらをお客様に代わってカウントします。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-969">**Workbook Statistics:** Cells, formulas, charts, tables... We count them so you don't have to.</span></span>

- <span data-ttu-id="7c7f2-970">**クエリ エディターでのデータ プロファイリング**: 列のデータを一目で分析し、エラーと空の値を識別し、配布ヒストグラムなどを確認します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-970">**Data Profiling in Query Editor:** Get at-a-glance analysis of the data in your columns, identify error and empty values, see distribution histograms and more.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-973">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-973">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7c7f2-974">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-974">Excel</span></span>

- <span data-ttu-id="7c7f2-975">CUBEVALUE 関数が間違った結果を返すことがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-975">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="7c7f2-976">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-976">Outlook</span></span>

- <span data-ttu-id="7c7f2-977">会議の [場所] フィールドにあるコンマがセミコロンになる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-977">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="7c7f2-978">複数のウィンドウで同じアイテムを表示するとクラッシュする場合がある問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-978">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="7c7f2-979">フラグ付きアイテムの強調表示を無効にするオプションが一部のシナリオで無視される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-979">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="7c7f2-980">同期のスライダーが小さい設定に設定されている場合でも、Outlook で予期せずすべてのメールが同期される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-980">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>


- <span data-ttu-id="7c7f2-981">黒のテーマを持つユーザーが [差出人] ドロップダウンを表示すると、白色の背景に白いテキストが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-981">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>


- <span data-ttu-id="7c7f2-982">この変更により、メッセージ ヘッダーに複数行の件名を表示できる機能が復元されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-982">This change restores the ability to view multi-line subjects in the message header.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2001-february-19"></a><span data-ttu-id="7c7f2-984">バージョン 2001: 2 月 19 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-984">Version 2001: February 19</span></span>
<span data-ttu-id="7c7f2-985">*バージョン 2001 (ビルド 12430.20288)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-985">*Version 2001 (Build 12430.20288)*</span></span>
* <span data-ttu-id="7c7f2-986">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-986">Various bugs and performance fixes.</span></span>

## <a name="version-2001-february-11"></a><span data-ttu-id="7c7f2-987">バージョン 2001: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-987">Version 2001: February 11</span></span>
<span data-ttu-id="7c7f2-988">*バージョン 2001 (ビルド 12430.20264)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-988">*Version 2001 (Build 12430.20264)*</span></span>

<span data-ttu-id="7c7f2-989">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-989">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-991">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-991">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7c7f2-992">Access</span><span class="sxs-lookup"><span data-stu-id="7c7f2-992">Access</span></span>

- <span data-ttu-id="7c7f2-993">Access テンプレートは、データベース内の添付ファイル列のエラーを発生させることがなくなりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-993">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="7c7f2-994">テンプレートのインスタンス化後に、データベースに添付ファイル フィールドを追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-994">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="7c7f2-995">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-995">Excel</span></span>

- <span data-ttu-id="7c7f2-996">コンテキスト メニューのコメント コマンドが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-996">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="7c7f2-997">スピル配列が含まれるセルで区切り位置を指定するとクラッシュが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-997">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


### <a name="outlook"></a><span data-ttu-id="7c7f2-998">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-998">Outlook</span></span>

- <span data-ttu-id="7c7f2-999">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-999">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="7c7f2-1000">ユーザーがアカウントのセットアップをキャンセルするときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1000">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>


### <a name="project"></a><span data-ttu-id="7c7f2-1001">Project</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1001">Project</span></span>

- <span data-ttu-id="7c7f2-1002">作業時間固定タイプの達成率 100% のタスクで、達成率が誤って 100% 未満に計算される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1002">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7c7f2-1003">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1003">Office Suite</span></span>

- <span data-ttu-id="7c7f2-1004">この変更では、Intel Integrated GPU を使用するグラフィック アダプターに関して報告された問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1004">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2001-january-30"></a><span data-ttu-id="7c7f2-1006">バージョン 2001: 1 月 30 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1006">Version 2001: January 30</span></span>
<span data-ttu-id="7c7f2-1007">*バージョン 2001 (ビルド 12430.20184)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1007">*Version 2001 (Build 12430.20184)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7c7f2-1009">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1009">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7c7f2-1010">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1010">Excel</span></span>

- <span data-ttu-id="7c7f2-1011">**すぐに読んで返信する**: ブックを開かずに、メールからコメントやメンションに直接返信します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1011">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="7c7f2-1012">**左を見て、右を見て... XLOOKUP をご利用いただけます!** XLOOKUP を使えば、表や範囲内で必要なものは何でも見つけられます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1012">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="7c7f2-1013">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1013">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)

### <a name="outlook"></a><span data-ttu-id="7c7f2-1014">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1014">Outlook</span></span>

- <span data-ttu-id="7c7f2-1015">**高度なグループ メールの設定:** この機能は、グループ ユーザーが受信トレイで受信/フォローするメールまたはイベントを、カスタマイズするのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1015">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="7c7f2-1016">**グループの名前付けポリシー**: グループの名前付けポリシーを使用すると、IT 管理者は組織内のユーザーが作成するグループの名前の標準化と管理を行えます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1016">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="7c7f2-1017">管理者は、グループが作成される際に特定のプレフィックスとサフィックスをグループ名に追加することを要求できます。また、特定の単語の使用を禁止できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1017">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="7c7f2-1018">これにより、グループ名での不適切な単語の使用を最小限に抑えられる他、ディレクトリ内のグループ名の記載を IT 管理者が管理できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1018">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="7c7f2-1019">また、名前付けポリシーを使用することで、チーム サイトを展開する組織は、チーム サイトを部署ごとに分類できるようにもなります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1019">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="word"></a><span data-ttu-id="7c7f2-1020">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1020">Word</span></span>

- <span data-ttu-id="7c7f2-1021">**より安全なビデオ エクスペリエンス:** セキュリティの強化は、より安全なオンライン ビデオ エクスペリエンスを意味します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1021">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="7c7f2-1022">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1022">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="7c7f2-1023">**インクのなげなわ:** [描画] タブのなげなわツールを使用すると、インクで描かれたオブジェクトを選択できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1023">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="7c7f2-1024">個別のストロークまたは文字全体を選択できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1024">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="7c7f2-1025">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1025">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)






[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-1028">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1028">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7c7f2-1029">Access</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1029">Access</span></span>

- <span data-ttu-id="7c7f2-1030">この更新プログラムでは、ADODB を使用する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1030">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="7c7f2-1031">VB コードのれコーター オブジェクトがエラーを誤って報告することがあります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1031">Recorder object in VB code may incorrectly report an error.</span></span>


- <span data-ttu-id="7c7f2-1032">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1032">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="7c7f2-1033">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1033">Excel</span></span>

- <span data-ttu-id="7c7f2-1034">署名の名前を変更したときにクラッシュする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1034">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>


### <a name="outlook"></a><span data-ttu-id="7c7f2-1035">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1035">Outlook</span></span>

- <span data-ttu-id="7c7f2-1036">署名の名前を変更したときにクラッシュする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1036">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1912-january-22"></a><span data-ttu-id="7c7f2-1038">バージョン 1912: 1 月 22 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1038">Version 1912: January 22</span></span>
<span data-ttu-id="7c7f2-1039">*バージョン 1912 (ビルド 12325.20344)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1039">*Version 1912 (Build 12325.20344)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-1041">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1041">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7c7f2-1042">Access</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1042">Access</span></span>

- <span data-ttu-id="7c7f2-1043">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1043">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1912-january-14"></a><span data-ttu-id="7c7f2-1045">バージョン 1912: 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1045">Version 1912: January 14</span></span>
<span data-ttu-id="7c7f2-1046">*バージョン 1912 (ビルド 12325.20298)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1046">*Version 1912 (Build 12325.20298)*</span></span>

<span data-ttu-id="7c7f2-1047">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1047">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-1912-january-08"></a><span data-ttu-id="7c7f2-1048">バージョン 1912: 1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1048">Version 1912: January 08</span></span>
<span data-ttu-id="7c7f2-1049">*バージョン 1912 (ビルド 12325.20288)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1049">*Version 1912 (Build 12325.20288)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7c7f2-1051">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1051">Feature updates</span></span>

### <a name="outlook"></a><span data-ttu-id="7c7f2-1052">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1052">Outlook</span></span>

- <span data-ttu-id="7c7f2-1053">**アクセシビリティ対応のメールを最も必要としている人に送信する:** Outlook では、メールのヒントが表示され、アクセシビリティ対応のコンテンツを必要とするユーザーに送信するときに、コンテンツがアクセシビリティ対応であることを確認できます</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1053">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7c7f2-1054">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1054">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-1055">**プレゼンテーションの最適化:** アクセシビリティ チェックを使用すると、スクリーン リーダーを考慮に入れて、スライド上のオブジェクトを配置することができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1055">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="7c7f2-1056">**簡単な GIF:** 1 つのスライド、1 つのフレーム。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1056">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="7c7f2-1057">PowerPoint でループ GIF を簡単に作成できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1057">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="7c7f2-1058">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1058">Learn more</span></span>](https://support.office.com/en-us/article/a598753e-92de-4f1b-8393-714db4d334b4)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-1061">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1061">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7c7f2-1062">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1062">Excel</span></span>

- <span data-ttu-id="7c7f2-1063">この変更は、ソフトウェア レンダリングを活用することにより、特定の Intel グラフィック ドライバーの問題を回避します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1063">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

### <a name="outlook"></a><span data-ttu-id="7c7f2-1064">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1064">Outlook</span></span>

- <span data-ttu-id="7c7f2-1065">会議をクリアした後、会議の場所が予期せずに会議に追加される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1065">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="7c7f2-1066">キーボード ショートカットを使用してメールボックス フォルダーを操作すると、ユーザーに顕著な遅延が発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1066">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="7c7f2-1067">状況によっては、表示された SMTP アドレスと一致しないアドレスに送信されたメールがユーザーに表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1067">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="7c7f2-1068">ユーザーがクラウド設定を取得する際に Outlook がフリーズする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1068">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

### <a name="word"></a><span data-ttu-id="7c7f2-1069">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1069">Word</span></span>

- <span data-ttu-id="7c7f2-1070">文書パーツ オーガナイザーに 「スタイル、文書パーツを変更しました」 という無効なアラートが表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1070">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="7c7f2-1071">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1071">Office Suite</span></span>

- <span data-ttu-id="7c7f2-1072">Office の更新プログラムが、意図したソース (ローカル共有、ネットワーク共有、構成マネージャー
で提供される場所など) からではなく、予期せずに Office CDN からファイルをダウンロードする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1072">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

## <a name="version-1911-december-10"></a><span data-ttu-id="7c7f2-1073">バージョン 1911: 12 月 10 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1073">Version 1911: December 10</span></span>
<span data-ttu-id="7c7f2-1074">*バージョン 1911 (ビルド 12228.20364)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1074">*Version 1911 (Build 12228.20364)*</span></span>

<span data-ttu-id="7c7f2-1075">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1075">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-1077">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1077">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="7c7f2-1078">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1078">Excel</span></span>

- <span data-ttu-id="7c7f2-1079">この変更は、ソフトウェア レンダリングを活用することにより、特定の Intel グラフィック ドライバーの問題を回避します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1079">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="7c7f2-1080">ピボット グラフの右クリック メニューを修正して、[詳細の表示] オプションを有効にしました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1080">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

### <a name="outlook"></a><span data-ttu-id="7c7f2-1081">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1081">Outlook</span></span>

- <span data-ttu-id="7c7f2-1082">Web アドインがデジタル著作権管理 (DRM) メッセージにアクセスする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1082">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1911-december-03"></a><span data-ttu-id="7c7f2-1084">バージョン 1911: 12 月 3 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1084">Version 1911: December 03</span></span>
<span data-ttu-id="7c7f2-1085">*バージョン 1911 (ビルド 12228.20332)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1085">*Version 1911 (Build 12228.20332)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7c7f2-1087">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1087">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="7c7f2-1088">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1088">Excel</span></span>

- <span data-ttu-id="7c7f2-1089">**複数の値を返す式を入力する:** 複数の値を返す式を素早く入力できるようになりました。隣接するセルに自動的に入力されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1089">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="7c7f2-1090">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1090">Learn more</span></span>](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)

- <span data-ttu-id="7c7f2-1091">**6 つの強力な機能:** スプレッドシートを強化する 6 つの新しい関数が追加されました。FILTER、SORT、SORTBY、UNIQUE、SEQUENCE、RANDARRAY です。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1091">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span> [<span data-ttu-id="7c7f2-1092">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1092">Learn more</span></span>](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- <span data-ttu-id="7c7f2-1093">**データ ビジュアライザー アドイン:** Excel から Visio フローチャートをすばやく作成します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1093">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="7c7f2-1094">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1094">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="7c7f2-1095">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1095">Word</span></span>

- <span data-ttu-id="7c7f2-1096">**共同編集の改善:** コンテンツの変更をリアルタイムでユーザーが受け取れるようにすることで、共同編集のエクスペリエンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1096">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-1099">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1099">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="7c7f2-1100">Access</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1100">Access</span></span>

- <span data-ttu-id="7c7f2-1101">更新クエリが実行されるか、SQL で UPDATE ステートメントが使用されるときに「&quot;クエリは破損しています&quot;」というエラーを発生させる場合のある Microsoft Access の問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1101">Fixed an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="7c7f2-1102">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1102">Excel</span></span>

- <span data-ttu-id="7c7f2-1103">信頼されていないネットワーク共有から保護されたファイルを編集する際に、Excel にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1103">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="7c7f2-1104">ブックが開かれていない状態で最近使用したファイルを検索する際にクラッシュが発生する可能性がある問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1104">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

### <a name="outlook"></a><span data-ttu-id="7c7f2-1105">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1105">Outlook</span></span>

- <span data-ttu-id="7c7f2-1106">アカウント作成コンテキストからサポートに連絡しようとすると、ユーザーに [&quot;OK&quot;] ボタンのある空のメッセージ ボックスが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1106">Addressed an issue that caused users to see an empty message box with an &quot;OK&quot; button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="7c7f2-1107">2019 年に ブラジル タイム ゾーンを使用している場合、2020 年の定期的な会議や予定が間違った時間帯に表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1107">When using the Brazilia time zone in the year 2019, recurring meetings and appointments are displayed in the wrong timeslot for the year 2020.</span></span> <span data-ttu-id="7c7f2-1108">この変更は、ブラジル タイム ゾーンに設定されているクライアントまたは同タイム ゾーンで設定された会議や予定に影響を与えます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1108">This change is relevant for clients set in the Brazilia time zone or for meetings and appointments set in that time zone.</span></span> 

- <span data-ttu-id="7c7f2-1109">ユーザーが [ルール] ダイアログを開くと、「&quot;このコンピューターのルールは、Microsoft Exchange のルールと異なります&quot;」というメッセージが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1109">Addressed an issue that caused users to see a &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="7c7f2-1110">SMIME アルゴリズムの選択に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1110">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="7c7f2-1111">会議の [場所] フィールドが予期せず更新される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1111">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7c7f2-1112">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1112">Office Suite</span></span>

- <span data-ttu-id="7c7f2-1113">Office の更新プログラムが、意図したソース (ローカル共有、ネットワーク共有、構成マネージャー
で提供される場所など) からではなく、予期せずに Office CDN からファイルをダウンロードする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1113">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="7c7f2-1114">ODT と GPO の更新期限設定で、相対期限の設定後、初回のみしか機能しない問題が修正されました。修正により、2 回目以降の更新プログラムで相対期限を使用きるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1114">Fixed an issue in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-november-22"></a><span data-ttu-id="7c7f2-1116">バージョン 1910: 11 月 22 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1116">Version 1910: November 22</span></span>
<span data-ttu-id="7c7f2-1117">*バージョン 1910 (ビルド 12130.20410)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1117">*Version 1910 (Build 12130.20410)*</span></span>
* <span data-ttu-id="7c7f2-1118">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1118">Various bugs and performance fixes.</span></span>

## <a name="version-1910-november-18"></a><span data-ttu-id="7c7f2-1119">バージョン 1910: 11 月 18 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1119">Version 1910: November 18</span></span>
<span data-ttu-id="7c7f2-1120">*バージョン 1910 (ビルド 12130.20390)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1120">*Version 1910 (Build 12130.20390)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-1122">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1122">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="7c7f2-1123">Access</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1123">Access</span></span>

- <span data-ttu-id="7c7f2-1124">更新クエリを実行すると "クエリが破損しています" という誤ったエラー メッセージが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1124">Fixed an issue where running an Update query would incorrectly give an error message: "Query is corrupt".</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-november-12"></a><span data-ttu-id="7c7f2-1126">バージョン 1910: 11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1126">Version 1910: November 12</span></span>
<span data-ttu-id="7c7f2-1127">*バージョン 1910 (ビルド 12130.20344)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1127">*Version 1910 (Build 12130.20344)*</span></span>

<span data-ttu-id="7c7f2-1128">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1128">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-1130">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1130">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7c7f2-1131">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1131">Outlook</span></span>

- <span data-ttu-id="7c7f2-1132">会議の場所フィールドが予期せず変更される原因となる問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1132">Addressed an issue that caused users to see the location field in meetings change unexpectedly.</span></span>

- <span data-ttu-id="7c7f2-1133">アカウント作成コンテキストからサポートに連絡しようとすると、ユーザーに [&quot;OK&quot;] ボタンのある空のメッセージ ボックスが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1133">Addressed an issue that caused users to see an empty message box with an &quot;OK&quot; button when trying to contact support from the Account Creation context.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-october-30"></a><span data-ttu-id="7c7f2-1135">バージョン 1910: 10 月 30 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1135">Version 1910: October 30</span></span>
<span data-ttu-id="7c7f2-1136">*バージョン 1910 (ビルド 12130.20272)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1136">*Version 1910 (Build 12130.20272)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="7c7f2-1137">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1137">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="7c7f2-1138">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1138">Outlook</span></span>

- <span data-ttu-id="7c7f2-1139">検索に関するフィードバックのエクスペリエンスでハングアップする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1139">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7c7f2-1141">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1141">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="7c7f2-1142">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1142">Excel</span></span>

- <span data-ttu-id="7c7f2-1143">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1143">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="7c7f2-1144">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1144">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="7c7f2-1145">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1145">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="7c7f2-1146">**ドキュメントとメールに秘密度ラベルを適用する:** ファイルとメールに秘密度ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1146">**Apply sensitivity labels to your documents and emails:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span> [<span data-ttu-id="7c7f2-1147">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1147">Learn more</span></span>](https://aka.ms/officemipdocs)

### <a name="outlook"></a><span data-ttu-id="7c7f2-1148">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1148">Outlook</span></span>

- <span data-ttu-id="7c7f2-1149">**ドキュメントとメールに秘密度ラベルを適用する:** ファイルとメールに秘密度ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1149">**Apply sensitivity labels to your documents and emails:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span> [<span data-ttu-id="7c7f2-1150">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1150">Learn more</span></span>](https://aka.ms/officemipdocs)

### <a name="powerpoint"></a><span data-ttu-id="7c7f2-1151">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1151">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-1152">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1152">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="7c7f2-1153">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1153">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="7c7f2-1154">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1154">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="7c7f2-1155">**ドキュメントとメールに秘密度ラベルを適用する:** ファイルとメールに秘密度ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1155">**Apply sensitivity labels to your documents and emails:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span> [<span data-ttu-id="7c7f2-1156">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1156">Learn more</span></span>](https://aka.ms/officemipdocs)

### <a name="word"></a><span data-ttu-id="7c7f2-1157">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1157">Word</span></span>

- <span data-ttu-id="7c7f2-1158">**共同編集の改善**: 変更を追跡したドキュメントで共同編集を行う際の Word のパフォーマンスが改善されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1158">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="7c7f2-1159">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1159">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="7c7f2-1160">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1160">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="7c7f2-1161">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1161">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="7c7f2-1162">**3D オブジェクトのマージによって引き起こされるドキュメント破損の問題を修正しました。:** 3D オブジェクトのマージによって引き起こされるドキュメント破損の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1162">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="7c7f2-1163">**ドキュメントとメールに秘密度ラベルを適用する:** ファイルとメールに秘密度ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1163">**Apply sensitivity labels to your documents and emails:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span> [<span data-ttu-id="7c7f2-1164">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1164">Learn more</span></span>](https://aka.ms/officemipdocs)

### <a name="office-suite"></a><span data-ttu-id="7c7f2-1165">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1165">Office Suite</span></span>

- <span data-ttu-id="7c7f2-1166">**Office 365 ProPlus の既存のインストールに Microsoft Teams をインストールする:** 6 月下旬から、Microsoft Teams は、これらのインストールの更新時に、Office 365 ProPlus (および Office 365 Business) の既存のインストールに含まれます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1166">**Install Microsoft Teams on existing installations of Office 365 ProPlus:** Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="7c7f2-1167">Teams が追加される日にちは、使用している更新プログラム チャネルによって異なります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1167">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="7c7f2-1168">追加情報については、「Office 365 ProPlus と同時に Microsoft Teams を展開する」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1168">Please refer to Deploy Microsoft Teams with Office 365 ProPlus for additional information.</span></span> [<span data-ttu-id="7c7f2-1169">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1169">Learn More</span></span>](/deployoffice/teams-install)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1909-october-22"></a><span data-ttu-id="7c7f2-1171">バージョン 1909: 10 月 22 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1171">Version 1909: October 22</span></span>
<span data-ttu-id="7c7f2-1172">*バージョン 1909 (ビルド 12026.20344)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1172">*Version 1909 (Build 12026.20344)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="7c7f2-1174">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1174">Non-security updates</span></span>
### <a name="project"></a><span data-ttu-id="7c7f2-1175">Project</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1175">Project</span></span>
- <span data-ttu-id="7c7f2-1176">読み取り専用のプロジェクトを開いたときに多数のメッセージを受けることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1176">Resolved an issue where users could get several messages when opening a read-only project.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7c7f2-1177">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1177">Office Suite</span></span>

- <span data-ttu-id="7c7f2-1178">Office ユーザーのセキュリティを保護するために、Microsoft Office の更新プログラムは SHA-2 アルゴリズムのみを使用して署名されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1178">To protect Office customers’ security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span><br>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="october-15"></a><span data-ttu-id="7c7f2-1180">10 月 15 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1180">October 15</span></span>

### <a name="non-security-updates"></a><span data-ttu-id="7c7f2-1181">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1181">Non-security updates</span></span>

### <a name="office-suite"></a><span data-ttu-id="7c7f2-1182">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1182">Office Suite</span></span>
- <span data-ttu-id="7c7f2-1183">12130.20184 よりも古いビルドで 2019 年 10 月 14 日に投稿された保存の問題を解決するために、一時的に [クラウド保存] ダイアログを無効にしました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1183">We have temporarily disabled the Cloud Save dialog to address the saving issue we posted on October 14, 2019 for builds older than 12130.20184.</span></span> <span data-ttu-id="7c7f2-1184">この機能は、まもなく有効になります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1184">This feature will be re-enabled soon.</span></span>


## <a name="version-1909-october-14"></a><span data-ttu-id="7c7f2-1185">バージョン 1909: 10 月 14 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1185">Version 1909: October 14</span></span>
<span data-ttu-id="7c7f2-1186">*バージョン 1909 (ビルド 12026.20334)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1186">*Version 1909 (Build 12026.20334)*</span></span>

### <a name="non-security-updates"></a><span data-ttu-id="7c7f2-1187">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1187">Non-security updates</span></span>

### <a name="office-suite"></a><span data-ttu-id="7c7f2-1188">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1188">Office Suite</span></span>

- <span data-ttu-id="7c7f2-1189">12130.20184 よりも古いビルドでユーザーが Word、Excel、および PowerPoint 2019 のドキュメントを保存できなくなるという問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1189">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint 2019 documents for builds older than 12130.20184.</span></span>  <span data-ttu-id="7c7f2-1190">この問題は、[保存] アイコンをクリックしたり Ctrl キーを押しながら S キーを押したりした後に、新しいファイルを作成して [名前を付けて保存] ダイアログを表示するユーザーに影響を与えます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1190">This issue affects users that create a new file and bring up the “Save As” dialog after clicking on the Save icon or pressing Ctrl + S.</span></span>


## <a name="version-1909-october-08"></a><span data-ttu-id="7c7f2-1191">バージョン 1909: 10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1191">Version 1909: October 08</span></span>
<span data-ttu-id="7c7f2-1192">*バージョン 1909 (ビルド 12026.20320)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1192">*Version 1909 (Build 12026.20320)*</span></span>

<span data-ttu-id="7c7f2-1193">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1193">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="7c7f2-1195">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1195">Non-security updates</span></span>

### <a name="outlook"></a><span data-ttu-id="7c7f2-1196">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1196">Outlook</span></span>

- <span data-ttu-id="7c7f2-1197">Outlook の添付ファイルのブロック ロジックが Python による添付ファイルもブロックする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1197">Fixed an issue with attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="7c7f2-1198">ユーザーが定期的な予定表の一部のインスタンスを開けない原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1198">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="7c7f2-1199">ユーザーが Outlook プロセスでメモリ リークを観測する原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1199">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="7c7f2-1200">ユーザーがプロフィールの作成中にクラッシュを発生させる原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1200">Addressed an issue that caused users to experience a crash during profile creation.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1909-september-30"></a><span data-ttu-id="7c7f2-1202">バージョン 1909: 9 月 30 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1202">Version 1909: September 30</span></span>
<span data-ttu-id="7c7f2-1203">*バージョン 1909 (ビルド 12026.20264)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1203">*Version 1909 (Build 12026.20264)*</span></span>
* <span data-ttu-id="7c7f2-1204">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1204">Various bugs and performance fixes.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="7c7f2-1206">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1206">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="7c7f2-1207">Access</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1207">Access</span></span>

- <span data-ttu-id="7c7f2-1208">**リンク テーブルをすばやく見つける:** 新しい検索ボックスを使用すると、リンク テーブルを簡単に見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1208">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="7c7f2-1209">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1209">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="7c7f2-1210">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1210">Excel</span></span>

- <span data-ttu-id="7c7f2-1211">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1211">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="outlook"></a><span data-ttu-id="7c7f2-1212">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1212">Outlook</span></span>

- <span data-ttu-id="7c7f2-1213">**テナント管理者によって定義されたアクセス許可を使用して、Outlook の [リンクの挿入] メニューでリンクを挿入する:** Outlook で最近使用されたリンクの挿入 (MRU) のリンクでは、既にそれに対するアクセス許可を持つユーザーのみに動作したリンクが挿入されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1213">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="7c7f2-1214">これは、ドキュメントへのアクセス権の付与を求めるユーザー間でのメールの行き来をしばしば引き起こします。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1214">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="7c7f2-1215">このエクスペリエンスが更新されましたので、テナント管理者によって設定される既定のアクセス許可を使用し、リンクを挿入できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1215">We've updated this experience so now the link is inserted with the default permission set by the tenant admin.</span></span>

- <span data-ttu-id="7c7f2-1216">**Outlook の外観の更新:** これは、Outlook で核となるエクスペリエンスの外観の更新の一部であり、閲覧ウィンドウとインスペクターに含まれるメール メッセージのレイアウトを更新しています。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1216">**Outlook visual refresh:** This is part of the visual refresh of core experiences in Outlook, updating how mail messages layout in the reading pane and inspector.</span></span>

- <span data-ttu-id="7c7f2-1217">**より高速化した共有カレンダーの更新**: Office 365 の共有カレンダーの場合、Outlook では REST API を使用してこれらのカレンダーを更新します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1217">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="7c7f2-1218">共有カレンダーのより高速で信頼性の高い更新を行うには、プレビューを有効にします。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1218">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="7c7f2-1219">**検索結果で関連メッセージを確認する:** Outlook では検索条件を分析し、最も関連性の高いメール メッセージを検索結果の上部に表示します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1219">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="7c7f2-1220">また、[上位の結果] セクションには、すべての結果が日付順に表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1220">You'll also see all results sorted by date in the Top Results section.</span></span>

- <span data-ttu-id="7c7f2-1221">**適切なユーザーにメールを送信する:** [宛先] 行をクリックして、連絡先候補から選択するだけです。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1221">**Send the mail to the right person:** Just click the To: line and choose from suggested contacts.</span></span> <span data-ttu-id="7c7f2-1222">画像とプレゼンス インジケーターにより、適切なユーザーを選択することができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1222">A picture and presence indicator helps you choose the right person.</span></span>

- <span data-ttu-id="7c7f2-1223">**攻撃に対する高度な保護:** Office 365 Advanced Threat Protection を用いると、メールの件名、添付メッセージ、署名されたメッセージ、ネットワーク パスなどの範囲内のハイパーリンクを利用した攻撃から保護されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1223">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="7c7f2-1224">**異なる明るさでメッセージを表示する:** [太陽] または [月] のボタンを使用して、閲覧ウィンドウの明るい背景と暗い背景を切り替えます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1224">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="7c7f2-1225">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1225">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

### <a name="powerpoint"></a><span data-ttu-id="7c7f2-1226">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1226">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-1227">**図を SVG として保存する:** グラフ、図形、その他の図を、サイズ変更しても画質が低下しないスケーラブル ベクター グラフィックとして保存できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1227">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="7c7f2-1228">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1228">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="7c7f2-1229">**インクを瞬時に再生:** インク描画にアニメーション効果を適用して、スライド ショーの間中、それが進んだり戻ったりして再生されるようにします。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1229">**Ink-stant replay:** Animate an ink drawing so that it replays forward or backward during your slide show.</span></span> [<span data-ttu-id="7c7f2-1230">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1230">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="7c7f2-1231">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1231">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="visio"></a><span data-ttu-id="7c7f2-1232">Visio</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1232">Visio</span></span>

- <span data-ttu-id="7c7f2-1233">**Microsoft Flow と Visio を使用したビジネス ワークフローの設計と自動化:** Visio を使用してワークフロー図を設計し、Microsoft Flow にエクスポートして自動化します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1233">**Design and automate business workflows using Microsoft Flow and Visio:** Use Visio to design workflow diagram and export it to Microsoft Flow to automate.</span></span>

### <a name="word"></a><span data-ttu-id="7c7f2-1234">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1234">Word</span></span>

- <span data-ttu-id="7c7f2-1235">**別の言葉で伝える:** 別の言葉で伝えたいときに、[書き換え] でお助けします。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1235">**Say it another way:** When you want to say it differently, Rewrite is there to help.</span></span> <span data-ttu-id="7c7f2-1236">[書き換え] では、フレーズを洗練させるための別の言葉遣いを提供します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1236">Rewrite offers alternatives for finessing your phrases.</span></span>

- <span data-ttu-id="7c7f2-1237">**共同編集の改善:** 共同編集時の信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1237">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="7c7f2-1238">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1238">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="7c7f2-1239">**他のユーザーがすばやく変更を確認:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1239">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="7c7f2-1242">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1242">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="7c7f2-1243">Excel</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1243">Excel</span></span>

- <div><span data-ttu-id="7c7f2-1244"><span style="background-color:rgb(255, 255, 255);display:inline !important;">一部の保護されたシートにハイパーリンクが貼り付けられない問題が解決されました。</span></span><span class="sxs-lookup"><span data-stu-id="7c7f2-1244"><span style="background-color:rgb(255, 255, 255);display:inline !important;">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span></span><br></div>


- <div><span data-ttu-id="7c7f2-1245">&nbsp;<span style="font-size:13.3333px;background-color:rgb(255, 255, 255);display:inline !important;">アドイン マネジャーで参照するときに</span>、16 個以上のアドインを表示できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1245">Enabled more than 16 add-ins to show&nbsp;<span style="font-size:13.3333px;background-color:rgb(255, 255, 255);display:inline !important;">when browsing in the add-in manager.</span></span></span></div>
- <div><span data-ttu-id="7c7f2-1246">Win32 クライアントの [アイデア] ボタンをクリックしてアドインを読み込むときにエラーが発生するという Excel のアイデア機能の問題を修正します。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1246">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.&nbsp;</span></span></div>

### <a name="outlook"></a><span data-ttu-id="7c7f2-1247">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1247">Outlook</span></span>

- <div><span data-ttu-id="7c7f2-1248">一部の safelinks に対して簡易的なホバーの URL が正しく表示されなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1248">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span></div>


- <span data-ttu-id="7c7f2-1249"><span style="background-color:rgb(255, 255, 255);display:inline !important;">Python による添付ファイルもブロックされるよう、Outlook の添付ファイルのブロック ロジックが更新されました。</span></span><span class="sxs-lookup"><span data-stu-id="7c7f2-1249"><span style="background-color:rgb(255, 255, 255);display:inline !important;">Updated the attachment blocking logic in Outlook to also block python attachments.</span></span></span>


- <span data-ttu-id="7c7f2-1250"><span style="background-color:rgb(255, 255, 255);display:inline !important;">ユーザーによって確認される Outlook のプロセスのメモリ リークを引き起こす問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="7c7f2-1250"><span style="background-color:rgb(255, 255, 255);display:inline !important;">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span></span>

- <span data-ttu-id="7c7f2-1251">WebDAV の場所にファイルを保存できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1251">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>


### <a name="office-suite"></a><span data-ttu-id="7c7f2-1252">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1252">Office Suite</span></span>

- <div><p style="margin:0in 0in 0.0001pt;font-size:11pt;font-family:Calibri, sans-serif;"><span data-ttu-id="7c7f2-1253">ファイルを開くときにユーザーが直面していた問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1253">We fixed an issue users were hitting when opening a file.</span></span></p></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-september-10"></a><span data-ttu-id="7c7f2-1255">バージョン 1908: 9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1255">Version 1908: September 10</span></span>
<span data-ttu-id="7c7f2-1256">*バージョン 1908 (ビルド 11929.20300)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1256">*Version 1908 (Build 11929.20300)*</span></span>

<span data-ttu-id="7c7f2-1257">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1257">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="7c7f2-1259">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1259">Non-security updates</span></span>
### <a name="outlook"></a><span data-ttu-id="7c7f2-1260">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1260">Outlook</span></span>

- <span data-ttu-id="7c7f2-1261">スクリーン リーダーからユーザーが場所の候補にアクセスできない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1261">Fixed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="7c7f2-1262">一部のユーザーが Outlook のクラウド設定を取得しようとすると、認証エラーが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1262">Fixed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="7c7f2-1263">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1263">PowerPoint</span></span>

- <span data-ttu-id="7c7f2-1264">PowerPoint ビデオ コントロールのアクセス可能な名前を復元する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1264">Fixed an issue to restore the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="7c7f2-1265">一部のアニメーションが開始できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1265">Fixed an issue which could prevent some animations from starting.</span></span>

### <a name="word"></a><span data-ttu-id="7c7f2-1266">Word</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1266">Word</span></span>

- <span data-ttu-id="7c7f2-1267">SharePoint 2016 に保存されているファイルを共有しようとすると、"申し訳ございません。何かがこのファイルの共有を妨げています。" というメッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1267">Fixed an issue which caused users to get the message "Sorry, something is preventing us from sharing this"  when trying to share files stored on SharePoint 2016.</span></span>

### <a name="office-suite"></a><span data-ttu-id="7c7f2-1268">Office スイート</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1268">Office Suite</span></span>

- <span data-ttu-id="7c7f2-1269">大きなツリー ビューの表示に失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1269">Fixed an issue where large tree views were failing.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-august-26"></a><span data-ttu-id="7c7f2-1271">バージョン 1908: 8 月 26 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1271">Version 1908: August 26</span></span>
<span data-ttu-id="7c7f2-1272">*バージョン 1908 (ビルド 11929.20254)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1272">*Version 1908 (Build 11929.20254)*</span></span>
* <span data-ttu-id="7c7f2-1273">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1273">Various bugs and performance fixes.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="7c7f2-1274">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1274">Excel: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1275">**あらましを描く:** ブック内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1275">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="7c7f2-1276">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1276">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="7c7f2-1277">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1277">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="7c7f2-1278">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1278">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="7c7f2-1279">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1279">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

- <span data-ttu-id="7c7f2-1280">**残っている作業に集中する:** [解決] を選択して、コメントを折りたたみ、開いているアイテムを目立たせます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1280">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

### <a name="office-suite-feature-updates"></a><span data-ttu-id="7c7f2-1281">Office スイート: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1281">Office Suite: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1282">**新しい外観を備えた Office のアイコン:** シンプルかつ高性能で、インテリジェントな Office のエクスペリエンスを反映するように、Office のアイコンがリニューアルされました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1282">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="7c7f2-1283">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1283">Outlook: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1284">**場所の候補を取得する:** 予定や会議をスケジュールするときに、[場所] に入力すると、会議室、住所、およびその他の最新の場所が提示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1284">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="7c7f2-1285">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1285">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="7c7f2-1286">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1286">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="7c7f2-1287">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1287">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="7c7f2-1288">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1288">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="7c7f2-1289">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1289">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1290">**あらましを描く:** プレゼンテーション内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1290">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="7c7f2-1291">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1291">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="7c7f2-1292">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1292">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="7c7f2-1293">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1293">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="7c7f2-1294">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1294">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="word-feature-updates"></a><span data-ttu-id="7c7f2-1295">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1295">Word: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1296">**あらましを描く:** ドキュメント内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1296">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="7c7f2-1297">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1297">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="7c7f2-1298">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1298">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="7c7f2-1299">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1299">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="7c7f2-1300">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1300">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

## <a name="version-1907-august-13"></a><span data-ttu-id="7c7f2-1301">バージョン 1907: 8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1301">Version 1907: August 13</span></span>
<span data-ttu-id="7c7f2-1302">*バージョン 1907 (ビルド 11901.20218)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1302">*Version 1907 (Build 11901.20218)*</span></span>

<span data-ttu-id="7c7f2-1303">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1303">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="7c7f2-1304">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1304">Excel: Non-security updates</span></span>

- <span data-ttu-id="7c7f2-1305">ピボットテーブルの並べ替え方法を変更し、他のユーザーとの共同編集セッション中にそれを更新する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1305">Fixed an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="7c7f2-1306">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1306">Outlook: Non-security updates</span></span>

- <span data-ttu-id="7c7f2-1307">メールボックスを基本認証から最新認証にアップグレードしたユーザーが、Outlook プロファイルに関連付けられた正しくないアカウントで終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1307">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

## <a name="version-1907-july-29"></a><span data-ttu-id="7c7f2-1308">バージョン 1907: (7 月 29 日)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1308">Version 1907: July 29</span></span>

<span data-ttu-id="7c7f2-1309">*バージョン 1907 (ビルド 11901.20176)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1309">*Version 1907 (Build 11901.20176)*</span></span>
* <span data-ttu-id="7c7f2-1310">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1310">Various bugs and performance fixes.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="7c7f2-1311">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1311">Excel: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1312">**ブラウザーへのバウンスは不要:** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定することができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1312">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="7c7f2-1313">**Power Query の機能強化を使用して素早くコーディングする:** オートコンプリートおよび構文の色分けによって素早くコーディングを完了できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1313">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="7c7f2-1314">関数、列、パラメーターも簡単に見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1314">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="7c7f2-1315">**マップ グラフを作成する:** この機能は、Excel の地理データ型を使用して、塗り分けされたマップ グラフにプロットするユーザーのための機能強化です。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1315">**Create a Map chart:** This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="7c7f2-1316">エンドユーザーにとっては、機能とエンドユーザーがマップする領域の精度向上とがより高度に統合されたことが利点です。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1316">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="7c7f2-1317">さらに、ポリゴンで都市をマッピングする機能も含まれてます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1317">Additional benefits include - ability to map city polygons.</span></span> [<span data-ttu-id="7c7f2-1318">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1318">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="7c7f2-1319">**類似列のテーブルを結合する:** 取得と変換 (Power Query) では、テーブルを統合するために列を比較するときに、近似文字列マッチング ロジック (あいまい一致とも呼ばれる) が使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1319">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="7c7f2-1320">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1320">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

### <a name="outlook-feature-updates"></a><span data-ttu-id="7c7f2-1321">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1321">Outlook: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1322">**あなたが人を検索するときに電子メールの提案を得ます:** [検索]ボックスにその人の名前を入力すると、最も関連性の高い電子メールメッセージが検索結果に含まれます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1322">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="7c7f2-1323">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1323">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="7c7f2-1324">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1324">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1325">**ブラウザーへのバウンスは不要:** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定することができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1325">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="7c7f2-1326">**オンライン ビデオの新しい保存場所:** Microsoft Stream にビデオを保存すれば、組織内のすべてのユーザーが視聴できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1326">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="7c7f2-1327">ビデオのリンクを挿入すれば、小さなファイル サイズでマルチメディア プレゼンテーションをご利用いただけます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1327">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="7c7f2-1328">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1328">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="7c7f2-1329">**マップ グラフを作成する:** この機能は、Excel の地理データ型を使用して、塗り分けされたマップ グラフにプロットするユーザーのための機能強化です。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1329">**Create a Map chart:** This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="7c7f2-1330">エンドユーザーにとっては、機能とエンドユーザーがマップする領域の精度向上とがより高度に統合されたことが利点です。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1330">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="7c7f2-1331">さらに、ポリゴンで都市をマッピングする機能も含まれてます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1331">Additional benefits include - ability to map city polygons.</span></span> [<span data-ttu-id="7c7f2-1332">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1332">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="7c7f2-1333">**スライドのタイトルを追加してプレゼンテーションをアクセス可能にする:** アクセシビリティ チェックは、不足しているスライドのタイトルを見つけて修正するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1333">**Add Slide Titles to make your presentations accessible:** Accessibility Checker helps you find and fix missing slide titles.</span></span> [<span data-ttu-id="7c7f2-1334">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1334">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="7c7f2-1335">**アクセスを容易にするため、[印刷] メニューに [配布資料にスライド番号を印刷する] を移動しました:** 配布資料を指定したら、[印刷]、[印刷レイアウト] ドロップダウンの順にクリックすれば見つかります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1335">**The setting to Print Slide Numbers in Handouts has been moved to the Print Menu for easier access:**  Find it in the Print > Print Layout dropdown when a Handout layout is selected.</span></span> <span data-ttu-id="7c7f2-1336">これにより、プレゼンテーションごとに簡単に設定を切り替えることもできます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1336">This also allows the setting to be easily toggled per presentation.</span></span> [<span data-ttu-id="7c7f2-1337">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1337">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

### <a name="word-feature-updates"></a><span data-ttu-id="7c7f2-1338">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1338">Word: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1339">**作業の邪魔をするものにさよならしましょう:** Mac のお気に入りの機能が Windows にも登場します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1339">**Say goodbye to distractions:** A favorite Mac feature comes to Windows.</span></span> <span data-ttu-id="7c7f2-1340">気を散らさずに作業に集中するには、[表示]メニューの[フォーカス]に切り替えます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1340">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> [<span data-ttu-id="7c7f2-1341">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1341">Learn more</span></span>](https://support.office.com/article/51af2fb2-194f-424b-ab7e-b65de9ec9292)

- <span data-ttu-id="7c7f2-1342">**ブラウザーへのバウンスは不要:** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定することができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1342">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="7c7f2-1343">**マップ グラフを作成する:** この機能は、Excel の地理データ型を使用して、塗り分けされたマップ グラフにプロットするユーザーのための機能強化です。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1343">**Create a Map chart:** This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="7c7f2-1344">エンドユーザーにとっては、機能とエンドユーザーがマップする領域の精度向上とがより高度に統合されたことが利点です。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1344">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="7c7f2-1345">さらに、ポリゴンで都市をマッピングする機能も含まれてます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1345">Additional benefits include - ability to map city polygons.</span></span> [<span data-ttu-id="7c7f2-1346">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1346">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="7c7f2-1347">**精度による消去:** 手描き入力の小さな不備を修正するのに、2 つのサイズの消しゴムから選択できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1347">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="7c7f2-1348">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1348">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

## <a name="version-1906-july-09"></a><span data-ttu-id="7c7f2-1349">バージョン 1906: 7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1349">Version 1906: July 09</span></span>
<span data-ttu-id="7c7f2-1350">*バージョン 1906 (ビルド 11727.20244)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1350">*Version 1906 (Build 11727.20244)*</span></span>

<span data-ttu-id="7c7f2-1351">セキュリティ更新プログラムの一覧は「[こちら](./microsoft365-apps-security-updates.md)」</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1351">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="7c7f2-1352">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1352">Outlook: Non-security updates</span></span>

- <span data-ttu-id="7c7f2-1353">現在のフォルダー検索で断続的な失敗を引き起こす問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1353">Addresses an issue that caused current folder search to intermittently fail.</span></span>

## <a name="version-1906-june-27"></a><span data-ttu-id="7c7f2-1354">バージョン 1906: 6 月 27 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1354">Version 1906: June 27</span></span>
<span data-ttu-id="7c7f2-1355">*バージョン 1906 (ビルド 11727.20230)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1355">*Version 1906 (Build 11727.20230)*</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="7c7f2-1356">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1356">Outlook: Non-security updates</span></span>

- <span data-ttu-id="7c7f2-1357">設定に関係なく、POP3 ユーザーの一部がプレーンテキストで書式設定されたすべてのメールを表示する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1357">Addresses an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span>  <span data-ttu-id="7c7f2-1358">この修正プログラムでは、HTML 形式のメッセージの表示が復元されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1358">This fix will restore the view of the HTML formatted messages.</span></span>

## <a name="version-1906-june-26"></a><span data-ttu-id="7c7f2-1359">バージョン 1906: 6 月 26 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1359">Version 1906: June 26</span></span>
<span data-ttu-id="7c7f2-1360">*バージョン 1906 (ビルド 11727.20224)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1360">*Version 1906 (Build 11727.20224)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="7c7f2-1361">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1361">Excel: Non-security updates</span></span>

- <span data-ttu-id="7c7f2-1362">図形やフォームコントロールに割り当てられているマクロが間違ったエラーメッセージとして表示される、または間違った対象範囲で動作する問題が Excel で修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1362">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>
- <span data-ttu-id="7c7f2-1363">テーブルの横にある切り取りと貼り付けの操作を、他のユーザーと共同編集しているときに失敗する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1363">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="7c7f2-1364">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1364">Outlook: Non-security updates</span></span>

- <span data-ttu-id="7c7f2-1365">代理人が特定の会議出席依頼に既に返信したかどうかに関係なく、管理者が不明瞭になる問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1365">Addresses an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

## <a name="version-1906-june-24"></a><span data-ttu-id="7c7f2-1366">バージョン 1906: 6 月24 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1366">Version 1906: June 24</span></span>
<span data-ttu-id="7c7f2-1367">*バージョン 1906 (ビルド 11727.20210)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1367">*Version 1906 (Build 11727.20210)*</span></span>
* <span data-ttu-id="7c7f2-1368">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1368">Various bugs and performance fixes.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="7c7f2-1369">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1369">Excel: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1370">**ワークシートが生まれ変わりました：** ワークブックを使ってアニメーション 3D グラフィックスを挿入し、心臓の鼓動、惑星軌道、そして T-Rex の大暴れを見ることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1370">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="7c7f2-1371">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1371">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

### <a name="outlook-feature-updates"></a><span data-ttu-id="7c7f2-1372">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1372">Outlook: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1373">**カスタマイズも可能、シンプルになったリボン：** 最もよく使うボタンが単一行にまとめられ、使いやすくなりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1373">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="7c7f2-1374">簡単に従来のビューとシンプルなビューを切り替えたり、コマンドを固定または固定解除できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1374">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="7c7f2-1375">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1375">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="7c7f2-1376">**お気に入りのアクションを選びましょう：** フラグや、削除機能を使いますか？</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1376">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="7c7f2-1377">アーカイブまたは既読に​​しますか?</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1377">How about Archive or Mark as Read?</span></span> <span data-ttu-id="7c7f2-1378">クイック操作メニューをカスタマイズしてよく使うコマンドを追加できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1378">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="7c7f2-1379">**多数のフォルダを持つメールボックスの共有フォルダ同期の向上：** 共有メールボックスを同期するとき、Outlook は長年にわたって最大 500 個のフォルダに制限されていました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1379">**Improved shared folder synchronization for mailboxes with many folders:** For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="7c7f2-1380">この変更により Outlook の改善が行われ、同期をする際の 500 フォルダーの制限がなくなりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1380">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

- <span data-ttu-id="7c7f2-1381">**集中受信トレイの設定がデバイス間で変わらなくなります：** 集中受信トレイの設定はクラウドに保存されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1381">**Focused Inbox settings remain the same across devices:** Your Focused Inbox preferences are now stored in the cloud.</span></span> <span data-ttu-id="7c7f2-1382">どのコンピューターの Windows 版 Outlook や Outlook on the web でも、同じ機能をご利用いただけます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1382">Enjoy the same experience when you use Outlook for Windows on any computer and Outlook on the web.</span></span> [<span data-ttu-id="7c7f2-1383">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1383">Learn more</span></span>](https://support.office.com/article/d77a442e-a86c-4bf8-b3dd-5571ae556986)

- <span data-ttu-id="7c7f2-1384">**ゆったりとしたレイアウト、まとめたレイアウト？自由に決めましょう：** 狭い間隔で、アイテム間の間隔をより広くしたり、レイアウトを狭くして表示量をより多くできます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1384">**Relaxed or tighter layout? You choose:** Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

- <span data-ttu-id="7c7f2-1385">**Outlook のユーザー エクスペリエンスを更新しました：** これまで Coming Soon でプレビューできていた、最も重要なことに集中できるようにするためのシンプルな操作性です。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1385">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="7c7f2-1386">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1386">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="7c7f2-1387">**自分で描いて表現しましょう:** 画像の上に走り書きするか、描画キャンバスを追加して、インクを用いて自分の考えを送信します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1387">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="7c7f2-1388">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1388">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

### <a name="word-feature-updates"></a><span data-ttu-id="7c7f2-1389">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1389">Word: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1390">**共同編集：** マクロを使用したドキュメントから締め出されるのにうんざりしていませんか。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1390">**CoAuthoring:** Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="7c7f2-1391">これで OneDrive for Business 上の docm ファイルで複数の作成者による同時編集が可能になります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1391">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="7c7f2-1392">Skype for Business: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1392">Skype for Business: Non-security updates</span></span> 

 - <span data-ttu-id="7c7f2-1393">モニタの倍率が 100 ％を超えたときに、会議で Polycom CX5500 および関連デバイスからのすべてのカメラストリームを表示するように修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1393">Fix to display all camera streams from Polycom CX5500 and related devices in a meeting when your monitor is scaled more than 100%</span></span>

- <span data-ttu-id="7c7f2-1394">[会議のビデオをトリミングして中央揃えにする] 設定が有効になっている場合、4Kモニタで会議のビデオを正しくトリミングします</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1394">Correctly crop video in a meeting on a 4K monitor when the "Crop and Center my video in meetings" setting is enabled</span></span>

- <span data-ttu-id="7c7f2-1395">複数のネットワークアダプタを備えた Windows 10 コンピュータから従来の Office Communicator クライアントへのファイル転送を許可します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1395">Allow transferring files to legacy Office Communicator clients from a Windows 10 computer with multiple network adapters.</span></span>

- <span data-ttu-id="7c7f2-1396">Skype for Business と Microsoft Teams の参加者間のコミュニケーションのしやすさが向上</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1396">Improved experience for communication between Skype for Business and Microsoft Teams participants</span></span>


## <a name="version-1905-june-11"></a><span data-ttu-id="7c7f2-1397">バージョン 1905: 6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1397">Version 1905: June 11</span></span>
<span data-ttu-id="7c7f2-1398">*バージョン 1905 (ビルド 11629.20246)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1398">*Version 1905 (Build 11629.20246)*</span></span>
<br/><span data-ttu-id="7c7f2-1399">[こちら](./microsoft365-apps-security-updates.md)にセキュリティ更新プログラムが記載されています</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1399">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="7c7f2-1400">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1400">Excel: Non-security updates</span></span>

- <span data-ttu-id="7c7f2-1401">セルが挿入または削除されたときに、ウォーターフォール図とじょうごグラフがテーブルと同期しなくなる原因となっていた問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1401">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="7c7f2-1402">PowerPoint: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1402">PowerPoint: Non-security updates</span></span>

- <span data-ttu-id="7c7f2-1403">一部のアドインがグラフの図形に対して予期しないエラーをスローさせる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1403">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

### <a name="visio-non-security-updates"></a><span data-ttu-id="7c7f2-1404">Visio: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1404">Visio: Non-security updates</span></span>

- <span data-ttu-id="7c7f2-1405">Visio から SVG へのエクスポートは、さまざまな図形に対して機能しませんでした。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1405">Export to SVG from Visio was not working for a variety of shapes.</span></span>

## <a name="version-1905-june-3"></a><span data-ttu-id="7c7f2-1406">バージョン 1905: 6 月 3 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1406">Version 1905: June 3</span></span>
<span data-ttu-id="7c7f2-1407">*バージョン 1905 (ビルド 11629.20214)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1407">*Version 1905 (Build 11629.20214)*</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="7c7f2-1408">PowerPoint: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1408">PowerPoint: Non-security updates</span></span>

- <span data-ttu-id="7c7f2-1409">一部のアドインがグラフの図形に対して予期しないエラーをスローさせる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1409">Fixed an issue where some addins would throw unexpected errors around shapes in charts.</span></span>

## <a name="version-1905-may-29"></a><span data-ttu-id="7c7f2-1410">バージョン 1905: 5 月 29 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1410">Version 1905: May 29</span></span>
<span data-ttu-id="7c7f2-1411">*バージョン 1905 (ビルド 11629.20196)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1411">*Version 1905 (Build 11629.20196)*</span></span>

### <a name="access-feature-updates"></a><span data-ttu-id="7c7f2-1412">Access: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1412">Access: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1413">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1413">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="7c7f2-1414">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1414">Switching between them has never been easier.</span></span> [<span data-ttu-id="7c7f2-1415">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1415">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="excel-feature-updates"></a><span data-ttu-id="7c7f2-1416">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1416">Excel: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1417">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1417">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="7c7f2-1418">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1418">Switching between them has never been easier.</span></span> [<span data-ttu-id="7c7f2-1419">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1419">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="7c7f2-1420">**近日公開予定:** 近日公開予定の Office に対する魅力あふれる変更点を確認してお試しいただき、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1420">**Coming Soon:** See what exciting changes are Coming Soon to Office, try them out and give us feedback.</span></span> [<span data-ttu-id="7c7f2-1421">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1421">Learn more</span></span>](https://support.office.com/article/7800e0cf0-812f-475a-80aa-d47376e076f2)

- <span data-ttu-id="7c7f2-1422">**コメント内で @メンションを使用してより効率的に共同作業を行う:** 共同作業がとても簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1422">**Collaborate more effectively with @Mentions in Comments:** Collaboration just became a whole lot easier!</span></span> <span data-ttu-id="7c7f2-1423">ドキュメントのコメント内でチームメートを @メンションできるようになりました。ドキュメントに案内するメール通知が自動的にチームメートに送られます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1423">Now you can @mention teammates in document comments and they will automatically receive an email notification drawing them into the document.</span></span>

- <span data-ttu-id="7c7f2-1424">**共同編集の結合の改善:** 条件付き書式、セルのスタイル、範囲の保護、グリッド線の表示、シート間の切り取り/貼り付けを使用する際に、共同編集での結合の成功率が改善されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1424">**Coauthoring merge improvements:** Coauthoring has improved the merge success rate when working with conditional formatting, cell styles, range protection, view gridlines, and cross-sheet cut/paste.</span></span> 

### <a name="outlook"></a><span data-ttu-id="7c7f2-1425">Outlook</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1425">Outlook</span></span>

- <span data-ttu-id="7c7f2-1426">**より簡単なアカウントの追加方法:** アカウントのセットアップの改善により、2 要素認証を使用する Outlook.com と Gmail のアカウントを Outlook に追加することが以前よりも簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1426">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="7c7f2-1427">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1427">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="7c7f2-1428">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1428">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1429">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1429">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="7c7f2-1430">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1430">Switching between them has never been easier.</span></span> [<span data-ttu-id="7c7f2-1431">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1431">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="7c7f2-1432">**ライブ キャプションと字幕:** 発表者の言葉が、キャプションまたは選択した言語での字幕として自動的に画面に表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1432">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="7c7f2-1433">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1433">Learn more</span></span>](https://support.office.com/article/d68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="7c7f2-1434">**近日公開予定:** 近日公開予定の Office に対する魅力あふれる変更点を確認してお試しいただき、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1434">**Coming Soon:** See what exciting changes are Coming Soon to Office, try them out and give us feedback.</span></span> [<span data-ttu-id="7c7f2-1435">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1435">Learn more</span></span>](https://support.office.com/article/7800e0cf0-812f-475a-80aa-d47376e076f2)

- <span data-ttu-id="7c7f2-1436">**コメント内で @メンションを使用してより効率的に共同作業を行う:** 共同作業がとても簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1436">**Collaborate more effectively with @Mentions in Comments:** Collaboration just became a whole lot easier!</span></span> <span data-ttu-id="7c7f2-1437">ドキュメントのコメント内でチームメートを @メンションできるようになりました。ドキュメントに案内するメール通知が自動的にチームメートに送られます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1437">Now you can @mention teammates in document comments and they will automatically receive an email notification drawing them into the document.</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="7c7f2-1438">Project: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1438">Project: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1439">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1439">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="7c7f2-1440">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1440">Switching between them has never been easier.</span></span> [<span data-ttu-id="7c7f2-1441">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1441">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio-feature-updates"></a><span data-ttu-id="7c7f2-1442">Visio: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1442">Visio: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1443">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1443">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="7c7f2-1444">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1444">Switching between them has never been easier.</span></span> [<span data-ttu-id="7c7f2-1445">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1445">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="7c7f2-1446">**PDF または PPT にエクスポートされた、またはメール サブスクリプションをセットアップした Power BI レポートで、Visio Visual もサポートされるようになりました:** Power BI レポートを PDF または PPT にエクスポート、またはメール サブスクリプションにセットアップした場合、Visio Visual はこれらのエクスポート先の形式でシームレスにレンダリングされます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1446">**Power BI reports exported to PDF, PPT or set up for email subscription will now feature Visio Visual as well:** If you export your Power BI reports to PDF, PPT or set up an email subscription for them, Visio Visual will render in these exported formats seamlessly.</span></span> [<span data-ttu-id="7c7f2-1447">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1447">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word-feature-updates"></a><span data-ttu-id="7c7f2-1448">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1448">Word: Feature updates</span></span>  

- <span data-ttu-id="7c7f2-1449">**コメント内で @メンションを使用してより効率的に共同作業を行う:** 共同作業がとても簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1449">**Collaborate more effectively with @Mentions in Comments:** Collaboration just became a whole lot easier!</span></span> <span data-ttu-id="7c7f2-1450">ドキュメントのコメント内でチームメートを @メンションできるようになりました。ドキュメントに案内するメール通知が自動的にチームメートに送られます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1450">Now you can @mention teammates in document comments and they will automatically receive an email notification drawing them into the document.</span></span>

- <span data-ttu-id="7c7f2-1451">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1451">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="7c7f2-1452">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1452">Switching between them has never been easier.</span></span> [<span data-ttu-id="7c7f2-1453">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1453">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="7c7f2-1454">**[学習ツール] モードで、ページで使用できる色が増えました:** Word の学習ツールでは、より多くのページ テーマ色が追加され、ページの背景色を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1454">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="7c7f2-1455">すべて白またはすべて黒の背景だと読みにくいと感じるユーザーは少なくないため、PC と Mac の Word で色の選択肢を拡大しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1455">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="7c7f2-1456">**近日公開予定:** 近日公開予定の Office に対する魅力あふれる変更点を確認してお試しいただき、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1456">**Coming Soon:** See what exciting changes are Coming Soon to Office, try them out and give us feedback.</span></span> [<span data-ttu-id="7c7f2-1457">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1457">Learn more</span></span>](https://support.office.com/article/7800e0cf0-812f-475a-80aa-d47376e076f2)

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="7c7f2-1458">Skype for Business: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1458">Skype for Business: Non-security updates</span></span>

- <span data-ttu-id="7c7f2-1459">"ユーザーに自分を知ってもらうのに役立つ、写真の追加" コンテキストのヒントを無効にするオプションを Skype for Business Online ユーザーに提供します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1459">Provides the option to Skype for Business Online users to disable the "Add your photo - it'll help people get to know you" contextual tip.</span></span> <span data-ttu-id="7c7f2-1460">この修正を有効にするには、[詳細情報](https://support.microsoft.com/help/4503469)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1460">To enable this fix, you can [Learn more](https://support.microsoft.com/help/4503469).</span></span>

- <span data-ttu-id="7c7f2-1461">Skype for Business の再起動後に、セカンダリ呼び出しの設定が常に有効になるのを防ぎます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1461">Prevents secondary ringer setting from always being enabled after restarting Skype for Business.</span></span> <span data-ttu-id="7c7f2-1462">この修正を有効にするには、[詳細情報](https://support.microsoft.com/help/4503470)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1462">To enable this fix, you can [Learn more](https://support.microsoft.com/help/4503470).</span></span>

 - <span data-ttu-id="7c7f2-1463">Lync SDK ベースのアプリケーションを使用しながら、大規模な会議に参加するときに Skype for Business の応答を停止させる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1463">Fix for an issue that made Skype for Business stop responding when joining a large meeting while also using a Lync SDK-based application.</span></span> <span data-ttu-id="7c7f2-1464">この修正を有効にするには、[詳細情報](https://support.microsoft.com/help/4503472)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1464">To enable this fix, you can [Learn more](https://support.microsoft.com/help/4503472).</span></span>

## <a name="version-1904-may-22"></a><span data-ttu-id="7c7f2-1465">バージョン 1904: 5 月 22 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1465">Version 1904: May 22</span></span>
<span data-ttu-id="7c7f2-1466">*バージョン 1904 (ビルド 11601.20230)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1466">*Version 1904 (Build 11601.20230)*</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="7c7f2-1467">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1467">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="7c7f2-1468">これにより、ユーザーがプライバシー レベルを選択して確認した後も、アプリケーションが起動される度に新しいプライバシー プロンプトが表示される問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1468">This addresses an issue where users see the new Privacy Prompt on every application launch even after selecting and committing a choice for their privacy level.</span></span>

## <a name="version-1904-may-14"></a><span data-ttu-id="7c7f2-1469">バージョン 1904: 5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1469">Version 1904: May 14</span></span> 
<span data-ttu-id="7c7f2-1470">*バージョン 1904 (ビルド 11601.20204)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1470">*Version 1904 (Build 11601.20204)*</span></span>

- <span data-ttu-id="7c7f2-1471">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1471">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-1904-may-8"></a><span data-ttu-id="7c7f2-1472">バージョン 1904: 5 月 8 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1472">Version 1904: May 8</span></span>
<span data-ttu-id="7c7f2-1473">*バージョン 1904 (ビルド 11601.20178)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1473">*Version 1904 (Build 11601.20178)*</span></span>

- <span data-ttu-id="7c7f2-1474">さまざまなバグやパフォーマンスが修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1474">Various bugs and performances fixes.</span></span>

## <a name="version-1904-april-29"></a><span data-ttu-id="7c7f2-1475">バージョン 1904: 4 月 29 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1475">Version 1904: April 29</span></span>
<span data-ttu-id="7c7f2-1476">*バージョン 1904 (ビルド 11601.20144)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1476">*Version 1904 (Build 11601.20144)*</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="7c7f2-1477">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1477">Excel: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1478">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1478">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="7c7f2-1479">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1479">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="7c7f2-1480">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1480">Outlook: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1481">**Outlook に LinkedIn ネットワークを接続する:** LinkedIn アカウントを Microsoft アカウントに安全に接続して、LinkedIn プロファイルからの情報を [連絡先カード] に直接表示できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1481">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="7c7f2-1482">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1482">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="7c7f2-1483">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1483">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1484">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1484">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="7c7f2-1485">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1485">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="7c7f2-1486">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1486">Word: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1487">**色の変更履歴、コメントとリアルタイムの共同作業の同期:** 当社の製品での、コメント、変更履歴と共同作業者のカーソルが同じ色で表示されることについての修正箇所を確認しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1487">**Colors for Track Changes, Comments and Real-Time Collaboration in Sync:** Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

- <span data-ttu-id="7c7f2-1488">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1488">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="7c7f2-1489">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1489">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="7c7f2-1490">Visio: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1490">Visio: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1491">**プロセス図を Word にエクスポート:** Word 文書に図形やメタデータなどのグラフ コンテンツを自動的に追加します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1491">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="7c7f2-1492">その後に、文書をカスタマイズしてプロセスに関するガイドラインや操作マニュアルを作成できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1492">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="7c7f2-1493">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1493">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

### <a name="office-suite-feature-updates"></a><span data-ttu-id="7c7f2-1494">Office スイート: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1494">Office Suite: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1495">**新しいアイコン:** フィードバックに基づいて、300 を超える新しいアイコンが追加されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1495">**New icons:** We've added over 300 new icons based on your feedback.</span></span> <span data-ttu-id="7c7f2-1496">[アイコン] ボタンを使用して、リボンの [挿入] タブに表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1496">You'll find them using the Icons button on the Insert tab of the ribbon.</span></span>

- <span data-ttu-id="7c7f2-1497">**プライバシー制御**: 診断データおよび関連するエクスペリエンスに関する新しく更新されて改善された制御。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1497">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="7c7f2-1498">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1498">Learn more</span></span>](/DeployOffice/privacy/overview-privacy-controls?toc=%2fdeployoffice%2ftoc.json)

### <a name="outlook-non-security-updates"></a><span data-ttu-id="7c7f2-1499">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1499">Outlook: Non-security updates</span></span>

- <span data-ttu-id="7c7f2-1500">件名が極端に小さくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1500">Fixed an issue causing the subject to show extremely small.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="7c7f2-1501">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1501">Office Suite: Non-security updates</span></span>
- <span data-ttu-id="7c7f2-1502">新時代の名前である「Reiwa」のひらがなと漢字をスペルミスまたは間違った文法として誤って識別していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1502">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="7c7f2-1503">プロキシ認証がシステムとして実行されたときに Office の更新プログラムがブロックされるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1503">Fixed an issue that blocked Office Updates when proxy authentication runs as SYSTEM.</span></span>

## <a name="version-1903-april-23"></a><span data-ttu-id="7c7f2-1504">バージョン 1903: 4 月 23 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1504">Version 1903: April 23</span></span>
<span data-ttu-id="7c7f2-1505">*バージョン 1903 (ビルド 11425.20244)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1505">*Version 1903 (Build 11425.20244)*</span></span>

- <span data-ttu-id="7c7f2-1506">さまざまなバグやパフォーマンスが修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1506">Various bugs and performances fixes.</span></span>

## <a name="version-1903-april-17"></a><span data-ttu-id="7c7f2-1507">バージョン 1903: 4 月 17 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1507">Version 1903: April 17</span></span>
<span data-ttu-id="7c7f2-1508">*バージョン 1903 (ビルド 11425.20228)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1508">*Version 1903 (Build 11425.20228)*</span></span>

- <span data-ttu-id="7c7f2-1509">さまざまなバグやパフォーマンスが修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1509">Various bugs and performances fixes.</span></span>

## <a name="version-1903-april-16"></a><span data-ttu-id="7c7f2-1510">バージョン 1903: 4 月 16 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1510">Version 1903: April 16</span></span>
<span data-ttu-id="7c7f2-1511">*バージョン 1903 (ビルド 11425.20218)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1511">*Version 1903 (Build 11425.20218)*</span></span>

- <span data-ttu-id="7c7f2-1512">さまざまなバグやパフォーマンスが修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1512">Various bugs and performances fixes.</span></span>

## <a name="version-1903-april-9"></a><span data-ttu-id="7c7f2-1513">バージョン 1903: 4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1513">Version 1903: April 9</span></span>
<span data-ttu-id="7c7f2-1514">*バージョン 1903 (ビルド 11425.20204)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1514">*Version 1903 (Build 11425.20204)*</span></span> 

- <span data-ttu-id="7c7f2-1515">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1515">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="7c7f2-1516">Skype for Business: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1516">Skype for Business: Non-security updates</span></span>
- <span data-ttu-id="7c7f2-1517">Lync (Skype for Business) で、参加者が 7 人以上のオンライン ミーティングのミーティング ウィンドウが表示されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1517">Fixed an issue in Lync (Skype for Business) where for any online meeting with more 7+ participants, the meeting window can disappear.</span></span>

## <a name="version-1903-april-01"></a><span data-ttu-id="7c7f2-1518">バージョン 1903: 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1518">Version 1903: April 01</span></span>
<span data-ttu-id="7c7f2-1519">*Version 1903 (Build 11425.20202)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1519">*Version 1903 (Build 11425.20202)*</span></span> 

### <a name="excel-feature-updates"></a><span data-ttu-id="7c7f2-1520">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1520">Excel: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1521">**Excel のインサイト:** インサイトには、ユーザーの範囲に値が用意されています。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1521">**Insights in Excel:** Insights provides value to a range of users.</span></span> <span data-ttu-id="7c7f2-1522">インサイトは、データ分析にソフトなアプローチを提供し、データに他からの違う視点を提供します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1522">Insights provides a softer approach to data analysis and for others it provides a different perspective to your data.</span></span> [<span data-ttu-id="7c7f2-1523">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1523">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)


- <span data-ttu-id="7c7f2-1524">**コンテンツのリーチを拡大:** アクセシビリティの高いスプレッドシートを作成する必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1524">**Increase the reach of your content:**  Need to make your spreadsheets accessible?</span></span> <span data-ttu-id="7c7f2-1525">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1525">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="7c7f2-1526">[校閲] > [アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1526">Try it by clicking Review > Check Accessibility and we’ll tell you when we find something you need to look at in the status bar.</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="7c7f2-1527">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1527">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1528">**よりよい変形操作:** 図形に名前を付けると、変形するときにより細かく制御できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1528">**Better shapeshifting:**  Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="7c7f2-1529">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1529">Learn more</span></span>](https://support.office.com/article/9bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="7c7f2-1530">**コンテンツのリーチを拡大:** アクセシビリティの高いプレゼンテーションを作成する必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1530">**Increase the reach of your content:**  Need to make your presentations accessible?</span></span> <span data-ttu-id="7c7f2-1531">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1531">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="7c7f2-1532">[校閲]>[アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1532">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="7c7f2-1533">**再利用できる場合、新たに作成し直しますか?**</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1533">**Why reinvent when you can re-use?**</span></span>  <span data-ttu-id="7c7f2-1534">作成した、または他のユーザーと共有しているスライドを再利用して時間を節約します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1534">Save time by re-using slides that you created or that others have shared with you.</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="7c7f2-1535">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1535">Excel: Non-security updates</span></span>

- <span data-ttu-id="7c7f2-1536">Excel では、ユーザーが変更を取得するためにブックを再び開くよう要求される結果となるマージ競合の問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1536">Fixed a merge conflict issue in Excel  that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="7c7f2-1537">Skype for Business: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1537">Skype for Business: Non-security updates</span></span>

- <span data-ttu-id="7c7f2-1538">サード パーティの SfB/Lync SDK アプリが存在する場合に、Skype for Business のチャット通知への応答が停止される原因となった問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1538">Fix for issue that caused Skype for Business to stop responding when responding to chat notifications if 3rd party SfB/Lync SDK app present.</span></span>
- <span data-ttu-id="7c7f2-1539">チャットに特定のクリップボードの内容を貼り付けるときにアプリがクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1539">Fix for app crash when specific clipboard content is pasted into a chat.</span></span>
- <span data-ttu-id="7c7f2-1540">いずれかの通話エージェントが受信した呼び出しキューの呼び出しの "受け入れ担当者" 情報が表示されるのを妨げている問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1540">Fix for issue that prevented display of the "accepted by" information for a Call Queue call that's picked up by one of the call agents.</span></span>
- <span data-ttu-id="7c7f2-1541">Teams のユーザーが Skype for Business 会議に参加したときに通話アイコンが非表示になる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1541">Fixed issue that hid call icons when a Teams user joins a Skype for Business meeting.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="7c7f2-1542">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1542">Word: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1543">**コンテンツのリーチを拡大:** アクセシビリティの高いドキュメントを作成する必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1543">**Increase the reach of your content:**  Need to make your documents accessible?</span></span> <span data-ttu-id="7c7f2-1544">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1544">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="7c7f2-1545">[校閲]>[アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1545">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

## <a name="version-1902-march-25"></a><span data-ttu-id="7c7f2-1546">バージョン 1902: 3 月 25 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1546">Version 1902: March 25</span></span>
<span data-ttu-id="7c7f2-1547">*バージョン 1902 (ビルド 11328.20222)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1547">*Version 1902 (Build 11328.20222)*</span></span>

- <span data-ttu-id="7c7f2-1548">さまざまなバグやパフォーマンスが修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1548">Various bugs and performances fixes.</span></span>

## <a name="version-1902-march-12"></a><span data-ttu-id="7c7f2-1549">バージョン 1902: 3 月 12 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1549">Version 1902: March 12</span></span>
<span data-ttu-id="7c7f2-1550">*バージョン 1902 (ビルド 11328.20158)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1550">*Version 1902 (Build 11328.20158)*</span></span> 

- <span data-ttu-id="7c7f2-1551">さまざまなバグやパフォーマンスが修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1551">Various bugs and performances fixes.</span></span>

## <a name="version-1902-march-4"></a><span data-ttu-id="7c7f2-1552">バージョン 1902: 3 月 4 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1552">Version 1902: March 4</span></span>
<span data-ttu-id="7c7f2-1553">*バージョン 1902 (ビルド 11328.20146)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1553">*Version 1902 (Build 11328.20146)*</span></span> 

### <a name="access-feature-updates"></a><span data-ttu-id="7c7f2-1554">Access: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1554">Access: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1555">**データベース オブジェクトをタブで管理する:** アクティブなタブが分かりやすく表示され、簡単にタブをドラッグして再配置し、ワンクリックでデータベース オブジェクトを閉じることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1555">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>
- <span data-ttu-id="7c7f2-1556">**より大きい [ズーム] ボックス:** [ズーム] ボックスがより大きく表示され、そこでフォントを変更することができます。変更内容はすべて [ズーム] ボックス内に記憶されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1556">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="7c7f2-1557">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1557">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel-feature-updates"></a><span data-ttu-id="7c7f2-1558">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1558">Excel: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1559">**\@メンションを使用してユーザーの注意を引く:** コメントで @メンションを使うと、仕事仲間による入力が必要な場合にそのユーザーに知らせることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1559">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="7c7f2-1560">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1560">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)
- <span data-ttu-id="7c7f2-1561">**データの詳細を検出する:** 新しいアイデア ボタンは、データのパターンを探し、それを使用してインテリジェントな個人向けの提案を作成します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1561">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions.</span></span> [<span data-ttu-id="7c7f2-1562">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1562">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)
- <span data-ttu-id="7c7f2-1563">**変更が発生したときに変更内容を自動的に保存する:** 変更が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1563">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>
- <span data-ttu-id="7c7f2-1564">**フィルターが適用された SVG を挿入する機能:** Office ユーザーは、フィルターが適用された SVG を挿入できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1564">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them.</span></span> [<span data-ttu-id="7c7f2-1565">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1565">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook-feature-updates"></a><span data-ttu-id="7c7f2-1566">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1566">Outlook: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1567">**連続する会議の合間に時間を組み込む:** 既定で 5 分から 10 分早く会議を終了するように設定することで、出席者に休憩時間や場所の移動時間を与えることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1567">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span> [<span data-ttu-id="7c7f2-1568">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1568">Learn more</span></span>](https://support.office.com/article/Schedule-a-meeting-with-other-people-5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F#BKMK_endmeetingsearly)
- <span data-ttu-id="7c7f2-1569">**音声読み上げを使用してメールの内容を聞く:** Outlook では、メールのテキストを読み上げながら強調表示することができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1569">**Use Read Aloud to listen to your email:** Outlook can read your email aloud, highlighting text as it's read.</span></span> <span data-ttu-id="7c7f2-1570">読み上げ機能をオンにするには、[簡単操作] の設定に移動します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1570">To turn on Read Aloud, go to the Ease of Access settings.</span></span> [<span data-ttu-id="7c7f2-1571">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1571">Learn more</span></span>](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)
- <span data-ttu-id="7c7f2-1572">**フィルターが適用された SVG を挿入する機能:** Office ユーザーは、フィルターが適用された SVG を挿入できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1572">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them.</span></span> [<span data-ttu-id="7c7f2-1573">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1573">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="7c7f2-1574">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1574">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1575">**これまで以上に簡単にオンライン ビデオを挿入できるようになりました:** Vimeo または YouTube からビデオをスライドに挿入する場合は、</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1575">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide?</span></span> <span data-ttu-id="7c7f2-1576">ビデオ ページへのリンクがあれば簡単に行えます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1576">The video page link is all you need.</span></span> [<span data-ttu-id="7c7f2-1577">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1577">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)
- <span data-ttu-id="7c7f2-1578">**手書きの数式の自動書式設定:** 手書きの数式を標準の文字に変換することができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1578">**You compute, we format:** We change hand-drawn math expressions into standard characters.</span></span> <span data-ttu-id="7c7f2-1579">変換を開始するには、[インクから数式] を選択して、手書きのメモを選択します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1579">Just choose Ink to Math and select your handwritten notes to get started.</span></span> [<span data-ttu-id="7c7f2-1580">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1580">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- <span data-ttu-id="7c7f2-1581">**変更が発生したときに変更内容を自動的に保存する:** 変更が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1581">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>
- <span data-ttu-id="7c7f2-1582">**フィルターが適用された SVG を挿入する機能:** Office ユーザーは、フィルターが適用された SVG を挿入できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1582">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them.</span></span> [<span data-ttu-id="7c7f2-1583">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1583">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- <span data-ttu-id="7c7f2-1584">**大きなファイルがより速く開くようになりました:** OneDrive または SharePoint に保存されているファイルを開くと、画像、ビデオ、およびその他の大きな要素がバックグラウンドでダウンロードされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1584">**Large files now open faster:** Images, videos, and other large elements now download in the background when opening files stored on OneDrive or SharePoint.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="7c7f2-1585">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1585">Word: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1586">**変更が発生したときに変更内容を自動的に保存する:** 変更が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1586">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>
- <span data-ttu-id="7c7f2-1587">**自動保存がオンになっていない理由を確認する**</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1587">**Find out why AutoSave isn't on!**</span></span> <span data-ttu-id="7c7f2-1588">自動保存がオフになっているときに自動保存トグルをクリックすると、吹き出しが表示されるようになりました。自動保存がオフになっている理由も示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1588">Clicking on the AutoSave toggle when it's off will now either display a helpful callout with reasons why AutoSave might be off.</span></span> <span data-ttu-id="7c7f2-1589">ドキュメントが OneDrive または SharePoint 上に存在しないという理由で自動保存ができない場合でも、1 つのボタンをクリックするだけでドキュメントを移動することができるようになります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1589">In the case where the only reason preventing AutoSave is the fact that the document is not on OneDrive or SharePoint, we will offer to move the document conveniently with one button click!</span></span>
- <span data-ttu-id="7c7f2-1590">**フィルターが適用された SVG を挿入する機能:** Office ユーザーは、フィルターが適用された SVG を挿入できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1590">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them.</span></span> [<span data-ttu-id="7c7f2-1591">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1591">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
 
### <a name="office-suite-feature-updates"></a><span data-ttu-id="7c7f2-1592">Office スイート: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1592">Office Suite: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1593">**Microsoft Teams のインストール:** Microsoft Teams は、Office 365 ProPlus の新規インストール用に既定でインストールされています。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1593">**Installation of Microsoft Teams:**  Microsoft Teams is installed by default for new installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="7c7f2-1594">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1594">Learn More</span></span>](/DeployOffice/teams-install)

## <a name="version-1901-february-12"></a><span data-ttu-id="7c7f2-1595">バージョン 1901: 2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1595">Version 1901: February 12</span></span>
<span data-ttu-id="7c7f2-1596">*バージョン 1901 (ビルド 11231.20174)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1596">*Version 1901 (Build 11231.20174)*</span></span> 

<span data-ttu-id="7c7f2-1597">セキュリティ更新プログラムの一覧は[こちら](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1597">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>

## <a name="version-1901-january-31"></a><span data-ttu-id="7c7f2-1598">バージョン 1901: 1 月 31 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1598">Version 1901: January 31</span></span>
<span data-ttu-id="7c7f2-1599">*バージョン 1901 (ビルド 11231.20130)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1599">*Version 1901 (Build 11231.20130)*</span></span> 

### <a name="excel-feature-updates"></a><span data-ttu-id="7c7f2-1600">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1600">Excel: Feature updates</span></span>

- <span data-ttu-id="7c7f2-p290">**コメントを利用して共同作業を行う:** 返信ボックスが組み込まれているので、スプレッドシートで直接会話を続けることができます。[詳細情報](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p290">**Collaborate with comments:** Keep the conversation going right in your spreadsheet with the built-in reply box. [Learn more](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="7c7f2-1603">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1603">Outlook: Feature updates</span></span>

- <span data-ttu-id="7c7f2-p291">**ミームが表示される:** テキストまたは静的イメージだけでは十分ではない場合、アニメーション GIF を使用して要点を示すことができます。[詳細情報](https://support.office.com/article/114BB251-861F-41CD-B20F-7E7289630C5B)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p291">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114BB251-861F-41CD-B20F-7E7289630C5B)</span></span>
 
### <a name="visio-feature-updates"></a><span data-ttu-id="7c7f2-1606">Visio: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1606">Visio: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1607">**ダブル テイク オン データ フローチャート:** データ ビジュアライザーのフローチャート用の新しいレイアウトは、きれいで鮮明でとても分かりやすいです。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1607">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> [<span data-ttu-id="7c7f2-1608">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1608">Learn more</span></span>](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)

- <span data-ttu-id="7c7f2-1609">**Azure ステンシルが組み込まれました:** 豊富な Azure ステンシルを使用してクラウド アプリの設計やアーキテクチャの計画を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1609">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="7c7f2-1610">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1610">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word-feature-updates"></a><span data-ttu-id="7c7f2-1611">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1611">Word: Feature updates</span></span>

- <span data-ttu-id="7c7f2-p294">**静的なドキュメントから魅力的なドキュメントへの変換:** ドキュメントを、すべてのデバイスに対応する対話型の使いやすい Web ページに変換します。[詳細情報](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p294">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

### <a name="office-suite-feature-updates"></a><span data-ttu-id="7c7f2-1614">Office スイート: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1614">Office Suite: Feature updates</span></span>

- <span data-ttu-id="7c7f2-p295">**Office のサード パーティ アプリケーションでは office.js api を使用した SVG の挿入をサポート:** Office アドインとも呼ばれるサード パーティ アプリケーションで SVG を挿入できるようになりました。ユーザーは、個人の SVG コレクションを Office に結び付けることができます。開発者は、Office.js API を使用してこの機能を利用できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p295">**Office 3rd Party Applications now have insert SVG support using the office.js api:** 3rd party applications also known as add-ins in Office now have the ability to insert SVG's. Users can now connect their personal collection of SVG's to Office. Developers can use this feature by using the Office.js API.</span></span>


## <a name="version-1812-january-14"></a><span data-ttu-id="7c7f2-1618">バージョン 1812: 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1618">Version 1812: January 14</span></span>
<span data-ttu-id="7c7f2-1619">*バージョン 1812 (ビルド 11126.20266)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1619">*Version 1812 (Build 11126.20266)*</span></span> 

<span data-ttu-id="7c7f2-1620">パフォーマンス上の問題に対処するセキュリティ関連ではない更新プログラムのみ。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1620">Non-security updates only, addressing performance issues.</span></span>

## <a name="version-1812-january-8"></a><span data-ttu-id="7c7f2-1621">バージョン 1812: 1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1621">Version 1812: January 8</span></span>
<span data-ttu-id="7c7f2-1622">*バージョン 1812 (ビルド 11126.20196)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1622">*Version 1812 (Build 11126.20196)*</span></span> 

### <a name="project-non-security-updates"></a><span data-ttu-id="7c7f2-1623">Project: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1623">Project: Non-security updates</span></span>
- <span data-ttu-id="7c7f2-1624">ガント チャートの [クリティカル]、[遅延]、[余裕期間] バー スタイルをオンにした後でオフにできない問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1624">Fixed an issue where you couldn't uncheck the Critical, Late and Slack bar styles for the Gantt chart after you checked one.</span></span>

## <a name="version-1812-january-3"></a><span data-ttu-id="7c7f2-1625">バージョン 1812: 1 月 3 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1625">Version 1812: January 3</span></span>
<span data-ttu-id="7c7f2-1626">*バージョン 1812 (ビルド 11126.20188)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1626">*Version 1812 (Build 11126.20188)*</span></span> 

### <a name="excel-feature-updates"></a><span data-ttu-id="7c7f2-1627">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1627">Excel: Feature updates</span></span>

- <span data-ttu-id="7c7f2-p296">**作業中にアクセシビリティ チェックを実行したままにする:** アクセシビリティ チェックを常に開いたままにしなくても、ドキュメントのアクセシビリティの問題を追跡できます。スペルチェックの場合のように、ステータス バーのインジケーターを介して、作業中に見つかったアクセシビリティの問題に Excel が自動的にフラグを付けます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p296">**Keep accessibility checker running while you work:** Keep track of accessibility issues in your document without needing the accessibility checker always open. Via an indicator in the status bar, much like spellcheck, Excel flags found accessibility issues while you are working.</span></span> 

### <a name="outlook-feature-updates"></a><span data-ttu-id="7c7f2-1630">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1630">Outlook: Feature updates</span></span>

- <span data-ttu-id="7c7f2-p297">**すべての暗号化オプションを 1 か所に集約:** [オプション] > [暗号化] の順に移動するだけで、電子メール メッセージを保護する方法を選択できます。[詳細情報](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p297">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="7c7f2-1633">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1633">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="7c7f2-p298">**インクで素晴らしいスライドを作成:** インクを標準的な図形とテキストに変換し、PowerPoint デザイナーからスマートなスライド デザイン アイデアを入手します。[詳細情報](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p298">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer. [Learn more](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)</span></span>
- <span data-ttu-id="7c7f2-p299">**作業中にアクセシビリティ チェックを実行したままにする:** アクセシビリティ チェックを常に開いたままにしなくても、ドキュメントのアクセシビリティの問題を追跡できます。スペルチェックの場合のように、ステータス バーのインジケーターを介して、作業中に見つかったアクセシビリティの問題に PowerPoint が自動的にフラグを付けます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p299">**Keep accessibility checker running while you work:** Keep track of accessibility issues in your document without needing the accessibility checker always open. Via an indicator in the status bar, much like spellcheck, PowerPoint flags found accessibility issues while you are working.</span></span> 

### <a name="word-feature-updates"></a><span data-ttu-id="7c7f2-1638">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1638">Word: Feature updates</span></span>

- <span data-ttu-id="7c7f2-p300">**行フォーカスによる読解力の向上:** ドキュメント内で行ごとの移動をスムーズに行います。一度に 1 行か、3 行か、5 行かを表示するようフォーカスを調整できます。[詳細情報](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p300">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>
- <span data-ttu-id="7c7f2-p301">**作業中にアクセシビリティ チェックを実行したままにする:** アクセシビリティ チェックを常に開いたままにしなくても、ドキュメントのアクセシビリティの問題を追跡できます。スペルチェックの場合のように、ステータス バーのインジケーターを介して、作業中に見つかったアクセシビリティの問題に Word が自動的にフラグを付けます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p301">**Keep accessibility checker running while you work:** Keep track of accessibility issues in your document without needing the accessibility checker always open. Via an indicator in the status bar, much like spellcheck, Word flags found accessibility issues while you are working.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="7c7f2-1644">Visio: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1644">Visio: Feature updates</span></span>

- <span data-ttu-id="7c7f2-p302">**壊れた Excel リンクの問題を解消:** データ ビジュアライザーの図にリンクされているはずの Excel ブックが見つかりませんか? 再リンクして、すぐに業務を再開できます。[詳細情報](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p302">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

### <a name="office-suite-feature-updates"></a><span data-ttu-id="7c7f2-1648">Office スイート: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1648">Office Suite: Feature updates</span></span>

- <span data-ttu-id="7c7f2-1649">**[新機能] ウィンドウ:** [新機能] はヘルプ ウィンドウに移行しました。そのため、最新の更新プログラムにより簡単にアクセスして最新情報を入手できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1649">**What's New Pane:** The What's New experience has moved to the Help Pane, so you can more easily access and stay up to date with our latest updates.</span></span>

## <a name="version-1811-december-11"></a><span data-ttu-id="7c7f2-1650">バージョン 1811: 12 月 11 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1650">Version 1811: December 11</span></span>
<span data-ttu-id="7c7f2-1651">*バージョン 1811 (ビルド 11029.20108)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1651">*Version 1811 (Build 11029.20108)*</span></span> 

 ### <a name="excel-security-updates"></a><span data-ttu-id="7c7f2-1652">Excel: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1652">Excel: Security updates</span></span> 

-   <span data-ttu-id="7c7f2-1653">[CVE-2018-8597](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8597): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1653">[CVE-2018-8597](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8597): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="7c7f2-1654">[CVE-2018-8598](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8598): Microsoft Excel の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1654">[CVE-2018-8598](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8598): Microsoft Excel Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="7c7f2-1655">[CVE-2018-8627](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8627): Microsoft Excel の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1655">[CVE-2018-8627](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8627): Microsoft Excel Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="7c7f2-1656">[CVE-2018-8636](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8636): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1656">[CVE-2018-8636](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8636): Microsoft Excel Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="7c7f2-1657">Outlook: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1657">Outlook: Security updates</span></span> 

-   <span data-ttu-id="7c7f2-1658">[CVE-2018-8587](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8587): Microsoft Outlook のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1658">[CVE-2018-8587](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8587): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 

### <a name="powerpoint-security-updates"></a><span data-ttu-id="7c7f2-1659">PowerPoint: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1659">PowerPoint: Security updates</span></span> 

-   <span data-ttu-id="7c7f2-1660">[CVE-2018-8628](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8628): Microsoft PowerPoint のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1660">[CVE-2018-8628](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8628): Microsoft PowerPoint Remote Code Execution Vulnerability</span></span> 


## <a name="version-1811-november-27"></a><span data-ttu-id="7c7f2-1661">バージョン 1811: 11 月 27 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1661">Version 1811: November 27</span></span>
<span data-ttu-id="7c7f2-1662">*バージョン 1811 (ビルド 11029.20079)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1662">*Version 1811 (Build 11029.20079)*</span></span> 

### <a name="access-feature-updates"></a><span data-ttu-id="7c7f2-1663">Access: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1663">Access: Feature updates</span></span>

- <span data-ttu-id="7c7f2-p303">**黒にペイントする、灰色にペイントする:** アクセスの外観を好きなだけ変更します。次の 4 つのテーマを選択: カラフル、濃い灰色、黒、白のいずれか。[詳細情報](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p303">**Paint it black, paint it gray:** Change the look of Access as often as you like. Four themes to choose from: Colorful, Dark Gray, Black, or White. [Learn more](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="7c7f2-1667">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1667">Outlook: Feature updates</span></span>

- <span data-ttu-id="7c7f2-p304">**ズームとスティック:** メッセージを読むたびにズームを調整するのではなく、すべてのメッセージに使用する既定値を選択します。[詳細情報](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p304">**Zoom and stick:** Instead of adjusting Zoom each time you read a message, choose a default to use for all your messages.  [Learn more](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)</span></span>
- <span data-ttu-id="7c7f2-1670">**メッセージの移動中も作業が可能:** Outlook では、メッセージの移動がバックグラウンドで行われるようになったため、フォルダ間で多数のメッセージの移動が行われている間も作業を続けることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1670">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>
- <span data-ttu-id="7c7f2-p305">**優先受信トレイのオン時とオフ時の操作の改良:** 優先受信トレイを使用していないユーザー向けに、[未開封] タブを全フォルダーのメッセージ一覧に復活させました。また、フラグが設定されたアイテムを簡単に見つけ出すために、フラグ別に並べ替える機能も追加しました。さらに、優先受信トレイの検索機能に、より使いやすい対話式モデルを採用しました。優先受信トレイはユーザーが検索を開始するまで表示されたままとなり、[結果] テキストは検索が完了した後に表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p305">**Polished the Focused Inbox on and off experiences:** For customers that do not use Focused Inbox, we brought back the Unread tab in the message list across all folders. We also added a sort by Flag to make it easier to find flagged items. Finally, Focused Inbox has a better interaction model with search: Focused Inbox remains until a user starts to search and we show 'Results' text shown after a search completes.</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="7c7f2-1674">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1674">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="7c7f2-p306">**印刷された配布資料のスライド番号を参照してください:** スライド番号を配布資料の印刷コピーに追加します。[詳細情報](https://support.office.com/article/91c62c83-9032-497c-ab76-cae8f3e1a402)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p306">**See slide number on printed handouts:** Add slide number to the print copy of your handouts. [Learn more](https://support.office.com/article/91c62c83-9032-497c-ab76-cae8f3e1a402)</span></span>

### <a name="office-suite-feature-updates"></a><span data-ttu-id="7c7f2-1677">Office スイート: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1677">Office Suite: Feature updates</span></span>

- <span data-ttu-id="7c7f2-p307">**情報バーに新しく表示されたボタンを使用して、ドキュメントを共有し、アップロードします:** 以前は、[共有]、[クリップボードへのパスのコピー]、[ファイルの場所を開く] ボタンは、ドキュメント保存パスの後ろからしかアクセスできませんでした。これらのボタンは情報バーに明確に表示されるようになりました。通常は、[ファイル] > [情報] の順に移動すると、これらの新しいボタンを表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p307">**Share and upload your documents with the new exposed buttons in the Info Place:** Previously Share, Copy Path to Clipboard, and Open File Location buttons were only accessible behind the document save path. Now they're buttons you can clearly see in the Info Place! Navigate to File > Info as you normally would to see these new buttons.</span></span>


## <a name="version-1810-november-13"></a><span data-ttu-id="7c7f2-1681">バージョン 1810: 11 月 13 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1681">Version 1810: November 13</span></span>
<span data-ttu-id="7c7f2-1682">*バージョン 1810 (ビルド 11001.20108)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1682">*Version 1810 (Build 11001.20108)*</span></span> 

### <a name="excel-security-updates"></a><span data-ttu-id="7c7f2-1683">Excel: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1683">Excel: Security updates</span></span>

-   <span data-ttu-id="7c7f2-1684">[CVE-2018-8574](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8574): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1684">[CVE-2018-8574](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8574): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="7c7f2-1685">[CVE-2018-8577](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8577): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1685">[CVE-2018-8577](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8577): Microsoft Excel Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="7c7f2-1686">Outlook: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1686">Outlook: Security updates</span></span> 

-   <span data-ttu-id="7c7f2-1687">[CVE-2018-8522](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8522): Microsoft Outlook のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1687">[CVE-2018-8522](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8522): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="7c7f2-1688">[CVE-2018-8524](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8524): Microsoft Outlook のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1688">[CVE-2018-8524](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8524): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="7c7f2-1689">[CVE-2018-8558](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8558): Microsoft Outlook の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1689">[CVE-2018-8558](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8558): Microsoft Outlook Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="7c7f2-1690">[CVE-2018-8576](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8576): Microsoft Outlook のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1690">[CVE-2018-8576](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8576): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="7c7f2-1691">[CVE-2018-8579](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8579): Microsoft Outlook の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1691">[CVE-2018-8579](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8579): Microsoft Outlook Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="7c7f2-1692">[CVE-2018-8582](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8582): Microsoft Outlook のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1692">[CVE-2018-8582](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8582): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 

### <a name="project-security-updates"></a><span data-ttu-id="7c7f2-1693">Project: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1693">Project: Security updates</span></span> 

-   <span data-ttu-id="7c7f2-1694">[CVE-2018-8575](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8575): Microsoft Project のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1694">[CVE-2018-8575](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8575): Microsoft Project Remote Code Execution Vulnerability</span></span> 

### <a name="word-security-updates"></a><span data-ttu-id="7c7f2-1695">Word: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1695">Word: Security updates</span></span>  

-   <span data-ttu-id="7c7f2-1696">[CVE-2018-8573](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8573): Microsoft Word のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1696">[CVE-2018-8573](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8573): Microsoft Word Remote Code Execution Vulnerability</span></span> 

### <a name="skype-for-business-security-updates"></a><span data-ttu-id="7c7f2-1697">Skype for Business: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1697">Skype for Business: Security updates</span></span> 

-   <span data-ttu-id="7c7f2-1698">[CVE-2018-8546](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8546): Microsoft Skype for Business のサービス拒否攻撃の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1698">[CVE-2018-8546](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8546): Microsoft Skype for Business Denial of Service Vulnerability</span></span> 

 ### <a name="project-non-security-updates"></a><span data-ttu-id="7c7f2-1699">Project: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1699">Project: Non-security Updates</span></span>

 - <span data-ttu-id="7c7f2-1700">Project Online にプロジェクトを保存/発行したときにステータス バーが最新の状態表示に更新されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1700">Fixed an issue where when saving/publishing a project to Project Online, the status bar was not always updating to show the latest status.</span></span>
 - <span data-ttu-id="7c7f2-1701">新しい先進エクスペリエンスで SharePoint ドキュメント ライブラリ上の Project ファイルの作業を行っている場合、チェックアウトが必要操作および読み取り専用操作に正しく従っていなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1701">Fixed an issue where if you were working with Project files on a SharePoint document library that was in the new modern experience, the Check-Out Required and Read-Only actions were not being correctly followed.</span></span>


## <a name="version-1810-october-29"></a><span data-ttu-id="7c7f2-1702">バージョン 1810: 10 月 29 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1702">Version 1810: October 29</span></span>
<span data-ttu-id="7c7f2-1703">*バージョン 1810 (ビルド 11001.20074)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1703">*Version 1810 (Build 11001.20074)*</span></span> 

### <a name="excel-feature-updates"></a><span data-ttu-id="7c7f2-1704">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1704">Excel: Feature updates</span></span> 

- <span data-ttu-id="7c7f2-p308">**コメントを利用して共同作業を行う:** 返信ボックスが組み込まれているので、スプレッドシートで直接会話を続けることができます。[詳細情報](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p308">**Collaborate with comments:** Keep the conversation going right in your spreadsheet with the built-in reply box. [Learn more](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)</span></span>
- <span data-ttu-id="7c7f2-p309">**株価情報をすぐに確認できる:** 新しい株価のデータ型で、最新の株価、価格の変動などを取得します。新しい地理のデータ型も利用することができます。[詳細情報](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p309">**Stock quotes at your fingertips:** Retrieve the latest stock price, change in price, and more with the new Stocks data type. There's a new data type for Geography too. [Learn more](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)</span></span>
- <span data-ttu-id="7c7f2-p310">**画像の背後を見えるようにする:** ワークシートに画像を挿入し、既定の設定から選択して、透明度の変化を確認するだけです。[詳細情報](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p310">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="7c7f2-p311">**数式バーでの編集が簡単に:** Ctrl + A キーを使用して、セル内または数式バーのテキストを選択できるようになりました。絵文字とその他の複雑な文字のサポートも改善されています。[詳細情報](https://support.office.com/article/402d8c2a-354c-4690-bacf-1c319c4ec2fb)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p311">**Easy editing in the formula bar:** You can now use CTRL+A to select text in a cell or the formula bar. There's also improved support for emojis and other complex characters. [Learn more](https://support.office.com/article/402d8c2a-354c-4690-bacf-1c319c4ec2fb)</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="7c7f2-1716">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1716">Outlook: Feature updates</span></span> 

- <span data-ttu-id="7c7f2-p312">**スケジュール アシスタントでの候補ユーザーの表示:** 会議のスケジュールを設定するときに、追加する出席者の候補が表示されます。スケジュール アシスタントと [宛先] 行を何度も切り替える必要はありません。[詳細情報](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p312">**People suggestions in the Scheduling Assistant:** See recommendations for attendees to add when you schedule a meeting. No more switching back and forth between the Scheduling Assistant and the To line. [Learn more](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)</span></span>
- <span data-ttu-id="7c7f2-1720">**会議室の予約がさらに簡単に:** 複数の会議室のリストを使用して、会議室を検索します。選択した会議室を失うことなく、リストを切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1720">**Reserving a room just got easier:** Look for a conference room using more than one room list - and switch lists without losing rooms you've selected.</span></span>
- <span data-ttu-id="7c7f2-p313">**過去のイベントのリマインダーの表示を停止:** 終了したイベントのリマインダーを自動的に破棄するようにカレンダーを設定することができます。[詳細情報](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p313">**Stop seeing reminders for past events:** You can set your calendar to automatically dismiss reminders for events after they've ended. [Learn more](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="7c7f2-1723">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1723">PowerPoint: Feature updates</span></span> 

- <span data-ttu-id="7c7f2-p314">**画像の背後を見えるようにする:** スライドに画像を挿入し、既定の設定から選択して、透明度の変化を確認するだけです。[詳細情報](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p314">**Reveal what's behind a picture:** Put a picture on a slide,  pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="7c7f2-p315">**新しい文書校正ツール:** 記述する内容についてストレスを感じる必要はありません。PowerPoint で、文法や書き方の推奨事項が提示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p315">**New proofreading tools:** Don't stress about your words. PowerPoint now provides grammar and writing suggestions.</span></span>
- <span data-ttu-id="7c7f2-p316">**スケッチするだけで自動的に洗練される:** 手書きのテキストや図形が洗練された図表に変更されます。インク ストロークを選ぶだけで機能を利用できます。[詳細情報](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p316">**You sketch, we polish:** We change hand-drawn text and shapes into refined diagrams. Just select your ink strokes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="7c7f2-1732">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1732">Word: Feature updates</span></span> 

- <span data-ttu-id="7c7f2-p317">**画像の背後を見えるようにする:** 文書に画像を挿入し、既定の設定から選択して、透明度の変化を確認するだけです。[詳細情報](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p317">**Reveal what's behind a picture:** Put a picture in a document,  pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="7c7f2-p318">**文書を活気づかせる:** アニメーション 3D グラフィックスを挿入して、鼓動する心臓、周回する惑星、暴れ回るティラノサウルスをページ上に表示できます。[詳細情報](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p318">**Watch your documents come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage across the page. [Learn more](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span></span>

### <a name="access-feature-updates"></a><span data-ttu-id="7c7f2-1738">Access: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1738">Access: Feature updates</span></span> 
- <span data-ttu-id="7c7f2-p319">**新しい見た目のリボン アイコン:** 機能に変化はないので、心配はいりません。さらに、どのサイズの画面でも、見た目がきれいです。[詳細情報](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p319">**Your ribbon icons have a new look** Don’t worry, everything works the same. Plus, they look great on screens of all sizes. [Learn more](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span></span>

### <a name="publisher-feature-updates"></a><span data-ttu-id="7c7f2-1742">Publisher: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1742">Publisher: Feature updates</span></span> 
- <span data-ttu-id="7c7f2-p320">**新しい見た目のリボン アイコン:** 機能に変化はないので、心配はいりません。さらに、どのサイズの画面でも、見た目がきれいです。[詳細情報](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p320">**Your ribbon icons have a new look** Don’t worry, everything works the same. Plus, they look great on screens of all sizes. [Learn more](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="7c7f2-1746">Project: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1746">Project: Feature updates</span></span> 
- <span data-ttu-id="7c7f2-p321">**新しい見た目のリボン アイコン:** 機能に変化はないので、心配はいりません。さらに、どのサイズの画面でも、見た目がきれいです。[詳細情報](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p321">**Your ribbon icons have a new look** Don’t worry, everything works the same. Plus, they look great on screens of all sizes. [Learn more](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="7c7f2-1750">Visio: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1750">Visio: Feature updates</span></span> 
- <span data-ttu-id="7c7f2-p322">**新しい見た目のリボン アイコン:** 機能に変化はないので、心配はいりません。さらに、どのサイズの画面でも、見た目がきれいです。[詳細情報](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p322">**Your ribbon icons have a new look** Don’t worry, everything works the same. Plus, they look great on screens of all sizes. [Learn more](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span></span>


## <a name="version-1809-october-16"></a><span data-ttu-id="7c7f2-1754">バージョン 1809: 10 月 16 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1754">Version 1809: October 16</span></span>
<span data-ttu-id="7c7f2-1755">*バージョン 1809 (ビルド 10827.20181)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1755">*Version 1809 (Build 10827.20181)*</span></span> 

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="7c7f2-1756">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1756">Office suite: Non-Security updates</span></span> 
-  <span data-ttu-id="7c7f2-1757">さまざまなパフォーマンスの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1757">Fixed various performance issues.</span></span>


## <a name="version-1809-october-9"></a><span data-ttu-id="7c7f2-1758">バージョン 1809: 10 月 9 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1758">Version 1809: October 9</span></span>
<span data-ttu-id="7c7f2-1759">*バージョン 1809 (ビルド 10827.20150)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1759">*Version 1809 (Build 10827.20150)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="7c7f2-1760">Excel: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1760">Excel: Security updates</span></span>
-   <span data-ttu-id="7c7f2-1761">[CVE-2018-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8502): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1761">[CVE-2018-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8502): Microsoft Excel Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="7c7f2-1762">Outlook: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1762">Outlook: Security updates</span></span> 
-   <span data-ttu-id="7c7f2-1763">[ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026): Microsoft Office の高度な防御の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1763">[ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026): Microsoft Office Defense in Depth Update</span></span> 

### <a name="powerpoint-security-updates"></a><span data-ttu-id="7c7f2-1764">PowerPoint: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1764">PowerPoint: Security updates</span></span> 
-   <span data-ttu-id="7c7f2-1765">[CVE-2018-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8501): Microsoft PowerPoint のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1765">[CVE-2018-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8501): Microsoft PowerPoint Remote Code Execution Vulnerability</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="7c7f2-1766">Word: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1766">Word: Security updates</span></span> 
-   <span data-ttu-id="7c7f2-1767">[CVE-2018-8504](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8504): Microsoft Word のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1767">[CVE-2018-8504](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8504): Microsoft Word Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="7c7f2-1768">[ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026): Microsoft Office の高度な防御の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1768">[ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026): Microsoft Office Defense in Depth Update</span></span> 

### <a name="office-suite-security-updates"></a><span data-ttu-id="7c7f2-1769">Office スイート: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1769">Office suite: Security updates</span></span> 
-   <span data-ttu-id="7c7f2-1770">[CVE-2018-8432](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8432): Microsoft グラフィック コンポーネントのリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1770">[CVE-2018-8432](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8432): Microsoft Graphics Components Remote Code Execution Vulnerability</span></span> 


## <a name="version-1809-september-27"></a><span data-ttu-id="7c7f2-1771">バージョン 1809: 9 月 27 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1771">Version 1809: September 27</span></span>
<span data-ttu-id="7c7f2-1772">*バージョン 1809 (ビルド 10827.20138)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1772">*Version 1809 (Build 10827.20138)*</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="7c7f2-1773">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1773">Excel: Feature Updates</span></span>
- <span data-ttu-id="7c7f2-p323">**迅速な検索:** VLOOKUP、HLOOKUP、MATCH 計算が強化され、解答をすばやく取得できるようになりました。[詳細情報](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p323">**Speedy Lookup** We've turbo-charged your VLOOKUP, HLOOKUP, and MATCH calculations so you can get answers faster. [Learn more](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)</span></span>
- <span data-ttu-id="7c7f2-p324">**データの取得と変換をご利用の皆様:** データの取得と変換をよく利用していただいているユーザーの皆様に、例からの列の機能が改善されたことをお知らせします。また、多くのコネクタも強化されました。[詳細情報](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p324">**Calling all Get & Transform fans** If you use Get & Transform a lot, you'll be happy to know that the Column From Example feature has been improved. And, many connectors have been improved as well. [Learn more](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)</span></span>
- <span data-ttu-id="7c7f2-p325">**新しい見た目のリボン アイコン:** 機能に変化はないので、心配はいりません。さらに、どのサイズの画面でも、見た目がきれいです。[詳細情報](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p325">**Your ribbon icons have a new look** Don’t worry, everything works the same. Plus, they look great on screens of all sizes. [Learn more](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="7c7f2-1782">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1782">Outlook: Feature Updates</span></span>
- <span data-ttu-id="7c7f2-p326">**今後のリリース予定を確認:** 新しいユーザー エクスペリエンスを公開前にお試しになり、ご意見をお寄せください。[詳細情報](https://support.office.com/article/d4b7db49-b4e0-4f98-a0dc-156952e551e2)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p326">**See what’s Coming Soon** Try out new user experiences before they’re released and let us know what you think. [Learn more](https://support.office.com/article/d4b7db49-b4e0-4f98-a0dc-156952e551e2)</span></span>
- <span data-ttu-id="7c7f2-1785">**安全なリンクの背後にある URL を表示する** 安全なリンクは、メールで受け取った悪意のある URL からユーザーを保護しますが、元の URL は非表示になります。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1785">**See the URL behind Safe Links** Safe Links protects you from malicious URLS received in email but they hide the original URL.</span></span> <span data-ttu-id="7c7f2-1786">元の URL を確認するには、URL をマウスでポイントします。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1786">To see the original, hover your mouse over the URL.</span></span> <span data-ttu-id="7c7f2-1787">Advanced Threat Protection のライセンスが必要です。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1787">Requires an Advanced Threat Protection license.</span></span> [<span data-ttu-id="7c7f2-1788">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1788">Learn more</span></span>](https://products.office.com/exchange/advance-threat-protection)
- <span data-ttu-id="7c7f2-1789">**検索のスペルの修正候補を取得する:** 検索を実行すると、Outlook により、スペルの修正候補を使用したお勧めの検索クエリが提供されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1789">**Get search spelling suggestions** After performing a search, Outlook will provide a suggested search query with spelling corrections.</span></span>
- <span data-ttu-id="7c7f2-p328">**新しい見た目のリボン アイコン:** 機能に変化はないので、心配はいりません。さらに、どのサイズの画面でも、見た目がきれいです。[詳細情報](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p328">**Your ribbon icons have a new look** Don’t worry, everything works the same. Plus, they look great on screens of all sizes. [Learn more](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="7c7f2-1793">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1793">PowerPoint: Feature Updates</span></span>
- <span data-ttu-id="7c7f2-p329">**スライドが活気のあるものに:** アニメーション 3D グラフィックを挿入して、心臓の鼓動、惑星の軌道、画面を暴れまわる T レックスを表示します。[詳細情報](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p329">**Watch your slides come alive** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage across the screen.  [Learn more](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span></span>
- <span data-ttu-id="7c7f2-p330">**新しい見た目のリボン アイコン:** 機能に変化はないので、心配はいりません。さらに、どのサイズの画面でも、見た目がきれいです。[詳細情報](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p330">**Your ribbon icons have a new look** Don’t worry, everything works the same. Plus, they look great on screens of all sizes. [Learn more](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="7c7f2-1799">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1799">Word: Feature Updates</span></span>
- <span data-ttu-id="7c7f2-p331">**\@メンションを使用してユーザーの注意を引く:** コメントで @メンションを使うと、仕事仲間による入力が必要な場合にそのユーザーに知らせることができます。[詳細情報](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p331">**Get their attention with \@mentions** Use @mentions in comments to let co-workers know when you need their input. [Learn more](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)</span></span>
- <span data-ttu-id="7c7f2-p332">**新しい見た目のリボン アイコン:** 機能に変化はないので、心配はいりません。さらに、どのサイズの画面でも、見た目がきれいです。[詳細情報](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p332">**Your ribbon icons have a new look** Don’t worry, everything works the same. Plus, they look great on screens of all sizes. [Learn more](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span></span>
- <span data-ttu-id="7c7f2-1805">**数式エディター コンバーター:** コンバーターにより、ユーザーは Microsoft 数式エディターを使用して作成された数式を、Office Math ML 形式に変換して、編集できるようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1805">**Equation Editor converter** Converter allows users to convert equations created using Microsoft Equation editor to Office Math ML format to enable editing.</span></span>
- <span data-ttu-id="7c7f2-1806">**静的なドキュメントから魅力的なドキュメントへの変換:** ドキュメントを、どのデバイスでも映える対話型の使いやすい Web ページに変換します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1806">**Take your doc from static to stunning** Transform your document into an interactive, easy-to-share web page that looks great on any device.</span></span> [<span data-ttu-id="7c7f2-1807">詳細情報</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1807">Learn more</span></span>](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)

## <a name="version-1808-september-11"></a><span data-ttu-id="7c7f2-1808">バージョン 1808: 9 月 11 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1808">Version 1808: September 11</span></span>
<span data-ttu-id="7c7f2-1809">*バージョン 1808 (ビルド 10730.20102)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1809">*Version 1808 (Build 10730.20102)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="7c7f2-1810">Excel: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1810">Excel: Security updates</span></span>
-   <span data-ttu-id="7c7f2-1811">[CVE-2018-8331](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8331): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1811">[CVE-2018-8331](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8331): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="7c7f2-1812">[CVE-2018-8429](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8429): Microsoft Excel の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1812">[CVE-2018-8429](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8429): Microsoft Excel Information Disclosure Vulnerability</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="7c7f2-1813">Word: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1813">Word: Security updates</span></span>
-   <span data-ttu-id="7c7f2-1814">[CVE-2018-8430](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8430): Windows PDF のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1814">[CVE-2018-8430](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8430): Word PDF Remote Code Execution Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="7c7f2-1815">Office スイート: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1815">Office suite: Security updates</span></span>
-   <span data-ttu-id="7c7f2-1816">[CVE-2018-8332](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8332): Win32k Graphics のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1816">[CVE-2018-8332](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8332): Win32k Graphics Remote Code Execution Vulnerability</span></span>


## <a name="version-1808-september-5"></a><span data-ttu-id="7c7f2-1817">バージョン 1808: 9 月 5 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1817">Version 1808: September 5</span></span>
<span data-ttu-id="7c7f2-1818">*バージョン 1808 (ビルド 10730.20088)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1818">*Version 1808 (Build 10730.20088)*</span></span>

### <a name="access-feature-updates"></a><span data-ttu-id="7c7f2-1819">Access: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1819">Access: Feature Updates</span></span>
 - <span data-ttu-id="7c7f2-p334">**リンク テーブルを更新、再リンク、または削除する:** 更新されたリンク テーブル マネージャーで、すべてのデータ ソースとリンク テーブルを管理できます。[詳細情報](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p334">**Refresh, relink, or remove linked tables** The updated Linked Table Manager is the location for managing all data sources and linked tables. [Learn more](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="7c7f2-1822">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1822">Outlook: Feature Updates</span></span>
 - <span data-ttu-id="7c7f2-p335">**会議の転送を無効にする:** 出席者が会議を他のユーザーに転送できないようにします。リボンに移動して、[応答オプション] をクリックするだけです。[詳細情報](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p335">**Turn off forwarding for a meeting** Prevent attendees from forwarding your meeting to others. Just go to the ribbon and click Response Options. [Learn more](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)</span></span>
 
### <a name="visio-feature-updates"></a><span data-ttu-id="7c7f2-1826">Visio: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1826">Visio: Feature Updates</span></span>
 - <span data-ttu-id="7c7f2-1827">**新しい図面でアイコンを楽しむ:** 分析、アート、お祝い、顔文字、スポーツなどのアイコンが含まれる 26 種類の新しいステンシルから選択できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1827">**Enjoy an iconic moment in your next diagram** Pick from 26 new stencils with icons for analytics, arts, celebration, faces, sports, and more.</span></span> 
 - <span data-ttu-id="7c7f2-p336">**Visio 図形から Word 文書を作成する:** 図形やメタデータなどのダイアグラム コンテンツを Word 文書に自動的に追加します。次にその文書をカスタマイズして、プロセス ガイドラインや操作マニュアルを作成します。[詳細情報](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p336">**Build a Word document out of Visio shapes** Automatically add diagram content, including shapes and metadata, to a Word document. Then customize the document to create process guidelines and operation manuals. [Learn more](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)</span></span>
 - <span data-ttu-id="7c7f2-p337">**Visio と Power BI: 相乗効果:** 数回クリックするだけで、Visio 図面を Power BI のインタラクティブな視覚化に変換できます。[詳細情報](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p337">**Visio and Power BI: Better together** In just a few clicks, turn your Visio diagram into an interactive Power BI visualization. [Learn more](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)</span></span>

 ### <a name="project-feature-updates"></a><span data-ttu-id="7c7f2-1833">Project: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1833">Project: Feature Updates</span></span>
 - <span data-ttu-id="7c7f2-p338">**タスク ボード カードに詳細を表示する:** タイトルだけでは内容が伝わらない場合は、最も重要な詳細がすべて表示されるようにタスク ボード カードをカスタマイズできます。[詳細情報](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p338">**See more info on Task Board cards** When the title alone doesn’t tell the story, customize your Task Board cards to show all the most important details. [Learn more](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="7c7f2-1836">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1836">Excel: Non-security updates</span></span>
-  <span data-ttu-id="7c7f2-1837">ユーザーがコピーするために選択したセルの範囲を示す点線が、その後の貼り付けなどの操作を行った後もクリップボードから消えずに残ったままになる Excel での問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1837">Fixes an issue in Excel wherein the dotted line marking the range of cells that a user selected for copying does not disappear and remains in clipboard even after a subsequent user operation like paste.</span></span> 

### <a name="outlook-non-security-updates"></a><span data-ttu-id="7c7f2-1838">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1838">Outlook: Non-security updates</span></span>
 - <span data-ttu-id="7c7f2-1839">複数の Exchange アカウントを構成している一部のユーザーで、検索結果リストに [クリックして詳細を表示する] リンクが表示されない原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1839">Addresses an issue that caused the "Click to view more..." link to be missing from the search results list for some users with multiple Exchange accounts configured.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="7c7f2-1840">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1840">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="7c7f2-1841">特定のシナリオで更新プログラムのインストールが長くかかる原因となった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1841">Fixed an issue that caused update install to take a long time in certain scenarios.</span></span>
 
### <a name="lync-non-security-updates"></a><span data-ttu-id="7c7f2-1842">Lync: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1842">Lync: Non-security updates</span></span>
 - <span data-ttu-id="7c7f2-1843">IM メッセージで絵文字を表示できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1843">Fixes an issue that prevented emoticons in IM messages from being displayed.</span></span> 


## <a name="version-1807-august-14"></a><span data-ttu-id="7c7f2-1844">バージョン 1807: 8 月 14 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1844">Version 1807: August 14</span></span>
<span data-ttu-id="7c7f2-1845">*バージョン 1807 (ビルド 10325.20118)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1845">*Version 1807 (Build 10325.20118)*</span></span>

### <a name="access-security-updates"></a><span data-ttu-id="7c7f2-1846">Access: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1846">Access: Security updates</span></span>
-   <span data-ttu-id="7c7f2-1847">[CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): Microsoft Access のリモート コード実行の Use After Free 脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1847">[CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): Microsoft Access Remote Code Execution Use After Free Vulnerability</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="7c7f2-1848">Excel: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1848">Excel: Security updates</span></span>
-   <span data-ttu-id="7c7f2-1849">[CVE-2018-8375](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8375): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1849">[CVE-2018-8375](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8375): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="7c7f2-1850">[CVE-2018-8379](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8379): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1850">[CVE-2018-8379](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8379): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="7c7f2-1851">[CVE-2018-8382](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8382): Microsoft Excel の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1851">[CVE-2018-8382](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8382): Microsoft Excel Information Disclosure Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="7c7f2-1852">Outlook: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1852">Outlook: Security updates</span></span>
-   <span data-ttu-id="7c7f2-1853">[ADV180021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180021): Microsoft Office の高度な防御の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1853">[ADV180021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180021): Microsoft Office Defense in Depth Update</span></span> 

### <a name="office-suite-security-updates"></a><span data-ttu-id="7c7f2-1854">Office スイート: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1854">Office Suite: Security updates</span></span>
-   <span data-ttu-id="7c7f2-1855">[CVE-2018-8378](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8378): Microsoft Office の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1855">[CVE-2018-8378](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8378): Microsoft Office Information Disclosure Vulnerability</span></span> 

## <a name="version-1807-july-25"></a><span data-ttu-id="7c7f2-1856">バージョン 1807: 7 月 25 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1856">Version 1807: July 25</span></span>
<span data-ttu-id="7c7f2-1857">*バージョン 1807 (ビルド 10325.20082)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1857">*Version 1807 (Build 10325.20082)*</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="7c7f2-1858">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1858">Outlook: Feature updates</span></span>
- <span data-ttu-id="7c7f2-p339">**Outlook アドインの警告:** Outlook COM アドインでは、Outlook の他の部分の速度を遅くする問題が発生する場合があります。これらの問題は、Outlook フォルダー間の切り替え、新規メールの受信、予定表アイテムを開くなどのイベントの遅延が原因の可能性があります。このような問題が発生した場合、Outlook では通知バーに警告が表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p339">**Outlook add-in warnings:** Occasionally an Outlook COM add-in can encounter problems that slows down the rest of Outlook. These problems could be due to latency of events such as switching between Outlook folders, arrival of new emails, opening Calendar items, etc. When such issues arise, Outlook will display a warning in the notification bar.</span></span>
- <span data-ttu-id="7c7f2-p340">**Outlook のアラーム ダイアログから Teams 会議に参加する:** Outlook が今後の会議についてユーザーに通知する際、会議が Teams のオンライン会議の場合には、[オンラインで参加] ボタンが表示されます。これは、Outlook のアラート ダイアログから Skype for Business 会議に参加する場合に似ています。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p340">**Join Teams meetings from the Outlook Reminders dialog:** When Outlook reminds users of an upcoming meeting, it will show a Join Online button if the upcoming meeting is a Teams online meeting. This is similar to the experience of joining a Skype for Business meeting from the Outlook Reminders dialog.</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="7c7f2-1863">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1863">PowerPoint: Feature updates</span></span>
 - <span data-ttu-id="7c7f2-p341">**ハイパーリンクの色:** ハイパーリンクの色はもはや青だけではありません。好きなフォントと色を適用します。[詳細](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p341">**Hyperlink colors:** Hyperlinks aren't just blue anymore. Apply any font color you like. [Learn more](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="7c7f2-1867">Visio: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1867">Visio: Feature updates</span></span>
 - <span data-ttu-id="7c7f2-p342">**Visio 図形から Word 文書を作成する:** 図形やメタデータなどのダイアグラム コンテンツを Word 文書に自動的に追加します。次にその文書をカスタマイズして、プロセス ガイドラインや操作マニュアルを作成します。[詳細](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p342">**Build a Word document out of Visio shapes:** Automatically add diagram content, including shapes and metadata, to a Word document. Then customize the document to create process guidelines and operation manuals. [Learn more](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="7c7f2-1871">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1871">Word: Feature updates</span></span>
 - <span data-ttu-id="7c7f2-1872">**IRM の変更履歴の記録:** IRM 保護文書の Word で、変更履歴の記録機能をフル コントロールの使用権限なしで使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1872">**Track changes with IRM:** You can now use the Track Changes feature in Word in IRM-protected documents without requiring the Full Control usage right.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="7c7f2-1873">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1873">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="7c7f2-1874">一部のユーザーが他の組織のユーザーと共有していた IRM 保護文書やメールを開くの妨げていた一連の問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1874">Fixed a set of issues that prevented some users from opening IRM-protected documents & emails that were shared with them by people in other organizations.</span></span>

## <a name="version-1806-july-17"></a><span data-ttu-id="7c7f2-1875">バージョン 1806: 7 月 17 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1875">Version 1806: July 17</span></span>
<span data-ttu-id="7c7f2-1876">*バージョン 1806 (ビルド 10228.20134)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1876">*Version 1806 (Build 10228.20134)*</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="7c7f2-1877">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1877">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="7c7f2-1878">いくつかのパフォーマンスの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1878">Fixed some performance issues.</span></span>

## <a name="version-1806-july-10"></a><span data-ttu-id="7c7f2-1879">バージョン 1806: 7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1879">Version 1806: July 10</span></span>
<span data-ttu-id="7c7f2-1880">*バージョン 1806 (ビルド 10228.20104)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1880">*Version 1806 (Build 10228.20104)*</span></span>

### <a name="access-security-updates"></a><span data-ttu-id="7c7f2-1881">Access: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1881">Access: Security updates</span></span>
-   <span data-ttu-id="7c7f2-1882">[CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): Microsoft Access のリモート コード実行の Use After Free 脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1882">[CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): Microsoft Access Remote Code Execution Use After Free Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="7c7f2-1883">Outlook: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1883">Outlook: Security updates</span></span>
-   <span data-ttu-id="7c7f2-1884">[CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310): Microsoft Office 改ざんの脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1884">[CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310): Microsoft Office Tampering Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="7c7f2-1885">Office スイート: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1885">Office Suite: Security updates</span></span>
-   <span data-ttu-id="7c7f2-1886">[CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281): Microsoft Office のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1886">[CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281): Microsoft Office Remote Code Execution Vulnerability</span></span>

## <a name="version-1806-june-25"></a><span data-ttu-id="7c7f2-1887">バージョン 1806: 6 月 25 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1887">Version 1806: June 25</span></span>
<span data-ttu-id="7c7f2-1888">*バージョン 1806 (ビルド 10228.20080)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1888">*Version 1806 (Build 10228.20080)*</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="7c7f2-1889">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1889">Excel: Feature updates</span></span>
- <span data-ttu-id="7c7f2-p343">**セルおよび数式バーの編集の強化:** Ctrl + A キーを押して、セルまたは数式バーのテキストを選択できるようになりました。絵文字とその他の複雑な文字のサポートも強化されました。[詳細情報](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p343">**Improved cell and formula bar editing:** You can now use CTRL+A to select text in a cell or the formula bar. There's also improved support for emojis and other complex characters.[Learn more](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)</span></span>
- <span data-ttu-id="7c7f2-p344">**SVG サポートの強化:** フィルターが適用された SVG を挿入できます。[詳細情報](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p344">**Improved SVG support:** You can insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="7c7f2-1894">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1894">Outlook: Feature updates</span></span>
- <span data-ttu-id="7c7f2-1895">**定期的なアイテムの既定値:** [定期的な予定の設定] ダイアログ ボックスの [期間] の下で、[終了日] は既定の設定 ([終了日未定] ではない) で、示されている最初の設定であり、既定の終了日が設定されています。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1895">**Recurrence default:** In the Appointment Recurrence dialog box (under "Range of recurrence"), “End by” is the default setting (instead of "No end date") and is the first setting listed, and a default end date is set.</span></span>
- <span data-ttu-id="7c7f2-p345">**アクセシビリティ チェックの改善:** アクセシビリティ チェックで、メッセージのアクセシビリティを向上させるための国際標準と推奨事項のサポートが更新されました。[詳細情報](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p345">**Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your messages more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="7c7f2-1898">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1898">PowerPoint: Feature updates</span></span>
- <span data-ttu-id="7c7f2-p346">**SVG サポートの強化:** フィルターが適用された SVG を挿入できます。[詳細情報](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p346">**Improved SVG support:** You can insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="7c7f2-p347">**ペンでスライドにタイトルを付ける:** ペンを使用してタイトルをインク入力すると、PowerPoint でテキストに変換されます。[詳細情報](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p347">**Title your slides with a pen:** Use your pen to ink in a title, and watch PowerPoint convert it to text. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="7c7f2-1903">Project: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1903">Project: Feature updates</span></span>
 - <span data-ttu-id="7c7f2-p348">**最近使用したファイルの保存場所の整理:** Project では、他のプロジェクトを保存した場所に関する最新のリストを保持します。プロジェクトを保存する準備ができたら、最近使用したファイルの保存場所の 1 つを選択し、それ以上気にする必要はありません。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p348">**Stay organized with Recent save locations:** Project keeps a running list of where you've saved other projects. When you're ready to save your project, just choose one of your Recent save locations and get on with your day.</span></span>
 - <span data-ttu-id="7c7f2-p349">**スプリントを管理する新しい方法:** アジャイルな方法でタスク ボードを使用できます。[スプリントの管理] に移動して、プロジェクトの拡大に伴って、スプリントを追加したり、削除したりできます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p349">**A new way to manage sprints:** Take an agile approach to working with Task Boards. Go to Manage Sprints to add and remove sprints as your project evolves.</span></span>


### <a name="project-non-security-updates"></a><span data-ttu-id="7c7f2-1908">Project: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1908">Project: Non-security updates</span></span>
 - <span data-ttu-id="7c7f2-1909">マスター プロジェクトからのサブプロジェクトの保存が失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1909">Fixed an issue where saving sub-projects from master projects would fail.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="7c7f2-1910">Visio: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1910">Visio: Feature updates</span></span>
 - <span data-ttu-id="7c7f2-1911">**その他のステンシル、その他のアイコン、その他の選択肢:** 分析、芸術、お祝い、顔、場所、医療、自然、人々、スポーツ、天気、季節などの 26 個のステンシルを追加しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1911">**More stencils, more icons, more choice:** We've added 26 stencils including Analytics, Arts, Celebration, Faces, Location, Medical, Nature, People, Sports, Weather and Seasons, and more.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="7c7f2-1912">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1912">Word: Feature updates</span></span>
 - <span data-ttu-id="7c7f2-p350">**SVG サポートの強化:** フィルターが適用された SVG を挿入できます。[詳細情報](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p350">**Improved SVG support:** You can insert SVGs that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>



## <a name="version-1805-june-13"></a><span data-ttu-id="7c7f2-1915">バージョン 1805: 6 月 13 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1915">Version 1805: June 13</span></span>
<span data-ttu-id="7c7f2-1916">*バージョン 1805 (ビルド 9330.2124)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1916">*Version 1805 (Build 9330.2124)*</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="7c7f2-1917">Outlook のセキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1917">Outlook Non-security updates</span></span>
 - <span data-ttu-id="7c7f2-1918">MAPI API を呼び出すアプリケーションがクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1918">Fix an issue where an application calling the MAPI API could result in a crash.</span></span>



## <a name="version-1805-june-12"></a><span data-ttu-id="7c7f2-1919">バージョン 1805: 6 月 12 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1919">Version 1805: June 12</span></span>
<span data-ttu-id="7c7f2-1920">*バージョン 1805 (ビルド 9330.2118)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1920">*Version 1805 (Build 9330.2118)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="7c7f2-1921">Excel: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1921">Excel: Security updates</span></span>
-   <span data-ttu-id="7c7f2-1922">[CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246): Microsoft Excel の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1922">[CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246): Microsoft Excel Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="7c7f2-1923">[CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1923">[CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="7c7f2-1924">Outlook: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1924">Outlook: Security updates</span></span>
-   <span data-ttu-id="7c7f2-1925">[CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244): Microsoft Outlook 特権の昇格の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1925">[CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244): Microsoft Outlook Elevation of Privilege Vulnerability</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="7c7f2-1926">Outlook のセキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1926">Outlook non-security updates</span></span>

- <span data-ttu-id="7c7f2-1927">MAPI API を呼び出すアプリケーションがクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1927">Fix an issue where an application calling the MAPI API could result in a crash.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="7c7f2-1928">Project: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1928">Project Non-security updates</span></span>

- <span data-ttu-id="7c7f2-1929">マスター プロジェクトのコンテキストでサブ プロジェクトの作業を行ったときに、サブ プロジェクトを保存できない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1929">Fix an issue where you are blocked from saving a sub project when working with them through the context of a master project.</span></span>

## <a name="version-1805-may-24"></a><span data-ttu-id="7c7f2-1930">バージョン 1805: 5 月 24 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1930">Version 1805: May 24</span></span>
<span data-ttu-id="7c7f2-1931">*バージョン 1805 (ビルド 9330.2087)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1931">*Version 1805 (Build 9330.2087)*</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="7c7f2-1932">Outlook のセキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1932">Outlook Non-security updates</span></span>
 - <span data-ttu-id="7c7f2-1933">iCloud アドインを使用すると Outlook がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1933">Fix an issue where Outlook crashes when using the iCloud add-in.</span></span>
 


## <a name="version-1805-may-23"></a><span data-ttu-id="7c7f2-1934">バージョン 1805: 5 月 23 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1934">Version 1805: May 23</span></span>
<span data-ttu-id="7c7f2-1935">*バージョン 1805 (ビルド 9330.2078)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1935">*Version 1805 (Build 9330.2078)*</span></span>

### <a name="access-feature-updates"></a><span data-ttu-id="7c7f2-1936">Access: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1936">Access: Feature updates</span></span>
 - <span data-ttu-id="7c7f2-p351">**新しいグラフを使用したデータの視覚化:** 11 種類のグラフから選択してフォームやレポートに追加することにより、データが見やすくなり、十分な情報に基づいて決定を下すことができます。[詳細情報](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p351">**Visualize data with new charts:** Choose from 11 charts and add one to your forms and reports to better visualize the data and make informed decisions. [Learn more](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="7c7f2-1939">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1939">Excel: Feature updates</span></span>
 - <span data-ttu-id="7c7f2-p352">**編編集するときに共同編集者とチャットする:** 共同編集者とチャットして、Excel から移動せずにより効率的に共同作業することができます。この機能は一部の地域では使用できないので注意してください。[詳細情報](https://support.office.com/article/1ecc6c7f-0b02-4baa-b9d9-c9d67023bedd)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p352">**Chat with co-authors while you edit:** Collaborate more effectively by chatting with your co-authors without ever leaving Excel. Note that this feature is not available in some regions.[Learn more](https://support.office.com/article/1ecc6c7f-0b02-4baa-b9d9-c9d67023bedd)</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="7c7f2-1942">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1942">Outlook: Feature updates</span></span>
 - <span data-ttu-id="7c7f2-p353">**ハンズ フリー入力:** 自分の声で口述するだけでメールを作成します。タイピングは必要ありません。[詳細情報](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p353">**Hands free typing:** Use your voice to create emails by simply dictating. No need to type. [Learn more](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)</span></span>
 - <span data-ttu-id="7c7f2-p354">**3 タイムゾーン表示:** タイム ゾーンが異なるユーザー間で会議をスケジュールする必要がある場合、カレンダーに複数のタイム ゾーンを追加すれば、全員の予定を確認し、全員にとって都合の良い時間を選択しやすくなります。[詳細情報](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p354">**View 3 time zones:** Need to schedule a meeting across time zones? Add multiple time zones to your calendar to easily see everyone's availability and pick a time that works for all. [Learn more](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)</span></span>
 - <span data-ttu-id="7c7f2-p355">**簡略化されたカレンダーの共有:** カレンダーを一層簡単に共有できるようになり、Outlook デスクトップから共有したカレンダーも Outlook Mobile で利用できるようになりました。[詳細情報](https://support.office.com/article/353ed2c1-3ec5-449d-8c73-6931a0adab88)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p355">**Calendar sharing made easy:** Sharing your calendars is simpler and calendars shared from Outlook Desktop are now also available in Outlook Mobile. [Learn more](https://support.office.com/article/353ed2c1-3ec5-449d-8c73-6931a0adab88)</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="7c7f2-1951">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1951">Outlook: Non-security updates</span></span>
- <span data-ttu-id="7c7f2-1952">カレンダーを共有するときの文言を、「このカレンダーを開く」から「同意する」に変更します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1952">Change the wording in an invite to share a calendar from “Open this calendar” to “Accept.”</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="7c7f2-1953">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1953">PowerPoint: Feature updates</span></span>
 - <span data-ttu-id="7c7f2-p356">**編集するときに共同編集者とチャットします:** PowerPoint を終了せずに共同編集者とチャットすることで、より効果的な共同作業ができます。[詳細情報](https://support.office.com/article/1ecc6c7f-0b02-4baa-b9d9-c9d67023bedd)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p356">**Chat with co-authors while you edit:** Collaborate more effectively by chatting with your co-authors without ever leaving PowerPoint. [Learn more](https://support.office.com/article/1ecc6c7f-0b02-4baa-b9d9-c9d67023bedd)</span></span>
 - <span data-ttu-id="7c7f2-p357">**ハンズ フリー入力:** 自分の声で口述するだけでプレゼンテーションを作成します。タイピングは必要ありません。[詳細情報](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p357">**Hands free typing:** Use your voice to create presentations by simply dictating. No need to type. [Learn more](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)</span></span>
 - <span data-ttu-id="7c7f2-p358">**Microsoft Forms:** テストやアンケートをスライドに配置します。Office で応答が自動的に収集され、保存されます。[詳細情報](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p358">**Microsoft Forms:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="7c7f2-1962">Project: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1962">Project: Non-security updates</span></span>
 - <span data-ttu-id="7c7f2-1963">Project Web App にプロジェクトを初めて保存したときに Project がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1963">Fix an issue where Project may crash the first time you save a project to Project Web App.</span></span>


### <a name="visio-feature-updates"></a><span data-ttu-id="7c7f2-1964">Visio: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1964">Visio: Feature updates</span></span>
 - <span data-ttu-id="7c7f2-1965">**スターター図面:** 組織図、ブレーンストーミング、SDL テンプレートには新しいスターター図面があり、これにより短時間で作業を効率的に進めることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1965">**Starter diagrams:** The Organization Chart, Brainstorming, and SDL templates have new starter diagrams to get you up and running quickly.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="7c7f2-1966">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1966">Word: Feature updates</span></span>
 - <span data-ttu-id="7c7f2-p359">**編集するときに共同編集者とチャットします:** Word を終了せずに共同編集者とチャットすることで、より効果的な共同作業ができます。[詳細情報](https://support.office.com/article/1ecc6c7f-0b02-4baa-b9d9-c9d67023bedd)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p359">**Chat with co-authors while you edit:** Collaborate more effectively by chatting with your co-authors without ever leaving Word. [Learn more](https://support.office.com/article/1ecc6c7f-0b02-4baa-b9d9-c9d67023bedd)</span></span>
 - <span data-ttu-id="7c7f2-p360">**ハンズ フリー入力:** 自分の声で口述するだけでドキュメントを作成します。タイピングは必要ありません。[詳細情報](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p360">**Hands free typing:** Use your voice to create documents by simply dictating. No need to type. [Learn more](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)</span></span>
 - <span data-ttu-id="7c7f2-p361">**インク エディターを使った自然な編集:** ペンを使って 1 ストローク描くだけで、単語の分割や結合、新しい線の追加、単語の挿入などができます。[詳細情報](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p361">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>



## <a name="version-1804-may-14"></a><span data-ttu-id="7c7f2-1974">バージョン 1804: 5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1974">Version 1804: May 14</span></span>
<span data-ttu-id="7c7f2-1975">*バージョン 1804 (ビルド 9226.2156)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1975">*Version 1804 (Build 9226.2156)*</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="7c7f2-1976">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1976">Office suite: Non-security updates</span></span>
- <span data-ttu-id="7c7f2-1977">ユーザーがアプリケーションを開いたときに、セーフ モードでの起動に関するメッセージが表示され、アプリケーションが起動しない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1977">Fix an issue where, when opening an application, the user might see a message about launching in Safe mode and then the application fails to open.</span></span>



## <a name="version-1804-may-8"></a><span data-ttu-id="7c7f2-1978">バージョン 1804: 5 月 8 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1978">Version 1804: May 8</span></span>
<span data-ttu-id="7c7f2-1979">*バージョン 1804 (ビルド 9226.2126)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1979">*Version 1804 (Build 9226.2126)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="7c7f2-1980">Excel: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1980">Excel: Security updates</span></span>
-   <span data-ttu-id="7c7f2-1981">[CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1981">[CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="7c7f2-1982">[CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1982">[CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="7c7f2-1983">[CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1983">[CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="7c7f2-1984">[CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163): Microsoft Excel の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1984">[CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163): Microsoft Excel Information Disclosure Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="7c7f2-1985">Outlook: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1985">Outlook: Security updates</span></span>
-   <span data-ttu-id="7c7f2-1986">[CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150): Microsoft Outlook のセキュリティ機能のバイパスの脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1986">[CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150): Microsoft Outlook Security Feature Bypass Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="7c7f2-1987">Office スイート: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1987">Office suite: Security updates</span></span>
-   <span data-ttu-id="7c7f2-1988">[CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157): Microsoft Office のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1988">[CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="7c7f2-1989">[CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158): Microsoft Office のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1989">[CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158): Microsoft Office Remote Code Execution Vulnerability</span></span>


## <a name="version-1804-april-25"></a><span data-ttu-id="7c7f2-1990">バージョン 1804: 4 月 25 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1990">Version 1804: April 25</span></span>
<span data-ttu-id="7c7f2-1991">*バージョン 1804 (ビルド 9226.2114)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1991">*Version 1804 (Build 9226.2114)*</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="7c7f2-1992">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-1992">Outlook: Feature updates</span></span>
-   <span data-ttu-id="7c7f2-p362">**メールの聞き取り:** Outlook でメールを読み上げることができるようになりました。読み上げと同時にテキストが強調表示されます。[詳細情報](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p362">**Listen to your emails:** Outlook can read your email aloud, highlighting text as it's read. [Learn more](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)</span></span>
-   <span data-ttu-id="7c7f2-p363">**アラームを見落とさない:** 作業中のウィンドウ上にポップアップ表示されるように、アラームを設定できます。設定しない場合でも、Outlook がタスク バーで点滅してユーザーの注意を引きます。[詳細情報](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p363">**Never miss a reminder:** Set reminders to pop up over windows you're working in. Otherwise, Outlook will blink in the taskbar to get your attention.[Learn more](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)</span></span>
-   <span data-ttu-id="7c7f2-p364">**削除済みアイテムを開封済みに:** 削除したメッセージすべてを開封済みとして設定できるようになりました。[ファイル] \> [オプション] \> [メール] \> [その他] の順に移動して、オプトインします。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p364">**Mark deleted items as read:** You can now set any message that you delete as read. Opt in by going to File \> Options \> Mail \> Other.</span></span>
-   <span data-ttu-id="7c7f2-p365">**暗号化オプション:** Office 365 Message Encryption ユーザーは、メッセージを暗号化して、組織内外の任意のユーザーに送信できます。暗号化オプションは、メッセージ作成時に [オプション] \> [アクセス許可] に表示されます。 [詳細情報](/microsoft-365/compliance/ome)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p365">**Encrypt option:** Office 365 Message Encryption users can encrypt a message and send it to anyone, inside or outside their organization. Encrypt option appears under Options \> Permissions when creating a message. [Learn more](/microsoft-365/compliance/ome)</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="7c7f2-2002">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2002">PowerPoint: Feature updates</span></span>
-   <span data-ttu-id="7c7f2-p366">**手書き内容の変換:** フリーハンドのメモや描画を読みやすいテキストや整った図形に変換して、洗練されたプレゼンテーションを作成します。 [詳細情報](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p366">**Convert your ink:** Take scribbled notes and drawings, and convert them into readable text and crisp shapes to create a polished presentation. [Learn more](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="7c7f2-2005">Project: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2005">Project: Feature updates</span></span>
-   <span data-ttu-id="7c7f2-2006">**タスク ボードのフィルター処理:** 主なリソースまたはサマリー タスクをフィルター処理して、タスク ボードを効率化します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2006">**Task board filtering:** Streamline your task boards by filtering on key resources or summary tasks.</span></span>
-   <span data-ttu-id="7c7f2-2007">**タスク ボードから達成率を設定:** 各列の達成率を選択し、ドラッグ アンド ドロップでタスクの完了を更新します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2007">**Set percent complete from a task board:** Choose a percent complete for each column, and then update task completion with drag-and-drop.</span></span>
-   <span data-ttu-id="7c7f2-2008">**スプリント ナビゲーション:** スプリント表示を切り替えて、タスクをスプリント間ですばやく移動します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2008">**Sprint navigation:** Switch from one sprint view to another, and quickly move tasks between sprints.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="7c7f2-2009">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2009">Word: Feature updates</span></span>
-   <span data-ttu-id="7c7f2-2010">**校正関連の問題の発見と修正:** ドキュメントで見つかった校正関連の問題の概要がエディター ウィンドウに表示されるようになりました。このため、ユーザーにとって最も関連の高い問題の修正にフォーカスが置かれます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2010">**Find and fix relevant proofing issues:** Editor pane now displays an overview of proofing issues found in your document, so the focus is on fixing the ones that are most relevant to you.</span></span>


## <a name="version-1803-april-11"></a><span data-ttu-id="7c7f2-2011">バージョン 1803: 4 月 11 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2011">Version 1803: April 11</span></span>
<span data-ttu-id="7c7f2-2012">*バージョン 1803 (ビルド 9126.2152)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2012">*Version 1803 (Build 9126.2152)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="7c7f2-2013">Excel: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2013">Excel: Security updates</span></span>
-   <span data-ttu-id="7c7f2-2014">[CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2014">[CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="7c7f2-2015">PowerPoint: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2015">PowerPoint: Non-security updates</span></span>
-   <span data-ttu-id="7c7f2-2016">複数のユーザーが同じプレゼンテーションを共同編集すると、スライド マスターに正しくない重複が発生する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2016">Fix an issue where multiple users co-authoring on the same presentation results in an incorrect duplication of slides masters.</span></span>
-   <span data-ttu-id="7c7f2-2017">OneDrive に保存されているファイルを開いた際、保護ビューを終了すると PowerPoint がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2017">Fix an issue where opening a file saved on OneDrive results in PowerPoint crashing when exiting Protected View.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="7c7f2-2018">Skype for Business: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2018">Skype for Business: Non-security updates</span></span>
-   <span data-ttu-id="7c7f2-2019">TLS 1.2 サポートに関連する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2019">Fix an issue related to TLS 1.2 support.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="7c7f2-2020">Word: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2020">Word: Non-security updates</span></span>
-   <span data-ttu-id="7c7f2-2021">メモリ不足を示すメッセージが表示される原因となる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2021">Fix an issue that causes an insufficient memory message to appear.</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="7c7f2-2022">Office スイート: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2022">Office suite: Security updates</span></span>
-   <span data-ttu-id="7c7f2-2023">[CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950): Microsoft Office の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2023">[CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="7c7f2-2024">[CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026): Microsoft Office のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2024">[CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="7c7f2-2025">[CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030): Microsoft Office のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2025">[CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="7c7f2-p367">**セキュリティ上の理由から、Office での Flash、Silverlight、および Shockwave のコントロールのアクティブ化がブロックされる:** セキュリティ上の理由から、Windows 上の Microsoft Office for Office 365 の新しいビルドでは、Flash、Silverlight、および Shockwave のコントロールのアクティブ化がブロックされます。詳細については、[こちら](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729)および [こちら](https://support.office.com/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1)をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p367">**Flash, Silverlight and Shockwave controls blocked from activating in Office for security reasons:** For security reasons new builds of Microsoft Office for Office 365 on Windows block activation of Flash, Silverlight, and Shockwave controls.  Learn more [here](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729) and [here](https://support.office.com/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1).</span></span>

## <a name="version-1803-march-27"></a><span data-ttu-id="7c7f2-2028">バージョン 1803: 3 月 27 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2028">Version 1803: March 27</span></span>
<span data-ttu-id="7c7f2-2029">*バージョン 1803 (ビルド 9126.2116)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2029">*Version 1803 (Build 9126.2116)*</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="7c7f2-2030">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2030">Excel: Feature updates</span></span>
-   <span data-ttu-id="7c7f2-p368">**Microsoft Translator:** Microsoft Translator を使用して、単語、フレーズ、または文章を別の言語に翻訳します。これは、リボンの [校閲] タブから実行できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p368">**Microsoft Translator:** Translate words, phrases or sentences to another language with Microsoft Translator. You can do this from the Review tab in the ribbon.</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="7c7f2-2033">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2033">Excel: Non-security updates</span></span>
-   <span data-ttu-id="7c7f2-2034">Outlook メールに添付された Excel ブックのクイック印刷が機能しない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2034">Fix an issue where Quick Print of an Excel workbook attached to an Outlook email may not print.</span></span>
-   <span data-ttu-id="7c7f2-2035">ハイパーリンクをクリックすると Excel がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2035">Fix an issue where clicking on a hyperlink may cause Excel to crash.</span></span>
-   <span data-ttu-id="7c7f2-2036">キューブ関数を使用すると、Excel がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2036">Fix an issue where using cube functions causes Excel to crash.</span></span>

### <a name="onedrive-for-business-non-security-updates"></a><span data-ttu-id="7c7f2-2037">OneDrive for Business: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2037">OneDrive for Business: Non-security updates</span></span>
-   <span data-ttu-id="7c7f2-2038">延長期間にタスク マネージャーで OneDrive for Business (Groove.exe) が 1 つの CPU コアの CPU の価値を消費する (4 コア CPU の 25% など) 問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2038">Fix an issue where OneDrive for Business (Groove.exe) consumes one CPU core’s worth of CPU (for example, 25% on a 4 core CPU) in Task Manager for extended periods of time.</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="7c7f2-2039">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2039">Outlook: Feature updates</span></span>
-   <span data-ttu-id="7c7f2-2040">**ブラインド カーボン コピー (Bcc) 警告:** BCC で受け取ったメッセージに対し [全員に返信] を選択した場合に警告が表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2040">**Blind carbon copy (Bcc) warning:** A warning appears if you choose Reply All to a message that you were Bcc’ed on.</span></span>
-   <span data-ttu-id="7c7f2-p369">**洗練された [宛先] 行:** メッセージの宛先を指定するために [宛先] 行をクリックすると、選択されそうな受信者の候補が表示されます。さらに、その人たちの画像が表示されるので、正しい人に送信しようとしていることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p369">**A smarter To: line:** When you click the To: line to address a message, we suggest recipients you're likely to choose. Plus, you can see their picture, so you know yo’re sending to the right person.</span></span> 

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="7c7f2-2043">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2043">PowerPoint: Feature updates</span></span>
-   <span data-ttu-id="7c7f2-p370">**Microsoft Translator:** Microsoft Translator を使用して、単語、フレーズ、または文章を別の言語に翻訳します。これは、リボンの [校閲] タブから実行できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p370">**Microsoft Translator:** Translate words, phrases or sentences to another language with Microsoft Translator. You can do this from the Review tab in the ribbon.</span></span>
-   <span data-ttu-id="7c7f2-p371">**改善された高解像度ディスプレイのサポート**: 複数のモニター、またはドッキングでラップトップを使用する場合、各ディスプレイの倍率設定が異なっていても Office アプリがすべてのディスプレイで鮮明に表示されるようになります。 [詳細情報](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p371">**Improved support for high definition displays**: If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings. [Learn more](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="7c7f2-2048">Skype for Business: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2048">Skype for Business: Non-security updates</span></span>
-   <span data-ttu-id="7c7f2-2049">会議で [Skype 通話] を選択してユーザーを追加するとエラーが発生する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2049">Fix an issue where adding users by selecting 'Skype Call' in a meeting causes an error.</span></span>
-   <span data-ttu-id="7c7f2-2050">Skype Room が場所として追加され、会議に既にチーム会議の座標が含まれている場合、会議に Skype 座標を追加するかどうかを確認するユーザー プロンプトを削除します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2050">Remove prompt asking user to add Skype coordinates to a meeting, if a Skype Room is added as the location and the meeting already contains Teams meeting coordinates.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="7c7f2-2051">Visio: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2051">Visio: Feature updates</span></span>
-   <span data-ttu-id="7c7f2-p372">**改善された高解像度ディスプレイのサポート**: 複数のモニター、またはドッキングでラップトップを使用する場合、各ディスプレイの倍率設定が異なっていても Office アプリがすべてのディスプレイで鮮明に表示されるようになります。 [詳細情報](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p372">**Improved support for high definition displays**: If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings. [Learn more](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="7c7f2-2054">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2054">Word: Feature updates</span></span>
-   <span data-ttu-id="7c7f2-p373">**改善された高解像度ディスプレイのサポート**: 複数のモニター、またはドッキングでラップトップを使用する場合、各ディスプレイの倍率設定が異なっていても Office アプリがすべてのディスプレイで鮮明に表示されるようになります。 [詳細情報](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p373">**Improved support for high definition displays**: If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings. [Learn more](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span></span>


## <a name="version-1802-march-13"></a><span data-ttu-id="7c7f2-2057">バージョン 1802: 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2057">Version 1802: March 13</span></span>
<span data-ttu-id="7c7f2-2058">*バージョン 1802 (ビルド 9029.2253)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2058">*Version 1802 (Build 9029.2253)*</span></span>

### <a name="access-security-updates"></a><span data-ttu-id="7c7f2-2059">Access: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2059">Access: Security updates</span></span>
-   <span data-ttu-id="7c7f2-2060">[CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903): Microsoft Access のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2060">[CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903): Microsoft Access Remote Code Execution Vulnerability</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="7c7f2-2061">Excel: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2061">Excel: Security updates</span></span>
-   <span data-ttu-id="7c7f2-2062">[CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): Microsoft Office Excel のセキュリティ機能のバイパス</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2062">[CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): Microsoft Office Excel Security Feature Bypass</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="7c7f2-2063">Word: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2063">Word: Security updates</span></span>
-   <span data-ttu-id="7c7f2-2064">[CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919): Microsoft Office の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2064">[CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919): Microsoft Office Information Disclosure Vulnerability</span></span>


## <a name="version-1802-february-26"></a><span data-ttu-id="7c7f2-2065">バージョン 1802: 2 月 26 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2065">Version 1802: February 26</span></span>
<span data-ttu-id="7c7f2-2066">*バージョン 1802 (ビルド 9029.2167)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2066">*Version 1802 (Build 9029.2167)*</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="7c7f2-2067">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2067">Outlook: Feature updates</span></span>
-   <span data-ttu-id="7c7f2-2068">**会議出席者を確認する:** 開催者でなくても、会議出席依頼に対する他のユーザーの応答を確認できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2068">**Know who you'll be meeting with:** You can see other people's responses to a meeting request, even if you aren't the organizer.</span></span>
-   <span data-ttu-id="7c7f2-2069">**簡単にメールを並べ替える:** フィードバックにお答えし、メッセージ一覧の上に並べ替えを戻し、優先受信トレイを使用していないユーザーのために未読フィルターを戻しました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2069">**Sort your email with ease:** Thanks to your feedback, we've brought back sorting above the message list and the Unread filter for people who don't use Focused Inbox.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="7c7f2-2070">Project: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2070">Project: Non-security updates</span></span>
-   <span data-ttu-id="7c7f2-2071">あるセッションで複数のベースラインを設定すると、MOD\_DATE の値が同じになるという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2071">Fix an issue where setting more than one baseline in a session sets the MOD\_DATE value as the same.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="7c7f2-2072">Skype for Business: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2072">Skype for Business: Non-security updates</span></span>
-   <span data-ttu-id="7c7f2-2073">UseLocationForE911Only が true に設定されている場合でも、場所が設定されるという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2073">Fix an issue where location is populated even when UseLocationForE911Only is set to true.</span></span>
-   <span data-ttu-id="7c7f2-2074">"会議センターを使用して通話する" オプションを使用して参加者一覧にあるユーザーを招待する際に、Skype for Business が停止する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2074">Fix an issue where Skype for Business hangs when using the "call using conference center" option to invite users from the roster.</span></span>
-   <span data-ttu-id="7c7f2-2075">Skype for Business 会議の作成中に、ターミナル サーバー上で動作している Outlook がフリーズする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2075">Fix an issue where Outlook running on terminal server freezes while creating a Skype for Business meeting.</span></span>
-   <span data-ttu-id="7c7f2-2076">EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket の既定値を TRUE に変更します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2076">Change the default value of EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket to TRUE.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="7c7f2-2077">Visio: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2077">Visio: Feature updates</span></span>
-   <span data-ttu-id="7c7f2-p374">**組み込みのデータベース モデル図:** 新しいデータベース モデルのテンプレートを使用して、データベースを Visio 図面として正確にモデル化します。アドインは必要ありません。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p374">**Built-in database model diagrams:** Use the new Database Model Diagram template to accurately model your database as a Visio diagram. No add-in required.</span></span>
-   <span data-ttu-id="7c7f2-2080">**ビジネス用ダイアグラムのその他のステンシル:** 現代的な図形を使用して、データをベン図表と比較対照したり、循環、マトリックス、ピラミッド型図表を描いたりして、考えをわかりやすく伝えることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2080">**More stencils for business diagrams:** Using modern shapes, compare and contrast data with a Venn diagram, or draw Cycle, Matrix, or Pyramid diagrams to help tell your story.</span></span>
-   <span data-ttu-id="7c7f2-2081">**ダイアグラムとソースの同期を維持:** Visio でデータ ビジュアライザーのダイアグラムを編集する場合、リンクされた Excel ソース データを最新のダイアグラム コンテンツに更新することができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2081">**Keep your diagram and source in sync:** When you edit a Data Visualizer diagram in Visio, you have the option to update the linked Excel source data with the latest diagram content.</span></span>


## <a name="version-1801-february-13"></a><span data-ttu-id="7c7f2-2082">バージョン 1801: 2 月 13 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2082">Version 1801: February 13</span></span>
<span data-ttu-id="7c7f2-2083">*バージョン 1801 (ビルド 9001.2171)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2083">*Version 1801 (Build 9001.2171)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="7c7f2-2084">Excel: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2084">Excel: Security updates</span></span>
-   <span data-ttu-id="7c7f2-2085">[CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2085">[CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="7c7f2-2086">Outlook: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2086">Outlook: Security updates</span></span>
-   <span data-ttu-id="7c7f2-2087">[CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850): Microsoft Outlook 特権の昇格の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2087">[CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850): Microsoft Outlook Elevation of Privilege Vulnerability</span></span>
-   <span data-ttu-id="7c7f2-2088">[CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852): Microsoft Outlook のメモリ破損の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2088">[CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852): Microsoft Outlook Memory Corruption Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="7c7f2-2089">Office スイート: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2089">Office suite: Security updates</span></span>
-   <span data-ttu-id="7c7f2-2090">[CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851): Microsoft Office のメモリ破損の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2090">[CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="7c7f2-2091">[CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853): Microsoft Office の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2091">[CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853): Microsoft Office Information Disclosure Vulnerability</span></span>


## <a name="version-1801-february-7"></a><span data-ttu-id="7c7f2-2092">バージョン 1801: 2 月 7 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2092">Version 1801: February 7</span></span>
<span data-ttu-id="7c7f2-2093">*バージョン 1801 (ビルド 9001.2144)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2093">*Version 1801 (Build 9001.2144)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="7c7f2-2094">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2094">Excel: Non-security updates</span></span>
-   <span data-ttu-id="7c7f2-2095">Excel で、編集の言語が日本語、中国語、韓国語のいずれかの場合に、[ホーム] タブで新しいフォントを選ぼうとしたり、編集したりするときにフリーズするという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2095">Fix an issue where, if your editing language is Japanese, Chinese, or Korean, Excel may freeze when you try to choose a new font on the Home tab or when you edit.</span></span>


## <a name="version-1801-february-1"></a><span data-ttu-id="7c7f2-2096">バージョン 1801: 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2096">Version 1801: February 1</span></span>
<span data-ttu-id="7c7f2-2097">*バージョン 1801 (ビルド 9001.2138)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2097">*Version 1801 (Build 9001.2138)*</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="7c7f2-2098">Project: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2098">Project: Non-security updates</span></span>
-   <span data-ttu-id="7c7f2-2099">[共有用に保存] セッションで実績作業時間が削除された後にも、実績作業時間がレポート テーブルに表示されるという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2099">Fix an issue where Actual Work is still shown in the reporting tables after being removed in a Save for Sharing session.</span></span>
-   <span data-ttu-id="7c7f2-2100">スケジュール設定するときに週の日付形式を使用するとエラーが返されるというドイツ語での問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2100">Fix an issue in the German language version where using a Weeks date format returns an error when scheduling.</span></span>
-   <span data-ttu-id="7c7f2-2101">スケジュール Web パーツで終了日を編集すると、タスクが時間範囲で配分されるのではなく、1 日に 8 時間ずつ割り当てられるという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2101">Fix an issue where, when editing finish dates in Schedule Web Part, tasks stay at 8 hours per day instead of being spread over time.</span></span>
-   <span data-ttu-id="7c7f2-2102">"進捗点の形状" が予期しない場所に描画されるという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2102">Fix an issue where "Progress point shape" is drawn at an unexpected location.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="7c7f2-2103">Skype for Business: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2103">Skype for Business: Non-security updates</span></span>
-   <span data-ttu-id="7c7f2-2104">会議が全画面表示モードの場合に [その他のオプション] ボタンと [さらに参加者を招待] ボタンが非表示になる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2104">Fix an issue where "More Options" and "Invite More People" buttons are hidden when a meeting is in full-screen mode.</span></span>
-   <span data-ttu-id="7c7f2-2105">P2P 音声通話ウィンドウまたは電話会議ウィンドウが、参加しようとすると透明になるという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2105">Fix an issue where the P2P audio call window or conference call window becomes transparent when you attempt to join.</span></span>
-   <span data-ttu-id="7c7f2-2106">近日開催される Skype 会議が [会議] タブに表示されない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2106">Fix an issue where upcoming Skype meetings do not show up in the meetings tab.</span></span>
-   <span data-ttu-id="7c7f2-2107">Skype for Business が音声なしの状態で会議に参加するよう構成されている場合、会議に音声を追加しようとすると、既存の会議に音声が追加されるのではなく、自分自身への新たな P2P 通話が開始される問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2107">Fix an issue where, when Skype for Business is configured to join meetings without audio, adding audio to a meeting initiates a new P2P call to the user itself rather than adding audio to the existing meeting.</span></span>
-   <span data-ttu-id="7c7f2-2108">Outlook から会議出席依頼の [Skype 会議への参加] リンクをクリックすると、「この Skype 会議が見つかりませんでした」というエラー メッセージが表示される問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2108">Fix an issue where user receives the error message "We couldn't find this Skype meeting" when clicking 'Join Skype Meeting' link in a meeting request from Outlook.</span></span>


## <a name="version-1712-january-30"></a><span data-ttu-id="7c7f2-2109">バージョン 1712: 1 月 30 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2109">Version 1712: January 30</span></span>
<span data-ttu-id="7c7f2-2110">*バージョン 1712 (ビルド 8827.2179)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2110">*Version 1712 (Build 8827.2179)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="7c7f2-2111">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2111">Excel: Non-security updates</span></span>
-   <span data-ttu-id="7c7f2-2112">Excel が最小化されているときにブックを開くとスクロールバーが表示されない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2112">Fix and issue where the scroll bars are missing when a workbook is opened when Excel is minimized.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="7c7f2-2113">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2113">Outlook: Non-security updates</span></span>
-   <span data-ttu-id="7c7f2-2114">検索範囲がすべてのメールボックスの場合、「一致する項目が見つかりませんでした」と表示されて検索できない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2114">Fix an issue where search fails with “No matches found” when search is scoped to All Mailboxes.</span></span>


## <a name="version-1712-january-17"></a><span data-ttu-id="7c7f2-2115">バージョン 1712: 1 月 17 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2115">Version 1712: January 17</span></span>
<span data-ttu-id="7c7f2-2116">*バージョン 1712 (ビルド 8827.2148)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2116">*Version 1712 (Build 8827.2148)*</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="7c7f2-2117">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2117">Excel: Feature updates</span></span>
-   <span data-ttu-id="7c7f2-2118">**SVG アイコンを図形に変換する:** すべての SVG の画像とアイコンを Office の図形に変換して、色、サイズ、テクスチャを変更できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2118">**Convert SVG icons to shapes:** Transform all SVG pictures and icons into Office shapes so you can change their color, size, or texture.</span></span>
-   <span data-ttu-id="7c7f2-2119">**セルを選択解除する:** ワークシートで選択を行い、間違ってクリックしたセルを選択解除します。最初からやり直す必要はありません。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2119">**Deselect cells:** Make selections in your worksheet and deselect cells that you accidentally clicked without having to start over.</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="7c7f2-2120">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2120">Excel: Non-security updates</span></span>
-   <span data-ttu-id="7c7f2-2121">ファイル エクスプローラーでファイル名をダブルクリックして複数のブックを開くときに、ブックの参照が失敗する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2121">Fix an issue where workbook references fail when opening multiple workbooks by double-clicking on the file names in File Explorer.</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="7c7f2-2122">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2122">Outlook: Feature updates</span></span>
-   <span data-ttu-id="7c7f2-2123">**SVG アイコンを図形に変換する:** すべての SVG の画像とアイコンを Office の図形に変換して、色、サイズ、テクスチャを変更できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2123">**Convert SVG icons to shapes:** Transform all SVG pictures and icons into Office shapes so you can change their color, size, or texture.</span></span>
-   <span data-ttu-id="7c7f2-2124">**Office 365 グループの機能強化:** グループ メッセージをダブルクリックして、独自のウィンドウで開くことができるので、これまで以上にグループ会話を読んで返信することが簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2124">**Improvements to Office 365 groups:** It’s easier than ever to read and reply to group conversations because you can double-click on a group message to open it in its own window.</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="7c7f2-2125">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2125">PowerPoint: Feature updates</span></span>
-   <span data-ttu-id="7c7f2-2126">**3D アニメーション:** 優しく揺らしたり、ジャンプして回転させたりするなど、アニメーションを使用して 3D モデルを生き生きとしたものにできます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2126">**3D animations:** Bring your 3D models to life with animations such as swinging gently or jumping and turning.</span></span>
-   <span data-ttu-id="7c7f2-2127">**SVG アイコンを図形に変換する:** すべての SVG の画像とアイコンを Office の図形に変換して、色、サイズ、テクスチャを変更できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2127">**Convert SVG icons to shapes:** Transform all SVG pictures and icons into Office shapes so you can change their color, size, or texture.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="7c7f2-2128">Skype for Business: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2128">Skype for Business: Non-security updates</span></span>
-   <span data-ttu-id="7c7f2-2129">着信の PSTN 呼び出しのトースト UI に通話の転送ボタンを追加します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2129">Add call transfer button in the toast UI for incoming PSTN calls.</span></span>
-   <span data-ttu-id="7c7f2-2130">ChatDefaultClient と CallDefaultClient がチームに設定されているとき、通話とチャットがチームに送信されていることをユーザーに通知します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2130">Notify users that calls and chat are being sent to Teams when ChatDefaultClient and CallDefaultClient are set to Teams.</span></span>
-   <span data-ttu-id="7c7f2-2131">会議に参加しておらず、Skype for Business で無効になっており、会議参加エクスペリエンスが [Native Limited Client] に設定されているユーザーの場合、ユーザーのプレゼンスは [オフライン] と表示されます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2131">Show user’s presence as Offline when user is not in a meeting and disabled from Skype for Business and meeting join experience is set to Native Limited Client.</span></span>
-   <span data-ttu-id="7c7f2-2132">Skype for Business が通知エリアに最小化されているときに、[開く] および [終了] 以外のすべてのオプションを無効にします。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2132">Disable all options except Open and Exit when Skype for Business is minimized to the notification area.</span></span> 
-   <span data-ttu-id="7c7f2-2133">Aries の電話と RedirectClient とのペアリングが有効である場合、新しい通話と会話を表示しません。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2133">Suppress new calls and conversations when paired with Aries phones and RedirectClient is enabled.</span></span>
-   <span data-ttu-id="7c7f2-2134">日付形式が US 形式 (mm/dd/yy) 以外の場合、日付を使った PChat のメッセージの検索が失敗する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2134">Fix an issue where searching messages in PChat by date fails when the date format is other than US format (mm/dd/yy).</span></span>
-   <span data-ttu-id="7c7f2-2135">EnableExternalP2PFileTransfer ポリシーが false に設定されている場合でも、ユーザーが引き続き会議にファイルを添付できる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2135">Fix an issue where, when EnableExternalP2PFileTransfer policy is set to false, users are still able to attach files in meetings.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="7c7f2-2136">Visio: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2136">Visio: Feature updates</span></span>
-   <span data-ttu-id="7c7f2-p375">**Excel テンプレートを使用して、Visio 図面にエクスポートします。** Visio フローチャートに移動します。プロセス マップの Excel テンプレートのいずれかにデータを入力し、Visio にエクスポートすると、図面が自動的に作成されます。Visio Pro for Office 365 が必要です。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-p375">**Use Excel templates to export to a Visio diagram:** Get a jump on your Visio flowcharts. Enter your data in one of the Process Map Excel templates and export to Visio to create the diagram automatically. Requires Visio Pro for Office 365.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="7c7f2-2140">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2140">Word: Feature updates</span></span>
-   <span data-ttu-id="7c7f2-2141">**SVG アイコンを図形に変換する:** すべての SVG の画像とアイコンを Office の図形に変換して、色、サイズ、テクスチャを変更できます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2141">**Convert SVG icons to shapes:** Transform all SVG pictures and icons into Office shapes so you can change their color, size, or texture.</span></span>


## <a name="version-1711-january-9"></a><span data-ttu-id="7c7f2-2142">バージョン 1711: 1 月 9 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2142">Version 1711: January 9</span></span>
<span data-ttu-id="7c7f2-2143">*バージョン 1711 (ビルド 8730.2175)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2143">*Version 1711 (Build 8730.2175)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="7c7f2-2144">Excel: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2144">Excel: Security updates</span></span>
-   <span data-ttu-id="7c7f2-2145">[CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2145">[CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="7c7f2-2146">[アドバイザリ 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Microsoft Office 多層防御の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2146">[Advisory 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Microsoft Office Defense in Depth Update</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="7c7f2-2147">Outlook: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2147">Outlook: Security updates</span></span>
-   <span data-ttu-id="7c7f2-2148">[CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791): Microsoft Outlook のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2148">[CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="7c7f2-2149">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2149">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook Remote Code Execution Vulnerability</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="7c7f2-2150">Word: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2150">Word: Security updates</span></span>
-   <span data-ttu-id="7c7f2-2151">[CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792): Microsoft Word のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2151">[CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="7c7f2-2152">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2152">[CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="7c7f2-2153">[CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794): Microsoft Word のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2153">[CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="7c7f2-2154">[CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798): Microsoft Office のメモリ破損の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2154">[CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="7c7f2-2155">[CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801): Microsoft Office のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2155">[CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="7c7f2-2156">[CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802): Microsoft Office のメモリ破損の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2156">[CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="7c7f2-2157">[CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804): Microsoft Word のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2157">[CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="7c7f2-2158">[CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805): Microsoft Word のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2158">[CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="7c7f2-2159">[CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806): Microsoft Word のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2159">[CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="7c7f2-2160">[CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807): Microsoft Word のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2160">[CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="7c7f2-2161">[CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812): Microsoft Word のメモリ破損の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2161">[CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812): Microsoft Word Memory Corruption Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="7c7f2-2162">Office スイート: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2162">Office suite: Security updates</span></span>
-   <span data-ttu-id="7c7f2-2163">[CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795): Microsoft Office のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2163">[CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="7c7f2-2164">[アドバイザリ 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003): Microsoft Office 多層防御の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2164">[Advisory 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003): Microsoft Office Defense in Depth Update</span></span>


## <a name="version-1711-january-2"></a><span data-ttu-id="7c7f2-2165">バージョン 1711: 1 月 2 日</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2165">Version 1711: January 2</span></span>
<span data-ttu-id="7c7f2-2166">*バージョン 1711 (ビルド 8730.2165)*</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2166">*Version 1711 (Build 8730.2165)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="7c7f2-2167">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2167">Excel: Non-security updates</span></span>
-   <span data-ttu-id="7c7f2-2168">ピボットテーブルのプログラムによる作成の後にプログラムによる更新が行われると、Excel がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2168">Fix an issue where the programmatic creation of a PivotTable followed by a programmatic refresh causes Excel to crash.</span></span>
-   <span data-ttu-id="7c7f2-2169">プログラムで Workbook.Open() を呼び出すと、Excel がクラッシュする可能性がある問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2169">Fix an issue where programmatically calling Workbook.Open() may cause Excel to crash.</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="7c7f2-2170">PowerPoint: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2170">PowerPoint: Non-security updates</span></span>
-   <span data-ttu-id="7c7f2-2171">ドキュメント プロパティと個人情報を削除すると、SharePoint への保存が失敗する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2171">Fix an issue where removing document properties and personal information causes saving to SharePoint to fail.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="7c7f2-2172">Project: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2172">Project: Non-security updates</span></span>
-   <span data-ttu-id="7c7f2-2173">VBA コードがプロジェクトから失われる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2173">Fix an issue where VBA code gets lost from projects.</span></span>



> [!NOTE]
> <span data-ttu-id="7c7f2-2174">Office の使用で問題がある場合は、[Microsoft の回答フォーラム](https://answers.microsoft.com/)に関するページまたは「[Microsoft Tech Community](https://techcommunity.microsoft.com/)」に質問を投稿するか、[サポート](https://support.microsoft.com/contactus)に問い合わせてサポートを受けることができます。</span><span class="sxs-lookup"><span data-stu-id="7c7f2-2174">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>