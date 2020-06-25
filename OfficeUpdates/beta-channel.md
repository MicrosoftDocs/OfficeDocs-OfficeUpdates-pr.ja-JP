---
title: ベータチャネルのリリースノート
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Insider Fast の対象ユーザーに主な新機能、修正プログラム、既知の問題の最新リストを提供します
ms.openlocfilehash: 9585d43c73676e2a12f38b34cbd6c57172bbe917
ms.sourcegitcommit: a0285b69d4d48b5ef4ac3c54678fb67ce399b73e
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/25/2020
ms.locfileid: "44874793"
---
# <a name="release-notes-for-beta-channel"></a><span data-ttu-id="84742-103">ベータチャネルのリリースノート</span><span class="sxs-lookup"><span data-stu-id="84742-103">Release Notes for Beta Channel</span></span>

<span data-ttu-id="84742-104">この記事には、Windows デスクトップ用の Word、Excel、PowerPoint、Outlook、Access、および Project のベータ版チャネルビルドのリリースノートが記載されています。</span><span class="sxs-lookup"><span data-stu-id="84742-104">This article contains release notes for Beta Channel builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="84742-105">Microsoft では、毎週、皆様にお知らせしたい魅力的な新機能、重要な修正プログラム、重大な問題に関する情報を提供しています。</span><span class="sxs-lookup"><span data-stu-id="84742-105">Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="84742-106">多くの場合、機能 (および場合によっては修正) をベータチャネルに長期間にわたってロールアウトすることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="84742-106">Note that we often roll out features (and sometimes even fixes) to Beta Channel over a period of time.</span></span> <span data-ttu-id="84742-107">これにより、Microsoft では、より広範な対象ユーザーに機能をリリースする前に、作業がスムーズに行われていることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="84742-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="84742-108">以下に示すものが表示されない場合でも、最終的には入手できますのでご安心ください。</span><span class="sxs-lookup"><span data-stu-id="84742-108">So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="84742-109">Microsoft 365 アプリの更新チャネルの更新プログラムチャネルに、新しい更新チャネル (月間エンタープライズ チャネル) の追加や、既存の更新プログラムチャネルの名前の変更など、いくつかの変更を行っています。</span><span class="sxs-lookup"><span data-stu-id="84742-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="84742-110">詳細については、[こちらの記事を参照](https://go.microsoft.com/fwlink/p/?linkid=2127441)をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="84742-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="84742-111">リリース ノートは毎週投稿され、場合により複数のビルドのコンパイルになります。</span><span class="sxs-lookup"><span data-stu-id="84742-111">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="84742-112">リリースノートの発行日は実際のビルドのリリース日と一致しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="84742-112">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (削除しないでください)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

## <a name="version-2007-june-19"></a><span data-ttu-id="84742-115">バージョン 2007: 6 月19日</span><span class="sxs-lookup"><span data-stu-id="84742-115">Version 2007: June 19</span></span>
<span data-ttu-id="84742-116">*バージョン 2007 (ビルド 13012.20000)*</span><span class="sxs-lookup"><span data-stu-id="84742-116">*Version 2007 (Build 13012.20000)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="84742-118">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="84742-118">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="84742-119">Excel</span><span class="sxs-lookup"><span data-stu-id="84742-119">Excel</span></span>

- <span data-ttu-id="84742-120">SharePoint/OneDrive にブックを保存するときに、カスタムリボンタブの CustomUI XML が削除されたという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-120">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>
- <span data-ttu-id="84742-121">ファイルが読み取り専用のみを推奨している場合、ブックが読み取り専用であるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-121">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

### <a name="outlook"></a><span data-ttu-id="84742-122">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-122">Outlook</span></span>

- <span data-ttu-id="84742-123">入力方式エディター (IME) ウィンドウが、さまざまな解像度の複数のモニターを使用しているときに、IME によって入力された基になるテキストと重なるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-123">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="84742-124">以前に保存された予定を閉じるときに次のエラーが表示される問題を修正しました。 "別のユーザーまたは別のウィンドウで変更されたため、アイテムを保存できません。</span><span class="sxs-lookup"><span data-stu-id="84742-124">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved: "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="84742-125">アイテムの既定のフォルダーにコピーを作成しますか? "</span><span class="sxs-lookup"><span data-stu-id="84742-125">Do you want to make a copy in the default folder for the item?"</span></span>
- <span data-ttu-id="84742-126">日本のユーザーは、ミニカレンダーの日付が太字で表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-126">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>
- <span data-ttu-id="84742-127">予定表のアラームで、会議が1週間未満であることを正確に表示できないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="84742-127">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="84742-128">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="84742-128">PowerPoint</span></span>

- <span data-ttu-id="84742-129">ライブ共同編集セッション中に、共同編集用のギャラリーでユーザーのプレゼンスカラーインジケーターが更新されなかったという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-129">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>

### <a name="project"></a><span data-ttu-id="84742-130">Project</span><span class="sxs-lookup"><span data-stu-id="84742-130">Project</span></span>

- <span data-ttu-id="84742-131">固定期間タスクが100% 完了しているにもかかわらず、実績終了日が指定されていないという問題を修正しました。タスク% 完了は100% 未満と表示されます。</span><span class="sxs-lookup"><span data-stu-id="84742-131">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

### <a name="word"></a><span data-ttu-id="84742-132">Word</span><span class="sxs-lookup"><span data-stu-id="84742-132">Word</span></span>

- <span data-ttu-id="84742-133">HTML ハイパーリンクの色が正しく表示されていない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-133">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="84742-134">Office スイート</span><span class="sxs-lookup"><span data-stu-id="84742-134">Office Suite</span></span>

- <span data-ttu-id="84742-135">Http または https ベースではない Url が最近使用した一覧に表示されていないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-135">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-june-12"></a><span data-ttu-id="84742-137">バージョン 2007: 6 月12日</span><span class="sxs-lookup"><span data-stu-id="84742-137">Version 2007: June 12</span></span>
<span data-ttu-id="84742-138">*バージョン 2007 (ビルド 13006.20002)*</span><span class="sxs-lookup"><span data-stu-id="84742-138">*Version 2007 (Build 13006.20002)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="84742-140">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="84742-140">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="84742-141">Excel</span><span class="sxs-lookup"><span data-stu-id="84742-141">Excel</span></span>

- <span data-ttu-id="84742-142">**データ型を使用して POWER BI から組織のデータを取得します。** Power BI からの Excel データ型は、Office 365 E5/A5 または Microsoft 365 E5/A5 を使用している組織内の内部に展開されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="84742-142">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="84742-143">必要な情報を取得して簡単に更新できることは、多くの日常のワークフローにとって非常に重要です。</span><span class="sxs-lookup"><span data-stu-id="84742-143">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="84742-144">Excel のデータ型として、Power BI から会社または組織の情報にアクセスできるようにします。これにより、スプレッドシートにリンクされた情報を取り込む機能が拡張されます。</span><span class="sxs-lookup"><span data-stu-id="84742-144">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="84742-145">詳細情報</span><span class="sxs-lookup"><span data-stu-id="84742-145">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="84742-146">[ブログの投稿](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="84742-146">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="84742-149">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="84742-149">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="84742-150">Access</span><span class="sxs-lookup"><span data-stu-id="84742-150">Access</span></span>

- <span data-ttu-id="84742-151">リンクされた SQL Server テーブル内の Id 列を特定できない原因となった問題を修正しました。これにより、行が誤って削除されたとして報告されることがあります。</span><span class="sxs-lookup"><span data-stu-id="84742-151">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="84742-152">Excel</span><span class="sxs-lookup"><span data-stu-id="84742-152">Excel</span></span>

- <span data-ttu-id="84742-153">レーダーチャートの主要なグリッド線が正しく書式設定できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-153">We fixed an issue where the major grid lines of radar charts could not be formatted correctly.</span></span>

### <a name="project"></a><span data-ttu-id="84742-154">Project</span><span class="sxs-lookup"><span data-stu-id="84742-154">Project</span></span>

- <span data-ttu-id="84742-155">プロジェクトのサマリータスクに変更があったとき、プロジェクトの開始/タスクフィールドのいずれかで ProjectBeforeTaskChange イベントが発生しなかったという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-155">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>
- <span data-ttu-id="84742-156">基準のリセットまたは更新によって、時間単位の予算コスト/作業リソースが変更され、基準値が正しくない予算値を表す可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-156">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>

### <a name="word"></a><span data-ttu-id="84742-157">Word</span><span class="sxs-lookup"><span data-stu-id="84742-157">Word</span></span>

- <span data-ttu-id="84742-158">Office リボンの [書式のクリア] ボタンを使用して、[コメント] ウィンドウ内の書式をクリアする機能が機能しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-158">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>
- <span data-ttu-id="84742-159">ルーラーが表示されない場合にテーブルのサイズを変更すると、バックグラウンドで実行されている他のアプリケーションのフラッシュが開始されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-159">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>
- <span data-ttu-id="84742-160">共同編集モードの場合、コメントの返信がコメントウィンドウに表示されないことがありますが、[変更履歴] ウィンドウに表示されることがあります。</span><span class="sxs-lookup"><span data-stu-id="84742-160">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>
- <span data-ttu-id="84742-161">Word では、50個を超える頻繁に開かれたドキュメントがある場合、ドキュメントを保存して開くと、そのドキュメントに変更が加えられていなくても、改訂履歴が表示されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-161">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-june-05"></a><span data-ttu-id="84742-163">バージョン 2006:05 年6月</span><span class="sxs-lookup"><span data-stu-id="84742-163">Version 2006: June 05</span></span>
<span data-ttu-id="84742-164">*バージョン 2006 (ビルド 13001.20002)*</span><span class="sxs-lookup"><span data-stu-id="84742-164">*Version 2006 (Build 13001.20002)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="84742-166">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="84742-166">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="84742-167">Excel</span><span class="sxs-lookup"><span data-stu-id="84742-167">Excel</span></span>

- <span data-ttu-id="84742-168">**Excel での共同作業の際に、並べ替え/フィルター処理を実行します。** 他のユーザーとの共同作業を行っているときに、Excel ファイルの並べ替えとフィルター処理を実行できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="84742-168">**Sort/filter while collaborating in Excel:** You can now sort and filter your Excel file while collaborating with others.</span></span> <span data-ttu-id="84742-169">この新機能により、ドキュメントを共同編集する際に、他のユーザーの並べ替えとフィルターの影響を受けないようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="84742-169">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span>

- <span data-ttu-id="84742-170">**Excel 内の POWER BI のデータセットからピボットテーブルを作成します。** Excel では、いくつかのクリックで Power BI に格納されたデータセットに接続されたピボットテーブルを作成できます。</span><span class="sxs-lookup"><span data-stu-id="84742-170">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span><span data-ttu-id="84742-171">これにより、ピボットテーブルと Power BI の両方を最大限に活用できます。</span><span class="sxs-lookup"><span data-stu-id="84742-171"> Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="84742-172">セキュリティで保護された Power BI データセットからのピボットテーブルを使用して、データの計算、要約、および分析を行います。</span><span class="sxs-lookup"><span data-stu-id="84742-172">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="84742-173">詳細情報</span><span class="sxs-lookup"><span data-stu-id="84742-173">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a><span data-ttu-id="84742-174">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-174">Outlook</span></span>

- <span data-ttu-id="84742-175">**以前のセッションからアイテムをすぐに再び開く:** 以前の Outlook セッションからアイテムをすばやく開くオプションを追加しました。</span><span class="sxs-lookup"><span data-stu-id="84742-175">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="84742-176">Outlook がクラッシュするか閉じるかにかかわらず、アプリを再度開くと、アイテムをすばやく再起動することができるようになります。</span><span class="sxs-lookup"><span data-stu-id="84742-176">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="84742-177">この機能は既定でオンになっています。</span><span class="sxs-lookup"><span data-stu-id="84742-177">This feature is on by default.</span></span> <span data-ttu-id="84742-178">この機能をオフにするには、[オプション > 全般 > の起動オプション] に移動します。</span><span class="sxs-lookup"><span data-stu-id="84742-178">To turn it off, go to Options > General > Start up Options.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="84742-181">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="84742-181">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="84742-182">Excel</span><span class="sxs-lookup"><span data-stu-id="84742-182">Excel</span></span>

- <span data-ttu-id="84742-183">グラフ軸のカスタム値が正しく適用されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-183">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>
- <span data-ttu-id="84742-184">定義された名前を持つ複数の数式を含むワークシートで、ファイルの保存に長い時間がかかるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-184">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

### <a name="outlook"></a><span data-ttu-id="84742-185">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-185">Outlook</span></span>

- <span data-ttu-id="84742-186">IME (入力方式エディター) ウィンドウが、さまざまな解像度の複数のモニターを使用しているときに、IME によって入力された基になるテキストと重なるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-186">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="84742-187">新しい電子メールメッセージの作成時にテンプレートを表示すると、クラッシュするという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="84742-187">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>
- <span data-ttu-id="84742-188">Outlook バージョン1911後にユーザーが2010パブリックフォルダーを交換できなかったという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-188">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>
- <span data-ttu-id="84742-189">Office リボンのグループ予定表の [分類] ボタンが無効になっているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="84742-189">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="84742-190">競合する連絡先を持つユーザーが Outlook でクラッシュする原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-190">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>
- <span data-ttu-id="84742-191">高 DPI モニター上のユーザーに対して、フォルダーのプロパティに [オンラインアーカイブ] ドロップダウンボックスが存在しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-191">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>
- <span data-ttu-id="84742-192">ユーザーがテキスト形式の電子メールでハイパーリンクを使用しているときに Outlook でクラッシュが発生する原因となった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-192">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>
- <span data-ttu-id="84742-193">RFC2231 でエンコードされた長いファイル名を Outlook が解析できない原因となった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-193">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>
- <span data-ttu-id="84742-194">スクリーンリーダーを使用しているときに、Outlook ユーザーが断続的なハングを発生させたという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-194">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="84742-195">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="84742-195">PowerPoint</span></span>

- <span data-ttu-id="84742-196">フォームベース認証を使用してサーバー構成ファイルを開くという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-196">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>
- <span data-ttu-id="84742-197">グラフまたはブックが埋め込まれている PowerPoint ファイルを保存すると、ファイルの保存に失敗することがあるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-197">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>
- <span data-ttu-id="84742-198">ユーザーによって閉じられたコメントウィンドウが自動的に再オープンされるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-198">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>
- <span data-ttu-id="84742-199">スライドエディターが次のスライドに重なる場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-199">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="84742-200">Project</span><span class="sxs-lookup"><span data-stu-id="84742-200">Project</span></span>

- <span data-ttu-id="84742-201">孤立したタスクが削除されたり、親のプランが削除された後に再度割り当てられることを妨げる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-201">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="word"></a><span data-ttu-id="84742-202">Word</span><span class="sxs-lookup"><span data-stu-id="84742-202">Word</span></span>

- <span data-ttu-id="84742-203">コメントウィンドウのタイムスタンプがシステムロケール時間に基づいていないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-203">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>
- <span data-ttu-id="84742-204">Web アプリとデスクトップアプリケーションとの間のコメントが同期されていないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-204">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version2006may29"></a><span data-ttu-id="84742-206">バージョン 2006: 5 月29日</span><span class="sxs-lookup"><span data-stu-id="84742-206">Version 2006: May 29</span></span>
<span data-ttu-id="84742-207">*バージョン 2006 (ビルド 12920.20000)*</span><span class="sxs-lookup"><span data-stu-id="84742-207">*Version 2006 (Build 12920.20000)*</span></span>

### <a name="featureupdates"></a><span data-ttu-id="84742-208">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="84742-208">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="84742-209">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-209">Outlook</span></span>

- <span data-ttu-id="84742-210">**Outlook トースト通知に追加された追加のボタン:** Windows 10 で Outlook を実行しているときに、クイックアクションボタンが Outlook トースト通知に表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="84742-210">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="84742-211">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="84742-211">PowerPoint</span></span>

- <span data-ttu-id="84742-212">**PowerPoint でのストリームビデオパフォーマンスの向上:** ビデオの読み込み時間を最小限に抑えてスムーズな表示を実現するために、Microsoft Stream ビデオの再生パフォーマンスが改善されました。</span><span class="sxs-lookup"><span data-stu-id="84742-212">**Improved Stream video performance in PowerPoint:** We've made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span>  <span data-ttu-id="84742-213">Microsoft Stream の企業ビデオを使用して、より良いプレゼンテーションを作成します。</span><span class="sxs-lookup"><span data-stu-id="84742-213">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolvedissues"></a><span data-ttu-id="84742-216">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="84742-216">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="84742-217">Excel</span><span class="sxs-lookup"><span data-stu-id="84742-217">Excel</span></span>

- <span data-ttu-id="84742-218">OneDrive の利用時に Excel が停止することがあるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-218">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>
- <span data-ttu-id="84742-219">同じブック内でブックマークが設定されたハイパーリンクをクリックすると、ブックが非表示になるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-219">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>
- <span data-ttu-id="84742-220">一部のコピーと貼り付けグラフのリンクで、ユニバーサルアドレスではなく、マップされたドライブアドレスが使用されているという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-220">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>
- <span data-ttu-id="84742-221">Ctrl + Shift + 方向キーを使用して、Excel ウィンドウが Teams によって共有されているときにスクロールした後、Excel が応答しなくなるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-221">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="84742-222">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="84742-222">PowerPoint</span></span>

- <span data-ttu-id="84742-223">マウスホイールを使用してズームした後、スライドが中央に配置されていないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-223">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

### <a name="word"></a><span data-ttu-id="84742-224">Word</span><span class="sxs-lookup"><span data-stu-id="84742-224">Word</span></span>

- <span data-ttu-id="84742-225">コメントウィンドウへのテキストのコピーと貼り付けが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-225">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>
- <span data-ttu-id="84742-226">100% ズームでコメントヒントのバブルがぼやけて表示されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-226">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>
- <span data-ttu-id="84742-227">ポリシー Word 2007 以降のバイナリ文書とテンプレートを有効にすると、一部の共同編集が失敗するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="84742-227">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>
- <span data-ttu-id="84742-228">長いパス名 (32K より大きい) を持つファイルが開かず、適切なエラーメッセージが表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-228">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2006-may-22"></a><span data-ttu-id="84742-229">バージョン 2006: 5 月22日</span><span class="sxs-lookup"><span data-stu-id="84742-229">Version 2006: May 22</span></span>
<span data-ttu-id="84742-230">*バージョン 2006 (ビルド 12914.20000)*</span><span class="sxs-lookup"><span data-stu-id="84742-230">*Version 2006 (Build 12914.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="84742-232">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="84742-232">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="84742-233">Excel</span><span class="sxs-lookup"><span data-stu-id="84742-233">Excel</span></span>

- <span data-ttu-id="84742-234">**固定フォルダーに保存します。** フォルダーを固定すると、Office ファイルの保存が容易になります。</span><span class="sxs-lookup"><span data-stu-id="84742-234">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="84742-235">新しいファイルを保存するときに利用可能なフォルダーをユーザーがより詳細に制御するためのフィードバックを受信しました。</span><span class="sxs-lookup"><span data-stu-id="84742-235">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="84742-236">新しい機能の提供: [保存] ダイアログでフォルダーを固定します。</span><span class="sxs-lookup"><span data-stu-id="84742-236">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="84742-237">この新しい機能により、Word、Excel、および PowerPoint のファイルを簡単に保存できるようになります。</span><span class="sxs-lookup"><span data-stu-id="84742-237">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="84742-238">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="84742-238">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="84742-239">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="84742-239">PowerPoint</span></span>

- <span data-ttu-id="84742-240">**固定フォルダーに保存します。** フォルダーを固定すると、Office ファイルの保存が容易になります。</span><span class="sxs-lookup"><span data-stu-id="84742-240">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="84742-241">新しいファイルを保存するときに利用可能なフォルダーをユーザーがより詳細に制御するためのフィードバックを受信しました。</span><span class="sxs-lookup"><span data-stu-id="84742-241">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="84742-242">新しい機能の提供: [保存] ダイアログでフォルダーを固定します。</span><span class="sxs-lookup"><span data-stu-id="84742-242">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="84742-243">この新しい機能により、Word、Excel、および PowerPoint のファイルを簡単に保存できるようになります。</span><span class="sxs-lookup"><span data-stu-id="84742-243">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="84742-244">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="84742-244">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="84742-245">Word</span><span class="sxs-lookup"><span data-stu-id="84742-245">Word</span></span>

- <span data-ttu-id="84742-246">**固定フォルダーに保存します。** フォルダーを固定すると、Office ファイルの保存が容易になります。</span><span class="sxs-lookup"><span data-stu-id="84742-246">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="84742-247">新しいファイルを保存するときに利用可能なフォルダーをユーザーがより詳細に制御するためのフィードバックを受信しました。</span><span class="sxs-lookup"><span data-stu-id="84742-247">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="84742-248">新しい機能の提供: [保存] ダイアログでフォルダーを固定します。</span><span class="sxs-lookup"><span data-stu-id="84742-248">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="84742-249">この新しい機能により、Word、Excel、および PowerPoint のファイルを簡単に保存できるようになります。</span><span class="sxs-lookup"><span data-stu-id="84742-249">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="84742-250">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="84742-250">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="84742-253">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="84742-253">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="84742-254">Excel</span><span class="sxs-lookup"><span data-stu-id="84742-254">Excel</span></span>

- <span data-ttu-id="84742-255">「現在、このブックは他のユーザーによって参照されていますが、閉じられていません」というエラーメッセージが表示される問題を修正しました。アドインはユーザーが指定した順序ではなくアルファベット順で読み込まれています。</span><span class="sxs-lookup"><span data-stu-id="84742-255">We fixed an issue where the error message: “This workbook is currently referenced by another and cannot be closed” would appear because Add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>
- <span data-ttu-id="84742-256">Excel とサードパーティ製の補助的なテクノロジアプリケーションの間でフォントを管理するときに、メモリが破損しているという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-256">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>
- <span data-ttu-id="84742-257">アドインが、noSelect ロックの図形を含むワークシートのホストアイテムを要求すると、Excel がクラッシュするという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-257">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

### <a name="outlook"></a><span data-ttu-id="84742-258">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-258">Outlook</span></span>

- <span data-ttu-id="84742-259">ユーザーがフォルダー間でアイテムを移動したときに、フォルダー BeforeItemMove イベントが正常に起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-259">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>
- <span data-ttu-id="84742-260">午前0時のしきい値を超える予定表アイテムが終日イベントとして認識されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-260">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>
- <span data-ttu-id="84742-261">2つのアドインがリボンの同じグループにボタンを追加したときに Outlook がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-261">We fixed an issue where Outlook crashed when two Add-ins added a button to the same group in the ribbon.</span></span>
- <span data-ttu-id="84742-262">ユーザーが予定表をゲストユーザーと共有できなかったという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-262">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="84742-263">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="84742-263">PowerPoint</span></span>

- <span data-ttu-id="84742-264">プレゼンテーション領域を拡大または縮小すると、拡大または縮小した選択マーキーとマウスポインターとの間にギャップが発生するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="84742-264">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

### <a name="project"></a><span data-ttu-id="84742-265">Project</span><span class="sxs-lookup"><span data-stu-id="84742-265">Project</span></span>

- <span data-ttu-id="84742-266">[オプション] をクリックした後、Project がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-266">We fixed an issue where Project would crash after clicking on Options.</span></span>

### <a name="word"></a><span data-ttu-id="84742-267">Word</span><span class="sxs-lookup"><span data-stu-id="84742-267">Word</span></span>

- <span data-ttu-id="84742-268">コメント内のハイパーリンクが機能していないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="84742-268">We fixed an issue where hyperlinks in comments weren’t working.</span></span>
- <span data-ttu-id="84742-269">プレゼンテーション領域を拡大または縮小すると、拡大または縮小した選択マーキーとマウスポインターとの間にギャップが発生するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="84742-269">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>
- <span data-ttu-id="84742-270">WordMail に HTML を貼り付ける予定表が機能していなかったという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-270">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>
- <span data-ttu-id="84742-271">共同編集セッションでコメントに返信すると、Word がフリーズすることがあるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-271">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-may-15"></a><span data-ttu-id="84742-273">バージョン 2006: 5 月15日</span><span class="sxs-lookup"><span data-stu-id="84742-273">Version 2006: May 15</span></span>
<span data-ttu-id="84742-274">*バージョン 2006 (ビルド 12905.20000)*</span><span class="sxs-lookup"><span data-stu-id="84742-274">*Version 2006 (Build 12905.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="84742-276">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="84742-276">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="84742-277">Excel</span><span class="sxs-lookup"><span data-stu-id="84742-277">Excel</span></span>

- <span data-ttu-id="84742-278">**PDF 接続を作成します。** PDF からのデータへの接続、インポート、更新を行います。</span><span class="sxs-lookup"><span data-stu-id="84742-278">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="84742-279">詳細情報</span><span class="sxs-lookup"><span data-stu-id="84742-279">Learn more</span></span>](https://support.office.com/article/9967afd8-85ee-4df3-aa06-753bcc1a2724)

### <a name="outlook"></a><span data-ttu-id="84742-280">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-280">Outlook</span></span>

- <span data-ttu-id="84742-281">**必要なものだけを見つけます。** フォルダー、送信者、日付、添付ファイル情報などのオプションを使用して、検索を絞り込むことができます。</span><span class="sxs-lookup"><span data-stu-id="84742-281">**Find just what you need:** Narrow your search with options like folder, sender, date, attachment info, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="84742-282">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="84742-282">PowerPoint</span></span>

- <span data-ttu-id="84742-283">**クリッカーを使用する必要はありません。 earbuds について説明します。** Surface Earbuds を使用して PowerPoint プレゼンテーションを制御します。</span><span class="sxs-lookup"><span data-stu-id="84742-283">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="84742-284">重要: プレゼンテーションを制御するためにジェスチャを使用するには、Surface Audio app in Windows 10 で Surface Earbuds をペアにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="84742-284">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="84742-285">Windows 10 で Surface Audio アプリの使用を開始する手順はこちらから入手できます。</span><span class="sxs-lookup"><span data-stu-id="84742-285">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="84742-286">詳細情報</span><span class="sxs-lookup"><span data-stu-id="84742-286">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="word"></a><span data-ttu-id="84742-287">Word</span><span class="sxs-lookup"><span data-stu-id="84742-287">Word</span></span>

- <span data-ttu-id="84742-288">**自動適用または推奨される機密ラベル:** Office では、検出された機密コンテンツに基づいて機密ラベルを推奨または自動適用できます。</span><span class="sxs-lookup"><span data-stu-id="84742-288">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="84742-291">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="84742-291">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="84742-292">Excel</span><span class="sxs-lookup"><span data-stu-id="84742-292">Excel</span></span>
- <span data-ttu-id="84742-293">マージされた列を削除したユーザーのパフォーマンスが向上する原因となった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-293">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>
- <div><span data-ttu-id="84742-294">使用可能なプリンターの一覧にプリンター名が複製される原因となった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-294">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="84742-295">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="84742-295">PowerPoint</span></span>
- <span data-ttu-id="84742-296">英語 (QWERTZ) キーボードを使用しているときに、キーボードショートカットとスペルチェックが期待どおりに機能しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-296">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

### <a name="word"></a><span data-ttu-id="84742-297">Word</span><span class="sxs-lookup"><span data-stu-id="84742-297">Word</span></span>
- <span data-ttu-id="84742-298">空白のドキュメントに新しいコメントを追加しても何も実行されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-298">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>
- <span data-ttu-id="84742-299">ドキュメントに100個を超えるエントリが含まれているインデックスを挿入または更新すると、アプリケーションがクラッシュする問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="84742-299">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>
- <span data-ttu-id="84742-300">カスタム xml 値を含むファイルが非常にゆっくり開かれるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-300">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="84742-301">Office スイート</span><span class="sxs-lookup"><span data-stu-id="84742-301">Office Suite</span></span>
- <span data-ttu-id="84742-302">Microsoft Office の Visual Basic for Applications では、ライブラリ名またはライブラリパスで DBCS 文字を含むコードライブラリへの参照が含まれている特定の VBA プロジェクトでは、読み込み時に Office アプリケーションが破損していると考えられるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-302">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-may-08"></a><span data-ttu-id="84742-305">バージョン 2006:08 年5月08</span><span class="sxs-lookup"><span data-stu-id="84742-305">Version 2006: May 08</span></span>
<span data-ttu-id="84742-306">*バージョン 2006 (ビルド 12829.20000)*</span><span class="sxs-lookup"><span data-stu-id="84742-306">*Version 2006 (Build 12829.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="84742-308">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="84742-308">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="84742-309">Excel</span><span class="sxs-lookup"><span data-stu-id="84742-309">Excel</span></span>

- <span data-ttu-id="84742-310">**ストーリーにアニメーション gif を通知します。** Office editor では、アニメーション Gif がサポートされるようになりました。ドキュメントは snazzier しただけです。</span><span class="sxs-lookup"><span data-stu-id="84742-310">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="84742-311">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-311">Outlook</span></span>

- <span data-ttu-id="84742-312">**より良い結果-jiffy では次のようになります。** 検索機能を更新して、これまでよりも賢明で迅速に、かつ信頼できるものにしました。</span><span class="sxs-lookup"><span data-stu-id="84742-312">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="84742-313">詳細情報</span><span class="sxs-lookup"><span data-stu-id="84742-313">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="84742-314">**ストーリーにアニメーション gif を通知します。** Office editor では、アニメーション Gif がサポートされるようになりました。ドキュメントは snazzier しただけです。</span><span class="sxs-lookup"><span data-stu-id="84742-314">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="84742-315">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="84742-315">PowerPoint</span></span>

- <span data-ttu-id="84742-316">**ストーリーにアニメーション gif を通知します。** Office editor では、アニメーション Gif がサポートされるようになりました。ドキュメントは snazzier しただけです。</span><span class="sxs-lookup"><span data-stu-id="84742-316">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span> [<span data-ttu-id="84742-317">詳細情報</span><span class="sxs-lookup"><span data-stu-id="84742-317">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="84742-318">Word</span><span class="sxs-lookup"><span data-stu-id="84742-318">Word</span></span>

- <span data-ttu-id="84742-319">**ストーリーにアニメーション gif を通知します。** Office editor では、アニメーション Gif がサポートされるようになりました。ドキュメントは snazzier しただけです。</span><span class="sxs-lookup"><span data-stu-id="84742-319">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="84742-322">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="84742-322">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="84742-323">Office スイート</span><span class="sxs-lookup"><span data-stu-id="84742-323">Office Suite</span></span>

- <span data-ttu-id="84742-324">OS シャットダウン後に InTune 経由の Office 365 ProPlus 展開が一時停止しているという問題を調査し、解決しました。</span><span class="sxs-lookup"><span data-stu-id="84742-324">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-may-01"></a><span data-ttu-id="84742-326">バージョン 2005: 5 月01</span><span class="sxs-lookup"><span data-stu-id="84742-326">Version 2005: May 01</span></span>
<span data-ttu-id="84742-327">*バージョン 2005 (ビルド 12827.20030)*</span><span class="sxs-lookup"><span data-stu-id="84742-327">*Version 2005 (Build 12827.20030)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="84742-329">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="84742-329">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="84742-330">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-330">Outlook</span></span>

- <span data-ttu-id="84742-331">**メール内の強化**されたリンク:ファイルへのリンクを含めると、そのファイル名が URL に置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="84742-331">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="84742-332">すべての受信者がアクセスできるようにアクセス許可を変更することができます。</span><span class="sxs-lookup"><span data-stu-id="84742-332">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="84742-333">詳細情報</span><span class="sxs-lookup"><span data-stu-id="84742-333">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="84742-336">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="84742-336">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="84742-337">Excel</span><span class="sxs-lookup"><span data-stu-id="84742-337">Excel</span></span>

- <span data-ttu-id="84742-338">グラフデータテーブルで、日付軸の値が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-338">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>
- <span data-ttu-id="84742-339">ページレイアウトまたは改ページプレビューに入った後に改ページを無効にできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-339">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>
- <span data-ttu-id="84742-340">系列データを使用して列の表示/非表示を切り替えると、グラフの線のスタイルが失われるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-340">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>
- <span data-ttu-id="84742-341">フィルター処理されたリストに列を挿入すると、予想よりも長くかかることがあります。</span><span class="sxs-lookup"><span data-stu-id="84742-341">Inserting a column in a filtered list would take longer than expected.</span></span>
- <span data-ttu-id="84742-342">従来の "共有ブック" モードを使用して、ブックの新しいシートに変更を表示しようとすると、クラッシュが発生する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="84742-342">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>
- <span data-ttu-id="84742-343">"負の値を反転する" オプションが有効になっていると、ピボットグラフでユーザー設定の書式設定が保存されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-343">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>
- <span data-ttu-id="84742-344">[負にする] オプションが選択されている場合に、ピボットグラフの1つのデータ要素に対してユーザー設定の書式設定が保存されなかったという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-344">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>
- <span data-ttu-id="84742-345">この変更により、CSV ファイルに ' @ ' 文字がアップロードされると、"@" 文字の後の文字列が数式に変換されるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="84742-345">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>
- <span data-ttu-id="84742-346">SEQUENCE 関数の10進数値が正しく丸められない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-346">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="outlook"></a><span data-ttu-id="84742-347">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-347">Outlook</span></span>

- <span data-ttu-id="84742-348">ユーザーが Outlook デスクトップクライアントでクリックしたときに、切り捨てによって読み込みが失敗するという非常に長い safelinks を発生させた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="84742-348">Addresses an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>
- <span data-ttu-id="84742-349">サーバーとの同期時に、DBCS (2 バイト文字セット) 文字を含む名前を持つ Outlook フォルダーが断続的に非表示になる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="84742-349">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="84742-350">これを行うには、Outlook で IMAP アカウントを構成し、ロケールが日本語に設定されているシステムで実行する必要があります。</span><span class="sxs-lookup"><span data-stu-id="84742-350">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="84742-351">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="84742-351">PowerPoint</span></span>

- <span data-ttu-id="84742-352">ユーザーが投稿せずにコメントを作成し、[コメント] ウィンドウを閉じてから、新しいウィンドウを開いて、複数のスライドに移動した後、ウィンドウを閉じ、最後に元のプレゼンテーションの [コメント] ウィンドウを再度開いた場合、下書きコメントを使用できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-352">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

### <a name="project"></a><span data-ttu-id="84742-353">Project</span><span class="sxs-lookup"><span data-stu-id="84742-353">Project</span></span>

- <span data-ttu-id="84742-354">Project が Project Web App に接続されていて、小数点がコンマであるという問題を修正しました。ラグが追加されると、TaskDependencies Add メソッドが失敗します。</span><span class="sxs-lookup"><span data-stu-id="84742-354">Fixed an issue where if Project is connected to the Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>

### <a name="word"></a><span data-ttu-id="84742-355">Word</span><span class="sxs-lookup"><span data-stu-id="84742-355">Word</span></span>

- <span data-ttu-id="84742-356">グループ作業モードでドキュメントにコメントを挿入すると必ずしも機能しないという問題を修正した。</span><span class="sxs-lookup"><span data-stu-id="84742-356">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>
- <span data-ttu-id="84742-357">この変更により、@ メンションがクリックされた場合に、People card がフラッシュされるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="84742-357">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>
- <span data-ttu-id="84742-358">下書きコメントを含むドキュメントを閉じるときに、下書きコメントを保存せずにドキュメントを閉じる必要がある場合にメッセージを表示するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-358">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="84742-359">プロンプトを取り消した場合は、ドキュメントを開いたままにして閉じます。</span><span class="sxs-lookup"><span data-stu-id="84742-359">Cancelling the prompt would close the document rather than leaving it open.</span></span>
- <span data-ttu-id="84742-360">投稿されたコメントを変換すると、"変換されたテキストの挿入に失敗しました" というエラーが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-360">Fixed an issue where translating a posted comment would result in the error "Inserting translated text failed".</span></span>
- <span data-ttu-id="84742-361">Web 表示/イマーシブリーダーでは、ヒントをクリックすると、表示されていた場合でも、上にスクロールします。</span><span class="sxs-lookup"><span data-stu-id="84742-361">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="84742-362">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="84742-362">This has been fixed.</span></span>
- <span data-ttu-id="84742-363">マクロを含むファイルを新しい名前で保存しようとすると、ユーザーが入力した内容に関係なく、そのファイルを .docx 拡張子とファイル名 WRO0004.docx に保存すると、ドキュメントが使用できなくなりますという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="84742-363">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version-2005-april-24"></a><span data-ttu-id="84742-365">バージョン 2005: 4 月 24 日</span><span class="sxs-lookup"><span data-stu-id="84742-365">Version 2005: April 24</span></span>
<span data-ttu-id="84742-366">*バージョン 2005 (ビルド 12816.20006)*</span><span class="sxs-lookup"><span data-stu-id="84742-366">*Version 2005 (Build 12816.20006)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="84742-368">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="84742-368">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="84742-369">Excel</span><span class="sxs-lookup"><span data-stu-id="84742-369">Excel</span></span>
- <span data-ttu-id="84742-370">この変更により、LINEST 関数が正しい値を返すにもかかわらず (強制的な y 切片のケースの) グラフの近似曲線の R-2 乗値が正しくないという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="84742-370">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>
- <span data-ttu-id="84742-371">この変更により、カスタマイズされたグラフの近似曲線の書式設定が保存されないことがあるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="84742-371">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

### <a name="outlook"></a><span data-ttu-id="84742-372">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-372">Outlook</span></span>
- <span data-ttu-id="84742-373">Office リボンのグループ予定表の [分類] ボタンが無効になっているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="84742-373">Fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="84742-374">グループ フォルダーを実装していないまたは動作させていないエンタープライズ ユーザーに、Outlook で "応答なし" というメッセージが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="84742-374">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="84742-375">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="84742-375">PowerPoint</span></span>
- <span data-ttu-id="84742-376">アスタリスク (\*) 記号の上にポインターを移動しても、最後にドキュメントを更新した人のユーザー名と日付が表示されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="84742-376">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="word"></a><span data-ttu-id="84742-377">Word</span><span class="sxs-lookup"><span data-stu-id="84742-377">Word</span></span>
- <span data-ttu-id="84742-378">[ブックマークの表示] オプションを有効にしても、ブックマークが表示されませんでした。</span><span class="sxs-lookup"><span data-stu-id="84742-378">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="84742-379">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="84742-379">This has been fixed.</span></span>
- <span data-ttu-id="84742-380">この変更により、[値の代わりにフィールド コードを表示する] オプションが有効になっている場合に、ハイパーリンク付きのテキストが表示されないという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="84742-380">This change fixes an issue where text with hyperlinks may not display if the option "Show field codes instead of their values" was enabled.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version-2005-april-17"></a><span data-ttu-id="84742-382">バージョン 2005: 4 月 17 日</span><span class="sxs-lookup"><span data-stu-id="84742-382">Version 2005: April 17</span></span>
<span data-ttu-id="84742-383">*バージョン 2005 (ビルド 12810.20002)*</span><span class="sxs-lookup"><span data-stu-id="84742-383">*Version 2005 (Build 12810.20002)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="84742-385">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="84742-385">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="84742-386">Excel</span><span class="sxs-lookup"><span data-stu-id="84742-386">Excel</span></span>
- <span data-ttu-id="84742-387">グラフと共に使用される [ユーザー設定の誤差範囲] ダイアログでセル参照エディット コントロールのサイズが大きくなります。</span><span class="sxs-lookup"><span data-stu-id="84742-387">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>
- <span data-ttu-id="84742-388">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="84742-388">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>
- <span data-ttu-id="84742-389">印刷時にフォーム コントロールのチェックボックスが拡大縮小されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-389">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>
- <span data-ttu-id="84742-390">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="84742-390">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>
- <span data-ttu-id="84742-391">この変更により、条件付き書式 (CF) 情報が .XLSB ファイルに正常に保存されなかった問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="84742-391">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="84742-392">OneNote</span><span class="sxs-lookup"><span data-stu-id="84742-392">OneNote</span></span>
- <span data-ttu-id="84742-393">改行が垂直タブとして保存されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-393">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="84742-394">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-394">Outlook</span></span>
- <span data-ttu-id="84742-395">ユーザーが個人用連絡先グループを会議の出席者として追加できなくなった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="84742-395">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>
- <span data-ttu-id="84742-396">スケジュール アシスタントで 2 か月以上離れた会議が会議の件名が表示されないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="84742-396">Addresses an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>
- <span data-ttu-id="84742-397">大きな HTML メッセージを転送するとき、ユーザーにメッセージ本文の全体が表示されないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="84742-397">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>
- <span data-ttu-id="84742-398">グループ ポリシーを使用して S/MIME の既定の署名構成を適用する機能が追加された。</span><span class="sxs-lookup"><span data-stu-id="84742-398">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>
- <span data-ttu-id="84742-399">ユーザーのプライマリ メールボックス以外のメールボックスに対して作成された削除ルールが無効になるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="84742-399">Addresses an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>
- <span data-ttu-id="84742-400">暗号化されたメッセージを転送するときに添付ファイルが削除されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="84742-400">Addresses an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

### <a name="project"></a><span data-ttu-id="84742-401">Project</span><span class="sxs-lookup"><span data-stu-id="84742-401">Project</span></span>
- <span data-ttu-id="84742-402">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="84742-402">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>
- <span data-ttu-id="84742-403">SharePoint タスク リストに接続されているプロジェクトのボードの状態フィールドを変更すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-403">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>
- <span data-ttu-id="84742-404">以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-404">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


## <a name="version-2004-april-10"></a><span data-ttu-id="84742-406">バージョン 2004: 4 月 10 日</span><span class="sxs-lookup"><span data-stu-id="84742-406">Version 2004: April 10</span></span>
<span data-ttu-id="84742-407">*バージョン 2004 (ビルド 12730.20024)*</span><span class="sxs-lookup"><span data-stu-id="84742-407">*Version 2004 (Build 12730.20024)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="84742-409">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="84742-409">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="84742-410">Access</span><span class="sxs-lookup"><span data-stu-id="84742-410">Access</span></span>

- <span data-ttu-id="84742-411">**[テーブルの表示] ダイアログ ボックスをバイパスし、作業ウィンドウに直接移動して、テーブルを効率よくリレーションシップやクエリに追加します。:** 4 つのタブをクリックして、名前を複数選択して、テキストで検索し、作業中に開いたままの作業ウィンドウからドラッグして、テーブルやクエリを追加 ます。</span><span class="sxs-lookup"><span data-stu-id="84742-411">**Bypass the Show Table dialog box, go directly to a task pane, and streamline adding tables to relationships and queries.:** Add tables and queries by clicking four tabs, multi-selecting names, searching by text, and dragging from a task pane that stays open while you work.</span></span>

### <a name="excel"></a><span data-ttu-id="84742-412">Excel</span><span class="sxs-lookup"><span data-stu-id="84742-412">Excel</span></span>

- <span data-ttu-id="84742-413">**M365 Premium Content Picker:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="84742-413">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="84742-414">1000 件のロイヤリティフリーのストック画像、アイコン、ステッカーを詳しく見る [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="84742-414">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="84742-415">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-415">Outlook</span></span>

- <span data-ttu-id="84742-416">**M365 Premium Content Picker:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="84742-416">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="84742-417">1000 件のロイヤリティフリーのストック画像、アイコン、ステッカーを詳しく見る [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="84742-417">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="84742-418">**メールの一部として画像を送信するときに、画像を高品質に維持する:** メールの内容の一部として画像を送信するときに、画像の圧縮を制限するための新しい Outlook の設定を使用できます。</span><span class="sxs-lookup"><span data-stu-id="84742-418">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

### <a name="powerpoint"></a><span data-ttu-id="84742-419">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="84742-419">PowerPoint</span></span>

- <span data-ttu-id="84742-420">**M365 Premium Content Picker:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="84742-420">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="84742-421">1000 件のロイヤリティフリーのストック画像、アイコン、ステッカーを詳しく見る [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="84742-421">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="84742-422">**プレゼンテーション中に変更を同期する:** プレゼンテーションがスライド ショー モードであれば、いつでも変更を同期できます。</span><span class="sxs-lookup"><span data-stu-id="84742-422">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="84742-423">Word</span><span class="sxs-lookup"><span data-stu-id="84742-423">Word</span></span>

- <span data-ttu-id="84742-424">**M365 Premium Content Picker:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="84742-424">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="84742-425">1000 件のロイヤリティフリーのストック画像、アイコン、ステッカーを詳しく見る [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="84742-425">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="84742-426">**個人用コピーに注釈を付ける:** 共有ドキュメントの個人用コピーを作成し、自分用の手書きノートを作成します。</span><span class="sxs-lookup"><span data-stu-id="84742-426">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="84742-427">[表示] > [個人用コピーの作成] に移動して開始します。</span><span class="sxs-lookup"><span data-stu-id="84742-427">Go to View > Create a Private Copy to get started.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="84742-430">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="84742-430">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="84742-431">Access</span><span class="sxs-lookup"><span data-stu-id="84742-431">Access</span></span>

- <span data-ttu-id="84742-432">作業ウィンドウのテーブルのサイズ変更と更新に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-432">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

### <a name="excel"></a><span data-ttu-id="84742-433">Excel</span><span class="sxs-lookup"><span data-stu-id="84742-433">Excel</span></span>

- <span data-ttu-id="84742-434">シートのセル範囲を選択すると、1 つのセルが選択されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-434">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="84742-435">X 軸の範囲に合わせてグラフのサイズを小さくすると、Excel が応答を停止する可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-435">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="84742-436">ユーザー定義のグラフ テンプレートを既定として挿入すると、縦棒グラフとして保存されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-436">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="84742-437">基になるデータ セルにタイトルがない場合に、グラフのデータ ラベルが空白として表示されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-437">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="84742-438">R1C1 セルの参照が有効になっている Excel シートが共同編集/共有される場合に、R1C1 モードでユーザー プレゼンス アイコンの上にカーソルを移動すると、アクティブセル参照が表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-438">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="84742-439">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-439">Outlook</span></span>

- <span data-ttu-id="84742-440">メール メッセージからカテゴリが消えることがあるという問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="84742-440">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="84742-441">共有メールボックスに対して、異なるコンピューター上の別のフォルダー階層が代理人に表示されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="84742-441">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="84742-442">ユーザーが組織フォームのプロパティを表示とするときにクラッシュするという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="84742-442">Addresses an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="84742-443">コンピューターのタイムゾーンを変更するときに、一部のリマインダーが発生しないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="84742-443">Addresses an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="84742-444">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="84742-444">PowerPoint</span></span>

- <span data-ttu-id="84742-445">この変更により、PowerPoint または Word に OLE オブジェクトとして埋め込まれたレガシ Excel グラフを表示するとき、グラフ タイトルが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="84742-445">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="84742-446">Excel から PowerPoint にテキストをコピーするときに、書式設定が変更される場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-446">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="84742-447">この変更により、[完全に一致する単語だけを検索する] を使用して特殊文字を検索するときに、想定どおりに動作しない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="84742-447">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="84742-448">Project</span><span class="sxs-lookup"><span data-stu-id="84742-448">Project</span></span>

- <span data-ttu-id="84742-449">実績作業時間の保護設定を有効にしているときに、ユーザーがタイムフェーズの基準作業時間を入力できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="84742-449">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="84742-450">Word</span><span class="sxs-lookup"><span data-stu-id="84742-450">Word</span></span>

- <span data-ttu-id="84742-451">この変更により、ヒントの上にカーソルを移動してもカードが強調表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="84742-451">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="84742-452">この変更により、なげなわ選択ツールを使用するとき、グループ化された図形のテキストが一時的に非表示になる場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="84742-452">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="84742-453">この変更により、PowerPoint または Word に OLE オブジェクトとして埋め込まれたレガシ Excel グラフを表示するとき、グラフ タイトルが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="84742-453">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="84742-454">この変更により、コメントを作成するとき、コメント アンカーが表示されない場合があるという 2 ページ表示の問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="84742-454">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="84742-455">スタイルがリストにリンクされている祖先のスタイルである段落の場合、そのリストの番号が失われる場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-455">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-march-27"></a><span data-ttu-id="84742-457">バージョン 2004: 3 月 27 日</span><span class="sxs-lookup"><span data-stu-id="84742-457">Version 2004: March 27</span></span>
<span data-ttu-id="84742-458">*バージョン 2004 (ビルド 12718.20010)*</span><span class="sxs-lookup"><span data-stu-id="84742-458">*Version 2004 (Build 12718.20010)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="84742-460">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="84742-460">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="84742-461">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-461">Outlook</span></span>

- <span data-ttu-id="84742-462">**メール作成時の @ メンションの候補表示を無効にするオプションが追加されました。** メンション ピッカーが便利どころか迷惑だと感じていますか?</span><span class="sxs-lookup"><span data-stu-id="84742-462">**New option to disable @ mention suggestions when composing mail:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="84742-463">今後は、必要に応じてオフにすることができます。</span><span class="sxs-lookup"><span data-stu-id="84742-463">Now you can turn it off if you prefer.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="84742-466">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="84742-466">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="84742-467">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-467">Outlook</span></span>
- <span data-ttu-id="84742-468">[添付ファイル ​​ツール] に [クラウドに保存] ボタンが表示されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="84742-468">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>
- <span data-ttu-id="84742-469">ユーザーが返信メッセージの所有者アクセス許可を持っていない場合、[インスペクタ] ウィンドウから権限がデジタル管理されたメッセージに返信するときに、ユーザーが署名を追加できないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="84742-469">Addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>
- <span data-ttu-id="84742-470">以前作成した会議に、Web 上の場所から追加の添付ファイルを追加できないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="84742-470">Addresses an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="84742-471">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="84742-471">PowerPoint</span></span>
- <span data-ttu-id="84742-472">この変更により、絵文字を含む PowerPoint ファイルを保存する場合に失敗する可能性があるエラーが修正されます。</span><span class="sxs-lookup"><span data-stu-id="84742-472">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

### <a name="project"></a><span data-ttu-id="84742-473">Project</span><span class="sxs-lookup"><span data-stu-id="84742-473">Project</span></span>
- <span data-ttu-id="84742-474">CustomFieldValueListGetItem が実行され、ユーザー設定フィールドの参照テーブルが存在しない場合、誤って空の参照テーブルが作成される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-474">Fixed an issue where if 'CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

### <a name="word"></a><span data-ttu-id="84742-475">Word</span><span class="sxs-lookup"><span data-stu-id="84742-475">Word</span></span>
- <span data-ttu-id="84742-476">この変更により、 [表示] メニューから複数のページを選択すると、[コメント] ウィンドウが空白で表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="84742-476">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-march-20"></a><span data-ttu-id="84742-478">バージョン 2004: 3 月 20 日</span><span class="sxs-lookup"><span data-stu-id="84742-478">Version 2004: March 20</span></span>
<span data-ttu-id="84742-479">*バージョン 2004 (ビルド 12711.20000)*</span><span class="sxs-lookup"><span data-stu-id="84742-479">*Version 2004 (Build 12711.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="84742-481">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="84742-481">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="84742-482">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-482">Outlook</span></span>

- <span data-ttu-id="84742-483">**予定表デザインの更新:** 昨年、Microsoft ではメール エクスペリエンスを更新しました。今年は予定表のデザインを更新します!</span><span class="sxs-lookup"><span data-stu-id="84742-483">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar's turn to get a facelift!</span></span> <span data-ttu-id="84742-484">更新されていますが使い慣れた製品ですので、経験豊富な Outlook ユーザーとして、すぐに使いこなして生産性を高めることができます。</span><span class="sxs-lookup"><span data-stu-id="84742-484">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

- <span data-ttu-id="84742-485">**グループ内のデータを保護:** グループを作成するときに選択する秘密度ラベルがグループ メール、ドキュメント、チーム サイトに適用されます。</span><span class="sxs-lookup"><span data-stu-id="84742-485">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

### <a name="powerpoint"></a><span data-ttu-id="84742-486">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="84742-486">PowerPoint</span></span>

- <span data-ttu-id="84742-487">**スライド ショーの実行中にスライドを更新する:** プレゼンテーション中に他の作成者が変更したスライドを更新します。</span><span class="sxs-lookup"><span data-stu-id="84742-487">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="84742-490">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="84742-490">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="84742-491">Excel</span><span class="sxs-lookup"><span data-stu-id="84742-491">Excel</span></span>

- <span data-ttu-id="84742-492">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="84742-492">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="84742-493">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-493">Outlook</span></span>

- <span data-ttu-id="84742-494">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="84742-494">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="84742-495">この変更により、下書きメールに対する最新の変更が更新されなかった問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="84742-495">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="84742-496">ファイルを右クリックして [送信] を使用しても機能しなかった問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="84742-496">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="84742-497">ユーザーがアドレス帳の検索パスをカスタマイズしていた場合に、Outlook の名前解決範囲がグローバル アドレス一覧 (GAL) ではなく、カスタマイズしたパスに制限されていた問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="84742-497">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="84742-498">返された一連の検索結果の中で、結果をカテゴリ別に並べ替えると、カテゴリ カラーが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="84742-498">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

### <a name="project"></a><span data-ttu-id="84742-499">Project</span><span class="sxs-lookup"><span data-stu-id="84742-499">Project</span></span>

- <span data-ttu-id="84742-500">ユーザーがスケジュール グループ内の [タスク] リボンにある「無効化」ボタンをクリックしたときに 'ProjectBeforeTaskChange' という Visual Basic Applications (VBA) イベントが発生しなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="84742-500">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the "Inactivate" button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="84742-501">[フォームの種類] ビュー内から先行タスクまたは後続タスクの詳細を設定した場合に、ProjectBeforeTaskChange という Visual Basic Applications (VBA) イベントが変更をキャプチャしないことがありました。</span><span class="sxs-lookup"><span data-stu-id="84742-501">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="84742-502">たとえば、依存関係を削除し、フォームで [OK] をクリックした場合に、イベントが発生しませんでした。</span><span class="sxs-lookup"><span data-stu-id="84742-502">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="84742-503">この動作が修正されました。</span><span class="sxs-lookup"><span data-stu-id="84742-503">This behavior has been fixed.</span></span>

- <span data-ttu-id="84742-504">日付の変更などの変更を加えた後に、終了した作業時間の実績コスト (ACWP) の最新の値が表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="84742-504">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="84742-505">[最近使用した項目 (MRU)] メニューを使用してプロジェクトを開くと、読み取り/書き込みアクセス権を伴ってプロジェクト ファイルが開かれる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="84742-505">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="84742-506">この変更によって、開始日時を指定した (しかし期間を指定しない) 手動タスクを作成した場合に、タイムライン上に間違った時刻が表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="84742-506">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="84742-507">イスラム暦予定表を使用してタイムラインを印刷すると、[印刷] ビューで、1 か月スキップされるか、または重複する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="84742-507">Fixed an issue where printing a timeline using Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="84742-508">この変更により、GDI オブジェクトを使用して Team Planner を操作するときに、GDI オブジェクトの割り当てが過剰になり、メモリ不足状態が発生する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="84742-508">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

### <a name="word"></a><span data-ttu-id="84742-509">Word</span><span class="sxs-lookup"><span data-stu-id="84742-509">Word</span></span>

- <span data-ttu-id="84742-510">コメントを投稿する機能が無効になる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="84742-510">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="84742-511">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="84742-511">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="84742-512">この変更により、アカウント マネージャーがサードパーティのアプリケーションを使用してメッセージを送ろうとすると、ハングしてディスパッチできないという問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="84742-512">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="84742-513">この変更により、文書に記載されていない見出しスタイルで目次が更新されるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="84742-513">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="84742-514">Word 文書をメール送信するときに、文書に保存されていたデジタル署名が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="84742-514">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-march-13"></a><span data-ttu-id="84742-516">バージョン 2004: 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="84742-516">Version 2004: March 13</span></span>
<span data-ttu-id="84742-517">*バージョン 2004 (ビルド 12703.20010)*</span><span class="sxs-lookup"><span data-stu-id="84742-517">*Version 2004 (Build 12703.20010)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="84742-519">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="84742-519">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="84742-520">Excel</span><span class="sxs-lookup"><span data-stu-id="84742-520">Excel</span></span>
- <span data-ttu-id="84742-521">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="84742-521">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="84742-522">詳細情報</span><span class="sxs-lookup"><span data-stu-id="84742-522">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="84742-523">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="84742-523">PowerPoint</span></span>
- <span data-ttu-id="84742-524">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="84742-524">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="84742-525">詳細情報</span><span class="sxs-lookup"><span data-stu-id="84742-525">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="84742-526">Word</span><span class="sxs-lookup"><span data-stu-id="84742-526">Word</span></span>
- <span data-ttu-id="84742-527">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="84742-527">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="84742-528">詳細情報</span><span class="sxs-lookup"><span data-stu-id="84742-528">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="84742-531">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="84742-531">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="84742-532">Access</span><span class="sxs-lookup"><span data-stu-id="84742-532">Access</span></span>
- <span data-ttu-id="84742-533">Access のインターナショナル バージョンにおいて、ユーザー インターフェイスに英語の文字列が表示されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-533">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="84742-534">Excel</span><span class="sxs-lookup"><span data-stu-id="84742-534">Excel</span></span>
- <span data-ttu-id="84742-535">プログラムを使って大きいセル範囲を編集するときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-535">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>
- <span data-ttu-id="84742-536">日本語の環境で CSV ファイルを開くときに発生するパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-536">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

### <a name="outlook"></a><span data-ttu-id="84742-537">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-537">Outlook</span></span>
- <span data-ttu-id="84742-538">(メニューからではなく) ドラッグ アンド ドロップでメールに添付ファイルを追加したり、メールから添付ファイルを保存したりすると、ファイルの「最終更新日」が更新される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="84742-538">Addresses an issue that caused the "Last Modified"; date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>
- <span data-ttu-id="84742-539">展開された [検索] ウィンドウで Enter キーを押しても検索が開始されず、代わりにユーザーが [検索] ボタンをクリックしなければならないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="84742-539">Addresses an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>
- <span data-ttu-id="84742-540">[利用可能な場合はユーザーの写真を表示する] オプションがオフになっている場合、検索結果にユーザーに関する情報が表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-540">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>

### <a name="project"></a><span data-ttu-id="84742-541">Project</span><span class="sxs-lookup"><span data-stu-id="84742-541">Project</span></span>
- <span data-ttu-id="84742-542">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-542">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>
- <span data-ttu-id="84742-543">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-543">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="84742-544">Word</span><span class="sxs-lookup"><span data-stu-id="84742-544">Word</span></span>
- <span data-ttu-id="84742-545">コメントを入力または編集し、Ctrl キーを押しながら A キーを押したときに、コメント カード内のテキストが選択されるのではなく、キャンバスのテキストが選択されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-545">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>
- <span data-ttu-id="84742-546">クイック印刷を使用して印刷した後に編集しようとしたときに、ドキュメント内の単語の配置が乱れてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-546">We fixed an issue in which the alignment of words in a document gets scrambled when tried to edit after printing using Quick Print.</span></span>
- <span data-ttu-id="84742-547">2 つのドキュメントを 1 つのドキュメントに結合するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-547">We fixed an issue when merging two documents into one document.</span></span>
- <span data-ttu-id="84742-548">数式を含む変更履歴をマークすると、ファイルを保存するときにエラーが発生するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-548">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-06"></a><span data-ttu-id="84742-550">バージョン 2003: 3 月 6 日</span><span class="sxs-lookup"><span data-stu-id="84742-550">Version 2003: March 06</span></span>
<span data-ttu-id="84742-551">*バージョン 2003 (ビルド 12624.20086)*</span><span class="sxs-lookup"><span data-stu-id="84742-551">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="84742-553">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="84742-553">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="84742-554">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-554">Outlook</span></span>

- <span data-ttu-id="84742-555">Outlook Web Access を使用してルールを作成しても Exchange サーバーに保存されず競合が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-555">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="84742-556">ダーク モードの Outlook の [差出人] フィールドにドロップダウン リストが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-556">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="84742-557">ファイルが別のアプリケーションで開かれているときに、ユーザーがエクスプローラーでファイルをメール メッセージに添付できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-557">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="84742-558">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="84742-558">PowerPoint</span></span>

- <span data-ttu-id="84742-559">サムネイルの上にマウスポインターを置くと推奨されるサムネイルが点滅する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-559">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="84742-560">場合によっては、これにより PowerPoint がクラッシュしてしまう可能性があります。</span><span class="sxs-lookup"><span data-stu-id="84742-560">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="84742-561">Word</span><span class="sxs-lookup"><span data-stu-id="84742-561">Word</span></span>

- <span data-ttu-id="84742-562">編集用に保護されたドキュメントの比較機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-562">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="84742-563">Office スイート</span><span class="sxs-lookup"><span data-stu-id="84742-563">Office Suite</span></span>

- <span data-ttu-id="84742-564">ユーザー プリンシパル名 (UPN) の大文字と小文字が区別されなくなり、SharePoint でファイルを操作するときにはエラーが少なくなるという Word/Excel/PowerPoint の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-564">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="84742-565">機能に影響はないものの、[ファイル]、[オプション] の順で進んだ後のダイアログの [OK] ボタンが灰色で表示されていた外観上の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-565">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

## <a name="version-2003-february-28"></a><span data-ttu-id="84742-568">バージョン 2003: 2 月 28 日</span><span class="sxs-lookup"><span data-stu-id="84742-568">Version 2003: February 28</span></span>
<span data-ttu-id="84742-569">*バージョン 2003 (ビルド 12619.20002)*</span><span class="sxs-lookup"><span data-stu-id="84742-569">*Version 2003 (Build 12619.20002)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="84742-571">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="84742-571">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="84742-572">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-572">Outlook</span></span>

- <span data-ttu-id="84742-573">**IT 管理者向けのインシデント通知:** Microsoft 365 テナントのグローバル管理者および Office Apps 管理者は、Outlook for Windows の新しい右側のパネル通知により、ユーザーに影響する Outlook および O365 Exchange インシデントについて通知されます。</span><span class="sxs-lookup"><span data-stu-id="84742-573">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="84742-574">詳細情報</span><span class="sxs-lookup"><span data-stu-id="84742-574">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

### <a name="powerpoint"></a><span data-ttu-id="84742-575">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="84742-575">PowerPoint</span></span>

- <span data-ttu-id="84742-576">\*\*インクを図形に変換する作図エクスペリエンスの向上: \*\*より良い図を描いて変換し、Office オブジェクトを操作できるようにします。[詳細情報](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="84742-576">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="84742-579">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="84742-579">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="84742-580">Excel</span><span class="sxs-lookup"><span data-stu-id="84742-580">Excel</span></span>

- <span data-ttu-id="84742-581">[印刷プレビュー] でスライサーのテキストが適切に拡大または縮小されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-581">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="84742-582">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-582">Outlook</span></span>

- <span data-ttu-id="84742-583">(メニューからではなく) ドラッグ アンド ドロップでメールに添付ファイルを追加したり、メールから添付ファイルを保存したりすると、ファイルの「最終更新日」が更新される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="84742-583">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="84742-584">Word</span><span class="sxs-lookup"><span data-stu-id="84742-584">Word</span></span>

- <span data-ttu-id="84742-585">コメント カードでタブすると、コメント編集ボックスにフォーカスが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-585">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="84742-586">コントロール (テキスト コンテンツ コントロールなど) を数式に挿入し、ファイルを保存して開くと、読み取り不可能なコンテンツ エラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="84742-586">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="84742-587">以前にパスワードで保護されたファイルをクラウド ストレージに保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-587">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="84742-588">Office スイート</span><span class="sxs-lookup"><span data-stu-id="84742-588">Office Suite</span></span>

- <span data-ttu-id="84742-589">同じ SharePoint ライブラリから Word/Excel/PowerPoint で複数のドキュメントが開かれている場合、最初に開いたドキュメントのみがポリシー コンプライアンスでスキャンされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-589">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-february-21"></a><span data-ttu-id="84742-591">バージョン 2003: 2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="84742-591">Version 2003: February 21</span></span>
<span data-ttu-id="84742-592">*バージョン 2003 (ビルド 12615.20000)*</span><span class="sxs-lookup"><span data-stu-id="84742-592">*Version 2003 (Build 12615.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="84742-594">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="84742-594">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="84742-595">Office スイート</span><span class="sxs-lookup"><span data-stu-id="84742-595">Office Suite</span></span>

- <span data-ttu-id="84742-596">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキスト ハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="84742-596">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="84742-599">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="84742-599">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="84742-600">Excel</span><span class="sxs-lookup"><span data-stu-id="84742-600">Excel</span></span>
- <span data-ttu-id="84742-601">ピボット テーブルのメジャーの名前を変更するときにユーザーが経験する可能性のある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-601">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="84742-602">VBA マクロを使用して範囲の内容をクリアするときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-602">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="84742-603">ユーザーがリボンを操作するマクロを実行したときに UI が点滅する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-603">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="84742-604">ファイルの最初の単語が TABLE である場合に CSV ファイルが誤ってロードされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-604">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="84742-605">ズーム レベルが異なる 2 つのブックを切り替える際にユーザーがクラッシュを経験する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-605">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="84742-606">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-606">Outlook</span></span>
- <span data-ttu-id="84742-607">Outlook を夜間に実行したままにしておくと、ユーザーがパブリック フォルダー メッセージを開けなくなる問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="84742-607">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="84742-608">Gmail アカウントを追加する認証ワークフロー中に、[アクセス許可] ページの [許可] および [拒否] ボタンが無効になる競合状態を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-608">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="84742-609">一部のシナリオで、ログがオフになっている場合でも Outlook が予期せずログ出力を生成する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="84742-609">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="84742-610">Word</span><span class="sxs-lookup"><span data-stu-id="84742-610">Word</span></span>
- <span data-ttu-id="84742-611">マウス ポインターをコメント カードの上に置いたときに、コメント カードが常に強調表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-611">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="84742-612">アクティブなドキュメントの共同編集セッション中に、画像をコメント カードに直接追加すると、タグが追加されている場合があります。</span><span class="sxs-lookup"><span data-stu-id="84742-612">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="84742-613">この問題は修正されています。</span><span class="sxs-lookup"><span data-stu-id="84742-613">This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="84742-614">Office スイート</span><span class="sxs-lookup"><span data-stu-id="84742-614">Office Suite</span></span>
- <span data-ttu-id="84742-615">Word/Excel/PowerPoint ドキュメントで Multichoice/Lookup/Managed-metadata プロパティを使用し、SharePoint ドキュメント ライブラリに保存する場合、これらのプロパティは以前は 255 文字に制限されていました。</span><span class="sxs-lookup"><span data-stu-id="84742-615">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="84742-616">これらのプロパティが 255 文字を超えると、そういったドキュメントは保存することができませんでした。</span><span class="sxs-lookup"><span data-stu-id="84742-616">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="84742-617">この変更により、この制限は 2048 文字に増加しました。</span><span class="sxs-lookup"><span data-stu-id="84742-617">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-february-14"></a><span data-ttu-id="84742-619">バージョン 2003: 2 月 14 日</span><span class="sxs-lookup"><span data-stu-id="84742-619">Version 2003: February 14</span></span>
<span data-ttu-id="84742-620">*バージョン 2003 (ビルド 12607.20000)*</span><span class="sxs-lookup"><span data-stu-id="84742-620">*Version 2003 (Build 12607.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="84742-622">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="84742-622">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="84742-623">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-623">Outlook</span></span>

- <span data-ttu-id="84742-624">**キャプティブ WiFi ネットワークの新しいエクスペリエンス**: サインインに Web ページを必要とする WiFi ネットワークに参加したことはありませんか ?</span><span class="sxs-lookup"><span data-stu-id="84742-624">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="84742-625">Outlook はこれを検出し、接続を支援します。</span><span class="sxs-lookup"><span data-stu-id="84742-625">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="84742-626">Word</span><span class="sxs-lookup"><span data-stu-id="84742-626">Word</span></span>

- <span data-ttu-id="84742-627">**描画ツールボックスでインク エディターを見つける**: [描画] を選択し、[インク エディター] ペンを選択して、指またはデジタル ペンでドキュメントを編集します。</span><span class="sxs-lookup"><span data-stu-id="84742-627">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="84742-628">詳細情報</span><span class="sxs-lookup"><span data-stu-id="84742-628">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="84742-629">Office スイート</span><span class="sxs-lookup"><span data-stu-id="84742-629">Office Suite</span></span>

- <span data-ttu-id="84742-630">**明瞭になったステータス バー アイコン:** ステータス バーのアイコンが見やすくなりました</span><span class="sxs-lookup"><span data-stu-id="84742-630">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="84742-633">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="84742-633">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="84742-634">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-634">Outlook</span></span>

- <span data-ttu-id="84742-635">ユーザーが「空き時間情報オプション」予定表のアクセス許可ダイアログにアクセスできなくなる問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="84742-635">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="84742-636">異なるタイム ゾーンから送信された定期的な会議インスタンスを開くときに「申し訳ございません、このアイテムを開くことができません」というアラートが発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-636">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="84742-637">メッセージから添付ファイルをドラッグ アンド ドロップした後、ユーザーが .msg ファイルを再度開くことができない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="84742-637">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="84742-638">Outlook から OneDrive に添付ファイルをアップロードした後、添付ファイルの名前にかっこが含まれているとファイル名が変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-638">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="84742-639">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="84742-639">PowerPoint</span></span>

- <span data-ttu-id="84742-640">Excel グラフを含む PowerPoint または Word でドキュメントを保存できないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-640">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="84742-641">Word</span><span class="sxs-lookup"><span data-stu-id="84742-641">Word</span></span>

- <span data-ttu-id="84742-642">ドキュメントを PDF にエクスポートすると、画像の透明性が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-642">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-february-07"></a><span data-ttu-id="84742-644">バージョン 2002: 2 月 7 日</span><span class="sxs-lookup"><span data-stu-id="84742-644">Version 2002: February 07</span></span>
<span data-ttu-id="84742-645">*バージョン 2002 (ビルド 12527.20040)*</span><span class="sxs-lookup"><span data-stu-id="84742-645">*Version 2002 (Build 12527.20040)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="84742-647">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="84742-647">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="84742-648">Access</span><span class="sxs-lookup"><span data-stu-id="84742-648">Access</span></span>

- <span data-ttu-id="84742-649">**クエリ デザイナー、SQL ビュー、およびリレーションシップ ウィンドウでの作業効率の向上:** テーブルを右クリックして、テーブルを開き、デザインし、サイズを変更し、非表示にします。</span><span class="sxs-lookup"><span data-stu-id="84742-649">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="84742-650">SQL ビューでテキストを検索および置換します。</span><span class="sxs-lookup"><span data-stu-id="84742-650">Search and replace text in SQL View.</span></span> <span data-ttu-id="84742-651">リレーションシップ ウィンドウ内の複数のテーブルを選択します。</span><span class="sxs-lookup"><span data-stu-id="84742-651">Select multiple tables in the Relationships window.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="84742-654">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="84742-654">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="84742-655">Access</span><span class="sxs-lookup"><span data-stu-id="84742-655">Access</span></span>

- <span data-ttu-id="84742-656">この更新プログラムでは、ADODB を使用する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="84742-656">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="84742-657">VB コードのレコーダー オブジェクトがエラーを誤って報告することがあります。</span><span class="sxs-lookup"><span data-stu-id="84742-657">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="84742-658">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="84742-658">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="84742-659">Excel</span><span class="sxs-lookup"><span data-stu-id="84742-659">Excel</span></span>

- <span data-ttu-id="84742-660">動的配列で [区切り位置] を使用すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-660">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="84742-661">Outlook</span><span class="sxs-lookup"><span data-stu-id="84742-661">Outlook</span></span>

- <span data-ttu-id="84742-662">月ビューで予定表をスクロールしても以前の予定表のイベントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-662">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="84742-663">Citrix 環境で 30 件を超える予定表を表示したときにクラッシュする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="84742-663">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="84742-664">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="84742-664">PowerPoint</span></span>

- <span data-ttu-id="84742-665">ファイルを閉じた後、実行中のイベント ハンドラーがある場合、PowerPoint がファイルを Presentations コレクションからすぐに削除しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-665">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="84742-666">したがって、オブジェクト モデルによって報告される開いているプレゼンテーションの数は正しくなく、PowerPoint のシャットダウンは防止されます。</span><span class="sxs-lookup"><span data-stu-id="84742-666">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="84742-667">蛍光ペンの問題を修正しました。暗い蛍光ペン色の白いテキストはグレースケールで黒として印刷されます。</span><span class="sxs-lookup"><span data-stu-id="84742-667">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="84742-668">Word</span><span class="sxs-lookup"><span data-stu-id="84742-668">Word</span></span>

- <span data-ttu-id="84742-669">目次を更新してスクロールすると、ドキュメント上に灰色の領域が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="84742-669">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="84742-670">ドキュメントが共同編集されている場合、ルート コメントのドラフト バージョンが保持されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-670">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="84742-671">コメント カード間を行き来すると、最初に選択されたコメントが選択の強調表示で表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-671">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="84742-672">コメントが書き込まれたが投稿されず、ユーザーがファイルを保存しようとした場合、「参照」を使用してファイルを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-672">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="84742-673">SlideTrack を有効にしてコメント ウィンドウを閉じると、Ctrl + Alt + M でコメント ウィンドウが開かない場合があります。</span><span class="sxs-lookup"><span data-stu-id="84742-673">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="84742-674">@メンションをテーブルに追加すると、「このドキュメントのテーブルが破損しました」というエラー メッセージが生成される場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="84742-674">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="84742-675">Office スイート</span><span class="sxs-lookup"><span data-stu-id="84742-675">Office Suite</span></span>

- <span data-ttu-id="84742-676">Norway Nynorsk (nn-no) 校正ツール パッケージが正しくインストールされなかった場合がある問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="84742-676">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (バグの詳細コンテンツ エンドを削除しないでください)
