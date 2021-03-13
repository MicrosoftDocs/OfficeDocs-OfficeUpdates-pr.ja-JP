---
title: 2020 年の月次エンタープライズ チャネル リリースのリリース ノート
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Microsoft 365 Apps 用の 2020 年の月次エンタープライズ チャネル リリースのリリース ノートを IT 担当者に提供します
ms.openlocfilehash: 729d6b9bd7d549522386c8f2b11c4d3b6761d117
ms.sourcegitcommit: 90a9ee90251f072398574a437e5f45d406d617eb
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/11/2021
ms.locfileid: "50735192"
---
# <a name="release-notes-for-monthly-enterprise-channel-releases-in-2020"></a><span data-ttu-id="79f18-103">2020 年の月次エンタープライズ チャネル リリースのリリース ノート</span><span class="sxs-lookup"><span data-stu-id="79f18-103">Release notes for Monthly Enterprise Channel releases in 2020</span></span>

<span data-ttu-id="79f18-104">このリリース ノートには、2020 年の月次エンタープライズ チャネルの更新プログラムに含まれる新機能と、セキュリティ以外の更新プログラムに関する情報が記載されています。対象となるのは、Microsoft 365 Apps for enterprise、Microsoft 365 Apps for business、および Project と Visio のデスクトップ アプリのサブスクリプション版です。</span><span class="sxs-lookup"><span data-stu-id="79f18-104">These release notes provide information about new features and non-security updates that are included in Monthly Enterprise Channel updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="79f18-105">Microsoft 365 アプリの更新チャネルの更新プログラムチャネルに、新しい更新チャネル (月間エンタープライズ チャネル) の追加や、既存の更新プログラムチャネルの名前の変更など、いくつかの変更を行っています。</span><span class="sxs-lookup"><span data-stu-id="79f18-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="79f18-106">詳細については、[こちらの記事を参照](https://go.microsoft.com/fwlink/p/?linkid=2127441)をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="79f18-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

[//]: # (削除しないでください)



## <a name="version-2101-march-09"></a><span data-ttu-id="79f18-108">バージョン 2101: 3 月 9 日</span><span class="sxs-lookup"><span data-stu-id="79f18-108">Version 2101: March 09</span></span>
<span data-ttu-id="79f18-109">*バージョン 2101 (ビルド 13628.20528)*</span><span class="sxs-lookup"><span data-stu-id="79f18-109">*Version 2101 (Build 13628.20528)*</span></span>

<span data-ttu-id="79f18-110">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="79f18-110">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="79f18-112">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="79f18-112">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="79f18-113">Excel</span><span class="sxs-lookup"><span data-stu-id="79f18-113">Excel</span></span>

- <span data-ttu-id="79f18-114">特定の Windows セキュリティのエクスプロイト保護設定 (SimExec、CallerCheck) を使用している場合に、Excel の起動に失敗したり、予期せず終了したりしてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-114">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


### <a name="outlook"></a><span data-ttu-id="79f18-115">Outlook</span><span class="sxs-lookup"><span data-stu-id="79f18-115">Outlook</span></span>

- <span data-ttu-id="79f18-116">[暗号化のみ] オプションを使用して送信されたメールの暗号化アイコンが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-116">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>


- <span data-ttu-id="79f18-117">ユーザーがデジタル署名のオプションのチェックを外した後も、メールがデジタル署名されたものとして送信される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-117">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


- <span data-ttu-id="79f18-118">OWA に既定の正しい署名が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-118">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="79f18-119">クラウド設定のユーザーが設定を更新するときにハングする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-119">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>


- <span data-ttu-id="79f18-120">ユーザーが Outlook で検索しているときに、アプリが予期せず閉じることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-120">We fixed an issue that caused the app to sometimes close unexpectedly when users were searching in Outlook.</span></span>


- <span data-ttu-id="79f18-121">プロファイルに大きな階層がある共有メールボックスまたは代理メールボックスを持つユーザーがハングする原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-121">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


- <span data-ttu-id="79f18-122">特定の検索シナリオで Outlook が予期せず終了するという一部のユーザーの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-122">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>


### <a name="project"></a><span data-ttu-id="79f18-123">Project</span><span class="sxs-lookup"><span data-stu-id="79f18-123">Project</span></span>

- <span data-ttu-id="79f18-124">コスト型リソースがマイルストーン タスクに割り当てられたとき、基準コストが正しくロールアップされないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-124">Fixed an issue where when a cost resource was assigned to a milestone task, baseline cost didn't rollup correctly.</span></span>


- <span data-ttu-id="79f18-125">チーム プランナー ビューのタスクに枠が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-125">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="79f18-126">チーム プランナー ビューのタスクでドラッグ アンド ドロップが機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-126">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>


### <a name="office-suite"></a><span data-ttu-id="79f18-127">Office スイート</span><span class="sxs-lookup"><span data-stu-id="79f18-127">Office Suite</span></span>

- <span data-ttu-id="79f18-128">メディア コントローラーのイベント通知に関連する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="79f18-128">Fixes an issue related to media controller event notifications.</span></span>


- <span data-ttu-id="79f18-129">メディア プレーヤー エンジンのタイミングに関連する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="79f18-129">Fixes an issue related to media player engine timing.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2012-march-09"></a><span data-ttu-id="79f18-131">バージョン 2012: 3 月 9 日</span><span class="sxs-lookup"><span data-stu-id="79f18-131">Version 2012: March 09</span></span>
<span data-ttu-id="79f18-132">*バージョン 2012 (ビルド 13530.20628)*</span><span class="sxs-lookup"><span data-stu-id="79f18-132">*Version 2012 (Build 13530.20628)*</span></span>

<span data-ttu-id="79f18-133">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="79f18-133">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2012-february-09"></a><span data-ttu-id="79f18-134">バージョン 2012: 2 月 9 日</span><span class="sxs-lookup"><span data-stu-id="79f18-134">Version 2012: February 09</span></span>
<span data-ttu-id="79f18-135">*バージョン 2012 (ビルド 13530.20528)*</span><span class="sxs-lookup"><span data-stu-id="79f18-135">*Version 2012 (Build 13530.20528)*</span></span>

<span data-ttu-id="79f18-136">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="79f18-136">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="79f18-138">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="79f18-138">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="79f18-139">Excel</span><span class="sxs-lookup"><span data-stu-id="79f18-139">Excel</span></span>

- <span data-ttu-id="79f18-140">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="79f18-140">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="79f18-141">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-141">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="79f18-142">**秘密度ラベル監査ログ:** ユーザーが、ドキュメントやメールで秘密度ラベルを適用、変更、削除すると、管理者は、その情報を Microsoft 365 監査ログで使用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="79f18-142">**Sensitivity label audit logging:** When users apply, change, or remove sensitivity labels on their documents and emails, that information is now made available to administrators in the Microsoft 365 audit logs.</span></span>

- <span data-ttu-id="79f18-143">**政府機関のお客様: ドキュメントおよびメールに秘密度ラベルを適用する:** GCC および GCC-H 環境のお客様は、秘密度のラベル付け機能を利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="79f18-143">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="79f18-144">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-144">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a><span data-ttu-id="79f18-145">Outlook</span><span class="sxs-lookup"><span data-stu-id="79f18-145">Outlook</span></span>

- <span data-ttu-id="79f18-146">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="79f18-146">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="79f18-147">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-147">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="79f18-148">**連続する会議の合間に時間を組み込む:** 既定で 5 分から 10 分遅く会議を開始するように設定することで、出席者に休憩時間や場所の移動時間を与えることができます。</span><span class="sxs-lookup"><span data-stu-id="79f18-148">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default.</span></span> [<span data-ttu-id="79f18-149">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-149">Learn more</span></span>](https://support.office.com/article/ebb4c4c9-6992-4ea7-9772-8b5883df8500)

- <span data-ttu-id="79f18-150">**秘密度ラベル監査ログ:** ユーザーが、ドキュメントやメールで秘密度ラベルを適用、変更、削除すると、管理者は、その情報を Microsoft 365 監査ログで使用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="79f18-150">**Sensitivity label audit logging:** When users apply, change, or remove sensitivity labels on their documents and emails, that information is now made available to administrators in the Microsoft 365 audit logs.</span></span>

- <span data-ttu-id="79f18-151">**すべてのオンライン会議:** 予定表設定を更新して、既定で Teams 会議を作成するすべての会議を作成します。これにより、Teams 会議オプションをクリックする必要がなくなります。</span><span class="sxs-lookup"><span data-stu-id="79f18-151">**Every meeting online:** Update your calendar settings to make every meeting you create a Teams Meeting by default so you no longer need to remember to click the Teams Meeting option.</span></span>

- <span data-ttu-id="79f18-152">**政府機関のお客様: ドキュメントおよびメールに秘密度ラベルを適用する:** GCC および GCC-H 環境のお客様は、秘密度のラベル付け機能を利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="79f18-152">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="79f18-153">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-153">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)

- <span data-ttu-id="79f18-154">**すべてのオンライン会議:** 予定表設定を更新して、既定で Teams 会議を作成するすべての会議を作成します。これにより、Teams 会議オプションをクリックする必要がなくなります。</span><span class="sxs-lookup"><span data-stu-id="79f18-154">**Every meeting online:** Update your calendar settings to make every meeting you create a Teams Meeting by default so you no longer need to remember to click the Teams Meeting option.</span></span>

- <span data-ttu-id="79f18-155">**新しい会議室の検索機能:** これまでと違うさまざまな機能で会議室を検索できます。</span><span class="sxs-lookup"><span data-stu-id="79f18-155">**New room finder:** Search for conference rooms by different capabilities.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="79f18-156">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="79f18-156">PowerPoint</span></span>

- <span data-ttu-id="79f18-157">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="79f18-157">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="79f18-158">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-158">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br /><span data-ttu-id="79f18-159">[ブログの投稿](https://insider.office.com/ja-JP/blog/svg-content-office-third-party-apps)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-159">See details in [blog post](https://insider.office.com/ja-JP/blog/svg-content-office-third-party-apps)</span></span>

- <span data-ttu-id="79f18-160">**秘密度ラベル監査ログ:** ユーザーが、ドキュメントやメールで秘密度ラベルを適用、変更、削除すると、管理者は、その情報を Microsoft 365 監査ログで使用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="79f18-160">**Sensitivity label audit logging:** When users apply, change, or remove sensitivity labels on their documents and emails, that information is now made available to administrators in the Microsoft 365 audit logs.</span></span>

- <span data-ttu-id="79f18-161">**政府機関のお客様: ドキュメントおよびメールに秘密度ラベルを適用する:** GCC および GCC-H 環境のお客様は、秘密度のラベル付け機能を利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="79f18-161">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="79f18-162">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-162">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)

### <a name="visio"></a><span data-ttu-id="79f18-163">Visio</span><span class="sxs-lookup"><span data-stu-id="79f18-163">Visio</span></span>

- <span data-ttu-id="79f18-164">**新しい Azure ステンシルと図形:** 最新の Azure 図を作成するために、多くのステンシルを追加しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-164">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="79f18-165">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-165">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a><span data-ttu-id="79f18-166">Word</span><span class="sxs-lookup"><span data-stu-id="79f18-166">Word</span></span>

- <span data-ttu-id="79f18-167">**SVG クリップボードのサポート:** Office からサードパーティのアプリに SVG コンテンツを貼り付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="79f18-167">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="79f18-168">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-168">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="79f18-169">**秘密度ラベル監査ログ:** ユーザーが、ドキュメントやメールで秘密度ラベルを適用、変更、削除すると、管理者は、その情報を Microsoft 365 監査ログで使用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="79f18-169">**Sensitivity label audit logging:** When users apply, change, or remove sensitivity labels on their documents and emails, that information is now made available to administrators in the Microsoft 365 audit logs.</span></span>

- <span data-ttu-id="79f18-170">**政府機関のお客様: ドキュメントおよびメールに秘密度ラベルを適用する:** GCC および GCC-H 環境のお客様は、秘密度のラベル付け機能を利用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="79f18-170">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="79f18-171">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-171">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="79f18-174">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="79f18-174">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="79f18-175">Excel</span><span class="sxs-lookup"><span data-stu-id="79f18-175">Excel</span></span>

- <span data-ttu-id="79f18-176">この変更により、数式内にフォントが正しく表示されないという問題に対処できます。</span><span class="sxs-lookup"><span data-stu-id="79f18-176">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="79f18-177">共同編集時に、一部のユーザーに対して、新しいバージョンのファイルを通知するメッセージ バーが誤って表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-177">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="79f18-178">Excel 4.0 マクロを含む Excel アドイン ファイルを開くときに、確認メッセージを表示せずにマクロが無効のままになる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-178">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="79f18-179">特定の Windows セキュリティのエクスプロイト保護設定 (SimExec、CallerCheck) を使用している場合に、Excel の起動に失敗したり、予期せず終了したりしてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-179">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="79f18-180">ピボットテーブルの [計算の種類] メニューの使用時に、Excel が予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-180">Fixed an issue where Excel might close unexpectedly when using the "Show Values As" menu for a PivotTable.</span></span>


- <span data-ttu-id="79f18-181">一部の従来の Excel 4.0 および Excel 5.0 マクロ、および dialogsheets.show への一部の VBA 呼び出しが破損する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-181">We fixed an issue that broke some legacy Excel 4.0 and Excel 5.0 macros as well as some VBA calls to dialogsheets.show.</span></span>


### <a name="outlook"></a><span data-ttu-id="79f18-182">Outlook</span><span class="sxs-lookup"><span data-stu-id="79f18-182">Outlook</span></span>

- <span data-ttu-id="79f18-183">ユーザーに保存を求めた後、編集した署名が保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-183">We fixed an issue that caused an edited signature to fail to save after prompting the user to do so.</span></span>


- <span data-ttu-id="79f18-184">特定の検索のシナリオで、Outlook が予期せず終了するという一部のユーザーに発生した問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-184">We fixed an issue that caused some users to experience Outlook closing unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="79f18-185">予定表の読み込み中にハングするという一部のお客様に発生した問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-185">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>


- <span data-ttu-id="79f18-186">プロファイルに大きな階層がある共有メールボックスまたは代理メールボックスを持つユーザーがハングするという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-186">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="79f18-187">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="79f18-187">PowerPoint</span></span>

- <span data-ttu-id="79f18-188">QAT で [フォントサイズ] コマンドが追加されたのに、更新すると最近定義されたフォント サイズにオート コンプリートするという問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-188">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="79f18-189">この変更により、数式内にフォントが正しく表示されないという問題に対処できます。</span><span class="sxs-lookup"><span data-stu-id="79f18-189">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="79f18-190">この変更により、特定のジオメトリで図形の結合操作を適用するときのパスの塗りつぶしに関する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-190">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


### <a name="office-suite"></a><span data-ttu-id="79f18-191">Office スイート</span><span class="sxs-lookup"><span data-stu-id="79f18-191">Office Suite</span></span>

- <span data-ttu-id="79f18-192">Anaheim WebView は、Windows 情報保護 (WIP) をまだサポートしていません。</span><span class="sxs-lookup"><span data-stu-id="79f18-192">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="79f18-193">この修正プログラムを適用すると、Office addin プラットフォームが、WIP が有効な環境でダウンレベルの WebView に戻ります。</span><span class="sxs-lookup"><span data-stu-id="79f18-193">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="79f18-194">お客様のコンピューター環境に応じて、Edge Spartan WebView または Trident WebView のいずれかになります。</span><span class="sxs-lookup"><span data-stu-id="79f18-194">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="79f18-195">ダウンレベル WebViews は、両方とも WIP をサポートしています。</span><span class="sxs-lookup"><span data-stu-id="79f18-195">Both down level WebViews support WIP.</span></span>


- <span data-ttu-id="79f18-196">最適化されたバイナリ サイズ。</span><span class="sxs-lookup"><span data-stu-id="79f18-196">Optimized binary size.</span></span>


- <span data-ttu-id="79f18-197">すべての相互依存のコンポーネントを正常に閉じる、ファイルの閉じ順序が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-197">Fixed the file closing sequence so that all the interdependent components are closed gracefully.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2011-february-09"></a><span data-ttu-id="79f18-199">バージョン 2011: 2 月 9 日</span><span class="sxs-lookup"><span data-stu-id="79f18-199">Version 2011: February 09</span></span>
<span data-ttu-id="79f18-200">*バージョン 2011 (ビルド 13426.20658)*</span><span class="sxs-lookup"><span data-stu-id="79f18-200">*Version 2011 (Build 13426.20658)*</span></span>

<span data-ttu-id="79f18-201">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="79f18-201">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2011-january-12"></a><span data-ttu-id="79f18-202">バージョン 2011: 1 月 12 日</span><span class="sxs-lookup"><span data-stu-id="79f18-202">Version 2011: January 12</span></span>
<span data-ttu-id="79f18-203">*バージョン 2011 (ビルド 13426.20526)*</span><span class="sxs-lookup"><span data-stu-id="79f18-203">*Version 2011 (Build 13426.20526)*</span></span>

<span data-ttu-id="79f18-204">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="79f18-204">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="79f18-206">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="79f18-206">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="79f18-207">Access</span><span class="sxs-lookup"><span data-stu-id="79f18-207">Access</span></span>

- <span data-ttu-id="79f18-208">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="79f18-208">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="79f18-209">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="79f18-209">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="79f18-210">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-210">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a><span data-ttu-id="79f18-211">Excel</span><span class="sxs-lookup"><span data-stu-id="79f18-211">Excel</span></span>

- <span data-ttu-id="79f18-212">**数式で使用する変数を作成する:** LET 関数を使用してパフォーマンス、読みやすさ、および構成性を向上させます。</span><span class="sxs-lookup"><span data-stu-id="79f18-212">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="79f18-213">この関数では、新規または既存の数式に名前付き変数を作成することができます。</span><span class="sxs-lookup"><span data-stu-id="79f18-213">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="79f18-214">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-214">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="79f18-215">[ブログの投稿](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-215">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="79f18-216">**Power Query でカスタム データ型を作成する:** 任意のデータ ソースを使用して、関連する複数の情報を 1 つの列に読み込むカスタム データ型を作成します。</span><span class="sxs-lookup"><span data-stu-id="79f18-216">**Create a custom data type in Power Query:** Use any data source to create a custom data type that lets you load multiple related pieces of information into one column.</span></span> [<span data-ttu-id="79f18-217">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-217">Learn more</span></span>](https://support.office.com/article/a465a3b7-3d37-4eb1-a59c-bd3163315308)<br /><span data-ttu-id="79f18-218">[ブログの投稿](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-218">See details in [blog post](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)</span></span>

- <span data-ttu-id="79f18-219">**ソース クエリを基に新しいシートに名前を付ける:** データが新しいシートに読み込まれると、シートはソース クエリの名前に基づいて名付けられます。</span><span class="sxs-lookup"><span data-stu-id="79f18-219">**Name the new sheet after the source query:** When the data is loaded into the new sheet, the sheet will be named based on the name of the source query.</span></span>

- <span data-ttu-id="79f18-220">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="79f18-220">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="79f18-221">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="79f18-221">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="79f18-222">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-222">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a><span data-ttu-id="79f18-223">OneNote</span><span class="sxs-lookup"><span data-stu-id="79f18-223">OneNote</span></span>

- <span data-ttu-id="79f18-224">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="79f18-224">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="79f18-225">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="79f18-225">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="79f18-226">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-226">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a><span data-ttu-id="79f18-227">Outlook</span><span class="sxs-lookup"><span data-stu-id="79f18-227">Outlook</span></span>

- <span data-ttu-id="79f18-228">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="79f18-228">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="79f18-229">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="79f18-229">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="79f18-230">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-230">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


### <a name="powerpoint"></a><span data-ttu-id="79f18-231">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="79f18-231">PowerPoint</span></span>

- <span data-ttu-id="79f18-232">**ビデオ ライブラリ:** アプリ内で利用可能な、質の良い無料のビデオ フッテージのライブラリを使用してドキュメントの質を高めます。</span><span class="sxs-lookup"><span data-stu-id="79f18-232">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app.</span></span>

- <span data-ttu-id="79f18-233">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="79f18-233">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="79f18-234">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="79f18-234">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="79f18-235">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-235">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a><span data-ttu-id="79f18-236">Project</span><span class="sxs-lookup"><span data-stu-id="79f18-236">Project</span></span>

- <span data-ttu-id="79f18-237">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="79f18-237">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="79f18-238">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="79f18-238">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="79f18-239">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-239">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a><span data-ttu-id="79f18-240">発行者</span><span class="sxs-lookup"><span data-stu-id="79f18-240">Publisher</span></span>

- <span data-ttu-id="79f18-241">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="79f18-241">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="79f18-242">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="79f18-242">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="79f18-243">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-243">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a><span data-ttu-id="79f18-244">Visio</span><span class="sxs-lookup"><span data-stu-id="79f18-244">Visio</span></span>

- <span data-ttu-id="79f18-245">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="79f18-245">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="79f18-246">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="79f18-246">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="79f18-247">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-247">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a><span data-ttu-id="79f18-248">Word</span><span class="sxs-lookup"><span data-stu-id="79f18-248">Word</span></span>

- <span data-ttu-id="79f18-249">**Office テーマを自動的に切り替える:** Office では、Windows 10 のテーマの設定に合わせてテーマを自動的に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="79f18-249">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="79f18-250">[ファイル] > [アカウント] の順に移動し、[Office テーマ] ドロップダウンで [システム設定を使用する] を選択します。</span><span class="sxs-lookup"><span data-stu-id="79f18-250">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="79f18-251">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-251">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="79f18-254">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="79f18-254">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="79f18-255">Excel</span><span class="sxs-lookup"><span data-stu-id="79f18-255">Excel</span></span>

- <span data-ttu-id="79f18-256">Excel によってファイルの新しいバージョンが使用可能であることを示すメッセージバーが誤って表示され、ブックのコピーに変更内容を保存するか、変更内容を破棄するように強制する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-256">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="79f18-257">Excel 4.0 マクロを含む Excel アドイン ファイルを開いたときにプロンプトが表示されずに Excel がマクロを無効のままにしてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-257">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


### <a name="outlook"></a><span data-ttu-id="79f18-258">Outlook</span><span class="sxs-lookup"><span data-stu-id="79f18-258">Outlook</span></span>

- <span data-ttu-id="79f18-259">1 つ以上の署名が構成されているにもかかわらず、ユーザーの署名が署名ドロップダウンに表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-259">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


- <span data-ttu-id="79f18-260">IDataObject 操作 (つまりクリップボードのドラッグやドロップ) で、ユーザーが添付ファイルに対して filetime の付加を無効にできるように、regkey を追加しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-260">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="79f18-261">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="79f18-261">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span> <span data-ttu-id="79f18-262">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="79f18-262">REG_DWORD IncludeFileTimesInDataObject.</span></span> <span data-ttu-id="79f18-263">0 = filetimes は除外されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-263">0 = filetimes are excluded.</span></span> <span data-ttu-id="79f18-264">1 = (既定) filetimes が含まれます。</span><span class="sxs-lookup"><span data-stu-id="79f18-264">1 = (default) filetimes are included.</span></span>


- <span data-ttu-id="79f18-265">Azure Information Protection の保護ラベルを使用してメッセージに返信するときに、インライン画像が消えるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-265">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="79f18-266">MailItem.BeforeAttachmentAdd イベントの破損原因となっていた問題を修正しました。 </span><span class="sxs-lookup"><span data-stu-id="79f18-266">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="79f18-267">タスクの進捗レポートを送信するときに、[宛先] フィールドが空白になってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-267">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


- <span data-ttu-id="79f18-268">他の出席者が会議を転送すると、会議の元の出席者の一部がキャンセルを受信してしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-268">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="79f18-269">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="79f18-269">PowerPoint</span></span>

- <span data-ttu-id="79f18-270">ドキュメントの修復操作の後であっても、一部の破損した PowerPoint ファイルを正常に開くことができないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-270">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="79f18-271">新たに録音したオーディオを含むスライドを複製した後にファイルを保存するときにエラーが発生してしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-271">We fixed an issue where there is an error when saving the file after duplicating a slide that contains a newly recorded audio.</span></span>


- <span data-ttu-id="79f18-272">Slide.Shapes.AddMediaObject2 が従来のビデオ形式 (.MPG-1、Mpeg-2) でクラッシュする VBA の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-272">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="79f18-273">この変更により、ビデオの読み込み中に発生する可能性のあるエラーの処理に関する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-273">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="79f18-274">Word から PowerPoint への数式のコピー/貼り付けに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-274">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


### <a name="project"></a><span data-ttu-id="79f18-275">Project</span><span class="sxs-lookup"><span data-stu-id="79f18-275">Project</span></span>

- <span data-ttu-id="79f18-276">ロードの特定の部分でプロジェクト ファイルに問題がある場合に、特定のプロジェクトを開くことができるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-276">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="word"></a><span data-ttu-id="79f18-277">Word</span><span class="sxs-lookup"><span data-stu-id="79f18-277">Word</span></span>

- <span data-ttu-id="79f18-278">最適化されたゲートが Word に影響を与えるアサート バグを修正します。</span><span class="sxs-lookup"><span data-stu-id="79f18-278">Fix an assert bug exposed by optimized gates affecting Word.</span></span>


- <span data-ttu-id="79f18-279">文書のスタイルがテンプレートとは別のスタイルに置き換わってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-279">We fixed an issue which document styles are replaced with other styles from the template.</span></span>


- <span data-ttu-id="79f18-280">この変更により、ドキュメントを編集するときのカーソルに関する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-280">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="79f18-281">Word から PowerPoint への数式のコピー/貼り付けに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-281">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


### <a name="office-suite"></a><span data-ttu-id="79f18-282">Office スイート</span><span class="sxs-lookup"><span data-stu-id="79f18-282">Office Suite</span></span>

- <span data-ttu-id="79f18-283">新しいバージョンの Office を特定の古いバージョンの Office の上からインストールすると、レジストリ エントリが存在していないために機能が低下してしまう (Power Query を使用できないなど) という問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-283">Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>


- <span data-ttu-id="79f18-284">キャッシュからの URL と OneDrive からの URL が一致しない場合に、ファイルが NOT SyncBacked として開かれてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-284">Fixed an issue of file would be opened as NOT SyncBacked when url from cache and url from OneDrive does NOT match.</span></span>


- <span data-ttu-id="79f18-285">SaveRequestManagerCam が原因で、エラーが返される代わりにアプリケーションが閉じられる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-285">We fixed an issue where SaveRequestManagerCam was causing the application to close instead of returning an error.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2010-january-12"></a><span data-ttu-id="79f18-287">バージョン 2010: 1 月 12 日</span><span class="sxs-lookup"><span data-stu-id="79f18-287">Version 2010: January 12</span></span>
<span data-ttu-id="79f18-288">*バージョン 2010 (ビルド 13328.20550)*</span><span class="sxs-lookup"><span data-stu-id="79f18-288">*Version 2010 (Build 13328.20550)*</span></span>

<span data-ttu-id="79f18-289">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="79f18-289">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2010-december-08"></a><span data-ttu-id="79f18-290">バージョン 2010: 12 月 08 日</span><span class="sxs-lookup"><span data-stu-id="79f18-290">Version 2010: December 08</span></span>
<span data-ttu-id="79f18-291">*バージョン 2010 (ビルド 13328.20478)*</span><span class="sxs-lookup"><span data-stu-id="79f18-291">*Version 2010 (Build 13328.20478)*</span></span>

<span data-ttu-id="79f18-292">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="79f18-292">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="79f18-294">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="79f18-294">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="79f18-295">Excel</span><span class="sxs-lookup"><span data-stu-id="79f18-295">Excel</span></span>

- <span data-ttu-id="79f18-296">**Power BI からデータ型を使用して組織データを取得する:** Power BI からの Excel データ型が Office 365、Microsoft 365、Power BI Pro サービス プランを使用する組織の Insider にロールアウトされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="79f18-296">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 / Microsoft 365 and the Power BI Pro service plan.</span></span> <span data-ttu-id="79f18-297">必要な情報を入手し、簡単に更新することは、多くの日常のワークフローに欠かせません。</span><span class="sxs-lookup"><span data-stu-id="79f18-297">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="79f18-298">Excel のデータ型として、Power BI から会社または組織の情報へのアクセスを提供し、スプレッドシートにリンクされた情報を取り込む機能を拡張します。</span><span class="sxs-lookup"><span data-stu-id="79f18-298">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="79f18-299">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-299">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="79f18-300">[ブログの投稿](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-300">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="79f18-301">Outlook</span><span class="sxs-lookup"><span data-stu-id="79f18-301">Outlook</span></span>

- <span data-ttu-id="79f18-302">**タスクのユーザー エクスペリエンスの更新:** タスク アイテムの視覚的な更新</span><span class="sxs-lookup"><span data-stu-id="79f18-302">**User Experience Updates for Tasks:** A visual refresh of task items</span></span>

- <span data-ttu-id="79f18-303">**メール内のリンクの改善:** ファイルへのリンクを含めると、ファイル名が URL に置き換わります。</span><span class="sxs-lookup"><span data-stu-id="79f18-303">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="79f18-304">アクセス許可を変更して、すべての受信者がアクセスできるようにすることができます。</span><span class="sxs-lookup"><span data-stu-id="79f18-304">You can change permissions so all recipients have access.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="79f18-305">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="79f18-305">PowerPoint</span></span>

- <span data-ttu-id="79f18-306">**アニメーション GIF を範囲内でエクスポートする**: アニメーション GIF にエクスポートするときにスライドの範囲を選択します</span><span class="sxs-lookup"><span data-stu-id="79f18-306">**Export animated GIF in a range:** Select a range of slides when exporting to animated GIF</span></span>

- <span data-ttu-id="79f18-307">**透過背景の GIF を作成する**: アニメーション GIF にエクスポートする場合、新しいオプションを使用して背景を透明にすることができます。</span><span class="sxs-lookup"><span data-stu-id="79f18-307">**Create GIFs with Transparent Backgrounds:** When exporting to an Animated GIF, a new option will allow you to make the background transparent.</span></span><br /><span data-ttu-id="79f18-308">[ブログの投稿](https://insider.office.com/ja-JP/blog/export-animated-gifs-transparent-backgrounds)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-308">See details in [blog post](https://insider.office.com/ja-JP/blog/export-animated-gifs-transparent-backgrounds)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="79f18-311">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="79f18-311">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="79f18-312">Access</span><span class="sxs-lookup"><span data-stu-id="79f18-312">Access</span></span>

- <span data-ttu-id="79f18-313">Office 以外のアプリケーションから DAO を使用すると、アプリケーションが予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-313">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="outlook"></a><span data-ttu-id="79f18-314">Outlook</span><span class="sxs-lookup"><span data-stu-id="79f18-314">Outlook</span></span>

- <span data-ttu-id="79f18-315">Outlook でクラウド設定を有効にしているユーザーに対して、2つ目の空白の署名を作成するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-315">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


- <span data-ttu-id="79f18-316">ユーザーに対してクラウド設定が既定でオンにならない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-316">We fixed a n issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="79f18-317">ユーザーの署名への変更が保存できない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-317">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>


- <span data-ttu-id="79f18-318">返信または転送時に中国語メッセージのヘッダーが読み取れなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-318">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="79f18-319">OFT ファイルとして保存するときに中国語の文字が疑問符に変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-319">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="79f18-320">IDataObject 操作 (つまりクリップボードのドラッグやドロップ) で、ユーザーが添付ファイルに対して filetime の付加を無効にできるように、regkey を追加しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-320">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="79f18-321">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="79f18-321">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span>  <span data-ttu-id="79f18-322">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="79f18-322">REG_DWORD IncludeFileTimesInDataObject.</span></span>  <span data-ttu-id="79f18-323">0 = filetimes は除外されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-323">0 = filetimes are excluded.</span></span>  <span data-ttu-id="79f18-324">1 = (既定) filetimes が含まれます。</span><span class="sxs-lookup"><span data-stu-id="79f18-324">1 = (default) filetimes are included.</span></span>


- <span data-ttu-id="79f18-325">MailItem.BeforeAttachmentAdd イベントの破損原因となった問題が修正されました。 </span><span class="sxs-lookup"><span data-stu-id="79f18-325">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="79f18-326">他の出席者が会議を転送すると、会議の元の出席者の一部がキャンセルを受信するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-326">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="79f18-327">ユーザーが代理人に編集者権限を付与できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-327">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="79f18-328">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="79f18-328">PowerPoint</span></span>

- <span data-ttu-id="79f18-329">これは、PresentationBeforeClose イベントを聞き、イベント ハンドラーの一部として Presentation.Saved プロパティをチェックするアドインがある場合、ドキュメントを閉じるときに保存プロンプトがループで表示される問題の修正です。</span><span class="sxs-lookup"><span data-stu-id="79f18-329">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


- <span data-ttu-id="79f18-330">マージ中に IRM/ 保護されたドキュメントを使用しているときに発生する問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="79f18-330">Fix to address a an issue when using IRM/protected documents during a merge error.</span></span>


- <span data-ttu-id="79f18-331">Word から Powerpoint への数式のコピーと貼り付けに関する問題を修正した。</span><span class="sxs-lookup"><span data-stu-id="79f18-331">Fixed an issue with copy/paste of an equation from Word to Powerpoint.</span></span>


### <a name="project"></a><span data-ttu-id="79f18-332">Project</span><span class="sxs-lookup"><span data-stu-id="79f18-332">Project</span></span>

- <span data-ttu-id="79f18-333">リソースの配分状況が特定の方法で指定されているファイルを開くと、Project が予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-333">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="79f18-334">プロジェクトを PWA からローカル mpp ファイルに保存すると、ユーザーが実際に変更していないデータに対して ProjectBeforeTaskChangeEvent が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-334">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="79f18-335">タスクフォームタイプビュー内でラグが変更された場合、ProjectBeforeTaskChagne イベントの NewVal に正しい値がない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-335">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


### <a name="visio"></a><span data-ttu-id="79f18-336">Visio</span><span class="sxs-lookup"><span data-stu-id="79f18-336">Visio</span></span>

- <span data-ttu-id="79f18-337">問題が修正され、ユーザーが Visio for Office 365 のコネクタを使用して、ユーザー設定の Visio ステンシルと組み込みのテンプレートの両方で直線を作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="79f18-337">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="79f18-338">Word</span><span class="sxs-lookup"><span data-stu-id="79f18-338">Word</span></span>

- <span data-ttu-id="79f18-339">Word から Powerpoint への数式のコピーと貼り付けに関する問題を修正した。</span><span class="sxs-lookup"><span data-stu-id="79f18-339">Fixed an issue with copy/paste of an equation from Word to Powerpoint.</span></span>


### <a name="office-suite"></a><span data-ttu-id="79f18-340">Office スイート</span><span class="sxs-lookup"><span data-stu-id="79f18-340">Office Suite</span></span>

- <span data-ttu-id="79f18-341">Microsoft 365 エンドポイントのデータ損失防止が、ディスク上の Office ドキュメントを分類できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-341">Fixed an issue where Microsoft 365 Endpoint data loss prevention was unable to classify Office documents on disk.</span></span>


- <span data-ttu-id="79f18-342">Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-342">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="79f18-343">このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-343">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="79f18-344">コメントから Excel にテキストをコピーして貼り付けるときにエラーが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-344">Fixed an issue where an error would occur when copy/paste text from a comment into Excel.</span></span>


- <span data-ttu-id="79f18-345">特定のシナリオで、[名前を付けて保存] の実行に失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-345">Fixed an issue where trying to do a SaveAs would fail in certain scenarios.</span></span>


- <span data-ttu-id="79f18-346">同期バックからサーバーのみに移行したファイルを保存しようとすると失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-346">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2009-december-08"></a><span data-ttu-id="79f18-348">バージョン 2009: 12 月 08 日</span><span class="sxs-lookup"><span data-stu-id="79f18-348">Version 2009: December 08</span></span>
<span data-ttu-id="79f18-349">*バージョン 2009 (ビルド 13231.20620)*</span><span class="sxs-lookup"><span data-stu-id="79f18-349">*Version 2009 (Build 13231.20620)*</span></span>

<span data-ttu-id="79f18-350">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="79f18-350">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2009-november-10"></a><span data-ttu-id="79f18-351">バージョン 2009: 11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="79f18-351">Version 2009: November 10</span></span>
<span data-ttu-id="79f18-352">*バージョン2009 (ビルド 13231.20514)*</span><span class="sxs-lookup"><span data-stu-id="79f18-352">*Version 2009 (Build 13231.20514)*</span></span>

<span data-ttu-id="79f18-353">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="79f18-353">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="79f18-355">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="79f18-355">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="79f18-356">Excel</span><span class="sxs-lookup"><span data-stu-id="79f18-356">Excel</span></span>

- <span data-ttu-id="79f18-357">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="79f18-357">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="79f18-358">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="79f18-358">PowerPoint</span></span>

- <span data-ttu-id="79f18-359">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="79f18-359">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="79f18-360">Word</span><span class="sxs-lookup"><span data-stu-id="79f18-360">Word</span></span>

- <span data-ttu-id="79f18-361">**秘密度ラベルの自動適用または推奨:** Office は、検出された機密コンテンツに基づいて機密ラベルを推奨または自動的に適用できます。</span><span class="sxs-lookup"><span data-stu-id="79f18-361">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="79f18-364">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="79f18-364">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="79f18-365">Outlook</span><span class="sxs-lookup"><span data-stu-id="79f18-365">Outlook</span></span>

- <span data-ttu-id="79f18-366">返信または転送時に中国語メッセージのヘッダーが読み取れなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-366">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="79f18-367">代理人が別のメールボックスで共有フォルダーを開くと、断続的にエラーが表示される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-367">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="79f18-368">件名が空白の場合、一部の自動的に生成されたメールの本文が空で送信される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-368">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="79f18-369">一部のユーザーの環境で、Outlook がオフラインの状態で予期せず起動する原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-369">Addressed an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="79f18-370">キャッシュされていない共有の予定表を検索するときに、結果が返されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-370">Addressed an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="79f18-371">ユーザーが検索結果を選択したときにアプリケーションが予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-371">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="79f18-372">ユーザーが代理人に編集者権限を付与できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-372">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="79f18-373">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="79f18-373">PowerPoint</span></span>

- <span data-ttu-id="79f18-374">特定のデータ オブジェクト タイプ (E2o) を大量に含むファイルの共同編集が遅くなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-374">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>


- <span data-ttu-id="79f18-375">セキュリティ修正プログラムを適用して、保護ビューで PowerPoint ファイルを開くと、 IRM による保護が無効になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-375">We fixed an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


- <span data-ttu-id="79f18-376">ユーザーが別のスライドをクリックして表示するまで、Forms コンテンツ アドインが挿入後にレンダリングされない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-376">We fixed an issue where Forms content add-in doesn't render after insertion until user clicks to another slide to make it show.</span></span>


### <a name="project"></a><span data-ttu-id="79f18-377">Project</span><span class="sxs-lookup"><span data-stu-id="79f18-377">Project</span></span>

- <span data-ttu-id="79f18-378">イベント コードの実行中に、[タスク フォーム] ビューから変更を加えようとするときに、[OK] ボタンをクリックしても変更が反映されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-378">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="79f18-379">リソースの配分状況が特定の方法で指定されているファイルを開くと、Project が予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-379">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="79f18-380">プロジェクトを PWA からローカル mpp ファイルに保存すると、ユーザーが実際に変更していないデータに対して ProjectBeforeTaskChangeEvent が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-380">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


### <a name="word"></a><span data-ttu-id="79f18-381">Word</span><span class="sxs-lookup"><span data-stu-id="79f18-381">Word</span></span>

- <span data-ttu-id="79f18-382">スタイル ギャラリー ダイアログの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-382">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="79f18-383">Office スイート</span><span class="sxs-lookup"><span data-stu-id="79f18-383">Office Suite</span></span>

- <span data-ttu-id="79f18-384">[図の圧縮] ダイアログで一部のユーザー設定が保持されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-384">We fixed an issue with the Compress Picture dialog not retaining certain user settings.</span></span>


- <span data-ttu-id="79f18-385">Microsoft 365 エンドポイントのデータ損失防止が、ディスク上の Office ドキュメントを分類できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-385">Fixed an issue where Microsoft 365 Endpoint data loss prevention was unable to classify Office documents on disk.</span></span>


- <span data-ttu-id="79f18-386">Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-386">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="79f18-387">このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-387">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-november-10"></a><span data-ttu-id="79f18-389">バージョン 2008: 11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="79f18-389">Version 2008: November 10</span></span>
<span data-ttu-id="79f18-390">*バージョン 2008 (ビルド 13127.20760)*</span><span class="sxs-lookup"><span data-stu-id="79f18-390">*Version 2008 (Build 13127.20760)*</span></span>

<span data-ttu-id="79f18-391">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="79f18-391">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="79f18-393">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="79f18-393">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="79f18-394">Excel</span><span class="sxs-lookup"><span data-stu-id="79f18-394">Excel</span></span>

- <span data-ttu-id="79f18-395">マクロを使用して、範囲の FormulaR1C1 プロパティを設定する問題を修正しました。グラフ シートがアクティブ シートである場合、セル参照が正しくありませんでした。</span><span class="sxs-lookup"><span data-stu-id="79f18-395">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="79f18-396">Excel で 1 つまたは複数の数式を計算しようとする際に発生する、Excelはリソース不足になりましたというエラーが生じる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-396">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="79f18-397">Office の言語がスペイン語に設定されているときに、データ検証リストにすべてのアイテムが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-397">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="79f18-398">OLAP PivotTables を更新するときにハングする場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-398">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="79f18-399">ブックをロードした後、特定の関数の結果が不正確であるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-399">We fixed an issue where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="79f18-400">XLAM アドイン参照と名前付き範囲に関連するアプリケーションが予期せず終了する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-400">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>

### <a name="outlook"></a><span data-ttu-id="79f18-401">Outlook</span><span class="sxs-lookup"><span data-stu-id="79f18-401">Outlook</span></span>

- <span data-ttu-id="79f18-402">返信または転送時に中国語メッセージのヘッダーが文字化けする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-402">We fixed an issue that caused the headers of Chinese messages to get garbled when replying or forwarding.</span></span>


- <span data-ttu-id="79f18-403">件名が空白の場合、一部の自動的に生成されたメールの本文が空で送信される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-403">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="79f18-404">代理人が別のメールボックスで共有フォルダーを開くと、断続的にエラーが表示される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-404">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="79f18-405">グループ予定表で検索結果が返されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-405">We fixed an issue that caused searches in Group calendars fail to return any results.</span></span>


- <span data-ttu-id="79f18-406">ユーザーが検索結果を選択したときにアプリケーションが予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-406">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="79f18-407">Outlook の IRM (Information Rights Management) を他の Office アプリケーションで無効にすることなく無効にできる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-407">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="79f18-408">ユーザーが代理人に編集者権限を付与できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-408">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="79f18-409">オプションの接続エクスペリエンスが Web アドインの読み込みをブロックする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-409">We fixed an issue where optional connected experiences blocked web add-ins from loading.</span></span><br /><span data-ttu-id="79f18-410">
  [ブログの投稿](https://developer.microsoft.com/ja-JP/office/blogs/outlook-add-ins-and-optional-connected-experiences/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-410">See details in [blog post](https://developer.microsoft.com/ja-JP/office/blogs/outlook-add-ins-and-optional-connected-experiences/)</span></span>


### <a name="powerpoint"></a><span data-ttu-id="79f18-411">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="79f18-411">PowerPoint</span></span>

- <span data-ttu-id="79f18-412">これは、PresentationBeforeClose イベントを聞き、イベント ハンドラーの一部として Presentation.Saved プロパティをチェックするアドインがある場合、ドキュメントを閉じるときに保存プロンプトがループで表示される問題の修正です。</span><span class="sxs-lookup"><span data-stu-id="79f18-412">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


- <span data-ttu-id="79f18-413">ユーザーが別のスライドをクリックして表示するまで、Forms コンテンツ アドインが挿入後にレンダリングされない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-413">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>


### <a name="office-suite"></a><span data-ttu-id="79f18-414">Office スイート</span><span class="sxs-lookup"><span data-stu-id="79f18-414">Office Suite</span></span>

- <span data-ttu-id="79f18-415">Microsoft 365 エンドポイントのデータ損失防止を使用して Office Update に System Center Configuration Manager またはその他の管理ツールを利用する商用顧客の問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-415">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>

- <span data-ttu-id="79f18-416">Office アドインのメッセージング API が機能しない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="79f18-416">Fix an issue that the Messaging API for Office Add-ins is not working.</span></span>



[//]: # (BUGDETAILS コンテンツ エンドを削除しないでください。終了)

## <a name="version-2008-october-13"></a><span data-ttu-id="79f18-418">バージョン 2008: 10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="79f18-418">Version 2008: October 13</span></span>
<span data-ttu-id="79f18-419">*バージョン 2008 (Build 13127.20638)*</span><span class="sxs-lookup"><span data-stu-id="79f18-419">*Version 2008 (Build 13127.20638)*</span></span>

<span data-ttu-id="79f18-420">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="79f18-420">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="79f18-422">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="79f18-422">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="79f18-423">Excel</span><span class="sxs-lookup"><span data-stu-id="79f18-423">Excel</span></span>

- <span data-ttu-id="79f18-424">**質問がある場合のExcel への質問:** Excel のアイデアを使用すると、データについて質問をすることができます。数式の記述に時間を費やす必要はありません(英語のみ使用可能)。</span><span class="sxs-lookup"><span data-stu-id="79f18-424">**Have a question? Ask Excel:** Now Excel Ideas allows you to ask questions about your data - no need to spend time writing formulas (available in English only).</span></span> [<span data-ttu-id="79f18-425">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-425">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- <span data-ttu-id="79f18-426">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="79f18-426">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="79f18-427">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="79f18-427">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="79f18-428">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="79f18-428">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="79f18-429">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="79f18-429">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="79f18-430">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-430">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="79f18-431">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-431">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

- <span data-ttu-id="79f18-432">**PDF に接続:** PDF からデータに接続、インポート、更新します。</span><span class="sxs-lookup"><span data-stu-id="79f18-432">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="79f18-433">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-433">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="79f18-434">**図形を画像として保存する:** 簡単なクリック操作で図形、アイコン、その他のオブジェクトを画像ファイルとして保存し、別の場所で再利用することができます。</span><span class="sxs-lookup"><span data-stu-id="79f18-434">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="79f18-435">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-435">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="79f18-436">**Excel で洗練された Visio 図を作成する:** ワークシートにデータを入力して、フロー チャートまたは組織図を作成します。</span><span class="sxs-lookup"><span data-stu-id="79f18-436">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="79f18-437">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-437">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a><span data-ttu-id="79f18-438">Outlook</span><span class="sxs-lookup"><span data-stu-id="79f18-438">Outlook</span></span>

- <span data-ttu-id="79f18-439">**クイック投票を使用して、Outlook で投票を作成:** 簡単に投票を作成し、票を収集して、メールに結果を表示します。[詳細情報](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="79f18-439">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="79f18-440">**Outlook の新しいプロファイル カード:** Outlook の新しいプロファイル カードは、組織ビューが改善され、Outlook Web のカード スタイルに一致します。</span><span class="sxs-lookup"><span data-stu-id="79f18-440">**New profile card for Outlook:** New profile card for Outlook including a better Organization view and matches the card style of Outlook Web.</span></span> [<span data-ttu-id="79f18-441">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-441">Learn more</span></span>](https://support.office.com/article/e80f931f-5fc4-4a59-ba6e-c1e35a85b501)

### <a name="powerpoint"></a><span data-ttu-id="79f18-442">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="79f18-442">PowerPoint</span></span>

- <span data-ttu-id="79f18-443">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="79f18-443">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="79f18-444">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="79f18-444">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="79f18-445">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="79f18-445">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="79f18-446">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="79f18-446">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="79f18-447">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-447">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="79f18-448">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-448">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="79f18-449">Word</span><span class="sxs-lookup"><span data-stu-id="79f18-449">Word</span></span>

- <span data-ttu-id="79f18-450">**固定フォルダーに保存する:** フォルダーをピン留めすると、Office ファイルの保存が簡単になります。</span><span class="sxs-lookup"><span data-stu-id="79f18-450">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span>  <span data-ttu-id="79f18-451">ユーザーは新しいファイルが保存されるときに使用可能なフォルダーをより詳細に制御したいとのフィードバックを受けました。</span><span class="sxs-lookup"><span data-stu-id="79f18-451">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="79f18-452">新しい機能が追加されました。 [保存] ダイアログ ボックスでフォルダーをピン留めできます。</span><span class="sxs-lookup"><span data-stu-id="79f18-452">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="79f18-453">この新しい機能により、Word、Excel、PowerPoint のファイルを簡単に保存できます。</span><span class="sxs-lookup"><span data-stu-id="79f18-453">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="79f18-454">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-454">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="79f18-455">[ブログの投稿](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-455">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="79f18-458">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="79f18-458">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="79f18-459">Access</span><span class="sxs-lookup"><span data-stu-id="79f18-459">Access</span></span>

- <span data-ttu-id="79f18-460">この問題は解決されました。これで、Office のクイック実行アプリケーション以外でも ODBC ドライバーを使用できます。</span><span class="sxs-lookup"><span data-stu-id="79f18-460">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>


- <span data-ttu-id="79f18-461">テキストを編集するため [ズーム] ボックスを起動する (Shift + F2) ときに、Access がクラッシュする可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-461">This change fixes an issue that could cause Access to crash when launching the Zoom box (Shift + F2) to edit text.</span></span>


- <span data-ttu-id="79f18-462">この問題は解決されましたので、クラッシュが発生しなくなったはずです。</span><span class="sxs-lookup"><span data-stu-id="79f18-462">This issue has now been resolved and you should no longer experience a crash.</span></span>


### <a name="excel"></a><span data-ttu-id="79f18-463">Excel</span><span class="sxs-lookup"><span data-stu-id="79f18-463">Excel</span></span>

- <span data-ttu-id="79f18-464">IFNA () を使用する数式が含まれている場合、破損したワークブックに関する警告を発する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-464">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


- <span data-ttu-id="79f18-465">シートの一番上の行を固定した後にクイック分析を使用すると Excel がクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-465">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="79f18-466">Analysis Services データベースに既に存在しない値に設定されているために、ユーザーがピボットテーブル フィルターを変更できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-466">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="79f18-467">Format Painter を使用すると、特定の状況で Excel がクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-467">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>


- <span data-ttu-id="79f18-468">' 前 ' と ' 後 ' のフィルター条件が逆転する バグをPivotDateFilter Api で修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-468">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


### <a name="outlook"></a><span data-ttu-id="79f18-469">Outlook</span><span class="sxs-lookup"><span data-stu-id="79f18-469">Outlook</span></span>

- <span data-ttu-id="79f18-470">ユーザーが新しいメールに返信または作成するときに次のエラーを受け取る原因となった問題に対処します。「この Web ページのファイルの一部が予期された場所にありません。</span><span class="sxs-lookup"><span data-stu-id="79f18-470">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="79f18-471">この Web ページをダウンロードする必要がありますか? </span><span class="sxs-lookup"><span data-stu-id="79f18-471">Do you want to download them anyway?</span></span> <span data-ttu-id="79f18-472">Web ページが信頼できるソースからのものであることを確認したら、[はい] をクリックします。」</span><span class="sxs-lookup"><span data-stu-id="79f18-472">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


- <span data-ttu-id="79f18-473">右クリックのコンテキストメニューが検索コントロールに表示されない問題の原因を解決しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-473">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>


- <span data-ttu-id="79f18-474">コンパクト ビューを使用するときに異常が表示される原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-474">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>


- <span data-ttu-id="79f18-475">これにより、受信者を編集しているときに時折クラッシュする問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-475">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>


- <span data-ttu-id="79f18-476">一部のユーザーにスケジュール アシスタント ページが表示されない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-476">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>


- <span data-ttu-id="79f18-477">添付ファイルのアップロードのパフォーマンスの問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="79f18-477">Addresses a performance issue with attachment upload.</span></span>


- <span data-ttu-id="79f18-478">[ヘッダーのみダウンロード] オプションが選択されている POP アカウントから 4 件以上のメールを削除しようとするとクラッシュするという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-478">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>


- <span data-ttu-id="79f18-479">クラウドの添付ファイルを開くときに、開こうとしていたドキュメントの代わりに、安全なリンクの ページにエラーが表示される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="79f18-479">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="79f18-480">クラウドの添付ファイルを操作するときに、ユーザーに時折クラッシュが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-480">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>


- <span data-ttu-id="79f18-481">隅にある [X] をクリックして共有の予定表を閉じることができない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="79f18-481">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="79f18-482">共有メールボックスを追加した後に、ユーザーがパブリック フォルダーに接続できない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-482">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


- <span data-ttu-id="79f18-483">特定の状況で代理人が会議を辞退したときに、マネージャーのカレンダーから削除されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-483">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>


- <span data-ttu-id="79f18-484">共有カレンダーの改善機能を使用している一部のユーザーが、新しく追加された共有カレンダーを表示できない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-484">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>


- <span data-ttu-id="79f18-485">[共有予定表の改善機能を有効にする] 設定が既存の共有予定表に適用されないことがある問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="79f18-485">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="79f18-486">プロファイルに追加されたサブ アカウントから会議出席依頼を作成しようとした場合に、ユーザーのメール アドレスの代わりに空欄の From: フィールドが表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-486">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="79f18-487">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="79f18-487">PowerPoint</span></span>

- <span data-ttu-id="79f18-488">PowerPoint アプリのクラッシュの原因となった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-488">We have fixed an issue which was causing the crash in PowerPoint app.</span></span>


- <span data-ttu-id="79f18-489">セキュリティ修正プログラムを適用して、保護ビューで PowerPoint ファイルを開くと、 IRM による保護が無効になる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="79f18-489">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


- <span data-ttu-id="79f18-490">この変更により、[エクスポート] ボタンをクリックしてもエクスポートされないという [アニメーション GIF にエクスポート] 機能の問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="79f18-490">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


### <a name="project"></a><span data-ttu-id="79f18-491">Project</span><span class="sxs-lookup"><span data-stu-id="79f18-491">Project</span></span>

- <span data-ttu-id="79f18-492">SharePoint タスクリストに接続されているプロジェクトのプロジェクト終了日が更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-492">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>


- <span data-ttu-id="79f18-493">リソースに複数のコスト単価表が定義されている場合に、残りのコストが正しく計算されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-493">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

### <a name="skype"></a><span data-ttu-id="79f18-494">Skype</span><span class="sxs-lookup"><span data-stu-id="79f18-494">Skype</span></span>

- <span data-ttu-id="79f18-495">ダンス絵文字の肌の色を中間色に変更しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-495">Changed dancing emoticon skin tone to neutral color.</span></span>


### <a name="visio"></a><span data-ttu-id="79f18-496">Visio</span><span class="sxs-lookup"><span data-stu-id="79f18-496">Visio</span></span>

- <span data-ttu-id="79f18-497">テキストを配置するとリアルタイムのプレビューがクラッシュする問題がお客様から報告されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-497">Live preview crashes on text alignment reported by customers.</span></span> <span data-ttu-id="79f18-498">7 月のフォークで最も多く報告されているクラッシュ。</span><span class="sxs-lookup"><span data-stu-id="79f18-498">Top hitting crash of July fork.</span></span>


### <a name="word"></a><span data-ttu-id="79f18-499">Word</span><span class="sxs-lookup"><span data-stu-id="79f18-499">Word</span></span>

- <span data-ttu-id="79f18-500">マクロ AutoOpen が AutoExec の前に実行されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-500">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>


- <span data-ttu-id="79f18-501">スタイル ギャラリー ダイアログの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-501">We fixed an issue with Style Gallery dialog.</span></span>


- <span data-ttu-id="79f18-502">Word を起動するときにクラッシュの原因となっている可能性のあった問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-502">Resolved an issue that may have caused a crash when booting Word.</span></span>


- <span data-ttu-id="79f18-503">基本スタイルが標準スタイルで更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-503">We fixed an issue which the base styles are not updated with Normal style.</span></span>


- <span data-ttu-id="79f18-504">ドキュメントを開くときに、ユーザーがクラッシュする可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-504">We fixed an issue which user might experience crash when opening a document.</span></span>


- <span data-ttu-id="79f18-505">図形のサイズを変更すると、ユーザーのコンテンツが失われる場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-505">We fixed an issue where the user might lose content when resize a shape.</span></span>


- <span data-ttu-id="79f18-506">サイズが非常に大きい特定のメールを開くとクラッシュが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-506">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="79f18-507">新しいメールに返信、または新しいメールを作成するときにユーザーにクラッシュが発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-507">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>


- <span data-ttu-id="79f18-508">この変更により、以前の共同編集セッションの後に Office アプリケーションがサイレント保存の状態に陥ることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-508">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>


### <a name="office-suite"></a><span data-ttu-id="79f18-509">Office スイート</span><span class="sxs-lookup"><span data-stu-id="79f18-509">Office Suite</span></span>

- <span data-ttu-id="79f18-510">この変更は、 d2d1.dll の読み込みに失敗したために、Office アプリを起動したときにクラッシュする場合があった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="79f18-510">This change addresses a crash when launching Office apps due to failing to load d2d1.dll.</span></span>


- <span data-ttu-id="79f18-511">GIF/アニメーション model3D を使用したアイドル時の高い CPU 使用率を修正します</span><span class="sxs-lookup"><span data-stu-id="79f18-511">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="79f18-512">Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-512">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="79f18-513">このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-513">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2007-october-13"></a><span data-ttu-id="79f18-515">バージョン 2007: 10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="79f18-515">Version 2007: October 13</span></span>
<span data-ttu-id="79f18-516">*バージョン 2007 (ビルド 13029.20708)*</span><span class="sxs-lookup"><span data-stu-id="79f18-516">*Version 2007 (Build 13029.20708)*</span></span>

<span data-ttu-id="79f18-517">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="79f18-517">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="79f18-519">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="79f18-519">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="79f18-520">Excel</span><span class="sxs-lookup"><span data-stu-id="79f18-520">Excel</span></span>

- <span data-ttu-id="79f18-521">' 前 ' と ' 後 ' のフィルター条件が逆転する バグをPivotDateFilter Api で修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-521">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>



[//]: # (BUG詳細 コンテンツを削除しないでください。終了)

## <a name="version-2007-september-08"></a><span data-ttu-id="79f18-523">バージョン 2007: 9 月 08 日</span><span class="sxs-lookup"><span data-stu-id="79f18-523">Version 2007: September 08</span></span>
<span data-ttu-id="79f18-524">*バージョン 2007 (ビルド 13029.20534)*</span><span class="sxs-lookup"><span data-stu-id="79f18-524">*Version 2007 (Build 13029.20534)*</span></span>

<span data-ttu-id="79f18-525">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="79f18-525">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="79f18-527">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="79f18-527">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="79f18-528">Outlook</span><span class="sxs-lookup"><span data-stu-id="79f18-528">Outlook</span></span>

- <span data-ttu-id="79f18-529">**IT 管理者向けのインシデント通知:** Microsoft 365 テナントのグローバル管理者および Office Apps 管理者は、Outlook for Windows の新しい右側のパネル通知により、ユーザーに影響する Outlook および O365 Exchange インシデントについて通知されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-529">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="79f18-530">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-530">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- <span data-ttu-id="79f18-531">**以前のセッションからアイテムを素早く再開する:** 以前の Outlook セッションからアイテムを素早く再開するためのオプションが追加されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-531">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="79f18-532">Outlook がクラッシュした場合でも、または終了した場合でも、アプリを再び開くと、すばやくアイテムを再起動することができます。</span><span class="sxs-lookup"><span data-stu-id="79f18-532">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="79f18-533">この機能は既定でオンになっています。</span><span class="sxs-lookup"><span data-stu-id="79f18-533">This feature is on by default.</span></span> <span data-ttu-id="79f18-534">オフにするには、[オプション] > [一般] > [開始オプション] に移動します。</span><span class="sxs-lookup"><span data-stu-id="79f18-534">To turn it off, go to Options > General > Start up Options.</span></span>

### <a name="word"></a><span data-ttu-id="79f18-535">Word</span><span class="sxs-lookup"><span data-stu-id="79f18-535">Word</span></span>

- <span data-ttu-id="79f18-536">**テキストをベクター内で保持:** 地図やグラフ、その他の SVG ベクターを Excel、Word、PowerPoint で変換する場合、それらのオブジェクトの中にテキストを保持できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="79f18-536">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>

### <a name="office-suite"></a><span data-ttu-id="79f18-537">Office スイート</span><span class="sxs-lookup"><span data-stu-id="79f18-537">Office Suite</span></span>

- <span data-ttu-id="79f18-538">**タブ付きのウィンドウ**: アプリの右側にあるタブ UI を使用して、複数のウィンドウ間を切り替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="79f18-538">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="79f18-539">UI は、2 つ以上のウィンドウが開かれている場合にのみ表示されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-539">The UI will only be visible when you have 2+ panes open.</span></span><br /><span data-ttu-id="79f18-540">[ブログの投稿](https://blog-insider.office.com/2020/02/20/improved-pane-management/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-540">See details in [blog post](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="79f18-543">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="79f18-543">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="79f18-544">Access</span><span class="sxs-lookup"><span data-stu-id="79f18-544">Access</span></span>

- <span data-ttu-id="79f18-545">この修正プログラムでは、特定のクエリを実行しようとすると、"クエリが複雑すぎます" というエラーメッセージが表示される問題に対処しています。</span><span class="sxs-lookup"><span data-stu-id="79f18-545">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>


### <a name="excel"></a><span data-ttu-id="79f18-546">Excel</span><span class="sxs-lookup"><span data-stu-id="79f18-546">Excel</span></span>

- <span data-ttu-id="79f18-547">改ページ プレビューで複数のシートを含むブックを読み込むときにエラーやハングが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-547">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>


- <span data-ttu-id="79f18-548">LET () 関数を使用して、数式を含むファイルを保存しようとすると、エラーが発生することがあります。</span><span class="sxs-lookup"><span data-stu-id="79f18-548">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>


### <a name="outlook"></a><span data-ttu-id="79f18-549">Outlook</span><span class="sxs-lookup"><span data-stu-id="79f18-549">Outlook</span></span>

- <span data-ttu-id="79f18-550">インシデント通知アラートのフォーマットの問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-550">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>


- <span data-ttu-id="79f18-551">Outlook ユーザーにコンパクト ビューでのナビゲーションの問題が表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-551">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>


- <span data-ttu-id="79f18-552">ユーザーがペルソナ情報を取得しようとしたときにクラッシュする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-552">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


- <span data-ttu-id="79f18-553">スケジュール アシスタント ページの表示が失敗する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-553">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="79f18-554">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカルコンピューターに保存できない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-554">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="79f18-555">[共有フォルダーのダウンロード] がチェックされていない場合、共有された予定表の会議の [返信オプション] に [転送を許可する] オプションが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-555">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="79f18-556">Outlook で検索候補を取得できない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-556">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="79f18-557">SharePoint ファイルに Smart Link を追加すると、一部の文字セットのユーザーにファイル名が正しく表示されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-557">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="79f18-558">保護されたコンテキストから保護されていないコンテキストに返信するとき、送信元アドレスを切り替えると、CLP のユーザーにクラッシュが発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-558">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>

- <span data-ttu-id="79f18-559">新しいメールに返信または作成するときにユーザーにクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-559">Addresses an issue that caused users to experience a crash when replying to or composing new mail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="79f18-560">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="79f18-560">PowerPoint</span></span>

- <span data-ttu-id="79f18-561">PowerPoint アプリでクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-561">We have fixed a crash issue with PowerPoint app.</span></span>


### <a name="project"></a><span data-ttu-id="79f18-562">Project</span><span class="sxs-lookup"><span data-stu-id="79f18-562">Project</span></span>

- <span data-ttu-id="79f18-563">Project から SharePoint ドキュメント ライブラリに PDF/XPS を保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-563">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="79f18-564">複数の依存関係があるタスクを貼り付けると、すべての依存関係が正しくコピーされるわけではない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-564">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="79f18-565">[リソースの割り当て] ダイアログ ボックスで選択されているタスクが、[タスク ボード] ビューで選択したタスクと異なる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-565">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="79f18-566">正常ではない状態になったプロジェクトを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-566">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



### <a name="office-suite"></a><span data-ttu-id="79f18-567">Office スイート</span><span class="sxs-lookup"><span data-stu-id="79f18-567">Office Suite</span></span>

- <span data-ttu-id="79f18-568">特定の状況下で UI 要素またはコンテンツが表示されない問題を修正しました。特に、発表者ツールのオン/オフ、または複数のモニターの使用に関して発生しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-568">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>


- <span data-ttu-id="79f18-569">製品版への移行が完了した場合でも、ランタイムメッセージが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-569">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="79f18-570">この問題の修正では、サービスが追加された製品を適切に計算するようにしました。</span><span class="sxs-lookup"><span data-stu-id="79f18-570">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="79f18-571">新たに追加された製品をフィルターで除外し (新しい構成に存在することも確認)、既存の製品リリース ID の最後に追加しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-571">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>


- <span data-ttu-id="79f18-572">以前の Web サービス ベースの [共有] ウィンドウで、[共有] ウィンドウが開いているときに文書を閉じるとクラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="79f18-572">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="79f18-573">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-573">This is now fixed.</span></span>



[//]: # (バグの詳細コンテンツ エンドを削除しないでください)

## <a name="version-2006-september-08"></a><span data-ttu-id="79f18-575">バージョン 2006: 9 月 08 日</span><span class="sxs-lookup"><span data-stu-id="79f18-575">Version 2006: September 08</span></span>
<span data-ttu-id="79f18-576">*バージョン 2006 (ビルド13001.20648)*</span><span class="sxs-lookup"><span data-stu-id="79f18-576">*Version 2006 (Build 13001.20648)*</span></span>

<span data-ttu-id="79f18-577">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="79f18-577">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2006-august-11"></a><span data-ttu-id="79f18-578">バージョン 2006: 8 月 11 日</span><span class="sxs-lookup"><span data-stu-id="79f18-578">Version 2006: August 11</span></span>
<span data-ttu-id="79f18-579">*バージョン 2006 (ビルド 13001.20520)*</span><span class="sxs-lookup"><span data-stu-id="79f18-579">*Version 2006 (Build 13001.20520)*</span></span>

<span data-ttu-id="79f18-580">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="79f18-580">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="79f18-582">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="79f18-582">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="79f18-583">Excel</span><span class="sxs-lookup"><span data-stu-id="79f18-583">Excel</span></span>

- <span data-ttu-id="79f18-584">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="79f18-584">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

- <span data-ttu-id="79f18-585">**他のユーザーを混乱させずに、フィルター処理して並べ替える:**、Sheet View で他のユーザーとの共同作業を行いながら Excel ファイルの並べ替えやフィルター処理ができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="79f18-585">**Filter and sort without disrupting others:** You can now sort and filter your Excel file while collaborating with others with Sheet View.</span></span> <span data-ttu-id="79f18-586">この新機能により、文書を共同編集しているときに、他のユーザーの並べ替えやフィルター処理による影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="79f18-586">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span> [<span data-ttu-id="79f18-587">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-587">Learn more</span></span>](https://support.office.com/article/0eea3dc5-d7d1-44c5-a953-25ebfbd6c1a6)

### <a name="outlook"></a><span data-ttu-id="79f18-588">Outlook</span><span class="sxs-lookup"><span data-stu-id="79f18-588">Outlook</span></span>

- <span data-ttu-id="79f18-589">**グループ内のデータを保護:** グループを作成するときに選択する秘密度ラベルがグループ メール、ドキュメント、チーム サイトに適用されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-589">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>

- <span data-ttu-id="79f18-590">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="79f18-590">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

- <span data-ttu-id="79f18-591">**Outlook でのメール作成時の @ メンションの候補表示を無効にするオプションが追加されました。**@ メンション ピッカーが便利どころか迷惑だと感じていますか?</span><span class="sxs-lookup"><span data-stu-id="79f18-591">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="79f18-592">今後は、必要に応じてオフにすることができます。</span><span class="sxs-lookup"><span data-stu-id="79f18-592">Now you can turn it off if you prefer.</span></span><br /><span data-ttu-id="79f18-593">[ブログの投稿](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-593">See details in [blog post](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)</span></span>

- <span data-ttu-id="79f18-594">**メールの一部として画像を送信するときに、画像を高品質に維持する:** メールの内容の一部として画像を送信するときに、画像の圧縮を制限するための新しい Outlook の設定を使用できます。</span><span class="sxs-lookup"><span data-stu-id="79f18-594">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="79f18-595">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="79f18-595">PowerPoint</span></span>

- <span data-ttu-id="79f18-596">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="79f18-596">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

- <span data-ttu-id="79f18-597">**PowerPoint でのストリーム ビデオのパフォーマンス向上:**、ビデオの読み込み時間を最小限に抑え、快適な表示を実現するために Microsoft Stream ビデオの再生パフォーマンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-597">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="79f18-598">お客様の社内ビデオを使用して、Microsoft Stream でより適切なプレゼンテーションを作成します。</span><span class="sxs-lookup"><span data-stu-id="79f18-598">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="word"></a><span data-ttu-id="79f18-599">Word</span><span class="sxs-lookup"><span data-stu-id="79f18-599">Word</span></span>

- <span data-ttu-id="79f18-600">**アニメーション Gif を使用してストーリーを伝える:** Office エディターでアニメーション Gif がサポートされるようになりました。これにより、さらに目を引くドキュメントを作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="79f18-600">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

- <span data-ttu-id="79f18-601">**別の言葉で伝える:** 別の言葉で伝えたいときに、[書き換え] でお助けします。</span><span class="sxs-lookup"><span data-stu-id="79f18-601">**Say it another way:** When you want to say it differently, Rewrite is there to help.</span></span> <span data-ttu-id="79f18-602">[書き換え] では、フレーズを洗練させるための別の言葉遣いを提供します。</span><span class="sxs-lookup"><span data-stu-id="79f18-602">Rewrite offers alternatives for finessing your phrases.</span></span><br /><span data-ttu-id="79f18-603">[ブログの投稿](https://blog-insider.office.com/2019/08/12/rewrite-in-word-say-it-another-way/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-603">See details in [blog post](https://blog-insider.office.com/2019/08/12/rewrite-in-word-say-it-another-way/)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="79f18-606">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="79f18-606">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="79f18-607">Access</span><span class="sxs-lookup"><span data-stu-id="79f18-607">Access</span></span>

- <span data-ttu-id="79f18-608">クエリの実行に予想よりも約 2 倍の時間がかかっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-608">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="79f18-609">ID (オートナンバーなど) フィールドが含まれるリンク付きの SQL 表を挿入する場合についての問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-609">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>


### <a name="excel"></a><span data-ttu-id="79f18-610">Excel</span><span class="sxs-lookup"><span data-stu-id="79f18-610">Excel</span></span>

- <span data-ttu-id="79f18-611">SharePoint/OneDrive に保存すると、ユーザー設定のリボンタブの CustomUI XML が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-611">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="79f18-612">改ページ プレビューで複数のシートを含むブックを読み込むときにエラーやハングが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-612">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="79f18-613">アカウントからサインアウトした場合にデータ接続を作成しようとすると発生する可能性があるクラッシュを修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-613">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

- <span data-ttu-id="79f18-614">読み取り専用モードのブックに対して、ドキュメント分類を自動的に行った可能性があります。</span><span class="sxs-lookup"><span data-stu-id="79f18-614">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

### <a name="onenote"></a><span data-ttu-id="79f18-615">OneNote</span><span class="sxs-lookup"><span data-stu-id="79f18-615">OneNote</span></span>

- <span data-ttu-id="79f18-616">リソースの使用率を低下させて、共同編集状態の検出機能を改善します。</span><span class="sxs-lookup"><span data-stu-id="79f18-616">Improve detection of co-authoring status to reduce resource utilization.</span></span>

### <a name="outlook"></a><span data-ttu-id="79f18-617">Outlook</span><span class="sxs-lookup"><span data-stu-id="79f18-617">Outlook</span></span>

- <span data-ttu-id="79f18-618">SVG 画像のコピーと貼り付けの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-618">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="79f18-619">Suggest a Feature で機能を検索しても結果が返されず、ユーザーが新しい機能のアイデアを提出するオプションがないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-619">Addresses an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>

- <span data-ttu-id="79f18-620">クラウド設定が有効になっているときに、Ctrl キーを押しながらクリックすると動作が停止する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="79f18-620">Addresses an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>

- <span data-ttu-id="79f18-621">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカル コンピューターに保存できない原因となっていた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="79f18-621">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="79f18-622">Outlook で、受信トレイ修復ツールを実行するように促す表示が継続的に発生していた問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="79f18-622">Addresses an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>

- <span data-ttu-id="79f18-623">共有された予定表の改良版のユーザーに予定表のエラーが表示される問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-623">Addresses an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>

- <span data-ttu-id="79f18-624">ドラッグ アンド ドロップによってファイル システムにコピーされた添付ファイルの作成日が、4501 年 1 月 1 日に設定される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="79f18-624">Addresses an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>

### <a name="project"></a><span data-ttu-id="79f18-625">Project</span><span class="sxs-lookup"><span data-stu-id="79f18-625">Project</span></span>

- <span data-ttu-id="79f18-626">プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-626">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="79f18-627">100% 完了とマークされているタスクが、100% 未満のタスクに間違って変更されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-627">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="79f18-628">URL が .com で終了している場合に、Project Web App からプロジェクト デスクトップ クライアントでプロジェクトを開くことができない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-628">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>

### <a name="word"></a><span data-ttu-id="79f18-629">Word</span><span class="sxs-lookup"><span data-stu-id="79f18-629">Word</span></span>

- <span data-ttu-id="79f18-630">SVG 画像のコピーと貼り付けの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-630">We fixed an issue for copy and paste SVG image.</span></span>

### <a name="office-suite"></a><span data-ttu-id="79f18-631">Office スイート</span><span class="sxs-lookup"><span data-stu-id="79f18-631">Office Suite</span></span>

- <span data-ttu-id="79f18-632">以前の AppV51 の回帰を修正するために、新しい AppV51 drop をバックポートします。</span><span class="sxs-lookup"><span data-stu-id="79f18-632">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="79f18-633">タイミングの問題で、Office ファイルを閉じるときにクラッシュすることがあります</span><span class="sxs-lookup"><span data-stu-id="79f18-633">A timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="79f18-634">レジストリ TabProcGrowth の値がREG_SZ型でアドインがアクティブ化されている場合に、Windows の Office ホストがクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-634">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-august-11"></a><span data-ttu-id="79f18-636">バージョン 2005: 8 月 11 日</span><span class="sxs-lookup"><span data-stu-id="79f18-636">Version 2005: August 11</span></span>
<span data-ttu-id="79f18-637">*バージョン 2005 (ビルド 12827.20656)*</span><span class="sxs-lookup"><span data-stu-id="79f18-637">*Version 2005 (Build 12827.20656)*</span></span>

<span data-ttu-id="79f18-638">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="79f18-638">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2005-july-14"></a><span data-ttu-id="79f18-639">バージョン 2005: 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="79f18-639">Version 2005: July 14</span></span>
<span data-ttu-id="79f18-640">*バージョン 2005 (ビルド 12827.20538)*</span><span class="sxs-lookup"><span data-stu-id="79f18-640">*Version 2005 (Build 12827.20538)*</span></span>

<span data-ttu-id="79f18-641">セキュリティ更新プログラムのリストは[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="79f18-641">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="79f18-643">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="79f18-643">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="79f18-644">Outlook</span><span class="sxs-lookup"><span data-stu-id="79f18-644">Outlook</span></span>

- <span data-ttu-id="79f18-645">**より迅速かつ適切な結果:** 検索機能が更新され、よりスマート、迅速、かつ信頼性が高くなりました。</span><span class="sxs-lookup"><span data-stu-id="79f18-645">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="79f18-646">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-646">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)




[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="79f18-649">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="79f18-649">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="79f18-650">Access</span><span class="sxs-lookup"><span data-stu-id="79f18-650">Access</span></span>

- <span data-ttu-id="79f18-651">アプリケーションのクラッシュを発生させずに、Date/Time Extended データ型をコードに呼び出すことができるように問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-651">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span>

- <span data-ttu-id="79f18-652">この問題は修正されて、最新の Access バージョンに戻し、 DAO/VBA を使用して 10 進数データ型を管理および編集することができます。</span><span class="sxs-lookup"><span data-stu-id="79f18-652">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>

### <a name="excel"></a><span data-ttu-id="79f18-653">Excel</span><span class="sxs-lookup"><span data-stu-id="79f18-653">Excel</span></span>

- <span data-ttu-id="79f18-654">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-654">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="79f18-655">同じブック内の場所へのハイパーリンクをクリックすると、ブックが非表示になることがあります。</span><span class="sxs-lookup"><span data-stu-id="79f18-655">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

- <span data-ttu-id="79f18-656">SharePoint/OneDrive に保存すると、ユーザー設定のリボンタブの CustomUI XML が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-656">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="79f18-657">ピボット テーブル をチャート シートに挿入しようとしたときに Excel がクラッシュする場合がある問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="79f18-657">Addresses an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="outlook"></a><span data-ttu-id="79f18-658">Outlook</span><span class="sxs-lookup"><span data-stu-id="79f18-658">Outlook</span></span>

- <span data-ttu-id="79f18-659">ユーザーが管理者通知からフィードバックを送信する場合にクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-659">Addresses an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

- <span data-ttu-id="79f18-660">Suggest a Feature で機能を検索しても結果が返されず、ユーザーが新しい機能のアイデアを提出するオプションがないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-660">Addresses an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>

- <span data-ttu-id="79f18-661">Outlook で、受信トレイ修復ツールを実行するように促す表示が継続的に発生していた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-661">Addresses an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>

- <span data-ttu-id="79f18-662">Windows 10 サーバー バージョンのユーザーに「アンチウイルスの状態が無効ですという警告が表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-662">Addresses an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="79f18-663">このバージョンの Windows はウイルス検出をサポートしていますが、ウイルス対策が正常にインストールされてもウイルス対策ソフトウェアが見つかりませんでした」。</span><span class="sxs-lookup"><span data-stu-id="79f18-663">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="79f18-664">一部のシナリオで、断続的なハングやクラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-664">Addresses an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>

- <span data-ttu-id="79f18-665">共有された Calendar - Outlook カレンダー の改良版のユーザーに予定表のエラーが表示される問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-665">Addresses an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>

- <span data-ttu-id="79f18-666">ユーザーが Outlook ルールを更新すると、"このコンピューターのルールは、Microsoft Exchange のルールと異なります" と表示される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="79f18-666">Addresses an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="79f18-667">ドラッグ アンド ドロップによってファイル システムにコピーされた添付ファイルの作成日が、4501 年 1 月 1 日に設定される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="79f18-667">Addresses an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>

- <span data-ttu-id="79f18-668">M365 Business Plus プランのサービスを利用していたユーザーがデータ損失防止の保護ポリシー ヒントを有効にできない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="79f18-668">Addresses an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="79f18-669">CLP の監査イベントで、返信/転送ラベルの問題に対応しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-669">Addresses an issue with the clp auditing event for the reply/forward label.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="79f18-670">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="79f18-670">PowerPoint</span></span>

- <span data-ttu-id="79f18-671">これにより、ユーザーがファイルに対してモダンおよびレガシのコメントを持っていて、コメントの更新をトリガーすると、クラッシュが修正されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-671">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

- <span data-ttu-id="79f18-672">提案ウィンドウでクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-672">We have fixed a crash issue with suggestion pane.</span></span>


### <a name="project"></a><span data-ttu-id="79f18-673">Project</span><span class="sxs-lookup"><span data-stu-id="79f18-673">Project</span></span>

- <span data-ttu-id="79f18-674">プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-674">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="79f18-675">100% 完了とマークされているタスクが、100% 未満のタスクに間違って変更されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-675">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

### <a name="skype"></a><span data-ttu-id="79f18-676">Skype</span><span class="sxs-lookup"><span data-stu-id="79f18-676">Skype</span></span>

- <span data-ttu-id="79f18-677">ユーザーが Teams Only に移動するポリシーを与えられた場合は、Skype for Business Outlook アドインを使用して会議をスケジュールできます。</span><span class="sxs-lookup"><span data-stu-id="79f18-677">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="79f18-678">この更新プログラムを適用すると、クライアントは Teams Only を対象としていることを示すポリシーをユーザーが読んでから会議参加のみのモードに入った後に、Skype for Business 会議のスケジュールを設定できなくなります。</span><span class="sxs-lookup"><span data-stu-id="79f18-678">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="79f18-679">また、skype for business Outlook アドインは、Skype for business クライアントが 「会議の参加のみ」 モードであることを確認した場合に起動した場合、自動的にアクティブ化されることはありません。</span><span class="sxs-lookup"><span data-stu-id="79f18-679">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

### <a name="word"></a><span data-ttu-id="79f18-680">Word</span><span class="sxs-lookup"><span data-stu-id="79f18-680">Word</span></span>

- <span data-ttu-id="79f18-681">一部のアプリケーションからコンテンツをドラッグしたときにクラッシュする問題の原因となっていた可能性がある問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-681">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>

### <a name="office-suite"></a><span data-ttu-id="79f18-682">Office スイート</span><span class="sxs-lookup"><span data-stu-id="79f18-682">Office Suite</span></span>

- <span data-ttu-id="79f18-683">この変更により、Gif や3D モデルなどのアニメーション コンテンツを読み込んだり、再生したりするときに、ハングする可能性があります。</span><span class="sxs-lookup"><span data-stu-id="79f18-683">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>

- <span data-ttu-id="79f18-684">Bing アドオンのインストール検証を既定で true に設定し、MSI のリターン成功をインストール成功とみなすことで、ValidateInstall のエラー率の問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-684">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>

- <span data-ttu-id="79f18-685">この更新プログラムでは、Microsoft Office で PATH 環境変数で指定した場所を検索することによって参照される可能性がある Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA ランタイムエラーが発生するという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-685">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="79f18-686">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-686">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="79f18-687">HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth のレジストリ キーが0に設定されている場合、アドインがアクティブになり、Windows で Office ホストがクラッシュしました。</span><span class="sxs-lookup"><span data-stu-id="79f18-687">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="79f18-688">この変更により、この問題は修正されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-688">This change would fix this issue.</span></span>


[//]: # (バグの詳細コンテンツを削除しないでください。終了)

## <a name="version-2004-july-14"></a><span data-ttu-id="79f18-690">バージョン 2004: 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="79f18-690">Version 2004: July 14</span></span>
<span data-ttu-id="79f18-691">*バージョン 2004 (ビルド 12730.20602)*</span><span class="sxs-lookup"><span data-stu-id="79f18-691">*Version 2004 (Build 12730.20602)*</span></span>

<span data-ttu-id="79f18-692">セキュリティ更新プログラムのリストは[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="79f18-692">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2004-june-09"></a><span data-ttu-id="79f18-693">バージョン 2004: 6月 09 日</span><span class="sxs-lookup"><span data-stu-id="79f18-693">Version 2004: June 09</span></span>
<span data-ttu-id="79f18-694">*バージョン 2004 (ビルド 12730.20430)*</span><span class="sxs-lookup"><span data-stu-id="79f18-694">*Version 2004 (Build 12730.20430)*</span></span>

<span data-ttu-id="79f18-695">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="79f18-695">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="79f18-697">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="79f18-697">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="79f18-698">アクセス</span><span class="sxs-lookup"><span data-stu-id="79f18-698">Access</span></span>

- <span data-ttu-id="79f18-699">**数回クリックするだけで表を追加する:** [テーブルの追加] 作業ウィンドウを使用すると、作業中も開いたまま、リレーションシップやクエリにテーブルを追加できます。</span><span class="sxs-lookup"><span data-stu-id="79f18-699">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="79f18-700">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-700">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="79f18-701">Excel</span><span class="sxs-lookup"><span data-stu-id="79f18-701">Excel</span></span>

- <span data-ttu-id="79f18-702">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="79f18-702">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="79f18-703">[ブログの投稿](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-703">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="79f18-704">**Facebook コネクタのサポート終了:** 2020 年 4 月以降、Excel では Facebook コネクタを使用する外部データ接続がサポートされなくなります。</span><span class="sxs-lookup"><span data-stu-id="79f18-704">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

- <span data-ttu-id="79f18-705">**ブックの見映えを良くする新しい画像:** 何千ものロイヤリティフリーの画像、アイコン、ステッカーが用意されており、これらをブックで使用できます。</span><span class="sxs-lookup"><span data-stu-id="79f18-705">**New images to bring your workbooks to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your workbooks.</span></span> <span data-ttu-id="79f18-706">開始するには、[挿入] > [画像] > [ストック画像] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="79f18-706">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="79f18-707">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-707">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br /><span data-ttu-id="79f18-708">[ブログの投稿](https://blog-insider.office.com/2020/04/06/premium-creative-content/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-708">See details in [blog post](https://blog-insider.office.com/2020/04/06/premium-creative-content/)</span></span>

### <a name="outlook"></a><span data-ttu-id="79f18-709">Outlook</span><span class="sxs-lookup"><span data-stu-id="79f18-709">Outlook</span></span>

- <span data-ttu-id="79f18-710">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="79f18-710">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="79f18-711">[ブログの投稿](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-711">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="79f18-712">**所有しているグループにメールをドラッグ:** メッセージや会話を受信トレイからドラッグして移動し、コピーします。</span><span class="sxs-lookup"><span data-stu-id="79f18-712">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="79f18-713">ドラッグしたメッセージは、すべてのグループ メンバーと共有されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-713">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="79f18-714">[ブログの投稿](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-714">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="79f18-715">**予定表が一新されます:** 予定表を簡単に読みやすくなるビジュアル アップデートをご覧ください。</span><span class="sxs-lookup"><span data-stu-id="79f18-715">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="79f18-716">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-716">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="79f18-717">[ブログの投稿](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-717">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="79f18-718">**メッセージの見映えを良くする新しい画像:** 何千ものロイヤリティフリーの画像、アイコン、ステッカーが用意されており、これらをメール メッセージで使用できます。</span><span class="sxs-lookup"><span data-stu-id="79f18-718">**New images to bring your messages to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your email messages.</span></span> <span data-ttu-id="79f18-719">開始するには、[挿入] > [画像] > [ストック画像] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="79f18-719">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="79f18-720">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-720">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br /><span data-ttu-id="79f18-721">[ブログの投稿](https://blog-insider.office.com/2020/04/06/premium-creative-content/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-721">See details in [blog post](https://blog-insider.office.com/2020/04/06/premium-creative-content/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="79f18-722">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="79f18-722">PowerPoint</span></span>

- <span data-ttu-id="79f18-723">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="79f18-723">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="79f18-724">[ブログの投稿](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-724">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="79f18-725">**プレゼンテーション中に変更を同期する:** プレゼンテーションがスライド ショー モードであっても、いつでも変更を同期できます。</span><span class="sxs-lookup"><span data-stu-id="79f18-725">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="79f18-726">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-726">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="79f18-727">[ブログの投稿](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-727">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="79f18-728">**スライドの見映えを良くする新しい画像:** 何千ものロイヤリティフリーの画像、アイコン、ステッカーが用意されており、これらをプレゼンテーションで使用できます。</span><span class="sxs-lookup"><span data-stu-id="79f18-728">**New images to bring your slides to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your presentations.</span></span> <span data-ttu-id="79f18-729">開始するには、[挿入] > [画像] > [ストック画像] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="79f18-729">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="79f18-730">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-730">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br /><span data-ttu-id="79f18-731">[ブログの投稿](https://blog-insider.office.com/2020/04/06/premium-creative-content/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-731">See details in [blog post](https://blog-insider.office.com/2020/04/06/premium-creative-content/)</span></span>

### <a name="word"></a><span data-ttu-id="79f18-732">Word</span><span class="sxs-lookup"><span data-stu-id="79f18-732">Word</span></span>

- <span data-ttu-id="79f18-733">**インクのなげなわ:** [描画] タブのなげなわツールを使用すると、インクで描かれたオブジェクトを選択できます。</span><span class="sxs-lookup"><span data-stu-id="79f18-733">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="79f18-734">個別のストロークまたは文字全体を選択できます。</span><span class="sxs-lookup"><span data-stu-id="79f18-734">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="79f18-735">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-735">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="79f18-736">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="79f18-736">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="79f18-737">[ブログの投稿](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-737">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="79f18-738">**ドキュメントの見映えを良くする新しい画像:** 何千ものロイヤリティフリーの画像、アイコン、ステッカーが用意されており、これらをドキュメントで使用できます。</span><span class="sxs-lookup"><span data-stu-id="79f18-738">**New images to bring your documents to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your documents.</span></span> <span data-ttu-id="79f18-739">開始するには、[挿入] > [画像] > [ストック画像] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="79f18-739">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="79f18-740">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-740">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br /><span data-ttu-id="79f18-741">[ブログの投稿](https://blog-insider.office.com/2020/04/06/premium-creative-content/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-741">See details in [blog post](https://blog-insider.office.com/2020/04/06/premium-creative-content/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="79f18-742">Office スイート</span><span class="sxs-lookup"><span data-stu-id="79f18-742">Office Suite</span></span>

- <span data-ttu-id="79f18-743">**秘密度ラベル:** カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="79f18-743">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="79f18-746">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="79f18-746">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="79f18-747">Excel</span><span class="sxs-lookup"><span data-stu-id="79f18-747">Excel</span></span>

- <span data-ttu-id="79f18-748">ファイル パスが長すぎる場合にファイルをもう一度開くと、外部リンクが機能しなくなった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-748">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="79f18-749">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="79f18-749">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="79f18-750">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="79f18-750">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="79f18-751">ピボットテーブルを含むシートをコピーした後、Excel がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-751">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

### <a name="outlook"></a><span data-ttu-id="79f18-752">Outlook</span><span class="sxs-lookup"><span data-stu-id="79f18-752">Outlook</span></span>

- <span data-ttu-id="79f18-753">ユーザーが管理者通知からフィードバックを送信する場合にクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-753">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

- <span data-ttu-id="79f18-754">Outlook の終了中に応答が停止する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-754">Addressed an issue that caused users to experience a hang while exiting Outlook.</span></span>

- <span data-ttu-id="79f18-755">ユーザーがトースト通知を表示するときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-755">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>

- <span data-ttu-id="79f18-756">Windows の更新後に、ローカルに保存された .msg または .oft ファイルを開くと Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-756">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="79f18-757">Windows の一部のビルドで Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-757">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="79f18-758">フォルダー ウィンドウの幅が予期せず変更される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-758">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

### <a name="project"></a><span data-ttu-id="79f18-759">Project</span><span class="sxs-lookup"><span data-stu-id="79f18-759">Project</span></span>

- <span data-ttu-id="79f18-760">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="79f18-760">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="79f18-761">Project Web App に接続されている Project を使用していて小数点の記号がカンマの場合に、依存関係のタイム ラグを生じさせようとすると TaskDependencies Add メソッドが失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-761">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

### <a name="office-suite"></a><span data-ttu-id="79f18-762">Office スイート</span><span class="sxs-lookup"><span data-stu-id="79f18-762">Office Suite</span></span>

- <span data-ttu-id="79f18-763">シンボリック リンクのハード リンクを試みる際に、更新の失敗を引き起こしていたクイック実行の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-763">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>

- <span data-ttu-id="79f18-764">HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth のレジストリ キーが0に設定されている場合、アドインがアクティブになり、Windows で Office ホストがクラッシュしました。</span><span class="sxs-lookup"><span data-stu-id="79f18-764">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="79f18-765">この変更により、この問題は修正されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-765">This change would fix this issue.</span></span>

- <span data-ttu-id="79f18-766">この修正プログラムで、アクセスの制限と、パスワードによるファイルの保護が同時に行えないというエラーが解決されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-766">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="79f18-767">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-767">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="79f18-768">この更新プログラムでは、Microsoft Office で PATH 環境変数で指定した場所を検索することによって参照される可能性がある Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA ランタイムエラーが発生するという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-768">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-june-09"></a><span data-ttu-id="79f18-770">バージョン 2003: 6月 9 日</span><span class="sxs-lookup"><span data-stu-id="79f18-770">Version 2003: June 09</span></span>
<span data-ttu-id="79f18-771">*バージョン 2003 (ビルド 12624.20708)*</span><span class="sxs-lookup"><span data-stu-id="79f18-771">*Version 2003 (Build 12624.20708)*</span></span>

<span data-ttu-id="79f18-772">セキュリティ更新プログラムのリストは[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="79f18-772">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="79f18-774">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="79f18-774">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="79f18-775">Office スイート</span><span class="sxs-lookup"><span data-stu-id="79f18-775">Office Suite</span></span>

- <span data-ttu-id="79f18-776">この更新プログラムでは、Microsoft Office で PATH 環境変数で指定した場所を検索することによって参照される可能性がある Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA ランタイムエラーが発生するという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-776">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-may-12"></a><span data-ttu-id="79f18-778">バージョン 2003: 5 月12 月</span><span class="sxs-lookup"><span data-stu-id="79f18-778">Version 2003: May 12</span></span>
<span data-ttu-id="79f18-779">*バージョン 2003 (ビルド 12624.20588)*</span><span class="sxs-lookup"><span data-stu-id="79f18-779">*Version 2003 (Build 12624.20588)*</span></span>

<span data-ttu-id="79f18-780">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="79f18-780">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="79f18-782">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="79f18-782">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="79f18-783">Access</span><span class="sxs-lookup"><span data-stu-id="79f18-783">Access</span></span>

- <span data-ttu-id="79f18-784">**クエリ デザイナー、SQL ビュー、およびリレーションシップ ウィンドウでの作業効率の向上:** テーブルを右クリックして、テーブルを開き、デザインし、サイズを変更し、非表示にします。</span><span class="sxs-lookup"><span data-stu-id="79f18-784">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="79f18-785">SQL ビューでテキストを検索および置換します。</span><span class="sxs-lookup"><span data-stu-id="79f18-785">Search and replace text in SQL View.</span></span> <span data-ttu-id="79f18-786">リレーションシップ ウィンドウ内の複数のテーブルを選択します。</span><span class="sxs-lookup"><span data-stu-id="79f18-786">Select multiple tables in the Relationships window.</span></span>

### <a name="excel"></a><span data-ttu-id="79f18-787">Excel</span><span class="sxs-lookup"><span data-stu-id="79f18-787">Excel</span></span>

- <span data-ttu-id="79f18-788">**複数の値を返す式を入力する:** 複数の値を返す式を素早く入力できるようになりました。隣接するセルに自動的に入力されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-788">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="79f18-789">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-789">Learn more</span></span>](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br /><span data-ttu-id="79f18-790">[ブログの投稿](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-790">See details in [blog post](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span></span>

- <span data-ttu-id="79f18-791">**ブラウザーへのバウンスは不要** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定します。</span><span class="sxs-lookup"><span data-stu-id="79f18-791">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="79f18-792">**6 つの強力な機能:** スプレッドシートを強化する 6 つの新しい関数が追加されました。FILTER、SORT、SORTBY、UNIQUE、SEQUENCE、RANDARRAY です。</span><span class="sxs-lookup"><span data-stu-id="79f18-792">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span> [<span data-ttu-id="79f18-793">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-793">Learn more</span></span>](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- <span data-ttu-id="79f18-794">**左を見て、右を見て... XLOOKUP をご利用いただけます!** XLOOKUP を使えば、表や範囲内で必要なものは何でも見つけられます。</span><span class="sxs-lookup"><span data-stu-id="79f18-794">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="79f18-795">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-795">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br /><span data-ttu-id="79f18-796">[ブログの投稿](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-796">See details in [blog post](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span></span>

- <span data-ttu-id="79f18-797">**すぐに読んで返信する** ブックを開かずに、メールからコメントおよびメンションに直接返信します。</span><span class="sxs-lookup"><span data-stu-id="79f18-797">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="79f18-798">Outlook</span><span class="sxs-lookup"><span data-stu-id="79f18-798">Outlook</span></span>

- <span data-ttu-id="79f18-799">**人物を検索するときにメールの候補を取得する:** [検索] ボックスに人の名前を入力すると、最も関連性の高いメール メッセージが検索候補に含まれます。</span><span class="sxs-lookup"><span data-stu-id="79f18-799">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="79f18-800">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-800">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

- <span data-ttu-id="79f18-801">**グループの名前付けポリシー**: グループの名前付けポリシーを使用すると、IT 管理者は組織内のユーザーが作成するグループの名前の標準化と管理を行えます。</span><span class="sxs-lookup"><span data-stu-id="79f18-801">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="79f18-802">管理者は、グループが作成される際に特定のプレフィックスとサフィックスをグループ名に追加することを要求できます。また、特定の単語の使用を禁止できます。</span><span class="sxs-lookup"><span data-stu-id="79f18-802">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="79f18-803">これにより、グループ名での不適切な単語の使用を最小限に抑えられる他、ディレクトリ内のグループ名の記載を IT 管理者が管理できます。</span><span class="sxs-lookup"><span data-stu-id="79f18-803">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="79f18-804">また、名前付けポリシーを使用することで、チーム サイトを展開する組織は、チーム サイトを部署ごとに分類できるようにもなります。</span><span class="sxs-lookup"><span data-stu-id="79f18-804">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

- <span data-ttu-id="79f18-805">**受信トレイを離れずに会議に参加する:** オンライン会議に参加するために、予定表に切り替える必要はありません。</span><span class="sxs-lookup"><span data-stu-id="79f18-805">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="79f18-806">[To Do] ウィンドウに固定された予定表を使用して、ワンクリックで任意の会議に参加します。</span><span class="sxs-lookup"><span data-stu-id="79f18-806">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="79f18-807">**キャプティブ WiFi ネットワークの新しいエクスペリエンス**: サインインに Web ページを必要とする WiFi ネットワークに参加したことはありませんか ?</span><span class="sxs-lookup"><span data-stu-id="79f18-807">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="79f18-808">Outlook はこれを検出し、接続を支援します。</span><span class="sxs-lookup"><span data-stu-id="79f18-808">Outlook now detects this and helps you get connected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="79f18-809">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="79f18-809">PowerPoint</span></span>

- <span data-ttu-id="79f18-810">**PowerPoint におけるリアルタイム コラボレーションが高速に:** PowerPoint でリアルタイム コラボレーションを高速で行えます。</span><span class="sxs-lookup"><span data-stu-id="79f18-810">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="79f18-811">**オンライン ビデオの新しい保存場所:** Microsoft Stream にビデオを保存すれば、組織内のすべてのユーザーが視聴できます。</span><span class="sxs-lookup"><span data-stu-id="79f18-811">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="79f18-812">ビデオのリンクを挿入すれば、小さなファイル サイズでマルチメディア プレゼンテーションをご利用いただけます。</span><span class="sxs-lookup"><span data-stu-id="79f18-812">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="79f18-813">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-813">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="79f18-814">**ブラウザーへのバウンスは不要:** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定することができます。</span><span class="sxs-lookup"><span data-stu-id="79f18-814">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="79f18-815">**簡単な GIF:** 1 つのスライド、1 つのフレーム。</span><span class="sxs-lookup"><span data-stu-id="79f18-815">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="79f18-816">PowerPoint でループ GIF を簡単に作成できます。</span><span class="sxs-lookup"><span data-stu-id="79f18-816">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="79f18-817">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-817">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="79f18-818">[ブログの投稿](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-818">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="79f18-819">**図の向上: コネクタが改善されており、インクの滑らかな変換のプロセスが** によって、アイデアをより自信のあるインクにすることができます。</span><span class="sxs-lookup"><span data-stu-id="79f18-819">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="79f18-820">詳細情報</span><span class="sxs-lookup"><span data-stu-id="79f18-820">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="79f18-821">**スライド ショーの実行中にスライドを更新する:** プレゼンテーション中に他の作成者が変更したスライドを更新します。</span><span class="sxs-lookup"><span data-stu-id="79f18-821">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span><br /><span data-ttu-id="79f18-822">[ブログの投稿](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="79f18-822">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

### <a name="word"></a><span data-ttu-id="79f18-823">Word</span><span class="sxs-lookup"><span data-stu-id="79f18-823">Word</span></span>

- <span data-ttu-id="79f18-824">**ブラウザーへのバウンスは不要:** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定することができます。</span><span class="sxs-lookup"><span data-stu-id="79f18-824">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="79f18-825">**他のユーザーがすばやく変更を確認する:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="79f18-825">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="79f18-826">Office スイート</span><span class="sxs-lookup"><span data-stu-id="79f18-826">Office Suite</span></span>

- <span data-ttu-id="79f18-827">**大規模なファイルをインクリメンタルに開く:** プレゼンテーションの一部 (たとえば、大規模なビデオや画像) のダウンロードが終了していなくても、大規模な Powerpoint プレゼンテーションを開いたり操作したり、ダウンロードしたりする機能。</span><span class="sxs-lookup"><span data-stu-id="79f18-827">**Open Large Files Incrementally:** The ability to download, open and interact with large powerpoint presentations, even if parts of the presentation (for example a large video or image) have not finished downloading yet.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="79f18-830">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="79f18-830">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="79f18-831">Excel</span><span class="sxs-lookup"><span data-stu-id="79f18-831">Excel</span></span>

- <span data-ttu-id="79f18-832">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="79f18-832">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="79f18-833">ソース ブックが閉じている場合、外部リンクが塗りつぶし時に更新されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-833">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>


### <a name="onenote"></a><span data-ttu-id="79f18-834">OneNote</span><span class="sxs-lookup"><span data-stu-id="79f18-834">OneNote</span></span>

- <span data-ttu-id="79f18-835">ページのバージョン履歴を作成する頻度を一時的に変更することで、同期およびサービスの安定性が改善されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-835">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>


- <span data-ttu-id="79f18-836">ごみ箱へのページの移動を一時的に無効にすることにより、同期およびサーバーの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-836">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="79f18-837">代わりに、ページを削除するユーザーにはページを完全に削除するか確認するダイアログが表示されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-837">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>


- <span data-ttu-id="79f18-838">OneNote 2016 に 50 MB へ埋め込まれた新しい添付ファイルの最大許容サイズが一時的に減少することにより、同期とサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-838">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="79f18-839">この制限を超えるファイルの場合、ユーザーは OneDrive にファイルをアップロードして、OneNote にリンクを挿入することができます。</span><span class="sxs-lookup"><span data-stu-id="79f18-839">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>


- <span data-ttu-id="79f18-840">OneNote 2016 でアプリ内動画のレコーディングを一時的に無効にすることで、同期およびサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-840">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="79f18-841">ローカルのノートブックはこの影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="79f18-841">Local notebooks are not impacted by this measure.</span></span>


- <span data-ttu-id="79f18-842">OneNote 2016 で同期頻度を一時的に調整することで、同期およびサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-842">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>


- <span data-ttu-id="79f18-843">全世界でサービス使用量が高まった際に、同期とサービスの可用性を改善できる、Microsoft OneNote の一時的な調整に関して、情報バーを介してユーザーに通知します。</span><span class="sxs-lookup"><span data-stu-id="79f18-843">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>


### <a name="outlook"></a><span data-ttu-id="79f18-844">Outlook</span><span class="sxs-lookup"><span data-stu-id="79f18-844">Outlook</span></span>

- <span data-ttu-id="79f18-845">終了後にタスク マネージャーに Outlook プロセスが残っているという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-845">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>


- <span data-ttu-id="79f18-846">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていたユーザーの問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-846">Addressed an issue that caused users to occasionally experience a crash when using the button on their mouse.</span></span>


- <span data-ttu-id="79f18-847">サードパーティ製の MAPI アプリケーションでクラッシュが発生した問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-847">Addressed an issue that caused users to experience crashes in third party MAPI applications.</span></span>


- <span data-ttu-id="79f18-848">Windows の更新後に、ローカルに保存された .msg または .oft ファイルを開くと Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-848">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>


- <span data-ttu-id="79f18-849">Windows の一部のビルドで Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-849">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>


- <span data-ttu-id="79f18-850">フォルダー ウィンドウの幅が予期せず変更される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-850">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>


### <a name="project"></a><span data-ttu-id="79f18-851">Project</span><span class="sxs-lookup"><span data-stu-id="79f18-851">Project</span></span>

- <span data-ttu-id="79f18-852">タスクを完了とマークした後に、タスクの達成率が 100% 完了より小さい値に誤って変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-852">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>


- <span data-ttu-id="79f18-853">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-853">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>


- <span data-ttu-id="79f18-854">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-854">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


- <span data-ttu-id="79f18-855">[無効化] ボタンを介してタスクが非アクティブ化/アクティブ化された場合に、ProjectBeforeTaskChange イベントが検出しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-855">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>


- <span data-ttu-id="79f18-856">[無効化] ボタンを介してタスクが非アクティブ化/アクティブ化された場合に、ProjectBeforeTaskChange イベントが検出しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-856">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>


- <span data-ttu-id="79f18-857">以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="79f18-857">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>


- <span data-ttu-id="79f18-858">実績作業時間の保護設定を有効にしている場合に、ユーザーがタイムフェーズの基準作業時間を入力できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-858">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>


- <span data-ttu-id="79f18-859">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="79f18-859">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>


### <a name="word"></a><span data-ttu-id="79f18-860">Word</span><span class="sxs-lookup"><span data-stu-id="79f18-860">Word</span></span>

- <span data-ttu-id="79f18-861">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていたユーザーの問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="79f18-861">Addresses an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="office-suite"></a><span data-ttu-id="79f18-862">Office スイート</span><span class="sxs-lookup"><span data-stu-id="79f18-862">Office Suite</span></span>

- <span data-ttu-id="79f18-863">この修正プログラムで、アクセスの制限と、パスワードによるファイルの保護が同時に行えないというエラーが解決されました。</span><span class="sxs-lookup"><span data-stu-id="79f18-863">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="79f18-864">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="79f18-864">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

[//]: # (削除しないでください。 終了)

> [!NOTE]
> <span data-ttu-id="79f18-868">Office の使用で問題がある場合は、[Microsoft の回答フォーラム](https://answers.microsoft.com/)に関するページまたは「[Microsoft Tech Community](https://techcommunity.microsoft.com/)」に質問を投稿するか、[サポート](https://support.microsoft.com/contactus)に問い合わせてサポートを受けることができます。</span><span class="sxs-lookup"><span data-stu-id="79f18-868">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (管理センターのメタデータのコンテンツを変更しないでください。開始)
[//]: # (|Win32|MEC|Production|Feature|16.0.13628.20528|version-2101-march-09|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13530.20528|version-2012-february-09|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13426.20526|version-2011-january-12|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13328.20478|version-2010-december-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13231.20514|version-2009-november-10|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13127.20638|version-2008-october-13|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13029.20534|version-2007-september-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13001.20520|version-2006-august-11|)
[//]: # (|Win32|MEC|生産|機能|16.0.12827.20538|バージョン-2005-7 月-14|)
[//]: # (管理センターのメタデータのコンテンツ エンドを変更しないでください)
