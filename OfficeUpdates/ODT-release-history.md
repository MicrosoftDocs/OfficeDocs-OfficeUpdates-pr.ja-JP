---
title: Office 展開ツール (ODT) のリリース履歴
ms.author: timda
author: TimDavenport
manager: TimDavenport
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: IT プロフェッショナルに、Office 展開ツール (ODT) のリリース履歴を提供します
ms.openlocfilehash: acc7e37ae203c824c0759eab641491d377073a7f
ms.sourcegitcommit: 0cba381a1439abdc7044a81772609c91998d65f0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 11/12/2020
ms.locfileid: "48999542"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="2c084-103">Office 展開ツールのリリース履歴</span><span class="sxs-lookup"><span data-stu-id="2c084-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="2c084-104">Office 展開ツール (ODT) はコマンドライン ツールです。これを使用すると、Microsoft 365 アプリなどのクイック実行バージョンの Office をクライアント コンピューターにダウンロードして展開することができます。</span><span class="sxs-lookup"><span data-stu-id="2c084-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="2c084-105">ODT により、Office インストール環境をより詳細に制御できるようになります。</span><span class="sxs-lookup"><span data-stu-id="2c084-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="2c084-106">具体的には、インストールする製品や言語の種類、それらの製品の更新方法、インストール操作をユーザーに表示するかどうかを制御できます。</span><span class="sxs-lookup"><span data-stu-id="2c084-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="2c084-107">ODT の使用方法については、[Office 展開ツールの概要](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="2c084-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="2c084-108">**サポートされているオペレーティング システム** : Windows 10、Windows 8.1、Windows Server 2019、Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="2c084-108">**Supported Operating System** : Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="2c084-109">**インストール方法** : 自己解凍実行ファイルをダウンロードして実行します。このファイルには、Office 展開ツールの実行可能ファイル (setupodt.exe) およびサンプル構成ファイル (configuration.xml) が含まれています。</span><span class="sxs-lookup"><span data-stu-id="2c084-109">**Install Instructions** : Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setupodt.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="2c084-110">Office 展開ツールのダウンロード</span><span class="sxs-lookup"><span data-stu-id="2c084-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="november-10-2020"></a><span data-ttu-id="2c084-111">2020年11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="2c084-111">November 10, 2020</span></span>
<span data-ttu-id="2c084-112">バージョン 16.0.13328.20356 (setupODT.exe バージョン 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="2c084-112">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="2c084-113">信頼性と復元の向上</span><span class="sxs-lookup"><span data-stu-id="2c084-113">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="2c084-114">混乱を防ぎ、セットアップエラーをより簡単に診断するために、ODTの名前は規定で setupODT.exe になりました。</span><span class="sxs-lookup"><span data-stu-id="2c084-114">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="2c084-115">2020 年 10 月 29 日</span><span class="sxs-lookup"><span data-stu-id="2c084-115">October 29, 2020</span></span>
<span data-ttu-id="2c084-116">バージョン 16.0.13328.20292 (setup.exe バージョン 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="2c084-116">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="2c084-117">RemoveMSI の使用時に特定の Office 2007 製品が予期せずインストールをブロックすることがある問題が解決されます</span><span class="sxs-lookup"><span data-stu-id="2c084-117">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="2c084-118">2020 年 10 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2c084-118">October 14, 2020</span></span>
<span data-ttu-id="2c084-119">バージョン 16.0.13231.20368 (setup.exe バージョン 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="2c084-119">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="2c084-120">チャネルが指定されていない場合は、すべての製品が既定で月次チャネルを使用します。</span><span class="sxs-lookup"><span data-stu-id="2c084-120">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="2c084-121">他の DLL’s を含むディレクトリから ODT を実行するときのセキュリティが強化されました</span><span class="sxs-lookup"><span data-stu-id="2c084-121">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="2c084-122">信頼性と復元の向上</span><span class="sxs-lookup"><span data-stu-id="2c084-122">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="2c084-123">2020 年 6 月 9 日</span><span class="sxs-lookup"><span data-stu-id="2c084-123">June 9, 2020</span></span>

<span data-ttu-id="2c084-124">バージョン 16.0.12827.20268 (setup.exe バージョン 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="2c084-124">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="2c084-125">チャネルが指定されていない場合は、現在のチャネルが既定のチャネルになります</span><span class="sxs-lookup"><span data-stu-id="2c084-125">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="2c084-126">月次エンタープライズ チャネルのサポートを追加しました</span><span class="sxs-lookup"><span data-stu-id="2c084-126">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="2c084-127">新しいチャネル名のサポートを追加しました</span><span class="sxs-lookup"><span data-stu-id="2c084-127">Added support for new channel names</span></span>
- <span data-ttu-id="2c084-128">使用できない言語リソースがある場合でも、可能な場合はインストールを続行するための追加の復元機能</span><span class="sxs-lookup"><span data-stu-id="2c084-128">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="2c084-129">MSIRemove 機能の拡張と Office 2007 製品の削除</span><span class="sxs-lookup"><span data-stu-id="2c084-129">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="2c084-130">MSIRemove 機能の拡張と Access データベース エンジンの削除</span><span class="sxs-lookup"><span data-stu-id="2c084-130">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="2c084-131">2020 年 4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="2c084-131">April 15, 2020</span></span>

<span data-ttu-id="2c084-132">バージョン 16.0.12624.20320 (バージョン 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="2c084-132">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="2c084-133">Windows 7 固有のサポート終了 Office バージョンを追加する</span><span class="sxs-lookup"><span data-stu-id="2c084-133">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="2c084-134">カスタマイズ設定が期待どおりに適用されない場合がある問題を修正します</span><span class="sxs-lookup"><span data-stu-id="2c084-134">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="2c084-135">不要な .cat ファイルが予期せずダウンロードされることがある問題を修正します</span><span class="sxs-lookup"><span data-stu-id="2c084-135">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="2c084-136">2020年 1 月 16 日</span><span class="sxs-lookup"><span data-stu-id="2c084-136">January 16, 2020</span></span>

<span data-ttu-id="2c084-137">バージョン 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="2c084-137">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="2c084-138">複数の言語がインストールされている場合に Office のインストール UI が正しい言語で表示されないことがある問題を修正します</span><span class="sxs-lookup"><span data-stu-id="2c084-138">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="2c084-139">特定の校正ツール パッケージがインストールされていると、Office のインストールが予期せず失敗することがある問題を修正します</span><span class="sxs-lookup"><span data-stu-id="2c084-139">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="2c084-140">[Bing 機能での Microsoft Search](https://go.microsoft.com/fwlink/p/?linkid=2109345) の初期展開をオプションで制御するサポートを追加します</span><span class="sxs-lookup"><span data-stu-id="2c084-140">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="2c084-141">2019 年 10 月 31 日</span><span class="sxs-lookup"><span data-stu-id="2c084-141">October 31, 2019</span></span>

<span data-ttu-id="2c084-142">バージョン 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="2c084-142">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="2c084-143">問題を修正して、Skype for Business Basic 2019 による 2019 の永続的な大企業向けボリューム ライセンスの製品のインストールができるようにします</span><span class="sxs-lookup"><span data-stu-id="2c084-143">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="2c084-144">プロキシを使用すると、特定の状況で ODT ダウンロード モードの予期しない失敗が引き起こされるという問題を修正します</span><span class="sxs-lookup"><span data-stu-id="2c084-144">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="2c084-145">ODT ダウンロード モードで、ポート 80 以外のポートを使用して HTTP 経由でのダウンロードをできるようにする新機能</span><span class="sxs-lookup"><span data-stu-id="2c084-145">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="2c084-146">2019 年 7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="2c084-146">July 10, 2019</span></span>

<span data-ttu-id="2c084-147">バージョン 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="2c084-147">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="2c084-148">Office 2019 と共にインストールされる次の製品のサポートが追加されました。Access Runtime、Skype for Business Basic</span><span class="sxs-lookup"><span data-stu-id="2c084-148">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="2c084-149">MSI からアップグレードされる場合のスタンドアロン製品の条件付きインストールのサポートが追加されました。</span><span class="sxs-lookup"><span data-stu-id="2c084-149">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="2c084-150">2019 年 4 月 23 日</span><span class="sxs-lookup"><span data-stu-id="2c084-150">April 23, 2019</span></span>

<span data-ttu-id="2c084-151">バージョン 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="2c084-151">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="2c084-152">関連するレジストリ設定をクリーンアップするように RemoveMSI=True のバグを修正しました。</span><span class="sxs-lookup"><span data-stu-id="2c084-152">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="2c084-153">予期しない障害 (E_UNEXPECTED) の追加情報を提供するようにエラー コードを更新しました。</span><span class="sxs-lookup"><span data-stu-id="2c084-153">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="2c084-154">2019 年 4 月 16 日</span><span class="sxs-lookup"><span data-stu-id="2c084-154">April 16 2019</span></span>

<span data-ttu-id="2c084-155">バージョン 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="2c084-155">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="2c084-156">新しい MigrateArch 属性で 32 ビット C2R から 64 ビット C2R へのアップグレードをサポート。</span><span class="sxs-lookup"><span data-stu-id="2c084-156">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="2c084-157">Web 上の場所 (http および https) に保存されている構成 XML ファイルへのアクセスを可能にする /configure のロジックを更新しました。</span><span class="sxs-lookup"><span data-stu-id="2c084-157">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="2c084-158">新しい属性 MatchInstalled が追加されました。これにより ODT では、製品や言語を追加するときに既存のバージョンをマッチングできます。</span><span class="sxs-lookup"><span data-stu-id="2c084-158">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="2c084-159">2019 年 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="2c084-159">March 13, 2019</span></span>

<span data-ttu-id="2c084-160">バージョン 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="2c084-160">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="2c084-161">アップグレードと移行のシナリオの改善。</span><span class="sxs-lookup"><span data-stu-id="2c084-161">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="2c084-162">2019 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2c084-162">January 14, 2019</span></span>

<span data-ttu-id="2c084-163">バージョン 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="2c084-163">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="2c084-164">展開構成用のロギングとテレメトリの改善。</span><span class="sxs-lookup"><span data-stu-id="2c084-164">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="2c084-165">関連リンク</span><span class="sxs-lookup"><span data-stu-id="2c084-165">Related links</span></span>

[<span data-ttu-id="2c084-166">ODT ダウンロード センター</span><span class="sxs-lookup"><span data-stu-id="2c084-166">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)