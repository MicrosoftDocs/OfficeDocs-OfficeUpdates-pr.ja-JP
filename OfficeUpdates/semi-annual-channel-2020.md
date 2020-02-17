---
title: 2020 年の半期チャネル リリースのリリース ノート
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Office 365 ProPlus 用の 2020 年の半期チャネル リリースのリリース ノートを IT プロフェッショナルに提供します
ms.openlocfilehash: 974a5db6f3bfba2bb20cd75f4e35a2777ea94ca8
ms.sourcegitcommit: 3598ca5e26109a1f99349ce3a4e70cb1d6f13e05
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/14/2020
ms.locfileid: "41978585"
---
# <a name="release-notes-for-semi-annual-channel-releases-in-2020"></a><span data-ttu-id="c839e-103">2020 年の半期チャネル リリースのリリース ノート</span><span class="sxs-lookup"><span data-stu-id="c839e-103">Release notes for Semi-Annual Channel releases in 2020</span></span>

<span data-ttu-id="c839e-104">これらのリリースノートには、Visio Pro for Office 365、Project Online Desktop Client、および Office 365 Business を含む、2020 年の Office 365 ProPlus の半期チャネルの更新プログラムに含まれる新機能およびセキュリティ以外の更新に関する情報が記載されています。</span><span class="sxs-lookup"><span data-stu-id="c839e-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Channel updates to Office 365 ProPlus in 2020, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

> [!NOTE]
>
>- <span data-ttu-id="c839e-105">多くの場合、機能 (場合によっては修正プログラムも) は、特定の期間にわたって半期チャネルにロールアウトされます。</span><span class="sxs-lookup"><span data-stu-id="c839e-105">We often roll out features (and sometimes even fixes) to Semi-Annual Channel over a period of time.</span></span> <span data-ttu-id="c839e-106">ここで説明される内容がすぐに確認できなくても、間もなく利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="c839e-106">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="c839e-107">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c839e-107">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
>- <span data-ttu-id="c839e-108">半期チャネルのユーザーが Office ポータルから Office 365 をダウンロードして Windows 10 にインストールしたときに、既定では OneNote 2016 は含まれません。</span><span class="sxs-lookup"><span data-stu-id="c839e-108">OneNote 2016 will not be included by default when a user on the Semi-Annual Channel downloads and installs Office 365 on Windows 10 from the Office Portal.</span></span>


## <a name="version-1908-february-11"></a><span data-ttu-id="c839e-109">バージョン 1908: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="c839e-109">Version 1908: February 11</span></span>
<span data-ttu-id="c839e-110">*バージョン 1908 (ビルド 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="c839e-110">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="c839e-111">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/ja-JP/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c839e-111">Security updates listed [here](https://docs.microsoft.com/ja-JP/officeupdates/office365-proplus-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="c839e-113">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="c839e-113">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c839e-114">Excel</span><span class="sxs-lookup"><span data-stu-id="c839e-114">Excel</span></span>

- <span data-ttu-id="c839e-115">この更新プログラムは、VBA を使用してグラフのヘッダー/フッターに画像を追加するたびにエラーが発生する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="c839e-115">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="c839e-116">グループ ボックス コントロールの境界線が印刷プレビューまたは印刷時に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-116">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="c839e-117">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="c839e-117">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="c839e-118">グラフを含むブックを保存すると、グラフ ヘッダーの画像のファイル サイズが大きくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-118">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="c839e-119">選択範囲を相互参照ブックと同期させ続けることにより、相互参照ブックの DBCS 文字が破損する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-119">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="c839e-120">自動調整を使用して行の高さを調整するときにチェック ボックスのコントロールが縮小される可能性があるという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-120">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="c839e-121">Outlook</span><span class="sxs-lookup"><span data-stu-id="c839e-121">Outlook</span></span>

- <span data-ttu-id="c839e-122">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-122">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="c839e-123">競合メッセージの処理中にユーザーに同期エラーが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-123">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="c839e-124">Outlook の起動時にユーザーが [プロファイルの読み込み中] 画面でハングアップする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-124">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="c839e-125">ビューを変更すると、断続的なクラッシュが発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-125">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="c839e-126">Citrix 環境で 30 件を超える予定表を表示したときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-126">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="c839e-127">[こちら](https://support.microsoft.com/ja-JP/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)は、以前のバージョンで文書化された個々の KB です。</span><span class="sxs-lookup"><span data-stu-id="c839e-127">[Here](https://support.microsoft.com/ja-JP/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="c839e-128">ユーザーが OST と同期している共有予定表フォルダーに問題があり、これらのフォルダーを操作しようとするとアクセス許可エラーが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-128">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="c839e-129">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c839e-129">PowerPoint</span></span>

- <span data-ttu-id="c839e-130">PowerPoint スライドでのコピーと貼り付けのシナリオである図形のコピーを改善しました。ループ内の他のスライドに貼り付けると例外で失敗する場合があります。</span><span class="sxs-lookup"><span data-stu-id="c839e-130">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="c839e-131">共同作業ユーザー間のパフォーマンスが低下する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-131">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="c839e-132">増分で開くファイルに、複数のメディア ストリームが埋め込まれたスライドが含まれている場合に発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-132">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="c839e-133">PowerPoint の初回起動時に、信頼されていないアドインに対してセキュリティ警告メッセージ バーが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-133">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="c839e-134">プロジェクト</span><span class="sxs-lookup"><span data-stu-id="c839e-134">Project</span></span>

- <span data-ttu-id="c839e-135">基本カレンダーが変更されたときにリソース カレンダーが更新されないために、実際の作業がタイムシートとプロジェクト計画の間で異なる場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-135">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="c839e-136">Word</span><span class="sxs-lookup"><span data-stu-id="c839e-136">Word</span></span>

- <span data-ttu-id="c839e-137">非推奨の API から移動することにより、Word でクラッシュが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-137">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c839e-138">Office スイート</span><span class="sxs-lookup"><span data-stu-id="c839e-138">Office Suite</span></span>

- <span data-ttu-id="c839e-139">この変更は、破損したファイルを開いた後の画像の正しいレンダリングに対処します。</span><span class="sxs-lookup"><span data-stu-id="c839e-139">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1902-february-11"></a><span data-ttu-id="c839e-141">バージョン 1902: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="c839e-141">Version 1902: February 11</span></span>
<span data-ttu-id="c839e-142">*バージョン 1902 (ビルド 11328.20526)*</span><span class="sxs-lookup"><span data-stu-id="c839e-142">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="c839e-143">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/ja-JP/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c839e-143">Security updates listed [here](https://docs.microsoft.com/ja-JP/officeupdates/office365-proplus-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="c839e-145">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="c839e-145">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="c839e-146">Outlook</span><span class="sxs-lookup"><span data-stu-id="c839e-146">Outlook</span></span>

- <span data-ttu-id="c839e-147">ユーザーが暗号化されたメールを送信しようとするときに、"暗号化アルゴリズムがサポートされていません" というエラーを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-147">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="c839e-148">Word</span><span class="sxs-lookup"><span data-stu-id="c839e-148">Word</span></span>

- <span data-ttu-id="c839e-149">非推奨の API から移動することにより、Word でクラッシュが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-149">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

## <a name="version-1808-february-11"></a><span data-ttu-id="c839e-152">バージョン 1808: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="c839e-152">Version 1808: February 11</span></span>
<span data-ttu-id="c839e-153">*バージョン 1808 (ビルド 10730.20438)*</span><span class="sxs-lookup"><span data-stu-id="c839e-153">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="c839e-154">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/ja-JP/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c839e-154">Security updates listed [here](https://docs.microsoft.com/ja-JP/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-january-14"></a><span data-ttu-id="c839e-156">バージョン 1908: 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="c839e-156">Version 1908: January 14</span></span>
<span data-ttu-id="c839e-157">*バージョン 1908 (ビルド 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="c839e-157">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="c839e-158">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c839e-158">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="c839e-160">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="c839e-160">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="c839e-161">Access</span><span class="sxs-lookup"><span data-stu-id="c839e-161">Access</span></span>

- <span data-ttu-id="c839e-162">**データベース オブジェクトをタブで管理する:** アクティブなタブが分かりやすく表示され、簡単にタブをドラッグして再配置し、ワンクリックでデータベース オブジェクトを閉じることができます。</span><span class="sxs-lookup"><span data-stu-id="c839e-162">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="c839e-163">**シームレスに切り替える:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用のアカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="c839e-163">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="c839e-164">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="c839e-164">Switching between them has never been easier.</span></span> [<span data-ttu-id="c839e-165">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c839e-165">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="c839e-166">**より大きい [ズーム] ボックス:** [ズーム] ボックスがより大きく表示され、そこでフォントを変更することができます。変更内容はすべて [ズーム] ボックス内に記憶されます。</span><span class="sxs-lookup"><span data-stu-id="c839e-166">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="c839e-167">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c839e-167">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="c839e-168">Excel</span><span class="sxs-lookup"><span data-stu-id="c839e-168">Excel</span></span>

- <span data-ttu-id="c839e-169">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="c839e-169">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="c839e-170">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="c839e-170">Switching between them has never been easier.</span></span> [<span data-ttu-id="c839e-171">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c839e-171">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="c839e-172">**コンテンツのリーチを拡大する:** プレゼンテーションのアクセシビリティを高める必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="c839e-172">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="c839e-173">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="c839e-173">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="c839e-174">[校閲]>[アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="c839e-174">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="c839e-175">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="c839e-175">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="c839e-176">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="c839e-176">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="c839e-177">**ワークシートが生まれ変わりました：** ワークブックを使ってアニメーション 3D グラフィックスを挿入し、心臓の鼓動、惑星軌道、そして T-Rex の大暴れを見ることができます。</span><span class="sxs-lookup"><span data-stu-id="c839e-177">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="c839e-178">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c839e-178">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="c839e-179">**データの詳細を検出する:** 新しいアイデア ボタンは、データのパターンを探し、それを使用してインテリジェントな個人向けの提案を作成します。</span><span class="sxs-lookup"><span data-stu-id="c839e-179">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions.</span></span> [<span data-ttu-id="c839e-180">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c839e-180">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- <span data-ttu-id="c839e-181">**共同作業がさらに簡単に:** 共同編集の改善とは、条件付き書式、セルのスタイルなどを使用して作業しているときに、ユーザーによる変更がシームレスに共同作業者の変更と統合されるということです。</span><span class="sxs-lookup"><span data-stu-id="c839e-181">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="c839e-182">**類似列のテーブルを結合する:** 取得と変換 (Power Query) では、テーブルを統合するために列を比較するときに、近似文字列マッチング ロジック (あいまい一致とも呼ばれる) が使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c839e-182">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="c839e-183">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c839e-183">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="c839e-184">**Power Query の機能強化を使用して素早くコーディングする:** オートコンプリートと構文の色分けを使用して、素早くコーディングを完了できます。</span><span class="sxs-lookup"><span data-stu-id="c839e-184">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="c839e-185">関数、列、パラメーターも簡単に見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="c839e-185">Easily discover functions, columns, and parameters, too.</span></span>

### <a name="outlook"></a><span data-ttu-id="c839e-186">Outlook</span><span class="sxs-lookup"><span data-stu-id="c839e-186">Outlook</span></span>

- <span data-ttu-id="c839e-187">\*\* Outlook のユーザー エクスペリエンスを更新しました：\*\* これまで Coming Soon でプレビューできていた、最も重要なことに集中できるようにするためのシンプルな操作性です。</span><span class="sxs-lookup"><span data-stu-id="c839e-187">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="c839e-188">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c839e-188">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="c839e-189">**カスタマイズも可能、シンプルになったリボン：** 最もよく使うボタンが単一行にまとめられ、使いやすくなりました。</span><span class="sxs-lookup"><span data-stu-id="c839e-189">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="c839e-190">簡単に従来のビューとシンプルなビューを切り替えたり、コマンドを固定または固定解除できます。</span><span class="sxs-lookup"><span data-stu-id="c839e-190">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="c839e-191">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c839e-191">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="c839e-192">**メッセージの移動中も作業が可能:** Outlook では、メッセージの移動がバックグラウンドで行われるようになったため、フォルダー間で多数のメッセージの移動が行われている間も作業を続けることができます。</span><span class="sxs-lookup"><span data-stu-id="c839e-192">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="c839e-193">**連続する会議の合間に時間を組み込む:** 既定で 5 分から 10 分早く会議を終了するように設定することで、出席者に休憩時間や場所の移動時間を与えることができます。</span><span class="sxs-lookup"><span data-stu-id="c839e-193">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="c839e-194">**お気に入りのアクションを選びましょう：** フラグや、削除機能を使いますか？</span><span class="sxs-lookup"><span data-stu-id="c839e-194">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="c839e-195">アーカイブまたは既読に​​しますか?</span><span class="sxs-lookup"><span data-stu-id="c839e-195">How about Archive or Mark as Read?</span></span> <span data-ttu-id="c839e-196">クイック操作メニューをカスタマイズしてよく使うコマンドを追加できます。</span><span class="sxs-lookup"><span data-stu-id="c839e-196">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="c839e-p115">**ミームが表示される:** テキストまたは静的イメージだけでは十分ではない場合、アニメーション GIF を使用して要点を示すことができます。[詳細情報](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="c839e-p115">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="c839e-199">**ゆったりとしたレイアウト、まとめたレイアウト？自由に決めましょう：** 狭い間隔で、アイテム間の間隔をより広くしたり、レイアウトを狭くして表示量をより多くできます。</span><span class="sxs-lookup"><span data-stu-id="c839e-199">**Relaxed or tighter layout? You choose:** Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

- <span data-ttu-id="c839e-200">**より簡単なアカウントの追加方法:** アカウントのセットアップの改善により、2 要素認証を使用する Outlook.com と Gmail のアカウントを Outlook に追加することが以前よりも簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="c839e-200">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="c839e-201">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c839e-201">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="c839e-202">**同期制限にさよならしましょう:** Outlook の改善によりフォルダーの制限が解消され、そのまま共有メールボックスが同期されます。</span><span class="sxs-lookup"><span data-stu-id="c839e-202">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c839e-203">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c839e-203">PowerPoint</span></span>

- <span data-ttu-id="c839e-204">**よりよい変形操作:** 図形に名前を付けると、変形するときにより細かく制御できます。</span><span class="sxs-lookup"><span data-stu-id="c839e-204">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="c839e-205">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c839e-205">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="c839e-206">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="c839e-206">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="c839e-207">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="c839e-207">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="c839e-208">**コンテンツのリーチを拡大する:** プレゼンテーションのアクセシビリティを高める必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="c839e-208">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="c839e-209">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="c839e-209">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="c839e-210">[校閲]>[アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="c839e-210">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="c839e-211">**シームレスに切り替える:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用のアカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="c839e-211">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="c839e-212">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="c839e-212">Switching between them has never been easier.</span></span> [<span data-ttu-id="c839e-213">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c839e-213">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="c839e-214">**オンライン ビデオの新しい保存場所:** Microsoft Stream にビデオを保存すれば、組織内のすべてのユーザーが視聴できます。</span><span class="sxs-lookup"><span data-stu-id="c839e-214">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="c839e-215">ビデオのリンクを挿入すれば、小さなファイル サイズでマルチメディア プレゼンテーションをご利用いただけます。</span><span class="sxs-lookup"><span data-stu-id="c839e-215">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="c839e-216">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c839e-216">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="c839e-217">**変更が発生したときに変更内容を自動的に保存する:** 変更が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="c839e-217">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="c839e-p122">**ユーザーへのテストやアンケート:** テストやアンケートをスライドに配置します。Office で応答が自動的に収集され、保存されます。[詳細情報](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="c839e-p122">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="c839e-221">**これまで以上に簡単にオンライン ビデオを挿入できるようになりました:** Vimeo または YouTube からビデオをスライドに挿入する場合は、</span><span class="sxs-lookup"><span data-stu-id="c839e-221">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide?</span></span> <span data-ttu-id="c839e-222">ビデオ ページへのリンクがあれば簡単に行えます。</span><span class="sxs-lookup"><span data-stu-id="c839e-222">The video page link is all you need.</span></span> [<span data-ttu-id="c839e-223">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c839e-223">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

### <a name="project"></a><span data-ttu-id="c839e-224">Project</span><span class="sxs-lookup"><span data-stu-id="c839e-224">Project</span></span>

- <span data-ttu-id="c839e-225">**シームレスに切り替える:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用のアカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="c839e-225">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="c839e-226">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="c839e-226">Switching between them has never been easier.</span></span> [<span data-ttu-id="c839e-227">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c839e-227">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="c839e-228">Visio</span><span class="sxs-lookup"><span data-stu-id="c839e-228">Visio</span></span>

- <span data-ttu-id="c839e-229">**プロセス図を Word にエクスポート:** Word 文書に図形やメタデータなどのグラフ コンテンツを自動的に追加します。</span><span class="sxs-lookup"><span data-stu-id="c839e-229">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="c839e-230">その後に、文書をカスタマイズしてプロセスに関するガイドラインや操作マニュアルを作成できます。</span><span class="sxs-lookup"><span data-stu-id="c839e-230">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="c839e-231">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c839e-231">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="c839e-232">**はっとするようなデータ フローチャート:** データ ビジュアライザーのフローチャートの見事な新しいレイアウトがすっきり、はっきり、わかりやすくなりました。</span><span class="sxs-lookup"><span data-stu-id="c839e-232">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="c839e-233">オプションの [デザイン] タブをクリックします。</span><span class="sxs-lookup"><span data-stu-id="c839e-233">Click the Design tab for options.</span></span>

- <span data-ttu-id="c839e-234">**Azure ステンシルが組み込まれました:** 豊富な Azure ステンシルを使用してクラウド アプリの設計やアーキテクチャの計画を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="c839e-234">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="c839e-235">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c839e-235">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="c839e-p128">**壊れた Excel リンクの問題を解消:** データ ビジュアライザーの図にリンクされているはずの Excel ブックが見つかりませんか? 再リンクして、すぐに業務を再開できます。[詳細情報](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="c839e-p128">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="c839e-239">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="c839e-239">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="c839e-240">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="c839e-240">Switching between them has never been easier.</span></span> [<span data-ttu-id="c839e-241">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c839e-241">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="c839e-242">**Power BI から Visio ビジュアルをエクスポートする:** Power BI レポートを PDF、PowerPoint などのファイルとしてエクスポートするときに、Power BI 用の Visio ビジュアルが正しく表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c839e-242">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="c839e-243">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c839e-243">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="c839e-244">Word</span><span class="sxs-lookup"><span data-stu-id="c839e-244">Word</span></span>

- <span data-ttu-id="c839e-245">**[学習ツール] モードで、ページで使用できる色が増えました:** Word の学習ツールでは、より多くのページ テーマ色が追加され、ページの背景色を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c839e-245">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="c839e-246">すべて白またはすべて黒の背景だと読みにくいと感じるユーザーは少なくないため、PC と Mac の Word で色の選択肢を拡大しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-246">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="c839e-p132">**インク エディターを使った自然な編集:** ペンを使って 1 ストローク描くだけで、単語の分割や結合、新しい線の追加、単語の挿入などができます。[詳細情報](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="c839e-p132">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="c839e-p133">**静的なドキュメントから魅力的なドキュメントへの変換:** ドキュメントを、すべてのデバイスに対応する対話型の使いやすい Web ページに変換します。[詳細情報](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="c839e-p133">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="c839e-251">**コンテンツのリーチを拡大する:** ドキュメントのアクセシビリティを高める必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="c839e-251">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="c839e-252">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="c839e-252">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="c839e-253">[校閲]>[アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="c839e-253">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="c839e-254">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="c839e-254">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="c839e-255">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="c839e-255">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="c839e-256">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="c839e-256">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="c839e-257">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="c839e-257">Switching between them has never been easier.</span></span> [<span data-ttu-id="c839e-258">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c839e-258">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="c839e-259">**作業の邪魔をするものにさよならしましょう:** Mac のお気に入りの機能が Windows に登場します。</span><span class="sxs-lookup"><span data-stu-id="c839e-259">**Say goodbye to distractions:** A favorite Mac feature comes to Windows.</span></span> <span data-ttu-id="c839e-260">気を散らさずに作業に集中するには、[表示]メニューの[フォーカス]に切り替えます。</span><span class="sxs-lookup"><span data-stu-id="c839e-260">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> [<span data-ttu-id="c839e-261">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c839e-261">Learn more</span></span>](https://support.office.com/article/51af2fb2-194f-424b-ab7e-b65de9ec9292)

- <span data-ttu-id="c839e-p138">**行フォーカスによる読解力の向上:** ドキュメント内で行ごとの移動をスムーズに行います。一度に 1 行か、3 行か、5 行かを表示するようフォーカスを調整できます。[詳細情報](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="c839e-p138">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="c839e-265">**変更時に変更内容を保存する:** すべての更新が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="c839e-265">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="c839e-266">**\@メンションを使用してユーザーの注意を引く:** コメントで @メンションを使うと、仕事仲間による入力が必要な場合にそのユーザーに知らせることができます。</span><span class="sxs-lookup"><span data-stu-id="c839e-266">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="c839e-267">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c839e-267">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="office-suite"></a><span data-ttu-id="c839e-268">Office スイート</span><span class="sxs-lookup"><span data-stu-id="c839e-268">Office Suite</span></span>

- <span data-ttu-id="c839e-269">**特定のファイルをすばやく見つける:** 最近作業を行ったファイルを探している場合は、</span><span class="sxs-lookup"><span data-stu-id="c839e-269">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="c839e-270">[ファイル] > [開く] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="c839e-270">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="c839e-271">**変更が発生したときに変更内容を自動的に保存する:** 変更が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="c839e-271">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="c839e-272">**プライバシー制御**: 診断データとコネクテッド エクスペリエンス用に新しく更新されて、改善された制御。</span><span class="sxs-lookup"><span data-stu-id="c839e-272">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="c839e-273">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c839e-273">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="c839e-274">**新しい外観を備えた Office のアイコン:** シンプルかつ高性能で、インテリジェントな Office のエクスペリエンスを反映するように、Office のアイコンがリニューアルされました。</span><span class="sxs-lookup"><span data-stu-id="c839e-274">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="c839e-275">**Microsoft Teams のインストール:** Microsoft Teams は、Office 365 ProPlus の既存のインストールに既定でインストールされています。</span><span class="sxs-lookup"><span data-stu-id="c839e-275">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="c839e-276">詳細情報</span><span class="sxs-lookup"><span data-stu-id="c839e-276">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="c839e-279">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="c839e-279">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="c839e-280">Access</span><span class="sxs-lookup"><span data-stu-id="c839e-280">Access</span></span>

- <span data-ttu-id="c839e-281">この更新プログラムにより、Sum などの集計が結果を整数値に切り捨てる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="c839e-281">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="c839e-282">この更新プログラムにより、リモート テーブル (SQL Server テーブルなど) への参照を含むユニオン クエリにより Access が閉じて再起動する問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="c839e-282">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="c839e-283">この更新プログラムにより、更新クエリが実行されるか、SQL で UPDATE ステートメントが使用されるときに &quot;クエリは破損しています&quot; というエラーを発生させる場合のある Microsoft Access の問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="c839e-283">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="c839e-284">Excel</span><span class="sxs-lookup"><span data-stu-id="c839e-284">Excel</span></span>

- <span data-ttu-id="c839e-285">ドキュメント タイトルのオランダ語の KeyTip が Alt-G に変更されました。</span><span class="sxs-lookup"><span data-stu-id="c839e-285">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="c839e-286">図形やフォームコントロールに割り当てられているマクロが間違ったエラーメッセージとして表示される、または間違った対象範囲で動作する問題が Excel で修正されました。</span><span class="sxs-lookup"><span data-stu-id="c839e-286">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="c839e-287">最初のアイテムを検索した後に、ダイアログでのフォーカスの位置が変更されてしまう検索と置換についての問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="c839e-287">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="c839e-288">これにより、ピボットテーブルの並べ替え方法を変更し、他のユーザーとの共同編集セッション中にそれを更新するとクラッシュが発生する可能性がある問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="c839e-288">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="c839e-289">OLAP ピボットテーブルのフィルターが、キューブから削除された値に設定された場合の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-289">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="c839e-290">グラフ テンプレートを使用してグラフを挿入する場合に、プレビューで正しい色が使用されるよう修正します。</span><span class="sxs-lookup"><span data-stu-id="c839e-290">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="c839e-291">シリーズ コレクションを変更するときに、散布図が適切にレンダリングされない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-291">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="c839e-292">セルが挿入または削除されたときに、ウォーターフォール図とじょうごグラフがテーブルと同期しなくなる原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-292">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="c839e-293">Excel で、ユーザーが変更を取得するためにブックを再び開くよう要求されるマージ競合の問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c839e-293">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="c839e-294">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-294">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="c839e-295">最小化されたウィンドウをアクティブにするマクロ実行時エラーの原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-295">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="c839e-296">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-296">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="c839e-297">他のユーザーと共同編集しているときに、テーブルの横にある切り取りと貼り付けの操作が失敗する原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-297">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="c839e-298">実行中のマクロでカスタム プロパティを変更するときに、共同編集の中断を引き起こす原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-298">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="c839e-299">アドインによって開かれた WPF (Windows Presentation Foundation) フォームのコンボ ボックスからアイテムを選ぶことができない問題が発生しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-299">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="c839e-300">ブックが開かれていない状態で最近使用したファイルを検索するときに、クラッシュを発生させる原因となっていた可能性がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-300">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="c839e-301">非同期のユーザー定義関数が同期して実行されるパフォーマンスの問題が発生しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-301">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="c839e-302">結合されたセルで列を削除するパフォーマンスが大幅に改善されました。</span><span class="sxs-lookup"><span data-stu-id="c839e-302">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="c839e-303">スクロール後にセルを選択すると間違ったセルが選択されることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-303">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="c839e-304">Lookup 関数がエラーを返す問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-304">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="c839e-305">Office の以前のバージョンで作成されたブックを Office の最新のバージョンで開いたときに、Excel の終了を引き起こす可能性がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-305">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="c839e-306">ファイルに広範な条件付き書式が設定されている場合に、[フォントの色] ボタンをクリックするとパフォーマンスが低下する問題。</span><span class="sxs-lookup"><span data-stu-id="c839e-306">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="c839e-307">印刷プレビューの印刷範囲が正しくないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-307">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="c839e-308">信頼されていないネットワーク共有から保護されたファイルを編集する際に、Excel にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="c839e-308">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="c839e-309">色によるフィルタリングのパフォーマンスが大幅に改善されました。</span><span class="sxs-lookup"><span data-stu-id="c839e-309">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="c839e-310">一部の保護されたシートにハイパーリンクが貼り付けられない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-310">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="c839e-311">アドイン マネジャーで参照するときに、16 個を超えるアドインを表示できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c839e-311">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="c839e-312">この変更は、ソフトウェア レンダリングを活用することにより、特定の Intel グラフィック ドライバーの問題を回避します。</span><span class="sxs-lookup"><span data-stu-id="c839e-312">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="c839e-313">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c839e-313">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="c839e-314">この更新プログラムにより、"アップロードできませんでした" というメッセージが表示され、Office ドキュメントが OneDrive for Business にアップロードされないことがあるエラーが修正されます。</span><span class="sxs-lookup"><span data-stu-id="c839e-314">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="c839e-315">Win32 クライアントの [アイデア] ボタンをクリックしてアドインを読み込むときにエラーが発生するという Excel のアイデア機能の問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="c839e-315">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="c839e-316">Outlook</span><span class="sxs-lookup"><span data-stu-id="c839e-316">Outlook</span></span>

- <span data-ttu-id="c839e-317">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c839e-317">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="c839e-318">メールボックスを基本認証から最新認証にアップグレードしたユーザーが、Outlook プロファイルに関連付けられた正しくないアカウントで終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-318">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="c839e-319">Web アドインがデジタル著作権管理 (DRM) メッセージにアクセスすべきでないときにアクセスする原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-319">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="c839e-320">一部のセーフリンクに対して簡易的なホバーの URL が正しく表示されなくなる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-320">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="c839e-321">これにより、Python による添付ファイルもブロックされるよう、Outlook の添付ファイルのブロック ロジックが更新されました。</span><span class="sxs-lookup"><span data-stu-id="c839e-321">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="c839e-322">設定に関係なく、一部の POP3 ユーザーに、すべてのメールがプレーンテキストで書式設定されて表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-322">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="c839e-323">この修正プログラムでは、HTML 形式のメッセージの表示が復元されます。</span><span class="sxs-lookup"><span data-stu-id="c839e-323">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="c839e-324">プライマリ予定表からグループ予定表にアイテムをコピーするときに、ユーザーにアクセス許可のエラーを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-324">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="c839e-325">ユーザーがスクリーン リーダーから場所の候補にアクセスできない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-325">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="c839e-326">ユーザーがキーボード ショートカットを使用してメールボックス フォルダーを操作するときに、顕著な遅延を発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-326">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="c839e-327">非常に長い Outlook セッションでメモリ リークを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-327">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="c839e-328">ユーザーが [ルール] ダイアログを開くと、"このコンピューターのルールは、Microsoft Exchange のルールと異なります" というメッセージが表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-328">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="c839e-329">特定のセーフリンクを操作するときに、Outlook でクラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-329">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="c839e-330">代理人が特定の会議出席依頼に既に返信したかどうかに関係なく、管理者が不明瞭になる原因となっていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-330">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="c839e-331">一部の AutoDiscover の応答を処理するときに、クラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-331">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="c839e-332">アカウント作成コンテキストからサポートに連絡しようとすると、ユーザーに [OK] ボタンのある空のメッセージ ボックスが表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-332">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="c839e-333">この変更により、UPN 経由で自動検出の認証プロンプトに提供されるアカウントのメールを選択するため、ポリシーを管理者が有効にできるようになります。</span><span class="sxs-lookup"><span data-stu-id="c839e-333">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="c839e-334">既定では、使用可能な場合に、自動検出ではアカウント UPN の方が選択されます。</span><span class="sxs-lookup"><span data-stu-id="c839e-334">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="c839e-335">最新のグループに対し、検索の失敗がユーザーに表示される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-335">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="c839e-336">Outlook ユーザーが特定のシナリオで "パスワードを要求している" 状態で停止する原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-336">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="c839e-337">会議室の空き時間外に行われた会議のためにユーザーにその会議室が提案される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-337">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="c839e-338">ユーザーが暗号化されたメールを送信しようとするときに、"暗号化アルゴリズムがサポートされていません" というエラーを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-338">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="c839e-339">英語以外の言語を使用するユーザーの、メールの件名が非常に小さくなるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-339">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="c839e-340">一部のユーザーに、セカンダリ Exchange アカウントを追加するときに作成された、重複した特別なフォルダーが表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-340">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="c839e-341">"不在着信した会話" メッセージのルールを作成しようとするときに、クラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-341">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="c839e-342">SMIME アルゴリズムの選択に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-342">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="c839e-343">代替送信者を使用しているときに、ポリシーのヒントが表示されない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-343">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="c839e-344">ユーザーが Outlook プロセスでメモリ リークを観測する原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-344">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="c839e-345">プレゼンス情報を更新するときに、断続的なクラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-345">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="c839e-346">現在のフォルダー検索で断続的な失敗を引き起こす原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-346">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="c839e-347">一部のユーザーが Outlook のクラウド設定を取得しようとするときに、認証エラーが発生する原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-347">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="c839e-348">検索に関するフィードバックのエクスペリエンスで終了する原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-348">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="c839e-349">一部の AutoDiscover の応答を処理するときに、クラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-349">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="c839e-350">プレゼンス情報を更新するときに、断続的なクラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-350">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c839e-351">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c839e-351">PowerPoint</span></span>

- <span data-ttu-id="c839e-352">一部のアドインがグラフの図形に対して予期しないエラーをスローさせる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-352">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="c839e-353">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c839e-353">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="c839e-354">この変更により、PowerPoint ビデオ コントロールのアクセス可能な名前が復元されます。</span><span class="sxs-lookup"><span data-stu-id="c839e-354">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="c839e-355">一部のアニメーションが開始しないことがあるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-355">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="c839e-356">スライドを 1 つのプレゼンテーションから別のプレゼンテーションにコピーすると、重複したマスターが作成される可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-356">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="c839e-357">最新のコメントを含むファイルを、サポートされていないバージョンで開くと黄色の警告が表示されます</span><span class="sxs-lookup"><span data-stu-id="c839e-357">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="c839e-358">信頼性の修正: サード パーティのアドインが PowerPoint のクラッシュを発生させる可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-358">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="c839e-359">PowerPoint の垂直テキスト ボックスで半角カタカナ文字が適切に回転しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-359">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="c839e-360">Project</span><span class="sxs-lookup"><span data-stu-id="c839e-360">Project</span></span>

- <span data-ttu-id="c839e-361">Windows 7 のユーザーが Project Web App および SharePoint サイトからプロジェクトを開くことができるように問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c839e-361">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="c839e-362">読み取り専用のプロジェクトを開いたときに複数のメッセージを取得する可能性があるという問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-362">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="c839e-363">[すべて平準化] コマンドがリソースの割り当て超過を適切に解決しません。</span><span class="sxs-lookup"><span data-stu-id="c839e-363">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="c839e-364">タスクの作業がゼロの割り当てがある場合、タスクに完了のマークを付けることができず、常に 99％ で表示される問題。</span><span class="sxs-lookup"><span data-stu-id="c839e-364">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="c839e-365">Visio</span><span class="sxs-lookup"><span data-stu-id="c839e-365">Visio</span></span>

- <span data-ttu-id="c839e-366">Visio から SVG へのエクスポートが、さまざまな図形で失敗していました。</span><span class="sxs-lookup"><span data-stu-id="c839e-366">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="c839e-367">Word</span><span class="sxs-lookup"><span data-stu-id="c839e-367">Word</span></span>

- <span data-ttu-id="c839e-368">この変更により、Word を使ってドキュメントを開くときのパフォーマンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="c839e-368">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="c839e-369">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c839e-369">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="c839e-370">Deskjet プリンターに印刷するときに、スケーリングの問題を引き起こす可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-370">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="c839e-371">無限ループになることがあるトラック変更の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-371">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="c839e-372">シャットダウン時にアプリが終了することがあるさまざまな問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-372">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="c839e-373">特定のアドインに関連するクラッシュも修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-373">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="c839e-374">Office スイート</span><span class="sxs-lookup"><span data-stu-id="c839e-374">Office Suite</span></span>

- <span data-ttu-id="c839e-375">新元号の名前である “Reiwa” のひらがなと漢字をスペルミスまたは間違った文法として誤って識別していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-375">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="c839e-376">SharePoint 2016 に保存されているファイルを共有しようとするときに、"申し訳ございません。何かがこのファイルの共有を妨げています。" というメッセージが表示される原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-376">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="c839e-377">PowerPoint での共同編集とオフライン編集の両方を含むセッションでデータの損失を引き起こす可能性のある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-377">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="c839e-378">これは、ユーザーがファイルを開くときに発生する可能性のあるクラッシュの修正プログラムです。</span><span class="sxs-lookup"><span data-stu-id="c839e-378">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="c839e-379">PowerPoint ユーザーがオンライン プレゼンテーションを行おうとするときに、エラーが発生しないようにします。</span><span class="sxs-lookup"><span data-stu-id="c839e-379">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="c839e-380">同期エンジンでバックアップされた Sharepoint ファイルに '保存済み' と表示されますが、場合によっては実際に変更が保存されないため、データを損失することになります。</span><span class="sxs-lookup"><span data-stu-id="c839e-380">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="c839e-381">ユーザーが Word、Excel、および PowerPoint のドキュメントを保存できなくなることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-381">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="c839e-382">この問題は、[保存] アイコンをクリックしたり Ctrl キーを押しながら S キーを押したりした後に、新しいファイルを作成して [ダイアログで保存] オプションを表示するユーザーに影響を与えます。</span><span class="sxs-lookup"><span data-stu-id="c839e-382">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="c839e-383">すべてのアプリのリボンで、図形の挿入ギャラリーが表示されるまでに約 4 秒かかるという Win7 のパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-383">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="c839e-384">Backstage の Info Place のスラブにアクセシビリティ情報が表示されていないというバグを修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-384">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="c839e-385">レジストリ整合性に関する Office 更新プロセスの信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-385">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="c839e-386">Office の更新プログラムが、意図したソース (ローカル共有、ネットワーク共有、構成マネージャー
で提供される場所など) からではなく、予期せずに Office CDN からファイルをダウンロードする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-386">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="c839e-387">Office の更新メッセージが、異なる言語で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-387">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="c839e-388">今後、Office の更新メッセージは Windows の表示言語と一致します。</span><span class="sxs-lookup"><span data-stu-id="c839e-388">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="c839e-389">ユーザーが管理者ではなく、システム アカウントにネットワーク接続が確立されていない場合に、更新プログラムが適用されない問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="c839e-389">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="c839e-390">特定の状況で、更新後に Office ショートカットが消えてしまう場合があります。</span><span class="sxs-lookup"><span data-stu-id="c839e-390">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="c839e-391">この更新プログラムにより、Office ショートカットを公開するときの信頼性が向上します。</span><span class="sxs-lookup"><span data-stu-id="c839e-391">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="c839e-392">従量制課金ネットワークで更新プログラムが予期せずブロックされる可能性があるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c839e-392">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="c839e-393">ODT と GPO の更新期限設定で、相対期限の設定後、初回のみしか機能しないバスが修正されました。修正により、2 回目以降の更新プログラムで相対期限を使用きるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c839e-393">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="c839e-394">以前に中断された可能性のあるダウンロードを再開することにより、Office の更新プログラムをダウンロードするときの信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-394">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="c839e-395">サード パーティ製プラグインのテキスト ボックスと図形の自動調整に関連する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-395">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="c839e-396">大きなツリー ビューがクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-396">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="c839e-397">Office ユーザーのセキュリティを保護するために、Microsoft Office の更新プログラムは SHA-2 アルゴリズムのみを使用して署名されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="c839e-397">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1902-january-14"></a><span data-ttu-id="c839e-399">バージョン 1902: 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="c839e-399">Version 1902: January 14</span></span>
<span data-ttu-id="c839e-400">*バージョン 1902 (ビルド 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="c839e-400">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="c839e-401">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c839e-401">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="c839e-403">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="c839e-403">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="c839e-404">Excel</span><span class="sxs-lookup"><span data-stu-id="c839e-404">Excel</span></span>

- <span data-ttu-id="c839e-405">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="c839e-405">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="c839e-406">Outlook</span><span class="sxs-lookup"><span data-stu-id="c839e-406">Outlook</span></span>

- <span data-ttu-id="c839e-407">ユーザーが暗号化されたメールを送信しようとするときに、"暗号化アルゴリズムがサポートされていません" というエラーを発生させる原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="c839e-407">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c839e-408">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c839e-408">PowerPoint</span></span>

- <span data-ttu-id="c839e-409">最新のコメントを含むファイルを、サポートされていないバージョンで開くと黄色の警告が表示されます。</span><span class="sxs-lookup"><span data-stu-id="c839e-409">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="c839e-410">Word</span><span class="sxs-lookup"><span data-stu-id="c839e-410">Word</span></span>

- <span data-ttu-id="c839e-411">この変更により、Word を使ってドキュメントを開くときのパフォーマンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="c839e-411">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1808-january-14"></a><span data-ttu-id="c839e-413">バージョン 1808: 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="c839e-413">Version 1808: January 14</span></span>
<span data-ttu-id="c839e-414">*バージョン 1808 (ビルド 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="c839e-414">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="c839e-415">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="c839e-415">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

> [!NOTE]
> <span data-ttu-id="c839e-417">Office の使用で問題がある場合は、[Microsoft の回答フォーラム](https://answers.microsoft.com/)に関するページまたは「[Microsoft Tech Community](https://techcommunity.microsoft.com/)」に質問を投稿するか、[サポート](https://support.microsoft.com/contactus)に問い合わせてサポートを受けることができます。</span><span class="sxs-lookup"><span data-stu-id="c839e-417">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>