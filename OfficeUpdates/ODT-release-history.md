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
ms.openlocfilehash: 046054dfb781c3cd19ca6505e5ae5f2f362f6a86
ms.sourcegitcommit: 04f3aa30703f4f1cf89721853a7c052fcca2b97f
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/24/2021
ms.locfileid: "51169965"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="f6eab-103">Office 展開ツールのリリース履歴</span><span class="sxs-lookup"><span data-stu-id="f6eab-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="f6eab-104">Office 展開ツール (ODT) はコマンドライン ツールです。これを使用すると、Microsoft 365 アプリなどのクイック実行バージョンの Office をクライアント コンピューターにダウンロードして展開することができます。</span><span class="sxs-lookup"><span data-stu-id="f6eab-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="f6eab-105">ODT により、Office インストール環境をより詳細に制御できるようになります。</span><span class="sxs-lookup"><span data-stu-id="f6eab-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="f6eab-106">具体的には、インストールする製品や言語の種類、それらの製品の更新方法、インストール操作をユーザーに表示するかどうかを制御できます。</span><span class="sxs-lookup"><span data-stu-id="f6eab-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="f6eab-107">ODT の使用方法については、[Office 展開ツールの概要](/deployoffice/overview-of-the-office-2016-deployment-tool)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f6eab-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="f6eab-108">**サポートされているオペレーティング システム**: Windows 10、Windows 8.1、Windows Server 2019、Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="f6eab-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="f6eab-109">**インストール方法**: 自己解凍実行ファイルをダウンロードして実行します。このファイルには、Office 展開ツールの実行可能ファイル (setup.exe) およびサンプル構成ファイル (configuration.xml) が含まれています。</span><span class="sxs-lookup"><span data-stu-id="f6eab-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="f6eab-110">Office 展開ツールのダウンロード</span><span class="sxs-lookup"><span data-stu-id="f6eab-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="march-23-2021"></a><span data-ttu-id="f6eab-111">2021 年 3 月 23 日</span><span class="sxs-lookup"><span data-stu-id="f6eab-111">March 23, 2021</span></span>
<span data-ttu-id="f6eab-112">バージョン 16.0.13801.20360 (setup.exe バージョン 16.0.13801.20340)</span><span class="sxs-lookup"><span data-stu-id="f6eab-112">Version 16.0.13801.20360 (setup.exe version 16.0.13801.20340)</span></span>
- <span data-ttu-id="f6eab-113">今後の Office 製品リリースのサポートに対する変更</span><span class="sxs-lookup"><span data-stu-id="f6eab-113">Changes to support upcoming Office product releases</span></span>
- <span data-ttu-id="f6eab-114">ARM プラットフォームの信頼性の修正</span><span class="sxs-lookup"><span data-stu-id="f6eab-114">Reliability fixes for ARM platforms</span></span>


## <a name="february-25-2021"></a><span data-ttu-id="f6eab-115">2021 年 2 月 25 日</span><span class="sxs-lookup"><span data-stu-id="f6eab-115">February 25, 2021</span></span>
<span data-ttu-id="f6eab-116">バージョン 16.0.13628.20476 (setup.exe バージョン 16.0.13628.20462)</span><span class="sxs-lookup"><span data-stu-id="f6eab-116">Version 16.0.13628.20476 (setup.exe version 16.0.13628.20462)</span></span>
- <span data-ttu-id="f6eab-117">数十の言語を指定する configuration.xml ファイルが検証に失敗する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f6eab-117">Fixed an issue where configuration.xml files specifying several dozen languages was failing to validate</span></span>
- <span data-ttu-id="f6eab-118">MigrateArch シナリオで FORCEAPPSHUTDOWN プロパティが尊重されていなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f6eab-118">Fixed an issue where the FORCEAPPSHUTDOWN property was not being respected in MigrateArch scenarios</span></span>
- <span data-ttu-id="f6eab-119">configuration.xml で 2 つ以上の PIDKEY 属性を指定すると、PIDKey のインストールに失敗する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f6eab-119">Fixed an issue where specifying 2 or more PIDKEY attributes in configuration.xml failed to install the PIDKeys</span></span>



## <a name="february-9-2021"></a><span data-ttu-id="f6eab-120">2021 年 2 月 9 日</span><span class="sxs-lookup"><span data-stu-id="f6eab-120">February 9, 2021</span></span>
<span data-ttu-id="f6eab-121">バージョン 16.0.13628.20274 (setup.exe バージョン 16.0.13628.20246)</span><span class="sxs-lookup"><span data-stu-id="f6eab-121">Version 16.0.13628.20274 (setup.exe version 16.0.13628.20246)</span></span>
- <span data-ttu-id="f6eab-122">Windows 8.0 でサポートされていないインストールについて警告し、防止するための検証を追加しました</span><span class="sxs-lookup"><span data-stu-id="f6eab-122">Added validation to warn about and prevent unsupported installations on Windows 8.0</span></span>
- <span data-ttu-id="f6eab-123">ARM64 デバイスの信頼性の修正</span><span class="sxs-lookup"><span data-stu-id="f6eab-123">Reliability fixes for ARM64 devices</span></span>


## <a name="january-12-2021"></a><span data-ttu-id="f6eab-124">2021 年 1 月 12 日</span><span class="sxs-lookup"><span data-stu-id="f6eab-124">January 12, 2021</span></span>
<span data-ttu-id="f6eab-125">バージョン 16.0.13530.20376 (setup.exe バージョン 16.0.13530.20334)</span><span class="sxs-lookup"><span data-stu-id="f6eab-125">Version 16.0.13530.20376 (setup.exe version 16.0.13530.20334)</span></span>
- <span data-ttu-id="f6eab-126">間違った製品登録や非標準の製品登録により、RemoveMSI 操作が失敗する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f6eab-126">Fixed an issue where corrupted or non-standard product registration could cause RemoveMSI operations to fail</span></span>

## <a name="december-21-2020"></a><span data-ttu-id="f6eab-127">2020 年 12 月 21 日</span><span class="sxs-lookup"><span data-stu-id="f6eab-127">December 21, 2020</span></span>
<span data-ttu-id="f6eab-128">バージョン 16.0.13426.20370 (setup.exe バージョン 16.0.13426.20352)</span><span class="sxs-lookup"><span data-stu-id="f6eab-128">Version 16.0.13426.20370 (setup.exe version 16.0.13426.20352)</span></span>
- <span data-ttu-id="f6eab-129">PerpetualVL2019 チャネルからの ProofingTools のローカル ソース インストールが失敗する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f6eab-129">Fixed an issue where local source installations of ProofingTools from the PerpetualVL2019 channel were failing</span></span>
- <span data-ttu-id="f6eab-130">完全ではない Office 言語の製品を既存のインストールに追加するときに、クイック実行クライアントが自己更新を試行するようにする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f6eab-130">Fixed an issue to ensure that the Click-To-Run client attempts a self-update when adding additional products in non-full Office languages to an existing installation</span></span>


## <a name="december-8-2020"></a><span data-ttu-id="f6eab-131">2020年12 月 8 日</span><span class="sxs-lookup"><span data-stu-id="f6eab-131">December 8, 2020</span></span>
<span data-ttu-id="f6eab-132">バージョン 16.0.13426.20308 (setup.exe バージョン 16.0.13426.20308)</span><span class="sxs-lookup"><span data-stu-id="f6eab-132">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span></span>
- <span data-ttu-id="f6eab-133">デバイスに Perpetual 2019 以外のチャネルから Office 製品がインストールされている場合に、ダウンロード モードが Perpetual 2019 チャネルのダウンロードをブロックする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f6eab-133">Fixed an issue where Download mode was blocking Perpetual 2019 channel downloads if the device had an Office product installed from a non-Perpetual 2019 channel.</span></span>
- <span data-ttu-id="f6eab-134">構成 XML で明示的なバージョンが指定されているダウンロード モードで作成されたローカル ソースに対してアーキテクチャの移行が失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f6eab-134">Fixed an issue where an Architecture Migration would fail against a local source created through Download mode that had specified an explicit Version in the configuration XML.</span></span>


## <a name="november-23-2020"></a><span data-ttu-id="f6eab-135">2020 年 11 月 23 日</span><span class="sxs-lookup"><span data-stu-id="f6eab-135">November 23, 2020</span></span>
<span data-ttu-id="f6eab-136">バージョン 16.0.13328.20420 (setup.exe バージョン 16.0.13328.20420)</span><span class="sxs-lookup"><span data-stu-id="f6eab-136">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="f6eab-137">/ダウンロード モードで校正ツールをダウンロードできなかった問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="f6eab-137">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="f6eab-138">昇格されていないユーザー コンテキストで実行したときに /ダウンロード モードが失敗する問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="f6eab-138">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="f6eab-139">構成 XML にバージョン属性を指定すると、/ダウンロード モードでのダウンロードが不完全になる問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="f6eab-139">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="f6eab-140">抽出時に Office 展開ツールの名前が "setup.exe" にならない問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="f6eab-140">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="f6eab-141">構成 XML にチャネル属性が指定されている際のインストール ソースの優先順位付けに関する問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="f6eab-141">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="f6eab-142">2020 年 11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="f6eab-142">November 10, 2020</span></span>
<span data-ttu-id="f6eab-143">バージョン 16.0.13328.20356 (setupODT.exe バージョン 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="f6eab-143">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="f6eab-144">信頼性と復元の向上</span><span class="sxs-lookup"><span data-stu-id="f6eab-144">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="f6eab-145">混乱を防ぎ、セットアップエラーをより簡単に診断するために、ODTの名前は規定で setupODT.exe になりました。</span><span class="sxs-lookup"><span data-stu-id="f6eab-145">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="f6eab-146">2020 年 10 月 29 日</span><span class="sxs-lookup"><span data-stu-id="f6eab-146">October 29, 2020</span></span>
<span data-ttu-id="f6eab-147">バージョン 16.0.13328.20292 (setup.exe バージョン 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="f6eab-147">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="f6eab-148">RemoveMSI の使用時に特定の Office 2007 製品が予期せずインストールをブロックすることがある問題が解決されます</span><span class="sxs-lookup"><span data-stu-id="f6eab-148">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="f6eab-149">2020 年 10 月 14 日</span><span class="sxs-lookup"><span data-stu-id="f6eab-149">October 14, 2020</span></span>
<span data-ttu-id="f6eab-150">バージョン 16.0.13231.20368 (setup.exe バージョン 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="f6eab-150">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="f6eab-151">チャネルが指定されていない場合は、すべての製品が既定で月次チャネルを使用します。</span><span class="sxs-lookup"><span data-stu-id="f6eab-151">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="f6eab-152">他の DLL’s を含むディレクトリから ODT を実行するときのセキュリティが強化されました</span><span class="sxs-lookup"><span data-stu-id="f6eab-152">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="f6eab-153">信頼性と復元の向上</span><span class="sxs-lookup"><span data-stu-id="f6eab-153">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="f6eab-154">2020 年 6 月 9 日</span><span class="sxs-lookup"><span data-stu-id="f6eab-154">June 9, 2020</span></span>

<span data-ttu-id="f6eab-155">バージョン 16.0.12827.20268 (setup.exe バージョン 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="f6eab-155">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="f6eab-156">チャネルが指定されていない場合は、現在のチャネルが既定のチャネルになります</span><span class="sxs-lookup"><span data-stu-id="f6eab-156">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="f6eab-157">月次エンタープライズ チャネルのサポートを追加しました</span><span class="sxs-lookup"><span data-stu-id="f6eab-157">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="f6eab-158">新しいチャネル名のサポートを追加しました</span><span class="sxs-lookup"><span data-stu-id="f6eab-158">Added support for new channel names</span></span>
- <span data-ttu-id="f6eab-159">使用できない言語リソースがある場合でも、可能な場合はインストールを続行するための追加の復元機能</span><span class="sxs-lookup"><span data-stu-id="f6eab-159">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="f6eab-160">MSIRemove 機能の拡張と Office 2007 製品の削除</span><span class="sxs-lookup"><span data-stu-id="f6eab-160">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="f6eab-161">MSIRemove 機能の拡張と Access データベース エンジンの削除</span><span class="sxs-lookup"><span data-stu-id="f6eab-161">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="f6eab-162">2020 年 4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="f6eab-162">April 15, 2020</span></span>

<span data-ttu-id="f6eab-163">バージョン 16.0.12624.20320 (バージョン 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="f6eab-163">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="f6eab-164">Windows 7 固有のサポート終了 Office バージョンを追加する</span><span class="sxs-lookup"><span data-stu-id="f6eab-164">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="f6eab-165">カスタマイズ設定が期待どおりに適用されない場合がある問題を修正します</span><span class="sxs-lookup"><span data-stu-id="f6eab-165">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="f6eab-166">不要な .cat ファイルが予期せずダウンロードされることがある問題を修正します</span><span class="sxs-lookup"><span data-stu-id="f6eab-166">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="f6eab-167">2020年 1 月 16 日</span><span class="sxs-lookup"><span data-stu-id="f6eab-167">January 16, 2020</span></span>

<span data-ttu-id="f6eab-168">バージョン 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="f6eab-168">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="f6eab-169">複数の言語がインストールされている場合に Office のインストール UI が正しい言語で表示されないことがある問題を修正します</span><span class="sxs-lookup"><span data-stu-id="f6eab-169">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="f6eab-170">特定の校正ツール パッケージがインストールされていると、Office のインストールが予期せず失敗することがある問題を修正します</span><span class="sxs-lookup"><span data-stu-id="f6eab-170">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="f6eab-171">[Bing 機能での Microsoft Search](/deployoffice/microsoft-search-bing) の初期展開をオプションで制御するサポートを追加します</span><span class="sxs-lookup"><span data-stu-id="f6eab-171">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](/deployoffice/microsoft-search-bing)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="f6eab-172">2019 年 10 月 31 日</span><span class="sxs-lookup"><span data-stu-id="f6eab-172">October 31, 2019</span></span>

<span data-ttu-id="f6eab-173">バージョン 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="f6eab-173">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="f6eab-174">問題を修正して、Skype for Business Basic 2019 による 2019 の永続的な大企業向けボリューム ライセンスの製品のインストールができるようにします</span><span class="sxs-lookup"><span data-stu-id="f6eab-174">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="f6eab-175">プロキシを使用すると、特定の状況で ODT ダウンロード モードの予期しない失敗が引き起こされるという問題を修正します</span><span class="sxs-lookup"><span data-stu-id="f6eab-175">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="f6eab-176">ODT ダウンロード モードで、ポート 80 以外のポートを使用して HTTP 経由でのダウンロードをできるようにする新機能</span><span class="sxs-lookup"><span data-stu-id="f6eab-176">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="f6eab-177">2019 年 7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="f6eab-177">July 10, 2019</span></span>

<span data-ttu-id="f6eab-178">バージョン 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="f6eab-178">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="f6eab-179">Office 2019 と共にインストールされる次の製品のサポートが追加されました。Access Runtime、Skype for Business Basic</span><span class="sxs-lookup"><span data-stu-id="f6eab-179">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="f6eab-180">MSI からアップグレードされる場合のスタンドアロン製品の条件付きインストールのサポートが追加されました。</span><span class="sxs-lookup"><span data-stu-id="f6eab-180">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="f6eab-181">2019 年 4 月 23 日</span><span class="sxs-lookup"><span data-stu-id="f6eab-181">April 23, 2019</span></span>

<span data-ttu-id="f6eab-182">バージョン 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="f6eab-182">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="f6eab-183">関連するレジストリ設定をクリーンアップするように RemoveMSI=True のバグを修正しました。</span><span class="sxs-lookup"><span data-stu-id="f6eab-183">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="f6eab-184">予期しない障害 (E_UNEXPECTED) の追加情報を提供するようにエラー コードを更新しました。</span><span class="sxs-lookup"><span data-stu-id="f6eab-184">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="f6eab-185">2019 年 4 月 16 日</span><span class="sxs-lookup"><span data-stu-id="f6eab-185">April 16 2019</span></span>

<span data-ttu-id="f6eab-186">バージョン 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="f6eab-186">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="f6eab-187">新しい MigrateArch 属性で 32 ビット C2R から 64 ビット C2R へのアップグレードをサポート。</span><span class="sxs-lookup"><span data-stu-id="f6eab-187">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="f6eab-188">Web 上の場所 (http および https) に保存されている構成 XML ファイルへのアクセスを可能にする /configure のロジックを更新しました。</span><span class="sxs-lookup"><span data-stu-id="f6eab-188">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="f6eab-189">新しい属性 MatchInstalled が追加されました。これにより ODT では、製品や言語を追加するときに既存のバージョンをマッチングできます。</span><span class="sxs-lookup"><span data-stu-id="f6eab-189">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="f6eab-190">2019 年 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="f6eab-190">March 13, 2019</span></span>

<span data-ttu-id="f6eab-191">バージョン 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="f6eab-191">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="f6eab-192">アップグレードと移行のシナリオの改善。</span><span class="sxs-lookup"><span data-stu-id="f6eab-192">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="f6eab-193">2019 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="f6eab-193">January 14, 2019</span></span>

<span data-ttu-id="f6eab-194">バージョン 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="f6eab-194">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="f6eab-195">展開構成用のロギングとテレメトリの改善。</span><span class="sxs-lookup"><span data-stu-id="f6eab-195">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="f6eab-196">関連リンク</span><span class="sxs-lookup"><span data-stu-id="f6eab-196">Related links</span></span>

[<span data-ttu-id="f6eab-197">ODT ダウンロード センター</span><span class="sxs-lookup"><span data-stu-id="f6eab-197">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)