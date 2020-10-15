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
ms.openlocfilehash: f7f3b39521132fb11226bc512f782e0adec5aba8
ms.sourcegitcommit: ef46a4fc154c7bca37e37a7456c36f92ffc15ebb
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/13/2020
ms.locfileid: "48453415"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-releases-in-2020"></a><span data-ttu-id="c0ea1-103">2020 年の半期エンタープライズ チャネル リリースのリリース ノート</span><span class="sxs-lookup"><span data-stu-id="c0ea1-103">Release notes for Semi-Annual Enterprise Channel releases in 2020</span></span>

<span data-ttu-id="c0ea1-104">このリリース ノートには、2020 年の半期エンタープライズ チャネルの更新プログラムに含まれる新機能と、セキュリティ以外の更新プログラムに関する情報が記載されています。対象となるのは、Microsoft 365 Apps for enterprise、Microsoft 365 Apps for business、および Project と Visio のデスクトップ アプリのサブスクリプション版です。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="c0ea1-105">現在、Microsoft 365 Apps の更新プログラム チャネルに、新しい更新プログラム チャネル (月次エンタープライズ チャネル) の追加や既存の更新プログラム チャネル名の変更など、いくつかの変更を進めています。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="c0ea1-106">詳細については、[こちらの記事](https://go.microsoft.com/fwlink/p/?linkid=2127441)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
>
>- <span data-ttu-id="c0ea1-107">半期エンタープライズ チャネルのユーザーが Office ポータルから Microsoft 365 Apps をダウンロードして Windows 10 にインストールすると、既定で OneNote 2016 が含まれるようになります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-107">OneNote 2016 will now be included by default when a user on the Semi-Annual Enterprise Channel downloads and installs Microsoft 365 Apps on Windows 10 from the Office Portal.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-october-13"></a><span data-ttu-id="c0ea1-109">バージョン 2002: 10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-109">Version 2002: October 13</span></span>
<span data-ttu-id="c0ea1-110">*バージョン2002 (ビルド 12527.21236)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-110">*Version 2002 (Build 12527.21236)*</span></span>

<span data-ttu-id="c0ea1-111">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-111">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="c0ea1-113">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="c0ea1-113">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c0ea1-114">Access</span><span class="sxs-lookup"><span data-stu-id="c0ea1-114">Access</span></span>

- <span data-ttu-id="c0ea1-115">Access データベースのガイドラインと要件を満たしている限り、Accessの 64-ビットバージョンで"クエリが複雑すぎます" や "システム超かエラー" が表示されなくなります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-115">You should no longer receive a "Query is too complex" or a system resource exceeded error on your 64-bit version of Access, as long as you are meeting Access database guidelines and requirements.</span></span>


- <span data-ttu-id="c0ea1-116">クエリデザイナーの後にフィルター機能を使用すると、データベースがクラッシュしなくなります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-116">Once you decide to use our filter feature after our query designer, your database should no longer crash.</span></span> <span data-ttu-id="c0ea1-117">それについて確認してください。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-117">Please check accordingly.</span></span>


### <a name="excel"></a><span data-ttu-id="c0ea1-118">Excel</span><span class="sxs-lookup"><span data-stu-id="c0ea1-118">Excel</span></span>

- <span data-ttu-id="c0ea1-119">Analysis Services データベースに既に存在しない値に設定されているために、ユーザーがピボットテーブル フィルターを変更できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-119">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c0ea1-120">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c0ea1-120">PowerPoint</span></span>

- <span data-ttu-id="c0ea1-121">テンプレートから作成された新しいプレゼンテーションは、効率的な共同編集をうまく行うことができない設定を継承する場合があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-121">New presentations created from a template could inherit a setting that prevented  a good co-authoring experience.</span></span> <span data-ttu-id="c0ea1-122">この修正プログラムでは、この場合は設定がクリアされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-122">This fix ensures that the setting is cleared in this case.</span></span>


### <a name="word"></a><span data-ttu-id="c0ea1-123">Word</span><span class="sxs-lookup"><span data-stu-id="c0ea1-123">Word</span></span>

- <span data-ttu-id="c0ea1-124">ページ区切りと列を含む文書を開くと、"Microsoft Word で許可されている最大ページ数を超えたか、またはドキュメントが破損している可能性があります" というエラーメッセージが表示されることがありましたが、この問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-124">We fixed an issue which when opening documents with page breaks and columns, user might encountered an error message, " You have exceeded the maximum number of pages allowed by Microsoft Word supported, or the document may be damaged"</span></span>


### <a name="office-suite"></a><span data-ttu-id="c0ea1-125">Office スイート</span><span class="sxs-lookup"><span data-stu-id="c0ea1-125">Office Suite</span></span>

- <span data-ttu-id="c0ea1-126">Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-126">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="c0ea1-127">このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-127">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-october-13"></a><span data-ttu-id="c0ea1-129">バージョン1908: 10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-129">Version 1908: October 13</span></span>
<span data-ttu-id="c0ea1-130">*バージョン 1908 (ビルド 11929.20966)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-130">*Version 1908 (Build 11929.20966)*</span></span>

<span data-ttu-id="c0ea1-131">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-131">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="c0ea1-133">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="c0ea1-133">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="c0ea1-134">Office スイート</span><span class="sxs-lookup"><span data-stu-id="c0ea1-134">Office Suite</span></span>

- <span data-ttu-id="c0ea1-135">Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-135">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="c0ea1-136">このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-136">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-september-08"></a><span data-ttu-id="c0ea1-138">バージョン 2002: 9 月 08 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-138">Version 2002: September 08</span></span>
<span data-ttu-id="c0ea1-139">*バージョン2002 (ビルド12527.21104)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-139">*Version 2002 (Build 12527.21104)*</span></span>

<span data-ttu-id="c0ea1-140">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-140">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="c0ea1-142">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="c0ea1-142">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c0ea1-143">Excel</span><span class="sxs-lookup"><span data-stu-id="c0ea1-143">Excel</span></span>

- <span data-ttu-id="c0ea1-144">これは、以前のバージョンの Office で SQL データプロバイダーによって作成された接続が内部テーブルのプロパティを Office 365 とは別に設定する問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-144">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="c0ea1-145">これにより、Office 365 を使用して開かれた以前のバージョンの Office で作成された接続を持つファイルに対して、[テーブルのプレビュー / クエリエディター] のドロップダウンが無効になりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-145">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>


- <span data-ttu-id="c0ea1-146">手描き入力で Excel が応答しなくなる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-146">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="c0ea1-147">Outlook</span><span class="sxs-lookup"><span data-stu-id="c0ea1-147">Outlook</span></span>

- <span data-ttu-id="c0ea1-148">共有メールボックスを追加した後に、ユーザーがパブリック フォルダーに接続できない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-148">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


### <a name="office-suite"></a><span data-ttu-id="c0ea1-149">Office スイート</span><span class="sxs-lookup"><span data-stu-id="c0ea1-149">Office Suite</span></span>

- <span data-ttu-id="c0ea1-150">この変更では、[図の圧縮] ダイアログで一部のユーザー設定が保持されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-150">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-1908-september-08"></a><span data-ttu-id="c0ea1-152">バージョン 1908: 9 月 08 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-152">Version 1908: September 08</span></span>
<span data-ttu-id="c0ea1-153">*バージョン 1908 (ビルド11929.20946)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-153">*Version 1908 (Build 11929.20946)*</span></span>

<span data-ttu-id="c0ea1-154">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-154">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-august-11"></a><span data-ttu-id="c0ea1-155">バージョン 2002: 8 月 11 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-155">Version 2002: August 11</span></span>
<span data-ttu-id="c0ea1-156">*バージョン 2002 (ビルド 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-156">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="c0ea1-157">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-157">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="c0ea1-159">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="c0ea1-159">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c0ea1-160">Excel</span><span class="sxs-lookup"><span data-stu-id="c0ea1-160">Excel</span></span>

- <span data-ttu-id="c0ea1-161">「読み取り専用推奨」として開かれたファイルの編集に切り替えられない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-161">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="c0ea1-162">OneNote</span><span class="sxs-lookup"><span data-stu-id="c0ea1-162">OneNote</span></span>

- <span data-ttu-id="c0ea1-163">リソースの使用率を低下させるための冗長な ID 呼び出しが削除されました</span><span class="sxs-lookup"><span data-stu-id="c0ea1-163">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="c0ea1-164">リソースの使用率を低下させて、共同編集状態の検出機能を改善します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-164">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="c0ea1-165">エラーを検出する機能が改善され、同期環境の品質が向上しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-165">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="c0ea1-166">Outlook</span><span class="sxs-lookup"><span data-stu-id="c0ea1-166">Outlook</span></span>

- <span data-ttu-id="c0ea1-167">一部のテナントで Outlook を起動したときに重大なパフォーマンスの問題が発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-167">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="c0ea1-168">Skype</span><span class="sxs-lookup"><span data-stu-id="c0ea1-168">Skype</span></span>

- <span data-ttu-id="c0ea1-169">数日間稼働した後に、32 ビット版の Skype for Business クライアントで画面共有を開始できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-169">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c0ea1-170">Office スイート</span><span class="sxs-lookup"><span data-stu-id="c0ea1-170">Office Suite</span></span>

- <span data-ttu-id="c0ea1-171">グループ ポリシーを介して自動保存が無効にされた場合に、ユーザーが [利用可能な更新] をクリックするまで一部のドキュメントで最新のサーバー コンテンツが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-171">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-august-11"></a><span data-ttu-id="c0ea1-173">バージョン 1908: 8 月 11 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-173">Version 1908: August 11</span></span>
<span data-ttu-id="c0ea1-174">*バージョン 1908 (ビルド 11929.20934)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-174">*Version 1908 (Build 11929.20934)*</span></span>

<span data-ttu-id="c0ea1-175">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-175">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1902-august-11"></a><span data-ttu-id="c0ea1-176">バージョン 1902: 8 月 11 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-176">Version 1902: August 11</span></span>
<span data-ttu-id="c0ea1-177">*バージョン 1902 (ビルド 11328.20644)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-177">*Version 1902 (Build 11328.20644)*</span></span>

<span data-ttu-id="c0ea1-178">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-178">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-july-14"></a><span data-ttu-id="c0ea1-181">バージョン 2002: 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-181">Version 2002: July 14</span></span>
<span data-ttu-id="c0ea1-182">*バージョン 2002 (ビルド 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-182">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="c0ea1-183">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-183">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="c0ea1-185">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="c0ea1-185">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="c0ea1-186">Access</span><span class="sxs-lookup"><span data-stu-id="c0ea1-186">Access</span></span>

- <span data-ttu-id="c0ea1-187">**リンク テーブルをすばやく見つける:** 新しい検索ボックスを使用すると、リンク テーブルを簡単に見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-187">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="c0ea1-188">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-188">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="c0ea1-189">Excel</span><span class="sxs-lookup"><span data-stu-id="c0ea1-189">Excel</span></span>

- <span data-ttu-id="c0ea1-190">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-190">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="c0ea1-191">**データ ビジュアライザー アドイン:** Excel から Visio フローチャートをすばやく作成します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-191">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="c0ea1-192">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-192">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="c0ea1-193">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-193">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="c0ea1-194">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-194">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="c0ea1-195">[ブログの投稿](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="c0ea1-195">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="c0ea1-196">**自分の気分を表現するアイコンの追加:** 300 個以上の新しいアイコンが追加されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-196">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="c0ea1-197">[挿入]、[アイコン] の順に検索してください。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-197">Find them at Insert > Icons.</span></span> [<span data-ttu-id="c0ea1-198">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-198">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="c0ea1-199">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-199">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="c0ea1-200">[ブログの投稿](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="c0ea1-200">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="c0ea1-201">**残っている作業に集中する:** [解決] を選択して、コメントを折りたたみ、開いているアイテムを目立たせます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-201">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="c0ea1-202">**複数の値を返す式を入力する:** 複数の値を返す式を素早く入力できるようになりました。隣接するセルに自動的に入力されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-202">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="c0ea1-203">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-203">Learn more</span></span>](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br /><span data-ttu-id="c0ea1-204">[ブログの投稿](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="c0ea1-204">See details in [blog post](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span></span>

- <span data-ttu-id="c0ea1-205">**ブラウザーへのバウンスは不要** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-205">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="c0ea1-206">**あらましを描く:** ブック内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-206">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="c0ea1-207">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-207">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="c0ea1-208">[ブログの投稿](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="c0ea1-208">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="c0ea1-209">**探しているものを見つける:** コマンド、ユーザー、ファイル、写真、Web の記事などを検索できます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-209">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="c0ea1-210">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-210">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="c0ea1-211">**6 つの強力な機能:** スプレッドシートを強化する 6 つの新しい関数が追加されました。FILTER、SORT、SORTBY、UNIQUE、SEQUENCE、RANDARRAY です。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-211">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span> [<span data-ttu-id="c0ea1-212">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-212">Learn more</span></span>](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- <span data-ttu-id="c0ea1-213">**左を見て、右を見て... XLOOKUP をご利用いただけます!** XLOOKUP を使えば、表や範囲内で必要なものは何でも見つけられます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-213">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="c0ea1-214">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-214">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br /><span data-ttu-id="c0ea1-215">[ブログの投稿](https://blog-insider.office.com/2019/08/29/announcing-xlookup/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="c0ea1-215">See details in [blog post](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span></span>

- <span data-ttu-id="c0ea1-216">**大きなブックを使いこなす:** セル、数式、グラフ、テーブル...ブックの統計情報を使用して、ブックのスナップショットを取得します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-216">**Tame your big workbook:** Cells, formulas, charts, tables... get a snapshot of your workbook with Workbook Statistics.</span></span>

- <span data-ttu-id="c0ea1-217">**すぐに読んで返信する:** ブックを開かずに、メールからコメントやメンションに直接返信します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-217">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="c0ea1-218">**\@メンションを使用してユーザーの注意を引く:** コメントで @メンションを使うと、仕事仲間による入力が必要な場合にそのユーザーに知らせることができます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-218">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="c0ea1-219">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-219">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="outlook"></a><span data-ttu-id="c0ea1-220">Outlook</span><span class="sxs-lookup"><span data-stu-id="c0ea1-220">Outlook</span></span>

- <span data-ttu-id="c0ea1-221">**より多くのメッセージを画面に収める:** [表示] > [より狭い文字間隔を使用] の順に選択し、メッセージの間隔を調整します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-221">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="c0ea1-222">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-222">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="c0ea1-223">**自分の気分を表現するアイコンの追加:** 300 個以上の新しいアイコンが追加されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-223">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="c0ea1-224">[挿入]、[アイコン] の順に検索してください。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-224">Find them at Insert > Icons.</span></span> [<span data-ttu-id="c0ea1-225">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-225">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="c0ea1-226">**自分で描いて表現しましょう:** 画像の上に走り書きするか、描画キャンバスを追加して、インクを用いて自分の考えを送信します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-226">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="c0ea1-227">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-227">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="c0ea1-228">**場所の候補を取得する:** 予定や会議をスケジュールするときに、[場所] に入力すると、会議室、住所、およびその他の最新の場所が提示されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-228">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="c0ea1-229">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-229">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)<br /><span data-ttu-id="c0ea1-230">[ブログの投稿](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="c0ea1-230">See details in [blog post](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span></span>

- <span data-ttu-id="c0ea1-231">**攻撃に対する高度な保護:** Office 365 Advanced Threat Protection を用いると、メールの件名、添付メッセージ、署名されたメッセージ、ネットワーク パスなどの範囲内のハイパーリンクを利用した攻撃から保護されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-231">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="c0ea1-232">**テナント管理者によって定義されたアクセス許可を使用して、Outlook の [リンクの挿入] メニューでリンクを挿入する:** Outlook で最近使用されたリンクの挿入 (MRU) のリンクでは、既にそれに対するアクセス許可を持つユーザーのみに動作したリンクが挿入されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-232">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="c0ea1-233">これは、ドキュメントへのアクセス権の付与を求めるユーザー間でのメールの行き来をしばしば引き起こします。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-233">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="c0ea1-234">このエクスペリエンスが更新されましたので、テナント管理者によって設定される既定のアクセス許可を使用し、リンクを挿入できるようになりました。MSIT の場合、これは「組織は編集可」なので、この方法で共有されるリンクを受信するすべての内部ユーザーもアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-234">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="c0ea1-235">**異なる明るさでメッセージを表示する:** [太陽] または [月] のボタンを使用して、閲覧ウィンドウの明るい背景と暗い背景を切り替えます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-235">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="c0ea1-236">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-236">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="c0ea1-237">**フィッシング メールの見分けが簡単に:** スパムとフィッシングのメッセージの外観が他とは異なるので、簡単に見分け、受信トレイから削除できます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-237">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="c0ea1-p123">**すべての暗号化オプションを 1 か所に集約:** [オプション] > [暗号化] の順に移動するだけで、電子メール メッセージを保護する方法を選択できます。[詳細情報](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-p123">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="c0ea1-240">**スペルチェックの問題や入力ミスで検索する:** スペルが一致しない場合でも何を検索しているか Outlook が探します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-240">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="c0ea1-241">\*\* Outlook に LinkedIn ネットワークを接続する:\*\* LinkedIn アカウントを Microsoft アカウントに安全に接続して、LinkedIn プロファイルからの情報を [連絡先カード] に直接表示できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-241">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="c0ea1-242">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-242">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="c0ea1-243">**検索結果で関連メッセージを確認する:** Outlook では検索条件を分析し、最も関連性の高いメール メッセージを検索結果の上部に表示します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-243">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="c0ea1-244">また、[上位の結果] セクションには、すべての結果が日付順に表示されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-244">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="c0ea1-245">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-245">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

### <a name="powerpoint"></a><span data-ttu-id="c0ea1-246">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c0ea1-246">PowerPoint</span></span>

- <span data-ttu-id="c0ea1-247">**手書きの数式の自動書式設定:** 手書きの数式を標準の文字に変換することができます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-247">**You compute, we format:** We change hand-drawn math expressions into standard characters.</span></span> <span data-ttu-id="c0ea1-248">変換を開始するには、[インクから数式] を選択して、手書きのメモを選択します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-248">Just choose Ink to Math and select your handwritten notes to get started.</span></span> [<span data-ttu-id="c0ea1-249">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-249">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="c0ea1-250">**探しているものを見つける:**[検索] ボックスを使用して、テキスト、コマンド、ヘルプなどを探します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-250">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="c0ea1-251">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-251">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="c0ea1-252">**インクで素晴らしいスライドを作成する:** インクを標準的な図形やテキストに変換してから、PowerPoint デザイナーの洗練されたスライドのデザイン アイデアを活用できます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-252">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="c0ea1-253">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-253">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="c0ea1-254">**あらましを描く:** プレゼンテーション内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-254">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="c0ea1-255">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-255">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="c0ea1-256">[ブログの投稿](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="c0ea1-256">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="c0ea1-257">**インクを瞬時に再生:** スライドで手描き入力する場合は、スライド ショー中にアニメーションの再生を適用して、インクの実際の描画が再生されるようにします。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-257">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="c0ea1-258">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-258">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)<br /><span data-ttu-id="c0ea1-259">[ブログの投稿](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="c0ea1-259">See details in [blog post](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span></span>

- <span data-ttu-id="c0ea1-260">**より安全なビデオ エクスペリエンス:** セキュリティの強化は、より安全なオンライン ビデオ エクスペリエンスを意味します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-260">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="c0ea1-261">**図を SVG として保存する:** グラフ、図形、その他の図を、サイズ変更しても画質が低下しないスケーラブル ベクター グラフィックとして保存できます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-261">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="c0ea1-262">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-262">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="c0ea1-263">**配布資料にスライド番号を印刷する:** スライド番号は配布資料に自動的に含まれます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-263">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="c0ea1-264">それらをオンのままにするか、オフにするか、選択します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-264">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="c0ea1-265">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-265">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="c0ea1-266">**欠落しているスライド タイトルを見つけて修正する:** スライド タイトルは、ピッチにパンチを加え、すべてのユーザーがスライドにアクセスできるようにします。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-266">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="c0ea1-267">アクセシビリティ ​​チェックは、タイトルがない場所を表示します。これにより、タイトルを簡単に追加できます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-267">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="c0ea1-268">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-268">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="c0ea1-269">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-269">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="c0ea1-270">[ブログの投稿](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="c0ea1-270">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="c0ea1-271">**自分の気分を表現するアイコンの追加:** 300 個以上の新しいアイコンが追加されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-271">**More icons to match your mood:** We've added more than 300 new icons.</span></span> <span data-ttu-id="c0ea1-272">[挿入]、[アイコン] の順に検索してください。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-272">Find them at Insert > Icons.</span></span> [<span data-ttu-id="c0ea1-273">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-273">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="c0ea1-274">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-274">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span><br /><span data-ttu-id="c0ea1-275">[ブログの投稿](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="c0ea1-275">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="c0ea1-276">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルのリストからドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-276">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="c0ea1-277">**PowerPoint におけるリアルタイム コラボレーションが高速に:** PowerPoint でリアルタイム コラボレーションを高速で行えます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-277">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="c0ea1-278">**ブラウザーへのバウンスは不要:** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-278">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="c0ea1-279">**新しい文書校正ツール:** 記述する内容についてストレスを感じる必要はありません。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-279">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="c0ea1-280">PowerPoint で、文法や書き方の推奨事項が提示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-280">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="c0ea1-281">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-281">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="c0ea1-282">**ライブ キャプションと字幕:** 発表者の言葉が、キャプションまたは選択した言語での字幕として自動的に画面に表示されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-282">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="c0ea1-283">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-283">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="c0ea1-284">**プレゼンテーションの最適化:** アクセシビリティ チェックを使用すると、スクリーン リーダーを考慮に入れて、スライド上のオブジェクトを配置することができます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-284">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span><br /><span data-ttu-id="c0ea1-285">[ブログの投稿](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="c0ea1-285">See details in [blog post](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span></span>

- <span data-ttu-id="c0ea1-286">**再利用しませんか?:** 作成した、または他のユーザーと共有しているスライドを再利用して時間を節約します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-286">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="c0ea1-287">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-287">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

### <a name="visio"></a><span data-ttu-id="c0ea1-288">Visio</span><span class="sxs-lookup"><span data-stu-id="c0ea1-288">Visio</span></span>

- <span data-ttu-id="c0ea1-289">**Excel で洗練された Visio 図を作成する:** ワークシートにデータを入力して、フロー チャートまたは組織図を作成します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-289">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="c0ea1-290">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-290">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="c0ea1-291">**犯行現場に戻る:** [犯罪現場] 調査テンプレートで新しい [証拠]、[室内]、および [屋外] のステンシルを使用して、犯罪現場を詳細に再現します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-291">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

### <a name="word"></a><span data-ttu-id="c0ea1-292">Word</span><span class="sxs-lookup"><span data-stu-id="c0ea1-292">Word</span></span>

- <span data-ttu-id="c0ea1-293">**より安全なビデオ エクスペリエンス:** セキュリティの強化は、より安全なオンライン ビデオ エクスペリエンスを意味します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-293">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="c0ea1-294">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-294">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="c0ea1-295">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-295">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="c0ea1-296">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-296">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="c0ea1-297">[ブログの投稿](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="c0ea1-297">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="c0ea1-298">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルのリストからドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-298">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="c0ea1-299">**自分の気分を表現するアイコンの追加:** 300 個以上の新しいアイコンが追加されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-299">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="c0ea1-300">[挿入]、[アイコン] の順に検索してください。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-300">Find them at Insert > Icons.</span></span> [<span data-ttu-id="c0ea1-301">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-301">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)<br /><span data-ttu-id="c0ea1-302">[ブログの投稿](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="c0ea1-302">See details in [blog post](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span></span>

- <span data-ttu-id="c0ea1-303">**精度による消去:** 手描き入力の小さな不備を修正するのに、2 つのサイズの消しゴムから選択できます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-303">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="c0ea1-304">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-304">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="c0ea1-305">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-305">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="c0ea1-306">[ブログの投稿](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="c0ea1-306">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="c0ea1-307">**あらましを描く:** ドキュメント内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-307">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="c0ea1-308">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-308">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="c0ea1-309">[ブログの投稿](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="c0ea1-309">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="c0ea1-310">**探しているものを見つける:**[検索] ボックスを使用して、テキスト、コマンド、ヘルプなどを探します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-310">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="c0ea1-311">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-311">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="c0ea1-312">**ブラウザーへのバウンスは不要** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-312">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="c0ea1-313">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-313">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="c0ea1-314">**Editor for Resume が LinkedIn 履歴書アシスタントに参加する:** Editor for Resume では履歴書に特化した文法とスタイルのチェックを選択できます。この機能は、より正確かつ専門的に作成するの役立ちます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-314">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="c0ea1-315">**他のユーザーがすばやく変更を確認する:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-315">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="c0ea1-316">**3D オブジェクトのマージによって引き起こされるドキュメント破損の問題を修正しました。:** 3D オブジェクトのマージによって引き起こされるドキュメント破損の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-316">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="c0ea1-317">**共同編集の改善:** 変更を追跡したドキュメントで共同編集を行う際の Word のパフォーマンスが改善されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-317">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="c0ea1-318">**共同編集の改善:** 共同編集時の信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-318">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="c0ea1-319">**鮮やかな色で共同作業する:** コメントや変更内容のカラー コードが共同作成者によって指定され、共同作成者のうちのだれによって行われたかが簡単にわかります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-319">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="c0ea1-320">**マクロ有効文書を共同作業で編集する:** 文書ファイルを OneDrive for Business に保存し、リアルタイムで共同作成者は編集できます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-320">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c0ea1-321">Office スイート</span><span class="sxs-lookup"><span data-stu-id="c0ea1-321">Office Suite</span></span>

- <span data-ttu-id="c0ea1-322">**手書きのインクを図形やテキスト、または Office 365 の PowerPoint での数式に変換する:** フリーフォームのインクを Office の図形、テキスト、数式に数ストロークで変換します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-322">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="c0ea1-323">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-323">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="c0ea1-326">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="c0ea1-326">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c0ea1-327">Access</span><span class="sxs-lookup"><span data-stu-id="c0ea1-327">Access</span></span>

- <span data-ttu-id="c0ea1-328">この更新プログラムでは、ADODB を使用する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-328">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="c0ea1-329">VB コードのれコーター オブジェクトがエラーを誤って報告することがあります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-329">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="c0ea1-330">Access テンプレートは、データベース内の添付ファイル列のエラーを発生させることがなくなりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-330">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="c0ea1-331">テンプレートのインスタンス化後に、データベースに添付ファイル フィールドを追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-331">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="c0ea1-332">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-332">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="c0ea1-333">この更新プログラムにより、更新クエリが実行されるか、SQL で UPDATE ステートメントが使用されるときに "クエリは破損しています" というエラーを発生させる場合のある Microsoft Access の問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-333">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="c0ea1-334">Excel</span><span class="sxs-lookup"><span data-stu-id="c0ea1-334">Excel</span></span>

- <span data-ttu-id="c0ea1-335">ローカルの OneDrive フォルダーで使用できるファイルの読み込み速度を向上します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-335">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="c0ea1-336">CUBEVALUE 関数が間違った結果を返すことがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-336">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="c0ea1-337">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-337">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="c0ea1-338">Word または PowerPoint に埋め込まれたブックをもう一度開くと、場合によっては Excel がクラッシュする可能性があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-338">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="c0ea1-339">コンテキスト メニューのコメント コマンドが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-339">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="c0ea1-340">ピボット グラフの右クリック メニューを修正して、[詳細の表示] オプションを有効にしました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-340">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="c0ea1-341">ブックが開かれていない状態で最近使用したファイルを検索するときに、クラッシュを発生させる原因となっていた可能性がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-341">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="c0ea1-342">同じブック内でブックマークされたハイパーリンクをクリックすると、ブックが非表示になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-342">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="c0ea1-343">CSV ファイルとして保存する場合、Excel はすべての列を 1 つの列にマージする場合があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-343">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="c0ea1-344">保護されたシートの範囲で Range.ClearContents を使用すると、予想よりも時間がかかる場合があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-344">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="c0ea1-345">[印刷プレビュー] に表示されるときのフォーム コントロール内のテキストの拡大縮小に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-345">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="c0ea1-346">リボンを操作する VBA マクロは、ScreenUpdating が True に設定されていると予期せず実行される場合があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-346">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="c0ea1-347">ピボットテーブルを含むシートをコピーした後、Excel がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-347">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="c0ea1-348">状況によっては、CSV ファイルを開くのに予想より時間がかかっていました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-348">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="c0ea1-349">Excel では、異なる拡大レベルでブックを切り替えるとクラッシュすることがあります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-349">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="c0ea1-350">値の範囲への入力に予想より時間がかかる VBA の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-350">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="c0ea1-351">色でフィルター処理された列からコピーしたデータは、正しく貼り付けられない場合があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-351">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="c0ea1-352">特に非表示のウィンドウで、多数のその他のブックを参照しながらブックを開くと、予想よりも時間がかかります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-352">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="c0ea1-353">ソース ブックが閉じていると、外部リンクが塗りつぶし (下方向に塗りつぶし、全体に塗りつぶしなど) 時に更新されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-353">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is& closed.</span></span>

- <span data-ttu-id="c0ea1-354">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-354">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="c0ea1-355">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-355">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="c0ea1-356">グラフの軸の "Value Crosses At" プロパティが、ファイルを保存してもう一度開くときに予期せず変更されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-356">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="c0ea1-357">SharePoint/OneDrive に保存すると、ユーザー設定のリボンタブの CustomUI XML が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-357">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="c0ea1-358">結合されたセルを持つ列を削除するときのパフォーマンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-358">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="c0ea1-359">[印刷] ダイアログ ボックスのプリンターのリストにプリンター名が繰り返されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-359">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="c0ea1-360">ファイル パスが長すぎる場合にファイルをもう一度開くと、外部リンクが機能しなくなった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-360">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="c0ea1-361">印刷時にフォーム コントロールのチェックボックスが拡大縮小されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-361">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="c0ea1-362">従来の "共有ブック" モードを使用して、ブックの新しいシートに変更を一覧表示しようとすると、クラッシュが発生する場合がありました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-362">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="c0ea1-363">フィルター処理されたリストに列を挿入すると、通常よりも時間がかかっていました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-363">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="c0ea1-364">コピー & ペーストされたグラフのリンクの一部で、ユニバーサル アドレスではなくマップされたドライブ アドレスが使用されていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-364">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="c0ea1-365">アドインが、ユーザーが指定した順番ではなくアルファベット順に読み込まれていたため、「このブックは現在別のユーザーに参照されており、閉じることができません」というエラー メッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-365">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="c0ea1-366">既に開いているブック内の場所へのハイパーリンクをクリックすると、ブックが非表示になることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-366">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="c0ea1-367">特に非表示のウィンドウで、多数のその他のブックを参照しながらブックを開くと、予想よりも時間がかかります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-367">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="c0ea1-368">VBA の Application.Evaluate が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-368">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="c0ea1-369">一部のユーザーが埋め込みオブジェクトとリンク オブジェクト (OLE) で経験する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-369">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="c0ea1-370">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-370">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="c0ea1-371">この更新によって、数式バーに予期したのとは異なるフォントでテキストが表示される原因となっていた問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-371">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="c0ea1-372">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-372">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="c0ea1-373">スクロール後にセルを選択すると間違ったセルが選択されることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-373">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="c0ea1-374">非表示の名前付き範囲にアクセスすると、ユーザーにエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-374">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="c0ea1-375">信頼されていないネットワーク共有から保護されたファイルを編集する際に、Excel にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-375">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="c0ea1-376">一部のローカライズにおいて、[Text to Column] 機能が失敗することがあります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-376">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="c0ea1-377">テンプレートからグラフを作成するときに発生するパフォーマンスの問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-377">Addresses a performance issue when creating charts from templates.</span></span>

- <span data-ttu-id="c0ea1-378">はみ出している列挙が含まれるセルで区切り位置を指定するとクラッシュが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-378">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="c0ea1-379">Range.Value と Range.Value2 (VBA) を使用すると、数式は動的配列として入力されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-379">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

- <span data-ttu-id="c0ea1-380">数式を開始する @ 記号が暗黙的な論理積演算子と見なされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-380">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

- <span data-ttu-id="c0ea1-381">定義された名前を持つ複数の数式を含むワークシートがファイルを保存するときに時間がかかる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-381">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="c0ea1-382">この変更は、ソフトウェア レンダリングを活用することにより、特定の Intel グラフィック ドライバーの問題を回避します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-382">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="c0ea1-383">署名の名前を変更したときにクラッシュする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-383">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="onenote"></a><span data-ttu-id="c0ea1-384">OneNote</span><span class="sxs-lookup"><span data-stu-id="c0ea1-384">OneNote</span></span>

- <span data-ttu-id="c0ea1-385">OneNote 2016 で同期頻度を一時的に調整することで、同期およびサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-385">Improve sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="c0ea1-386">ユーザーが OneNote 2016 のページに移動するまで、オンライン ノートブックの埋め込みファイルおよび画像のダウンロードを一時的に遅らせることで、同期およびサービスの安定性を改善します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-386">Improve sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="c0ea1-387">OneNote 2016 のごみ箱を一時的に無効にすることにより、同期およびサービスの安定性を改善します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-387">Improve sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="c0ea1-388">ユーザーが、通常はごみ箱に送られるデータを削除しようとすると、データを保持するか、完全に削除するかを確認するメッセージが表示されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-388">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="c0ea1-389">OneNote 2016 のバージョン履歴ページの数と同期頻度を一時的に減らすことで、同期およびサービスの安定性を改善します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-389">Improve sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="c0ea1-390">同期およびサービスの安定性を改善するために、OneNote ユーザー エクスペリエンスで実行されている一時的な手段についての詳細情報をユーザーが学べるようにする通知を表示します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-390">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="c0ea1-391">OneNote 2016 に 50 MB へ埋め込まれた新しい添付ファイルの最大許容サイズが一時的に減少することにより、同期とサービスの安定性を改善します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-391">Improve sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="c0ea1-392">この制限を超えるファイルの場合、ユーザーは OneDrive にファイルをアップロードして、OneNote にリンクを挿入することができます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-392">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="c0ea1-393">OneNote 2016 でアプリ内動画のレコーディングを一時的に無効にすることで、同期およびサービスの安定性を改善します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-393">Improve sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="c0ea1-394">ローカルのノートブックはこの影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-394">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="c0ea1-395">同期およびサービスの安定性を改善するために、OneNote ユーザー エクスペリエンスで実行されている一時的な手段についての詳細情報をユーザーが学べるようにする通知をローカライズします。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-395">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="c0ea1-396">Outlook</span><span class="sxs-lookup"><span data-stu-id="c0ea1-396">Outlook</span></span>

- <span data-ttu-id="c0ea1-397">解像度の異なる複数のモニターを使用している場合に、IME(Input Method Editor)ウィンドウで入力されたテキストが重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-397">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="c0ea1-398">Outlook でユーザーが不定期に遭遇するクラッシュの原因になる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-398">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="c0ea1-399">これにより、Python による添付ファイルもブロックされるよう、Outlook の添付ファイルのブロック ロジックが更新されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-399">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="c0ea1-400">Web アドインがデジタル著作権管理 (DRM) メッセージにアクセスする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-400">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="c0ea1-401">タイムゾーンの定義を変更するときに、定期的な予定や会議が誤った時間に表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-401">Addresses an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="c0ea1-402">2019 年に ブラジル タイム ゾーンを使用している場合、2020 年の定期的な会議や予定が間違った時間帯に表示されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-402">When using the Brazilia time zone in the year 2019, recurring meetings and appointments are displayed in the wrong timeslot for the year 2020.</span></span> <span data-ttu-id="c0ea1-403">この変更は、ブラジル タイム ゾーンに設定されているクライアントまたは同タイム ゾーンで設定された会議や予定に影響を与えます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-403">This change is relevant for clients set in the Brazilia time zone or for meetings and appointments set in that time zone.</span></span><br><br><span data-ttu-id="c0ea1-404">この変更により、Outlook では、使用する特定のタイムゾーン設定を上書きできます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-404">This change allows Outlook to override certain time zone settings used by Outlook.</span></span> <span data-ttu-id="c0ea1-405">タイムゾーンの上書きを起動するには、現在のユーザーのレジストリキーを設定する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-405">In order to invoke a time zone override you must set a registry key for the current user.</span></span> <span data-ttu-id="c0ea1-406">レジストリキーの名前は、タイムゾーンの内部名と一致する必要があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-406">The registry key name must match the internal name of the time zone.</span></span> <span data-ttu-id="c0ea1-407">この値は、有効な年の代わりに、使用されるタイムゾーン ルールの年を示します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-407">The value indicates the time zone rule's year to be used in place of the effective year.</span></span> <span data-ttu-id="c0ea1-408">たとえば、次のレジストリキーの上書き値は、2020 年のブラジル タイムゾーン ルールを有効なルールとして使用します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-408">For example, the following registry key override value will use the Brazilia time zone rule for the year 2020 as the effective rule.</span></span> <span data-ttu-id="c0ea1-409">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-409">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span></span> <span data-ttu-id="c0ea1-410">南アメリカ標準時 "=dword:000007e4。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-410">South America Standard Time"=dword:000007e4.</span></span>

- <span data-ttu-id="c0ea1-411">会議の場所フィールドが予期せず変更される原因となる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-411">Addresses an issue that caused users to see the location field in meetings change unexpectedly.</span></span>

- <span data-ttu-id="c0ea1-412">会議の [場所] フィールドが予期せず更新される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-412">Addresses an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="c0ea1-413">会議をクリアした後、会議の場所が予期せずに会議に追加される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-413">Addresses an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="c0ea1-414">会議の [場所] フィールドにあるコンマがセミコロンになる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-414">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="c0ea1-415">ネイティブの Teams クライアントを介して Teams 会議に直接参加できます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-415">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="c0ea1-416">Exchange 2010 サーバー上にメールボックスを持つユーザーが、予定表の項目に添付ファイルを追加するときに生じる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-416">Addresses an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="c0ea1-417">ユーザーがデジタル署名されたメッセージに返信するときに生じる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-417">Addresses an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="c0ea1-418">ユーザーが定期的な予定表の一部のインスタンスを開けない原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-418">Addresses an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="c0ea1-419">一部のシナリオで、グループ ヘッダーが予期せず拡張される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-419">Addresses an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="c0ea1-420">フォルダー ウィンドウの幅が予期せず変更される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-420">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="c0ea1-421">M365 Business Plus プランのサービスを利用していたユーザーがデータ損失防止の保護ポリシー ヒントを有効にできない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-421">Addresses an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="c0ea1-422">キーボード ショートカットを使用してメールボックス フォルダーを操作すると、ユーザーに顕著な遅延が発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-422">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="c0ea1-423">複数のウィンドウで同じアイテムを表示するとクラッシュする場合がある問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-423">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="c0ea1-424">ユーザーが Outlook ルールを更新すると、"このコンピューターのルールは、Microsoft Exchange のルールと異なります" と表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-424">Addresses an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="c0ea1-425">非常に長い Outlook セッションでメモリ リークを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-425">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="c0ea1-426">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-426">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="c0ea1-427">ユーザーが [ルール] ダイアログを開くと、"このコンピューターのルールは、Microsoft Exchange のルールと異なります" というメッセージが表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-427">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="c0ea1-428">フラグ付きアイテムの強調表示を無効にするオプションが一部のシナリオで無視される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-428">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="c0ea1-429">[アクセシビリティ チェック] ペインを閉じた後に "S" キーを押すと、メールが予期せず送信されたようにユーザーに表示される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-429">Addresses an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="c0ea1-430">署名の名前を変更したときにクラッシュする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-430">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="c0ea1-431">ユーザーがアカウントのセットアップをキャンセルするときにクラッシュする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-431">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="c0ea1-432">同期のスライダーが小さい設定に設定されている場合でも、Outlook で予期せずすべてのメールが同期される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-432">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="c0ea1-433">黒のテーマを持つユーザーが [差出人] ドロップダウンを表示すると、白色の背景に白いテキストが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-433">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="c0ea1-434">ユーザーがプロフィールの作成中にクラッシュを発生させる原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-434">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="c0ea1-435">アカウント作成コンテキストからサポートに連絡しようとすると、ユーザーに [OK] ボタンのある空のメッセージ ボックスが表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-435">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="c0ea1-436">アカウント作成コンテキストからサポートに連絡しようとすると、ユーザーに [OK] ボタンのある空のメッセージ ボックスが表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-436">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="c0ea1-437">サードパーティ製アプリケーションがメールを送信できない原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-437">Addresses an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="c0ea1-438">メール メッセージからカテゴリが消えることがあるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-438">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="c0ea1-439">サーバー オペレーティング システムの Outlook ユーザーに "ウイルス対策ステータス: 無効" のエラーを表示する原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-439">Addresses an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="c0ea1-440">このバージョンの Windows はウイルス検出をサポートしていますが、ウイルス対策を適切に構成してもウイルス対策ソフトウェアが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-440">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

- <span data-ttu-id="c0ea1-441">共有メールボックスに対して、異なるコンピューター上の別のフォルダー階層が代理人に表示されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-441">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="c0ea1-442">管理者のカレンダー上で既存のカレンダーの予定を編集するときに代理人がエラーを受け取る問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-442">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="c0ea1-443">間違ったブラウザー エミュレーション設定でユーザーが Gmail の認証プロンプトを完了できなくなるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-443">Addresses an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="c0ea1-444">[共有フォルダーのダウンロード] がチェックされていない場合、共有の予定表の会議の [返信オプション] に [転送を許可する] オプションが表示されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-444">Addresses an issue that caused the " Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="c0ea1-445">ユーザーが Windows Update の後に .msg および .oft ファイルを開こうとするとクラッシュが起きるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-445">Addresses an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="c0ea1-446">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-446">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="c0ea1-447">特定の検索結果を選択すると、ユーザーがクラッシュする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-447">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="c0ea1-448">[添付ファイル ​​ツール] に [クラウドに保存] ボタンが表示されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-448">Addresses an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="c0ea1-449">この変更により、メッセージ ヘッダーに複数行の件名を表示できる機能が復元されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-449">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="c0ea1-450">2 つのアドインが同じリボン グループにボタンを追加するときにユーザーにクラッシュが発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-450">Addresses an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="c0ea1-451">テナントの既定のアクセス許可が "全員" として構成されている場合に、適切なテナントの既定のアクセス許可を使用して、リンクがメールに追加されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-451">Addresses an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as "anyone".</span></span>

- <span data-ttu-id="c0ea1-452">ユーザーが個人用配布リストにメールを送信できなくなった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-452">Addresses an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="c0ea1-453">大きな HTML メッセージを転送するとき、ユーザーにメッセージ本文の全体が表示されないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-453">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="c0ea1-454">SMIME アルゴリズムの選択に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-454">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="c0ea1-455">WebDAV の場所にファイルを保存できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-455">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="c0ea1-456">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカル コンピューターに保存できない原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-456">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="c0ea1-457">件名を編集した後、NDR メッセージの本文が Unicode から ASCII に変更される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-457">Addresses an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="c0ea1-458">ユーザーが Outlook プロセスでメモリ リークを観測する原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-458">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="c0ea1-459">状況によっては、表示された SMTP アドレスと一致しないアドレスに送信されたメールがユーザーに表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-459">Addresses an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="c0ea1-460">検索ボックスが高 DPI モードで不適切に表示される原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-460">Addresses an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="c0ea1-461">ユーザーがクラウド設定を取得する際に Outlook がフリーズする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-461">Addresses an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="c0ea1-462">検索に関するフィードバックのエクスペリエンスで終了する原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-462">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="c0ea1-463">Outlook でユーザーが不定期に遭遇するクラッシュの原因になる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-463">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="c0ea1-464">署名の名前を変更したときにクラッシュする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-464">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="c0ea1-465">ユーザーがプロフィールの作成中にクラッシュを発生させる原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-465">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="c0ea1-466">Outlook でユーザーが不定期に遭遇するクラッシュの原因になる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-466">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c0ea1-467">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c0ea1-467">PowerPoint</span></span>

- <span data-ttu-id="c0ea1-468">従来の PPT コメントでコンテキスト メニューを使用するときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-468">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

- <span data-ttu-id="c0ea1-469">コピーと貼り付けのシナリオを改善しました。PowerPoint スライドでの図形のコピーと、ループ内の他のスライドへの貼り付けが例外で失敗する場合があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-469">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="c0ea1-470">問題の修正により、改善済みのコメントが入ったファイルのコピーを開くユーザーに正しいメッセージを送れるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-470">Fixes an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="project"></a><span data-ttu-id="c0ea1-471">Project</span><span class="sxs-lookup"><span data-stu-id="c0ea1-471">Project</span></span>

- <span data-ttu-id="c0ea1-472">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-472">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="c0ea1-473">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-473">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="c0ea1-474">[無効化] ボタンを介してタスクが非アクティブ化/アクティブ化された場合に、ProjectBeforeTaskChange イベントが検出しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-474">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="c0ea1-475">以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-475">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="c0ea1-476">読み取り専用のプロジェクトを開いたときに複数のメッセージを取得する可能性があるという問題を特定しました</span><span class="sxs-lookup"><span data-stu-id="c0ea1-476">Identified an issue where users could get several messages when opening a read-only project</span></span>

- <span data-ttu-id="c0ea1-477">作業時間固定タイプの達成率 100% のタスクで、達成率が誤って 100% 未満に計算される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-477">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="c0ea1-478">Word</span><span class="sxs-lookup"><span data-stu-id="c0ea1-478">Word</span></span>

- <span data-ttu-id="c0ea1-479">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-479">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="c0ea1-480">クイック印刷を使用して印刷した後に編集しようとしたときに、ドキュメント内の単語の配置が乱れてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-480">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="c0ea1-481">表内のテキストに合わせる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-481">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="c0ea1-482">水平線の挿入が短くなく、中央に配置されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-482">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>

- <span data-ttu-id="c0ea1-483">文書パーツ オーガナイザーに "スタイル、文書パーツを変更しました" という無効なアラートが表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-483">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

- <span data-ttu-id="c0ea1-484">ポリシー FileBlick\Word2007Files を有効にしたときの共同編集に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-484">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="c0ea1-485">名前が変更されたルックアップ フィールドを追加するときに Word QuickPart が機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-485">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

- <span data-ttu-id="c0ea1-486">2 つのドキュメントを 1 つのドキュメントに結合するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-486">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="c0ea1-487">編集用に保護されたドキュメントの比較機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-487">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="c0ea1-488">この更新プログラムでは、Microsoft Word で、ラベル ポリシーにヘッダーやフッターまたは透かしが適用されている場合にラベルを変更または削除すると、255 文字を超える文字の挿入されたテキストが識別および削除できなかった問題が修正されています。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-488">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c0ea1-489">Office スイート</span><span class="sxs-lookup"><span data-stu-id="c0ea1-489">Office Suite</span></span>

- <span data-ttu-id="c0ea1-490">大規模な PowerPoint ファイルの共同編集中に、ユーザーがネットワークと CPU の使用率が過剰になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-490">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="c0ea1-491">これは、ファイルがクライアントにキャッシュされるときに Project アプリがネットワークをブロックしないようにするための修正プログラムです。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-491">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>


- <span data-ttu-id="c0ea1-492">この問題を解決するため、Backstage のチャネル名を 2020 年 1 月のフォークにある新しいチャネル名に更新しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-492">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="c0ea1-493">この問題は修正されましたが、今後、デバイスがポリシー管理されている場合、DMS の対象ユーザー API は呼び出されません。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-493">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="c0ea1-494">単一のトランザクションでアプリを追加および削除したときに、削除が不完全になるという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-494">We have resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="c0ea1-495">ODT と GPO の更新期限設定で、相対期限の設定後、初回のみしか機能しないバスが修正されました。修正により、2 回目以降の更新プログラムで相対期限を使用きるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-495">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="c0ea1-496">Office の更新プログラムが、意図したソース (ローカル共有、ネットワーク共有、構成マネージャーで提供される場所など) からではなく、予期せずに Office CDN からファイルをダウンロードする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-496">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="c0ea1-497">ODT と GPO の更新期限設定で、相対期限の設定後、初回のみしか機能しないバスが修正されました。修正により、2 回目以降の更新プログラムで相対期限を使用きるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-497">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="c0ea1-498">以前の AppV51 の回帰を修正するために、新しい AppV51 drop をバックポートしました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-498">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="c0ea1-499">ログ記録して続行するのではなく、内部操作により失敗時に例外がスローされていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-499">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="c0ea1-500">影響を受けるユーザーは、更新プログラムの受信をブロックされなくなります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-500">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="c0ea1-501">チームでは、半期エンタープライズ プレビューで Office CDN ドメインのテレメトリを報告するためのクライアント サポートを追加しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-501">Our team has added client support for reporting telemetry on the Office CDN domains in Semi-Annual Enterprise Preview.</span></span>

- <span data-ttu-id="c0ea1-502">この変更では、Intel Integrated GPU を使用するグラフィック アダプターに関して報告された問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-502">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="c0ea1-503">この変更により、リボンのスケッチされたアウトラインは正常に機能するようになります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-503">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="c0ea1-504">特定のプロキシの構成でオンプレミスの場所からファイルを開く際の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-504">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="c0ea1-505">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-505">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="c0ea1-506">問題を解決し、Office のハンドオフ セッション中のクラッシュを解消し、ユーザー エクスペリエンスの信頼性を向上させました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-506">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>

- <span data-ttu-id="c0ea1-507">このバグは、Enhanced Configuration Service (ECS) url エンドポイントを更新します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-507">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="c0ea1-508">この新しいエンドポイントを呼び出すと、ECS からのフェッチ成功率が高くなります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-508">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

- <span data-ttu-id="c0ea1-509">この更新プログラムでは、メッセージの表示または作成時に Microsoft Outlook で現在の機密ラベルが表示されないという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-509">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="c0ea1-510">同じ SharePoint ライブラリから Word/Excel/PowerPoint で複数のドキュメントが開かれている場合、最初に開いたドキュメントのみがポリシー コンプライアンスでスキャンされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-510">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

- <span data-ttu-id="c0ea1-511">Office ユーザーのセキュリティを保護するために、Microsoft Office の更新プログラムは SHA-2 アルゴリズムのみを使用して署名されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-511">To protect Office customers’ security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="c0ea1-512">HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth のレジストリ キーが 0 に設定されている場合、アドインがアクティブになり、Windows で Office ホストがクラッシュしました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-512">The office host was crashing in windows, when an add-in is being activated while the registry key  HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="c0ea1-513">この変更により、この問題は修正されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-513">This change would fix this issue.</span></span>

- <span data-ttu-id="c0ea1-514">レジストリ TabProcGrowth の値が REG_SZ 型でアドインがアクティブ化されている場合に、Windows の Office ホストがクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-514">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="c0ea1-515">この更新プログラムでは、Microsoft Office で PATH 環境変数で指定した場所を検索することによって参照される可能性がある Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA ランタイムエラーが発生するという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-515">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="c0ea1-516">インストールされている言語によって Access と Publisher が正常に起動しなかった問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-516">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)





[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-july-14"></a><span data-ttu-id="c0ea1-519">バージョン 1908: 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-519">Version 1908: July 14</span></span>
<span data-ttu-id="c0ea1-520">*バージョン 1908 (ビルド 11929.20904)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-520">*Version 1908 (Build 11929.20904)*</span></span>

<span data-ttu-id="c0ea1-521">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-521">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="c0ea1-523">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="c0ea1-523">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c0ea1-524">Access</span><span class="sxs-lookup"><span data-stu-id="c0ea1-524">Access</span></span>

- <span data-ttu-id="c0ea1-525">この更新プログラムにより、Sum などの集計が結果を整数値に切り捨てる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-525">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="c0ea1-526">この更新プログラムにより、リモート テーブル (SQL Server テーブルなど) への参照を含むユニオン クエリにより Access が閉じて再起動する問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-526">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="c0ea1-527">この更新プログラムにより、更新クエリが実行されるか、SQL で UPDATE ステートメントが使用されるときに "クエリは破損しています" というエラーを発生させる場合のある Microsoft Access の問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-527">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="c0ea1-528">Excel</span><span class="sxs-lookup"><span data-stu-id="c0ea1-528">Excel</span></span>

- <span data-ttu-id="c0ea1-529">ドキュメント タイトルのオランダ語の KeyTip が Alt-G に変更されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-529">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="c0ea1-530">図形やフォームコントロールに割り当てられているマクロが間違ったエラーメッセージとして表示される、または間違った対象範囲で動作する問題が Excel で修正されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-530">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="c0ea1-531">最初のアイテムを検索した後に、ダイアログでのフォーカスの位置が変更されてしまう検索と置換についての問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-531">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="c0ea1-532">これにより、ピボットテーブルの並べ替え方法を変更し、他のユーザーとの共同編集セッション中にそれを更新するとクラッシュが発生する可能性がある問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-532">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="c0ea1-533">OLAP ピボットテーブルのフィルターが、キューブから削除された値に設定された場合の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-533">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="c0ea1-534">この更新プログラムは、VBA を使用してグラフのヘッダー/フッターに画像を追加するたびにエラーが発生する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-534">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="c0ea1-535">シリーズ コレクションを変更するときに、散布図が適切にレンダリングされない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="c0ea1-535">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span>

- <span data-ttu-id="c0ea1-536">グラフ テンプレートを使用してグラフを挿入する場合に、プレビューで正しい色が使用されるよう修正します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-536">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="c0ea1-537">セルが挿入または削除されたときに、ウォーターフォール図とじょうごグラフがテーブルと同期しなくなる原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-537">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="c0ea1-538">Excel で、ユーザーが変更を取得するためにブックを再び開くよう要求されるマージ競合の問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-538">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="c0ea1-539">最小化されたウィンドウをアクティブにするマクロ実行時エラーの原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-539">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="c0ea1-540">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-540">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="c0ea1-541">他のユーザーと共同編集しているときに、テーブルの横にある切り取りと貼り付けの操作が失敗する原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-541">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="c0ea1-542">実行中のマクロでカスタム プロパティを変更するときに、共同編集の中断を引き起こす原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-542">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="c0ea1-543">アドインによって開かれた WPF (Windows Presentation Foundation) フォームのコンボ ボックスからアイテムを選ぶことができない問題が発生しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-543">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="c0ea1-544">ブックが開かれていない状態で最近使用したファイルを検索するときに、クラッシュを発生させる原因となっていた可能性がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-544">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="c0ea1-545">グループ ボックス コントロールの境界線が印刷プレビューまたは印刷時に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-545">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="c0ea1-546">ブックで外部リンクがある場合に、一部のユーザーでポップアップ ウィンドウが複数表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-546">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="c0ea1-547">VBA マクロを使用して範囲の内容をクリアするときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-547">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="c0ea1-548">値の範囲への入力に予想より時間がかかる VBA の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-548">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="c0ea1-549">グラフの軸の "Value Crosses At" プロパティが、ファイルを保存してもう一度開くときに予期せず変更されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-549">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="c0ea1-550">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-550">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="c0ea1-551">結合されたセルを含む列を削除するときにパフォーマンスが低下する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-551">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="c0ea1-552">[印刷プレビュー] に表示されるときのフォーム コントロール内のテキストの拡大縮小に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-552">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="c0ea1-553">色でフィルタリングされたデータを異なる幅の列にコピーすると、値が貼り付けられません。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-553">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

- <span data-ttu-id="c0ea1-554">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-554">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="c0ea1-555">印刷時にフォーム コントロールのチェックボックスが拡大縮小されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-555">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="c0ea1-556">同じブック内でブックマークされたハイパーリンクをクリックすると、ブックが非表示になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-556">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="c0ea1-557">従来の "共有ブック" モードを使用して、ブックの新しいシートに変更をリスト表示しようとすると、クラッシュが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-557">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="c0ea1-558">一部のロケールにおいて、[Text to Column] 機能が失敗することがあります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-558">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="c0ea1-559">非表示の名前付き範囲にアクセスすると、ユーザーにエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-559">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="c0ea1-560">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-560">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="c0ea1-561">グラフを含むブックを保存すると、グラフ ヘッダーの画像のファイル サイズが大きくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-561">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>

- <span data-ttu-id="c0ea1-562">非同期のユーザー定義関数が同期して実行されるパフォーマンスの問題が発生しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-562">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="c0ea1-563">結合されたセルで列を削除するパフォーマンスが大幅に改善されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-563">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="c0ea1-564">スクロール後にセルを選択すると間違ったセルが選択されることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-564">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="c0ea1-565">Lookup 関数がエラーを返す問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-565">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="c0ea1-566">選択範囲を相互参照ブックと同期させ続けることにより、相互参照ブックの DBCS 文字が破損する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-566">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="c0ea1-567">自動調整を使用して行の高さを調整するときにチェック ボックスのコントロールが縮小される可能性があるという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-567">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>

- <span data-ttu-id="c0ea1-568">ファイルに広範な条件付き書式が設定されている場合に、[フォントの色] ボタンをクリックするとパフォーマンスが低下する問題。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-568">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="c0ea1-569">印刷プレビューの印刷範囲が正しくないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-569">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="c0ea1-570">信頼されていないネットワーク共有から保護されたファイルを編集する際に、Excel にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-570">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="c0ea1-571">色によるフィルタリングのパフォーマンスが大幅に改善されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-571">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="c0ea1-572">Office の以前のバージョンで作成されたブックを Office の最新のバージョンで開いたときに、Excel の終了を引き起こす可能性がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-572">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="c0ea1-573">アドイン マネジャーで参照するときに、16 個を超えるアドインを表示できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-573">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="c0ea1-574">一部の保護されたシートにハイパーリンクが貼り付けられない問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-574">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="c0ea1-575">この変更は、ソフトウェア レンダリングを活用することにより、特定の Intel グラフィック ドライバーの問題を回避します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-575">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="c0ea1-576">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-576">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="c0ea1-577">この更新プログラムにより、"アップロードできませんでした" というメッセージが表示され、Office ドキュメントが OneDrive for Business にアップロードされないことがあるエラーが修正されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-577">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="c0ea1-578">Win32 クライアントの [アイデア] ボタンをクリックしてアドインを読み込むときにエラーが発生するという Excel のアイデア機能の問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-578">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span> 

### <a name="onenote"></a><span data-ttu-id="c0ea1-579">OneNote</span><span class="sxs-lookup"><span data-stu-id="c0ea1-579">OneNote</span></span>

- <span data-ttu-id="c0ea1-580">同期およびサービスの安定性を改善するために、OneNote ユーザー エクスペリエンスで実行されている一時的な手段についての詳細情報をユーザーが学べるようにする通知をローカライズします。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-580">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="c0ea1-581">Outlook</span><span class="sxs-lookup"><span data-stu-id="c0ea1-581">Outlook</span></span>

- <span data-ttu-id="c0ea1-582">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-582">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="c0ea1-583">メールボックスを基本認証から最新認証にアップグレードしたユーザーが、Outlook プロファイルに関連付けられた正しくないアカウントで終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-583">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="c0ea1-584">Web アドインがデジタル著作権管理 (DRM) メッセージにアクセスすべきでないときにアクセスする原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-584">Addresses an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="c0ea1-585">一部のセーフリンクに対して簡易的なホバーの URL が正しく表示されなくなる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-585">Addresses an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="c0ea1-586">これにより、Python による添付ファイルもブロックされるよう、Outlook の添付ファイルのブロック ロジックが更新されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-586">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="c0ea1-587">設定に関係なく、POP3 ユーザーの一部がプレーンテキストで書式設定されたすべてのメールを表示する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-587">Addresses an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="c0ea1-588">この修正プログラムでは、HTML 形式のメッセージの表示が復元されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-588">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="c0ea1-589">プライマリ予定表からグループ予定表にアイテムをコピーするときに、ユーザーにアクセス許可のエラーを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-589">Addresses an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="c0ea1-590">ユーザーがスクリーン リーダーから場所の候補にアクセスできない原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-590">Addresses an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="c0ea1-591">キーボード ショートカットを使用してメールボックス フォルダーを操作すると、ユーザーに顕著な遅延が発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-591">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="c0ea1-592">非常に長い Outlook セッションでメモリ リークを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-592">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="c0ea1-593">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-593">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="c0ea1-594">ユーザーが [ルール] ダイアログを開くと、"このコンピューターのルールは、Microsoft Exchange のルールと異なります" というメッセージが表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-594">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="c0ea1-595">特定のセーフリンクを操作するときに、Outlook でクラッシュを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-595">Addresses an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="c0ea1-596">代理人が特定の会議出席依頼に既に返信したかどうかに関係なく、管理者が不明瞭になる問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-596">Addresses an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="c0ea1-597">一部の AutoDiscover の応答を処理するときに、クラッシュを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-597">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="c0ea1-598">アカウント作成コンテキストからサポートに連絡しようとすると、ユーザーに [OK] ボタンのある空のメッセージ ボックスが表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-598">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="c0ea1-599">この変更により、UPN 経由で自動検出の認証プロンプトに提供されるアカウントのメールを選択するため、ポリシーを管理者が有効にできるようになります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-599">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="c0ea1-600">既定では、使用可能な場合に、自動検出ではアカウント UPN の方が選択されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-600">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="c0ea1-601">最新のグループに対し、検索の失敗がユーザーに表示される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-601">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="c0ea1-602">Outlook ユーザーが特定のシナリオで "パスワードを要求している" 状態で停止する原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-602">Addresses an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="c0ea1-603">競合メッセージの処理中にユーザーに同期エラーが発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-603">Addresses an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="c0ea1-604">最新の Windows 更新プログラム適用後に、ユーザーが msg および .oft ファイルを開こうとするとクラッシュが起きる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-604">Addresses an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="c0ea1-605">Outlook の起動時にユーザーが [プロファイルの読み込み中] 画面でハングアップする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-605">Addresses an issue that caused users to experience a hang at the "Loading Profile" screen when Outlook is starting up.</span></span>

- <span data-ttu-id="c0ea1-606">特定の検索結果を選択すると、ユーザーがクラッシュする問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-606">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="c0ea1-607">[添付ファイル ​​ツール] に [クラウドに保存] ボタンが表示されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-607">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="c0ea1-608">既定では、アイテム保持ポリシーのラベルには、保持期間がかっこ内に表示されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-608">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="c0ea1-609">これにより、管理者はポリシー名のみを表示するように指定するレジストリ キーを取得することができます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-609">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="c0ea1-610">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = アイテム保持ポリシー テキストの PolicyName のみが表示されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-610">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

- <span data-ttu-id="c0ea1-611">Outlook のシャットダウン時にクラッシュが発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-611">Addresses an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="c0ea1-612">一部のシナリオで顧客に空室リストが表示される原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-612">Addresses an issue that caused customers to see an empty room list in some scenarios.</span></span>

- <span data-ttu-id="c0ea1-613">ビューを変更すると、断続的なクラッシュが発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-613">Addresses an issue that caused users to see intermittent crashes when changing views.</span></span>

- <span data-ttu-id="c0ea1-614">ユーザーが OST と同期している共有予定表フォルダーに問題があり、これらのフォルダーを操作しようとするとアクセス許可エラーが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-614">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>

- <span data-ttu-id="c0ea1-615">Citrix 環境で 30 件を超える予定表を表示したときにクラッシュする原因になった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-615">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="c0ea1-616">以前のバージョンで文書化された個々の [KB については、こちらを参照してください](https://support.microsoft.com/ja-JP/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-616">Here's the individual [KB where this was documented for previous versions](https://support.microsoft.com/ja-JP/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span></span>

- <span data-ttu-id="c0ea1-617">SMIME アルゴリズムの選択に関する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-617">Corrects an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="c0ea1-618">代替送信者の使用中にポリシーのヒントが表示されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-618">Addresses an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="c0ea1-619">会議室の空き時間外に行われた会議のためにユーザーにその会議室が提案される原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-619">Addresses an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="c0ea1-620">英語以外の言語を使用するユーザーの、メールの件名が非常に小さくなるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-620">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="c0ea1-621">"不在着信した会話" メッセージのルールを作成しようとするときに、クラッシュを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-621">Addresses an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="c0ea1-622">一部のユーザーに、セカンダリ Exchange アカウントを追加するときに作成された重複した特別なフォルダーが表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-622">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="c0ea1-623">大きな HTML メッセージを転送するとき、ユーザーにメッセージ本文の全体が表示されないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-623">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="c0ea1-624">ユーザーが Outlook プロセスでメモリ リークを観測する原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-624">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="c0ea1-625">プレゼンス情報を更新するときに、断続的なクラッシュを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-625">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="c0ea1-626">現在のフォルダー検索で断続的な失敗を引き起こす問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-626">Addresses an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="c0ea1-627">一部のユーザーが Outlook のクラウド設定を取得しようとするときに、認証エラーが発生する原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-627">Addresses an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="c0ea1-628">検索に関するフィードバックのエクスペリエンスで終了する原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-628">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="c0ea1-629">一部の AutoDiscover の応答を処理するときに、クラッシュを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-629">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="c0ea1-630">プレゼンス情報を更新するときに、断続的なクラッシュを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-630">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c0ea1-631">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c0ea1-631">PowerPoint</span></span>

- <span data-ttu-id="c0ea1-632">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-632">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="c0ea1-633">この変更により、PowerPoint ビデオ コントロールのアクセス可能な名前が復元されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-633">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="c0ea1-634">一部のアニメーションが開始されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="c0ea1-634">We fixed an issue which could prevent some animations from starting</span></span>

- <span data-ttu-id="c0ea1-635">スライドを 1 つのプレゼンテーションから別のプレゼンテーションにコピーすると、重複したマスターが作成される可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-635">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span><br>

- <span data-ttu-id="c0ea1-636">コピーと貼り付けのシナリオを改善しました。PowerPoint スライドでの図形のコピーと、ループ内の他のスライドへの貼り付けが例外で失敗する場合があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-636">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="c0ea1-637">蛍光ペンの問題を修正しました。暗い蛍光ペン色の白いテキストはグレースケールで黒として印刷されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-637">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

- <span data-ttu-id="c0ea1-638">最新のコメントを含むファイルを、サポートされていないバージョンで開くと黄色の警告が表示されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-638">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

- <span data-ttu-id="c0ea1-639">共同作業ユーザー間のパフォーマンスが低下する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-639">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="c0ea1-640">信頼性の修正: サード パーティのアドインが PowerPoint のクラッシュを発生させる可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-640">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="c0ea1-641">増分で開くファイルに、複数のメディア ストリームが埋め込まれたスライドが含まれている場合に発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-641">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="c0ea1-642">Shape.Paste メソッドを使用する際に発生する問題を解決しました。Shape.Paste メソッドを使用して図形をコピーして貼り付けるときに、貼り付けられた図形の選択内容が変更するという問題です。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-642">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="c0ea1-643">PowerPoint の初回起動時に、信頼されていないアドインに対してセキュリティ警告メッセージ バーが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-643">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

- <span data-ttu-id="c0ea1-644">一部のアドインがグラフの図形に対して予期しないエラーをスローさせる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-644">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="c0ea1-645">PowerPoint ユーザーがオンライン プレゼンテーションを行おうとするときに、エラーが発生しないようにします。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-645">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

### <a name="project"></a><span data-ttu-id="c0ea1-646">Project</span><span class="sxs-lookup"><span data-stu-id="c0ea1-646">Project</span></span>

- <span data-ttu-id="c0ea1-647">Windows 7 のユーザーが Project Web App および SharePoint サイトからプロジェクトを開くことができるように問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-647">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="c0ea1-648">読み取り専用のプロジェクトを開いたときに複数のメッセージを取得する可能性があるという問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-648">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="c0ea1-649">[すべて平準化] コマンドがリソースの割り当て超過を適切に解決しません。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-649">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="c0ea1-650">タスクの作業がゼロの割り当てがある場合、タスクに完了のマークを付けることができず、常に 99％ で表示される問題。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-650">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

- <span data-ttu-id="c0ea1-651">基本カレンダーが変更されたときにリソース カレンダーが更新されないために、実際の作業がタイムシートとプロジェクト計画の間で異なる場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-651">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="skype"></a><span data-ttu-id="c0ea1-652">Skype</span><span class="sxs-lookup"><span data-stu-id="c0ea1-652">Skype</span></span>

- <span data-ttu-id="c0ea1-653">複数の会話が発生している場合の、タブ表示の会話のタイトル名を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-653">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="visio"></a><span data-ttu-id="c0ea1-654">Visio</span><span class="sxs-lookup"><span data-stu-id="c0ea1-654">Visio</span></span>

- <span data-ttu-id="c0ea1-655">Visio から SVG へのエクスポートが、さまざまな図形で失敗していました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-655">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="c0ea1-656">Word</span><span class="sxs-lookup"><span data-stu-id="c0ea1-656">Word</span></span>

- <span data-ttu-id="c0ea1-657">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-657">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="c0ea1-658">Deskjet プリンターへの印刷時に、スケーリングの問題を引き起こす可能性があった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="c0ea1-658">We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span>

- <span data-ttu-id="c0ea1-659">表での文字の均等割り付けの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-659">We fixed an issue in Fit Text in Table.</span></span>

- <span data-ttu-id="c0ea1-660">無限ループになることがあるトラック変更の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-660">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="c0ea1-661">既存のファイルを保存すると [名前を付けて保存] ダイアログが必ず表示され、ファイルは実際には保存されない場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-661">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="c0ea1-662">2 つのドキュメントを 1 つのドキュメントに結合するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-662">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="c0ea1-663">編集用に保護されたドキュメントの比較機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-663">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="c0ea1-664">シャットダウン時にアプリが終了することがあるさまざまな問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-664">Fixes various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="c0ea1-665">特定のアドインに関連するクラッシュも修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-665">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c0ea1-666">Office スイート</span><span class="sxs-lookup"><span data-stu-id="c0ea1-666">Office Suite</span></span>

- <span data-ttu-id="c0ea1-667">新元号の名前である “Reiwa” のひらがなと漢字をスペルミスまたは間違った文法として誤って識別していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-667">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="c0ea1-668">SharePoint 2016 に保存されているファイルを共有しようとするときに、"申し訳ございません。何かがこのファイルの共有を妨げています。" というメッセージが表示される原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-668">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="c0ea1-669">PowerPoint での共同編集とオフライン編集の両方を含むセッションでデータの損失を引き起こす可能性のある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-669">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="c0ea1-670">これは、ユーザーがファイルを開くときに発生する可能性のあるクラッシュの修正プログラムです。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-670">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="c0ea1-671">同期エンジンでバックアップされた Sharepoint ファイルに '保存済み' と表示されますが、場合によっては実際に変更が保存されないため、データを損失することになります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-671">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="c0ea1-672">ユーザーが Word、Excel、および PowerPoint のドキュメントを保存できなくなることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-672">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="c0ea1-673">この問題は、[保存] アイコンをクリックしたり Ctrl キーを押しながら S キーを押したりした後に、新しいファイルを作成して [ダイアログで保存] オプションを表示するユーザーに影響を与えます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-673">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="c0ea1-674">非推奨の API から移動することにより、Word でクラッシュが発生する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-674">Fixes a crash in Word by moving away from a deprecated API.</span></span>

- <span data-ttu-id="c0ea1-675">PowerPoint の垂直テキスト ボックスで半角カタカナ文字が適切に回転しない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-675">Fixing an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="c0ea1-676">すべてのアプリのリボンで、図形の挿入ギャラリーが表示されるまでに約 4 秒かかるという Win7 のパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-676">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="c0ea1-677">Backstage の Info Place のスラブにアクセシビリティ情報が表示されていないというバグを修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-677">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="c0ea1-678">レジストリ整合性に関する Office 更新プロセスの信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-678">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="c0ea1-679">1 月と 7 月の 2019 フォークのチャネル名が新しいチャネル名に更新しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-679">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="c0ea1-680">従量制課金ネットワークで更新プログラムが予期せずブロックされる可能性があるという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-680">Corrects an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="c0ea1-681">ODT と GPO の更新期限設定で、相対期限の設定後、初回のみしか機能しないバスが修正されました。修正により、2 回目以降の更新プログラムで相対期限を使用きるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-681">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="c0ea1-682">特定の状況で、更新後に Office ショートカットが消えてしまう場合があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-682">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="c0ea1-683">この更新プログラムにより、Office ショートカットを公開するときの信頼性が向上します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-683">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="c0ea1-684">Office の更新プログラムが、意図したソース (ローカル共有、ネットワーク共有、構成マネージャーで提供される場所など) からではなく、予期せずに Office CDN からファイルをダウンロードする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-684">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="c0ea1-685">ユーザーが管理者ではなく、システム アカウントにネットワーク接続が確立されていない場合に、更新プログラムが適用されない問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-685">Resolves an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="c0ea1-686">Office の更新メッセージが、異なる言語で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-686">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="c0ea1-687">今後、Office の更新メッセージは Windows の表示言語と一致します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-687">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="c0ea1-688">以前に中断された可能性のあるダウンロードを再開することにより、Office の更新プログラムをダウンロードするときの信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-688">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="c0ea1-689">サード パーティ製プラグインのテキスト ボックスと図形の自動調整に関連する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-689">Address issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="c0ea1-690">この変更は、破損したファイルを開いた後の画像の正しいレンダリングに対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-690">This change addresses correctly rendering images after opening a corrupted file.</span></span>

- <span data-ttu-id="c0ea1-691">この変更により、マーカー付きの一部の散布図の表示が遅くなる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-691">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="c0ea1-692">大きなツリー ビューがクラッシュすることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="c0ea1-692">We fixed an issue where large tree views could result in a crash</span></span>

- <span data-ttu-id="c0ea1-693">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-693">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="c0ea1-694">Office ユーザーのセキュリティを保護するために、Microsoft Office の更新プログラムは SHA-2 アルゴリズムのみを使用して署名されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-694">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="c0ea1-695">Office ユーザーのセキュリティを保護するために、Microsoft Office の更新プログラムは SHA-2 アルゴリズムのみを使用して署名されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-695">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1902-july-14"></a><span data-ttu-id="c0ea1-697">バージョン 1902: 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-697">Version 1902: July 14</span></span>
<span data-ttu-id="c0ea1-698">*バージョン 1902 (ビルド 11328.20624)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-698">*Version 1902 (Build 11328.20624)*</span></span>

<span data-ttu-id="c0ea1-699">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-699">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1908-june-09"></a><span data-ttu-id="c0ea1-700">バージョン 1908: 6 月 9 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-700">Version 1908: June 09</span></span>
<span data-ttu-id="c0ea1-701">*バージョン 1908 (ビルド 11929.20838)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-701">*Version 1908 (Build 11929.20838)*</span></span>

<span data-ttu-id="c0ea1-702">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-702">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="c0ea1-704">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="c0ea1-704">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c0ea1-705">Excel</span><span class="sxs-lookup"><span data-stu-id="c0ea1-705">Excel</span></span>

- <span data-ttu-id="c0ea1-706">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-706">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="c0ea1-707">印刷時にフォーム コントロールのチェックボックスが拡大縮小されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-707">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="c0ea1-708">従来の "共有ブック" モードを使用して、ブックの新しいシートに変更を一覧表示しようとすると、クラッシュが発生する場合がありました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-708">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="c0ea1-709">Outlook</span><span class="sxs-lookup"><span data-stu-id="c0ea1-709">Outlook</span></span>

- <span data-ttu-id="c0ea1-710">大きな HTML メッセージを転送するとき、ユーザーにメッセージ本文の全体が表示されないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-710">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c0ea1-711">Office スイート</span><span class="sxs-lookup"><span data-stu-id="c0ea1-711">Office Suite</span></span>

- <span data-ttu-id="c0ea1-712">1月と7月の2019フォークのチャネル名が新しいチャネル名に更新されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-712">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1902-june-09"></a><span data-ttu-id="c0ea1-714">バージョン 1902: 6月 9 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-714">Version 1902: June 09</span></span>
<span data-ttu-id="c0ea1-715">*バージョン 1902 (ビルド 11328.20602)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-715">*Version 1902 (Build 11328.20602)*</span></span>

<span data-ttu-id="c0ea1-716">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-716">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="c0ea1-718">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="c0ea1-718">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="c0ea1-719">Office スイート</span><span class="sxs-lookup"><span data-stu-id="c0ea1-719">Office Suite</span></span>

- <span data-ttu-id="c0ea1-720">1月と7月の2019フォークのチャネル名が新しいチャネル名に更新されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-720">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="c0ea1-721">C2R ビルドを中断していたベースライン ファイルから、古い形式の参照を削除しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-721">We removed obsolete references from the baseline files that were breaking the C2R Build.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-may-12"></a><span data-ttu-id="c0ea1-723">バージョン 1908: 5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-723">Version 1908: May 12</span></span>
<span data-ttu-id="c0ea1-724">*バージョン 1908 (ビルド 11929.20776)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-724">*Version 1908 (Build 11929.20776)*</span></span>

<span data-ttu-id="c0ea1-725">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-725">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="c0ea1-727">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="c0ea1-727">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c0ea1-728">Excel</span><span class="sxs-lookup"><span data-stu-id="c0ea1-728">Excel</span></span>

- <span data-ttu-id="c0ea1-729">色でフィルタリングされたデータを異なる幅の列にコピーすると、値が貼り付けられません。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-729">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

### <a name="outlook"></a><span data-ttu-id="c0ea1-730">Outlook</span><span class="sxs-lookup"><span data-stu-id="c0ea1-730">Outlook</span></span>

- <span data-ttu-id="c0ea1-731">最新の Windows 更新プログラム適用後に、ユーザーが msg および .oft ファイルを開こうとするとクラッシュが起きる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-731">Addressed an issue that caused users to experience a crash when opening msg and .oft files after applying a recent Windows update.</span></span>

### <a name="word"></a><span data-ttu-id="c0ea1-732">Word</span><span class="sxs-lookup"><span data-stu-id="c0ea1-732">Word</span></span>

- <span data-ttu-id="c0ea1-733">2 つのドキュメントを 1 つのドキュメントに結合するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-733">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="c0ea1-734">編集用に保護されたドキュメントの比較機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-734">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1902-may-12"></a><span data-ttu-id="c0ea1-736">バージョン 1902: 5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-736">Version 1902: May 12</span></span>
<span data-ttu-id="c0ea1-737">*バージョン 1902 (ビルド 11328.20586)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-737">*Version 1902 (Build 11328.20586)*</span></span>

<span data-ttu-id="c0ea1-738">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-738">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="c0ea1-740">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="c0ea1-740">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="c0ea1-741">Outlook</span><span class="sxs-lookup"><span data-stu-id="c0ea1-741">Outlook</span></span>

- <span data-ttu-id="c0ea1-742">最新の Windows 更新プログラム適用後に、ユーザーが msg および .oft ファイルを開こうとするとクラッシュが起きる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-742">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="c0ea1-743">既定では、アイテム保持ポリシーのラベルには、保持期間がかっこ内に表示されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-743">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="c0ea1-744">これにより、管理者はポリシー名のみを表示するように指定するレジストリ キーを取得することができます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-744">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="c0ea1-745">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="c0ea1-745">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="c0ea1-746">0 = 既定値。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-746">0 = Default.</span></span>  <span data-ttu-id="c0ea1-747">1 = アイテム保持ポリシー テキスト のPolicyName のみが表示されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-747">1 = we will only show the PolicyName for Retention policy text.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-may-04"></a><span data-ttu-id="c0ea1-749">バージョン 1908: 5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-749">Version 1908: May 04</span></span>
<span data-ttu-id="c0ea1-750">*バージョン 1908 (ビルド 11929.20752)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-750">*Version 1908 (Build 11929.20752)*</span></span>

<span data-ttu-id="c0ea1-751">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-751">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="c0ea1-752">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="c0ea1-752">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="c0ea1-753">Outlook</span><span class="sxs-lookup"><span data-stu-id="c0ea1-753">Outlook</span></span>

- <span data-ttu-id="c0ea1-754">ユーザーが特定の検索結果を選択すると、クラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-754">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="c0ea1-755">[添付ファイル] ​​ツールに [クラウドに保存] ボタンが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-755">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="c0ea1-756">既定では、アイテム保持ポリシーのラベルには、保持期間がかっこ内に表示されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-756">By default, retention policy labels display the retention time period in parenthesis.</span></span><span data-ttu-id="c0ea1-757">これにより、管理者はポリシー名のみを表示するように指定するレジストリ キーを取得することができます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-757"> This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span><span data-ttu-id="c0ea1-758"> HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="c0ea1-758"> HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span><span data-ttu-id="c0ea1-759"> 0 = 既定値 1 = アイテム保持ポリシー テキスト のPolicyName のみが表示されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-759"> 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c0ea1-760">Office スイート</span><span class="sxs-lookup"><span data-stu-id="c0ea1-760">Office Suite</span></span>

- <span data-ttu-id="c0ea1-761">Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-761">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1902-may-04"></a><span data-ttu-id="c0ea1-762">バージョン 1902: 5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-762">Version 1902: May 04</span></span>
<span data-ttu-id="c0ea1-763">*バージョン 1902 (ビルド 11328.20572)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-763">*Version 1902 (Build 11328.20572)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="c0ea1-764">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="c0ea1-764">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="c0ea1-765">Office スイート</span><span class="sxs-lookup"><span data-stu-id="c0ea1-765">Office Suite</span></span>

- <span data-ttu-id="c0ea1-766">Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-766">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version1908april-26"></a><span data-ttu-id="c0ea1-767">バージョン 1908: 4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-767">Version 1908: April 26</span></span>
<span data-ttu-id="c0ea1-768">*バージョン 1908 (ビルド 11929.20736)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-768">*Version 1908 (Build 11929.20736)*</span></span>

<span data-ttu-id="c0ea1-769">セキュリティ更新プログラムのリストは  [こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-769">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="c0ea1-770">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="c0ea1-770">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c0ea1-771">Excel</span><span class="sxs-lookup"><span data-stu-id="c0ea1-771">Excel</span></span>

- <span data-ttu-id="c0ea1-772">VBA マクロを使用して範囲の内容をクリアするときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-772">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="c0ea1-773">値の範囲への入力に予想より時間がかかる VBA の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-773">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="c0ea1-774">グラフの軸の "Value Crosses At" プロパティが、ファイルを保存してもう一度開くときに予期せず変更されるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-774">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="c0ea1-775">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-775">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


### <a name="onenote"></a><span data-ttu-id="c0ea1-776">OneNote</span><span class="sxs-lookup"><span data-stu-id="c0ea1-776">OneNote</span></span>

- <span data-ttu-id="c0ea1-777">同期およびサービスの安定性を改善するために、OneNote ユーザー エクスペリエンスで実行されている一時的な手段についての詳細情報をユーザーが学べるようにする通知をローカライズします。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-777">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>


## <a name="version-1908-april-14"></a><span data-ttu-id="c0ea1-778">バージョン 1908: 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-778">Version 1908: April 14</span></span>
<span data-ttu-id="c0ea1-779">*バージョン 1908 (ビルド 11929.20708)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-779">*Version 1908 (Build 11929.20708)*</span></span>

<span data-ttu-id="c0ea1-780">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-780">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="c0ea1-782">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="c0ea1-782">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c0ea1-783">Excel</span><span class="sxs-lookup"><span data-stu-id="c0ea1-783">Excel</span></span>

- <span data-ttu-id="c0ea1-784">結合されたセルを含む列を削除するときにパフォーマンスが低下する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-784">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="c0ea1-785">[印刷プレビュー] に表示されるときのフォーム コントロール内のテキストの拡大縮小に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-785">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

### <a name="skype"></a><span data-ttu-id="c0ea1-786">Skype</span><span class="sxs-lookup"><span data-stu-id="c0ea1-786">Skype</span></span>

- <span data-ttu-id="c0ea1-787">複数の会話が発生している場合の、タブ表示の会話のタイトル名を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-787">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="outlook"></a><span data-ttu-id="c0ea1-788">Outlook</span><span class="sxs-lookup"><span data-stu-id="c0ea1-788">Outlook</span></span>

- <span data-ttu-id="c0ea1-789">Outlook のシャットダウン時にクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-789">Addressed an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="c0ea1-790">一部のシナリオで顧客に空室リストが表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-790">Addressed an issue that caused customers to see an empty room list in some scenarios.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c0ea1-791">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c0ea1-791">PowerPoint</span></span>

- <span data-ttu-id="c0ea1-792">蛍光ペンの問題を修正しました。暗い蛍光ペン色の白いテキストはグレースケールで黒として印刷されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-792">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="c0ea1-793">Word</span><span class="sxs-lookup"><span data-stu-id="c0ea1-793">Word</span></span>

- <span data-ttu-id="c0ea1-794">表での、文字の均等割り付けの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-794">Fixed an issue in Fit Text in Table.</span></span>


## <a name="version-1902-april-14"></a><span data-ttu-id="c0ea1-795">バージョン 1902: 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-795">Version 1902: April 14</span></span>
<span data-ttu-id="c0ea1-796">*バージョン 1902 (ビルド 11328.20564)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-796">*Version 1902 (Build 11328.20564)*</span></span>

<span data-ttu-id="c0ea1-797">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-797">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-march-10"></a><span data-ttu-id="c0ea1-799">バージョン 1908: 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-799">Version 1908: March 10</span></span>
<span data-ttu-id="c0ea1-800">*バージョン 1908 (ビルド 11929.20648)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-800">*Version 1908 (Build 11929.20648)*</span></span>

<span data-ttu-id="c0ea1-801">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-801">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="c0ea1-803">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="c0ea1-803">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c0ea1-804">Excel</span><span class="sxs-lookup"><span data-stu-id="c0ea1-804">Excel</span></span>

- <span data-ttu-id="c0ea1-805">ブックで外部リンクがある場合にポップアップ ウィンドウが複数表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-805">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>


- <span data-ttu-id="c0ea1-806">一部のロケールにおいて、[Text to Column] 機能が失敗することがあります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-806">Text to Column functionality may fail for some locales.</span></span>


- <span data-ttu-id="c0ea1-807">非表示の名前付き範囲にアクセスすると、ユーザーにエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-807">Users may encounter an error when accessing a hidden named range.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c0ea1-808">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c0ea1-808">PowerPoint</span></span>

- <span data-ttu-id="c0ea1-809">Shape.Paste メソッドを使用する際に発生する問題を解決しました。Shape.Paste メソッドを使用して図形をコピーして貼り付けるときに、貼り付けられた図形の選択内容が変更するという問題です。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-809">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>


### <a name="word"></a><span data-ttu-id="c0ea1-810">Word</span><span class="sxs-lookup"><span data-stu-id="c0ea1-810">Word</span></span>

- <span data-ttu-id="c0ea1-811">既存のファイルを保存すると [名前を付けて保存] ダイアログが必ず表示され、ファイルは実際には保存されない場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-811">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>


### <a name="office-suite"></a><span data-ttu-id="c0ea1-812">Office スイート</span><span class="sxs-lookup"><span data-stu-id="c0ea1-812">Office Suite</span></span>

- <span data-ttu-id="c0ea1-813">この変更により、マーカー付きの一部の散布図の表示が遅くなる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-813">This change addresses slow rendering of some scatter charts with markers.</span></span>

## <a name="version-1902-march-10"></a><span data-ttu-id="c0ea1-814">バージョン 1902: 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-814">Version 1902: March 10</span></span>
<span data-ttu-id="c0ea1-815">*バージョン 1902 (ビルド 11328.20554)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-815">*Version 1902 (Build 11328.20554)*</span></span>

<span data-ttu-id="c0ea1-816">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-816">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-february-11"></a><span data-ttu-id="c0ea1-818">バージョン 1908: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-818">Version 1908: February 11</span></span>
<span data-ttu-id="c0ea1-819">*バージョン 1908 (ビルド 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-819">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="c0ea1-820">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-820">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="c0ea1-822">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="c0ea1-822">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c0ea1-823">Excel</span><span class="sxs-lookup"><span data-stu-id="c0ea1-823">Excel</span></span>

- <span data-ttu-id="c0ea1-824">この更新プログラムは、VBA を使用してグラフのヘッダー/フッターに画像を追加するたびにエラーが発生する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-824">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="c0ea1-825">グループ ボックス コントロールの境界線が印刷プレビューまたは印刷時に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-825">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="c0ea1-826">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-826">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="c0ea1-827">グラフを含むブックを保存すると、グラフ ヘッダーの画像のファイル サイズが大きくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-827">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="c0ea1-828">選択範囲を相互参照ブックと同期させ続けることにより、相互参照ブックの DBCS 文字が破損する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-828">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="c0ea1-829">自動調整を使用して行の高さを調整するときにチェック ボックスのコントロールが縮小される可能性があるという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-829">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="c0ea1-830">Outlook</span><span class="sxs-lookup"><span data-stu-id="c0ea1-830">Outlook</span></span>

- <span data-ttu-id="c0ea1-831">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-831">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="c0ea1-832">競合メッセージの処理中にユーザーに同期エラーが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-832">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="c0ea1-833">Outlook の起動時にユーザーが [プロファイルの読み込み中] 画面でハングアップする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-833">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="c0ea1-834">ビューを変更すると、断続的なクラッシュが発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-834">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="c0ea1-835">Citrix 環境で 30 件を超える予定表を表示したときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-835">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="c0ea1-836">[こちら](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)は、以前のバージョンで文書化された個々の KB です。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-836">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="c0ea1-837">ユーザーが OST と同期している共有予定表フォルダーに問題があり、これらのフォルダーを操作しようとするとアクセス許可エラーが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-837">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c0ea1-838">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c0ea1-838">PowerPoint</span></span>

- <span data-ttu-id="c0ea1-839">PowerPoint スライドでのコピーと貼り付けのシナリオである図形のコピーを改善しました。ループ内の他のスライドに貼り付けると例外で失敗する場合があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-839">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="c0ea1-840">共同作業ユーザー間のパフォーマンスが低下する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-840">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="c0ea1-841">増分で開くファイルに、複数のメディア ストリームが埋め込まれたスライドが含まれている場合に発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-841">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="c0ea1-842">PowerPoint の初回起動時に、信頼されていないアドインに対してセキュリティ警告メッセージ バーが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-842">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="c0ea1-843">Project</span><span class="sxs-lookup"><span data-stu-id="c0ea1-843">Project</span></span>

- <span data-ttu-id="c0ea1-844">基本カレンダーが変更されたときにリソース カレンダーが更新されないために、実際の作業がタイムシートとプロジェクト計画の間で異なる場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-844">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="c0ea1-845">Word</span><span class="sxs-lookup"><span data-stu-id="c0ea1-845">Word</span></span>

- <span data-ttu-id="c0ea1-846">非推奨の API から移動することにより、Word でクラッシュが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-846">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c0ea1-847">Office スイート</span><span class="sxs-lookup"><span data-stu-id="c0ea1-847">Office Suite</span></span>

- <span data-ttu-id="c0ea1-848">この変更は、破損したファイルを開いた後の画像の正しいレンダリングに対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-848">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1902-february-11"></a><span data-ttu-id="c0ea1-850">バージョン 1902: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-850">Version 1902: February 11</span></span>
<span data-ttu-id="c0ea1-851">*バージョン 1902 (ビルド 11328.20526)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-851">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="c0ea1-852">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-852">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="c0ea1-854">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="c0ea1-854">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="c0ea1-855">Outlook</span><span class="sxs-lookup"><span data-stu-id="c0ea1-855">Outlook</span></span>

- <span data-ttu-id="c0ea1-856">ユーザーが暗号化されたメールを送信しようとするときに、"暗号化アルゴリズムがサポートされていません" というエラーを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-856">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="c0ea1-857">Word</span><span class="sxs-lookup"><span data-stu-id="c0ea1-857">Word</span></span>

- <span data-ttu-id="c0ea1-858">非推奨の API から移動することにより、Word でクラッシュが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-858">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

## <a name="version-1808-february-11"></a><span data-ttu-id="c0ea1-861">バージョン 1808: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-861">Version 1808: February 11</span></span>
<span data-ttu-id="c0ea1-862">*バージョン 1808 (ビルド 10730.20438)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-862">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="c0ea1-863">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-863">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-january-14"></a><span data-ttu-id="c0ea1-865">バージョン 1908: 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-865">Version 1908: January 14</span></span>
<span data-ttu-id="c0ea1-866">*バージョン 1908 (ビルド 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-866">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="c0ea1-867">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-867">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="c0ea1-869">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="c0ea1-869">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="c0ea1-870">Access</span><span class="sxs-lookup"><span data-stu-id="c0ea1-870">Access</span></span>

- <span data-ttu-id="c0ea1-871">**データベース オブジェクトをタブで管理する:** アクティブなタブが分かりやすく表示され、簡単にタブをドラッグして再配置し、ワンクリックでデータベース オブジェクトを閉じることができます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-871">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="c0ea1-872">**シームレスに切り替える:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用のアカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-872">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="c0ea1-873">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-873">Switching between them has never been easier.</span></span> [<span data-ttu-id="c0ea1-874">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-874">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="c0ea1-875">**より大きい [ズーム] ボックス:** [ズーム] ボックスがより大きく表示され、そこでフォントを変更することができます。変更内容はすべて [ズーム] ボックス内に記憶されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-875">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="c0ea1-876">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-876">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="c0ea1-877">Excel</span><span class="sxs-lookup"><span data-stu-id="c0ea1-877">Excel</span></span>

- <span data-ttu-id="c0ea1-878">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-878">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="c0ea1-879">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-879">Switching between them has never been easier.</span></span> [<span data-ttu-id="c0ea1-880">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-880">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="c0ea1-881">**コンテンツのリーチを拡大する:** プレゼンテーションのアクセシビリティを高める必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="c0ea1-881">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="c0ea1-882">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-882">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="c0ea1-883">[校閲]>[アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-883">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="c0ea1-884">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="c0ea1-884">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="c0ea1-885">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-885">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="c0ea1-886">**ワークシートが生まれ変わりました：** ワークブックを使ってアニメーション 3D グラフィックスを挿入し、心臓の鼓動、惑星軌道、そして T-Rex の大暴れを見ることができます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-886">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="c0ea1-887">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-887">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="c0ea1-888">**データの詳細を検出する:** 新しいアイデア ボタンは、データのパターンを探し、それを使用してインテリジェントな個人向けの提案を作成します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-888">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions.</span></span> [<span data-ttu-id="c0ea1-889">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-889">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- <span data-ttu-id="c0ea1-890">**共同作業がさらに簡単に:** 共同編集の改善とは、条件付き書式、セルのスタイルなどを使用して作業しているときに、ユーザーによる変更がシームレスに共同作業者の変更と統合されるということです。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-890">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="c0ea1-891">**類似列のテーブルを結合する:** 取得と変換 (Power Query) では、テーブルを統合するために列を比較するときに、近似文字列マッチング ロジック (あいまい一致とも呼ばれる) が使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-891">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="c0ea1-892">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-892">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="c0ea1-893">**Power Query の機能強化を使用して素早くコーディングする:** オートコンプリートと構文の色分けを使用して、素早くコーディングを完了できます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-893">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="c0ea1-894">関数、列、パラメーターも簡単に見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-894">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="c0ea1-895">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-895">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="c0ea1-896">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-896">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="c0ea1-897">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-897">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="c0ea1-898">Outlook</span><span class="sxs-lookup"><span data-stu-id="c0ea1-898">Outlook</span></span>

- <span data-ttu-id="c0ea1-899">\*\* Outlook のユーザー エクスペリエンスを更新しました：\*\* これまで Coming Soon でプレビューできていた、最も重要なことに集中できるようにするためのシンプルな操作性です。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-899">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="c0ea1-900">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-900">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="c0ea1-901">**カスタマイズも可能、シンプルになったリボン：** 最もよく使うボタンが単一行にまとめられ、使いやすくなりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-901">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="c0ea1-902">簡単に従来のビューとシンプルなビューを切り替えたり、コマンドを固定または固定解除できます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-902">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="c0ea1-903">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-903">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="c0ea1-904">**メッセージの移動中も作業が可能:** Outlook では、メッセージの移動がバックグラウンドで行われるようになったため、フォルダー間で多数のメッセージの移動が行われている間も作業を続けることができます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-904">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="c0ea1-905">**連続する会議の合間に時間を組み込む:** 既定で 5 分から 10 分早く会議を終了するように設定することで、出席者に休憩時間や場所の移動時間を与えることができます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-905">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="c0ea1-906">**お気に入りのアクションを選びましょう：** フラグや、削除機能を使いますか？</span><span class="sxs-lookup"><span data-stu-id="c0ea1-906">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="c0ea1-907">アーカイブまたは既読に​​しますか?</span><span class="sxs-lookup"><span data-stu-id="c0ea1-907">How about Archive or Mark as Read?</span></span> <span data-ttu-id="c0ea1-908">クイック操作メニューをカスタマイズしてよく使うコマンドを追加できます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-908">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="c0ea1-p182">**ミームが表示される:** テキストまたは静的イメージだけでは十分ではない場合、アニメーション GIF を使用して要点を示すことができます。[詳細情報](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-p182">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="c0ea1-911">**より簡単なアカウントの追加方法:** アカウントのセットアップの改善により、2 要素認証を使用する Outlook.com と Gmail のアカウントを Outlook に追加することが以前よりも簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-911">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="c0ea1-912">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-912">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="c0ea1-913">**同期制限にさよならしましょう:** Outlook の改善によりフォルダーの制限が解消され、そのまま共有メールボックスが同期されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-913">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="c0ea1-914">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-914">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="c0ea1-915">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-915">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="c0ea1-916">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-916">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="c0ea1-917">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c0ea1-917">PowerPoint</span></span>

- <span data-ttu-id="c0ea1-918">**よりよい変形操作:** 図形に名前を付けると、変形するときにより細かく制御できます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-918">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="c0ea1-919">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-919">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="c0ea1-920">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="c0ea1-920">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="c0ea1-921">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-921">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="c0ea1-922">**コンテンツのリーチを拡大する:** プレゼンテーションのアクセシビリティを高める必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="c0ea1-922">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="c0ea1-923">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-923">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="c0ea1-924">[校閲]>[アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-924">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="c0ea1-925">**シームレスに切り替える:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用のアカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-925">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="c0ea1-926">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-926">Switching between them has never been easier.</span></span> [<span data-ttu-id="c0ea1-927">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-927">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="c0ea1-928">**オンライン ビデオの新しい保存場所:** Microsoft Stream にビデオを保存すれば、組織内のすべてのユーザーが視聴できます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-928">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="c0ea1-929">ビデオのリンクを挿入すれば、小さなファイル サイズでマルチメディア プレゼンテーションをご利用いただけます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-929">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="c0ea1-930">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-930">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="c0ea1-931">**変更が発生したときに変更内容を自動的に保存する:** 変更が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-931">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="c0ea1-p190">**ユーザーへのテストやアンケート:** テストやアンケートをスライドに配置します。Office で応答が自動的に収集され、保存されます。[詳細情報](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-p190">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="c0ea1-935">**これまで以上に簡単にオンライン ビデオを挿入できるようになりました:** Vimeo または YouTube からビデオをスライドに挿入する場合は、</span><span class="sxs-lookup"><span data-stu-id="c0ea1-935">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide?</span></span> <span data-ttu-id="c0ea1-936">ビデオ ページへのリンクがあれば簡単に行えます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-936">The video page link is all you need.</span></span> [<span data-ttu-id="c0ea1-937">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-937">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="c0ea1-938">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-938">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="c0ea1-939">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-939">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="c0ea1-940">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-940">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="c0ea1-941">Project</span><span class="sxs-lookup"><span data-stu-id="c0ea1-941">Project</span></span>

- <span data-ttu-id="c0ea1-942">**シームレスに切り替える:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用のアカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-942">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="c0ea1-943">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-943">Switching between them has never been easier.</span></span> [<span data-ttu-id="c0ea1-944">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-944">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="c0ea1-945">Visio</span><span class="sxs-lookup"><span data-stu-id="c0ea1-945">Visio</span></span>

- <span data-ttu-id="c0ea1-946">**プロセス図を Word にエクスポート:** Word 文書に図形やメタデータなどのグラフ コンテンツを自動的に追加します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-946">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="c0ea1-947">その後に、文書をカスタマイズしてプロセスに関するガイドラインや操作マニュアルを作成できます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-947">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="c0ea1-948">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-948">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="c0ea1-949">**はっとするようなデータ フローチャート:** データ ビジュアライザーのフローチャートの見事な新しいレイアウトがすっきり、はっきり、わかりやすくなりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-949">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="c0ea1-950">オプションの [デザイン] タブをクリックします。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-950">Click the Design tab for options.</span></span>

- <span data-ttu-id="c0ea1-951">**Azure ステンシルが組み込まれました:** 豊富な Azure ステンシルを使用してクラウド アプリの設計やアーキテクチャの計画を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-951">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="c0ea1-952">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-952">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="c0ea1-p197">**壊れた Excel リンクの問題を解消:** データ ビジュアライザーの図にリンクされているはずの Excel ブックが見つかりませんか? 再リンクして、すぐに業務を再開できます。[詳細情報](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-p197">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="c0ea1-956">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-956">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="c0ea1-957">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-957">Switching between them has never been easier.</span></span> [<span data-ttu-id="c0ea1-958">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-958">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="c0ea1-959">**Power BI から Visio ビジュアルをエクスポートする:** Power BI レポートを PDF、PowerPoint などのファイルとしてエクスポートするときに、Power BI 用の Visio ビジュアルが正しく表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-959">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="c0ea1-960">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-960">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="c0ea1-961">Word</span><span class="sxs-lookup"><span data-stu-id="c0ea1-961">Word</span></span>

- <span data-ttu-id="c0ea1-962">**[学習ツール] モードで、ページで使用できる色が増えました:** Word の学習ツールでは、より多くのページ テーマ色が追加され、ページの背景色を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-962">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="c0ea1-963">すべて白またはすべて黒の背景だと読みにくいと感じるユーザーは少なくないため、PC と Mac の Word で色の選択肢を拡大しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-963">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="c0ea1-p201">**インク エディターを使った自然な編集:** ペンを使って 1 ストローク描くだけで、単語の分割や結合、新しい線の追加、単語の挿入などができます。[詳細情報](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-p201">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="c0ea1-p202">**静的なドキュメントから魅力的なドキュメントへの変換:** ドキュメントを、すべてのデバイスに対応する対話型の使いやすい Web ページに変換します。[詳細情報](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-p202">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="c0ea1-968">**コンテンツのリーチを拡大する:** ドキュメントのアクセシビリティを高める必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="c0ea1-968">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="c0ea1-969">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-969">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="c0ea1-970">[校閲]>[アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-970">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="c0ea1-971">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="c0ea1-971">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="c0ea1-972">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-972">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="c0ea1-973">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-973">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="c0ea1-974">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-974">Switching between them has never been easier.</span></span> [<span data-ttu-id="c0ea1-975">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-975">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="c0ea1-p206">**行フォーカスによる読解力の向上:** ドキュメント内で行ごとの移動をスムーズに行います。一度に 1 行か、3 行か、5 行かを表示するようフォーカスを調整できます。[詳細情報](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-p206">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="c0ea1-979">**変更時に変更内容を保存する:** すべての更新が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-979">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="c0ea1-980">**\@メンションを使用してユーザーの注意を引く:** コメントで @メンションを使うと、仕事仲間による入力が必要な場合にそのユーザーに知らせることができます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-980">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="c0ea1-981">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-981">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="c0ea1-982">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-982">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="c0ea1-983">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-983">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="c0ea1-984">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-984">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="c0ea1-985">Office スイート</span><span class="sxs-lookup"><span data-stu-id="c0ea1-985">Office Suite</span></span>

- <span data-ttu-id="c0ea1-986">**特定のファイルをすばやく見つける:** 最近作業を行ったファイルを探している場合は、</span><span class="sxs-lookup"><span data-stu-id="c0ea1-986">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="c0ea1-987">[ファイル] > [開く] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-987">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="c0ea1-988">**変更が発生したときに変更内容を自動的に保存する:** 変更が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-988">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="c0ea1-989">**プライバシー制御**: 診断データとコネクテッド エクスペリエンス用に新しく更新されて、改善された制御。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-989">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="c0ea1-990">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-990">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="c0ea1-991">**新しい外観を備えた Office のアイコン:** シンプルかつ高性能で、インテリジェントな Office のエクスペリエンスを反映するように、Office のアイコンがリニューアルされました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-991">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="c0ea1-992">**Microsoft Teams のインストール:** Microsoft Teams は、Office 365 ProPlus の既存のインストールに既定でインストールされています。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-992">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="c0ea1-993">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c0ea1-993">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="c0ea1-996">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="c0ea1-996">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c0ea1-997">Access</span><span class="sxs-lookup"><span data-stu-id="c0ea1-997">Access</span></span>

- <span data-ttu-id="c0ea1-998">この更新プログラムにより、Sum などの集計が結果を整数値に切り捨てる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-998">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="c0ea1-999">この更新プログラムにより、リモート テーブル (SQL Server テーブルなど) への参照を含むユニオン クエリにより Access が閉じて再起動する問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-999">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="c0ea1-1000">この更新プログラムにより、更新クエリが実行されるか、SQL で UPDATE ステートメントが使用されるときに &quot;クエリは破損しています&quot; というエラーを発生させる場合のある Microsoft Access の問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1000">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="c0ea1-1001">Excel</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1001">Excel</span></span>

- <span data-ttu-id="c0ea1-1002">ドキュメント タイトルのオランダ語の KeyTip が Alt-G に変更されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1002">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="c0ea1-1003">図形やフォームコントロールに割り当てられているマクロが間違ったエラーメッセージとして表示される、または間違った対象範囲で動作する問題が Excel で修正されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1003">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="c0ea1-1004">最初のアイテムを検索した後に、ダイアログでのフォーカスの位置が変更されてしまう検索と置換についての問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1004">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="c0ea1-1005">これにより、ピボットテーブルの並べ替え方法を変更し、他のユーザーとの共同編集セッション中にそれを更新するとクラッシュが発生する可能性がある問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1005">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="c0ea1-1006">OLAP ピボットテーブルのフィルターが、キューブから削除された値に設定された場合の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1006">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="c0ea1-1007">グラフ テンプレートを使用してグラフを挿入する場合に、プレビューで正しい色が使用されるよう修正します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1007">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="c0ea1-1008">シリーズ コレクションを変更するときに、散布図が適切にレンダリングされない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1008">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="c0ea1-1009">セルが挿入または削除されたときに、ウォーターフォール図とじょうごグラフがテーブルと同期しなくなる原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1009">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="c0ea1-1010">Excel で、ユーザーが変更を取得するためにブックを再び開くよう要求されるマージ競合の問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1010">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="c0ea1-1011">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1011">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="c0ea1-1012">最小化されたウィンドウをアクティブにするマクロ実行時エラーの原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1012">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="c0ea1-1013">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1013">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="c0ea1-1014">他のユーザーと共同編集しているときに、テーブルの横にある切り取りと貼り付けの操作が失敗する原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1014">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="c0ea1-1015">実行中のマクロでカスタム プロパティを変更するときに、共同編集の中断を引き起こす原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1015">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="c0ea1-1016">アドインによって開かれた WPF (Windows Presentation Foundation) フォームのコンボ ボックスからアイテムを選ぶことができない問題が発生しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1016">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="c0ea1-1017">ブックが開かれていない状態で最近使用したファイルを検索するときに、クラッシュを発生させる原因となっていた可能性がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1017">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="c0ea1-1018">非同期のユーザー定義関数が同期して実行されるパフォーマンスの問題が発生しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1018">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="c0ea1-1019">結合されたセルで列を削除するパフォーマンスが大幅に改善されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1019">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="c0ea1-1020">スクロール後にセルを選択すると間違ったセルが選択されることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1020">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="c0ea1-1021">Lookup 関数がエラーを返す問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1021">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="c0ea1-1022">Office の以前のバージョンで作成されたブックを Office の最新のバージョンで開いたときに、Excel の終了を引き起こす可能性がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1022">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="c0ea1-1023">ファイルに広範な条件付き書式が設定されている場合に、[フォントの色] ボタンをクリックするとパフォーマンスが低下する問題。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1023">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="c0ea1-1024">印刷プレビューの印刷範囲が正しくないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1024">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="c0ea1-1025">信頼されていないネットワーク共有から保護されたファイルを編集する際に、Excel にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1025">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="c0ea1-1026">色によるフィルタリングのパフォーマンスが大幅に改善されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1026">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="c0ea1-1027">一部の保護されたシートにハイパーリンクが貼り付けられない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1027">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="c0ea1-1028">アドイン マネジャーで参照するときに、16 個を超えるアドインを表示できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1028">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="c0ea1-1029">この変更は、ソフトウェア レンダリングを活用することにより、特定の Intel グラフィック ドライバーの問題を回避します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1029">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="c0ea1-1030">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1030">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="c0ea1-1031">この更新プログラムにより、"アップロードできませんでした" というメッセージが表示され、Office ドキュメントが OneDrive for Business にアップロードされないことがあるエラーが修正されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1031">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="c0ea1-1032">Win32 クライアントの [アイデア] ボタンをクリックしてアドインを読み込むときにエラーが発生するという Excel のアイデア機能の問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1032">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="c0ea1-1033">Outlook</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1033">Outlook</span></span>

- <span data-ttu-id="c0ea1-1034">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1034">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="c0ea1-1035">メールボックスを基本認証から最新認証にアップグレードしたユーザーが、Outlook プロファイルに関連付けられた正しくないアカウントで終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1035">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="c0ea1-1036">Web アドインがデジタル著作権管理 (DRM) メッセージにアクセスすべきでないときにアクセスする原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1036">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="c0ea1-1037">一部のセーフリンクに対して簡易的なホバーの URL が正しく表示されなくなる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1037">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="c0ea1-1038">これにより、Python による添付ファイルもブロックされるよう、Outlook の添付ファイルのブロック ロジックが更新されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1038">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="c0ea1-1039">設定に関係なく、一部の POP3 ユーザーに、すべてのメールがプレーンテキストで書式設定されて表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1039">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="c0ea1-1040">この修正プログラムでは、HTML 形式のメッセージの表示が復元されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1040">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="c0ea1-1041">プライマリ予定表からグループ予定表にアイテムをコピーするときに、ユーザーにアクセス許可のエラーを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1041">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="c0ea1-1042">ユーザーがスクリーン リーダーから場所の候補にアクセスできない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1042">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="c0ea1-1043">ユーザーがキーボード ショートカットを使用してメールボックス フォルダーを操作するときに、顕著な遅延を発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1043">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="c0ea1-1044">非常に長い Outlook セッションでメモリ リークを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1044">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="c0ea1-1045">ユーザーが [ルール] ダイアログを開くと、"このコンピューターのルールは、Microsoft Exchange のルールと異なります" というメッセージが表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1045">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="c0ea1-1046">特定のセーフリンクを操作するときに、Outlook でクラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1046">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="c0ea1-1047">代理人が特定の会議出席依頼に既に返信したかどうかに関係なく、管理者が不明瞭になる原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1047">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="c0ea1-1048">一部の AutoDiscover の応答を処理するときに、クラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1048">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="c0ea1-1049">アカウント作成コンテキストからサポートに連絡しようとすると、ユーザーに [OK] ボタンのある空のメッセージ ボックスが表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1049">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="c0ea1-1050">この変更により、UPN 経由で自動検出の認証プロンプトに提供されるアカウントのメールを選択するため、ポリシーを管理者が有効にできるようになります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1050">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="c0ea1-1051">既定では、使用可能な場合に、自動検出ではアカウント UPN の方が選択されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1051">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="c0ea1-1052">最新のグループに対し、検索の失敗がユーザーに表示される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1052">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="c0ea1-1053">Outlook ユーザーが特定のシナリオで "パスワードを要求している" 状態で停止する原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1053">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="c0ea1-1054">会議室の空き時間外に行われた会議のためにユーザーにその会議室が提案される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1054">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="c0ea1-1055">ユーザーが暗号化されたメールを送信しようとするときに、"暗号化アルゴリズムがサポートされていません" というエラーを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1055">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="c0ea1-1056">英語以外の言語を使用するユーザーの、メールの件名が非常に小さくなるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1056">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="c0ea1-1057">一部のユーザーに、セカンダリ Exchange アカウントを追加するときに作成された、重複した特別なフォルダーが表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1057">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="c0ea1-1058">"不在着信した会話" メッセージのルールを作成しようとするときに、クラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1058">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="c0ea1-1059">SMIME アルゴリズムの選択に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1059">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="c0ea1-1060">代替送信者を使用しているときに、ポリシーのヒントが表示されない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1060">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="c0ea1-1061">ユーザーが Outlook プロセスでメモリ リークを観測する原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1061">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="c0ea1-1062">プレゼンス情報を更新するときに、断続的なクラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1062">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="c0ea1-1063">現在のフォルダー検索で断続的な失敗を引き起こす原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1063">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="c0ea1-1064">一部のユーザーが Outlook のクラウド設定を取得しようとするときに、認証エラーが発生する原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1064">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="c0ea1-1065">検索に関するフィードバックのエクスペリエンスで終了する原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1065">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="c0ea1-1066">一部の AutoDiscover の応答を処理するときに、クラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1066">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="c0ea1-1067">プレゼンス情報を更新するときに、断続的なクラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1067">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c0ea1-1068">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1068">PowerPoint</span></span>

- <span data-ttu-id="c0ea1-1069">一部のアドインがグラフの図形に対して予期しないエラーをスローさせる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1069">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="c0ea1-1070">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1070">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="c0ea1-1071">この変更により、PowerPoint ビデオ コントロールのアクセス可能な名前が復元されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1071">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="c0ea1-1072">一部のアニメーションが開始しないことがあるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1072">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="c0ea1-1073">スライドを 1 つのプレゼンテーションから別のプレゼンテーションにコピーすると、重複したマスターが作成される可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1073">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="c0ea1-1074">最新のコメントを含むファイルを、サポートされていないバージョンで開くと黄色の警告が表示されます</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1074">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="c0ea1-1075">信頼性の修正: サード パーティのアドインが PowerPoint のクラッシュを発生させる可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1075">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="c0ea1-1076">PowerPoint の垂直テキスト ボックスで半角カタカナ文字が適切に回転しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1076">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="c0ea1-1077">Project</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1077">Project</span></span>

- <span data-ttu-id="c0ea1-1078">Windows 7 のユーザーが Project Web App および SharePoint サイトからプロジェクトを開くことができるように問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1078">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="c0ea1-1079">読み取り専用のプロジェクトを開いたときに複数のメッセージを取得する可能性があるという問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1079">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="c0ea1-1080">[すべて平準化] コマンドがリソースの割り当て超過を適切に解決しません。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1080">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="c0ea1-1081">タスクの作業がゼロの割り当てがある場合、タスクに完了のマークを付けることができず、常に 99％ で表示される問題。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1081">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="c0ea1-1082">Visio</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1082">Visio</span></span>

- <span data-ttu-id="c0ea1-1083">Visio から SVG へのエクスポートが、さまざまな図形で失敗していました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1083">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="c0ea1-1084">Word</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1084">Word</span></span>

- <span data-ttu-id="c0ea1-1085">この変更により、Word を使ってドキュメントを開くときのパフォーマンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1085">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="c0ea1-1086">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1086">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="c0ea1-1087">Deskjet プリンターに印刷するときに、スケーリングの問題を引き起こす可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1087">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="c0ea1-1088">無限ループになることがあるトラック変更の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1088">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="c0ea1-1089">シャットダウン時にアプリが終了することがあるさまざまな問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1089">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="c0ea1-1090">特定のアドインに関連するクラッシュも修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1090">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c0ea1-1091">Office スイート</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1091">Office Suite</span></span>

- <span data-ttu-id="c0ea1-1092">新元号の名前である “Reiwa” のひらがなと漢字をスペルミスまたは間違った文法として誤って識別していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1092">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="c0ea1-1093">SharePoint 2016 に保存されているファイルを共有しようとするときに、"申し訳ございません。何かがこのファイルの共有を妨げています。" というメッセージが表示される原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1093">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="c0ea1-1094">PowerPoint での共同編集とオフライン編集の両方を含むセッションでデータの損失を引き起こす可能性のある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1094">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="c0ea1-1095">これは、ユーザーがファイルを開くときに発生する可能性のあるクラッシュの修正プログラムです。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1095">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="c0ea1-1096">PowerPoint ユーザーがオンライン プレゼンテーションを行おうとするときに、エラーが発生しないようにします。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1096">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="c0ea1-1097">同期エンジンでバックアップされた Sharepoint ファイルに '保存済み' と表示されますが、場合によっては実際に変更が保存されないため、データを損失することになります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1097">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="c0ea1-1098">ユーザーが Word、Excel、および PowerPoint のドキュメントを保存できなくなることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1098">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="c0ea1-1099">この問題は、[保存] アイコンをクリックしたり Ctrl キーを押しながら S キーを押したりした後に、新しいファイルを作成して [ダイアログで保存] オプションを表示するユーザーに影響を与えます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1099">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="c0ea1-1100">すべてのアプリのリボンで、図形の挿入ギャラリーが表示されるまでに約 4 秒かかるという Win7 のパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1100">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="c0ea1-1101">Backstage の Info Place のスラブにアクセシビリティ情報が表示されていないというバグを修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1101">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="c0ea1-1102">レジストリ整合性に関する Office 更新プロセスの信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1102">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="c0ea1-1103">Office の更新プログラムが、意図したソース (ローカル共有、ネットワーク共有、構成マネージャー
で提供される場所など) からではなく、予期せずに Office CDN からファイルをダウンロードする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1103">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="c0ea1-1104">Office の更新メッセージが、異なる言語で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1104">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="c0ea1-1105">今後、Office の更新メッセージは Windows の表示言語と一致します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1105">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="c0ea1-1106">ユーザーが管理者ではなく、システム アカウントにネットワーク接続が確立されていない場合に、更新プログラムが適用されない問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1106">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="c0ea1-1107">特定の状況で、更新後に Office ショートカットが消えてしまう場合があります。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1107">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="c0ea1-1108">この更新プログラムにより、Office ショートカットを公開するときの信頼性が向上します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1108">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="c0ea1-1109">従量制課金ネットワークで更新プログラムが予期せずブロックされる可能性があるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1109">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="c0ea1-1110">ODT と GPO の更新期限設定で、相対期限の設定後、初回のみしか機能しないバスが修正されました。修正により、2 回目以降の更新プログラムで相対期限を使用きるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1110">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="c0ea1-1111">以前に中断された可能性のあるダウンロードを再開することにより、Office の更新プログラムをダウンロードするときの信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1111">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="c0ea1-1112">サード パーティ製プラグインのテキスト ボックスと図形の自動調整に関連する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1112">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="c0ea1-1113">大きなツリー ビューがクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1113">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="c0ea1-1114">Office ユーザーのセキュリティを保護するために、Microsoft Office の更新プログラムは SHA-2 アルゴリズムのみを使用して署名されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1114">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1902-january-14"></a><span data-ttu-id="c0ea1-1116">バージョン 1902: 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1116">Version 1902: January 14</span></span>
<span data-ttu-id="c0ea1-1117">*バージョン 1902 (ビルド 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1117">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="c0ea1-1118">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1118">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="c0ea1-1120">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1120">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c0ea1-1121">Excel</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1121">Excel</span></span>

- <span data-ttu-id="c0ea1-1122">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1122">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="c0ea1-1123">Outlook</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1123">Outlook</span></span>

- <span data-ttu-id="c0ea1-1124">ユーザーが暗号化されたメールを送信しようとするときに、"暗号化アルゴリズムがサポートされていません" というエラーを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1124">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c0ea1-1125">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1125">PowerPoint</span></span>

- <span data-ttu-id="c0ea1-1126">最新のコメントを含むファイルを、サポートされていないバージョンで開くと黄色の警告が表示されます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1126">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="c0ea1-1127">Word</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1127">Word</span></span>

- <span data-ttu-id="c0ea1-1128">この変更により、Word を使ってドキュメントを開くときのパフォーマンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1128">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1808-january-14"></a><span data-ttu-id="c0ea1-1130">バージョン 1808: 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1130">Version 1808: January 14</span></span>
<span data-ttu-id="c0ea1-1131">*バージョン 1808 (ビルド 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1131">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="c0ea1-1132">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1132">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

> [!NOTE]
> <span data-ttu-id="c0ea1-1134">Office の使用で問題がある場合は、[Microsoft の回答フォーラム](https://answers.microsoft.com/)に関するページまたは「[Microsoft Tech Community](https://techcommunity.microsoft.com/)」に質問を投稿するか、[サポート](https://support.microsoft.com/contactus)に問い合わせてサポートを受けることができます。</span><span class="sxs-lookup"><span data-stu-id="c0ea1-1134">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (管理センターのメタデータのコンテンツを変更しないでください。開始)
[//]: # (|Win32|DC|Production| |16.0.12527.21236|version-2002-october-13|)
[//]: # (|Win32|DC|Production| |16.0.12527.21104|version-2002-september-08|)
[//]: # (|Win32|DC|Production| |16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|DC|Production| |16.0.12527.20880|バージョン-2002-7 月-14|)
[//]: # (管理センターのメタデータのコンテンツ エンドを変更しないでください)
