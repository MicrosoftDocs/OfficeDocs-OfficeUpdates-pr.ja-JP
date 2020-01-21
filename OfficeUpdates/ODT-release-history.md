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
ms.openlocfilehash: fb59993362c4c186518f8472cb0330fa1b1e8d58
ms.sourcegitcommit: f042b25b15960fc4911a7e7d8500dcfd992ee95c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/17/2020
ms.locfileid: "41230065"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="2eb78-103">Office 展開ツールのリリース履歴</span><span class="sxs-lookup"><span data-stu-id="2eb78-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="2eb78-104">Office 展開ツール (ODT) はコマンドライン ツールです。これを使用すると、Office 365 ProPlus など、Click-to-Run バージョンの Office をクライアント コンピューターにダウンロードして展開することができます。</span><span class="sxs-lookup"><span data-stu-id="2eb78-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Office 365 ProPlus, to your client computers.</span></span> 


<span data-ttu-id="2eb78-105">ODT により、Office インストール環境をより詳細に制御できるようになります。</span><span class="sxs-lookup"><span data-stu-id="2eb78-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="2eb78-106">具体的には、インストールする製品や言語の種類、それらの製品の更新方法、インストール操作をユーザーに表示するかどうかを制御できます。</span><span class="sxs-lookup"><span data-stu-id="2eb78-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="2eb78-107">ODT の使用方法については、[Office 展開ツールの概要](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="2eb78-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="2eb78-108">**サポートされるオペレーティング システム**: Windows 10、Windows 7、Windows 8、Windows 8.1、Windows Server 2008 R2、Windows Server 2012、Windows Server 2012 R2</span><span class="sxs-lookup"><span data-stu-id="2eb78-108">**Supported Operating System**: Windows 10, Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, Windows Server 2012 R2</span></span> 
 
 <span data-ttu-id="2eb78-109">**インストール方法**: 自己解凍実行ファイルをダウンロードして実行します。このファイルには、Office 展開ツールの実行可能ファイル (setup.exe) およびサンプル構成ファイル (configuration.xml) が含まれています。</span><span class="sxs-lookup"><span data-stu-id="2eb78-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="2eb78-110">Office 展開ツールのダウンロード</span><span class="sxs-lookup"><span data-stu-id="2eb78-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="january-16-2020"></a><span data-ttu-id="2eb78-111">2020年 1 月 16 日</span><span class="sxs-lookup"><span data-stu-id="2eb78-111">January 16, 2020</span></span>

<span data-ttu-id="2eb78-112">バージョン 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="2eb78-112">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="2eb78-113">複数の言語がインストールされている場合に Office のインストール UI が正しい言語で表示されないことがある問題を修正します</span><span class="sxs-lookup"><span data-stu-id="2eb78-113">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="2eb78-114">特定の校正ツール パッケージがインストールされていると、Office のインストールが予期せず失敗することがある問題を修正します</span><span class="sxs-lookup"><span data-stu-id="2eb78-114">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="2eb78-115">[Bing 機能での Microsoft Search](https://go.microsoft.com/fwlink/p/?linkid=2109345) の初期展開をオプションで制御するサポートを追加します</span><span class="sxs-lookup"><span data-stu-id="2eb78-115">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="2eb78-116">2019 年 10 月 31 日</span><span class="sxs-lookup"><span data-stu-id="2eb78-116">October 31, 2019</span></span>

<span data-ttu-id="2eb78-117">バージョン 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="2eb78-117">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="2eb78-118">問題を修正して、Skype for Business Basic 2019 による 2019 の永続的な大企業向けボリューム ライセンスの製品のインストールができるようにします</span><span class="sxs-lookup"><span data-stu-id="2eb78-118">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="2eb78-119">プロキシを使用すると、特定の状況で ODT ダウンロード モードの予期しない失敗が引き起こされるという問題を修正します</span><span class="sxs-lookup"><span data-stu-id="2eb78-119">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="2eb78-120">ODT ダウンロード モードで、ポート 80 以外のポートを使用して HTTP 経由でのダウンロードをできるようにする新機能</span><span class="sxs-lookup"><span data-stu-id="2eb78-120">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="2eb78-121">2019 年 7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="2eb78-121">July 10, 2019</span></span>

<span data-ttu-id="2eb78-122">バージョン 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="2eb78-122">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="2eb78-123">Office 2019 と共にインストールされる次の製品のサポートが追加されました。Access Runtime、Skype for Business Basic</span><span class="sxs-lookup"><span data-stu-id="2eb78-123">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="2eb78-124">MSI からアップグレードされる場合のスタンドアロン製品の条件付きインストールのサポートが追加されました。</span><span class="sxs-lookup"><span data-stu-id="2eb78-124">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="2eb78-125">2019 年 4 月 23 日</span><span class="sxs-lookup"><span data-stu-id="2eb78-125">April 23, 2019</span></span>

<span data-ttu-id="2eb78-126">バージョン 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="2eb78-126">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="2eb78-127">関連するレジストリ設定をクリーンアップするように RemoveMSI=True のバグを修正しました。</span><span class="sxs-lookup"><span data-stu-id="2eb78-127">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="2eb78-128">予期しない障害 (E_UNEXPECTED) の追加情報を提供するようにエラー コードを更新しました。</span><span class="sxs-lookup"><span data-stu-id="2eb78-128">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="2eb78-129">2019 年 4 月 16 日</span><span class="sxs-lookup"><span data-stu-id="2eb78-129">April 16 2019</span></span>

<span data-ttu-id="2eb78-130">バージョン 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="2eb78-130">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="2eb78-131">新しい MigrateArch 属性で 32 ビット C2R から 64 ビット C2R へのアップグレードをサポート。</span><span class="sxs-lookup"><span data-stu-id="2eb78-131">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="2eb78-132">Web 上の場所 (http および https) に保存されている構成 XML ファイルへのアクセスを可能にする /configure のロジックを更新しました。</span><span class="sxs-lookup"><span data-stu-id="2eb78-132">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="2eb78-133">新しい属性 MatchInstalled が追加されました。これにより ODT では、製品や言語を追加するときに既存のバージョンをマッチングできます。</span><span class="sxs-lookup"><span data-stu-id="2eb78-133">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="2eb78-134">2019 年 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="2eb78-134">March 13, 2019</span></span>

<span data-ttu-id="2eb78-135">バージョン 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="2eb78-135">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="2eb78-136">アップグレードと移行のシナリオの改善。</span><span class="sxs-lookup"><span data-stu-id="2eb78-136">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="2eb78-137">2019 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2eb78-137">January 14, 2019</span></span>

<span data-ttu-id="2eb78-138">バージョン 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="2eb78-138">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="2eb78-139">展開構成用のロギングとテレメトリの改善。</span><span class="sxs-lookup"><span data-stu-id="2eb78-139">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="2eb78-140">関連リンク</span><span class="sxs-lookup"><span data-stu-id="2eb78-140">Related links</span></span>

[<span data-ttu-id="2eb78-141">ODT ダウンロード センター</span><span class="sxs-lookup"><span data-stu-id="2eb78-141">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)