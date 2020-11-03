---
title: 2020 年の最新のチャネル リリースのリリース ノート
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Microsoft 365 Apps 用の 2020 年の月次チャネル リリースのリリース ノートを IT 担当者に提供します
ms.openlocfilehash: 82e056874fbe4e95247e6b5ccb09accdfcc98816
ms.sourcegitcommit: 8b12ed0c94df66ae0220e8c6e2e4c957d4c64e75
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 11/02/2020
ms.locfileid: "48830328"
---
# <a name="release-notes-for-current-channel-releases-in-2020"></a><span data-ttu-id="2154d-103">2020 年の最新のチャネル リリースのリリース ノート</span><span class="sxs-lookup"><span data-stu-id="2154d-103">Release notes for Current Channel releases in 2020</span></span>

<span data-ttu-id="2154d-104">このリリース ノートには、2020 年の最新チャネルの更新プログラムに含まれる新機能と、セキュリティ以外の更新プログラムに関する情報が記載されています。対象となるのは、Microsoft 365 Apps for enterprise、Microsoft 365 Apps for business、および Project と Visio のデスクトップ アプリのサブスクリプション版です。</span><span class="sxs-lookup"><span data-stu-id="2154d-104">These release notes provide information about new features and non-security updates that are included in Current Channel updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="2154d-p101">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="2154d-p101">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

 > [!NOTE]
>
>- <span data-ttu-id="2154d-107">Microsoft では多くの場合、現在の一定期間にわたって、機能 (および場合によっては修正プログラム) を展開します。</span><span class="sxs-lookup"><span data-stu-id="2154d-107">We often roll out features (and sometimes even fixes) to Current over a period of time.</span></span>  <span data-ttu-id="2154d-108">ここで説明した内容がすぐに表示されない場合は、間もなく利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="2154d-108">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="2154d-109">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-109">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
>- <span data-ttu-id="2154d-110">Microsoft Teams の機能は、リリース頻度が高いため、最新のCurrent Channel とは異なる場合があります。</span><span class="sxs-lookup"><span data-stu-id="2154d-110">Microsoft Teams features may differ from the latest Current Channel released as they have a more frequent release cadence.</span></span>




[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-october-27"></a><span data-ttu-id="2154d-113">バージョン 2010: 10 月 27 日</span><span class="sxs-lookup"><span data-stu-id="2154d-113">Version 2010: October 27</span></span>
<span data-ttu-id="2154d-114">*バージョン 2010 (ビルド 13328.20292)*</span><span class="sxs-lookup"><span data-stu-id="2154d-114">*Version 2010 (Build 13328.20292)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2154d-116">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2154d-116">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2154d-117">Access</span><span class="sxs-lookup"><span data-stu-id="2154d-117">Access</span></span>

- <span data-ttu-id="2154d-118">**時代に追いつきましょう! 日付/時刻の拡張データ型では、より精度が高くなります。:** 改良されたデータ型をご紹介します。</span><span class="sxs-lookup"><span data-stu-id="2154d-118">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span> <span data-ttu-id="2154d-119">SQL との構文の互換性を高め、日付と時刻を含むレコードの精度と詳細レベルを向上させるため、Access に DateTime2 データ型を実装しています。</span><span class="sxs-lookup"><span data-stu-id="2154d-119">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="2154d-120">この追加の日付および時間のデータ型には、より大きい日付範囲 (0001-01-01 ～ 9999-12-31) が含まれます。これにより、指定された時間の精度 (秒単位ではなくナノ秒) で提供され、計算を実行できるようになります。</span><span class="sxs-lookup"><span data-stu-id="2154d-120">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="2154d-121">有効にするには、[新しいフィールド] > [日付と時間の拡張] を選択します。</span><span class="sxs-lookup"><span data-stu-id="2154d-121">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="2154d-122">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-122">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="2154d-123">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-123">Excel</span></span>

- <span data-ttu-id="2154d-124">**Power Query を使用してデータ型を作成する:** Power Query を使用してあらゆるデータ ソースから豊富なデータ型を作成します。</span><span class="sxs-lookup"><span data-stu-id="2154d-124">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source.</span></span> [<span data-ttu-id="2154d-125">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-125">Learn more</span></span>](https://support.office.com/article/a465a3b7-3d37-4eb1-a59c-bd3163315308)<br /><span data-ttu-id="2154d-126">[ブログの投稿](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2154d-126">See details in [blog post](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)</span></span>

- <span data-ttu-id="2154d-127">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-127">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="2154d-128">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="2154d-128">No conversion required.</span></span><br /><span data-ttu-id="2154d-129">[ブログ記事](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2154d-129">See details in [blog post](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="2154d-130">**アクション ペンを使用してすばやく編集する:** アクション ペンを使用すると、セルに直接手書きで書き込み、自動的に Excel データに変換されるインクでデータを書き留めることができます。</span><span class="sxs-lookup"><span data-stu-id="2154d-130">**Make quick edits using the action pen:** With the action pen, you can write by hand directly in the cells, jot down data with ink that gets automatically converted to Excel data.</span></span>

### <a name="outlook"></a><span data-ttu-id="2154d-131">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-131">Outlook</span></span>

- <span data-ttu-id="2154d-132">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-132">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="2154d-133">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="2154d-133">No conversion required.</span></span><br /><span data-ttu-id="2154d-134">[ブログ記事](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2154d-134">See details in [blog post](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="2154d-135">**文章校正による支援:** Outlook では、入力中に文章校正のエラーが表示されます。シングル クリックで候補を適用できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-135">**Grammar checking's got your back:** Outlook marks grammar errors as you type, so you can apply suggestions with a single click.</span></span> [<span data-ttu-id="2154d-136">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-136">Learn more</span></span>](https://support.office.com/article/ddbadc42-4637-451d-b3f4-ecf295036fa9)<br /><span data-ttu-id="2154d-137">[ブログの投稿](https://insider.office.com/en-us/blog/grammar-and-style-suggestions-available-in-outlook)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2154d-137">See details in [blog post](https://insider.office.com/en-us/blog/grammar-and-style-suggestions-available-in-outlook)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2154d-138">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2154d-138">PowerPoint</span></span>

- <span data-ttu-id="2154d-139">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-139">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="2154d-140">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="2154d-140">No conversion required.</span></span><br /><span data-ttu-id="2154d-141">[ブログの投稿](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2154d-141">See details in [blog post](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="teams"></a><span data-ttu-id="2154d-142">Teams</span><span class="sxs-lookup"><span data-stu-id="2154d-142">Teams</span></span>

- <span data-ttu-id="2154d-143">**Microsoft Teams のテンプレート:** Teams のテンプレートを使用すると、ユーザーは新しいチームを作成するときにさまざまなカスタマイズ可能なテンプレートから選択できるため、すばやく開始できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-143">**Templates in Microsoft Teams:** With Templates in Teams, users can choose from a variety of customizable templates when creating a new team, helping them get started quickly.</span></span> <span data-ttu-id="2154d-144">IT 担当者は、組織の新しいカスタム テンプレートを作成して、チーム構造を標準化し、関連するアプリを表示し、ベスト プラクティスを拡張することもできます。</span><span class="sxs-lookup"><span data-stu-id="2154d-144">IT professionals can also create new custom templates for their organization, allowing them to standardize team structures, surface relevant apps, and scale best practices.</span></span>

- <span data-ttu-id="2154d-145">**ピン留めされた投稿:** この機能を使用すると、ユーザーはチャネル内のメッセージをチャネル情報ペインに「ピン留め」して、チャネルのすべてのメンバーに表示させることができます。</span><span class="sxs-lookup"><span data-stu-id="2154d-145">**Pinned Posts:** This feature allows users to "pin" any message in a channel to the channel info pane for all members of the channel to see.</span></span> <span data-ttu-id="2154d-146">チャネルにアクセスできるメンバーは誰でも、ピン留めされたメッセージを見ることができます。</span><span class="sxs-lookup"><span data-stu-id="2154d-146">Any members who have access to the channel will be able to see pinned messages.</span></span> <span data-ttu-id="2154d-147">チャネルのすべてのメンバーは、(チャネルのモデレート設定でオフにされていない限り) 任意のメッセージをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="2154d-147">Any member of a channel will be able to pin any message (unless turned off via channel moderation settings).</span></span>

- <span data-ttu-id="2154d-148">**アプリ カタログに送信:** この画面の左下に [アプリ カタログに送信] リンクが表示されます。</span><span class="sxs-lookup"><span data-stu-id="2154d-148">**Submit to app catalog:** You’ll see a Submit to app catalog link on the lower left of this screen.</span></span> <span data-ttu-id="2154d-149">App Studio と Visual Studio に加えて、承認のためにアプリを送信できるもう 1 つの場所です。</span><span class="sxs-lookup"><span data-stu-id="2154d-149">In addition to App Studio and Visual Studio, it’s another place where you can submit apps for approval.</span></span>

- <span data-ttu-id="2154d-150">**InVision によるフリーハンドを使用して、ポップアウトされた会議エクスペリエンスでホワイトボードを作成する:** InVision によるフリーハンド アプリを使用して、ポップアウトされた会議エクスペリエンスでホワイトボードを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-150">**Use Freehand by Invision to whiteboard in the popped out meeting experience:** You can now use the Freehand by Invision app to whiteboard in any meeting you take in the popped out meeting experience.</span></span> <span data-ttu-id="2154d-151">共有コンテンツ トレイからフリーハンド アプリを選択してインストールし、同僚とのホワイトボード セッションを開始することで、シームレスにブレーンストーミングを開始できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-151">Seamlessly start brainstorming by selecting the Freehand app from the share content tray and, installing it, and starting the whiteboarding session with your colleagues!</span></span>

### <a name="word"></a><span data-ttu-id="2154d-152">Word</span><span class="sxs-lookup"><span data-stu-id="2154d-152">Word</span></span>

- <span data-ttu-id="2154d-153">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-153">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="2154d-154">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="2154d-154">No conversion required.</span></span><br /><span data-ttu-id="2154d-155">[ブログの投稿](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2154d-155">See details in [blog post](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-158">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-158">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2154d-159">Access</span><span class="sxs-lookup"><span data-stu-id="2154d-159">Access</span></span>

- <span data-ttu-id="2154d-160">Office 以外のアプリケーションから DAO を使用すると、アプリケーションが予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-160">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="outlook"></a><span data-ttu-id="2154d-161">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-161">Outlook</span></span>

- <span data-ttu-id="2154d-162">返信または転送時に中国語メッセージのヘッダーが読み取れなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-162">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="2154d-163">OFT ファイルとして保存するときに中国語の文字が疑問符に変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-163">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="2154d-164">クラウド設定を有効にしているユーザーに対して、2つ目の空白の署名を作成するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2154d-164">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


- <span data-ttu-id="2154d-165">ユーザーに対してクラウド設定が既定でオンにならない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-165">We fixed a n issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="2154d-166">ユーザーの署名への変更が保存できない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-166">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2154d-167">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2154d-167">PowerPoint</span></span>

- <span data-ttu-id="2154d-168">これは、PresentationBeforeClose イベントを聞き、イベント ハンドラーの一部として Presentation.Saved プロパティをチェックするアドインがある場合、ドキュメントを閉じるときに保存プロンプトがループで表示される問題の修正です。</span><span class="sxs-lookup"><span data-stu-id="2154d-168">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


### <a name="project"></a><span data-ttu-id="2154d-169">Project</span><span class="sxs-lookup"><span data-stu-id="2154d-169">Project</span></span>

- <span data-ttu-id="2154d-170">プロジェクトを PWA からローカル mpp ファイルに保存すると、ユーザーが実際に変更していないデータに対して ProjectBeforeTaskChangeEvent が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-170">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="2154d-171">リソースの配分状況が特定の方法で指定されているファイルを開くと、Project が予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-171">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="2154d-172">プロジェクトを PWA からローカル mpp ファイルに保存すると、ユーザーが実際に変更していないデータに対して ProjectBeforeTaskChangeEvent が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-172">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="2154d-173">タスクフォームタイプビュー内でラグが変更された場合、ProjectBeforeTaskChagne イベントの NewVal に正しい値がない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-173">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2154d-174">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2154d-174">Office Suite</span></span>

- <span data-ttu-id="2154d-175">Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。</span><span class="sxs-lookup"><span data-stu-id="2154d-175">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="2154d-176">このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。</span><span class="sxs-lookup"><span data-stu-id="2154d-176">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-october-21"></a><span data-ttu-id="2154d-178">バージョン 2009 : 10 月 21 日</span><span class="sxs-lookup"><span data-stu-id="2154d-178">Version 2009: October 21</span></span>
<span data-ttu-id="2154d-179">*バージョン 2009 (ビルド 13231.20418)*</span><span class="sxs-lookup"><span data-stu-id="2154d-179">*Version 2009 (Build 13231.20418)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-181">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-181">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2154d-182">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-182">Outlook</span></span>

- <span data-ttu-id="2154d-183">ユーザーが代理人に編集者権限を付与できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-183">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="2154d-184">ユーザーが検索結果を選択したときにアプリケーションが予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-184">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="2154d-185">返信または転送時に中国語メッセージのヘッダーが読み取れなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-185">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2154d-186">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2154d-186">PowerPoint</span></span>

- <span data-ttu-id="2154d-187">ユーザーが別のスライドをクリックして表示するまで、Forms コンテンツ アドインが挿入後にレンダリングされない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-187">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-october-13"></a><span data-ttu-id="2154d-189">バージョン2009: 10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="2154d-189">Version 2009: October 13</span></span>
<span data-ttu-id="2154d-190">*バージョン2009 (ビルド 13231.20390)*</span><span class="sxs-lookup"><span data-stu-id="2154d-190">*Version 2009 (Build 13231.20390)*</span></span>

<span data-ttu-id="2154d-191">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2154d-191">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-193">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-193">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="2154d-194">Project</span><span class="sxs-lookup"><span data-stu-id="2154d-194">Project</span></span>

- <span data-ttu-id="2154d-195">リソースの配分状況が特定の方法で指定されている場合に、Project がクラッシュすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-195">Fixed an issue where Project may crash on opening files where resource contours were specified in a certain manner.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-october-08"></a><span data-ttu-id="2154d-197">バージョン 2009: 10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="2154d-197">Version 2009: October 08</span></span>
<span data-ttu-id="2154d-198">*バージョン 2009 (ビルド 13231.20368)*</span><span class="sxs-lookup"><span data-stu-id="2154d-198">*Version 2009 (Build 13231.20368)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-200">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-200">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2154d-201">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-201">Outlook</span></span>

- <span data-ttu-id="2154d-202">キャッシュされていない共有の予定表を検索するときに、結果が返されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2154d-202">Addresses an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="2154d-203">一部のユーザーの環境で、Outlook がオフラインの状態で予期せず起動する原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2154d-203">Addresses an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="2154d-204">代理人が別のメールボックスで共有フォルダーを開くと、断続的にエラーが表示される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2154d-204">Addresses an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2154d-205">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2154d-205">PowerPoint</span></span>

- <span data-ttu-id="2154d-206">セキュリティ修正プログラムを適用して、保護ビューで PowerPoint ファイルを開くと、 IRM による保護が無効になる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2154d-206">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2154d-207">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2154d-207">Office Suite</span></span>

- <span data-ttu-id="2154d-208">Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。</span><span class="sxs-lookup"><span data-stu-id="2154d-208">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="2154d-209">このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。</span><span class="sxs-lookup"><span data-stu-id="2154d-209">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-september-28"></a><span data-ttu-id="2154d-211">バージョン 2009: 9 月 28 日</span><span class="sxs-lookup"><span data-stu-id="2154d-211">Version 2009: September 28</span></span>
<span data-ttu-id="2154d-212">*バージョン 2009 (ビルド13231.20262)*</span><span class="sxs-lookup"><span data-stu-id="2154d-212">*Version 2009 (Build 13231.20262)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2154d-214">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2154d-214">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2154d-215">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-215">Excel</span></span>

- <span data-ttu-id="2154d-216">**図形を画像として保存する:** 簡単なクリック操作で図形、アイコン、その他のオブジェクトを画像ファイルとして保存し、別の場所で再利用することができます。</span><span class="sxs-lookup"><span data-stu-id="2154d-216">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="2154d-217">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-217">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="2154d-218">**Power BI からデータ型を使用して組織データを取得する:** Power BI からの Excel データ型が Office 365 E5/A5 または Microsoft 365 E5/A5 を使用する組織の Insider にロールアウトされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-218">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="2154d-219">必要な情報を入手し、簡単に更新することは、多くの日常のワークフローに欠かせません。</span><span class="sxs-lookup"><span data-stu-id="2154d-219">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="2154d-220">Excel のデータ型として、Power BI から会社または組織の情報へのアクセスを提供し、スプレッドシートにリンクされた情報を取り込む機能を拡張します。</span><span class="sxs-lookup"><span data-stu-id="2154d-220">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="2154d-221">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-221">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="2154d-222">[ブログの投稿](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2154d-222">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="2154d-223">**数式で使用する変数を作成する:** LET 関数を使用してパフォーマンス、読みやすさ、および構成性を向上させます。</span><span class="sxs-lookup"><span data-stu-id="2154d-223">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="2154d-224">この関数では、新規または既存の数式に名前付き変数を作成することができます。</span><span class="sxs-lookup"><span data-stu-id="2154d-224">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="2154d-225">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-225">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="2154d-226">[ブログの投稿](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2154d-226">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="2154d-227">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-227">Outlook</span></span>

- <span data-ttu-id="2154d-228">**自動拡張オンライン アーカイブ検索:** 自動拡張オンライン アーカイブ検索を有効にします</span><span class="sxs-lookup"><span data-stu-id="2154d-228">**Auto-Expanding Online Archive Search:** Enabling auto-expanding Online Archive Search</span></span>

- <span data-ttu-id="2154d-229">**Outlook の新しいプロファイル カード:** Outlook の新しいプロファイル カードは、組織ビューの詳細を含み、Outlook Web のカード スタイルに一致します。</span><span class="sxs-lookup"><span data-stu-id="2154d-229">**New profile card for Outlook:** New profile card for Outlook including a better Organization view and matches the card style of Outlook Web.</span></span>

### <a name="teams"></a><span data-ttu-id="2154d-230">Teams</span><span class="sxs-lookup"><span data-stu-id="2154d-230">Teams</span></span>

- <span data-ttu-id="2154d-231">**Microsoft Teams でファイルを共有:** [詳細情報](https://docs.microsoft.com/MicrosoftTeams/sharing-files-in-teams)</span><span class="sxs-lookup"><span data-stu-id="2154d-231">**Sharing files in Microsoft Teams:** [Learn more](https://docs.microsoft.com/MicrosoftTeams/sharing-files-in-teams)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-234">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-234">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2154d-235">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-235">Outlook</span></span>

- <span data-ttu-id="2154d-236">件名が空白の場合、一部の自動的に生成されたメールの本文が空で送信される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2154d-236">Addresses an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2154d-237">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2154d-237">PowerPoint</span></span>

- <span data-ttu-id="2154d-238">特定のデータ オブジェクト タイプ (E2o) を大量に含むファイルの共同編集が遅くなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-238">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>


### <a name="project"></a><span data-ttu-id="2154d-239">Project</span><span class="sxs-lookup"><span data-stu-id="2154d-239">Project</span></span>

- <span data-ttu-id="2154d-240">イベント コードの実行中に、[タスク フォーム] ビューから変更を加えようとするときに、[OK] ボタンをクリックしても変更が反映されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-240">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


### <a name="word"></a><span data-ttu-id="2154d-241">Word</span><span class="sxs-lookup"><span data-stu-id="2154d-241">Word</span></span>

- <span data-ttu-id="2154d-242">スタイル ギャラリー ダイアログの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-242">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2154d-243">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2154d-243">Office Suite</span></span>

- <span data-ttu-id="2154d-244">この変更により、[エクスポート] ボタンをクリックしてもエクスポートされないという [アニメーション GIF にエクスポート] 機能の問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2154d-244">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="2154d-245">この変更では、[図の圧縮] ダイアログで一部のユーザー設定が保持されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-245">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-september-22"></a><span data-ttu-id="2154d-247">バージョン 2008: 9 月 22 日</span><span class="sxs-lookup"><span data-stu-id="2154d-247">Version 2008: September 22</span></span>
<span data-ttu-id="2154d-248">*バージョン 2008 (ビルド 13127.20508)*</span><span class="sxs-lookup"><span data-stu-id="2154d-248">*Version 2008 (Build 13127.20508)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-250">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-250">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2154d-251">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-251">Excel</span></span>

- <span data-ttu-id="2154d-252">シートの一番上の行を固定した後にクイック分析を使用すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-252">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="2154d-253">IFNA () を使用する数式が含まれている場合、破損したワークブックに関する警告を発する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-253">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="2154d-254">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-254">Outlook</span></span>

- <span data-ttu-id="2154d-255">隅にある [X] をクリックして共有の予定表を閉じることができない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2154d-255">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="2154d-256">添付ファイルのアップロードのパフォーマンスの問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2154d-256">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2154d-257">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2154d-257">PowerPoint</span></span>

- <span data-ttu-id="2154d-258">PowerPoint アプリのクラッシュの原因となった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-258">We have fixed an issue which was causing the crash in PowerPoint app.</span></span>


### <a name="visio"></a><span data-ttu-id="2154d-259">Visio</span><span class="sxs-lookup"><span data-stu-id="2154d-259">Visio</span></span>

- <span data-ttu-id="2154d-260">テキストを配置するとリアルタイムのプレビューがクラッシュする問題がお客様から報告されました。</span><span class="sxs-lookup"><span data-stu-id="2154d-260">Live preview crashes on text alignment reported by customers.</span></span> <span data-ttu-id="2154d-261">7 月のフォークで最も多く報告されているクラッシュ。</span><span class="sxs-lookup"><span data-stu-id="2154d-261">Top hitting crash of July fork.</span></span>


### <a name="word"></a><span data-ttu-id="2154d-262">Word</span><span class="sxs-lookup"><span data-stu-id="2154d-262">Word</span></span>

- <span data-ttu-id="2154d-263">スタイル ギャラリー ダイアログの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-263">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2154d-264">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2154d-264">Office Suite</span></span>

- <span data-ttu-id="2154d-265">GIF/アニメーション model3D を使用したアイドル時の高い CPU 使用率を修正</span><span class="sxs-lookup"><span data-stu-id="2154d-265">Fixes high CPU usage on idle with GIF/animated model3D</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-september-09"></a><span data-ttu-id="2154d-267">バージョン 2008: 9 月 9 日</span><span class="sxs-lookup"><span data-stu-id="2154d-267">Version 2008: September 09</span></span>
<span data-ttu-id="2154d-268">*バージョン 2008(ビルド13127.20408)*</span><span class="sxs-lookup"><span data-stu-id="2154d-268">*Version 2008 (Build 13127.20408)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-270">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-270">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2154d-271">Access</span><span class="sxs-lookup"><span data-stu-id="2154d-271">Access</span></span>

- <span data-ttu-id="2154d-272">テキストを編集するため [ズーム] ボックスを起動する (Shift + F2) ときに、Access がクラッシュする可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2154d-272">This change fixes an issue that could cause Access to crash when launching the Zoom box (Shift + F2) to edit text.</span></span>


### <a name="excel"></a><span data-ttu-id="2154d-273">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-273">Excel</span></span>

- <span data-ttu-id="2154d-274">Format Painter を使用すると、特定の状況で Excel がクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-274">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>


### <a name="word"></a><span data-ttu-id="2154d-275">Word</span><span class="sxs-lookup"><span data-stu-id="2154d-275">Word</span></span>

- <span data-ttu-id="2154d-276">図形のサイズを変更すると、ユーザーのコンテンツが失われる場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-276">We fixed an issue where the user might lose content when resize a shape.</span></span>


- <span data-ttu-id="2154d-277">基本スタイルが標準スタイルで更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-277">We fixed an issue which the base styles are not updated with Normal style.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2154d-278">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2154d-278">Office Suite</span></span>

- <span data-ttu-id="2154d-279">この変更では、[図の圧縮] ダイアログで一部のユーザー設定が保持されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-279">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-august-31"></a><span data-ttu-id="2154d-281">バージョン 2008: 8 月 31 日</span><span class="sxs-lookup"><span data-stu-id="2154d-281">Version 2008: August 31</span></span>
<span data-ttu-id="2154d-282">*バージョン 2008 (ビルド 13127.20296)*</span><span class="sxs-lookup"><span data-stu-id="2154d-282">*Version 2008 (Build 13127.20296)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2154d-284">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2154d-284">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2154d-285">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-285">Excel</span></span>

- <span data-ttu-id="2154d-286">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="2154d-286">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="2154d-287">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="2154d-287">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="2154d-288">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="2154d-288">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="2154d-289">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-289">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="2154d-290">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-290">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="2154d-291">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2154d-291">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="outlook"></a><span data-ttu-id="2154d-292">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-292">Outlook</span></span>

- <span data-ttu-id="2154d-293">**メール内のリンクの改善:** ファイルへのリンクを含めると、ファイル名が URL に置き換わります。</span><span class="sxs-lookup"><span data-stu-id="2154d-293">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="2154d-294">アクセス許可を変更して、すべての受信者がアクセスできるようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="2154d-294">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="2154d-295">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-295">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="2154d-296">[ブログの投稿](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2154d-296">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>



### <a name="powerpoint"></a><span data-ttu-id="2154d-297">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2154d-297">PowerPoint</span></span>

- <span data-ttu-id="2154d-298">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="2154d-298">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="2154d-299">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="2154d-299">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="2154d-300">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="2154d-300">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="2154d-301">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-301">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="2154d-302">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-302">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="2154d-303">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2154d-303">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="teams"></a><span data-ttu-id="2154d-304">Teams</span><span class="sxs-lookup"><span data-stu-id="2154d-304">Teams</span></span>

- <span data-ttu-id="2154d-305">**コールマージ:** コールマージにより、エンドユーザーは、アクティブな保持された 1 対 1 の 通話を別の1 対 1 の通話または別のグループ通話に結合できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-305">**Call Merge:** Call Merge gives end users the capability to merge their active unheld 1-1 call into another 1-1 call or another group call.</span></span> <span data-ttu-id="2154d-306">これは、Teams の VOIP 通話と PSTN 通話に適用されます。</span><span class="sxs-lookup"><span data-stu-id="2154d-306">This applies to Teams VOIP calls and PSTN calls.</span></span>

- <span data-ttu-id="2154d-307">**管理者は、Firstline ワーカーの出席状況をシフトベース (オンシフト、オフシフト) で構成できます:** 管理者は、シフト中、ビジー (シフト中に切り替えることができます)、シフト外といったシフトベースの出席状況を表示できるように Firstline ワーカーを構成できます。

</span><span class="sxs-lookup"><span data-stu-id="2154d-307">**Admins can configure shift-based presence (On shift, Off shift) for their Firstline workers:** Admins can configure their firstline workers to have shift-based presence states: On shift, Busy (can be toggled when on shift), and Off shift.</span></span>

- <span data-ttu-id="2154d-308">**Teams の Cortana 音声スキル:** Teams モバイルアプリの Cortana 音声スキルにより、ユーザーは自然な話し言葉を使用して、会議、コミュニケーション、コラボレーションといったタスクを簡単に実行できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-308">**Cortana voice skills in Teams:** Cortana voice skills in Teams mobile app help users perform meeting, communication and collaboration tasks simply using spoken natural language.</span></span> <span data-ttu-id="2154d-309">ユーザーは、家事を色々こなしたり、犬の散歩をしたり、外出先で誰かと連絡する必要がある場合、Teams アプリのマイクボタンをクリックして Cortana に話しかけ、「ミーガンに電話する」や「次の会議にメッセージを送信する」といったリクエストを行うことができます。

</span><span class="sxs-lookup"><span data-stu-id="2154d-309">Users can speak to Cortana by clicking on the microphone button in Teams app and make requests like “Call Megan” or “Send a message to my next meeting” if they need to connect with someone while juggling household chores or walking the dog or generally on the go.</span></span> <span data-ttu-id="2154d-310">ユーザーは「次の会議に参加する」と言うだけで会議に参加したり、「午前中の予定を教えて」と質問してカレンダーを確認したりできます。</span><span class="sxs-lookup"><span data-stu-id="2154d-310">Users can join meetings simply by saying “Join my next meeting” or check their calendar by asking “what do I have this morning”.</span></span> <span data-ttu-id="2154d-311">会議または通話に入ると、会議ステージのオーバーフローメニューから Cortana を呼び出して、名前または番号によるメンバーの追加 (「通話にミーガンを追加」)、デッキプレゼンテーション (「プレゼンテーション 四半期レビューデッキ」) またはスライドの紹介 (「付録スライドを紹介」) といった、一般的な会議のタスクを実行したりできます。</span><span class="sxs-lookup"><span data-stu-id="2154d-311">Once in a meeting or a call, they can invoke Cortana from the overflow menu in the meeting stage and perform typical in-meeting tasks like adding people by name or number (“Add Megan to the call”), deck presentation (“present the quarterly review deck”) or navigating slides (“Go to the appendix slide”).</span></span> <span data-ttu-id="2154d-312">この機能がサポートするその他の機能としては、ファイルの検索と共有、検索、およびTeamsアプリ内での一般的な移動 (「Johnとのチャットを開く、未読のアクティビティに移動する、メンションに移動する」など) があります。</span><span class="sxs-lookup"><span data-stu-id="2154d-312">Other things that the feature supports are finding and sharing files, search, and generally navigating within the Teams app (“Open my chat with John, Go to my unread activity, Go to my mentions etc.).</span></span> <span data-ttu-id="2154d-313">チーム内の Cortana は、[オンラインサービス規約 (OST) ](https://www.microsoft.com/licensing/product-licensing/products)に反映されているように、Cortana エンタープライズサービスと同じエンタープライズレベルのプライバシー、セキュリティ、およびコンプライアンスの約束を満たしています。</span><span class="sxs-lookup"><span data-stu-id="2154d-313">Cortana in Teams meets the same enterprise-level privacy, security, and compliance promises for Cortana enterprise services, as reflected in the [Online Services Terms (OST)](https://www.microsoft.com/licensing/product-licensing/products).</span></span>

- <span data-ttu-id="2154d-314">**グループチャットの拡大:** Teams で 250 人がグループチャットに参加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-314">**Group chat increase:** Teams added the ability to now have 250 participants in a group chat.</span></span>

- <span data-ttu-id="2154d-315">**シフトによるタグ付け:** この機能を使用すると、 Teams の [シフトアプリ](https://support.microsoft.com/office/get-started-in-shifts-5f3e30d8-1821-4904-be26-c3cd25a497d6#bkmk_openshiftsappdesktop)で、スケジュールとシフトグループ名に一致するタグが自動的に割り当てられます。</span><span class="sxs-lookup"><span data-stu-id="2154d-315">**Tagging by Shift:** With this feature, people are automatically assigned tags that match their schedule and shift group name in the [Shifts app](https://support.microsoft.com/office/get-started-in-shifts-5f3e30d8-1821-4904-be26-c3cd25a497d6#bkmk_openshiftsappdesktop) in Teams.</span></span>

### <a name="word"></a><span data-ttu-id="2154d-316">Word</span><span class="sxs-lookup"><span data-stu-id="2154d-316">Word</span></span>

- <span data-ttu-id="2154d-317">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="2154d-317">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="2154d-318">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="2154d-318">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="2154d-319">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="2154d-319">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="2154d-320">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-320">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="2154d-321">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-321">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="2154d-322">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2154d-322">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="2154d-323">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2154d-323">Office Suite</span></span>

- <span data-ttu-id="2154d-324">**タブ付きのウィンドウ** : アプリの右側にあるタブ UI を使用して、複数のウィンドウ間を切り替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-324">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="2154d-325">UI は、2 つ以上のウィンドウが開かれている場合にのみ表示されます。</span><span class="sxs-lookup"><span data-stu-id="2154d-325">The UI will only be visible when you have 2+ panes open.</span></span><br /><span data-ttu-id="2154d-326">[ブログの投稿](https://blog-insider.office.com/2020/02/20/improved-pane-management/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2154d-326">See details in [blog post](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-329">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-329">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2154d-330">Access</span><span class="sxs-lookup"><span data-stu-id="2154d-330">Access</span></span>

- <span data-ttu-id="2154d-331">この問題は解決されました。これで、Office のクイック実行アプリケーション以外でも ODBC ドライバーを使用できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-331">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>


### <a name="outlook"></a><span data-ttu-id="2154d-332">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-332">Outlook</span></span>

- <span data-ttu-id="2154d-333">プロファイルに追加されたサブ アカウントから会議出席依頼を作成しようとした場合に、ユーザーのメール アドレスの代わりに空欄の From: フィールドが表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-333">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="2154d-334">共有メールボックスを追加した後に、ユーザーがパブリック フォルダーに接続できない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-334">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="2154d-335">特定の状況で代理人が会議を辞退したときに、マネージャーのカレンダーから削除されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-335">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="2154d-336">共有カレンダーの改善機能を使用している一部のユーザーが、新しく追加された共有カレンダーを表示できない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-336">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="2154d-337">クラウドの添付ファイルを操作するときに、ユーザーに時折クラッシュが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-337">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="2154d-338">SharePoint ファイルに Smart Link を追加すると、一部の文字セットのユーザーにファイル名が正しく表示されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-338">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="2154d-339">新しいメールに返信、または新しいメールを作成するときにユーザーにクラッシュが発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-339">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="2154d-340">[ヘッダーのみダウンロード] オプションが選択されている POP アカウントから 4 件以上のメールを削除しようとするとクラッシュするという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-340">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="2154d-341">一部のユーザーにスケジュール アシスタント ページが表示されない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-341">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="2154d-342">これにより、受信者を編集しているときに不定期にクラッシュする問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2154d-342">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="2154d-343">コンパクト ビューを使用するときに異常が表示される原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-343">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="2154d-344">右クリックのコンテキストメニューが検索コントロールに表示されない問題の原因を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-344">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="2154d-345">ユーザーが新しいメールに返信または作成するときに次のエラーを受け取る原因となった問題に対処します。「この Web ページのファイルの一部が予期された場所にありません。</span><span class="sxs-lookup"><span data-stu-id="2154d-345">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="2154d-346">この Web ページをダウンロードする必要がありますか? </span><span class="sxs-lookup"><span data-stu-id="2154d-346">Do you want to download them anyway?</span></span> <span data-ttu-id="2154d-347">Web ページが信頼できるソースからのものであることを確認したら、[はい] をクリックします。」</span><span class="sxs-lookup"><span data-stu-id="2154d-347">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


### <a name="project"></a><span data-ttu-id="2154d-348">Project</span><span class="sxs-lookup"><span data-stu-id="2154d-348">Project</span></span>

- <span data-ttu-id="2154d-349">SharePoint タスクリストに接続されているプロジェクトのプロジェクト終了日が更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-349">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="2154d-350">リソースに複数のコスト単価表が定義されている場合に、残りのコストが正しく計算されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-350">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

### <a name="skype"></a><span data-ttu-id="2154d-351">Skype</span><span class="sxs-lookup"><span data-stu-id="2154d-351">Skype</span></span>

- <span data-ttu-id="2154d-352">ダンス絵文字の肌の色を中間色に変更しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-352">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="2154d-353">Word</span><span class="sxs-lookup"><span data-stu-id="2154d-353">Word</span></span>

- <span data-ttu-id="2154d-354">この変更により、以前の共同編集セッションの後に Office アプリケーションがサイレントな保存の失敗状態に陥ることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2154d-354">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="2154d-355">マクロ AutoOpen が AutoExec の前に実行されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-355">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-august-25"></a><span data-ttu-id="2154d-357">バージョン 2007: 8 月 25 日</span><span class="sxs-lookup"><span data-stu-id="2154d-357">Version 2007: August 25</span></span>
<span data-ttu-id="2154d-358">*バージョン 2007 (ビルド 13029.20460)*</span><span class="sxs-lookup"><span data-stu-id="2154d-358">*Version 2007 (Build 13029.20460)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-360">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-360">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2154d-361">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-361">Excel</span></span>

- <span data-ttu-id="2154d-362">LET () 関数を使用して、数式を含むファイルを保存しようとすると、エラーが発生することがあります。</span><span class="sxs-lookup"><span data-stu-id="2154d-362">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>


### <a name="outlook"></a><span data-ttu-id="2154d-363">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-363">Outlook</span></span>

- <span data-ttu-id="2154d-364">SharePoint ファイルに Smart Link を追加すると、一部の文字セットのユーザーにファイル名が正しく表示されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-364">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="2154d-365">Outlook ユーザーにコンパクト ビューでのナビゲーションの問題が表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-365">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2154d-366">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2154d-366">PowerPoint</span></span>

- <span data-ttu-id="2154d-367">PowerPoint アプリでクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-367">We have fixed a crash issue with PowerPoint app.</span></span>


### <a name="word"></a><span data-ttu-id="2154d-368">Word</span><span class="sxs-lookup"><span data-stu-id="2154d-368">Word</span></span>

- <span data-ttu-id="2154d-369">新しいメールに返信または作成するときにユーザーにクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-369">Addresses an issue that caused users to experience a crash when replying to or composing new mail.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2154d-370">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2154d-370">Office Suite</span></span>

- <span data-ttu-id="2154d-371">以前の Web サービス ベースの [共有] ウィンドウで、[共有] ウィンドウが開いているときに文書を閉じるとクラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="2154d-371">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="2154d-372">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="2154d-372">This is now fixed.</span></span>


- <span data-ttu-id="2154d-373">特定の状況下で UI 要素またはコンテンツが表示されない問題を修正しました。特に、発表者ツールのオン/オフ、または複数のモニターの使用に関して発生しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-373">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-august-11"></a><span data-ttu-id="2154d-375">バージョン 2007: 8 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2154d-375">Version 2007: August 11</span></span>
<span data-ttu-id="2154d-376">*バージョン 2007 (ビルド 13029.20344)*</span><span class="sxs-lookup"><span data-stu-id="2154d-376">*Version 2007 (Build 13029.20344)*</span></span>

<span data-ttu-id="2154d-377">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2154d-377">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-379">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-379">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2154d-380">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-380">Outlook</span></span>

- <span data-ttu-id="2154d-381">Outlook で検索候補を取得できない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-381">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="2154d-382">ユーザーがペルソナ情報を取得しようとしたときにクラッシュする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-382">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


### <a name="project"></a><span data-ttu-id="2154d-383">Project</span><span class="sxs-lookup"><span data-stu-id="2154d-383">Project</span></span>

- <span data-ttu-id="2154d-384">正常ではない状態になったプロジェクトを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-384">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-july-30"></a><span data-ttu-id="2154d-386">バージョン 2007: 7 月 30 日</span><span class="sxs-lookup"><span data-stu-id="2154d-386">Version 2007: July 30</span></span>
<span data-ttu-id="2154d-387">*バージョン 2007 (ビルド 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="2154d-387">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2154d-389">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2154d-389">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2154d-390">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-390">Excel</span></span>

- <span data-ttu-id="2154d-391">**PDF に接続:** PDF からデータに接続、インポート、更新します。</span><span class="sxs-lookup"><span data-stu-id="2154d-391">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="2154d-392">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-392">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="2154d-393">**他のユーザーを混乱させずに、フィルター処理して並べ替える:** 、Sheet View で他のユーザーとの共同作業を行いながら Excel ファイルの並べ替えやフィルター処理ができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-393">**Filter and sort without disrupting others:** You can now sort and filter your Excel file while collaborating with others with Sheet View.</span></span> <span data-ttu-id="2154d-394">この新機能により、文書を共同編集しているときに、他のユーザーの並べ替えやフィルター処理による影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="2154d-394">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span> [<span data-ttu-id="2154d-395">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-395">Learn more</span></span>](https://support.office.com/article/0eea3dc5-d7d1-44c5-a953-25ebfbd6c1a6)

- <span data-ttu-id="2154d-396">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-396">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

- <span data-ttu-id="2154d-397">**Excel で Power BI のデータセットからピボットテーブルを作成する:** Power BI に保存されているデータセットに接続されている Excel のピボットテーブルを数回のクリックで作成できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-397">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="2154d-398">これにより、ピボットテーブルと Power BI の両方を最大限に活用できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-398">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="2154d-399">セキュリティで保護された Power BI データセットからピボットテーブルを使って、データの計算、集計、分析を行います。</span><span class="sxs-lookup"><span data-stu-id="2154d-399">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="2154d-400">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-400">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="2154d-401">[ブログの投稿](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2154d-401">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="2154d-402">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-402">Outlook</span></span>

- <span data-ttu-id="2154d-403">**クイック投票を使用して、Outlook で投票を作成:** 簡単に投票を作成し、票を収集して、メールに結果を表示します。 [詳細情報](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="2154d-403">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="2154d-404">**メールの一部として画像を送信するときに、画像を高品質に維持する:** メールの内容の一部として画像を送信するときに、画像の圧縮を制限するための新しい Outlook の設定を使用できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-404">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

- <span data-ttu-id="2154d-405">**以前のセッションからアイテムを素早く再開する:** 以前の Outlook セッションからアイテムを素早く再開するためのオプションが追加されました。</span><span class="sxs-lookup"><span data-stu-id="2154d-405">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="2154d-406">Outlook がクラッシュした場合でも、または終了した場合でも、アプリを再び開くと、すばやくアイテムを再起動することができます。</span><span class="sxs-lookup"><span data-stu-id="2154d-406">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="2154d-407">この機能は既定でオンになっています。</span><span class="sxs-lookup"><span data-stu-id="2154d-407">This feature is on by default.</span></span> <span data-ttu-id="2154d-408">オフにするには、[オプション] > [一般] > [開始オプション] に移動します。</span><span class="sxs-lookup"><span data-stu-id="2154d-408">To turn it off, go to Options > General > Start up Options.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2154d-409">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2154d-409">PowerPoint</span></span>

- <span data-ttu-id="2154d-410">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-410">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="teams"></a><span data-ttu-id="2154d-411">Teams</span><span class="sxs-lookup"><span data-stu-id="2154d-411">Teams</span></span>

- <span data-ttu-id="2154d-412">**簡素化された新しい通知設定:** 機能が強化され、やり方がより簡素化された通知設定をユーザーが管理できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-412">**New simplified notification settings:** Users can now manage their notifications settings in a more simplified manner with enhanced functionalities.</span></span>

- <span data-ttu-id="2154d-413">**Teams でWindows ネイティブ通知をサポート:** ユーザーはバナーに組み込まれた Teams、または Windows のネイティブ バナーのいずれかを使用して、通知配信の優先手段を選択できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-413">**Windows Native Notification are now Supported on Teams:** Users can now select their preferred means of notification delivery, either through teams built in banners or the windows native banners.</span></span>

- <span data-ttu-id="2154d-414">**[チャンネル情報] ウィンドウ:** チャンネルヘッダーの "チャンネル情報" アイコンを選択したときに、[チャンネルの説明]、[最近の寄稿者]、[メンバー] に加えて、システム メッセージの新しいホームを含むチャンネル情報の概要を表示するウィンドウが開きます。</span><span class="sxs-lookup"><span data-stu-id="2154d-414">**Channel Info Pane:** When selecting on the "Channel info" icon in the channel header, a pane will open where you will see a summary of channel information including the channel description, a list of recent contributors and members, as well as the new home for system messages.</span></span>

- <span data-ttu-id="2154d-415">**チャット通知のプレビューをオフにする:** 、ユーザーは設定を変更したり、チャット通知トーストのプレビューを管理したりすることができます。</span><span class="sxs-lookup"><span data-stu-id="2154d-415">**Turn off previews for your chat notifications:** Users can change settings and manage previews for their chat notification toasts.</span></span>

- <span data-ttu-id="2154d-416">**返信の候補:** Teams ユーザーに、自分の会話への返信の候補を提案する機能が追加されました。</span><span class="sxs-lookup"><span data-stu-id="2154d-416">**Suggested replies:** We added the ability for Teams users to have a suggested reply to their conversations.</span></span> <span data-ttu-id="2154d-417">これらの候補が有効になっている場合は、チャット メッセージの下部に表示されます。</span><span class="sxs-lookup"><span data-stu-id="2154d-417">These suggestions will appear at the bottom of a chat message if they are enabled.</span></span> <span data-ttu-id="2154d-418">メッセージへの返信をすばやく簡単に作成できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-418">They make replying to messages quick and easy!</span></span>

### <a name="word"></a><span data-ttu-id="2154d-419">Word</span><span class="sxs-lookup"><span data-stu-id="2154d-419">Word</span></span>

- <span data-ttu-id="2154d-420">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-420">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

- <span data-ttu-id="2154d-421">**テキストをベクター内で保持:** 地図やグラフ、その他の SVG ベクターを Excel、Word、PowerPoint で変換する場合、それらのオブジェクトの中にテキストを保持できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-421">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-424">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-424">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2154d-425">Access</span><span class="sxs-lookup"><span data-stu-id="2154d-425">Access</span></span>

- <span data-ttu-id="2154d-426">この修正プログラムでは、特定のクエリを実行しようとすると、"クエリが複雑すぎます" というエラーメッセージが表示される問題に対処しています。</span><span class="sxs-lookup"><span data-stu-id="2154d-426">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex".</span></span>

### <a name="excel"></a><span data-ttu-id="2154d-427">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-427">Excel</span></span>

- <span data-ttu-id="2154d-428">改ページ プレビューで複数のシートを含むブックを読み込むときにエラーやハングが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-428">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>


### <a name="outlook"></a><span data-ttu-id="2154d-429">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-429">Outlook</span></span>

- <span data-ttu-id="2154d-430">保護されたコンテキストから保護されていないコンテキストに返信するとき、送信元アドレスを切り替えると、CLP のユーザーにクラッシュが発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-430">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="2154d-431">[共有フォルダーのダウンロード] がチェックされていない場合、共有された予定表の会議の [返信オプション] に [転送を許可する] オプションが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-431">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="2154d-432">管理者のカレンダー上で既存のカレンダーの予定を編集するときに代理人がエラーを受け取る問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-432">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="2154d-433">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカルコンピューターに保存できない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-433">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="2154d-434">スケジュール アシスタント ページが表示されない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-434">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="2154d-435">インシデント通知アラートのフォーマットの問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-435">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

### <a name="project"></a><span data-ttu-id="2154d-436">Project</span><span class="sxs-lookup"><span data-stu-id="2154d-436">Project</span></span>

- <span data-ttu-id="2154d-437">[リソースの割り当て] ダイアログ ボックスで選択されているタスクが、[タスク ボード] ビューで選択したタスクと異なる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-437">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="2154d-438">複数の依存関係があるタスクを貼り付けると、すべての依存関係が正しくコピーされるわけではない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-438">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="2154d-439">Project から SharePoint ドキュメント ライブラリに PDF/XPS を保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-439">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2154d-440">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2154d-440">Office Suite</span></span>

- <span data-ttu-id="2154d-441">製品版への移行が完了した場合でも、ランタイムメッセージが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2154d-441">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="2154d-442">この問題の修正では、サービスが追加された製品を適切に計算するようにしました。</span><span class="sxs-lookup"><span data-stu-id="2154d-442">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="2154d-443">新たに追加された製品をフィルターで除外し (新しい構成に存在することも確認)、既存の製品リリース ID の最後に追加しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-443">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-july-28"></a><span data-ttu-id="2154d-445">バージョン 2006: 7 月 28 日</span><span class="sxs-lookup"><span data-stu-id="2154d-445">Version 2006: July 28</span></span>
<span data-ttu-id="2154d-446">*バージョン 2006 (ビルド 13001.20498)*</span><span class="sxs-lookup"><span data-stu-id="2154d-446">*Version 2006 (Build 13001.20498)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-448">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-448">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2154d-449">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-449">Excel</span></span>

- <span data-ttu-id="2154d-450">改ページ プレビューで複数のシートを含むブックを読み込むときにエラーやハングが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-450">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>


### <a name="outlook"></a><span data-ttu-id="2154d-451">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-451">Outlook</span></span>

- <span data-ttu-id="2154d-452">SVG 画像のコピーと貼り付けの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-452">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="word"></a><span data-ttu-id="2154d-453">Word</span><span class="sxs-lookup"><span data-stu-id="2154d-453">Word</span></span>

- <span data-ttu-id="2154d-454">SVG 画像のコピーと貼り付けの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-454">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2154d-455">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2154d-455">Office Suite</span></span>

- <span data-ttu-id="2154d-456">タイミングの問題で、Office ファイルを閉じるときにクラッシュすることがあります。</span><span class="sxs-lookup"><span data-stu-id="2154d-456">A timing issue could cause a crash when closing office files.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-july-14"></a><span data-ttu-id="2154d-458">バージョン 2006: 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2154d-458">Version 2006: July 14</span></span>
<span data-ttu-id="2154d-459">*バージョン 2006 (ビルド 13001.20384)*</span><span class="sxs-lookup"><span data-stu-id="2154d-459">*Version 2006 (Build 13001.20384)*</span></span>

<span data-ttu-id="2154d-460">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2154d-460">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-462">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-462">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2154d-463">アクセス</span><span class="sxs-lookup"><span data-stu-id="2154d-463">Access</span></span>

- <span data-ttu-id="2154d-464">ID (オートナンバーなど) フィールドが含まれるリンク付きの SQL 表を挿入する場合についての問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-464">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

### <a name="excel"></a><span data-ttu-id="2154d-465">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-465">Excel</span></span>

- <span data-ttu-id="2154d-466">読み取り専用モードのブックに対して、ドキュメント分類を自動的に行った可能性があります。</span><span class="sxs-lookup"><span data-stu-id="2154d-466">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="2154d-467">アカウントからサインアウトした場合にデータ接続を作成しようとすると発生する可能性があるクラッシュを修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-467">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="onenote"></a><span data-ttu-id="2154d-468">OneNote</span><span class="sxs-lookup"><span data-stu-id="2154d-468">OneNote</span></span>

- <span data-ttu-id="2154d-469">リソースの使用率を低下させて、共同編集状態の検出機能を改善します。</span><span class="sxs-lookup"><span data-stu-id="2154d-469">Improve detection of co-authoring status to reduce resource utilization.</span></span>

### <a name="outlook"></a><span data-ttu-id="2154d-470">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-470">Outlook</span></span>

- <span data-ttu-id="2154d-471">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカルコンピューターに保存できない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-471">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2154d-472">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2154d-472">Office Suite</span></span>

- <span data-ttu-id="2154d-473">以前の AppV51 の回帰を修正するために、新しい AppV51 drop をバックポートします。</span><span class="sxs-lookup"><span data-stu-id="2154d-473">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="2154d-474">レジストリ TabProcGrowth の値がREG_SZ型でアドインがアクティブ化されている場合に、Windows の Office ホストがクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-474">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-june-30"></a><span data-ttu-id="2154d-476">バージョン 2006: 6 月 30 日</span><span class="sxs-lookup"><span data-stu-id="2154d-476">Version 2006: June 30</span></span>
<span data-ttu-id="2154d-477">*バージョン 2006 (ビルド 13001.20266)*</span><span class="sxs-lookup"><span data-stu-id="2154d-477">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2154d-479">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2154d-479">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2154d-480">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-480">Excel</span></span>

- <span data-ttu-id="2154d-481">**長いファイル名** : Windows デスクトップ版の Excel は、名前とパスが最大400文字の OneDrive/SharePoint ファイルをサポートするようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-481">**Longer file names:** Excel for Windows desktop now supports OneDrive/SharePoint files with names and paths of up to 400 characters.</span></span>

- <span data-ttu-id="2154d-482">**Realtimedata (RTD) の改善:** Office 365 バージョン 2002 の月間チャネル以降、ExcelのRealTimeData (RTD) 関数は、Excel 2010 のスプレッドシートのデータ計算よりもはるかに高速になります。</span><span class="sxs-lookup"><span data-stu-id="2154d-482">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="2154d-483">基盤となるメモリとデータ構造のボトルネックを取り除き、マルチスレッド再計算  (MTR) の使用可能なすべてのスレッドで計算できるようにスレッドセーフにしました。</span><span class="sxs-lookup"><span data-stu-id="2154d-483">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="2154d-484">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-484">Outlook</span></span>

- <span data-ttu-id="2154d-485">**Outlook でのメール作成時の @ メンションの候補表示を無効にするオプションが追加されました。** @ メンション ピッカーが便利どころか迷惑だと感じていますか?</span><span class="sxs-lookup"><span data-stu-id="2154d-485">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="2154d-486">今後は、必要に応じてオフにすることができます。</span><span class="sxs-lookup"><span data-stu-id="2154d-486">Now you can turn it off if you prefer.</span></span><br /><span data-ttu-id="2154d-487">[ブログの投稿](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2154d-487">See details in [blog post](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)</span></span>

- <span data-ttu-id="2154d-488">**IT 管理者向けのインシデント通知:** Microsoft 365 テナントのグローバル管理者および Office Apps 管理者は、Outlook for Windows の新しい右側のパネル通知により、ユーザーに影響する Outlook および O365 Exchange インシデントについて通知されます。</span><span class="sxs-lookup"><span data-stu-id="2154d-488">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="2154d-489">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-489">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- <span data-ttu-id="2154d-490">**Outlook トースト通知に追加されたその他のボタン:** Outlook for Windows 10で Outlook を実行しているときに Outlook トースト通知にクイック アクション ボタンが表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-490">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2154d-491">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2154d-491">PowerPoint</span></span>

- <span data-ttu-id="2154d-492">**PowerPoint でのストリーム ビデオのパフォーマンス向上:** 、ビデオの読み込み時間を最小限に抑え、快適な表示を実現するために Microsoft Stream ビデオの再生パフォーマンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-492">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="2154d-493">お客様の社内ビデオを使用して、Microsoft Stream でより適切なプレゼンテーションを作成します。</span><span class="sxs-lookup"><span data-stu-id="2154d-493">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="teams"></a><span data-ttu-id="2154d-494">Teams</span><span class="sxs-lookup"><span data-stu-id="2154d-494">Teams</span></span>

- <span data-ttu-id="2154d-495">**PSTN の参加者の電話番号は、外部ユーザーからマスクされます** 。Teams 会議でオーディオ会議を有効にしているお客様は、組織の外部から参加しているユーザーに PSTN 参加者の電話番号をマスクします。</span><span class="sxs-lookup"><span data-stu-id="2154d-495">**PSTN participant phone numbers are masked from external users:** For customers with Audio Conferencing enabled for their Teams meetings, we will mask the PSTN participant's phone number to users who have joined from outside of your organization.</span></span>

- <span data-ttu-id="2154d-496">**チャネル通知の設定を管理する簡単な方法:** チームやチャネルのリストを通して、またはチャネル ヘッダーから、ワンクリックで、またはユーザー設定によって、ユーザーはすべてのアクティビティのオンとオフを切り替えることで、お好きな順序を設定できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-496">**Simplified way to manage your channel notification settings:** Through the teams and channels list or from the channel header, the users can quickly manage their notification settings by turning all activity on or off with a single click or diving deep into custom to set their preferred permutations.</span></span>

- <span data-ttu-id="2154d-497">**Walkie Talkie :** プッシュツートークを使用した、インスタント音声コミュニケーション。</span><span class="sxs-lookup"><span data-stu-id="2154d-497">**Walkie Talkie:** Instant voice communication using push-to-talk.</span></span>

### <a name="word"></a><span data-ttu-id="2154d-498">Word</span><span class="sxs-lookup"><span data-stu-id="2154d-498">Word</span></span>

- <span data-ttu-id="2154d-499">**スクリーン リーダーでの操作の確認:** 操作の確認は、重要なアクセシビリティ要件です。</span><span class="sxs-lookup"><span data-stu-id="2154d-499">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="2154d-500">Windows からの新しい通知 API の導入により、操作の成功をスクリーン リーダーのユーザーに通知できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-500">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="2154d-501">切り取り、コピー、貼り付け、太字、斜体、下線、元に戻す、やり直し、自動修正、および自動大文字化が、Win32 Word のナレーター ユーザーにすべて通知されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-501">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="2154d-502">この機能を有効にするには、Windows + Ctrl + Enter キーを押してナレーターをオンにします。</span><span class="sxs-lookup"><span data-stu-id="2154d-502">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-505">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-505">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2154d-506">Access</span><span class="sxs-lookup"><span data-stu-id="2154d-506">Access</span></span>

- <span data-ttu-id="2154d-507">クエリの実行に予想よりも約2倍の時間がかかっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-507">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>


### <a name="excel"></a><span data-ttu-id="2154d-508">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-508">Excel</span></span>

- <span data-ttu-id="2154d-509">SharePoint/OneDrive に保存すると、ユーザー設定のリボンタブの CustomUI XML が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2154d-509">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>


### <a name="outlook"></a><span data-ttu-id="2154d-510">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-510">Outlook</span></span>

- <span data-ttu-id="2154d-511">ドラッグ アンド ドロップによってファイル システムにコピーされた添付ファイルの作成日が、4501年1月1日に設定された問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-511">Addressed an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>

- <span data-ttu-id="2154d-512">共有された予定表の改良版のユーザーに予定表のエラーが表示される問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-512">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="2154d-513">Outlook で、受信トレイ修復ツールを実行するように促す表示が継続的に発生していた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-513">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="2154d-514">クラウド設定が有効になっているときに、Ctrl キーを押しながらクリックすると動作が停止する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-514">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>


- <span data-ttu-id="2154d-515">Suggest a Feature で機能を検索しても結果が返されず、ユーザーが新しい機能のアイデアを提出するオプションがないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-515">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


### <a name="project"></a><span data-ttu-id="2154d-516">Project</span><span class="sxs-lookup"><span data-stu-id="2154d-516">Project</span></span>

- <span data-ttu-id="2154d-517">URL が .com で終了している場合に、Project Web App からプロジェクト デスクトップ クライアントでプロジェクトを開くことができない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2154d-517">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="2154d-518">プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2154d-518">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>


- <span data-ttu-id="2154d-519">100% 完了とマークされているタスクが、100% 未満のタスクに間違って変更されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-519">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="2154d-520">Word</span><span class="sxs-lookup"><span data-stu-id="2154d-520">Word</span></span>

- <span data-ttu-id="2154d-521">URL にクエリ コンポーネントが含まれている場合にカスタム ドキュメント配信 (aspx) から Word ドキュメントを開く問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-521">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2005-june-24"></a><span data-ttu-id="2154d-523">バージョン 2005: 6 月 24 日</span><span class="sxs-lookup"><span data-stu-id="2154d-523">Version 2005: June 24</span></span>
<span data-ttu-id="2154d-524">*バージョン 2005 (ビルド 12827.20470)*</span><span class="sxs-lookup"><span data-stu-id="2154d-524">*Version 2005 (Build 12827.20470)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-526">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-526">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2154d-527">Access</span><span class="sxs-lookup"><span data-stu-id="2154d-527">Access</span></span>

- <span data-ttu-id="2154d-528">このバグは修正されました。アプリケーションのクラッシュを発生させずに、コードに日付/時刻の拡張データ型を呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="2154d-528">This bug has now been fixed; you should be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span> <span data-ttu-id="2154d-529">問題が発生した場合は、チームにお知らせください。</span><span class="sxs-lookup"><span data-stu-id="2154d-529">Please let the team know if you encounter further issues.</span></span>


- <span data-ttu-id="2154d-530">この問題は修正されました。これで、最新の Access バージョンに戻すことができるようになりました。さらに、DAO/VBA を使用して10進数データ型を管理および編集することができます。</span><span class="sxs-lookup"><span data-stu-id="2154d-530">This issue has now been fixed; you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span> <span data-ttu-id="2154d-531">データ型を使用して問題が発生した場合は、Access チームにお知らせください。</span><span class="sxs-lookup"><span data-stu-id="2154d-531">Please let the Access team know if you encounter any further issues with using our data type.</span></span>


### <a name="excel"></a><span data-ttu-id="2154d-532">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-532">Excel</span></span>

- <span data-ttu-id="2154d-533">SharePoint/OneDrive に保存すると、ユーザー設定のリボンタブの CustomUI XML が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2154d-533">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>





### <a name="outlook"></a><span data-ttu-id="2154d-534">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-534">Outlook</span></span>

- <span data-ttu-id="2154d-535">M365 Business Plus プランのサービスを利用していたユーザーがデータ損失防止の保護ポリシー ヒントを有効にできない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-535">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>


- <span data-ttu-id="2154d-536">ドラッグ アンド ドロップによってファイル システムにコピーされた添付ファイルの作成日が、4501年1月1日に設定された問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-536">Addressed an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="2154d-537">ユーザーがOutlook ルールを更新すると、「&quot;このコンピューターのルールは、Microsoft Exchange のルールと異なります&quot;」 と表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-537">Addressed an issue that caused users to see the &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; message when updating their rules in Outlook.</span></span>


- <span data-ttu-id="2154d-538">共有された予定表の改良版のユーザーに予定表のエラーが表示される問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-538">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="2154d-539">一部のシナリオで、断続的なハングやクラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-539">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>


- <span data-ttu-id="2154d-540">Outlook で、受信トレイ修復ツールを実行するように促す表示が継続的に発生していた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-540">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="2154d-541">Suggest a Feature で機能を検索しても結果が返されず、ユーザーが新しい機能のアイデアを提出するオプションがないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-541">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2154d-542">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2154d-542">PowerPoint</span></span>

- <span data-ttu-id="2154d-543">提案ウィンドウでクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-543">We have fixed a crash issue with suggestion pane.</span></span>


### <a name="project"></a><span data-ttu-id="2154d-544">Project</span><span class="sxs-lookup"><span data-stu-id="2154d-544">Project</span></span>

- <span data-ttu-id="2154d-545">100% 完了とマークされているタスクが、100% 未満のタスクに間違って変更されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-545">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="2154d-546">Word</span><span class="sxs-lookup"><span data-stu-id="2154d-546">Word</span></span>

- <span data-ttu-id="2154d-547">一部のアプリケーションからコンテンツをドラッグしたときにクラッシュする問題の原因となっていた可能性がある問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="2154d-547">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2154d-548">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2154d-548">Office Suite</span></span>

- <span data-ttu-id="2154d-549">この変更により、Gif や3D モデルなどのアニメーション コンテンツを読み込んだり、再生したりするときに、ハングする可能性があります。</span><span class="sxs-lookup"><span data-stu-id="2154d-549">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>




[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-june-09"></a><span data-ttu-id="2154d-551">バージョン 2005: 6月 9 日</span><span class="sxs-lookup"><span data-stu-id="2154d-551">Version 2005: June 09</span></span>
<span data-ttu-id="2154d-552">*バージョン 2005 (ビルド 12827.20336)*</span><span class="sxs-lookup"><span data-stu-id="2154d-552">*Version 2005 (Build 12827.20336)*</span></span>

<span data-ttu-id="2154d-553">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2154d-553">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="feature-updates"></a><span data-ttu-id="2154d-554">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2154d-554">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2154d-555">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-555">Excel</span></span>

- <span data-ttu-id="2154d-556">**[描画] の [ツール] ボックスのなげなわと消しゴム:** 描画ツールを使用しているときに、[描画] の [ツール] ボックスでなげなわと消しゴムを使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-556">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2154d-557">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2154d-557">PowerPoint</span></span>

- <span data-ttu-id="2154d-558">**[描画] の [ツール] ボックスのなげなわと消しゴム:** 描画ツールを使用しているときに、[描画] の [ツール] ボックスでなげなわと消しゴムを使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-558">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>

### <a name="word"></a><span data-ttu-id="2154d-559">Word</span><span class="sxs-lookup"><span data-stu-id="2154d-559">Word</span></span>

- <span data-ttu-id="2154d-560">**[描画] の [ツール] ボックスのなげなわと消しゴム:** 描画ツールを使用しているときに、[描画] の [ツール] ボックスでなげなわと消しゴムを使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-560">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>




[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-563">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-563">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2154d-564">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-564">Excel</span></span>

- <span data-ttu-id="2154d-565">ピボットテーブルをチャート シートに挿入しようとしたときに Excel がクラッシュする場合がある問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2154d-565">Addresses an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2154d-566">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2154d-566">PowerPoint</span></span>

- <span data-ttu-id="2154d-567">これにより、ユーザーがファイルに対してモダンおよびレガシのコメントを持っていて、コメントの更新をトリガーすると、クラッシュが修正されます。</span><span class="sxs-lookup"><span data-stu-id="2154d-567">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

### <a name="project"></a><span data-ttu-id="2154d-568">Project</span><span class="sxs-lookup"><span data-stu-id="2154d-568">Project</span></span>

- <span data-ttu-id="2154d-569">プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2154d-569">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2154d-570">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2154d-570">Office Suite</span></span>

- <span data-ttu-id="2154d-571">Bing アドオンのインストール検証を既定で true に設定し、MSI のリターン成功をインストール成功とみなすことで、ValidateInstall のエラー率の問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-571">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2005-june-02"></a><span data-ttu-id="2154d-573">バージョン 2005: 6 月 2 日</span><span class="sxs-lookup"><span data-stu-id="2154d-573">Version 2005: June 02</span></span>
<span data-ttu-id="2154d-574">*バージョン 2005 (ビルド 12827.20268)*</span><span class="sxs-lookup"><span data-stu-id="2154d-574">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2154d-576">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2154d-576">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2154d-577">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-577">Excel</span></span>

- <span data-ttu-id="2154d-578">**新しいデータ型を自動的に使用する :** 可能性のある株式や地理的な場所に似たデータ値を入力すると、Excel は、関連付けられた該当する株価や地理といったデータ型に変換することを提案します。</span><span class="sxs-lookup"><span data-stu-id="2154d-578">**Automatically use new data types:** When you type a data value that resembles a stock or a geographic location, Excel offers to convert it to the right connected data type - Stocks or Geography.</span></span> [<span data-ttu-id="2154d-579">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-579">Learn more</span></span>](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- <span data-ttu-id="2154d-580">**アニメーション Gif を使用してストーリーを伝える :** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-580">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>

### <a name="outlook"></a><span data-ttu-id="2154d-581">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-581">Outlook</span></span>

- <span data-ttu-id="2154d-582">**グループ内のデータを保護:** グループを作成するときに選択する秘密度ラベルがグループ メール、ドキュメント、チーム サイトに適用されます。</span><span class="sxs-lookup"><span data-stu-id="2154d-582">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

- <span data-ttu-id="2154d-583">**より迅速かつ適切な結果:** 検索機能が更新され、よりスマート、迅速、かつ信頼性が高くなりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-583">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="2154d-584">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-584">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="2154d-585">**アニメーション Gif を使用してストーリーを伝える :** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-585">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>

- <span data-ttu-id="2154d-586">**予定表が一新されます:** 予定表を簡単に読みやすくなるビジュアル アップデートをご覧ください。</span><span class="sxs-lookup"><span data-stu-id="2154d-586">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="2154d-587">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-587">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="2154d-588">[ブログの投稿](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2154d-588">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2154d-589">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2154d-589">PowerPoint</span></span>

- <span data-ttu-id="2154d-590">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。 [詳細については、こちらを参照してください。](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span><span class="sxs-lookup"><span data-stu-id="2154d-590">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier [Learn more](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span></span>

- <span data-ttu-id="2154d-591">**プレゼンテーション中に変更を同期する:** プレゼンテーションがスライド ショー モードであれば、いつでも変更を同期できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-591">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="2154d-592">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-592">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="2154d-593">[ブログの投稿](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2154d-593">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="2154d-594">**クリッカーは不要: イヤホンでカバー:** Surface Earbuds を使用して、PowerPoint プレゼンテーションを制御します。</span><span class="sxs-lookup"><span data-stu-id="2154d-594">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="2154d-595">機能のしくみ: ペアリングすると、PowerPoint の機能を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="2154d-595">How it works:  Once paired, you'll need to enable the feature in PowerPoint.</span></span> <span data-ttu-id="2154d-596">F5 キーを押すか、[スライド ショー] > [最初から] を選択してプレゼンテーションを開始します。</span><span class="sxs-lookup"><span data-stu-id="2154d-596">Start a presentation by pressing F5 or selecting Slide Show > From Beginning.</span></span>  <span data-ttu-id="2154d-597">スライドショーでは、スライドを右クリックし、Surface Earbuds の設定で、[ジェスチャを使用してプレゼンテーションを制御] を選択します。</span><span class="sxs-lookup"><span data-stu-id="2154d-597">In Slide Show, right click on the slide and under Surface Earbuds Settings choose Use Gestures to Control Presentation.</span></span>  <span data-ttu-id="2154d-598">この設定は、今後作成するすべてのプレゼンテーションに記録されます。</span><span class="sxs-lookup"><span data-stu-id="2154d-598">This setting will be remembered for all future presentations.</span></span> <span data-ttu-id="2154d-599">スライド ショー モードで左イヤホンを使用して前後にスワイプし、プレゼンテーションをナビゲートできます。</span><span class="sxs-lookup"><span data-stu-id="2154d-599">You can now can swipe forward and backward on the left earbud to navigate your presentations in Slide Show mode.</span></span>  <span data-ttu-id="2154d-600">ダブルタップして、埋め込まれたビデオを再生または一時停止します。</span><span class="sxs-lookup"><span data-stu-id="2154d-600">Double tap to play or pause embedded videos.</span></span>  <span data-ttu-id="2154d-601">重要: ジェスチャーを使用してプレゼンテーションを制御するには、Windows 10 の Surface Audio アプリで Surface Earbuds をペアリングする必要があります。</span><span class="sxs-lookup"><span data-stu-id="2154d-601">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="2154d-602">Windows 10 で Surface Audio アプリを使い始める方法については、こちらをご覧ください。</span><span class="sxs-lookup"><span data-stu-id="2154d-602">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="2154d-603">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-603">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="teams"></a><span data-ttu-id="2154d-604">Teams</span><span class="sxs-lookup"><span data-stu-id="2154d-604">Teams</span></span>

- <span data-ttu-id="2154d-605">**Teams 会議でのビデオ レイアウトの変更:** 近日中に、Teams 会議中に同時に表示できる参加者の数は、4名から9名に増加します。</span><span class="sxs-lookup"><span data-stu-id="2154d-605">**Changes to video layout in Teams meetings:** Soon, the number of participants that can be viewed simultaneously during a Teams meeting will increase from 4 to 9.</span></span>

- <span data-ttu-id="2154d-606">**[ライブイベント] にシステム オーディオを含める** : ライブ イベントの発表者やプロデューサーは、ライブ イベント中にデスクトップまたはウィンドウ画面を共有するときに、システム オーディオを含めることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-606">**Include system audio in live events:** Presenters and producers in live events can now include system audio when sharing a desktop or window screen during the live event.</span></span> <span data-ttu-id="2154d-607">これにより、共有するコンテンツのオーディオ部分をユーザーが聞くことができます。</span><span class="sxs-lookup"><span data-stu-id="2154d-607">This will allow your users to hear any audio part of the content you are sharing.</span></span>

- <span data-ttu-id="2154d-608">[ **ダイヤルイン ユーザーによるロビーのバイパスを許可する :** ] この設定では、スマートフォンでダイヤル インするユーザーが会議に直接参加するのか、[ユーザーの参加を自動的に許可する] の設定に関わらずロビーで待機するのかを制御します。</span><span class="sxs-lookup"><span data-stu-id="2154d-608">**Enable organizers to change lobby settings for dial-in participants:** This setting controls whether people who dial in by phone join the meeting directly or wait in the lobby regardless of the Automatically admit people setting.</span></span>

- <span data-ttu-id="2154d-609">**会議で挙手しましょう:** ユーザーは会議で仮想の手を上げることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-609">**Raise Your Hand in Meetings:** Users can now raise a virtual hand in a meeting!</span></span> <span data-ttu-id="2154d-610">他のユーザーは、会議のステージで参加者名簿の自分の名前の横で挙手しているのが表示されるのを見ることができます。</span><span class="sxs-lookup"><span data-stu-id="2154d-610">Other participants will see your raised hand next to your name in the meeting stage and next to your name in the roster.</span></span>

- <span data-ttu-id="2154d-611">**ビデオ会議の背景をカスタマイズ:** ビデオ会議を実施しているときに、使用する静的な背景画像を選択できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-611">**Customize meeting video backgrounds:** When you are meeting with video, you now have the choice of different static background images to use.</span></span> <span data-ttu-id="2154d-612">この操作により、実際に座っている場所の背景ではない、選択した画像が表示されます。</span><span class="sxs-lookup"><span data-stu-id="2154d-612">This will let you show this image and not the actual background of where you are sitting.</span></span>

- <span data-ttu-id="2154d-613">**チャットにユーザーを追加する:** 、最大350人のユーザーを1つのチャットスレッドに追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-613">**Add more people to chat:** We made it possible to now add up to 350 people to a single chat thread.</span></span>

- <span data-ttu-id="2154d-614">**アクティビティ フィードの設定ギア** : ユーザーは、[設定] ギアを使用して、フィードの左側のレールから、アクティビティ フィードと通知の設定に直接アクセスできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-614">**Settings Gear on your Activity Feed:** Users can now directly access activity feed and notification setting from the feed left rail by the means of a settings gear.</span></span>

- <span data-ttu-id="2154d-615">**進行中の Teams 会議内から会議のオプションに簡単にアクセス可能:** 会議の開催者は、参加者ウィンドウに直接アクセスできるリンクを提供することで、会議の開催者が発表者やロビーの設定をすばやく簡単に変更することができます。</span><span class="sxs-lookup"><span data-stu-id="2154d-615">**Easily access meeting options from within a Teams meeting in progress:** We are making it easier for meeting organizers to quickly and easily change their presenter and lobby settings once a Teams meeting starts by providing an easy to access link directly in the participants pane.</span></span> <span data-ttu-id="2154d-616">この新機能は、予定されている、または 「今から会議」 の会議に使用できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-616">This new functionality will be present for both scheduled and “Meet Now” meetings.</span></span>

- <span data-ttu-id="2154d-617">**チームとチャネルの分析 :** チームの分析に加えて、チャネル レベルのメトリックスやインサイトを表示することもできます。</span><span class="sxs-lookup"><span data-stu-id="2154d-617">**Team and channel analytics:** In addition to team analytics, now you can also view channel level metrics and insights.</span></span> <span data-ttu-id="2154d-618">また、より長期間にわたってデータを分析できるように、期間が90日に延長されました。</span><span class="sxs-lookup"><span data-stu-id="2154d-618">We've also enhanced the time period to 90 days so you can analyze data for longer periods.</span></span> <span data-ttu-id="2154d-619">それ以外に、このリリースには、チームやチャネルの投稿、返信、会議の数についての新しいメトリックスやグラフも含まれます。</span><span class="sxs-lookup"><span data-stu-id="2154d-619">Apart from that, this release also includes new metrics and charts around count of posts, replies and meetings for a team or channel.</span></span>

- <span data-ttu-id="2154d-620">**入退場のアナウンス:** 会議の開催者が会議の入退場アナウンスのオン / オフを切り替えできる機能を追加しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-620">**Entry/exit announcements:** We added this feature that lets meeting organizers have the ability to turn on or off entry and exit announcements for a meeting.</span></span>

### <a name="word"></a><span data-ttu-id="2154d-621">Word</span><span class="sxs-lookup"><span data-stu-id="2154d-621">Word</span></span>

- <span data-ttu-id="2154d-622">**Wordを終了せずに頭字語をデコードする:** Word で頭字語が見つかった場合、他のユーザーによるその使用方法に基づいく定義が示されます。</span><span class="sxs-lookup"><span data-stu-id="2154d-622">**Decode acronyms without leaving Word:** When you encounter an acronym, Word will try to define it based on how others use it.</span></span>

- <span data-ttu-id="2154d-623">**アニメーション Gif を使用してストーリーを伝える :** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-623">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-626">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-626">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="2154d-627">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-627">Excel</span></span>

- <span data-ttu-id="2154d-628">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2154d-628">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="2154d-629">同じブック内の場所へのハイパーリンクをクリックすると、ブックが非表示になることがあります。</span><span class="sxs-lookup"><span data-stu-id="2154d-629">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

### <a name="outlook"></a><span data-ttu-id="2154d-630">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-630">Outlook</span></span>

- <span data-ttu-id="2154d-631">CLP の監査イベントで、返信/転送ラベルの問題に対応しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-631">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="2154d-632">Windows 10 サーバー バージョンのユーザーに「アンチウイルスの状態が無効です」という警告が表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-632">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid".</span></span> <span data-ttu-id="2154d-633">このバージョンの Windows はウイルス検出をサポートしていますが、ウイルス対策が正常にインストールされてもウイルス対策ソフトウェアが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="2154d-633">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="2154d-634">ユーザーが管理者通知からフィードバックを送信する場合にクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-634">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

### <a name="skype"></a><span data-ttu-id="2154d-635">Skype</span><span class="sxs-lookup"><span data-stu-id="2154d-635">Skype</span></span>

- <span data-ttu-id="2154d-636">ユーザーが Teams Only に移動するポリシーを与えられた場合は、Skype for Business Outlook アドインを使用して会議をスケジュールできます。</span><span class="sxs-lookup"><span data-stu-id="2154d-636">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="2154d-637">この更新プログラムを適用すると、クライアントは Teams Only を対象としていることを示すポリシーをユーザーが読んでから会議参加のみのモードに入った後に、Skype for Business 会議のスケジュールを設定できなくなります。</span><span class="sxs-lookup"><span data-stu-id="2154d-637">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="2154d-638">また、skype for business Outlook アドインは、Skype for business クライアントが 「会議の参加のみ」 モードであることを確認した場合に起動した場合、自動的にアクティブ化されることはありません。</span><span class="sxs-lookup"><span data-stu-id="2154d-638">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2154d-639">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2154d-639">Office Suite</span></span>

- <span data-ttu-id="2154d-640">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2154d-640">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="2154d-641">この更新プログラムでは、Microsoft Office で PATH 環境変数で指定した場所を検索することによって参照される可能性がある Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA ランタイムエラーが発生するという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2154d-641">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="2154d-642">HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth のレジストリ キーが0に設定されている場合、アドインがアクティブになり、Windows で Office ホストがクラッシュしました。</span><span class="sxs-lookup"><span data-stu-id="2154d-642">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="2154d-643">この変更により、この問題は修正されます。</span><span class="sxs-lookup"><span data-stu-id="2154d-643">This change would fix this issue.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2004-may-21"></a><span data-ttu-id="2154d-645">バージョン 2004: 5 月 21 日</span><span class="sxs-lookup"><span data-stu-id="2154d-645">Version 2004: May 21</span></span>
<span data-ttu-id="2154d-646">*バージョン 2004 (ビルド 12730.20352)*</span><span class="sxs-lookup"><span data-stu-id="2154d-646">*Version 2004 (Build 12730.20352)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-648">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-648">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2154d-649">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-649">Excel</span></span>

- <span data-ttu-id="2154d-650">ファイル パスが長すぎる場合にファイルをもう一度開くと、外部リンクが機能しなくなった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2154d-650">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>


### <a name="outlook"></a><span data-ttu-id="2154d-651">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-651">Outlook</span></span>

- <span data-ttu-id="2154d-652">ユーザーが管理者通知からフィードバックを送信する場合にクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-652">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2154d-653">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2154d-653">Office Suite</span></span>

- <span data-ttu-id="2154d-654">クイック実行に関する問題が修正され、最新のビルドへの更新プログラムに失敗することがあった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-654">Fixed a Click-to-Run issue which was resulting in occasional update failures to the latest builds.</span></span>

- <span data-ttu-id="2154d-655">Microsoft Office で、PATH 環境変数で指定した場所を検索すれば見つかるはずの参照を含む Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA のランタイム エラーになる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2154d-655">Fixed an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2004-may-12"></a><span data-ttu-id="2154d-657">バージョン 2004: 5 月 12 月</span><span class="sxs-lookup"><span data-stu-id="2154d-657">Version 2004: May 12</span></span>
<span data-ttu-id="2154d-658">*バージョン 2004 (ビルド 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="2154d-658">*Version 2004 (Build 12730.20270)*</span></span>

<span data-ttu-id="2154d-659">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2154d-659">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-661">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-661">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2154d-662">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-662">Outlook</span></span>

- <span data-ttu-id="2154d-663">ユーザーがトースト通知を表示するときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-663">Addresses an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-may-04"></a><span data-ttu-id="2154d-665">バージョン 2004: 5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="2154d-665">Version 2004: May 04</span></span>
<span data-ttu-id="2154d-666">*バージョン 2004 (ビルド 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="2154d-666">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-668">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-668">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="2154d-669">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2154d-669">Office Suite</span></span>

- <span data-ttu-id="2154d-670">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2154d-670">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-april-29"></a><span data-ttu-id="2154d-672">バージョン 2004: 4 月 29 日</span><span class="sxs-lookup"><span data-stu-id="2154d-672">Version 2004: April 29</span></span>
<span data-ttu-id="2154d-673">*バージョン 2004 (ビルド 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="2154d-673">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2154d-675">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2154d-675">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2154d-676">Access</span><span class="sxs-lookup"><span data-stu-id="2154d-676">Access</span></span>

- <span data-ttu-id="2154d-677">**クエリ デザイナー、SQL ビュー、およびリレーションシップ ウィンドウでの作業効率の向上:** テーブルを右クリックして、テーブルを開き、デザインし、サイズを変更し、非表示にします。</span><span class="sxs-lookup"><span data-stu-id="2154d-677">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="2154d-678">SQL ビューでテキストを検索および置換します。</span><span class="sxs-lookup"><span data-stu-id="2154d-678">Search and replace text in SQL View.</span></span> <span data-ttu-id="2154d-679">リレーションシップ ウィンドウ内の複数のテーブルを選択します。</span><span class="sxs-lookup"><span data-stu-id="2154d-679">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="2154d-680">**数回クリックするだけで表を追加する:** [テーブルの追加] 作業ウィンドウを使用すると、作業中も開いたまま、リレーションシップやクエリにテーブルを追加できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-680">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="2154d-681">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-681">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)


### <a name="excel"></a><span data-ttu-id="2154d-682">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-682">Excel</span></span>

- <span data-ttu-id="2154d-683">**Facebook コネクタのサポート終了:** 2020 年 4 月以降、Excel では Facebook コネクタを使用する外部データ接続がサポートされなくなります。</span><span class="sxs-lookup"><span data-stu-id="2154d-683">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

- <span data-ttu-id="2154d-684">**質問がある場合のExcel への質問:** Excel のアイデアを使用すると、データについて質問をすることができます。数式の記述に時間を費やす必要はありません(英語のみ使用可能)。</span><span class="sxs-lookup"><span data-stu-id="2154d-684">**Have a question? Ask Excel:** Now Excel Ideas allows you to ask questions about your data - no need to spend time writing formulas (available in English only).</span></span> [<span data-ttu-id="2154d-685">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-685">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- <span data-ttu-id="2154d-686">**ブックの見映えを良くする新しい画像:** 何千ものロイヤリティフリーの画像、アイコン、ステッカーが用意されており、これらをブックで使用できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-686">**New images to bring your workbooks to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your workbooks.</span></span> <span data-ttu-id="2154d-687">開始するには、[挿入] > [画像] > [ストック画像] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="2154d-687">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="2154d-688">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-688">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="outlook"></a><span data-ttu-id="2154d-689">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-689">Outlook</span></span>

- <span data-ttu-id="2154d-690">**受信トレイを離れずに会議に参加する:** オンライン会議に参加するために、予定表に切り替える必要はありません。</span><span class="sxs-lookup"><span data-stu-id="2154d-690">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="2154d-691">[To Do] ウィンドウに固定された予定表を使用して、ワンクリックで任意の会議に参加します。</span><span class="sxs-lookup"><span data-stu-id="2154d-691">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="2154d-692">**メッセージの見映えを良くする新しい画像:** 何千ものロイヤリティフリーの画像、アイコン、ステッカーが用意されており、これらをメール メッセージで使用できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-692">**New images to bring your messages to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your email messages.</span></span> <span data-ttu-id="2154d-693">開始するには、[挿入] > [画像] > [ストック画像] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="2154d-693">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="2154d-694">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-694">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

- <span data-ttu-id="2154d-695">**定期的な会議の場所の提案サポート:** 定期的な会議のスケジュールで会議室を検索します。</span><span class="sxs-lookup"><span data-stu-id="2154d-695">**Location suggestion support for recurring meeting:** Search for conference rooms with scheduling recurring meetings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2154d-696">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2154d-696">PowerPoint</span></span>

- <span data-ttu-id="2154d-697">**スライド ショーの実行中にスライドを更新する:** プレゼンテーション中に他の作成者が変更したスライドを更新します。</span><span class="sxs-lookup"><span data-stu-id="2154d-697">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

- <span data-ttu-id="2154d-698">**スライドの見映えを良くする新しい画像:** 何千ものロイヤリティフリーの画像、アイコン、ステッカーが用意されており、これらをプレゼンテーションで使用できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-698">**New images to bring your slides to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your presentations.</span></span> <span data-ttu-id="2154d-699">開始するには、[挿入] > [画像] > [ストック画像] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="2154d-699">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="2154d-700">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-700">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="teams"></a><span data-ttu-id="2154d-701">Teams</span><span class="sxs-lookup"><span data-stu-id="2154d-701">Teams</span></span>

- <span data-ttu-id="2154d-702">**Teams の予定表の改善:** 予定表の項目を右クリックすると、出欠確認のオプションを表示したり、会議の参加者とのチャットを開始したり、会議開始時にすぐにその会議に参加したりすることができます。</span><span class="sxs-lookup"><span data-stu-id="2154d-702">**Improvements to the Teams calendar:** Right-click an item in your calendar to pull up RSVP options, start a chat with meeting participants, or quickly join a meeting when it starts.</span></span> <span data-ttu-id="2154d-703">また、イベントのスケジュール設定のフォームも改善されています。</span><span class="sxs-lookup"><span data-stu-id="2154d-703">We've also made improvements to the event scheduling form.</span></span>

- <span data-ttu-id="2154d-704">**ユーザーへのタグ付け:** タグを作成してユーザーに割り当てて、グループ、役割、部署などに @mention を付けることができます。チームの所有者はぜひお試しください。</span><span class="sxs-lookup"><span data-stu-id="2154d-704">**Tag, you're it!:** Create tags and assign people to them so you can @mention a group, role, department, etc. Team owners, try it out for yourselves.</span></span> <span data-ttu-id="2154d-705">チームに移動し、[その他のオプション]、[タグの管理] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="2154d-705">Go to a team, select More options, Manage tags.</span></span>

### <a name="word"></a><span data-ttu-id="2154d-706">Word</span><span class="sxs-lookup"><span data-stu-id="2154d-706">Word</span></span>

- <span data-ttu-id="2154d-707">**ツールの使いやすさを維持:** [描画] ツールボックスには、テキストにインク ジェスチャを追加できるインテリジェント ペンが用意されています。</span><span class="sxs-lookup"><span data-stu-id="2154d-707">**Keep your tools handy:** In your drawing toolbox, find the intelligent pen that allows you to add ink gestures to text.</span></span> [<span data-ttu-id="2154d-708">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-708">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- <span data-ttu-id="2154d-709">**ドキュメントの見映えを良くする新しい画像:** 何千ものロイヤリティフリーの画像、アイコン、ステッカーが用意されており、これらをドキュメントで使用できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-709">**New images to bring your documents to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your documents.</span></span> <span data-ttu-id="2154d-710">開始するには、[挿入] > [画像] > [ストック画像] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="2154d-710">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="2154d-711">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-711">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-714">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-714">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2154d-715">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-715">Excel</span></span>

- <span data-ttu-id="2154d-716">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="2154d-716">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="2154d-717">ピボットテーブルを含むシートをコピーした後、Excel がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-717">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="2154d-718">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="2154d-718">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="2154d-719">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-719">Outlook</span></span>

- <span data-ttu-id="2154d-720">フォルダー ウィンドウの幅が予期せず変更される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-720">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>


- <span data-ttu-id="2154d-721">Windows の一部のビルドで Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-721">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>


- <span data-ttu-id="2154d-722">Windows の更新後に、ローカルに保存された .msg または .oft ファイルを開くと Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-722">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>


- <span data-ttu-id="2154d-723">Windows の一部のビルドで Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-723">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>


- <span data-ttu-id="2154d-724">Outlook の終了中に応答が停止するする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-724">Addressed an issue that caused users to experience a hang while exiting Outlook.</span></span>


### <a name="project"></a><span data-ttu-id="2154d-725">Project</span><span class="sxs-lookup"><span data-stu-id="2154d-725">Project</span></span>

- <span data-ttu-id="2154d-726">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="2154d-726">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>


- <span data-ttu-id="2154d-727">Project Web App に接続されている Project を使用していて小数点の記号がカンマの場合に、依存関係のタイム ラグを生じさせようとすると TaskDependencies Add メソッドが失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-727">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2154d-728">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2154d-728">Office Suite</span></span>

- <span data-ttu-id="2154d-729">アクセスの制限と、パスワードによるファイルの保護が同時に行えないというエラーを解決しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-729">Resolved an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-april-15"></a><span data-ttu-id="2154d-731">バージョン 2003: 4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="2154d-731">Version 2003: April 15</span></span>
<span data-ttu-id="2154d-732">*バージョン 2003 (ビルド 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="2154d-732">*Version 2003 (Build 12624.20466)*</span></span>
* <span data-ttu-id="2154d-733">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="2154d-733">Various bugs and performance fixes.</span></span>

## <a name="version-2003-april-14"></a><span data-ttu-id="2154d-734">バージョン 2003: 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2154d-734">Version 2003: April 14</span></span>
<span data-ttu-id="2154d-735">*バージョン 2003 (ビルド 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="2154d-735">*Version 2003 (Build 12624.20442)*</span></span>

<span data-ttu-id="2154d-736">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2154d-736">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-738">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-738">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2154d-739">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-739">Excel</span></span>

- <span data-ttu-id="2154d-740">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="2154d-740">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="2154d-741">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-741">Outlook</span></span>

- <span data-ttu-id="2154d-742">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-742">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="2154d-743">Project</span><span class="sxs-lookup"><span data-stu-id="2154d-743">Project</span></span>

- <span data-ttu-id="2154d-744">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="2154d-744">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

### <a name="word"></a><span data-ttu-id="2154d-745">Word</span><span class="sxs-lookup"><span data-stu-id="2154d-745">Word</span></span>

- <span data-ttu-id="2154d-746">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-746">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-31"></a><span data-ttu-id="2154d-748">バージョン 2003: 3 月 31 日</span><span class="sxs-lookup"><span data-stu-id="2154d-748">Version 2003: March 31</span></span>
<span data-ttu-id="2154d-749">*バージョン 2003 (ビルド 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="2154d-749">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-751">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-751">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="2154d-752">OneNote</span><span class="sxs-lookup"><span data-stu-id="2154d-752">OneNote</span></span>

- <span data-ttu-id="2154d-753">全世界でサービス使用量が高まった際に、同期とサービスの可用性を改善できる、Microsoft OneNote の一時的な調整に関して、情報バーを介してユーザーに通知します。</span><span class="sxs-lookup"><span data-stu-id="2154d-753">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

### <a name="project"></a><span data-ttu-id="2154d-754">Project</span><span class="sxs-lookup"><span data-stu-id="2154d-754">Project</span></span>

- <span data-ttu-id="2154d-755">実績作業時間の保護設定を有効にしているときに、ユーザーがタイムフェーズの基準作業時間を入力できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2154d-755">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-25"></a><span data-ttu-id="2154d-757">バージョン 2003: 3 月 25 日</span><span class="sxs-lookup"><span data-stu-id="2154d-757">Version 2003: March 25</span></span>
<span data-ttu-id="2154d-758">*バージョン 2003 (ビルド 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="2154d-758">*Version 2003 (Build 12624.20320)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2154d-760">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2154d-760">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2154d-761">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-761">Excel</span></span>

- <span data-ttu-id="2154d-762">**お気に入りの Excel 関数が速くなりました：** SUMIFS、AVERAGEIFS、COUNTIFS、MAXIFS、および MINIFS 関数がこれまでよりもはるかに高速になりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-762">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="2154d-763">もっと素早く一番下に移動します。</span><span class="sxs-lookup"><span data-stu-id="2154d-763">Get to the bottom line more quickly.</span></span> <span data-ttu-id="2154d-764">今すぐお試しください。</span><span class="sxs-lookup"><span data-stu-id="2154d-764">Try one now.</span></span>

### <a name="outlook"></a><span data-ttu-id="2154d-765">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-765">Outlook</span></span>

- <span data-ttu-id="2154d-766">**所有しているグループにメールをドラッグ:** メッセージや会話を受信トレイからドラッグして移動し、コピーします。</span><span class="sxs-lookup"><span data-stu-id="2154d-766">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="2154d-767">ドラッグしたメッセージは、すべてのグループ メンバーと共有されます。</span><span class="sxs-lookup"><span data-stu-id="2154d-767">Messages you drag will be shared with all group members.</span></span>

- <span data-ttu-id="2154d-768">**キャプティブ WiFi ネットワークの新しいエクスペリエンス** : サインインに Web ページを必要とする WiFi ネットワークに参加したことはありませんか ?</span><span class="sxs-lookup"><span data-stu-id="2154d-768">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="2154d-769">Outlook はこれを検出し、接続を支援します。</span><span class="sxs-lookup"><span data-stu-id="2154d-769">Outlook now detects this and helps you get connected.</span></span>

###<a name="powerpoint"></a><span data-ttu-id="2154d-770">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2154d-770">PowerPoint</span></span>

- <span data-ttu-id="2154d-771">**コメント:** PowerPoint の新しいコメント機能により、ドキュメントにコメントをすばやく簡単に見つけて追加できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-771">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="2154d-772">コメントの固定、解決、タスク、改善された通知などの新機能を使用して、コラボレーションワークフローを最新のものにします。</span><span class="sxs-lookup"><span data-stu-id="2154d-772">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span>

### <a name="word"></a><span data-ttu-id="2154d-773">Word</span><span class="sxs-lookup"><span data-stu-id="2154d-773">Word</span></span>

- <span data-ttu-id="2154d-774">**他のユーザーがすばやく変更を確認する:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="2154d-774">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2154d-775">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2154d-775">Office Suite</span></span>

- <span data-ttu-id="2154d-776">**秘密度ラベル:** カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-776">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-779">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-779">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2154d-780">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-780">Excel</span></span>

- <span data-ttu-id="2154d-781">Word または PowerPoint に埋め込まれたブックをもう一度開くと、場合によっては Excel がクラッシュする可能性があります。</span><span class="sxs-lookup"><span data-stu-id="2154d-781">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="2154d-782">ソース ブックが閉じていると、外部リンクが塗りつぶし時に更新されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-782">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="2154d-783">テンプレートからグラフを作成するときに発生するパフォーマンスの問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-783">Addressed a performance issue when creating charts from templates.</span></span>

### <a name="onenote"></a><span data-ttu-id="2154d-784">OneNote</span><span class="sxs-lookup"><span data-stu-id="2154d-784">OneNote</span></span>

- <span data-ttu-id="2154d-785">新しい埋め込み添付ファイルの最大許容サイズを一時的に 50 MB に削減することにより、同期とサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="2154d-785">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB.</span></span> <span data-ttu-id="2154d-786">この制限を超えるファイルの場合、ユーザーは OneDrive にファイルをアップロードして、OneNote にリンクを挿入することができます。</span><span class="sxs-lookup"><span data-stu-id="2154d-786">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="2154d-787">OneNote 2016 で同期頻度を一時的に調整することで、同期およびサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="2154d-787">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

### <a name="outlook"></a><span data-ttu-id="2154d-788">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-788">Outlook</span></span>

- <span data-ttu-id="2154d-789">終了後にタスク マネージャーに Outlook プロセスが残っているという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-789">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2154d-790">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2154d-790">PowerPoint</span></span>

- <span data-ttu-id="2154d-791">コピーと貼り付けのシナリオを改善しました。PowerPoint スライドでの図形のコピーと、ループ内の他のスライドへの貼り付けが例外で失敗する場合があります。</span><span class="sxs-lookup"><span data-stu-id="2154d-791">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="2154d-792">Project</span><span class="sxs-lookup"><span data-stu-id="2154d-792">Project</span></span>

- <span data-ttu-id="2154d-793">[無効化] ボタンを介してタスクが非アクティブ化/アクティブ化された場合に、ProjectBeforeTaskChange イベントが検出しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-793">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="2154d-794">以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-794">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="2154d-795">タスクを完了とマークした後に、タスクの達成率が 100% 完了より小さい値に誤って変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-795">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="2154d-796">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-796">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-march-10"></a><span data-ttu-id="2154d-798">バージョン 2002: 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="2154d-798">Version 2002: March 10</span></span>
<span data-ttu-id="2154d-799">*バージョン 2002 (ビルド 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="2154d-799">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="2154d-800">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2154d-800">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2154d-802">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2154d-802">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="2154d-803">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2154d-803">PowerPoint</span></span>

- <span data-ttu-id="2154d-804">**スライドへのリンク:** 同僚にスライド デッキへの投稿を依頼し、ヘルプが必要なスライド上で直接開始します。</span><span class="sxs-lookup"><span data-stu-id="2154d-804">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-807">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-807">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="2154d-808">Project</span><span class="sxs-lookup"><span data-stu-id="2154d-808">Project</span></span>

- <span data-ttu-id="2154d-809">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-809">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2002-march-01"></a><span data-ttu-id="2154d-811">バージョン 2002: 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="2154d-811">Version 2002: March 01</span></span>
<span data-ttu-id="2154d-812">*バージョン 2002 (ビルド 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="2154d-812">*Version 2002 (Build 12527.20242)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-814">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-814">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2154d-815">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-815">Outlook</span></span>

- <span data-ttu-id="2154d-816">サードパーティ製アプリケーションがメールを送信できない原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2154d-816">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2002-february-25"></a><span data-ttu-id="2154d-818">バージョン 2002: 2 月 25 日</span><span class="sxs-lookup"><span data-stu-id="2154d-818">Version 2002: February 25</span></span>
<span data-ttu-id="2154d-819">*バージョン 2002 (ビルド 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="2154d-819">*Version 2002 (Build 12527.20194)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2154d-821">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2154d-821">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2154d-822">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-822">Excel</span></span>

- <span data-ttu-id="2154d-823">**ブックの統計情報:** セル、数式、グラフ、テーブル...これらをお客様に代わってカウントします。</span><span class="sxs-lookup"><span data-stu-id="2154d-823">**Workbook Statistics:** Cells, formulas, charts, tables... We count them so you don't have to.</span></span>

- <span data-ttu-id="2154d-824">**クエリ エディターでのデータ プロファイリング** : 列のデータを一目で分析し、エラーと空の値を識別し、配布ヒストグラムなどを確認します。</span><span class="sxs-lookup"><span data-stu-id="2154d-824">**Data Profiling in Query Editor:** Get at-a-glance analysis of the data in your columns, identify error and empty values, see distribution histograms and more.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-827">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-827">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2154d-828">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-828">Excel</span></span>

- <span data-ttu-id="2154d-829">CUBEVALUE 関数が間違った結果を返すことがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2154d-829">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="2154d-830">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-830">Outlook</span></span>

- <span data-ttu-id="2154d-831">会議の [場所] フィールドにあるコンマがセミコロンになる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-831">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="2154d-832">複数のウィンドウで同じアイテムを表示するとクラッシュする場合がある問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-832">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="2154d-833">フラグ付きアイテムの強調表示を無効にするオプションが一部のシナリオで無視される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2154d-833">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="2154d-834">同期のスライダーが小さい設定に設定されている場合でも、Outlook で予期せずすべてのメールが同期される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-834">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>


- <span data-ttu-id="2154d-835">黒のテーマを持つユーザーが [差出人] ドロップダウンを表示すると、白色の背景に白いテキストが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-835">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>


- <span data-ttu-id="2154d-836">この変更により、メッセージ ヘッダーに複数行の件名を表示できる機能が復元されます。</span><span class="sxs-lookup"><span data-stu-id="2154d-836">This change restores the ability to view multi-line subjects in the message header.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2001-february-19"></a><span data-ttu-id="2154d-838">バージョン 2001: 2 月 19 日</span><span class="sxs-lookup"><span data-stu-id="2154d-838">Version 2001: February 19</span></span>
<span data-ttu-id="2154d-839">*バージョン 2001 (ビルド 12430.20288)*</span><span class="sxs-lookup"><span data-stu-id="2154d-839">*Version 2001 (Build 12430.20288)*</span></span>
* <span data-ttu-id="2154d-840">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="2154d-840">Various bugs and performance fixes.</span></span>

## <a name="version-2001-february-11"></a><span data-ttu-id="2154d-841">バージョン 2001: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2154d-841">Version 2001: February 11</span></span>
<span data-ttu-id="2154d-842">*バージョン 2001 (ビルド 12430.20264)*</span><span class="sxs-lookup"><span data-stu-id="2154d-842">*Version 2001 (Build 12430.20264)*</span></span>

<span data-ttu-id="2154d-843">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2154d-843">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-845">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-845">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2154d-846">Access</span><span class="sxs-lookup"><span data-stu-id="2154d-846">Access</span></span>

- <span data-ttu-id="2154d-847">Access テンプレートは、データベース内の添付ファイル列のエラーを発生させることがなくなりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-847">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="2154d-848">テンプレートのインスタンス化後に、データベースに添付ファイル フィールドを追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2154d-848">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="2154d-849">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-849">Excel</span></span>

- <span data-ttu-id="2154d-850">コンテキスト メニューのコメント コマンドが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-850">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="2154d-851">スピル配列が含まれるセルで区切り位置を指定するとクラッシュが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-851">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


### <a name="outlook"></a><span data-ttu-id="2154d-852">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-852">Outlook</span></span>

- <span data-ttu-id="2154d-853">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-853">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="2154d-854">ユーザーがアカウントのセットアップをキャンセルするときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-854">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>


### <a name="project"></a><span data-ttu-id="2154d-855">Project</span><span class="sxs-lookup"><span data-stu-id="2154d-855">Project</span></span>

- <span data-ttu-id="2154d-856">作業時間固定タイプの達成率 100% のタスクで、達成率が誤って 100% 未満に計算される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-856">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2154d-857">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2154d-857">Office Suite</span></span>

- <span data-ttu-id="2154d-858">この変更では、Intel Integrated GPU を使用するグラフィック アダプターに関して報告された問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2154d-858">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2001-january-30"></a><span data-ttu-id="2154d-860">バージョン 2001: 1 月 30 日</span><span class="sxs-lookup"><span data-stu-id="2154d-860">Version 2001: January 30</span></span>
<span data-ttu-id="2154d-861">*バージョン 2001 (ビルド 12430.20184)*</span><span class="sxs-lookup"><span data-stu-id="2154d-861">*Version 2001 (Build 12430.20184)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2154d-863">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2154d-863">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2154d-864">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-864">Excel</span></span>

- <span data-ttu-id="2154d-865">**すぐに読んで返信する** : ブックを開かずに、メールからコメントやメンションに直接返信します。</span><span class="sxs-lookup"><span data-stu-id="2154d-865">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="2154d-866">**左を見て、右を見て... XLOOKUP をご利用いただけます!** XLOOKUP を使えば、表や範囲内で必要なものは何でも見つけられます。</span><span class="sxs-lookup"><span data-stu-id="2154d-866">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="2154d-867">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-867">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)

### <a name="outlook"></a><span data-ttu-id="2154d-868">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-868">Outlook</span></span>

- <span data-ttu-id="2154d-869">**高度なグループ メールの設定:** この機能は、グループ ユーザーが受信トレイで受信/フォローするメールまたはイベントを、カスタマイズするのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="2154d-869">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="2154d-870">**グループの名前付けポリシー** : グループの名前付けポリシーを使用すると、IT 管理者は組織内のユーザーが作成するグループの名前の標準化と管理を行えます。</span><span class="sxs-lookup"><span data-stu-id="2154d-870">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="2154d-871">管理者は、グループが作成される際に特定のプレフィックスとサフィックスをグループ名に追加することを要求できます。また、特定の単語の使用を禁止できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-871">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="2154d-872">これにより、グループ名での不適切な単語の使用を最小限に抑えられる他、ディレクトリ内のグループ名の記載を IT 管理者が管理できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-872">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="2154d-873">また、名前付けポリシーを使用することで、チーム サイトを展開する組織は、チーム サイトを部署ごとに分類できるようにもなります。</span><span class="sxs-lookup"><span data-stu-id="2154d-873">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="word"></a><span data-ttu-id="2154d-874">Word</span><span class="sxs-lookup"><span data-stu-id="2154d-874">Word</span></span>

- <span data-ttu-id="2154d-875">**より安全なビデオ エクスペリエンス:** セキュリティの強化は、より安全なオンライン ビデオ エクスペリエンスを意味します。</span><span class="sxs-lookup"><span data-stu-id="2154d-875">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="2154d-876">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-876">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="2154d-877">**インクのなげなわ:** [描画] タブのなげなわツールを使用すると、インクで描かれたオブジェクトを選択できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-877">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="2154d-878">個別のストロークまたは文字全体を選択できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-878">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="2154d-879">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-879">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)






[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-882">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-882">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2154d-883">Access</span><span class="sxs-lookup"><span data-stu-id="2154d-883">Access</span></span>

- <span data-ttu-id="2154d-884">この更新プログラムでは、ADODB を使用する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="2154d-884">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="2154d-885">VB コードのレコーダー オブジェクトがエラーを誤って報告することがあります。</span><span class="sxs-lookup"><span data-stu-id="2154d-885">Recorder object in VB code may incorrectly report an error.</span></span>


- <span data-ttu-id="2154d-886">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2154d-886">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="2154d-887">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-887">Excel</span></span>

- <span data-ttu-id="2154d-888">署名の名前を変更したときにクラッシュする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2154d-888">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>


### <a name="outlook"></a><span data-ttu-id="2154d-889">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-889">Outlook</span></span>

- <span data-ttu-id="2154d-890">署名の名前を変更したときにクラッシュする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2154d-890">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1912-january-22"></a><span data-ttu-id="2154d-892">バージョン 1912: 1 月 22 日</span><span class="sxs-lookup"><span data-stu-id="2154d-892">Version 1912: January 22</span></span>
<span data-ttu-id="2154d-893">*バージョン 1912 (ビルド 12325.20344)*</span><span class="sxs-lookup"><span data-stu-id="2154d-893">*Version 1912 (Build 12325.20344)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-895">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-895">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2154d-896">Access</span><span class="sxs-lookup"><span data-stu-id="2154d-896">Access</span></span>

- <span data-ttu-id="2154d-897">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2154d-897">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1912-january-14"></a><span data-ttu-id="2154d-899">バージョン 1912: 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2154d-899">Version 1912: January 14</span></span>
<span data-ttu-id="2154d-900">*バージョン 1912 (ビルド 12325.20298)*</span><span class="sxs-lookup"><span data-stu-id="2154d-900">*Version 1912 (Build 12325.20298)*</span></span>

<span data-ttu-id="2154d-901">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2154d-901">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1912-january-08"></a><span data-ttu-id="2154d-902">バージョン 1912: 1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="2154d-902">Version 1912: January 08</span></span>
<span data-ttu-id="2154d-903">*バージョン 1912 (ビルド 12325.20288)*</span><span class="sxs-lookup"><span data-stu-id="2154d-903">*Version 1912 (Build 12325.20288)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2154d-905">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2154d-905">Feature updates</span></span>

### <a name="outlook"></a><span data-ttu-id="2154d-906">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-906">Outlook</span></span>

- <span data-ttu-id="2154d-907">**アクセシビリティ対応のメールを最も必要としている人に送信する:** Outlook では、メールのヒントが表示され、アクセシビリティ対応のコンテンツを必要とするユーザーに送信するときに、コンテンツがアクセシビリティ対応であることを確認できます</span><span class="sxs-lookup"><span data-stu-id="2154d-907">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2154d-908">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2154d-908">PowerPoint</span></span>

- <span data-ttu-id="2154d-909">**プレゼンテーションの最適化:** アクセシビリティ チェックを使用すると、スクリーン リーダーを考慮に入れて、スライド上のオブジェクトを配置することができます。</span><span class="sxs-lookup"><span data-stu-id="2154d-909">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="2154d-910">**簡単な GIF:** 1 つのスライド、1 つのフレーム。</span><span class="sxs-lookup"><span data-stu-id="2154d-910">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="2154d-911">PowerPoint でループ GIF を簡単に作成できます。</span><span class="sxs-lookup"><span data-stu-id="2154d-911">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="2154d-912">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2154d-912">Learn more</span></span>](https://support.office.com/en-us/article/a598753e-92de-4f1b-8393-714db4d334b4)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2154d-915">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2154d-915">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2154d-916">Excel</span><span class="sxs-lookup"><span data-stu-id="2154d-916">Excel</span></span>

- <span data-ttu-id="2154d-917">この変更は、ソフトウェア レンダリングを活用することにより、特定の Intel グラフィック ドライバーの問題を回避します。</span><span class="sxs-lookup"><span data-stu-id="2154d-917">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

### <a name="outlook"></a><span data-ttu-id="2154d-918">Outlook</span><span class="sxs-lookup"><span data-stu-id="2154d-918">Outlook</span></span>

- <span data-ttu-id="2154d-919">会議をクリアした後、会議の場所が予期せずに会議に追加される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-919">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="2154d-920">キーボード ショートカットを使用してメールボックス フォルダーを操作すると、ユーザーに顕著な遅延が発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-920">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="2154d-921">状況によっては、表示された SMTP アドレスと一致しないアドレスに送信されたメールがユーザーに表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-921">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="2154d-922">ユーザーがクラウド設定を取得する際に Outlook がフリーズする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-922">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

### <a name="word"></a><span data-ttu-id="2154d-923">Word</span><span class="sxs-lookup"><span data-stu-id="2154d-923">Word</span></span>

- <span data-ttu-id="2154d-924">文書パーツ オーガナイザーに 「スタイル、文書パーツを変更しました」 という無効なアラートが表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="2154d-924">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="2154d-925">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2154d-925">Office Suite</span></span>

- <span data-ttu-id="2154d-926">Office の更新プログラムが、意図したソース (ローカル共有、ネットワーク共有、構成マネージャー
で提供される場所など) からではなく、予期せずに Office CDN からファイルをダウンロードする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2154d-926">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

> [!NOTE]
> <span data-ttu-id="2154d-928">Office の使用で問題がある場合は、[Microsoft の回答フォーラム](https://answers.microsoft.com/)に関するページまたは「[Microsoft Tech Community](https://techcommunity.microsoft.com/)」に質問を投稿するか、[サポート](https://support.microsoft.com/contactus)に問い合わせてサポートを受けることができます。</span><span class="sxs-lookup"><span data-stu-id="2154d-928">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>

[//]: # (管理センターのメタデータのコンテンツを変更しないでください。開始)
[//]: # (|Win32|CC|Production| |16.0.13328.20292|version-2010-october-27|)
[//]: # (|Win32|CC|Production| |16.0.13231.20418|version-2009-october-21|)
[//]: # (|Win32|CC|Production| |16.0.13231.20390|version-2009-october-13|)
[//]: # (|Win32|CC|Production| |16.0.13231.20368|version-2009-october-08|)
[//]: # (|Win32|CC|Production| |16.0.13231.20262|バージョン-2009-september-28|)
[//]: # (|Win32|CC|Production| |16.0.13127.20508|version-2008-september-22|)
[//]: # (|Win32|CC|Production| |16.0.13127.20408|version-2008-september-09|)
[//]: # (|Win32|CC|Production| |16.0.13127.20296|バージョン-2008-8-31|)
[//]: # (|Win32|CC|Production| |16.0.13029.20460|バージョン-2007-8-25|)
[//]: # (|Win32|CC|Production| |16.0.13029.20344|バージョン-2007-8-11|)
[//]: # (管理センターのメタデータのコンテンツを変更しないでください。終了)
