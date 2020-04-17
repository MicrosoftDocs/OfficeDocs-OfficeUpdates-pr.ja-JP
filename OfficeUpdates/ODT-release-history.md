---
title: Office 展開ツール (ODT) のリリース履歴
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: IT プロフェッショナルに、Office 展開ツール (ODT) のリリース履歴を提供します
ms.openlocfilehash: b9cb0e347e785f14c1dd23ae9cfbcaa327ce4873
ms.sourcegitcommit: fab2c3d8c42b3e2fde49853068c834f96ccbf105
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/15/2020
ms.locfileid: "43521215"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="ef26c-103">Office 展開ツールのリリース履歴</span><span class="sxs-lookup"><span data-stu-id="ef26c-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="ef26c-104">Office 展開ツール (ODT) はコマンドライン ツールです。これを使用すると、Office 365 ProPlus など、Click-to-Run バージョンの Office をクライアント コンピューターにダウンロードして展開することができます。</span><span class="sxs-lookup"><span data-stu-id="ef26c-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Office 365 ProPlus, to your client computers.</span></span> 


<span data-ttu-id="ef26c-105">ODT により、Office インストール環境をより詳細に制御できるようになります。</span><span class="sxs-lookup"><span data-stu-id="ef26c-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="ef26c-106">具体的には、インストールする製品や言語の種類、それらの製品の更新方法、インストール操作をユーザーに表示するかどうかを制御できます。</span><span class="sxs-lookup"><span data-stu-id="ef26c-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="ef26c-107">ODT の使用方法については、[Office 展開ツールの概要](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ef26c-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="ef26c-108">**サポートされるオペレーティング システム**: Windows 10、Windows 7、Windows 8、Windows 8.1、Windows Server 2008 R2、Windows Server 2012、Windows Server 2012 R2</span><span class="sxs-lookup"><span data-stu-id="ef26c-108">**Supported Operating System**: Windows 10, Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, Windows Server 2012 R2</span></span> 
 
 <span data-ttu-id="ef26c-109">**インストール方法**: 自己解凍実行ファイルをダウンロードして実行します。このファイルには、Office 展開ツールの実行可能ファイル (setup.exe) およびサンプル構成ファイル (configuration.xml) が含まれています。</span><span class="sxs-lookup"><span data-stu-id="ef26c-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="ef26c-110">Office 展開ツールのダウンロード</span><span class="sxs-lookup"><span data-stu-id="ef26c-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="april-15-2020"></a><span data-ttu-id="ef26c-111">2020 年 4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="ef26c-111">April 15, 2020</span></span>

<span data-ttu-id="ef26c-112">バージョン 16.0.12624.20320 (バージョン 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="ef26c-112">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="ef26c-113">Windows 7 固有のサポート終了 Office バージョンを追加する</span><span class="sxs-lookup"><span data-stu-id="ef26c-113">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="ef26c-114">カスタマイズ設定が期待どおりに適用されない場合がある問題を修正します</span><span class="sxs-lookup"><span data-stu-id="ef26c-114">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="ef26c-115">不要な .cat ファイルが予期せずダウンロードされることがある問題を修正します</span><span class="sxs-lookup"><span data-stu-id="ef26c-115">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="ef26c-116">2020年 1 月 16 日</span><span class="sxs-lookup"><span data-stu-id="ef26c-116">January 16, 2020</span></span>

<span data-ttu-id="ef26c-117">バージョン 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="ef26c-117">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="ef26c-118">複数の言語がインストールされている場合に Office のインストール UI が正しい言語で表示されないことがある問題を修正します</span><span class="sxs-lookup"><span data-stu-id="ef26c-118">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="ef26c-119">特定の校正ツール パッケージがインストールされていると、Office のインストールが予期せず失敗することがある問題を修正します</span><span class="sxs-lookup"><span data-stu-id="ef26c-119">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="ef26c-120">[Bing 機能での Microsoft Search](https://go.microsoft.com/fwlink/p/?linkid=2109345) の初期展開をオプションで制御するサポートを追加します</span><span class="sxs-lookup"><span data-stu-id="ef26c-120">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="ef26c-121">2019 年 10 月 31 日</span><span class="sxs-lookup"><span data-stu-id="ef26c-121">October 31, 2019</span></span>

<span data-ttu-id="ef26c-122">バージョン 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="ef26c-122">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="ef26c-123">問題を修正して、Skype for Business Basic 2019 による 2019 の永続的な大企業向けボリューム ライセンスの製品のインストールができるようにします</span><span class="sxs-lookup"><span data-stu-id="ef26c-123">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="ef26c-124">プロキシを使用すると、特定の状況で ODT ダウンロード モードの予期しない失敗が引き起こされるという問題を修正します</span><span class="sxs-lookup"><span data-stu-id="ef26c-124">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="ef26c-125">ODT ダウンロード モードで、ポート 80 以外のポートを使用して HTTP 経由でのダウンロードをできるようにする新機能</span><span class="sxs-lookup"><span data-stu-id="ef26c-125">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="ef26c-126">2019 年 7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="ef26c-126">July 10, 2019</span></span>

<span data-ttu-id="ef26c-127">バージョン 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="ef26c-127">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="ef26c-128">Office 2019 と共にインストールされる次の製品のサポートが追加されました。Access Runtime、Skype for Business Basic</span><span class="sxs-lookup"><span data-stu-id="ef26c-128">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="ef26c-129">MSI からアップグレードされる場合のスタンドアロン製品の条件付きインストールのサポートが追加されました。</span><span class="sxs-lookup"><span data-stu-id="ef26c-129">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="ef26c-130">2019 年 4 月 23 日</span><span class="sxs-lookup"><span data-stu-id="ef26c-130">April 23, 2019</span></span>

<span data-ttu-id="ef26c-131">バージョン 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="ef26c-131">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="ef26c-132">関連するレジストリ設定をクリーンアップするように RemoveMSI=True のバグを修正しました。</span><span class="sxs-lookup"><span data-stu-id="ef26c-132">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="ef26c-133">予期しない障害 (E_UNEXPECTED) の追加情報を提供するようにエラー コードを更新しました。</span><span class="sxs-lookup"><span data-stu-id="ef26c-133">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="ef26c-134">2019 年 4 月 16 日</span><span class="sxs-lookup"><span data-stu-id="ef26c-134">April 16 2019</span></span>

<span data-ttu-id="ef26c-135">バージョン 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="ef26c-135">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="ef26c-136">新しい MigrateArch 属性で 32 ビット C2R から 64 ビット C2R へのアップグレードをサポート。</span><span class="sxs-lookup"><span data-stu-id="ef26c-136">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="ef26c-137">Web 上の場所 (http および https) に保存されている構成 XML ファイルへのアクセスを可能にする /configure のロジックを更新しました。</span><span class="sxs-lookup"><span data-stu-id="ef26c-137">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="ef26c-138">新しい属性 MatchInstalled が追加されました。これにより ODT では、製品や言語を追加するときに既存のバージョンをマッチングできます。</span><span class="sxs-lookup"><span data-stu-id="ef26c-138">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="ef26c-139">2019 年 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="ef26c-139">March 13, 2019</span></span>

<span data-ttu-id="ef26c-140">バージョン 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="ef26c-140">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="ef26c-141">アップグレードと移行のシナリオの改善。</span><span class="sxs-lookup"><span data-stu-id="ef26c-141">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="ef26c-142">2019 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="ef26c-142">January 14, 2019</span></span>

<span data-ttu-id="ef26c-143">バージョン 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="ef26c-143">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="ef26c-144">展開構成用のロギングとテレメトリの改善。</span><span class="sxs-lookup"><span data-stu-id="ef26c-144">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="ef26c-145">関連リンク</span><span class="sxs-lookup"><span data-stu-id="ef26c-145">Related links</span></span>

[<span data-ttu-id="ef26c-146">ODT ダウンロード センター</span><span class="sxs-lookup"><span data-stu-id="ef26c-146">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)