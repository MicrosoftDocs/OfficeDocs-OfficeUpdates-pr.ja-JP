---
title: Office Insider のリリース ノート
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Insider Fast の対象ユーザーに主な新機能、修正プログラム、既知の問題の最新リストを提供します
ms.openlocfilehash: b136c43128f6f995057f35c7b47c9e517c457097
ms.sourcegitcommit: 78fb0c27e6b75aefcfcbd1b0ac7d17c1b53f86e0
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/07/2020
ms.locfileid: "40951095"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="f2011-103">Office Insider のリリース ノート</span><span class="sxs-lookup"><span data-stu-id="f2011-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="f2011-104">この記事には、Windows デスクトップ向け Word、Excel、PowerPoint、Outlook、Access、Project の Insider ビルドのリリース ノートが含まれています。</span><span class="sxs-lookup"><span data-stu-id="f2011-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="f2011-105">Microsoft では、毎週、皆様にお知らせしたい魅力的な新機能、重要な修正プログラム、重大な問題に関する情報を提供しています。</span><span class="sxs-lookup"><span data-stu-id="f2011-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="f2011-106">多くの場合、機能 (場合によっては修正プログラムも) は、特定の期間にわたって Insider にロールアウトされます。</span><span class="sxs-lookup"><span data-stu-id="f2011-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="f2011-107">これにより、Microsoft では、より広範な対象ユーザーに機能をリリースする前に、作業がスムーズに行われていることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="f2011-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="f2011-108">したがって、下記のものが表示されない場合でも、心配する必要はなく、いずれは表示されます。</span><span class="sxs-lookup"><span data-stu-id="f2011-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="f2011-109">リリース ノートは毎週投稿され、場合により複数のビルドのコンパイルになります。</span><span class="sxs-lookup"><span data-stu-id="f2011-109">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="f2011-110">リリースノートの発行日は実際のビルドのリリース日と一致しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-110">The release notes publication date may not match the actual build release date.</span></span>
> - <span data-ttu-id="f2011-111">Microsoft Teams に関連する既存の Office 365 ProPlus のインストール - 6 月の下旬から、これらの更新プログラムのインストール時に、Microsoft Teams が既存の Office 365 ProPlus (Office 365 Business) のインストールの中に含められます。</span><span class="sxs-lookup"><span data-stu-id="f2011-111">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="f2011-112">Teams が追加される日にちは、使用している更新プログラム チャネルによって異なります。</span><span class="sxs-lookup"><span data-stu-id="f2011-112">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="f2011-113">追加情報については、「[Office 365 ProPlus と同時に Microsoft Teams を展開する](https://docs.microsoft.com/deployoffice/teams-install)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f2011-113">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install) for additional information.</span></span>

[//]: # (削除しないでください)

## <a name="version-2001-january-03"></a><span data-ttu-id="f2011-115">バージョン 2001: 1 月 3 日</span><span class="sxs-lookup"><span data-stu-id="f2011-115">Version 2001: January 03</span></span>
<span data-ttu-id="f2011-116">*バージョン 2001 (ビルド 12425.20000)*</span><span class="sxs-lookup"><span data-stu-id="f2011-116">*Version 2001 (Build 12425.20000)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="f2011-118">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="f2011-118">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-119">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-119">Excel</span></span>
- <span data-ttu-id="f2011-120">一部の罫線は A4 サイズ用紙に印刷されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="f2011-120">Some border lines may not print as expected on A4 size paper.</span></span>
- <span data-ttu-id="f2011-121">VBA を使用してシート上のグラフオブジェクトのヘッダーまたはフッターに画像を追加すると、エラーが発生することがあります。</span><span class="sxs-lookup"><span data-stu-id="f2011-121">Adding an image to the header/footer of a chart object on a sheet using VBA may result in an error.</span></span>
- <span data-ttu-id="f2011-122">グラフの軸を書式設定するときにラベルの間隔が 255 に制限されます。</span><span class="sxs-lookup"><span data-stu-id="f2011-122">When formatting a chart axis, the interval between labels was limited to 255.</span></span>
- <span data-ttu-id="f2011-123">データ ソースの URL が切り詰められている XML クエリを更新しようとするとエラーが発生するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-123">Fixed an issue where an error would occur trying to refresh an XML query in which the URL to the datasource was being truncated.</span></span>
- <span data-ttu-id="f2011-124">ブックの統計情報では、個人のマクロ ブックを含め、開いているすべてのブックからマクロの回数が報告されます。</span><span class="sxs-lookup"><span data-stu-id="f2011-124">Workbook Statistics would report a macro count from all open workbooks, including the personal macro workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-125">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-125">Outlook</span></span>
- <span data-ttu-id="f2011-126">フォルダーを切り替えると、メール リスト/メール プレビューに、しばらく白い「フラッシュ」が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-126">Switching folders may result in a brief white 'flash' in the mail list / mail preview.</span></span> <span data-ttu-id="f2011-127">この現象は、ダーク モードでより顕著になりました。</span><span class="sxs-lookup"><span data-stu-id="f2011-127">This behavior was more pronounced in dark mode.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-128">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-128">PowerPoint</span></span>
- <span data-ttu-id="f2011-129">Shape.Paste メソッドを呼び出すと貼り付けられた図形がフォーカスされるオブジェクトモデルの問題を修正しました。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="f2011-129">Fixed an Object Model issue where calling Shape.Paste method would result in the pasted shape receiving focus.&nbsp;</span></span>
- <span data-ttu-id="f2011-130">コピーと貼り付けシナリオの改善: &nbsp;PowerPoint スライドからプログラムによってコピーして、ループ内の別のスライドに貼り付けると、例外エラーが発生する場合があります。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="f2011-130">Improved a copy-paste scenario:&nbsp;Progamatically copying a shape from a PowerPoint slide and pasting it to another slide in a loop could fail with an exception error.&nbsp;</span></span>
- <span data-ttu-id="f2011-131">スライドのセクション ヘッダー内のアニメーションは、セクション ヘッダーを折りたたんで展開した後は、正しくレンダリングされません。</span><span class="sxs-lookup"><span data-stu-id="f2011-131">Animation in the section headers of slides would not render properly after collapsing and expanding section headers.</span></span>

### <a name="project"></a><span data-ttu-id="f2011-132">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-132">Project</span></span>
- <span data-ttu-id="f2011-133">文字列の折り返しが [タスク] ビュー と [リソース配分状況] ビューで機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-133">Fixed an issue where text wrapping wasn't working in the task and resource usage views.</span></span>
- <span data-ttu-id="f2011-134">リソースに複数の原価率がある場合、割り当ての原価価値が正しくない可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-134">Fixed an issue where if a resource has more than one cost rate, cost value on assignments may not be correct.</span></span>

### <a name="word"></a><span data-ttu-id="f2011-135">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-135">Word</span></span>
- <span data-ttu-id="f2011-136">コントロール (テキスト コンテンツ コントロールなど) を数式に挿入し、ファイルを保存して開くと、読み取り不可能なコンテンツ エラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="f2011-136">Inserting a control (such as a Text Content Control) in an equation, then saving and opening the file would result in an un-readable content error.</span></span>
- <span data-ttu-id="f2011-137">共同編集時に、Word Online を使用して追加したコメントが Word デスクトップに表示されません。</span><span class="sxs-lookup"><span data-stu-id="f2011-137">When co-authoring, adding a comment using Word online may not appear in Word desktop.</span></span>

### <a name="office-suite"></a><span data-ttu-id="f2011-138">Office スイート</span><span class="sxs-lookup"><span data-stu-id="f2011-138">Office Suite</span></span>
- <span data-ttu-id="f2011-139">ライセンスを 1 つだけ使用してライセンスを変更しようとしたときに、有効なライセンスの有効期限が誤って表示されなくなりました。</span><span class="sxs-lookup"><span data-stu-id="f2011-139">Removed showing an erroneous expiry date of the valid license when trying to change license with only one license.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2001-december-13"></a><span data-ttu-id="f2011-141">バージョン 2001: 12 月 13 日</span><span class="sxs-lookup"><span data-stu-id="f2011-141">Version 2001: December 13</span></span>
<span data-ttu-id="f2011-142">*バージョン 2001 (ビルド 12410.20000)*</span><span class="sxs-lookup"><span data-stu-id="f2011-142">*Version 2001 (Build 12410.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="f2011-144">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="f2011-144">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="f2011-145">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-145">Outlook</span></span>

- <span data-ttu-id="f2011-146">**所有しているグループにメールをドラッグ:** メッセージや会話を受信トレイからドラッグして移動し、コピーします。</span><span class="sxs-lookup"><span data-stu-id="f2011-146">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="f2011-147">ドラッグしたメッセージは、すべてのグループ メンバーと共有されます。</span><span class="sxs-lookup"><span data-stu-id="f2011-147">Messages you drag will be shared with all group members.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="f2011-150">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="f2011-150">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="f2011-151">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-151">Access</span></span>
- <span data-ttu-id="f2011-152">リンクされた ODBC テーブルを参照し、Order By 句を含めるユニオン クエリを実行すると、64ビット版アクセスがクラッシュします。</span><span class="sxs-lookup"><span data-stu-id="f2011-152">Executing a union query that references linked ODBC table(s) and contains an Order By clause crashes 64 bit Access.</span></span>
- <span data-ttu-id="f2011-153">Access (O365) のユニオン クエリからデータを集計すると、10 進型データを切り捨ててしまうことがあります。</span><span class="sxs-lookup"><span data-stu-id="f2011-153">Summing of data from union queries in Access (O365) may result in truncation of decimal data.</span></span>
- <span data-ttu-id="f2011-154">ACE の COM インターフェイスは、Office アプリケーションの外部で使用することはできません。</span><span class="sxs-lookup"><span data-stu-id="f2011-154">COM Interfaces for ACE are not exposed for use outside of Office applications.</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-155">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-155">Excel</span></span>
- <span data-ttu-id="f2011-156">3D モデル (アニメーションまたはスタティック) を挿入し、[図として保存] を行おうとしても動作しません。</span><span class="sxs-lookup"><span data-stu-id="f2011-156">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>
- <span data-ttu-id="f2011-157">Backstage からフィードバックを開始するためのショートカットキー (Alt + Ctrl + 7/8) は、AZERTY キーボード (Alt - Gr + 7/8) と競合しています。</span><span class="sxs-lookup"><span data-stu-id="f2011-157">The shortkey (Alt+Ctrl + 7/8)  to launch feedback from backstage is in conflict with AZERTY keyboards (Alt-Gr + 7/8).</span></span> <span data-ttu-id="f2011-158">影響: ユーザーは次のような文字を使用できない場合があります'\'。</span><span class="sxs-lookup"><span data-stu-id="f2011-158">Impact: users may not be able to use some characters such as: '\'.</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-159">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-159">Outlook</span></span>
- <span data-ttu-id="f2011-160">メールが受信者の間違ったアドレスに送信される原因となる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="f2011-160">Addresses an issue that caused email to be sent to the wrong address for the recipient.</span></span>
- <span data-ttu-id="f2011-161">Outlook でメールボックスへの &quot;読み取り&quot; アクセス権のあるユーザーに対して、メッセージの [既読/未読] 状態の変更を誤って許可する原因となる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="f2011-161">Addresses an issue that caused Outlook to incorrectly allow users with &quot;read&quot; access to a mailbox to change the read/unread state of a message.</span></span>
- <span data-ttu-id="f2011-162">Web サイト上のセキュリティ証明書を失効すると、製品サポートによって再度作成することはできません。</span><span class="sxs-lookup"><span data-stu-id="f2011-162">The revocation of the security certificate on the web site is not re-producible by Product Support.</span></span> <span data-ttu-id="f2011-163">この問題の根本原因を解決するには、ログを追加する必要があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-163">Logging needs to be added to help root cause the issue.</span></span>
- <span data-ttu-id="f2011-164">同期エラーが表示されてしまう問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="f2011-164">Addresses an issue that caused users to see synchronization failures.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-165">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-165">PowerPoint</span></span>
- <span data-ttu-id="f2011-166">3D モデル (アニメーションまたはスタティック) を挿入し、[図として保存] を行おうとしても動作しません。</span><span class="sxs-lookup"><span data-stu-id="f2011-166">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="project"></a><span data-ttu-id="f2011-167">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-167">Project</span></span>
- <span data-ttu-id="f2011-168">タスクの作業は、手動スケジュール タスクの Summary roll-up では計算されません。</span><span class="sxs-lookup"><span data-stu-id="f2011-168">Task work is not calculated in Summary roll-up for manually scheduled child tasks.</span></span>
- <span data-ttu-id="f2011-169">サーバーベースのプロジェクトを保存しようとすると、リボン ボタンから呼び出された Project VBA コードが機能しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-169">Project VBA Code invoked from a Ribbon button may not work when trying to save server-based Projects.</span></span>
- <span data-ttu-id="f2011-170">プロジェクトを実行していない場合は、SharePoint ドキュメント ライブラリからプロジェクト ファイルを開くとエラーが表示され、ファイルが開くことはできません。</span><span class="sxs-lookup"><span data-stu-id="f2011-170">Unless Project is already running, opening Project files from a SharePoint document library displays an error and the file will not open.</span></span>

### <a name="word"></a><span data-ttu-id="f2011-171">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-171">Word</span></span>
- <span data-ttu-id="f2011-172">既存のファイルの保存が出来ない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-172">Saving existing files may not work.</span></span>
- <span data-ttu-id="f2011-173">[スペルチェックと文章校正] ウィンドウで方向キーを使用すると、断続的に画面がちらつくことがあります。</span><span class="sxs-lookup"><span data-stu-id="f2011-173">Using arrow keys in the Spelling and Grammar editor window may result in intermittent flickering.</span></span>
- <span data-ttu-id="f2011-174">フォローアップを解決するときに、関連するコメントはポイントのコメントに変換されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="f2011-174">When resolving a follow-up, associated comments may not convert to point comments.</span></span>
- <span data-ttu-id="f2011-175">3D モデル (アニメーションまたはスタティック) を挿入し、[図として保存] を行おうとしても動作しません。</span><span class="sxs-lookup"><span data-stu-id="f2011-175">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="f2011-176">Office スイート</span><span class="sxs-lookup"><span data-stu-id="f2011-176">Office Suite</span></span>
- <span data-ttu-id="f2011-177">Office の更新メッセージが、異なる言語で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-177">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="f2011-178">今後、Office の更新メッセージは Windows の表示言語と一致します。</span><span class="sxs-lookup"><span data-stu-id="f2011-178">Going forward, Office update messages will correctly match the Windows display language.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1912-december-06"></a><span data-ttu-id="f2011-180">バージョン 1912: 12 月 6 日</span><span class="sxs-lookup"><span data-stu-id="f2011-180">Version 1912: December 06</span></span>
<span data-ttu-id="f2011-181">*バージョン 1912 (ビルド 12325.20012)*</span><span class="sxs-lookup"><span data-stu-id="f2011-181">*Version 1912 (Build 12325.20012)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="f2011-183">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="f2011-183">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="f2011-184">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-184">Outlook</span></span>

- <span data-ttu-id="f2011-185">**高度なグループ メールの設定:** この機能は、グループ ユーザーが受信トレイで受信/フォローするメールまたはイベントを、カスタマイズするのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="f2011-185">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="f2011-186">**グループの名前付けポリシー**: グループの名前付けポリシーを使用すると、IT 管理者は組織内のユーザーが作成するグループの名前の標準化と管理を行えます。</span><span class="sxs-lookup"><span data-stu-id="f2011-186">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="f2011-187">管理者は、グループが作成される際に特定のプレフィックスとサフィックスをグループ名に追加することを要求できます。また、特定の単語の使用を禁止できます。</span><span class="sxs-lookup"><span data-stu-id="f2011-187">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="f2011-188">これにより、グループ名での不適切な単語の使用を最小限に抑えられる他、ディレクトリ内のグループ名の記載を IT 管理者が管理できます。</span><span class="sxs-lookup"><span data-stu-id="f2011-188">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="f2011-189">また、名前付けポリシーを使用することで、チーム サイトを展開する組織は、チーム サイトを部署ごとに分類できるようにもなります。</span><span class="sxs-lookup"><span data-stu-id="f2011-189">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="office-suite"></a><span data-ttu-id="f2011-190">Office スイート</span><span class="sxs-lookup"><span data-stu-id="f2011-190">Office Suite</span></span>

- <span data-ttu-id="f2011-191">**タブ付きのウィンドウ**: アプリの右側にあるタブ UI を使用して、複数のウィンドウ間を切り替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="f2011-191">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="f2011-192">UI は、2 つ以上のウィンドウが開かれている場合にのみ表示されます。</span><span class="sxs-lookup"><span data-stu-id="f2011-192">The UI will only be visible when you have 2+ panes open.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="f2011-195">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="f2011-195">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="f2011-196">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-196">Excel</span></span>
- <span data-ttu-id="f2011-197">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-197">Users may encounter an error when saving changes while using some non-English character sets.</span></span>
- <span data-ttu-id="f2011-198">非表示の名前付き範囲にアクセスすると、ユーザーにエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-198">Users may encounter an error when accessing a hidden named range.</span></span>
- <span data-ttu-id="f2011-199">4K 解像度のハードウェアのグラフィック アクセラレータを無効にすると、スクロールしたときにセルのレンダリングが遅れる場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-199">Disabling hardware graphics acceleration with 4K resolution may result in delayed rendering of cells when scrolling around.</span></span>
- <span data-ttu-id="f2011-200">セルの境界に重なる長い数式をクリアしても、セルの境界を越えて表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-200">Clearing a long formula that overlaps a cell boundary may still display across the cell boundary.</span></span>
- <span data-ttu-id="f2011-201">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-201">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>
- <span data-ttu-id="f2011-202">余白のドロップダウン メニューが正しくレンダリングされない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-202">Margin dropdown menu may not render correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="f2011-203">OneNote</span><span class="sxs-lookup"><span data-stu-id="f2011-203">OneNote</span></span>
- <span data-ttu-id="f2011-204">OneNote は、「会議ノート」の Outlook アドインを介して開かない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-204">OneNote may not open via the 'Meeting Notes' Outlook add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-205">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-205">Outlook</span></span>
- <span data-ttu-id="f2011-206">保持ポリシーのラベルには、保持期間がかっこ内に表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-206">Retention policy labels may display the retention time period in parenthesis.</span></span>
- <span data-ttu-id="f2011-207">日本語パックの連絡先カードに空白が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-207">Blank spaces may appear in Contact cards with Japanese language pack.</span></span>
- <span data-ttu-id="f2011-208">Outlook のメール メッセージにインラインで挿入された画像のサイズが変更される場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-208">Images inserted inline to Outlook e-mail messages can sometimes get resized.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-209">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-209">PowerPoint</span></span>
- <span data-ttu-id="f2011-210">クラウド ファイル内のスライドに 2 つ以上の異なるビデオがある場合、ビデオの画像は正しく表示されますが、ユーザーがそれぞれのビデオを再生するためにクリックすると、同一の内容のビデオが再生されます。</span><span class="sxs-lookup"><span data-stu-id="f2011-210">If a user has two (or more) different videos on a slide in a cloud file, the video images are rendered correctly, but when the user clicks on each one to play, the video content is the same.</span></span>
- <span data-ttu-id="f2011-211">場合によっては、タッチ デバイスでのスクロールが機能しないことがあります。</span><span class="sxs-lookup"><span data-stu-id="f2011-211">In some cases, scrolling with touch devices will not work.</span></span>
- <span data-ttu-id="f2011-212">余白のドロップダウン メニューが正しくレンダリングされない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-212">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="f2011-213">ある Office アプリケーションから別の Office アプリケーションへの安全なリンクは、リンクされたアプリケーションを起動しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-213">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="project"></a><span data-ttu-id="f2011-214">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-214">Project</span></span>
- <span data-ttu-id="f2011-215">[プロジェクトの比較] 機能を使用すると、Project がクラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-215">Project may crash when you use the Compare Projects feature.</span></span>
- <span data-ttu-id="f2011-216">ダーク モードの場合、リソースが過剰に割り当てられているタスクのタスク検査パネルに移動すると、表を読み取ることができません。</span><span class="sxs-lookup"><span data-stu-id="f2011-216">If you are in Dark mode, when you go to the task inspector panel on a task with an over allocated resource, you are unable to read the table.</span></span>
- <span data-ttu-id="f2011-217">割り当てのないタスクに作業を設定すると、1 日間に丸められます。</span><span class="sxs-lookup"><span data-stu-id="f2011-217">Setting effort on tasks that have no assignments are rounded to 1 day.</span></span>

### <a name="word"></a><span data-ttu-id="f2011-218">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-218">Word</span></span>
- <span data-ttu-id="f2011-219">差し込み印刷の実行後に、特定の条件下でファイルを保存できない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-219">Saving a file after doing a mail merge may not work under certain conditions.</span></span>
- <span data-ttu-id="f2011-220">文書パーツ オーガナイザーに無効なアラートが表示される場合があります。&quot;スタイル、文書パーツを変更しました。&quot;</span><span class="sxs-lookup"><span data-stu-id="f2011-220">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>
- <span data-ttu-id="f2011-221">コピーと貼り付けを使用すると、コメント ウィンドウが再読み込みされることがあります。</span><span class="sxs-lookup"><span data-stu-id="f2011-221">Comment pane sometimes gets reloaded when using copy/paste.</span></span>
- <span data-ttu-id="f2011-222">コメントが正しい順序で貼り付けられない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-222">Comments are sometimes not pasted in the correct order.</span></span>
- <span data-ttu-id="f2011-223">カスタム スタイルのマルチレベル リストで構成されるテンプレートを既存のドキュメントに適用すると、特定の条件下でスタイルが保持されない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-223">Applying a template consisting of a multi-level list with custom styles to existing documents may not preserve the style under certain conditions.</span></span>
- <span data-ttu-id="f2011-224">分割画面の境界のサイズを変更すると、さらに分割画面が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-224">Resizing a split screen border may introduce an additional split screen.</span></span>
- <span data-ttu-id="f2011-225">余白のドロップダウン メニューが正しくレンダリングされない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-225">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="f2011-226">コメント カードでユーザーをメンションすると、JSON が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-226">At-mentioning a user in a comment card may show JSON.</span></span>
- <span data-ttu-id="f2011-227">ある Office アプリケーションから別の Office アプリケーションへの安全なリンクは、リンクされたアプリケーションを起動しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-227">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="office-suite"></a><span data-ttu-id="f2011-228">Office スイート</span><span class="sxs-lookup"><span data-stu-id="f2011-228">Office Suite</span></span>
- <span data-ttu-id="f2011-229">日本語ベースの製品の場合、アカウント ユーザーの姓と名が誤った順序で表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-229">For Japanese based products, account user first name, last name may appear in incorrect order.</span></span>
- <span data-ttu-id="f2011-230">コメントにマウス ポインターを合わせた際に、コメントの周りにテキストボックスのアウトラインが表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-230">Hovering a mouse pointer over comments may display a textbox outline around the comment.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1912-november-15"></a><span data-ttu-id="f2011-232">バージョン 1912: 11 月 15 日</span><span class="sxs-lookup"><span data-stu-id="f2011-232">Version 1912: November 15</span></span>
<span data-ttu-id="f2011-233">*バージョン 1912 (ビルド 12307.20000)*</span><span class="sxs-lookup"><span data-stu-id="f2011-233">*Version 1912 (Build 12307.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="f2011-235">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="f2011-235">Feature updates</span></span>
### <a name="insights-services"></a><span data-ttu-id="f2011-236">インサイト サービス</span><span class="sxs-lookup"><span data-stu-id="f2011-236">Insights Services</span></span>
- <span data-ttu-id="f2011-237">**Excel のアイデアの自然言語のクエリ:** データについて自然言語の質問をする Excel のアイデアの新機能。</span><span class="sxs-lookup"><span data-stu-id="f2011-237">**Natural Language Queries in Ideas in Excel:** Excel Ideas's new capability to ask a natural language question about your data.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="f2011-240">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="f2011-240">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="f2011-241">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-241">Excel</span></span>
- <span data-ttu-id="f2011-242">一部のローカライズにおいて、[Text to Column] 機能が失敗することがあります。</span><span class="sxs-lookup"><span data-stu-id="f2011-242">Text to Column functionality may fail for some localizations.</span></span>
- <span data-ttu-id="f2011-243">セル内の動的配列数式を編集すると、セルの境界の外にテキストが並んでしまう場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-243">Editing dynamic array formulas within a cell may result in text being aligned outside of the boundary of the cell.</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-244">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-244">Outlook</span></span>
- <span data-ttu-id="f2011-245">グループ ポリシーを使用して S/MIME 構成を適用する機能が追加されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-245">Added the ability to enforce S/MIME configuration via group policy.</span></span>
- <span data-ttu-id="f2011-246">思ったよりも埋め込み画像が小さく表示されることがあります。</span><span class="sxs-lookup"><span data-stu-id="f2011-246">Embedded images may appear smaller than expected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-247">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-247">PowerPoint</span></span>
- <span data-ttu-id="f2011-248">テキストからフォーカスを移動した後、カーソルが表示されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="f2011-248">Cursor may disappear after moving focus from text.</span></span>

### <a name="project"></a><span data-ttu-id="f2011-249">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-249">Project</span></span>
- <span data-ttu-id="f2011-250">ユーザーにライセンスに関するエラーが表示されることがあります。</span><span class="sxs-lookup"><span data-stu-id="f2011-250">Users may experience an error regarding licensing.</span></span>
- <span data-ttu-id="f2011-251">日付の選択の [今日] ボタンで正しくない日付が設定されることがあります。</span><span class="sxs-lookup"><span data-stu-id="f2011-251">The Today button in the date picker may sometimes set the incorrect date.</span></span>

### <a name="word"></a><span data-ttu-id="f2011-252">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-252">Word</span></span>
- <span data-ttu-id="f2011-253">右クリックすると、完全に一致する単語が選択されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="f2011-253">Right-clicking can sometimes not result in selecting the whole word.</span></span>
- <span data-ttu-id="f2011-254">提案されたファイル形式に変換した後、カーソルがオブジェクト内でアクティブのままになってしまうことがあります。</span><span class="sxs-lookup"><span data-stu-id="f2011-254">The cursor may remain active within an object after converting to a suggested format.</span></span>
- <span data-ttu-id="f2011-255">一部のシナリオでは、メッセージ内の画像が正しく拡大されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="f2011-255">Images in messages may be incorrectly scaled in some scenarios.</span></span>
- <span data-ttu-id="f2011-256">一部のテーマでは、どのコメントが選択されているかの判断が困難になることがあります。</span><span class="sxs-lookup"><span data-stu-id="f2011-256">Some themes may make it difficult to determine which comment is selected.</span></span>
- <span data-ttu-id="f2011-257">ウィンドウ スイッチャーで非表示のときに、コメントのヒントを選択すると最新のコメント ウィンドウが表示されるようになります。</span><span class="sxs-lookup"><span data-stu-id="f2011-257">Selecting a comment hint should now show the modern comments pane when hidden in pane switcher.</span></span>

### <a name="office-suite"></a><span data-ttu-id="f2011-258">Office スイート</span><span class="sxs-lookup"><span data-stu-id="f2011-258">Office Suite</span></span>
- <span data-ttu-id="f2011-259">コメントに返信すると、テキスト ボックスがウィンドウの端を超えて縦方向に展開されることがあります。</span><span class="sxs-lookup"><span data-stu-id="f2011-259">Replying to a comment may cause the textbox to expand vertically beyond the edge of the pane.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1912-november-08"></a><span data-ttu-id="f2011-261">バージョン 1912: 11 月 8 日</span><span class="sxs-lookup"><span data-stu-id="f2011-261">Version 1912: November 08</span></span>
<span data-ttu-id="f2011-262">*バージョン 1912 (ビルド 12231.20000)*</span><span class="sxs-lookup"><span data-stu-id="f2011-262">*Version 1912 (Build 12231.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="f2011-264">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="f2011-264">Feature updates</span></span>
### <a name="user-lifecycle"></a><span data-ttu-id="f2011-265">ユーザーのライフサイクル</span><span class="sxs-lookup"><span data-stu-id="f2011-265">User Lifecycle</span></span>
- <span data-ttu-id="f2011-266">**AFO アクティベーションのエクスペリエンスの改善:** 新しい PC にバンドルされている Office のアクティベーション時にお客様に表示される画面の更新。</span><span class="sxs-lookup"><span data-stu-id="f2011-266">**Experience improvements for AFO activation:** Updates to the screens customers see when activating Office that comes bundled with their new PC.</span></span>

### <a name="word"></a><span data-ttu-id="f2011-267">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-267">Word</span></span>
- <span data-ttu-id="f2011-268">**Word の新しい、改善されたオンライン ビデオ エクスペリエンス:** Word での新しいビデオの挿入および既存のビデオの再生に役立つ、新しくより安全なオンライン ビデオ エクスペリエンス。</span><span class="sxs-lookup"><span data-stu-id="f2011-268">**New and improved online video experience in Word:** New and more secure online video experience to help you insert new videos and play existing videos in Word.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="f2011-271">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="f2011-271">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="f2011-272">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-272">Outlook</span></span>
- <span data-ttu-id="f2011-273">クロス フォルダー コンテンツを含む断続的なクラッシュ。</span><span class="sxs-lookup"><span data-stu-id="f2011-273">Intermittent crash involving cross folder content.</span></span>

### <a name="office-suite"></a><span data-ttu-id="f2011-274">Office スイート</span><span class="sxs-lookup"><span data-stu-id="f2011-274">Office Suite</span></span>
- <span data-ttu-id="f2011-275">Excel から PowerPoint にグラフを貼り付けると、グラフのサイズが小さくなる場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-275">Pasting a chart from Excel to PowerPoint can reduce the size of the chart.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1911-november-01"></a><span data-ttu-id="f2011-277">バージョン 1911: 11 月 1 日</span><span class="sxs-lookup"><span data-stu-id="f2011-277">Version 1911: November 01</span></span>
<span data-ttu-id="f2011-278">*バージョン 1911 (ビルド 12228.20020)*</span><span class="sxs-lookup"><span data-stu-id="f2011-278">*Version 1911 (Build 12228.20020)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="f2011-280">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="f2011-280">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="f2011-281">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-281">Excel</span></span>
- <span data-ttu-id="f2011-282">**SVG オブジェクトにコンテキストを取り入れる:** 地図やグラフ、その他の SVG ベクターを Office で変換する場合、それらのオブジェクトの中にテキストを保持できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="f2011-282">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="f2011-283">**Surface ペンを使用するときにペンのオプションを確認する:** Word、Excel、PowerPoint で Surface ペンを初めて使用するときに、ペンの色を簡単に選べる [描画] タブがアクティブになります。</span><span class="sxs-lookup"><span data-stu-id="f2011-283">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-284">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-284">PowerPoint</span></span>
- <span data-ttu-id="f2011-285">**SVG オブジェクトにコンテキストを取り入れる:** 地図やグラフ、その他の SVG ベクターを Office で変換する場合、それらのオブジェクトの中にテキストを保持できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="f2011-285">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="f2011-286">**Surface ペンを使用するときにペンのオプションを確認する:** Word、Excel、PowerPoint で Surface ペンを初めて使用するときに、ペンの色を簡単に選べる [描画] タブがアクティブになります。</span><span class="sxs-lookup"><span data-stu-id="f2011-286">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="visio"></a><span data-ttu-id="f2011-287">Visio</span><span class="sxs-lookup"><span data-stu-id="f2011-287">Visio</span></span>
- <span data-ttu-id="f2011-288">**Excel で洗練された Visio 図を作成する:** すばやく簡単に、データを Excel 内の洗練された Visio 図に可視化します。</span><span class="sxs-lookup"><span data-stu-id="f2011-288">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> <span data-ttu-id="f2011-289">[詳細情報](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c) を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f2011-289">[Learn more](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).</span></span>

### <a name="word"></a><span data-ttu-id="f2011-290">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-290">Word</span></span>
- <span data-ttu-id="f2011-291">**Surface ペンを使用するときにペンのオプションを確認する:** Word、Excel、PowerPoint で Surface ペンを初めて使用するときに、ペンの色を簡単に選べる [描画] タブがアクティブになります。</span><span class="sxs-lookup"><span data-stu-id="f2011-291">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

- <span data-ttu-id="f2011-292">**共同編集の改善:** コンテンツの変更をリアルタイムでユーザーが受け取れるようにすることで、共同編集のエクスペリエンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-292">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="f2011-293">**他のユーザーがすばやく変更を確認:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="f2011-293">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="f2011-296">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="f2011-296">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="f2011-297">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-297">Excel</span></span>
- <span data-ttu-id="f2011-298">信頼されていないネットワーク共有から保護されたファイルを編集すると、Excel がクラッシュすることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-298">Resolved an issue where Excel may crash when editing a protected file from an untrusted network share.</span></span>
- <span data-ttu-id="f2011-299">別のシートのデータを参照しているスパークラインを含むシートを削除すると、再びそのファイルを開いた時に破損したファイルとして識別されるという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-299">Resolved an issue where deleting sheets containing sparklines referencing data on another sheet could cause the file to be identified as corrupted when re-opened.</span></span>
- <span data-ttu-id="f2011-300">SQL 表形式サーバーのクエリのピボットテーブルの残りの部分と一緒にレポート フィルターを変換すると、正しい結果が返されないことがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-300">Resolved an Issue where you may get incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span>
- <span data-ttu-id="f2011-301">ナレーターと拡大鏡を同時に使用すると、クラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-301">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="f2011-302">ナレーターと拡大鏡を同時に使用すると、クラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-302">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-303">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-303">Outlook</span></span>
- <span data-ttu-id="f2011-304">メールを転送すると、埋め込み画像がなくなる場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-304">A forwarded e-mail may be missing embedded images.</span></span>
- <span data-ttu-id="f2011-305">会議室の検索ツールで、使用可能な会議室が&quot;なし&quot;と表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-305">Room Finder tool may be displaying &quot;None&quot; for available rooms.</span></span>
- <span data-ttu-id="f2011-306">厳しいテナント制限がある Outlook プロファイルをユーザーが作成できない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-306">Users may not be able to create Outlook profiles with strict tenant restriction.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-307">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-307">PowerPoint</span></span>
- <span data-ttu-id="f2011-308">ナレーターと拡大鏡を同時に使用すると、クラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-308">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="project"></a><span data-ttu-id="f2011-309">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-309">Project</span></span>
- <span data-ttu-id="f2011-310">ユーザーがタスクを完了としてマークすることができず、99% に設定されます。</span><span class="sxs-lookup"><span data-stu-id="f2011-310">User is unable to mark a task as complete, and it gets set to 99%.</span></span>
- <span data-ttu-id="f2011-311">平準化によって割り当て超過が解決されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="f2011-311">Overallocations are not resolved by leveling.</span></span>

### <a name="word"></a><span data-ttu-id="f2011-312">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-312">Word</span></span>
- <span data-ttu-id="f2011-313">ナレーターと拡大鏡を同時に使用すると、クラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-313">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="f2011-314">以前のドキュメントを開いたまま [情報] タブに移動すると、クラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-314">Opening legacy documents and then going to the Info tab can cause a crash.</span></span>
- <span data-ttu-id="f2011-315">文章校正の候補がコンテキスト メニューに表示されません。</span><span class="sxs-lookup"><span data-stu-id="f2011-315">Proofing suggestins are not displaying in contextual menus.</span></span>
- <span data-ttu-id="f2011-316">コンテンツ ポリシーがコメントに正しく適用されません。</span><span class="sxs-lookup"><span data-stu-id="f2011-316">Content policies are being incorrectly applied to comments.</span></span>
- <span data-ttu-id="f2011-317">濃色のテキストで書かれた従来のコメントがダーク モードで表示されません。</span><span class="sxs-lookup"><span data-stu-id="f2011-317">Legacy comments written with dark text is not visible in Dark Mode.</span></span>
- <span data-ttu-id="f2011-318">韓国語/英語のオートコレクトを使用しているときに、間違った文字が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-318">Incorrect characters may appear when using Korean/English autocorrect.</span></span>
- <span data-ttu-id="f2011-319">上位のポリシー ラベルが優先して適用されるべき時に、低いポリシー ラベルが適用されることがあります。</span><span class="sxs-lookup"><span data-stu-id="f2011-319">Lower policy labels may be applied when a higher policy label should have taken priority.</span></span>
- <span data-ttu-id="f2011-320">Outlook メッセージ &nbsp; からの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="f2011-320">The links of cid: images from Outlook messages&nbsp;can now be successfully broken when requested.</span></span>
- <span data-ttu-id="f2011-321">ナレーターと拡大鏡を同時に使用すると、クラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-321">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="f2011-322">ナビゲーション ウィンドウから検索できない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-322">Searching from the Navigation pane may fail.</span></span>

### <a name="office-suite"></a><span data-ttu-id="f2011-323">Office スイート</span><span class="sxs-lookup"><span data-stu-id="f2011-323">Office Suite</span></span>
- <span data-ttu-id="f2011-324">一部の描画がプレビューやスライド ショーに表示されない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-324">Some drawings may not display in preview or slide shows.</span></span>
- <span data-ttu-id="f2011-325">縦書きのテキスト ボックス内で一部のカタカナが正しく表示されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="f2011-325">Some katakana characters may display incorrectly in a vertical text box.</span></span>
- <span data-ttu-id="f2011-326">接続されていないネットワーク共有にファイルを保存しようとすると、クラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-326">Attempting to save a file to a disconnected network share may result in a crash.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1911-october-25"></a><span data-ttu-id="f2011-328">バージョン 1911: 10 月 25 日</span><span class="sxs-lookup"><span data-stu-id="f2011-328">Version 1911: October 25</span></span>
<span data-ttu-id="f2011-329">*バージョン 1911 (ビルド 12215.20006)*</span><span class="sxs-lookup"><span data-stu-id="f2011-329">*Version 1911 (Build 12215.20006)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="f2011-331">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="f2011-331">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="f2011-332">Visio</span><span class="sxs-lookup"><span data-stu-id="f2011-332">Visio</span></span>

- <span data-ttu-id="f2011-333">**Excel で洗練された Visio 図を作成する:** すばやく簡単に、データを Excel 内の洗練された Visio 図に可視化します。</span><span class="sxs-lookup"><span data-stu-id="f2011-333">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> [<span data-ttu-id="f2011-334">詳細情報</span><span class="sxs-lookup"><span data-stu-id="f2011-334">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="f2011-335">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-335">Word</span></span>

- <span data-ttu-id="f2011-336">**共同編集の改善:** コンテンツの変更をリアルタイムでユーザーが受け取れるようにすることで、共同編集のエクスペリエンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-336">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="f2011-337">**他のユーザーがすばやく変更を確認:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="f2011-337">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="f2011-340">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="f2011-340">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="f2011-341">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-341">Access</span></span>

- <div><span data-ttu-id="f2011-342"><span>レコードのカウントが正しくないという問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-342"><span>The record count could be incorrect</span></span></span></div>


### <a name="excel"></a><span data-ttu-id="f2011-343">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-343">Excel</span></span>

- <div><span data-ttu-id="f2011-344"><span>結合されたセルで列を削除するパフォーマンスが大幅に改善されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-344"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


- <div><span data-ttu-id="f2011-345"><span>ユーザーが Office 365 の Excel ブック形式で保存できなくなる問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-345"><span>Users could be prevented from saving in Office 365 Excel Workbook format</span></span></span></div>


- <div><span data-ttu-id="f2011-346"><span>チェックボックスで正しく表示できないという問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-346"><span>Checkboxes could not render correctly</span></span></span></div>


- <div><span data-ttu-id="f2011-347"><span>グラフのサイズの変更が保存できないという問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-347"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="f2011-348"><span>VBA 関数の一部で、新しいグラフの種類に関するエラーが返される問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-348"><span>Some VBA functions would return an error on new chart types</span></span></span></div>


- <div><span data-ttu-id="f2011-349"><span>[データ ソースの選択] ダイアログで、一部のフィールドの大文字小文字の区別をしなかった問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-349"><span>Select Data Source dialogs were not case sensitive for some fields</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="f2011-350">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-350">PowerPoint</span></span>

- <div><span data-ttu-id="f2011-351"><span>グラフのサイズの変更が保存できないという問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-351"><span>Changes to a chart size could not be saved</span></span></span></div>


### <a name="publisher"></a><span data-ttu-id="f2011-352">Publisher</span><span class="sxs-lookup"><span data-stu-id="f2011-352">Publisher</span></span>

- <div><span data-ttu-id="f2011-353"><span>図形がグラフィックの境界線の外側に表示される問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-353"><span>Shapes could appear outside of the graphics border</span></span></span></div>


### <a name="word"></a><span data-ttu-id="f2011-354">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-354">Word</span></span>

- <div><span data-ttu-id="f2011-355"><span>図形がグラフィックの境界線の外側に表示される問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-355"><span>Shapes could appear outside of the graphics border</span></span></span></div>


- <div><span data-ttu-id="f2011-356"><span>テキストの強調表示が課題になるという問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-356"><span>Highlighting text could be challenging</span></span></span></div>


- <div><span data-ttu-id="f2011-357"><span>ユーザーがエディターの個々のアイテムに移動できなくなる問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-357"><span>A user could be prevented from navigating to an individual item in the editor</span></span></span></div>


- <div><span data-ttu-id="f2011-358"><span>文法またはスペルのエラーが強調表示されない問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-358"><span>Grammar or spelling errors might not be highlighted</span></span></span></div>


- <div><span data-ttu-id="f2011-359"><span>グラフのサイズの変更が保存できないという問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-359"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="f2011-360"><span>連絡先カードが、@ メンションに書式を設定した後に、開けなくなる問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-360"><span>A contact card could be prevented from opening after apply formatting to an @ mention</span></span></span></div>


- <div><span data-ttu-id="f2011-361"><span>ユーザーが、Word、Excel、PowerPoint のドキュメントを保存できなくなる場合があるという問題が解決されました。&nbsp;この問題は、[保存] アイコンをクリックしたり Ctrl キーを押しながら S キーを押したりした後に、新しいファイルを作成して &quot;[モデル形式で保存] ダイアログ&quot; を表示するユーザーに影響を与えます。</span></span><span class="sxs-lookup"><span data-stu-id="f2011-361"><span>Resolvedan issue where users may be unable to save Word, Excel, and PowerPoint documents.&nbsp; This issue affects users that create a new file and bring up the &quot;Save as Model Dialog&quot; option after clicking on the Save icon or pressing Ctrl + S.</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="f2011-362">Office スイート</span><span class="sxs-lookup"><span data-stu-id="f2011-362">Office Suite</span></span>

- <div><span data-ttu-id="f2011-363"><span>Windows 7 で図形を使用する場合のパフォーマンスの問題</span></span><span class="sxs-lookup"><span data-stu-id="f2011-363"><span>Performance issue when using Shapes on Windows 7</span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1911-october-18"></a><span data-ttu-id="f2011-365">バージョン 1911: 10 月 18 日</span><span class="sxs-lookup"><span data-stu-id="f2011-365">Version 1911: October 18</span></span>
<span data-ttu-id="f2011-366">*バージョン 1911 (ビルド 12209.20010)*</span><span class="sxs-lookup"><span data-stu-id="f2011-366">*Version 1911 (Build 12209.20010)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="f2011-368">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="f2011-368">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="f2011-369">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-369">Outlook</span></span>

- <span data-ttu-id="f2011-370">**アクセシビリティ対応のメールを最も必要としている人に送信する:** Outlook では、メールのヒントが表示され、アクセシビリティ対応のコンテンツを必要とするユーザーに送信するときに、コンテンツがアクセシビリティ対応であることを確認できます</span><span class="sxs-lookup"><span data-stu-id="f2011-370">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-371">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-371">PowerPoint</span></span>

- <span data-ttu-id="f2011-372">**プレゼンテーションの最適化:** アクセシビリティ チェックを使用すると、スクリーン リーダーを考慮に入れて、スライド上のオブジェクトを配置することができます。</span><span class="sxs-lookup"><span data-stu-id="f2011-372">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

### <a name="office-suite"></a><span data-ttu-id="f2011-373">Office スイート</span><span class="sxs-lookup"><span data-stu-id="f2011-373">Office Suite</span></span>

- <span data-ttu-id="f2011-374">**アップロード センターは、Files Needing Attention experience に置き換えられます:** アップロード センターは、[ファイル] > [開く] の Office アプリケーション内に表示される Files Needing Attention experience に置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="f2011-374">**The Upload Center is being replaced by the Files Needing Attention experience:** The Upload Center is being replaced by the Files Needing Attention experience that will show up inside the Office applications under File > Open.</span></span> <span data-ttu-id="f2011-375">この新しいエクスペリエンスは、アップロード センターに比べ、最新かつ総合的で、煩わしくありません。</span><span class="sxs-lookup"><span data-stu-id="f2011-375">This new experience is more modern, integrated, and less intrusive compared to the Upload Center.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="f2011-378">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="f2011-378">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="f2011-379">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-379">Excel</span></span>

- <div><span data-ttu-id="f2011-380"><span>自動調整を使用して行の高さを調整するときにチェック ボックスのコントロールが縮小されるという問題を解決しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-380"><span>Resolved an issue where check box controls could shrink when using autofit to adjust row height</span></span></span></div>


- <div><span data-ttu-id="f2011-381"><span>スクロール後にセルを選択すると間違ったセルが選択されるという問題を解決しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-381"><span>Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="f2011-382">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-382">Outlook</span></span>

- <div><span data-ttu-id="f2011-383"><span>メールにデジタル署名付きの添付ファイルがある場合にそのメールに署名するとデジタル署名が破損する可能性があるという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-383"><span>Identified an issue which could cause digital signatures to become broken when signing an e-mail with a digitally signed attachment</span></span></span></div>


- <div><span data-ttu-id="f2011-384"><span>長いファイル名がメッセージ本文へのドラッグ アンド ドロップ後に切り捨てられるという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-384"><span>Identified an issue where long filenames were truncated after draging and droping to the message body</span></span></span></div>


- <div><span data-ttu-id="f2011-385">リボンを自動的に非表示にするよう設定されている場合に検索ボックスが消えるという問題を特定しました</span><span class="sxs-lookup"><span data-stu-id="f2011-385">Identified an issue where the search box could disappear when the ribbon is set to hide automatically</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="f2011-386">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-386">PowerPoint</span></span>

- <div><span data-ttu-id="f2011-387"><span>スライド プレビューの縦横比が適切にロック/ロック解除されていないという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-387"><span>Identified an issuewhere aspect ratio for the slide preview was not being properly locked/unlocked</span></span></span></div>

### <a name="project"></a><span data-ttu-id="f2011-388">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-388">Project</span></span>

- <div><span data-ttu-id="f2011-389">タスクの更新を実行中に入力したノートが保存されない可能性があるという問題を特定しました</span><span class="sxs-lookup"><span data-stu-id="f2011-389">Identified an issue where notes might not persist if entered while doing update tasks</span></span><br></div>


- <div><span data-ttu-id="f2011-390">ファイルがユーザーによってロックされている場合に、ユーザー名がエラー メッセージに表示されない可能性があるという問題を特定しました</span><span class="sxs-lookup"><span data-stu-id="f2011-390">Identified an issue where a file could be locked by a user, but no username would be displayed in the error message</span></span></div>


- <div><span data-ttu-id="f2011-391"><span>読み取り専用のプロジェクトを開いたときに複数のメッセージを取得する可能性があるという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-391"><span>Identified an issue where users could get several messages when opening a read-only project</span></span></span></div>


### <a name="word"></a><span data-ttu-id="f2011-392">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-392">Word</span></span>

- <div><span data-ttu-id="f2011-393"><span>スクリーン リーダーを使用中にコメントを表示するときの問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-393"><span>Identified an issue when viewing comments while using a screen reader</span></span></span></div>


- <div><span data-ttu-id="f2011-394"><span>一部の批評がスペルまたは文法の批評と誤って識別されるという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-394"><span>Identified an issue where some critiques were misidentified as being spelling or grammar critiques</span></span></span></div>


- <div><span data-ttu-id="f2011-395"><span>新しいコメント ダイアログがフォーカスを取得できないことがあるという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-395"><span>Identified an issue where a new comment dialog could sometimes not obtain focus</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="f2011-396">Office スイート</span><span class="sxs-lookup"><span data-stu-id="f2011-396">Office Suite</span></span>

- <div><span data-ttu-id="f2011-397"><span>&quot;[別のインストールが進行中です]&quot; という誤ったエラー メッセージによりアップグレードに失敗することがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-397"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="f2011-398"><span>ローカル リソースからクラウド リソースへの同期に影響する可能性がある問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-398"><span>Identified an issue which could affect syncing from a local resource to a cloud resource</span></span></span></div>

- <div><span data-ttu-id="f2011-399"><span>ウェルカム メッセージに無効なリンクが含まれているという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-399"><span>Identified an issue where a welcome message contained an invalid link</span></span></span></div>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-october-11"></a><span data-ttu-id="f2011-401">バージョン 1910: 10 月 11 日</span><span class="sxs-lookup"><span data-stu-id="f2011-401">Version 1910: October 11</span></span>
<span data-ttu-id="f2011-402">*バージョン 1910 (ビルド 12130.20112)*</span><span class="sxs-lookup"><span data-stu-id="f2011-402">*Version 1910 (Build 12130.20112)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)
[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)
[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="f2011-406">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="f2011-406">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="f2011-407">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-407">Excel</span></span>

- <div><span data-ttu-id="f2011-408">OneDrive からオブジェクトとしてファイルを挿入する場合の問題が解決されました</span><span class="sxs-lookup"><span data-stu-id="f2011-408">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="f2011-409">ハイパーリンク形式が一部のコンテンツに適切に適用されない場合がある問題が解決されました</span><span class="sxs-lookup"><span data-stu-id="f2011-409">Resolved an issue where the hyperlink format could not be properly applied to some content</span></span></div>


- <div><span data-ttu-id="f2011-410">数式に構造化された絶対参照が含まれる場合に誤って調整される可能性がある問題が解決されました</span><span class="sxs-lookup"><span data-stu-id="f2011-410">Resolved an issue where formulas containing structured absolute references may be adjusted incorrectly</span></span></div>


- <div><span data-ttu-id="f2011-411">Office 現在のバージョンで開いた場合に Excel の停止を引き起こす可能性がある、Office の以前のバージョンで作成されるブックの問題が解決されました</span><span class="sxs-lookup"><span data-stu-id="f2011-411">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office</span></span></div>


- <div><span data-ttu-id="f2011-412">Excel からコピーされたコンテンツを他の Office アプリケーションに貼り付けると、間違って表示されることがある問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-412">Resolved an issue where content copied from Excel could appear incorrect when pasted into other Office applications</span></span></div>


- <div><span data-ttu-id="f2011-413">グラフ テンプレートを使用してグラフを挿入する場合に、プレビューで正しい色が使用されるよう修正します</span><span class="sxs-lookup"><span data-stu-id="f2011-413">Fix to correct colors used in previews when inserting charts using chart templates</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="f2011-414">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-414">PowerPoint</span></span>

- <div><span data-ttu-id="f2011-415">AirSpace WinComp 下で実行しているときに ARC デバイスの接続が失われる問題を特定しました</span><span class="sxs-lookup"><span data-stu-id="f2011-415">Identified an issue where ARC Devices could lose connection when running under AirSpace WinComp</span></span></div>


### <a name="word"></a><span data-ttu-id="f2011-416">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-416">Word</span></span>

- <div><span data-ttu-id="f2011-417">OneDrive からオブジェクトとしてファイルを挿入する場合の問題が解決されました</span><span class="sxs-lookup"><span data-stu-id="f2011-417">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="f2011-418"><span>メールのスレッドからグラフィカル コンテンツが削除される原因となっていた問題を修正&nbsp;</span>するための回復手順が改善されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-418">Improved our recovery steps to f<span>ix an issue that caused graphical content to get deleted from email threads.&nbsp;</span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-october-04"></a><span data-ttu-id="f2011-420">バージョン 1910: 10 月 4 日</span><span class="sxs-lookup"><span data-stu-id="f2011-420">Version 1910: October 04</span></span>
<span data-ttu-id="f2011-421">*バージョン 1910 (ビルド 12126.20000)*</span><span class="sxs-lookup"><span data-stu-id="f2011-421">*Version 1910 (Build 12126.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="f2011-423">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="f2011-423">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="f2011-424">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-424">Excel</span></span>

- <span data-ttu-id="f2011-425">**データ ビジュアライザー アドイン:** Excel から Visio フローチャートをすばやく作成します。</span><span class="sxs-lookup"><span data-stu-id="f2011-425">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="f2011-426">詳細情報</span><span class="sxs-lookup"><span data-stu-id="f2011-426">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="f2011-429">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="f2011-429">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="f2011-430">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-430">Excel</span></span>

- <div><span data-ttu-id="f2011-431"><span>印刷プレビューの印刷範囲が正しくない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-431"><span>We fixed an issue where the print area in print preview was not correct</span></span></span></div>


- <div><span data-ttu-id="f2011-432"><span>共同編集セッション中にピボット テーブルが更新されないことがあった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-432"><span>We fixed an issue which could have prevented pivot tables from being refreshed during a co-authoring session</span></span></span></div>


### <a name="access"></a><span data-ttu-id="f2011-433">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-433">Access</span></span>

- <div><span data-ttu-id="f2011-434">共有データベースの使用中に、"&quot;矛盾がある状態&quot;" エラーがユーザーに表示されることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-434">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


### <a name="outlook"></a><span data-ttu-id="f2011-435">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-435">Outlook</span></span>

- <div><span data-ttu-id="f2011-436"><span>メール フォルダーの重複を引き起こすことがあった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-436"><span>We fixed an issue which could have caused duplication of mail folders</span></span></span></div>


- <div><span data-ttu-id="f2011-437"><span>S/MIME で暗号化された電子メールを送信しようとしたときに誤ったエラー メッセージが表示されることがあった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-437"><span>We fixed an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail</span></span></span></div>


- <div><span data-ttu-id="f2011-438"><span>ユーザーが Skype から「不在着信した会話」メッセージを受信したときにクラッシュすることがあった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-438"><span>We fixed an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype</span></span></span></div>


- <div><span data-ttu-id="f2011-439"><span>メモリ リークを引き起こすことがあった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-439"><span>We fixed an issue which could have resulted in a memory leak</span></span></span></div>


- <div><span data-ttu-id="f2011-440"><span>下書きとして保存したときに送信者の名前が変更されることがあった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-440"><span>We fixed an issue which could have caused the senders name to change when saved as a draft</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="f2011-441">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-441">PowerPoint</span></span>

- <div><span></span></div><span data-ttu-id="f2011-442">スライド マスターとスライド レイアウトのヘッダー/フッター/スライド番号プレースホルダーにテキストを貼り付けた後、TextRanges が破損することがあった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-442">We fixed an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout</span></span>


- <div><span></span></div><span data-ttu-id="f2011-443">ハイパーリンク付きのテキストを貼り付けるときにハイパーリンクが作成されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-443">We fixed an issue which prevented hyperlink from being created when pasting text with hyperlink</span></span>


- <div><span data-ttu-id="f2011-444">統計が正常に機能しなくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-444">We fixed an issue which would prevent statistics from working correctly</span></span></div>


### <a name="word"></a><span data-ttu-id="f2011-445">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-445">Word</span></span>

- <div><span data-ttu-id="f2011-446"><span>フォントの色がコミットされない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-446"><span>We fixed an issue where font colors were not being committed</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="f2011-447">Office スイート</span><span class="sxs-lookup"><span data-stu-id="f2011-447">Office Suite</span></span>

- <div><span data-ttu-id="f2011-448">この機能が無効になったときにバージョン履歴が表示されることがあった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-448">We fixed an issue which could offer version history when that feature was disabled</span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-september-27"></a><span data-ttu-id="f2011-450">バージョン 1910: 9 月 27 日</span><span class="sxs-lookup"><span data-stu-id="f2011-450">Version 1910: September 27</span></span>
<span data-ttu-id="f2011-451">*バージョン 1910 (ビルド 12119.20000)*</span><span class="sxs-lookup"><span data-stu-id="f2011-451">*Version 1910 (Build 12119.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)
[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)
[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="f2011-455">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="f2011-455">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="f2011-456">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-456">Excel</span></span>

- <div><span data-ttu-id="f2011-457"><span>シリーズ コレクションを変更するときに、散布図が適切にレンダリングされない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-457"><span>We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="f2011-458">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-458">Outlook</span></span>

- <div><span data-ttu-id="f2011-459"><span>共有予定表フォルダーを操作するときに、アクセス許可エラーを報告する可能性があった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-459"><span>We fixed an issue which could have reported permission errors when interacting with shared calendar folders</span></span></span></div>


- <div><span data-ttu-id="f2011-460"><span>ユーザーが予定表に添付ファイルを追加できない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-460"><span>We fixed an issue which could have prevented users from adding attachments to calendars</span></span></span></div>


- <div><span data-ttu-id="f2011-461"><span>デジタル署名されたメッセージに返信するときに、エラー メッセージが表示される問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-461"><span>We fixed an issue which caused error messages to display when replying to a digitally signed message</span></span></span></div>


### <a name="word"></a><span data-ttu-id="f2011-462">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-462">Word</span></span>

- <div><span data-ttu-id="f2011-463"><span>Deskjet プリンターへの印刷時に、スケーリングの問題を引き起こす可能性があった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-463"><span>We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="f2011-464">Office スイート</span><span class="sxs-lookup"><span data-stu-id="f2011-464">Office Suite</span></span>

- <div><span data-ttu-id="f2011-465"><span>中太字のテキストのスタイルが正しく表示されない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-465"><span>We fixed an issue where medium bold text could be incorrectly styled</span></span></span></div>


- <div><span data-ttu-id="f2011-466"><span>アップロードが保留されているファイルを閉じるときに、ユーザーに誤ったエラー メッセージが表示される問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-466"><span>We fixed an issue where a user could be given an incorrect error message when closing a file with a pending upload</span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-september-20"></a><span data-ttu-id="f2011-468">バージョン 1910: 9 月 20 日</span><span class="sxs-lookup"><span data-stu-id="f2011-468">Version 1910: September 20</span></span>
<span data-ttu-id="f2011-469">*バージョン 1910 (ビルド 12112.20000)*</span><span class="sxs-lookup"><span data-stu-id="f2011-469">*Version 1910 (Build 12112.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="f2011-473">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="f2011-473">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="f2011-474">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-474">Excel</span></span>

- <div><span data-ttu-id="f2011-475"><span>Excel が起動時にハングすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-475"><span>We fixed an issue where Excel could sometimes hang at launch</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="f2011-476">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-476">Outlook</span></span>

- <div><span data-ttu-id="f2011-477"><span>多数の部屋が利用可能な場合の部屋選択のパフォーマンスが大幅に向上しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-477"><span>We significantly improved the performance of room selection when there are a large number of rooms available</span></span></span></div>


- <div><span data-ttu-id="f2011-478"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Office 365 の最新の認証に移行するときに、Outlook に複数のメールボックスを使用しているユーザーのメールボックスの同期を妨げる可能性がある問題を修正しました。</span></span><span class="sxs-lookup"><span data-stu-id="f2011-478"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can prevent mailbox sync for customers with multiple mailboxes in Outlook when migrating to modern authentication in Office 365.</span></span></span><br></div>


- <div><span data-ttu-id="f2011-479"><span>署名ラベルの一部の文字がドロップダウン メニューに表示されない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-479"><span>We fixed an issue where some characters in signature labels would not display in the dropdown menu</span></span></span></div>


### <a name="project"></a><span data-ttu-id="f2011-480">プロジェクト</span><span class="sxs-lookup"><span data-stu-id="f2011-480">Project</span></span>

- <div><span data-ttu-id="f2011-481"><span>エンタープライズ リソースをローカル リソースに置き換えるとクラッシュする可能性がある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-481"><span>We fixed an issue which could cause a crash when replacing an enterprise resource with a local resource</span></span></span></div>


### <a name="word"></a><span data-ttu-id="f2011-482">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-482">Word</span></span>

- <div><span data-ttu-id="f2011-483"><span>下書き表示で同期スクロールが正常に機能しない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-483"><span>We fixed an issue which could prevent synchronous scrolling from working properly in draft view</span></span></span></div>


- <div><span data-ttu-id="f2011-484">ドキュメントを初めて保存した後、ツール ヒントが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-484">We fixed an issue which could prevent Tool Tips from displaying properly after saving a document for the first time</span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-september-13"></a><span data-ttu-id="f2011-486">バージョン 1910: 9 月 13 日</span><span class="sxs-lookup"><span data-stu-id="f2011-486">Version 1910: September 13</span></span>
<span data-ttu-id="f2011-487">*バージョン 1910 (ビルド 12105.20000)*</span><span class="sxs-lookup"><span data-stu-id="f2011-487">*Version 1910 (Build 12105.20000)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="f2011-489">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="f2011-489">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="f2011-490">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-490">Excel</span></span>

- <div><span data-ttu-id="f2011-491"><span>一部の保護されたシートにユーザーがハイパーリンクを貼り付けられない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-491"><span>We fixed an issue which could prevent a user from pasting hyperlinks in some protected sheets</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="f2011-492">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-492">Outlook</span></span>

- <div><span data-ttu-id="f2011-493"><span>コンパクト ビューで UI が動かなくなる問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-493"><span>We fixed an issue where the UI could get stuck in a compact view</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="f2011-494">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-494">PowerPoint</span></span>

- <div><span data-ttu-id="f2011-495"><span>PDFへの印刷時、ユーザーにエラーが発生する問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-495"><span>We fixed an issue where a user could experience an error upon printing to PDF</span></span></span></div>


### <a name="project"></a><span data-ttu-id="f2011-496">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-496">Project</span></span>

- <div><span data-ttu-id="f2011-497"><span>問題を修正しました (<span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">保護された作業が有効になっている場合、サマリー タスクの作業値を変更するとクラッシュする</span></span>)</span><span class="sxs-lookup"><span data-stu-id="f2011-497"><span>We fixed an issue where <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">changes to a work value on a summary task could cause a crash if protected work is enabled</span></span></span></span></div>


- <span data-ttu-id="f2011-498"><font size=2 style="background-color:rgb(255, 255, 255);">エンタープライズ カレンダーとイベントを同期する機能を阻害する可能性がある問題を修正しました</font></span><span class="sxs-lookup"><span data-stu-id="f2011-498"><font size=2 style="background-color:rgb(255, 255, 255);">We fixed an issue which could inhibit the ability to sync events with enterprise calendars</font></span></span>


### <a name="office-suite"></a><span data-ttu-id="f2011-499">Office スイート</span><span class="sxs-lookup"><span data-stu-id="f2011-499">Office Suite</span></span>

- <div><span data-ttu-id="f2011-500"><span>ファイルのローカル バージョンの破棄を促す警告が繰り返し発生する可能性がある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-500"><span>We fixed an issue which could cause a repeated warning to discard local versions of a file</span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-september-06"></a><span data-ttu-id="f2011-502">バージョン 1910: 9 月 6 日</span><span class="sxs-lookup"><span data-stu-id="f2011-502">Version 1910: September 06</span></span>
<span data-ttu-id="f2011-503">*バージョン 1910 (ビルド 12030.20004)*</span><span class="sxs-lookup"><span data-stu-id="f2011-503">*Version 1910 (Build 12030.20004)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="f2011-505">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="f2011-505">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="f2011-506">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-506">Excel</span></span>

- <span data-ttu-id="f2011-507">**準備ができたら、描画を開始:** Surface ペンを持てば、描画の準備完了です。</span><span class="sxs-lookup"><span data-stu-id="f2011-507">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="f2011-508">詳細情報</span><span class="sxs-lookup"><span data-stu-id="f2011-508">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="powerpoint"></a><span data-ttu-id="f2011-509">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-509">PowerPoint</span></span>

- <span data-ttu-id="f2011-510">**準備ができたら、描画を開始:** Surface ペンを持てば、描画の準備完了です。</span><span class="sxs-lookup"><span data-stu-id="f2011-510">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="f2011-511">詳細情報</span><span class="sxs-lookup"><span data-stu-id="f2011-511">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a><span data-ttu-id="f2011-512">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-512">Word</span></span>

- <span data-ttu-id="f2011-513">**準備ができたら、描画を開始:** Surface ペンを持てば、描画の準備完了です。</span><span class="sxs-lookup"><span data-stu-id="f2011-513">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="f2011-514">詳細情報</span><span class="sxs-lookup"><span data-stu-id="f2011-514">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="f2011-517">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="f2011-517">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="f2011-518">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-518">Excel</span></span>

- <div><span data-ttu-id="f2011-519"><span> リボンのフォント名が使用されているフォントと異なることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-519"><span>We fixed an issue which could cause the font name in the ribbon to be different from the font being used</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="f2011-520">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-520">Outlook</span></span>

- <div><span data-ttu-id="f2011-521"><span> Internet Explorer で制限付きサイトの保護モードが無効になると、Outlook により不適切なリソースの使用量になることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-521"><span>We fixed an issue that could result in inappropriate resource consumption by Outlook when Protected Mode is disabled for Restricted Sites in Internet Explorer</span></span></span></div>


- <div><span data-ttu-id="f2011-522"><span>時々、ANSI ソースのテキスト貼り付けるときに Unicode 文字が表示されることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-522"><span>We fixed an issue which could sometimes cause Unicode characters to appear when pasting text from an ANSI source</span></span></span></div>


- <div><span data-ttu-id="f2011-523"><span>グループ スケジュール ビューで一部のユーザーがオフラインとして間違って表示される問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-523"><span>We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span></span></div>


### <a name="word"></a><span data-ttu-id="f2011-524">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-524">Word</span></span>

- <div><span data-ttu-id="f2011-525"><span>テーブルの書式設定が失われることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-525"><span>We fixed an issue where table formatting could be lost</span></span></span></div>


- <div><span data-ttu-id="f2011-526"><span>Ctrl + V ショートカット キーが効かなくなることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-526"><span>We fixed an issue which could break the ctrl+v keyboard shortcut</span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1909-august-30"></a><span data-ttu-id="f2011-528">バージョン 1909: 8 月 30 日</span><span class="sxs-lookup"><span data-stu-id="f2011-528">Version 1909: August 30</span></span>
<span data-ttu-id="f2011-529">*バージョン 1909 (ビルド 12026.20000)*</span><span class="sxs-lookup"><span data-stu-id="f2011-529">*Version 1909 (Build 12026.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="f2011-531">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="f2011-531">Feature updates</span></span>

### <a name="access"></a><span data-ttu-id="f2011-532">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-532">Access</span></span>

- <span data-ttu-id="f2011-533">**リンク テーブルの高速検索:** 新しい検索ボックスにより、リンク テーブルを簡単に見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="f2011-533">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-534">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-534">PowerPoint</span></span>

- <span data-ttu-id="f2011-535">**図を SVG として保存する:** グラフ、図形、その他の図を、サイズ変更しても画質が低下しないスケーラブル ベクター グラフィックとして保存できます。</span><span class="sxs-lookup"><span data-stu-id="f2011-535">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="f2011-536">詳細情報</span><span class="sxs-lookup"><span data-stu-id="f2011-536">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="f2011-539">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="f2011-539">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="f2011-540">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-540">Excel</span></span>

- <div><span data-ttu-id="f2011-541"><span>&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">秘密度</span>のキー ヒントが&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">別のキー ヒントと競合している問題が修正されました。</span></span></span><span class="sxs-lookup"><span data-stu-id="f2011-541"><span>We fixed an issue where the keytip for&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">Sensitivity </span>was&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">conflicting with another keytip.</span></span></span></span></div>

- <div><span data-ttu-id="f2011-542"><span>共有ブックでの作業中に保存を行おうとする際に発生する問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="f2011-542"><span>We fixed an issue that occurred while working on a shared workbook when trying to save.</span></span></span></div>

- <div><span data-ttu-id="f2011-543"><span>Excel で、レジストリ値 "\Excel\Add-in Manager" にあるアドインのうち、最初の 16 個しか表示されない問題が修正されました。<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span><span class="sxs-lookup"><span data-stu-id="f2011-543"><span>We fixed an issue where Excel only lists the first 16 addins located in the '\Excel\Add-in Manager' registry values.<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span></span></div>


- <div><span data-ttu-id="f2011-544"><span>関数 Frequency() が誤った結果を返す問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="f2011-544"><span>We fixed an issue where the function Frequency() returns incorrect results.</span></span></span></div>


- <div><span data-ttu-id="f2011-545"><span>色によるフィルター処理のパフォーマンスが大幅に改善されました。</span></span><span class="sxs-lookup"><span data-stu-id="f2011-545"><span>We have significantly improved the performance of filtering by color.</span></span></span></div>


- <div><span data-ttu-id="f2011-546"><span>Surface のユーザーがマウスを動かすと、それがマウス クリックのイベントとして解釈されることがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="f2011-546"><span>We fixed an issue for Surface users where moving the mouse could be interpreted as a mouse click event.</span></span></span></div>


- <div><span data-ttu-id="f2011-547"><span>[検索と置換] ダイアログでキーボードによるナビゲーションを行えない問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-547"><span>We fixed an issue which prevented keyboard navigation in the Find/Replace dialog</span></span></span></div>


- <div><span data-ttu-id="f2011-548"><span>一部のフォント名が正しく表示されない問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-548"><span>We fixed an issue where the name of some fonts were not displayed correctly</span></span></span></div>


- <div><span data-ttu-id="f2011-549"><span>サポートされているファイル形式として CSV が表示されない問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-549"><span>We fixed an issue which prevented CSV from appearing as a supported file type</span></span></span></div>


### <a name="access"></a><span data-ttu-id="f2011-550">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-550">Access</span></span>

- <div><span data-ttu-id="f2011-551">共有データベースの使用中に、"&quot;矛盾がある状態&quot;" エラーがユーザーに表示されることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-551">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


- <div><span data-ttu-id="f2011-552"><span>日付選択カレンダーが表示されるべきではないときに表示されてしまうことがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="f2011-552"><span>We fixed an issue which could cause the date picker to appear when it shouldn't</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="f2011-553">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-553">Outlook</span></span>

- <div><span data-ttu-id="f2011-554"><span>一部の POP3 ユーザーに HTML コンテンツが表示されない問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-554"><span>We fixed an issue which prevented HTML content from appearing for some POP3 users</span></span></span></div>


- <div><span data-ttu-id="f2011-555"><span>Planner を利用できない環境で、連絡先カードのオーバーフロー メニューから機能しない [Planner] リンクを削除するための修正を行いました。</span></span><span class="sxs-lookup"><span data-stu-id="f2011-555"><span>We fixed an issue to remove non-functional 'Planner' link from the overflow menu in the contact card when working in environments where it is not available.</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="f2011-556">OneNote</span><span class="sxs-lookup"><span data-stu-id="f2011-556">OneNote</span></span>

- <div><span data-ttu-id="f2011-557"><span>フォーカスが &nbsp;OneNote のバックグラウンド同期に移動してしまうことがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="f2011-557"><span>We fixed an issue where&nbsp;OneNote background sync was sometimes stealing focus.</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="f2011-558">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-558">PowerPoint</span></span>

- <div><span data-ttu-id="f2011-559"><span>3-D Turntable の回転の向きに影響を与えていた問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="f2011-559"><span>We fixed an issue which would affect the rotation orientation of a 3D Turntable.</span></span></span></div>

- <div><span data-ttu-id="f2011-560"><span>ハイパーリンクに特殊文字が含まれている場合に一部のハイパーリンクが機能しない問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="f2011-560"><span>We fixed an issue which prevented some hyperlinks from working if they contained special characters.</span></span></span></div>

- <div><span data-ttu-id="f2011-561"><span>同時に複数のコメント ウィンドウが開かれる問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="f2011-561"><span>We fixed an issue which caused multiple comment panes to open at the same time.</span></span></span></div>

### <a name="project"></a><span data-ttu-id="f2011-562">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-562">Project</span></span>

- <div><span data-ttu-id="f2011-563"><span>チーム プランナー ビューを印刷した後にクラッシュすることがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="f2011-563"><span>We fixed an issue which could sometimes cause a crash after printing a Team Planner view.</span></span></span></div>

### <a name="word"></a><span data-ttu-id="f2011-564">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-564">Word</span></span>

- <div><span data-ttu-id="f2011-565">閲覧表示で、縦書きテキスト ボックス内の複数バイト文字が重なって表示される問題が<span>修正されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-565">We f<span>ixed an issue where multi-byte characters in vertical text box are shown overlapped in reading view.</span></span><br></span></div>

- <div><span data-ttu-id="f2011-566"><span>&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">ユーザーがアドイン ウィザードでアクションを実行する際に、日本語のはがきとグリーティング カードに関連するアドインのリソースが見つからない問題が修正されました。</span></span></span><span class="sxs-lookup"><span data-stu-id="f2011-566"><span>We&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">fixed an issue where Japanese post card and greeting card related addin resources are not found when the user takes action in the addin wizard.</span></span></span></span></div>

- <div><span data-ttu-id="f2011-567"><span>保護ビューで表示中に、タイトル バーのユーザー インターフェイスで問題を発生させることがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="f2011-567"><span>We fixed an issue which could cause issues with the Title Bar User Interface when in Protected View</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="f2011-568">Office スイート</span><span class="sxs-lookup"><span data-stu-id="f2011-568">Office Suite</span></span>

- <div><span data-ttu-id="f2011-569"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">標準の図形とコネクタ図形の両方が含まれる選択部分に対して [図形の変更] を適用するとファイルが破損する問題が修正されました。</span></span></span><span class="sxs-lookup"><span data-stu-id="f2011-569"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> We fixed a corrupt file issue when you Change Shape on a selection that contains both a normal shape and a connector shape.</span></span></span></span></div>

- <div><span data-ttu-id="f2011-570"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">複数の外付けモニターからドッキングとドッキングの解除を使用すると、アプリケーションに問題が発生する</span>問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="f2011-570"><span>We fixed an issue that <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">caused a problem in applications when using dock/undock from multiple external displays. </span></span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="august-23-2019br"></a><span data-ttu-id="f2011-572">**2019 年 8 月 23 日**</span><span class="sxs-lookup"><span data-stu-id="f2011-572">**August 23, 2019**</span></span><br/>
<span data-ttu-id="f2011-573">バージョン 1909 (ビルド 12015.20004)</span><span class="sxs-lookup"><span data-stu-id="f2011-573">Version 1909 (Build 12015.20004)</span></span><br/>



## <a name="non-security-updates"></a><span data-ttu-id="f2011-574">セキュリティ以外の更新プログラム:</span><span class="sxs-lookup"><span data-stu-id="f2011-574">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-575">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-575">Excel</span></span>

- <div><span data-ttu-id="f2011-576"><span>結合されたセルで列を削除するパフォーマンスが大幅に改善されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-576"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="f2011-577">Office スイート</span><span class="sxs-lookup"><span data-stu-id="f2011-577">Office Suite</span></span>

- <div><span data-ttu-id="f2011-578"><span>一部の Unicode 文字がブラウザー上で表示されない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-578"><span>We fixed an issue which could prevent some Unicode characters from being displayed when viewed in a browser</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="f2011-579">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-579">Outlook</span></span>

- <div><span data-ttu-id="f2011-580"><span>WebDAV の場所にファイルを保存できないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-580"><span>We fixed an issue which could have prevented files from being saved to a WebDAV location</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="f2011-581">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-581">PowerPoint</span></span>

- <div><span data-ttu-id="f2011-582"><span>ユーザーがあるコメントをクリックすると別のコメントが選択される問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-582"><span>We fixed an issue where a user would click on one comment, but another comment would be selected</span></span></span></div>





## <a name="august-16-2019br"></a><span data-ttu-id="f2011-583">**2019 年 8 月 16 日**</span><span class="sxs-lookup"><span data-stu-id="f2011-583">**August 16, 2019**</span></span><br/>
<span data-ttu-id="f2011-584">バージョン 1909 (ビルド 12013.20000)</span><span class="sxs-lookup"><span data-stu-id="f2011-584">Version 1909 (Build 12013.20000)</span></span><br/>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="f2011-585">PowerPoint 機能の更新:</span><span class="sxs-lookup"><span data-stu-id="f2011-585">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="f2011-586">**配布資料にスライド番号を印刷する:** スライド番号は配布資料に自動的に含まれます。</span><span class="sxs-lookup"><span data-stu-id="f2011-586">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="f2011-587">それらをオンのままにするか、オフにするか、選択します。</span><span class="sxs-lookup"><span data-stu-id="f2011-587">Leave them on, turn them off, it's all up to you.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="f2011-588">セキュリティ以外の更新プログラム:</span><span class="sxs-lookup"><span data-stu-id="f2011-588">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-589">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-589">Excel</span></span>

- <div><span data-ttu-id="f2011-590"><span>自動保存が有効になることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-590"><span>We fixed an issue which could cause AutoSave to become enabled</span></span></span></div>


- <div><span data-ttu-id="f2011-591">セルの高さが不正確に測定されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-591">We fixed an issue which could result in cell heights being measured inaccurately</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="f2011-592">Office スイート</span><span class="sxs-lookup"><span data-stu-id="f2011-592">Office Suite</span></span>

- <div><span data-ttu-id="f2011-593"><span>コメント機能のパフォーマンスを大幅に改善する問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-593"><span>We fixed an issue which significantly improves the performance of the Comments feature</span></span></span></div>


- <div><span data-ttu-id="f2011-594"><span>検索中に方向キーを使用するとクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-594"><span>We fixed an issue which could cause a crash when using arrow keys while in search</span></span></span></div>


- <div><span data-ttu-id="f2011-595"><span>@ 記号が特定の文字の後に配置された場合に @メンションを使用できないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-595"><span>We fixed an issue which could prevent an @ mention if the @ symbol was placed after certain characters</span></span></span></div>


- <div><span data-ttu-id="f2011-596"><span>@メンションを削除するとクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-596"><span>We fixed an issue which could sometimes cause a crash when deleting @ mentions</span></span></span></div>


- <div><span data-ttu-id="f2011-597"><span>コメント カードに絵文字が正しく表示されない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-597"><span>We fixed an issue which prevented emojis from displaying correctly in comment cards</span></span></span></div>


- <div><span data-ttu-id="f2011-598"><span>アクティブ​​ クリップボード​​でクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-598"><span>We fixed an issue with Active Clipboard which could sometimes result in a crash</span></span></span></div>


- <div><span data-ttu-id="f2011-599"><span>クイック アクセス ツール バーのボタンが機能しなくなることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-599"><span>We fixed an issue which could cause the Quick Access Toolbar buttons to stop working</span></span></span></div>


- <div><span data-ttu-id="f2011-600"><span>文書の書式設定プレビュー​​がバックグラウンドに切り替わらないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-600"><span>We fixed an issue which could prevent the Document Formatting Preview from switching to the background</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="f2011-601">OneNote</span><span class="sxs-lookup"><span data-stu-id="f2011-601">OneNote</span></span>

- <span data-ttu-id="f2011-602">Office テーマが黒に設定されている場合、セクションのドロップダウン リストにセクションの名前が空白で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-602">We fixed an issue where the names of sections appear blank in the section dropdown list when Office Theme is set to Black.</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-603">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-603">Outlook</span></span>

- <div><span data-ttu-id="f2011-604"><span>Outlook が繰り返しフォーカスを取得して失うことがある送信イベントに関する問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-604"><span>We fixed an issue with Send Events which could cause Outlook to repeatedly gain and lose focus</span></span></span></div>


- <div><span data-ttu-id="f2011-605"><span>[フォルダーに返信を投稿] ショートカットが機能しない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-605"><span>We fixed an issue which prevented the Post Reply to Folder shortcut from working</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="f2011-606">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-606">PowerPoint</span></span>

- <div><span data-ttu-id="f2011-607"><span>共同作業の際に問題を引き起こすことがある保護ビューの問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-607"><span>We fixed an issue with Protected View which could sometimes cause problems when collaborating</span></span></span></div>


- <div><span data-ttu-id="f2011-608"><span>コメント ウィンドウのタスクが適切に表示されないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-608"><span>We fixed an issue which could prevent tasks in comment panes from displaying properly</span></span></span></div>


- <div><span data-ttu-id="f2011-609"><span>新しいスライドを挿入するときにクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-609"><span>We fixed an issue which could cause a crash when inserting new slides</span></span></span></div>


### <a name="user-lifecycle"></a><span data-ttu-id="f2011-610">ユーザーのライフサイクル</span><span class="sxs-lookup"><span data-stu-id="f2011-610">User Lifecycle</span></span>

- <div><span data-ttu-id="f2011-611"><span>サブスクリプション機能が消えることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-611"><span>We fixed an issue which could sometimes result in subscription features disappearing</span></span></span></div>


### <a name="word"></a><span data-ttu-id="f2011-612">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-612">Word</span></span>

- <div><span data-ttu-id="f2011-613"><span>ハイパーリンクに特定の文字が含まれている場合、ハイパーリンクが壊れることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-613"><span>We fixed an issue where hyperlinks could be broken if the hyperlink contained certain characters</span></span></span></div>


- <div><span data-ttu-id="f2011-614"><span>画像のコメントを表示するときに画像のサイズが不適切になることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-614"><span>We fixed an issue where images could be improperly sized when viewing a comment for that image</span></span></span></div>


- <div><span data-ttu-id="f2011-615"><span>箇条書きのドロップダウン メニューでクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-615"><span>We fixed an issue with the Bullet List drop down menu which could sometimes result in a crash</span></span></span></div>





## <a name="august-09-2019br"></a><span data-ttu-id="f2011-616">**2019 年 8 月 9 日**</span><span class="sxs-lookup"><span data-stu-id="f2011-616">**August 09, 2019**</span></span><br/>
<span data-ttu-id="f2011-617">バージョン 1909 (ビルド 12001.20000)</span><span class="sxs-lookup"><span data-stu-id="f2011-617">Version 1909 (Build 12001.20000)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="f2011-618">Excel 機能の更新</span><span class="sxs-lookup"><span data-stu-id="f2011-618">Excel Feature updates:</span></span>

- <span data-ttu-id="f2011-619">**共同作業がさらに簡単に:** 共同編集の改善とは、条件付き書式、セルのスタイルなどを使用して作業しているときに、ユーザーによる変更がシームレスに共同作業者のそれらと統合されるということを意味します。</span><span class="sxs-lookup"><span data-stu-id="f2011-619">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>


- <span data-ttu-id="f2011-620">**検索して楽しむ:** 目的のアイコンを簡単に検索できるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-620">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="f2011-621">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="f2011-621">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="office-suite-feature-updates"></a><span data-ttu-id="f2011-622">Office スイートの機能の更新</span><span class="sxs-lookup"><span data-stu-id="f2011-622">Office Suite Feature updates:</span></span>

- <span data-ttu-id="f2011-623">**新しい Office アプリのアイコン:** シンプルかつ高性能で、インテリジェントな Office のエクスペリエンスを反映するように、アプリのアイコンがリニューアルされました。</span><span class="sxs-lookup"><span data-stu-id="f2011-623">**New Office app icons:** Redesigned app icons to reflect the simple, powerful, and intelligent experiences of Office</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="f2011-624">Outlook 機能の更新</span><span class="sxs-lookup"><span data-stu-id="f2011-624">Outlook Feature updates:</span></span>

- <span data-ttu-id="f2011-625">**攻撃に対する高度な保護:** Office 365 Advanced Threat Protection を用いると、メールの件名、添付メッセージ、署名されたメッセージ、ネットワーク パスなどの範囲内のハイパーリンクを利用した攻撃から保護されます。</span><span class="sxs-lookup"><span data-stu-id="f2011-625">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>


- <span data-ttu-id="f2011-626">**検索して楽しむ:** 目的のアイコンを簡単に検索できるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-626">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="f2011-627">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="f2011-627">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="f2011-628">PowerPoint 機能の更新</span><span class="sxs-lookup"><span data-stu-id="f2011-628">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="f2011-629">**検索して楽しむ:** 目的のアイコンを簡単に検索できるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-629">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="f2011-630">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="f2011-630">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="f2011-631">Word 機能の更新</span><span class="sxs-lookup"><span data-stu-id="f2011-631">Word Feature updates:</span></span>

- <span data-ttu-id="f2011-632">**他のユーザーがすばやく変更を確認する:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="f2011-632">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


- <span data-ttu-id="f2011-633">**検索して楽しむ:** 目的のアイコンを簡単に検索できるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-633">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="f2011-634">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="f2011-634">And when you're selecting, the Insert button tells you how many you've picked.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="f2011-635">セキュリティ以外の更新プログラム:</span><span class="sxs-lookup"><span data-stu-id="f2011-635">Non-security updates:</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-636">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-636">Outlook</span></span>

- <div><span data-ttu-id="f2011-637"><span>会議がキャンセルされた後に、会議の受信者が 2 つの通知を受け取る原因となっていた問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-637"><span>We fixed an issue which caused meeting recipients to receive two notifications after a meeting was cancelled</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="f2011-638">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-638">PowerPoint</span></span>

- <div><span data-ttu-id="f2011-639"><span>図形とアイコンの [線なし]、[塗りつぶしなし] をユーザーが選択したときに、クラッシュを引き起こす問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-639"><span>We fixed an issue which could cause a crash when the user selected No Outline or No Fill for Shapes and Icons</span></span></span></div>





## <a name="august-02-2019br"></a><span data-ttu-id="f2011-640">**2019 年 8 月 2 日**</span><span class="sxs-lookup"><span data-stu-id="f2011-640">**August 02, 2019**</span></span><br/>
<span data-ttu-id="f2011-641">バージョン 1908 (ビルド 11929.20002)</span><span class="sxs-lookup"><span data-stu-id="f2011-641">Version 1908 (Build 11929.20002)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="f2011-642">Excel 機能の更新</span><span class="sxs-lookup"><span data-stu-id="f2011-642">Excel Feature updates:</span></span>

- <span data-ttu-id="f2011-643">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="f2011-643">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="f2011-644">**ドキュメントに機密ラベルを適用する:** ファイルとメールに機密ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="f2011-644">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="f2011-645">Outlook 機能の更新</span><span class="sxs-lookup"><span data-stu-id="f2011-645">Outlook Feature updates:</span></span>

- <span data-ttu-id="f2011-646">**ドキュメントに機密ラベルを適用する:** ファイルとメールに機密ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="f2011-646">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="f2011-647">PowerPoint 機能の更新</span><span class="sxs-lookup"><span data-stu-id="f2011-647">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="f2011-648">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="f2011-648">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="f2011-649">**ドキュメントに機密ラベルを適用する:** ファイルとメールに機密ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="f2011-649">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="f2011-650">Word 機能の更新</span><span class="sxs-lookup"><span data-stu-id="f2011-650">Word Feature updates:</span></span>

- <span data-ttu-id="f2011-651">**ファイルを変換してアクセシビリティを向上させる:** ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="f2011-651">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="f2011-652">**別の言葉で伝える:** 別の言葉で伝えたいときに、[書き換え] でお助けします。</span><span class="sxs-lookup"><span data-stu-id="f2011-652">**Say it another way:** When you want to say it differently, Rewrite is there to help.</span></span> <span data-ttu-id="f2011-653">[書き換え] では、フレーズを洗練させるための別の言葉遣いを提供します。</span><span class="sxs-lookup"><span data-stu-id="f2011-653">Rewrite offers alternatives for finessing your phrases.</span></span>


- <span data-ttu-id="f2011-654">**ドキュメントに機密ラベルを適用する:** ファイルとメールに機密ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="f2011-654">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="f2011-655">セキュリティ以外の更新プログラム:</span><span class="sxs-lookup"><span data-stu-id="f2011-655">Non-security updates:</span></span>

### <a name="access"></a><span data-ttu-id="f2011-656">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-656">Access</span></span>
- <span data-ttu-id="f2011-657">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-657">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-658">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-658">Excel</span></span>

- <div><span data-ttu-id="f2011-659"><span>PDF に印刷するときに [&quot;すべてのラベルを繰り返す&quot;] が適用されているかのように表示されていた問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-659"><span>We fixed an issue which made it appear as though &quot;repeat all labels&quot; was applied when printing to a PDF</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="f2011-660">Office スイート</span><span class="sxs-lookup"><span data-stu-id="f2011-660">Office Suite</span></span>

- <div><span data-ttu-id="f2011-661"><span>デスクトップからドキュメントを開けないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-661"><span>We fixed an issue which could have prevented users from opening a document from the desktop</span></span></span></div>

- <div><span data-ttu-id="f2011-662"><span>[&quot;別のインストールが進行中です&quot;] という誤ったエラー メッセージによりアップグレードに失敗することがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-662"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="f2011-663"><span>セキュリティ更新プログラムがインストールされるときに、エラー メッセージが表示されることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-663"><span>We fixed an issue where a user could see error messages when security updates are installed</span></span></span></div>

- <div><span data-ttu-id="f2011-664"><span>カーソルが消えることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-664"><span>We fixed an issue which could cause the cursor to disappear</span></span></span></div>

- <div><span data-ttu-id="f2011-665"><span>既定で [ホーム] タブではなく [描画] タブが設定されていることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-665"><span>We fixed an issue where a user could be defaulted to the draw tab instead of the home tab</span></span></span></div>

- <div><span data-ttu-id="f2011-666"><span>大きなツリー ビューがクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-666"><span>We fixed an issue where large tree views could result in a crash</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="f2011-667">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-667">Outlook</span></span>

- <div></div><span data-ttu-id="f2011-668"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">パスワード入力画面が繰り返し表示されることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-668"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can cause repeated password prompts</span></span></span>

- <div><span data-ttu-id="f2011-669"><span>メール アドレスが正しくクエリされないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-669"><span>We fixed an issue which could prevent an email address from being queried correctly</span></span></span></div>

- <div><span data-ttu-id="f2011-670"><span>以前のバージョンの Outlook で作成した予定表アイテムを開けないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-670"><span>We fixed an issue which could prevent users from opening calendar items created by legacy versions of Outlook</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="f2011-671">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-671">PowerPoint</span></span>

- <div><span data-ttu-id="f2011-672"><span>一部のアニメーションが開始されないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-672"><span>We fixed an issue which could prevent some animations from starting</span></span></span></div>

### <a name="project"></a><span data-ttu-id="f2011-673">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-673">Project</span></span>
- <span data-ttu-id="f2011-674">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-674">Various performance and stability fixes</span></span>

### <a name="word"></a><span data-ttu-id="f2011-675">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-675">Word</span></span>

- <div><span data-ttu-id="f2011-676"><span>コメントへの返信が順番に表示されないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-676"><span>We fixed an issue where replies to comments could appear out of order</span></span></span></div>

- <div><span data-ttu-id="f2011-677"><span>状況によって、コメントの代わりにヒントが表示されることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-677"><span>We fixed an issue where in some situations, hints would be displayed instead of comments</span></span></span></div>

- <div><span data-ttu-id="f2011-678"><span>新しいコメントを追加しようとしたときに [変更履歴] ウィンドウが表示されることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-678"><span>We fixed an issue where the Revisions Pane could display when the user tried to add a new comment</span></span></span></div>

- <div><span data-ttu-id="f2011-679"><span>[元に戻す] ドロップダウン リストが表示されないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-679"><span>We fixed an issue which could prevent the undo dropdown list from appearing</span></span></span></div>

- <div><span data-ttu-id="f2011-680"><span>コメントを追加できないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="f2011-680"><span>We fixed an issue which could prevent comments from being added</span></span></span></div>


## <a name="july-26-2019"></a><span data-ttu-id="f2011-681">2019 年 7 月 26 日</span><span class="sxs-lookup"><span data-stu-id="f2011-681">July 26, 2019</span></span>
<span data-ttu-id="f2011-682">バージョン 1908 (ビルド 11916.20000)</span><span class="sxs-lookup"><span data-stu-id="f2011-682">Version 1908 (build 11916.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="f2011-683">新機能:</span><span class="sxs-lookup"><span data-stu-id="f2011-683">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="f2011-684">Word、Excel、PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-684">Word, Excel, PowerPoint</span></span>

#### <a name="create-more-accessible-pdfs"></a><span data-ttu-id="f2011-685">よりアクセシビリティの高い PDF ファイルを作成する</span><span class="sxs-lookup"><span data-stu-id="f2011-685">Create more accessible PDFs</span></span>

<span data-ttu-id="f2011-686">PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="f2011-686">Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="f2011-687">主な修正:</span><span class="sxs-lookup"><span data-stu-id="f2011-687">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="f2011-688">すべて</span><span class="sxs-lookup"><span data-stu-id="f2011-688">All</span></span>

- <span data-ttu-id="f2011-689">Office の更新後に、Office のファイルの種類の関連付けとアイコンが破損する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-689">We fixed an issue where file type association and icons for Office could sometimes break after an Office Update</span></span>

### <a name="word"></a><span data-ttu-id="f2011-690">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-690">Word</span></span> 
- <span data-ttu-id="f2011-691">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-691">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-692">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-692">Excel</span></span>
- <span data-ttu-id="f2011-693">グラフを移動するとクラッシュする場合がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-693">We fixed an issue where moving a chart could sometimes result in a crash</span></span>
- <span data-ttu-id="f2011-694">グラフの種類を変更した後にグラフ オブジェクトからブック オブジェクトを取得するとエラーが発生することがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-694">We fixed an issue where to get Workbook object from Chart object after changing chart types could sometimes result in an error</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-695">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-695">PowerPoint</span></span>
- <span data-ttu-id="f2011-696">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-696">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-697">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-697">Outlook</span></span>
- <span data-ttu-id="f2011-698">シンプル リボンで、無効にしてあるコントロールが淡色表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-698">We fixed an issue where in simplified ribbon, a disabled control could sometimes not be greyed out in the ribbon</span></span>

### <a name="access"></a><span data-ttu-id="f2011-699">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-699">Access</span></span>
- <span data-ttu-id="f2011-700">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="f2011-700">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="f2011-701">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-701">Project</span></span>
- <span data-ttu-id="f2011-702">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-702">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-19-2019"></a><span data-ttu-id="f2011-703">2019 年 7 月 19 日</span><span class="sxs-lookup"><span data-stu-id="f2011-703">July 19, 2019</span></span>
<span data-ttu-id="f2011-704">バージョン 1908 (ビルド 11911.20000)</span><span class="sxs-lookup"><span data-stu-id="f2011-704">Version 1908 (build 11911.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="f2011-705">新機能:</span><span class="sxs-lookup"><span data-stu-id="f2011-705">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="f2011-706">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-706">Word</span></span>

#### <a name="learn-what-acronyms-mean-when-you-read-in-word-online"></a><span data-ttu-id="f2011-707">Word Online の文書で使われている略語の意味を確認する</span><span class="sxs-lookup"><span data-stu-id="f2011-707">Learn what Acronyms mean when you read in Word Online</span></span>

<span data-ttu-id="f2011-708">略語を見つけたら、組織内のデータを使用してそれを定義しようとします。</span><span class="sxs-lookup"><span data-stu-id="f2011-708">When you encounter an Acronym, we'll try to define it using data from within your organization.</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="f2011-709">主な修正:</span><span class="sxs-lookup"><span data-stu-id="f2011-709">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="f2011-710">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-710">Word</span></span> 
- <span data-ttu-id="f2011-711">BookMarkEnd タグが欠けているという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-711">We fixed an issue which BookMarkEnd tag was missing.</span></span>
- <span data-ttu-id="f2011-712">ユーザーが特殊文字を入力しているときに、フォントの選択が変更される場合があるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-712">We fixed an issue where the font selection could change while the user was typing special characters</span></span>
- <span data-ttu-id="f2011-713">新しいコメント カードに空白の返信が発生することがあるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-713">We fixed an issue which could sometimes cause blank replies to a new comment card</span></span>
- <span data-ttu-id="f2011-714">メールを共有すると、書式設定が失われる場合があるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-714">We fixed an issue which could cause formatting to be lost when sharing an email</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-715">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-715">Excel</span></span>
- <span data-ttu-id="f2011-716">範囲の広い配列がクラッシュすることがあるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-716">We fixed an issue where an array with a large range could sometimes cause a crash</span></span>
- <span data-ttu-id="f2011-717">フィルター処理された範囲からデータをコピーする場合のパフォーマンスを大幅に向上しました</span><span class="sxs-lookup"><span data-stu-id="f2011-717">We significantly improved the performance of copying data from filtered ranges</span></span>
- <span data-ttu-id="f2011-718">ファイル名に特殊文字が含まれていると、一部のファイルを開くことができないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-718">We fixed an issue which prevented some files from opening if the filenames contained special characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-719">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-719">PowerPoint</span></span>
- <span data-ttu-id="f2011-720">PowerPoint で新しく作成したセクションのセクション名が既定で選択されていないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-720">We fixed an issue where section name was not selected by default for newly created section in PowerPoint.</span></span>
- <span data-ttu-id="f2011-721">4:3 ディスプレイを使用すると、UI の使用が困難になることがあるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-721">We fixed an issue which could cause the UI to become difficult to use when using a 4:3 display</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-722">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-722">Outlook</span></span>
- <span data-ttu-id="f2011-723">利用可能な会議室がリストに表示されないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-723">We fixed an issue which could prevent available rooms from being listed</span></span>
- <span data-ttu-id="f2011-724">一部の POP3 ユーザーの HTML 形式を設定できないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-724">We fixed an issue which prevented HTML formatting for some POP3 users</span></span>

### <a name="access"></a><span data-ttu-id="f2011-725">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-725">Access</span></span>
- <span data-ttu-id="f2011-726">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="f2011-726">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="f2011-727">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-727">Project</span></span>
- <span data-ttu-id="f2011-728">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-728">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-12-2019"></a><span data-ttu-id="f2011-729">2019 年 7 月 12 日</span><span class="sxs-lookup"><span data-stu-id="f2011-729">July 12, 2019</span></span>
<span data-ttu-id="f2011-730">バージョン 1907 (ビルド 11901.20038)</span><span class="sxs-lookup"><span data-stu-id="f2011-730">Version 1907 (build 11901.20038)</span></span>

## <a name="whats-new"></a><span data-ttu-id="f2011-731">新機能:</span><span class="sxs-lookup"><span data-stu-id="f2011-731">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-732">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-732">PowerPoint</span></span>
 
#### <a name="use-ink-replay-in-your-presentations"></a><span data-ttu-id="f2011-733">プレゼンテーションでインクの再生を使用する</span><span class="sxs-lookup"><span data-stu-id="f2011-733">Use ink replay in your presentations</span></span>
 
<span data-ttu-id="f2011-734">PowerPoint でインクの再生アニメーションを適用して、プレゼンテーションの表現力とコミュニケーション力を高めます。</span><span class="sxs-lookup"><span data-stu-id="f2011-734">Apply a replay animation for ink in PowerPoint to express and communicate more in presentations.</span></span> 

## <a name="notable-fixes"></a><span data-ttu-id="f2011-735">主な修正:</span><span class="sxs-lookup"><span data-stu-id="f2011-735">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="f2011-736">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-736">Word</span></span> 
- <span data-ttu-id="f2011-737">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-737">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-738">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-738">Excel</span></span>
- <span data-ttu-id="f2011-739">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-739">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-740">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-740">PowerPoint</span></span>
- <span data-ttu-id="f2011-741">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-741">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-742">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-742">Outlook</span></span>
- <span data-ttu-id="f2011-743">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-743">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="f2011-744">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-744">Access</span></span>
- <span data-ttu-id="f2011-745">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="f2011-745">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="f2011-746">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-746">Project</span></span>
- <span data-ttu-id="f2011-747">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-747">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-5-2019"></a><span data-ttu-id="f2011-748">2019 年 7 月 5 日</span><span class="sxs-lookup"><span data-stu-id="f2011-748">July 5, 2019</span></span>
<span data-ttu-id="f2011-749">バージョン 1907 (ビルド 11901.20018)</span><span class="sxs-lookup"><span data-stu-id="f2011-749">Version 1907 (build 11901.20018)</span></span>

## <a name="whats-new"></a><span data-ttu-id="f2011-750">新機能:</span><span class="sxs-lookup"><span data-stu-id="f2011-750">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="f2011-751">Word、Excel、PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-751">Word, Excel, PowerPoint</span></span>

#### <a name="sketchy-shapes"></a><span data-ttu-id="f2011-752">Sketchy で描く!</span><span class="sxs-lookup"><span data-stu-id="f2011-752">Sketchy Shapes!</span></span>

<span data-ttu-id="f2011-753">プレゼンテーションを作成中ですか。</span><span class="sxs-lookup"><span data-stu-id="f2011-753">In the middle of drafting a presentation?</span></span> <span data-ttu-id="f2011-754">まだ作業中であることを示す Sketchy スタイルを適用します。</span><span class="sxs-lookup"><span data-stu-id="f2011-754">Apply the sketchy style to show that you're still working on it.</span></span> <span data-ttu-id="f2011-755">これを使用すると、自由形式や手描きの図形に変えることなく、オブジェクトに個人的なタッチを与えることができます。</span><span class="sxs-lookup"><span data-stu-id="f2011-755">It gives a personal touch to your objects without turning it into a free form, hand-drawn shapes.</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-756">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-756">Excel</span></span>

- <span data-ttu-id="f2011-757">**ファイル共有の高速化**: ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="f2011-757">**Faster file sharing**: Share your documents right from the recently used list without having to open the file.</span></span>
### <a name="powerpoint"></a><span data-ttu-id="f2011-758">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-758">PowerPoint</span></span>

- <span data-ttu-id="f2011-759">**アクセスを容易にするため、[印刷] メニューに [配布資料にスライド番号を印刷する] を移動しました:** 配布資料が指定されているときに、[印刷] > [印刷レイアウト] ドロップダウンの順にクリックすると見つかります。</span><span class="sxs-lookup"><span data-stu-id="f2011-759">**The setting to Print Slide Numbers in Handouts has been moved to the Print Menu for easier access:**  Find it in the Print > Print Layout dropdown when a Handout layout is selected.</span></span> <span data-ttu-id="f2011-760">これにより、プレゼンテーションごとに簡単に設定を切り替えることもできます。</span><span class="sxs-lookup"><span data-stu-id="f2011-760">This also allows the setting to be easily toggled per presentation.</span></span> [<span data-ttu-id="f2011-761">詳細情報</span><span class="sxs-lookup"><span data-stu-id="f2011-761">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="f2011-762">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="f2011-762">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="word"></a><span data-ttu-id="f2011-763">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-763">Word</span></span>

- <span data-ttu-id="f2011-764">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="f2011-764">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="f2011-765">主な修正:</span><span class="sxs-lookup"><span data-stu-id="f2011-765">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="f2011-766">すべて</span><span class="sxs-lookup"><span data-stu-id="f2011-766">All</span></span>
- <span data-ttu-id="f2011-767">リボンのキー ヒントのパフォーマンスが大幅に改善されました</span><span class="sxs-lookup"><span data-stu-id="f2011-767">We significantly improved the performance of Ribbon KeyTips</span></span>
- <span data-ttu-id="f2011-768">「今後のリリース予定を確認」ダイアログが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-768">We fixed an issue which prevented the "See what's coming soon" dialog from being displayed properly</span></span>
- <span data-ttu-id="f2011-769">共著ギャラリーのポップアップで写真の位置がずれてしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-769">We fixed an issue which could cause Photos to be misaligned in the Co-auth Gallery flyout</span></span>

### <a name="word"></a><span data-ttu-id="f2011-770">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-770">Word</span></span> 
- <span data-ttu-id="f2011-771">新しいコメントが追加されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-771">We fixed an issue which could sometimes prevent new comments from being added</span></span>
- <span data-ttu-id="f2011-772">表がクラッシュすることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-772">We fixed an issue where tables could sometimes cause a crash</span></span>
- <span data-ttu-id="f2011-773">無効なデータが差し込み印刷の最後に追加されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-773">We fixed an issue where invalid data could sometimes be added to the end of a mail merge</span></span>
- <span data-ttu-id="f2011-774">一部の LaTeX 数式が正しく表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-774">We fixed an issue which could cause some LaTeX equations to render incorrectly</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-775">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-775">Excel</span></span>
- <span data-ttu-id="f2011-776">グラフの種類を変更するとランタイム例外が発生することがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-776">We fixed an issue where changing chart types could sometimes result in a runtime exception</span></span>
- <span data-ttu-id="f2011-777">複数のウィンドウを開いたときに正しくないリボンが表示されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-777">We fixed an issue where the incorrect ribbon could be displayed when multiple windows were open</span></span>
- <span data-ttu-id="f2011-778">マクロがブックの 2 番目のインスタンスを開いたときにエラーが発生することがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-778">We fixed an issue which could cause an error when a macro opened a second instance of a workbook</span></span>
- <span data-ttu-id="f2011-779">ブックを開いたり作成したりするとき、またはブックを切り替えるときにクラッシュすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-779">We fixed an issue which could cause a crash when opening or creating a workbook, or switching between workbooks</span></span>
- <span data-ttu-id="f2011-780">ユーザーが Word で作成した PDF を Teams で開くことができない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-780">We fixed an issue preventing users from opening a PDF created from Word in Teams</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-781">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-781">PowerPoint</span></span>
- <span data-ttu-id="f2011-782">PDF にエクスポートすると、グラフの品質が低下する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-782">We fixed an issue which would degrade the quality of a chart when exported to a pdf</span></span>
- <span data-ttu-id="f2011-783">中心までの距離を示すヒントが表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-783">We fixed an issue which prevented a tooltip indicating the distance to center from displaying</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-784">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-784">Outlook</span></span>
- <span data-ttu-id="f2011-785">ディスクの領域不足エラーが表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-785">We fixed an issue which could sometimes prevent a Disk Full error to be displayed</span></span>
- <span data-ttu-id="f2011-786">会議出席依頼を更新する際に添付ファイルが複製されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-786">We fixed an issue which could cause attachments to become duplicated when updating a meeting request</span></span>

### <a name="access"></a><span data-ttu-id="f2011-787">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-787">Access</span></span>
- <span data-ttu-id="f2011-788">一部のクエリが大きい整数値を返さない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-788">We fixed an issue which prevented some queries from returning large integer values</span></span>
- <span data-ttu-id="f2011-789">SQL テキストボックスが編集できなくなることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-789">We fixed an issue which could make the sql textbox uneditable</span></span>
- <span data-ttu-id="f2011-790">一部の高 DPI ディスプレイでは、ヒントが見づらいことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-790">We fixed an issue where tooltips could be difficult to see on some High DPI displays</span></span>

### <a name="project"></a><span data-ttu-id="f2011-791">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-791">Project</span></span>
- <span data-ttu-id="f2011-792">新しいタスクでフラグの値が編集できなくなることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-792">We fixed an issue which could cause flag values to become uneditable in new tasks</span></span>
- <span data-ttu-id="f2011-793">ステータスの更新によって割り当てとタスクの実際の開始日が不適切に設定されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-793">We fixed an issue which could cause a status update to improperly set Actual Start Date on Assignments and Tasks</span></span>
- <span data-ttu-id="f2011-794">一部のリソースが間違って割り当て超過に表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-794">We fixed an issue which could cause some resources to incorreclty appear overallocated</span></span>
- <span data-ttu-id="f2011-795">ラグが追加され、小数点の記号がカンマで、サーバーに接続されていると TaskDependencies Add メソッドが失敗することがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-795">We fixed an issue where the TaskDependencies Add method could fail when Lag is added, the decimal separator is a comma, and when connected to a server</span></span>
- <span data-ttu-id="f2011-796">CSOM を使用してローカル ユーザー設定フィールドの参照テーブルの値を更新すると PCS がクラッシュすることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-796">We fixed an issue where updating local custom field lookup table values via CSOM could crash PCS</span></span>
- <span data-ttu-id="f2011-797">作業時間の合計値に小数点が含まれる場合に正しく表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-797">We fixed an issue where the total work values may appear incorrect if they contain a decimal</span></span>

</BR></BR>

## <a name="june-28-2019"></a><span data-ttu-id="f2011-798">2019 年 6 月 28 日</span><span class="sxs-lookup"><span data-stu-id="f2011-798">June 28, 2019</span></span>
<span data-ttu-id="f2011-799">バージョン 1907 (ビルド 11819.20002)</span><span class="sxs-lookup"><span data-stu-id="f2011-799">Version 1907 (build 11819.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="f2011-800">新機能:</span><span class="sxs-lookup"><span data-stu-id="f2011-800">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-801">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-801">Excel</span></span>

- <span data-ttu-id="f2011-802">**Power Query の機能強化を使用して素早くコーディングする:** オートコンプリートと構文の色分けを使用して、素早くコーディングを完了します。</span><span class="sxs-lookup"><span data-stu-id="f2011-802">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="f2011-803">関数、列、パラメーターも簡単に見つけることができます</span><span class="sxs-lookup"><span data-stu-id="f2011-803">Easily discover functions, columns, and parameters, too</span></span>

- <span data-ttu-id="f2011-804">**類似列のテーブルを結合する:** 取得と変換 (Power Query) では、テーブルを結合するために列を比較するときに、近似テキスト マッチング ロジック (あいまい一致とも呼ばれる) が使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="f2011-804">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span>

### <a name="word"></a><span data-ttu-id="f2011-805">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-805">Word</span></span>

- <span data-ttu-id="f2011-806">**共同編集の改善:** 共同編集時の信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-806">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>
 
### <a name="word-excel-powerpoint-and-visio"></a><span data-ttu-id="f2011-807">Word、Excel、PowerPoint、Visio</span><span class="sxs-lookup"><span data-stu-id="f2011-807">Word, Excel, PowerPoint, and Visio</span></span>

#### <a name="recommended-documents"></a><span data-ttu-id="f2011-808">推奨されるドキュメント</span><span class="sxs-lookup"><span data-stu-id="f2011-808">Recommended Documents</span></span>

<span data-ttu-id="f2011-809">推奨される関連アクティビティを含むドキュメントをご確認ください。</span><span class="sxs-lookup"><span data-stu-id="f2011-809">Find documents with relevant activity recommended to you.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="f2011-810">主な修正:</span><span class="sxs-lookup"><span data-stu-id="f2011-810">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="f2011-811">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-811">Word</span></span> 
- <span data-ttu-id="f2011-812">一部の .DOC を開くことができない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-812">We fixed an issue which could prevent some .DOC files from opening</span></span>
- <span data-ttu-id="f2011-813">コメントが正常に読み込まれない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-813">We fixed an issue which could have prevented comments from loading properly</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-814">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-814">Excel</span></span>
- <span data-ttu-id="f2011-815">Power Query のパフォーマンスが向上しました</span><span class="sxs-lookup"><span data-stu-id="f2011-815">We improved the performance of Power Queries</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-816">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-816">PowerPoint</span></span>
- <span data-ttu-id="f2011-817">画面のちらつきの原因となる、Surface デバイスでのペン使用に関連する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-817">We fixed an issue related to using a pen on a Surface device which could cause the screen to flicker</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-818">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-818">Outlook</span></span>
- <span data-ttu-id="f2011-819">会議に変換すると、予定の空き時間情報が変更される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-819">We fixed an issue which could change the free/busy status of an appointment when converted to a meeting</span></span>
- <span data-ttu-id="f2011-820">電子メールがアドホック テンプレートで保護されている場合に、不適切なテンプレートと説明が表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-820">We fixed an issue where the wrong template and description would be displayed when an e-mail was protected with an ad-hoc template</span></span>

### <a name="access"></a><span data-ttu-id="f2011-821">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-821">Access</span></span>
- <span data-ttu-id="f2011-822">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="f2011-822">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="f2011-823">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-823">Project</span></span>
- <span data-ttu-id="f2011-824">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-824">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-21-2019"></a><span data-ttu-id="f2011-825">2019 年 6 月 21 日</span><span class="sxs-lookup"><span data-stu-id="f2011-825">June 21, 2019</span></span>
<span data-ttu-id="f2011-826">バージョン 1907 (ビルド 11815.20002)</span><span class="sxs-lookup"><span data-stu-id="f2011-826">Version 1907 (build 11815.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="f2011-827">新機能:</span><span class="sxs-lookup"><span data-stu-id="f2011-827">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-828">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-828">Outlook</span></span>

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a><span data-ttu-id="f2011-829">Outlook デスクトップにおける黒のテーマでの濃色モード</span><span class="sxs-lookup"><span data-stu-id="f2011-829">Dark Mode for Black Theme in Outlook Desktop</span></span>

<span data-ttu-id="f2011-830">[濃色] モードで黒のテーマを使用しているユーザーには、電子メールを読むときに [閲覧] ウィンドウは暗く表示され、メールを作成するときも同様に表示されます。</span><span class="sxs-lookup"><span data-stu-id="f2011-830">With dark mode, users in black theme will now also see the reading pane with a dark background when reading emails, and the compose experience with a dark background when writing emails.</span></span> <span data-ttu-id="f2011-831">ユーザーが明るい背景でメッセージがどのように見えるかを確認する場合に備えて、[閲覧] ウィンドウとリボンに [太陽/月] トグルがあります。</span><span class="sxs-lookup"><span data-stu-id="f2011-831">There is a sun/moon toggle on the reading pane and in the ribbon in case users want to preview what the message looks like with a light background instead.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="f2011-832">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="f2011-832">Getting Started:</span></span>

1. <span data-ttu-id="f2011-833">[黒のテーマ] に切り替えると、既定では濃色モードになります。</span><span class="sxs-lookup"><span data-stu-id="f2011-833">Turn on black theme and dark mode will be on by default.</span></span>
2. <span data-ttu-id="f2011-834">(閲覧ウィンドウとリボンにある) [月/太陽] トグルを使用して、濃色モードでないユーザーにメッセージがどのように見えるかを表示します。</span><span class="sxs-lookup"><span data-stu-id="f2011-834">Use the moon/sun toggle (in the reading pane and in the ribbon) to preview what the message looks like for users not in dark mode</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="f2011-835">次の操作を試してみてください</span><span class="sxs-lookup"><span data-stu-id="f2011-835">Scenarios to Try</span></span>

1. <span data-ttu-id="f2011-836">濃色モードでメールを読みます。</span><span class="sxs-lookup"><span data-stu-id="f2011-836">Read emails in dark mode.</span></span> <span data-ttu-id="f2011-837">何も見えない場合は、[閲覧] ウィンドウの [太陽] トグルを使用して、背景を明るくします。</span><span class="sxs-lookup"><span data-stu-id="f2011-837">If you are unable to read something, use the sun toggle in the Reading Pane to switch to a light background.</span></span> 
2. <span data-ttu-id="f2011-838">[濃色] モードでメールを作成します。</span><span class="sxs-lookup"><span data-stu-id="f2011-838">Compose emails in dark mode.</span></span> <span data-ttu-id="f2011-839">リボンの [太陽] トグルを使用して、メッセージが明るい背景でどのように見えるかを確認します。</span><span class="sxs-lookup"><span data-stu-id="f2011-839">Preview what your message will look like with a light background by using the sun toggle in the ribbon.</span></span> 

<span data-ttu-id="f2011-840">正常に表示されないメールが見つかった場合は、(添付ファイルとして) OutlookDarkModeFail@service.microsoft.com に送信してください</span><span class="sxs-lookup"><span data-stu-id="f2011-840">If you encounter any emails that don't render properly, please send them (as an attachment) to OutlookDarkModeFail@service.microsoft.com</span></span>

#### <a name="get-location-suggestions"></a><span data-ttu-id="f2011-841">場所の候補を取得する</span><span class="sxs-lookup"><span data-stu-id="f2011-841">Get location suggestions</span></span>

<span data-ttu-id="f2011-842">入力を開始すると、Outlook で一致する場所が検索されます。</span><span class="sxs-lookup"><span data-stu-id="f2011-842">Start typing and Outlook will look for matching locations.</span></span>

<span data-ttu-id="f2011-843">予定や会議を作成するときは、[場所] フィールドに適用されます。</span><span class="sxs-lookup"><span data-stu-id="f2011-843">This applies to the Location field when creating Appointments and Meetings.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="f2011-844">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="f2011-844">Getting Started:</span></span>

- <span data-ttu-id="f2011-845">Outlook で O365 または Outlook.com の予定表に予定や会議を作成します。</span><span class="sxs-lookup"><span data-stu-id="f2011-845">Create an Appointment or Meeting on an O365 or Outlook.com calendar in Outlook.</span></span> 
- <span data-ttu-id="f2011-846">[場所] フィールドをクリックして、入力を開始します...。</span><span class="sxs-lookup"><span data-stu-id="f2011-846">Click into the Location field and start typing…</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="f2011-847">次の操作を試してみてください</span><span class="sxs-lookup"><span data-stu-id="f2011-847">Scenarios to Try</span></span>

<span data-ttu-id="f2011-848">会議に会議室を追加するときは、[会議室の検索] アドインやアドレス帳を使用するのではなく、[場所] フィールドをクリックします。</span><span class="sxs-lookup"><span data-stu-id="f2011-848">When adding a conference room to a meeting, click into Location field, rather than using Room Finder add-in or Address Book.</span></span>
<span data-ttu-id="f2011-849">レストラン、喫茶店、歯科医院といった公共の場所での予定がある場合は、新しいピッカーを使用して正確な位置を見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="f2011-849">For appointments at a physical place with a public location - like a restaurant, coffee shop, or even your dentist's office - try finding the exact location using the new picker.</span></span> <span data-ttu-id="f2011-850">こうすることで、外出するときに Outlook Mobile で通知を受け取ることができます。</span><span class="sxs-lookup"><span data-stu-id="f2011-850">This way, you'll be able to get notified on Outlook Mobile when it's time to leave.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="f2011-851">主な修正:</span><span class="sxs-lookup"><span data-stu-id="f2011-851">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="f2011-852">すべて</span><span class="sxs-lookup"><span data-stu-id="f2011-852">All</span></span>
- <span data-ttu-id="f2011-853">オフラインで [検索] ボックスが有効なままになる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-853">We fixed an issue which would keep the Search Box enabled while offline</span></span>

### <a name="word"></a><span data-ttu-id="f2011-854">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-854">Word</span></span> 
- <span data-ttu-id="f2011-855">キーボード フォーカスが表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-855">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>
- <span data-ttu-id="f2011-856">新しいドキュメントにテキストを貼り付けたときに、テキストが間違えて配置される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-856">We fixed an issue where text pasted into a new document could sometimes have the wrong text alignment</span></span>
- <span data-ttu-id="f2011-857">コンピューターを中断した後に、一部のユーザーが変更を保存できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-857">We fixed an issue which could prevent some users from saving changes after suspending their computer</span></span>
- <span data-ttu-id="f2011-858">特定の場合に、選択したページの代わりにドキュメント全体が印刷される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-858">We fixed an issue where in certain cases an entire document would be printed instead of the selected range</span></span>
- <span data-ttu-id="f2011-859">小さなディスプレイでコメントが読みにくくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-859">We fixed an issue which could make comments difficult to read on smaller displays</span></span>
- <span data-ttu-id="f2011-860">デバイスにキャプチャするときにクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-860">We fixed an issue which could cause a crash when capturing to a device</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-861">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-861">Excel</span></span>
- <span data-ttu-id="f2011-862">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-862">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-863">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-863">PowerPoint</span></span>
- <span data-ttu-id="f2011-864">キーボード フォーカスが表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-864">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-865">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-865">Outlook</span></span>
- <span data-ttu-id="f2011-866">有効ではないときにアドインが誤って有効になっていると表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-866">We fixed an issue which could incorrectly display an add-in as being enabled when it was not.</span></span>
- <span data-ttu-id="f2011-867">多数の保持ポリシーが表示されていない場合、ユーザーがすべての保持ポリシーを表示できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-867">We fixed an issue which would prevent a customer from viewing all retention policies if there were a large number of them</span></span>

### <a name="access"></a><span data-ttu-id="f2011-868">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-868">Access</span></span>
- <span data-ttu-id="f2011-869">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="f2011-869">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="f2011-870">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-870">Project</span></span>
- <span data-ttu-id="f2011-871">さまざまなパフォーマンスと安定性に関する修正</span><span class="sxs-lookup"><span data-stu-id="f2011-871">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-14-2019"></a><span data-ttu-id="f2011-872">2019 年 6 月 14 日</span><span class="sxs-lookup"><span data-stu-id="f2011-872">June 14, 2019</span></span>
<span data-ttu-id="f2011-873">バージョン 1907 (ビルド 11807.20000)</span><span class="sxs-lookup"><span data-stu-id="f2011-873">Version 1907 (build 11807.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="f2011-874">主な修正:</span><span class="sxs-lookup"><span data-stu-id="f2011-874">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="f2011-875">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-875">Word</span></span> 
- <span data-ttu-id="f2011-876">OneDrive に保存しているときにユーザーがサインインするのを妨げていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="f2011-876">We fixed an issue which could prevent a user from signing in when saving to OneDrive</span></span>
- <span data-ttu-id="f2011-877">アクセス制限モード中にユーザーによる SharePoint のプロパティの変更が妨げられていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="f2011-877">We fixed an issue where a user could be prevented from changing SharePoint properties while in restricted access mode</span></span>
- <span data-ttu-id="f2011-878">余白を調整しているときにヘッダーやフッターの内容が変更されてしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="f2011-878">We fixed an issue where header and footer content could change when adjusting margins</span></span>
- <span data-ttu-id="f2011-879">Web ビューに切り替えているときに書式設定が崩れてしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="f2011-879">We fixed an issue where formatting could break when switching to web view</span></span>
- <span data-ttu-id="f2011-880">SharePoint で開いたときにユーザーによるカスタム フィールドの使用を妨げていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="f2011-880">We fixed an issue which could prevent a user from using custom fields when opened from SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-881">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-881">Excel</span></span>
- <span data-ttu-id="f2011-882">フィルター処理された行を削除するときのパフォーマンスの問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="f2011-882">We fixed a performance issue when deleting rows of a filtered set</span></span>
- <span data-ttu-id="f2011-883">時々、保護ビューでマウスをちらつかせる原因になっていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="f2011-883">We fixed an issue which could sometimes cause the mouse to flicker in protected view</span></span>
- <span data-ttu-id="f2011-884">系列を削除しているときにクラッシュを引き起こしていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="f2011-884">We fixed an issue which could have caused a crash when deleting a series</span></span>
- <span data-ttu-id="f2011-885">利用できなかった場合に一部のユーザーがバージョン履歴を追加するオプションを使用していたところの問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="f2011-885">We fixed an issue where some users would have the option to add version history when that was not available</span></span>
- <span data-ttu-id="f2011-886">スプレッドシート比較ツールを使用しているときに例外を引き起こしていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="f2011-886">We fixed an issue which could have caused an exception when using the Spreadsheet Compare tool</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-887">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-887">PowerPoint</span></span>
- <span data-ttu-id="f2011-888">SharePoint へのリンクをクリックしたときにクラッシュを発生させていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="f2011-888">We fixed an issue where a crash could occur when clicking a link to SharePoint</span></span>
- <span data-ttu-id="f2011-889">ユーザーが Surface ペンを使用して入力しているのに、次のページに切り替わってしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="f2011-889">We fixed an issue which could switch the user to the next page while typing using a Surface Pen</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-890">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-890">Outlook</span></span>
- <span data-ttu-id="f2011-891">一部の宛先フィールドが通常より大きくなってしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="f2011-891">We fixed an issue where in some cases the To field was larger than normal</span></span>

### <a name="access"></a><span data-ttu-id="f2011-892">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-892">Access</span></span>
- <span data-ttu-id="f2011-893">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="f2011-893">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="f2011-894">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-894">Project</span></span>
- <span data-ttu-id="f2011-895">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-895">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-7-2019"></a><span data-ttu-id="f2011-896">2019 年 6 月 7 日</span><span class="sxs-lookup"><span data-stu-id="f2011-896">June 7, 2019</span></span>
<span data-ttu-id="f2011-897">バージョン 1907 (ビルド 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="f2011-897">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="f2011-898">主な修正:</span><span class="sxs-lookup"><span data-stu-id="f2011-898">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="f2011-899">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-899">Word</span></span> 
- <span data-ttu-id="f2011-900">オートコレクトが文の先頭文字を大文字にするように設定されていると Word がクラッシュする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-900">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="f2011-901">SharePoint でドキュメントを編集する際のパフォーマンスが向上しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-901">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="f2011-902">Adobe Illustrator で作成されたベクター ベースの画像が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-902">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-903">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-903">Excel</span></span>
- <span data-ttu-id="f2011-904">マクロを記録するときに、並べ替えフィールドが正しく設定されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-904">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="f2011-905">配列数式の計算中にハングまたはクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-905">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-906">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-906">PowerPoint</span></span>
- <span data-ttu-id="f2011-907">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-907">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-908">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-908">Outlook</span></span>
- <span data-ttu-id="f2011-909">インライン添付ファイルが誤って拡大縮小されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-909">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="f2011-910">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-910">Access</span></span>
- <span data-ttu-id="f2011-911">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="f2011-911">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="f2011-912">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-912">Project</span></span>
- <span data-ttu-id="f2011-913">固定期間のタイムシートが割り当て終了日を変更するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-913">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="f2011-914">以前のバージョンからプロジェクトを開くと、[完了率] の値が正しくない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-914">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="f2011-915">2019 年 5 月 31 日</span><span class="sxs-lookup"><span data-stu-id="f2011-915">May 31, 2019</span></span>
<span data-ttu-id="f2011-916">バージョン 1906 (ビルド 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="f2011-916">Version 1906 (build 11722.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="f2011-917">新機能:</span><span class="sxs-lookup"><span data-stu-id="f2011-917">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-918">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-918">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="f2011-919">サポートに問い合わせるためのダイアログがドッキング可能になり、右側に表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="f2011-919">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="f2011-920">サポートへの問い合わせに使用するダイアログが右側のウィンドウに表示され、最初からドッキングされたウィンドウとして表示されます。</span><span class="sxs-lookup"><span data-stu-id="f2011-920">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="f2011-921">メールでインクを使用する</span><span class="sxs-lookup"><span data-stu-id="f2011-921">Ink in Your Email!</span></span>

<span data-ttu-id="f2011-922">Outlook メールで画像を描画し、注釈を付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="f2011-922">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="f2011-923">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-923">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="f2011-924">ドキュメント リンクを Word で開く</span><span class="sxs-lookup"><span data-stu-id="f2011-924">Open document links in Word</span></span>

<span data-ttu-id="f2011-925">Office でドキュメント リンクをクリックしたときに既定で Word アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="f2011-925">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="f2011-926">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="f2011-926">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="f2011-927">詳しくは、以下を参照してください。https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="f2011-927">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="f2011-928">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="f2011-928">Getting Started:</span></span>

<span data-ttu-id="f2011-929">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="f2011-929">Feature will default to off.</span></span> <span data-ttu-id="f2011-930">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="f2011-930">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="f2011-931">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="f2011-931">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="f2011-932">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="f2011-932">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="f2011-933">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="f2011-933">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="f2011-934">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="f2011-934">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="f2011-935">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="f2011-935">Scenarios to Try:</span></span>

<span data-ttu-id="f2011-936">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている Word ドキュメントへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="f2011-936">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="f2011-937">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="f2011-937">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-938">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-938">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="f2011-939">プレゼンテーションへのリンクを PowerPoint で開く</span><span class="sxs-lookup"><span data-stu-id="f2011-939">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="f2011-940">Office でプレゼンテーションへのリンクをクリックしたときに既定で PowerPoint アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="f2011-940">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="f2011-941">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="f2011-941">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="f2011-942">詳しくは、以下を参照してください。https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="f2011-942">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="f2011-943">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="f2011-943">Getting Started:</span></span>

<span data-ttu-id="f2011-944">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="f2011-944">Feature will default to off.</span></span> <span data-ttu-id="f2011-945">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="f2011-945">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="f2011-946">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="f2011-946">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="f2011-947">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="f2011-947">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="f2011-948">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="f2011-948">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="f2011-949">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="f2011-949">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="f2011-950">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="f2011-950">Scenarios to Try:</span></span>

<span data-ttu-id="f2011-951">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている PowerPoint プレゼンテーションへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="f2011-951">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="f2011-952">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="f2011-952">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-953">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-953">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="f2011-954">ブックのリンクを Excel で開く</span><span class="sxs-lookup"><span data-stu-id="f2011-954">Open workbook links in Excel</span></span>

<span data-ttu-id="f2011-955">Office でブックのリンクをクリックしたときに既定で Excel アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="f2011-955">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="f2011-956">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="f2011-956">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="f2011-957">詳細については、以下を参照してください。https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="f2011-957">Learn More: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="f2011-958">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="f2011-958">Getting Started:</span></span>

<span data-ttu-id="f2011-959">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="f2011-959">Feature will default to off.</span></span> <span data-ttu-id="f2011-960">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="f2011-960">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="f2011-961">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="f2011-961">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="f2011-962">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="f2011-962">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="f2011-963">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="f2011-963">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="f2011-964">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="f2011-964">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="f2011-965">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="f2011-965">Scenarios to Try:</span></span>

<span data-ttu-id="f2011-966">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている Excel ブックへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="f2011-966">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="f2011-967">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="f2011-967">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="f2011-968">主な修正:</span><span class="sxs-lookup"><span data-stu-id="f2011-968">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="f2011-969">すべて</span><span class="sxs-lookup"><span data-stu-id="f2011-969">All</span></span>
- <span data-ttu-id="f2011-970">自動保存が無効になっている場合でも、ファイルが自動保存されてしまう場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-970">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="f2011-971">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-971">Word</span></span> 
- <span data-ttu-id="f2011-972">一部のユーザーがファイルを SharePoint に保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-972">We fixed an issue which may have prevented some users from saving to SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-973">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-973">Excel</span></span>
- <span data-ttu-id="f2011-974">無効なフィルターに間違ったアイコンが表示される場合がある問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="f2011-974">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-975">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-975">PowerPoint</span></span>
- <span data-ttu-id="f2011-976">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-976">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-977">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-977">Outlook</span></span>
- <span data-ttu-id="f2011-978">グループ スケジュール ビューで一部のユーザーがオフラインとして間違って表示される問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="f2011-978">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="f2011-979">末尾にスペースが挿入されている URL が SafeLink で解析できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-979">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="f2011-980">業務時間外に部屋が利用可能と表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-980">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="f2011-981">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-981">Access</span></span>
- <span data-ttu-id="f2011-982">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="f2011-982">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="f2011-983">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-983">Project</span></span>
- <span data-ttu-id="f2011-984">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-984">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="f2011-985">2019 年 5 月 24 日</span><span class="sxs-lookup"><span data-stu-id="f2011-985">May 24, 2019</span></span>
<span data-ttu-id="f2011-986">バージョン 1906 (ビルド 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="f2011-986">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="f2011-987">新機能:</span><span class="sxs-lookup"><span data-stu-id="f2011-987">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="f2011-988">ユーザー エクスペリエンスの更新</span><span class="sxs-lookup"><span data-stu-id="f2011-988">User Experience Updates</span></span>

<span data-ttu-id="f2011-989">近日公開となっていた更新プログラムが公開されました。この更新には、シンプル リボンおよびフォルダー ウィンドウ、メッセージ一覧、閲覧ウィンドウの外観の更新が含まれます。</span><span class="sxs-lookup"><span data-stu-id="f2011-989">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="f2011-990">主な修正:</span><span class="sxs-lookup"><span data-stu-id="f2011-990">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="f2011-991">すべて</span><span class="sxs-lookup"><span data-stu-id="f2011-991">All</span></span>

- <span data-ttu-id="f2011-992">チャットウィンドウが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-992">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="f2011-993">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-993">Word</span></span> 
- <span data-ttu-id="f2011-994">Word で文法エラーのテキストが誤って強調表示されることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-994">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-995">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-995">Excel</span></span>
- <span data-ttu-id="f2011-996">誤ったアイコンがグラフ要素に使用されているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-996">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="f2011-997">同じブックが既に開いているときに、不正なブックが VBA スクリプトでアクティブになるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-997">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-998">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-998">PowerPoint</span></span>
- <span data-ttu-id="f2011-999">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-999">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-1000">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-1000">Outlook</span></span>
- <span data-ttu-id="f2011-1001">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1001">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="f2011-1002">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-1002">Access</span></span>
- <span data-ttu-id="f2011-1003">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1003">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="f2011-1004">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-1004">Project</span></span>
- <span data-ttu-id="f2011-1005">タスクバーに切り替えた後、Project がクラッシュする可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1005">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="f2011-1006">2019 年 5 月 17 日</span><span class="sxs-lookup"><span data-stu-id="f2011-1006">May 17, 2019</span></span>
<span data-ttu-id="f2011-1007">バージョン 1906 (ビルド 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="f2011-1007">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="f2011-1008">新機能:</span><span class="sxs-lookup"><span data-stu-id="f2011-1008">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-1009">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-1009">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="f2011-1010">ユーザー エクスペリエンスのアップデート</span><span class="sxs-lookup"><span data-stu-id="f2011-1010">User Experience Updates</span></span>

<span data-ttu-id="f2011-1011">近日公開となっていた更新プログラムが公開されました。この更新には、シンプル リボンおよびフォルダー ウィンドウ、メッセージ一覧、閲覧ウィンドウの外観の更新が含まれます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1011">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="f2011-1012">利用するには:</span><span class="sxs-lookup"><span data-stu-id="f2011-1012">Getting Started:</span></span>

<span data-ttu-id="f2011-1013">これらの変更は、新しい既定の UI の一部になります。この新しい UI は、すべての運用環境ユーザー向けに [近日公開] スイッチで 12 月中旬以来提供されてきました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1013">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="f2011-1014">カスタマイズ可能なシンプル リボン</span><span class="sxs-lookup"><span data-stu-id="f2011-1014">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="f2011-1015">従来のビューとシンプルなビューの切り替えやコマンドの固定または固定解除を簡単にできます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1015">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="f2011-1016">利用するには:</span><span class="sxs-lookup"><span data-stu-id="f2011-1016">Getting Started:</span></span>

<span data-ttu-id="f2011-1017">シンプル リボンを使用するには、まず [近日公開] 機能をオンにし、リボンの山形マークをクリックして従来の複数行のリボンと新しい 1 行のシンプル リボンを切り替えます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1017">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="f2011-1018">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="f2011-1018">Scenarios to Try:</span></span>

<span data-ttu-id="f2011-1019">従来のリボンからシンプル リボンに切り替える</span><span class="sxs-lookup"><span data-stu-id="f2011-1019">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="f2011-1020">お気に入りの操作を選択する</span><span class="sxs-lookup"><span data-stu-id="f2011-1020">Pick your favorite action</span></span>

<span data-ttu-id="f2011-1021">[フラグ] 機能や [削除] 機能はお使いになられていないかもしれません。</span><span class="sxs-lookup"><span data-stu-id="f2011-1021">Don't use Flag and Delete?</span></span> <span data-ttu-id="f2011-1022">アーカイブまたは既読に​​しますか?</span><span class="sxs-lookup"><span data-stu-id="f2011-1022">How about Archive or Mark as Read?</span></span> <span data-ttu-id="f2011-1023">クイック操作メニューをカスタマイズしてよく使うコマンドを追加できます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1023">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="f2011-1024">利用するには:</span><span class="sxs-lookup"><span data-stu-id="f2011-1024">Getting Started:</span></span>

<span data-ttu-id="f2011-1025">希望のクイック操作を選ぶには、メッセージ一覧でメールを右クリックし、コンテキスト メニューを表示します。</span><span class="sxs-lookup"><span data-stu-id="f2011-1025">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="f2011-1026">次に、[クイック操作の設定] をクリックします。</span><span class="sxs-lookup"><span data-stu-id="f2011-1026">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="f2011-1027">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="f2011-1027">Scenarios to Try:</span></span>

<span data-ttu-id="f2011-1028">既定の設定を [フラグ] または [削除] から [アーカイブ]、[移動]、[既読にする]、または [なし] に変更すると、メッセージ一覧をすっきりした外観にできます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1028">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="f2011-1029">レイアウトの間隔を</span><span class="sxs-lookup"><span data-stu-id="f2011-1029">Relaxed or tighter layout?</span></span> <span data-ttu-id="f2011-1030">自由に選べます</span><span class="sxs-lookup"><span data-stu-id="f2011-1030">You choose</span></span>

<span data-ttu-id="f2011-1031">[狭い間隔を使用] オプションを使用すると、アイテム間のスペースを広く取るか、間隔の狭いレイアウトでより多くのアイテムを表示するかを選べます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1031">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="f2011-1032">利用するには:</span><span class="sxs-lookup"><span data-stu-id="f2011-1032">Getting Started:</span></span>

<span data-ttu-id="f2011-1033">従来のリボンの場合、[表示] タブの [メッセージ] グループで、[狭い間隔を使用] チェックボックスをオンにします。シンプル リボンの場合は、[現在のビュー] 設定で [狭い間隔を使用] を選択します。</span><span class="sxs-lookup"><span data-stu-id="f2011-1033">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="f2011-1034">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="f2011-1034">Scenarios to Try:</span></span>

<span data-ttu-id="f2011-1035">Outlook で、この設定をオフにした状態でメッセージをトリアージしたり作成したりしてみます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1035">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="f2011-1036">この機能をオンにすると、1 ページに収まるメッセージの数が増え、新規作成フォームのコントロールの表示がすっきりとします。</span><span class="sxs-lookup"><span data-stu-id="f2011-1036">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="f2011-1037">Onedrive 同期クライアントを使用する際の MRU エントリの重複を除去する</span><span class="sxs-lookup"><span data-stu-id="f2011-1037">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="f2011-1038">クラウド添付ファイルを使用すると、MRU エントリの重複を除去できるため、Onedrive の統合を効率化できます。クラウド添付ファイルを使用すれば、同期されたデータでコピーの添付をする動作が早くなります。</span><span class="sxs-lookup"><span data-stu-id="f2011-1038">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="f2011-1039">利用するには:</span><span class="sxs-lookup"><span data-stu-id="f2011-1039">Getting Started:</span></span>

<span data-ttu-id="f2011-1040">OneDrive 同期クライアントを使用している場合は、添付ファイル MRU に重複ファイルが表示されなくなります。</span><span class="sxs-lookup"><span data-stu-id="f2011-1040">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="f2011-1041">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="f2011-1041">Scenarios to Try:</span></span>

<span data-ttu-id="f2011-1042">OneDrive 同期クライアントを有効にして、Outlook デスクトップで [ファイルの添付] メニューを使用する</span><span class="sxs-lookup"><span data-stu-id="f2011-1042">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="f2011-1043">フォルダーを多数含むメールボックスでの共有フォルダーの同期が改善されました</span><span class="sxs-lookup"><span data-stu-id="f2011-1043">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="f2011-1044">長い間、Outlook での共有メールボックスの同期は、最大で 500 フォルダーに制限されてきました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1044">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="f2011-1045">この変更により Outlook の改善が行われ、同期をする際の 500 フォルダーの制限がなくなりました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1045">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="f2011-1046">利用するには:</span><span class="sxs-lookup"><span data-stu-id="f2011-1046">Getting Started:</span></span>

<span data-ttu-id="f2011-1047">メールボックスにフォルダーを 1000 個作成し、誰か他のユーザーにそのメールボックスへのアクセスを許可し、このユーザーの Outlook プロファイルを作成します。同期が正常に動作することを確認します。</span><span class="sxs-lookup"><span data-stu-id="f2011-1047">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="f2011-1048">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-1048">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="f2011-1049">少しだけ消す</span><span class="sxs-lookup"><span data-stu-id="f2011-1049">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="f2011-1050">利用するには:</span><span class="sxs-lookup"><span data-stu-id="f2011-1050">Getting Started:</span></span>

<span data-ttu-id="f2011-1051">[描画] タブに移動します。 [消しゴム] ドロップダウンを選択します。</span><span class="sxs-lookup"><span data-stu-id="f2011-1051">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="f2011-1052">[消しゴム (小)] または [消しゴム (中)] を選びます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1052">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="f2011-1053">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="f2011-1053">Scenarios to Try:</span></span>

<span data-ttu-id="f2011-1054">[描画] タブに移動します。ペンを選びます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1054">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="f2011-1055">インク ストロークを描きます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1055">Draw an ink stroke.</span></span> <span data-ttu-id="f2011-1056">[消しゴム] ドロップダウンを選択します。</span><span class="sxs-lookup"><span data-stu-id="f2011-1056">Select the Eraser dropdown.</span></span> <span data-ttu-id="f2011-1057">[消しゴム (小)] または [消しゴム (中)] を選びます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1057">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="f2011-1058">インク ストロークを少しだけ消してみます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1058">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="f2011-1059">主な修正:</span><span class="sxs-lookup"><span data-stu-id="f2011-1059">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="f2011-1060">すべて</span><span class="sxs-lookup"><span data-stu-id="f2011-1060">All</span></span> 
- <span data-ttu-id="f2011-1061">一部のユーザーが PDF として保存できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1061">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="f2011-1062">32 ビット システムでの大容量ファイルの保存に影響する場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1062">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="f2011-1063">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-1063">Word</span></span> 
- <span data-ttu-id="f2011-1064">音声入力機能の応答性が大幅に向上されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1064">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-1065">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-1065">Excel</span></span>
- <span data-ttu-id="f2011-1066">タッチ スクリーン デバイスでダブルクリック イベントが失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1066">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="f2011-1067">一部のユーザーが VBA マクロを編集できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1067">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="f2011-1068">スライサーを使用した際にパフォーマンスに影響する場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1068">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-1069">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-1069">PowerPoint</span></span>
- <span data-ttu-id="f2011-1070">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1070">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-1071">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-1071">Outlook</span></span>
- <span data-ttu-id="f2011-1072">選択したテンプレートとは異なるテンプレートが表示される場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1072">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="f2011-1073">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-1073">Access</span></span>
- <span data-ttu-id="f2011-1074">長いリッチ テキストの表示に Zoom Builder を使うと、読みづらくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1074">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="f2011-1075">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-1075">Project</span></span>
- <span data-ttu-id="f2011-1076">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1076">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="f2011-1077">2019 年 5 月 10日</span><span class="sxs-lookup"><span data-stu-id="f2011-1077">May 10, 2019</span></span>
<span data-ttu-id="f2011-1078">バージョン 1906 (ビルド 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="f2011-1078">Version 1906 (build 11702.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="f2011-1079">新機能:</span><span class="sxs-lookup"><span data-stu-id="f2011-1079">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-1080">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-1080">Outlook</span></span>

<span data-ttu-id="f2011-1081">**より多くのメッセージを画面に収める:** [表示] > [より狭い文字間隔を使用] の順に選択し、メッセージの間隔を調整します。</span><span class="sxs-lookup"><span data-stu-id="f2011-1081">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="f2011-1082">主な修正:</span><span class="sxs-lookup"><span data-stu-id="f2011-1082">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="f2011-1083">すべて</span><span class="sxs-lookup"><span data-stu-id="f2011-1083">All</span></span>
- <span data-ttu-id="f2011-1084">[名前を付けて保存] ダイアログボックスに誤ったパスが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1084">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="f2011-1085">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-1085">Word</span></span> 
- <span data-ttu-id="f2011-1086">操作アシストからの一部の選択が挿入されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1086">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-1087">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-1087">Excel</span></span>
- <span data-ttu-id="f2011-1088">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1088">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-1089">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-1089">PowerPoint</span></span>
- <span data-ttu-id="f2011-1090">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1090">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-1091">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-1091">Outlook</span></span>
- <span data-ttu-id="f2011-1092">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1092">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="f2011-1093">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-1093">Access</span></span>
- <span data-ttu-id="f2011-1094">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1094">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="f2011-1095">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-1095">Project</span></span>
- <span data-ttu-id="f2011-1096">タスク ID の確認に強調表示が必要となる可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1096">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="f2011-1097">2019 年 5 月 3日</span><span class="sxs-lookup"><span data-stu-id="f2011-1097">May 3, 2019</span></span>
<span data-ttu-id="f2011-1098">バージョン 1906 (ビルド 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="f2011-1098">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="f2011-1099">新機能:</span><span class="sxs-lookup"><span data-stu-id="f2011-1099">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-1100">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-1100">Outlook</span></span>

<span data-ttu-id="f2011-1101">**すべての暗号化オプションを1か所で:** [オプション] > [暗号化] の順に移動して、メール メッセージを保護する方法を選択します。</span><span class="sxs-lookup"><span data-stu-id="f2011-1101">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="f2011-1102">主な修正:</span><span class="sxs-lookup"><span data-stu-id="f2011-1102">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="f2011-1103">すべて</span><span class="sxs-lookup"><span data-stu-id="f2011-1103">All</span></span>
- <span data-ttu-id="f2011-1104">一部のユーザーが OneDrive for Business との同期で問題が発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1104">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="f2011-1105">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-1105">Word</span></span> 
- <span data-ttu-id="f2011-1106">Word の起動に時間がかかる場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1106">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-1107">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-1107">Excel</span></span>
- <span data-ttu-id="f2011-1108">新しいバージョンの Excel にアップグレードした後、ブックから外部リンクが削除されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1108">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="f2011-1109">一部のユーザーが新しいワークブックでセルを選択するのが困難な問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1109">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-1110">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-1110">PowerPoint</span></span>
- <span data-ttu-id="f2011-1111">図面をテキストに変換するときにフォントサイズが一致しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1111">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-1112">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-1112">Outlook</span></span>
- <span data-ttu-id="f2011-1113">a .VCF ファイルから連絡先を保存すると空のフィールドが発生する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1113">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="f2011-1114">送信されていても、送信トレイ フォルダーにメッセージが残ってしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1114">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="f2011-1115">DRM メッセージの表示中に Outlook がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1115">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="f2011-1116">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-1116">Access</span></span>
- <span data-ttu-id="f2011-1117">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1117">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="f2011-1118">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-1118">Project</span></span>
- <span data-ttu-id="f2011-1119">エディターが中国語から英語に切り替わる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1119">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="f2011-1120">マスター プロジェクトの公開コピーに未公開タスクが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1120">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="f2011-1121">2019 年 4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="f2011-1121">April 26, 2019</span></span>
<span data-ttu-id="f2011-1122">バージョン 1905 (ビルド 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="f2011-1122">Version 1905 (build 11617.20002)</span></span>

## <a name="new-features"></a><span data-ttu-id="f2011-1123">新機能</span><span class="sxs-lookup"><span data-stu-id="f2011-1123">New Features</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-1124">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-1124">Outlook</span></span>

<span data-ttu-id="f2011-1125">**共有カレンダーの更新がより速く**: Office 365 の共有カレンダーの場合、Outlook は REST API を使用してこれらのカレンダーを更新できます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1125">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="f2011-1126">共有カレンダーのより高速で信頼性の高い更新を行うには、プレビューを有効にします。</span><span class="sxs-lookup"><span data-stu-id="f2011-1126">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-1127">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-1127">Excel</span></span>

#### <a name="coauthoring-improvements"></a><span data-ttu-id="f2011-1128">共同編集の改善</span><span class="sxs-lookup"><span data-stu-id="f2011-1128">Coauthoring improvements</span></span>

<span data-ttu-id="f2011-1129">他のユーザーがリアルタイムでコンテンツの変更を受け取れるようにすることで、共同編集のエクスペリエンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1129">Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

### <a name="visio"></a><span data-ttu-id="f2011-1130">Visio</span><span class="sxs-lookup"><span data-stu-id="f2011-1130">Visio</span></span>

- <span data-ttu-id="f2011-1131">**Power BI から Visio ビジュアルをエクスポートする:** PDF、PowerPoint のファイルなどの Power BI レポートをエクスポートするときに、Power BI 用の Visio Visual が正しく表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1131">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="f2011-1132">主な修正:</span><span class="sxs-lookup"><span data-stu-id="f2011-1132">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="f2011-1133">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-1133">Word</span></span> 
- <span data-ttu-id="f2011-1134">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1134">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-1135">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-1135">Excel</span></span>
- <span data-ttu-id="f2011-1136">ソルバー マクロの実行が失敗するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1136">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="f2011-1137">Excel ファイルを SharePoint にインポートできないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1137">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-1138">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-1138">PowerPoint</span></span>
- <span data-ttu-id="f2011-1139">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1139">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-1140">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-1140">Outlook</span></span>
- <span data-ttu-id="f2011-1141">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1141">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="f2011-1142">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-1142">Access</span></span>
- <span data-ttu-id="f2011-1143">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1143">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="f2011-1144">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-1144">Project</span></span>
- <span data-ttu-id="f2011-1145">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1145">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="f2011-1146">2019 年 4 月 19 日</span><span class="sxs-lookup"><span data-stu-id="f2011-1146">April 19, 2019</span></span>
<span data-ttu-id="f2011-1147">バージョン 1905 (ビルド 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="f2011-1147">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="f2011-1148">新機能:</span><span class="sxs-lookup"><span data-stu-id="f2011-1148">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-1149">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-1149">Outlook</span></span>

<span data-ttu-id="f2011-1150">**人物を検索するときにメールの候補を取得する:** [検索] ボックスに人の名前を入力すると、最も関連性の高いメール メッセージが検索候補に含まれます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1150">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-1151">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-1151">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="f2011-1152">データ型を使用した塗り分けマップのエクスペリエンス向上</span><span class="sxs-lookup"><span data-stu-id="f2011-1152">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="f2011-1153">この機能は、Excel の地理データ型を使用して、塗り分けされたマップ グラフにプロットするユーザーのための機能強化です。</span><span class="sxs-lookup"><span data-stu-id="f2011-1153">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="f2011-1154">エンドユーザーにとっては、機能とエンドユーザーがマップする領域の精度向上とがより高度に統合されたことが利点です。</span><span class="sxs-lookup"><span data-stu-id="f2011-1154">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="f2011-1155">さらに、ポリゴンで都市をマッピングする機能も含まれてます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1155">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="f2011-1156">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="f2011-1156">Getting Started:</span></span>

- <span data-ttu-id="f2011-1157">この機能は、Excel 内の既存の機能を改善したものです。</span><span class="sxs-lookup"><span data-stu-id="f2011-1157">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="f2011-1158">この改善を使用するには、位置をリッチエンティティに変換し、塗り分けマップでプロットします。</span><span class="sxs-lookup"><span data-stu-id="f2011-1158">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="f2011-1159">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="f2011-1159">Scenarios to Try:</span></span>

- <span data-ttu-id="f2011-1160">ユーザーは、都市、州、都道府県、国、郵便番号のマッピングを試すことができます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1160">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="f2011-1161">主な修正:</span><span class="sxs-lookup"><span data-stu-id="f2011-1161">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="f2011-1162">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="f2011-1162">All Applications</span></span>
- <span data-ttu-id="f2011-1163">アプリケーションが起動したときに最初の実行ダイアログが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1163">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="f2011-1164">[名前を付けて保存] ダイアログボックス内の SharePoint リンクが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1164">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="f2011-1165">ユーザーが [今すぐ修復] ダイアログを誤って表示する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1165">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="f2011-1166">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-1166">Word</span></span> 
- <span data-ttu-id="f2011-1167">フォントの要求時に、一部のユーザーがメモリ不足またはディスク領域のエラーを受信する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1167">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="f2011-1168">[コメント] ウィンドウから切り替えたときにウィンドウがフォーカスを失う可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1168">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-1169">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-1169">Excel</span></span>
- <span data-ttu-id="f2011-1170">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1170">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-1171">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-1171">PowerPoint</span></span>
- <span data-ttu-id="f2011-1172">ブランド化された図形のサイズ変更ができない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1172">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="f2011-1173">保護ビューモードでファイルを開くときに PowerPoint がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1173">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-1174">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-1174">Outlook</span></span>
- <span data-ttu-id="f2011-1175">一部のユーザーが中国語の単語を選択できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1175">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="f2011-1176">有効期限が正しく計算されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1176">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="f2011-1177">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-1177">Access</span></span>
- <span data-ttu-id="f2011-1178">一部のユーザーがマクロ ビルダーを使用できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1178">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="f2011-1179">レポートを印刷すると最初のページしか印刷されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1179">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="f2011-1180">ハイパーリンクの上にカーソルを置くとアプリケーションがクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1180">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="f2011-1181">リレーションシップ ビューを使用すると、一部のアイテムが画面外に表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1181">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="f2011-1182">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-1182">Project</span></span>
- <span data-ttu-id="f2011-1183">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1183">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="f2011-1184">2019 年 4 月 12 日</span><span class="sxs-lookup"><span data-stu-id="f2011-1184">April 12, 2019</span></span>
<span data-ttu-id="f2011-1185">バージョン 1905 (ビルド 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="f2011-1185">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="f2011-1186">新機能:</span><span class="sxs-lookup"><span data-stu-id="f2011-1186">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="f2011-1187">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-1187">Access</span></span>

#### <a name="get-smart-with-microsoft-graph"></a><span data-ttu-id="f2011-1188">Microsoft Graph を使用してスマートに作業</span><span class="sxs-lookup"><span data-stu-id="f2011-1188">Get smart with Microsoft Graph</span></span>

<span data-ttu-id="f2011-1189">インテリジェントなテクノロジを使用して、インテリジェントなデータをインポートしたり、またはデータにリンクしたりして、デスクトップ データベースを作り変えましょう。</span><span class="sxs-lookup"><span data-stu-id="f2011-1189">Import or link to intelligent data and reinvent your desktop database with Intelligent Technology.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="f2011-1190">主な修正:</span><span class="sxs-lookup"><span data-stu-id="f2011-1190">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="f2011-1191">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="f2011-1191">All Applications</span></span>
 - <span data-ttu-id="f2011-1192">一部のユーザーがクラウドの場所にファイルを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1192">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="f2011-1193">リボンから間違ったウィンドウが開く問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1193">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="f2011-1194">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-1194">Word</span></span> 
- <span data-ttu-id="f2011-1195">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1195">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-1196">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-1196">Excel</span></span>
- <span data-ttu-id="f2011-1197">リンクされたデータ型を含まないブックであるにもかかわらず、リンクされたデータ型に対するエラーメッセージが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1197">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="f2011-1198">Word 文書内のリンクの URL がオンラインとローカルで表示したときに変更される可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1198">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-1199">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-1199">PowerPoint</span></span>
- <span data-ttu-id="f2011-1200">[アニメーション] タブで変更を元に戻すと、PowerPoint がクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1200">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-1201">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-1201">Outlook</span></span>
- <span data-ttu-id="f2011-1202">一部のユーザーがパブリック フォルダー内の連絡先の [メモ] フィールドを変更できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1202">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="f2011-1203">失効日と削除日の間に競合が発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1203">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="f2011-1204">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-1204">Access</span></span>
- <span data-ttu-id="f2011-1205">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1205">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="f2011-1206">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-1206">Project</span></span>
- <span data-ttu-id="f2011-1207">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1207">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="f2011-1208">2019年4月5日</span><span class="sxs-lookup"><span data-stu-id="f2011-1208">April 5, 2019</span></span>
<span data-ttu-id="f2011-1209">バージョン 1904 (ビルド 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="f2011-1209">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="f2011-1210">新機能:</span><span class="sxs-lookup"><span data-stu-id="f2011-1210">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-1211">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-1211">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="f2011-1212">Windows 用の Outlook: 優先受信トレイの設定を設定して共有します。</span><span class="sxs-lookup"><span data-stu-id="f2011-1212">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="f2011-1213">優先受信トレイの設定はクラウドに保存されるため、どのコンピューターで Web 上の Outlook for Windows と Outlook を使用しても同じように一貫したエクスペリエンスを楽しめます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1213">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="f2011-1214">利用するには:</span><span class="sxs-lookup"><span data-stu-id="f2011-1214">Getting Started:</span></span>

<span data-ttu-id="f2011-1215">[ファイル]、[オプション]、[全般] の順に移動すると、[Outlook の設定をクラウドに保存する] という新しい設定があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-1215">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="f2011-1216">ユーザーは、自分の優先受信トレイの設定を他の Outlook Desktop インストールおよび OWA に移動できるようにするには、このチェック ボックスをオンにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-1216">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="f2011-1217">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="f2011-1217">Scenarios to Try:</span></span>

<span data-ttu-id="f2011-1218">クラウド設定の設定を有効にしているコンピューターで優先受信トレイを変更します。</span><span class="sxs-lookup"><span data-stu-id="f2011-1218">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="f2011-1219">OWA に移動して、そこに適用されている設定も確認してください。</span><span class="sxs-lookup"><span data-stu-id="f2011-1219">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="f2011-1220">OWA で優先受信トレイを変更し、デスクトップ Outlook を起動して反映された優先順位を表示します。</span><span class="sxs-lookup"><span data-stu-id="f2011-1220">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="f2011-1221">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-1221">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="f2011-1222">学習ツール モードでは、より多くのページの色が追加でサポートされます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1222">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="f2011-1223">Word の学習ツールは、より多くのページ テーマ色を追加し、ページの背景色を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1223">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="f2011-1224">多くのユーザーがすべて白、またはすべて黒の背景だと閲覧が難しいという課題があったため、PC と Mac の Word で色の選択肢を拡大しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1224">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="f2011-1225">利用するには:</span><span class="sxs-lookup"><span data-stu-id="f2011-1225">Getting Started:</span></span>

<span data-ttu-id="f2011-1226">この操作を行うには、[表示] タブに移動し、[学習ツール]、[ページの色] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="f2011-1226">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="f2011-1227">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="f2011-1227">Scenarios to Try:</span></span>

<span data-ttu-id="f2011-1228">この操作を行うには、[表示] タブに移動し、[学習ツール]、[ページの色] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="f2011-1228">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-1229">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-1229">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="f2011-1230">3D アニメーション モデルで創造性を高める</span><span class="sxs-lookup"><span data-stu-id="f2011-1230">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="f2011-1231">Office では、アニメーションモデルをサポートするようになりました。エディターで再生するので、シートを活用することができます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1231">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="f2011-1232">利用するには:</span><span class="sxs-lookup"><span data-stu-id="f2011-1232">Getting Started:</span></span>

1. <span data-ttu-id="f2011-1233">Excel を開く</span><span class="sxs-lookup"><span data-stu-id="f2011-1233">Open Excel</span></span>
2. <span data-ttu-id="f2011-1234">3D アニメーション モデルを挿入します (まもなく Remix が公開されますが、今はここでアニメーション モデルにアクセスしてください: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="f2011-1234">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="f2011-1235">アニメーション モデルがエディターで再生されるようになります。</span><span class="sxs-lookup"><span data-stu-id="f2011-1235">The animated model will play in the editor!</span></span> <span data-ttu-id="f2011-1236">スライドショー モードも再生されるようになりますので、確認してください。</span><span class="sxs-lookup"><span data-stu-id="f2011-1236">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="f2011-1237">[3D 形式] リボンで、モデル内の他のアニメーション シーンを探索する</span><span class="sxs-lookup"><span data-stu-id="f2011-1237">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="f2011-1238">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="f2011-1238">Scenarios to Try:</span></span>

1. <span data-ttu-id="f2011-1239">アニメーション モデルを挿入し、エディターで再生します。</span><span class="sxs-lookup"><span data-stu-id="f2011-1239">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="f2011-1240">アニメーション化されたモデルで使用できるアニメーション シーンについては、シーン ギャラリー ([3D 書式] リボンから利用できます) を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f2011-1240">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="f2011-1241">リボン、フローティング ツール バーまたはスペースバーを介してアニメーションを簡単に再生および一時停止することができます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1241">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="f2011-1242">主な修正:</span><span class="sxs-lookup"><span data-stu-id="f2011-1242">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="f2011-1243">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="f2011-1243">All Applications</span></span>
- <span data-ttu-id="f2011-1244">Excel の間違ったアプリ アイコンがコンテキストメニューに表示されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1244">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="f2011-1245">アップデートをインストールした後に [ファイル メニュー] ボタンが消えてしまうことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1245">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="f2011-1246">ユーザー ライセンスに変更をおよぼす可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1246">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="f2011-1247">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-1247">Word</span></span> 
- <span data-ttu-id="f2011-1248">特定のズーム レベルでテキストが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1248">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-1249">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-1249">Excel</span></span>
- <span data-ttu-id="f2011-1250">編集後に、ブックを保存するかどうかを確認するメッセージが表示されない問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="f2011-1250">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="f2011-1251">ユーザーがブックを共有している場合に BeforeSave イベントが開始しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1251">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="f2011-1252">列のサイズを 6 ピクセル未満に変更すると誤ったエラーメッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1252">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="f2011-1253">Excel が Application.Visible フラグを無視する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1253">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="f2011-1254">トレースの矢印がアクティブでない固定ウィンドウに残る問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1254">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="f2011-1255">ブックを開くときに通貨の日付のセルの書式設定が変わることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1255">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="f2011-1256">ツールヒントが突然移動する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1256">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="f2011-1257">Power Query エディターのローカライズの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1257">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="f2011-1258">ブックを添付ファイルとしてメールで送信するときにブックが削除される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1258">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-1259">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-1259">PowerPoint</span></span>
- <span data-ttu-id="f2011-1260">図形のコピーに通常以上に時間がかかる問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="f2011-1260">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-1261">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-1261">Outlook</span></span>
- <span data-ttu-id="f2011-1262">描画ツールの使用中に Outlook がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1262">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="f2011-1263">HTML メールを作成する際のローカライズの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1263">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="f2011-1264">下側のウィンドウが選択しにくい問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1264">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="f2011-1265">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-1265">Access</span></span>
- <span data-ttu-id="f2011-1266">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1266">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="f2011-1267">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-1267">Project</span></span>
- <span data-ttu-id="f2011-1268">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1268">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="f2011-1269">2019 年 3 月 22 日</span><span class="sxs-lookup"><span data-stu-id="f2011-1269">March 22, 2019</span></span>
<span data-ttu-id="f2011-1270">バージョン 1904 (ビルド 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="f2011-1270">Version 1904 (build 11514.20004)</span></span>

## <a name="new-features"></a><span data-ttu-id="f2011-1271">新機能</span><span class="sxs-lookup"><span data-stu-id="f2011-1271">New Features</span></span>

- <span data-ttu-id="f2011-1272">**プライバシー制御**: 診断データとコネクテッド エクスペリエンス用に新しく更新されて、改善された制御。</span><span class="sxs-lookup"><span data-stu-id="f2011-1272">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> <span data-ttu-id="f2011-1273">詳細 <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span><span class="sxs-lookup"><span data-stu-id="f2011-1273">Learn more <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span></span>

- <span data-ttu-id="f2011-1274">**新しい外観を備えた Office のアイコン:** シンプルかつ高性能で、インテリジェントな Office のエクスペリエンスを反映するように、Office のアイコンがリニューアルされました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1274">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="f2011-1275">主な修正:</span><span class="sxs-lookup"><span data-stu-id="f2011-1275">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="f2011-1276">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-1276">Word</span></span> 
- <span data-ttu-id="f2011-1277">UI に常に "変更を確認しています" と表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1277">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-1278">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-1278">Excel</span></span>
- <span data-ttu-id="f2011-1279">ワークシートを移動した後にアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1279">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="f2011-1280">PDF 形式で保存した後にアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1280">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="f2011-1281">保存ダイアログで韓国語の文字を使用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1281">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-1282">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-1282">PowerPoint</span></span>
- <span data-ttu-id="f2011-1283">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1283">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-1284">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-1284">Outlook</span></span>
- <span data-ttu-id="f2011-1285">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1285">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="f2011-1286">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-1286">Access</span></span>
- <span data-ttu-id="f2011-1287">Access で余計なショートカットが作成されるという問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1287">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="f2011-1288">リンクされた SharePoint のデータが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1288">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="f2011-1289">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-1289">Project</span></span>
- <span data-ttu-id="f2011-1290">言語設定が中国語から英語に変わる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1290">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="f2011-1291">SharePoint に同期するとアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1291">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="f2011-1292">2019 年 3 月 15 日</span><span class="sxs-lookup"><span data-stu-id="f2011-1292">March 15, 2019</span></span>
<span data-ttu-id="f2011-1293">バージョン 1904 (ビルド 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="f2011-1293">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="f2011-1294">新機能:</span><span class="sxs-lookup"><span data-stu-id="f2011-1294">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="f2011-1295">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-1295">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="f2011-1296">フォーカス モード</span><span class="sxs-lookup"><span data-stu-id="f2011-1296">Focus Mode</span></span>

<span data-ttu-id="f2011-1297">気を散らさずに作業に集中するには、[表示]メニューの[フォーカス]に切り替えます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1297">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="f2011-1298">Office 365 サブスクリプションが必要です。</span><span class="sxs-lookup"><span data-stu-id="f2011-1298">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="f2011-1299">利用するには:</span><span class="sxs-lookup"><span data-stu-id="f2011-1299">Getting Started:</span></span>

<span data-ttu-id="f2011-1300">リボンのステータス バー [フォーカス] ボタンの [フォーカス] ボタンをタブして表示</span><span class="sxs-lookup"><span data-stu-id="f2011-1300">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="f2011-1301">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="f2011-1301">Scenarios to Try:</span></span>

<span data-ttu-id="f2011-1302">フォーカス モードにしてフォーカス エクスペリエンスを経験する</span><span class="sxs-lookup"><span data-stu-id="f2011-1302">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="f2011-1303">主な修正:</span><span class="sxs-lookup"><span data-stu-id="f2011-1303">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="f2011-1304">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-1304">Word</span></span> 
- <span data-ttu-id="f2011-1305">PDF として保存した文書の画像に間違った DPI が設定される問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1305">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-1306">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-1306">Excel</span></span>
- <span data-ttu-id="f2011-1307">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1307">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-1308">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-1308">PowerPoint</span></span>
- <span data-ttu-id="f2011-1309">コメント ウィンドウが正しく開閉しない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1309">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="f2011-1310">動画を削除するとアプリケーションがクラッシュする可能性がある問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1310">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="f2011-1311">アプリケーションの一部のインスタンスを起動できない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1311">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-1312">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-1312">Outlook</span></span>
- <span data-ttu-id="f2011-1313">日本語で表示するとき、開封確認が正しく表示されない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1313">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="f2011-1314">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-1314">Access</span></span>
- <span data-ttu-id="f2011-1315">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1315">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="f2011-1316">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-1316">Project</span></span>
- <span data-ttu-id="f2011-1317">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1317">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="f2011-1318">2019 年 3 月 8 日</span><span class="sxs-lookup"><span data-stu-id="f2011-1318">March 8, 2019</span></span> 
<span data-ttu-id="f2011-1319">バージョン 1903 (ビルド 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="f2011-1319">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="f2011-1320">新機能:</span><span class="sxs-lookup"><span data-stu-id="f2011-1320">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="f2011-1321">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-1321">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="f2011-1322">探している情報を Microsoft Search で検索する</span><span class="sxs-lookup"><span data-stu-id="f2011-1322">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="f2011-1323">Microsoft Search を使用して、作業を完了するのに必要なすべてのファイル、操作、連絡先、ヘルプを検索することができます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1323">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="f2011-1324">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="f2011-1324">Getting Started:</span></span>

- <span data-ttu-id="f2011-1325">この機能は、ヘッダーの UI の上部に目立つように表示されています。</span><span class="sxs-lookup"><span data-stu-id="f2011-1325">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="f2011-1326">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="f2011-1326">Scenarios to Try:</span></span>

- <span data-ttu-id="f2011-1327">大学、最近使用したドキュメント、最もよく使用するリボン コマンドなどを検索する</span><span class="sxs-lookup"><span data-stu-id="f2011-1327">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="f2011-1328">トピックや話題を検索して、その詳細情報を取得する</span><span class="sxs-lookup"><span data-stu-id="f2011-1328">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="f2011-1329">共同編集</span><span class="sxs-lookup"><span data-stu-id="f2011-1329">CoAuthoring</span></span>

<span data-ttu-id="f2011-1330">マクロの文書を編集できない状況にうんざりしていませんか?</span><span class="sxs-lookup"><span data-stu-id="f2011-1330">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="f2011-1331">これで OneDrive for Business 上の docm ファイルで複数の作成者による同時編集が可能になります。</span><span class="sxs-lookup"><span data-stu-id="f2011-1331">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="f2011-1332">利用するには:</span><span class="sxs-lookup"><span data-stu-id="f2011-1332">Getting Started:</span></span>

<span data-ttu-id="f2011-1333">ユーザーは、この機能にアクセスするために UI のボタンを押す必要はありません。</span><span class="sxs-lookup"><span data-stu-id="f2011-1333">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="f2011-1334">OneDrive for Business の docm ファイルでは、既定で有効になっています。</span><span class="sxs-lookup"><span data-stu-id="f2011-1334">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="f2011-1335">したがって、試すには、ユーザーが docm ファイルを OneDrive for Business に保存しておく必要があります。</span><span class="sxs-lookup"><span data-stu-id="f2011-1335">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="f2011-1336">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="f2011-1336">Scenarios to Try:</span></span>

<span data-ttu-id="f2011-1337">OneDrive for Business で docm ファイルを作成し、同僚と共有して共同作業を行います。</span><span class="sxs-lookup"><span data-stu-id="f2011-1337">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="f2011-1338">主な修正:</span><span class="sxs-lookup"><span data-stu-id="f2011-1338">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="f2011-1339">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-1339">Word</span></span> 
- <span data-ttu-id="f2011-1340">オプションの表示中に ‘Esc’ キーを押すと発生するクラッシュの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1340">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="f2011-1341">コメントに返信するときにクラッシュが発生するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1341">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="f2011-1342">Word から PowerPoint Online へのコピーと貼り付けで発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1342">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-1343">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-1343">Excel</span></span>
- <span data-ttu-id="f2011-1344">保護されたドキュメントや編集可能なドキュメントを開いているときに Excel でセルをコピーすると CPU 使用率が高くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1344">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-1345">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-1345">PowerPoint</span></span>
- <span data-ttu-id="f2011-1346">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1346">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-1347">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-1347">Outlook</span></span>
- <span data-ttu-id="f2011-1348">Outlook Search が選択した日付の並べ替えを使用しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1348">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="f2011-1349">"このタスクを開く" ワークフロー リボンのボタンが特定のメールで応答しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1349">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="f2011-1350">ユーザーが Outlook の会議室の検索で空いている会議室を選択した後、社内の会議室がクリアされなくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1350">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="f2011-1351">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-1351">Access</span></span>
- <span data-ttu-id="f2011-1352">ダーク テーマで白い背景に白いテキストが表示されていた、保存済みのインポート/エクスポートのダイアログを修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1352">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="f2011-1353">表のデザインのテキストボックスに [Yes/No] フィールドの DisplayControl プロパティを設定できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1353">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="f2011-1354">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-1354">Project</span></span>
- <span data-ttu-id="f2011-1355">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1355">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="f2011-1356">2019 年 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="f2011-1356">March 1, 2019</span></span> 
<span data-ttu-id="f2011-1357">バージョン 1903 (ビルド 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="f2011-1357">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="f2011-1358">新機能</span><span class="sxs-lookup"><span data-stu-id="f2011-1358">What's New</span></span>

### <a name="word"></a><span data-ttu-id="f2011-1359">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-1359">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="f2011-1360">色の変更履歴、コメントとリアルタイムの共同作業の同期</span><span class="sxs-lookup"><span data-stu-id="f2011-1360">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="f2011-1361">当社の製品での、コメント、変更履歴と共同作業者のカーソルが同じ色で表示されることについての修正箇所を確認しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1361">Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="f2011-1362">利用するには:</span><span class="sxs-lookup"><span data-stu-id="f2011-1362">Getting Started:</span></span>

<span data-ttu-id="f2011-1363">他のユーザーが開いている SharePoint または OneDrive のドキュメントを開きます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1363">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="f2011-1364">ユーザーの変更履歴とコメントの色が、ユーザーのカーソルの色と一致することを確認します。</span><span class="sxs-lookup"><span data-stu-id="f2011-1364">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="f2011-1365">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="f2011-1365">Scenarios to Try:</span></span>

<span data-ttu-id="f2011-1366">他のユーザーが開いている SharePoint または OneDrive のドキュメントを開きます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1366">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="f2011-1367">ユーザーの変更履歴とコメントの色が、ユーザーのカーソルの色と一致することを確認します。</span><span class="sxs-lookup"><span data-stu-id="f2011-1367">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="f2011-1368">主な修正:</span><span class="sxs-lookup"><span data-stu-id="f2011-1368">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="f2011-1369">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-1369">Word</span></span> 
- <span data-ttu-id="f2011-1370">オプションの表示中に ‘Esc’ キーを押すと発生するクラッシュの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1370">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="f2011-1371">Word から PowerPoint Online へのコピーと貼り付けで発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1371">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-1372">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-1372">Excel</span></span>
- <span data-ttu-id="f2011-1373">保護されたドキュメントや編集可能なドキュメントを開いているときに Excel でセルをコピーすると CPU 使用率が高くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1373">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-1374">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-1374">PowerPoint</span></span>
- <span data-ttu-id="f2011-1375">PowerPoint で @メンションを使用するときのスライド イメージのサイズに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1375">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-1376">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-1376">Outlook</span></span>
- <span data-ttu-id="f2011-1377">Outlook Search が選択した日付の並べ替えを使用しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1377">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="f2011-1378">"このタスクを開く" ワークフロー リボンのボタンが特定のメールで応答しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1378">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="f2011-1379">ユーザーが Outlook の会議室の検索で空いている会議室を選択した後、社内の会議室がクリアされなくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1379">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="f2011-1380">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-1380">Access</span></span>
- <span data-ttu-id="f2011-1381">テーブルとデータソースの再リンクを確認するときに表示されるメッセージを更新しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1381">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="f2011-1382">ダーク テーマで白い背景に白いテキストが表示されていた、保存済みのインポート/エクスポートのダイアログを修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1382">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="f2011-1383">表のデザインのテキストボックスに [Yes/No] フィールドの表示コントロール プロパティを設定できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1383">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="f2011-1384">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-1384">Project</span></span>
- <span data-ttu-id="f2011-1385">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1385">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="f2011-1386">2019 年 2 月 15 日</span><span class="sxs-lookup"><span data-stu-id="f2011-1386">February 15, 2019</span></span> 
<span data-ttu-id="f2011-1387">バージョン 1903 (ビルド 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="f2011-1387">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="f2011-1388">新機能:</span><span class="sxs-lookup"><span data-stu-id="f2011-1388">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-1389">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-1389">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="f2011-1390">画面切り替え効果の機能強化 - 名前で変形</span><span class="sxs-lookup"><span data-stu-id="f2011-1390">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="f2011-1391">変形する図形を指定します</span><span class="sxs-lookup"><span data-stu-id="f2011-1391">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="f2011-1392">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="f2011-1392">Getting Started:</span></span>

- <span data-ttu-id="f2011-1393">[変形] で 2 つのオブジェクトを同じオブジェクトとして扱うために、[選択] ウィンドウを使って図形の名前を変更することができます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1393">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="f2011-1394">[変形] で名前を使って既定のマッチング動作を上書きするには、</span><span class="sxs-lookup"><span data-stu-id="f2011-1394">The name must be prefaced with “!!”</span></span> <span data-ttu-id="f2011-1395">名前の前に "!!" (2 つの感嘆符) を付ける必要があります (例: "!!Name")。</span><span class="sxs-lookup"><span data-stu-id="f2011-1395">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="f2011-1396">名前の先頭に "!!" が付いていない図形の名前変更を続行できます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1396">Users can continue to rename shapes with any name that doesn’t start with “!!”</span></span> <span data-ttu-id="f2011-1397">[変形] の動作が変更されることを気にする必要はありません</span><span class="sxs-lookup"><span data-stu-id="f2011-1397">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="f2011-1398">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="f2011-1398">Scenarios to Try:</span></span>

- <span data-ttu-id="f2011-1399">スライドに図形 (たとえば、四角形) を挿入します</span><span class="sxs-lookup"><span data-stu-id="f2011-1399">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="f2011-1400">新しいスライドを作成します</span><span class="sxs-lookup"><span data-stu-id="f2011-1400">Create a new slide</span></span>
- <span data-ttu-id="f2011-1401">2 枚目のスライドに別の図形 (たとえば、三角形) を挿入します</span><span class="sxs-lookup"><span data-stu-id="f2011-1401">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="f2011-1402">[オブジェクトの選択と表示] でスライド 1 の四角形の名前を "!!shape" に変更し、スライド 2 の三角形の名前を "!!shape" に変更します</span><span class="sxs-lookup"><span data-stu-id="f2011-1402">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="f2011-1403">2 枚目のスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="f2011-1403">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="f2011-1404">画面切り替え効果の機能強化 - SmartArt</span><span class="sxs-lookup"><span data-stu-id="f2011-1404">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="f2011-1405">SmartArt の変形をより滑らかに切り替え</span><span class="sxs-lookup"><span data-stu-id="f2011-1405">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="f2011-1406">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="f2011-1406">Getting Started:</span></span>

<span data-ttu-id="f2011-1407">SmartArt と同様の方法で変形を使用します</span><span class="sxs-lookup"><span data-stu-id="f2011-1407">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="f2011-1408">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="f2011-1408">Scenarios to Try:</span></span>

- <span data-ttu-id="f2011-1409">スライドに SmartArt を挿入します</span><span class="sxs-lookup"><span data-stu-id="f2011-1409">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="f2011-1410">スライドを複製します</span><span class="sxs-lookup"><span data-stu-id="f2011-1410">Duplicate the Slide</span></span>
- <span data-ttu-id="f2011-1411">複製されたスライド上で SmartArt のサイズ変更/変更/移動を行います</span><span class="sxs-lookup"><span data-stu-id="f2011-1411">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="f2011-1412">複製されたスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="f2011-1412">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="f2011-1413">画面切り替え効果の機能強化 - 表</span><span class="sxs-lookup"><span data-stu-id="f2011-1413">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="f2011-1414">表の変形をより滑らかに切り替え</span><span class="sxs-lookup"><span data-stu-id="f2011-1414">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="f2011-1415">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="f2011-1415">Getting Started:</span></span>
<span data-ttu-id="f2011-1416">表と同様の方法で変形を使用します</span><span class="sxs-lookup"><span data-stu-id="f2011-1416">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="f2011-1417">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="f2011-1417">Scenarios to Try:</span></span>

- <span data-ttu-id="f2011-1418">スライドに表を挿入します</span><span class="sxs-lookup"><span data-stu-id="f2011-1418">Insert a Table in a slide</span></span>
- <span data-ttu-id="f2011-1419">スライドを複製します</span><span class="sxs-lookup"><span data-stu-id="f2011-1419">Duplicate the slide</span></span>
- <span data-ttu-id="f2011-1420">複製されたスライド上で表のサイズ変更/変更/移動を行います</span><span class="sxs-lookup"><span data-stu-id="f2011-1420">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="f2011-1421">複製されたスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="f2011-1421">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="f2011-1422">Word、Excel、PowerPoint、OneNote、Access、Project、Publisher、Visio</span><span class="sxs-lookup"><span data-stu-id="f2011-1422">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="f2011-1423">アカウントをシームレスに切り替える</span><span class="sxs-lookup"><span data-stu-id="f2011-1423">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="f2011-1424">新しいアカウント マネージャーでは、仕事用アカウントと個人用アカウントのすべてが 1 か所に表示されます。また、アカウントを自由に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="f2011-1424">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="f2011-1425">この更新されたエクスペリエンスでは、ログイン方法がわかりやすくなりました。また、先にサインアウトしたり複雑なダイアログを操作したりする必要なく、仕事用アカウントと個人用アカウントを切り替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1425">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="f2011-1427">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="f2011-1427">Scenarios to Try:</span></span>
- <span data-ttu-id="f2011-1428">アカウントを切り替えます</span><span class="sxs-lookup"><span data-stu-id="f2011-1428">Switch between accounts</span></span>
- <span data-ttu-id="f2011-1429">新しいアカウントを追加します [注: [ファイル]、[アカウント]、[接続済みサービス] の順に移動してから、仕事用アカウントに接続されている個人用サービス (またはその逆) を削除することができます]</span><span class="sxs-lookup"><span data-stu-id="f2011-1429">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="f2011-1430">アカウントからサインアウトします</span><span class="sxs-lookup"><span data-stu-id="f2011-1430">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="f2011-1431">主な修正:</span><span class="sxs-lookup"><span data-stu-id="f2011-1431">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="f2011-1432">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-1432">Word</span></span> 
- <span data-ttu-id="f2011-1433">表と画像のコンテキスト プレビューに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1433">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-1434">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-1434">Excel</span></span>
- <span data-ttu-id="f2011-1435">[黒] のテーマでオートフィルターの [検索] フィールドのテキストが白くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1435">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="f2011-1436">新しい Office アドインの同意の UI に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1436">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-1437">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-1437">PowerPoint</span></span>
- <span data-ttu-id="f2011-1438">ノート PC またはタブレットでスライドショーを表示すると、表示が自動的に拡大される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f2011-1438">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-1439">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-1439">Outlook</span></span>
- <span data-ttu-id="f2011-1440">[OneNote に送る] ボタンの表示に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1440">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="f2011-1441">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-1441">Access</span></span>
- <span data-ttu-id="f2011-1442">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1442">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="f2011-1443">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-1443">Project</span></span>
- <span data-ttu-id="f2011-1444">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1444">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="f2011-1445">2019 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="f2011-1445">February 11, 2019</span></span>
<span data-ttu-id="f2011-1446">バージョン 1903 (ビルド 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="f2011-1446">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="f2011-1447">主な修正:</span><span class="sxs-lookup"><span data-stu-id="f2011-1447">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="f2011-1448">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-1448">Word</span></span> 
- <span data-ttu-id="f2011-1449">一部のカスタマイズされたスタイルを Word Online に適用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1449">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="f2011-1450">Word のリッチ オブジェクトでのコンテキスト プレビューに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1450">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="f2011-1451">リストを貼り付けると Word がクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1451">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-1452">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-1452">Excel</span></span>
- <span data-ttu-id="f2011-1453">通貨記号がない場合に、数値の書式の後ろに追加されるスペースが表示されない問題を修正しました特殊文字</span><span class="sxs-lookup"><span data-stu-id="f2011-1453">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="f2011-1454">株価の自動検出に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1454">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-1455">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-1455">PowerPoint</span></span>
- <span data-ttu-id="f2011-1456">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1456">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-1457">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-1457">Outlook</span></span>
- <span data-ttu-id="f2011-1458">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1458">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="f2011-1459">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-1459">Access</span></span>
- <span data-ttu-id="f2011-1460">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1460">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="f2011-1461">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-1461">Project</span></span>
- <span data-ttu-id="f2011-1462">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1462">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="f2011-1463">2019 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="f2011-1463">February 1, 2019</span></span> 
<span data-ttu-id="f2011-1464">バージョン 1902 (ビルド 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="f2011-1464">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="f2011-1465">主な修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1465">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="f2011-1466">Word</span><span class="sxs-lookup"><span data-stu-id="f2011-1466">Word</span></span> 
- <span data-ttu-id="f2011-1467">埋め込まれた Excel の表のセルのサイズ変更に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1467">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="f2011-1468">描画キャンバス内の図形のコピー/貼り付けの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1468">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="f2011-1469">Excel</span><span class="sxs-lookup"><span data-stu-id="f2011-1469">Excel</span></span>
- <span data-ttu-id="f2011-1470">Excel Web App からファイルを開く際の問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1470">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="f2011-1471">CSV ファイルを .XLSX として保存する際にファイル名のサイズが原因で失敗する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1471">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="f2011-1472">コンテキスト メニューのオプションの表示に関してコンテキスト メニューを修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1472">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f2011-1473">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f2011-1473">PowerPoint</span></span>
- <span data-ttu-id="f2011-1474">角かっこを入力するためにユーザーがキーボード ショートカット Ctrl+Alt+7 および Ctrl+Alt+8 を使用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1474">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="f2011-1475">ローカル ビデオを PowerPoint に挿入すると C ドライブのディスク領域が減ってしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1475">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="f2011-1476">一部のユーザーに表示されていなかった [Microsoft Stream に公開する] ボタンを修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1476">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="f2011-1477">Outlook</span><span class="sxs-lookup"><span data-stu-id="f2011-1477">Outlook</span></span>
- <span data-ttu-id="f2011-1478">カレンダーのタスク ビューでタスクの件名が正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1478">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="f2011-1479">Access</span><span class="sxs-lookup"><span data-stu-id="f2011-1479">Access</span></span>
- <span data-ttu-id="f2011-1480">グラフのスケーリングの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="f2011-1480">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="f2011-1481">Project</span><span class="sxs-lookup"><span data-stu-id="f2011-1481">Project</span></span>
- <span data-ttu-id="f2011-1482">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="f2011-1482">Various performance and stability fixes</span></span>
