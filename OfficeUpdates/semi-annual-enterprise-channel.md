---
title: 2020 年の半期エンタープライズ チャネル リリースのリリース ノート
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Microsoft 365 Apps 用の 2020 年の半期チャネル リリースのリリース ノートを IT 担当者に提供します
ms.openlocfilehash: 6b50195e2e84292b0b4b1e259254592f2c4a591b
ms.sourcegitcommit: 568fdf9ae96367ef3a4f601128df80944dd265a7
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/10/2021
ms.locfileid: "50173656"
---
# <a name="release-notes-for-semi-annual-enterprise-channel"></a><span data-ttu-id="ffbd9-103">半期エンタープライズ チャネルのリリース ノート</span><span class="sxs-lookup"><span data-stu-id="ffbd9-103">Release notes for Semi-Annual Enterprise Channel</span></span>

<span data-ttu-id="ffbd9-104">このリリース ノートには、半期エンタープライズ チャネルの更新プログラムに含まれる新機能と、セキュリティ以外の更新プログラムに関する情報が記載されています。対象となるのは、Microsoft 365 Apps for enterprise、Microsoft 365 Apps for business、および Project と Visio のデスクトップ アプリのサブスクリプション版です。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="ffbd9-105">現在、Microsoft 365 Apps の更新プログラム チャネルに、新しい更新プログラム チャネル (月次エンタープライズ チャネル) の追加や既存の更新プログラム チャネル名の変更など、いくつかの変更を進めています。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="ffbd9-106">詳細については、[こちらの記事](https://go.microsoft.com/fwlink/p/?linkid=2127441)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
>
>- <span data-ttu-id="ffbd9-107">半期エンタープライズ チャネルのユーザーが Office ポータルから Microsoft 365 Apps をダウンロードして Windows 10 にインストールすると、既定で OneNote 2016 が含まれるようになります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-107">OneNote 2016 will now be included by default when a user on the Semi-Annual Enterprise Channel downloads and installs Microsoft 365 Apps on Windows 10 from the Office Portal.</span></span>


[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2008-february-09"></a><span data-ttu-id="ffbd9-109">バージョン 2008: 2 月 9 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-109">Version 2008: February 09</span></span>
<span data-ttu-id="ffbd9-110">*バージョン 2008 (ビルド 13127.21216)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-110">*Version 2008 (Build 13127.21216)*</span></span>

<span data-ttu-id="ffbd9-111">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-111">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-113">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-113">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ffbd9-114">Excel</span><span class="sxs-lookup"><span data-stu-id="ffbd9-114">Excel</span></span>

- <span data-ttu-id="ffbd9-115">無効なファイル属性 (作成時刻、修正時刻など) を持つ UNC ファイルを開くと、Excel が予期せず終了してしまう可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-115">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="ffbd9-116">Excel からグラフをコピーして Word または PowerPoint に貼り付けるときに、10 進数と桁区切りの記号の設定を継承しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-116">We fixed an issue where decimal and thousands separators settings would not carry over when copying a chart from Excel and pasting into Word or PowerPoint.</span></span>


- <span data-ttu-id="ffbd9-117">毎回マクロが実行されているとピボットテーブルの範囲の形式を含むマクロを実行するパフォーマンスが悪化する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-117">We fixed an issue where the performance of running a macro involving PivotTable range formatting would get worse each time the macro is run.</span></span>


- <span data-ttu-id="ffbd9-118">シートを別のブックにコピーまたは移動する場合に条件付き書式のルールが破棄される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-118">We fixed an issue where conditional formatting rules were dropped when copying or moving sheets to another workbook.</span></span>


- <span data-ttu-id="ffbd9-119">アプリのスタート画面のブートが無効の場合にユーザーが秘密度ラベルを Excel ファイルに適用できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-119">We fixed an issue where users were unable to apply sensitivity labels to Excel files when the start screen on app boot was disabled.</span></span>


- <span data-ttu-id="ffbd9-120">OneDrive 同期フォルダーからクラウド ファイルを開く場合の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-120">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="ffbd9-121">Outlook</span><span class="sxs-lookup"><span data-stu-id="ffbd9-121">Outlook</span></span>

- <span data-ttu-id="ffbd9-122">添付ファイルを追加または保存するときに Outlook が散発的に機能しなくなる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-122">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ffbd9-123">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ffbd9-123">PowerPoint</span></span>

- <span data-ttu-id="ffbd9-124">QAT で [フォントサイズ] コマンドが追加されたのに、更新すると最近定義されたフォント サイズにオート コンプリートするという問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-124">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="ffbd9-125">‘ ソースの形式を保持する ’ オプションを使用してスライドのコピーまたは貼り付けを行う場合に予期せず新しいスライド マスターを上書きすることがある問題は修正されました</span><span class="sxs-lookup"><span data-stu-id="ffbd9-125">Fixed an issue where copy and paste of a slide with 'keep source formatting' option would sometimes copy over a new slide master unexpectedly</span></span>


### <a name="word"></a><span data-ttu-id="ffbd9-126">Word</span><span class="sxs-lookup"><span data-stu-id="ffbd9-126">Word</span></span>

- <span data-ttu-id="ffbd9-127">Word 文書を開くと、エラー ダイアログが表示されることがある変更履歴の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-127">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="ffbd9-128">OneDrive 同期フォルダーからクラウド ファイルを開く場合の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-128">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ffbd9-129">Office スイート</span><span class="sxs-lookup"><span data-stu-id="ffbd9-129">Office Suite</span></span>

- <span data-ttu-id="ffbd9-130">Office で正常にファイルを開けなくなる問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-130">Fixed an issue that prevented successful open of a file in Office.</span></span>


- <span data-ttu-id="ffbd9-131">書式のコピー/貼り付けを介してコネクタに適用されたスケッチ アウトラインを含むドキュメントが壊れる可能性がある問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-131">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-february-09"></a><span data-ttu-id="ffbd9-133">バージョン 2002: 2 月 9 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-133">Version 2002: February 09</span></span>
<span data-ttu-id="ffbd9-134">*バージョン 2002 (ビルド 12527.21594)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-134">*Version 2002 (Build 12527.21594)*</span></span>

<span data-ttu-id="ffbd9-135">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-135">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-137">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-137">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="ffbd9-138">Office スイート</span><span class="sxs-lookup"><span data-stu-id="ffbd9-138">Office Suite</span></span>

- <span data-ttu-id="ffbd9-139">書式のコピー/貼り付けを介してコネクタに適用されたスケッチ アウトラインを含むドキュメントが壊れる可能性がある問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-139">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-february-09"></a><span data-ttu-id="ffbd9-141">バージョン 1908: 2 月 9 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-141">Version 1908: February 09</span></span>
<span data-ttu-id="ffbd9-142">*バージョン 1908 (ビルド 11929.21008)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-142">*Version 1908 (Build 11929.21008)*</span></span>

<span data-ttu-id="ffbd9-143">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-143">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2008-january-12"></a><span data-ttu-id="ffbd9-144">バージョン 2008: 1 月 12 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-144">Version 2008: January 12</span></span>
<span data-ttu-id="ffbd9-145">*バージョン 2008 (ビルド 13127.21064)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-145">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="ffbd9-146">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-146">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="ffbd9-148">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="ffbd9-148">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="ffbd9-149">Access</span><span class="sxs-lookup"><span data-stu-id="ffbd9-149">Access</span></span>

- <span data-ttu-id="ffbd9-150">**クエリ デザイナー、SQL ビュー、およびリレーションシップ ウィンドウでの作業効率の向上:** テーブルを右クリックして、テーブルを開き、デザインし、サイズを変更し、非表示にします。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-150">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="ffbd9-151">SQL ビューでテキストを検索および置換します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-151">Search and replace text in SQL View.</span></span> <span data-ttu-id="ffbd9-152">リレーションシップ ウィンドウ内の複数のテーブルを選択します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-152">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="ffbd9-153">**数回クリックするだけで表を追加する:** [テーブルの追加] 作業ウィンドウを使用すると、作業中も開いたまま、リレーションシップやクエリにテーブルを追加できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-153">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="ffbd9-154">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-154">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="ffbd9-155">Excel</span><span class="sxs-lookup"><span data-stu-id="ffbd9-155">Excel</span></span>

- <span data-ttu-id="ffbd9-156">**お気に入りの Excel 関数が速くなりました：** SUMIFS、AVERAGEIFS、COUNTIFS、MAXIFS、および MINIFS 関数がこれまでよりもはるかに高速になりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-156">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="ffbd9-157">もっと素早く一番下に移動します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-157">Get to the bottom line more quickly.</span></span> <span data-ttu-id="ffbd9-158">今すぐお試しください。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-158">Try one now.</span></span>

- <span data-ttu-id="ffbd9-159">**Realtimedata (RTD) の改善:** Office 365 バージョン 2002 の月間チャネル以降、ExcelのRealTimeData (RTD) 関数は、Excel 2010 のスプレッドシートのデータ計算よりもはるかに高速になります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-159">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="ffbd9-160">基盤となるメモリとデータ構造のボトルネックを取り除き、マルチスレッド再計算  (MTR) の使用可能なすべてのスレッドで計算できるようにスレッドセーフにしました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-160">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

- <span data-ttu-id="ffbd9-161">**改善されたマップ グラフ:** マップ グラフを Excel の地理のデータの種類と統合することにより、マップ グラフを改善しました。これにより、マップされた場所に関する豊富な情報を明らかにすることができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-161">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="ffbd9-162">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-162">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="ffbd9-163">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-163">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="ffbd9-164">[ブログの投稿](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-164">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="ffbd9-165">**Excel で Power BI のデータセットからピボットテーブルを作成する:** Power BI に保存されているデータセットに接続されている Excel のピボットテーブルを数回のクリックで作成できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-165">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="ffbd9-166">これにより、ピボットテーブルと Power BI の両方を最大限に活用できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-166">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="ffbd9-167">セキュリティで保護された Power BI データセットからピボットテーブルを使って、データの計算、集計、分析を行います。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-167">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="ffbd9-168">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-168">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="ffbd9-169">[ブログの投稿](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-169">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="ffbd9-170">Outlook</span><span class="sxs-lookup"><span data-stu-id="ffbd9-170">Outlook</span></span>

- <span data-ttu-id="ffbd9-171">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-171">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="ffbd9-172">[ブログの投稿](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-172">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="ffbd9-173">**予定表が一新されます:** 予定表を簡単に読みやすくなるビジュアル アップデートをご覧ください。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-173">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="ffbd9-174">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-174">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="ffbd9-175">[ブログの投稿](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-175">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="ffbd9-176">**より高速化した共有カレンダーの更新**: Office 365 の共有カレンダーの場合、Outlook では REST API を使用してこれらのカレンダーを更新します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-176">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="ffbd9-177">共有カレンダーのより高速で信頼性の高い更新を行うには、プレビューを有効にします。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-177">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="ffbd9-178">**所有しているグループにメールをドラッグ:** メッセージや会話を受信トレイからドラッグして移動し、コピーします。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-178">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="ffbd9-179">ドラッグしたメッセージは、すべてのグループ メンバーと共有されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-179">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="ffbd9-180">[ブログの投稿](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-180">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="ffbd9-181">**受信トレイを離れずに会議に参加する:** オンライン会議に参加するために、予定表に切り替える必要はありません。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-181">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="ffbd9-182">[To Do] ウィンドウに固定された予定表を使用して、ワンクリックで任意の会議に参加します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-182">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span> [<span data-ttu-id="ffbd9-183">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-183">Learn more</span></span>](https://support.office.com/article/d8baa9d5-0645-41b8-9f36-b498a6c36064 )

- <span data-ttu-id="ffbd9-184">**キャプティブ WiFi ネットワークの新しいエクスペリエンス**: サインインに Web ページを必要とする WiFi ネットワークに参加したことはありませんか ?</span><span class="sxs-lookup"><span data-stu-id="ffbd9-184">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="ffbd9-185">Outlook はこれを検出し、接続を支援します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-185">Outlook now detects this and helps you get connected.</span></span><br /><span data-ttu-id="ffbd9-186">[ブログの投稿](https://insider.office.com/ja-JP/blog/outlook-on-public-wi-fi-networks-just-got-easier)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-186">See details in [blog post](https://insider.office.com/ja-JP/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span></span>

- <span data-ttu-id="ffbd9-187">**人物を検索するときにメールの候補を取得する:** [検索] ボックスに人の名前を入力すると、最も関連性の高いメール メッセージが検索候補に含まれます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-187">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="ffbd9-188">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-188">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

- <span data-ttu-id="ffbd9-189">**より迅速かつ適切な結果:** 検索機能が更新され、よりスマート、迅速、かつ信頼性が高くなりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-189">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="ffbd9-190">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-190">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

### <a name="powerpoint"></a><span data-ttu-id="ffbd9-191">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ffbd9-191">PowerPoint</span></span>

- <span data-ttu-id="ffbd9-192">**簡単な GIF:** 1 つのスライド、1 つのフレーム。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-192">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="ffbd9-193">PowerPoint でループ GIF を簡単に作成できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-193">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="ffbd9-194">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-194">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="ffbd9-195">[ブログの投稿](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-195">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="ffbd9-196">**スライドへのリンク:** 同僚にスライド デッキへの投稿を依頼し、ヘルプが必要なスライド上で直接開始します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-196">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span> [<span data-ttu-id="ffbd9-197">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-197">Learn more</span></span>](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br /><span data-ttu-id="ffbd9-198">[ブログの投稿](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-198">See details in [blog post](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span></span>

- <span data-ttu-id="ffbd9-199">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-199">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="ffbd9-200">[ブログの投稿](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-200">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="ffbd9-201">**改善されたマップ グラフ:** マップ グラフを Excel の地理のデータの種類と統合することにより、マップ グラフを改善しました。これにより、マップされた場所に関する豊富な情報を明らかにすることができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-201">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="ffbd9-202">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-202">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="ffbd9-203">**図の向上: コネクタが改善されており、インクの滑らかな変換のプロセスが** によって、アイデアをより自信のあるインクにすることができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-203">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="ffbd9-204">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-204">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="ffbd9-205">**PowerPoint でのストリーム ビデオのパフォーマンス向上:**、ビデオの読み込み時間を最小限に抑え、快適な表示を実現するために Microsoft Stream ビデオの再生パフォーマンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-205">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="ffbd9-206">お客様の社内ビデオを使用して、Microsoft Stream でより適切なプレゼンテーションを作成します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-206">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

- <span data-ttu-id="ffbd9-207">**\@メンションを使用してユーザーの注意を引く:** コメントで @メンションを使うと、仕事仲間による入力が必要な場合にそのユーザーに知らせることができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-207">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="ffbd9-208">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-208">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="ffbd9-209">**プレゼンテーション中に変更を同期する:** プレゼンテーションがスライド ショー モードであっても、いつでも変更を同期できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-209">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="ffbd9-210">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-210">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="ffbd9-211">[ブログの投稿](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-211">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="ffbd9-212">**コメント:** PowerPoint の新しいコメント機能により、ドキュメントにコメントをすばやく簡単に見つけて追加できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-212">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="ffbd9-213">コメントの固定、解決、タスク、改善された通知などの新機能を使用して、コラボレーションワークフローを最新のものにします。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-213">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span> [<span data-ttu-id="ffbd9-214">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-214">Learn more</span></span>](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

### <a name="word"></a><span data-ttu-id="ffbd9-215">Word</span><span class="sxs-lookup"><span data-stu-id="ffbd9-215">Word</span></span>

- <span data-ttu-id="ffbd9-216">**インクのなげなわ:** [描画] タブのなげなわツールを使用すると、インクで描かれたオブジェクトを選択できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-216">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="ffbd9-217">個別のストロークまたは文字全体を選択できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-217">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="ffbd9-218">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-218">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="ffbd9-219">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-219">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="ffbd9-220">[ブログの投稿](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-220">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="ffbd9-221">**改善されたマップ グラフ:** マップ グラフを Excel の地理のデータの種類と統合することにより、マップ グラフを改善しました。これにより、マップされた場所に関する豊富な情報を明らかにすることができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-221">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="ffbd9-222">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-222">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="ffbd9-223">**スクリーン リーダーでの操作の確認:** 操作の確認は、重要なアクセシビリティ要件です。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-223">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="ffbd9-224">Windows からの新しい通知 API の導入により、操作の成功をスクリーン リーダーのユーザーに通知できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-224">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="ffbd9-225">切り取り、コピー、貼り付け、太字、斜体、下線、元に戻す、やり直し、自動修正、および自動大文字化が、Win32 Word のナレーター ユーザーにすべて通知されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-225">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="ffbd9-226">この機能を有効にするには、Windows + Ctrl + Enter キーを押してナレーターをオンにします。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-226">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span><br /><span data-ttu-id="ffbd9-227">[ブログの投稿](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-227">See details in [blog post](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="ffbd9-228">Office スイート</span><span class="sxs-lookup"><span data-stu-id="ffbd9-228">Office Suite</span></span>

- <span data-ttu-id="ffbd9-229">**秘密度ラベル:** カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-229">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-232">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-232">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ffbd9-233">Access</span><span class="sxs-lookup"><span data-stu-id="ffbd9-233">Access</span></span>

- <span data-ttu-id="ffbd9-234">[ズーム] ウィンドウの使用中に、アプリケーションが予期せず終了してしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-234">Fixed an issue where the application would  close unexpectedly when using Zoom window.</span></span>


- <span data-ttu-id="ffbd9-235">この修正プログラムでは、特定のクエリを実行しようとすると、"クエリが複雑すぎます" というエラー メッセージが表示されてしまう問題に対処しています。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-235">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>


- <span data-ttu-id="ffbd9-236">テキストを編集するため [ズーム] ボックスを起動する (Shift + F2) ときに、Access が予期せずに終了してしまう可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-236">This change fixes an issue that could cause Access to to close unexpectedly when launching the Zoom box (Shift + F2) to edit text.</span></span>


- <span data-ttu-id="ffbd9-237">ID (オートナンバーなど) フィールドが含まれるリンク付きの SQL 表を挿入する場合についての問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-237">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>


- <span data-ttu-id="ffbd9-238">クエリの実行に予想よりも約 2 倍の時間がかかっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-238">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>


- <span data-ttu-id="ffbd9-239">アプリケーションの問題を発生させずに、日付/時刻の拡張データ型をコードに呼び出すことができるように問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-239">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any issues in your app.</span></span>


- <span data-ttu-id="ffbd9-240">この問題は修正されて、最新の Access バージョンに戻し、 DAO/VBA を使用して 10 進数データ型を管理および編集することができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-240">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>


- <span data-ttu-id="ffbd9-241">ODBC DSNBuilder を使用しようとするときに発生するエラーに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="ffbd9-241">We fixed an error issue when trying to use ODBC DSN builder</span></span>


- <span data-ttu-id="ffbd9-242">この問題は解決されました。これで、Office のクイック実行アプリケーション以外の ODBC ドライバーを使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-242">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>


### <a name="excel"></a><span data-ttu-id="ffbd9-243">Excel</span><span class="sxs-lookup"><span data-stu-id="ffbd9-243">Excel</span></span>

- <span data-ttu-id="ffbd9-244">読み取り専用モードのブックに対して、ドキュメント分類を自動的に行った可能性があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-244">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>


- <span data-ttu-id="ffbd9-245">アカウントからサインアウトしている場合に、データ接続を作成しようとすると発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-245">Fixed an issue that could happen when trying to create a data connection if you have signed out from your account.</span></span>


- <span data-ttu-id="ffbd9-246">"前" と "後" のフィルター条件が逆転してしまうバグをPivotDateFilter API で修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-246">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


- <span data-ttu-id="ffbd9-247">ピボットテーブルをチャート シートに挿入しようとしたときに Excel が予期せずに終了してしまう場合がある問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-247">Addressed an issue where Excel may close unexpectedly when attempting to insert PivotTables into a chart sheet.</span></span>


- <span data-ttu-id="ffbd9-248">プロジェクト計画からエクスポートした場合に、ピボットテーブルを編集できず、ブックを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-248">Fixed an issue where pivot tables could not be edited and workbooks could not be saved if they were exported from Project plan.</span></span>


- <span data-ttu-id="ffbd9-249">LET() 関数を使用している数式を含むファイルを保存しようとするときに、エラーが発生する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-249">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>


- <span data-ttu-id="ffbd9-250">ファイルを読み取り専用モードで開いたときに、複数のメッセージ バーが表示される場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-250">We fixed an issue where in some cases, multiple message bars were appearing when a file was opened in read-only mode.</span></span>


- <span data-ttu-id="ffbd9-251">列ヘッダーの値が重複していると、アウトラインの小計が機能しなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-251">We fixed an issue where outline sub-totals could stop working when there were many duplicate column header values.</span></span>


- <span data-ttu-id="ffbd9-252">読み取り専用のブックを開いたときに、ピボット テーブルのデータが更新されなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-252">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="ffbd9-253">この変更により、次の問題が修正されます: OneDrive ローカル同期フォルダーからファイルを挿入すると、Excel の [オブジェクトの挿入] に正しいアイコンが表示されない。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-253">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="ffbd9-254">マルチ スレッドの再計算中にグループ ポリシー オブジェクトの更新 (リモート グループ ポリシーの更新など) が行われた場合に Excel が機能しなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-254">We fixed an issue where Excel would stop working when there is a Group Policy Object update (e.g. via Remote Group Policy Refresh) during multithreaded recalc.</span></span>


- <span data-ttu-id="ffbd9-255">ユーザーが 255 を超える列で subtotal 関数を使用すると、Excel が機能しなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-255">We fixed an issue where Excel would stop working when users use the subtotal function on more than 255 columns.</span></span>


- <span data-ttu-id="ffbd9-256">PowerPoint でコンテンツを Excel からコピーし、Embed オプションを使用して PowerPoint に貼り付けたときのテキスト カーニングを改善しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-256">Improved text kerning in PowerPoint when when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="ffbd9-257">PowerPivot のテーブルプレビューとクエリエディターからの切り替えができなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-257">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="ffbd9-258">ユーザーが SharePoint から .atomsvc (UTF8 + BOM) ファイルを直接開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-258">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="ffbd9-259">共同編集のときに、新しいバージョンのファイルに関する通知が誤って送信される可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-259">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="ffbd9-260">Overwrite モードで IME を使用するときに、余計な文字を誤って前に進めてしまうという編集に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-260">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="ffbd9-261">リアルタイム データをマルチスレッドの再計算機能と組み合わせて使用するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-261">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="ffbd9-262">特定の Windows セキュリティのエクスプロイト保護設定 (SimExec、CallerCheck) を使用している場合に、Excel の起動に失敗したり、予期せずクラッシュしたりしてしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="ffbd9-262">Fixes an issue where Excel would fail to launch or crash unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


- <span data-ttu-id="ffbd9-263">Format Painter を使用しているときに、特定の状況で Excel が予期せず終了してしまう可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-263">Fixed an issue where Excel could close unexpectedly in certain circumstances when using the Format Painter.</span></span>


- <span data-ttu-id="ffbd9-264">Analysis Services データベースに既に存在しない値に設定されているために、ユーザーがピボットテーブル フィルターを変更できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-264">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="ffbd9-265">シートの一番上の行を固定した後にクイック分析を使用するときに、Excel が予期せず終了してしまう可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-265">Fixed an issue where Excel could close unexpectedly when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="ffbd9-266">ブックをロードした後、特定の関数の結果が不正確であるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-266">We fixed an issue where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="ffbd9-267">XLAM アドイン参照と名前付き範囲に関連するアプリケーションが予期せず終了する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-267">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="ffbd9-268">マクロを使用して、範囲の FormulaR1C1 プロパティを設定する問題を修正しました。グラフ シートがアクティブ シートである場合、セル参照が正しくありませんでした。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-268">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="ffbd9-269">Excel で 1 つまたは複数の数式を計算しようとする際に発生する、Excelはリソース不足になりましたというエラーが生じる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-269">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="ffbd9-270">Office の言語がスペイン語に設定されているときに、データ検証リストにすべてのアイテムが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-270">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="ffbd9-271">OLAP ピボットテーブルを更新するときにハングする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-271">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="ffbd9-272">SharePoint/OneDrive に保存すると、ユーザー設定のリボンタブの CustomUI XML が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-272">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>


- <span data-ttu-id="ffbd9-273">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-273">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="ffbd9-274">同じブック内の場所へのハイパーリンクをクリックすると、ブックが非表示になることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-274">Fixed an issue where in some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


- <span data-ttu-id="ffbd9-275">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-275">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>


- <span data-ttu-id="ffbd9-276">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-276">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


- <span data-ttu-id="ffbd9-277">ピボットテーブルを含むシートをコピーした後、Excel が予期せず終了してしまう可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-277">Fixed an issue which would cause Excel to close unexpectedly in some cases after copying a sheet containing a PivotTable.</span></span>


- <span data-ttu-id="ffbd9-278">ファイル パスが長すぎる場合にファイルをもう一度開くと、外部リンクが機能しなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-278">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>


- <span data-ttu-id="ffbd9-279">リアルタイム データをマルチスレッドの再計算機能と組み合わせて使用するときに、アプリケーションが予期せず終了してしまう可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-279">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality could cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="ffbd9-280">ソース ブックが閉じている場合に、外部リンクが塗りつぶし時に更新されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-280">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>


- <span data-ttu-id="ffbd9-281">IFNA() を使用している数式が含まれている場合、破損したワークブックに関する警告が表示される可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-281">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


- <span data-ttu-id="ffbd9-282">問題が修正され、Power Pivot がタブ区切り文字を正常に認識するようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-282">We fixed an issue where Power Pivot will now successfully recognize tab delimiter.</span></span>


### <a name="onenote"></a><span data-ttu-id="ffbd9-283">OneNote</span><span class="sxs-lookup"><span data-stu-id="ffbd9-283">OneNote</span></span>

- <span data-ttu-id="ffbd9-284">全世界でサービス使用量が高まった際に、同期とサービスの可用性を改善できる、Microsoft OneNote の一時的な調整に関して、情報バーを介してユーザーに通知します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-284">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>


- <span data-ttu-id="ffbd9-285">OneNote 2016 で同期頻度を一時的に調整することで、同期およびサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-285">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>


- <span data-ttu-id="ffbd9-286">リソースの使用率を低下させて、共同編集状態の検出機能を改善します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-286">Improved detection of co-authoring status to reduce resource utilization.</span></span>


- <span data-ttu-id="ffbd9-287">ページのバージョン履歴を作成する頻度を一時的に変更することで、同期およびサービスの安定性が改善されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-287">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>


- <span data-ttu-id="ffbd9-288">OneNote 2016 に 50 MB へ埋め込まれた新しい添付ファイルの最大許容サイズが一時的に減少することにより、同期とサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-288">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="ffbd9-289">この制限を超えるファイルの場合、ユーザーは OneDrive にファイルをアップロードして、OneNote にリンクを挿入することができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-289">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>


- <span data-ttu-id="ffbd9-290">OneNote 2016 でアプリ内動画のレコーディングを一時的に無効にすることで、同期およびサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-290">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="ffbd9-291">ローカルのノートブックはこの影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-291">Local notebooks are not impacted by this measure.</span></span>


- <span data-ttu-id="ffbd9-292">ごみ箱へのページの移動を一時的に無効にすることにより、同期およびサーバーの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-292">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="ffbd9-293">代わりに、ページを削除するユーザーにはページを完全に削除するか確認するダイアログが表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-293">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>


- <span data-ttu-id="ffbd9-294">スペル ​​チェック メニューが読み込まれないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-294">We fixed an issue where the spelling menu was not loading.</span></span>


### <a name="outlook"></a><span data-ttu-id="ffbd9-295">Outlook</span><span class="sxs-lookup"><span data-stu-id="ffbd9-295">Outlook</span></span>

- <span data-ttu-id="ffbd9-296">オプションの接続エクスペリエンスが Web アドインの読み込みをブロックしてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-296">We fixed an issue where optional connected experiences blocked web add-ins from loading.</span></span>  <span data-ttu-id="ffbd9-297">詳細については、以下を参照してください: https://developer.microsoft.com/en-us/office/blogs/outlook-add-ins-and-optional-connected-experiences/</span><span class="sxs-lookup"><span data-stu-id="ffbd9-297">See more detail here:  https://developer.microsoft.com/en-us/office/blogs/outlook-add-ins-and-optional-connected-experiences/</span></span>


- <span data-ttu-id="ffbd9-298">Outlook の IRM (Information Rights Management) を他の Office アプリケーションで無効にすることなく無効にできる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-298">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="ffbd9-299">ユーザーが代理人に編集者権限を付与できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-299">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="ffbd9-300">ユーザーが検索結果を選択したときにアプリケーションが予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-300">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="ffbd9-301">プロファイルに追加されたサブ アカウントから会議出席依頼を作成しようとした場合に、ユーザーのメール アドレスの代わりに空欄の From: フィールドが表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-301">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>


- <span data-ttu-id="ffbd9-302">共有メールボックスを追加した後に、ユーザーがパブリック フォルダーに接続できない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-302">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


- <span data-ttu-id="ffbd9-303">特定の状況で代理人が会議を辞退したときに、マネージャーのカレンダーから削除されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-303">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>


- <span data-ttu-id="ffbd9-304">共有カレンダーの改善機能を使用している一部のユーザーが、新しく追加された共有カレンダーを表示できない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-304">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>


- <span data-ttu-id="ffbd9-305">隅にある [X] をクリックして共有の予定表を閉じることができない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-305">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="ffbd9-306">[共有予定表の機能を有効にする] 設定が既存の共有予定表に適用されないことがある問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-306">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="ffbd9-307">グループ予定表で検索結果が返されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-307">We fixed an issue that caused searches in Group calendars fail to return any results.</span></span>


- <span data-ttu-id="ffbd9-308">クラウドの添付ファイルを操作しているときに、不定期に終了してしまう場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-308">Fixes an issue that caused users to experience occasional closures when interacting with Cloud attachments.</span></span>


- <span data-ttu-id="ffbd9-309">保護されたコンテキストから保護されていないコンテキストに返信するとき、送信元アドレスを切り替えると、CLP のユーザーにエラーが発生してしまう問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-309">Addressed an issue that caused users of CLP to experience an issue when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="ffbd9-310">クラウドの添付ファイルを開くときに、開こうとしていたドキュメントの代わりに、安全なリンクの ページにエラーが表示される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-310">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="ffbd9-311">M365 Business Plus プランのサービスを利用していたユーザーがデータ損失防止の保護ポリシー ヒントを有効にできない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-311">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>


- <span data-ttu-id="ffbd9-312">CLP の監査イベントで、返信/転送ラベルの問題に対応しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-312">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="ffbd9-313">フォルダー ウィンドウの幅が予期せず変更される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-313">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>


- <span data-ttu-id="ffbd9-314">タスクのステータスレポートを送信するときに To: フィールドが空白になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-314">We fixed an issue that caused the To: field to be empty when sending a status report on a Task.</span></span>


- <span data-ttu-id="ffbd9-315">MailItem.BeforeAttachmentAdd イベントの破損原因となった問題が修正されました。 </span><span class="sxs-lookup"><span data-stu-id="ffbd9-315">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="ffbd9-316">ドラッグ アンド ドロップによってファイル システムにコピーされた添付ファイルの作成日が、4501年1月1日に設定される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-316">Addressed an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>


- <span data-ttu-id="ffbd9-317">SharePoint ファイルに Smart Link を追加すると、一部の文字セットのユーザーにファイル名が正しく表示されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-317">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="ffbd9-318">ユーザーが Outlook のルールを更新すると、「このコンピューターのルールは、Microsoft Exchange のルールと異なります」というメッセージが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-318">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>


- <span data-ttu-id="ffbd9-319">Outlook で検索候補を取得できない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-319">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="ffbd9-320">共有された予定表の改良版のユーザーに予定表のエラーが表示される問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-320">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="ffbd9-321">一部のシナリオで、断続的なハングや終了を発生させる原因となっている問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-321">Addressed an issue that caused users to experience intermittent hangs and closures in some scenarios.</span></span>


- <span data-ttu-id="ffbd9-322">[ヘッダーのみダウンロード] オプションが選択されている POP アカウントから 4 件以上のメールを削除しようとするとエラーが発生するという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-322">Addressed an issue which caused users to experience an issue when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>


- <span data-ttu-id="ffbd9-323">代理人が別のメールボックスで共有フォルダーを開くと、断続的にエラーが表示される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-323">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="ffbd9-324">件名が空白の場合、一部の自動的に生成されたメールの本文が空で送信される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-324">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="ffbd9-325">[共有フォルダーのダウンロード] がチェックされていない場合、共有された予定表の会議の [返信オプション] に [転送を許可する] オプションが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-325">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="ffbd9-326">管理者のカレンダー上で既存のカレンダーの予定を編集するときに代理人がエラーを受け取る問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-326">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="ffbd9-327">サードパーティ製の MAPI アプリケーションでエラーが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-327">Addressed an issue that caused users to experience an issue in third party MAPI applications.</span></span>


- <span data-ttu-id="ffbd9-328">Windows の更新後に、ローカルに保存された .msg または .oft ファイルを開くと Outlook が予期せず終了してしまうという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-328">Addressed an issue that caused Outlook to close unexpectedly when opening .msg or .oft files that were saved locally after a Windows update.</span></span>


- <span data-ttu-id="ffbd9-329">Windows の一部のビルドで Outlook が予期せず終了してしまう問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-329">Addressed an issue that caused Outlook to close unexpectedly on some builds of Windows.</span></span>


- <span data-ttu-id="ffbd9-330">Windows 10 サーバー バージョンのユーザーに、以下の警告が表示される問題に対処しました。「アンチウイルスの状態が無効です。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-330">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="ffbd9-331">このバージョンの Windows はウイルス対策ソフト検出をサポートしていますが、ウイルス対策ソフトが見つかりませんでした」という警告が、アンチウイルスが正しくインストールされているにもかかわらず表示されていました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-331">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>


- <span data-ttu-id="ffbd9-332">Outlook 以外のアプリケーションから Outlook メールを送信するときに、一部のユーザーのアプリケーションが予期せず閉じる原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-332">We fixed an issue that was causing some users to experience the application to close unexpectedly when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="ffbd9-333">添付ファイルのアップロードのパフォーマンスの問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-333">Addresses a performance issue with attachment upload.</span></span>


- <span data-ttu-id="ffbd9-334">Outlook で、受信トレイ修復ツールを実行するように促す表示が継続的に発生してしまうという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-334">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="ffbd9-335">マウスで ”X” ボタンを使用しているときにエラーが発生する原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-335">Addressed an issue that caused users to occasionally experience an issue when using the "X" button on their mouse.</span></span>


- <span data-ttu-id="ffbd9-336">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカルコンピューターに保存できない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-336">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="ffbd9-337">返信または転送時に、中国語メッセージのヘッダーが文字化けしてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-337">We fixed an issue that caused the headers of Chinese messages to get garbled when replying or forwarding.</span></span>


- <span data-ttu-id="ffbd9-338">スケジュール アシスタント ページが表示されない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-338">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="ffbd9-339">一部のユーザーにスケジュール アシスタント ページが表示されない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-339">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>


- <span data-ttu-id="ffbd9-340">オンライン モードでフォルダ間で複数のメール アイテムを移動すると、ユーザーのパフォーマンスが低下する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-340">We fixed an issue that caused users to experience degraded performance when moving multiple mail items between folders in online mode.</span></span>


- <span data-ttu-id="ffbd9-341">IDataObject 操作 (つまりクリップボードのドラッグやドロップ) で、ユーザーが添付ファイルに対して filetime の付加を無効にできるように、regkey を追加しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-341">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span> <span data-ttu-id="ffbd9-342">HKCU \ SOFTWARE \ Microsoft \ Office \ 16.0 \ Outlook \ Attachments REG_DWORD IncludeFileTimesInDataObject 0 = filetimes は除外されます 1 = (既定)filetimes が含まれます</span><span class="sxs-lookup"><span data-stu-id="ffbd9-342">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes are excluded  1 = (default) filetimes are included</span></span>


- <span data-ttu-id="ffbd9-343">Azure Information Protection の保護ラベルを使用してメッセージに返信するときに、インライン画像が消えるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-343">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="ffbd9-344">Azure Protected Voicemail を送信するときにユーザー名が電話番号として表示され、Outlook Desktop ユーザーが外部ユーザーからのボイス メールを開くことができなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-344">We fixed an issue that caused the user name to be displayed as a phone number when sending an Azure Protected Voicemail, causing Outlook Desktop users to be unable to open voicemails from external users.</span></span>


- <span data-ttu-id="ffbd9-345">OME構成を設定すると、DecryptAttachmentsForEncryptOnly オプションがサービス側で設定されていても、メールアイテムに無関係な添付ファイルが追加され、Outlook がメッセージを暗号化するように強制される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-345">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though the DecryptAttachmentsForEncryptOnly option was setup on the service side.</span></span>


- <span data-ttu-id="ffbd9-346">ポリシーによって無効にしているにもかかわらず、一部のシナリオにおいて暗号化のみおよび転送不可オプションが有効になってしまう場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-346">We fixed an issue that caused the Encrypt Only and Do Not Forward options to continue to be enabled in some scenarios despite being disabled by policy.</span></span>


- <span data-ttu-id="ffbd9-347">下書きに保存するときに、SmartLinks が書式設定を失ってしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-347">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="ffbd9-348">ポリシーを上書きするときに、正当化テキストをカスタマイズする方法をユーザーに提供してしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-348">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="ffbd9-349">OFT ファイルとして保存するときに、中国語の文字が疑問符に変更されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-349">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="ffbd9-350">ユーザーがペルソナ情報を取得しようとするときに、意図せず終了してしまう場合があるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-350">Addressed an issue that caused users to occasionally experience unexpected closures when retrieving persona information.</span></span>


- <span data-ttu-id="ffbd9-351">これにより、受信者を編集しているときに、不定期にアプリケーションが終了してしまうという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-351">This fixes an issue that caused users to experience occasional application closures when editing recipients.</span></span>


- <span data-ttu-id="ffbd9-352">コンパクト ビューを使用するときに異常が表示される原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-352">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>


- <span data-ttu-id="ffbd9-353">Outlook ユーザーにコンパクト ビューでのナビゲーションの問題が表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-353">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>


- <span data-ttu-id="ffbd9-354">右クリックのコンテキストメニューが検索コントロールに表示されない問題の原因を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-354">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>


- <span data-ttu-id="ffbd9-355">ユーザーが新しいメールに返信または作成するときに次のエラーを受け取る原因となった問題に対処します。「この Web ページのファイルの一部が予期された場所にありません。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-355">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="ffbd9-356">この Web ページをダウンロードする必要がありますか? </span><span class="sxs-lookup"><span data-stu-id="ffbd9-356">Do you want to download them anyway?</span></span> <span data-ttu-id="ffbd9-357">Web ページが信頼できるソースからのものであることを確認したら、[はい] をクリックします。」</span><span class="sxs-lookup"><span data-stu-id="ffbd9-357">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


- <span data-ttu-id="ffbd9-358">Outlook の終了中に応答停止が発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-358">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


- <span data-ttu-id="ffbd9-359">Suggest a Feature で機能を検索しても結果が返されず、ユーザーが新しい機能のアイデアを提出するオプションがないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-359">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


- <span data-ttu-id="ffbd9-360">インシデント通知アラートのフォーマットの問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-360">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>


- <span data-ttu-id="ffbd9-361">ユーザーが管理者通知からフィードバックを送信するときに、予期せず終了してしまうという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-361">Addressed an issue that caused users to experience sudden closures when submitting feedback from an Admin Notification.</span></span>


- <span data-ttu-id="ffbd9-362">SVG 画像のコピーと貼り付けの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-362">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ffbd9-363">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ffbd9-363">PowerPoint</span></span>

- <span data-ttu-id="ffbd9-364">この変更により、[エクスポート] ボタンをクリックしてもエクスポートされないという [アニメーション GIF にエクスポート] 機能の問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-364">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="ffbd9-365">ユーザーが別のスライドをクリックして表示するまで、Forms コンテンツ アドインが挿入後にレンダリングされないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-365">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>


- <span data-ttu-id="ffbd9-366">セキュリティ修正プログラムを適用し、保護ビューで PowerPoint ファイルを開いたときに IRM による保護が無効になってしまうという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-366">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


- <span data-ttu-id="ffbd9-367">Slide.Shapes.AddMediaObject2 が従来のビデオ形式 (MPG-1、Mpeg-2) でクラッシュする VBA の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-367">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="ffbd9-368">ユーザーがソース パスをローカルの OneDrive フォルダーに変更すると、リンクされた Excel グラフが誤って Excel シートに変更されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-368">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="ffbd9-369">ユーザーがファイルに最新のコメントと従来のコメントの両方を持っていると、コメントのアップグレードが開始されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-369">Fixed an issue when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


- <span data-ttu-id="ffbd9-370">アプリケーションが予期せず終了してしまう場合がある提案ウィンドウに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-370">We have fixed an issue with suggestion pane that may cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="ffbd9-371">PowerPoint アプリで予期しない終了の原因となっていたオブジェクトの動作設定の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-371">We have fixed an issue in Action Settings dialog which was causing the PowerPoint app to close unexpectedly.</span></span>


- <span data-ttu-id="ffbd9-372">PowerPoint アプリが予期せず終了してしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-372">We have fixed an issue with PowerPoint app that may cause it to close unexpectedly.</span></span>


- <span data-ttu-id="ffbd9-373">「Welcome back!」機能が原因で発生した問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-373">We fixed an issue due to which the feature ‘Welcome back!</span></span> <span data-ttu-id="ffbd9-374">PowerPoint で機能していなかったオフィスで中断したところから再開します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-374">Pick up where you left off in the office' was not working in the PowerPoint .</span></span>


- <span data-ttu-id="ffbd9-375">ドキュメントの修復操作の後であっても、一部の破損した PowerPoint ファイルを正常に開くことができないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-375">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="ffbd9-376">ドキュメントの修復操作の後であっても、一部の破損した PowerPoint ファイルを正常に開くことができないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-376">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="ffbd9-377">保護ビューでのスライドショーが機能しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-377">We fixed an issue where Slideshow in protected view was not working.</span></span>


### <a name="project"></a><span data-ttu-id="ffbd9-378">Project</span><span class="sxs-lookup"><span data-stu-id="ffbd9-378">Project</span></span>

- <span data-ttu-id="ffbd9-379">[リソースの割り当て] ダイアログ ボックスで選択されているタスクが、[タスク ボード] ビューで選択したタスクと異なる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-379">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="ffbd9-380">リソースに複数のコスト単価表が定義されている場合に、残りのコストが正しく計算されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-380">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>


- <span data-ttu-id="ffbd9-381">SharePoint タスクリストに接続されているプロジェクトのプロジェクト終了日が更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-381">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>


- <span data-ttu-id="ffbd9-382">Project Web App に接続されている Project を使用していて小数点の記号がカンマの場合に、依存関係のタイム ラグを生じさせようとすると TaskDependencies Add メソッドが失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-382">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


- <span data-ttu-id="ffbd9-383">タスクを完了とマークした後に、タスクの達成率が 100% 完了より小さい値に誤って変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-383">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>


- <span data-ttu-id="ffbd9-384">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-384">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>


- <span data-ttu-id="ffbd9-385">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-385">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


- <span data-ttu-id="ffbd9-386">[無効化] ボタンを介してタスクが非アクティブ化/アクティブ化された場合に、ProjectBeforeTaskChange イベントが検出しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-386">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>


- <span data-ttu-id="ffbd9-387">先行処理/後続処理データがフォーム ビュー内で編集されるときに、余計な ProjectBeforeTaskChange イベントが発生してしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-387">Fixed an issue when Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>


- <span data-ttu-id="ffbd9-388">以前のバージョンの Project で作成したプロジェクトを保存するときに、Project が予期せず終了してしまう場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-388">Fixed an issue where Project may close unexpectedly when saving projects created with older versions of Project.</span></span>


- <span data-ttu-id="ffbd9-389">実績作業時間の保護設定を有効にしているときに、ユーザーがタイムフェーズの基準作業時間を入力できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-389">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>


- <span data-ttu-id="ffbd9-390">Project から SharePoint ドキュメント ライブラリに PDF/XPS を保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-390">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="ffbd9-391">複数の依存関係があるタスクを貼り付けると、すべての依存関係が正しくコピーされるわけではない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-391">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="ffbd9-392">URL が .com で終了している場合に、Project Web App からプロジェクト デスクトップ クライアントでプロジェクトを開くことができない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-392">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="ffbd9-393">プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-393">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>


- <span data-ttu-id="ffbd9-394">100% 完了とマークされているタスクが、100% 未満のタスクに間違って変更されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-394">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>


- <span data-ttu-id="ffbd9-395">リソースの配分状況が特定の方法で指定されている場合に、Project が予期せず終了してしまう場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-395">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="ffbd9-396">Skype</span><span class="sxs-lookup"><span data-stu-id="ffbd9-396">Skype</span></span>

- <span data-ttu-id="ffbd9-397">ダンス絵文字の肌の色を中間色に変更しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-397">Changed dancing emoticon skin tone to neutral color.</span></span>


- <span data-ttu-id="ffbd9-398">ユーザーが Teams Only に移動するポリシーを与えられた場合は、Skype for Business Outlook アドインを使用して会議をスケジュールできます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-398">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="ffbd9-399">この更新プログラムを適用すると、クライアントは Teams Only を対象としていることを示すポリシーをユーザーが読んでから会議参加のみのモードに入った後に、Skype for Business 会議のスケジュールを設定できなくなります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-399">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="ffbd9-400">また、skype for business Outlook アドインは、Skype for business クライアントが 「会議の参加のみ」 モードであることを確認した場合に起動した場合、自動的にアクティブ化されることはありません。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-400">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>


- <span data-ttu-id="ffbd9-401">ユーザの TLS-DSK 証明書が期待通りの時間に更新されず、有効期間が 12 時間未満の場合にのみ更新されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-401">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="ffbd9-402">Office にまだライセンスが付与されていない場合、サインイン後に Skype for Business UI が空白で表示されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-402">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="visio"></a><span data-ttu-id="ffbd9-403">Visio</span><span class="sxs-lookup"><span data-stu-id="ffbd9-403">Visio</span></span>

- <span data-ttu-id="ffbd9-404">テキストの配置で、リアルタイムのプレビュー表示が予期せず終了してしまう原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-404">We fixed an issue that caused the Live preview to close unexpectedly on text alignment.</span></span>


- <span data-ttu-id="ffbd9-405">問題が修正され、ユーザーが Visio for Office 365 のコネクタを使用して、ユーザー設定の Visio ステンシルと組み込みのテンプレートの両方で直線を作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-405">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="ffbd9-406">Word</span><span class="sxs-lookup"><span data-stu-id="ffbd9-406">Word</span></span>

- <span data-ttu-id="ffbd9-407">URL にクエリ コンポーネントが含まれている場合にカスタム ドキュメント配信 (aspx) から Word ドキュメントを開く問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-407">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>


- <span data-ttu-id="ffbd9-408">この変更により、以前の共同編集セッションの後に Office アプリケーションがサイレント保存の失敗状態に陥ることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-408">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>


- <span data-ttu-id="ffbd9-409">新しいメールに返信、または新しいメールを作成するときにユーザーにエラーが発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-409">Addresses an issue that caused users to experience an issue when replying to or composing new email.</span></span>


- <span data-ttu-id="ffbd9-410">マウスで ”X” ボタンを使用しているときにエラーが発生する原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-410">Addressed an issue that caused users to occasionally experience an issue when using the "X" button on their mouse.</span></span>


- <span data-ttu-id="ffbd9-411">サイズが非常に大きい特定のメールを開くとエラーが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-411">Fixes an issue that caused users to experience an issue when opening certain very large emails.</span></span>


- <span data-ttu-id="ffbd9-412">番号付きの見出しを貼り付けるときに、追加のインデントが表示されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-412">We fixed an issue where pasted numbered headings showed an additional indent.</span></span>


- <span data-ttu-id="ffbd9-413">SVG 画像のコピーと貼り付けの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-413">We fixed an issue for copy and paste SVG image.</span></span>


- <span data-ttu-id="ffbd9-414">図形のサイズを変更すると、ユーザーがコンテンツを失う可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-414">We fixed an issue where the user might lose content when resize a shape.</span></span>


- <span data-ttu-id="ffbd9-415">ドキュメントを開くときに、ユーザーにエラーが表示されてしまう可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-415">We fixed an issue which user might experience issues when opening a document.</span></span>


- <span data-ttu-id="ffbd9-416">ドキュメントを HTML 形式に保存するときに、長いリンクが折り返されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-416">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="ffbd9-417">基本スタイルが標準スタイルで更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-417">We fixed an issue which the base styles are not updated with Normal style.</span></span>


- <span data-ttu-id="ffbd9-418">コメントの拡張機能で、コメントの返信が親コメントと同じ拡張子になってしまうというバグを修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-418">FIxes a bug with comment extensions where the comment reply would have the same extension as the parent comment.</span></span>


- <span data-ttu-id="ffbd9-419">拡張子リストにない拡張子がある親コメントに返信すると、返信に同じ拡張子が含まれる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-419">We fixed an issue where if you reply to a parent comment that has unknown extensions in an extension list, the reply will get those same extensions.</span></span>


- <span data-ttu-id="ffbd9-420">起動時にアプリケーションが予期せず終了してしまう原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-420">Resolved an issue that may have caused the application to close unexpectedly when booting.</span></span>


- <span data-ttu-id="ffbd9-421">メッセージが [転送不可] に設定されてしまう Outlook の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-421">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="ffbd9-422">スタイル ギャラリー ダイアログの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-422">We fixed an issue with Style Gallery dialog.</span></span>


- <span data-ttu-id="ffbd9-423">マクロ AutoOpen が AutoExec の前に実行されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-423">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>


### <a name="office-suite"></a><span data-ttu-id="ffbd9-424">Office スイート</span><span class="sxs-lookup"><span data-stu-id="ffbd9-424">Office Suite</span></span>

- <span data-ttu-id="ffbd9-425">以前の Web サービス ベースの [共有] ウィンドウで、[共有] ウィンドウが開いているときに文書を閉じるとアプリケーションが予期せず終了してしまう可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-425">Fixed an issue for the old, non-web service based Share pane, where upon closing the document while the Share pane is open could cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="ffbd9-426">Office ファイルを閉じるときに、アプリケーションが予期せず終了してしまう可能性があるタイミングの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-426">Fixed a timing issue that could cause the application to close unexpectedly when closing office files.</span></span>


- <span data-ttu-id="ffbd9-427">ADAL が無効になっているときに、ユーザーが SPO リストをインポートできない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-427">Addresses an issue that prevented users from importing SPO Lists when ADAL was disabled.</span></span>


- <span data-ttu-id="ffbd9-428">Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-428">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="ffbd9-429">このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-429">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="ffbd9-430">Bing アドオンのインストール検証を既定で true に設定し、MSI のリターン成功をインストール成功とみなすことで、ValidateInstall のエラー率の問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-430">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>


- <span data-ttu-id="ffbd9-431">以前の AppV51 の回帰を修正するために、新しい AppV51 drop をバックポートします。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-431">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>


- <span data-ttu-id="ffbd9-432">シンボリック リンクのハード リンクを試みる際に、更新の失敗を引き起こしていたクイック実行の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-432">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>


- <span data-ttu-id="ffbd9-433">Microsoft 365 エンドポイントのデータ損失防止を使用して Office Update に System Center Configuration Manager またはその他の管理ツールを利用する商用顧客の問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-433">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>


- <span data-ttu-id="ffbd9-434">製品版への移行が完了した場合でも、ランタイムメッセージが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-434">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="ffbd9-435">この問題の修正では、サービスが追加された製品を適切に計算するようにしました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-435">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="ffbd9-436">新たに追加された製品をフィルターで除外し (新しい構成に存在することも確認)、既存の製品リリース ID の最後に追加しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-436">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>


- <span data-ttu-id="ffbd9-437">特定の状況下で UI 要素またはコンテンツが表示されない問題を修正しました。特に、発表者ツールのオン/オフ、または複数のモニターの使用に関して発生しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-437">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>


- <span data-ttu-id="ffbd9-438">この変更により、従来の図面を含むファイルを開くことに関連する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-438">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="ffbd9-439">この変更により、SVG フォールバック プロキシでアクセス違反が発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-439">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>


- <span data-ttu-id="ffbd9-440">GIF/アニメーション model3D を使用したアイドル時の高い CPU 使用率を修正します</span><span class="sxs-lookup"><span data-stu-id="ffbd9-440">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="ffbd9-441">この変更により、Gif や3D モデルなどのアニメーション コンテンツを読み込んだり、再生したりするときに、ハングしてしまう可能性があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-441">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>


- <span data-ttu-id="ffbd9-442">この変更は、d2d1.dll の読み込みに失敗したために、Office アプリを起動したときにエラーが発生してしまう場合がある問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-442">This change addresses a issue when launching Office apps due to failing to load d2d1.dll.</span></span>


- <span data-ttu-id="ffbd9-443">レジストリ キー HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth が 0 に設定されている場合、アドインがアクティブになり、Windows で Office ホストが予期せず終了します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-443">The office host was  close unexpectedly in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="ffbd9-444">この変更により、この問題は修正されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-444">This change would fix this issue.</span></span>


- <span data-ttu-id="ffbd9-445">Office アドインのメッセージング API が機能しない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-445">Fix an issue that the Messaging API for Office Add-ins is not working.</span></span>

- <span data-ttu-id="ffbd9-446">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-446">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


- <span data-ttu-id="ffbd9-447">この更新プログラムでは、Microsoft Office で PATH 環境変数で指定した場所を検索することによって参照される可能性がある Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA ランタイムエラーが発生するという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-447">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="ffbd9-448">この修正プログラムで、アクセスの制限と、パスワードによるファイルの保護が同時に行えないというエラーが解決されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-448">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="ffbd9-449">一部のアプリケーションからコンテンツをドラッグしたときに予期せず終了してしまう問題の原因となっていた可能性がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-449">Resolved an issue that may have caused an unexpected closure when dragging some content from the app.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-january-12"></a><span data-ttu-id="ffbd9-451">バージョン 2002: 1 月 12 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-451">Version 2002: January 12</span></span>
<span data-ttu-id="ffbd9-452">*バージョン 2002 (ビルド 12527.21504)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-452">*Version 2002 (Build 12527.21504)*</span></span>

<span data-ttu-id="ffbd9-453">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-453">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-455">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-455">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ffbd9-456">Excel</span><span class="sxs-lookup"><span data-stu-id="ffbd9-456">Excel</span></span>

- <span data-ttu-id="ffbd9-457">リアルタイム データをマルチスレッドの再計算機能と組み合わせて使用するときに、アプリケーションが予期せず終了してしまう可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-457">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality could cause the application to close unexpectedly.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ffbd9-458">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ffbd9-458">PowerPoint</span></span>

- <span data-ttu-id="ffbd9-459">ドキュメントの修復操作の後であっても、一部の破損した PowerPoint ファイルを正常に開くことができないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-459">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="word"></a><span data-ttu-id="ffbd9-460">Word</span><span class="sxs-lookup"><span data-stu-id="ffbd9-460">Word</span></span>

- <span data-ttu-id="ffbd9-461">コメントの拡張機能で、コメントの返信が親コメントと同じ拡張子になってしまうというバグを修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-461">Fixes a bug with comment extensions where the comment reply would have the same extension as the parent comment.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-january-12"></a><span data-ttu-id="ffbd9-463">バージョン 1908: 1 月 12 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-463">Version 1908: January 12</span></span>
<span data-ttu-id="ffbd9-464">*バージョン 1908 (ビルド 11929.20994)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-464">*Version 1908 (Build 11929.20994)*</span></span>

<span data-ttu-id="ffbd9-465">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-465">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-467">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-467">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="ffbd9-468">Office スイート</span><span class="sxs-lookup"><span data-stu-id="ffbd9-468">Office Suite</span></span>

- <span data-ttu-id="ffbd9-469">この変更により、従来の図面を含むファイルを開くことに関連する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-469">This change addresses an issue related to opening files containing legacy diagrams.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2002-december-08"></a><span data-ttu-id="ffbd9-471">バージョン 2002: 12 月 08 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-471">Version 2002: December 08</span></span>
<span data-ttu-id="ffbd9-472">*バージョン 2002 (ビルド 12527.21416)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-472">*Version 2002 (Build 12527.21416)*</span></span>

<span data-ttu-id="ffbd9-473">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-473">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-475">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-475">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ffbd9-476">Excel</span><span class="sxs-lookup"><span data-stu-id="ffbd9-476">Excel</span></span>

- <span data-ttu-id="ffbd9-477">コンテンツが Excel からコピーされ、[埋め込み] オプションを使用して PowerPoint に貼り付けられたときの PowerPoint のテキスト カーニングが改善されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-477">Improved text kerning in PowerPoint when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="ffbd9-478">Excel が再計算中に作業を停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-478">We fixed an issue where Excel would stop working during recalc.</span></span>


- <span data-ttu-id="ffbd9-479">ユーザーが SharePoint から .atomsvc (UTF8 + BOM) ファイルを直接開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-479">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="ffbd9-480">PowerPivot のテーブル プレビューとクエリ エディターからの切り替えができなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-480">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="ffbd9-481">最近リリースされた機能の多くを使用しているファイルのパフォーマンスが向上しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-481">Improved performance for files that are using many of the more recently released functions.</span></span>


### <a name="outlook"></a><span data-ttu-id="ffbd9-482">Outlook</span><span class="sxs-lookup"><span data-stu-id="ffbd9-482">Outlook</span></span>

- <span data-ttu-id="ffbd9-483">サービス側で DecryptAttachmentsForEncryptOnly オプションが設定されていても、OME 構成を設定すると、メールアイテムに無関係な添付ファイルが追加され、Outlook がメッセージを強制的に暗号化される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-483">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though DecryptAttachmentsForEncryptOnly option is setup on the service side.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ffbd9-484">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ffbd9-484">PowerPoint</span></span>

- <span data-ttu-id="ffbd9-485">ユーザーがソース パスをローカルの OneDrive フォルダーに変更すると、リンクされた Excel グラフが誤って Excel シートに変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-485">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


### <a name="project"></a><span data-ttu-id="ffbd9-486">Project</span><span class="sxs-lookup"><span data-stu-id="ffbd9-486">Project</span></span>

- <span data-ttu-id="ffbd9-487">URL が「.com」で終了している場合に、Project Web App から Project デスクトップ クライアントでプロジェクトを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-487">We fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App is the URL ended in .com.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-december-08"></a><span data-ttu-id="ffbd9-489">バージョン 1908: 12 月 08 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-489">Version 1908: December 08</span></span>
<span data-ttu-id="ffbd9-490">*バージョン 1908 (ビルド 11929.20984)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-490">*Version 1908 (Build 11929.20984)*</span></span>

<span data-ttu-id="ffbd9-491">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-491">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-november-10"></a><span data-ttu-id="ffbd9-492">バージョン 2002: 11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-492">Version 2002: November 10</span></span>
<span data-ttu-id="ffbd9-493">*バージョン 2002 (ビルド 12527.21330)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-493">*Version 2002 (Build 12527.21330)*</span></span>

<span data-ttu-id="ffbd9-494">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-494">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-496">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-496">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ffbd9-497">Excel</span><span class="sxs-lookup"><span data-stu-id="ffbd9-497">Excel</span></span>

- <span data-ttu-id="ffbd9-498">Office の言語がスペイン語に設定されているときに、データ検証リストにすべてのアイテムが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-498">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="ffbd9-499">OLAP ピボットテーブルを更新するときにハングする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-499">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="ffbd9-500">ブックをロードした後、特定の関数の結果が不正確であるというバグが修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-500">Fixed a bug where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="ffbd9-501">XLAM アドイン参照と名前付き範囲に関連するアプリケーションが予期せず終了する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-501">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="ffbd9-502">高度なフィルターマクロを実行すると誤ってエラーが報告される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-502">Fixed an issue where running the advanced filter macro would incorrectly report errors.</span></span>


### <a name="outlook"></a><span data-ttu-id="ffbd9-503">Outlook</span><span class="sxs-lookup"><span data-stu-id="ffbd9-503">Outlook</span></span>

- <span data-ttu-id="ffbd9-504">オプションの接続エクスペリエンスが無効になっていると、内部アドインが予期せず無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-504">We fixed an issue that caused internal add-ins to be unexpectedly disabled when optional connected experiences were disabled.</span></span>


- <span data-ttu-id="ffbd9-505">ユーザーが、グローバル アドレス リストから隠されていた配布リストとして、またはその代理として送信できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-505">We fixed an issue that caused users to be unable to send as or on behalf of a Distribution List that was hidden from the Global Address List.</span></span>



[//]: # (BUGDETAILS コンテンツ エンドを削除しないでください。終了)

## <a name="version-1908-november-10"></a><span data-ttu-id="ffbd9-507">バージョン 1908: 11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-507">Version 1908: November 10</span></span>
<span data-ttu-id="ffbd9-508">*バージョン 1908 (ビルド 11929.20974)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-508">*Version 1908 (Build 11929.20974)*</span></span>

<span data-ttu-id="ffbd9-509">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-509">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-october-13"></a><span data-ttu-id="ffbd9-510">バージョン 2002: 10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-510">Version 2002: October 13</span></span>
<span data-ttu-id="ffbd9-511">*バージョン2002 (ビルド 12527.21236)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-511">*Version 2002 (Build 12527.21236)*</span></span>

<span data-ttu-id="ffbd9-512">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-512">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-514">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-514">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ffbd9-515">Access</span><span class="sxs-lookup"><span data-stu-id="ffbd9-515">Access</span></span>

- <span data-ttu-id="ffbd9-516">Access データベースのガイドラインと要件を満たしている限り、Accessの 64-ビットバージョンで"クエリが複雑すぎます" や "システム超かエラー" が表示されなくなります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-516">You should no longer receive a "Query is too complex" or a system resource exceeded error on your 64-bit version of Access, as long as you are meeting Access database guidelines and requirements.</span></span>


- <span data-ttu-id="ffbd9-517">クエリデザイナーの後にフィルター機能を使用すると、データベースがクラッシュしなくなります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-517">Once you decide to use our filter feature after our query designer, your database should no longer crash.</span></span> <span data-ttu-id="ffbd9-518">それについて確認してください。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-518">Please check accordingly.</span></span>


### <a name="excel"></a><span data-ttu-id="ffbd9-519">Excel</span><span class="sxs-lookup"><span data-stu-id="ffbd9-519">Excel</span></span>

- <span data-ttu-id="ffbd9-520">Analysis Services データベースに既に存在しない値に設定されているために、ユーザーがピボットテーブル フィルターを変更できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-520">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ffbd9-521">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ffbd9-521">PowerPoint</span></span>

- <span data-ttu-id="ffbd9-522">テンプレートから作成された新しいプレゼンテーションは、効率的な共同編集をうまく行うことができない設定を継承する場合があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-522">New presentations created from a template could inherit a setting that prevented  a good co-authoring experience.</span></span> <span data-ttu-id="ffbd9-523">この修正プログラムでは、この場合は設定がクリアされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-523">This fix ensures that the setting is cleared in this case.</span></span>


### <a name="word"></a><span data-ttu-id="ffbd9-524">Word</span><span class="sxs-lookup"><span data-stu-id="ffbd9-524">Word</span></span>

- <span data-ttu-id="ffbd9-525">ページ区切りと列を含む文書を開くと、"Microsoft Word で許可されている最大ページ数を超えたか、またはドキュメントが破損している可能性があります" というエラーメッセージが表示されることがありましたが、この問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-525">We fixed an issue which when opening documents with page breaks and columns, user might encountered an error message, " You have exceeded the maximum number of pages allowed by Microsoft Word supported, or the document may be damaged"</span></span>


### <a name="office-suite"></a><span data-ttu-id="ffbd9-526">Office スイート</span><span class="sxs-lookup"><span data-stu-id="ffbd9-526">Office Suite</span></span>

- <span data-ttu-id="ffbd9-527">Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-527">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="ffbd9-528">このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-528">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-october-13"></a><span data-ttu-id="ffbd9-530">バージョン1908: 10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-530">Version 1908: October 13</span></span>
<span data-ttu-id="ffbd9-531">*バージョン 1908 (ビルド 11929.20966)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-531">*Version 1908 (Build 11929.20966)*</span></span>

<span data-ttu-id="ffbd9-532">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-532">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-534">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-534">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="ffbd9-535">Office スイート</span><span class="sxs-lookup"><span data-stu-id="ffbd9-535">Office Suite</span></span>

- <span data-ttu-id="ffbd9-536">Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-536">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="ffbd9-537">このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-537">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-september-08"></a><span data-ttu-id="ffbd9-539">バージョン 2002: 9 月 08 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-539">Version 2002: September 08</span></span>
<span data-ttu-id="ffbd9-540">*バージョン2002 (ビルド12527.21104)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-540">*Version 2002 (Build 12527.21104)*</span></span>

<span data-ttu-id="ffbd9-541">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-541">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-543">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-543">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ffbd9-544">Excel</span><span class="sxs-lookup"><span data-stu-id="ffbd9-544">Excel</span></span>

- <span data-ttu-id="ffbd9-545">これは、以前のバージョンの Office で SQL データプロバイダーによって作成された接続が内部テーブルのプロパティを Office 365 とは別に設定する問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-545">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="ffbd9-546">これにより、Office 365 を使用して開かれた以前のバージョンの Office で作成された接続を持つファイルに対して、[テーブルのプレビュー / クエリエディター] のドロップダウンが無効になりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-546">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>


- <span data-ttu-id="ffbd9-547">手描き入力で Excel が応答しなくなる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-547">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="ffbd9-548">Outlook</span><span class="sxs-lookup"><span data-stu-id="ffbd9-548">Outlook</span></span>

- <span data-ttu-id="ffbd9-549">共有メールボックスを追加した後に、ユーザーがパブリック フォルダーに接続できない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-549">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ffbd9-550">Office スイート</span><span class="sxs-lookup"><span data-stu-id="ffbd9-550">Office Suite</span></span>

- <span data-ttu-id="ffbd9-551">この変更では、[図の圧縮] ダイアログで一部のユーザー設定が保持されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-551">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-1908-september-08"></a><span data-ttu-id="ffbd9-553">バージョン 1908: 9 月 08 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-553">Version 1908: September 08</span></span>
<span data-ttu-id="ffbd9-554">*バージョン 1908 (ビルド11929.20946)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-554">*Version 1908 (Build 11929.20946)*</span></span>

<span data-ttu-id="ffbd9-555">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-555">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-august-11"></a><span data-ttu-id="ffbd9-556">バージョン 2002: 8 月 11 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-556">Version 2002: August 11</span></span>
<span data-ttu-id="ffbd9-557">*バージョン 2002 (ビルド 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-557">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="ffbd9-558">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-558">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-560">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-560">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ffbd9-561">Excel</span><span class="sxs-lookup"><span data-stu-id="ffbd9-561">Excel</span></span>

- <span data-ttu-id="ffbd9-562">「読み取り専用推奨」として開かれたファイルの編集に切り替えられない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-562">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="ffbd9-563">OneNote</span><span class="sxs-lookup"><span data-stu-id="ffbd9-563">OneNote</span></span>

- <span data-ttu-id="ffbd9-564">リソースの使用率を低下させるための冗長な ID 呼び出しが削除されました</span><span class="sxs-lookup"><span data-stu-id="ffbd9-564">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="ffbd9-565">リソースの使用率を低下させて、共同編集状態の検出機能を改善します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-565">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="ffbd9-566">エラーを検出する機能が改善され、同期環境の品質が向上しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-566">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="ffbd9-567">Outlook</span><span class="sxs-lookup"><span data-stu-id="ffbd9-567">Outlook</span></span>

- <span data-ttu-id="ffbd9-568">一部のテナントで Outlook を起動したときに重大なパフォーマンスの問題が発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-568">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="ffbd9-569">Skype</span><span class="sxs-lookup"><span data-stu-id="ffbd9-569">Skype</span></span>

- <span data-ttu-id="ffbd9-570">数日間稼働した後に、32 ビット版の Skype for Business クライアントで画面共有を開始できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-570">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ffbd9-571">Office スイート</span><span class="sxs-lookup"><span data-stu-id="ffbd9-571">Office Suite</span></span>

- <span data-ttu-id="ffbd9-572">グループ ポリシーを介して自動保存が無効にされた場合に、ユーザーが [利用可能な更新] をクリックするまで一部のドキュメントで最新のサーバー コンテンツが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-572">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-august-11"></a><span data-ttu-id="ffbd9-574">バージョン 1908: 8 月 11 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-574">Version 1908: August 11</span></span>
<span data-ttu-id="ffbd9-575">*バージョン 1908 (ビルド 11929.20934)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-575">*Version 1908 (Build 11929.20934)*</span></span>

<span data-ttu-id="ffbd9-576">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-576">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1902-august-11"></a><span data-ttu-id="ffbd9-577">バージョン 1902: 8 月 11 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-577">Version 1902: August 11</span></span>
<span data-ttu-id="ffbd9-578">*バージョン 1902 (ビルド 11328.20644)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-578">*Version 1902 (Build 11328.20644)*</span></span>

<span data-ttu-id="ffbd9-579">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-579">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-july-14"></a><span data-ttu-id="ffbd9-582">バージョン 2002: 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-582">Version 2002: July 14</span></span>
<span data-ttu-id="ffbd9-583">*バージョン 2002 (ビルド 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-583">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="ffbd9-584">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-584">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="ffbd9-586">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="ffbd9-586">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="ffbd9-587">Access</span><span class="sxs-lookup"><span data-stu-id="ffbd9-587">Access</span></span>

- <span data-ttu-id="ffbd9-588">**リンク テーブルをすばやく見つける:** 新しい検索ボックスを使用すると、リンク テーブルを簡単に見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-588">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="ffbd9-589">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-589">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="ffbd9-590">Excel</span><span class="sxs-lookup"><span data-stu-id="ffbd9-590">Excel</span></span>

- <span data-ttu-id="ffbd9-591">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-591">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="ffbd9-592">**データ ビジュアライザー アドイン:** Excel から Visio フローチャートをすばやく作成します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-592">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="ffbd9-593">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-593">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="ffbd9-594">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-594">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="ffbd9-595">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-595">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="ffbd9-596">[ブログの投稿](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-596">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="ffbd9-597">**自分の気分を表現するアイコンの追加:** 300 個以上の新しいアイコンが追加されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-597">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="ffbd9-598">[挿入]、[アイコン] の順に検索してください。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-598">Find them at Insert > Icons.</span></span> [<span data-ttu-id="ffbd9-599">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-599">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="ffbd9-600">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-600">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="ffbd9-601">[ブログの投稿](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-601">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="ffbd9-602">**残っている作業に集中する:** [解決] を選択して、コメントを折りたたみ、開いているアイテムを目立たせます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-602">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="ffbd9-603">**複数の値を返す式を入力する:** 複数の値を返す式を素早く入力できるようになりました。隣接するセルに自動的に入力されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-603">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="ffbd9-604">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-604">Learn more</span></span>](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br /><span data-ttu-id="ffbd9-605">[ブログの投稿](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-605">See details in [blog post](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span></span>

- <span data-ttu-id="ffbd9-606">**ブラウザーへのバウンスは不要** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-606">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="ffbd9-607">**あらましを描く:** ブック内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-607">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="ffbd9-608">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-608">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="ffbd9-609">[ブログの投稿](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-609">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="ffbd9-610">**探しているものを見つける:** コマンド、ユーザー、ファイル、写真、Web の記事などを検索できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-610">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="ffbd9-611">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-611">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="ffbd9-612">**6 つの強力な機能:** スプレッドシートを強化する 6 つの新しい関数が追加されました。FILTER、SORT、SORTBY、UNIQUE、SEQUENCE、RANDARRAY です。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-612">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span> [<span data-ttu-id="ffbd9-613">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-613">Learn more</span></span>](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- <span data-ttu-id="ffbd9-614">**左を見て、右を見て... XLOOKUP をご利用いただけます!** XLOOKUP を使えば、表や範囲内で必要なものは何でも見つけられます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-614">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="ffbd9-615">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-615">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br /><span data-ttu-id="ffbd9-616">[ブログの投稿](https://blog-insider.office.com/2019/08/29/announcing-xlookup/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-616">See details in [blog post](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span></span>

- <span data-ttu-id="ffbd9-617">**大きなブックを使いこなす:** セル、数式、グラフ、テーブル...ブックの統計情報を使用して、ブックのスナップショットを取得します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-617">**Tame your big workbook:** Cells, formulas, charts, tables... get a snapshot of your workbook with Workbook Statistics.</span></span>

- <span data-ttu-id="ffbd9-618">**すぐに読んで返信する:** ブックを開かずに、メールからコメントやメンションに直接返信します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-618">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="ffbd9-619">**\@メンションを使用してユーザーの注意を引く:** コメントで @メンションを使うと、仕事仲間による入力が必要な場合にそのユーザーに知らせることができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-619">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="ffbd9-620">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-620">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="outlook"></a><span data-ttu-id="ffbd9-621">Outlook</span><span class="sxs-lookup"><span data-stu-id="ffbd9-621">Outlook</span></span>

- <span data-ttu-id="ffbd9-622">**より多くのメッセージを画面に収める:** [表示] > [より狭い文字間隔を使用] の順に選択し、メッセージの間隔を調整します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-622">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="ffbd9-623">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-623">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="ffbd9-624">**自分の気分を表現するアイコンの追加:** 300 個以上の新しいアイコンが追加されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-624">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="ffbd9-625">[挿入]、[アイコン] の順に検索してください。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-625">Find them at Insert > Icons.</span></span> [<span data-ttu-id="ffbd9-626">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-626">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="ffbd9-627">**自分で描いて表現しましょう:** 画像の上に走り書きするか、描画キャンバスを追加して、インクを用いて自分の考えを送信します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-627">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="ffbd9-628">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-628">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="ffbd9-629">**場所の候補を取得する:** 予定や会議をスケジュールするときに、[場所] に入力すると、会議室、住所、およびその他の最新の場所が提示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-629">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="ffbd9-630">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-630">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)<br /><span data-ttu-id="ffbd9-631">[ブログの投稿](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-631">See details in [blog post](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span></span>

- <span data-ttu-id="ffbd9-632">**攻撃に対する高度な保護:** Office 365 Advanced Threat Protection を用いると、メールの件名、添付メッセージ、署名されたメッセージ、ネットワーク パスなどの範囲内のハイパーリンクを利用した攻撃から保護されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-632">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="ffbd9-633">**テナント管理者によって定義されたアクセス許可を使用して、Outlook の [リンクの挿入] メニューでリンクを挿入する:** Outlook で最近使用されたリンクの挿入 (MRU) のリンクでは、既にそれに対するアクセス許可を持つユーザーのみに動作したリンクが挿入されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-633">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="ffbd9-634">これは、ドキュメントへのアクセス権の付与を求めるユーザー間でのメールの行き来をしばしば引き起こします。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-634">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="ffbd9-635">このエクスペリエンスが更新されましたので、テナント管理者によって設定される既定のアクセス許可を使用し、リンクを挿入できるようになりました。MSIT の場合、これは「組織は編集可」なので、この方法で共有されるリンクを受信するすべての内部ユーザーもアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-635">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="ffbd9-636">**異なる明るさでメッセージを表示する:** [太陽] または [月] のボタンを使用して、閲覧ウィンドウの明るい背景と暗い背景を切り替えます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-636">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="ffbd9-637">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-637">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="ffbd9-638">**フィッシング メールの見分けが簡単に:** スパムとフィッシングのメッセージの外観が他とは異なるので、簡単に見分け、受信トレイから削除できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-638">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="ffbd9-p159">**すべての暗号化オプションを 1 か所に集約:** [オプション] > [暗号化] の順に移動するだけで、電子メール メッセージを保護する方法を選択できます。[詳細情報](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-p159">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="ffbd9-641">**スペルチェックの問題や入力ミスで検索する:** スペルが一致しない場合でも何を検索しているか Outlook が探します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-641">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="ffbd9-642">**Outlook に LinkedIn ネットワークを接続する:** LinkedIn アカウントを Microsoft アカウントに安全に接続して、LinkedIn プロファイルからの情報を [連絡先カード] に直接表示できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-642">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="ffbd9-643">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-643">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="ffbd9-644">**検索結果で関連メッセージを確認する:** Outlook では検索条件を分析し、最も関連性の高いメール メッセージを検索結果の上部に表示します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-644">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="ffbd9-645">また、[上位の結果] セクションには、すべての結果が日付順に表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-645">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="ffbd9-646">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-646">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

### <a name="powerpoint"></a><span data-ttu-id="ffbd9-647">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ffbd9-647">PowerPoint</span></span>

- <span data-ttu-id="ffbd9-648">**手書きの数式の自動書式設定:** 手書きの数式を標準の文字に変換することができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-648">**You compute, we format:** We change hand-drawn math expressions into standard characters.</span></span> <span data-ttu-id="ffbd9-649">変換を開始するには、[インクから数式] を選択して、手書きのメモを選択します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-649">Just choose Ink to Math and select your handwritten notes to get started.</span></span> [<span data-ttu-id="ffbd9-650">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-650">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="ffbd9-651">**探しているものを見つける:**[検索] ボックスを使用して、テキスト、コマンド、ヘルプなどを探します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-651">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="ffbd9-652">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-652">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="ffbd9-653">**インクで素晴らしいスライドを作成する:** インクを標準的な図形やテキストに変換してから、PowerPoint デザイナーの洗練されたスライドのデザイン アイデアを活用できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-653">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="ffbd9-654">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-654">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="ffbd9-655">**あらましを描く:** プレゼンテーション内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-655">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="ffbd9-656">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-656">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="ffbd9-657">[ブログの投稿](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-657">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="ffbd9-658">**インクを瞬時に再生:** スライドで手描き入力する場合は、スライド ショー中にアニメーションの再生を適用して、インクの実際の描画が再生されるようにします。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-658">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="ffbd9-659">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-659">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)<br /><span data-ttu-id="ffbd9-660">[ブログの投稿](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-660">See details in [blog post](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span></span>

- <span data-ttu-id="ffbd9-661">**より安全なビデオ エクスペリエンス:** セキュリティの強化は、より安全なオンライン ビデオ エクスペリエンスを意味します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-661">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="ffbd9-662">**図を SVG として保存する:** グラフ、図形、その他の図を、サイズ変更しても画質が低下しないスケーラブル ベクター グラフィックとして保存できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-662">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="ffbd9-663">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-663">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="ffbd9-664">**配布資料にスライド番号を印刷する:** スライド番号は配布資料に自動的に含まれます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-664">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="ffbd9-665">それらをオンのままにするか、オフにするか、選択します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-665">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="ffbd9-666">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-666">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="ffbd9-667">**欠落しているスライド タイトルを見つけて修正する:** スライド タイトルは、ピッチにパンチを加え、すべてのユーザーがスライドにアクセスできるようにします。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-667">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="ffbd9-668">アクセシビリティ ​​チェックは、タイトルがない場所を表示します。これにより、タイトルを簡単に追加できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-668">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="ffbd9-669">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-669">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="ffbd9-670">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-670">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="ffbd9-671">[ブログの投稿](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-671">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="ffbd9-672">**自分の気分を表現するアイコンの追加:** 300 個以上の新しいアイコンが追加されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-672">**More icons to match your mood:** We've added more than 300 new icons.</span></span> <span data-ttu-id="ffbd9-673">[挿入]、[アイコン] の順に検索してください。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-673">Find them at Insert > Icons.</span></span> [<span data-ttu-id="ffbd9-674">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-674">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="ffbd9-675">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-675">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span><br /><span data-ttu-id="ffbd9-676">[ブログの投稿](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-676">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="ffbd9-677">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルのリストからドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-677">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="ffbd9-678">**PowerPoint におけるリアルタイム コラボレーションが高速に:** PowerPoint でリアルタイム コラボレーションを高速で行えます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-678">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="ffbd9-679">**ブラウザーへのバウンスは不要:** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-679">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="ffbd9-680">**新しい文書校正ツール:** 記述する内容についてストレスを感じる必要はありません。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-680">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="ffbd9-681">PowerPoint で、文法や書き方の推奨事項が提示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-681">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="ffbd9-682">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-682">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="ffbd9-683">**ライブ キャプションと字幕:** 発表者の言葉が、キャプションまたは選択した言語での字幕として自動的に画面に表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-683">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="ffbd9-684">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-684">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="ffbd9-685">**プレゼンテーションの最適化:** アクセシビリティ チェックを使用すると、スクリーン リーダーを考慮に入れて、スライド上のオブジェクトを配置することができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-685">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span><br /><span data-ttu-id="ffbd9-686">[ブログの投稿](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-686">See details in [blog post](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span></span>

- <span data-ttu-id="ffbd9-687">**再利用しませんか?:** 作成した、または他のユーザーと共有しているスライドを再利用して時間を節約します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-687">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="ffbd9-688">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-688">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

### <a name="visio"></a><span data-ttu-id="ffbd9-689">Visio</span><span class="sxs-lookup"><span data-stu-id="ffbd9-689">Visio</span></span>

- <span data-ttu-id="ffbd9-690">**Excel で洗練された Visio 図を作成する:** ワークシートにデータを入力して、フロー チャートまたは組織図を作成します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-690">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="ffbd9-691">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-691">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="ffbd9-692">**犯行現場に戻る:** [犯罪現場] 調査テンプレートで新しい [証拠]、[室内]、および [屋外] のステンシルを使用して、犯罪現場を詳細に再現します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-692">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

### <a name="word"></a><span data-ttu-id="ffbd9-693">Word</span><span class="sxs-lookup"><span data-stu-id="ffbd9-693">Word</span></span>

- <span data-ttu-id="ffbd9-694">**より安全なビデオ エクスペリエンス:** セキュリティの強化は、より安全なオンライン ビデオ エクスペリエンスを意味します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-694">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="ffbd9-695">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-695">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="ffbd9-696">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-696">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="ffbd9-697">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-697">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="ffbd9-698">[ブログの投稿](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-698">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="ffbd9-699">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルのリストからドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-699">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="ffbd9-700">**自分の気分を表現するアイコンの追加:** 300 個以上の新しいアイコンが追加されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-700">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="ffbd9-701">[挿入]、[アイコン] の順に検索してください。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-701">Find them at Insert > Icons.</span></span> [<span data-ttu-id="ffbd9-702">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-702">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)<br /><span data-ttu-id="ffbd9-703">[ブログの投稿](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-703">See details in [blog post](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span></span>

- <span data-ttu-id="ffbd9-704">**精度による消去:** 手描き入力の小さな不備を修正するのに、2 つのサイズの消しゴムから選択できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-704">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="ffbd9-705">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-705">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="ffbd9-706">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-706">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="ffbd9-707">[ブログの投稿](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-707">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="ffbd9-708">**あらましを描く:** ドキュメント内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-708">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="ffbd9-709">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-709">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="ffbd9-710">[ブログの投稿](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="ffbd9-710">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="ffbd9-711">**探しているものを見つける:**[検索] ボックスを使用して、テキスト、コマンド、ヘルプなどを探します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-711">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="ffbd9-712">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-712">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="ffbd9-713">**ブラウザーへのバウンスは不要** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-713">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="ffbd9-714">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-714">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="ffbd9-715">**Editor for Resume が LinkedIn 履歴書アシスタントに参加する:** Editor for Resume では履歴書に特化した文法とスタイルのチェックを選択できます。この機能は、より正確かつ専門的に作成するの役立ちます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-715">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="ffbd9-716">**他のユーザーがすばやく変更を確認する:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-716">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="ffbd9-717">**3D オブジェクトのマージによって引き起こされるドキュメント破損の問題を修正しました。:** 3D オブジェクトのマージによって引き起こされるドキュメント破損の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-717">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="ffbd9-718">**共同編集の改善:** 変更を追跡したドキュメントで共同編集を行う際の Word のパフォーマンスが改善されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-718">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="ffbd9-719">**共同編集の改善:** 共同編集時の信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-719">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="ffbd9-720">**鮮やかな色で共同作業する:** コメントや変更内容のカラー コードが共同作成者によって指定され、共同作成者のうちのだれによって行われたかが簡単にわかります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-720">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="ffbd9-721">**マクロ有効文書を共同作業で編集する:** 文書ファイルを OneDrive for Business に保存し、リアルタイムで共同作成者は編集できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-721">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ffbd9-722">Office スイート</span><span class="sxs-lookup"><span data-stu-id="ffbd9-722">Office Suite</span></span>

- <span data-ttu-id="ffbd9-723">**手書きのインクを図形やテキスト、または Office 365 の PowerPoint での数式に変換する:** フリーフォームのインクを Office の図形、テキスト、数式に数ストロークで変換します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-723">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="ffbd9-724">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-724">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-727">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-727">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ffbd9-728">Access</span><span class="sxs-lookup"><span data-stu-id="ffbd9-728">Access</span></span>

- <span data-ttu-id="ffbd9-729">この更新プログラムでは、ADODB を使用する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-729">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="ffbd9-730">VB コードのれコーター オブジェクトがエラーを誤って報告することがあります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-730">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="ffbd9-731">Access テンプレートは、データベース内の添付ファイル列のエラーを発生させることがなくなりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-731">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="ffbd9-732">テンプレートのインスタンス化後に、データベースに添付ファイル フィールドを追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-732">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="ffbd9-733">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-733">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="ffbd9-734">この更新プログラムにより、更新クエリが実行されるか、SQL で UPDATE ステートメントが使用されるときに "クエリは破損しています" というエラーを発生させる場合のある Microsoft Access の問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-734">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="ffbd9-735">Excel</span><span class="sxs-lookup"><span data-stu-id="ffbd9-735">Excel</span></span>

- <span data-ttu-id="ffbd9-736">ローカルの OneDrive フォルダーで使用できるファイルの読み込み速度を向上します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-736">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="ffbd9-737">CUBEVALUE 関数が間違った結果を返すことがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-737">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="ffbd9-738">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-738">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="ffbd9-739">Word または PowerPoint に埋め込まれたブックをもう一度開くと、場合によっては Excel がクラッシュする可能性があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-739">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="ffbd9-740">コンテキスト メニューのコメント コマンドが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-740">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="ffbd9-741">ピボット グラフの右クリック メニューを修正して、[詳細の表示] オプションを有効にしました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-741">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="ffbd9-742">ブックが開かれていない状態で最近使用したファイルを検索するときに、クラッシュを発生させる原因となっていた可能性がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-742">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="ffbd9-743">同じブック内でブックマークされたハイパーリンクをクリックすると、ブックが非表示になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-743">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="ffbd9-744">CSV ファイルとして保存する場合、Excel はすべての列を 1 つの列にマージする場合があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-744">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="ffbd9-745">保護されたシートの範囲で Range.ClearContents を使用すると、予想よりも時間がかかる場合があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-745">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="ffbd9-746">[印刷プレビュー] に表示されるときのフォーム コントロール内のテキストの拡大縮小に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-746">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="ffbd9-747">リボンを操作する VBA マクロは、ScreenUpdating が True に設定されていると予期せず実行される場合があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-747">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="ffbd9-748">ピボットテーブルを含むシートをコピーした後、Excel がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-748">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="ffbd9-749">状況によっては、CSV ファイルを開くのに予想より時間がかかっていました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-749">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="ffbd9-750">Excel では、異なる拡大レベルでブックを切り替えるとクラッシュすることがあります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-750">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="ffbd9-751">値の範囲への入力に予想より時間がかかる VBA の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-751">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="ffbd9-752">色でフィルター処理された列からコピーしたデータは、正しく貼り付けられない場合があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-752">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="ffbd9-753">特に非表示のウィンドウで、多数のその他のブックを参照しながらブックを開くと、予想よりも時間がかかります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-753">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="ffbd9-754">ソース ブックが閉じていると、外部リンクが塗りつぶし (下方向に塗りつぶし、全体に塗りつぶしなど) 時に更新されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-754">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is& closed.</span></span>

- <span data-ttu-id="ffbd9-755">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-755">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="ffbd9-756">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-756">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="ffbd9-757">グラフの軸の "Value Crosses At" プロパティが、ファイルを保存してもう一度開くときに予期せず変更されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-757">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="ffbd9-758">SharePoint/OneDrive に保存すると、ユーザー設定のリボンタブの CustomUI XML が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-758">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="ffbd9-759">結合されたセルを持つ列を削除するときのパフォーマンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-759">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="ffbd9-760">[印刷] ダイアログ ボックスのプリンターのリストにプリンター名が繰り返されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-760">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="ffbd9-761">ファイル パスが長すぎる場合にファイルをもう一度開くと、外部リンクが機能しなくなった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-761">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="ffbd9-762">印刷時にフォーム コントロールのチェックボックスが拡大縮小されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-762">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="ffbd9-763">従来の "共有ブック" モードを使用して、ブックの新しいシートに変更を一覧表示しようとすると、クラッシュが発生する場合がありました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-763">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="ffbd9-764">フィルター処理されたリストに列を挿入すると、通常よりも時間がかかっていました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-764">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="ffbd9-765">コピー & ペーストされたグラフのリンクの一部で、ユニバーサル アドレスではなくマップされたドライブ アドレスが使用されていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-765">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="ffbd9-766">アドインが、ユーザーが指定した順番ではなくアルファベット順に読み込まれていたため、「このブックは現在別のユーザーに参照されており、閉じることができません」というエラー メッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-766">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="ffbd9-767">既に開いているブック内の場所へのハイパーリンクをクリックすると、ブックが非表示になることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-767">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="ffbd9-768">特に非表示のウィンドウで、多数のその他のブックを参照しながらブックを開くと、予想よりも時間がかかります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-768">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="ffbd9-769">VBA の Application.Evaluate が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-769">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="ffbd9-770">一部のユーザーが埋め込みオブジェクトとリンク オブジェクト (OLE) で経験する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-770">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="ffbd9-771">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-771">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="ffbd9-772">この更新によって、数式バーに予期したのとは異なるフォントでテキストが表示される原因となっていた問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-772">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="ffbd9-773">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-773">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="ffbd9-774">スクロール後にセルを選択すると間違ったセルが選択されることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-774">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="ffbd9-775">非表示の名前付き範囲にアクセスすると、ユーザーにエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-775">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="ffbd9-776">信頼されていないネットワーク共有から保護されたファイルを編集する際に、Excel にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-776">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="ffbd9-777">一部のローカライズにおいて、[Text to Column] 機能が失敗することがあります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-777">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="ffbd9-778">テンプレートからグラフを作成するときに発生するパフォーマンスの問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-778">Addresses a performance issue when creating charts from templates.</span></span>

- <span data-ttu-id="ffbd9-779">はみ出している列挙が含まれるセルで区切り位置を指定するとクラッシュが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-779">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="ffbd9-780">Range.Value と Range.Value2 (VBA) を使用すると、数式は動的配列として入力されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-780">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

- <span data-ttu-id="ffbd9-781">数式を開始する @ 記号が暗黙的な論理積演算子と見なされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-781">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

- <span data-ttu-id="ffbd9-782">定義された名前を持つ複数の数式を含むワークシートがファイルを保存するときに時間がかかる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-782">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="ffbd9-783">この変更は、ソフトウェア レンダリングを活用することにより、特定の Intel グラフィック ドライバーの問題を回避します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-783">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="ffbd9-784">署名の名前を変更したときにクラッシュする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-784">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="onenote"></a><span data-ttu-id="ffbd9-785">OneNote</span><span class="sxs-lookup"><span data-stu-id="ffbd9-785">OneNote</span></span>

- <span data-ttu-id="ffbd9-786">OneNote 2016 で同期頻度を一時的に調整することで、同期およびサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-786">Improve sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="ffbd9-787">ユーザーが OneNote 2016 のページに移動するまで、オンライン ノートブックの埋め込みファイルおよび画像のダウンロードを一時的に遅らせることで、同期およびサービスの安定性を改善します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-787">Improve sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="ffbd9-788">OneNote 2016 のごみ箱を一時的に無効にすることにより、同期およびサービスの安定性を改善します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-788">Improve sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="ffbd9-789">ユーザーが、通常はごみ箱に送られるデータを削除しようとすると、データを保持するか、完全に削除するかを確認するメッセージが表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-789">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="ffbd9-790">OneNote 2016 のバージョン履歴ページの数と同期頻度を一時的に減らすことで、同期およびサービスの安定性を改善します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-790">Improve sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="ffbd9-791">同期およびサービスの安定性を改善するために、OneNote ユーザー エクスペリエンスで実行されている一時的な手段についての詳細情報をユーザーが学べるようにする通知を表示します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-791">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="ffbd9-792">OneNote 2016 に 50 MB へ埋め込まれた新しい添付ファイルの最大許容サイズが一時的に減少することにより、同期とサービスの安定性を改善します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-792">Improve sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="ffbd9-793">この制限を超えるファイルの場合、ユーザーは OneDrive にファイルをアップロードして、OneNote にリンクを挿入することができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-793">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="ffbd9-794">OneNote 2016 でアプリ内動画のレコーディングを一時的に無効にすることで、同期およびサービスの安定性を改善します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-794">Improve sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="ffbd9-795">ローカルのノートブックはこの影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-795">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="ffbd9-796">同期およびサービスの安定性を改善するために、OneNote ユーザー エクスペリエンスで実行されている一時的な手段についての詳細情報をユーザーが学べるようにする通知をローカライズします。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-796">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="ffbd9-797">Outlook</span><span class="sxs-lookup"><span data-stu-id="ffbd9-797">Outlook</span></span>

- <span data-ttu-id="ffbd9-798">解像度の異なる複数のモニターを使用している場合に、IME(Input Method Editor)ウィンドウで入力されたテキストが重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-798">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="ffbd9-799">Outlook でユーザーが不定期に遭遇するクラッシュの原因になる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-799">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="ffbd9-800">これにより、Python による添付ファイルもブロックされるよう、Outlook の添付ファイルのブロック ロジックが更新されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-800">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="ffbd9-801">Web アドインがデジタル著作権管理 (DRM) メッセージにアクセスする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-801">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="ffbd9-802">タイムゾーンの定義を変更するときに、定期的な予定や会議が誤った時間に表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-802">Addresses an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="ffbd9-803">2019 年に ブラジル タイム ゾーンを使用している場合、2020 年の定期的な会議や予定が間違った時間帯に表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-803">When using the Brazilia time zone in the year 2019, recurring meetings and appointments are displayed in the wrong timeslot for the year 2020.</span></span> <span data-ttu-id="ffbd9-804">この変更は、ブラジル タイム ゾーンに設定されているクライアントまたは同タイム ゾーンで設定された会議や予定に影響を与えます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-804">This change is relevant for clients set in the Brazilia time zone or for meetings and appointments set in that time zone.</span></span><br><br><span data-ttu-id="ffbd9-805">この変更により、Outlook では、使用する特定のタイムゾーン設定を上書きできます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-805">This change allows Outlook to override certain time zone settings used by Outlook.</span></span> <span data-ttu-id="ffbd9-806">タイムゾーンの上書きを起動するには、現在のユーザーのレジストリキーを設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-806">In order to invoke a time zone override you must set a registry key for the current user.</span></span> <span data-ttu-id="ffbd9-807">レジストリキーの名前は、タイムゾーンの内部名と一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-807">The registry key name must match the internal name of the time zone.</span></span> <span data-ttu-id="ffbd9-808">この値は、有効な年の代わりに、使用されるタイムゾーン ルールの年を示します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-808">The value indicates the time zone rule's year to be used in place of the effective year.</span></span> <span data-ttu-id="ffbd9-809">たとえば、次のレジストリキーの上書き値は、2020 年のブラジル タイムゾーン ルールを有効なルールとして使用します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-809">For example, the following registry key override value will use the Brazilia time zone rule for the year 2020 as the effective rule.</span></span> <span data-ttu-id="ffbd9-810">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-810">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span></span> <span data-ttu-id="ffbd9-811">南アメリカ標準時 "=dword:000007e4。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-811">South America Standard Time"=dword:000007e4.</span></span>

- <span data-ttu-id="ffbd9-812">会議の場所フィールドが予期せず変更される原因となる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-812">Addresses an issue that caused users to see the location field in meetings change unexpectedly.</span></span>

- <span data-ttu-id="ffbd9-813">会議の [場所] フィールドが予期せず更新される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-813">Addresses an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="ffbd9-814">会議をクリアした後、会議の場所が予期せずに会議に追加される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-814">Addresses an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="ffbd9-815">会議の [場所] フィールドにあるコンマがセミコロンになる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-815">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="ffbd9-816">ネイティブの Teams クライアントを介して Teams 会議に直接参加できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-816">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="ffbd9-817">Exchange 2010 サーバー上にメールボックスを持つユーザーが、予定表の項目に添付ファイルを追加するときに生じる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-817">Addresses an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="ffbd9-818">ユーザーがデジタル署名されたメッセージに返信するときに生じる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-818">Addresses an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="ffbd9-819">ユーザーが定期的な予定表の一部のインスタンスを開けない原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-819">Addresses an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="ffbd9-820">一部のシナリオで、グループ ヘッダーが予期せず拡張される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-820">Addresses an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="ffbd9-821">フォルダー ウィンドウの幅が予期せず変更される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-821">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="ffbd9-822">M365 Business Plus プランのサービスを利用していたユーザーがデータ損失防止の保護ポリシー ヒントを有効にできない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-822">Addresses an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="ffbd9-823">キーボード ショートカットを使用してメールボックス フォルダーを操作すると、ユーザーに顕著な遅延が発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-823">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="ffbd9-824">複数のウィンドウで同じアイテムを表示するとクラッシュする場合がある問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-824">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="ffbd9-825">ユーザーが Outlook ルールを更新すると、"このコンピューターのルールは、Microsoft Exchange のルールと異なります" と表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-825">Addresses an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="ffbd9-826">非常に長い Outlook セッションでメモリ リークを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-826">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="ffbd9-827">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-827">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="ffbd9-828">ユーザーが [ルール] ダイアログを開くと、"このコンピューターのルールは、Microsoft Exchange のルールと異なります" というメッセージが表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-828">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="ffbd9-829">フラグ付きアイテムの強調表示を無効にするオプションが一部のシナリオで無視される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-829">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="ffbd9-830">[アクセシビリティ チェック] ペインを閉じた後に "S" キーを押すと、メールが予期せず送信されたようにユーザーに表示される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-830">Addresses an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="ffbd9-831">署名の名前を変更したときにクラッシュする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-831">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="ffbd9-832">ユーザーがアカウントのセットアップをキャンセルするときにクラッシュする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-832">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="ffbd9-833">同期のスライダーが小さい設定に設定されている場合でも、Outlook で予期せずすべてのメールが同期される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-833">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="ffbd9-834">黒のテーマを持つユーザーが [差出人] ドロップダウンを表示すると、白色の背景に白いテキストが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-834">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="ffbd9-835">ユーザーがプロフィールの作成中にクラッシュを発生させる原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-835">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="ffbd9-836">アカウント作成コンテキストからサポートに連絡しようとすると、ユーザーに [OK] ボタンのある空のメッセージ ボックスが表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-836">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="ffbd9-837">アカウント作成コンテキストからサポートに連絡しようとすると、ユーザーに [OK] ボタンのある空のメッセージ ボックスが表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-837">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="ffbd9-838">サードパーティ製アプリケーションがメールを送信できない原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-838">Addresses an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="ffbd9-839">メール メッセージからカテゴリが消えることがあるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-839">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="ffbd9-840">サーバー オペレーティング システムの Outlook ユーザーに "ウイルス対策ステータス: 無効" のエラーを表示する原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-840">Addresses an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="ffbd9-841">このバージョンの Windows はウイルス検出をサポートしていますが、ウイルス対策を適切に構成してもウイルス対策ソフトウェアが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-841">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

- <span data-ttu-id="ffbd9-842">共有メールボックスに対して、異なるコンピューター上の別のフォルダー階層が代理人に表示されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-842">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="ffbd9-843">管理者のカレンダー上で既存のカレンダーの予定を編集するときに代理人がエラーを受け取る問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-843">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="ffbd9-844">間違ったブラウザー エミュレーション設定でユーザーが Gmail の認証プロンプトを完了できなくなるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-844">Addresses an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="ffbd9-845">[共有フォルダーのダウンロード] がチェックされていない場合、共有の予定表の会議の [返信オプション] に [転送を許可する] オプションが表示されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-845">Addresses an issue that caused the " Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="ffbd9-846">ユーザーが Windows Update の後に .msg および .oft ファイルを開こうとするとクラッシュが起きるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-846">Addresses an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="ffbd9-847">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-847">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="ffbd9-848">特定の検索結果を選択すると、ユーザーがクラッシュする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-848">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="ffbd9-849">[添付ファイル ​​ツール] に [クラウドに保存] ボタンが表示されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-849">Addresses an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="ffbd9-850">この変更により、メッセージ ヘッダーに複数行の件名を表示できる機能が復元されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-850">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="ffbd9-851">2 つのアドインが同じリボン グループにボタンを追加するときにユーザーにクラッシュが発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-851">Addresses an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="ffbd9-852">テナントの既定のアクセス許可が "全員" として構成されている場合に、適切なテナントの既定のアクセス許可を使用して、リンクがメールに追加されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-852">Addresses an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as "anyone".</span></span>

- <span data-ttu-id="ffbd9-853">ユーザーが個人用配布リストにメールを送信できなくなった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-853">Addresses an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="ffbd9-854">大きな HTML メッセージを転送するとき、ユーザーにメッセージ本文の全体が表示されないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-854">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="ffbd9-855">SMIME アルゴリズムの選択に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-855">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="ffbd9-856">WebDAV の場所にファイルを保存できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-856">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="ffbd9-857">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカル コンピューターに保存できない原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-857">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="ffbd9-858">件名を編集した後、NDR メッセージの本文が Unicode から ASCII に変更される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-858">Addresses an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="ffbd9-859">ユーザーが Outlook プロセスでメモリ リークを観測する原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-859">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="ffbd9-860">状況によっては、表示された SMTP アドレスと一致しないアドレスに送信されたメールがユーザーに表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-860">Addresses an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="ffbd9-861">検索ボックスが高 DPI モードで不適切に表示される原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-861">Addresses an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="ffbd9-862">ユーザーがクラウド設定を取得する際に Outlook がフリーズする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-862">Addresses an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="ffbd9-863">検索に関するフィードバックのエクスペリエンスで終了する原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-863">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="ffbd9-864">Outlook でユーザーが不定期に遭遇するクラッシュの原因になる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-864">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="ffbd9-865">署名の名前を変更したときにクラッシュする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-865">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="ffbd9-866">ユーザーがプロフィールの作成中にクラッシュを発生させる原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-866">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="ffbd9-867">Outlook でユーザーが不定期に遭遇するクラッシュの原因になる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-867">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ffbd9-868">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ffbd9-868">PowerPoint</span></span>

- <span data-ttu-id="ffbd9-869">従来の PPT コメントでコンテキスト メニューを使用するときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-869">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

- <span data-ttu-id="ffbd9-870">コピーと貼り付けのシナリオを改善しました。PowerPoint スライドでの図形のコピーと、ループ内の他のスライドへの貼り付けが例外で失敗する場合があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-870">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="ffbd9-871">問題の修正により、改善済みのコメントが入ったファイルのコピーを開くユーザーに正しいメッセージを送れるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-871">Fixes an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="project"></a><span data-ttu-id="ffbd9-872">Project</span><span class="sxs-lookup"><span data-stu-id="ffbd9-872">Project</span></span>

- <span data-ttu-id="ffbd9-873">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-873">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="ffbd9-874">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-874">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="ffbd9-875">[無効化] ボタンを介してタスクが非アクティブ化/アクティブ化された場合に、ProjectBeforeTaskChange イベントが検出しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-875">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="ffbd9-876">以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-876">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="ffbd9-877">読み取り専用のプロジェクトを開いたときに複数のメッセージを取得する可能性があるという問題を特定しました</span><span class="sxs-lookup"><span data-stu-id="ffbd9-877">Identified an issue where users could get several messages when opening a read-only project</span></span>

- <span data-ttu-id="ffbd9-878">作業時間固定タイプの達成率 100% のタスクで、達成率が誤って 100% 未満に計算される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-878">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="ffbd9-879">Word</span><span class="sxs-lookup"><span data-stu-id="ffbd9-879">Word</span></span>

- <span data-ttu-id="ffbd9-880">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-880">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="ffbd9-881">クイック印刷を使用して印刷した後に編集しようとしたときに、ドキュメント内の単語の配置が乱れてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-881">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="ffbd9-882">表内のテキストに合わせる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-882">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="ffbd9-883">水平線の挿入が短くなく、中央に配置されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-883">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>

- <span data-ttu-id="ffbd9-884">文書パーツ オーガナイザーに "スタイル、文書パーツを変更しました" という無効なアラートが表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-884">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

- <span data-ttu-id="ffbd9-885">ポリシー FileBlick\Word2007Files を有効にしたときの共同編集に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-885">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="ffbd9-886">名前が変更されたルックアップ フィールドを追加するときに Word QuickPart が機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-886">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

- <span data-ttu-id="ffbd9-887">2 つのドキュメントを 1 つのドキュメントに結合するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-887">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="ffbd9-888">編集用に保護されたドキュメントの比較機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-888">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="ffbd9-889">この更新プログラムでは、Microsoft Word で、ラベル ポリシーにヘッダーやフッターまたは透かしが適用されている場合にラベルを変更または削除すると、255 文字を超える文字の挿入されたテキストが識別および削除できなかった問題が修正されています。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-889">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ffbd9-890">Office スイート</span><span class="sxs-lookup"><span data-stu-id="ffbd9-890">Office Suite</span></span>

- <span data-ttu-id="ffbd9-891">大規模な PowerPoint ファイルの共同編集中に、ユーザーがネットワークと CPU の使用率が過剰になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-891">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="ffbd9-892">これは、ファイルがクライアントにキャッシュされるときに Project アプリがネットワークをブロックしないようにするための修正プログラムです。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-892">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>


- <span data-ttu-id="ffbd9-893">この問題を解決するため、Backstage のチャネル名を 2020 年 1 月のフォークにある新しいチャネル名に更新しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-893">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="ffbd9-894">この問題は修正されましたが、今後、デバイスがポリシー管理されている場合、DMS の対象ユーザー API は呼び出されません。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-894">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="ffbd9-895">単一のトランザクションでアプリを追加および削除したときに、削除が不完全になるという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-895">We have resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="ffbd9-896">ODT と GPO の更新期限設定で、相対期限の設定後、初回のみしか機能しないバスが修正されました。修正により、2 回目以降の更新プログラムで相対期限を使用きるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-896">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="ffbd9-897">Office の更新プログラムが、意図したソース (ローカル共有、ネットワーク共有、構成マネージャーで提供される場所など) からではなく、予期せずに Office CDN からファイルをダウンロードする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-897">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="ffbd9-898">ODT と GPO の更新期限設定で、相対期限の設定後、初回のみしか機能しないバスが修正されました。修正により、2 回目以降の更新プログラムで相対期限を使用きるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-898">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="ffbd9-899">以前の AppV51 の回帰を修正するために、新しい AppV51 drop をバックポートしました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-899">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="ffbd9-900">ログ記録して続行するのではなく、内部操作により失敗時に例外がスローされていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-900">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="ffbd9-901">影響を受けるユーザーは、更新プログラムの受信をブロックされなくなります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-901">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="ffbd9-902">チームでは、半期エンタープライズ プレビューで Office CDN ドメインのテレメトリを報告するためのクライアント サポートを追加しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-902">Our team has added client support for reporting telemetry on the Office CDN domains in Semi-Annual Enterprise Preview.</span></span>

- <span data-ttu-id="ffbd9-903">この変更では、Intel Integrated GPU を使用するグラフィック アダプターに関して報告された問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-903">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="ffbd9-904">この変更により、リボンのスケッチされたアウトラインは正常に機能するようになります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-904">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="ffbd9-905">特定のプロキシの構成でオンプレミスの場所からファイルを開く際の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-905">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="ffbd9-906">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-906">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="ffbd9-907">問題を解決し、Office のハンドオフ セッション中のクラッシュを解消し、ユーザー エクスペリエンスの信頼性を向上させました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-907">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>

- <span data-ttu-id="ffbd9-908">このバグは、Enhanced Configuration Service (ECS) url エンドポイントを更新します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-908">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="ffbd9-909">この新しいエンドポイントを呼び出すと、ECS からのフェッチ成功率が高くなります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-909">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

- <span data-ttu-id="ffbd9-910">この更新プログラムでは、メッセージの表示または作成時に Microsoft Outlook で現在の機密ラベルが表示されないという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-910">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="ffbd9-911">同じ SharePoint ライブラリから Word/Excel/PowerPoint で複数のドキュメントが開かれている場合、最初に開いたドキュメントのみがポリシー コンプライアンスでスキャンされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-911">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

- <span data-ttu-id="ffbd9-912">Office ユーザーのセキュリティを保護するために、Microsoft Office の更新プログラムは SHA-2 アルゴリズムのみを使用して署名されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-912">To protect Office customers’ security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="ffbd9-913">レジストリ キー HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth が 0 に設定されている場合、アドインがアクティブになり、Windows で Office ホストが終了します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-913">The office host was closing in windows, when an add-in is being activated while the registry key  HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="ffbd9-914">この変更により、この問題は修正されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-914">This change would fix this issue.</span></span>

- <span data-ttu-id="ffbd9-915">インストールされている言語によって Access と Publisher が正常に起動しなかった問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-915">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)





[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-july-14"></a><span data-ttu-id="ffbd9-918">バージョン 1908: 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-918">Version 1908: July 14</span></span>
<span data-ttu-id="ffbd9-919">*バージョン 1908 (ビルド 11929.20904)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-919">*Version 1908 (Build 11929.20904)*</span></span>

<span data-ttu-id="ffbd9-920">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-920">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-922">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-922">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ffbd9-923">Access</span><span class="sxs-lookup"><span data-stu-id="ffbd9-923">Access</span></span>

- <span data-ttu-id="ffbd9-924">この更新プログラムにより、Sum などの集計が結果を整数値に切り捨てる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-924">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="ffbd9-925">この更新プログラムにより、リモート テーブル (SQL Server テーブルなど) への参照を含むユニオン クエリにより Access が閉じて再起動する問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-925">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="ffbd9-926">この更新プログラムにより、更新クエリが実行されるか、SQL で UPDATE ステートメントが使用されるときに "クエリは破損しています" というエラーを発生させる場合のある Microsoft Access の問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-926">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="ffbd9-927">Excel</span><span class="sxs-lookup"><span data-stu-id="ffbd9-927">Excel</span></span>

- <span data-ttu-id="ffbd9-928">ドキュメント タイトルのオランダ語の KeyTip が Alt-G に変更されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-928">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="ffbd9-929">図形やフォームコントロールに割り当てられているマクロが間違ったエラーメッセージとして表示される、または間違った対象範囲で動作する問題が Excel で修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-929">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="ffbd9-930">最初のアイテムを検索した後に、ダイアログでのフォーカスの位置が変更されてしまう検索と置換についての問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-930">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="ffbd9-931">これにより、ピボットテーブルの並べ替え方法を変更し、他のユーザーとの共同編集セッション中にそれを更新するとクラッシュが発生する可能性がある問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-931">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="ffbd9-932">OLAP ピボットテーブルのフィルターが、キューブから削除された値に設定された場合の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-932">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="ffbd9-933">この更新プログラムは、VBA を使用してグラフのヘッダー/フッターに画像を追加するたびにエラーが発生する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-933">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="ffbd9-934">シリーズ コレクションを変更するときに、散布図が適切にレンダリングされない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="ffbd9-934">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span>

- <span data-ttu-id="ffbd9-935">グラフ テンプレートを使用してグラフを挿入する場合に、プレビューで正しい色が使用されるよう修正します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-935">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="ffbd9-936">セルが挿入または削除されたときに、ウォーターフォール図とじょうごグラフがテーブルと同期しなくなる原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-936">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="ffbd9-937">Excel で、ユーザーが変更を取得するためにブックを再び開くよう要求されるマージ競合の問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-937">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="ffbd9-938">最小化されたウィンドウをアクティブにするマクロ実行時エラーの原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-938">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="ffbd9-939">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-939">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="ffbd9-940">他のユーザーと共同編集しているときに、テーブルの横にある切り取りと貼り付けの操作が失敗する原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-940">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="ffbd9-941">実行中のマクロでカスタム プロパティを変更するときに、共同編集の中断を引き起こす原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-941">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="ffbd9-942">アドインによって開かれた WPF (Windows Presentation Foundation) フォームのコンボ ボックスからアイテムを選ぶことができない問題が発生しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-942">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="ffbd9-943">ブックが開かれていない状態で最近使用したファイルを検索するときに、クラッシュを発生させる原因となっていた可能性がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-943">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="ffbd9-944">グループ ボックス コントロールの境界線が印刷プレビューまたは印刷時に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-944">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="ffbd9-945">ブックで外部リンクがある場合に、一部のユーザーでポップアップ ウィンドウが複数表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-945">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="ffbd9-946">VBA マクロを使用して範囲の内容をクリアするときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-946">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="ffbd9-947">値の範囲への入力に予想より時間がかかる VBA の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-947">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="ffbd9-948">グラフの軸の "Value Crosses At" プロパティが、ファイルを保存してもう一度開くときに予期せず変更されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-948">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="ffbd9-949">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-949">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="ffbd9-950">結合されたセルを含む列を削除するときにパフォーマンスが低下する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-950">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="ffbd9-951">[印刷プレビュー] に表示されるときのフォーム コントロール内のテキストの拡大縮小に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-951">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="ffbd9-952">色でフィルタリングされたデータを異なる幅の列にコピーすると、値が貼り付けられません。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-952">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

- <span data-ttu-id="ffbd9-953">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-953">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="ffbd9-954">印刷時にフォーム コントロールのチェックボックスが拡大縮小されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-954">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="ffbd9-955">同じブック内でブックマークされたハイパーリンクをクリックすると、ブックが非表示になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-955">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="ffbd9-956">従来の "共有ブック" モードを使用して、ブックの新しいシートに変更をリスト表示しようとすると、クラッシュが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-956">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="ffbd9-957">一部のロケールにおいて、[Text to Column] 機能が失敗することがあります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-957">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="ffbd9-958">非表示の名前付き範囲にアクセスすると、ユーザーにエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-958">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="ffbd9-959">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-959">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="ffbd9-960">グラフを含むブックを保存すると、グラフ ヘッダーの画像のファイル サイズが大きくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-960">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>

- <span data-ttu-id="ffbd9-961">非同期のユーザー定義関数が同期して実行されるパフォーマンスの問題が発生しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-961">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="ffbd9-962">結合されたセルで列を削除するパフォーマンスが大幅に改善されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-962">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="ffbd9-963">スクロール後にセルを選択すると間違ったセルが選択されることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-963">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="ffbd9-964">Lookup 関数がエラーを返す問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-964">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="ffbd9-965">選択範囲を相互参照ブックと同期させ続けることにより、相互参照ブックの DBCS 文字が破損する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-965">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="ffbd9-966">自動調整を使用して行の高さを調整するときにチェック ボックスのコントロールが縮小される可能性があるという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-966">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>

- <span data-ttu-id="ffbd9-967">ファイルに広範な条件付き書式が設定されている場合に、[フォントの色] ボタンをクリックするとパフォーマンスが低下する問題。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-967">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="ffbd9-968">印刷プレビューの印刷範囲が正しくないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-968">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="ffbd9-969">信頼されていないネットワーク共有から保護されたファイルを編集する際に、Excel にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-969">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="ffbd9-970">色によるフィルタリングのパフォーマンスが大幅に改善されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-970">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="ffbd9-971">Office の以前のバージョンで作成されたブックを Office の最新のバージョンで開いたときに、Excel の終了を引き起こす可能性がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-971">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="ffbd9-972">アドイン マネジャーで参照するときに、16 個を超えるアドインを表示できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-972">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="ffbd9-973">一部の保護されたシートにハイパーリンクが貼り付けられない問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-973">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="ffbd9-974">この変更は、ソフトウェア レンダリングを活用することにより、特定の Intel グラフィック ドライバーの問題を回避します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-974">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="ffbd9-975">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-975">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="ffbd9-976">この更新プログラムにより、"アップロードできませんでした" というメッセージが表示され、Office ドキュメントが OneDrive for Business にアップロードされないことがあるエラーが修正されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-976">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="ffbd9-977">Win32 クライアントの [アイデア] ボタンをクリックしてアドインを読み込むときにエラーが発生するという Excel のアイデア機能の問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-977">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span> 

### <a name="onenote"></a><span data-ttu-id="ffbd9-978">OneNote</span><span class="sxs-lookup"><span data-stu-id="ffbd9-978">OneNote</span></span>

- <span data-ttu-id="ffbd9-979">同期およびサービスの安定性を改善するために、OneNote ユーザー エクスペリエンスで実行されている一時的な手段についての詳細情報をユーザーが学べるようにする通知をローカライズします。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-979">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="ffbd9-980">Outlook</span><span class="sxs-lookup"><span data-stu-id="ffbd9-980">Outlook</span></span>

- <span data-ttu-id="ffbd9-981">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-981">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="ffbd9-982">メールボックスを基本認証から最新認証にアップグレードしたユーザーが、Outlook プロファイルに関連付けられた正しくないアカウントで終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-982">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="ffbd9-983">Web アドインがデジタル著作権管理 (DRM) メッセージにアクセスすべきでないときにアクセスする原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-983">Addresses an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="ffbd9-984">一部のセーフリンクに対して簡易的なホバーの URL が正しく表示されなくなる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-984">Addresses an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="ffbd9-985">これにより、Python による添付ファイルもブロックされるよう、Outlook の添付ファイルのブロック ロジックが更新されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-985">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="ffbd9-986">設定に関係なく、POP3 ユーザーの一部がプレーンテキストで書式設定されたすべてのメールを表示する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-986">Addresses an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="ffbd9-987">この修正プログラムでは、HTML 形式のメッセージの表示が復元されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-987">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="ffbd9-988">プライマリ予定表からグループ予定表にアイテムをコピーするときに、ユーザーにアクセス許可のエラーを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-988">Addresses an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="ffbd9-989">ユーザーがスクリーン リーダーから場所の候補にアクセスできない原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-989">Addresses an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="ffbd9-990">キーボード ショートカットを使用してメールボックス フォルダーを操作すると、ユーザーに顕著な遅延が発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-990">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="ffbd9-991">非常に長い Outlook セッションでメモリ リークを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-991">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="ffbd9-992">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-992">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="ffbd9-993">ユーザーが [ルール] ダイアログを開くと、"このコンピューターのルールは、Microsoft Exchange のルールと異なります" というメッセージが表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-993">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="ffbd9-994">特定のセーフリンクを操作するときに、Outlook でクラッシュを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-994">Addresses an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="ffbd9-995">代理人が特定の会議出席依頼に既に返信したかどうかに関係なく、管理者が不明瞭になる問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-995">Addresses an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="ffbd9-996">一部の AutoDiscover の応答を処理するときに、クラッシュを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-996">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="ffbd9-997">アカウント作成コンテキストからサポートに連絡しようとすると、ユーザーに [OK] ボタンのある空のメッセージ ボックスが表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-997">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="ffbd9-998">この変更により、UPN 経由で自動検出の認証プロンプトに提供されるアカウントのメールを選択するため、ポリシーを管理者が有効にできるようになります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-998">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="ffbd9-999">既定では、使用可能な場合に、自動検出ではアカウント UPN の方が選択されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-999">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="ffbd9-1000">最新のグループに対し、検索の失敗がユーザーに表示される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1000">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="ffbd9-1001">Outlook ユーザーが特定のシナリオで "パスワードを要求している" 状態で停止する原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1001">Addresses an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="ffbd9-1002">競合メッセージの処理中にユーザーに同期エラーが発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1002">Addresses an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="ffbd9-1003">最新の Windows 更新プログラム適用後に、ユーザーが msg および .oft ファイルを開こうとするとクラッシュが起きる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1003">Addresses an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="ffbd9-1004">Outlook の起動時にユーザーが [プロファイルの読み込み中] 画面でハングアップする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1004">Addresses an issue that caused users to experience a hang at the "Loading Profile" screen when Outlook is starting up.</span></span>

- <span data-ttu-id="ffbd9-1005">特定の検索結果を選択すると、ユーザーがクラッシュする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1005">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="ffbd9-1006">[添付ファイル ​​ツール] に [クラウドに保存] ボタンが表示されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1006">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="ffbd9-1007">既定では、アイテム保持ポリシーのラベルには、保持期間がかっこ内に表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1007">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="ffbd9-1008">これにより、管理者はポリシー名のみを表示するように指定するレジストリ キーを取得することができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1008">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="ffbd9-1009">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = アイテム保持ポリシー テキストの PolicyName のみが表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1009">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

- <span data-ttu-id="ffbd9-1010">Outlook のシャットダウン時にクラッシュが発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1010">Addresses an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="ffbd9-1011">一部のシナリオで顧客に空室リストが表示される原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1011">Addresses an issue that caused customers to see an empty room list in some scenarios.</span></span>

- <span data-ttu-id="ffbd9-1012">ビューを変更すると、断続的なクラッシュが発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1012">Addresses an issue that caused users to see intermittent crashes when changing views.</span></span>

- <span data-ttu-id="ffbd9-1013">ユーザーが OST と同期している共有予定表フォルダーに問題があり、これらのフォルダーを操作しようとするとアクセス許可エラーが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1013">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>

- <span data-ttu-id="ffbd9-1014">Citrix 環境で 30 件を超える予定表を表示したときにクラッシュする原因になった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1014">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="ffbd9-1015">以前のバージョンで文書化された個々の [KB については、こちらを参照してください](https://support.microsoft.com/ja-JP/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1015">Here's the individual [KB where this was documented for previous versions](https://support.microsoft.com/ja-JP/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span></span>

- <span data-ttu-id="ffbd9-1016">SMIME アルゴリズムの選択に関する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1016">Corrects an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="ffbd9-1017">代替送信者の使用中にポリシーのヒントが表示されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1017">Addresses an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="ffbd9-1018">会議室の空き時間外に行われた会議のためにユーザーにその会議室が提案される原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1018">Addresses an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="ffbd9-1019">英語以外の言語を使用するユーザーの、メールの件名が非常に小さくなるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1019">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="ffbd9-1020">"不在着信した会話" メッセージのルールを作成しようとするときに、クラッシュを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1020">Addresses an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="ffbd9-1021">一部のユーザーに、セカンダリ Exchange アカウントを追加するときに作成された重複した特別なフォルダーが表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1021">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="ffbd9-1022">大きな HTML メッセージを転送するとき、ユーザーにメッセージ本文の全体が表示されないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1022">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="ffbd9-1023">ユーザーが Outlook プロセスでメモリ リークを観測する原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1023">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="ffbd9-1024">プレゼンス情報を更新するときに、断続的なクラッシュを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1024">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="ffbd9-1025">現在のフォルダー検索で断続的な失敗を引き起こす問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1025">Addresses an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="ffbd9-1026">一部のユーザーが Outlook のクラウド設定を取得しようとするときに、認証エラーが発生する原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1026">Addresses an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="ffbd9-1027">検索に関するフィードバックのエクスペリエンスで終了する原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1027">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="ffbd9-1028">一部の AutoDiscover の応答を処理するときに、クラッシュを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1028">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="ffbd9-1029">プレゼンス情報を更新するときに、断続的なクラッシュを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1029">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ffbd9-1030">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1030">PowerPoint</span></span>

- <span data-ttu-id="ffbd9-1031">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1031">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="ffbd9-1032">この変更により、PowerPoint ビデオ コントロールのアクセス可能な名前が復元されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1032">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="ffbd9-1033">一部のアニメーションが開始されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1033">We fixed an issue which could prevent some animations from starting</span></span>

- <span data-ttu-id="ffbd9-1034">スライドを 1 つのプレゼンテーションから別のプレゼンテーションにコピーすると、重複したマスターが作成される可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1034">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span><br>

- <span data-ttu-id="ffbd9-1035">コピーと貼り付けのシナリオを改善しました。PowerPoint スライドでの図形のコピーと、ループ内の他のスライドへの貼り付けが例外で失敗する場合があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1035">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="ffbd9-1036">蛍光ペンの問題を修正しました。暗い蛍光ペン色の白いテキストはグレースケールで黒として印刷されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1036">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

- <span data-ttu-id="ffbd9-1037">最新のコメントを含むファイルを、サポートされていないバージョンで開くと黄色の警告が表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1037">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

- <span data-ttu-id="ffbd9-1038">共同作業ユーザー間のパフォーマンスが低下する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1038">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="ffbd9-1039">信頼性の修正: サード パーティのアドインが PowerPoint のクラッシュを発生させる可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1039">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="ffbd9-1040">増分で開くファイルに、複数のメディア ストリームが埋め込まれたスライドが含まれている場合に発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1040">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="ffbd9-1041">Shape.Paste メソッドを使用する際に発生する問題を解決しました。Shape.Paste メソッドを使用して図形をコピーして貼り付けるときに、貼り付けられた図形の選択内容が変更するという問題です。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1041">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="ffbd9-1042">PowerPoint の初回起動時に、信頼されていないアドインに対してセキュリティ警告メッセージ バーが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1042">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

- <span data-ttu-id="ffbd9-1043">一部のアドインがグラフの図形に対して予期しないエラーをスローさせる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1043">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="ffbd9-1044">PowerPoint ユーザーがオンライン プレゼンテーションを行おうとするときに、エラーが発生しないようにします。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1044">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

### <a name="project"></a><span data-ttu-id="ffbd9-1045">Project</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1045">Project</span></span>

- <span data-ttu-id="ffbd9-1046">Windows 7 のユーザーが Project Web App および SharePoint サイトからプロジェクトを開くことができるように問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1046">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="ffbd9-1047">読み取り専用のプロジェクトを開いたときに複数のメッセージを取得する可能性があるという問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1047">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="ffbd9-1048">[すべて平準化] コマンドがリソースの割り当て超過を適切に解決しません。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1048">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="ffbd9-1049">タスクの作業がゼロの割り当てがある場合、タスクに完了のマークを付けることができず、常に 99％ で表示される問題。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1049">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

- <span data-ttu-id="ffbd9-1050">基本カレンダーが変更されたときにリソース カレンダーが更新されないために、実際の作業がタイムシートとプロジェクト計画の間で異なる場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1050">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="skype"></a><span data-ttu-id="ffbd9-1051">Skype</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1051">Skype</span></span>

- <span data-ttu-id="ffbd9-1052">複数の会話が発生している場合の、タブ表示の会話のタイトル名を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1052">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="visio"></a><span data-ttu-id="ffbd9-1053">Visio</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1053">Visio</span></span>

- <span data-ttu-id="ffbd9-1054">Visio から SVG へのエクスポートが、さまざまな図形で失敗していました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1054">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="ffbd9-1055">Word</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1055">Word</span></span>

- <span data-ttu-id="ffbd9-1056">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1056">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="ffbd9-1057">Deskjet プリンターへの印刷時に、スケーリングの問題を引き起こす可能性があった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1057">We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span>

- <span data-ttu-id="ffbd9-1058">表での文字の均等割り付けの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1058">We fixed an issue in Fit Text in Table.</span></span>

- <span data-ttu-id="ffbd9-1059">無限ループになることがあるトラック変更の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1059">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="ffbd9-1060">既存のファイルを保存すると [名前を付けて保存] ダイアログが必ず表示され、ファイルは実際には保存されない場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1060">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="ffbd9-1061">2 つのドキュメントを 1 つのドキュメントに結合するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1061">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="ffbd9-1062">編集用に保護されたドキュメントの比較機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1062">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="ffbd9-1063">シャットダウン時にアプリが終了することがあるさまざまな問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1063">Fixes various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="ffbd9-1064">特定のアドインに関連するクラッシュも修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1064">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ffbd9-1065">Office スイート</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1065">Office Suite</span></span>

- <span data-ttu-id="ffbd9-1066">新元号の名前である “Reiwa” のひらがなと漢字をスペルミスまたは間違った文法として誤って識別していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1066">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="ffbd9-1067">SharePoint 2016 に保存されているファイルを共有しようとするときに、"申し訳ございません。何かがこのファイルの共有を妨げています。" というメッセージが表示される原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1067">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="ffbd9-1068">PowerPoint での共同編集とオフライン編集の両方を含むセッションでデータの損失を引き起こす可能性のある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1068">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="ffbd9-1069">これは、ユーザーがファイルを開くときに発生する可能性のあるクラッシュの修正プログラムです。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1069">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="ffbd9-1070">同期エンジンでバックアップされた Sharepoint ファイルに '保存済み' と表示されますが、場合によっては実際に変更が保存されないため、データを損失することになります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1070">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="ffbd9-1071">ユーザーが Word、Excel、および PowerPoint のドキュメントを保存できなくなることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1071">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="ffbd9-1072">この問題は、[保存] アイコンをクリックしたり Ctrl キーを押しながら S キーを押したりした後に、新しいファイルを作成して [ダイアログで保存] オプションを表示するユーザーに影響を与えます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1072">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="ffbd9-1073">非推奨の API から移動することにより、Word でクラッシュが発生する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1073">Fixes a crash in Word by moving away from a deprecated API.</span></span>

- <span data-ttu-id="ffbd9-1074">PowerPoint の垂直テキスト ボックスで半角カタカナ文字が適切に回転しない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1074">Fixing an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="ffbd9-1075">すべてのアプリのリボンで、図形の挿入ギャラリーが表示されるまでに約 4 秒かかるという Win7 のパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1075">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="ffbd9-1076">Backstage の Info Place のスラブにアクセシビリティ情報が表示されていないというバグを修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1076">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="ffbd9-1077">レジストリ整合性に関する Office 更新プロセスの信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1077">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="ffbd9-1078">1 月と 7 月の 2019 フォークのチャネル名が新しいチャネル名に更新しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1078">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="ffbd9-1079">従量制課金ネットワークで更新プログラムが予期せずブロックされる可能性があるという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1079">Corrects an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="ffbd9-1080">ODT と GPO の更新期限設定で、相対期限の設定後、初回のみしか機能しないバスが修正されました。修正により、2 回目以降の更新プログラムで相対期限を使用きるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1080">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="ffbd9-1081">特定の状況で、更新後に Office ショートカットが消えてしまう場合があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1081">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="ffbd9-1082">この更新プログラムにより、Office ショートカットを公開するときの信頼性が向上します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1082">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="ffbd9-1083">Office の更新プログラムが、意図したソース (ローカル共有、ネットワーク共有、構成マネージャーで提供される場所など) からではなく、予期せずに Office CDN からファイルをダウンロードする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1083">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="ffbd9-1084">ユーザーが管理者ではなく、システム アカウントにネットワーク接続が確立されていない場合に、更新プログラムが適用されない問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1084">Resolves an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="ffbd9-1085">Office の更新メッセージが、異なる言語で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1085">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="ffbd9-1086">今後、Office の更新メッセージは Windows の表示言語と一致します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1086">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="ffbd9-1087">以前に中断された可能性のあるダウンロードを再開することにより、Office の更新プログラムをダウンロードするときの信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1087">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="ffbd9-1088">サード パーティ製プラグインのテキスト ボックスと図形の自動調整に関連する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1088">Address issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="ffbd9-1089">この変更は、破損したファイルを開いた後の画像の正しいレンダリングに対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1089">This change addresses correctly rendering images after opening a corrupted file.</span></span>

- <span data-ttu-id="ffbd9-1090">この変更により、マーカー付きの一部の散布図の表示が遅くなる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1090">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="ffbd9-1091">大きなツリー ビューがクラッシュすることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1091">We fixed an issue where large tree views could result in a crash</span></span>

- <span data-ttu-id="ffbd9-1092">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1092">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="ffbd9-1093">Office ユーザーのセキュリティを保護するために、Microsoft Office の更新プログラムは SHA-2 アルゴリズムのみを使用して署名されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1093">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="ffbd9-1094">Office ユーザーのセキュリティを保護するために、Microsoft Office の更新プログラムは SHA-2 アルゴリズムのみを使用して署名されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1094">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1902-july-14"></a><span data-ttu-id="ffbd9-1096">バージョン 1902: 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1096">Version 1902: July 14</span></span>
<span data-ttu-id="ffbd9-1097">*バージョン 1902 (ビルド 11328.20624)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1097">*Version 1902 (Build 11328.20624)*</span></span>

<span data-ttu-id="ffbd9-1098">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1098">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1908-june-09"></a><span data-ttu-id="ffbd9-1099">バージョン 1908: 6 月 9 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1099">Version 1908: June 09</span></span>
<span data-ttu-id="ffbd9-1100">*バージョン 1908 (ビルド 11929.20838)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1100">*Version 1908 (Build 11929.20838)*</span></span>

<span data-ttu-id="ffbd9-1101">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1101">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-1103">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1103">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ffbd9-1104">Excel</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1104">Excel</span></span>

- <span data-ttu-id="ffbd9-1105">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1105">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="ffbd9-1106">印刷時にフォーム コントロールのチェックボックスが拡大縮小されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1106">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="ffbd9-1107">従来の "共有ブック" モードを使用して、ブックの新しいシートに変更を一覧表示しようとすると、クラッシュが発生する場合がありました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1107">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="ffbd9-1108">Outlook</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1108">Outlook</span></span>

- <span data-ttu-id="ffbd9-1109">大きな HTML メッセージを転送するとき、ユーザーにメッセージ本文の全体が表示されないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1109">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ffbd9-1110">Office スイート</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1110">Office Suite</span></span>

- <span data-ttu-id="ffbd9-1111">1月と7月の2019フォークのチャネル名が新しいチャネル名に更新されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1111">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1902-june-09"></a><span data-ttu-id="ffbd9-1113">バージョン 1902: 6月 9 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1113">Version 1902: June 09</span></span>
<span data-ttu-id="ffbd9-1114">*バージョン 1902 (ビルド 11328.20602)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1114">*Version 1902 (Build 11328.20602)*</span></span>

<span data-ttu-id="ffbd9-1115">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1115">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-1117">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1117">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="ffbd9-1118">Office スイート</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1118">Office Suite</span></span>

- <span data-ttu-id="ffbd9-1119">1月と7月の2019フォークのチャネル名が新しいチャネル名に更新されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1119">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="ffbd9-1120">C2R ビルドを中断していたベースライン ファイルから、古い形式の参照を削除しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1120">We removed obsolete references from the baseline files that were breaking the C2R Build.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-may-12"></a><span data-ttu-id="ffbd9-1122">バージョン 1908: 5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1122">Version 1908: May 12</span></span>
<span data-ttu-id="ffbd9-1123">*バージョン 1908 (ビルド 11929.20776)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1123">*Version 1908 (Build 11929.20776)*</span></span>

<span data-ttu-id="ffbd9-1124">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1124">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-1126">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1126">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ffbd9-1127">Excel</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1127">Excel</span></span>

- <span data-ttu-id="ffbd9-1128">色でフィルタリングされたデータを異なる幅の列にコピーする場合、値は貼り付けられません。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1128">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

### <a name="outlook"></a><span data-ttu-id="ffbd9-1129">Outlook</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1129">Outlook</span></span>

- <span data-ttu-id="ffbd9-1130">最新の Windows 更新プログラム適用後に、ユーザーが msg および .oft ファイルを開こうとするとクラッシュが起こる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1130">Addressed an issue that caused users to experience a crash when opening msg and .oft files after applying a recent Windows update.</span></span>

### <a name="word"></a><span data-ttu-id="ffbd9-1131">Word</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1131">Word</span></span>

- <span data-ttu-id="ffbd9-1132">2 つのドキュメントを 1 つのドキュメントに結合するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1132">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="ffbd9-1133">編集用に保護されたドキュメントの比較機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1133">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1902-may-12"></a><span data-ttu-id="ffbd9-1135">バージョン 1902: 5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1135">Version 1902: May 12</span></span>
<span data-ttu-id="ffbd9-1136">*バージョン 1902 (ビルド 11328.20586)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1136">*Version 1902 (Build 11328.20586)*</span></span>

<span data-ttu-id="ffbd9-1137">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1137">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-1139">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1139">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ffbd9-1140">Outlook</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1140">Outlook</span></span>

- <span data-ttu-id="ffbd9-1141">最新の Windows 更新プログラム適用後に、ユーザーが msg および .oft ファイルを開こうとするとクラッシュが起きる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1141">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="ffbd9-1142">既定では、アイテム保持ポリシーのラベルには、保持期間がかっこ内に表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1142">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="ffbd9-1143">これにより、管理者はポリシー名のみを表示するように指定するレジストリ キーを取得することができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1143">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="ffbd9-1144">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1144">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="ffbd9-1145">0 = 既定値。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1145">0 = Default.</span></span>  <span data-ttu-id="ffbd9-1146">1 = アイテム保持ポリシー テキスト のPolicyName のみが表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1146">1 = we will only show the PolicyName for Retention policy text.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-may-04"></a><span data-ttu-id="ffbd9-1148">バージョン 1908: 5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1148">Version 1908: May 04</span></span>
<span data-ttu-id="ffbd9-1149">*バージョン 1908 (ビルド 11929.20752)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1149">*Version 1908 (Build 11929.20752)*</span></span>

<span data-ttu-id="ffbd9-1150">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1150">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-1151">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1151">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ffbd9-1152">Outlook</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1152">Outlook</span></span>

- <span data-ttu-id="ffbd9-1153">ユーザーが特定の検索結果を選択すると、クラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1153">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="ffbd9-1154">[添付ファイル ​​ツール] に [クラウドに保存] ボタンが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1154">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="ffbd9-1155">既定では、アイテム保持ポリシーのラベルには、保持期間がかっこ内に表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1155">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="ffbd9-1156">これにより、管理者はポリシー名のみを表示するように指定するレジストリ キーを取得することができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1156">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="ffbd9-1157">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1157">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="ffbd9-1158">0 = 既定値 1 = アイテム保持ポリシー テキスト のPolicyName のみが表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1158">0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ffbd9-1159">Office スイート</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1159">Office Suite</span></span>

- <span data-ttu-id="ffbd9-1160">Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1160">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1902-may-04"></a><span data-ttu-id="ffbd9-1161">バージョン 1902: 5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1161">Version 1902: May 04</span></span>
<span data-ttu-id="ffbd9-1162">*バージョン 1902 (ビルド 11328.20572)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1162">*Version 1902 (Build 11328.20572)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-1163">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1163">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="ffbd9-1164">Office スイート</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1164">Office Suite</span></span>

- <span data-ttu-id="ffbd9-1165">Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1165">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1908-april-26"></a><span data-ttu-id="ffbd9-1166">バージョン 1908: 4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1166">Version 1908: April 26</span></span>
<span data-ttu-id="ffbd9-1167">*バージョン 1908 (ビルド 11929.20736)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1167">*Version 1908 (Build 11929.20736)*</span></span>

<span data-ttu-id="ffbd9-1168">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1168">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-1169">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1169">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ffbd9-1170">Excel</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1170">Excel</span></span>

- <span data-ttu-id="ffbd9-1171">VBA マクロを使用して範囲の内容をクリアするときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1171">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="ffbd9-1172">値の範囲への入力に予想より時間がかかる VBA の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1172">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="ffbd9-1173">グラフの軸の "Value Crosses At" プロパティが、ファイルを保存してもう一度開くときに予期せず変更されるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1173">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="ffbd9-1174">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1174">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


### <a name="onenote"></a><span data-ttu-id="ffbd9-1175">OneNote</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1175">OneNote</span></span>

- <span data-ttu-id="ffbd9-1176">同期およびサービスの安定性を改善するために、OneNote ユーザー エクスペリエンスで実行されている一時的な手段についての詳細情報をユーザーが学べるようにする通知をローカライズします。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1176">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>


## <a name="version-1908-april-14"></a><span data-ttu-id="ffbd9-1177">バージョン 1908: 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1177">Version 1908: April 14</span></span>
<span data-ttu-id="ffbd9-1178">*バージョン 1908 (ビルド 11929.20708)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1178">*Version 1908 (Build 11929.20708)*</span></span>

<span data-ttu-id="ffbd9-1179">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1179">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-1181">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1181">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ffbd9-1182">Excel</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1182">Excel</span></span>

- <span data-ttu-id="ffbd9-1183">結合されたセルを含む列を削除するときにパフォーマンスが低下する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1183">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="ffbd9-1184">[印刷プレビュー] に表示されるときのフォーム コントロール内のテキストの拡大縮小に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1184">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

### <a name="skype"></a><span data-ttu-id="ffbd9-1185">Skype</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1185">Skype</span></span>

- <span data-ttu-id="ffbd9-1186">複数の会話が発生している場合の、タブ表示の会話のタイトル名を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1186">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="outlook"></a><span data-ttu-id="ffbd9-1187">Outlook</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1187">Outlook</span></span>

- <span data-ttu-id="ffbd9-1188">Outlook のシャットダウン時にクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1188">Addressed an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="ffbd9-1189">一部のシナリオで顧客に空室リストが表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1189">Addressed an issue that caused customers to see an empty room list in some scenarios.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ffbd9-1190">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1190">PowerPoint</span></span>

- <span data-ttu-id="ffbd9-1191">蛍光ペンの問題を修正しました。暗い蛍光ペン色の白いテキストはグレースケールで黒として印刷されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1191">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="ffbd9-1192">Word</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1192">Word</span></span>

- <span data-ttu-id="ffbd9-1193">表での、文字の均等割り付けの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1193">Fixed an issue in Fit Text in Table.</span></span>


## <a name="version-1902-april-14"></a><span data-ttu-id="ffbd9-1194">バージョン 1902: 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1194">Version 1902: April 14</span></span>
<span data-ttu-id="ffbd9-1195">*バージョン 1902 (ビルド 11328.20564)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1195">*Version 1902 (Build 11328.20564)*</span></span>

<span data-ttu-id="ffbd9-1196">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1196">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-march-10"></a><span data-ttu-id="ffbd9-1198">バージョン 1908: 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1198">Version 1908: March 10</span></span>
<span data-ttu-id="ffbd9-1199">*バージョン 1908 (ビルド 11929.20648)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1199">*Version 1908 (Build 11929.20648)*</span></span>

<span data-ttu-id="ffbd9-1200">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1200">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-1202">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1202">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ffbd9-1203">Excel</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1203">Excel</span></span>

- <span data-ttu-id="ffbd9-1204">ブックで外部リンクがある場合にポップアップ ウィンドウが複数表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1204">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>


- <span data-ttu-id="ffbd9-1205">一部のロケールにおいて、[Text to Column] 機能が失敗することがあります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1205">Text to Column functionality may fail for some locales.</span></span>


- <span data-ttu-id="ffbd9-1206">非表示の名前付き範囲にアクセスすると、ユーザーにエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1206">Users may encounter an error when accessing a hidden named range.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ffbd9-1207">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1207">PowerPoint</span></span>

- <span data-ttu-id="ffbd9-1208">Shape.Paste メソッドを使用する際に発生する問題を解決しました。Shape.Paste メソッドを使用して図形をコピーして貼り付けるときに、貼り付けられた図形の選択内容が変更するという問題です。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1208">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>


### <a name="word"></a><span data-ttu-id="ffbd9-1209">Word</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1209">Word</span></span>

- <span data-ttu-id="ffbd9-1210">既存のファイルを保存すると [名前を付けて保存] ダイアログが必ず表示され、ファイルは実際には保存されない場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1210">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>


### <a name="office-suite"></a><span data-ttu-id="ffbd9-1211">Office スイート</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1211">Office Suite</span></span>

- <span data-ttu-id="ffbd9-1212">この変更により、マーカー付きの一部の散布図の表示が遅くなる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1212">This change addresses slow rendering of some scatter charts with markers.</span></span>

## <a name="version-1902-march-10"></a><span data-ttu-id="ffbd9-1213">バージョン 1902: 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1213">Version 1902: March 10</span></span>
<span data-ttu-id="ffbd9-1214">*バージョン 1902 (ビルド 11328.20554)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1214">*Version 1902 (Build 11328.20554)*</span></span>

<span data-ttu-id="ffbd9-1215">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1215">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-february-11"></a><span data-ttu-id="ffbd9-1217">バージョン 1908: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1217">Version 1908: February 11</span></span>
<span data-ttu-id="ffbd9-1218">*バージョン 1908 (ビルド 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1218">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="ffbd9-1219">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1219">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-1221">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1221">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ffbd9-1222">Excel</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1222">Excel</span></span>

- <span data-ttu-id="ffbd9-1223">この更新プログラムは、VBA を使用してグラフのヘッダー/フッターに画像を追加するたびにエラーが発生する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1223">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="ffbd9-1224">グループ ボックス コントロールの境界線が印刷プレビューまたは印刷時に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1224">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="ffbd9-1225">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1225">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="ffbd9-1226">グラフを含むブックを保存すると、グラフ ヘッダーの画像のファイル サイズが大きくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1226">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="ffbd9-1227">選択範囲を相互参照ブックと同期させ続けることにより、相互参照ブックの DBCS 文字が破損する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1227">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="ffbd9-1228">自動調整を使用して行の高さを調整するときにチェック ボックスのコントロールが縮小される可能性があるという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1228">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="ffbd9-1229">Outlook</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1229">Outlook</span></span>

- <span data-ttu-id="ffbd9-1230">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1230">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="ffbd9-1231">競合メッセージの処理中にユーザーに同期エラーが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1231">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="ffbd9-1232">Outlook の起動時にユーザーが [プロファイルの読み込み中] 画面でハングアップする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1232">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="ffbd9-1233">ビューを変更すると、断続的なクラッシュが発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1233">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="ffbd9-1234">Citrix 環境で 30 件を超える予定表を表示したときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1234">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="ffbd9-1235">[こちら](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)は、以前のバージョンで文書化された個々の KB です。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1235">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="ffbd9-1236">ユーザーが OST と同期している共有予定表フォルダーに問題があり、これらのフォルダーを操作しようとするとアクセス許可エラーが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1236">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="ffbd9-1237">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1237">PowerPoint</span></span>

- <span data-ttu-id="ffbd9-1238">PowerPoint スライドでのコピーと貼り付けのシナリオである図形のコピーを改善しました。ループ内の他のスライドに貼り付けると例外で失敗する場合があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1238">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="ffbd9-1239">共同作業ユーザー間のパフォーマンスが低下する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1239">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="ffbd9-1240">増分で開くファイルに、複数のメディア ストリームが埋め込まれたスライドが含まれている場合に発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1240">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="ffbd9-1241">PowerPoint の初回起動時に、信頼されていないアドインに対してセキュリティ警告メッセージ バーが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1241">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="ffbd9-1242">Project</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1242">Project</span></span>

- <span data-ttu-id="ffbd9-1243">基本カレンダーが変更されたときにリソース カレンダーが更新されないために、実際の作業がタイムシートとプロジェクト計画の間で異なる場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1243">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="ffbd9-1244">Word</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1244">Word</span></span>

- <span data-ttu-id="ffbd9-1245">非推奨の API から移動することにより、Word でクラッシュが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1245">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ffbd9-1246">Office スイート</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1246">Office Suite</span></span>

- <span data-ttu-id="ffbd9-1247">この変更は、破損したファイルを開いた後の画像の正しいレンダリングに対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1247">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1902-february-11"></a><span data-ttu-id="ffbd9-1249">バージョン 1902: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1249">Version 1902: February 11</span></span>
<span data-ttu-id="ffbd9-1250">*バージョン 1902 (ビルド 11328.20526)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1250">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="ffbd9-1251">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1251">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-1253">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1253">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="ffbd9-1254">Outlook</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1254">Outlook</span></span>

- <span data-ttu-id="ffbd9-1255">ユーザーが暗号化されたメールを送信しようとするときに、"暗号化アルゴリズムがサポートされていません" というエラーを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1255">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="ffbd9-1256">Word</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1256">Word</span></span>

- <span data-ttu-id="ffbd9-1257">非推奨の API から移動することにより、Word でクラッシュが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1257">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

## <a name="version-1808-february-11"></a><span data-ttu-id="ffbd9-1260">バージョン 1808: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1260">Version 1808: February 11</span></span>
<span data-ttu-id="ffbd9-1261">*バージョン 1808 (ビルド 10730.20438)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1261">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="ffbd9-1262">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1262">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-january-14"></a><span data-ttu-id="ffbd9-1264">バージョン 1908: 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1264">Version 1908: January 14</span></span>
<span data-ttu-id="ffbd9-1265">*バージョン 1908 (ビルド 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1265">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="ffbd9-1266">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1266">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="ffbd9-1268">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1268">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="ffbd9-1269">Access</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1269">Access</span></span>

- <span data-ttu-id="ffbd9-1270">**データベース オブジェクトをタブで管理する:** アクティブなタブが分かりやすく表示され、簡単にタブをドラッグして再配置し、ワンクリックでデータベース オブジェクトを閉じることができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1270">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="ffbd9-1271">**シームレスに切り替える:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用のアカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1271">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="ffbd9-1272">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1272">Switching between them has never been easier.</span></span> [<span data-ttu-id="ffbd9-1273">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1273">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="ffbd9-1274">**より大きい [ズーム] ボックス:** [ズーム] ボックスがより大きく表示され、そこでフォントを変更することができます。変更内容はすべて [ズーム] ボックス内に記憶されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1274">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="ffbd9-1275">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1275">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="ffbd9-1276">Excel</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1276">Excel</span></span>

- <span data-ttu-id="ffbd9-1277">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1277">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="ffbd9-1278">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1278">Switching between them has never been easier.</span></span> [<span data-ttu-id="ffbd9-1279">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1279">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="ffbd9-1280">**コンテンツのリーチを拡大する:** プレゼンテーションのアクセシビリティを高める必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1280">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="ffbd9-1281">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1281">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="ffbd9-1282">[校閲]>[アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1282">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="ffbd9-1283">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1283">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="ffbd9-1284">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1284">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="ffbd9-1285">**ワークシートが生まれ変わりました：** ワークブックを使ってアニメーション 3D グラフィックスを挿入し、心臓の鼓動、惑星軌道、そして T-Rex の大暴れを見ることができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1285">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="ffbd9-1286">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1286">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="ffbd9-1287">**データの詳細を検出する:** 新しいアイデア ボタンは、データのパターンを探し、それを使用してインテリジェントな個人向けの提案を作成します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1287">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions.</span></span> [<span data-ttu-id="ffbd9-1288">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1288">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- <span data-ttu-id="ffbd9-1289">**共同作業がさらに簡単に:** 共同編集の改善とは、条件付き書式、セルのスタイルなどを使用して作業しているときに、ユーザーによる変更がシームレスに共同作業者の変更と統合されるということです。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1289">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="ffbd9-1290">**類似列のテーブルを結合する:** 取得と変換 (Power Query) では、テーブルを統合するために列を比較するときに、近似文字列マッチング ロジック (あいまい一致とも呼ばれる) が使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1290">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="ffbd9-1291">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1291">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="ffbd9-1292">**Power Query の機能強化を使用して素早くコーディングする:** オートコンプリートと構文の色分けを使用して、素早くコーディングを完了できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1292">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="ffbd9-1293">関数、列、パラメーターも簡単に見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1293">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="ffbd9-1294">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1294">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="ffbd9-1295">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1295">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="ffbd9-1296">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1296">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="ffbd9-1297">Outlook</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1297">Outlook</span></span>

- <span data-ttu-id="ffbd9-1298">**Outlook のユーザー エクスペリエンスを更新しました：** これまで Coming Soon でプレビューできていた、最も重要なことに集中できるようにするためのシンプルな操作性です。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1298">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="ffbd9-1299">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1299">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="ffbd9-1300">**カスタマイズも可能、シンプルになったリボン：** 最もよく使うボタンが単一行にまとめられ、使いやすくなりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1300">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="ffbd9-1301">簡単に従来のビューとシンプルなビューを切り替えたり、コマンドを固定または固定解除できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1301">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="ffbd9-1302">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1302">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="ffbd9-1303">**メッセージの移動中も作業が可能:** Outlook では、メッセージの移動がバックグラウンドで行われるようになったため、フォルダー間で多数のメッセージの移動が行われている間も作業を続けることができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1303">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="ffbd9-1304">**連続する会議の合間に時間を組み込む:** 既定で 5 分から 10 分早く会議を終了するように設定することで、出席者に休憩時間や場所の移動時間を与えることができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1304">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="ffbd9-1305">**お気に入りのアクションを選びましょう：** フラグや、削除機能を使いますか？</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1305">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="ffbd9-1306">アーカイブまたは既読に​​しますか?</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1306">How about Archive or Mark as Read?</span></span> <span data-ttu-id="ffbd9-1307">クイック操作メニューをカスタマイズしてよく使うコマンドを追加できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1307">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="ffbd9-p218">**ミームが表示される:** テキストまたは静的イメージだけでは十分ではない場合、アニメーション GIF を使用して要点を示すことができます。[詳細情報](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-p218">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="ffbd9-1310">**より簡単なアカウントの追加方法:** アカウントのセットアップの改善により、2 要素認証を使用する Outlook.com と Gmail のアカウントを Outlook に追加することが以前よりも簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1310">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="ffbd9-1311">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1311">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="ffbd9-1312">**同期制限にさよならしましょう:** Outlook の改善によりフォルダーの制限が解消され、そのまま共有メールボックスが同期されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1312">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="ffbd9-1313">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1313">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="ffbd9-1314">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1314">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="ffbd9-1315">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1315">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="ffbd9-1316">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1316">PowerPoint</span></span>

- <span data-ttu-id="ffbd9-1317">**よりよい変形操作:** 図形に名前を付けると、変形するときにより細かく制御できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1317">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="ffbd9-1318">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1318">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="ffbd9-1319">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1319">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="ffbd9-1320">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1320">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="ffbd9-1321">**コンテンツのリーチを拡大する:** プレゼンテーションのアクセシビリティを高める必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1321">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="ffbd9-1322">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1322">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="ffbd9-1323">[校閲]>[アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1323">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="ffbd9-1324">**シームレスに切り替える:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用のアカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1324">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="ffbd9-1325">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1325">Switching between them has never been easier.</span></span> [<span data-ttu-id="ffbd9-1326">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1326">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="ffbd9-1327">**オンライン ビデオの新しい保存場所:** Microsoft Stream にビデオを保存すれば、組織内のすべてのユーザーが視聴できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1327">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="ffbd9-1328">ビデオのリンクを挿入すれば、小さなファイル サイズでマルチメディア プレゼンテーションをご利用いただけます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1328">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="ffbd9-1329">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1329">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="ffbd9-1330">**変更が発生したときに変更内容を自動的に保存する:** 変更が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1330">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="ffbd9-p226">**ユーザーへのテストやアンケート:** テストやアンケートをスライドに配置します。Office で応答が自動的に収集され、保存されます。[詳細情報](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-p226">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="ffbd9-1334">**これまで以上に簡単にオンライン ビデオを挿入できるようになりました:** Vimeo または YouTube からビデオをスライドに挿入する場合は、</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1334">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide?</span></span> <span data-ttu-id="ffbd9-1335">ビデオ ページへのリンクがあれば簡単に行えます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1335">The video page link is all you need.</span></span> [<span data-ttu-id="ffbd9-1336">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1336">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="ffbd9-1337">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1337">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="ffbd9-1338">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1338">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="ffbd9-1339">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1339">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="ffbd9-1340">Project</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1340">Project</span></span>

- <span data-ttu-id="ffbd9-1341">**シームレスに切り替える:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用のアカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1341">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="ffbd9-1342">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1342">Switching between them has never been easier.</span></span> [<span data-ttu-id="ffbd9-1343">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1343">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="ffbd9-1344">Visio</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1344">Visio</span></span>

- <span data-ttu-id="ffbd9-1345">**プロセス図を Word にエクスポート:** Word 文書に図形やメタデータなどのグラフ コンテンツを自動的に追加します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1345">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="ffbd9-1346">その後に、文書をカスタマイズしてプロセスに関するガイドラインや操作マニュアルを作成できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1346">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="ffbd9-1347">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1347">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="ffbd9-1348">**はっとするようなデータ フローチャート:** データ ビジュアライザーのフローチャートの見事な新しいレイアウトがすっきり、はっきり、わかりやすくなりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1348">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="ffbd9-1349">オプションの [デザイン] タブをクリックします。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1349">Click the Design tab for options.</span></span>

- <span data-ttu-id="ffbd9-1350">**Azure ステンシルが組み込まれました:** 豊富な Azure ステンシルを使用してクラウド アプリの設計やアーキテクチャの計画を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1350">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="ffbd9-1351">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1351">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="ffbd9-p233">**壊れた Excel リンクの問題を解消:** データ ビジュアライザーの図にリンクされているはずの Excel ブックが見つかりませんか? 再リンクして、すぐに業務を再開できます。[詳細情報](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-p233">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="ffbd9-1355">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1355">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="ffbd9-1356">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1356">Switching between them has never been easier.</span></span> [<span data-ttu-id="ffbd9-1357">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1357">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="ffbd9-1358">**Power BI から Visio ビジュアルをエクスポートする:** Power BI レポートを PDF、PowerPoint などのファイルとしてエクスポートするときに、Power BI 用の Visio ビジュアルが正しく表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1358">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="ffbd9-1359">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1359">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="ffbd9-1360">Word</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1360">Word</span></span>

- <span data-ttu-id="ffbd9-1361">**[学習ツール] モードで、ページで使用できる色が増えました:** Word の学習ツールでは、より多くのページ テーマ色が追加され、ページの背景色を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1361">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="ffbd9-1362">すべて白またはすべて黒の背景だと読みにくいと感じるユーザーは少なくないため、PC と Mac の Word で色の選択肢を拡大しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1362">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="ffbd9-p237">**インク エディターを使った自然な編集:** ペンを使って 1 ストローク描くだけで、単語の分割や結合、新しい線の追加、単語の挿入などができます。[詳細情報](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-p237">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="ffbd9-p238">**静的なドキュメントから魅力的なドキュメントへの変換:** ドキュメントを、すべてのデバイスに対応する対話型の使いやすい Web ページに変換します。[詳細情報](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-p238">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="ffbd9-1367">**コンテンツのリーチを拡大する:** ドキュメントのアクセシビリティを高める必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1367">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="ffbd9-1368">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1368">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="ffbd9-1369">[校閲]>[アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1369">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="ffbd9-1370">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1370">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="ffbd9-1371">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1371">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="ffbd9-1372">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1372">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="ffbd9-1373">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1373">Switching between them has never been easier.</span></span> [<span data-ttu-id="ffbd9-1374">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1374">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="ffbd9-p242">**行フォーカスによる読解力の向上:** ドキュメント内で行ごとの移動をスムーズに行います。一度に 1 行か、3 行か、5 行かを表示するようフォーカスを調整できます。[詳細情報](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-p242">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="ffbd9-1378">**変更時に変更内容を保存する:** すべての更新が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1378">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="ffbd9-1379">**\@メンションを使用してユーザーの注意を引く:** コメントで @メンションを使うと、仕事仲間による入力が必要な場合にそのユーザーに知らせることができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1379">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="ffbd9-1380">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1380">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="ffbd9-1381">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1381">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="ffbd9-1382">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1382">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="ffbd9-1383">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1383">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="ffbd9-1384">Office スイート</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1384">Office Suite</span></span>

- <span data-ttu-id="ffbd9-1385">**特定のファイルをすばやく見つける:** 最近作業を行ったファイルを探している場合は、</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1385">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="ffbd9-1386">[ファイル] > [開く] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1386">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="ffbd9-1387">**変更が発生したときに変更内容を自動的に保存する:** 変更が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1387">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="ffbd9-1388">**プライバシー制御**: 診断データとコネクテッド エクスペリエンス用に新しく更新されて、改善された制御。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1388">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="ffbd9-1389">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1389">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="ffbd9-1390">**新しい外観を備えた Office のアイコン:** シンプルかつ高性能で、インテリジェントな Office のエクスペリエンスを反映するように、Office のアイコンがリニューアルされました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1390">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="ffbd9-1391">**Microsoft Teams のインストール:** Microsoft Teams は、Office 365 ProPlus の既存のインストールに既定でインストールされています。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1391">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="ffbd9-1392">詳細情報</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1392">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-1395">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1395">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="ffbd9-1396">Access</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1396">Access</span></span>

- <span data-ttu-id="ffbd9-1397">この更新プログラムにより、Sum などの集計が結果を整数値に切り捨てる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1397">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="ffbd9-1398">この更新プログラムにより、リモート テーブル (SQL Server テーブルなど) への参照を含むユニオン クエリにより Access が閉じて再起動する問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1398">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="ffbd9-1399">この更新プログラムにより、更新クエリが実行されるか、SQL で UPDATE ステートメントが使用されるときに &quot;クエリは破損しています&quot; というエラーを発生させる場合のある Microsoft Access の問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1399">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="ffbd9-1400">Excel</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1400">Excel</span></span>

- <span data-ttu-id="ffbd9-1401">ドキュメント タイトルのオランダ語の KeyTip が Alt-G に変更されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1401">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="ffbd9-1402">図形やフォームコントロールに割り当てられているマクロが間違ったエラーメッセージとして表示される、または間違った対象範囲で動作する問題が Excel で修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1402">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="ffbd9-1403">最初のアイテムを検索した後に、ダイアログでのフォーカスの位置が変更されてしまう検索と置換についての問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1403">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="ffbd9-1404">これにより、ピボットテーブルの並べ替え方法を変更し、他のユーザーとの共同編集セッション中にそれを更新するとクラッシュが発生する可能性がある問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1404">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="ffbd9-1405">OLAP ピボットテーブルのフィルターが、キューブから削除された値に設定された場合の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1405">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="ffbd9-1406">グラフ テンプレートを使用してグラフを挿入する場合に、プレビューで正しい色が使用されるよう修正します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1406">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="ffbd9-1407">シリーズ コレクションを変更するときに、散布図が適切にレンダリングされない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1407">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="ffbd9-1408">セルが挿入または削除されたときに、ウォーターフォール図とじょうごグラフがテーブルと同期しなくなる原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1408">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="ffbd9-1409">Excel で、ユーザーが変更を取得するためにブックを再び開くよう要求されるマージ競合の問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1409">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="ffbd9-1410">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1410">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="ffbd9-1411">最小化されたウィンドウをアクティブにするマクロ実行時エラーの原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1411">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="ffbd9-1412">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1412">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="ffbd9-1413">他のユーザーと共同編集しているときに、テーブルの横にある切り取りと貼り付けの操作が失敗する原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1413">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="ffbd9-1414">実行中のマクロでカスタム プロパティを変更するときに、共同編集の中断を引き起こす原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1414">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="ffbd9-1415">アドインによって開かれた WPF (Windows Presentation Foundation) フォームのコンボ ボックスからアイテムを選ぶことができない問題が発生しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1415">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="ffbd9-1416">ブックが開かれていない状態で最近使用したファイルを検索するときに、クラッシュを発生させる原因となっていた可能性がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1416">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="ffbd9-1417">非同期のユーザー定義関数が同期して実行されるパフォーマンスの問題が発生しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1417">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="ffbd9-1418">結合されたセルで列を削除するパフォーマンスが大幅に改善されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1418">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="ffbd9-1419">スクロール後にセルを選択すると間違ったセルが選択されることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1419">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="ffbd9-1420">Lookup 関数がエラーを返す問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1420">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="ffbd9-1421">Office の以前のバージョンで作成されたブックを Office の最新のバージョンで開いたときに、Excel の終了を引き起こす可能性がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1421">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="ffbd9-1422">ファイルに広範な条件付き書式が設定されている場合に、[フォントの色] ボタンをクリックするとパフォーマンスが低下する問題。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1422">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="ffbd9-1423">印刷プレビューの印刷範囲が正しくないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1423">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="ffbd9-1424">信頼されていないネットワーク共有から保護されたファイルを編集する際に、Excel にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1424">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="ffbd9-1425">色によるフィルタリングのパフォーマンスが大幅に改善されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1425">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="ffbd9-1426">一部の保護されたシートにハイパーリンクが貼り付けられない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1426">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="ffbd9-1427">アドイン マネジャーで参照するときに、16 個を超えるアドインを表示できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1427">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="ffbd9-1428">この変更は、ソフトウェア レンダリングを活用することにより、特定の Intel グラフィック ドライバーの問題を回避します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1428">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="ffbd9-1429">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1429">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="ffbd9-1430">この更新プログラムにより、"アップロードできませんでした" というメッセージが表示され、Office ドキュメントが OneDrive for Business にアップロードされないことがあるエラーが修正されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1430">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="ffbd9-1431">Win32 クライアントの [アイデア] ボタンをクリックしてアドインを読み込むときにエラーが発生するという Excel のアイデア機能の問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1431">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="ffbd9-1432">Outlook</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1432">Outlook</span></span>

- <span data-ttu-id="ffbd9-1433">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1433">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="ffbd9-1434">メールボックスを基本認証から最新認証にアップグレードしたユーザーが、Outlook プロファイルに関連付けられた正しくないアカウントで終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1434">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="ffbd9-1435">Web アドインがデジタル著作権管理 (DRM) メッセージにアクセスすべきでないときにアクセスする原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1435">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="ffbd9-1436">一部のセーフリンクに対して簡易的なホバーの URL が正しく表示されなくなる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1436">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="ffbd9-1437">これにより、Python による添付ファイルもブロックされるよう、Outlook の添付ファイルのブロック ロジックが更新されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1437">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="ffbd9-1438">設定に関係なく、一部の POP3 ユーザーに、すべてのメールがプレーンテキストで書式設定されて表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1438">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="ffbd9-1439">この修正プログラムでは、HTML 形式のメッセージの表示が復元されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1439">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="ffbd9-1440">プライマリ予定表からグループ予定表にアイテムをコピーするときに、ユーザーにアクセス許可のエラーを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1440">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="ffbd9-1441">ユーザーがスクリーン リーダーから場所の候補にアクセスできない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1441">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="ffbd9-1442">ユーザーがキーボード ショートカットを使用してメールボックス フォルダーを操作するときに、顕著な遅延を発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1442">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="ffbd9-1443">非常に長い Outlook セッションでメモリ リークを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1443">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="ffbd9-1444">ユーザーが [ルール] ダイアログを開くと、"このコンピューターのルールは、Microsoft Exchange のルールと異なります" というメッセージが表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1444">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="ffbd9-1445">特定のセーフリンクを操作するときに、Outlook でクラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1445">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="ffbd9-1446">代理人が特定の会議出席依頼に既に返信したかどうかに関係なく、管理者が不明瞭になる原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1446">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="ffbd9-1447">一部の AutoDiscover の応答を処理するときに、クラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1447">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="ffbd9-1448">アカウント作成コンテキストからサポートに連絡しようとすると、ユーザーに [OK] ボタンのある空のメッセージ ボックスが表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1448">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="ffbd9-1449">この変更により、UPN 経由で自動検出の認証プロンプトに提供されるアカウントのメールを選択するため、ポリシーを管理者が有効にできるようになります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1449">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="ffbd9-1450">既定では、使用可能な場合に、自動検出ではアカウント UPN の方が選択されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1450">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="ffbd9-1451">最新のグループに対し、検索の失敗がユーザーに表示される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1451">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="ffbd9-1452">Outlook ユーザーが特定のシナリオで "パスワードを要求している" 状態で停止する原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1452">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="ffbd9-1453">会議室の空き時間外に行われた会議のためにユーザーにその会議室が提案される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1453">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="ffbd9-1454">ユーザーが暗号化されたメールを送信しようとするときに、"暗号化アルゴリズムがサポートされていません" というエラーを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1454">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="ffbd9-1455">英語以外の言語を使用するユーザーの、メールの件名が非常に小さくなるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1455">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="ffbd9-1456">一部のユーザーに、セカンダリ Exchange アカウントを追加するときに作成された、重複した特別なフォルダーが表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1456">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="ffbd9-1457">"不在着信した会話" メッセージのルールを作成しようとするときに、クラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1457">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="ffbd9-1458">SMIME アルゴリズムの選択に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1458">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="ffbd9-1459">代替送信者を使用しているときに、ポリシーのヒントが表示されない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1459">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="ffbd9-1460">ユーザーが Outlook プロセスでメモリ リークを観測する原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1460">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="ffbd9-1461">プレゼンス情報を更新するときに、断続的なクラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1461">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="ffbd9-1462">現在のフォルダー検索で断続的な失敗を引き起こす原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1462">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="ffbd9-1463">一部のユーザーが Outlook のクラウド設定を取得しようとするときに、認証エラーが発生する原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1463">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="ffbd9-1464">検索に関するフィードバックのエクスペリエンスで終了する原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1464">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="ffbd9-1465">一部の AutoDiscover の応答を処理するときに、クラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1465">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="ffbd9-1466">プレゼンス情報を更新するときに、断続的なクラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1466">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ffbd9-1467">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1467">PowerPoint</span></span>

- <span data-ttu-id="ffbd9-1468">一部のアドインがグラフの図形に対して予期しないエラーをスローさせる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1468">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="ffbd9-1469">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1469">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="ffbd9-1470">この変更により、PowerPoint ビデオ コントロールのアクセス可能な名前が復元されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1470">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="ffbd9-1471">一部のアニメーションが開始しないことがあるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1471">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="ffbd9-1472">スライドを 1 つのプレゼンテーションから別のプレゼンテーションにコピーすると、重複したマスターが作成される可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1472">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="ffbd9-1473">最新のコメントを含むファイルを、サポートされていないバージョンで開くと黄色の警告が表示されます</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1473">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="ffbd9-1474">信頼性の修正: サード パーティのアドインが PowerPoint のクラッシュを発生させる可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1474">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="ffbd9-1475">PowerPoint の垂直テキスト ボックスで半角カタカナ文字が適切に回転しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1475">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="ffbd9-1476">Project</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1476">Project</span></span>

- <span data-ttu-id="ffbd9-1477">Windows 7 のユーザーが Project Web App および SharePoint サイトからプロジェクトを開くことができるように問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1477">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="ffbd9-1478">読み取り専用のプロジェクトを開いたときに複数のメッセージを取得する可能性があるという問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1478">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="ffbd9-1479">[すべて平準化] コマンドがリソースの割り当て超過を適切に解決しません。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1479">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="ffbd9-1480">タスクの作業がゼロの割り当てがある場合、タスクに完了のマークを付けることができず、常に 99％ で表示される問題。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1480">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="ffbd9-1481">Visio</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1481">Visio</span></span>

- <span data-ttu-id="ffbd9-1482">Visio から SVG へのエクスポートが、さまざまな図形で失敗していました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1482">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="ffbd9-1483">Word</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1483">Word</span></span>

- <span data-ttu-id="ffbd9-1484">この変更により、Word を使ってドキュメントを開くときのパフォーマンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1484">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="ffbd9-1485">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1485">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="ffbd9-1486">Deskjet プリンターに印刷するときに、スケーリングの問題を引き起こす可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1486">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="ffbd9-1487">無限ループになることがあるトラック変更の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1487">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="ffbd9-1488">シャットダウン時にアプリが終了することがあるさまざまな問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1488">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="ffbd9-1489">特定のアドインに関連するクラッシュも修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1489">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="ffbd9-1490">Office スイート</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1490">Office Suite</span></span>

- <span data-ttu-id="ffbd9-1491">新元号の名前である “Reiwa” のひらがなと漢字をスペルミスまたは間違った文法として誤って識別していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1491">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="ffbd9-1492">SharePoint 2016 に保存されているファイルを共有しようとするときに、"申し訳ございません。何かがこのファイルの共有を妨げています。" というメッセージが表示される原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1492">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="ffbd9-1493">PowerPoint での共同編集とオフライン編集の両方を含むセッションでデータの損失を引き起こす可能性のある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1493">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="ffbd9-1494">これは、ユーザーがファイルを開くときに発生する可能性のあるクラッシュの修正プログラムです。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1494">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="ffbd9-1495">PowerPoint ユーザーがオンライン プレゼンテーションを行おうとするときに、エラーが発生しないようにします。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1495">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="ffbd9-1496">同期エンジンでバックアップされた Sharepoint ファイルに '保存済み' と表示されますが、場合によっては実際に変更が保存されないため、データを損失することになります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1496">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="ffbd9-1497">ユーザーが Word、Excel、および PowerPoint のドキュメントを保存できなくなることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1497">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="ffbd9-1498">この問題は、[保存] アイコンをクリックしたり Ctrl キーを押しながら S キーを押したりした後に、新しいファイルを作成して [ダイアログで保存] オプションを表示するユーザーに影響を与えます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1498">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="ffbd9-1499">すべてのアプリのリボンで、図形の挿入ギャラリーが表示されるまでに約 4 秒かかるという Win7 のパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1499">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="ffbd9-1500">Backstage の Info Place のスラブにアクセシビリティ情報が表示されていないというバグを修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1500">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="ffbd9-1501">レジストリ整合性に関する Office 更新プロセスの信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1501">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="ffbd9-1502">Office の更新プログラムが、意図したソース (ローカル共有、ネットワーク共有、構成マネージャー
で提供される場所など) からではなく、予期せずに Office CDN からファイルをダウンロードする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1502">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="ffbd9-1503">Office の更新メッセージが、異なる言語で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1503">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="ffbd9-1504">今後、Office の更新メッセージは Windows の表示言語と一致します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1504">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="ffbd9-1505">ユーザーが管理者ではなく、システム アカウントにネットワーク接続が確立されていない場合に、更新プログラムが適用されない問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1505">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="ffbd9-1506">特定の状況で、更新後に Office ショートカットが消えてしまう場合があります。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1506">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="ffbd9-1507">この更新プログラムにより、Office ショートカットを公開するときの信頼性が向上します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1507">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="ffbd9-1508">従量制課金ネットワークで更新プログラムが予期せずブロックされる可能性があるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1508">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="ffbd9-1509">ODT と GPO の更新期限設定で、相対期限の設定後、初回のみしか機能しないバスが修正されました。修正により、2 回目以降の更新プログラムで相対期限を使用きるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1509">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="ffbd9-1510">以前に中断された可能性のあるダウンロードを再開することにより、Office の更新プログラムをダウンロードするときの信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1510">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="ffbd9-1511">サード パーティ製プラグインのテキスト ボックスと図形の自動調整に関連する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1511">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="ffbd9-1512">大きなツリー ビューがクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1512">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="ffbd9-1513">Office ユーザーのセキュリティを保護するために、Microsoft Office の更新プログラムは SHA-2 アルゴリズムのみを使用して署名されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1513">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1902-january-14"></a><span data-ttu-id="ffbd9-1515">バージョン 1902: 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1515">Version 1902: January 14</span></span>
<span data-ttu-id="ffbd9-1516">*バージョン 1902 (ビルド 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1516">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="ffbd9-1517">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1517">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="ffbd9-1519">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1519">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="ffbd9-1520">Excel</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1520">Excel</span></span>

- <span data-ttu-id="ffbd9-1521">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1521">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="ffbd9-1522">Outlook</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1522">Outlook</span></span>

- <span data-ttu-id="ffbd9-1523">ユーザーが暗号化されたメールを送信しようとするときに、"暗号化アルゴリズムがサポートされていません" というエラーを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1523">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="ffbd9-1524">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1524">PowerPoint</span></span>

- <span data-ttu-id="ffbd9-1525">最新のコメントを含むファイルを、サポートされていないバージョンで開くと黄色の警告が表示されます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1525">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="ffbd9-1526">Word</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1526">Word</span></span>

- <span data-ttu-id="ffbd9-1527">この変更により、Word を使ってドキュメントを開くときのパフォーマンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1527">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1808-january-14"></a><span data-ttu-id="ffbd9-1529">バージョン 1808: 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1529">Version 1808: January 14</span></span>
<span data-ttu-id="ffbd9-1530">*バージョン 1808 (ビルド 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1530">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="ffbd9-1531">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1531">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

> [!NOTE]
> <span data-ttu-id="ffbd9-1533">Office の使用で問題がある場合は、[Microsoft の回答フォーラム](https://answers.microsoft.com/)に関するページまたは「[Microsoft Tech Community](https://techcommunity.microsoft.com/)」に質問を投稿するか、[サポート](https://support.microsoft.com/contactus)に問い合わせてサポートを受けることができます。</span><span class="sxs-lookup"><span data-stu-id="ffbd9-1533">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (管理センターのメタデータのコンテンツを変更しないでください。開始)
[//]: # (|Win32|DC|Production| |16.0.13127.21216|version-2008-february-09|)
[//]: # (|Win32|DC|Production| |16.0.13127.21064|version-2008-january-12|)
[//]: # (|Win32|DC|Production| |16.0.12527.21416|バージョン-2002-12 月-08|)
[//]: # (|Win32|DC|Production| |16.0.12527.21330|version-2002-november-10|)
[//]: # (|Win32|DC|Production| |16.0.12527.21236|version-2002-october-13|)
[//]: # (|Win32|DC|Production| |16.0.12527.21104|version-2002-september-08|)
[//]: # (|Win32|DC|Production| |16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|DC|Production| |16.0.12527.20880|バージョン-2002-7 月-14|)
[//]: # (管理センターのメタデータのコンテンツ エンドを変更しないでください)
