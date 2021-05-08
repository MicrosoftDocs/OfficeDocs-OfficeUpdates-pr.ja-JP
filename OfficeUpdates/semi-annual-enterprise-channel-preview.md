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
ms.openlocfilehash: 15057ecbf2e351bc294a9937e1548f51a43f7ba6
ms.sourcegitcommit: 596cdb3423140df0324a952157fbc39ebedc12b9
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2021
ms.locfileid: "52278114"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview"></a><span data-ttu-id="d2773-103">半期エンタープライズ チャネル (プレビュー) のリリース ノート</span><span class="sxs-lookup"><span data-stu-id="d2773-103">Release notes for Semi-Annual Enterprise Channel (Preview)</span></span>

<span data-ttu-id="d2773-104">このリリース ノートには、半期エンタープライズ チャネル (プレビュー) の更新プログラムに含まれる新機能と、セキュリティ以外の更新プログラムに関する情報が記載されています。対象となるのは、Microsoft 365 Apps for enterprise、Microsoft 365 Apps for business、および Project と Visio のデスクトップ アプリのサブスクリプション版です。</span><span class="sxs-lookup"><span data-stu-id="d2773-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>


## <a name="version-2102-april-13"></a><span data-ttu-id="d2773-105">バージョン 2102: 4 月 13 日</span><span class="sxs-lookup"><span data-stu-id="d2773-105">Version 2102: April 13</span></span>
<span data-ttu-id="d2773-106">*バージョン 2102 (ビルド 13801.20506)*</span><span class="sxs-lookup"><span data-stu-id="d2773-106">*Version 2102 (Build 13801.20506)*</span></span>

<span data-ttu-id="d2773-107">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="d2773-107">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d2773-109">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d2773-109">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="d2773-110">Access</span><span class="sxs-lookup"><span data-stu-id="d2773-110">Access</span></span>

- <span data-ttu-id="d2773-111">SQL Server パススルー クエリを実行すると、"無効なカーソル状態" があったことを示すエラー メッセージが表示されることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d2773-111">Fixed an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="d2773-112">Excel</span><span class="sxs-lookup"><span data-stu-id="d2773-112">Excel</span></span>

- <span data-ttu-id="d2773-113">Office リボンで無効にされたコマンドでアイコンがグレー表示され、ダークグレーの Office テーマのテキストが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-113">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="d2773-114">別のシートのテーブルに行を追加すると、予期せずセルにデータ検証が適用される可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-114">We fixed an issue in which data validation could be applied to cells unexpectedly after adding rows to a table on another sheet.</span></span>


- <span data-ttu-id="d2773-115">32 ビット版の Excel で DialogSheets show 関数が動作しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="d2773-115">We fixed an issue where the DialogSheets show function was not working on 32 bit versions of Excel</span></span>


### <a name="outlook"></a><span data-ttu-id="d2773-116">Outlook</span><span class="sxs-lookup"><span data-stu-id="d2773-116">Outlook</span></span>

- <span data-ttu-id="d2773-117">アイドル状態のときに Outlook がクラッシュする原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-117">We fixed an issue that caused Outlook to crash when idle.</span></span>


- <span data-ttu-id="d2773-118">新しいデバイスで Outlook を構成した後、クラウド設定機能のユーザーにカスタマイズされた設定が既定の設定で上書きされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-118">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="d2773-119">ユーザーに予想よりも多くの署名が表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-119">We fixed an issue that caused users to see more signatures than expected.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="d2773-120">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d2773-120">PowerPoint</span></span>

- <span data-ttu-id="d2773-121">Office リボンで無効にされたコマンドでアイコンがグレー表示され、ダークグレーの Office テーマのテキストが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-121">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="word"></a><span data-ttu-id="d2773-122">Word</span><span class="sxs-lookup"><span data-stu-id="d2773-122">Word</span></span>

- <span data-ttu-id="d2773-123">Office リボンで無効にされたコマンドでアイコンがグレー表示され、ダークグレーの Office テーマのテキストが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-123">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


- <span data-ttu-id="d2773-124">SVG 画像のコピーと貼り付けの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-124">We fixed an issue relating to copy and paste.</span></span>


- <span data-ttu-id="d2773-125">非表示の段落の最後に入力すると、アプリケーションがハングする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-125">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


### <a name="office-suite"></a><span data-ttu-id="d2773-126">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d2773-126">Office Suite</span></span>

- <span data-ttu-id="d2773-127">以前に開いたファイルを開いたときに、編集内容が保存されていない状態でファイルが削除されたため、ユーザーがファイルを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-127">Fixed an issue where users are unable to save file when open a previously opened file with edits not saved but now the file has been deleted.</span></span> <span data-ttu-id="d2773-128">修正後、ユーザーはファイルが削除されたことを通知するわかりやすいメッセージを受け取ります。したがって、ユーザーは変更を破棄するか、ファイルに名前を付けて保存するかを選択できます。</span><span class="sxs-lookup"><span data-stu-id="d2773-128">After the fix, users will get a friendly message to inform them that the file is deleted, thus user can choose to discard changes, or SaveAs the file.</span></span>


- <span data-ttu-id="d2773-129">SyncBacked ファイルをオフラインで開いてから、ファイルを保存する前にアプリでファイルの名前を変更した際にエラーが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d2773-129">Fixed rename failure issue when open a SyncBacked file offline then rename the file in app before saving file.</span></span>


- <span data-ttu-id="d2773-130">GCC ユーザーのディクテーションが無効になっていた問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="d2773-130">Fixed an issue where Dictation was disabled for GCC users</span></span>


- <span data-ttu-id="d2773-131">Outlook のテキストが透明になり、判読できなくなることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-131">Fixed an issue that could sometimes lead to text in Outlook becoming transparent and thereby not legible.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2102-march-09"></a><span data-ttu-id="d2773-133">バージョン 2102: 3 月 9 日</span><span class="sxs-lookup"><span data-stu-id="d2773-133">Version 2102: March 09</span></span>
<span data-ttu-id="d2773-134">*バージョン 2102 (ビルド 13801.20294)*</span><span class="sxs-lookup"><span data-stu-id="d2773-134">*Version 2102 (Build 13801.20294)*</span></span>

<span data-ttu-id="d2773-135">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="d2773-135">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="d2773-137">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="d2773-137">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="d2773-138">Excel</span><span class="sxs-lookup"><span data-stu-id="d2773-138">Excel</span></span>

- <span data-ttu-id="d2773-139">**[描画] の [ツール] ボックスのなげなわと消しゴム:** 描画ツールを使用しているときに、[描画] の [ツール] ボックスでなげなわと消しゴムを使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d2773-139">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="d2773-140">[ブログの投稿](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="d2773-140">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="d2773-141">**PDF に接続:** PDF からデータに接続、インポート、更新します。</span><span class="sxs-lookup"><span data-stu-id="d2773-141">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="d2773-142">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d2773-142">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="d2773-143">**数式で使用する変数を作成する:** LET 関数を使用してパフォーマンス、読みやすさ、および構成性を向上させます。</span><span class="sxs-lookup"><span data-stu-id="d2773-143">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="d2773-144">この関数では、新規または既存の数式に名前付き変数を作成することができます。</span><span class="sxs-lookup"><span data-stu-id="d2773-144">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="d2773-145">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d2773-145">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="d2773-146">[ブログの投稿](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="d2773-146">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="d2773-147">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="d2773-147">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="d2773-148">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="d2773-148">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="d2773-149">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="d2773-149">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="d2773-150">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="d2773-150">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="d2773-151">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d2773-151">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="d2773-152">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="d2773-152">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="d2773-153">**データ型を使用して Power BI から組織データを取得する:** Power BI からの Excel データ型が Office 365、Microsoft 365、Power BI Pro サービス プランを使用する組織の Insider に展開されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d2773-153">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 / Microsoft 365 and the Power BI Pro service plan.</span></span> <span data-ttu-id="d2773-154">必要な情報を入手し、簡単に更新することは、多くの日常のワークフローに欠かせません。</span><span class="sxs-lookup"><span data-stu-id="d2773-154">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="d2773-155">Excel のデータ型として、Power BI から会社または組織の情報へのアクセスを提供し、スプレッドシートにリンクされた情報を取り込む機能を拡張します。</span><span class="sxs-lookup"><span data-stu-id="d2773-155">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="d2773-156">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d2773-156">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="d2773-157">[ブログの投稿](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="d2773-157">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="d2773-158">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="d2773-158">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="d2773-159">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="d2773-159">No conversion required.</span></span><br /><span data-ttu-id="d2773-160">[ブログの投稿](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="d2773-160">See details in [blog post](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="d2773-161">**Excel で洗練された Visio 図面を作成する:** ワークシートのデータからフローチャートや組織図などのデータ駆動型の図面を作成。</span><span class="sxs-lookup"><span data-stu-id="d2773-161">**Make polished Visio diagrams in Excel:** Create data-driven diagrams like flowcharts or organizational charts from data in a worksheet.</span></span> [<span data-ttu-id="d2773-162">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d2773-162">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a><span data-ttu-id="d2773-163">Outlook</span><span class="sxs-lookup"><span data-stu-id="d2773-163">Outlook</span></span>

- <span data-ttu-id="d2773-164">**グループ内のデータを保護:** グループを作成するときに選択する秘密度ラベルがグループ メール、ドキュメント、チーム サイトに適用されます。</span><span class="sxs-lookup"><span data-stu-id="d2773-164">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>

- <span data-ttu-id="d2773-165">**IT 管理者向けのインシデント通知:** Microsoft 365 テナントのグローバル管理者および Office Apps 管理者は、Outlook for Windows の新しい右側のパネル通知により、ユーザーに影響する Outlook および O365 Exchange インシデントについて通知されます。</span><span class="sxs-lookup"><span data-stu-id="d2773-165">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="d2773-166">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d2773-166">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- <span data-ttu-id="d2773-167">**クイック投票を使用して、Outlook で投票を作成:** 簡単に投票を作成し、票を収集して、メールに結果を表示します。[詳細情報](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="d2773-167">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="d2773-168">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="d2773-168">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="d2773-169">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="d2773-169">No conversion required.</span></span><br /><span data-ttu-id="d2773-170">[ブログの投稿](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="d2773-170">See details in [blog post](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="d2773-171">**新しい会議室の検索機能:** これまでと違うさまざまな機能で会議室を検索できます。</span><span class="sxs-lookup"><span data-stu-id="d2773-171">**New room finder:** Search for conference rooms by different capabilities.</span></span>

- <span data-ttu-id="d2773-172">**普段使う言葉で検索:** 「先週の獣医の予約」といったように、普段使うような言葉で検索をフィルタリングして絞り込みます。 </span><span class="sxs-lookup"><span data-stu-id="d2773-172">**Search for it the way you'd say it:** Use everyday language like "vet appointment last week" to filter and narrow your search.</span></span>

- <span data-ttu-id="d2773-173">**以前の Outlook セッションからアイテムを素早く再開するオプション:** 以前の Outlook セッションからアイテムを素早く再開するためのオプションが追加されました。</span><span class="sxs-lookup"><span data-stu-id="d2773-173">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span><br /><span data-ttu-id="d2773-174">[ブログの投稿](https://insider.office.com/en-us/blog/automatically-restore-windows-in-outlook)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="d2773-174">See details in [blog post](https://insider.office.com/en-us/blog/automatically-restore-windows-in-outlook)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="d2773-175">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d2773-175">PowerPoint</span></span>

- <span data-ttu-id="d2773-176">**[描画] の [ツール] ボックスのなげなわと消しゴム:** 描画ツールを使用しているときに、[描画] の [ツール] ボックスでなげなわと消しゴムを使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d2773-176">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="d2773-177">[ブログの投稿](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="d2773-177">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="d2773-178">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="d2773-178">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="d2773-179">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="d2773-179">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="d2773-180">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="d2773-180">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="d2773-181">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="d2773-181">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="d2773-182">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d2773-182">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="d2773-183">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="d2773-183">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="d2773-184">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="d2773-184">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="d2773-185">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="d2773-185">No conversion required.</span></span><br /><span data-ttu-id="d2773-186">[ブログの投稿](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="d2773-186">See details in [blog post](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="visio"></a><span data-ttu-id="d2773-187">Visio</span><span class="sxs-lookup"><span data-stu-id="d2773-187">Visio</span></span>

- <span data-ttu-id="d2773-188">**新しい Azure ステンシルと図形:** 最新の Azure 図を作成するために、多くのステンシルを追加しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-188">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="d2773-189">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d2773-189">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a><span data-ttu-id="d2773-190">Word</span><span class="sxs-lookup"><span data-stu-id="d2773-190">Word</span></span>

- <span data-ttu-id="d2773-191">**[描画] の [ツール] ボックスのなげなわと消しゴム:** 描画ツールを使用しているときに、[描画] の [ツール] ボックスでなげなわと消しゴムを使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d2773-191">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span><br /><span data-ttu-id="d2773-192">[ブログの投稿](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="d2773-192">See details in [blog post](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)</span></span>

- <span data-ttu-id="d2773-193">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="d2773-193">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="d2773-194">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="d2773-194">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="d2773-195">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="d2773-195">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="d2773-196">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="d2773-196">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="d2773-197">詳細情報</span><span class="sxs-lookup"><span data-stu-id="d2773-197">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="d2773-198">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="d2773-198">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="d2773-199">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="d2773-199">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="d2773-200">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="d2773-200">No conversion required.</span></span><br /><span data-ttu-id="d2773-201">[ブログの投稿](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="d2773-201">See details in [blog post](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="office-suite"></a><span data-ttu-id="d2773-202">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d2773-202">Office Suite</span></span>

- <span data-ttu-id="d2773-203">**タブ付きのウィンドウ**: アプリの右側にあるタブ UI を使用して、複数のウィンドウ間を切り替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d2773-203">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="d2773-204">UI は、2 つ以上のウィンドウが開かれている場合にのみ表示されます。</span><span class="sxs-lookup"><span data-stu-id="d2773-204">The UI will only be visible when you have 2+ panes open.</span></span><br /><span data-ttu-id="d2773-205">[ブログの投稿](https://blog-insider.office.com/2020/02/20/improved-pane-management/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="d2773-205">See details in [blog post](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d2773-208">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d2773-208">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="d2773-209">Access</span><span class="sxs-lookup"><span data-stu-id="d2773-209">Access</span></span>

- <span data-ttu-id="d2773-210">Office 以外のアプリケーションから DAO を使用すると、アプリケーションが予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-210">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="d2773-211">ユーザーに「無効なカーソル状態」というエラー ダイアログが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-211">We fixed an issue where users were getting an error dialog " Invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="d2773-212">Excel</span><span class="sxs-lookup"><span data-stu-id="d2773-212">Excel</span></span>

- <span data-ttu-id="d2773-213">一部の従来の Excel 4.0 および Excel 5.0 マクロ、および dialogsheets.show への一部の VBA 呼び出しが破損する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-213">We fixed an issue that broke some legacy Excel 4.0 and Excel 5.0 macros as well as some VBA calls to dialogsheets.show.</span></span>


- <span data-ttu-id="d2773-214">ピボットテーブルの [計算の種類] メニューの使用時に、Excel が予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-214">Fixed an issue where Excel might close unexpectedly when using the "Show Values As" menu for a PivotTable.</span></span>


- <span data-ttu-id="d2773-215">ユーザーが Excel ブックを PDF にエクスポートできない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-215">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="d2773-216">[リンクされた画像を貼り付け] オプションを使用すると、画像が予想よりも小さくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-216">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="d2773-217">.xls または .xlt 形式で保存するときに、一部のピボットテーブル形式でブックが破損する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-217">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


- <span data-ttu-id="d2773-218">Excel 4.0 マクロを含む Excel アドイン ファイルを開くときに、確認メッセージを表示せずにマクロが無効のままになる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-218">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="d2773-219">Excel によってファイルの新しいバージョンが使用可能であることを示すメッセージバーが誤って表示され、ブックのコピーに変更内容を保存するか、変更内容を破棄するように強制する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d2773-219">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="d2773-220">共同編集時に、一部のユーザーに対して、新しいバージョンのファイルを通知するメッセージ バーが誤って表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-220">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="d2773-221">特定の Windows セキュリティのエクスプロイト保護設定 (SimExec、CallerCheck) を使用している場合に、Excel の起動に失敗したり、予期せず終了したりしてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-221">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="d2773-222">グラフでデータ系列を選択した後に Excel が応答を停止する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-222">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="d2773-223">この変更により、数式内にフォントが正しく表示されない問題に対処できます。</span><span class="sxs-lookup"><span data-stu-id="d2773-223">This change addresses an issue with properly displaying fonts within equations.</span></span>


### <a name="outlook"></a><span data-ttu-id="d2773-224">Outlook</span><span class="sxs-lookup"><span data-stu-id="d2773-224">Outlook</span></span>

- <span data-ttu-id="d2773-225">ユーザーが代理人に編集者権限を付与できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-225">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="d2773-226">特定の検索シナリオで Outlook が予期せず終了するという一部のユーザーの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d2773-226">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="d2773-227">プロファイルに大きな階層がある共有メールボックスまたは代理メールボックスを持つユーザーがハングする原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-227">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


- <span data-ttu-id="d2773-228">件名が空白の場合、一部の自動的に生成されたメールの本文が空で送信される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-228">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="d2773-229">一部のユーザーの環境で、Outlook がオフラインの状態で予期せず起動する原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-229">Addressed an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="d2773-230">代理人が別のメールボックスで共有フォルダーを開くと、断続的にエラーが表示される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-230">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="d2773-231">ユーザーが検索結果を選択したときにアプリケーションが予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-231">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="d2773-232">予定表の読み込み中にハングするという一部のお客様に発生した問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-232">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>


- <span data-ttu-id="d2773-233">他の出席者が会議を転送すると、会議の元の出席者の一部がキャンセルを受信してしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-233">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="d2773-234">新しいグループを作成した後、重複する予定表のグループが表示される原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-234">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="d2773-235">改善された共有カレンダーのユーザーが、カレンダーの色を黄色または茶色に設定できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-235">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="d2773-236">Outlook を再起動するまで、新しく追加された予定表がナビゲーション ウィンドウに表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-236">We fixed a problem that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


- <span data-ttu-id="d2773-237">キャッシュされていない共有の予定表を検索するときに、結果が返されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-237">Addressed an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="d2773-238">一部のユーザーがメッセージ ウィンドウを閉じるときにアプリがシャットダウンする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-238">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="d2773-239">タスクの進捗レポートを送信するときに、[宛先] フィールドが空白になる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d2773-239">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


- <span data-ttu-id="d2773-240">MailItem.BeforeAttachmentAdd イベントの破損原因となった問題が修正されました。 </span><span class="sxs-lookup"><span data-stu-id="d2773-240">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="d2773-241">特定の検索のシナリオで、Outlook が予期せず終了するという一部のユーザーに発生した問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d2773-241">We fixed an issue that caused some users to experience Outlook closing unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="d2773-242">ユーザーが Outlook で検索しているときに、アプリが予期せず閉じることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-242">We fixed an issue that caused the app to sometimes close unexpectedly when users were searching in Outlook.</span></span>


- <span data-ttu-id="d2773-243">クラウド設定のユーザーが設定を更新するときにハングする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-243">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>


- <span data-ttu-id="d2773-244">ユーザーに保存を求めた後、編集した署名が保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-244">We fixed an issue that caused an edited signature to fail to save after prompting the user to do so.</span></span>


- <span data-ttu-id="d2773-245">1 つ以上の署名が構成されているにもかかわらず、ユーザーの署名が署名ドロップダウンに表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d2773-245">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


- <span data-ttu-id="d2773-246">ユーザーに対してクラウド設定が既定でオンにならない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-246">We fixed an issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="d2773-247">ユーザーの署名への変更が保存できない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-247">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>


- <span data-ttu-id="d2773-248">クラウド設定を有効にしているユーザーに対して、Outlook が 2 つ目の空白の署名を作成するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d2773-248">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


- <span data-ttu-id="d2773-249">OWA に既定の正しい署名が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-249">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="d2773-250">Unicode コンテンツを含む署名が破損するのをユーザーに表示する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-250">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="d2773-251">インライン翻訳のユーザーがフィードバックを送信できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-251">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="d2773-252">返信または転送時に中国語メッセージのヘッダーが読み取れなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-252">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="d2773-253">OFT ファイルとして保存するときに中国語の文字が疑問符に変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-253">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="d2773-254">IDataObject 操作 (つまりクリップボードのドラッグやドロップ) で、ユーザーが添付ファイルに対して filetime の付加を無効にできるように、regkey を追加しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-254">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="d2773-255">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="d2773-255">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span>  <span data-ttu-id="d2773-256">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="d2773-256">REG_DWORD IncludeFileTimesInDataObject.</span></span>  <span data-ttu-id="d2773-257">0 = filetimes は除外されます。</span><span class="sxs-lookup"><span data-stu-id="d2773-257">0 = filetimes are excluded.</span></span>  <span data-ttu-id="d2773-258">1 = (既定) filetimes が含まれます。</span><span class="sxs-lookup"><span data-stu-id="d2773-258">1 = (default) filetimes are included.</span></span>


- <span data-ttu-id="d2773-259">Azure Information Protection の保護ラベルを使用してメッセージに返信するときに、インライン画像が消えるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d2773-259">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="d2773-260">[暗号化のみ] オプションを使用して送信されたメールの暗号化アイコンが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-260">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>


- <span data-ttu-id="d2773-261">デジタル署名のオプションのチェックを外した後も、メールがデジタル署名されたものとして送信される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-261">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="d2773-262">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d2773-262">PowerPoint</span></span>

- <span data-ttu-id="d2773-263">ドキュメントの保存に失敗した場合にアプリケーションが予期せず終了してしまう可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-263">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="d2773-264">Word から PowerPoint への数式のコピー/貼り付けに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-264">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="d2773-265">この変更により、特定のジオメトリで図形の結合操作を適用するときの軌跡の塗りつぶしに関する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="d2773-265">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


- <span data-ttu-id="d2773-266">この変更により、数式内にフォントが正しく表示されないという問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="d2773-266">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="d2773-267">この変更により、ビデオの読み込み中に発生する可能性のあるエラーの処理に関する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="d2773-267">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="d2773-268">Slide.Shapes.AddMediaObject2 が従来のビデオ形式 (MPG-1、Mpeg-2) でクラッシュする VBA の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-268">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="d2773-269">QAT で [フォントサイズ] コマンドが追加されたのに、更新すると最近定義されたフォント サイズにオート コンプリートするという問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="d2773-269">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="d2773-270">新たに録音したオーディオを含むスライドを複製した後にファイルを保存するときにエラーが発生してしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-270">We fixed an issue where there is an error when saving the file after duplicating a slide that contains a newly recorded audio.</span></span>


- <span data-ttu-id="d2773-271">ユーザーが別のスライドをクリックして表示するまで、Forms コンテンツ アドインが挿入後にレンダリングされない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-271">We fixed an issue where Forms content add-in doesn't render after insertion until user clicks to another slide to make it show.</span></span>


- <span data-ttu-id="d2773-272">セキュリティ修正プログラムを適用して、保護ビューで PowerPoint ファイルを開くと、 IRM による保護が無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-272">We fixed an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


- <span data-ttu-id="d2773-273">特定のデータ オブジェクト タイプ (E2o) を大量に含むファイルの共同編集が遅くなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-273">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>


- <span data-ttu-id="d2773-274">マージ中に IRM 保護されたドキュメントを使用しているときに発生する問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="d2773-274">Fix to address a an issue when using IRM/protected documents during a merge error.</span></span>


- <span data-ttu-id="d2773-275">これは、PresentationBeforeClose イベントを聞き、イベント ハンドラーの一部として Presentation.Saved プロパティをチェックするアドインがある場合、ドキュメントを閉じるときに保存プロンプトがループで表示される問題の修正です。</span><span class="sxs-lookup"><span data-stu-id="d2773-275">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


- <span data-ttu-id="d2773-276">ドキュメントの修復操作の後であっても、一部の破損した PowerPoint ファイルを正常に開くことができないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d2773-276">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="d2773-277">場合によって、デザイン アイデアを選択するとプレゼンテーションのデータ分類ラベルが削除される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-277">Addresses an issue where selecting a Design Idea removes the presentation's Data Classification Label, in certain cases.</span></span>


### <a name="project"></a><span data-ttu-id="d2773-278">Project</span><span class="sxs-lookup"><span data-stu-id="d2773-278">Project</span></span>

- <span data-ttu-id="d2773-279">プロジェクトを PWA からローカル mpp ファイルに保存すると、ユーザーが実際に変更していないデータに対して ProjectBeforeTaskChangeEvent が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-279">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="d2773-280">タスクフォームタイプビュー内でラグが変更された場合、ProjectBeforeTaskChagne イベントの NewVal に正しい値がない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-280">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="d2773-281">イベント コードの実行中に、[タスク フォーム] ビューから変更を加えようとするときに、[OK] ボタンをクリックしても変更が反映されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-281">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="d2773-282">リソースの配分状況が特定の方法で指定されているファイルを開くと、Project が予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-282">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="d2773-283">ロードの特定の部分でプロジェクト ファイルに問題がある場合に、特定のプロジェクトを開くことができるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d2773-283">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


- <span data-ttu-id="d2773-284">チーム プランナー ビューのタスクに枠が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-284">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="d2773-285">チーム プランナー ビューのタスクでドラッグ アンド ドロップが機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-285">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="d2773-286">コスト型リソースがマイルストーン タスクに割り当てられたとき、基準コストが正しくロールアップされないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d2773-286">Fixed an issue where when a cost resource was assigned to a milestone task, baseline cost didn't rollup correctly.</span></span>


### <a name="visio"></a><span data-ttu-id="d2773-287">Visio</span><span class="sxs-lookup"><span data-stu-id="d2773-287">Visio</span></span>

- <span data-ttu-id="d2773-288">問題が修正され、ユーザーが Visio for Office 365 のコネクタを使用して、ユーザー設定の Visio ステンシルと組み込みのテンプレートの両方で直線を作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="d2773-288">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="d2773-289">Word</span><span class="sxs-lookup"><span data-stu-id="d2773-289">Word</span></span>

- <span data-ttu-id="d2773-290">ドキュメントの保存に失敗した場合にアプリケーションが予期せず終了してしまう可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-290">Fixed an issue that could cause the application to close unexpectedly if a document save failed.</span></span>


- <span data-ttu-id="d2773-291">Word から PowerPoint への数式のコピー/貼り付けに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-291">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="d2773-292">この変更により、ドキュメントを編集するときのカーソルに関する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="d2773-292">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="d2773-293">3D 効果のあるアイコンと SVG グラフィックに適用される色の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-293">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="d2773-294">段落をスキップする可能性があるナレーターの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-294">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="d2773-295">リッチ テキスト コンテンツ コントロールの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-295">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="d2773-296">スタイル ギャラリー ダイアログの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-296">We fixed an issue with Style Gallery dialog.</span></span>


- <span data-ttu-id="d2773-297">共同編集中の競合を解決する際の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-297">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


- <span data-ttu-id="d2773-298">文書のスタイルがテンプレートとは別のスタイルに置き換わってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-298">We fixed an issue which document styles are replaced with other styles from the template.</span></span>


- <span data-ttu-id="d2773-299">最適化されたゲートが Word に影響を与えるアサート バグを修正します。</span><span class="sxs-lookup"><span data-stu-id="d2773-299">Fix an assert bug exposed by optimized gates affecting Word.</span></span>


### <a name="office-suite"></a><span data-ttu-id="d2773-300">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d2773-300">Office Suite</span></span>

- <span data-ttu-id="d2773-301">同期バックからサーバーのみに移行したファイルを保存しようとすると失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-301">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>


- <span data-ttu-id="d2773-302">特定のシナリオで、[名前を付けて保存] の実行に失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d2773-302">Fixed an issue where trying to do a SaveAs would fail in certain scenarios.</span></span>


- <span data-ttu-id="d2773-303">SaveRequestManagerCam が原因で、エラーが返される代わりにアプリケーションが閉じられる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-303">We fixed an issue where SaveRequestManagerCam was causing the application to close instead of returning an error.</span></span>


- <span data-ttu-id="d2773-304">すべての相互依存のコンポーネントを正常に閉じる、ファイルの閉じ順序が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d2773-304">Fixed the file closing sequence so that all the interdependent components are closed gracefully.</span></span>


- <span data-ttu-id="d2773-305">キャッシュからの URL と OneDrive からの URL が一致しない場合に、ファイルが NOT SyncBacked として開かれてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-305">Fixed an issue of file would be opened as NOT SyncBacked when url from cache and url from OneDrive does NOT match.</span></span>


- <span data-ttu-id="d2773-306">Skype for Business メッセージのコピー/貼り付けで、「コンテンツの貼り付け時に問題が発生しました」というダイアログが表示されるバグを修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-306">Fixing a bug where copy/paste in Skype for Business messages resulted in a dialog displaying "Something went wrong when pasting your content".</span></span>


- <span data-ttu-id="d2773-307">コメントから Excel にテキストをコピーして貼り付けるときにエラーが発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="d2773-307">Fixed an issue where an error would occur when copy/paste text from a comment into Excel</span></span>


- <span data-ttu-id="d2773-308">数式を含むテキスト内でナレーターを使用するとクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-308">Fix a crash that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="d2773-p117">Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。</span><span class="sxs-lookup"><span data-stu-id="d2773-p117">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners. Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="d2773-311">新しいバージョンの Office を特定の古いバージョンの Office の上からインストールすると、レジストリ エントリが存在していないために機能が低下してしまう (Power Query を使用できないなど) という問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-311">Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>


- <span data-ttu-id="d2773-312">Microsoft 365 エンドポイントのデータ損失防止が、ディスク上の Office ドキュメントを分類できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-312">Fixed an issue where Microsoft 365 Endpoint data loss prevention was unable to classify Office documents on disk.</span></span>


- <span data-ttu-id="d2773-313">[図の圧縮] ダイアログで一部のユーザー設定が保持されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-313">We fixed an issue with the Compress Picture dialog not retaining certain user settings.</span></span>


- <span data-ttu-id="d2773-314">メディア コントローラーのイベント通知に関連する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="d2773-314">Fixes an issue related to media controller event notifications.</span></span>


- <span data-ttu-id="d2773-315">メディア プレーヤー エンジンのタイミングに関連する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="d2773-315">Fixes an issue related to media player engine timing.</span></span>


- <span data-ttu-id="d2773-316">最適化されたバイナリ サイズ。</span><span class="sxs-lookup"><span data-stu-id="d2773-316">Optimized binary size.</span></span>


- <span data-ttu-id="d2773-317">Anaheim WebView は、Windows 情報保護 (WIP) をまだサポートしていません。</span><span class="sxs-lookup"><span data-stu-id="d2773-317">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="d2773-318">この修正プログラムを適用すると、Office addin プラットフォームが、WIP が有効な環境でダウンレベルの WebView に戻ります。</span><span class="sxs-lookup"><span data-stu-id="d2773-318">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="d2773-319">お客様のコンピューター環境に応じて、Edge Spartan WebView または Trident WebView のいずれかになります。</span><span class="sxs-lookup"><span data-stu-id="d2773-319">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="d2773-320">ダウンレベル WebViews は、両方とも WIP をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="d2773-320">Both down level WebViews support WIP.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-february-09"></a><span data-ttu-id="d2773-322">バージョン 2008: 2 月 9 日</span><span class="sxs-lookup"><span data-stu-id="d2773-322">Version 2008: February 09</span></span>
<span data-ttu-id="d2773-323">*バージョン 2008 (ビルド 13127.21216)*</span><span class="sxs-lookup"><span data-stu-id="d2773-323">*Version 2008 (Build 13127.21216)*</span></span>

<span data-ttu-id="d2773-324">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="d2773-324">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d2773-326">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d2773-326">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d2773-327">Excel</span><span class="sxs-lookup"><span data-stu-id="d2773-327">Excel</span></span>

- <span data-ttu-id="d2773-328">無効なファイル属性 (作成時刻、修正時刻など) を持つ UNC ファイルを開くと、Excel が予期せず終了してしまう可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-328">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="d2773-329">Excel からグラフをコピーして Word または PowerPoint に貼り付けるときに、10 進数と桁区切りの記号の設定を継承しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-329">We fixed an issue where decimal and thousands separators settings would not carry over when copying a chart from Excel and pasting into Word or PowerPoint.</span></span>


- <span data-ttu-id="d2773-330">毎回マクロが実行されているとピボットテーブルの範囲の形式を含むマクロを実行するパフォーマンスが悪化する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-330">We fixed an issue where the performance of running a macro involving PivotTable range formatting would get worse each time the macro is run.</span></span>


- <span data-ttu-id="d2773-331">シートを別のブックにコピーまたは移動する場合に条件付き書式のルールが破棄される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-331">We fixed an issue where conditional formatting rules were dropped when copying or moving sheets to another workbook.</span></span>


- <span data-ttu-id="d2773-332">アプリのスタート画面のブートが無効の場合にユーザーが秘密度ラベルを Excel ファイルに適用できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-332">We fixed an issue where users were unable to apply sensitivity labels to Excel files when the start screen on app boot was disabled.</span></span>


- <span data-ttu-id="d2773-333">OneDrive 同期フォルダーからクラウド ファイルを開く場合の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-333">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="d2773-334">Outlook</span><span class="sxs-lookup"><span data-stu-id="d2773-334">Outlook</span></span>

- <span data-ttu-id="d2773-335">添付ファイルを追加または保存するときに Outlook が散発的に機能しなくなる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-335">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="d2773-336">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d2773-336">PowerPoint</span></span>

- <span data-ttu-id="d2773-337">QAT で [フォントサイズ] コマンドが追加されたのに、更新すると最近定義されたフォント サイズにオート コンプリートするという問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="d2773-337">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="d2773-338">‘ ソースの形式を保持する ’ オプションを使用してスライドのコピーまたは貼り付けを行う場合に予期せず新しいスライド マスターを上書きすることがある問題は修正されました</span><span class="sxs-lookup"><span data-stu-id="d2773-338">Fixed an issue where copy and paste of a slide with 'keep source formatting' option would sometimes copy over a new slide master unexpectedly</span></span>


### <a name="word"></a><span data-ttu-id="d2773-339">Word</span><span class="sxs-lookup"><span data-stu-id="d2773-339">Word</span></span>

- <span data-ttu-id="d2773-340">Word 文書を開くと、エラー ダイアログが表示されることがある変更履歴の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-340">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="d2773-341">OneDrive 同期フォルダーからクラウド ファイルを開く場合の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-341">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="office-suite"></a><span data-ttu-id="d2773-342">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d2773-342">Office Suite</span></span>

- <span data-ttu-id="d2773-343">Office で正常にファイルを開けなくなる問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="d2773-343">Fixed an issue that prevented successful open of a file in Office.</span></span>


- <span data-ttu-id="d2773-344">書式のコピー/貼り付けを介してコネクタに適用されたスケッチ アウトラインを含むドキュメントが壊れる可能性がある問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="d2773-344">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2008-january-12"></a><span data-ttu-id="d2773-346">バージョン 2008: 1 月 12 日</span><span class="sxs-lookup"><span data-stu-id="d2773-346">Version 2008: January 12</span></span>
<span data-ttu-id="d2773-347">*バージョン 2008 (ビルド 13127.21064)*</span><span class="sxs-lookup"><span data-stu-id="d2773-347">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="d2773-348">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="d2773-348">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="d2773-350">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="d2773-350">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="d2773-351">Excel</span><span class="sxs-lookup"><span data-stu-id="d2773-351">Excel</span></span>

- <span data-ttu-id="d2773-352">読み取り専用のブックを開いたときに、ピボット テーブルのデータが更新されなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-352">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="d2773-353">この変更により、次の問題が修正されます: OneDrive ローカル同期フォルダーからファイルを挿入すると、Excel の [オブジェクトの挿入] に正しいアイコンが表示されない。</span><span class="sxs-lookup"><span data-stu-id="d2773-353">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="d2773-354">共同編集のときに、新しいバージョンのファイルに関する通知が誤って送信される可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-354">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="d2773-355">Overwrite モードで IME を使用するときに、余計な文字を誤って前に進めてしまうという編集に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-355">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="d2773-356">リアルタイム データをマルチスレッドの再計算機能と組み合わせて使用するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-356">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="d2773-357">特定の Windows セキュリティのエクスプロイト保護設定 (SimExec、CallerCheck) を使用している場合に、Excel の起動に失敗したり、予期せず終了したりしてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-357">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


### <a name="outlook"></a><span data-ttu-id="d2773-358">Outlook</span><span class="sxs-lookup"><span data-stu-id="d2773-358">Outlook</span></span>

- <span data-ttu-id="d2773-359">下書きに保存したときに SmartLinks の書式設定が失われるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d2773-359">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="d2773-360">ポリシーを上書きするときに、正当化テキストをカスタマイズする方法をユーザーに提供してしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-360">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="d2773-361">OFT ファイルとして保存するときに、中国語の文字が疑問符に変更されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-361">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="d2773-362">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="d2773-362">PowerPoint</span></span>

- <span data-ttu-id="d2773-363">Slide.Shapes.AddMediaObject2 が従来のビデオ形式 (.MPG-1、Mpeg-2) で予期せず終了してしまう可能性がある VBA の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-363">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="d2773-364">ドキュメントの修復操作の後であっても、一部の破損した PowerPoint ファイルを正常に開くことができないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="d2773-364">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="d2773-365">Project</span><span class="sxs-lookup"><span data-stu-id="d2773-365">Project</span></span>

- <span data-ttu-id="d2773-366">リソースの配分状況が特定の方法で指定されている場合に、Project が予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-366">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="d2773-367">Skype</span><span class="sxs-lookup"><span data-stu-id="d2773-367">Skype</span></span>

- <span data-ttu-id="d2773-368">ユーザの TLS-DSK 証明書が期待通りの時間に更新されず、有効期間が 12 時間未満の場合にのみ更新されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-368">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="d2773-369">Office にまだライセンスが付与されていない場合、サインイン後に Skype for Business UI が空白で表示されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="d2773-369">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="d2773-370">Office スイート</span><span class="sxs-lookup"><span data-stu-id="d2773-370">Office Suite</span></span>

- <span data-ttu-id="d2773-371">この変更により、従来の図面を含むファイルを開くことに関連する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d2773-371">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="d2773-372">この変更により、SVG フォールバック プロキシでアクセス違反が発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="d2773-372">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

> [!NOTE]
> <span data-ttu-id="d2773-375">Office の使用で問題がある場合は、[Microsoft の回答フォーラム](https://answers.microsoft.com/)に関するページまたは「[Microsoft Tech Community](https://techcommunity.microsoft.com/)」に質問を投稿するか、[サポート](https://support.microsoft.com/contactus)に問い合わせてサポートを受けることができます。</span><span class="sxs-lookup"><span data-stu-id="d2773-375">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (管理センターのメタデータのコンテンツを変更しないでください。開始)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20506|version-2102-april-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20294|version-2102-march-09|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21216|version-2008-february-09|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21064|version-2008-january-12|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20910|version-2008-december-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20760|version-2008-november-10|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20638|version-2008-october-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20408|version-2008-september-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20880|version-2002-july-14|)
[//]: # (管理センターのメタデータのコンテンツ エンドを変更しないでください)
