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
ms.openlocfilehash: 9e420ed8c7c6f5c329b3137f21b952f7a29af7e1
ms.sourcegitcommit: b7cd1fc37ece6cf0399d89549f7916a4dc40d829
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/16/2020
ms.locfileid: "47942774"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-releases-in-2020"></a><span data-ttu-id="2c202-103">2020 年の半期エンタープライズ チャネル リリースのリリース ノート</span><span class="sxs-lookup"><span data-stu-id="2c202-103">Release notes for Semi-Annual Enterprise Channel releases in 2020</span></span>

<span data-ttu-id="2c202-104">このリリース ノートには、2020 年の半期エンタープライズ チャネルの更新プログラムに含まれる新機能と、セキュリティ以外の更新プログラムに関する情報が記載されています。対象となるのは、Microsoft 365 Apps for enterprise、Microsoft 365 Apps for business、および Project と Visio のデスクトップ アプリのサブスクリプション版です。</span><span class="sxs-lookup"><span data-stu-id="2c202-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="2c202-105">現在、Microsoft 365 Apps の更新プログラム チャネルに、新しい更新プログラム チャネル (月次エンタープライズ チャネル) の追加や既存の更新プログラム チャネル名の変更など、いくつかの変更を進めています。</span><span class="sxs-lookup"><span data-stu-id="2c202-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="2c202-106">詳細については、[こちらの記事](https://go.microsoft.com/fwlink/p/?linkid=2127441)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="2c202-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
>
>- <span data-ttu-id="2c202-107">半期エンタープライズ チャネルのユーザーが Office ポータルから Microsoft 365 Apps をダウンロードして Windows 10 にインストールすると、既定で OneNote 2016 が含まれるようになります。</span><span class="sxs-lookup"><span data-stu-id="2c202-107">OneNote 2016 will now be included by default when a user on the Semi-Annual Enterprise Channel downloads and installs Microsoft 365 Apps on Windows 10 from the Office Portal.</span></span>


[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2002-september-08"></a><span data-ttu-id="2c202-109">バージョン 2002: 9 月 08 日</span><span class="sxs-lookup"><span data-stu-id="2c202-109">Version 2002: September 08</span></span>
<span data-ttu-id="2c202-110">*バージョン2002 (ビルド12527.21104)*</span><span class="sxs-lookup"><span data-stu-id="2c202-110">*Version 2002 (Build 12527.21104)*</span></span>

<span data-ttu-id="2c202-111">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2c202-111">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2c202-113">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2c202-113">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2c202-114">Excel</span><span class="sxs-lookup"><span data-stu-id="2c202-114">Excel</span></span>

- <span data-ttu-id="2c202-115">これは、以前のバージョンの Office で SQL データプロバイダーによって作成された接続が内部テーブルのプロパティを Office 365 とは別に設定する問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="2c202-115">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="2c202-116">これにより、Office 365 を使用して開かれた以前のバージョンの Office で作成された接続を持つファイルに対して、[テーブルのプレビュー / クエリエディター] のドロップダウンが無効になりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-116">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>


- <span data-ttu-id="2c202-117">手描き入力で Excel が応答しなくなる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-117">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="2c202-118">Outlook</span><span class="sxs-lookup"><span data-stu-id="2c202-118">Outlook</span></span>

- <span data-ttu-id="2c202-119">共有メールボックスを追加した後に、ユーザーがパブリック フォルダーに接続できない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-119">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2c202-120">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2c202-120">Office Suite</span></span>

- <span data-ttu-id="2c202-121">この変更では、[図の圧縮] ダイアログで一部のユーザー設定が保持されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-121">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-1908-september-08"></a><span data-ttu-id="2c202-123">バージョン 1908: 9 月 08 日</span><span class="sxs-lookup"><span data-stu-id="2c202-123">Version 1908: September 08</span></span>
<span data-ttu-id="2c202-124">*バージョン 1908 (ビルド11929.20946)*</span><span class="sxs-lookup"><span data-stu-id="2c202-124">*Version 1908 (Build 11929.20946)*</span></span>

<span data-ttu-id="2c202-125">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2c202-125">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-august-11"></a><span data-ttu-id="2c202-126">バージョン 2002: 8 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2c202-126">Version 2002: August 11</span></span>
<span data-ttu-id="2c202-127">*バージョン 2002 (ビルド 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="2c202-127">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="2c202-128">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2c202-128">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2c202-130">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2c202-130">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2c202-131">Excel</span><span class="sxs-lookup"><span data-stu-id="2c202-131">Excel</span></span>

- <span data-ttu-id="2c202-132">「読み取り専用推奨」として開かれたファイルの編集に切り替えられない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-132">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="2c202-133">OneNote</span><span class="sxs-lookup"><span data-stu-id="2c202-133">OneNote</span></span>

- <span data-ttu-id="2c202-134">リソースの使用率を低下させるための冗長な ID 呼び出しが削除されました</span><span class="sxs-lookup"><span data-stu-id="2c202-134">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="2c202-135">リソースの使用率を低下させて、共同編集状態の検出機能を改善します。</span><span class="sxs-lookup"><span data-stu-id="2c202-135">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="2c202-136">エラーを検出する機能が改善され、同期環境の品質が向上しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-136">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="2c202-137">Outlook</span><span class="sxs-lookup"><span data-stu-id="2c202-137">Outlook</span></span>

- <span data-ttu-id="2c202-138">一部のテナントで Outlook を起動したときに重大なパフォーマンスの問題が発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-138">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="2c202-139">Skype</span><span class="sxs-lookup"><span data-stu-id="2c202-139">Skype</span></span>

- <span data-ttu-id="2c202-140">数日間稼働した後に、32 ビット版の Skype for Business クライアントで画面共有を開始できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-140">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2c202-141">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2c202-141">Office Suite</span></span>

- <span data-ttu-id="2c202-142">グループ ポリシーを介して自動保存が無効にされた場合に、ユーザーが [利用可能な更新] をクリックするまで一部のドキュメントで最新のサーバー コンテンツが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-142">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-august-11"></a><span data-ttu-id="2c202-144">バージョン 1908: 8 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2c202-144">Version 1908: August 11</span></span>
<span data-ttu-id="2c202-145">*バージョン 1908 (ビルド 11929.20934)*</span><span class="sxs-lookup"><span data-stu-id="2c202-145">*Version 1908 (Build 11929.20934)*</span></span>

<span data-ttu-id="2c202-146">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2c202-146">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1902-august-11"></a><span data-ttu-id="2c202-147">バージョン 1902: 8 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2c202-147">Version 1902: August 11</span></span>
<span data-ttu-id="2c202-148">*バージョン 1902 (ビルド 11328.20644)*</span><span class="sxs-lookup"><span data-stu-id="2c202-148">*Version 1902 (Build 11328.20644)*</span></span>

<span data-ttu-id="2c202-149">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2c202-149">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-july-14"></a><span data-ttu-id="2c202-152">バージョン 2002: 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2c202-152">Version 2002: July 14</span></span>
<span data-ttu-id="2c202-153">*バージョン 2002 (ビルド 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="2c202-153">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="2c202-154">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2c202-154">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2c202-156">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2c202-156">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2c202-157">Access</span><span class="sxs-lookup"><span data-stu-id="2c202-157">Access</span></span>

- <span data-ttu-id="2c202-158">**リンク テーブルをすばやく見つける:** 新しい検索ボックスを使用すると、リンク テーブルを簡単に見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="2c202-158">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="2c202-159">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-159">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="2c202-160">Excel</span><span class="sxs-lookup"><span data-stu-id="2c202-160">Excel</span></span>

- <span data-ttu-id="2c202-161">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="2c202-161">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="2c202-162">**データ ビジュアライザー アドイン:** Excel から Visio フローチャートをすばやく作成します。</span><span class="sxs-lookup"><span data-stu-id="2c202-162">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="2c202-163">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-163">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="2c202-164">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="2c202-164">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="2c202-165">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-165">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="2c202-166">[ブログの投稿](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2c202-166">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="2c202-167">**自分の気分を表現するアイコンの追加:** 300 個以上の新しいアイコンが追加されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-167">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="2c202-168">[挿入]、[アイコン] の順に検索してください。</span><span class="sxs-lookup"><span data-stu-id="2c202-168">Find them at Insert > Icons.</span></span> [<span data-ttu-id="2c202-169">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-169">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="2c202-170">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="2c202-170">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="2c202-171">[ブログの投稿](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2c202-171">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="2c202-172">**残っている作業に集中する:** [解決] を選択して、コメントを折りたたみ、開いているアイテムを目立たせます。</span><span class="sxs-lookup"><span data-stu-id="2c202-172">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="2c202-173">**複数の値を返す式を入力する:** 複数の値を返す式を素早く入力できるようになりました。隣接するセルに自動的に入力されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-173">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="2c202-174">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-174">Learn more</span></span>](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br /><span data-ttu-id="2c202-175">[ブログの投稿](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2c202-175">See details in [blog post](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span></span>

- <span data-ttu-id="2c202-176">**ブラウザーへのバウンスは不要** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定します。</span><span class="sxs-lookup"><span data-stu-id="2c202-176">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="2c202-177">**あらましを描く:** ブック内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="2c202-177">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="2c202-178">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-178">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="2c202-179">[ブログの投稿](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2c202-179">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="2c202-180">**探しているものを見つける:** コマンド、ユーザー、ファイル、写真、Web の記事などを検索できます。</span><span class="sxs-lookup"><span data-stu-id="2c202-180">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="2c202-181">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-181">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="2c202-182">**6 つの強力な機能:** スプレッドシートを強化する 6 つの新しい関数が追加されました。FILTER、SORT、SORTBY、UNIQUE、SEQUENCE、RANDARRAY です。</span><span class="sxs-lookup"><span data-stu-id="2c202-182">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span> [<span data-ttu-id="2c202-183">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-183">Learn more</span></span>](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- <span data-ttu-id="2c202-184">**左を見て、右を見て... XLOOKUP をご利用いただけます!** XLOOKUP を使えば、表や範囲内で必要なものは何でも見つけられます。</span><span class="sxs-lookup"><span data-stu-id="2c202-184">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="2c202-185">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-185">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br /><span data-ttu-id="2c202-186">[ブログの投稿](https://blog-insider.office.com/2019/08/29/announcing-xlookup/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2c202-186">See details in [blog post](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span></span>

- <span data-ttu-id="2c202-187">**大きなブックを使いこなす:** セル、数式、グラフ、テーブル...ブックの統計情報を使用して、ブックのスナップショットを取得します。</span><span class="sxs-lookup"><span data-stu-id="2c202-187">**Tame your big workbook:** Cells, formulas, charts, tables... get a snapshot of your workbook with Workbook Statistics.</span></span>

- <span data-ttu-id="2c202-188">**すぐに読んで返信する:** ブックを開かずに、メールからコメントやメンションに直接返信します。</span><span class="sxs-lookup"><span data-stu-id="2c202-188">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="2c202-189">**\@メンションを使用してユーザーの注意を引く:** コメントで @メンションを使うと、仕事仲間による入力が必要な場合にそのユーザーに知らせることができます。</span><span class="sxs-lookup"><span data-stu-id="2c202-189">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="2c202-190">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-190">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="outlook"></a><span data-ttu-id="2c202-191">Outlook</span><span class="sxs-lookup"><span data-stu-id="2c202-191">Outlook</span></span>

- <span data-ttu-id="2c202-192">**より多くのメッセージを画面に収める:** [表示] > [より狭い文字間隔を使用] の順に選択し、メッセージの間隔を調整します。</span><span class="sxs-lookup"><span data-stu-id="2c202-192">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="2c202-193">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-193">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="2c202-194">**自分の気分を表現するアイコンの追加:** 300 個以上の新しいアイコンが追加されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-194">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="2c202-195">[挿入]、[アイコン] の順に検索してください。</span><span class="sxs-lookup"><span data-stu-id="2c202-195">Find them at Insert > Icons.</span></span> [<span data-ttu-id="2c202-196">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-196">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="2c202-197">**自分で描いて表現しましょう:** 画像の上に走り書きするか、描画キャンバスを追加して、インクを用いて自分の考えを送信します。</span><span class="sxs-lookup"><span data-stu-id="2c202-197">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="2c202-198">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-198">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="2c202-199">**場所の候補を取得する:** 予定や会議をスケジュールするときに、[場所] に入力すると、会議室、住所、およびその他の最新の場所が提示されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-199">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="2c202-200">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-200">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)<br /><span data-ttu-id="2c202-201">[ブログの投稿](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2c202-201">See details in [blog post](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span></span>

- <span data-ttu-id="2c202-202">**攻撃に対する高度な保護:** Office 365 Advanced Threat Protection を用いると、メールの件名、添付メッセージ、署名されたメッセージ、ネットワーク パスなどの範囲内のハイパーリンクを利用した攻撃から保護されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-202">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="2c202-203">**テナント管理者によって定義されたアクセス許可を使用して、Outlook の [リンクの挿入] メニューでリンクを挿入する:** Outlook で最近使用されたリンクの挿入 (MRU) のリンクでは、既にそれに対するアクセス許可を持つユーザーのみに動作したリンクが挿入されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-203">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="2c202-204">これは、ドキュメントへのアクセス権の付与を求めるユーザー間でのメールの行き来をしばしば引き起こします。</span><span class="sxs-lookup"><span data-stu-id="2c202-204">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="2c202-205">このエクスペリエンスが更新されましたので、テナント管理者によって設定される既定のアクセス許可を使用し、リンクを挿入できるようになりました。MSIT の場合、これは「組織は編集可」なので、この方法で共有されるリンクを受信するすべての内部ユーザーもアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="2c202-205">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="2c202-206">**異なる明るさでメッセージを表示する:** [太陽] または [月] のボタンを使用して、閲覧ウィンドウの明るい背景と暗い背景を切り替えます。</span><span class="sxs-lookup"><span data-stu-id="2c202-206">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="2c202-207">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-207">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="2c202-208">**フィッシング メールの見分けが簡単に:** スパムとフィッシングのメッセージの外観が他とは異なるので、簡単に見分け、受信トレイから削除できます。</span><span class="sxs-lookup"><span data-stu-id="2c202-208">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="2c202-p119">**すべての暗号化オプションを 1 か所に集約:** [オプション] > [暗号化] の順に移動するだけで、電子メール メッセージを保護する方法を選択できます。[詳細情報](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="2c202-p119">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="2c202-211">**スペルチェックの問題や入力ミスで検索する:** スペルが一致しない場合でも何を検索しているか Outlook が探します。</span><span class="sxs-lookup"><span data-stu-id="2c202-211">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="2c202-212">\*\* Outlook に LinkedIn ネットワークを接続する:\*\* LinkedIn アカウントを Microsoft アカウントに安全に接続して、LinkedIn プロファイルからの情報を [連絡先カード] に直接表示できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-212">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="2c202-213">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-213">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="2c202-214">**検索結果で関連メッセージを確認する:** Outlook では検索条件を分析し、最も関連性の高いメール メッセージを検索結果の上部に表示します。</span><span class="sxs-lookup"><span data-stu-id="2c202-214">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="2c202-215">また、[上位の結果] セクションには、すべての結果が日付順に表示されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-215">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="2c202-216">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-216">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

### <a name="powerpoint"></a><span data-ttu-id="2c202-217">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2c202-217">PowerPoint</span></span>

- <span data-ttu-id="2c202-218">**手書きの数式の自動書式設定:** 手書きの数式を標準の文字に変換することができます。</span><span class="sxs-lookup"><span data-stu-id="2c202-218">**You compute, we format:** We change hand-drawn math expressions into standard characters.</span></span> <span data-ttu-id="2c202-219">変換を開始するには、[インクから数式] を選択して、手書きのメモを選択します。</span><span class="sxs-lookup"><span data-stu-id="2c202-219">Just choose Ink to Math and select your handwritten notes to get started.</span></span> [<span data-ttu-id="2c202-220">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-220">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="2c202-221">**探しているものを見つける:**[検索] ボックスを使用して、テキスト、コマンド、ヘルプなどを探します。</span><span class="sxs-lookup"><span data-stu-id="2c202-221">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="2c202-222">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-222">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="2c202-223">**インクで素晴らしいスライドを作成する:** インクを標準的な図形やテキストに変換してから、PowerPoint デザイナーの洗練されたスライドのデザイン アイデアを活用できます。</span><span class="sxs-lookup"><span data-stu-id="2c202-223">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="2c202-224">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-224">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="2c202-225">**あらましを描く:** プレゼンテーション内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="2c202-225">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="2c202-226">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-226">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="2c202-227">[ブログの投稿](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2c202-227">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="2c202-228">**インクを瞬時に再生:** スライドで手描き入力する場合は、スライド ショー中にアニメーションの再生を適用して、インクの実際の描画が再生されるようにします。</span><span class="sxs-lookup"><span data-stu-id="2c202-228">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="2c202-229">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-229">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)<br /><span data-ttu-id="2c202-230">[ブログの投稿](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2c202-230">See details in [blog post](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span></span>

- <span data-ttu-id="2c202-231">**より安全なビデオ エクスペリエンス:** セキュリティの強化は、より安全なオンライン ビデオ エクスペリエンスを意味します。</span><span class="sxs-lookup"><span data-stu-id="2c202-231">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="2c202-232">**図を SVG として保存する:** グラフ、図形、その他の図を、サイズ変更しても画質が低下しないスケーラブル ベクター グラフィックとして保存できます。</span><span class="sxs-lookup"><span data-stu-id="2c202-232">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="2c202-233">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-233">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="2c202-234">**配布資料にスライド番号を印刷する:** スライド番号は配布資料に自動的に含まれます。</span><span class="sxs-lookup"><span data-stu-id="2c202-234">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="2c202-235">それらをオンのままにするか、オフにするか、選択します。</span><span class="sxs-lookup"><span data-stu-id="2c202-235">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="2c202-236">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-236">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="2c202-237">**欠落しているスライド タイトルを見つけて修正する:** スライド タイトルは、ピッチにパンチを加え、すべてのユーザーがスライドにアクセスできるようにします。</span><span class="sxs-lookup"><span data-stu-id="2c202-237">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="2c202-238">アクセシビリティ ​​チェックは、タイトルがない場所を表示します。これにより、タイトルを簡単に追加できます。</span><span class="sxs-lookup"><span data-stu-id="2c202-238">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="2c202-239">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-239">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="2c202-240">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="2c202-240">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="2c202-241">[ブログの投稿](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2c202-241">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="2c202-242">**自分の気分を表現するアイコンの追加:** 300 個以上の新しいアイコンが追加されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-242">**More icons to match your mood:** We've added more than 300 new icons.</span></span> <span data-ttu-id="2c202-243">[挿入]、[アイコン] の順に検索してください。</span><span class="sxs-lookup"><span data-stu-id="2c202-243">Find them at Insert > Icons.</span></span> [<span data-ttu-id="2c202-244">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-244">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="2c202-245">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="2c202-245">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span><br /><span data-ttu-id="2c202-246">[ブログの投稿](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2c202-246">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="2c202-247">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルのリストからドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="2c202-247">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="2c202-248">**PowerPoint におけるリアルタイム コラボレーションが高速に:** PowerPoint でリアルタイム コラボレーションを高速で行えます。</span><span class="sxs-lookup"><span data-stu-id="2c202-248">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="2c202-249">**ブラウザーへのバウンスは不要:** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定します。</span><span class="sxs-lookup"><span data-stu-id="2c202-249">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="2c202-250">**新しい文書校正ツール:** 記述する内容についてストレスを感じる必要はありません。</span><span class="sxs-lookup"><span data-stu-id="2c202-250">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="2c202-251">PowerPoint で、文法や書き方の推奨事項が提示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-251">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="2c202-252">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-252">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="2c202-253">**ライブ キャプションと字幕:** 発表者の言葉が、キャプションまたは選択した言語での字幕として自動的に画面に表示されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-253">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="2c202-254">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-254">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="2c202-255">**プレゼンテーションの最適化:** アクセシビリティ チェックを使用すると、スクリーン リーダーを考慮に入れて、スライド上のオブジェクトを配置することができます。</span><span class="sxs-lookup"><span data-stu-id="2c202-255">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span><br /><span data-ttu-id="2c202-256">[ブログの投稿](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2c202-256">See details in [blog post](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span></span>

- <span data-ttu-id="2c202-257">**再利用しませんか?:** 作成した、または他のユーザーと共有しているスライドを再利用して時間を節約します。</span><span class="sxs-lookup"><span data-stu-id="2c202-257">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="2c202-258">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-258">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

### <a name="visio"></a><span data-ttu-id="2c202-259">Visio</span><span class="sxs-lookup"><span data-stu-id="2c202-259">Visio</span></span>

- <span data-ttu-id="2c202-260">**Excel で洗練された Visio 図を作成する:** ワークシートにデータを入力して、フロー チャートまたは組織図を作成します。</span><span class="sxs-lookup"><span data-stu-id="2c202-260">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="2c202-261">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-261">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="2c202-262">**犯行現場に戻る:** [犯罪現場] 調査テンプレートで新しい [証拠]、[室内]、および [屋外] のステンシルを使用して、犯罪現場を詳細に再現します。</span><span class="sxs-lookup"><span data-stu-id="2c202-262">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

### <a name="word"></a><span data-ttu-id="2c202-263">Word</span><span class="sxs-lookup"><span data-stu-id="2c202-263">Word</span></span>

- <span data-ttu-id="2c202-264">**より安全なビデオ エクスペリエンス:** セキュリティの強化は、より安全なオンライン ビデオ エクスペリエンスを意味します。</span><span class="sxs-lookup"><span data-stu-id="2c202-264">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="2c202-265">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-265">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="2c202-266">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="2c202-266">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="2c202-267">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-267">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="2c202-268">[ブログの投稿](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2c202-268">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="2c202-269">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルのリストからドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="2c202-269">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="2c202-270">**自分の気分を表現するアイコンの追加:** 300 個以上の新しいアイコンが追加されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-270">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="2c202-271">[挿入]、[アイコン] の順に検索してください。</span><span class="sxs-lookup"><span data-stu-id="2c202-271">Find them at Insert > Icons.</span></span> [<span data-ttu-id="2c202-272">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-272">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)<br /><span data-ttu-id="2c202-273">[ブログの投稿](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2c202-273">See details in [blog post](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span></span>

- <span data-ttu-id="2c202-274">**精度による消去:** 手描き入力の小さな不備を修正するのに、2 つのサイズの消しゴムから選択できます。</span><span class="sxs-lookup"><span data-stu-id="2c202-274">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="2c202-275">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-275">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="2c202-276">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="2c202-276">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="2c202-277">[ブログの投稿](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2c202-277">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="2c202-278">**あらましを描く:** ドキュメント内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="2c202-278">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="2c202-279">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-279">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="2c202-280">[ブログの投稿](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="2c202-280">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="2c202-281">**探しているものを見つける:**[検索] ボックスを使用して、テキスト、コマンド、ヘルプなどを探します。</span><span class="sxs-lookup"><span data-stu-id="2c202-281">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="2c202-282">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-282">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="2c202-283">**ブラウザーへのバウンスは不要** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定します。</span><span class="sxs-lookup"><span data-stu-id="2c202-283">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="2c202-284">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-284">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="2c202-285">**Editor for Resume が LinkedIn 履歴書アシスタントに参加する:** Editor for Resume では履歴書に特化した文法とスタイルのチェックを選択できます。この機能は、より正確かつ専門的に作成するの役立ちます。</span><span class="sxs-lookup"><span data-stu-id="2c202-285">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="2c202-286">**他のユーザーがすばやく変更を確認する:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="2c202-286">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="2c202-287">**3D オブジェクトのマージによって引き起こされるドキュメント破損の問題を修正しました。:** 3D オブジェクトのマージによって引き起こされるドキュメント破損の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-287">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="2c202-288">**共同編集の改善:** 変更を追跡したドキュメントで共同編集を行う際の Word のパフォーマンスが改善されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-288">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="2c202-289">**共同編集の改善:** 共同編集時の信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-289">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="2c202-290">**鮮やかな色で共同作業する:** コメントや変更内容のカラー コードが共同作成者によって指定され、共同作成者のうちのだれによって行われたかが簡単にわかります。</span><span class="sxs-lookup"><span data-stu-id="2c202-290">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="2c202-291">**マクロ有効文書を共同作業で編集する:** 文書ファイルを OneDrive for Business に保存し、リアルタイムで共同作成者は編集できます。</span><span class="sxs-lookup"><span data-stu-id="2c202-291">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2c202-292">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2c202-292">Office Suite</span></span>

- <span data-ttu-id="2c202-293">**手書きのインクを図形やテキスト、または Office 365 の PowerPoint での数式に変換する:** フリーフォームのインクを Office の図形、テキスト、数式に数ストロークで変換します。</span><span class="sxs-lookup"><span data-stu-id="2c202-293">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="2c202-294">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-294">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2c202-297">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2c202-297">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2c202-298">Access</span><span class="sxs-lookup"><span data-stu-id="2c202-298">Access</span></span>

- <span data-ttu-id="2c202-299">この更新プログラムでは、ADODB を使用する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="2c202-299">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="2c202-300">VB コードのれコーター オブジェクトがエラーを誤って報告することがあります。</span><span class="sxs-lookup"><span data-stu-id="2c202-300">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="2c202-301">Access テンプレートは、データベース内の添付ファイル列のエラーを発生させることがなくなりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-301">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="2c202-302">テンプレートのインスタンス化後に、データベースに添付ファイル フィールドを追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-302">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="2c202-303">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-303">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="2c202-304">この更新プログラムにより、更新クエリが実行されるか、SQL で UPDATE ステートメントが使用されるときに "クエリは破損しています" というエラーを発生させる場合のある Microsoft Access の問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-304">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="2c202-305">Excel</span><span class="sxs-lookup"><span data-stu-id="2c202-305">Excel</span></span>

- <span data-ttu-id="2c202-306">ローカルの OneDrive フォルダーで使用できるファイルの読み込み速度を向上します。</span><span class="sxs-lookup"><span data-stu-id="2c202-306">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="2c202-307">CUBEVALUE 関数が間違った結果を返すことがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-307">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="2c202-308">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-308">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="2c202-309">Word または PowerPoint に埋め込まれたブックをもう一度開くと、場合によっては Excel がクラッシュする可能性があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-309">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="2c202-310">コンテキスト メニューのコメント コマンドが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-310">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="2c202-311">ピボット グラフの右クリック メニューを修正して、[詳細の表示] オプションを有効にしました。</span><span class="sxs-lookup"><span data-stu-id="2c202-311">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="2c202-312">ブックが開かれていない状態で最近使用したファイルを検索するときに、クラッシュを発生させる原因となっていた可能性がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-312">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="2c202-313">同じブック内でブックマークされたハイパーリンクをクリックすると、ブックが非表示になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-313">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="2c202-314">CSV ファイルとして保存する場合、Excel はすべての列を 1 つの列にマージする場合があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-314">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="2c202-315">保護されたシートの範囲で Range.ClearContents を使用すると、予想よりも時間がかかる場合があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-315">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="2c202-316">[印刷プレビュー] に表示されるときのフォーム コントロール内のテキストの拡大縮小に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-316">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="2c202-317">リボンを操作する VBA マクロは、ScreenUpdating が True に設定されていると予期せず実行される場合があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-317">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="2c202-318">ピボットテーブルを含むシートをコピーした後、Excel がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-318">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="2c202-319">状況によっては、CSV ファイルを開くのに予想より時間がかかっていました。</span><span class="sxs-lookup"><span data-stu-id="2c202-319">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="2c202-320">Excel では、異なる拡大レベルでブックを切り替えるとクラッシュすることがあります。</span><span class="sxs-lookup"><span data-stu-id="2c202-320">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="2c202-321">値の範囲への入力に予想より時間がかかる VBA の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-321">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="2c202-322">色でフィルター処理された列からコピーしたデータは、正しく貼り付けられない場合があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-322">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="2c202-323">特に非表示のウィンドウで、多数のその他のブックを参照しながらブックを開くと、予想よりも時間がかかります。</span><span class="sxs-lookup"><span data-stu-id="2c202-323">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="2c202-324">ソース ブックが閉じていると、外部リンクが塗りつぶし (下方向に塗りつぶし、全体に塗りつぶしなど) 時に更新されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-324">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is& closed.</span></span>

- <span data-ttu-id="2c202-325">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-325">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="2c202-326">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-326">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="2c202-327">グラフの軸の "Value Crosses At" プロパティが、ファイルを保存してもう一度開くときに予期せず変更されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-327">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="2c202-328">SharePoint/OneDrive に保存すると、ユーザー設定のリボンタブの CustomUI XML が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-328">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="2c202-329">結合されたセルを持つ列を削除するときのパフォーマンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-329">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="2c202-330">[印刷] ダイアログ ボックスのプリンターのリストにプリンター名が繰り返されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-330">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="2c202-331">ファイル パスが長すぎる場合にファイルをもう一度開くと、外部リンクが機能しなくなった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-331">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="2c202-332">印刷時にフォーム コントロールのチェックボックスが拡大縮小されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-332">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="2c202-333">従来の "共有ブック" モードを使用して、ブックの新しいシートに変更を一覧表示しようとすると、クラッシュが発生する場合がありました。</span><span class="sxs-lookup"><span data-stu-id="2c202-333">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="2c202-334">フィルター処理されたリストに列を挿入すると、通常よりも時間がかかっていました。</span><span class="sxs-lookup"><span data-stu-id="2c202-334">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="2c202-335">コピー & ペーストされたグラフのリンクの一部で、ユニバーサル アドレスではなくマップされたドライブ アドレスが使用されていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-335">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="2c202-336">アドインが、ユーザーが指定した順番ではなくアルファベット順に読み込まれていたため、「このブックは現在別のユーザーに参照されており、閉じることができません」というエラー メッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-336">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="2c202-337">既に開いているブック内の場所へのハイパーリンクをクリックすると、ブックが非表示になることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-337">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="2c202-338">特に非表示のウィンドウで、多数のその他のブックを参照しながらブックを開くと、予想よりも時間がかかります。</span><span class="sxs-lookup"><span data-stu-id="2c202-338">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="2c202-339">VBA の Application.Evaluate が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="2c202-339">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="2c202-340">一部のユーザーが埋め込みオブジェクトとリンク オブジェクト (OLE) で経験する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-340">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="2c202-341">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-341">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="2c202-342">この更新によって、数式バーに予期したのとは異なるフォントでテキストが表示される原因となっていた問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-342">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="2c202-343">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-343">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="2c202-344">スクロール後にセルを選択すると間違ったセルが選択されることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-344">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="2c202-345">非表示の名前付き範囲にアクセスすると、ユーザーにエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-345">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="2c202-346">信頼されていないネットワーク共有から保護されたファイルを編集する際に、Excel にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-346">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="2c202-347">一部のローカライズにおいて、[Text to Column] 機能が失敗することがあります。</span><span class="sxs-lookup"><span data-stu-id="2c202-347">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="2c202-348">テンプレートからグラフを作成するときに発生するパフォーマンスの問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-348">Addresses a performance issue when creating charts from templates.</span></span>

- <span data-ttu-id="2c202-349">はみ出している列挙が含まれるセルで区切り位置を指定するとクラッシュが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-349">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="2c202-350">Range.Value と Range.Value2 (VBA) を使用すると、数式は動的配列として入力されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-350">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

- <span data-ttu-id="2c202-351">数式を開始する @ 記号が暗黙的な論理積演算子と見なされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-351">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

- <span data-ttu-id="2c202-352">定義された名前を持つ複数の数式を含むワークシートがファイルを保存するときに時間がかかる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-352">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="2c202-353">この変更は、ソフトウェア レンダリングを活用することにより、特定の Intel グラフィック ドライバーの問題を回避します。</span><span class="sxs-lookup"><span data-stu-id="2c202-353">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="2c202-354">署名の名前を変更したときにクラッシュする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-354">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="onenote"></a><span data-ttu-id="2c202-355">OneNote</span><span class="sxs-lookup"><span data-stu-id="2c202-355">OneNote</span></span>

- <span data-ttu-id="2c202-356">OneNote 2016 で同期頻度を一時的に調整することで、同期およびサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-356">Improve sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="2c202-357">ユーザーが OneNote 2016 のページに移動するまで、オンライン ノートブックの埋め込みファイルおよび画像のダウンロードを一時的に遅らせることで、同期およびサービスの安定性を改善します。</span><span class="sxs-lookup"><span data-stu-id="2c202-357">Improve sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="2c202-358">OneNote 2016 のごみ箱を一時的に無効にすることにより、同期およびサービスの安定性を改善します。</span><span class="sxs-lookup"><span data-stu-id="2c202-358">Improve sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="2c202-359">ユーザーが、通常はごみ箱に送られるデータを削除しようとすると、データを保持するか、完全に削除するかを確認するメッセージが表示されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-359">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="2c202-360">OneNote 2016 のバージョン履歴ページの数と同期頻度を一時的に減らすことで、同期およびサービスの安定性を改善します。</span><span class="sxs-lookup"><span data-stu-id="2c202-360">Improve sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="2c202-361">同期およびサービスの安定性を改善するために、OneNote ユーザー エクスペリエンスで実行されている一時的な手段についての詳細情報をユーザーが学べるようにする通知を表示します。</span><span class="sxs-lookup"><span data-stu-id="2c202-361">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="2c202-362">OneNote 2016 に 50 MB へ埋め込まれた新しい添付ファイルの最大許容サイズが一時的に減少することにより、同期とサービスの安定性を改善します。</span><span class="sxs-lookup"><span data-stu-id="2c202-362">Improve sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="2c202-363">この制限を超えるファイルの場合、ユーザーは OneDrive にファイルをアップロードして、OneNote にリンクを挿入することができます。</span><span class="sxs-lookup"><span data-stu-id="2c202-363">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="2c202-364">OneNote 2016 でアプリ内動画のレコーディングを一時的に無効にすることで、同期およびサービスの安定性を改善します。</span><span class="sxs-lookup"><span data-stu-id="2c202-364">Improve sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="2c202-365">ローカルのノートブックはこの影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="2c202-365">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="2c202-366">同期およびサービスの安定性を改善するために、OneNote ユーザー エクスペリエンスで実行されている一時的な手段についての詳細情報をユーザーが学べるようにする通知をローカライズします。</span><span class="sxs-lookup"><span data-stu-id="2c202-366">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="2c202-367">Outlook</span><span class="sxs-lookup"><span data-stu-id="2c202-367">Outlook</span></span>

- <span data-ttu-id="2c202-368">解像度の異なる複数のモニターを使用している場合に、IME(Input Method Editor)ウィンドウで入力されたテキストが重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-368">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="2c202-369">Outlook でユーザーが不定期に遭遇するクラッシュの原因になる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-369">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="2c202-370">これにより、Python による添付ファイルもブロックされるよう、Outlook の添付ファイルのブロック ロジックが更新されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-370">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="2c202-371">Web アドインがデジタル著作権管理 (DRM) メッセージにアクセスする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-371">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="2c202-372">タイムゾーンの定義を変更するときに、定期的な予定や会議が誤った時間に表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-372">Addresses an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="2c202-373">2019 年に ブラジル タイム ゾーンを使用している場合、2020 年の定期的な会議や予定が間違った時間帯に表示されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-373">When using the Brazilia time zone in the year 2019, recurring meetings and appointments are displayed in the wrong timeslot for the year 2020.</span></span> <span data-ttu-id="2c202-374">この変更は、ブラジル タイム ゾーンに設定されているクライアントまたは同タイム ゾーンで設定された会議や予定に影響を与えます。</span><span class="sxs-lookup"><span data-stu-id="2c202-374">This change is relevant for clients set in the Brazilia time zone or for meetings and appointments set in that time zone.</span></span><br><br><span data-ttu-id="2c202-375">この変更により、Outlook では、使用する特定のタイムゾーン設定を上書きできます。</span><span class="sxs-lookup"><span data-stu-id="2c202-375">This change allows Outlook to override certain time zone settings used by Outlook.</span></span> <span data-ttu-id="2c202-376">タイムゾーンの上書きを起動するには、現在のユーザーのレジストリキーを設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-376">In order to invoke a time zone override you must set a registry key for the current user.</span></span> <span data-ttu-id="2c202-377">レジストリキーの名前は、タイムゾーンの内部名と一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-377">The registry key name must match the internal name of the time zone.</span></span> <span data-ttu-id="2c202-378">この値は、有効な年の代わりに、使用されるタイムゾーン ルールの年を示します。</span><span class="sxs-lookup"><span data-stu-id="2c202-378">The value indicates the time zone rule's year to be used in place of the effective year.</span></span> <span data-ttu-id="2c202-379">たとえば、次のレジストリキーの上書き値は、2020 年のブラジル タイムゾーン ルールを有効なルールとして使用します。</span><span class="sxs-lookup"><span data-stu-id="2c202-379">For example, the following registry key override value will use the Brazilia time zone rule for the year 2020 as the effective rule.</span></span> <span data-ttu-id="2c202-380">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E。</span><span class="sxs-lookup"><span data-stu-id="2c202-380">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span></span> <span data-ttu-id="2c202-381">南アメリカ標準時 "=dword:000007e4。</span><span class="sxs-lookup"><span data-stu-id="2c202-381">South America Standard Time"=dword:000007e4.</span></span>

- <span data-ttu-id="2c202-382">会議の場所フィールドが予期せず変更される原因となる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-382">Addresses an issue that caused users to see the location field in meetings change unexpectedly.</span></span>

- <span data-ttu-id="2c202-383">会議の [場所] フィールドが予期せず更新される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-383">Addresses an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="2c202-384">会議をクリアした後、会議の場所が予期せずに会議に追加される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-384">Addresses an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="2c202-385">会議の [場所] フィールドにあるコンマがセミコロンになる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-385">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="2c202-386">ネイティブの Teams クライアントを介して Teams 会議に直接参加できます。</span><span class="sxs-lookup"><span data-stu-id="2c202-386">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="2c202-387">Exchange 2010 サーバー上にメールボックスを持つユーザーが、予定表の項目に添付ファイルを追加するときに生じる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-387">Addresses an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="2c202-388">ユーザーがデジタル署名されたメッセージに返信するときに生じる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-388">Addresses an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="2c202-389">ユーザーが定期的な予定表の一部のインスタンスを開けない原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-389">Addresses an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="2c202-390">一部のシナリオで、グループ ヘッダーが予期せず拡張される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-390">Addresses an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="2c202-391">フォルダー ウィンドウの幅が予期せず変更される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-391">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="2c202-392">M365 Business Plus プランのサービスを利用していたユーザーがデータ損失防止の保護ポリシー ヒントを有効にできない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-392">Addresses an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="2c202-393">キーボード ショートカットを使用してメールボックス フォルダーを操作すると、ユーザーに顕著な遅延が発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-393">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="2c202-394">複数のウィンドウで同じアイテムを表示するとクラッシュする場合がある問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-394">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="2c202-395">ユーザーが Outlook ルールを更新すると、"このコンピューターのルールは、Microsoft Exchange のルールと異なります" と表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-395">Addresses an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="2c202-396">非常に長い Outlook セッションでメモリ リークを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-396">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="2c202-397">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-397">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="2c202-398">ユーザーが [ルール] ダイアログを開くと、"このコンピューターのルールは、Microsoft Exchange のルールと異なります" というメッセージが表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-398">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="2c202-399">フラグ付きアイテムの強調表示を無効にするオプションが一部のシナリオで無視される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-399">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="2c202-400">[アクセシビリティ チェック] ペインを閉じた後に "S" キーを押すと、メールが予期せず送信されたようにユーザーに表示される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-400">Addresses an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="2c202-401">署名の名前を変更したときにクラッシュする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-401">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="2c202-402">ユーザーがアカウントのセットアップをキャンセルするときにクラッシュする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-402">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="2c202-403">同期のスライダーが小さい設定に設定されている場合でも、Outlook で予期せずすべてのメールが同期される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-403">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="2c202-404">黒のテーマを持つユーザーが [差出人] ドロップダウンを表示すると、白色の背景に白いテキストが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-404">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="2c202-405">ユーザーがプロフィールの作成中にクラッシュを発生させる原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-405">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="2c202-406">アカウント作成コンテキストからサポートに連絡しようとすると、ユーザーに [OK] ボタンのある空のメッセージ ボックスが表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-406">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="2c202-407">アカウント作成コンテキストからサポートに連絡しようとすると、ユーザーに [OK] ボタンのある空のメッセージ ボックスが表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-407">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="2c202-408">サードパーティ製アプリケーションがメールを送信できない原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-408">Addresses an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="2c202-409">メール メッセージからカテゴリが消えることがあるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-409">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="2c202-410">サーバー オペレーティング システムの Outlook ユーザーに "ウイルス対策ステータス: 無効" のエラーを表示する原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-410">Addresses an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="2c202-411">このバージョンの Windows はウイルス検出をサポートしていますが、ウイルス対策を適切に構成してもウイルス対策ソフトウェアが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="2c202-411">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

- <span data-ttu-id="2c202-412">共有メールボックスに対して、異なるコンピューター上の別のフォルダー階層が代理人に表示されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-412">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="2c202-413">管理者のカレンダー上で既存のカレンダーの予定を編集するときに代理人がエラーを受け取る問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-413">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="2c202-414">間違ったブラウザー エミュレーション設定でユーザーが Gmail の認証プロンプトを完了できなくなるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-414">Addresses an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="2c202-415">[共有フォルダーのダウンロード] がチェックされていない場合、共有の予定表の会議の [返信オプション] に [転送を許可する] オプションが表示されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-415">Addresses an issue that caused the " Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="2c202-416">ユーザーが Windows Update の後に .msg および .oft ファイルを開こうとするとクラッシュが起きるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-416">Addresses an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="2c202-417">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-417">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="2c202-418">特定の検索結果を選択すると、ユーザーがクラッシュする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-418">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="2c202-419">[添付ファイル ​​ツール] に [クラウドに保存] ボタンが表示されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-419">Addresses an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="2c202-420">この変更により、メッセージ ヘッダーに複数行の件名を表示できる機能が復元されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-420">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="2c202-421">2 つのアドインが同じリボン グループにボタンを追加するときにユーザーにクラッシュが発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-421">Addresses an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="2c202-422">テナントの既定のアクセス許可が "全員" として構成されている場合に、適切なテナントの既定のアクセス許可を使用して、リンクがメールに追加されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-422">Addresses an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as "anyone".</span></span>

- <span data-ttu-id="2c202-423">ユーザーが個人用配布リストにメールを送信できなくなった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-423">Addresses an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="2c202-424">大きな HTML メッセージを転送するとき、ユーザーにメッセージ本文の全体が表示されないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-424">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="2c202-425">SMIME アルゴリズムの選択に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-425">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="2c202-426">WebDAV の場所にファイルを保存できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-426">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="2c202-427">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカル コンピューターに保存できない原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-427">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="2c202-428">件名を編集した後、NDR メッセージの本文が Unicode から ASCII に変更される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-428">Addresses an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="2c202-429">ユーザーが Outlook プロセスでメモリ リークを観測する原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-429">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="2c202-430">状況によっては、表示された SMTP アドレスと一致しないアドレスに送信されたメールがユーザーに表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-430">Addresses an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="2c202-431">検索ボックスが高 DPI モードで不適切に表示される原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-431">Addresses an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="2c202-432">ユーザーがクラウド設定を取得する際に Outlook がフリーズする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-432">Addresses an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="2c202-433">検索に関するフィードバックのエクスペリエンスで終了する原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-433">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="2c202-434">Outlook でユーザーが不定期に遭遇するクラッシュの原因になる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-434">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="2c202-435">署名の名前を変更したときにクラッシュする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-435">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="2c202-436">ユーザーがプロフィールの作成中にクラッシュを発生させる原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-436">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="2c202-437">Outlook でユーザーが不定期に遭遇するクラッシュの原因になる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-437">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2c202-438">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2c202-438">PowerPoint</span></span>

- <span data-ttu-id="2c202-439">従来の PPT コメントでコンテキスト メニューを使用するときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-439">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

- <span data-ttu-id="2c202-440">コピーと貼り付けのシナリオを改善しました。PowerPoint スライドでの図形のコピーと、ループ内の他のスライドへの貼り付けが例外で失敗する場合があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-440">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="2c202-441">問題の修正により、改善済みのコメントが入ったファイルのコピーを開くユーザーに正しいメッセージを送れるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-441">Fixes an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="project"></a><span data-ttu-id="2c202-442">Project</span><span class="sxs-lookup"><span data-stu-id="2c202-442">Project</span></span>

- <span data-ttu-id="2c202-443">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-443">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="2c202-444">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-444">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="2c202-445">[無効化] ボタンを介してタスクが非アクティブ化/アクティブ化された場合に、ProjectBeforeTaskChange イベントが検出しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-445">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="2c202-446">以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-446">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="2c202-447">読み取り専用のプロジェクトを開いたときに複数のメッセージを取得する可能性があるという問題を特定しました</span><span class="sxs-lookup"><span data-stu-id="2c202-447">Identified an issue where users could get several messages when opening a read-only project</span></span>

- <span data-ttu-id="2c202-448">作業時間固定タイプの達成率 100% のタスクで、達成率が誤って 100% 未満に計算される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-448">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="2c202-449">Word</span><span class="sxs-lookup"><span data-stu-id="2c202-449">Word</span></span>

- <span data-ttu-id="2c202-450">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-450">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="2c202-451">クイック印刷を使用して印刷した後に編集しようとしたときに、ドキュメント内の単語の配置が乱れてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-451">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="2c202-452">表内のテキストに合わせる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-452">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="2c202-453">水平線の挿入が短くなく、中央に配置されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-453">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>

- <span data-ttu-id="2c202-454">文書パーツ オーガナイザーに "スタイル、文書パーツを変更しました" という無効なアラートが表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-454">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

- <span data-ttu-id="2c202-455">ポリシー FileBlick\Word2007Files を有効にしたときの共同編集に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-455">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="2c202-456">名前が変更されたルックアップ フィールドを追加するときに Word QuickPart が機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-456">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

- <span data-ttu-id="2c202-457">2 つのドキュメントを 1 つのドキュメントに結合するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-457">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="2c202-458">編集用に保護されたドキュメントの比較機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-458">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="2c202-459">この更新プログラムでは、Microsoft Word で、ラベル ポリシーにヘッダーやフッターまたは透かしが適用されている場合にラベルを変更または削除すると、255 文字を超える文字の挿入されたテキストが識別および削除できなかった問題が修正されています。</span><span class="sxs-lookup"><span data-stu-id="2c202-459">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2c202-460">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2c202-460">Office Suite</span></span>

- <span data-ttu-id="2c202-461">大規模な PowerPoint ファイルの共同編集中に、ユーザーがネットワークと CPU の使用率が過剰になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-461">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="2c202-462">これは、ファイルがクライアントにキャッシュされるときに Project アプリがネットワークをブロックしないようにするための修正プログラムです。</span><span class="sxs-lookup"><span data-stu-id="2c202-462">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>


- <span data-ttu-id="2c202-463">この問題を解決するため、Backstage のチャネル名を 2020 年 1 月のフォークにある新しいチャネル名に更新しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-463">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="2c202-464">この問題は修正されましたが、今後、デバイスがポリシー管理されている場合、DMS の対象ユーザー API は呼び出されません。</span><span class="sxs-lookup"><span data-stu-id="2c202-464">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="2c202-465">単一のトランザクションでアプリを追加および削除したときに、削除が不完全になるという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-465">We have resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="2c202-466">ODT と GPO の更新期限設定で、相対期限の設定後、初回のみしか機能しないバスが修正されました。修正により、2 回目以降の更新プログラムで相対期限を使用きるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-466">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="2c202-467">Office の更新プログラムが、意図したソース (ローカル共有、ネットワーク共有、構成マネージャーで提供される場所など) からではなく、予期せずに Office CDN からファイルをダウンロードする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-467">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="2c202-468">ODT と GPO の更新期限設定で、相対期限の設定後、初回のみしか機能しないバスが修正されました。修正により、2 回目以降の更新プログラムで相対期限を使用きるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-468">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="2c202-469">以前の AppV51 の回帰を修正するために、新しい AppV51 drop をバックポートしました。</span><span class="sxs-lookup"><span data-stu-id="2c202-469">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="2c202-470">ログ記録して続行するのではなく、内部操作により失敗時に例外がスローされていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-470">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="2c202-471">影響を受けるユーザーは、更新プログラムの受信をブロックされなくなります。</span><span class="sxs-lookup"><span data-stu-id="2c202-471">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="2c202-472">チームでは、半期エンタープライズ プレビューで Office CDN ドメインのテレメトリを報告するためのクライアント サポートを追加しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-472">Our team has added client support for reporting telemetry on the Office CDN domains in Semi-Annual Enterprise Preview.</span></span>

- <span data-ttu-id="2c202-473">この変更では、Intel Integrated GPU を使用するグラフィック アダプターに関して報告された問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-473">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="2c202-474">この変更により、リボンのスケッチされたアウトラインは正常に機能するようになります。</span><span class="sxs-lookup"><span data-stu-id="2c202-474">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="2c202-475">特定のプロキシの構成でオンプレミスの場所からファイルを開く際の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-475">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="2c202-476">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-476">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="2c202-477">問題を解決し、Office のハンドオフ セッション中のクラッシュを解消し、ユーザー エクスペリエンスの信頼性を向上させました。</span><span class="sxs-lookup"><span data-stu-id="2c202-477">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>

- <span data-ttu-id="2c202-478">このバグは、Enhanced Configuration Service (ECS) url エンドポイントを更新します。</span><span class="sxs-lookup"><span data-stu-id="2c202-478">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="2c202-479">この新しいエンドポイントを呼び出すと、ECS からのフェッチ成功率が高くなります。</span><span class="sxs-lookup"><span data-stu-id="2c202-479">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

- <span data-ttu-id="2c202-480">この更新プログラムでは、メッセージの表示または作成時に Microsoft Outlook で現在の機密ラベルが表示されないという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="2c202-480">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="2c202-481">同じ SharePoint ライブラリから Word/Excel/PowerPoint で複数のドキュメントが開かれている場合、最初に開いたドキュメントのみがポリシー コンプライアンスでスキャンされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-481">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

- <span data-ttu-id="2c202-482">Office ユーザーのセキュリティを保護するために、Microsoft Office の更新プログラムは SHA-2 アルゴリズムのみを使用して署名されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-482">To protect Office customers’ security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="2c202-483">HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth のレジストリ キーが 0 に設定されている場合、アドインがアクティブになり、Windows で Office ホストがクラッシュしました。</span><span class="sxs-lookup"><span data-stu-id="2c202-483">The office host was crashing in windows, when an add-in is being activated while the registry key  HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="2c202-484">この変更により、この問題は修正されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-484">This change would fix this issue.</span></span>

- <span data-ttu-id="2c202-485">レジストリ TabProcGrowth の値が REG_SZ 型でアドインがアクティブ化されている場合に、Windows の Office ホストがクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-485">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="2c202-486">この更新プログラムでは、Microsoft Office で PATH 環境変数で指定した場所を検索することによって参照される可能性がある Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA ランタイムエラーが発生するという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-486">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="2c202-487">インストールされている言語によって Access と Publisher が正常に起動しなかった問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-487">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)





[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-july-14"></a><span data-ttu-id="2c202-490">バージョン 1908: 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2c202-490">Version 1908: July 14</span></span>
<span data-ttu-id="2c202-491">*バージョン 1908 (ビルド 11929.20904)*</span><span class="sxs-lookup"><span data-stu-id="2c202-491">*Version 1908 (Build 11929.20904)*</span></span>

<span data-ttu-id="2c202-492">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2c202-492">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2c202-494">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2c202-494">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2c202-495">Access</span><span class="sxs-lookup"><span data-stu-id="2c202-495">Access</span></span>

- <span data-ttu-id="2c202-496">この更新プログラムにより、Sum などの集計が結果を整数値に切り捨てる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-496">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="2c202-497">この更新プログラムにより、リモート テーブル (SQL Server テーブルなど) への参照を含むユニオン クエリにより Access が閉じて再起動する問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-497">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="2c202-498">この更新プログラムにより、更新クエリが実行されるか、SQL で UPDATE ステートメントが使用されるときに "クエリは破損しています" というエラーを発生させる場合のある Microsoft Access の問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-498">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="2c202-499">Excel</span><span class="sxs-lookup"><span data-stu-id="2c202-499">Excel</span></span>

- <span data-ttu-id="2c202-500">ドキュメント タイトルのオランダ語の KeyTip が Alt-G に変更されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-500">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="2c202-501">図形やフォームコントロールに割り当てられているマクロが間違ったエラーメッセージとして表示される、または間違った対象範囲で動作する問題が Excel で修正されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-501">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="2c202-502">最初のアイテムを検索した後に、ダイアログでのフォーカスの位置が変更されてしまう検索と置換についての問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-502">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="2c202-503">これにより、ピボットテーブルの並べ替え方法を変更し、他のユーザーとの共同編集セッション中にそれを更新するとクラッシュが発生する可能性がある問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-503">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="2c202-504">OLAP ピボットテーブルのフィルターが、キューブから削除された値に設定された場合の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-504">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="2c202-505">この更新プログラムは、VBA を使用してグラフのヘッダー/フッターに画像を追加するたびにエラーが発生する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="2c202-505">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="2c202-506">シリーズ コレクションを変更するときに、散布図が適切にレンダリングされない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2c202-506">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span>

- <span data-ttu-id="2c202-507">グラフ テンプレートを使用してグラフを挿入する場合に、プレビューで正しい色が使用されるよう修正します。</span><span class="sxs-lookup"><span data-stu-id="2c202-507">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="2c202-508">セルが挿入または削除されたときに、ウォーターフォール図とじょうごグラフがテーブルと同期しなくなる原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-508">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="2c202-509">Excel で、ユーザーが変更を取得するためにブックを再び開くよう要求されるマージ競合の問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-509">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="2c202-510">最小化されたウィンドウをアクティブにするマクロ実行時エラーの原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-510">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="2c202-511">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-511">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="2c202-512">他のユーザーと共同編集しているときに、テーブルの横にある切り取りと貼り付けの操作が失敗する原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-512">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="2c202-513">実行中のマクロでカスタム プロパティを変更するときに、共同編集の中断を引き起こす原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-513">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="2c202-514">アドインによって開かれた WPF (Windows Presentation Foundation) フォームのコンボ ボックスからアイテムを選ぶことができない問題が発生しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-514">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="2c202-515">ブックが開かれていない状態で最近使用したファイルを検索するときに、クラッシュを発生させる原因となっていた可能性がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-515">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="2c202-516">グループ ボックス コントロールの境界線が印刷プレビューまたは印刷時に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-516">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="2c202-517">ブックで外部リンクがある場合に、一部のユーザーでポップアップ ウィンドウが複数表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-517">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="2c202-518">VBA マクロを使用して範囲の内容をクリアするときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-518">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="2c202-519">値の範囲への入力に予想より時間がかかる VBA の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-519">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="2c202-520">グラフの軸の "Value Crosses At" プロパティが、ファイルを保存してもう一度開くときに予期せず変更されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-520">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="2c202-521">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-521">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="2c202-522">結合されたセルを含む列を削除するときにパフォーマンスが低下する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-522">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="2c202-523">[印刷プレビュー] に表示されるときのフォーム コントロール内のテキストの拡大縮小に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-523">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="2c202-524">色でフィルタリングされたデータを異なる幅の列にコピーすると、値が貼り付けられません。</span><span class="sxs-lookup"><span data-stu-id="2c202-524">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

- <span data-ttu-id="2c202-525">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-525">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="2c202-526">印刷時にフォーム コントロールのチェックボックスが拡大縮小されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-526">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="2c202-527">同じブック内でブックマークされたハイパーリンクをクリックすると、ブックが非表示になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-527">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="2c202-528">従来の "共有ブック" モードを使用して、ブックの新しいシートに変更をリスト表示しようとすると、クラッシュが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-528">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="2c202-529">一部のロケールにおいて、[Text to Column] 機能が失敗することがあります。</span><span class="sxs-lookup"><span data-stu-id="2c202-529">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="2c202-530">非表示の名前付き範囲にアクセスすると、ユーザーにエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-530">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="2c202-531">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-531">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="2c202-532">グラフを含むブックを保存すると、グラフ ヘッダーの画像のファイル サイズが大きくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-532">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>

- <span data-ttu-id="2c202-533">非同期のユーザー定義関数が同期して実行されるパフォーマンスの問題が発生しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-533">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="2c202-534">結合されたセルで列を削除するパフォーマンスが大幅に改善されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-534">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="2c202-535">スクロール後にセルを選択すると間違ったセルが選択されることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-535">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="2c202-536">Lookup 関数がエラーを返す問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-536">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="2c202-537">選択範囲を相互参照ブックと同期させ続けることにより、相互参照ブックの DBCS 文字が破損する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-537">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="2c202-538">自動調整を使用して行の高さを調整するときにチェック ボックスのコントロールが縮小される可能性があるという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-538">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>

- <span data-ttu-id="2c202-539">ファイルに広範な条件付き書式が設定されている場合に、[フォントの色] ボタンをクリックするとパフォーマンスが低下する問題。</span><span class="sxs-lookup"><span data-stu-id="2c202-539">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="2c202-540">印刷プレビューの印刷範囲が正しくないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-540">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="2c202-541">信頼されていないネットワーク共有から保護されたファイルを編集する際に、Excel にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-541">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="2c202-542">色によるフィルタリングのパフォーマンスが大幅に改善されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-542">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="2c202-543">Office の以前のバージョンで作成されたブックを Office の最新のバージョンで開いたときに、Excel の終了を引き起こす可能性がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-543">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="2c202-544">アドイン マネジャーで参照するときに、16 個を超えるアドインを表示できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-544">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="2c202-545">一部の保護されたシートにハイパーリンクが貼り付けられない問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-545">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="2c202-546">この変更は、ソフトウェア レンダリングを活用することにより、特定の Intel グラフィック ドライバーの問題を回避します。</span><span class="sxs-lookup"><span data-stu-id="2c202-546">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="2c202-547">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-547">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2c202-548">この更新プログラムにより、"アップロードできませんでした" というメッセージが表示され、Office ドキュメントが OneDrive for Business にアップロードされないことがあるエラーが修正されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-548">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="2c202-549">Win32 クライアントの [アイデア] ボタンをクリックしてアドインを読み込むときにエラーが発生するという Excel のアイデア機能の問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="2c202-549">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span> 

### <a name="onenote"></a><span data-ttu-id="2c202-550">OneNote</span><span class="sxs-lookup"><span data-stu-id="2c202-550">OneNote</span></span>

- <span data-ttu-id="2c202-551">同期およびサービスの安定性を改善するために、OneNote ユーザー エクスペリエンスで実行されている一時的な手段についての詳細情報をユーザーが学べるようにする通知をローカライズします。</span><span class="sxs-lookup"><span data-stu-id="2c202-551">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="2c202-552">Outlook</span><span class="sxs-lookup"><span data-stu-id="2c202-552">Outlook</span></span>

- <span data-ttu-id="2c202-553">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-553">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2c202-554">メールボックスを基本認証から最新認証にアップグレードしたユーザーが、Outlook プロファイルに関連付けられた正しくないアカウントで終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-554">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="2c202-555">Web アドインがデジタル著作権管理 (DRM) メッセージにアクセスすべきでないときにアクセスする原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-555">Addresses an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="2c202-556">一部のセーフリンクに対して簡易的なホバーの URL が正しく表示されなくなる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-556">Addresses an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="2c202-557">これにより、Python による添付ファイルもブロックされるよう、Outlook の添付ファイルのブロック ロジックが更新されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-557">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="2c202-558">設定に関係なく、POP3 ユーザーの一部がプレーンテキストで書式設定されたすべてのメールを表示する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-558">Addresses an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="2c202-559">この修正プログラムでは、HTML 形式のメッセージの表示が復元されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-559">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="2c202-560">プライマリ予定表からグループ予定表にアイテムをコピーするときに、ユーザーにアクセス許可のエラーを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-560">Addresses an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="2c202-561">ユーザーがスクリーン リーダーから場所の候補にアクセスできない原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-561">Addresses an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="2c202-562">キーボード ショートカットを使用してメールボックス フォルダーを操作すると、ユーザーに顕著な遅延が発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-562">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="2c202-563">非常に長い Outlook セッションでメモリ リークを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-563">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="2c202-564">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-564">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="2c202-565">ユーザーが [ルール] ダイアログを開くと、"このコンピューターのルールは、Microsoft Exchange のルールと異なります" というメッセージが表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-565">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="2c202-566">特定のセーフリンクを操作するときに、Outlook でクラッシュを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-566">Addresses an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="2c202-567">代理人が特定の会議出席依頼に既に返信したかどうかに関係なく、管理者が不明瞭になる問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="2c202-567">Addresses an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="2c202-568">一部の AutoDiscover の応答を処理するときに、クラッシュを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-568">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="2c202-569">アカウント作成コンテキストからサポートに連絡しようとすると、ユーザーに [OK] ボタンのある空のメッセージ ボックスが表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-569">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="2c202-570">この変更により、UPN 経由で自動検出の認証プロンプトに提供されるアカウントのメールを選択するため、ポリシーを管理者が有効にできるようになります。</span><span class="sxs-lookup"><span data-stu-id="2c202-570">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="2c202-571">既定では、使用可能な場合に、自動検出ではアカウント UPN の方が選択されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-571">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="2c202-572">最新のグループに対し、検索の失敗がユーザーに表示される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-572">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="2c202-573">Outlook ユーザーが特定のシナリオで "パスワードを要求している" 状態で停止する原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-573">Addresses an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="2c202-574">競合メッセージの処理中にユーザーに同期エラーが発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-574">Addresses an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="2c202-575">最新の Windows 更新プログラム適用後に、ユーザーが msg および .oft ファイルを開こうとするとクラッシュが起きる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-575">Addresses an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="2c202-576">Outlook の起動時にユーザーが [プロファイルの読み込み中] 画面でハングアップする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-576">Addresses an issue that caused users to experience a hang at the "Loading Profile" screen when Outlook is starting up.</span></span>

- <span data-ttu-id="2c202-577">特定の検索結果を選択すると、ユーザーがクラッシュする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-577">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="2c202-578">[添付ファイル ​​ツール] に [クラウドに保存] ボタンが表示されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-578">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="2c202-579">既定では、アイテム保持ポリシーのラベルには、保持期間がかっこ内に表示されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-579">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="2c202-580">これにより、管理者はポリシー名のみを表示するように指定するレジストリ キーを取得することができます。</span><span class="sxs-lookup"><span data-stu-id="2c202-580">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="2c202-581">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = アイテム保持ポリシー テキストの PolicyName のみが表示されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-581">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

- <span data-ttu-id="2c202-582">Outlook のシャットダウン時にクラッシュが発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-582">Addresses an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="2c202-583">一部のシナリオで顧客に空室リストが表示される原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-583">Addresses an issue that caused customers to see an empty room list in some scenarios.</span></span>

- <span data-ttu-id="2c202-584">ビューを変更すると、断続的なクラッシュが発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-584">Addresses an issue that caused users to see intermittent crashes when changing views.</span></span>

- <span data-ttu-id="2c202-585">ユーザーが OST と同期している共有予定表フォルダーに問題があり、これらのフォルダーを操作しようとするとアクセス許可エラーが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-585">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>

- <span data-ttu-id="2c202-586">Citrix 環境で 30 件を超える予定表を表示したときにクラッシュする原因になった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-586">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="2c202-587">以前のバージョンで文書化された個々の [KB については、こちらを参照してください](https://support.microsoft.com/en-us/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span><span class="sxs-lookup"><span data-stu-id="2c202-587">Here's the individual [KB where this was documented for previous versions](https://support.microsoft.com/en-us/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span></span>

- <span data-ttu-id="2c202-588">SMIME アルゴリズムの選択に関する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="2c202-588">Corrects an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="2c202-589">代替送信者の使用中にポリシーのヒントが表示されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-589">Addresses an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="2c202-590">会議室の空き時間外に行われた会議のためにユーザーにその会議室が提案される原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-590">Addresses an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="2c202-591">英語以外の言語を使用するユーザーの、メールの件名が非常に小さくなるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-591">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="2c202-592">"不在着信した会話" メッセージのルールを作成しようとするときに、クラッシュを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-592">Addresses an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="2c202-593">一部のユーザーに、セカンダリ Exchange アカウントを追加するときに作成された重複した特別なフォルダーが表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-593">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="2c202-594">大きな HTML メッセージを転送するとき、ユーザーにメッセージ本文の全体が表示されないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-594">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="2c202-595">ユーザーが Outlook プロセスでメモリ リークを観測する原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-595">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="2c202-596">プレゼンス情報を更新するときに、断続的なクラッシュを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-596">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="2c202-597">現在のフォルダー検索で断続的な失敗を引き起こす問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-597">Addresses an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="2c202-598">一部のユーザーが Outlook のクラウド設定を取得しようとするときに、認証エラーが発生する原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-598">Addresses an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="2c202-599">検索に関するフィードバックのエクスペリエンスで終了する原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-599">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="2c202-600">一部の AutoDiscover の応答を処理するときに、クラッシュを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-600">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="2c202-601">プレゼンス情報を更新するときに、断続的なクラッシュを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-601">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2c202-602">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2c202-602">PowerPoint</span></span>

- <span data-ttu-id="2c202-603">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-603">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2c202-604">この変更により、PowerPoint ビデオ コントロールのアクセス可能な名前が復元されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-604">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="2c202-605">一部のアニメーションが開始されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2c202-605">We fixed an issue which could prevent some animations from starting</span></span>

- <span data-ttu-id="2c202-606">スライドを 1 つのプレゼンテーションから別のプレゼンテーションにコピーすると、重複したマスターが作成される可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-606">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span><br>

- <span data-ttu-id="2c202-607">コピーと貼り付けのシナリオを改善しました。PowerPoint スライドでの図形のコピーと、ループ内の他のスライドへの貼り付けが例外で失敗する場合があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-607">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="2c202-608">蛍光ペンの問題を修正しました。暗い蛍光ペン色の白いテキストはグレースケールで黒として印刷されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-608">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

- <span data-ttu-id="2c202-609">最新のコメントを含むファイルを、サポートされていないバージョンで開くと黄色の警告が表示されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-609">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

- <span data-ttu-id="2c202-610">共同作業ユーザー間のパフォーマンスが低下する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-610">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="2c202-611">信頼性の修正: サード パーティのアドインが PowerPoint のクラッシュを発生させる可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-611">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="2c202-612">増分で開くファイルに、複数のメディア ストリームが埋め込まれたスライドが含まれている場合に発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-612">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="2c202-613">Shape.Paste メソッドを使用する際に発生する問題を解決しました。Shape.Paste メソッドを使用して図形をコピーして貼り付けるときに、貼り付けられた図形の選択内容が変更するという問題です。</span><span class="sxs-lookup"><span data-stu-id="2c202-613">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="2c202-614">PowerPoint の初回起動時に、信頼されていないアドインに対してセキュリティ警告メッセージ バーが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-614">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

- <span data-ttu-id="2c202-615">一部のアドインがグラフの図形に対して予期しないエラーをスローさせる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-615">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="2c202-616">PowerPoint ユーザーがオンライン プレゼンテーションを行おうとするときに、エラーが発生しないようにします。</span><span class="sxs-lookup"><span data-stu-id="2c202-616">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

### <a name="project"></a><span data-ttu-id="2c202-617">Project</span><span class="sxs-lookup"><span data-stu-id="2c202-617">Project</span></span>

- <span data-ttu-id="2c202-618">Windows 7 のユーザーが Project Web App および SharePoint サイトからプロジェクトを開くことができるように問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-618">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="2c202-619">読み取り専用のプロジェクトを開いたときに複数のメッセージを取得する可能性があるという問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-619">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="2c202-620">[すべて平準化] コマンドがリソースの割り当て超過を適切に解決しません。</span><span class="sxs-lookup"><span data-stu-id="2c202-620">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="2c202-621">タスクの作業がゼロの割り当てがある場合、タスクに完了のマークを付けることができず、常に 99％ で表示される問題。</span><span class="sxs-lookup"><span data-stu-id="2c202-621">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

- <span data-ttu-id="2c202-622">基本カレンダーが変更されたときにリソース カレンダーが更新されないために、実際の作業がタイムシートとプロジェクト計画の間で異なる場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-622">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="skype"></a><span data-ttu-id="2c202-623">Skype</span><span class="sxs-lookup"><span data-stu-id="2c202-623">Skype</span></span>

- <span data-ttu-id="2c202-624">複数の会話が発生している場合の、タブ表示の会話のタイトル名を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-624">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="visio"></a><span data-ttu-id="2c202-625">Visio</span><span class="sxs-lookup"><span data-stu-id="2c202-625">Visio</span></span>

- <span data-ttu-id="2c202-626">Visio から SVG へのエクスポートが、さまざまな図形で失敗していました。</span><span class="sxs-lookup"><span data-stu-id="2c202-626">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="2c202-627">Word</span><span class="sxs-lookup"><span data-stu-id="2c202-627">Word</span></span>

- <span data-ttu-id="2c202-628">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-628">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2c202-629">Deskjet プリンターへの印刷時に、スケーリングの問題を引き起こす可能性があった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2c202-629">We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span>

- <span data-ttu-id="2c202-630">表での文字の均等割り付けの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-630">We fixed an issue in Fit Text in Table.</span></span>

- <span data-ttu-id="2c202-631">無限ループになることがあるトラック変更の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-631">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="2c202-632">既存のファイルを保存すると [名前を付けて保存] ダイアログが必ず表示され、ファイルは実際には保存されない場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-632">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="2c202-633">2 つのドキュメントを 1 つのドキュメントに結合するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-633">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="2c202-634">編集用に保護されたドキュメントの比較機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-634">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="2c202-635">シャットダウン時にアプリが終了することがあるさまざまな問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="2c202-635">Fixes various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="2c202-636">特定のアドインに関連するクラッシュも修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-636">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2c202-637">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2c202-637">Office Suite</span></span>

- <span data-ttu-id="2c202-638">新元号の名前である “Reiwa” のひらがなと漢字をスペルミスまたは間違った文法として誤って識別していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-638">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="2c202-639">SharePoint 2016 に保存されているファイルを共有しようとするときに、"申し訳ございません。何かがこのファイルの共有を妨げています。" というメッセージが表示される原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-639">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="2c202-640">PowerPoint での共同編集とオフライン編集の両方を含むセッションでデータの損失を引き起こす可能性のある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-640">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="2c202-641">これは、ユーザーがファイルを開くときに発生する可能性のあるクラッシュの修正プログラムです。</span><span class="sxs-lookup"><span data-stu-id="2c202-641">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="2c202-642">同期エンジンでバックアップされた Sharepoint ファイルに '保存済み' と表示されますが、場合によっては実際に変更が保存されないため、データを損失することになります。</span><span class="sxs-lookup"><span data-stu-id="2c202-642">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="2c202-643">ユーザーが Word、Excel、および PowerPoint のドキュメントを保存できなくなることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-643">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="2c202-644">この問題は、[保存] アイコンをクリックしたり Ctrl キーを押しながら S キーを押したりした後に、新しいファイルを作成して [ダイアログで保存] オプションを表示するユーザーに影響を与えます。</span><span class="sxs-lookup"><span data-stu-id="2c202-644">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="2c202-645">非推奨の API から移動することにより、Word でクラッシュが発生する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="2c202-645">Fixes a crash in Word by moving away from a deprecated API.</span></span>

- <span data-ttu-id="2c202-646">PowerPoint の垂直テキスト ボックスで半角カタカナ文字が適切に回転しない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="2c202-646">Fixing an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="2c202-647">すべてのアプリのリボンで、図形の挿入ギャラリーが表示されるまでに約 4 秒かかるという Win7 のパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-647">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="2c202-648">Backstage の Info Place のスラブにアクセシビリティ情報が表示されていないというバグを修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-648">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="2c202-649">レジストリ整合性に関する Office 更新プロセスの信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-649">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="2c202-650">1 月と 7 月の 2019 フォークのチャネル名が新しいチャネル名に更新しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-650">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="2c202-651">従量制課金ネットワークで更新プログラムが予期せずブロックされる可能性があるという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="2c202-651">Corrects an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="2c202-652">ODT と GPO の更新期限設定で、相対期限の設定後、初回のみしか機能しないバスが修正されました。修正により、2 回目以降の更新プログラムで相対期限を使用きるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-652">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="2c202-653">特定の状況で、更新後に Office ショートカットが消えてしまう場合があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-653">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="2c202-654">この更新プログラムにより、Office ショートカットを公開するときの信頼性が向上します。</span><span class="sxs-lookup"><span data-stu-id="2c202-654">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="2c202-655">Office の更新プログラムが、意図したソース (ローカル共有、ネットワーク共有、構成マネージャーで提供される場所など) からではなく、予期せずに Office CDN からファイルをダウンロードする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-655">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="2c202-656">ユーザーが管理者ではなく、システム アカウントにネットワーク接続が確立されていない場合に、更新プログラムが適用されない問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="2c202-656">Resolves an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="2c202-657">Office の更新メッセージが、異なる言語で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-657">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="2c202-658">今後、Office の更新メッセージは Windows の表示言語と一致します。</span><span class="sxs-lookup"><span data-stu-id="2c202-658">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="2c202-659">以前に中断された可能性のあるダウンロードを再開することにより、Office の更新プログラムをダウンロードするときの信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-659">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="2c202-660">サード パーティ製プラグインのテキスト ボックスと図形の自動調整に関連する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-660">Address issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="2c202-661">この変更は、破損したファイルを開いた後の画像の正しいレンダリングに対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-661">This change addresses correctly rendering images after opening a corrupted file.</span></span>

- <span data-ttu-id="2c202-662">この変更により、マーカー付きの一部の散布図の表示が遅くなる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-662">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="2c202-663">大きなツリー ビューがクラッシュすることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="2c202-663">We fixed an issue where large tree views could result in a crash</span></span>

- <span data-ttu-id="2c202-664">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-664">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="2c202-665">Office ユーザーのセキュリティを保護するために、Microsoft Office の更新プログラムは SHA-2 アルゴリズムのみを使用して署名されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-665">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="2c202-666">Office ユーザーのセキュリティを保護するために、Microsoft Office の更新プログラムは SHA-2 アルゴリズムのみを使用して署名されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-666">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1902-july-14"></a><span data-ttu-id="2c202-668">バージョン 1902: 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2c202-668">Version 1902: July 14</span></span>
<span data-ttu-id="2c202-669">*バージョン 1902 (ビルド 11328.20624)*</span><span class="sxs-lookup"><span data-stu-id="2c202-669">*Version 1902 (Build 11328.20624)*</span></span>

<span data-ttu-id="2c202-670">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2c202-670">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1908-june-09"></a><span data-ttu-id="2c202-671">バージョン 1908: 6 月 9 日</span><span class="sxs-lookup"><span data-stu-id="2c202-671">Version 1908: June 09</span></span>
<span data-ttu-id="2c202-672">*バージョン 1908 (ビルド 11929.20838)*</span><span class="sxs-lookup"><span data-stu-id="2c202-672">*Version 1908 (Build 11929.20838)*</span></span>

<span data-ttu-id="2c202-673">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2c202-673">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2c202-675">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2c202-675">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2c202-676">Excel</span><span class="sxs-lookup"><span data-stu-id="2c202-676">Excel</span></span>

- <span data-ttu-id="2c202-677">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-677">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="2c202-678">印刷時にフォーム コントロールのチェックボックスが拡大縮小されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-678">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="2c202-679">従来の "共有ブック" モードを使用して、ブックの新しいシートに変更を一覧表示しようとすると、クラッシュが発生する場合がありました。</span><span class="sxs-lookup"><span data-stu-id="2c202-679">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="2c202-680">Outlook</span><span class="sxs-lookup"><span data-stu-id="2c202-680">Outlook</span></span>

- <span data-ttu-id="2c202-681">大きな HTML メッセージを転送するとき、ユーザーにメッセージ本文の全体が表示されないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-681">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2c202-682">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2c202-682">Office Suite</span></span>

- <span data-ttu-id="2c202-683">1月と7月の2019フォークのチャネル名が新しいチャネル名に更新されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-683">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1902-june-09"></a><span data-ttu-id="2c202-685">バージョン 1902: 6月 9 日</span><span class="sxs-lookup"><span data-stu-id="2c202-685">Version 1902: June 09</span></span>
<span data-ttu-id="2c202-686">*バージョン 1902 (ビルド 11328.20602)*</span><span class="sxs-lookup"><span data-stu-id="2c202-686">*Version 1902 (Build 11328.20602)*</span></span>

<span data-ttu-id="2c202-687">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2c202-687">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2c202-689">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2c202-689">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="2c202-690">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2c202-690">Office Suite</span></span>

- <span data-ttu-id="2c202-691">1月と7月の2019フォークのチャネル名が新しいチャネル名に更新されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-691">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="2c202-692">C2R ビルドを中断していたベースライン ファイルから、古い形式の参照を削除しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-692">We removed obsolete references from the baseline files that were breaking the C2R Build.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-may-12"></a><span data-ttu-id="2c202-694">バージョン 1908: 5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="2c202-694">Version 1908: May 12</span></span>
<span data-ttu-id="2c202-695">*バージョン 1908 (ビルド 11929.20776)*</span><span class="sxs-lookup"><span data-stu-id="2c202-695">*Version 1908 (Build 11929.20776)*</span></span>

<span data-ttu-id="2c202-696">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2c202-696">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2c202-698">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2c202-698">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2c202-699">Excel</span><span class="sxs-lookup"><span data-stu-id="2c202-699">Excel</span></span>

- <span data-ttu-id="2c202-700">色でフィルタリングされたデータを異なる幅の列にコピーすると、値が貼り付けられません。</span><span class="sxs-lookup"><span data-stu-id="2c202-700">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

### <a name="outlook"></a><span data-ttu-id="2c202-701">Outlook</span><span class="sxs-lookup"><span data-stu-id="2c202-701">Outlook</span></span>

- <span data-ttu-id="2c202-702">最新の Windows 更新プログラム適用後に、ユーザーが msg および .oft ファイルを開こうとするとクラッシュが起きる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-702">Addressed an issue that caused users to experience a crash when opening msg and .oft files after applying a recent Windows update.</span></span>

### <a name="word"></a><span data-ttu-id="2c202-703">Word</span><span class="sxs-lookup"><span data-stu-id="2c202-703">Word</span></span>

- <span data-ttu-id="2c202-704">2 つのドキュメントを 1 つのドキュメントに結合するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-704">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="2c202-705">編集用に保護されたドキュメントの比較機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-705">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1902-may-12"></a><span data-ttu-id="2c202-707">バージョン 1902: 5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="2c202-707">Version 1902: May 12</span></span>
<span data-ttu-id="2c202-708">*バージョン 1902 (ビルド 11328.20586)*</span><span class="sxs-lookup"><span data-stu-id="2c202-708">*Version 1902 (Build 11328.20586)*</span></span>

<span data-ttu-id="2c202-709">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2c202-709">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2c202-711">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2c202-711">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2c202-712">Outlook</span><span class="sxs-lookup"><span data-stu-id="2c202-712">Outlook</span></span>

- <span data-ttu-id="2c202-713">最新の Windows 更新プログラム適用後に、ユーザーが msg および .oft ファイルを開こうとするとクラッシュが起きる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-713">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="2c202-714">既定では、アイテム保持ポリシーのラベルには、保持期間がかっこ内に表示されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-714">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="2c202-715">これにより、管理者はポリシー名のみを表示するように指定するレジストリ キーを取得することができます。</span><span class="sxs-lookup"><span data-stu-id="2c202-715">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="2c202-716">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="2c202-716">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="2c202-717">0 = 既定値。</span><span class="sxs-lookup"><span data-stu-id="2c202-717">0 = Default.</span></span>  <span data-ttu-id="2c202-718">1 = アイテム保持ポリシー テキスト のPolicyName のみが表示されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-718">1 = we will only show the PolicyName for Retention policy text.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-may-04"></a><span data-ttu-id="2c202-720">バージョン 1908: 5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="2c202-720">Version 1908: May 04</span></span>
<span data-ttu-id="2c202-721">*バージョン 1908 (ビルド 11929.20752)*</span><span class="sxs-lookup"><span data-stu-id="2c202-721">*Version 1908 (Build 11929.20752)*</span></span>

<span data-ttu-id="2c202-722">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2c202-722">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="2c202-723">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2c202-723">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2c202-724">Outlook</span><span class="sxs-lookup"><span data-stu-id="2c202-724">Outlook</span></span>

- <span data-ttu-id="2c202-725">ユーザーが特定の検索結果を選択すると、クラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-725">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="2c202-726">[添付ファイル] ​​ツールに [クラウドに保存] ボタンが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-726">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="2c202-727">既定では、アイテム保持ポリシーのラベルには、保持期間がかっこ内に表示されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-727">By default, retention policy labels display the retention time period in parenthesis.</span></span><span data-ttu-id="2c202-728">これにより、管理者はポリシー名のみを表示するように指定するレジストリ キーを取得することができます。</span><span class="sxs-lookup"><span data-stu-id="2c202-728"> This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span><span data-ttu-id="2c202-729"> HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="2c202-729"> HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span><span data-ttu-id="2c202-730"> 0 = 既定値 1 = アイテム保持ポリシー テキスト のPolicyName のみが表示されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-730"> 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2c202-731">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2c202-731">Office Suite</span></span>

- <span data-ttu-id="2c202-732">Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-732">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1902-may-04"></a><span data-ttu-id="2c202-733">バージョン 1902: 5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="2c202-733">Version 1902: May 04</span></span>
<span data-ttu-id="2c202-734">*バージョン 1902 (ビルド 11328.20572)*</span><span class="sxs-lookup"><span data-stu-id="2c202-734">*Version 1902 (Build 11328.20572)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="2c202-735">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2c202-735">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="2c202-736">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2c202-736">Office Suite</span></span>

- <span data-ttu-id="2c202-737">Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-737">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version1908april-26"></a><span data-ttu-id="2c202-738">バージョン 1908: 4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="2c202-738">Version 1908: April 26</span></span>
<span data-ttu-id="2c202-739">*バージョン 1908 (ビルド 11929.20736)*</span><span class="sxs-lookup"><span data-stu-id="2c202-739">*Version 1908 (Build 11929.20736)*</span></span>

<span data-ttu-id="2c202-740">セキュリティ更新プログラムのリストは  [こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2c202-740">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="2c202-741">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2c202-741">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2c202-742">Excel</span><span class="sxs-lookup"><span data-stu-id="2c202-742">Excel</span></span>

- <span data-ttu-id="2c202-743">VBA マクロを使用して範囲の内容をクリアするときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-743">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="2c202-744">値の範囲への入力に予想より時間がかかる VBA の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-744">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="2c202-745">グラフの軸の "Value Crosses At" プロパティが、ファイルを保存してもう一度開くときに予期せず変更されるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-745">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="2c202-746">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-746">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


### <a name="onenote"></a><span data-ttu-id="2c202-747">OneNote</span><span class="sxs-lookup"><span data-stu-id="2c202-747">OneNote</span></span>

- <span data-ttu-id="2c202-748">同期およびサービスの安定性を改善するために、OneNote ユーザー エクスペリエンスで実行されている一時的な手段についての詳細情報をユーザーが学べるようにする通知をローカライズします。</span><span class="sxs-lookup"><span data-stu-id="2c202-748">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>


## <a name="version-1908-april-14"></a><span data-ttu-id="2c202-749">バージョン 1908: 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2c202-749">Version 1908: April 14</span></span>
<span data-ttu-id="2c202-750">*バージョン 1908 (ビルド 11929.20708)*</span><span class="sxs-lookup"><span data-stu-id="2c202-750">*Version 1908 (Build 11929.20708)*</span></span>

<span data-ttu-id="2c202-751">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2c202-751">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2c202-753">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2c202-753">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2c202-754">Excel</span><span class="sxs-lookup"><span data-stu-id="2c202-754">Excel</span></span>

- <span data-ttu-id="2c202-755">結合されたセルを含む列を削除するときにパフォーマンスが低下する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-755">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="2c202-756">[印刷プレビュー] に表示されるときのフォーム コントロール内のテキストの拡大縮小に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-756">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

### <a name="skype"></a><span data-ttu-id="2c202-757">Skype</span><span class="sxs-lookup"><span data-stu-id="2c202-757">Skype</span></span>

- <span data-ttu-id="2c202-758">複数の会話が発生している場合の、タブ表示の会話のタイトル名を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-758">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="outlook"></a><span data-ttu-id="2c202-759">Outlook</span><span class="sxs-lookup"><span data-stu-id="2c202-759">Outlook</span></span>

- <span data-ttu-id="2c202-760">Outlook のシャットダウン時にクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-760">Addressed an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="2c202-761">一部のシナリオで顧客に空室リストが表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-761">Addressed an issue that caused customers to see an empty room list in some scenarios.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2c202-762">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2c202-762">PowerPoint</span></span>

- <span data-ttu-id="2c202-763">蛍光ペンの問題を修正しました。暗い蛍光ペン色の白いテキストはグレースケールで黒として印刷されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-763">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="2c202-764">Word</span><span class="sxs-lookup"><span data-stu-id="2c202-764">Word</span></span>

- <span data-ttu-id="2c202-765">表での、文字の均等割り付けの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-765">Fixed an issue in Fit Text in Table.</span></span>


## <a name="version-1902-april-14"></a><span data-ttu-id="2c202-766">バージョン 1902: 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2c202-766">Version 1902: April 14</span></span>
<span data-ttu-id="2c202-767">*バージョン 1902 (ビルド 11328.20564)*</span><span class="sxs-lookup"><span data-stu-id="2c202-767">*Version 1902 (Build 11328.20564)*</span></span>

<span data-ttu-id="2c202-768">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2c202-768">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-march-10"></a><span data-ttu-id="2c202-770">バージョン 1908: 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="2c202-770">Version 1908: March 10</span></span>
<span data-ttu-id="2c202-771">*バージョン 1908 (ビルド 11929.20648)*</span><span class="sxs-lookup"><span data-stu-id="2c202-771">*Version 1908 (Build 11929.20648)*</span></span>

<span data-ttu-id="2c202-772">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2c202-772">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2c202-774">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2c202-774">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2c202-775">Excel</span><span class="sxs-lookup"><span data-stu-id="2c202-775">Excel</span></span>

- <span data-ttu-id="2c202-776">ブックで外部リンクがある場合にポップアップ ウィンドウが複数表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-776">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>


- <span data-ttu-id="2c202-777">一部のロケールにおいて、[Text to Column] 機能が失敗することがあります。</span><span class="sxs-lookup"><span data-stu-id="2c202-777">Text to Column functionality may fail for some locales.</span></span>


- <span data-ttu-id="2c202-778">非表示の名前付き範囲にアクセスすると、ユーザーにエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-778">Users may encounter an error when accessing a hidden named range.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2c202-779">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2c202-779">PowerPoint</span></span>

- <span data-ttu-id="2c202-780">Shape.Paste メソッドを使用する際に発生する問題を解決しました。Shape.Paste メソッドを使用して図形をコピーして貼り付けるときに、貼り付けられた図形の選択内容が変更するという問題です。</span><span class="sxs-lookup"><span data-stu-id="2c202-780">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>


### <a name="word"></a><span data-ttu-id="2c202-781">Word</span><span class="sxs-lookup"><span data-stu-id="2c202-781">Word</span></span>

- <span data-ttu-id="2c202-782">既存のファイルを保存すると [名前を付けて保存] ダイアログが必ず表示され、ファイルは実際には保存されない場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-782">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2c202-783">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2c202-783">Office Suite</span></span>

- <span data-ttu-id="2c202-784">この変更により、マーカー付きの一部の散布図の表示が遅くなる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-784">This change addresses slow rendering of some scatter charts with markers.</span></span>

## <a name="version-1902-march-10"></a><span data-ttu-id="2c202-785">バージョン 1902: 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="2c202-785">Version 1902: March 10</span></span>
<span data-ttu-id="2c202-786">*バージョン 1902 (ビルド 11328.20554)*</span><span class="sxs-lookup"><span data-stu-id="2c202-786">*Version 1902 (Build 11328.20554)*</span></span>

<span data-ttu-id="2c202-787">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2c202-787">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-february-11"></a><span data-ttu-id="2c202-789">バージョン 1908: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2c202-789">Version 1908: February 11</span></span>
<span data-ttu-id="2c202-790">*バージョン 1908 (ビルド 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="2c202-790">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="2c202-791">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2c202-791">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2c202-793">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2c202-793">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2c202-794">Excel</span><span class="sxs-lookup"><span data-stu-id="2c202-794">Excel</span></span>

- <span data-ttu-id="2c202-795">この更新プログラムは、VBA を使用してグラフのヘッダー/フッターに画像を追加するたびにエラーが発生する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="2c202-795">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="2c202-796">グループ ボックス コントロールの境界線が印刷プレビューまたは印刷時に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-796">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="2c202-797">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-797">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="2c202-798">グラフを含むブックを保存すると、グラフ ヘッダーの画像のファイル サイズが大きくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-798">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="2c202-799">選択範囲を相互参照ブックと同期させ続けることにより、相互参照ブックの DBCS 文字が破損する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-799">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="2c202-800">自動調整を使用して行の高さを調整するときにチェック ボックスのコントロールが縮小される可能性があるという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-800">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="2c202-801">Outlook</span><span class="sxs-lookup"><span data-stu-id="2c202-801">Outlook</span></span>

- <span data-ttu-id="2c202-802">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-802">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="2c202-803">競合メッセージの処理中にユーザーに同期エラーが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-803">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="2c202-804">Outlook の起動時にユーザーが [プロファイルの読み込み中] 画面でハングアップする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-804">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="2c202-805">ビューを変更すると、断続的なクラッシュが発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-805">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="2c202-806">Citrix 環境で 30 件を超える予定表を表示したときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-806">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="2c202-807">[こちら](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)は、以前のバージョンで文書化された個々の KB です。</span><span class="sxs-lookup"><span data-stu-id="2c202-807">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="2c202-808">ユーザーが OST と同期している共有予定表フォルダーに問題があり、これらのフォルダーを操作しようとするとアクセス許可エラーが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-808">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2c202-809">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2c202-809">PowerPoint</span></span>

- <span data-ttu-id="2c202-810">PowerPoint スライドでのコピーと貼り付けのシナリオである図形のコピーを改善しました。ループ内の他のスライドに貼り付けると例外で失敗する場合があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-810">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="2c202-811">共同作業ユーザー間のパフォーマンスが低下する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-811">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="2c202-812">増分で開くファイルに、複数のメディア ストリームが埋め込まれたスライドが含まれている場合に発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-812">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="2c202-813">PowerPoint の初回起動時に、信頼されていないアドインに対してセキュリティ警告メッセージ バーが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-813">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="2c202-814">Project</span><span class="sxs-lookup"><span data-stu-id="2c202-814">Project</span></span>

- <span data-ttu-id="2c202-815">基本カレンダーが変更されたときにリソース カレンダーが更新されないために、実際の作業がタイムシートとプロジェクト計画の間で異なる場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-815">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="2c202-816">Word</span><span class="sxs-lookup"><span data-stu-id="2c202-816">Word</span></span>

- <span data-ttu-id="2c202-817">非推奨の API から移動することにより、Word でクラッシュが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-817">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2c202-818">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2c202-818">Office Suite</span></span>

- <span data-ttu-id="2c202-819">この変更は、破損したファイルを開いた後の画像の正しいレンダリングに対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-819">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1902-february-11"></a><span data-ttu-id="2c202-821">バージョン 1902: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2c202-821">Version 1902: February 11</span></span>
<span data-ttu-id="2c202-822">*バージョン 1902 (ビルド 11328.20526)*</span><span class="sxs-lookup"><span data-stu-id="2c202-822">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="2c202-823">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2c202-823">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2c202-825">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2c202-825">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2c202-826">Outlook</span><span class="sxs-lookup"><span data-stu-id="2c202-826">Outlook</span></span>

- <span data-ttu-id="2c202-827">ユーザーが暗号化されたメールを送信しようとするときに、"暗号化アルゴリズムがサポートされていません" というエラーを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-827">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="2c202-828">Word</span><span class="sxs-lookup"><span data-stu-id="2c202-828">Word</span></span>

- <span data-ttu-id="2c202-829">非推奨の API から移動することにより、Word でクラッシュが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-829">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

## <a name="version-1808-february-11"></a><span data-ttu-id="2c202-832">バージョン 1808: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2c202-832">Version 1808: February 11</span></span>
<span data-ttu-id="2c202-833">*バージョン 1808 (ビルド 10730.20438)*</span><span class="sxs-lookup"><span data-stu-id="2c202-833">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="2c202-834">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2c202-834">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-january-14"></a><span data-ttu-id="2c202-836">バージョン 1908: 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2c202-836">Version 1908: January 14</span></span>
<span data-ttu-id="2c202-837">*バージョン 1908 (ビルド 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="2c202-837">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="2c202-838">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2c202-838">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2c202-840">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2c202-840">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2c202-841">Access</span><span class="sxs-lookup"><span data-stu-id="2c202-841">Access</span></span>

- <span data-ttu-id="2c202-842">**データベース オブジェクトをタブで管理する:** アクティブなタブが分かりやすく表示され、簡単にタブをドラッグして再配置し、ワンクリックでデータベース オブジェクトを閉じることができます。</span><span class="sxs-lookup"><span data-stu-id="2c202-842">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="2c202-843">**シームレスに切り替える:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用のアカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-843">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="2c202-844">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-844">Switching between them has never been easier.</span></span> [<span data-ttu-id="2c202-845">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-845">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="2c202-846">**より大きい [ズーム] ボックス:** [ズーム] ボックスがより大きく表示され、そこでフォントを変更することができます。変更内容はすべて [ズーム] ボックス内に記憶されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-846">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="2c202-847">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-847">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="2c202-848">Excel</span><span class="sxs-lookup"><span data-stu-id="2c202-848">Excel</span></span>

- <span data-ttu-id="2c202-849">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-849">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="2c202-850">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-850">Switching between them has never been easier.</span></span> [<span data-ttu-id="2c202-851">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-851">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="2c202-852">**コンテンツのリーチを拡大する:** プレゼンテーションのアクセシビリティを高める必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="2c202-852">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="2c202-853">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="2c202-853">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="2c202-854">[校閲]>[アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-854">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="2c202-855">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="2c202-855">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="2c202-856">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="2c202-856">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="2c202-857">**ワークシートが生まれ変わりました：** ワークブックを使ってアニメーション 3D グラフィックスを挿入し、心臓の鼓動、惑星軌道、そして T-Rex の大暴れを見ることができます。</span><span class="sxs-lookup"><span data-stu-id="2c202-857">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="2c202-858">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-858">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="2c202-859">**データの詳細を検出する:** 新しいアイデア ボタンは、データのパターンを探し、それを使用してインテリジェントな個人向けの提案を作成します。</span><span class="sxs-lookup"><span data-stu-id="2c202-859">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions.</span></span> [<span data-ttu-id="2c202-860">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-860">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- <span data-ttu-id="2c202-861">**共同作業がさらに簡単に:** 共同編集の改善とは、条件付き書式、セルのスタイルなどを使用して作業しているときに、ユーザーによる変更がシームレスに共同作業者の変更と統合されるということです。</span><span class="sxs-lookup"><span data-stu-id="2c202-861">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="2c202-862">**類似列のテーブルを結合する:** 取得と変換 (Power Query) では、テーブルを統合するために列を比較するときに、近似文字列マッチング ロジック (あいまい一致とも呼ばれる) が使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-862">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="2c202-863">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-863">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="2c202-864">**Power Query の機能強化を使用して素早くコーディングする:** オートコンプリートと構文の色分けを使用して、素早くコーディングを完了できます。</span><span class="sxs-lookup"><span data-stu-id="2c202-864">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="2c202-865">関数、列、パラメーターも簡単に見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="2c202-865">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="2c202-866">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-866">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="2c202-867">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="2c202-867">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="2c202-868">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-868">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="2c202-869">Outlook</span><span class="sxs-lookup"><span data-stu-id="2c202-869">Outlook</span></span>

- <span data-ttu-id="2c202-870">\*\* Outlook のユーザー エクスペリエンスを更新しました：\*\* これまで Coming Soon でプレビューできていた、最も重要なことに集中できるようにするためのシンプルな操作性です。</span><span class="sxs-lookup"><span data-stu-id="2c202-870">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="2c202-871">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-871">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="2c202-872">**カスタマイズも可能、シンプルになったリボン：** 最もよく使うボタンが単一行にまとめられ、使いやすくなりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-872">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="2c202-873">簡単に従来のビューとシンプルなビューを切り替えたり、コマンドを固定または固定解除できます。</span><span class="sxs-lookup"><span data-stu-id="2c202-873">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="2c202-874">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-874">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="2c202-875">**メッセージの移動中も作業が可能:** Outlook では、メッセージの移動がバックグラウンドで行われるようになったため、フォルダー間で多数のメッセージの移動が行われている間も作業を続けることができます。</span><span class="sxs-lookup"><span data-stu-id="2c202-875">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="2c202-876">**連続する会議の合間に時間を組み込む:** 既定で 5 分から 10 分早く会議を終了するように設定することで、出席者に休憩時間や場所の移動時間を与えることができます。</span><span class="sxs-lookup"><span data-stu-id="2c202-876">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="2c202-877">**お気に入りのアクションを選びましょう：** フラグや、削除機能を使いますか？</span><span class="sxs-lookup"><span data-stu-id="2c202-877">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="2c202-878">アーカイブまたは既読に​​しますか?</span><span class="sxs-lookup"><span data-stu-id="2c202-878">How about Archive or Mark as Read?</span></span> <span data-ttu-id="2c202-879">クイック操作メニューをカスタマイズしてよく使うコマンドを追加できます。</span><span class="sxs-lookup"><span data-stu-id="2c202-879">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="2c202-p178">**ミームが表示される:** テキストまたは静的イメージだけでは十分ではない場合、アニメーション GIF を使用して要点を示すことができます。[詳細情報](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="2c202-p178">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="2c202-882">**より簡単なアカウントの追加方法:** アカウントのセットアップの改善により、2 要素認証を使用する Outlook.com と Gmail のアカウントを Outlook に追加することが以前よりも簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-882">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="2c202-883">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-883">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="2c202-884">**同期制限にさよならしましょう:** Outlook の改善によりフォルダーの制限が解消され、そのまま共有メールボックスが同期されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-884">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="2c202-885">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-885">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="2c202-886">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="2c202-886">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="2c202-887">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-887">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="2c202-888">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2c202-888">PowerPoint</span></span>

- <span data-ttu-id="2c202-889">**よりよい変形操作:** 図形に名前を付けると、変形するときにより細かく制御できます。</span><span class="sxs-lookup"><span data-stu-id="2c202-889">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="2c202-890">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-890">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="2c202-891">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="2c202-891">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="2c202-892">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="2c202-892">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="2c202-893">**コンテンツのリーチを拡大する:** プレゼンテーションのアクセシビリティを高める必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="2c202-893">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="2c202-894">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="2c202-894">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="2c202-895">[校閲]>[アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-895">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="2c202-896">**シームレスに切り替える:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用のアカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-896">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="2c202-897">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-897">Switching between them has never been easier.</span></span> [<span data-ttu-id="2c202-898">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-898">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="2c202-899">**オンライン ビデオの新しい保存場所:** Microsoft Stream にビデオを保存すれば、組織内のすべてのユーザーが視聴できます。</span><span class="sxs-lookup"><span data-stu-id="2c202-899">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="2c202-900">ビデオのリンクを挿入すれば、小さなファイル サイズでマルチメディア プレゼンテーションをご利用いただけます。</span><span class="sxs-lookup"><span data-stu-id="2c202-900">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="2c202-901">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-901">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="2c202-902">**変更が発生したときに変更内容を自動的に保存する:** 変更が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="2c202-902">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="2c202-p186">**ユーザーへのテストやアンケート:** テストやアンケートをスライドに配置します。Office で応答が自動的に収集され、保存されます。[詳細情報](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="2c202-p186">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="2c202-906">**これまで以上に簡単にオンライン ビデオを挿入できるようになりました:** Vimeo または YouTube からビデオをスライドに挿入する場合は、</span><span class="sxs-lookup"><span data-stu-id="2c202-906">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide?</span></span> <span data-ttu-id="2c202-907">ビデオ ページへのリンクがあれば簡単に行えます。</span><span class="sxs-lookup"><span data-stu-id="2c202-907">The video page link is all you need.</span></span> [<span data-ttu-id="2c202-908">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-908">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="2c202-909">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-909">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="2c202-910">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="2c202-910">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="2c202-911">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-911">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="2c202-912">Project</span><span class="sxs-lookup"><span data-stu-id="2c202-912">Project</span></span>

- <span data-ttu-id="2c202-913">**シームレスに切り替える:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用のアカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-913">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="2c202-914">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-914">Switching between them has never been easier.</span></span> [<span data-ttu-id="2c202-915">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-915">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="2c202-916">Visio</span><span class="sxs-lookup"><span data-stu-id="2c202-916">Visio</span></span>

- <span data-ttu-id="2c202-917">**プロセス図を Word にエクスポート:** Word 文書に図形やメタデータなどのグラフ コンテンツを自動的に追加します。</span><span class="sxs-lookup"><span data-stu-id="2c202-917">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="2c202-918">その後に、文書をカスタマイズしてプロセスに関するガイドラインや操作マニュアルを作成できます。</span><span class="sxs-lookup"><span data-stu-id="2c202-918">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="2c202-919">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-919">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="2c202-920">**はっとするようなデータ フローチャート:** データ ビジュアライザーのフローチャートの見事な新しいレイアウトがすっきり、はっきり、わかりやすくなりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-920">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="2c202-921">オプションの [デザイン] タブをクリックします。</span><span class="sxs-lookup"><span data-stu-id="2c202-921">Click the Design tab for options.</span></span>

- <span data-ttu-id="2c202-922">**Azure ステンシルが組み込まれました:** 豊富な Azure ステンシルを使用してクラウド アプリの設計やアーキテクチャの計画を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="2c202-922">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="2c202-923">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-923">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="2c202-p193">**壊れた Excel リンクの問題を解消:** データ ビジュアライザーの図にリンクされているはずの Excel ブックが見つかりませんか? 再リンクして、すぐに業務を再開できます。[詳細情報](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="2c202-p193">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="2c202-927">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-927">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="2c202-928">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-928">Switching between them has never been easier.</span></span> [<span data-ttu-id="2c202-929">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-929">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="2c202-930">**Power BI から Visio ビジュアルをエクスポートする:** Power BI レポートを PDF、PowerPoint などのファイルとしてエクスポートするときに、Power BI 用の Visio ビジュアルが正しく表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-930">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="2c202-931">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-931">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="2c202-932">Word</span><span class="sxs-lookup"><span data-stu-id="2c202-932">Word</span></span>

- <span data-ttu-id="2c202-933">**[学習ツール] モードで、ページで使用できる色が増えました:** Word の学習ツールでは、より多くのページ テーマ色が追加され、ページの背景色を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-933">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="2c202-934">すべて白またはすべて黒の背景だと読みにくいと感じるユーザーは少なくないため、PC と Mac の Word で色の選択肢を拡大しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-934">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="2c202-p197">**インク エディターを使った自然な編集:** ペンを使って 1 ストローク描くだけで、単語の分割や結合、新しい線の追加、単語の挿入などができます。[詳細情報](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="2c202-p197">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="2c202-p198">**静的なドキュメントから魅力的なドキュメントへの変換:** ドキュメントを、すべてのデバイスに対応する対話型の使いやすい Web ページに変換します。[詳細情報](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="2c202-p198">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="2c202-939">**コンテンツのリーチを拡大する:** ドキュメントのアクセシビリティを高める必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="2c202-939">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="2c202-940">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="2c202-940">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="2c202-941">[校閲]>[アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-941">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="2c202-942">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="2c202-942">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="2c202-943">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="2c202-943">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="2c202-944">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-944">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="2c202-945">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-945">Switching between them has never been easier.</span></span> [<span data-ttu-id="2c202-946">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-946">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="2c202-p202">**行フォーカスによる読解力の向上:** ドキュメント内で行ごとの移動をスムーズに行います。一度に 1 行か、3 行か、5 行かを表示するようフォーカスを調整できます。[詳細情報](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="2c202-p202">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="2c202-950">**変更時に変更内容を保存する:** すべての更新が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="2c202-950">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="2c202-951">**\@メンションを使用してユーザーの注意を引く:** コメントで @メンションを使うと、仕事仲間による入力が必要な場合にそのユーザーに知らせることができます。</span><span class="sxs-lookup"><span data-stu-id="2c202-951">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="2c202-952">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-952">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="2c202-953">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-953">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="2c202-954">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="2c202-954">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="2c202-955">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-955">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="2c202-956">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2c202-956">Office Suite</span></span>

- <span data-ttu-id="2c202-957">**特定のファイルをすばやく見つける:** 最近作業を行ったファイルを探している場合は、</span><span class="sxs-lookup"><span data-stu-id="2c202-957">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="2c202-958">[ファイル] > [開く] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="2c202-958">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="2c202-959">**変更が発生したときに変更内容を自動的に保存する:** 変更が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="2c202-959">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="2c202-960">**プライバシー制御**: 診断データとコネクテッド エクスペリエンス用に新しく更新されて、改善された制御。</span><span class="sxs-lookup"><span data-stu-id="2c202-960">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="2c202-961">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-961">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="2c202-962">**新しい外観を備えた Office のアイコン:** シンプルかつ高性能で、インテリジェントな Office のエクスペリエンスを反映するように、Office のアイコンがリニューアルされました。</span><span class="sxs-lookup"><span data-stu-id="2c202-962">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="2c202-963">**Microsoft Teams のインストール:** Microsoft Teams は、Office 365 ProPlus の既存のインストールに既定でインストールされています。</span><span class="sxs-lookup"><span data-stu-id="2c202-963">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="2c202-964">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2c202-964">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2c202-967">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2c202-967">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2c202-968">Access</span><span class="sxs-lookup"><span data-stu-id="2c202-968">Access</span></span>

- <span data-ttu-id="2c202-969">この更新プログラムにより、Sum などの集計が結果を整数値に切り捨てる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-969">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="2c202-970">この更新プログラムにより、リモート テーブル (SQL Server テーブルなど) への参照を含むユニオン クエリにより Access が閉じて再起動する問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-970">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="2c202-971">この更新プログラムにより、更新クエリが実行されるか、SQL で UPDATE ステートメントが使用されるときに &quot;クエリは破損しています&quot; というエラーを発生させる場合のある Microsoft Access の問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-971">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="2c202-972">Excel</span><span class="sxs-lookup"><span data-stu-id="2c202-972">Excel</span></span>

- <span data-ttu-id="2c202-973">ドキュメント タイトルのオランダ語の KeyTip が Alt-G に変更されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-973">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="2c202-974">図形やフォームコントロールに割り当てられているマクロが間違ったエラーメッセージとして表示される、または間違った対象範囲で動作する問題が Excel で修正されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-974">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="2c202-975">最初のアイテムを検索した後に、ダイアログでのフォーカスの位置が変更されてしまう検索と置換についての問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-975">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="2c202-976">これにより、ピボットテーブルの並べ替え方法を変更し、他のユーザーとの共同編集セッション中にそれを更新するとクラッシュが発生する可能性がある問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-976">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="2c202-977">OLAP ピボットテーブルのフィルターが、キューブから削除された値に設定された場合の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-977">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="2c202-978">グラフ テンプレートを使用してグラフを挿入する場合に、プレビューで正しい色が使用されるよう修正します。</span><span class="sxs-lookup"><span data-stu-id="2c202-978">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="2c202-979">シリーズ コレクションを変更するときに、散布図が適切にレンダリングされない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-979">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="2c202-980">セルが挿入または削除されたときに、ウォーターフォール図とじょうごグラフがテーブルと同期しなくなる原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-980">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="2c202-981">Excel で、ユーザーが変更を取得するためにブックを再び開くよう要求されるマージ競合の問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-981">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="2c202-982">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-982">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="2c202-983">最小化されたウィンドウをアクティブにするマクロ実行時エラーの原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-983">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="2c202-984">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-984">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="2c202-985">他のユーザーと共同編集しているときに、テーブルの横にある切り取りと貼り付けの操作が失敗する原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-985">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="2c202-986">実行中のマクロでカスタム プロパティを変更するときに、共同編集の中断を引き起こす原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-986">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="2c202-987">アドインによって開かれた WPF (Windows Presentation Foundation) フォームのコンボ ボックスからアイテムを選ぶことができない問題が発生しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-987">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="2c202-988">ブックが開かれていない状態で最近使用したファイルを検索するときに、クラッシュを発生させる原因となっていた可能性がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-988">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="2c202-989">非同期のユーザー定義関数が同期して実行されるパフォーマンスの問題が発生しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-989">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="2c202-990">結合されたセルで列を削除するパフォーマンスが大幅に改善されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-990">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="2c202-991">スクロール後にセルを選択すると間違ったセルが選択されることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-991">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="2c202-992">Lookup 関数がエラーを返す問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-992">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="2c202-993">Office の以前のバージョンで作成されたブックを Office の最新のバージョンで開いたときに、Excel の終了を引き起こす可能性がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-993">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="2c202-994">ファイルに広範な条件付き書式が設定されている場合に、[フォントの色] ボタンをクリックするとパフォーマンスが低下する問題。</span><span class="sxs-lookup"><span data-stu-id="2c202-994">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="2c202-995">印刷プレビューの印刷範囲が正しくないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-995">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="2c202-996">信頼されていないネットワーク共有から保護されたファイルを編集する際に、Excel にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-996">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="2c202-997">色によるフィルタリングのパフォーマンスが大幅に改善されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-997">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="2c202-998">一部の保護されたシートにハイパーリンクが貼り付けられない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-998">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="2c202-999">アドイン マネジャーで参照するときに、16 個を超えるアドインを表示できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-999">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="2c202-1000">この変更は、ソフトウェア レンダリングを活用することにより、特定の Intel グラフィック ドライバーの問題を回避します。</span><span class="sxs-lookup"><span data-stu-id="2c202-1000">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="2c202-1001">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1001">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2c202-1002">この更新プログラムにより、"アップロードできませんでした" というメッセージが表示され、Office ドキュメントが OneDrive for Business にアップロードされないことがあるエラーが修正されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-1002">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="2c202-1003">Win32 クライアントの [アイデア] ボタンをクリックしてアドインを読み込むときにエラーが発生するという Excel のアイデア機能の問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="2c202-1003">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="2c202-1004">Outlook</span><span class="sxs-lookup"><span data-stu-id="2c202-1004">Outlook</span></span>

- <span data-ttu-id="2c202-1005">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1005">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2c202-1006">メールボックスを基本認証から最新認証にアップグレードしたユーザーが、Outlook プロファイルに関連付けられた正しくないアカウントで終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1006">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="2c202-1007">Web アドインがデジタル著作権管理 (DRM) メッセージにアクセスすべきでないときにアクセスする原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1007">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="2c202-1008">一部のセーフリンクに対して簡易的なホバーの URL が正しく表示されなくなる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1008">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="2c202-1009">これにより、Python による添付ファイルもブロックされるよう、Outlook の添付ファイルのブロック ロジックが更新されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1009">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="2c202-1010">設定に関係なく、一部の POP3 ユーザーに、すべてのメールがプレーンテキストで書式設定されて表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1010">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="2c202-1011">この修正プログラムでは、HTML 形式のメッセージの表示が復元されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-1011">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="2c202-1012">プライマリ予定表からグループ予定表にアイテムをコピーするときに、ユーザーにアクセス許可のエラーを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1012">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="2c202-1013">ユーザーがスクリーン リーダーから場所の候補にアクセスできない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1013">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="2c202-1014">ユーザーがキーボード ショートカットを使用してメールボックス フォルダーを操作するときに、顕著な遅延を発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1014">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="2c202-1015">非常に長い Outlook セッションでメモリ リークを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1015">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="2c202-1016">ユーザーが [ルール] ダイアログを開くと、"このコンピューターのルールは、Microsoft Exchange のルールと異なります" というメッセージが表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1016">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="2c202-1017">特定のセーフリンクを操作するときに、Outlook でクラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1017">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="2c202-1018">代理人が特定の会議出席依頼に既に返信したかどうかに関係なく、管理者が不明瞭になる原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1018">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="2c202-1019">一部の AutoDiscover の応答を処理するときに、クラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1019">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="2c202-1020">アカウント作成コンテキストからサポートに連絡しようとすると、ユーザーに [OK] ボタンのある空のメッセージ ボックスが表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1020">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="2c202-1021">この変更により、UPN 経由で自動検出の認証プロンプトに提供されるアカウントのメールを選択するため、ポリシーを管理者が有効にできるようになります。</span><span class="sxs-lookup"><span data-stu-id="2c202-1021">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="2c202-1022">既定では、使用可能な場合に、自動検出ではアカウント UPN の方が選択されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-1022">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="2c202-1023">最新のグループに対し、検索の失敗がユーザーに表示される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1023">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="2c202-1024">Outlook ユーザーが特定のシナリオで "パスワードを要求している" 状態で停止する原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1024">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="2c202-1025">会議室の空き時間外に行われた会議のためにユーザーにその会議室が提案される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1025">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="2c202-1026">ユーザーが暗号化されたメールを送信しようとするときに、"暗号化アルゴリズムがサポートされていません" というエラーを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1026">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="2c202-1027">英語以外の言語を使用するユーザーの、メールの件名が非常に小さくなるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1027">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="2c202-1028">一部のユーザーに、セカンダリ Exchange アカウントを追加するときに作成された、重複した特別なフォルダーが表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1028">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="2c202-1029">"不在着信した会話" メッセージのルールを作成しようとするときに、クラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1029">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="2c202-1030">SMIME アルゴリズムの選択に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1030">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="2c202-1031">代替送信者を使用しているときに、ポリシーのヒントが表示されない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1031">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="2c202-1032">ユーザーが Outlook プロセスでメモリ リークを観測する原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1032">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="2c202-1033">プレゼンス情報を更新するときに、断続的なクラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1033">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="2c202-1034">現在のフォルダー検索で断続的な失敗を引き起こす原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1034">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="2c202-1035">一部のユーザーが Outlook のクラウド設定を取得しようとするときに、認証エラーが発生する原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1035">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="2c202-1036">検索に関するフィードバックのエクスペリエンスで終了する原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1036">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="2c202-1037">一部の AutoDiscover の応答を処理するときに、クラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1037">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="2c202-1038">プレゼンス情報を更新するときに、断続的なクラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1038">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2c202-1039">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2c202-1039">PowerPoint</span></span>

- <span data-ttu-id="2c202-1040">一部のアドインがグラフの図形に対して予期しないエラーをスローさせる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1040">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="2c202-1041">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1041">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2c202-1042">この変更により、PowerPoint ビデオ コントロールのアクセス可能な名前が復元されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-1042">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="2c202-1043">一部のアニメーションが開始しないことがあるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1043">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="2c202-1044">スライドを 1 つのプレゼンテーションから別のプレゼンテーションにコピーすると、重複したマスターが作成される可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1044">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="2c202-1045">最新のコメントを含むファイルを、サポートされていないバージョンで開くと黄色の警告が表示されます</span><span class="sxs-lookup"><span data-stu-id="2c202-1045">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="2c202-1046">信頼性の修正: サード パーティのアドインが PowerPoint のクラッシュを発生させる可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1046">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="2c202-1047">PowerPoint の垂直テキスト ボックスで半角カタカナ文字が適切に回転しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1047">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="2c202-1048">Project</span><span class="sxs-lookup"><span data-stu-id="2c202-1048">Project</span></span>

- <span data-ttu-id="2c202-1049">Windows 7 のユーザーが Project Web App および SharePoint サイトからプロジェクトを開くことができるように問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1049">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="2c202-1050">読み取り専用のプロジェクトを開いたときに複数のメッセージを取得する可能性があるという問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1050">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="2c202-1051">[すべて平準化] コマンドがリソースの割り当て超過を適切に解決しません。</span><span class="sxs-lookup"><span data-stu-id="2c202-1051">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="2c202-1052">タスクの作業がゼロの割り当てがある場合、タスクに完了のマークを付けることができず、常に 99％ で表示される問題。</span><span class="sxs-lookup"><span data-stu-id="2c202-1052">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="2c202-1053">Visio</span><span class="sxs-lookup"><span data-stu-id="2c202-1053">Visio</span></span>

- <span data-ttu-id="2c202-1054">Visio から SVG へのエクスポートが、さまざまな図形で失敗していました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1054">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="2c202-1055">Word</span><span class="sxs-lookup"><span data-stu-id="2c202-1055">Word</span></span>

- <span data-ttu-id="2c202-1056">この変更により、Word を使ってドキュメントを開くときのパフォーマンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="2c202-1056">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="2c202-1057">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1057">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2c202-1058">Deskjet プリンターに印刷するときに、スケーリングの問題を引き起こす可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1058">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="2c202-1059">無限ループになることがあるトラック変更の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1059">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="2c202-1060">シャットダウン時にアプリが終了することがあるさまざまな問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1060">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="2c202-1061">特定のアドインに関連するクラッシュも修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1061">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2c202-1062">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2c202-1062">Office Suite</span></span>

- <span data-ttu-id="2c202-1063">新元号の名前である “Reiwa” のひらがなと漢字をスペルミスまたは間違った文法として誤って識別していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1063">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="2c202-1064">SharePoint 2016 に保存されているファイルを共有しようとするときに、"申し訳ございません。何かがこのファイルの共有を妨げています。" というメッセージが表示される原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1064">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="2c202-1065">PowerPoint での共同編集とオフライン編集の両方を含むセッションでデータの損失を引き起こす可能性のある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1065">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="2c202-1066">これは、ユーザーがファイルを開くときに発生する可能性のあるクラッシュの修正プログラムです。</span><span class="sxs-lookup"><span data-stu-id="2c202-1066">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="2c202-1067">PowerPoint ユーザーがオンライン プレゼンテーションを行おうとするときに、エラーが発生しないようにします。</span><span class="sxs-lookup"><span data-stu-id="2c202-1067">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="2c202-1068">同期エンジンでバックアップされた Sharepoint ファイルに '保存済み' と表示されますが、場合によっては実際に変更が保存されないため、データを損失することになります。</span><span class="sxs-lookup"><span data-stu-id="2c202-1068">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="2c202-1069">ユーザーが Word、Excel、および PowerPoint のドキュメントを保存できなくなることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1069">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="2c202-1070">この問題は、[保存] アイコンをクリックしたり Ctrl キーを押しながら S キーを押したりした後に、新しいファイルを作成して [ダイアログで保存] オプションを表示するユーザーに影響を与えます。</span><span class="sxs-lookup"><span data-stu-id="2c202-1070">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="2c202-1071">すべてのアプリのリボンで、図形の挿入ギャラリーが表示されるまでに約 4 秒かかるという Win7 のパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1071">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="2c202-1072">Backstage の Info Place のスラブにアクセシビリティ情報が表示されていないというバグを修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1072">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="2c202-1073">レジストリ整合性に関する Office 更新プロセスの信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1073">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="2c202-1074">Office の更新プログラムが、意図したソース (ローカル共有、ネットワーク共有、構成マネージャー
で提供される場所など) からではなく、予期せずに Office CDN からファイルをダウンロードする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1074">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="2c202-1075">Office の更新メッセージが、異なる言語で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1075">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="2c202-1076">今後、Office の更新メッセージは Windows の表示言語と一致します。</span><span class="sxs-lookup"><span data-stu-id="2c202-1076">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="2c202-1077">ユーザーが管理者ではなく、システム アカウントにネットワーク接続が確立されていない場合に、更新プログラムが適用されない問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1077">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="2c202-1078">特定の状況で、更新後に Office ショートカットが消えてしまう場合があります。</span><span class="sxs-lookup"><span data-stu-id="2c202-1078">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="2c202-1079">この更新プログラムにより、Office ショートカットを公開するときの信頼性が向上します。</span><span class="sxs-lookup"><span data-stu-id="2c202-1079">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="2c202-1080">従量制課金ネットワークで更新プログラムが予期せずブロックされる可能性があるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1080">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="2c202-1081">ODT と GPO の更新期限設定で、相対期限の設定後、初回のみしか機能しないバスが修正されました。修正により、2 回目以降の更新プログラムで相対期限を使用きるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1081">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="2c202-1082">以前に中断された可能性のあるダウンロードを再開することにより、Office の更新プログラムをダウンロードするときの信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1082">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="2c202-1083">サード パーティ製プラグインのテキスト ボックスと図形の自動調整に関連する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1083">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="2c202-1084">大きなツリー ビューがクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1084">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="2c202-1085">Office ユーザーのセキュリティを保護するために、Microsoft Office の更新プログラムは SHA-2 アルゴリズムのみを使用して署名されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1085">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1902-january-14"></a><span data-ttu-id="2c202-1087">バージョン 1902: 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2c202-1087">Version 1902: January 14</span></span>
<span data-ttu-id="2c202-1088">*バージョン 1902 (ビルド 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="2c202-1088">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="2c202-1089">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2c202-1089">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2c202-1091">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2c202-1091">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2c202-1092">Excel</span><span class="sxs-lookup"><span data-stu-id="2c202-1092">Excel</span></span>

- <span data-ttu-id="2c202-1093">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2c202-1093">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="2c202-1094">Outlook</span><span class="sxs-lookup"><span data-stu-id="2c202-1094">Outlook</span></span>

- <span data-ttu-id="2c202-1095">ユーザーが暗号化されたメールを送信しようとするときに、"暗号化アルゴリズムがサポートされていません" というエラーを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2c202-1095">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2c202-1096">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2c202-1096">PowerPoint</span></span>

- <span data-ttu-id="2c202-1097">最新のコメントを含むファイルを、サポートされていないバージョンで開くと黄色の警告が表示されます。</span><span class="sxs-lookup"><span data-stu-id="2c202-1097">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="2c202-1098">Word</span><span class="sxs-lookup"><span data-stu-id="2c202-1098">Word</span></span>

- <span data-ttu-id="2c202-1099">この変更により、Word を使ってドキュメントを開くときのパフォーマンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="2c202-1099">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1808-january-14"></a><span data-ttu-id="2c202-1101">バージョン 1808: 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2c202-1101">Version 1808: January 14</span></span>
<span data-ttu-id="2c202-1102">*バージョン 1808 (ビルド 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="2c202-1102">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="2c202-1103">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2c202-1103">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

> [!NOTE]
> <span data-ttu-id="2c202-1105">Office の使用で問題がある場合は、[Microsoft の回答フォーラム](https://answers.microsoft.com/)に関するページまたは「[Microsoft Tech Community](https://techcommunity.microsoft.com/)」に質問を投稿するか、[サポート](https://support.microsoft.com/contactus)に問い合わせてサポートを受けることができます。</span><span class="sxs-lookup"><span data-stu-id="2c202-1105">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (管理センターのメタデータのコンテンツを変更しないでください。開始)
[//]: # (|Win32|DC|Production| |16.0.12527.21104|version-2002-september-08|)
[//]: # (|Win32|DC|Production| |16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|DC|Production| |16.0.12527.20880|バージョン-2002-7 月-14|)
[//]: # (管理センターのメタデータのコンテンツ エンドを変更しないでください)
