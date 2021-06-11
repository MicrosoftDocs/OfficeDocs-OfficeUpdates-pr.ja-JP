---
title: 2021 年の半期エンタープライズ チャネル (プレビュー) リリースのリリース ノート
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Microsoft 365 Apps 用の 2021 年の半期チャネル リリース (対象指定) のリリース ノートを IT 担当者に提供します
ms.openlocfilehash: 95bdd111e041dd07689ad84254dde5b95a8efebe
ms.sourcegitcommit: ad3ff8ea83a9930956cbb6f30300b0b57d3ef151
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/09/2021
ms.locfileid: "52852007"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview"></a><span data-ttu-id="e2c6c-103">半期エンタープライズ チャネル (プレビュー) のリリース ノート</span><span class="sxs-lookup"><span data-stu-id="e2c6c-103">Release notes for Semi-Annual Enterprise Channel (Preview)</span></span>

<span data-ttu-id="e2c6c-104">このリリース ノートには、半期エンタープライズ チャネル (プレビュー) の更新プログラムに含まれる新機能と、セキュリティ以外の更新プログラムに関する情報が記載されています。対象となるのは、Microsoft 365 Apps for enterprise、Microsoft 365 Apps for business、および Project と Visio のデスクトップ アプリのサブスクリプション版です。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>


## <a name="version-2102-june-08"></a><span data-ttu-id="e2c6c-105">バージョン 2102: 6月 8 日</span><span class="sxs-lookup"><span data-stu-id="e2c6c-105">Version 2102: June 08</span></span>
<span data-ttu-id="e2c6c-106">*バージョン 2102 (ビルド 13801.20738)*</span><span class="sxs-lookup"><span data-stu-id="e2c6c-106">*Version 2102 (Build 13801.20738)*</span></span>

<span data-ttu-id="e2c6c-107">セキュリティ更新プログラムの一覧は[こちら](microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="e2c6c-107">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="e2c6c-109">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="e2c6c-109">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="e2c6c-110">Excel</span><span class="sxs-lookup"><span data-stu-id="e2c6c-110">Excel</span></span>

- <span data-ttu-id="e2c6c-111">パレート図に表示される余計なパディングが削除され、利用可能なグラフ作成空間が狭くなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-111">We fixed an issue which removes extra padding that appeared on Pareto charts and reduced the available charting space.</span></span>


- <span data-ttu-id="e2c6c-112">一部のユーザーの Excel アドイン一覧に追加のエントリが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-112">Fixed an issue where extra entries appeared in the Excel Add-in list for some users.</span></span>


- <span data-ttu-id="e2c6c-113">一部のユーザーに対して、ステータス バーが準備完了状態を表示しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-113">We fixed an issue that caused the Status Bar to not indicate a Ready state for some users.</span></span>


- <span data-ttu-id="e2c6c-114">Power BI のデータ型を更新すると、ユーザーが一部のデータ型にアクセスできない場合のエラー メッセージを改善し、問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-114">We fixed an issue by improving the error message when refreshing Power BI data types and the user does not have access to some of the data types.</span></span>


- <span data-ttu-id="e2c6c-115">プロパティのオート コンプリートのドロップダウンに表示できるプロパティの数を 256 に増やすことで、問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-115">We fixed an issue by increasing the number of properties that can show in the property AutoComplete drop down to 256 properties.</span></span>


### <a name="outlook"></a><span data-ttu-id="e2c6c-116">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2c6c-116">Outlook</span></span>

- <span data-ttu-id="e2c6c-117">EWS の内部エンドポイントと外部エンドポイントが異なる場合に、内部エンドポイントへの呼び出しに失敗すると、接続エラーが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-117">We fixed an issue that caused users to get connectivity errors when the internal and external EWS endpoints are different and the call to the internal endpoint fails.</span></span>


- <span data-ttu-id="e2c6c-118">メールの再送信時に、送信者のアドレスが LegacyExchangeDN として表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-118">We fixed an issue that caused the sender's address to be displayed as a LegacyExchangeDN when resending an email.</span></span>


- <span data-ttu-id="e2c6c-119">エンドユーザーや管理者が [クラウド] 設定をオンにできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-119">Fixed an issue where end users and administrators were unable to turn on Cloud Settings.</span></span>


- <span data-ttu-id="e2c6c-120">外部ネットワークに接続された Hybrid Azure AD Join マシンで、ZeroConfigExchange が正しく動作しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-120">We fixed an issue that caused ZeroConfigExchange to fail to work properly on Hybrid Azure AD joined machines connected to an external network.</span></span>


- <span data-ttu-id="e2c6c-121">カスタム ドメインのユーザーがメール メッセージにリンクを貼り付ける場合に、アクセス許可に関する警告メッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-121">We fixed an issue that caused users of custom domains to see a warning message about permissions when pasting a link into an email message.</span></span>
</br>

- <span data-ttu-id="e2c6c-122">新しい「会議室​​の検索」機能 (Outlook for Webと同じ機能) を無効にして、従来の「時間の候補」を含む「会議室​​の検索」機能を有効にするレジストリ キーを追加しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-122">We added a registry key that disables the new Room Finder experience (the same experience as in Outlook for Web) and enables the legacy Room Finder with Suggested Times.</span></span>

    <span data-ttu-id="e2c6c-123">レジストリ キー:</span><span class="sxs-lookup"><span data-stu-id="e2c6c-123">Registry Key:</span></span>

    ><span data-ttu-id="e2c6c-124">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span><span class="sxs-lookup"><span data-stu-id="e2c6c-124">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span></span> </br>
    ><span data-ttu-id="e2c6c-125">REG_DWORD “ShowLegacyRoomFinder”</span><span class="sxs-lookup"><span data-stu-id="e2c6c-125">REG_DWORD “ShowLegacyRoomFinder”</span></span></br></br>
    ><span data-ttu-id="e2c6c-126">0 (既定) - ユーザーが [会議室の検索] ボタンをクリックして利用可能な会議室を検索する際、Outlook は会議室の新しい検索機能 “OWA Powered eXperience” を使用します</span><span class="sxs-lookup"><span data-stu-id="e2c6c-126">0 (default) - Outlook uses new Room Finder OWA Powered eXperience when user clicks 'Room Finder' button to search for available rooms</span></span>  </br>
    ><span data-ttu-id="e2c6c-127">1 - Outlook は従来の会議室検索ユーザーインタフェースを使用して、利用可能な会議室を検索します</span><span class="sxs-lookup"><span data-stu-id="e2c6c-127">1 - Outlook uses legacy Room Finder UI to search for available rooms</span></span> </br>


### <a name="powerpoint"></a><span data-ttu-id="e2c6c-128">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2c6c-128">PowerPoint</span></span>

- <span data-ttu-id="e2c6c-129">一元展開をサポートするためにストアをバージョン 1.0.0.2 に更新する場合に発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-129">We fixed an issue where the store is updated to version 1.0.0.2 to support central deployment.</span></span> <span data-ttu-id="e2c6c-130">ユーザーがストアにアクセスするには、PowerPoint バージョン情報を更新する必要があります。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-130">The user will need to update the version info in PowerPoint to access the store.</span></span>


### <a name="project"></a><span data-ttu-id="e2c6c-131">Project</span><span class="sxs-lookup"><span data-stu-id="e2c6c-131">Project</span></span>

- <span data-ttu-id="e2c6c-132">ProjectDate */ProjectDur* 関数を使用するユーザー設定フィールドの式を作成し、2 番目のパラメーターが Date()、Now()、Time() のいずれかの日付と時刻に関する数式である場合に、結果として #ERROR が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-132">Fixed an issue where if you create a custom field formula which uses the ProjectDate */ProjectDur* functions and if the second parameter is the Date(), Now() or Time() date and time functions, then a #ERROR results.</span></span>


- <span data-ttu-id="e2c6c-133">リソース共有元が応答せず、開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-133">Fixed an issue where the resource pool becomes unresponsive and can't be opened.</span></span>


### <a name="visio"></a><span data-ttu-id="e2c6c-134">Visio</span><span class="sxs-lookup"><span data-stu-id="e2c6c-134">Visio</span></span>

- <span data-ttu-id="e2c6c-135">図形の検索で検索キーワードを入力する場合に、検索結果が見つからなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-135">We fixed an issue related to missing results on entering search keywords in shape search.</span></span>


### <a name="word"></a><span data-ttu-id="e2c6c-136">Word</span><span class="sxs-lookup"><span data-stu-id="e2c6c-136">Word</span></span>

- <span data-ttu-id="e2c6c-137">オンライン画像の挿入時にアプリケーションのハングが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-137">Fixed an issue related to unresponsiveness of the application when inserting Online Pictures.</span></span>


- <span data-ttu-id="e2c6c-138">貼り付けたテキストで、コピーと貼り付けのスタイルが同じにならない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-138">We fixed an issue where copy and paste styles may not be same in pasted text.</span></span>


- <span data-ttu-id="e2c6c-139">コンテンツ コントロールで使用できる文字列のサイズ制限がなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-139">We fixed an issue which removes limit on size of strings allowed for content controls.</span></span>


- <span data-ttu-id="e2c6c-140">OLE オブジェクトの編集に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-140">We fixed an issue related to editing OLE object.</span></span>


### <a name="office-suite"></a><span data-ttu-id="e2c6c-141">Office スイート</span><span class="sxs-lookup"><span data-stu-id="e2c6c-141">Office Suite</span></span>

- <span data-ttu-id="e2c6c-142">プレースホルダー ファイルを開く場合の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-142">Fixed an issue when open placeholder files.</span></span> <span data-ttu-id="e2c6c-143">同期し直したファイルを開こうとしても、Office でハングが発生しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-143">Office was non-responsive to open the sync-backed file.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2102-may-11"></a><span data-ttu-id="e2c6c-145">バージョン 2102: 5 月 11 日</span><span class="sxs-lookup"><span data-stu-id="e2c6c-145">Version 2102: May 11</span></span>
<span data-ttu-id="e2c6c-146">*バージョン 2102 (ビルド 13801.20638)*</span><span class="sxs-lookup"><span data-stu-id="e2c6c-146">*Version 2102 (Build 13801.20638)*</span></span>

<span data-ttu-id="e2c6c-147">セキュリティ更新プログラムのリストは次のとおりです: 「[Microsoft Office セキュリティ更新プログラムのリリース ノート](microsoft365-apps-security-updates.md)」</span><span class="sxs-lookup"><span data-stu-id="e2c6c-147">Security updates are listed here: [Release notes for Microsoft Office security updates](microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="e2c6c-149">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="e2c6c-149">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="e2c6c-150">Excel</span><span class="sxs-lookup"><span data-stu-id="e2c6c-150">Excel</span></span>

- <span data-ttu-id="e2c6c-151">Excel の一部のオートメーション アドインの読み込みに失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-151">Fixed an issue where some automation add-ins for Excel unable to load.</span></span>


- <span data-ttu-id="e2c6c-152">アドインを使用するときに、一部の言語で日付の書式が正しく表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-152">We fixed an issue that caused date formatting to be displayed incorrectly on some languages when using Add-ins.</span></span>


- <span data-ttu-id="e2c6c-153">保護されたシートに数式として貼り付けることができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-153">We fixed an issue that was preventing the ability to paste as formulas on a protected sheet.</span></span>


### <a name="outlook"></a><span data-ttu-id="e2c6c-154">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2c6c-154">Outlook</span></span>

- <span data-ttu-id="e2c6c-155">これにより、エンド ユーザーは、作成するすべての会議にオンライン会議を追加するように Outlook を構成できます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-155">This enables end users to configure Outlook to add an online meeting to every meeting they create.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="e2c6c-156">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2c6c-156">PowerPoint</span></span>

- <span data-ttu-id="e2c6c-157">リンクされた図に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-157">We fixed an issue related to linked pictures.</span></span>


### <a name="word"></a><span data-ttu-id="e2c6c-158">Word</span><span class="sxs-lookup"><span data-stu-id="e2c6c-158">Word</span></span>

- <span data-ttu-id="e2c6c-159">リンク内の 2084 番目の文字がエスケープ文字である場合に、他のユーザーがアイテムを送信できないという Wordmail の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-159">Fixed an issue in Wordmail where someone cannot send an item when the 2084th character in a link is an escaped character.</span></span>


### <a name="office-suite"></a><span data-ttu-id="e2c6c-160">Office スイート</span><span class="sxs-lookup"><span data-stu-id="e2c6c-160">Office Suite</span></span>

- <span data-ttu-id="e2c6c-161">GPO によって無効な要求が送信された場合でも Office テンプレートが有効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-161">Fixed an issue where Office templates turned on even with GPO placed disable request.</span></span>


- <span data-ttu-id="e2c6c-162">長い文書の印刷中に Word が予期せず終了する原因になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-162">Fixed an issue that caused Word to close unexpectedly while printing long documents.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2102-april-13"></a><span data-ttu-id="e2c6c-164">バージョン 2102: 4 月 13 日</span><span class="sxs-lookup"><span data-stu-id="e2c6c-164">Version 2102: April 13</span></span>
<span data-ttu-id="e2c6c-165">*バージョン 2102 (ビルド 13801.20506)*</span><span class="sxs-lookup"><span data-stu-id="e2c6c-165">*Version 2102 (Build 13801.20506)*</span></span>

<span data-ttu-id="e2c6c-166">セキュリティ更新プログラムのリストは次のとおりです: 「[Microsoft Office セキュリティ更新プログラムのリリース ノート](microsoft365-apps-security-updates.md)」</span><span class="sxs-lookup"><span data-stu-id="e2c6c-166">Security updates are listed here: [Release notes for Microsoft Office security updates](microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="e2c6c-168">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="e2c6c-168">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="e2c6c-169">Access</span><span class="sxs-lookup"><span data-stu-id="e2c6c-169">Access</span></span>

- <span data-ttu-id="e2c6c-170">SQL Server パススルー クエリを実行すると、"無効なカーソル状態" があったことを示すエラー メッセージが表示されることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-170">Fixed an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="e2c6c-171">Excel</span><span class="sxs-lookup"><span data-stu-id="e2c6c-171">Excel</span></span>

- <span data-ttu-id="e2c6c-172">Office リボンで無効にされたコマンドでアイコンがグレー表示され、ダークグレーの Office テーマのテキストが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-172">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="e2c6c-173">別のシートのテーブルに行を追加すると、予期せずセルにデータ検証が適用される可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-173">We fixed an issue in which data validation could be applied to cells unexpectedly after adding rows to a table on another sheet.</span></span>


- <span data-ttu-id="e2c6c-174">32 ビット版の Excel で DialogSheets show 関数が動作しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="e2c6c-174">We fixed an issue where the DialogSheets show function was not working on 32 bit versions of Excel</span></span>


### <a name="outlook"></a><span data-ttu-id="e2c6c-175">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2c6c-175">Outlook</span></span>

- <span data-ttu-id="e2c6c-176">アイドル状態のときに Outlook がクラッシュする原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-176">We fixed an issue that caused Outlook to crash when idle.</span></span>


- <span data-ttu-id="e2c6c-177">新しいデバイスで Outlook を構成した後、クラウド設定機能のユーザーにカスタマイズされた設定が既定の設定で上書きされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-177">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="e2c6c-178">ユーザーに予想よりも多くの署名が表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-178">We fixed an issue that caused users to see more signatures than expected.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="e2c6c-179">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2c6c-179">PowerPoint</span></span>

- <span data-ttu-id="e2c6c-180">Office リボンで無効にされたコマンドでアイコンがグレー表示され、ダークグレーの Office テーマのテキストが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-180">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="word"></a><span data-ttu-id="e2c6c-181">Word</span><span class="sxs-lookup"><span data-stu-id="e2c6c-181">Word</span></span>

- <span data-ttu-id="e2c6c-182">Office リボンで無効にされたコマンドでアイコンがグレー表示され、ダークグレーの Office テーマのテキストが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-182">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="e2c6c-183">SVG 画像のコピーと貼り付けの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-183">We fixed an issue relating to copy and paste.</span></span>


- <span data-ttu-id="e2c6c-184">非表示の段落の最後に入力すると、アプリケーションがハングする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-184">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


### <a name="office-suite"></a><span data-ttu-id="e2c6c-185">Office スイート</span><span class="sxs-lookup"><span data-stu-id="e2c6c-185">Office Suite</span></span>

- <span data-ttu-id="e2c6c-186">以前に開いたファイルを開いたときに、編集内容が保存されていない状態でファイルが削除されたため、ユーザーがファイルを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-186">Fixed an issue where users are unable to save file when open a previously opened file with edits not saved but now the file has been deleted.</span></span> <span data-ttu-id="e2c6c-187">修正後、ユーザーはファイルが削除されたことを通知するわかりやすいメッセージを受け取ります。したがって、ユーザーは変更を破棄するか、ファイルに名前を付けて保存するかを選択できます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-187">After the fix, users will get a friendly message to inform them that the file is deleted, thus user can choose to discard changes, or SaveAs the file.</span></span>


- <span data-ttu-id="e2c6c-188">SyncBacked ファイルをオフラインで開いてから、ファイルを保存する前にアプリでファイルの名前を変更した際にエラーが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-188">Fixed rename failure issue when open a SyncBacked file offline then rename the file in app before saving file.</span></span>


- <span data-ttu-id="e2c6c-189">GCC ユーザーのディクテーションが無効になっていた問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="e2c6c-189">Fixed an issue where Dictation was disabled for GCC users</span></span>


- <span data-ttu-id="e2c6c-190">Outlook のテキストが透明になり、判読できなくなることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-190">Fixed an issue that could sometimes lead to text in Outlook becoming transparent and thereby not legible.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2102-march-09"></a><span data-ttu-id="e2c6c-192">バージョン 2102: 3 月 9 日</span><span class="sxs-lookup"><span data-stu-id="e2c6c-192">Version 2102: March 09</span></span>
<span data-ttu-id="e2c6c-193">*バージョン 2102 (ビルド 13801.20294)*</span><span class="sxs-lookup"><span data-stu-id="e2c6c-193">*Version 2102 (Build 13801.20294)*</span></span>

<span data-ttu-id="e2c6c-194">セキュリティ更新プログラムのリストは次のとおりです: 「[Microsoft Office セキュリティ更新プログラムのリリース ノート](microsoft365-apps-security-updates.md)」</span><span class="sxs-lookup"><span data-stu-id="e2c6c-194">Security updates are listed here: [Release notes for Microsoft Office security updates](microsoft365-apps-security-updates.md)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="e2c6c-196">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="e2c6c-196">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="e2c6c-197">Excel</span><span class="sxs-lookup"><span data-stu-id="e2c6c-197">Excel</span></span>

- <span data-ttu-id="e2c6c-198">**[描画] の [ツール] ボックスのなげなわと消しゴム:** 描画ツールを使用しているときに、[描画] の [ツール] ボックスでなげなわと消しゴムを使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-198">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="e2c6c-199">[ブログの投稿](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="e2c6c-199">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="e2c6c-200">**PDF に接続:** PDF からデータに接続、インポート、更新します。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-200">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="e2c6c-201">詳細情報</span><span class="sxs-lookup"><span data-stu-id="e2c6c-201">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="e2c6c-202">**数式で使用する変数を作成する:** LET 関数を使用してパフォーマンス、読みやすさ、および構成性を向上させます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-202">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="e2c6c-203">この関数では、新規または既存の数式に名前付き変数を作成することができます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-203">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="e2c6c-204">詳細情報</span><span class="sxs-lookup"><span data-stu-id="e2c6c-204">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="e2c6c-205">[ブログの投稿](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="e2c6c-205">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="e2c6c-206">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-206">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="e2c6c-207">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-207">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="e2c6c-208">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-208">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="e2c6c-209">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-209">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="e2c6c-210">詳細情報</span><span class="sxs-lookup"><span data-stu-id="e2c6c-210">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="e2c6c-211">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="e2c6c-211">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="e2c6c-212">**データ型を使用して Power BI から組織データを取得する:** Power BI からの Excel データ型が Office 365、Microsoft 365、Power BI Pro サービス プランを使用する組織の Insider に展開されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-212">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 / Microsoft 365 and the Power BI Pro service plan.</span></span> <span data-ttu-id="e2c6c-213">必要な情報を入手し、簡単に更新することは、多くの日常のワークフローに欠かせません。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-213">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="e2c6c-214">Excel のデータ型として、Power BI から会社または組織の情報へのアクセスを提供し、スプレッドシートにリンクされた情報を取り込む機能を拡張します。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-214">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="e2c6c-215">詳細情報</span><span class="sxs-lookup"><span data-stu-id="e2c6c-215">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="e2c6c-216">[ブログの投稿](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="e2c6c-216">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="e2c6c-217">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-217">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="e2c6c-218">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-218">No conversion required.</span></span><br /><span data-ttu-id="e2c6c-219">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="e2c6c-219">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="e2c6c-220">**Excel で洗練された Visio 図面を作成する:** ワークシートのデータからフローチャートや組織図などのデータ駆動型の図面を作成。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-220">**Make polished Visio diagrams in Excel:** Create data-driven diagrams like flowcharts or organizational charts from data in a worksheet.</span></span> [<span data-ttu-id="e2c6c-221">詳細情報</span><span class="sxs-lookup"><span data-stu-id="e2c6c-221">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


- <span data-ttu-id="e2c6c-222">**XLM マクロのための AMSI と Office の統合:** AMSI は、アプリケーションが、インストールされているウイルス対策またはセキュリティ ソリューションによって、メモリ バッファーの同期スキャンの要求を実行するときに Windows 10 で使用可能なオープン インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-222">**AMSI integration with Office for XLM macros:** AMSI is an open interface available on Windows 10 for applications to request, at runtime, a synchronous scan of a memory buffer by an installed antivirus or security solution.</span></span> <span data-ttu-id="e2c6c-223">悪意のあるアクティビティが検出されると、Excel はユーザーに通知し、これ以上の損傷を防ぐために、アプリケーション セッションはシャットダウンされます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-223">When malicious activity is detected, the user is notified by Excel, and the application session is shut down to avoid any further damage.</span></span> <span data-ttu-id="e2c6c-224">これにより、攻撃を抑止することができ、デバイスとユーザーの両方を保護できます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-224">This can stop an attack in its tracks, protecting both the device and user.</span></span> <span data-ttu-id="e2c6c-225">詳細は、[ブログの投稿](https://www.microsoft.com/security/blog/2021/03/03/xlm-amsi-new-runtime-defense-against-excel-4-0-macro-malware/) をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-225">See details in [blog post](https://www.microsoft.com/security/blog/2021/03/03/xlm-amsi-new-runtime-defense-against-excel-4-0-macro-malware/).</span></span>

### <a name="outlook"></a><span data-ttu-id="e2c6c-226">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2c6c-226">Outlook</span></span>

- <span data-ttu-id="e2c6c-227">**グループ内のデータを保護:** グループを作成するときに選択する秘密度ラベルがグループ メール、ドキュメント、チーム サイトに適用されます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-227">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>

- <span data-ttu-id="e2c6c-228">**IT 管理者向けのインシデント通知:** Microsoft 365 テナントのグローバル管理者および Office Apps 管理者は、Outlook for Windows の新しい右側のパネル通知により、ユーザーに影響する Outlook および O365 Exchange インシデントについて通知されます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-228">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="e2c6c-229">詳細情報</span><span class="sxs-lookup"><span data-stu-id="e2c6c-229">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- <span data-ttu-id="e2c6c-230">**クイック投票を使用して、Outlook で投票を作成:** 簡単に投票を作成し、票を収集して、メールに結果を表示します。[詳細情報](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="e2c6c-230">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="e2c6c-231">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-231">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="e2c6c-232">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-232">No conversion required.</span></span><br /><span data-ttu-id="e2c6c-233">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="e2c6c-233">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="e2c6c-234">**新しい会議室の検索機能:** これまでと違うさまざまな機能で会議室を検索できます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-234">**New room finder:** Search for conference rooms by different capabilities.</span></span>

- <span data-ttu-id="e2c6c-235">**普段使う言葉で検索:** 「先週の獣医の予約」といったように、普段使うような言葉で検索をフィルタリングして絞り込みます。 </span><span class="sxs-lookup"><span data-stu-id="e2c6c-235">**Search for it the way you'd say it:** Use everyday language like "vet appointment last week" to filter and narrow your search.</span></span>

- <span data-ttu-id="e2c6c-236">**以前の Outlook セッションからアイテムを素早く再開するオプション:** 以前の Outlook セッションからアイテムを素早く再開するためのオプションが追加されました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-236">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span><br /><span data-ttu-id="e2c6c-237">[ブログの投稿](https://insider.office.com/ja-JP/blog/automatically-restore-windows-in-outlook)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="e2c6c-237">See details in [blog post](https://insider.office.com/ja-JP/blog/automatically-restore-windows-in-outlook)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e2c6c-238">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2c6c-238">PowerPoint</span></span>

- <span data-ttu-id="e2c6c-239">**[描画] の [ツール] ボックスのなげなわと消しゴム:** 描画ツールを使用しているときに、[描画] の [ツール] ボックスでなげなわと消しゴムを使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-239">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="e2c6c-240">[ブログの投稿](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="e2c6c-240">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="e2c6c-241">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-241">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="e2c6c-242">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-242">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="e2c6c-243">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-243">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="e2c6c-244">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-244">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="e2c6c-245">詳細情報</span><span class="sxs-lookup"><span data-stu-id="e2c6c-245">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="e2c6c-246">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="e2c6c-246">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="e2c6c-247">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-247">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="e2c6c-248">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-248">No conversion required.</span></span><br /><span data-ttu-id="e2c6c-249">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="e2c6c-249">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="visio"></a><span data-ttu-id="e2c6c-250">Visio</span><span class="sxs-lookup"><span data-stu-id="e2c6c-250">Visio</span></span>

- <span data-ttu-id="e2c6c-251">**新しい Azure ステンシルと図形:** 最新の Azure 図を作成するために、多くのステンシルを追加しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-251">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="e2c6c-252">詳細情報</span><span class="sxs-lookup"><span data-stu-id="e2c6c-252">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a><span data-ttu-id="e2c6c-253">Word</span><span class="sxs-lookup"><span data-stu-id="e2c6c-253">Word</span></span>

- <span data-ttu-id="e2c6c-254">**[描画] の [ツール] ボックスのなげなわと消しゴム:** 描画ツールを使用しているときに、[描画] の [ツール] ボックスでなげなわと消しゴムを使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-254">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="e2c6c-255">[ブログの投稿](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="e2c6c-255">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="e2c6c-256">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-256">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="e2c6c-257">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-257">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="e2c6c-258">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-258">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="e2c6c-259">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-259">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="e2c6c-260">詳細情報</span><span class="sxs-lookup"><span data-stu-id="e2c6c-260">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="e2c6c-261">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="e2c6c-261">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="e2c6c-262">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-262">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="e2c6c-263">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-263">No conversion required.</span></span><br /><span data-ttu-id="e2c6c-264">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="e2c6c-264">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="office-suite"></a><span data-ttu-id="e2c6c-265">Office スイート</span><span class="sxs-lookup"><span data-stu-id="e2c6c-265">Office Suite</span></span>

- <span data-ttu-id="e2c6c-266">**タブ付きのウィンドウ**: アプリの右側にあるタブ UI を使用して、複数のウィンドウ間を切り替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-266">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="e2c6c-267">UI は、2 つ以上のウィンドウが開かれている場合にのみ表示されます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-267">The UI will only be visible when you have 2+ panes open.</span></span><br /><span data-ttu-id="e2c6c-268">[ブログの投稿](https://blog-insider.office.com/2020/02/20/improved-pane-management/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="e2c6c-268">See details in [blog post](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="e2c6c-271">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="e2c6c-271">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="e2c6c-272">Access</span><span class="sxs-lookup"><span data-stu-id="e2c6c-272">Access</span></span>

- <span data-ttu-id="e2c6c-273">Office 以外のアプリケーションから DAO を使用すると、アプリケーションが予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-273">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="e2c6c-274">ユーザーに「無効なカーソル状態」というエラー ダイアログが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-274">We fixed an issue where users were getting an error dialog " Invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="e2c6c-275">Excel</span><span class="sxs-lookup"><span data-stu-id="e2c6c-275">Excel</span></span>

- <span data-ttu-id="e2c6c-276">一部の従来の Excel 4.0 および Excel 5.0 マクロ、および dialogsheets.show への一部の VBA 呼び出しが破損する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-276">We fixed an issue that broke some legacy Excel 4.0 and Excel 5.0 macros as well as some VBA calls to dialogsheets.show.</span></span>


- <span data-ttu-id="e2c6c-277">ピボットテーブルの [計算の種類] メニューの使用時に、Excel が予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-277">Fixed an issue where Excel might close unexpectedly when using the "Show Values As" menu for a PivotTable.</span></span>


- <span data-ttu-id="e2c6c-278">ユーザーが Excel ブックを PDF にエクスポートできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-278">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="e2c6c-279">[リンクされた画像を貼り付け] オプションを使用すると、画像が予想よりも小さくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-279">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="e2c6c-280">.xls または .xlt 形式で保存するときに、一部のピボットテーブル形式でブックが破損する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-280">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


- <span data-ttu-id="e2c6c-281">Excel 4.0 マクロを含む Excel アドイン ファイルを開くときに、確認メッセージを表示せずにマクロが無効のままになる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-281">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="e2c6c-282">Excel によってファイルの新しいバージョンが使用可能であることを示すメッセージバーが誤って表示され、ブックのコピーに変更内容を保存するか、変更内容を破棄するように強制する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-282">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="e2c6c-283">共同編集時に、一部のユーザーに対して、新しいバージョンのファイルを通知するメッセージ バーが誤って表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-283">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="e2c6c-284">特定の Windows セキュリティのエクスプロイト保護設定 (SimExec、CallerCheck) を使用している場合に、Excel の起動に失敗したり、予期せず終了したりしてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-284">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="e2c6c-285">グラフでデータ系列を選択した後に Excel が応答を停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-285">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="e2c6c-286">この変更により、数式内にフォントが正しく表示されない問題に対処できます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-286">This change addresses an issue with properly displaying fonts within equations.</span></span>


### <a name="outlook"></a><span data-ttu-id="e2c6c-287">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2c6c-287">Outlook</span></span>

- <span data-ttu-id="e2c6c-288">ユーザーが代理人に編集者権限を付与できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-288">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="e2c6c-289">特定の検索シナリオで Outlook が予期せず終了するという一部のユーザーの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-289">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="e2c6c-290">プロファイルに大きな階層がある共有メールボックスまたは代理メールボックスを持つユーザーがハングする原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-290">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


- <span data-ttu-id="e2c6c-291">件名が空白の場合、一部の自動的に生成されたメールの本文が空で送信される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-291">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="e2c6c-292">一部のユーザーの環境で、Outlook がオフラインの状態で予期せず起動する原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-292">Addressed an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="e2c6c-293">代理人が別のメールボックスで共有フォルダーを開くと、断続的にエラーが表示される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-293">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="e2c6c-294">ユーザーが検索結果を選択したときにアプリケーションが予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-294">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="e2c6c-295">予定表の読み込み中にハングするという一部のお客様に発生した問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-295">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>


- <span data-ttu-id="e2c6c-296">他の出席者が会議を転送すると、会議の元の出席者の一部がキャンセルを受信してしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-296">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="e2c6c-297">新しいグループを作成した後、重複する予定表のグループが表示される原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-297">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="e2c6c-298">改善された共有カレンダーのユーザーが、カレンダーの色を黄色または茶色に設定できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-298">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="e2c6c-299">Outlook を再起動するまで、新しく追加された予定表がナビゲーション ウィンドウに表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-299">We fixed a problem that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


- <span data-ttu-id="e2c6c-300">キャッシュされていない共有の予定表を検索するときに、結果が返されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-300">Addressed an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="e2c6c-301">一部のユーザーがメッセージ ウィンドウを閉じるときにアプリがシャットダウンする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-301">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="e2c6c-302">タスクの進捗レポートを送信するときに、[宛先] フィールドが空白になる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-302">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


- <span data-ttu-id="e2c6c-303">MailItem.BeforeAttachmentAdd イベントの破損原因となった問題が修正されました。 </span><span class="sxs-lookup"><span data-stu-id="e2c6c-303">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="e2c6c-304">特定の検索のシナリオで、Outlook が予期せず終了するという一部のユーザーに発生した問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-304">We fixed an issue that caused some users to experience Outlook closing unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="e2c6c-305">ユーザーが Outlook で検索しているときに、アプリが予期せず閉じることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-305">We fixed an issue that caused the app to sometimes close unexpectedly when users were searching in Outlook.</span></span>


- <span data-ttu-id="e2c6c-306">クラウド設定のユーザーが設定を更新するときにハングする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-306">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>


- <span data-ttu-id="e2c6c-307">ユーザーに保存を求めた後、編集した署名が保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-307">We fixed an issue that caused an edited signature to fail to save after prompting the user to do so.</span></span>


- <span data-ttu-id="e2c6c-308">1 つ以上の署名が構成されているにもかかわらず、ユーザーの署名が署名ドロップダウンに表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-308">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


- <span data-ttu-id="e2c6c-309">ユーザーに対してクラウド設定が既定でオンにならない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-309">We fixed an issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="e2c6c-310">ユーザーの署名への変更が保存できない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-310">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>


- <span data-ttu-id="e2c6c-311">クラウド設定を有効にしているユーザーに対して、Outlook が 2 つ目の空白の署名を作成するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-311">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


- <span data-ttu-id="e2c6c-312">OWA に既定の正しい署名が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-312">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="e2c6c-313">Unicode コンテンツを含む署名が破損するのをユーザーに表示する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-313">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="e2c6c-314">インライン翻訳のユーザーがフィードバックを送信できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-314">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="e2c6c-315">返信または転送時に中国語メッセージのヘッダーが読み取れなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-315">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="e2c6c-316">OFT ファイルとして保存するときに中国語の文字が疑問符に変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-316">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="e2c6c-317">IDataObject 操作 (つまりクリップボードのドラッグやドロップ) で、ユーザーが添付ファイルに対して filetime の付加を無効にできるように、regkey を追加しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-317">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="e2c6c-318">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="e2c6c-318">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span>  <span data-ttu-id="e2c6c-319">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="e2c6c-319">REG_DWORD IncludeFileTimesInDataObject.</span></span>  <span data-ttu-id="e2c6c-320">0 = filetimes は除外されます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-320">0 = filetimes are excluded.</span></span>  <span data-ttu-id="e2c6c-321">1 = (既定) filetimes が含まれます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-321">1 = (default) filetimes are included.</span></span>


- <span data-ttu-id="e2c6c-322">Azure Information Protection の保護ラベルを使用してメッセージに返信するときに、インライン画像が消えるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-322">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="e2c6c-323">[暗号化のみ] オプションを使用して送信されたメールの暗号化アイコンが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-323">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>


- <span data-ttu-id="e2c6c-324">デジタル署名のオプションのチェックを外した後も、メールがデジタル署名されたものとして送信される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-324">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="e2c6c-325">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2c6c-325">PowerPoint</span></span>

- <span data-ttu-id="e2c6c-326">ドキュメントの保存に失敗した場合にアプリケーションが予期せず終了してしまう可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-326">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="e2c6c-327">Word から PowerPoint への数式のコピー/貼り付けに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-327">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="e2c6c-328">この変更により、特定のジオメトリで図形の結合操作を適用するときの軌跡の塗りつぶしに関する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-328">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


- <span data-ttu-id="e2c6c-329">この変更により、数式内にフォントが正しく表示されないという問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-329">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="e2c6c-330">この変更により、ビデオの読み込み中に発生する可能性のあるエラーの処理に関する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-330">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="e2c6c-331">Slide.Shapes.AddMediaObject2 が従来のビデオ形式 (MPG-1、Mpeg-2) でクラッシュする VBA の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-331">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="e2c6c-332">QAT で [フォントサイズ] コマンドが追加されたのに、更新すると最近定義されたフォント サイズにオート コンプリートするという問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-332">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="e2c6c-333">新たに録音したオーディオを含むスライドを複製した後にファイルを保存するときにエラーが発生してしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-333">We fixed an issue where there is an error when saving the file after duplicating a slide that contains a newly recorded audio.</span></span>


- <span data-ttu-id="e2c6c-334">ユーザーが別のスライドをクリックして表示するまで、Forms コンテンツ アドインが挿入後にレンダリングされない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-334">We fixed an issue where Forms content add-in doesn't render after insertion until user clicks to another slide to make it show.</span></span>


- <span data-ttu-id="e2c6c-335">セキュリティ修正プログラムを適用して、保護ビューで PowerPoint ファイルを開くと、 IRM による保護が無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-335">We fixed an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


- <span data-ttu-id="e2c6c-336">特定のデータ オブジェクト タイプ (E2o) を大量に含むファイルの共同編集が遅くなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-336">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>


- <span data-ttu-id="e2c6c-337">マージ中に IRM 保護されたドキュメントを使用しているときに発生する問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-337">Fix to address a an issue when using IRM/protected documents during a merge error.</span></span>


- <span data-ttu-id="e2c6c-338">これは、PresentationBeforeClose イベントを聞き、イベント ハンドラーの一部として Presentation.Saved プロパティをチェックするアドインがある場合、ドキュメントを閉じるときに保存プロンプトがループで表示される問題の修正です。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-338">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


- <span data-ttu-id="e2c6c-339">ドキュメントの修復操作の後であっても、一部の破損した PowerPoint ファイルを正常に開くことができないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-339">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="e2c6c-340">場合によって、デザイン アイデアを選択するとプレゼンテーションのデータ分類ラベルが削除される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-340">Addresses an issue where selecting a Design Idea removes the presentation's Data Classification Label, in certain cases.</span></span>


### <a name="project"></a><span data-ttu-id="e2c6c-341">Project</span><span class="sxs-lookup"><span data-stu-id="e2c6c-341">Project</span></span>

- <span data-ttu-id="e2c6c-342">プロジェクトを PWA からローカル mpp ファイルに保存すると、ユーザーが実際に変更していないデータに対して ProjectBeforeTaskChangeEvent が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-342">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="e2c6c-343">タスクフォームタイプビュー内でラグが変更された場合、ProjectBeforeTaskChagne イベントの NewVal に正しい値がない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-343">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="e2c6c-344">イベント コードの実行中に、[タスク フォーム] ビューから変更を加えようとするときに、[OK] ボタンをクリックしても変更が反映されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-344">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="e2c6c-345">リソースの配分状況が特定の方法で指定されているファイルを開くと、Project が予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-345">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="e2c6c-346">ロードの特定の部分でプロジェクト ファイルに問題がある場合に、特定のプロジェクトを開くことができるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-346">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


- <span data-ttu-id="e2c6c-347">チーム プランナー ビューのタスクに枠が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-347">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="e2c6c-348">チーム プランナー ビューのタスクでドラッグ アンド ドロップが機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-348">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="e2c6c-349">コスト型リソースがマイルストーン タスクに割り当てられたとき、基準コストが正しくロールアップされないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-349">Fixed an issue where when a cost resource was assigned to a milestone task, baseline cost didn't rollup correctly.</span></span>


### <a name="visio"></a><span data-ttu-id="e2c6c-350">Visio</span><span class="sxs-lookup"><span data-stu-id="e2c6c-350">Visio</span></span>

- <span data-ttu-id="e2c6c-351">問題が修正され、ユーザーが Visio for Office 365 のコネクタを使用して、ユーザー設定の Visio ステンシルと組み込みのテンプレートの両方で直線を作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-351">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="e2c6c-352">Word</span><span class="sxs-lookup"><span data-stu-id="e2c6c-352">Word</span></span>

- <span data-ttu-id="e2c6c-353">ドキュメントの保存に失敗した場合にアプリケーションが予期せず終了してしまう可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-353">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="e2c6c-354">Word から PowerPoint への数式のコピー/貼り付けに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-354">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="e2c6c-355">この変更により、ドキュメントを編集するときのカーソルに関する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-355">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="e2c6c-356">3D 効果のあるアイコンと SVG グラフィックに適用される色の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-356">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="e2c6c-357">段落をスキップする可能性があるナレーターの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-357">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="e2c6c-358">リッチ テキスト コンテンツ コントロールの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-358">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="e2c6c-359">スタイル ギャラリー ダイアログの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-359">We fixed an issue with Style Gallery dialog.</span></span>


- <span data-ttu-id="e2c6c-360">共同編集中の競合を解決する際の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-360">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


- <span data-ttu-id="e2c6c-361">文書のスタイルがテンプレートとは別のスタイルに置き換わってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-361">We fixed an issue which document styles are replaced with other styles from the template.</span></span>


- <span data-ttu-id="e2c6c-362">最適化されたゲートが Word に影響を与えるアサート バグを修正します。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-362">Fix an assert bug exposed by optimized gates affecting Word.</span></span>


### <a name="office-suite"></a><span data-ttu-id="e2c6c-363">Office スイート</span><span class="sxs-lookup"><span data-stu-id="e2c6c-363">Office Suite</span></span>

- <span data-ttu-id="e2c6c-364">同期バックからサーバーのみに移行したファイルを保存しようとすると失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-364">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>


- <span data-ttu-id="e2c6c-365">特定のシナリオで、[名前を付けて保存] の実行に失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-365">Fixed an issue where trying to do a SaveAs would fail in certain scenarios.</span></span>


- <span data-ttu-id="e2c6c-366">SaveRequestManagerCam が原因で、エラーが返される代わりにアプリケーションが閉じられる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-366">We fixed an issue where SaveRequestManagerCam was causing the application to close instead of returning an error.</span></span>


- <span data-ttu-id="e2c6c-367">すべての相互依存のコンポーネントを正常に閉じる、ファイルの閉じ順序が修正されました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-367">Fixed the file closing sequence so that all the interdependent components are closed gracefully.</span></span>


- <span data-ttu-id="e2c6c-368">キャッシュからの URL と OneDrive からの URL が一致しない場合に、ファイルが NOT SyncBacked として開かれてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-368">Fixed an issue of file would be opened as NOT SyncBacked when url from cache and url from OneDrive does NOT match.</span></span>


- <span data-ttu-id="e2c6c-369">Skype for Business メッセージのコピー/貼り付けで、「コンテンツの貼り付け時に問題が発生しました」というダイアログが表示されるバグを修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-369">Fixing a bug where copy/paste in Skype for Business messages resulted in a dialog displaying "Something went wrong when pasting your content".</span></span>


- <span data-ttu-id="e2c6c-370">コメントから Excel にテキストをコピーして貼り付けるときにエラーが発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="e2c6c-370">Fixed an issue where an error would occur when copy/paste text from a comment into Excel</span></span>


- <span data-ttu-id="e2c6c-371">数式を含むテキスト内でナレーターを使用するとクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-371">Fix a crash that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="e2c6c-p120">Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-p120">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners. Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="e2c6c-374">新しいバージョンの Office を特定の古いバージョンの Office の上からインストールすると、レジストリ エントリが存在していないために機能が低下してしまう (Power Query を使用できないなど) という問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-374">Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>


- <span data-ttu-id="e2c6c-375">Microsoft 365 エンドポイントのデータ損失防止が、ディスク上の Office ドキュメントを分類できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-375">Fixed an issue where Microsoft 365 Endpoint data loss prevention was unable to classify Office documents on disk.</span></span>


- <span data-ttu-id="e2c6c-376">[図の圧縮] ダイアログで一部のユーザー設定が保持されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-376">We fixed an issue with the Compress Picture dialog not retaining certain user settings.</span></span>


- <span data-ttu-id="e2c6c-377">メディア コントローラーのイベント通知に関連する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-377">Fixes an issue related to media controller event notifications.</span></span>


- <span data-ttu-id="e2c6c-378">メディア プレーヤー エンジンのタイミングに関連する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-378">Fixes an issue related to media player engine timing.</span></span>


- <span data-ttu-id="e2c6c-379">最適化されたバイナリ サイズ。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-379">Optimized binary size.</span></span>


- <span data-ttu-id="e2c6c-380">Anaheim WebView は、Windows 情報保護 (WIP) をまだサポートしていません。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-380">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="e2c6c-381">この修正プログラムを適用すると、Office addin プラットフォームが、WIP が有効な環境でダウンレベルの WebView に戻ります。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-381">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="e2c6c-382">お客様のコンピューター環境に応じて、Edge Spartan WebView または Trident WebView のいずれかになります。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-382">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="e2c6c-383">ダウンレベル WebViews は、両方とも WIP をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-383">Both down level WebViews support WIP.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-february-09"></a><span data-ttu-id="e2c6c-385">バージョン 2008: 2 月 9 日</span><span class="sxs-lookup"><span data-stu-id="e2c6c-385">Version 2008: February 09</span></span>
<span data-ttu-id="e2c6c-386">*バージョン 2008 (ビルド 13127.21216)*</span><span class="sxs-lookup"><span data-stu-id="e2c6c-386">*Version 2008 (Build 13127.21216)*</span></span>

<span data-ttu-id="e2c6c-387">セキュリティ更新プログラムのリストは次のとおりです: 「[Microsoft Office セキュリティ更新プログラムのリリース ノート](microsoft365-apps-security-updates.md)」</span><span class="sxs-lookup"><span data-stu-id="e2c6c-387">Security updates are listed here: [Release notes for Microsoft Office security updates](microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="e2c6c-389">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="e2c6c-389">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="e2c6c-390">Excel</span><span class="sxs-lookup"><span data-stu-id="e2c6c-390">Excel</span></span>

- <span data-ttu-id="e2c6c-391">無効なファイル属性 (作成時刻、修正時刻など) を持つ UNC ファイルを開くと、Excel が予期せず終了してしまう可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-391">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="e2c6c-392">Excel からグラフをコピーして Word または PowerPoint に貼り付けるときに、10 進数と桁区切りの記号の設定を継承しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-392">We fixed an issue where decimal and thousands separators settings would not carry over when copying a chart from Excel and pasting into Word or PowerPoint.</span></span>


- <span data-ttu-id="e2c6c-393">毎回マクロが実行されているとピボットテーブルの範囲の形式を含むマクロを実行するパフォーマンスが悪化する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-393">We fixed an issue where the performance of running a macro involving PivotTable range formatting would get worse each time the macro is run.</span></span>


- <span data-ttu-id="e2c6c-394">シートを別のブックにコピーまたは移動する場合に条件付き書式のルールが破棄される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-394">We fixed an issue where conditional formatting rules were dropped when copying or moving sheets to another workbook.</span></span>


- <span data-ttu-id="e2c6c-395">アプリのスタート画面のブートが無効の場合にユーザーが秘密度ラベルを Excel ファイルに適用できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-395">We fixed an issue where users were unable to apply sensitivity labels to Excel files when the start screen on app boot was disabled.</span></span>


- <span data-ttu-id="e2c6c-396">OneDrive 同期フォルダーからクラウド ファイルを開く場合の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-396">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="e2c6c-397">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2c6c-397">Outlook</span></span>

- <span data-ttu-id="e2c6c-398">添付ファイルを追加または保存するときに Outlook が散発的に機能しなくなる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-398">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="e2c6c-399">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2c6c-399">PowerPoint</span></span>

- <span data-ttu-id="e2c6c-400">QAT で [フォントサイズ] コマンドが追加されたのに、更新すると最近定義されたフォント サイズにオート コンプリートするという問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-400">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="e2c6c-401">‘ ソースの形式を保持する ’ オプションを使用してスライドのコピーまたは貼り付けを行う場合に予期せず新しいスライド マスターを上書きすることがある問題は修正されました</span><span class="sxs-lookup"><span data-stu-id="e2c6c-401">Fixed an issue where copy and paste of a slide with 'keep source formatting' option would sometimes copy over a new slide master unexpectedly</span></span>


### <a name="word"></a><span data-ttu-id="e2c6c-402">Word</span><span class="sxs-lookup"><span data-stu-id="e2c6c-402">Word</span></span>

- <span data-ttu-id="e2c6c-403">Word 文書を開くと、エラー ダイアログが表示されることがある変更履歴の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-403">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="e2c6c-404">OneDrive 同期フォルダーからクラウド ファイルを開く場合の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-404">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="office-suite"></a><span data-ttu-id="e2c6c-405">Office スイート</span><span class="sxs-lookup"><span data-stu-id="e2c6c-405">Office Suite</span></span>

- <span data-ttu-id="e2c6c-406">Office で正常にファイルを開けなくなる問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-406">Fixed an issue that prevented successful open of a file in Office.</span></span>


- <span data-ttu-id="e2c6c-407">書式のコピー/貼り付けを介してコネクタに適用されたスケッチ アウトラインを含むドキュメントが壊れる可能性がある問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-407">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2008-january-12"></a><span data-ttu-id="e2c6c-409">バージョン 2008: 1 月 12 日</span><span class="sxs-lookup"><span data-stu-id="e2c6c-409">Version 2008: January 12</span></span>
<span data-ttu-id="e2c6c-410">*バージョン 2008 (ビルド 13127.21064)*</span><span class="sxs-lookup"><span data-stu-id="e2c6c-410">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="e2c6c-411">セキュリティ更新プログラムのリストは次のとおりです: 「[Microsoft Office セキュリティ更新プログラムのリリース ノート](microsoft365-apps-security-updates.md)」</span><span class="sxs-lookup"><span data-stu-id="e2c6c-411">Security updates are listed here: [Release notes for Microsoft Office security updates](microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="e2c6c-413">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="e2c6c-413">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="e2c6c-414">Excel</span><span class="sxs-lookup"><span data-stu-id="e2c6c-414">Excel</span></span>

- <span data-ttu-id="e2c6c-415">読み取り専用のブックを開いたときに、ピボット テーブルのデータが更新されなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-415">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="e2c6c-416">この変更により、次の問題が修正されます: OneDrive ローカル同期フォルダーからファイルを挿入すると、Excel の [オブジェクトの挿入] に正しいアイコンが表示されない。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-416">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="e2c6c-417">共同編集のときに、新しいバージョンのファイルに関する通知が誤って送信される可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-417">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="e2c6c-418">Overwrite モードで IME を使用するときに、余計な文字を誤って前に進めてしまうという編集に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-418">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="e2c6c-419">リアルタイム データをマルチスレッドの再計算機能と組み合わせて使用するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-419">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="e2c6c-420">特定の Windows セキュリティのエクスプロイト保護設定 (SimExec、CallerCheck) を使用している場合に、Excel の起動に失敗したり、予期せず終了したりしてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-420">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


### <a name="outlook"></a><span data-ttu-id="e2c6c-421">Outlook</span><span class="sxs-lookup"><span data-stu-id="e2c6c-421">Outlook</span></span>

- <span data-ttu-id="e2c6c-422">下書きに保存したときに SmartLinks の書式設定が失われるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-422">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="e2c6c-423">ポリシーを上書きするときに、正当化テキストをカスタマイズする方法をユーザーに提供してしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-423">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="e2c6c-424">OFT ファイルとして保存するときに、中国語の文字が疑問符に変更されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-424">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="e2c6c-425">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e2c6c-425">PowerPoint</span></span>

- <span data-ttu-id="e2c6c-426">Slide.Shapes.AddMediaObject2 が従来のビデオ形式 (.MPG-1、Mpeg-2) で予期せず終了してしまう可能性がある VBA の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-426">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="e2c6c-427">ドキュメントの修復操作の後であっても、一部の破損した PowerPoint ファイルを正常に開くことができないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-427">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="e2c6c-428">Project</span><span class="sxs-lookup"><span data-stu-id="e2c6c-428">Project</span></span>

- <span data-ttu-id="e2c6c-429">リソースの配分状況が特定の方法で指定されている場合に、Project が予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-429">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="e2c6c-430">Skype</span><span class="sxs-lookup"><span data-stu-id="e2c6c-430">Skype</span></span>

- <span data-ttu-id="e2c6c-431">ユーザの TLS-DSK 証明書が期待通りの時間に更新されず、有効期間が 12 時間未満の場合にのみ更新されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-431">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="e2c6c-432">Office にまだライセンスが付与されていない場合、サインイン後に Skype for Business UI が空白で表示されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-432">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="e2c6c-433">Office スイート</span><span class="sxs-lookup"><span data-stu-id="e2c6c-433">Office Suite</span></span>

- <span data-ttu-id="e2c6c-434">この変更により、従来の図面を含むファイルを開くことに関連する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-434">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="e2c6c-435">この変更により、SVG フォールバック プロキシでアクセス違反が発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-435">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

> [!NOTE]
> <span data-ttu-id="e2c6c-438">Office の使用で問題がある場合は、[Microsoft の回答フォーラム](https://answers.microsoft.com/)に関するページまたは「[Microsoft Tech Community](https://techcommunity.microsoft.com/)」に質問を投稿するか、[サポート](https://support.microsoft.com/contactus)に問い合わせてサポートを受けることができます。</span><span class="sxs-lookup"><span data-stu-id="e2c6c-438">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (管理センターのメタデータのコンテンツを変更しないでください。開始)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20738|version-2102-june-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20638|version-2102-may-11|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20506|version-2102-april-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20294|version-2102-march-09|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21216|version-2008-february-09|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21064|version-2008-january-12|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20910|version-2008-december-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20760|version-2008-november-10|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20638|version-2008-october-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20408|version-2008-september-08|)
[//]: # (管理センターのメタデータのコンテンツ エンドを変更しないでください)
