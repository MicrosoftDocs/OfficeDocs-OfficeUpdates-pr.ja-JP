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
ms.openlocfilehash: b0f53ad140880f7ef173efc544892d56f0658bb1
ms.sourcegitcommit: 917d87752cde322a74251b6d23b12815587d1e51
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/16/2019
ms.locfileid: "36444949"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="84551-103">Office 展開ツールのリリース履歴</span><span class="sxs-lookup"><span data-stu-id="84551-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="84551-104">Office 展開ツール (ODT) はコマンドライン ツールです。これを使用すると、Office 365 ProPlus など、Click-to-Run バージョンの Office をクライアント コンピューターにダウンロードして展開することができます。</span><span class="sxs-lookup"><span data-stu-id="84551-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Office 365 ProPlus, to your client computers.</span></span> 


<span data-ttu-id="84551-105">ODT により、Office インストール環境をより詳細に制御できるようになります。</span><span class="sxs-lookup"><span data-stu-id="84551-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="84551-106">具体的には、インストールする製品や言語の種類、それらの製品の更新方法、インストール操作をユーザーに表示するかどうかを制御できます。</span><span class="sxs-lookup"><span data-stu-id="84551-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="84551-107">ODT の使用方法については、[Office 展開ツールの概要](https://docs.microsoft.com/ja-JP/deployoffice/overview-of-the-office-2016-deployment-tool)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="84551-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/en-us/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="84551-108">**サポートされるオペレーティング システム**: Windows 10、Windows 7、Windows 8、Windows 8.1、Windows Server 2008 R2、Windows Server 2012、Windows Server 2012 R2</span><span class="sxs-lookup"><span data-stu-id="84551-108">The tool runs on Windows 10 , Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, and Windows Server 2012 R2.</span></span> 
 
 <span data-ttu-id="84551-109">**インストール方法**: 自己解凍実行ファイルをダウンロードして実行します。このファイルには、Office 展開ツールの実行可能ファイル (setup.exe) およびサンプル構成ファイル (configuration.xml) が含まれています。</span><span class="sxs-lookup"><span data-stu-id="84551-109">After downloading the file, run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

<span data-ttu-id="84551-110">[Office 展開ツールのダウンロード](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)</span><span class="sxs-lookup"><span data-stu-id="84551-110">Download the [Office Deployment Tool](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117).</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="84551-111">2019 年 7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="84551-111">July 10, 2019</span></span>

<span data-ttu-id="84551-112">バージョン 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="84551-112">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="84551-113">Office 2019 と共にインストールされる次の製品のサポートが追加されました。Access Runtime、Skype for Business Basic</span><span class="sxs-lookup"><span data-stu-id="84551-113">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="84551-114">MSI からアップグレードされる場合のスタンドアロン製品の条件付きインストールのサポートが追加されました。</span><span class="sxs-lookup"><span data-stu-id="84551-114">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="84551-115">2019 年 4 月 23 日</span><span class="sxs-lookup"><span data-stu-id="84551-115">April 23, 2019</span></span>

<span data-ttu-id="84551-116">バージョン 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="84551-116">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="84551-117">関連するレジストリ設定をクリーンアップするように RemoveMSI=True のバグを修正しました。</span><span class="sxs-lookup"><span data-stu-id="84551-117">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="84551-118">予期しない障害 (E_UNEXPECTED) の追加情報を提供するようにエラー コードを更新しました。</span><span class="sxs-lookup"><span data-stu-id="84551-118">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="84551-119">2019 年 4 月 16 日</span><span class="sxs-lookup"><span data-stu-id="84551-119">April 16, 2019</span></span>

<span data-ttu-id="84551-120">バージョン 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="84551-120">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="84551-121">新しい MigrateArch 属性で 32 ビット C2R から 64 ビット C2R へのアップグレードをサポート。</span><span class="sxs-lookup"><span data-stu-id="84551-121">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="84551-122">Web 上の場所 (http および https) に保存されている構成 XML ファイルへのアクセスを可能にする /configure のロジックを更新しました。</span><span class="sxs-lookup"><span data-stu-id="84551-122">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="84551-123">新しい属性 MatchInstalled が追加されました。これにより ODT では、製品や言語を追加するときに既存のバージョンをマッチングできます。</span><span class="sxs-lookup"><span data-stu-id="84551-123">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="84551-124">2019 年 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="84551-124">March 13, 2019</span></span>

<span data-ttu-id="84551-125">バージョン 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="84551-125">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="84551-126">アップグレードと移行のシナリオの改善。</span><span class="sxs-lookup"><span data-stu-id="84551-126">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="84551-127">2019 年 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="84551-127">January 14, 2019</span></span>

<span data-ttu-id="84551-128">バージョン 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="84551-128">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="84551-129">展開構成用のロギングとテレメトリの改善。</span><span class="sxs-lookup"><span data-stu-id="84551-129">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="84551-130">関連リンク</span><span class="sxs-lookup"><span data-stu-id="84551-130">Related links</span></span>

[<span data-ttu-id="84551-131">ODT リリース ノート</span><span class="sxs-lookup"><span data-stu-id="84551-131">ODT Release notes</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)