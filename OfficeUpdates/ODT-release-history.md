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
ms.openlocfilehash: 65dbad6110d38fd98fb7b6df94c2a54df2f89459
ms.sourcegitcommit: 6570d42ebb04c11b9aa40dac7825ae8da9694e10
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/31/2019
ms.locfileid: "37902403"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="1c23e-103">Office 展開ツールのリリース履歴</span><span class="sxs-lookup"><span data-stu-id="1c23e-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="1c23e-104">Office 展開ツール (ODT) はコマンドライン ツールです。これを使用すると、Office 365 ProPlus など、Click-to-Run バージョンの Office をクライアント コンピューターにダウンロードして展開することができます。</span><span class="sxs-lookup"><span data-stu-id="1c23e-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Office 365 ProPlus, to your client computers.</span></span> 


<span data-ttu-id="1c23e-105">ODT により、Office インストール環境をより詳細に制御できるようになります。</span><span class="sxs-lookup"><span data-stu-id="1c23e-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="1c23e-106">具体的には、インストールする製品や言語の種類、それらの製品の更新方法、インストール操作をユーザーに表示するかどうかを制御できます。</span><span class="sxs-lookup"><span data-stu-id="1c23e-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="1c23e-107">ODT の使用方法については、[Office 展開ツールの概要](https://docs.microsoft.com/ja-JP/deployoffice/overview-of-the-office-2016-deployment-tool)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="1c23e-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/ja-JP/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="1c23e-108">**サポートされるオペレーティング システム**: Windows 10、Windows 7、Windows 8、Windows 8.1、Windows Server 2008 R2、Windows Server 2012、Windows Server 2012 R2</span><span class="sxs-lookup"><span data-stu-id="1c23e-108">**Supported Operating System**: Windows 10, Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, Windows Server 2012 R2</span></span> 
 
 <span data-ttu-id="1c23e-109">**インストール方法**: 自己解凍実行ファイルをダウンロードして実行します。このファイルには、Office 展開ツールの実行可能ファイル (setup.exe) およびサンプル構成ファイル (configuration.xml) が含まれています。</span><span class="sxs-lookup"><span data-stu-id="1c23e-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="1c23e-110">Office 展開ツールのダウンロード</span><span class="sxs-lookup"><span data-stu-id="1c23e-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="october-31-2019"></a><span data-ttu-id="1c23e-111">2019 年 10 月 31 日</span><span class="sxs-lookup"><span data-stu-id="1c23e-111">October 31, 2019</span></span>

<span data-ttu-id="1c23e-112">バージョン 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="1c23e-112">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="1c23e-113">問題を修正して、Skype for Business Basic 2019 による 2019 の永続的な大企業向けボリューム ライセンスの製品のインストールができるようにします</span><span class="sxs-lookup"><span data-stu-id="1c23e-113">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="1c23e-114">プロキシを使用すると、特定の状況で ODT ダウンロード モードの予期しない失敗が引き起こされるという問題を修正します</span><span class="sxs-lookup"><span data-stu-id="1c23e-114">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="1c23e-115">ODT ダウンロード モードで、ポート 80 以外のポートを使用して HTTP 経由でのダウンロードをできるようにする新機能</span><span class="sxs-lookup"><span data-stu-id="1c23e-115">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="1c23e-116">2019 年 7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="1c23e-116">July 10, 2019</span></span>

<span data-ttu-id="1c23e-117">バージョン 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="1c23e-117">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="1c23e-118">Office 2019 と共にインストールされる次の製品のサポートが追加されました。Access Runtime、Skype for Business Basic</span><span class="sxs-lookup"><span data-stu-id="1c23e-118">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="1c23e-119">MSI からアップグレードされる場合のスタンドアロン製品の条件付きインストールのサポートが追加されました。</span><span class="sxs-lookup"><span data-stu-id="1c23e-119">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="1c23e-120">2019 年 4 月 23 日</span><span class="sxs-lookup"><span data-stu-id="1c23e-120">April 23, 2019</span></span>

<span data-ttu-id="1c23e-121">バージョン 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="1c23e-121">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="1c23e-122">関連するレジストリ設定をクリーンアップするように RemoveMSI=True のバグを修正しました。</span><span class="sxs-lookup"><span data-stu-id="1c23e-122">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="1c23e-123">予期しない障害 (E_UNEXPECTED) の追加情報を提供するようにエラー コードを更新しました。</span><span class="sxs-lookup"><span data-stu-id="1c23e-123">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="1c23e-124">2019 年 4 月 16 日</span><span class="sxs-lookup"><span data-stu-id="1c23e-124">April 16 2019</span></span>

<span data-ttu-id="1c23e-125">バージョン 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="1c23e-125">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="1c23e-126">新しい MigrateArch 属性で 32 ビット C2R から 64 ビット C2R へのアップグレードをサポート。</span><span class="sxs-lookup"><span data-stu-id="1c23e-126">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="1c23e-127">Web 上の場所 (http および https) に保存されている構成 XML ファイルへのアクセスを可能にする /configure のロジックを更新しました。</span><span class="sxs-lookup"><span data-stu-id="1c23e-127">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="1c23e-128">新しい属性 MatchInstalled が追加されました。これにより ODT では、製品や言語を追加するときに既存のバージョンをマッチングできます。</span><span class="sxs-lookup"><span data-stu-id="1c23e-128">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="1c23e-129">2019 年 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="1c23e-129">March 13, 2019</span></span>

<span data-ttu-id="1c23e-130">バージョン 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="1c23e-130">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="1c23e-131">アップグレードと移行のシナリオの改善。</span><span class="sxs-lookup"><span data-stu-id="1c23e-131">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="1c23e-132">2019 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="1c23e-132">January 14, 2019</span></span>

<span data-ttu-id="1c23e-133">バージョン 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="1c23e-133">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="1c23e-134">展開構成用のロギングとテレメトリの改善。</span><span class="sxs-lookup"><span data-stu-id="1c23e-134">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="1c23e-135">関連リンク</span><span class="sxs-lookup"><span data-stu-id="1c23e-135">Related links</span></span>

[<span data-ttu-id="1c23e-136">ODT ダウンロード センター</span><span class="sxs-lookup"><span data-stu-id="1c23e-136">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)