---
title: 2020 年の最新のチャネル リリースのリリース ノート
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Microsoft 365 Apps 用の 2020 年の月次チャネル リリースのリリース ノートを IT 担当者に提供します
ms.openlocfilehash: 5fab650e5b8ebb66b1507e889a744a95c3322809
ms.sourcegitcommit: 34bca539ddfe0e06b772aaa294f4e992630b2a41
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/28/2021
ms.locfileid: "50032305"
---
# <a name="release-notes-for-current-channel"></a><span data-ttu-id="4f58d-103">現在のチャネルのリリース ノート</span><span class="sxs-lookup"><span data-stu-id="4f58d-103">Release notes for Current Channel</span></span>

<span data-ttu-id="4f58d-104">このリリース ノートには、現在のチャネルの更新プログラムに含まれる新機能と、セキュリティ以外の更新プログラムに関する情報が記載されています。対象となるのは、Microsoft 365 Apps for enterprise、Microsoft 365 Apps for business、および Project と Visio のデスクトップ アプリのサブスクリプション版です。</span><span class="sxs-lookup"><span data-stu-id="4f58d-104">These release notes provide information about new features and non-security updates that are included in Current Channel updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="4f58d-105">現在、Microsoft 365 Apps の更新プログラム チャネルに、新しい更新プログラム チャネル (月次エンタープライズ チャネル) の追加や既存の更新プログラム チャネル名の変更など、いくつかの変更を進めています。</span><span class="sxs-lookup"><span data-stu-id="4f58d-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="4f58d-106">詳細については、[こちらの記事](https://go.microsoft.com/fwlink/p/?linkid=2127441)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="4f58d-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

 > [!NOTE]
>
>- <span data-ttu-id="4f58d-107">Microsoft では多くの場合、現在の一定期間にわたって、機能 (および場合によっては修正プログラム) を展開します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-107">We often roll out features (and sometimes even fixes) to Current over a period of time.</span></span>  <span data-ttu-id="4f58d-108">ここで説明した内容がすぐに表示されない場合は、間もなく利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-108">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="4f58d-109">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-109">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
>- <span data-ttu-id="4f58d-110">Microsoft Teams の機能は、リリース頻度が高いため、最新のCurrent Channel とは異なる場合があります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-110">Microsoft Teams features may differ from the latest Current Channel released as they have a more frequent release cadence.</span></span>




[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2101-january-26"></a><span data-ttu-id="4f58d-113">バージョン 2101: 1 月 26 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-113">Version 2101: January 26</span></span>
<span data-ttu-id="4f58d-114">*バージョン 2101 (ビルド 13628.20274)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-114">*Version 2101 (Build 13628.20274)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="4f58d-116">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="4f58d-116">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="4f58d-117">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-117">Excel</span></span>

- <span data-ttu-id="4f58d-118">**M365 の管理者に機密度ラベルに関する監査データを送信する** : ユーザーがドキュメントやメールに機密度ラベルを適用、変更、または削除したときに、Office は M365 監査バックエンドに監査データを送信し管理者の目に入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="4f58d-118">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="4f58d-119">これは、管理者のためのサイレント機能 (UI なし) です。</span><span class="sxs-lookup"><span data-stu-id="4f58d-119">This is a silent functionality (no UI) for administrator benefit.</span></span>

- <span data-ttu-id="4f58d-120">**政府機関のお客様: ドキュメントおよびメールに秘密度ラベルを適用する:** GCC および GCC-H 環境のお客様は、秘密度のラベル付け機能を利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-120">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="4f58d-121">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-121">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a><span data-ttu-id="4f58d-122">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-122">Outlook</span></span>

- <span data-ttu-id="4f58d-123">**メッセージの所有者として会話を削除する:** この機能を使用すると、メッセージの所有者による会話を削除できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-123">**Delete conversation by message owner:** This feature allows you to delete a conversation by message owner.</span></span>

- <span data-ttu-id="4f58d-124">**連続する会議の合間に時間を組み込む:** 既定で 5 分から 10 分遅く会議を開始するように設定することで、出席者に休憩時間や場所の移動時間を与えることができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-124">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default.</span></span> [<span data-ttu-id="4f58d-125">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-125">Learn more</span></span>](https://support.office.com/article/be84396a-0903-4e25-b31c-1c99ce0dacf2)

- <span data-ttu-id="4f58d-126">**すべてのオンライン会議:** 予定表設定を更新して、既定で Teams 会議を作成するすべての会議を作成します。これにより、Teams 会議オプションをクリックする必要がなくなります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-126">**Every meeting online:** Update your calendar settings to make every meeting you create a Teams Meeting by default so you no longer need to remember to click the Teams Meeting option.</span></span>

- <span data-ttu-id="4f58d-127">**M365 の管理者に機密度ラベルに関する監査データを送信する** : ユーザーがドキュメントやメールに機密度ラベルを適用、変更、または削除したときに、Office は M365 監査バックエンドに監査データを送信し管理者の目に入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="4f58d-127">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="4f58d-128">これは、管理者のためのサイレント機能 (UI なし) です。</span><span class="sxs-lookup"><span data-stu-id="4f58d-128">This is a silent functionality (no UI) for administrator benefit.</span></span>

- <span data-ttu-id="4f58d-129">**政府機関のお客様: ドキュメントおよびメールに秘密度ラベルを適用する:** GCC および GCC-H 環境のお客様は、秘密度のラベル付け機能を利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-129">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="4f58d-130">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-130">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)

### <a name="powerpoint"></a><span data-ttu-id="4f58d-131">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-131">PowerPoint</span></span>

- <span data-ttu-id="4f58d-132">**M365 の管理者に機密度ラベルに関する監査データを送信する** : ユーザーがドキュメントやメールに機密度ラベルを適用、変更、または削除したときに、Office は M365 監査バックエンドに監査データを送信し管理者の目に入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="4f58d-132">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="4f58d-133">これは、管理者のためのサイレント機能 (UI なし) です。</span><span class="sxs-lookup"><span data-stu-id="4f58d-133">This is a silent functionality (no UI) for administrator benefit.</span></span>

- <span data-ttu-id="4f58d-134">**政府機関のお客様: ドキュメントおよびメールに秘密度ラベルを適用する:** GCC および GCC-H 環境のお客様は、秘密度のラベル付け機能を利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-134">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="4f58d-135">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-135">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)

### <a name="word"></a><span data-ttu-id="4f58d-136">Word</span><span class="sxs-lookup"><span data-stu-id="4f58d-136">Word</span></span>

- <span data-ttu-id="4f58d-137">**M365 の管理者に機密度ラベルに関する監査データを送信する** : ユーザーがドキュメントやメールに機密度ラベルを適用、変更、または削除したときに、Office は M365 監査バックエンドに監査データを送信し管理者の目に入れるようにします。</span><span class="sxs-lookup"><span data-stu-id="4f58d-137">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="4f58d-138">これは、管理者のためのサイレント機能 (UI なし) です。</span><span class="sxs-lookup"><span data-stu-id="4f58d-138">This is a silent functionality (no UI) for administrator benefit.</span></span>

- <span data-ttu-id="4f58d-139">**政府機関のお客様: ドキュメントおよびメールに秘密度ラベルを適用する:** GCC および GCC-H 環境のお客様は、秘密度のラベル付け機能を利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-139">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="4f58d-140">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-140">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-143">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-143">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4f58d-144">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-144">Excel</span></span>

- <span data-ttu-id="4f58d-145">特定の Windows セキュリティのエクスプロイト保護設定 (SimExec、CallerCheck) を使用している場合に、Excel の起動に失敗したり、予期せず終了したりしてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-145">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


- <span data-ttu-id="4f58d-146">一部の従来の Excel 4.0 および Excel 5.0 マクロ、および dialogsheets.show への一部の VBA 呼び出しが破損する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-146">We fixed an issue that broke some legacy Excel 4.0 and Excel5.0 macros as well as some VBA calls to dialogsheets.show.</span></span>


### <a name="outlook"></a><span data-ttu-id="4f58d-147">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-147">Outlook</span></span>

- <span data-ttu-id="4f58d-148">特定の検索シナリオで Outlook が予期せず終了するという一部のユーザーの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-148">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="4f58d-149">プロファイルに大きな階層がある共有メールボックスまたは代理メールボックスを持つユーザーがハングする原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-149">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


### <a name="project"></a><span data-ttu-id="4f58d-150">Project</span><span class="sxs-lookup"><span data-stu-id="4f58d-150">Project</span></span>

- <span data-ttu-id="4f58d-151">チーム プランナー ビューのタスクに枠が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-151">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="4f58d-152">チーム プランナー ビューのタスクでドラッグ アンド ドロップが機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-152">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="4f58d-153">コスト型リソースがマイルストーン タスクに割り当てられたとき、基準コストが正しくロールアップされないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-153">Fixed an issue where when a cost resource was assigned to a milestone task, baseline cost didn't rollup correctly.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-january-21"></a><span data-ttu-id="4f58d-155">バージョン 2012: 1 月 21 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-155">Version 2012: January 21</span></span>
<span data-ttu-id="4f58d-156">*バージョン 2012 (ビルド 13530.20440)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-156">*Version 2012 (Build 13530.20440)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-158">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-158">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="4f58d-159">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-159">Outlook</span></span>

- <span data-ttu-id="4f58d-160">プロファイルに大きな階層がある共有メールボックスまたは代理メールボックスを持つユーザーがハングする原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-160">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


- <span data-ttu-id="4f58d-161">特定の検索シナリオで Outlook が予期せず終了するという一部のユーザーに発生した問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-161">We fixed an issue that caused some users to experience Outlook closing unexpectedly in certain search scenarios.</span></span>


### <a name="office-suite"></a><span data-ttu-id="4f58d-162">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-162">Office Suite</span></span>

- <span data-ttu-id="4f58d-163">すべての相互依存のコンポーネントを正常に閉じる、ファイルの閉じ順序が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-163">Fixed the file closing sequence so that all the interdependent components are closed gracefully.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-january-12"></a><span data-ttu-id="4f58d-165">バージョン 2012: 1 月 12 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-165">Version 2012: January 12</span></span>
<span data-ttu-id="4f58d-166">*バージョン 2012 (ビルド 13530.20376)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-166">*Version 2012 (Build 13530.20376)*</span></span>

<span data-ttu-id="4f58d-167">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4f58d-167">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-169">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-169">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4f58d-170">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-170">Excel</span></span>

- <span data-ttu-id="4f58d-171">特定の Windows セキュリティのエクスプロイト保護設定 (SimExec、CallerCheck) を使用している場合に、Excel の起動に失敗したり、予期せず終了したりしてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-171">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


### <a name="outlook"></a><span data-ttu-id="4f58d-172">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-172">Outlook</span></span>

- <span data-ttu-id="4f58d-173">ユーザーに保存を求めた後、編集した署名が保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-173">We fixed an issue that caused an edited signature to fail to save after prompting the user to do so.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-january-05"></a><span data-ttu-id="4f58d-175">バージョン 2012: 1 月 5 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-175">Version 2012: January 05</span></span>
<span data-ttu-id="4f58d-176">*バージョン 2012 (ビルド 13530.20316)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-176">*Version 2012 (Build 13530.20316)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="4f58d-178">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="4f58d-178">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="4f58d-179">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-179">Outlook</span></span>

- <span data-ttu-id="4f58d-180">**クラウドでの Outlook の設定** [自動応答]、[優先受信トレイ]、[プライバシー] などの Outlook for Windows の設定を選択し、任意の PC でアクセスできるようにします。</span><span class="sxs-lookup"><span data-stu-id="4f58d-180">**Your Outlook settings in the cloud:** Choose your Outlook for Windows settings like Automatic Replies, Focused Inbox, and Privacy, and get to them on any PC.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="4f58d-181">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-181">PowerPoint</span></span>

- <span data-ttu-id="4f58d-182">**プレゼンター コーチでプレゼンテーションのリハーサルを行う:** 話す速度、ピッチ、つなぎ語、機微な表現など、聴衆の関心を引きつけておくのに役立つ内容についてフィードバックを受けます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-182">**Rehearse your presentation with Presenter Coach:** Get feedback on the things that help keep an audience engaged — like pacing, pitch, filler words, sensitive phrases, and more.</span></span> [<span data-ttu-id="4f58d-183">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-183">Learn more</span></span>](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-186">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-186">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4f58d-187">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-187">Excel</span></span>

- <span data-ttu-id="4f58d-188">ピボットテーブルの [計算の種類] メニューを使用すると、Excel が予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-188">Fixed an issue where Excel might close unexpectedly when using the "Show Values As" menu for a PivotTable.</span></span>


- <span data-ttu-id="4f58d-189">Excel 4.0 マクロを含む Excel アドイン ファイルを開いたときにプロンプトが表示されずにマクロが無効のままになる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-189">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="4f58d-190">共同編集時に、一部のユーザーに対して、新しいバージョンのファイルを通知するメッセージ バーが誤って表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-190">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="4f58d-191">この変更により、数式内にフォントが正しく表示されない問題に対処できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-191">This change addresses an issue with properly displaying fonts within equations.</span></span>


### <a name="outlook"></a><span data-ttu-id="4f58d-192">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-192">Outlook</span></span>

- <span data-ttu-id="4f58d-193">一部のお客様の環境で、予定表の読み込み中にハングアップする原因となった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-193">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="4f58d-194">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-194">PowerPoint</span></span>

- <span data-ttu-id="4f58d-195">この変更により、特定のジオメトリで図形の結合操作を適用するときの軌跡の塗りつぶしに関する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-195">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


- <span data-ttu-id="4f58d-196">この変更により、数式内にフォントが正しく表示されないという問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-196">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="4f58d-197">QAT に追加された font size コマンドが、更新中に定義された最も近いフォントサイズに自動補完される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-197">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


### <a name="office-suite"></a><span data-ttu-id="4f58d-198">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-198">Office Suite</span></span>

- <span data-ttu-id="4f58d-199">最適化されたバイナリ サイズ。</span><span class="sxs-lookup"><span data-stu-id="4f58d-199">Optimized binary size.</span></span>


- <span data-ttu-id="4f58d-200">Anaheim WebView は、Windows 情報保護 (WIP) をまだサポートしていません。</span><span class="sxs-lookup"><span data-stu-id="4f58d-200">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="4f58d-201">この修正プログラムを適用すると、Office addin プラットフォームが、WIP が有効な環境でダウンレベルの WebView に戻ります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-201">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="4f58d-202">お客様のコンピューター環境に応じて、Edge Spartan WebView または Trident WebView のいずれかになります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-202">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="4f58d-203">ダウンレベル WebViews は、両方とも WIP をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="4f58d-203">Both down level WebViews support WIP.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-december-21"></a><span data-ttu-id="4f58d-205">バージョン 2011: 12 月 21 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-205">Version 2011: December 21</span></span>
<span data-ttu-id="4f58d-206">*バージョン 2011 (ビルド 13426.20404)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-206">*Version 2011 (Build 13426.20404)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-208">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-208">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4f58d-209">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-209">Excel</span></span>

- <span data-ttu-id="4f58d-210">Excel によってファイルの新しいバージョンが使用可能であることを示すメッセージバーが誤って表示され、ブックのコピーに変更内容を保存するか、変更内容を破棄するように強制する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-210">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="4f58d-211">Excel 4.0 マクロを含む Excel アドイン ファイルを開いたときにプロンプトが表示されずに Excel がマクロを無効のままにしてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-211">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


### <a name="office-suite"></a><span data-ttu-id="4f58d-212">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-212">Office Suite</span></span>

- <span data-ttu-id="4f58d-213">キャッシュからの URL と OneDrive からの URL が一致しない場合に、ファイルが NOT SyncBacked として開かれる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-213">Fixed an issue of file would be opened as NOT SyncBacked when url from cache and url from OneDrive does NOT match.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-december-08"></a><span data-ttu-id="4f58d-215">バージョン 2011: 12 月 08 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-215">Version 2011: December 08</span></span>
<span data-ttu-id="4f58d-216">*バージョン 2011 (ビルド 13426.20332)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-216">*Version 2011 (Build 13426.20332)*</span></span>

<span data-ttu-id="4f58d-217">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4f58d-217">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-219">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-219">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="4f58d-220">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-220">Office Suite</span></span>

- <span data-ttu-id="4f58d-221">SaveRequestManagerCam が原因で、エラーが返される代わりにアプリケーションが閉じられる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-221">We fixed an issue where SaveRequestManagerCam was causing the application to close instead of returning an error.</span></span> 




[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-december-02"></a><span data-ttu-id="4f58d-223">バージョン 2011: 12 月 2 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-223">Version 2011: December 02</span></span>
<span data-ttu-id="4f58d-224">*バージョン 2011 (ビルド 13426.20308)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-224">*Version 2011 (Build 13426.20308)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-226">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-226">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="4f58d-227">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-227">Outlook</span></span>

- <span data-ttu-id="4f58d-228">他の出席者が会議を転送すると、会議の元の出席者の一部がキャンセルを受信するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-228">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="4f58d-229">1 つ以上の署名が構成されているにもかかわらず、ユーザーの署名が署名ドロップダウンに表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-229">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


### <a name="project"></a><span data-ttu-id="4f58d-230">Project</span><span class="sxs-lookup"><span data-stu-id="4f58d-230">Project</span></span>

- <span data-ttu-id="4f58d-231">ロードの特定の部分でプロジェクト ファイルに問題がある場合に、特定のプロジェクトを開くことができるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-231">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="office-suite"></a><span data-ttu-id="4f58d-232">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-232">Office Suite</span></span>

- <span data-ttu-id="4f58d-233">Office スイートでは、新しいバージョンの Office を特定の古いバージョンの Office の上からインストールすると、レジストリ エントリが存在していないために機能が低下する(Power Query を使用できないなど) という問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-233">Office Suite Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-november-30"></a><span data-ttu-id="4f58d-235">バージョン 2011: 11 月 30 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-235">Version 2011: November 30</span></span>
<span data-ttu-id="4f58d-236">*バージョン 2011 (ビルド 13426.20294)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-236">*Version 2011 (Build 13426.20294)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-238">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-238">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="4f58d-239">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-239">PowerPoint</span></span>

- <span data-ttu-id="4f58d-240">Word から Powerpoint への数式のコピー/貼り付けに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-240">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


### <a name="word"></a><span data-ttu-id="4f58d-241">Word</span><span class="sxs-lookup"><span data-stu-id="4f58d-241">Word</span></span>

- <span data-ttu-id="4f58d-242">Word から Powerpoint への数式のコピー/貼り付けに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-242">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


- <span data-ttu-id="4f58d-243">文書のスタイルがテンプレートとは別のスタイルに置き換わる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-243">We fixed an issue which document styles are replaced with other styles from the template.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-november-23"></a><span data-ttu-id="4f58d-245">バージョン 2011: 11 月 23 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-245">Version 2011: November 23</span></span>
<span data-ttu-id="4f58d-246">*バージョン 2011 (ビルド 13426.20274)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-246">*Version 2011 (Build 13426.20274)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="4f58d-248">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="4f58d-248">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="4f58d-249">Access</span><span class="sxs-lookup"><span data-stu-id="4f58d-249">Access</span></span>

- <span data-ttu-id="4f58d-250">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-250">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="4f58d-251">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-251">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="4f58d-252">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-252">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a><span data-ttu-id="4f58d-253">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-253">Excel</span></span>

- <span data-ttu-id="4f58d-254">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-254">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="4f58d-255">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-255">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="4f58d-256">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-256">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="4f58d-257">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-257">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="4f58d-258">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-258">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

- <span data-ttu-id="4f58d-259">**ソース クエリを基に新しいシートに名前を付ける:** データが新しいシートに読み込まれると、シートはソース クエリの名前に基づいて名付けられます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-259">**Name the new sheet after the source query:** When the data is loaded into the new sheet, the sheet will be named based on the name of the source query.</span></span>

- <span data-ttu-id="4f58d-260">**[詳細] ダイアログ ボックスを使用してデータ型を作成する:** [詳細] ダイアログ ボックスでは、作成するデータ型を組み合わせる列を手動で選択できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-260">**Use the Advanced Dialog to Create Data Types:** The Advanced Dialog allows you to manually select the columns which combine the Data Type you are creating.</span></span>

### <a name="onenote"></a><span data-ttu-id="4f58d-261">OneNote</span><span class="sxs-lookup"><span data-stu-id="4f58d-261">OneNote</span></span>

- <span data-ttu-id="4f58d-262">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-262">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="4f58d-263">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-263">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="4f58d-264">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-264">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a><span data-ttu-id="4f58d-265">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-265">Outlook</span></span>

- <span data-ttu-id="4f58d-266">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-266">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="4f58d-267">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-267">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="4f58d-268">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-268">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="4f58d-269">[ファイル] > [Office アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-269">Go to File > Office Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="4f58d-270">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-270">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

- <span data-ttu-id="4f58d-271">**タスクのユーザー エクスペリエンスの更新:** タスク アイテムの視覚的な更新。</span><span class="sxs-lookup"><span data-stu-id="4f58d-271">**User Experience Updates for Tasks:** A visual refresh of task items.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="4f58d-272">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-272">PowerPoint</span></span>

- <span data-ttu-id="4f58d-273">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-273">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="4f58d-274">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-274">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br /><span data-ttu-id="4f58d-275">[ブログの投稿](https://insider.office.com/ja-JP/blog/svg-content-office-third-party-apps)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="4f58d-275">See details in [blog post](https://insider.office.com/ja-JP/blog/svg-content-office-third-party-apps)</span></span>

- <span data-ttu-id="4f58d-276">**透過背景の GIF を作成する**: アニメーション GIF にエクスポートする場合、新しいオプションを使用して背景を透明にすることができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-276">**Create GIFs with Transparent Backgrounds:** When exporting to an Animated GIF, a new option will allow you to make the background transparent.</span></span><br /><span data-ttu-id="4f58d-277">[ブログの投稿](https://insider.office.com/ja-JP/blog/export-animated-gifs-transparent-backgrounds)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="4f58d-277">See details in [blog post](https://insider.office.com/ja-JP/blog/export-animated-gifs-transparent-backgrounds)</span></span>

- <span data-ttu-id="4f58d-278">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-278">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="4f58d-279">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-279">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="4f58d-280">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-280">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

- <span data-ttu-id="4f58d-281">**アニメーション GIF を範囲内でエクスポートする**: アニメーション GIF にエクスポートするときにスライドの範囲を選択します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-281">**Export animated GIF in a range:** Select a range of slides when exporting to animated GIF.</span></span>

- <span data-ttu-id="4f58d-282">**ビデオ ライブラリ:** アプリ内で利用可能な、質の良い無料のビデオ ライブラリを使用してドキュメントの質を高めます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-282">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app</span></span>

### <a name="project"></a><span data-ttu-id="4f58d-283">Project</span><span class="sxs-lookup"><span data-stu-id="4f58d-283">Project</span></span>

- <span data-ttu-id="4f58d-284">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-284">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="4f58d-285">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-285">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="4f58d-286">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-286">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a><span data-ttu-id="4f58d-287">発行者</span><span class="sxs-lookup"><span data-stu-id="4f58d-287">Publisher</span></span>

- <span data-ttu-id="4f58d-288">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-288">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="4f58d-289">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-289">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="4f58d-290">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-290">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a><span data-ttu-id="4f58d-291">Visio</span><span class="sxs-lookup"><span data-stu-id="4f58d-291">Visio</span></span>

- <span data-ttu-id="4f58d-292">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-292">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="4f58d-293">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-293">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="4f58d-294">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-294">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a><span data-ttu-id="4f58d-295">Word</span><span class="sxs-lookup"><span data-stu-id="4f58d-295">Word</span></span>

- <span data-ttu-id="4f58d-296">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-296">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="4f58d-297">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-297">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="4f58d-298">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-298">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="4f58d-299">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-299">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="4f58d-300">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-300">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-303">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-303">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="4f58d-304">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-304">Outlook</span></span>

- <span data-ttu-id="4f58d-305">タスクの進捗レポートを送信するときに、[宛先] フィールドが空白になる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-305">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


- <span data-ttu-id="4f58d-306">MailItem.BeforeAttachmentAdd イベントの破損原因となった問題が修正されました。 </span><span class="sxs-lookup"><span data-stu-id="4f58d-306">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="4f58d-307">IDataObject 操作 (つまりクリップボードのドラッグやドロップ) で、ユーザーが添付ファイルに対して filetime の付加を無効にできるように、regkey を追加しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-307">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="4f58d-308">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="4f58d-308">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span> <span data-ttu-id="4f58d-309">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="4f58d-309">REG_DWORD IncludeFileTimesInDataObject.</span></span> <span data-ttu-id="4f58d-310">0 = filetimes は除外されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-310">0 = filetimes are excluded.</span></span> <span data-ttu-id="4f58d-311">1 = (既定) filetimes が含まれます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-311">1 = (default) filetimes are included.</span></span>


- <span data-ttu-id="4f58d-312">Azure Information Protection の保護ラベルを使用してメッセージに返信するときに、インライン画像が消えるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-312">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="4f58d-313">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-313">PowerPoint</span></span>

- <span data-ttu-id="4f58d-314">Slide.Shapes.AddMediaObject2 が従来のビデオ形式 (.MPG-1、Mpeg-2) でクラッシュする VBA の問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-314">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="4f58d-315">新たに録音したオーディオを含むスライドを複製した後にファイルを保存するときにエラーが発生するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-315">We fixed an issue where there is an error when saving the file after duplicating a slide that contains a newly recorded audio.</span></span>


- <span data-ttu-id="4f58d-316">ドキュメントの修復操作の後であっても、一部の破損した PowerPoint ファイルを正常に開くことができないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-316">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="word"></a><span data-ttu-id="4f58d-317">Word</span><span class="sxs-lookup"><span data-stu-id="4f58d-317">Word</span></span>

- <span data-ttu-id="4f58d-318">最適化されたゲートがWord に影響を与えるアサート バグが修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-318">Fixed an assert bug exposed by optimized gates affecting Word.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-november-17"></a><span data-ttu-id="4f58d-320">バージョン 2010: 11 月 17 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-320">Version 2010: November 17</span></span>
<span data-ttu-id="4f58d-321">*バージョン 2010 (ビルド 13328.20408)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-321">*Version 2010 (Build 13328.20408)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-323">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-323">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="4f58d-324">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-324">Outlook</span></span>

- <span data-ttu-id="4f58d-325">MailItem.BeforeAttachmentAdd イベントの破損原因となった問題が修正されました。 </span><span class="sxs-lookup"><span data-stu-id="4f58d-325">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="4f58d-326">IDataObject 操作 (つまりクリップボードのドラッグやドロップ) で、ユーザーが添付ファイルに対して filetime の付加を無効にできるように、regkey を追加しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-326">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="4f58d-327">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="4f58d-327">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span>  <span data-ttu-id="4f58d-328">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="4f58d-328">REG_DWORD IncludeFileTimesInDataObject.</span></span>  <span data-ttu-id="4f58d-329">0 = filetimes は除外されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-329">0 = filetimes are excluded.</span></span>  <span data-ttu-id="4f58d-330">1 = (既定) filetimes が含まれます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-330">1 = (default) filetimes are included.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="4f58d-331">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-331">PowerPoint</span></span>

- <span data-ttu-id="4f58d-332">マージ中に IRM 保護されたドキュメントを使用しているときに発生する問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-332">Fix to address a an issue when using IRM/protected documents during a merge error.</span></span>


### <a name="visio"></a><span data-ttu-id="4f58d-333">Visio</span><span class="sxs-lookup"><span data-stu-id="4f58d-333">Visio</span></span>

- <span data-ttu-id="4f58d-334">問題を解決したので、ユーザーが Visio for Office 365 のコネクタを使用して、ユーザー設定の Visio ステンシルと組み込みのテンプレートの両方で直線を作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-334">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="office-suite"></a><span data-ttu-id="4f58d-335">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-335">Office Suite</span></span>

- <span data-ttu-id="4f58d-336">特定のシナリオで、[名前を付けて保存] の実行に失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-336">Fixed an issue where trying to do a SaveAs would fail in certain scenarios.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-november-10"></a><span data-ttu-id="4f58d-338">バージョン 2010: 11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-338">Version 2010: November 10</span></span>
<span data-ttu-id="4f58d-339">*バージョン 2010 (ビルド 13328.20356)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-339">*Version 2010 (Build 13328.20356)*</span></span>

<span data-ttu-id="4f58d-340">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4f58d-340">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-342">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-342">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="4f58d-343">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-343">Outlook</span></span>

- <span data-ttu-id="4f58d-344">ユーザーが代理人に編集者権限を付与できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-344">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


### <a name="office-suite"></a><span data-ttu-id="4f58d-345">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-345">Office Suite</span></span>

- <span data-ttu-id="4f58d-346">同期バックからサーバーのみに移行したファイルを保存しようとすると失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-346">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-october-27"></a><span data-ttu-id="4f58d-348">バージョン 2010: 10 月 27 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-348">Version 2010: October 27</span></span>
<span data-ttu-id="4f58d-349">*バージョン 2010 (ビルド 13328.20292)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-349">*Version 2010 (Build 13328.20292)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="4f58d-351">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="4f58d-351">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="4f58d-352">Access</span><span class="sxs-lookup"><span data-stu-id="4f58d-352">Access</span></span>

- <span data-ttu-id="4f58d-353">**時代に追いつきましょう! 日付/時刻の拡張データ型では、より精度が高くなります。:** 改良されたデータ型をご紹介します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-353">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span> <span data-ttu-id="4f58d-354">SQL との構文の互換性を高め、日付と時刻を含むレコードの精度と詳細レベルを向上させるため、Access に DateTime2 データ型を実装しています。</span><span class="sxs-lookup"><span data-stu-id="4f58d-354">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="4f58d-355">この追加の日付および時間のデータ型には、より大きい日付範囲 (0001-01-01 ～ 9999-12-31) が含まれます。これにより、指定された時間の精度 (秒単位ではなくナノ秒) で提供され、計算を実行できるようになります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-355">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="4f58d-356">有効にするには、[新しいフィールド] > [日付と時間の拡張] を選択します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-356">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="4f58d-357">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-357">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="4f58d-358">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-358">Excel</span></span>

- <span data-ttu-id="4f58d-359">**Power Query を使用してデータ型を作成する:** Power Query を使用してあらゆるデータ ソースから豊富なデータ型を作成します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-359">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source.</span></span> [<span data-ttu-id="4f58d-360">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-360">Learn more</span></span>](https://support.office.com/article/a465a3b7-3d37-4eb1-a59c-bd3163315308)<br /><span data-ttu-id="4f58d-361">[ブログの投稿](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="4f58d-361">See details in [blog post](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)</span></span>

- <span data-ttu-id="4f58d-362">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-362">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="4f58d-363">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="4f58d-363">No conversion required.</span></span><br /><span data-ttu-id="4f58d-364">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="4f58d-364">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="4f58d-365">**アクション ペンを使用してすばやく編集する:** アクション ペンを使用すると、セルに直接手書きで書き込み、自動的に Excel データに変換されるインクでデータを書き留めることができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-365">**Make quick edits using the action pen:** With the action pen, you can write by hand directly in the cells, jot down data with ink that gets automatically converted to Excel data.</span></span>

### <a name="outlook"></a><span data-ttu-id="4f58d-366">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-366">Outlook</span></span>

- <span data-ttu-id="4f58d-367">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-367">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="4f58d-368">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="4f58d-368">No conversion required.</span></span><br /><span data-ttu-id="4f58d-369">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="4f58d-369">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="4f58d-370">**文章校正による支援:** Outlook では、入力中に文章校正のエラーが表示されます。シングル クリックで候補を適用できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-370">**Grammar checking's got your back:** Outlook marks grammar errors as you type, so you can apply suggestions with a single click.</span></span> [<span data-ttu-id="4f58d-371">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-371">Learn more</span></span>](https://support.office.com/article/ddbadc42-4637-451d-b3f4-ecf295036fa9)<br /><span data-ttu-id="4f58d-372">[ブログの投稿](https://insider.office.com/ja-JP/blog/grammar-and-style-suggestions-available-in-outlook)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="4f58d-372">See details in [blog post](https://insider.office.com/ja-JP/blog/grammar-and-style-suggestions-available-in-outlook)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="4f58d-373">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-373">PowerPoint</span></span>

- <span data-ttu-id="4f58d-374">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-374">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="4f58d-375">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="4f58d-375">No conversion required.</span></span><br /><span data-ttu-id="4f58d-376">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="4f58d-376">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="teams"></a><span data-ttu-id="4f58d-377">Teams</span><span class="sxs-lookup"><span data-stu-id="4f58d-377">Teams</span></span>

- <span data-ttu-id="4f58d-378">**Microsoft Teams のテンプレート:** Teams のテンプレートを使用すると、ユーザーは新しいチームを作成するときにさまざまなカスタマイズ可能なテンプレートから選択できるため、すばやく開始できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-378">**Templates in Microsoft Teams:** With Templates in Teams, users can choose from a variety of customizable templates when creating a new team, helping them get started quickly.</span></span> <span data-ttu-id="4f58d-379">IT 担当者は、組織の新しいカスタム テンプレートを作成して、チーム構造を標準化し、関連するアプリを表示し、ベスト プラクティスを拡張することもできます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-379">IT professionals can also create new custom templates for their organization, allowing them to standardize team structures, surface relevant apps, and scale best practices.</span></span>

- <span data-ttu-id="4f58d-380">**ピン留めされた投稿:** この機能を使用すると、ユーザーはチャネル内のメッセージをチャネル情報ペインに「ピン留め」して、チャネルのすべてのメンバーに表示させることができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-380">**Pinned Posts:** This feature allows users to "pin" any message in a channel to the channel info pane for all members of the channel to see.</span></span> <span data-ttu-id="4f58d-381">チャネルにアクセスできるメンバーは誰でも、ピン留めされたメッセージを見ることができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-381">Any members who have access to the channel will be able to see pinned messages.</span></span> <span data-ttu-id="4f58d-382">チャネルのすべてのメンバーは、(チャネルのモデレート設定でオフにされていない限り) 任意のメッセージをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-382">Any member of a channel will be able to pin any message (unless turned off via channel moderation settings).</span></span>

- <span data-ttu-id="4f58d-383">**アプリ カタログに送信:** この画面の左下に [アプリ カタログに送信] リンクが表示されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-383">**Submit to app catalog:** You’ll see a Submit to app catalog link on the lower left of this screen.</span></span> <span data-ttu-id="4f58d-384">App Studio と Visual Studio に加えて、承認のためにアプリを送信できるもう 1 つの場所です。</span><span class="sxs-lookup"><span data-stu-id="4f58d-384">In addition to App Studio and Visual Studio, it’s another place where you can submit apps for approval.</span></span>

- <span data-ttu-id="4f58d-385">**InVision によるフリーハンドを使用して、ポップアウトされた会議エクスペリエンスでホワイトボードを作成する:** InVision によるフリーハンド アプリを使用して、ポップアウトされた会議エクスペリエンスでホワイトボードを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-385">**Use Freehand by Invision to whiteboard in the popped out meeting experience:** You can now use the Freehand by Invision app to whiteboard in any meeting you take in the popped out meeting experience.</span></span> <span data-ttu-id="4f58d-386">共有コンテンツ トレイからフリーハンド アプリを選択してインストールし、同僚とのホワイトボード セッションを開始することで、シームレスにブレーンストーミングを開始できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-386">Seamlessly start brainstorming by selecting the Freehand app from the share content tray and, installing it, and starting the whiteboarding session with your colleagues!</span></span>

### <a name="word"></a><span data-ttu-id="4f58d-387">Word</span><span class="sxs-lookup"><span data-stu-id="4f58d-387">Word</span></span>

- <span data-ttu-id="4f58d-388">**Office に iPhone の写真を直接挿入する:** スマートフォンから HEIC 形式の写真をシームレスに Office へ挿入できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-388">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="4f58d-389">変換は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="4f58d-389">No conversion required.</span></span><br /><span data-ttu-id="4f58d-390">[ブログの投稿](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="4f58d-390">See details in [blog post](https://insider.office.com/ja-JP/blog/insert-apple-photos-into-office-easily)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-393">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-393">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="4f58d-394">Access</span><span class="sxs-lookup"><span data-stu-id="4f58d-394">Access</span></span>

- <span data-ttu-id="4f58d-395">Office 以外のアプリケーションから DAO を使用すると、アプリケーションが予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-395">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="outlook"></a><span data-ttu-id="4f58d-396">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-396">Outlook</span></span>

- <span data-ttu-id="4f58d-397">返信または転送時に中国語メッセージのヘッダーが読み取れなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-397">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="4f58d-398">OFT ファイルとして保存するときに中国語の文字が疑問符に変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-398">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="4f58d-399">クラウド設定を有効にしているユーザーに対して、2つ目の空白の署名を作成するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-399">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


- <span data-ttu-id="4f58d-400">ユーザーに対してクラウド設定が既定でオンにならない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-400">We fixed a n issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="4f58d-401">ユーザーの署名への変更が保存できない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-401">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="4f58d-402">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-402">PowerPoint</span></span>

- <span data-ttu-id="4f58d-403">これは、PresentationBeforeClose イベントを聞き、イベント ハンドラーの一部として Presentation.Saved プロパティをチェックするアドインがある場合、ドキュメントを閉じるときに保存プロンプトがループで表示される問題の修正です。</span><span class="sxs-lookup"><span data-stu-id="4f58d-403">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


### <a name="project"></a><span data-ttu-id="4f58d-404">Project</span><span class="sxs-lookup"><span data-stu-id="4f58d-404">Project</span></span>

- <span data-ttu-id="4f58d-405">プロジェクトを PWA からローカル mpp ファイルに保存すると、ユーザーが実際に変更していないデータに対して ProjectBeforeTaskChangeEvent が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-405">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="4f58d-406">リソースの配分状況が特定の方法で指定されているファイルを開くと、Project が予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-406">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="4f58d-407">プロジェクトを PWA からローカル mpp ファイルに保存すると、ユーザーが実際に変更していないデータに対して ProjectBeforeTaskChangeEvent が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-407">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="4f58d-408">タスクフォームタイプビュー内でラグが変更された場合、ProjectBeforeTaskChagne イベントの NewVal に正しい値がない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-408">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


### <a name="office-suite"></a><span data-ttu-id="4f58d-409">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-409">Office Suite</span></span>

- <span data-ttu-id="4f58d-410">Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-410">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="4f58d-411">このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-411">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>

- <span data-ttu-id="4f58d-412">Microsoft 365 エンドポイントのデータ損失防止が、ディスク上の Office ドキュメントを分類できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-412">Fixed an issue where Microsoft 365 Endpoint data loss prevention was unable to classify Office documents on disk.</span></span>


[//]: # (BUGDETAILS コンテンツ エンドを削除しないでください。終了)

## <a name="version-2009-october-21"></a><span data-ttu-id="4f58d-414">バージョン 2009 : 10 月 21 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-414">Version 2009: October 21</span></span>
<span data-ttu-id="4f58d-415">*バージョン 2009 (ビルド 13231.20418)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-415">*Version 2009 (Build 13231.20418)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-417">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-417">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="4f58d-418">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-418">Outlook</span></span>

- <span data-ttu-id="4f58d-419">ユーザーが代理人に編集者権限を付与できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-419">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="4f58d-420">ユーザーが検索結果を選択したときにアプリケーションが予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-420">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="4f58d-421">返信または転送時に中国語メッセージのヘッダーが読み取れなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-421">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="4f58d-422">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-422">PowerPoint</span></span>

- <span data-ttu-id="4f58d-423">ユーザーが別のスライドをクリックして表示するまで、Forms コンテンツ アドインが挿入後にレンダリングされない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-423">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-october-13"></a><span data-ttu-id="4f58d-425">バージョン2009: 10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-425">Version 2009: October 13</span></span>
<span data-ttu-id="4f58d-426">*バージョン2009 (ビルド 13231.20390)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-426">*Version 2009 (Build 13231.20390)*</span></span>

<span data-ttu-id="4f58d-427">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4f58d-427">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-429">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-429">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="4f58d-430">Project</span><span class="sxs-lookup"><span data-stu-id="4f58d-430">Project</span></span>

- <span data-ttu-id="4f58d-431">リソースの配分状況が特定の方法で指定されている場合に、Project がクラッシュすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-431">Fixed an issue where Project may crash on opening files where resource contours were specified in a certain manner.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-october-08"></a><span data-ttu-id="4f58d-433">バージョン 2009: 10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-433">Version 2009: October 08</span></span>
<span data-ttu-id="4f58d-434">*バージョン 2009 (ビルド 13231.20368)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-434">*Version 2009 (Build 13231.20368)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-436">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-436">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="4f58d-437">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-437">Outlook</span></span>

- <span data-ttu-id="4f58d-438">キャッシュされていない共有の予定表を検索するときに、結果が返されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-438">Addresses an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="4f58d-439">一部のユーザーの環境で、Outlook がオフラインの状態で予期せず起動する原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-439">Addresses an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="4f58d-440">代理人が別のメールボックスで共有フォルダーを開くと、断続的にエラーが表示される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-440">Addresses an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="4f58d-441">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-441">PowerPoint</span></span>

- <span data-ttu-id="4f58d-442">セキュリティ修正プログラムを適用して、保護ビューで PowerPoint ファイルを開くと、 IRM による保護が無効になる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-442">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


### <a name="office-suite"></a><span data-ttu-id="4f58d-443">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-443">Office Suite</span></span>

- <span data-ttu-id="4f58d-444">Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-444">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="4f58d-445">このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-445">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-september-28"></a><span data-ttu-id="4f58d-447">バージョン 2009: 9 月 28 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-447">Version 2009: September 28</span></span>
<span data-ttu-id="4f58d-448">*バージョン 2009 (ビルド13231.20262)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-448">*Version 2009 (Build 13231.20262)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="4f58d-450">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="4f58d-450">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="4f58d-451">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-451">Excel</span></span>

- <span data-ttu-id="4f58d-452">**図形を画像として保存する:** 簡単なクリック操作で図形、アイコン、その他のオブジェクトを画像ファイルとして保存し、別の場所で再利用することができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-452">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="4f58d-453">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-453">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="4f58d-454">**Power BI からデータ型を使用して組織データを取得する:** Power BI からの Excel データ型が Office 365 E5/A5 または Microsoft 365 E5/A5 を使用する組織の Insider にロールアウトされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-454">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="4f58d-455">必要な情報を入手し、簡単に更新することは、多くの日常のワークフローに欠かせません。</span><span class="sxs-lookup"><span data-stu-id="4f58d-455">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="4f58d-456">Excel のデータ型として、Power BI から会社または組織の情報へのアクセスを提供し、スプレッドシートにリンクされた情報を取り込む機能を拡張します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-456">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="4f58d-457">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-457">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="4f58d-458">[ブログの投稿](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="4f58d-458">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="4f58d-459">**数式で使用する変数を作成する:** LET 関数を使用してパフォーマンス、読みやすさ、および構成性を向上させます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-459">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="4f58d-460">この関数では、新規または既存の数式に名前付き変数を作成することができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-460">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="4f58d-461">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-461">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="4f58d-462">[ブログの投稿](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="4f58d-462">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="4f58d-463">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-463">Outlook</span></span>

- <span data-ttu-id="4f58d-464">**自動拡張オンライン アーカイブ検索:** 自動拡張オンライン アーカイブ検索を有効にします</span><span class="sxs-lookup"><span data-stu-id="4f58d-464">**Auto-Expanding Online Archive Search:** Enabling auto-expanding Online Archive Search</span></span>

- <span data-ttu-id="4f58d-465">**Outlook の新しいプロファイル カード:** Outlook の新しいプロファイル カードは、組織ビューの詳細を含み、Outlook Web のカード スタイルに一致します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-465">**New profile card for Outlook:** New profile card for Outlook including a better Organization view and matches the card style of Outlook Web.</span></span>

### <a name="teams"></a><span data-ttu-id="4f58d-466">Teams</span><span class="sxs-lookup"><span data-stu-id="4f58d-466">Teams</span></span>

- <span data-ttu-id="4f58d-467">**Microsoft Teams でファイルを共有:** [詳細情報](https://docs.microsoft.com/MicrosoftTeams/sharing-files-in-teams)</span><span class="sxs-lookup"><span data-stu-id="4f58d-467">**Sharing files in Microsoft Teams:** [Learn more](https://docs.microsoft.com/MicrosoftTeams/sharing-files-in-teams)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-470">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-470">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="4f58d-471">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-471">Outlook</span></span>

- <span data-ttu-id="4f58d-472">件名が空白の場合、一部の自動的に生成されたメールの本文が空で送信される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-472">Addresses an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="4f58d-473">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-473">PowerPoint</span></span>

- <span data-ttu-id="4f58d-474">特定のデータ オブジェクト タイプ (E2o) を大量に含むファイルの共同編集が遅くなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-474">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>


### <a name="project"></a><span data-ttu-id="4f58d-475">Project</span><span class="sxs-lookup"><span data-stu-id="4f58d-475">Project</span></span>

- <span data-ttu-id="4f58d-476">イベント コードの実行中に、[タスク フォーム] ビューから変更を加えようとするときに、[OK] ボタンをクリックしても変更が反映されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-476">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


### <a name="word"></a><span data-ttu-id="4f58d-477">Word</span><span class="sxs-lookup"><span data-stu-id="4f58d-477">Word</span></span>

- <span data-ttu-id="4f58d-478">スタイル ギャラリー ダイアログの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-478">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="4f58d-479">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-479">Office Suite</span></span>

- <span data-ttu-id="4f58d-480">この変更により、[エクスポート] ボタンをクリックしてもエクスポートされないという [アニメーション GIF にエクスポート] 機能の問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-480">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="4f58d-481">この変更では、[図の圧縮] ダイアログで一部のユーザー設定が保持されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-481">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-september-22"></a><span data-ttu-id="4f58d-483">バージョン 2008: 9 月 22 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-483">Version 2008: September 22</span></span>
<span data-ttu-id="4f58d-484">*バージョン 2008 (ビルド 13127.20508)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-484">*Version 2008 (Build 13127.20508)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-486">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-486">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4f58d-487">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-487">Excel</span></span>

- <span data-ttu-id="4f58d-488">シートの一番上の行を固定した後にクイック分析を使用すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-488">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="4f58d-489">IFNA () を使用する数式が含まれている場合、破損したワークブックに関する警告を発する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-489">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="4f58d-490">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-490">Outlook</span></span>

- <span data-ttu-id="4f58d-491">隅にある [X] をクリックして共有の予定表を閉じることができない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-491">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="4f58d-492">添付ファイルのアップロードのパフォーマンスの問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-492">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="4f58d-493">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-493">PowerPoint</span></span>

- <span data-ttu-id="4f58d-494">PowerPoint アプリのクラッシュの原因となった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-494">We have fixed an issue which was causing the crash in PowerPoint app.</span></span>


### <a name="visio"></a><span data-ttu-id="4f58d-495">Visio</span><span class="sxs-lookup"><span data-stu-id="4f58d-495">Visio</span></span>

- <span data-ttu-id="4f58d-496">テキストを配置するとリアルタイムのプレビューがクラッシュする問題がお客様から報告されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-496">Live preview crashes on text alignment reported by customers.</span></span> <span data-ttu-id="4f58d-497">7 月のフォークで最も多く報告されているクラッシュ。</span><span class="sxs-lookup"><span data-stu-id="4f58d-497">Top hitting crash of July fork.</span></span>


### <a name="word"></a><span data-ttu-id="4f58d-498">Word</span><span class="sxs-lookup"><span data-stu-id="4f58d-498">Word</span></span>

- <span data-ttu-id="4f58d-499">スタイル ギャラリー ダイアログの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-499">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="4f58d-500">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-500">Office Suite</span></span>

- <span data-ttu-id="4f58d-501">GIF/アニメーション model3D を使用したアイドル時の高い CPU 使用率を修正</span><span class="sxs-lookup"><span data-stu-id="4f58d-501">Fixes high CPU usage on idle with GIF/animated model3D</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-september-09"></a><span data-ttu-id="4f58d-503">バージョン 2008: 9 月 9 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-503">Version 2008: September 09</span></span>
<span data-ttu-id="4f58d-504">*バージョン 2008(ビルド13127.20408)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-504">*Version 2008 (Build 13127.20408)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-506">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-506">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="4f58d-507">Access</span><span class="sxs-lookup"><span data-stu-id="4f58d-507">Access</span></span>

- <span data-ttu-id="4f58d-508">テキストを編集するため [ズーム] ボックスを起動する (Shift + F2) ときに、Access がクラッシュする可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-508">This change fixes an issue that could cause Access to crash when launching the Zoom box (Shift + F2) to edit text.</span></span>


### <a name="excel"></a><span data-ttu-id="4f58d-509">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-509">Excel</span></span>

- <span data-ttu-id="4f58d-510">Format Painter を使用すると、特定の状況で Excel がクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-510">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>


### <a name="word"></a><span data-ttu-id="4f58d-511">Word</span><span class="sxs-lookup"><span data-stu-id="4f58d-511">Word</span></span>

- <span data-ttu-id="4f58d-512">図形のサイズを変更すると、ユーザーのコンテンツが失われる場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-512">We fixed an issue where the user might lose content when resize a shape.</span></span>


- <span data-ttu-id="4f58d-513">基本スタイルが標準スタイルで更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-513">We fixed an issue which the base styles are not updated with Normal style.</span></span>


### <a name="office-suite"></a><span data-ttu-id="4f58d-514">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-514">Office Suite</span></span>

- <span data-ttu-id="4f58d-515">この変更では、[図の圧縮] ダイアログで一部のユーザー設定が保持されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-515">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-august-31"></a><span data-ttu-id="4f58d-517">バージョン 2008: 8 月 31 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-517">Version 2008: August 31</span></span>
<span data-ttu-id="4f58d-518">*バージョン 2008 (ビルド 13127.20296)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-518">*Version 2008 (Build 13127.20296)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="4f58d-520">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="4f58d-520">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="4f58d-521">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-521">Excel</span></span>

- <span data-ttu-id="4f58d-522">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-522">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="4f58d-523">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-523">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="4f58d-524">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-524">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="4f58d-525">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-525">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="4f58d-526">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-526">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="4f58d-527">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="4f58d-527">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="outlook"></a><span data-ttu-id="4f58d-528">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-528">Outlook</span></span>

- <span data-ttu-id="4f58d-529">**メール内のリンクの改善:** ファイルへのリンクを含めると、ファイル名が URL に置き換わります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-529">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="4f58d-530">アクセス許可を変更して、すべての受信者がアクセスできるようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-530">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="4f58d-531">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-531">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="4f58d-532">[ブログの投稿](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="4f58d-532">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>



### <a name="powerpoint"></a><span data-ttu-id="4f58d-533">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-533">PowerPoint</span></span>

- <span data-ttu-id="4f58d-534">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-534">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="4f58d-535">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-535">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="4f58d-536">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-536">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="4f58d-537">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-537">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="4f58d-538">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-538">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="4f58d-539">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="4f58d-539">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="teams"></a><span data-ttu-id="4f58d-540">Teams</span><span class="sxs-lookup"><span data-stu-id="4f58d-540">Teams</span></span>

- <span data-ttu-id="4f58d-541">**コールマージ:** コールマージにより、エンドユーザーは、アクティブな保持された 1 対 1 の 通話を別の1 対 1 の通話または別のグループ通話に結合できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-541">**Call Merge:** Call Merge gives end users the capability to merge their active unheld 1-1 call into another 1-1 call or another group call.</span></span> <span data-ttu-id="4f58d-542">これは、Teams の VOIP 通話と PSTN 通話に適用されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-542">This applies to Teams VOIP calls and PSTN calls.</span></span>

- <span data-ttu-id="4f58d-543">**管理者は、Firstline ワーカーの出席状況をシフトベース (オンシフト、オフシフト) で構成できます:** 管理者は、シフト中、ビジー (シフト中に切り替えることができます)、シフト外といったシフトベースの出席状況を表示できるように Firstline ワーカーを構成できます。

</span><span class="sxs-lookup"><span data-stu-id="4f58d-543">**Admins can configure shift-based presence (On shift, Off shift) for their Firstline workers:** Admins can configure their firstline workers to have shift-based presence states: On shift, Busy (can be toggled when on shift), and Off shift.</span></span>

- <span data-ttu-id="4f58d-544">**Teams の Cortana 音声スキル:** Teams モバイルアプリの Cortana 音声スキルにより、ユーザーは自然な話し言葉を使用して、会議、コミュニケーション、コラボレーションといったタスクを簡単に実行できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-544">**Cortana voice skills in Teams:** Cortana voice skills in Teams mobile app help users perform meeting, communication and collaboration tasks simply using spoken natural language.</span></span> <span data-ttu-id="4f58d-545">ユーザーは、家事を色々こなしたり、犬の散歩をしたり、外出先で誰かと連絡する必要がある場合、Teams アプリのマイクボタンをクリックして Cortana に話しかけ、「ミーガンに電話する」や「次の会議にメッセージを送信する」といったリクエストを行うことができます。

</span><span class="sxs-lookup"><span data-stu-id="4f58d-545">Users can speak to Cortana by clicking on the microphone button in Teams app and make requests like “Call Megan” or “Send a message to my next meeting” if they need to connect with someone while juggling household chores or walking the dog or generally on the go.</span></span> <span data-ttu-id="4f58d-546">ユーザーは「次の会議に参加する」と言うだけで会議に参加したり、「午前中の予定を教えて」と質問してカレンダーを確認したりできます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-546">Users can join meetings simply by saying “Join my next meeting” or check their calendar by asking “what do I have this morning”.</span></span> <span data-ttu-id="4f58d-547">会議または通話に入ると、会議ステージのオーバーフローメニューから Cortana を呼び出して、名前または番号によるメンバーの追加 (「通話にミーガンを追加」)、デッキプレゼンテーション (「プレゼンテーション 四半期レビューデッキ」) またはスライドの紹介 (「付録スライドを紹介」) といった、一般的な会議のタスクを実行したりできます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-547">Once in a meeting or a call, they can invoke Cortana from the overflow menu in the meeting stage and perform typical in-meeting tasks like adding people by name or number (“Add Megan to the call”), deck presentation (“present the quarterly review deck”) or navigating slides (“Go to the appendix slide”).</span></span> <span data-ttu-id="4f58d-548">この機能がサポートするその他の機能としては、ファイルの検索と共有、検索、およびTeamsアプリ内での一般的な移動 (「Johnとのチャットを開く、未読のアクティビティに移動する、メンションに移動する」など) があります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-548">Other things that the feature supports are finding and sharing files, search, and generally navigating within the Teams app (“Open my chat with John, Go to my unread activity, Go to my mentions etc.).</span></span> <span data-ttu-id="4f58d-549">チーム内の Cortana は、[オンラインサービス規約 (OST) ](https://www.microsoft.com/licensing/product-licensing/products)に反映されているように、Cortana エンタープライズサービスと同じエンタープライズレベルのプライバシー、セキュリティ、およびコンプライアンスの約束を満たしています。</span><span class="sxs-lookup"><span data-stu-id="4f58d-549">Cortana in Teams meets the same enterprise-level privacy, security, and compliance promises for Cortana enterprise services, as reflected in the [Online Services Terms (OST)](https://www.microsoft.com/licensing/product-licensing/products).</span></span>

- <span data-ttu-id="4f58d-550">**グループチャットの拡大:** Teams で 250 人がグループチャットに参加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-550">**Group chat increase:** Teams added the ability to now have 250 participants in a group chat.</span></span>

- <span data-ttu-id="4f58d-551">**シフトによるタグ付け:** この機能を使用すると、 Teams の [シフトアプリ](https://support.microsoft.com/office/get-started-in-shifts-5f3e30d8-1821-4904-be26-c3cd25a497d6#bkmk_openshiftsappdesktop)で、スケジュールとシフトグループ名に一致するタグが自動的に割り当てられます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-551">**Tagging by Shift:** With this feature, people are automatically assigned tags that match their schedule and shift group name in the [Shifts app](https://support.microsoft.com/office/get-started-in-shifts-5f3e30d8-1821-4904-be26-c3cd25a497d6#bkmk_openshiftsappdesktop) in Teams.</span></span>

### <a name="word"></a><span data-ttu-id="4f58d-552">Word</span><span class="sxs-lookup"><span data-stu-id="4f58d-552">Word</span></span>

- <span data-ttu-id="4f58d-553">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-553">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="4f58d-554">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-554">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="4f58d-555">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-555">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="4f58d-556">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-556">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="4f58d-557">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-557">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="4f58d-558">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="4f58d-558">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="4f58d-559">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-559">Office Suite</span></span>

- <span data-ttu-id="4f58d-560">**タブ付きのウィンドウ**: アプリの右側にあるタブ UI を使用して、複数のウィンドウ間を切り替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-560">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="4f58d-561">UI は、2 つ以上のウィンドウが開かれている場合にのみ表示されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-561">The UI will only be visible when you have 2+ panes open.</span></span><br /><span data-ttu-id="4f58d-562">[ブログの投稿](https://blog-insider.office.com/2020/02/20/improved-pane-management/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="4f58d-562">See details in [blog post](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-565">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-565">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="4f58d-566">Access</span><span class="sxs-lookup"><span data-stu-id="4f58d-566">Access</span></span>

- <span data-ttu-id="4f58d-567">この問題は解決されました。これで、Office のクイック実行アプリケーション以外でも ODBC ドライバーを使用できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-567">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>


### <a name="outlook"></a><span data-ttu-id="4f58d-568">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-568">Outlook</span></span>

- <span data-ttu-id="4f58d-569">プロファイルに追加されたサブ アカウントから会議出席依頼を作成しようとした場合に、ユーザーのメール アドレスの代わりに空欄の From: フィールドが表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-569">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="4f58d-570">共有メールボックスを追加した後に、ユーザーがパブリック フォルダーに接続できない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-570">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="4f58d-571">特定の状況で代理人が会議を辞退したときに、マネージャーのカレンダーから削除されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-571">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="4f58d-572">共有カレンダーの改善機能を使用している一部のユーザーが、新しく追加された共有カレンダーを表示できない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-572">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="4f58d-573">クラウドの添付ファイルを操作するときに、ユーザーに時折クラッシュが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-573">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="4f58d-574">SharePoint ファイルに Smart Link を追加すると、一部の文字セットのユーザーにファイル名が正しく表示されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-574">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="4f58d-575">新しいメールに返信、または新しいメールを作成するときにユーザーにクラッシュが発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-575">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="4f58d-576">[ヘッダーのみダウンロード] オプションが選択されている POP アカウントから 4 件以上のメールを削除しようとするとクラッシュするという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-576">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="4f58d-577">一部のユーザーにスケジュール アシスタント ページが表示されない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-577">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="4f58d-578">これにより、受信者を編集しているときに不定期にクラッシュする問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-578">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="4f58d-579">コンパクト ビューを使用するときに異常が表示される原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-579">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="4f58d-580">右クリックのコンテキストメニューが検索コントロールに表示されない問題の原因を解決しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-580">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="4f58d-581">ユーザーが新しいメールに返信または作成するときに次のエラーを受け取る原因となった問題に対処します。「この Web ページのファイルの一部が予期された場所にありません。</span><span class="sxs-lookup"><span data-stu-id="4f58d-581">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="4f58d-582">この Web ページをダウンロードする必要がありますか? </span><span class="sxs-lookup"><span data-stu-id="4f58d-582">Do you want to download them anyway?</span></span> <span data-ttu-id="4f58d-583">Web ページが信頼できるソースからのものであることを確認したら、[はい] をクリックします。」</span><span class="sxs-lookup"><span data-stu-id="4f58d-583">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


### <a name="project"></a><span data-ttu-id="4f58d-584">Project</span><span class="sxs-lookup"><span data-stu-id="4f58d-584">Project</span></span>

- <span data-ttu-id="4f58d-585">SharePoint タスクリストに接続されているプロジェクトのプロジェクト終了日が更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-585">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="4f58d-586">リソースに複数のコスト単価表が定義されている場合に、残りのコストが正しく計算されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-586">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

### <a name="skype"></a><span data-ttu-id="4f58d-587">Skype</span><span class="sxs-lookup"><span data-stu-id="4f58d-587">Skype</span></span>

- <span data-ttu-id="4f58d-588">ダンス絵文字の肌の色を中間色に変更しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-588">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="4f58d-589">Word</span><span class="sxs-lookup"><span data-stu-id="4f58d-589">Word</span></span>

- <span data-ttu-id="4f58d-590">この変更により、以前の共同編集セッションの後に Office アプリケーションがサイレントな保存の失敗状態に陥ることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-590">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="4f58d-591">マクロ AutoOpen が AutoExec の前に実行されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-591">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-august-25"></a><span data-ttu-id="4f58d-593">バージョン 2007: 8 月 25 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-593">Version 2007: August 25</span></span>
<span data-ttu-id="4f58d-594">*バージョン 2007 (ビルド 13029.20460)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-594">*Version 2007 (Build 13029.20460)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-596">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-596">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4f58d-597">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-597">Excel</span></span>

- <span data-ttu-id="4f58d-598">LET () 関数を使用して、数式を含むファイルを保存しようとすると、エラーが発生することがあります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-598">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>


### <a name="outlook"></a><span data-ttu-id="4f58d-599">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-599">Outlook</span></span>

- <span data-ttu-id="4f58d-600">SharePoint ファイルに Smart Link を追加すると、一部の文字セットのユーザーにファイル名が正しく表示されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-600">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="4f58d-601">Outlook ユーザーにコンパクト ビューでのナビゲーションの問題が表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-601">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="4f58d-602">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-602">PowerPoint</span></span>

- <span data-ttu-id="4f58d-603">PowerPoint アプリでクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-603">We have fixed a crash issue with PowerPoint app.</span></span>


### <a name="word"></a><span data-ttu-id="4f58d-604">Word</span><span class="sxs-lookup"><span data-stu-id="4f58d-604">Word</span></span>

- <span data-ttu-id="4f58d-605">新しいメールに返信または作成するときにユーザーにクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-605">Addresses an issue that caused users to experience a crash when replying to or composing new mail.</span></span>


### <a name="office-suite"></a><span data-ttu-id="4f58d-606">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-606">Office Suite</span></span>

- <span data-ttu-id="4f58d-607">以前の Web サービス ベースの [共有] ウィンドウで、[共有] ウィンドウが開いているときに文書を閉じるとクラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-607">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="4f58d-608">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-608">This is now fixed.</span></span>


- <span data-ttu-id="4f58d-609">特定の状況下で UI 要素またはコンテンツが表示されない問題を修正しました。特に、発表者ツールのオン/オフ、または複数のモニターの使用に関して発生しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-609">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-august-11"></a><span data-ttu-id="4f58d-611">バージョン 2007: 8 月 11 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-611">Version 2007: August 11</span></span>
<span data-ttu-id="4f58d-612">*バージョン 2007 (ビルド 13029.20344)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-612">*Version 2007 (Build 13029.20344)*</span></span>

<span data-ttu-id="4f58d-613">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4f58d-613">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-615">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-615">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="4f58d-616">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-616">Outlook</span></span>

- <span data-ttu-id="4f58d-617">Outlook で検索候補を取得できない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-617">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="4f58d-618">ユーザーがペルソナ情報を取得しようとしたときにクラッシュする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-618">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


### <a name="project"></a><span data-ttu-id="4f58d-619">Project</span><span class="sxs-lookup"><span data-stu-id="4f58d-619">Project</span></span>

- <span data-ttu-id="4f58d-620">正常ではない状態になったプロジェクトを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-620">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-july-30"></a><span data-ttu-id="4f58d-622">バージョン 2007: 7 月 30 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-622">Version 2007: July 30</span></span>
<span data-ttu-id="4f58d-623">*バージョン 2007 (ビルド 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-623">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="4f58d-625">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="4f58d-625">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="4f58d-626">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-626">Excel</span></span>

- <span data-ttu-id="4f58d-627">**PDF に接続:** PDF からデータに接続、インポート、更新します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-627">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="4f58d-628">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-628">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="4f58d-629">**他のユーザーを混乱させずに、フィルター処理して並べ替える:**、Sheet View で他のユーザーとの共同作業を行いながら Excel ファイルの並べ替えやフィルター処理ができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-629">**Filter and sort without disrupting others:** You can now sort and filter your Excel file while collaborating with others with Sheet View.</span></span> <span data-ttu-id="4f58d-630">この新機能により、文書を共同編集しているときに、他のユーザーの並べ替えやフィルター処理による影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="4f58d-630">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span> [<span data-ttu-id="4f58d-631">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-631">Learn more</span></span>](https://support.office.com/article/0eea3dc5-d7d1-44c5-a953-25ebfbd6c1a6)

- <span data-ttu-id="4f58d-632">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-632">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

- <span data-ttu-id="4f58d-633">**Excel で Power BI のデータセットからピボットテーブルを作成する:** Power BI に保存されているデータセットに接続されている Excel のピボットテーブルを数回のクリックで作成できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-633">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="4f58d-634">これにより、ピボットテーブルと Power BI の両方を最大限に活用できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-634">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="4f58d-635">セキュリティで保護された Power BI データセットからピボットテーブルを使って、データの計算、集計、分析を行います。</span><span class="sxs-lookup"><span data-stu-id="4f58d-635">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="4f58d-636">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-636">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="4f58d-637">[ブログの投稿](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="4f58d-637">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="4f58d-638">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-638">Outlook</span></span>

- <span data-ttu-id="4f58d-639">**クイック投票を使用して、Outlook で投票を作成:** 簡単に投票を作成し、票を収集して、メールに結果を表示します。[詳細情報](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="4f58d-639">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="4f58d-640">**メールの一部として画像を送信するときに、画像を高品質に維持する:** メールの内容の一部として画像を送信するときに、画像の圧縮を制限するための新しい Outlook の設定を使用できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-640">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

- <span data-ttu-id="4f58d-641">**以前のセッションからアイテムを素早く再開する:** 以前の Outlook セッションからアイテムを素早く再開するためのオプションが追加されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-641">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="4f58d-642">Outlook がクラッシュした場合でも、または終了した場合でも、アプリを再び開くと、すばやくアイテムを再起動することができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-642">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="4f58d-643">この機能は既定でオンになっています。</span><span class="sxs-lookup"><span data-stu-id="4f58d-643">This feature is on by default.</span></span> <span data-ttu-id="4f58d-644">オフにするには、[オプション] > [一般] > [開始オプション] に移動します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-644">To turn it off, go to Options > General > Start up Options.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="4f58d-645">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-645">PowerPoint</span></span>

- <span data-ttu-id="4f58d-646">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-646">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="teams"></a><span data-ttu-id="4f58d-647">Teams</span><span class="sxs-lookup"><span data-stu-id="4f58d-647">Teams</span></span>

- <span data-ttu-id="4f58d-648">**簡素化された新しい通知設定:** 機能が強化され、やり方がより簡素化された通知設定をユーザーが管理できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-648">**New simplified notification settings:** Users can now manage their notifications settings in a more simplified manner with enhanced functionalities.</span></span>

- <span data-ttu-id="4f58d-649">**Teams でWindows ネイティブ通知をサポート:** ユーザーはバナーに組み込まれた Teams、または Windows のネイティブ バナーのいずれかを使用して、通知配信の優先手段を選択できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-649">**Windows Native Notification are now Supported on Teams:** Users can now select their preferred means of notification delivery, either through teams built in banners or the windows native banners.</span></span>

- <span data-ttu-id="4f58d-650">**[チャンネル情報] ウィンドウ:** チャンネルヘッダーの "チャンネル情報" アイコンを選択したときに、[チャンネルの説明]、[最近の寄稿者]、[メンバー] に加えて、システム メッセージの新しいホームを含むチャンネル情報の概要を表示するウィンドウが開きます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-650">**Channel Info Pane:** When selecting on the "Channel info" icon in the channel header, a pane will open where you will see a summary of channel information including the channel description, a list of recent contributors and members, as well as the new home for system messages.</span></span>

- <span data-ttu-id="4f58d-651">**チャット通知のプレビューをオフにする:**、ユーザーは設定を変更したり、チャット通知トーストのプレビューを管理したりすることができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-651">**Turn off previews for your chat notifications:** Users can change settings and manage previews for their chat notification toasts.</span></span>

- <span data-ttu-id="4f58d-652">**返信の候補:** Teams ユーザーに、自分の会話への返信の候補を提案する機能が追加されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-652">**Suggested replies:** We added the ability for Teams users to have a suggested reply to their conversations.</span></span> <span data-ttu-id="4f58d-653">これらの候補が有効になっている場合は、チャット メッセージの下部に表示されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-653">These suggestions will appear at the bottom of a chat message if they are enabled.</span></span> <span data-ttu-id="4f58d-654">メッセージへの返信をすばやく簡単に作成できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-654">They make replying to messages quick and easy!</span></span>

### <a name="word"></a><span data-ttu-id="4f58d-655">Word</span><span class="sxs-lookup"><span data-stu-id="4f58d-655">Word</span></span>

- <span data-ttu-id="4f58d-656">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-656">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

- <span data-ttu-id="4f58d-657">**テキストをベクター内で保持:** 地図やグラフ、その他の SVG ベクターを Excel、Word、PowerPoint で変換する場合、それらのオブジェクトの中にテキストを保持できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-657">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-660">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-660">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="4f58d-661">Access</span><span class="sxs-lookup"><span data-stu-id="4f58d-661">Access</span></span>

- <span data-ttu-id="4f58d-662">この修正プログラムでは、特定のクエリを実行しようとすると、"クエリが複雑すぎます" というエラーメッセージが表示される問題に対処しています。</span><span class="sxs-lookup"><span data-stu-id="4f58d-662">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex".</span></span>

### <a name="excel"></a><span data-ttu-id="4f58d-663">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-663">Excel</span></span>

- <span data-ttu-id="4f58d-664">改ページ プレビューで複数のシートを含むブックを読み込むときにエラーやハングが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-664">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>


### <a name="outlook"></a><span data-ttu-id="4f58d-665">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-665">Outlook</span></span>

- <span data-ttu-id="4f58d-666">保護されたコンテキストから保護されていないコンテキストに返信するとき、送信元アドレスを切り替えると、CLP のユーザーにクラッシュが発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-666">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="4f58d-667">[共有フォルダーのダウンロード] がチェックされていない場合、共有された予定表の会議の [返信オプション] に [転送を許可する] オプションが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-667">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="4f58d-668">管理者のカレンダー上で既存のカレンダーの予定を編集するときに代理人がエラーを受け取る問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-668">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="4f58d-669">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカルコンピューターに保存できない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-669">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="4f58d-670">スケジュール アシスタント ページが表示されない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-670">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="4f58d-671">インシデント通知アラートのフォーマットの問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-671">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

### <a name="project"></a><span data-ttu-id="4f58d-672">Project</span><span class="sxs-lookup"><span data-stu-id="4f58d-672">Project</span></span>

- <span data-ttu-id="4f58d-673">[リソースの割り当て] ダイアログ ボックスで選択されているタスクが、[タスク ボード] ビューで選択したタスクと異なる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-673">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="4f58d-674">複数の依存関係があるタスクを貼り付けると、すべての依存関係が正しくコピーされるわけではない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-674">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="4f58d-675">Project から SharePoint ドキュメント ライブラリに PDF/XPS を保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-675">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


### <a name="office-suite"></a><span data-ttu-id="4f58d-676">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-676">Office Suite</span></span>

- <span data-ttu-id="4f58d-677">製品版への移行が完了した場合でも、ランタイムメッセージが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-677">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="4f58d-678">この問題の修正では、サービスが追加された製品を適切に計算するようにしました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-678">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="4f58d-679">新たに追加された製品をフィルターで除外し (新しい構成に存在することも確認)、既存の製品リリース ID の最後に追加しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-679">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-july-28"></a><span data-ttu-id="4f58d-681">バージョン 2006: 7 月 28 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-681">Version 2006: July 28</span></span>
<span data-ttu-id="4f58d-682">*バージョン 2006 (ビルド 13001.20498)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-682">*Version 2006 (Build 13001.20498)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-684">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-684">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4f58d-685">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-685">Excel</span></span>

- <span data-ttu-id="4f58d-686">改ページ プレビューで複数のシートを含むブックを読み込むときにエラーやハングが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-686">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>


### <a name="outlook"></a><span data-ttu-id="4f58d-687">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-687">Outlook</span></span>

- <span data-ttu-id="4f58d-688">SVG 画像のコピーと貼り付けの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-688">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="word"></a><span data-ttu-id="4f58d-689">Word</span><span class="sxs-lookup"><span data-stu-id="4f58d-689">Word</span></span>

- <span data-ttu-id="4f58d-690">SVG 画像のコピーと貼り付けの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-690">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="office-suite"></a><span data-ttu-id="4f58d-691">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-691">Office Suite</span></span>

- <span data-ttu-id="4f58d-692">タイミングの問題で、Office ファイルを閉じるときにクラッシュすることがあります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-692">A timing issue could cause a crash when closing office files.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-july-14"></a><span data-ttu-id="4f58d-694">バージョン 2006: 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-694">Version 2006: July 14</span></span>
<span data-ttu-id="4f58d-695">*バージョン 2006 (ビルド 13001.20384)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-695">*Version 2006 (Build 13001.20384)*</span></span>

<span data-ttu-id="4f58d-696">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4f58d-696">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-698">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-698">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="4f58d-699">アクセス</span><span class="sxs-lookup"><span data-stu-id="4f58d-699">Access</span></span>

- <span data-ttu-id="4f58d-700">ID (オートナンバーなど) フィールドが含まれるリンク付きの SQL 表を挿入する場合についての問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-700">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

### <a name="excel"></a><span data-ttu-id="4f58d-701">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-701">Excel</span></span>

- <span data-ttu-id="4f58d-702">読み取り専用モードのブックに対して、ドキュメント分類を自動的に行った可能性があります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-702">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="4f58d-703">アカウントからサインアウトした場合にデータ接続を作成しようとすると発生する可能性があるクラッシュを修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-703">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="onenote"></a><span data-ttu-id="4f58d-704">OneNote</span><span class="sxs-lookup"><span data-stu-id="4f58d-704">OneNote</span></span>

- <span data-ttu-id="4f58d-705">リソースの使用率を低下させて、共同編集状態の検出機能を改善します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-705">Improve detection of co-authoring status to reduce resource utilization.</span></span>

### <a name="outlook"></a><span data-ttu-id="4f58d-706">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-706">Outlook</span></span>

- <span data-ttu-id="4f58d-707">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカルコンピューターに保存できない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-707">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="4f58d-708">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-708">Office Suite</span></span>

- <span data-ttu-id="4f58d-709">以前の AppV51 の回帰を修正するために、新しい AppV51 drop をバックポートします。</span><span class="sxs-lookup"><span data-stu-id="4f58d-709">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="4f58d-710">レジストリ TabProcGrowth の値がREG_SZ型でアドインがアクティブ化されている場合に、Windows の Office ホストがクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-710">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2006-june-30"></a><span data-ttu-id="4f58d-712">バージョン 2006: 6 月 30 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-712">Version 2006: June 30</span></span>
<span data-ttu-id="4f58d-713">*バージョン 2006 (ビルド 13001.20266)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-713">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="4f58d-715">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="4f58d-715">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="4f58d-716">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-716">Excel</span></span>

- <span data-ttu-id="4f58d-717">**長いファイル名**: Windows デスクトップ版の Excel は、名前とパスが最大400文字の OneDrive/SharePoint ファイルをサポートするようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-717">**Longer file names:** Excel for Windows desktop now supports OneDrive/SharePoint files with names and paths of up to 400 characters.</span></span>

- <span data-ttu-id="4f58d-718">**Realtimedata (RTD) の改善:** Office 365 バージョン 2002 の月間チャネル以降、ExcelのRealTimeData (RTD) 関数は、Excel 2010 のスプレッドシートのデータ計算よりもはるかに高速になります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-718">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="4f58d-719">基盤となるメモリとデータ構造のボトルネックを取り除き、マルチスレッド再計算  (MTR) の使用可能なすべてのスレッドで計算できるようにスレッドセーフにしました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-719">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="4f58d-720">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-720">Outlook</span></span>

- <span data-ttu-id="4f58d-721">**Outlook でのメール作成時の @ メンションの候補表示を無効にするオプションが追加されました。**@ メンション ピッカーが便利どころか迷惑だと感じていますか?</span><span class="sxs-lookup"><span data-stu-id="4f58d-721">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="4f58d-722">今後は、必要に応じてオフにすることができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-722">Now you can turn it off if you prefer.</span></span><br /><span data-ttu-id="4f58d-723">[ブログの投稿](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="4f58d-723">See details in [blog post](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)</span></span>

- <span data-ttu-id="4f58d-724">**IT 管理者向けのインシデント通知:** Microsoft 365 テナントのグローバル管理者および Office Apps 管理者は、Outlook for Windows の新しい右側のパネル通知により、ユーザーに影響する Outlook および O365 Exchange インシデントについて通知されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-724">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="4f58d-725">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-725">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- <span data-ttu-id="4f58d-726">**Outlook トースト通知に追加されたその他のボタン:** Outlook for Windows 10で Outlook を実行しているときに Outlook トースト通知にクイック アクション ボタンが表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-726">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10</span></span>

### <a name="powerpoint"></a><span data-ttu-id="4f58d-727">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-727">PowerPoint</span></span>

- <span data-ttu-id="4f58d-728">**PowerPoint でのストリーム ビデオのパフォーマンス向上:**、ビデオの読み込み時間を最小限に抑え、快適な表示を実現するために Microsoft Stream ビデオの再生パフォーマンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-728">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="4f58d-729">お客様の社内ビデオを使用して、Microsoft Stream でより適切なプレゼンテーションを作成します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-729">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="teams"></a><span data-ttu-id="4f58d-730">Teams</span><span class="sxs-lookup"><span data-stu-id="4f58d-730">Teams</span></span>

- <span data-ttu-id="4f58d-731">**PSTN の参加者の電話番号は、外部ユーザーからマスクされます**。Teams 会議でオーディオ会議を有効にしているお客様は、組織の外部から参加しているユーザーに PSTN 参加者の電話番号をマスクします。</span><span class="sxs-lookup"><span data-stu-id="4f58d-731">**PSTN participant phone numbers are masked from external users:** For customers with Audio Conferencing enabled for their Teams meetings, we will mask the PSTN participant's phone number to users who have joined from outside of your organization.</span></span>

- <span data-ttu-id="4f58d-732">**チャネル通知の設定を管理する簡単な方法:** チームやチャネルのリストを通して、またはチャネル ヘッダーから、ワンクリックで、またはユーザー設定によって、ユーザーはすべてのアクティビティのオンとオフを切り替えることで、お好きな順序を設定できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-732">**Simplified way to manage your channel notification settings:** Through the teams and channels list or from the channel header, the users can quickly manage their notification settings by turning all activity on or off with a single click or diving deep into custom to set their preferred permutations.</span></span>

- <span data-ttu-id="4f58d-733">**Walkie Talkie :** プッシュツートークを使用した、インスタント音声コミュニケーション。</span><span class="sxs-lookup"><span data-stu-id="4f58d-733">**Walkie Talkie:** Instant voice communication using push-to-talk.</span></span>

### <a name="word"></a><span data-ttu-id="4f58d-734">Word</span><span class="sxs-lookup"><span data-stu-id="4f58d-734">Word</span></span>

- <span data-ttu-id="4f58d-735">**スクリーン リーダーでの操作の確認:** 操作の確認は、重要なアクセシビリティ要件です。</span><span class="sxs-lookup"><span data-stu-id="4f58d-735">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="4f58d-736">Windows からの新しい通知 API の導入により、操作の成功をスクリーン リーダーのユーザーに通知できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-736">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="4f58d-737">切り取り、コピー、貼り付け、太字、斜体、下線、元に戻す、やり直し、自動修正、および自動大文字化が、Win32 Word のナレーター ユーザーにすべて通知されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-737">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="4f58d-738">この機能を有効にするには、Windows + Ctrl + Enter キーを押してナレーターをオンにします。</span><span class="sxs-lookup"><span data-stu-id="4f58d-738">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-741">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-741">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="4f58d-742">Access</span><span class="sxs-lookup"><span data-stu-id="4f58d-742">Access</span></span>

- <span data-ttu-id="4f58d-743">クエリの実行に予想よりも約2倍の時間がかかっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-743">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>


### <a name="excel"></a><span data-ttu-id="4f58d-744">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-744">Excel</span></span>

- <span data-ttu-id="4f58d-745">SharePoint/OneDrive に保存すると、ユーザー設定のリボンタブの CustomUI XML が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-745">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>


### <a name="outlook"></a><span data-ttu-id="4f58d-746">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-746">Outlook</span></span>

- <span data-ttu-id="4f58d-747">ドラッグ アンド ドロップによってファイル システムにコピーされた添付ファイルの作成日が、4501年1月1日に設定された問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-747">Addressed an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>

- <span data-ttu-id="4f58d-748">共有された予定表の改良版のユーザーに予定表のエラーが表示される問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-748">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="4f58d-749">Outlook で、受信トレイ修復ツールを実行するように促す表示が継続的に発生していた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-749">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="4f58d-750">クラウド設定が有効になっているときに、Ctrl キーを押しながらクリックすると動作が停止する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-750">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>


- <span data-ttu-id="4f58d-751">Suggest a Feature で機能を検索しても結果が返されず、ユーザーが新しい機能のアイデアを提出するオプションがないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-751">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


### <a name="project"></a><span data-ttu-id="4f58d-752">Project</span><span class="sxs-lookup"><span data-stu-id="4f58d-752">Project</span></span>

- <span data-ttu-id="4f58d-753">URL が .com で終了している場合に、Project Web App からプロジェクト デスクトップ クライアントでプロジェクトを開くことができない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-753">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="4f58d-754">プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-754">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>


- <span data-ttu-id="4f58d-755">100% 完了とマークされているタスクが、100% 未満のタスクに間違って変更されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-755">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="4f58d-756">Word</span><span class="sxs-lookup"><span data-stu-id="4f58d-756">Word</span></span>

- <span data-ttu-id="4f58d-757">URL にクエリ コンポーネントが含まれている場合にカスタム ドキュメント配信 (aspx) から Word ドキュメントを開く問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-757">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2005-june-24"></a><span data-ttu-id="4f58d-759">バージョン 2005: 6 月 24 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-759">Version 2005: June 24</span></span>
<span data-ttu-id="4f58d-760">*バージョン 2005 (ビルド 12827.20470)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-760">*Version 2005 (Build 12827.20470)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-762">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-762">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="4f58d-763">Access</span><span class="sxs-lookup"><span data-stu-id="4f58d-763">Access</span></span>

- <span data-ttu-id="4f58d-764">このバグは修正されました。アプリケーションのクラッシュを発生させずに、コードに日付/時刻の拡張データ型を呼び出すことができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-764">This bug has now been fixed; you should be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span> <span data-ttu-id="4f58d-765">問題が発生した場合は、チームにお知らせください。</span><span class="sxs-lookup"><span data-stu-id="4f58d-765">Please let the team know if you encounter further issues.</span></span>


- <span data-ttu-id="4f58d-766">この問題は修正されました。これで、最新の Access バージョンに戻すことができるようになりました。さらに、DAO/VBA を使用して10進数データ型を管理および編集することができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-766">This issue has now been fixed; you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span> <span data-ttu-id="4f58d-767">データ型を使用して問題が発生した場合は、Access チームにお知らせください。</span><span class="sxs-lookup"><span data-stu-id="4f58d-767">Please let the Access team know if you encounter any further issues with using our data type.</span></span>


### <a name="excel"></a><span data-ttu-id="4f58d-768">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-768">Excel</span></span>

- <span data-ttu-id="4f58d-769">SharePoint/OneDrive に保存すると、ユーザー設定のリボンタブの CustomUI XML が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-769">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>





### <a name="outlook"></a><span data-ttu-id="4f58d-770">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-770">Outlook</span></span>

- <span data-ttu-id="4f58d-771">M365 Business Plus プランのサービスを利用していたユーザーがデータ損失防止の保護ポリシー ヒントを有効にできない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-771">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>


- <span data-ttu-id="4f58d-772">ドラッグ アンド ドロップによってファイル システムにコピーされた添付ファイルの作成日が、4501年1月1日に設定された問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-772">Addressed an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="4f58d-773">ユーザーがOutlook ルールを更新すると、「&quot;このコンピューターのルールは、Microsoft Exchange のルールと異なります&quot;」 と表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-773">Addressed an issue that caused users to see the &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; message when updating their rules in Outlook.</span></span>


- <span data-ttu-id="4f58d-774">共有された予定表の改良版のユーザーに予定表のエラーが表示される問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-774">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="4f58d-775">一部のシナリオで、断続的なハングやクラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-775">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>


- <span data-ttu-id="4f58d-776">Outlook で、受信トレイ修復ツールを実行するように促す表示が継続的に発生していた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-776">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="4f58d-777">Suggest a Feature で機能を検索しても結果が返されず、ユーザーが新しい機能のアイデアを提出するオプションがないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-777">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="4f58d-778">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-778">PowerPoint</span></span>

- <span data-ttu-id="4f58d-779">提案ウィンドウでクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-779">We have fixed a crash issue with suggestion pane.</span></span>


### <a name="project"></a><span data-ttu-id="4f58d-780">Project</span><span class="sxs-lookup"><span data-stu-id="4f58d-780">Project</span></span>

- <span data-ttu-id="4f58d-781">100% 完了とマークされているタスクが、100% 未満のタスクに間違って変更されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-781">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="4f58d-782">Word</span><span class="sxs-lookup"><span data-stu-id="4f58d-782">Word</span></span>

- <span data-ttu-id="4f58d-783">一部のアプリケーションからコンテンツをドラッグしたときにクラッシュする問題の原因となっていた可能性がある問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-783">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="4f58d-784">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-784">Office Suite</span></span>

- <span data-ttu-id="4f58d-785">この変更により、Gif や3D モデルなどのアニメーション コンテンツを読み込んだり、再生したりするときに、ハングする可能性があります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-785">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>




[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-june-09"></a><span data-ttu-id="4f58d-787">バージョン 2005: 6月 9 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-787">Version 2005: June 09</span></span>
<span data-ttu-id="4f58d-788">*バージョン 2005 (ビルド 12827.20336)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-788">*Version 2005 (Build 12827.20336)*</span></span>

<span data-ttu-id="4f58d-789">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4f58d-789">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="feature-updates"></a><span data-ttu-id="4f58d-790">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="4f58d-790">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="4f58d-791">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-791">Excel</span></span>

- <span data-ttu-id="4f58d-792">**[描画] の [ツール] ボックスのなげなわと消しゴム:** 描画ツールを使用しているときに、[描画] の [ツール] ボックスでなげなわと消しゴムを使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-792">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="4f58d-793">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-793">PowerPoint</span></span>

- <span data-ttu-id="4f58d-794">**[描画] の [ツール] ボックスのなげなわと消しゴム:** 描画ツールを使用しているときに、[描画] の [ツール] ボックスでなげなわと消しゴムを使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-794">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>

### <a name="word"></a><span data-ttu-id="4f58d-795">Word</span><span class="sxs-lookup"><span data-stu-id="4f58d-795">Word</span></span>

- <span data-ttu-id="4f58d-796">**[描画] の [ツール] ボックスのなげなわと消しゴム:** 描画ツールを使用しているときに、[描画] の [ツール] ボックスでなげなわと消しゴムを使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-796">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>




[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-799">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-799">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4f58d-800">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-800">Excel</span></span>

- <span data-ttu-id="4f58d-801">ピボットテーブルをチャート シートに挿入しようとしたときに Excel がクラッシュする場合がある問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-801">Addresses an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="4f58d-802">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-802">PowerPoint</span></span>

- <span data-ttu-id="4f58d-803">これにより、ユーザーがファイルに対してモダンおよびレガシのコメントを持っていて、コメントの更新をトリガーすると、クラッシュが修正されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-803">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

### <a name="project"></a><span data-ttu-id="4f58d-804">Project</span><span class="sxs-lookup"><span data-stu-id="4f58d-804">Project</span></span>

- <span data-ttu-id="4f58d-805">プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-805">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

### <a name="office-suite"></a><span data-ttu-id="4f58d-806">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-806">Office Suite</span></span>

- <span data-ttu-id="4f58d-807">Bing アドオンのインストール検証を既定で true に設定し、MSI のリターン成功をインストール成功とみなすことで、ValidateInstall のエラー率の問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-807">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2005-june-02"></a><span data-ttu-id="4f58d-809">バージョン 2005: 6 月 2 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-809">Version 2005: June 02</span></span>
<span data-ttu-id="4f58d-810">*バージョン 2005 (ビルド 12827.20268)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-810">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="4f58d-812">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="4f58d-812">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="4f58d-813">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-813">Excel</span></span>

- <span data-ttu-id="4f58d-814">**新しいデータ型を自動的に使用する :** 可能性のある株式や地理的な場所に似たデータ値を入力すると、Excel は、関連付けられた該当する株価や地理といったデータ型に変換することを提案します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-814">**Automatically use new data types:** When you type a data value that resembles a stock or a geographic location, Excel offers to convert it to the right connected data type - Stocks or Geography.</span></span> [<span data-ttu-id="4f58d-815">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-815">Learn more</span></span>](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- <span data-ttu-id="4f58d-816">**アニメーション Gif を使用してストーリーを伝える :** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-816">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>

### <a name="outlook"></a><span data-ttu-id="4f58d-817">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-817">Outlook</span></span>

- <span data-ttu-id="4f58d-818">**グループ内のデータを保護:** グループを作成するときに選択する秘密度ラベルがグループ メール、ドキュメント、チーム サイトに適用されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-818">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

- <span data-ttu-id="4f58d-819">**より迅速かつ適切な結果:** 検索機能が更新され、よりスマート、迅速、かつ信頼性が高くなりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-819">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="4f58d-820">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-820">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="4f58d-821">**アニメーション Gif を使用してストーリーを伝える :** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-821">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>

- <span data-ttu-id="4f58d-822">**予定表が一新されます:** 予定表を簡単に読みやすくなるビジュアル アップデートをご覧ください。</span><span class="sxs-lookup"><span data-stu-id="4f58d-822">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="4f58d-823">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-823">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="4f58d-824">[ブログの投稿](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="4f58d-824">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="4f58d-825">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-825">PowerPoint</span></span>

- <span data-ttu-id="4f58d-826">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。[詳細については、こちらを参照してください。](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span><span class="sxs-lookup"><span data-stu-id="4f58d-826">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier [Learn more](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span></span>

- <span data-ttu-id="4f58d-827">**プレゼンテーション中に変更を同期する:** プレゼンテーションがスライド ショー モードであれば、いつでも変更を同期できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-827">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="4f58d-828">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-828">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="4f58d-829">[ブログの投稿](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="4f58d-829">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="4f58d-830">**クリッカーは不要: イヤホンでカバー:** Surface Earbuds を使用して、PowerPoint プレゼンテーションを制御します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-830">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="4f58d-831">機能のしくみ: ペアリングすると、PowerPoint の機能を有効にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-831">How it works:  Once paired, you'll need to enable the feature in PowerPoint.</span></span> <span data-ttu-id="4f58d-832">F5 キーを押すか、[スライド ショー] > [最初から] を選択してプレゼンテーションを開始します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-832">Start a presentation by pressing F5 or selecting Slide Show > From Beginning.</span></span>  <span data-ttu-id="4f58d-833">スライドショーでは、スライドを右クリックし、Surface Earbuds の設定で、[ジェスチャを使用してプレゼンテーションを制御] を選択します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-833">In Slide Show, right click on the slide and under Surface Earbuds Settings choose Use Gestures to Control Presentation.</span></span>  <span data-ttu-id="4f58d-834">この設定は、今後作成するすべてのプレゼンテーションに記録されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-834">This setting will be remembered for all future presentations.</span></span> <span data-ttu-id="4f58d-835">スライド ショー モードで左イヤホンを使用して前後にスワイプし、プレゼンテーションをナビゲートできます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-835">You can now can swipe forward and backward on the left earbud to navigate your presentations in Slide Show mode.</span></span>  <span data-ttu-id="4f58d-836">ダブルタップして、埋め込まれたビデオを再生または一時停止します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-836">Double tap to play or pause embedded videos.</span></span>  <span data-ttu-id="4f58d-837">重要: ジェスチャーを使用してプレゼンテーションを制御するには、Windows 10 の Surface Audio アプリで Surface Earbuds をペアリングする必要があります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-837">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="4f58d-838">Windows 10 で Surface Audio アプリを使い始める方法については、こちらをご覧ください。</span><span class="sxs-lookup"><span data-stu-id="4f58d-838">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="4f58d-839">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-839">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="teams"></a><span data-ttu-id="4f58d-840">Teams</span><span class="sxs-lookup"><span data-stu-id="4f58d-840">Teams</span></span>

- <span data-ttu-id="4f58d-841">**Teams 会議でのビデオ レイアウトの変更:** 近日中に、Teams 会議中に同時に表示できる参加者の数は、4名から9名に増加します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-841">**Changes to video layout in Teams meetings:** Soon, the number of participants that can be viewed simultaneously during a Teams meeting will increase from 4 to 9.</span></span>

- <span data-ttu-id="4f58d-842">**[ライブイベント] にシステム オーディオを含める**: ライブ イベントの発表者やプロデューサーは、ライブ イベント中にデスクトップまたはウィンドウ画面を共有するときに、システム オーディオを含めることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-842">**Include system audio in live events:** Presenters and producers in live events can now include system audio when sharing a desktop or window screen during the live event.</span></span> <span data-ttu-id="4f58d-843">これにより、共有するコンテンツのオーディオ部分をユーザーが聞くことができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-843">This will allow your users to hear any audio part of the content you are sharing.</span></span>

- <span data-ttu-id="4f58d-844">[**ダイヤルイン ユーザーによるロビーのバイパスを許可する :**] この設定では、スマートフォンでダイヤル インするユーザーが会議に直接参加するのか、[ユーザーの参加を自動的に許可する] の設定に関わらずロビーで待機するのかを制御します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-844">**Enable organizers to change lobby settings for dial-in participants:** This setting controls whether people who dial in by phone join the meeting directly or wait in the lobby regardless of the Automatically admit people setting.</span></span>

- <span data-ttu-id="4f58d-845">**会議で挙手しましょう:** ユーザーは会議で仮想の手を上げることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-845">**Raise Your Hand in Meetings:** Users can now raise a virtual hand in a meeting!</span></span> <span data-ttu-id="4f58d-846">他のユーザーは、会議のステージで参加者名簿の自分の名前の横で挙手しているのが表示されるのを見ることができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-846">Other participants will see your raised hand next to your name in the meeting stage and next to your name in the roster.</span></span>

- <span data-ttu-id="4f58d-847">**ビデオ会議の背景をカスタマイズ:** ビデオ会議を実施しているときに、使用する静的な背景画像を選択できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-847">**Customize meeting video backgrounds:** When you are meeting with video, you now have the choice of different static background images to use.</span></span> <span data-ttu-id="4f58d-848">この操作により、実際に座っている場所の背景ではない、選択した画像が表示されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-848">This will let you show this image and not the actual background of where you are sitting.</span></span>

- <span data-ttu-id="4f58d-849">**チャットにユーザーを追加する:**、最大350人のユーザーを1つのチャットスレッドに追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-849">**Add more people to chat:** We made it possible to now add up to 350 people to a single chat thread.</span></span>

- <span data-ttu-id="4f58d-850">**アクティビティ フィードの設定ギア**: ユーザーは、[設定] ギアを使用して、フィードの左側のレールから、アクティビティ フィードと通知の設定に直接アクセスできるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-850">**Settings Gear on your Activity Feed:** Users can now directly access activity feed and notification setting from the feed left rail by the means of a settings gear.</span></span>

- <span data-ttu-id="4f58d-851">**進行中の Teams 会議内から会議のオプションに簡単にアクセス可能:** 会議の開催者は、参加者ウィンドウに直接アクセスできるリンクを提供することで、会議の開催者が発表者やロビーの設定をすばやく簡単に変更することができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-851">**Easily access meeting options from within a Teams meeting in progress:** We are making it easier for meeting organizers to quickly and easily change their presenter and lobby settings once a Teams meeting starts by providing an easy to access link directly in the participants pane.</span></span> <span data-ttu-id="4f58d-852">この新機能は、予定されている、または 「今から会議」 の会議に使用できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-852">This new functionality will be present for both scheduled and “Meet Now” meetings.</span></span>

- <span data-ttu-id="4f58d-853">**チームとチャネルの分析 :** チームの分析に加えて、チャネル レベルのメトリックスやインサイトを表示することもできます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-853">**Team and channel analytics:** In addition to team analytics, now you can also view channel level metrics and insights.</span></span> <span data-ttu-id="4f58d-854">また、より長期間にわたってデータを分析できるように、期間が90日に延長されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-854">We've also enhanced the time period to 90 days so you can analyze data for longer periods.</span></span> <span data-ttu-id="4f58d-855">それ以外に、このリリースには、チームやチャネルの投稿、返信、会議の数についての新しいメトリックスやグラフも含まれます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-855">Apart from that, this release also includes new metrics and charts around count of posts, replies and meetings for a team or channel.</span></span>

- <span data-ttu-id="4f58d-856">**入退場のアナウンス:** 会議の開催者が会議の入退場アナウンスのオン / オフを切り替えできる機能を追加しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-856">**Entry/exit announcements:** We added this feature that lets meeting organizers have the ability to turn on or off entry and exit announcements for a meeting.</span></span>

### <a name="word"></a><span data-ttu-id="4f58d-857">Word</span><span class="sxs-lookup"><span data-stu-id="4f58d-857">Word</span></span>

- <span data-ttu-id="4f58d-858">**Wordを終了せずに頭字語をデコードする:** Word で頭字語が見つかった場合、他のユーザーによるその使用方法に基づいく定義が示されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-858">**Decode acronyms without leaving Word:** When you encounter an acronym, Word will try to define it based on how others use it.</span></span>

- <span data-ttu-id="4f58d-859">**アニメーション Gif を使用してストーリーを伝える :** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-859">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-862">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-862">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="4f58d-863">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-863">Excel</span></span>

- <span data-ttu-id="4f58d-864">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-864">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="4f58d-865">同じブック内の場所へのハイパーリンクをクリックすると、ブックが非表示になることがあります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-865">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

### <a name="outlook"></a><span data-ttu-id="4f58d-866">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-866">Outlook</span></span>

- <span data-ttu-id="4f58d-867">CLP の監査イベントで、返信/転送ラベルの問題に対応しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-867">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="4f58d-868">Windows 10 サーバー バージョンのユーザーに「アンチウイルスの状態が無効です」という警告が表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-868">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid".</span></span> <span data-ttu-id="4f58d-869">このバージョンの Windows はウイルス検出をサポートしていますが、ウイルス対策が正常にインストールされてもウイルス対策ソフトウェアが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="4f58d-869">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="4f58d-870">ユーザーが管理者通知からフィードバックを送信する場合にクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-870">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

### <a name="skype"></a><span data-ttu-id="4f58d-871">Skype</span><span class="sxs-lookup"><span data-stu-id="4f58d-871">Skype</span></span>

- <span data-ttu-id="4f58d-872">ユーザーが Teams Only に移動するポリシーを与えられた場合は、Skype for Business Outlook アドインを使用して会議をスケジュールできます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-872">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="4f58d-873">この更新プログラムを適用すると、クライアントは Teams Only を対象としていることを示すポリシーをユーザーが読んでから会議参加のみのモードに入った後に、Skype for Business 会議のスケジュールを設定できなくなります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-873">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="4f58d-874">また、skype for business Outlook アドインは、Skype for business クライアントが 「会議の参加のみ」 モードであることを確認した場合に起動した場合、自動的にアクティブ化されることはありません。</span><span class="sxs-lookup"><span data-stu-id="4f58d-874">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

### <a name="office-suite"></a><span data-ttu-id="4f58d-875">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-875">Office Suite</span></span>

- <span data-ttu-id="4f58d-876">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-876">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="4f58d-877">この更新プログラムでは、Microsoft Office で PATH 環境変数で指定した場所を検索することによって参照される可能性がある Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA ランタイムエラーが発生するという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-877">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="4f58d-878">HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth のレジストリ キーが0に設定されている場合、アドインがアクティブになり、Windows で Office ホストがクラッシュしました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-878">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="4f58d-879">この変更により、この問題は修正されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-879">This change would fix this issue.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2004-may-21"></a><span data-ttu-id="4f58d-881">バージョン 2004: 5 月 21 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-881">Version 2004: May 21</span></span>
<span data-ttu-id="4f58d-882">*バージョン 2004 (ビルド 12730.20352)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-882">*Version 2004 (Build 12730.20352)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-884">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-884">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4f58d-885">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-885">Excel</span></span>

- <span data-ttu-id="4f58d-886">ファイル パスが長すぎる場合にファイルをもう一度開くと、外部リンクが機能しなくなった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-886">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>


### <a name="outlook"></a><span data-ttu-id="4f58d-887">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-887">Outlook</span></span>

- <span data-ttu-id="4f58d-888">ユーザーが管理者通知からフィードバックを送信する場合にクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-888">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>


### <a name="office-suite"></a><span data-ttu-id="4f58d-889">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-889">Office Suite</span></span>

- <span data-ttu-id="4f58d-890">クイック実行に関する問題が修正され、最新のビルドへの更新プログラムに失敗することがあった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-890">Fixed a Click-to-Run issue which was resulting in occasional update failures to the latest builds.</span></span>

- <span data-ttu-id="4f58d-891">Microsoft Office で、PATH 環境変数で指定した場所を検索すれば見つかるはずの参照を含む Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA のランタイム エラーになる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-891">Fixed an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2004-may-12"></a><span data-ttu-id="4f58d-893">バージョン 2004: 5 月 12 月</span><span class="sxs-lookup"><span data-stu-id="4f58d-893">Version 2004: May 12</span></span>
<span data-ttu-id="4f58d-894">*バージョン 2004 (ビルド 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-894">*Version 2004 (Build 12730.20270)*</span></span>

<span data-ttu-id="4f58d-895">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4f58d-895">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-897">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-897">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="4f58d-898">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-898">Outlook</span></span>

- <span data-ttu-id="4f58d-899">ユーザーがトースト通知を表示するときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-899">Addresses an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-may-04"></a><span data-ttu-id="4f58d-901">バージョン 2004: 5 月 4 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-901">Version 2004: May 04</span></span>
<span data-ttu-id="4f58d-902">*バージョン 2004 (ビルド 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-902">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-904">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-904">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="4f58d-905">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-905">Office Suite</span></span>

- <span data-ttu-id="4f58d-906">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-906">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-april-29"></a><span data-ttu-id="4f58d-908">バージョン 2004: 4 月 29 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-908">Version 2004: April 29</span></span>
<span data-ttu-id="4f58d-909">*バージョン 2004 (ビルド 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-909">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="4f58d-911">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="4f58d-911">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="4f58d-912">Access</span><span class="sxs-lookup"><span data-stu-id="4f58d-912">Access</span></span>

- <span data-ttu-id="4f58d-913">**クエリ デザイナー、SQL ビュー、およびリレーションシップ ウィンドウでの作業効率の向上:** テーブルを右クリックして、テーブルを開き、デザインし、サイズを変更し、非表示にします。</span><span class="sxs-lookup"><span data-stu-id="4f58d-913">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="4f58d-914">SQL ビューでテキストを検索および置換します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-914">Search and replace text in SQL View.</span></span> <span data-ttu-id="4f58d-915">リレーションシップ ウィンドウ内の複数のテーブルを選択します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-915">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="4f58d-916">**数回クリックするだけで表を追加する:** [テーブルの追加] 作業ウィンドウを使用すると、作業中も開いたまま、リレーションシップやクエリにテーブルを追加できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-916">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="4f58d-917">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-917">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)


### <a name="excel"></a><span data-ttu-id="4f58d-918">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-918">Excel</span></span>

- <span data-ttu-id="4f58d-919">**Facebook コネクタのサポート終了:** 2020 年 4 月以降、Excel では Facebook コネクタを使用する外部データ接続がサポートされなくなります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-919">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

- <span data-ttu-id="4f58d-920">**質問がある場合のExcel への質問:** Excel のアイデアを使用すると、データについて質問をすることができます。数式の記述に時間を費やす必要はありません(英語のみ使用可能)。</span><span class="sxs-lookup"><span data-stu-id="4f58d-920">**Have a question? Ask Excel:** Now Excel Ideas allows you to ask questions about your data - no need to spend time writing formulas (available in English only).</span></span> [<span data-ttu-id="4f58d-921">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-921">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- <span data-ttu-id="4f58d-922">**ブックの見映えを良くする新しい画像:** 何千ものロイヤリティフリーの画像、アイコン、ステッカーが用意されており、これらをブックで使用できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-922">**New images to bring your workbooks to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your workbooks.</span></span> <span data-ttu-id="4f58d-923">開始するには、[挿入] > [画像] > [ストック画像] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-923">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="4f58d-924">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-924">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="outlook"></a><span data-ttu-id="4f58d-925">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-925">Outlook</span></span>

- <span data-ttu-id="4f58d-926">**受信トレイを離れずに会議に参加する:** オンライン会議に参加するために、予定表に切り替える必要はありません。</span><span class="sxs-lookup"><span data-stu-id="4f58d-926">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="4f58d-927">[To Do] ウィンドウに固定された予定表を使用して、ワンクリックで任意の会議に参加します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-927">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span> [<span data-ttu-id="4f58d-928">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-928">Learn more</span></span>](https://support.office.com/article/d8baa9d5-0645-41b8-9f36-b498a6c36064 )

- <span data-ttu-id="4f58d-929">**メッセージの見映えを良くする新しい画像:** 何千ものロイヤリティフリーの画像、アイコン、ステッカーが用意されており、これらをメール メッセージで使用できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-929">**New images to bring your messages to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your email messages.</span></span> <span data-ttu-id="4f58d-930">開始するには、[挿入] > [画像] > [ストック画像] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-930">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="4f58d-931">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-931">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

- <span data-ttu-id="4f58d-932">**定期的な会議の場所の提案サポート:** 定期的な会議のスケジュールで会議室を検索します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-932">**Location suggestion support for recurring meeting:** Search for conference rooms with scheduling recurring meetings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="4f58d-933">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-933">PowerPoint</span></span>

- <span data-ttu-id="4f58d-934">**スライド ショーの実行中にスライドを更新する:** プレゼンテーション中に他の作成者が変更したスライドを更新します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-934">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

- <span data-ttu-id="4f58d-935">**スライドの見映えを良くする新しい画像:** 何千ものロイヤリティフリーの画像、アイコン、ステッカーが用意されており、これらをプレゼンテーションで使用できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-935">**New images to bring your slides to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your presentations.</span></span> <span data-ttu-id="4f58d-936">開始するには、[挿入] > [画像] > [ストック画像] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-936">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="4f58d-937">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-937">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="teams"></a><span data-ttu-id="4f58d-938">Teams</span><span class="sxs-lookup"><span data-stu-id="4f58d-938">Teams</span></span>

- <span data-ttu-id="4f58d-939">**Teams の予定表の改善:** 予定表の項目を右クリックすると、出欠確認のオプションを表示したり、会議の参加者とのチャットを開始したり、会議開始時にすぐにその会議に参加したりすることができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-939">**Improvements to the Teams calendar:** Right-click an item in your calendar to pull up RSVP options, start a chat with meeting participants, or quickly join a meeting when it starts.</span></span> <span data-ttu-id="4f58d-940">また、イベントのスケジュール設定のフォームも改善されています。</span><span class="sxs-lookup"><span data-stu-id="4f58d-940">We've also made improvements to the event scheduling form.</span></span>

- <span data-ttu-id="4f58d-941">**ユーザーへのタグ付け:** タグを作成してユーザーに割り当てて、グループ、役割、部署などに @mention を付けることができます。チームの所有者はぜひお試しください。</span><span class="sxs-lookup"><span data-stu-id="4f58d-941">**Tag, you're it!:** Create tags and assign people to them so you can @mention a group, role, department, etc. Team owners, try it out for yourselves.</span></span> <span data-ttu-id="4f58d-942">チームに移動し、[その他のオプション]、[タグの管理] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-942">Go to a team, select More options, Manage tags.</span></span>

### <a name="word"></a><span data-ttu-id="4f58d-943">Word</span><span class="sxs-lookup"><span data-stu-id="4f58d-943">Word</span></span>

- <span data-ttu-id="4f58d-944">**ツールの使いやすさを維持:** [描画] ツールボックスには、テキストにインク ジェスチャを追加できるインテリジェント ペンが用意されています。</span><span class="sxs-lookup"><span data-stu-id="4f58d-944">**Keep your tools handy:** In your drawing toolbox, find the intelligent pen that allows you to add ink gestures to text.</span></span> [<span data-ttu-id="4f58d-945">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-945">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- <span data-ttu-id="4f58d-946">**ドキュメントの見映えを良くする新しい画像:** 何千ものロイヤリティフリーの画像、アイコン、ステッカーが用意されており、これらをドキュメントで使用できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-946">**New images to bring your documents to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your documents.</span></span> <span data-ttu-id="4f58d-947">開始するには、[挿入] > [画像] > [ストック画像] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-947">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="4f58d-948">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-948">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-951">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-951">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4f58d-952">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-952">Excel</span></span>

- <span data-ttu-id="4f58d-953">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-953">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="4f58d-954">ピボットテーブルを含むシートをコピーした後、Excel がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-954">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="4f58d-955">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-955">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="4f58d-956">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-956">Outlook</span></span>

- <span data-ttu-id="4f58d-957">フォルダー ウィンドウの幅が予期せず変更される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-957">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>


- <span data-ttu-id="4f58d-958">Windows の一部のビルドで Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-958">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>


- <span data-ttu-id="4f58d-959">Windows の更新後に、ローカルに保存された .msg または .oft ファイルを開くと Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-959">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>


- <span data-ttu-id="4f58d-960">Windows の一部のビルドで Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-960">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>


- <span data-ttu-id="4f58d-961">Outlook の終了中に応答が停止するする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-961">Addressed an issue that caused users to experience a hang while exiting Outlook.</span></span>


### <a name="project"></a><span data-ttu-id="4f58d-962">Project</span><span class="sxs-lookup"><span data-stu-id="4f58d-962">Project</span></span>

- <span data-ttu-id="4f58d-963">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-963">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>


- <span data-ttu-id="4f58d-964">Project Web App に接続されている Project を使用していて小数点の記号がカンマの場合に、依存関係のタイム ラグを生じさせようとすると TaskDependencies Add メソッドが失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-964">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

### <a name="office-suite"></a><span data-ttu-id="4f58d-965">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-965">Office Suite</span></span>

- <span data-ttu-id="4f58d-966">アクセスの制限と、パスワードによるファイルの保護が同時に行えないというエラーを解決しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-966">Resolved an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-april-15"></a><span data-ttu-id="4f58d-968">バージョン 2003: 4 月 15 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-968">Version 2003: April 15</span></span>
<span data-ttu-id="4f58d-969">*バージョン 2003 (ビルド 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-969">*Version 2003 (Build 12624.20466)*</span></span>
* <span data-ttu-id="4f58d-970">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="4f58d-970">Various bugs and performance fixes.</span></span>

## <a name="version-2003-april-14"></a><span data-ttu-id="4f58d-971">バージョン 2003: 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-971">Version 2003: April 14</span></span>
<span data-ttu-id="4f58d-972">*バージョン 2003 (ビルド 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-972">*Version 2003 (Build 12624.20442)*</span></span>

<span data-ttu-id="4f58d-973">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4f58d-973">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-975">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-975">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4f58d-976">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-976">Excel</span></span>

- <span data-ttu-id="4f58d-977">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-977">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="4f58d-978">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-978">Outlook</span></span>

- <span data-ttu-id="4f58d-979">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-979">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="4f58d-980">Project</span><span class="sxs-lookup"><span data-stu-id="4f58d-980">Project</span></span>

- <span data-ttu-id="4f58d-981">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-981">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

### <a name="word"></a><span data-ttu-id="4f58d-982">Word</span><span class="sxs-lookup"><span data-stu-id="4f58d-982">Word</span></span>

- <span data-ttu-id="4f58d-983">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-983">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-31"></a><span data-ttu-id="4f58d-985">バージョン 2003: 3 月 31 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-985">Version 2003: March 31</span></span>
<span data-ttu-id="4f58d-986">*バージョン 2003 (ビルド 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-986">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-988">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-988">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="4f58d-989">OneNote</span><span class="sxs-lookup"><span data-stu-id="4f58d-989">OneNote</span></span>

- <span data-ttu-id="4f58d-990">全世界でサービス使用量が高まった際に、同期とサービスの可用性を改善できる、Microsoft OneNote の一時的な調整に関して、情報バーを介してユーザーに通知します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-990">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

### <a name="project"></a><span data-ttu-id="4f58d-991">Project</span><span class="sxs-lookup"><span data-stu-id="4f58d-991">Project</span></span>

- <span data-ttu-id="4f58d-992">実績作業時間の保護設定を有効にしているときに、ユーザーがタイムフェーズの基準作業時間を入力できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-992">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-25"></a><span data-ttu-id="4f58d-994">バージョン 2003: 3 月 25 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-994">Version 2003: March 25</span></span>
<span data-ttu-id="4f58d-995">*バージョン 2003 (ビルド 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-995">*Version 2003 (Build 12624.20320)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="4f58d-997">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="4f58d-997">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="4f58d-998">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-998">Excel</span></span>

- <span data-ttu-id="4f58d-999">**お気に入りの Excel 関数が速くなりました：** SUMIFS、AVERAGEIFS、COUNTIFS、MAXIFS、および MINIFS 関数がこれまでよりもはるかに高速になりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-999">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="4f58d-1000">もっと素早く一番下に移動します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1000">Get to the bottom line more quickly.</span></span> <span data-ttu-id="4f58d-1001">今すぐお試しください。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1001">Try one now.</span></span>

### <a name="outlook"></a><span data-ttu-id="4f58d-1002">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-1002">Outlook</span></span>

- <span data-ttu-id="4f58d-1003">**所有しているグループにメールをドラッグ:** メッセージや会話を受信トレイからドラッグして移動し、コピーします。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1003">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="4f58d-1004">ドラッグしたメッセージは、すべてのグループ メンバーと共有されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1004">Messages you drag will be shared with all group members.</span></span>

- <span data-ttu-id="4f58d-1005">**キャプティブ WiFi ネットワークの新しいエクスペリエンス**: サインインに Web ページを必要とする WiFi ネットワークに参加したことはありませんか ?</span><span class="sxs-lookup"><span data-stu-id="4f58d-1005">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="4f58d-1006">Outlook はこれを検出し、接続を支援します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1006">Outlook now detects this and helps you get connected.</span></span>

###<a name="powerpoint"></a><span data-ttu-id="4f58d-1007">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-1007">PowerPoint</span></span>

- <span data-ttu-id="4f58d-1008">**コメント:** PowerPoint の新しいコメント機能により、ドキュメントにコメントをすばやく簡単に見つけて追加できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1008">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="4f58d-1009">コメントの固定、解決、タスク、改善された通知などの新機能を使用して、コラボレーションワークフローを最新のものにします。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1009">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span>

### <a name="word"></a><span data-ttu-id="4f58d-1010">Word</span><span class="sxs-lookup"><span data-stu-id="4f58d-1010">Word</span></span>

- <span data-ttu-id="4f58d-1011">**他のユーザーがすばやく変更を確認する:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1011">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="4f58d-1012">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-1012">Office Suite</span></span>

- <span data-ttu-id="4f58d-1013">**秘密度ラベル:** カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1013">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-1016">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-1016">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4f58d-1017">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-1017">Excel</span></span>

- <span data-ttu-id="4f58d-1018">Word または PowerPoint に埋め込まれたブックをもう一度開くと、場合によっては Excel がクラッシュする可能性があります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1018">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="4f58d-1019">ソース ブックが閉じていると、外部リンクが塗りつぶし時に更新されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1019">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="4f58d-1020">テンプレートからグラフを作成するときに発生するパフォーマンスの問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1020">Addressed a performance issue when creating charts from templates.</span></span>

### <a name="onenote"></a><span data-ttu-id="4f58d-1021">OneNote</span><span class="sxs-lookup"><span data-stu-id="4f58d-1021">OneNote</span></span>

- <span data-ttu-id="4f58d-1022">新しい埋め込み添付ファイルの最大許容サイズを一時的に 50 MB に削減することにより、同期とサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1022">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB.</span></span> <span data-ttu-id="4f58d-1023">この制限を超えるファイルの場合、ユーザーは OneDrive にファイルをアップロードして、OneNote にリンクを挿入することができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1023">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="4f58d-1024">OneNote 2016 で同期頻度を一時的に調整することで、同期およびサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1024">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

### <a name="outlook"></a><span data-ttu-id="4f58d-1025">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-1025">Outlook</span></span>

- <span data-ttu-id="4f58d-1026">終了後にタスク マネージャーに Outlook プロセスが残っているという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1026">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="4f58d-1027">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-1027">PowerPoint</span></span>

- <span data-ttu-id="4f58d-1028">コピーと貼り付けのシナリオを改善しました。PowerPoint スライドでの図形のコピーと、ループ内の他のスライドへの貼り付けが例外で失敗する場合があります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1028">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="4f58d-1029">Project</span><span class="sxs-lookup"><span data-stu-id="4f58d-1029">Project</span></span>

- <span data-ttu-id="4f58d-1030">[無効化] ボタンを介してタスクが非アクティブ化/アクティブ化された場合に、ProjectBeforeTaskChange イベントが検出しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1030">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="4f58d-1031">以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1031">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="4f58d-1032">タスクを完了とマークした後に、タスクの達成率が 100% 完了より小さい値に誤って変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1032">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="4f58d-1033">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1033">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-march-10"></a><span data-ttu-id="4f58d-1035">バージョン 2002: 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-1035">Version 2002: March 10</span></span>
<span data-ttu-id="4f58d-1036">*バージョン 2002 (ビルド 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-1036">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="4f58d-1037">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4f58d-1037">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="4f58d-1039">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="4f58d-1039">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="4f58d-1040">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-1040">PowerPoint</span></span>

- <span data-ttu-id="4f58d-1041">**スライドへのリンク:** 同僚にスライド デッキへの投稿を依頼し、ヘルプが必要なスライド上で直接開始します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1041">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-1044">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-1044">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="4f58d-1045">Project</span><span class="sxs-lookup"><span data-stu-id="4f58d-1045">Project</span></span>

- <span data-ttu-id="4f58d-1046">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1046">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2002-march-01"></a><span data-ttu-id="4f58d-1048">バージョン 2002: 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-1048">Version 2002: March 01</span></span>
<span data-ttu-id="4f58d-1049">*バージョン 2002 (ビルド 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-1049">*Version 2002 (Build 12527.20242)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-1051">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-1051">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="4f58d-1052">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-1052">Outlook</span></span>

- <span data-ttu-id="4f58d-1053">サードパーティ製アプリケーションがメールを送信できない原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1053">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2002-february-25"></a><span data-ttu-id="4f58d-1055">バージョン 2002: 2 月 25 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-1055">Version 2002: February 25</span></span>
<span data-ttu-id="4f58d-1056">*バージョン 2002 (ビルド 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-1056">*Version 2002 (Build 12527.20194)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="4f58d-1058">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="4f58d-1058">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="4f58d-1059">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-1059">Excel</span></span>

- <span data-ttu-id="4f58d-1060">**ブックの統計情報:** セル、数式、グラフ、テーブル...これらをお客様に代わってカウントします。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1060">**Workbook Statistics:** Cells, formulas, charts, tables... We count them so you don't have to.</span></span>

- <span data-ttu-id="4f58d-1061">**クエリ エディターでのデータ プロファイリング**: 列のデータを一目で分析し、エラーと空の値を識別し、配布ヒストグラムなどを確認します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1061">**Data Profiling in Query Editor:** Get at-a-glance analysis of the data in your columns, identify error and empty values, see distribution histograms and more.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-1064">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-1064">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4f58d-1065">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-1065">Excel</span></span>

- <span data-ttu-id="4f58d-1066">CUBEVALUE 関数が間違った結果を返すことがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1066">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="4f58d-1067">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-1067">Outlook</span></span>

- <span data-ttu-id="4f58d-1068">会議の [場所] フィールドにあるコンマがセミコロンになる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1068">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="4f58d-1069">複数のウィンドウで同じアイテムを表示するとクラッシュする場合がある問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1069">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="4f58d-1070">フラグ付きアイテムの強調表示を無効にするオプションが一部のシナリオで無視される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1070">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="4f58d-1071">同期のスライダーが小さい設定に設定されている場合でも、Outlook で予期せずすべてのメールが同期される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1071">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>


- <span data-ttu-id="4f58d-1072">黒のテーマを持つユーザーが [差出人] ドロップダウンを表示すると、白色の背景に白いテキストが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1072">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>


- <span data-ttu-id="4f58d-1073">この変更により、メッセージ ヘッダーに複数行の件名を表示できる機能が復元されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1073">This change restores the ability to view multi-line subjects in the message header.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2001-february-19"></a><span data-ttu-id="4f58d-1075">バージョン 2001: 2 月 19 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-1075">Version 2001: February 19</span></span>
<span data-ttu-id="4f58d-1076">*バージョン 2001 (ビルド 12430.20288)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-1076">*Version 2001 (Build 12430.20288)*</span></span>
* <span data-ttu-id="4f58d-1077">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1077">Various bugs and performance fixes.</span></span>

## <a name="version-2001-february-11"></a><span data-ttu-id="4f58d-1078">バージョン 2001: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-1078">Version 2001: February 11</span></span>
<span data-ttu-id="4f58d-1079">*バージョン 2001 (ビルド 12430.20264)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-1079">*Version 2001 (Build 12430.20264)*</span></span>

<span data-ttu-id="4f58d-1080">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4f58d-1080">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-1082">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-1082">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="4f58d-1083">Access</span><span class="sxs-lookup"><span data-stu-id="4f58d-1083">Access</span></span>

- <span data-ttu-id="4f58d-1084">Access テンプレートは、データベース内の添付ファイル列のエラーを発生させることがなくなりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1084">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="4f58d-1085">テンプレートのインスタンス化後に、データベースに添付ファイル フィールドを追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1085">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="4f58d-1086">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-1086">Excel</span></span>

- <span data-ttu-id="4f58d-1087">コンテキスト メニューのコメント コマンドが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1087">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="4f58d-1088">スピル配列が含まれるセルで区切り位置を指定するとクラッシュが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1088">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


### <a name="outlook"></a><span data-ttu-id="4f58d-1089">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-1089">Outlook</span></span>

- <span data-ttu-id="4f58d-1090">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1090">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="4f58d-1091">ユーザーがアカウントのセットアップをキャンセルするときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1091">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>


### <a name="project"></a><span data-ttu-id="4f58d-1092">Project</span><span class="sxs-lookup"><span data-stu-id="4f58d-1092">Project</span></span>

- <span data-ttu-id="4f58d-1093">作業時間固定タイプの達成率 100% のタスクで、達成率が誤って 100% 未満に計算される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1093">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="office-suite"></a><span data-ttu-id="4f58d-1094">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-1094">Office Suite</span></span>

- <span data-ttu-id="4f58d-1095">この変更では、Intel Integrated GPU を使用するグラフィック アダプターに関して報告された問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1095">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2001-january-30"></a><span data-ttu-id="4f58d-1097">バージョン 2001: 1 月 30 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-1097">Version 2001: January 30</span></span>
<span data-ttu-id="4f58d-1098">*バージョン 2001 (ビルド 12430.20184)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-1098">*Version 2001 (Build 12430.20184)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="4f58d-1100">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="4f58d-1100">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="4f58d-1101">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-1101">Excel</span></span>

- <span data-ttu-id="4f58d-1102">**すぐに読んで返信する**: ブックを開かずに、メールからコメントやメンションに直接返信します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1102">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="4f58d-1103">**左を見て、右を見て... XLOOKUP をご利用いただけます!** XLOOKUP を使えば、表や範囲内で必要なものは何でも見つけられます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1103">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="4f58d-1104">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-1104">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)

### <a name="outlook"></a><span data-ttu-id="4f58d-1105">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-1105">Outlook</span></span>

- <span data-ttu-id="4f58d-1106">**高度なグループ メールの設定:** この機能は、グループ ユーザーが受信トレイで受信/フォローするメールまたはイベントを、カスタマイズするのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1106">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="4f58d-1107">**グループの名前付けポリシー**: グループの名前付けポリシーを使用すると、IT 管理者は組織内のユーザーが作成するグループの名前の標準化と管理を行えます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1107">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="4f58d-1108">管理者は、グループが作成される際に特定のプレフィックスとサフィックスをグループ名に追加することを要求できます。また、特定の単語の使用を禁止できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1108">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="4f58d-1109">これにより、グループ名での不適切な単語の使用を最小限に抑えられる他、ディレクトリ内のグループ名の記載を IT 管理者が管理できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1109">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="4f58d-1110">また、名前付けポリシーを使用することで、チーム サイトを展開する組織は、チーム サイトを部署ごとに分類できるようにもなります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1110">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="word"></a><span data-ttu-id="4f58d-1111">Word</span><span class="sxs-lookup"><span data-stu-id="4f58d-1111">Word</span></span>

- <span data-ttu-id="4f58d-1112">**より安全なビデオ エクスペリエンス:** セキュリティの強化は、より安全なオンライン ビデオ エクスペリエンスを意味します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1112">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="4f58d-1113">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-1113">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="4f58d-1114">**インクのなげなわ:** [描画] タブのなげなわツールを使用すると、インクで描かれたオブジェクトを選択できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1114">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="4f58d-1115">個別のストロークまたは文字全体を選択できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1115">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="4f58d-1116">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-1116">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)






[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-1119">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-1119">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="4f58d-1120">Access</span><span class="sxs-lookup"><span data-stu-id="4f58d-1120">Access</span></span>

- <span data-ttu-id="4f58d-1121">この更新プログラムでは、ADODB を使用する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1121">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="4f58d-1122">VB コードのれコーター オブジェクトがエラーを誤って報告することがあります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1122">Recorder object in VB code may incorrectly report an error.</span></span>


- <span data-ttu-id="4f58d-1123">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1123">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="4f58d-1124">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-1124">Excel</span></span>

- <span data-ttu-id="4f58d-1125">署名の名前を変更したときにクラッシュする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1125">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>


### <a name="outlook"></a><span data-ttu-id="4f58d-1126">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-1126">Outlook</span></span>

- <span data-ttu-id="4f58d-1127">署名の名前を変更したときにクラッシュする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1127">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1912-january-22"></a><span data-ttu-id="4f58d-1129">バージョン 1912: 1 月 22 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-1129">Version 1912: January 22</span></span>
<span data-ttu-id="4f58d-1130">*バージョン 1912 (ビルド 12325.20344)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-1130">*Version 1912 (Build 12325.20344)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-1132">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-1132">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="4f58d-1133">Access</span><span class="sxs-lookup"><span data-stu-id="4f58d-1133">Access</span></span>

- <span data-ttu-id="4f58d-1134">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1134">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1912-january-14"></a><span data-ttu-id="4f58d-1136">バージョン 1912: 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-1136">Version 1912: January 14</span></span>
<span data-ttu-id="4f58d-1137">*バージョン 1912 (ビルド 12325.20298)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-1137">*Version 1912 (Build 12325.20298)*</span></span>

<span data-ttu-id="4f58d-1138">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="4f58d-1138">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1912-january-08"></a><span data-ttu-id="4f58d-1139">バージョン 1912: 1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="4f58d-1139">Version 1912: January 08</span></span>
<span data-ttu-id="4f58d-1140">*バージョン 1912 (ビルド 12325.20288)*</span><span class="sxs-lookup"><span data-stu-id="4f58d-1140">*Version 1912 (Build 12325.20288)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="4f58d-1142">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="4f58d-1142">Feature updates</span></span>

### <a name="outlook"></a><span data-ttu-id="4f58d-1143">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-1143">Outlook</span></span>

- <span data-ttu-id="4f58d-1144">**アクセシビリティ対応のメールを最も必要としている人に送信する:** Outlook では、メールのヒントが表示され、アクセシビリティ対応のコンテンツを必要とするユーザーに送信するときに、コンテンツがアクセシビリティ対応であることを確認できます</span><span class="sxs-lookup"><span data-stu-id="4f58d-1144">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="4f58d-1145">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="4f58d-1145">PowerPoint</span></span>

- <span data-ttu-id="4f58d-1146">**プレゼンテーションの最適化:** アクセシビリティ チェックを使用すると、スクリーン リーダーを考慮に入れて、スライド上のオブジェクトを配置することができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1146">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="4f58d-1147">**簡単な GIF:** 1 つのスライド、1 つのフレーム。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1147">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="4f58d-1148">PowerPoint でループ GIF を簡単に作成できます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1148">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="4f58d-1149">詳細情報</span><span class="sxs-lookup"><span data-stu-id="4f58d-1149">Learn more</span></span>](https://support.office.com/ja-JP/article/a598753e-92de-4f1b-8393-714db4d334b4)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="4f58d-1152">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="4f58d-1152">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="4f58d-1153">Excel</span><span class="sxs-lookup"><span data-stu-id="4f58d-1153">Excel</span></span>

- <span data-ttu-id="4f58d-1154">この変更は、ソフトウェア レンダリングを活用することにより、特定の Intel グラフィック ドライバーの問題を回避します。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1154">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

### <a name="outlook"></a><span data-ttu-id="4f58d-1155">Outlook</span><span class="sxs-lookup"><span data-stu-id="4f58d-1155">Outlook</span></span>

- <span data-ttu-id="4f58d-1156">会議をクリアした後、会議の場所が予期せずに会議に追加される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1156">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="4f58d-1157">キーボード ショートカットを使用してメールボックス フォルダーを操作すると、ユーザーに顕著な遅延が発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1157">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="4f58d-1158">状況によっては、表示された SMTP アドレスと一致しないアドレスに送信されたメールがユーザーに表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1158">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="4f58d-1159">ユーザーがクラウド設定を取得する際に Outlook がフリーズする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1159">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

### <a name="word"></a><span data-ttu-id="4f58d-1160">Word</span><span class="sxs-lookup"><span data-stu-id="4f58d-1160">Word</span></span>

- <span data-ttu-id="4f58d-1161">文書パーツ オーガナイザーに 「スタイル、文書パーツを変更しました」 という無効なアラートが表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1161">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="4f58d-1162">Office スイート</span><span class="sxs-lookup"><span data-stu-id="4f58d-1162">Office Suite</span></span>

- <span data-ttu-id="4f58d-1163">Office の更新プログラムが、意図したソース (ローカル共有、ネットワーク共有、構成マネージャー
で提供される場所など) からではなく、予期せずに Office CDN からファイルをダウンロードする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1163">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

> [!NOTE]
> <span data-ttu-id="4f58d-1165">Office の使用で問題がある場合は、[Microsoft の回答フォーラム](https://answers.microsoft.com/)に関するページまたは「[Microsoft Tech Community](https://techcommunity.microsoft.com/)」に質問を投稿するか、[サポート](https://support.microsoft.com/contactus)に問い合わせてサポートを受けることができます。</span><span class="sxs-lookup"><span data-stu-id="4f58d-1165">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>

[//]: # (管理センターのメタデータのコンテンツを変更しないでください。開始)
[//]: # (|Win32|CC|Production| |16.0.13628.20274|version-2101-january-26|)
[//]: # (|Win32|CC|Production| |16.0.13530.20440|version-2012-january-21|)
[//]: # (|Win32|CC|Production| |16.0.13530.20376|version-2012-january-12|)
[//]: # (|Win32|CC|Production| |16.0.13530.20316|version-2012-january-05|)
[//]: # (|Win32|CC|Production| |16.0.13426.20404|version-2011-december-21|)
[//]: # (|Win32|CC|Production| |16.0.13426.20332|version-2011-december-08|)
[//]: # (|Win32|CC|Production| |16.0.13426.20308|version-2011-december-02|)
[//]: # (|Win32|CC|Production| |16.0.13426.20294|version-2011-november-30|)
[//]: # (|Win32|CC|Production| |16.0.13426.20274|version-2011-november-23|)
[//]: # (|Win32|CC|Production| |16.0.13328.20408|version-2010-november-17|)
[//]: # (管理センターのメタデータのコンテンツ エンドを変更しないでください)
