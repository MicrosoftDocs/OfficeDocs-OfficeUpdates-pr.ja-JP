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
ms.openlocfilehash: 81474ca6ba2e2cce145dfc8b80dff8c8b2857541
ms.sourcegitcommit: e7eb58247abb6fc7f7082e98ae4847344f35a69e
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 11/02/2019
ms.locfileid: "37931911"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="0d5f7-103">Office Insider のリリース ノート</span><span class="sxs-lookup"><span data-stu-id="0d5f7-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="0d5f7-104">この記事には、Windows デスクトップ向け Word、Excel、PowerPoint、Outlook、Access、Project の Insider ビルドのリリース ノートが含まれています。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="0d5f7-105">Microsoft では、毎週、皆様にお知らせしたい魅力的な新機能、重要な修正プログラム、重大な問題に関する情報を提供しています。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="0d5f7-106">多くの場合、機能 (場合によっては修正プログラムも) は、特定の期間にわたって Insider にロールアウトされます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="0d5f7-107">これにより、Microsoft では、より広範な対象ユーザーに機能をリリースする前に、作業がスムーズに行われていることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="0d5f7-108">したがって、下記のものが表示されない場合でも、心配する必要はなく、いずれは表示されます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="0d5f7-109">リリース ノートは毎週投稿され、場合により複数のビルドのコンパイルになります</span><span class="sxs-lookup"><span data-stu-id="0d5f7-109">Release notes are posted weekly and may be a compilation of multiple builds</span></span>
> - <span data-ttu-id="0d5f7-110">リリースノートの発行日は実際のビルドのリリース日と一致しない場合があります</span><span class="sxs-lookup"><span data-stu-id="0d5f7-110">The release notes publication date may not match the actual build release date</span></span>

 > [!NOTE]
> - <span data-ttu-id="0d5f7-111">Microsoft Teams に関連する既存の Office 365 ProPlus のインストール - 6 月の下旬から、これらの更新プログラムのインストール時に、Microsoft Teams が既存の Office 365 ProPlus (Office 365 Business) のインストールの中に含められます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-111">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="0d5f7-112">Teams が追加される日にちは、使用している更新プログラム チャネルによって異なります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-112">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="0d5f7-113">追加情報については、「[Office 365 ProPlus と同時に Microsoft Teams を展開する](https://docs.microsoft.com/ja-JP/deployoffice/teams-install)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-113">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/ja-JP/deployoffice/teams-install) for additional information.</span></span>

[//]: # (削除しないでください)


## <a name="version-1911-november-01"></a><span data-ttu-id="0d5f7-115">バージョン 1911: 11 月 1 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-115">Version 1911: November 01</span></span>
<span data-ttu-id="0d5f7-116">*バージョン 1911 (ビルド 12228.20020)*</span><span class="sxs-lookup"><span data-stu-id="0d5f7-116">*Version 1911 (Build 12215.20006)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="0d5f7-118">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="0d5f7-118">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="0d5f7-119">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-119">Excel</span></span>

- <span data-ttu-id="0d5f7-120">**SVG オブジェクトにコンテキストを取り入れる:** 地図やグラフ、その他の SVG ベクターを Office で変換する場合、それらのオブジェクトの中にテキストを保持できるようになりました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-120">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office</span></span>

- <span data-ttu-id="0d5f7-121">**Surface ペンを使用するときにペンのオプションを確認する:** Word、Excel、PowerPoint で Surface ペンを初めて使用するときに、ペンの色を簡単に選べる [描画] タブがアクティブになります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-121">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-122">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-122">PowerPoint</span></span>

- <span data-ttu-id="0d5f7-123">**SVG オブジェクトにコンテキストを取り入れる:** 地図やグラフ、その他の SVG ベクターを Office で変換する場合、それらのオブジェクトの中にテキストを保持できるようになりました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-123">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office</span></span>

- <span data-ttu-id="0d5f7-124">**Surface ペンを使用するときにペンのオプションを確認する:** Word、Excel、PowerPoint で Surface ペンを初めて使用するときに、ペンの色を簡単に選べる [描画] タブがアクティブになります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-124">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="visio"></a><span data-ttu-id="0d5f7-125">Visio</span><span class="sxs-lookup"><span data-stu-id="0d5f7-125">Visio</span></span>

- <span data-ttu-id="0d5f7-126">**Excel で洗練された Visio 図を作成する:** すばやく簡単に、データを Excel 内の洗練された Visio 図に可視化します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-126">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> [<span data-ttu-id="0d5f7-127">詳細情報</span><span class="sxs-lookup"><span data-stu-id="0d5f7-127">Learn more</span></span>](https://support.office.com/ja-JP/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="0d5f7-128">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-128">Word</span></span>

- <span data-ttu-id="0d5f7-129">**Surface ペンを使用するときにペンのオプションを確認する:** Word、Excel、PowerPoint で Surface ペンを初めて使用するときに、ペンの色を簡単に選べる [描画] タブがアクティブになります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-129">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

- <span data-ttu-id="0d5f7-130">**共同編集の改善:** コンテンツの変更をリアルタイムでユーザーが受け取れるようにすることで、共同編集のエクスペリエンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-130">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="0d5f7-131">**他のユーザーがすばやく変更を確認:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-131">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="0d5f7-134">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="0d5f7-134">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="0d5f7-135">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-135">Excel</span></span>

- <div><span data-ttu-id="0d5f7-136"><span>信頼されていないネットワーク共有から保護されたファイルを編集すると、Excel がクラッシュすることがある問題を解決しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-136"><span>Resolved an issue where Excel may crash when editing a protected file from an untrusted network share</span></span></span></div>


- <div><span data-ttu-id="0d5f7-137">別のシートのデータを参照しているスパークラインを含むシートを削除すると、再びそのファイルを開いた時に破損したファイルとして識別されるという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-137">Resolved an issue where deleting sheets containing sparklines referencing data on another sheet could cause the file to be identified as corrupted when re-opened.</span></span></div>


- <div><span data-ttu-id="0d5f7-138">SQL 表形式サーバーのクエリのピボットテーブルの残りの部分と一緒にレポート フィルターを変換すると、正しい結果が返されないことがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-138">Resolved an Issue where you may get incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span></span></div>


- <div><span data-ttu-id="0d5f7-139"><span>ナレーターと拡大鏡を同時に使用すると、クラッシュする場合がある問題</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-139"><span>Using Narrator and Magnifier at the same time may result in a crash</span></span></span></div>


- <div><span data-ttu-id="0d5f7-140"><span>ナレーターと拡大鏡を同時に使用すると、クラッシュする場合がある問題</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-140"><span>Using Narrator and Magnifier at the same time may result in a crash</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="0d5f7-141">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-141">Outlook</span></span>

- <div><span data-ttu-id="0d5f7-142">メールを転送すると、埋め込み画像がなくなる場合がある問題</span><span class="sxs-lookup"><span data-stu-id="0d5f7-142">A forwarded e-mail may be missing embedded images</span></span></div>


- <div><span data-ttu-id="0d5f7-143"><span>会議室の検索ツールで、使用可能な会議室が&quot;なし&quot;と表示される場合がある問題</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-143"><span>Room Finder tool may be displaying &quot;None&quot; for available rooms</span></span></span></div>


- <div><span data-ttu-id="0d5f7-144"><span>厳しいテナント制限がある Outlook プロファイルをユーザーが作成できない場合がある問題</span><span class="sxs-lookup"><span data-stu-id="0d5f7-144"><span>Users may not be able to create Outlook profiles with strict tenant restriction</span></span></div></span>


### <a name="powerpoint"></a><span data-ttu-id="0d5f7-145">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-145">PowerPoint</span></span>

- <div><span data-ttu-id="0d5f7-146"><span>ナレーターと拡大鏡を同時に使用すると、クラッシュする場合がある問題</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-146"><span>Using Narrator and Magnifier at the same time may result in a crash</span></span></span></div>


### <a name="project"></a><span data-ttu-id="0d5f7-147">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-147">Project</span></span>

- <div><span data-ttu-id="0d5f7-148"><span>ユーザーがタスクを完了としてマークすることができず、99% に設定される問題</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-148"><span>User is unable to mark a task as complete, and it gets set to 99%</span></span></span></div>


- <div><span data-ttu-id="0d5f7-149">平準化によって割り当て超過が解決されない問題</span><span class="sxs-lookup"><span data-stu-id="0d5f7-149">Overallocations are not resolved by leveling</span></span></div>


### <a name="word"></a><span data-ttu-id="0d5f7-150">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-150">Word</span></span>

- <div><span data-ttu-id="0d5f7-151"><span>ナレーターと拡大鏡を同時に使用すると、クラッシュする場合がある問題</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-151"><span>Using Narrator and Magnifier at the same time may result in a crash</span></span></span></div>


- <div><span data-ttu-id="0d5f7-152"><span>以前のドキュメントを開いたまま [情報] タブに移動すると、クラッシュする場合がある問題</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-152"><span>Opening legacy documents and then going to the Info tab can cause a crash</span></span></span></div>


- <div><span data-ttu-id="0d5f7-153"><span>文章校正の候補がコンテキスト メニューに表示されない問題</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-153"><span>Proofing suggestins are not displaying in contextual menus</span></span></span></div>


- <div><span data-ttu-id="0d5f7-154"><span>コンテンツ ポリシーがコメントに正しく適用されない問題</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-154"><span>Content policies are being incorrectly applied to comments</span></span></span></div>


- <div><span data-ttu-id="0d5f7-155"><span>濃色のテキストで書かれた従来のコメントがダーク モードで表示されない問題</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-155"><span>Legacy comments written with dark text is not visible in Dark Mode</span></span></span></div>


- <div><span data-ttu-id="0d5f7-156"><span>韓国語/英語のオートコレクトを使用しているときに、間違った文字が表示される場合がある問題</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-156"><span>Incorrect characters may appear when using Korean/English autocorrect</span></span></span></div>


- <div><span data-ttu-id="0d5f7-157"><span>上位のポリシー ラベルが優先して適用されるべき時に、低いポリシー ラベルが適用される場合がある問題</span><span class="sxs-lookup"><span data-stu-id="0d5f7-157"><span>Lower policy labels may be applied when a higher policy label should have taken priority</span></span></div></span>


- <div><span data-ttu-id="0d5f7-158"><span>Outlook メッセージからの cid: 画像のリンク&nbsp;が、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-158"><span>The links of cid: images from Outlook messages&nbsp;can now be successfully broken when requested.</span></span></div></span>


- <div><span data-ttu-id="0d5f7-159"><span>ナレーターと拡大鏡を同時に使用すると、クラッシュする場合がある問題</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-159"><span>Using Narrator and Magnifier at the same time may result in a crash</span></span></span></div>


- <div><span data-ttu-id="0d5f7-160"><span>ナビゲーション ウィンドウから検索できない場合がある問題</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-160"><span>Searching from the Navigation pane may fail</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="0d5f7-161">Office スイート</span><span class="sxs-lookup"><span data-stu-id="0d5f7-161">Office Suite</span></span>

- <div><span data-ttu-id="0d5f7-162"><span>一部の描画がプレビューやスライドショーに表示されない場合がある問題</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-162"><span>Some drawings may not display in preview or slide shows</span></span></span></div>


- <div><span data-ttu-id="0d5f7-163"><span>縦書きのテキスト ボックス内で一部のカタカナが正しく表示されないことがある問題</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-163"><span>Some katakana characters may display incorrectly in a vertical text box</span></span></span></div>


- <div><span data-ttu-id="0d5f7-164">接続されていないネットワーク共有にファイルを保存しようとすると、クラッシュする場合がある問題</span><span class="sxs-lookup"><span data-stu-id="0d5f7-164">Attempting to save a file to a disconnected network share may result in a crash</span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1911-october-25"></a><span data-ttu-id="0d5f7-166">バージョン 1911: 10 月 25 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-166">Version 1911: October 25</span></span>
<span data-ttu-id="0d5f7-167">*バージョン 1911 (ビルド 12215.20006)*</span><span class="sxs-lookup"><span data-stu-id="0d5f7-167">*Version 1911 (Build 12215.20006)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="0d5f7-169">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="0d5f7-169">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="0d5f7-170">Visio</span><span class="sxs-lookup"><span data-stu-id="0d5f7-170">Visio</span></span>

- <span data-ttu-id="0d5f7-171">**Excel で洗練された Visio 図を作成する:** すばやく簡単に、データを Excel 内の洗練された Visio 図に可視化します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-171">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> [<span data-ttu-id="0d5f7-172">詳細情報</span><span class="sxs-lookup"><span data-stu-id="0d5f7-172">Learn more</span></span>](https://support.office.com/ja-JP/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="0d5f7-173">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-173">Word</span></span>

- <span data-ttu-id="0d5f7-174">**共同編集の改善:** コンテンツの変更をリアルタイムでユーザーが受け取れるようにすることで、共同編集のエクスペリエンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-174">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="0d5f7-175">**他のユーザーがすばやく変更を確認:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-175">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="0d5f7-178">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="0d5f7-178">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="0d5f7-179">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-179">Access</span></span>

- <div><span data-ttu-id="0d5f7-180"><span>レコードのカウントが正しくないという問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-180"><span>The record count could be incorrect</span></span></span></div>


### <a name="excel"></a><span data-ttu-id="0d5f7-181">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-181">Excel</span></span>

- <div><span data-ttu-id="0d5f7-182"><span>結合されたセルで列を削除するパフォーマンスが大幅に改善されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-182"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


- <div><span data-ttu-id="0d5f7-183"><span>ユーザーが Office 365 の Excel ブック形式で保存できなくなる問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-183"><span>Users could be prevented from saving in Office 365 Excel Workbook format</span></span></span></div>


- <div><span data-ttu-id="0d5f7-184"><span>チェックボックスで正しく表示できないという問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-184"><span>Checkboxes could not render correctly</span></span></span></div>


- <div><span data-ttu-id="0d5f7-185"><span>グラフのサイズの変更が保存できないという問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-185"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="0d5f7-186"><span>VBA 関数の一部で、新しいグラフの種類に関するエラーが返される問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-186"><span>Some VBA functions would return an error on new chart types</span></span></span></div>


- <div><span data-ttu-id="0d5f7-187"><span>[データ ソースの選択] ダイアログで、一部のフィールドの大文字小文字の区別をしなかった問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-187"><span>Select Data Source dialogs were not case sensitive for some fields</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="0d5f7-188">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-188">PowerPoint</span></span>

- <div><span data-ttu-id="0d5f7-189"><span>グラフのサイズの変更が保存できないという問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-189"><span>Changes to a chart size could not be saved</span></span></span></div>


### <a name="publisher"></a><span data-ttu-id="0d5f7-190">Publisher</span><span class="sxs-lookup"><span data-stu-id="0d5f7-190">Publisher</span></span>

- <div><span data-ttu-id="0d5f7-191"><span>図形がグラフィックの境界線の外側に表示される問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-191"><span>Shapes could appear outside of the graphics border</span></span></span></div>


### <a name="word"></a><span data-ttu-id="0d5f7-192">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-192">Word</span></span>

- <div><span data-ttu-id="0d5f7-193"><span>図形がグラフィックの境界線の外側に表示される問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-193"><span>Shapes could appear outside of the graphics border</span></span></span></div>


- <div><span data-ttu-id="0d5f7-194"><span>テキストの強調表示が課題になるという問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-194"><span>Highlighting text could be challenging</span></span></span></div>


- <div><span data-ttu-id="0d5f7-195"><span>ユーザーがエディターの個々のアイテムに移動できなくなる問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-195"><span>A user could be prevented from navigating to an individual item in the editor</span></span></span></div>


- <div><span data-ttu-id="0d5f7-196"><span>文法またはスペルのエラーが強調表示されない問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-196"><span>Grammar or spelling errors might not be highlighted</span></span></span></div>


- <div><span data-ttu-id="0d5f7-197"><span>グラフのサイズの変更が保存できないという問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-197"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="0d5f7-198"><span>連絡先カードが、@ メンションに書式を設定した後に、開けなくなる問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-198"><span>A contact card could be prevented from opening after apply formatting to an @ mention</span></span></span></div>


- <div><span data-ttu-id="0d5f7-199"><span>ユーザーが、Word、Excel、PowerPoint のドキュメントを保存できなくなる場合があるという問題が解決されました。&nbsp;この問題は、[保存] アイコンをクリックしたり Ctrl キーを押しながら S キーを押したりした後に、新しいファイルを作成して &quot;[モデル形式で保存] ダイアログ&quot; を表示するユーザーに影響を与えます。</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-199"><span>Resolvedan issue where users may be unable to save Word, Excel, and PowerPoint documents.&nbsp; This issue affects users that create a new file and bring up the &quot;Save as Model Dialog&quot; option after clicking on the Save icon or pressing Ctrl + S.</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="0d5f7-200">Office スイート</span><span class="sxs-lookup"><span data-stu-id="0d5f7-200">Office Suite</span></span>

- <div><span data-ttu-id="0d5f7-201"><span>Windows 7 で図形を使用する場合のパフォーマンスの問題</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-201"><span>Performance issue when using Shapes on Windows 7</span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1911-october-18"></a><span data-ttu-id="0d5f7-203">バージョン 1911: 10 月 18 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-203">Version 1911: October 18</span></span>
<span data-ttu-id="0d5f7-204">*バージョン 1911 (ビルド 12209.20010)*</span><span class="sxs-lookup"><span data-stu-id="0d5f7-204">*Version 1911 (Build 12209.20010)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="0d5f7-206">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="0d5f7-206">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="0d5f7-207">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-207">Outlook</span></span>

- <span data-ttu-id="0d5f7-208">**アクセシビリティ対応のメールを最も必要としている人に送信する:** Outlook では、メールのヒントが表示され、アクセシビリティ対応のコンテンツを必要とするユーザーに送信するときに、コンテンツがアクセシビリティ対応であることを確認できます</span><span class="sxs-lookup"><span data-stu-id="0d5f7-208">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-209">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-209">PowerPoint</span></span>

- <span data-ttu-id="0d5f7-210">**プレゼンテーションの最適化:** アクセシビリティ チェックを使用すると、スクリーン リーダーを考慮に入れて、スライド上のオブジェクトを配置することができます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-210">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

### <a name="office-suite"></a><span data-ttu-id="0d5f7-211">Office スイート</span><span class="sxs-lookup"><span data-stu-id="0d5f7-211">Office Suite</span></span>

- <span data-ttu-id="0d5f7-212">**アップロード センターは、Files Needing Attention experience に置き換えられます:** アップロード センターは、[ファイル] > [開く] の Office アプリケーション内に表示される Files Needing Attention experience に置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-212">**The Upload Center is being replaced by the Files Needing Attention experience:** The Upload Center is being replaced by the Files Needing Attention experience that will show up inside the Office applications under File > Open.</span></span> <span data-ttu-id="0d5f7-213">この新しいエクスペリエンスは、アップロード センターに比べ、最新かつ総合的で、煩わしくありません。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-213">This new experience is more modern, integrated, and less intrusive compared to the Upload Center.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="0d5f7-216">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="0d5f7-216">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="0d5f7-217">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-217">Excel</span></span>

- <div><span data-ttu-id="0d5f7-218"><span>自動調整を使用して行の高さを調整するときにチェック ボックスのコントロールが縮小されるという問題を解決しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-218"><span>Resolved an issue where check box controls could shrink when using autofit to adjust row height</span></span></span></div>


- <div><span data-ttu-id="0d5f7-219"><span>スクロール後にセルを選択すると間違ったセルが選択されるという問題を解決しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-219"><span>Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="0d5f7-220">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-220">Outlook</span></span>

- <div><span data-ttu-id="0d5f7-221"><span>メールにデジタル署名付きの添付ファイルがある場合にそのメールに署名するとデジタル署名が破損する可能性があるという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-221"><span>Identified an issue which could cause digital signatures to become broken when signing an e-mail with a digitally signed attachment</span></span></span></div>


- <div><span data-ttu-id="0d5f7-222"><span>長いファイル名がメッセージ本文へのドラッグ アンド ドロップ後に切り捨てられるという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-222"><span>Identified an issue where long filenames were truncated after draging and droping to the message body</span></span></span></div>


- <div><span data-ttu-id="0d5f7-223">リボンを自動的に非表示にするよう設定されている場合に検索ボックスが消えるという問題を特定しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-223">Identified an issue where the search box could disappear when the ribbon is set to hide automatically</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="0d5f7-224">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-224">PowerPoint</span></span>

- <div><span data-ttu-id="0d5f7-225"><span>スライド プレビューの縦横比が適切にロック/ロック解除されていないという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-225"><span>Identified an issuewhere aspect ratio for the slide preview was not being properly locked/unlocked</span></span></span></div>

### <a name="project"></a><span data-ttu-id="0d5f7-226">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-226">Project</span></span>

- <div><span data-ttu-id="0d5f7-227">タスクの更新を実行中に入力したノートが保存されない可能性があるという問題を特定しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-227">Identified an issue where notes might not persist if entered while doing update tasks</span></span><br></div>


- <div><span data-ttu-id="0d5f7-228">ファイルがユーザーによってロックされている場合に、ユーザー名がエラー メッセージに表示されない可能性があるという問題を特定しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-228">Identified an issue where a file could be locked by a user, but no username would be displayed in the error message</span></span></div>


- <div><span data-ttu-id="0d5f7-229"><span>読み取り専用のプロジェクトを開いたときに複数のメッセージを取得する可能性があるという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-229"><span>Identified an issue where users could get several messages when opening a read-only project</span></span></span></div>


### <a name="word"></a><span data-ttu-id="0d5f7-230">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-230">Word</span></span>

- <div><span data-ttu-id="0d5f7-231"><span>スクリーン リーダーを使用中にコメントを表示するときの問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-231"><span>Identified an issue when viewing comments while using a screen reader</span></span></span></div>


- <div><span data-ttu-id="0d5f7-232"><span>一部の批評がスペルまたは文法の批評と誤って識別されるという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-232"><span>Identified an issue where some critiques were misidentified as being spelling or grammar critiques</span></span></span></div>


- <div><span data-ttu-id="0d5f7-233"><span>新しいコメント ダイアログがフォーカスを取得できないことがあるという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-233"><span>Identified an issue where a new comment dialog could sometimes not obtain focus</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="0d5f7-234">Office スイート</span><span class="sxs-lookup"><span data-stu-id="0d5f7-234">Office Suite</span></span>

- <div><span data-ttu-id="0d5f7-235"><span>&quot;[別のインストールが進行中です]&quot; という誤ったエラー メッセージによりアップグレードに失敗することがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-235"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="0d5f7-236"><span>ローカル リソースからクラウド リソースへの同期に影響する可能性がある問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-236"><span>Identified an issue which could affect syncing from a local resource to a cloud resource</span></span></span></div>

- <div><span data-ttu-id="0d5f7-237"><span>ウェルカム メッセージに無効なリンクが含まれているという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-237"><span>Identified an issue where a welcome message contained an invalid link</span></span></span></div>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-october-11"></a><span data-ttu-id="0d5f7-239">バージョン 1910: 10 月 11 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-239">Version 1910: October 11</span></span>
<span data-ttu-id="0d5f7-240">*バージョン 1910 (ビルド 12130.20112)*</span><span class="sxs-lookup"><span data-stu-id="0d5f7-240">*Version 1910 (Build 12130.20112)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)
[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)
[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="0d5f7-244">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="0d5f7-244">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="0d5f7-245">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-245">Excel</span></span>

- <div><span data-ttu-id="0d5f7-246">OneDrive からオブジェクトとしてファイルを挿入する場合の問題が解決されました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-246">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="0d5f7-247">ハイパーリンク形式が一部のコンテンツに適切に適用されない場合がある問題が解決されました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-247">Resolved an issue where the hyperlink format could not be properly applied to some content</span></span></div>


- <div><span data-ttu-id="0d5f7-248">数式に構造化された絶対参照が含まれる場合に誤って調整される可能性がある問題が解決されました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-248">Resolved an issue where formulas containing structured absolute references may be adjusted incorrectly</span></span></div>


- <div><span data-ttu-id="0d5f7-249">Office 現在のバージョンで開いた場合に Excel の停止を引き起こす可能性がある、Office の以前のバージョンで作成されるブックの問題が解決されました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-249">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office</span></span></div>


- <div><span data-ttu-id="0d5f7-250">Excel からコピーされたコンテンツを他の Office アプリケーションに貼り付けると、間違って表示されることがある問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-250">Resolved an issue where content copied from Excel could appear incorrect when pasted into other Office applications</span></span></div>


- <div><span data-ttu-id="0d5f7-251">グラフ テンプレートを使用してグラフを挿入する場合に、プレビューで正しい色が使用されるよう修正します</span><span class="sxs-lookup"><span data-stu-id="0d5f7-251">Fix to correct colors used in previews when inserting charts using chart templates</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="0d5f7-252">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-252">PowerPoint</span></span>

- <div><span data-ttu-id="0d5f7-253">AirSpace WinComp 下で実行しているときに ARC デバイスの接続が失われる問題を特定しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-253">Identified an issue where ARC Devices could lose connection when running under AirSpace WinComp</span></span></div>


### <a name="word"></a><span data-ttu-id="0d5f7-254">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-254">Word</span></span>

- <div><span data-ttu-id="0d5f7-255">OneDrive からオブジェクトとしてファイルを挿入する場合の問題が解決されました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-255">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="0d5f7-256"><span>メールのスレッドからグラフィカル コンテンツが削除される原因となっていた問題を修正&nbsp;</span>するための回復手順が改善されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-256">Improved our recovery steps to f<span>ix an issue that caused graphical content to get deleted from email threads.&nbsp;</span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-october-04"></a><span data-ttu-id="0d5f7-258">バージョン 1910: 10 月 4 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-258">Version 1910: October 04</span></span>
<span data-ttu-id="0d5f7-259">*バージョン 1910 (ビルド 12126.20000)*</span><span class="sxs-lookup"><span data-stu-id="0d5f7-259">*Version 1910 (Build 12126.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="0d5f7-261">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="0d5f7-261">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="0d5f7-262">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-262">Excel</span></span>

- <span data-ttu-id="0d5f7-263">**データ ビジュアライザー アドイン:** Excel から Visio フローチャートをすばやく作成します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-263">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="0d5f7-264">詳細情報</span><span class="sxs-lookup"><span data-stu-id="0d5f7-264">Learn more</span></span>](https://support.office.com/ja-JP/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="0d5f7-267">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="0d5f7-267">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="0d5f7-268">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-268">Excel</span></span>

- <div><span data-ttu-id="0d5f7-269"><span>印刷プレビューの印刷範囲が正しくない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-269"><span>We fixed an issue where the print area in print preview was not correct</span></span></span></div>


- <div><span data-ttu-id="0d5f7-270"><span>共同編集セッション中にピボット テーブルが更新されないことがあった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-270"><span>We fixed an issue which could have prevented pivot tables from being refreshed during a co-authoring session</span></span></span></div>


### <a name="access"></a><span data-ttu-id="0d5f7-271">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-271">Access</span></span>

- <div><span data-ttu-id="0d5f7-272">共有データベースの使用中に、"&quot;矛盾がある状態&quot;" エラーがユーザーに表示されることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-272">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


### <a name="outlook"></a><span data-ttu-id="0d5f7-273">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-273">Outlook</span></span>

- <div><span data-ttu-id="0d5f7-274"><span>メール フォルダーの重複を引き起こすことがあった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-274"><span>We fixed an issue which could have caused duplication of mail folders</span></span></span></div>


- <div><span data-ttu-id="0d5f7-275"><span>S/MIME で暗号化された電子メールを送信しようとしたときに誤ったエラー メッセージが表示されることがあった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-275"><span>We fixed an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail</span></span></span></div>


- <div><span data-ttu-id="0d5f7-276"><span>ユーザーが Skype から「不在着信した会話」メッセージを受信したときにクラッシュすることがあった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-276"><span>We fixed an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype</span></span></span></div>


- <div><span data-ttu-id="0d5f7-277"><span>メモリ リークを引き起こすことがあった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-277"><span>We fixed an issue which could have resulted in a memory leak</span></span></span></div>


- <div><span data-ttu-id="0d5f7-278"><span>下書きとして保存したときに送信者の名前が変更されることがあった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-278"><span>We fixed an issue which could have caused the senders name to change when saved as a draft</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="0d5f7-279">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-279">PowerPoint</span></span>

- <div><span></span></div><span data-ttu-id="0d5f7-280">スライド マスターとスライド レイアウトのヘッダー/フッター/スライド番号プレースホルダーにテキストを貼り付けた後、TextRanges が破損することがあった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-280">We fixed an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout</span></span>


- <div><span></span></div><span data-ttu-id="0d5f7-281">ハイパーリンク付きのテキストを貼り付けるときにハイパーリンクが作成されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-281">We fixed an issue which prevented hyperlink from being created when pasting text with hyperlink</span></span>


- <div><span data-ttu-id="0d5f7-282">統計が正常に機能しなくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-282">We fixed an issue which would prevent statistics from working correctly</span></span></div>


### <a name="word"></a><span data-ttu-id="0d5f7-283">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-283">Word</span></span>

- <div><span data-ttu-id="0d5f7-284"><span>フォントの色がコミットされない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-284"><span>We fixed an issue where font colors were not being committed</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="0d5f7-285">Office スイート</span><span class="sxs-lookup"><span data-stu-id="0d5f7-285">Office Suite</span></span>

- <div><span data-ttu-id="0d5f7-286">この機能が無効になったときにバージョン履歴が表示されることがあった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-286">We fixed an issue which could offer version history when that feature was disabled</span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-september-27"></a><span data-ttu-id="0d5f7-288">バージョン 1910: 9 月 27 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-288">Version 1910: September 27</span></span>
<span data-ttu-id="0d5f7-289">*バージョン 1910 (ビルド 12119.20000)*</span><span class="sxs-lookup"><span data-stu-id="0d5f7-289">*Version 1910 (Build 12119.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)
[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)
[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="0d5f7-293">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="0d5f7-293">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="0d5f7-294">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-294">Excel</span></span>

- <div><span data-ttu-id="0d5f7-295"><span>シリーズ コレクションを変更するときに、散布図が適切にレンダリングされない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-295"><span>We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="0d5f7-296">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-296">Outlook</span></span>

- <div><span data-ttu-id="0d5f7-297"><span>共有予定表フォルダーを操作するときに、アクセス許可エラーを報告する可能性があった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-297"><span>We fixed an issue which could have reported permission errors when interacting with shared calendar folders</span></span></span></div>


- <div><span data-ttu-id="0d5f7-298"><span>ユーザーが予定表に添付ファイルを追加できない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-298"><span>We fixed an issue which could have prevented users from adding attachments to calendars</span></span></span></div>


- <div><span data-ttu-id="0d5f7-299"><span>デジタル署名されたメッセージに返信するときに、エラー メッセージが表示される問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-299"><span>We fixed an issue which caused error messages to display when replying to a digitally signed message</span></span></span></div>


### <a name="word"></a><span data-ttu-id="0d5f7-300">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-300">Word</span></span>

- <div><span data-ttu-id="0d5f7-301"><span>Deskjet プリンターへの印刷時に、スケーリングの問題を引き起こす可能性があった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-301"><span>We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="0d5f7-302">Office スイート</span><span class="sxs-lookup"><span data-stu-id="0d5f7-302">Office Suite</span></span>

- <div><span data-ttu-id="0d5f7-303"><span>中太字のテキストのスタイルが正しく表示されない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-303"><span>We fixed an issue where medium bold text could be incorrectly styled</span></span></span></div>


- <div><span data-ttu-id="0d5f7-304"><span>アップロードが保留されているファイルを閉じるときに、ユーザーに誤ったエラー メッセージが表示される問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-304"><span>We fixed an issue where a user could be given an incorrect error message when closing a file with a pending upload</span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-september-20"></a><span data-ttu-id="0d5f7-306">バージョン 1910: 9 月 20 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-306">Version 1910: September 20</span></span>
<span data-ttu-id="0d5f7-307">*バージョン 1910 (ビルド 12112.20000)*</span><span class="sxs-lookup"><span data-stu-id="0d5f7-307">*Version 1910 (Build 12112.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="0d5f7-311">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="0d5f7-311">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="0d5f7-312">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-312">Excel</span></span>

- <div><span data-ttu-id="0d5f7-313"><span>Excel が起動時にハングすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-313"><span>We fixed an issue where Excel could sometimes hang at launch</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="0d5f7-314">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-314">Outlook</span></span>

- <div><span data-ttu-id="0d5f7-315"><span>多数の部屋が利用可能な場合の部屋選択のパフォーマンスが大幅に向上しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-315"><span>We significantly improved the performance of room selection when there are a large number of rooms available</span></span></span></div>


- <div><span data-ttu-id="0d5f7-316"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Office 365 の最新の認証に移行するときに、Outlook に複数のメールボックスを使用しているユーザーのメールボックスの同期を妨げる可能性がある問題を修正しました。</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-316"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can prevent mailbox sync for customers with multiple mailboxes in Outlook when migrating to modern authentication in Office 365.</span></span></span><br></div>


- <div><span data-ttu-id="0d5f7-317"><span>署名ラベルの一部の文字がドロップダウン メニューに表示されない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-317"><span>We fixed an issue where some characters in signature labels would not display in the dropdown menu</span></span></span></div>


### <a name="project"></a><span data-ttu-id="0d5f7-318">プロジェクト</span><span class="sxs-lookup"><span data-stu-id="0d5f7-318">Project</span></span>

- <div><span data-ttu-id="0d5f7-319"><span>エンタープライズ リソースをローカル リソースに置き換えるとクラッシュする可能性がある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-319"><span>We fixed an issue which could cause a crash when replacing an enterprise resource with a local resource</span></span></span></div>


### <a name="word"></a><span data-ttu-id="0d5f7-320">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-320">Word</span></span>

- <div><span data-ttu-id="0d5f7-321"><span>下書き表示で同期スクロールが正常に機能しない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-321"><span>We fixed an issue which could prevent synchronous scrolling from working properly in draft view</span></span></span></div>


- <div><span data-ttu-id="0d5f7-322">ドキュメントを初めて保存した後、ツール ヒントが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-322">We fixed an issue which could prevent Tool Tips from displaying properly after saving a document for the first time</span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-september-13"></a><span data-ttu-id="0d5f7-324">バージョン 1910: 9 月 13 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-324">Version 1910: September 13</span></span>
<span data-ttu-id="0d5f7-325">*バージョン 1910 (ビルド 12105.20000)*</span><span class="sxs-lookup"><span data-stu-id="0d5f7-325">*Version 1910 (Build 12105.20000)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="0d5f7-327">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="0d5f7-327">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="0d5f7-328">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-328">Excel</span></span>

- <div><span data-ttu-id="0d5f7-329"><span>一部の保護されたシートにユーザーがハイパーリンクを貼り付けられない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-329"><span>We fixed an issue which could prevent a user from pasting hyperlinks in some protected sheets</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="0d5f7-330">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-330">Outlook</span></span>

- <div><span data-ttu-id="0d5f7-331"><span>コンパクト ビューで UI が動かなくなる問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-331"><span>We fixed an issue where the UI could get stuck in a compact view</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="0d5f7-332">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-332">PowerPoint</span></span>

- <div><span data-ttu-id="0d5f7-333"><span>PDFへの印刷時、ユーザーにエラーが発生する問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-333"><span>We fixed an issue where a user could experience an error upon printing to PDF</span></span></span></div>


### <a name="project"></a><span data-ttu-id="0d5f7-334">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-334">Project</span></span>

- <div><span data-ttu-id="0d5f7-335"><span>問題を修正しました (<span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">保護された作業が有効になっている場合、サマリー タスクの作業値を変更するとクラッシュする</span></span>)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-335"><span>We fixed an issue where <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">changes to a work value on a summary task could cause a crash if protected work is enabled</span></span></span></span></div>


- <span data-ttu-id="0d5f7-336"><font size=2 style="background-color:rgb(255, 255, 255);">エンタープライズ カレンダーとイベントを同期する機能を阻害する可能性がある問題を修正しました</font></span><span class="sxs-lookup"><span data-stu-id="0d5f7-336"><font size=2 style="background-color:rgb(255, 255, 255);">We fixed an issue which could inhibit the ability to sync events with enterprise calendars</font></span></span>


### <a name="office-suite"></a><span data-ttu-id="0d5f7-337">Office スイート</span><span class="sxs-lookup"><span data-stu-id="0d5f7-337">Office Suite</span></span>

- <div><span data-ttu-id="0d5f7-338"><span>ファイルのローカル バージョンの破棄を促す警告が繰り返し発生する可能性がある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-338"><span>We fixed an issue which could cause a repeated warning to discard local versions of a file</span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-september-06"></a><span data-ttu-id="0d5f7-340">バージョン 1910: 9 月 6 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-340">Version 1910: September 06</span></span>
<span data-ttu-id="0d5f7-341">*バージョン 1910 (ビルド 12030.20004)*</span><span class="sxs-lookup"><span data-stu-id="0d5f7-341">*Version 1910 (Build 12030.20004)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="0d5f7-343">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="0d5f7-343">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="0d5f7-344">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-344">Excel</span></span>

- <span data-ttu-id="0d5f7-345">**準備ができたら、描画を開始:** Surface ペンを持てば、描画の準備完了です。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-345">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="0d5f7-346">詳細情報</span><span class="sxs-lookup"><span data-stu-id="0d5f7-346">Learn more</span></span>](https://support.office.com/ja-JP/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-347">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-347">PowerPoint</span></span>

- <span data-ttu-id="0d5f7-348">**準備ができたら、描画を開始:** Surface ペンを持てば、描画の準備完了です。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-348">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="0d5f7-349">詳細情報</span><span class="sxs-lookup"><span data-stu-id="0d5f7-349">Learn more</span></span>](https://support.office.com/ja-JP/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a><span data-ttu-id="0d5f7-350">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-350">Word</span></span>

- <span data-ttu-id="0d5f7-351">**準備ができたら、描画を開始:** Surface ペンを持てば、描画の準備完了です。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-351">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="0d5f7-352">詳細情報</span><span class="sxs-lookup"><span data-stu-id="0d5f7-352">Learn more</span></span>](https://support.office.com/ja-JP/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="0d5f7-355">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="0d5f7-355">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="0d5f7-356">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-356">Excel</span></span>

- <div><span data-ttu-id="0d5f7-357"><span> リボンのフォント名が使用されているフォントと異なることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-357"><span>We fixed an issue which could cause the font name in the ribbon to be different from the font being used</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="0d5f7-358">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-358">Outlook</span></span>

- <div><span data-ttu-id="0d5f7-359"><span> Internet Explorer で制限付きサイトの保護モードが無効になると、Outlook により不適切なリソースの使用量になることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-359"><span>We fixed an issue that could result in inappropriate resource consumption by Outlook when Protected Mode is disabled for Restricted Sites in Internet Explorer</span></span></span></div>


- <div><span data-ttu-id="0d5f7-360"><span>時々、ANSI ソースのテキスト貼り付けるときに Unicode 文字が表示されることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-360"><span>We fixed an issue which could sometimes cause Unicode characters to appear when pasting text from an ANSI source</span></span></span></div>


- <div><span data-ttu-id="0d5f7-361"><span>グループ スケジュール ビューで一部のユーザーがオフラインとして間違って表示される問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-361"><span>We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span></span></div>


### <a name="word"></a><span data-ttu-id="0d5f7-362">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-362">Word</span></span>

- <div><span data-ttu-id="0d5f7-363"><span>テーブルの書式設定が失われることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-363"><span>We fixed an issue where table formatting could be lost</span></span></span></div>


- <div><span data-ttu-id="0d5f7-364"><span>Ctrl + V ショートカット キーが効かなくなることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-364"><span>We fixed an issue which could break the ctrl+v keyboard shortcut</span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1909-august-30"></a><span data-ttu-id="0d5f7-366">バージョン 1909: 8 月 30 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-366">Version 1909: August 30</span></span>
<span data-ttu-id="0d5f7-367">*バージョン 1909 (ビルド 12026.20000)*</span><span class="sxs-lookup"><span data-stu-id="0d5f7-367">*Version 1909 (Build 12026.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="0d5f7-369">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="0d5f7-369">Feature updates</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-370">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-370">Access</span></span>

- <span data-ttu-id="0d5f7-371">**リンク テーブルの高速検索:** 新しい検索ボックスにより、リンク テーブルを簡単に見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-371">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-372">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-372">PowerPoint</span></span>

- <span data-ttu-id="0d5f7-373">**図を SVG として保存する:** グラフ、図形、その他の図を、サイズ変更しても画質が低下しないスケーラブル ベクター グラフィックとして保存できます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-373">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="0d5f7-374">詳細情報</span><span class="sxs-lookup"><span data-stu-id="0d5f7-374">Learn more</span></span>](https://support.office.com/ja-JP/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="0d5f7-377">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="0d5f7-377">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="0d5f7-378">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-378">Excel</span></span>

- <div><span data-ttu-id="0d5f7-379"><span>&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">秘密度</span>のキー ヒントが&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">別のキー ヒントと競合している問題が修正されました。</span></span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-379"><span>We fixed an issue where the keytip for&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">Sensitivity </span>was&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">conflicting with another keytip.</span></span></span></span></div>

- <div><span data-ttu-id="0d5f7-380"><span>共有ブックでの作業中に保存を行おうとする際に発生する問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-380"><span>We fixed an issue that occurred while working on a shared workbook when trying to save.</span></span></span></div>

- <div><span data-ttu-id="0d5f7-381"><span>Excel で、レジストリ値 "\Excel\Add-in Manager" にあるアドインのうち、最初の 16 個しか表示されない問題が修正されました。<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-381"><span>We fixed an issue where Excel only lists the first 16 addins located in the '\Excel\Add-in Manager' registry values.<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span></span></div>


- <div><span data-ttu-id="0d5f7-382"><span>関数 Frequency() が誤った結果を返す問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-382"><span>We fixed an issue where the function Frequency() returns incorrect results.</span></span></span></div>


- <div><span data-ttu-id="0d5f7-383"><span>色によるフィルター処理のパフォーマンスが大幅に改善されました。</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-383"><span>We have significantly improved the performance of filtering by color.</span></span></span></div>


- <div><span data-ttu-id="0d5f7-384"><span>Surface のユーザーがマウスを動かすと、それがマウス クリックのイベントとして解釈されることがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-384"><span>We fixed an issue for Surface users where moving the mouse could be interpreted as a mouse click event.</span></span></span></div>


- <div><span data-ttu-id="0d5f7-385"><span>[検索と置換] ダイアログでキーボードによるナビゲーションを行えない問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-385"><span>We fixed an issue which prevented keyboard navigation in the Find/Replace dialog</span></span></span></div>


- <div><span data-ttu-id="0d5f7-386"><span>一部のフォント名が正しく表示されない問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-386"><span>We fixed an issue where the name of some fonts were not displayed correctly</span></span></span></div>


- <div><span data-ttu-id="0d5f7-387"><span>サポートされているファイル形式として CSV が表示されない問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-387"><span>We fixed an issue which prevented CSV from appearing as a supported file type</span></span></span></div>


### <a name="access"></a><span data-ttu-id="0d5f7-388">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-388">Access</span></span>

- <div><span data-ttu-id="0d5f7-389">共有データベースの使用中に、"&quot;矛盾がある状態&quot;" エラーがユーザーに表示されることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-389">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


- <div><span data-ttu-id="0d5f7-390"><span>日付選択カレンダーが表示されるべきではないときに表示されてしまうことがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-390"><span>We fixed an issue which could cause the date picker to appear when it shouldn't</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="0d5f7-391">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-391">Outlook</span></span>

- <div><span data-ttu-id="0d5f7-392"><span>一部の POP3 ユーザーに HTML コンテンツが表示されない問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-392"><span>We fixed an issue which prevented HTML content from appearing for some POP3 users</span></span></span></div>


- <div><span data-ttu-id="0d5f7-393"><span>Planner を利用できない環境で、連絡先カードのオーバーフロー メニューから機能しない [Planner] リンクを削除するための修正を行いました。</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-393"><span>We fixed an issue to remove non-functional 'Planner' link from the overflow menu in the contact card when working in environments where it is not available.</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="0d5f7-394">OneNote</span><span class="sxs-lookup"><span data-stu-id="0d5f7-394">OneNote</span></span>

- <div><span data-ttu-id="0d5f7-395"><span>フォーカスが &nbsp;OneNote のバックグラウンド同期に移動してしまうことがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-395"><span>We fixed an issue where&nbsp;OneNote background sync was sometimes stealing focus.</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="0d5f7-396">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-396">PowerPoint</span></span>

- <div><span data-ttu-id="0d5f7-397"><span>3-D Turntable の回転の向きに影響を与えていた問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-397"><span>We fixed an issue which would affect the rotation orientation of a 3D Turntable.</span></span></span></div>

- <div><span data-ttu-id="0d5f7-398"><span>ハイパーリンクに特殊文字が含まれている場合に一部のハイパーリンクが機能しない問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-398"><span>We fixed an issue which prevented some hyperlinks from working if they contained special characters.</span></span></span></div>

- <div><span data-ttu-id="0d5f7-399"><span>同時に複数のコメント ウィンドウが開かれる問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-399"><span>We fixed an issue which caused multiple comment panes to open at the same time.</span></span></span></div>

### <a name="project"></a><span data-ttu-id="0d5f7-400">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-400">Project</span></span>

- <div><span data-ttu-id="0d5f7-401"><span>チーム プランナー ビューを印刷した後にクラッシュすることがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-401"><span>We fixed an issue which could sometimes cause a crash after printing a Team Planner view.</span></span></span></div>

### <a name="word"></a><span data-ttu-id="0d5f7-402">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-402">Word</span></span>

- <div><span data-ttu-id="0d5f7-403">閲覧表示で、縦書きテキスト ボックス内の複数バイト文字が重なって表示される問題が<span>修正されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-403">We f<span>ixed an issue where multi-byte characters in vertical text box are shown overlapped in reading view.</span></span><br></span></div>

- <div><span data-ttu-id="0d5f7-404"><span>&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">ユーザーがアドイン ウィザードでアクションを実行する際に、日本語のはがきとグリーティング カードに関連するアドインのリソースが見つからない問題が修正されました。</span></span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-404"><span>We&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">fixed an issue where Japanese post card and greeting card related addin resources are not found when the user takes action in the addin wizard.</span></span></span></span></div>

- <div><span data-ttu-id="0d5f7-405"><span>保護ビューで表示中に、タイトル バーのユーザー インターフェイスで問題を発生させることがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-405"><span>We fixed an issue which could cause issues with the Title Bar User Interface when in Protected View</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="0d5f7-406">Office スイート</span><span class="sxs-lookup"><span data-stu-id="0d5f7-406">Office Suite</span></span>

- <div><span data-ttu-id="0d5f7-407"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">標準の図形とコネクタ図形の両方が含まれる選択部分に対して [図形の変更] を適用するとファイルが破損する問題が修正されました。</span></span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-407"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> We fixed a corrupt file issue when you Change Shape on a selection that contains both a normal shape and a connector shape.</span></span></span></span></div>

- <div><span data-ttu-id="0d5f7-408"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">複数の外付けモニターからドッキングとドッキングの解除を使用すると、アプリケーションに問題が発生する</span>問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-408"><span>We fixed an issue that <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">caused a problem in applications when using dock/undock from multiple external displays. </span></span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="august-23-2019br"></a><span data-ttu-id="0d5f7-410">**2019 年 8 月 23 日**</span><span class="sxs-lookup"><span data-stu-id="0d5f7-410">**August 23, 2019**</span></span><br/>
<span data-ttu-id="0d5f7-411">バージョン 1909 (ビルド 12015.20004)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-411">Version 1909 (Build 12015.20004)</span></span><br/>



## <a name="non-security-updates"></a><span data-ttu-id="0d5f7-412">セキュリティ以外の更新プログラム:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-412">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-413">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-413">Excel</span></span>

- <div><span data-ttu-id="0d5f7-414"><span>結合されたセルで列を削除するパフォーマンスが大幅に改善されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-414"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="0d5f7-415">Office スイート</span><span class="sxs-lookup"><span data-stu-id="0d5f7-415">Office Suite</span></span>

- <div><span data-ttu-id="0d5f7-416"><span>一部の Unicode 文字がブラウザー上で表示されない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-416"><span>We fixed an issue which could prevent some Unicode characters from being displayed when viewed in a browser</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="0d5f7-417">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-417">Outlook</span></span>

- <div><span data-ttu-id="0d5f7-418"><span>WebDAV の場所にファイルを保存できないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-418"><span>We fixed an issue which could have prevented files from being saved to a WebDAV location</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="0d5f7-419">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-419">PowerPoint</span></span>

- <div><span data-ttu-id="0d5f7-420"><span>ユーザーがあるコメントをクリックすると別のコメントが選択される問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-420"><span>We fixed an issue where a user would click on one comment, but another comment would be selected</span></span></span></div>





## <a name="august-16-2019br"></a><span data-ttu-id="0d5f7-421">**2019 年 8 月 16 日**</span><span class="sxs-lookup"><span data-stu-id="0d5f7-421">**August 16, 2019**</span></span><br/>
<span data-ttu-id="0d5f7-422">バージョン 1909 (ビルド 12013.20000)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-422">Version 1909 (Build 12013.20000)</span></span><br/>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="0d5f7-423">PowerPoint 機能の更新:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-423">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="0d5f7-424">**配布資料にスライド番号を印刷する:** スライド番号は配布資料に自動的に含まれます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-424">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="0d5f7-425">それらをオンのままにするか、オフにするか、選択します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-425">Leave them on, turn them off, it's all up to you.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="0d5f7-426">セキュリティ以外の更新プログラム:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-426">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-427">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-427">Excel</span></span>

- <div><span data-ttu-id="0d5f7-428"><span>自動保存が有効になることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-428"><span>We fixed an issue which could cause AutoSave to become enabled</span></span></span></div>


- <div><span data-ttu-id="0d5f7-429">セルの高さが不正確に測定されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-429">We fixed an issue which could result in cell heights being measured inaccurately</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="0d5f7-430">Office スイート</span><span class="sxs-lookup"><span data-stu-id="0d5f7-430">Office Suite</span></span>

- <div><span data-ttu-id="0d5f7-431"><span>コメント機能のパフォーマンスを大幅に改善する問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-431"><span>We fixed an issue which significantly improves the performance of the Comments feature</span></span></span></div>


- <div><span data-ttu-id="0d5f7-432"><span>検索中に方向キーを使用するとクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-432"><span>We fixed an issue which could cause a crash when using arrow keys while in search</span></span></span></div>


- <div><span data-ttu-id="0d5f7-433"><span>@ 記号が特定の文字の後に配置された場合に @メンションを使用できないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-433"><span>We fixed an issue which could prevent an @ mention if the @ symbol was placed after certain characters</span></span></span></div>


- <div><span data-ttu-id="0d5f7-434"><span>@メンションを削除するとクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-434"><span>We fixed an issue which could sometimes cause a crash when deleting @ mentions</span></span></span></div>


- <div><span data-ttu-id="0d5f7-435"><span>コメント カードに絵文字が正しく表示されない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-435"><span>We fixed an issue which prevented emojis from displaying correctly in comment cards</span></span></span></div>


- <div><span data-ttu-id="0d5f7-436"><span>アクティブ​​ クリップボード​​でクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-436"><span>We fixed an issue with Active Clipboard which could sometimes result in a crash</span></span></span></div>


- <div><span data-ttu-id="0d5f7-437"><span>クイック アクセス ツール バーのボタンが機能しなくなることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-437"><span>We fixed an issue which could cause the Quick Access Toolbar buttons to stop working</span></span></span></div>


- <div><span data-ttu-id="0d5f7-438"><span>文書の書式設定プレビュー​​がバックグラウンドに切り替わらないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-438"><span>We fixed an issue which could prevent the Document Formatting Preview from switching to the background</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="0d5f7-439">OneNote</span><span class="sxs-lookup"><span data-stu-id="0d5f7-439">OneNote</span></span>

- <span data-ttu-id="0d5f7-440">Office テーマが黒に設定されている場合、セクションのドロップダウン リストにセクションの名前が空白で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-440">We fixed an issue where the names of sections appear blank in the section dropdown list when Office Theme is set to Black.</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-441">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-441">Outlook</span></span>

- <div><span data-ttu-id="0d5f7-442"><span>Outlook が繰り返しフォーカスを取得して失うことがある送信イベントに関する問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-442"><span>We fixed an issue with Send Events which could cause Outlook to repeatedly gain and lose focus</span></span></span></div>


- <div><span data-ttu-id="0d5f7-443"><span>[フォルダーに返信を投稿] ショートカットが機能しない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-443"><span>We fixed an issue which prevented the Post Reply to Folder shortcut from working</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-444">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-444">PowerPoint</span></span>

- <div><span data-ttu-id="0d5f7-445"><span>共同作業の際に問題を引き起こすことがある保護ビューの問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-445"><span>We fixed an issue with Protected View which could sometimes cause problems when collaborating</span></span></span></div>


- <div><span data-ttu-id="0d5f7-446"><span>コメント ウィンドウのタスクが適切に表示されないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-446"><span>We fixed an issue which could prevent tasks in comment panes from displaying properly</span></span></span></div>


- <div><span data-ttu-id="0d5f7-447"><span>新しいスライドを挿入するときにクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-447"><span>We fixed an issue which could cause a crash when inserting new slides</span></span></span></div>


### <a name="user-lifecycle"></a><span data-ttu-id="0d5f7-448">ユーザーのライフサイクル</span><span class="sxs-lookup"><span data-stu-id="0d5f7-448">User Lifecycle</span></span>

- <div><span data-ttu-id="0d5f7-449"><span>サブスクリプション機能が消えることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-449"><span>We fixed an issue which could sometimes result in subscription features disappearing</span></span></span></div>


### <a name="word"></a><span data-ttu-id="0d5f7-450">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-450">Word</span></span>

- <div><span data-ttu-id="0d5f7-451"><span>ハイパーリンクに特定の文字が含まれている場合、ハイパーリンクが壊れることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-451"><span>We fixed an issue where hyperlinks could be broken if the hyperlink contained certain characters</span></span></span></div>


- <div><span data-ttu-id="0d5f7-452"><span>画像のコメントを表示するときに画像のサイズが不適切になることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-452"><span>We fixed an issue where images could be improperly sized when viewing a comment for that image</span></span></span></div>


- <div><span data-ttu-id="0d5f7-453"><span>箇条書きのドロップダウン メニューでクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-453"><span>We fixed an issue with the Bullet List drop down menu which could sometimes result in a crash</span></span></span></div>





## <a name="august-09-2019br"></a><span data-ttu-id="0d5f7-454">**2019 年 8 月 9 日**</span><span class="sxs-lookup"><span data-stu-id="0d5f7-454">**August 09, 2019**</span></span><br/>
<span data-ttu-id="0d5f7-455">バージョン 1909 (ビルド 12001.20000)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-455">Version 1909 (Build 12001.20000)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="0d5f7-456">Excel 機能の更新</span><span class="sxs-lookup"><span data-stu-id="0d5f7-456">Excel Feature updates:</span></span>

- <span data-ttu-id="0d5f7-457">**共同作業がさらに簡単に:** 共同編集の改善とは、条件付き書式、セルのスタイルなどを使用して作業しているときに、ユーザーによる変更がシームレスに共同作業者のそれらと統合されるということを意味します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-457">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>


- <span data-ttu-id="0d5f7-458">**検索して楽しむ:** 目的のアイコンを簡単に検索できるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-458">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="0d5f7-459">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-459">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="office-suite-feature-updates"></a><span data-ttu-id="0d5f7-460">Office スイートの機能の更新</span><span class="sxs-lookup"><span data-stu-id="0d5f7-460">Office Suite Feature updates:</span></span>

- <span data-ttu-id="0d5f7-461">**新しい Office アプリのアイコン:** シンプルかつ高性能で、インテリジェントな Office のエクスペリエンスを反映するように、アプリのアイコンがリニューアルされました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-461">**New Office app icons:** Redesigned app icons to reflect the simple, powerful, and intelligent experiences of Office</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="0d5f7-462">Outlook 機能の更新</span><span class="sxs-lookup"><span data-stu-id="0d5f7-462">Outlook Feature updates:</span></span>

- <span data-ttu-id="0d5f7-463">**攻撃に対する高度な保護:** Office 365 Advanced Threat Protection を用いると、メールの件名、添付メッセージ、署名されたメッセージ、ネットワーク パスなどの範囲内のハイパーリンクを利用した攻撃から保護されます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-463">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>


- <span data-ttu-id="0d5f7-464">**検索して楽しむ:** 目的のアイコンを簡単に検索できるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-464">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="0d5f7-465">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-465">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="0d5f7-466">PowerPoint 機能の更新</span><span class="sxs-lookup"><span data-stu-id="0d5f7-466">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="0d5f7-467">**検索して楽しむ:** 目的のアイコンを簡単に検索できるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-467">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="0d5f7-468">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-468">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="0d5f7-469">Word 機能の更新</span><span class="sxs-lookup"><span data-stu-id="0d5f7-469">Word Feature updates:</span></span>

- <span data-ttu-id="0d5f7-470">**他のユーザーがすばやく変更を確認する:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-470">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


- <span data-ttu-id="0d5f7-471">**検索して楽しむ:** 目的のアイコンを簡単に検索できるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-471">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="0d5f7-472">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-472">And when you're selecting, the Insert button tells you how many you've picked.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="0d5f7-473">セキュリティ以外の更新プログラム:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-473">Non-security updates:</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-474">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-474">Outlook</span></span>

- <div><span data-ttu-id="0d5f7-475"><span>会議がキャンセルされた後に、会議の受信者が 2 つの通知を受け取る原因となっていた問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-475"><span>We fixed an issue which caused meeting recipients to receive two notifications after a meeting was cancelled</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="0d5f7-476">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-476">PowerPoint</span></span>

- <div><span data-ttu-id="0d5f7-477"><span>図形とアイコンの [線なし]、[塗りつぶしなし] をユーザーが選択したときに、クラッシュを引き起こす問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-477"><span>We fixed an issue which could cause a crash when the user selected No Outline or No Fill for Shapes and Icons</span></span></span></div>





## <a name="august-02-2019br"></a><span data-ttu-id="0d5f7-478">**2019 年 8 月 2 日**</span><span class="sxs-lookup"><span data-stu-id="0d5f7-478">**August 02, 2019**</span></span><br/>
<span data-ttu-id="0d5f7-479">バージョン 1908 (ビルド 11929.20002)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-479">Version 1908 (Build 11929.20002)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="0d5f7-480">Excel 機能の更新</span><span class="sxs-lookup"><span data-stu-id="0d5f7-480">Excel Feature updates:</span></span>

- <span data-ttu-id="0d5f7-481">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-481">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="0d5f7-482">**ドキュメントに機密ラベルを適用する:** ファイルとメールに機密ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-482">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="0d5f7-483">Outlook 機能の更新</span><span class="sxs-lookup"><span data-stu-id="0d5f7-483">Outlook Feature updates:</span></span>

- <span data-ttu-id="0d5f7-484">**ドキュメントに機密ラベルを適用する:** ファイルとメールに機密ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-484">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="0d5f7-485">PowerPoint 機能の更新</span><span class="sxs-lookup"><span data-stu-id="0d5f7-485">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="0d5f7-486">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-486">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="0d5f7-487">**ドキュメントに機密ラベルを適用する:** ファイルとメールに機密ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-487">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="0d5f7-488">Word 機能の更新</span><span class="sxs-lookup"><span data-stu-id="0d5f7-488">Word Feature updates:</span></span>

- <span data-ttu-id="0d5f7-489">**ファイルを変換してアクセシビリティを向上させる:** ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-489">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="0d5f7-490">**別の言葉で伝える:** 別の言葉で伝えたいときに、[書き換え] でお助けします。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-490">**Say it another way:** When you want to say it differently, Rewrite is there to help.</span></span> <span data-ttu-id="0d5f7-491">[書き換え] では、フレーズを洗練させるための別の言葉遣いを提供します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-491">Rewrite offers alternatives for finessing your phrases.</span></span>


- <span data-ttu-id="0d5f7-492">**ドキュメントに機密ラベルを適用する:** ファイルとメールに機密ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-492">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="0d5f7-493">セキュリティ以外の更新プログラム:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-493">Non-security updates:</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-494">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-494">Access</span></span>
- <span data-ttu-id="0d5f7-495">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-495">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-496">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-496">Excel</span></span>

- <div><span data-ttu-id="0d5f7-497"><span>PDF に印刷するときに [&quot;すべてのラベルを繰り返す&quot;] が適用されているかのように表示されていた問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-497"><span>We fixed an issue which made it appear as though &quot;repeat all labels&quot; was applied when printing to a PDF</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="0d5f7-498">Office スイート</span><span class="sxs-lookup"><span data-stu-id="0d5f7-498">Office Suite</span></span>

- <div><span data-ttu-id="0d5f7-499"><span>デスクトップからドキュメントを開けないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-499"><span>We fixed an issue which could have prevented users from opening a document from the desktop</span></span></span></div>

- <div><span data-ttu-id="0d5f7-500"><span>[&quot;別のインストールが進行中です&quot;] という誤ったエラー メッセージによりアップグレードに失敗することがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-500"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="0d5f7-501"><span>セキュリティ更新プログラムがインストールされるときに、エラー メッセージが表示されることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-501"><span>We fixed an issue where a user could see error messages when security updates are installed</span></span></span></div>

- <div><span data-ttu-id="0d5f7-502"><span>カーソルが消えることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-502"><span>We fixed an issue which could cause the cursor to disappear</span></span></span></div>

- <div><span data-ttu-id="0d5f7-503"><span>既定で [ホーム] タブではなく [描画] タブが設定されていることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-503"><span>We fixed an issue where a user could be defaulted to the draw tab instead of the home tab</span></span></span></div>

- <div><span data-ttu-id="0d5f7-504"><span>大きなツリー ビューがクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-504"><span>We fixed an issue where large tree views could result in a crash</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="0d5f7-505">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-505">Outlook</span></span>

- <div></div><span data-ttu-id="0d5f7-506"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">パスワード入力画面が繰り返し表示されることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-506"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can cause repeated password prompts</span></span></span>

- <div><span data-ttu-id="0d5f7-507"><span>メール アドレスが正しくクエリされないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-507"><span>We fixed an issue which could prevent an email address from being queried correctly</span></span></span></div>

- <div><span data-ttu-id="0d5f7-508"><span>以前のバージョンの Outlook で作成した予定表アイテムを開けないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-508"><span>We fixed an issue which could prevent users from opening calendar items created by legacy versions of Outlook</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-509">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-509">PowerPoint</span></span>

- <div><span data-ttu-id="0d5f7-510"><span>一部のアニメーションが開始されないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-510"><span>We fixed an issue which could prevent some animations from starting</span></span></span></div>

### <a name="project"></a><span data-ttu-id="0d5f7-511">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-511">Project</span></span>
- <span data-ttu-id="0d5f7-512">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-512">Various performance and stability fixes</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-513">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-513">Word</span></span>

- <div><span data-ttu-id="0d5f7-514"><span>コメントへの返信が順番に表示されないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-514"><span>We fixed an issue where replies to comments could appear out of order</span></span></span></div>

- <div><span data-ttu-id="0d5f7-515"><span>状況によって、コメントの代わりにヒントが表示されることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-515"><span>We fixed an issue where in some situations, hints would be displayed instead of comments</span></span></span></div>

- <div><span data-ttu-id="0d5f7-516"><span>新しいコメントを追加しようとしたときに [変更履歴] ウィンドウが表示されることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-516"><span>We fixed an issue where the Revisions Pane could display when the user tried to add a new comment</span></span></span></div>

- <div><span data-ttu-id="0d5f7-517"><span>[元に戻す] ドロップダウン リストが表示されないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-517"><span>We fixed an issue which could prevent the undo dropdown list from appearing</span></span></span></div>

- <div><span data-ttu-id="0d5f7-518"><span>コメントを追加できないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="0d5f7-518"><span>We fixed an issue which could prevent comments from being added</span></span></span></div>


## <a name="july-26-2019"></a><span data-ttu-id="0d5f7-519">2019 年 7 月 26 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-519">July 26, 2019</span></span>
<span data-ttu-id="0d5f7-520">バージョン 1908 (ビルド 11916.20000)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-520">Version 1908 (build 11916.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="0d5f7-521">新機能:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-521">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="0d5f7-522">Word、Excel、PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-522">Word, Excel, PowerPoint</span></span>

#### <a name="create-more-accessible-pdfs"></a><span data-ttu-id="0d5f7-523">よりアクセシビリティの高い PDF ファイルを作成する</span><span class="sxs-lookup"><span data-stu-id="0d5f7-523">Create more accessible PDFs</span></span>

<span data-ttu-id="0d5f7-524">PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-524">Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="0d5f7-525">主な修正:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-525">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="0d5f7-526">すべて</span><span class="sxs-lookup"><span data-stu-id="0d5f7-526">All</span></span>

- <span data-ttu-id="0d5f7-527">Office の更新後に、Office のファイルの種類の関連付けとアイコンが破損する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-527">We fixed an issue where file type association and icons for Office could sometimes break after an Office Update</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-528">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-528">Word</span></span> 
- <span data-ttu-id="0d5f7-529">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-529">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-530">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-530">Excel</span></span>
- <span data-ttu-id="0d5f7-531">グラフを移動するとクラッシュする場合がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-531">We fixed an issue where moving a chart could sometimes result in a crash</span></span>
- <span data-ttu-id="0d5f7-532">グラフの種類を変更した後にグラフ オブジェクトからブック オブジェクトを取得するとエラーが発生することがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-532">We fixed an issue where to get Workbook object from Chart object after changing chart types could sometimes result in an error</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-533">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-533">PowerPoint</span></span>
- <span data-ttu-id="0d5f7-534">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-534">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-535">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-535">Outlook</span></span>
- <span data-ttu-id="0d5f7-536">シンプル リボンで、無効にしてあるコントロールが淡色表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-536">We fixed an issue where in simplified ribbon, a disabled control could sometimes not be greyed out in the ribbon</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-537">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-537">Access</span></span>
- <span data-ttu-id="0d5f7-538">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-538">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="0d5f7-539">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-539">Project</span></span>
- <span data-ttu-id="0d5f7-540">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-540">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-19-2019"></a><span data-ttu-id="0d5f7-541">2019 年 7 月 19 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-541">July 19, 2019</span></span>
<span data-ttu-id="0d5f7-542">バージョン 1908 (ビルド 11911.20000)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-542">Version 1908 (build 11911.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="0d5f7-543">新機能:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-543">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-544">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-544">Word</span></span>

#### <a name="learn-what-acronyms-mean-when-you-read-in-word-online"></a><span data-ttu-id="0d5f7-545">Word Online の文書で使われている略語の意味を確認する</span><span class="sxs-lookup"><span data-stu-id="0d5f7-545">Learn what Acronyms mean when you read in Word Online</span></span>

<span data-ttu-id="0d5f7-546">略語を見つけたら、組織内のデータを使用してそれを定義しようとします。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-546">When you encounter an Acronym, we'll try to define it using data from within your organization.</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="0d5f7-547">主な修正:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-547">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-548">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-548">Word</span></span> 
- <span data-ttu-id="0d5f7-549">BookMarkEnd タグが欠けているという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-549">We fixed an issue which BookMarkEnd tag was missing.</span></span>
- <span data-ttu-id="0d5f7-550">ユーザーが特殊文字を入力しているときに、フォントの選択が変更される場合があるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-550">We fixed an issue where the font selection could change while the user was typing special characters</span></span>
- <span data-ttu-id="0d5f7-551">新しいコメント カードに空白の返信が発生することがあるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-551">We fixed an issue which could sometimes cause blank replies to a new comment card</span></span>
- <span data-ttu-id="0d5f7-552">メールを共有すると、書式設定が失われる場合があるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-552">We fixed an issue which could cause formatting to be lost when sharing an email</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-553">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-553">Excel</span></span>
- <span data-ttu-id="0d5f7-554">範囲の広い配列がクラッシュすることがあるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-554">We fixed an issue where an array with a large range could sometimes cause a crash</span></span>
- <span data-ttu-id="0d5f7-555">フィルター処理された範囲からデータをコピーする場合のパフォーマンスを大幅に向上しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-555">We significantly improved the performance of copying data from filtered ranges</span></span>
- <span data-ttu-id="0d5f7-556">ファイル名に特殊文字が含まれていると、一部のファイルを開くことができないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-556">We fixed an issue which prevented some files from opening if the filenames contained special characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-557">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-557">PowerPoint</span></span>
- <span data-ttu-id="0d5f7-558">PowerPoint で新しく作成したセクションのセクション名が既定で選択されていないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-558">We fixed an issue where section name was not selected by default for newly created section in PowerPoint.</span></span>
- <span data-ttu-id="0d5f7-559">4:3 ディスプレイを使用すると、UI の使用が困難になることがあるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-559">We fixed an issue which could cause the UI to become difficult to use when using a 4:3 display</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-560">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-560">Outlook</span></span>
- <span data-ttu-id="0d5f7-561">利用可能な会議室がリストに表示されないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-561">We fixed an issue which could prevent available rooms from being listed</span></span>
- <span data-ttu-id="0d5f7-562">一部の POP3 ユーザーの HTML 形式を設定できないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-562">We fixed an issue which prevented HTML formatting for some POP3 users</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-563">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-563">Access</span></span>
- <span data-ttu-id="0d5f7-564">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-564">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="0d5f7-565">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-565">Project</span></span>
- <span data-ttu-id="0d5f7-566">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-566">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-12-2019"></a><span data-ttu-id="0d5f7-567">2019 年 7 月 12 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-567">July 12, 2019</span></span>
<span data-ttu-id="0d5f7-568">バージョン 1907 (ビルド 11901.20038)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-568">Version 1907 (build 11901.20038)</span></span>

## <a name="whats-new"></a><span data-ttu-id="0d5f7-569">新機能:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-569">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-570">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-570">PowerPoint</span></span>
 
#### <a name="use-ink-replay-in-your-presentations"></a><span data-ttu-id="0d5f7-571">プレゼンテーションでインクの再生を使用する</span><span class="sxs-lookup"><span data-stu-id="0d5f7-571">Use ink replay in your presentations</span></span>
 
<span data-ttu-id="0d5f7-572">PowerPoint でインクの再生アニメーションを適用して、プレゼンテーションの表現力とコミュニケーション力を高めます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-572">Apply a replay animation for ink in PowerPoint to express and communicate more in presentations.</span></span> 

## <a name="notable-fixes"></a><span data-ttu-id="0d5f7-573">主な修正:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-573">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-574">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-574">Word</span></span> 
- <span data-ttu-id="0d5f7-575">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-575">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-576">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-576">Excel</span></span>
- <span data-ttu-id="0d5f7-577">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-577">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-578">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-578">PowerPoint</span></span>
- <span data-ttu-id="0d5f7-579">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-579">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-580">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-580">Outlook</span></span>
- <span data-ttu-id="0d5f7-581">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-581">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-582">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-582">Access</span></span>
- <span data-ttu-id="0d5f7-583">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-583">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="0d5f7-584">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-584">Project</span></span>
- <span data-ttu-id="0d5f7-585">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-585">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-5-2019"></a><span data-ttu-id="0d5f7-586">2019 年 7 月 5 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-586">July 5, 2019</span></span>
<span data-ttu-id="0d5f7-587">バージョン 1907 (ビルド 11901.20018)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-587">Version 1907 (build 11901.20018)</span></span>

## <a name="whats-new"></a><span data-ttu-id="0d5f7-588">新機能:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-588">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="0d5f7-589">Word、Excel、PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-589">Word, Excel, PowerPoint</span></span>

#### <a name="sketchy-shapes"></a><span data-ttu-id="0d5f7-590">Sketchy で描く!</span><span class="sxs-lookup"><span data-stu-id="0d5f7-590">Sketchy Shapes!</span></span>

<span data-ttu-id="0d5f7-591">プレゼンテーションを作成中ですか。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-591">In the middle of drafting a presentation?</span></span> <span data-ttu-id="0d5f7-592">まだ作業中であることを示す Sketchy スタイルを適用します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-592">Apply the sketchy style to show that you're still working on it.</span></span> <span data-ttu-id="0d5f7-593">これを使用すると、自由形式や手描きの図形に変えることなく、オブジェクトに個人的なタッチを与えることができます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-593">It gives a personal touch to your objects without turning it into a free form, hand-drawn shapes.</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-594">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-594">Excel</span></span>

- <span data-ttu-id="0d5f7-595">**ファイル共有の高速化**: ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-595">**Faster file sharing**: Share your documents right from the recently used list without having to open the file.</span></span>
### <a name="powerpoint"></a><span data-ttu-id="0d5f7-596">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-596">PowerPoint</span></span>

- <span data-ttu-id="0d5f7-597">**アクセスを容易にするため、[印刷] メニューに [配布資料にスライド番号を印刷する] を移動しました:** 配布資料が指定されているときに、[印刷] > [印刷レイアウト] ドロップダウンの順にクリックすると見つかります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-597">**The setting to Print Slide Numbers in Handouts has been moved to the Print Menu for easier access:**  Find it in the Print > Print Layout dropdown when a Handout layout is selected.</span></span> <span data-ttu-id="0d5f7-598">これにより、プレゼンテーションごとに簡単に設定を切り替えることもできます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-598">This also allows the setting to be easily toggled per presentation.</span></span> [<span data-ttu-id="0d5f7-599">詳細情報</span><span class="sxs-lookup"><span data-stu-id="0d5f7-599">Learn more</span></span>](https://support.office.com/ja-JP/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="0d5f7-600">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-600">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-601">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-601">Word</span></span>

- <span data-ttu-id="0d5f7-602">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-602">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="0d5f7-603">主な修正:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-603">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="0d5f7-604">すべて</span><span class="sxs-lookup"><span data-stu-id="0d5f7-604">All</span></span>
- <span data-ttu-id="0d5f7-605">リボンのキー ヒントのパフォーマンスが大幅に改善されました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-605">We significantly improved the performance of Ribbon KeyTips</span></span>
- <span data-ttu-id="0d5f7-606">「今後のリリース予定を確認」ダイアログが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-606">We fixed an issue which prevented the "See what's coming soon" dialog from being displayed properly</span></span>
- <span data-ttu-id="0d5f7-607">共著ギャラリーのポップアップで写真の位置がずれてしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-607">We fixed an issue which could cause Photos to be misaligned in the Co-auth Gallery flyout</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-608">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-608">Word</span></span> 
- <span data-ttu-id="0d5f7-609">新しいコメントが追加されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-609">We fixed an issue which could sometimes prevent new comments from being added</span></span>
- <span data-ttu-id="0d5f7-610">表がクラッシュすることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-610">We fixed an issue where tables could sometimes cause a crash</span></span>
- <span data-ttu-id="0d5f7-611">無効なデータが差し込み印刷の最後に追加されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-611">We fixed an issue where invalid data could sometimes be added to the end of a mail merge</span></span>
- <span data-ttu-id="0d5f7-612">一部の LaTeX 数式が正しく表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-612">We fixed an issue which could cause some LaTeX equations to render incorrectly</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-613">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-613">Excel</span></span>
- <span data-ttu-id="0d5f7-614">グラフの種類を変更するとランタイム例外が発生することがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-614">We fixed an issue where changing chart types could sometimes result in a runtime exception</span></span>
- <span data-ttu-id="0d5f7-615">複数のウィンドウを開いたときに正しくないリボンが表示されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-615">We fixed an issue where the incorrect ribbon could be displayed when multiple windows were open</span></span>
- <span data-ttu-id="0d5f7-616">マクロがブックの 2 番目のインスタンスを開いたときにエラーが発生することがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-616">We fixed an issue which could cause an error when a macro opened a second instance of a workbook</span></span>
- <span data-ttu-id="0d5f7-617">ブックを開いたり作成したりするとき、またはブックを切り替えるときにクラッシュすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-617">We fixed an issue which could cause a crash when opening or creating a workbook, or switching between workbooks</span></span>
- <span data-ttu-id="0d5f7-618">ユーザーが Word で作成した PDF を Teams で開くことができない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-618">We fixed an issue preventing users from opening a PDF created from Word in Teams</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-619">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-619">PowerPoint</span></span>
- <span data-ttu-id="0d5f7-620">PDF にエクスポートすると、グラフの品質が低下する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-620">We fixed an issue which would degrade the quality of a chart when exported to a pdf</span></span>
- <span data-ttu-id="0d5f7-621">中心までの距離を示すヒントが表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-621">We fixed an issue which prevented a tooltip indicating the distance to center from displaying</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-622">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-622">Outlook</span></span>
- <span data-ttu-id="0d5f7-623">ディスクの領域不足エラーが表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-623">We fixed an issue which could sometimes prevent a Disk Full error to be displayed</span></span>
- <span data-ttu-id="0d5f7-624">会議出席依頼を更新する際に添付ファイルが複製されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-624">We fixed an issue which could cause attachments to become duplicated when updating a meeting request</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-625">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-625">Access</span></span>
- <span data-ttu-id="0d5f7-626">一部のクエリが大きい整数値を返さない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-626">We fixed an issue which prevented some queries from returning large integer values</span></span>
- <span data-ttu-id="0d5f7-627">SQL テキストボックスが編集できなくなることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-627">We fixed an issue which could make the sql textbox uneditable</span></span>
- <span data-ttu-id="0d5f7-628">一部の高 DPI ディスプレイでは、ヒントが見づらいことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-628">We fixed an issue where tooltips could be difficult to see on some High DPI displays</span></span>

### <a name="project"></a><span data-ttu-id="0d5f7-629">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-629">Project</span></span>
- <span data-ttu-id="0d5f7-630">新しいタスクでフラグの値が編集できなくなることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-630">We fixed an issue which could cause flag values to become uneditable in new tasks</span></span>
- <span data-ttu-id="0d5f7-631">ステータスの更新によって割り当てとタスクの実際の開始日が不適切に設定されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-631">We fixed an issue which could cause a status update to improperly set Actual Start Date on Assignments and Tasks</span></span>
- <span data-ttu-id="0d5f7-632">一部のリソースが間違って割り当て超過に表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-632">We fixed an issue which could cause some resources to incorreclty appear overallocated</span></span>
- <span data-ttu-id="0d5f7-633">ラグが追加され、小数点の記号がカンマで、サーバーに接続されていると TaskDependencies Add メソッドが失敗することがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-633">We fixed an issue where the TaskDependencies Add method could fail when Lag is added, the decimal separator is a comma, and when connected to a server</span></span>
- <span data-ttu-id="0d5f7-634">CSOM を使用してローカル ユーザー設定フィールドの参照テーブルの値を更新すると PCS がクラッシュすることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-634">We fixed an issue where updating local custom field lookup table values via CSOM could crash PCS</span></span>
- <span data-ttu-id="0d5f7-635">作業時間の合計値に小数点が含まれる場合に正しく表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-635">We fixed an issue where the total work values may appear incorrect if they contain a decimal</span></span>

</BR></BR>

## <a name="june-28-2019"></a><span data-ttu-id="0d5f7-636">2019 年 6 月 28 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-636">June 28, 2019</span></span>
<span data-ttu-id="0d5f7-637">バージョン 1907 (ビルド 11819.20002)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-637">Version 1907 (build 11819.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="0d5f7-638">新機能:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-638">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-639">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-639">Excel</span></span>

- <span data-ttu-id="0d5f7-640">**Power Query の機能強化を使用して素早くコーディングする:** オートコンプリートと構文の色分けを使用して、素早くコーディングを完了します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-640">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="0d5f7-641">関数、列、パラメーターも簡単に見つけることができます</span><span class="sxs-lookup"><span data-stu-id="0d5f7-641">Easily discover functions, columns, and parameters, too</span></span>

- <span data-ttu-id="0d5f7-642">**類似列のテーブルを結合する:** 取得と変換 (Power Query) では、テーブルを結合するために列を比較するときに、近似テキスト マッチング ロジック (あいまい一致とも呼ばれる) が使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-642">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-643">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-643">Word</span></span>

- <span data-ttu-id="0d5f7-644">**共同編集の改善:** 共同編集時の信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-644">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>
 
### <a name="word-excel-powerpoint-and-visio"></a><span data-ttu-id="0d5f7-645">Word、Excel、PowerPoint、Visio</span><span class="sxs-lookup"><span data-stu-id="0d5f7-645">Word, Excel, PowerPoint, and Visio</span></span>

#### <a name="recommended-documents"></a><span data-ttu-id="0d5f7-646">推奨されるドキュメント</span><span class="sxs-lookup"><span data-stu-id="0d5f7-646">Recommended Documents</span></span>

<span data-ttu-id="0d5f7-647">推奨される関連アクティビティを含むドキュメントをご確認ください。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-647">Find documents with relevant activity recommended to you.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="0d5f7-648">主な修正:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-648">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-649">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-649">Word</span></span> 
- <span data-ttu-id="0d5f7-650">一部の .DOC を開くことができない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-650">We fixed an issue which could prevent some .DOC files from opening</span></span>
- <span data-ttu-id="0d5f7-651">コメントが正常に読み込まれない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-651">We fixed an issue which could have prevented comments from loading properly</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-652">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-652">Excel</span></span>
- <span data-ttu-id="0d5f7-653">Power Query のパフォーマンスが向上しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-653">We improved the performance of Power Queries</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-654">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-654">PowerPoint</span></span>
- <span data-ttu-id="0d5f7-655">画面のちらつきの原因となる、Surface デバイスでのペン使用に関連する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-655">We fixed an issue related to using a pen on a Surface device which could cause the screen to flicker</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-656">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-656">Outlook</span></span>
- <span data-ttu-id="0d5f7-657">会議に変換すると、予定の空き時間情報が変更される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-657">We fixed an issue which could change the free/busy status of an appointment when converted to a meeting</span></span>
- <span data-ttu-id="0d5f7-658">電子メールがアドホック テンプレートで保護されている場合に、不適切なテンプレートと説明が表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-658">We fixed an issue where the wrong template and description would be displayed when an e-mail was protected with an ad-hoc template</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-659">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-659">Access</span></span>
- <span data-ttu-id="0d5f7-660">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-660">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="0d5f7-661">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-661">Project</span></span>
- <span data-ttu-id="0d5f7-662">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-662">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-21-2019"></a><span data-ttu-id="0d5f7-663">2019 年 6 月 21 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-663">June 21, 2019</span></span>
<span data-ttu-id="0d5f7-664">バージョン 1907 (ビルド 11815.20002)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-664">Version 1907 (build 11815.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="0d5f7-665">新機能:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-665">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-666">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-666">Outlook</span></span>

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a><span data-ttu-id="0d5f7-667">Outlook デスクトップにおける黒のテーマでの濃色モード</span><span class="sxs-lookup"><span data-stu-id="0d5f7-667">Dark Mode for Black Theme in Outlook Desktop</span></span>

<span data-ttu-id="0d5f7-668">[濃色] モードで黒のテーマを使用しているユーザーには、電子メールを読むときに [閲覧] ウィンドウは暗く表示され、メールを作成するときも同様に表示されます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-668">With dark mode, users in black theme will now also see the reading pane with a dark background when reading emails, and the compose experience with a dark background when writing emails.</span></span> <span data-ttu-id="0d5f7-669">ユーザーが明るい背景でメッセージがどのように見えるかを確認する場合に備えて、[閲覧] ウィンドウとリボンに [太陽/月] トグルがあります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-669">There is a sun/moon toggle on the reading pane and in the ribbon in case users want to preview what the message looks like with a light background instead.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="0d5f7-670">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-670">Getting Started:</span></span>

1. <span data-ttu-id="0d5f7-671">[黒のテーマ] に切り替えると、既定では濃色モードになります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-671">Turn on black theme and dark mode will be on by default.</span></span>
2. <span data-ttu-id="0d5f7-672">(閲覧ウィンドウとリボンにある) [月/太陽] トグルを使用して、濃色モードでないユーザーにメッセージがどのように見えるかを表示します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-672">Use the moon/sun toggle (in the reading pane and in the ribbon) to preview what the message looks like for users not in dark mode</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="0d5f7-673">次の操作を試してみてください</span><span class="sxs-lookup"><span data-stu-id="0d5f7-673">Scenarios to Try</span></span>

1. <span data-ttu-id="0d5f7-674">濃色モードでメールを読みます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-674">Read emails in dark mode.</span></span> <span data-ttu-id="0d5f7-675">何も見えない場合は、[閲覧] ウィンドウの [太陽] トグルを使用して、背景を明るくします。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-675">If you are unable to read something, use the sun toggle in the Reading Pane to switch to a light background.</span></span> 
2. <span data-ttu-id="0d5f7-676">[濃色] モードでメールを作成します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-676">Compose emails in dark mode.</span></span> <span data-ttu-id="0d5f7-677">リボンの [太陽] トグルを使用して、メッセージが明るい背景でどのように見えるかを確認します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-677">Preview what your message will look like with a light background by using the sun toggle in the ribbon.</span></span> 

<span data-ttu-id="0d5f7-678">正常に表示されないメールが見つかった場合は、(添付ファイルとして) OutlookDarkModeFail@service.microsoft.com に送信してください</span><span class="sxs-lookup"><span data-stu-id="0d5f7-678">If you encounter any emails that don't render properly, please send them (as an attachment) to OutlookDarkModeFail@service.microsoft.com</span></span>

#### <a name="get-location-suggestions"></a><span data-ttu-id="0d5f7-679">場所の候補を取得する</span><span class="sxs-lookup"><span data-stu-id="0d5f7-679">Get location suggestions</span></span>

<span data-ttu-id="0d5f7-680">入力を開始すると、Outlook で一致する場所が検索されます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-680">Start typing and Outlook will look for matching locations.</span></span>

<span data-ttu-id="0d5f7-681">予定や会議を作成するときは、[場所] フィールドに適用されます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-681">This applies to the Location field when creating Appointments and Meetings.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="0d5f7-682">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-682">Getting Started:</span></span>

- <span data-ttu-id="0d5f7-683">Outlook で O365 または Outlook.com の予定表に予定や会議を作成します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-683">Create an Appointment or Meeting on an O365 or Outlook.com calendar in Outlook.</span></span> 
- <span data-ttu-id="0d5f7-684">[場所] フィールドをクリックして、入力を開始します...。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-684">Click into the Location field and start typing…</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="0d5f7-685">次の操作を試してみてください</span><span class="sxs-lookup"><span data-stu-id="0d5f7-685">Scenarios to Try</span></span>

<span data-ttu-id="0d5f7-686">会議に会議室を追加するときは、[会議室の検索] アドインやアドレス帳を使用するのではなく、[場所] フィールドをクリックします。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-686">When adding a conference room to a meeting, click into Location field, rather than using Room Finder add-in or Address Book.</span></span>
<span data-ttu-id="0d5f7-687">レストラン、喫茶店、歯科医院といった公共の場所での予定がある場合は、新しいピッカーを使用して正確な位置を見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-687">For appointments at a physical place with a public location - like a restaurant, coffee shop, or even your dentist's office - try finding the exact location using the new picker.</span></span> <span data-ttu-id="0d5f7-688">こうすることで、外出するときに Outlook Mobile で通知を受け取ることができます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-688">This way, you'll be able to get notified on Outlook Mobile when it's time to leave.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="0d5f7-689">主な修正:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-689">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="0d5f7-690">すべて</span><span class="sxs-lookup"><span data-stu-id="0d5f7-690">All</span></span>
- <span data-ttu-id="0d5f7-691">オフラインで [検索] ボックスが有効なままになる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-691">We fixed an issue which would keep the Search Box enabled while offline</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-692">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-692">Word</span></span> 
- <span data-ttu-id="0d5f7-693">キーボード フォーカスが表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-693">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>
- <span data-ttu-id="0d5f7-694">新しいドキュメントにテキストを貼り付けたときに、テキストが間違えて配置される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-694">We fixed an issue where text pasted into a new document could sometimes have the wrong text alignment</span></span>
- <span data-ttu-id="0d5f7-695">コンピューターを中断した後に、一部のユーザーが変更を保存できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-695">We fixed an issue which could prevent some users from saving changes after suspending their computer</span></span>
- <span data-ttu-id="0d5f7-696">特定の場合に、選択したページの代わりにドキュメント全体が印刷される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-696">We fixed an issue where in certain cases an entire document would be printed instead of the selected range</span></span>
- <span data-ttu-id="0d5f7-697">小さなディスプレイでコメントが読みにくくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-697">We fixed an issue which could make comments difficult to read on smaller displays</span></span>
- <span data-ttu-id="0d5f7-698">デバイスにキャプチャするときにクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-698">We fixed an issue which could cause a crash when capturing to a device</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-699">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-699">Excel</span></span>
- <span data-ttu-id="0d5f7-700">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-700">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-701">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-701">PowerPoint</span></span>
- <span data-ttu-id="0d5f7-702">キーボード フォーカスが表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-702">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-703">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-703">Outlook</span></span>
- <span data-ttu-id="0d5f7-704">有効ではないときにアドインが誤って有効になっていると表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-704">We fixed an issue which could incorrectly display an add-in as being enabled when it was not.</span></span>
- <span data-ttu-id="0d5f7-705">多数の保持ポリシーが表示されていない場合、ユーザーがすべての保持ポリシーを表示できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-705">We fixed an issue which would prevent a customer from viewing all retention policies if there were a large number of them</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-706">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-706">Access</span></span>
- <span data-ttu-id="0d5f7-707">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-707">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="0d5f7-708">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-708">Project</span></span>
- <span data-ttu-id="0d5f7-709">さまざまなパフォーマンスと安定性に関する修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-709">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-14-2019"></a><span data-ttu-id="0d5f7-710">2019 年 6 月 14 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-710">June 14, 2019</span></span>
<span data-ttu-id="0d5f7-711">バージョン 1907 (ビルド 11807.20000)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-711">Version 1907 (build 11807.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="0d5f7-712">主な修正:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-712">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-713">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-713">Word</span></span> 
- <span data-ttu-id="0d5f7-714">OneDrive に保存しているときにユーザーがサインインするのを妨げていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-714">We fixed an issue which could prevent a user from signing in when saving to OneDrive</span></span>
- <span data-ttu-id="0d5f7-715">アクセス制限モード中にユーザーによる SharePoint のプロパティの変更が妨げられていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-715">We fixed an issue where a user could be prevented from changing SharePoint properties while in restricted access mode</span></span>
- <span data-ttu-id="0d5f7-716">余白を調整しているときにヘッダーやフッターの内容が変更されてしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-716">We fixed an issue where header and footer content could change when adjusting margins</span></span>
- <span data-ttu-id="0d5f7-717">Web ビューに切り替えているときに書式設定が崩れてしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-717">We fixed an issue where formatting could break when switching to web view</span></span>
- <span data-ttu-id="0d5f7-718">SharePoint で開いたときにユーザーによるカスタム フィールドの使用を妨げていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-718">We fixed an issue which could prevent a user from using custom fields when opened from SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-719">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-719">Excel</span></span>
- <span data-ttu-id="0d5f7-720">フィルター処理された行を削除するときのパフォーマンスの問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-720">We fixed a performance issue when deleting rows of a filtered set</span></span>
- <span data-ttu-id="0d5f7-721">時々、保護ビューでマウスをちらつかせる原因になっていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-721">We fixed an issue which could sometimes cause the mouse to flicker in protected view</span></span>
- <span data-ttu-id="0d5f7-722">系列を削除しているときにクラッシュを引き起こしていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-722">We fixed an issue which could have caused a crash when deleting a series</span></span>
- <span data-ttu-id="0d5f7-723">利用できなかった場合に一部のユーザーがバージョン履歴を追加するオプションを使用していたところの問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-723">We fixed an issue where some users would have the option to add version history when that was not available</span></span>
- <span data-ttu-id="0d5f7-724">スプレッドシート比較ツールを使用しているときに例外を引き起こしていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-724">We fixed an issue which could have caused an exception when using the Spreadsheet Compare tool</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-725">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-725">PowerPoint</span></span>
- <span data-ttu-id="0d5f7-726">SharePoint へのリンクをクリックしたときにクラッシュを発生させていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-726">We fixed an issue where a crash could occur when clicking a link to SharePoint</span></span>
- <span data-ttu-id="0d5f7-727">ユーザーが Surface ペンを使用して入力しているのに、次のページに切り替わってしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-727">We fixed an issue which could switch the user to the next page while typing using a Surface Pen</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-728">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-728">Outlook</span></span>
- <span data-ttu-id="0d5f7-729">一部の宛先フィールドが通常より大きくなってしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-729">We fixed an issue where in some cases the To field was larger than normal</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-730">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-730">Access</span></span>
- <span data-ttu-id="0d5f7-731">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-731">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="0d5f7-732">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-732">Project</span></span>
- <span data-ttu-id="0d5f7-733">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-733">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-7-2019"></a><span data-ttu-id="0d5f7-734">2019 年 6 月 7 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-734">June 7, 2019</span></span>
<span data-ttu-id="0d5f7-735">バージョン 1907 (ビルド 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-735">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="0d5f7-736">主な修正:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-736">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-737">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-737">Word</span></span> 
- <span data-ttu-id="0d5f7-738">オートコレクトが文の先頭文字を大文字にするように設定されていると Word がクラッシュする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-738">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="0d5f7-739">SharePoint でドキュメントを編集する際のパフォーマンスが向上しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-739">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="0d5f7-740">Adobe Illustrator で作成されたベクター ベースの画像が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-740">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-741">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-741">Excel</span></span>
- <span data-ttu-id="0d5f7-742">マクロを記録するときに、並べ替えフィールドが正しく設定されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-742">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="0d5f7-743">配列数式の計算中にハングまたはクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-743">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-744">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-744">PowerPoint</span></span>
- <span data-ttu-id="0d5f7-745">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-745">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-746">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-746">Outlook</span></span>
- <span data-ttu-id="0d5f7-747">インライン添付ファイルが誤って拡大縮小されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-747">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-748">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-748">Access</span></span>
- <span data-ttu-id="0d5f7-749">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-749">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="0d5f7-750">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-750">Project</span></span>
- <span data-ttu-id="0d5f7-751">固定期間のタイムシートが割り当て終了日を変更するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-751">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="0d5f7-752">以前のバージョンからプロジェクトを開くと、[完了率] の値が正しくない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-752">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="0d5f7-753">2019 年 5 月 31 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-753">May 31, 2019</span></span>
<span data-ttu-id="0d5f7-754">バージョン 1906 (ビルド 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-754">Version 1906 (build 11722.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="0d5f7-755">新機能:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-755">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-756">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-756">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="0d5f7-757">サポートに問い合わせるためのダイアログがドッキング可能になり、右側に表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-757">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="0d5f7-758">サポートへの問い合わせに使用するダイアログが右側のウィンドウに表示され、最初からドッキングされたウィンドウとして表示されます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-758">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="0d5f7-759">メールでインクを使用する</span><span class="sxs-lookup"><span data-stu-id="0d5f7-759">Ink in Your Email!</span></span>

<span data-ttu-id="0d5f7-760">Outlook メールで画像を描画し、注釈を付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-760">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-761">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-761">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="0d5f7-762">ドキュメント リンクを Word で開く</span><span class="sxs-lookup"><span data-stu-id="0d5f7-762">Open document links in Word</span></span>

<span data-ttu-id="0d5f7-763">Office でドキュメント リンクをクリックしたときに既定で Word アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-763">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="0d5f7-764">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-764">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="0d5f7-765">詳しくは、以下を参照してください。https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="0d5f7-765">Learn more: https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="0d5f7-766">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-766">Getting Started:</span></span>

<span data-ttu-id="0d5f7-767">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-767">Feature will default to off.</span></span> <span data-ttu-id="0d5f7-768">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-768">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="0d5f7-769">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-769">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="0d5f7-770">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-770">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="0d5f7-771">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="0d5f7-771">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="0d5f7-772">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-772">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="0d5f7-773">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-773">Scenarios to Try:</span></span>

<span data-ttu-id="0d5f7-774">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている Word ドキュメントへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-774">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="0d5f7-775">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-775">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-776">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-776">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="0d5f7-777">プレゼンテーションへのリンクを PowerPoint で開く</span><span class="sxs-lookup"><span data-stu-id="0d5f7-777">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="0d5f7-778">Office でプレゼンテーションへのリンクをクリックしたときに既定で PowerPoint アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-778">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="0d5f7-779">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-779">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="0d5f7-780">詳しくは、以下を参照してください。https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="0d5f7-780">Learn more: https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="0d5f7-781">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-781">Getting Started:</span></span>

<span data-ttu-id="0d5f7-782">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-782">Feature will default to off.</span></span> <span data-ttu-id="0d5f7-783">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-783">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="0d5f7-784">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-784">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="0d5f7-785">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-785">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="0d5f7-786">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="0d5f7-786">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="0d5f7-787">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-787">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="0d5f7-788">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-788">Scenarios to Try:</span></span>

<span data-ttu-id="0d5f7-789">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている PowerPoint プレゼンテーションへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-789">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="0d5f7-790">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-790">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-791">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-791">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="0d5f7-792">ブックのリンクを Excel で開く</span><span class="sxs-lookup"><span data-stu-id="0d5f7-792">Open workbook links in Excel</span></span>

<span data-ttu-id="0d5f7-793">Office でブックのリンクをクリックしたときに既定で Excel アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-793">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="0d5f7-794">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-794">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="0d5f7-795">詳細については、以下を参照してください。https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="0d5f7-795">Learn More: https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="0d5f7-796">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-796">Getting Started:</span></span>

<span data-ttu-id="0d5f7-797">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-797">Feature will default to off.</span></span> <span data-ttu-id="0d5f7-798">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-798">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="0d5f7-799">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-799">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="0d5f7-800">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-800">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="0d5f7-801">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="0d5f7-801">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="0d5f7-802">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-802">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="0d5f7-803">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-803">Scenarios to Try:</span></span>

<span data-ttu-id="0d5f7-804">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている Excel ブックへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-804">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="0d5f7-805">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-805">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="0d5f7-806">主な修正:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-806">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="0d5f7-807">すべて</span><span class="sxs-lookup"><span data-stu-id="0d5f7-807">All</span></span>
- <span data-ttu-id="0d5f7-808">自動保存が無効になっている場合でも、ファイルが自動保存されてしまう場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-808">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-809">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-809">Word</span></span> 
- <span data-ttu-id="0d5f7-810">一部のユーザーがファイルを SharePoint に保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-810">We fixed an issue which may have prevented some users from saving to SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-811">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-811">Excel</span></span>
- <span data-ttu-id="0d5f7-812">無効なフィルターに間違ったアイコンが表示される場合がある問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-812">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-813">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-813">PowerPoint</span></span>
- <span data-ttu-id="0d5f7-814">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-814">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-815">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-815">Outlook</span></span>
- <span data-ttu-id="0d5f7-816">グループ スケジュール ビューで一部のユーザーがオフラインとして間違って表示される問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-816">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="0d5f7-817">末尾にスペースが挿入されている URL が SafeLink で解析できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-817">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="0d5f7-818">業務時間外に部屋が利用可能と表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-818">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-819">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-819">Access</span></span>
- <span data-ttu-id="0d5f7-820">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-820">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="0d5f7-821">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-821">Project</span></span>
- <span data-ttu-id="0d5f7-822">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-822">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="0d5f7-823">2019 年 5 月 24 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-823">May 24, 2019</span></span>
<span data-ttu-id="0d5f7-824">バージョン 1906 (ビルド 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-824">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="0d5f7-825">新機能:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-825">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="0d5f7-826">ユーザー エクスペリエンスの更新</span><span class="sxs-lookup"><span data-stu-id="0d5f7-826">User Experience Updates</span></span>

<span data-ttu-id="0d5f7-827">近日公開となっていた更新プログラムが公開されました。この更新には、シンプル リボンおよびフォルダー ウィンドウ、メッセージ一覧、閲覧ウィンドウの外観の更新が含まれます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-827">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="0d5f7-828">主な修正:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-828">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="0d5f7-829">すべて</span><span class="sxs-lookup"><span data-stu-id="0d5f7-829">All</span></span>

- <span data-ttu-id="0d5f7-830">チャットウィンドウが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-830">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-831">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-831">Word</span></span> 
- <span data-ttu-id="0d5f7-832">Word で文法エラーのテキストが誤って強調表示されることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-832">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-833">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-833">Excel</span></span>
- <span data-ttu-id="0d5f7-834">誤ったアイコンがグラフ要素に使用されているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-834">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="0d5f7-835">同じブックが既に開いているときに、不正なブックが VBA スクリプトでアクティブになるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-835">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-836">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-836">PowerPoint</span></span>
- <span data-ttu-id="0d5f7-837">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-837">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-838">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-838">Outlook</span></span>
- <span data-ttu-id="0d5f7-839">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-839">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-840">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-840">Access</span></span>
- <span data-ttu-id="0d5f7-841">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-841">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="0d5f7-842">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-842">Project</span></span>
- <span data-ttu-id="0d5f7-843">タスクバーに切り替えた後、Project がクラッシュする可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-843">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="0d5f7-844">2019 年 5 月 17 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-844">May 17, 2019</span></span>
<span data-ttu-id="0d5f7-845">バージョン 1906 (ビルド 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-845">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="0d5f7-846">新機能:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-846">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-847">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-847">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="0d5f7-848">ユーザー エクスペリエンスのアップデート</span><span class="sxs-lookup"><span data-stu-id="0d5f7-848">User Experience Updates</span></span>

<span data-ttu-id="0d5f7-849">近日公開となっていた更新プログラムが公開されました。この更新には、シンプル リボンおよびフォルダー ウィンドウ、メッセージ一覧、閲覧ウィンドウの外観の更新が含まれます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-849">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="0d5f7-850">利用するには:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-850">Getting Started:</span></span>

<span data-ttu-id="0d5f7-851">これらの変更は、新しい既定の UI の一部になります。この新しい UI は、すべての運用環境ユーザー向けに [近日公開] スイッチで 12 月中旬以来提供されてきました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-851">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="0d5f7-852">カスタマイズ可能なシンプル リボン</span><span class="sxs-lookup"><span data-stu-id="0d5f7-852">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="0d5f7-853">従来のビューとシンプルなビューの切り替えやコマンドの固定または固定解除を簡単にできます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-853">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="0d5f7-854">利用するには:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-854">Getting Started:</span></span>

<span data-ttu-id="0d5f7-855">シンプル リボンを使用するには、まず [近日公開] 機能をオンにし、リボンの山形マークをクリックして従来の複数行のリボンと新しい 1 行のシンプル リボンを切り替えます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-855">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="0d5f7-856">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-856">Scenarios to Try:</span></span>

<span data-ttu-id="0d5f7-857">従来のリボンからシンプル リボンに切り替える</span><span class="sxs-lookup"><span data-stu-id="0d5f7-857">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="0d5f7-858">お気に入りの操作を選択する</span><span class="sxs-lookup"><span data-stu-id="0d5f7-858">Pick your favorite action</span></span>

<span data-ttu-id="0d5f7-859">[フラグ] 機能や [削除] 機能はお使いになられていないかもしれません。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-859">Don't use Flag and Delete?</span></span> <span data-ttu-id="0d5f7-860">アーカイブまたは既読に​​しますか?</span><span class="sxs-lookup"><span data-stu-id="0d5f7-860">How about Archive or Mark as Read?</span></span> <span data-ttu-id="0d5f7-861">クイック操作メニューをカスタマイズしてよく使うコマンドを追加できます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-861">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="0d5f7-862">利用するには:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-862">Getting Started:</span></span>

<span data-ttu-id="0d5f7-863">希望のクイック操作を選ぶには、メッセージ一覧でメールを右クリックし、コンテキスト メニューを表示します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-863">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="0d5f7-864">次に、[クイック操作の設定] をクリックします。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-864">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="0d5f7-865">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-865">Scenarios to Try:</span></span>

<span data-ttu-id="0d5f7-866">既定の設定を [フラグ] または [削除] から [アーカイブ]、[移動]、[既読にする]、または [なし] に変更すると、メッセージ一覧をすっきりした外観にできます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-866">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="0d5f7-867">レイアウトの間隔を</span><span class="sxs-lookup"><span data-stu-id="0d5f7-867">Relaxed or tighter layout?</span></span> <span data-ttu-id="0d5f7-868">自由に選べます</span><span class="sxs-lookup"><span data-stu-id="0d5f7-868">You choose</span></span>

<span data-ttu-id="0d5f7-869">[狭い間隔を使用] オプションを使用すると、アイテム間のスペースを広く取るか、間隔の狭いレイアウトでより多くのアイテムを表示するかを選べます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-869">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="0d5f7-870">利用するには:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-870">Getting Started:</span></span>

<span data-ttu-id="0d5f7-871">従来のリボンの場合、[表示] タブの [メッセージ] グループで、[狭い間隔を使用] チェックボックスをオンにします。シンプル リボンの場合は、[現在のビュー] 設定で [狭い間隔を使用] を選択します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-871">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="0d5f7-872">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-872">Scenarios to Try:</span></span>

<span data-ttu-id="0d5f7-873">Outlook で、この設定をオフにした状態でメッセージをトリアージしたり作成したりしてみます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-873">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="0d5f7-874">この機能をオンにすると、1 ページに収まるメッセージの数が増え、新規作成フォームのコントロールの表示がすっきりとします。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-874">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="0d5f7-875">Onedrive 同期クライアントを使用する際の MRU エントリの重複を除去する</span><span class="sxs-lookup"><span data-stu-id="0d5f7-875">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="0d5f7-876">クラウド添付ファイルを使用すると、MRU エントリの重複を除去できるため、Onedrive の統合を効率化できます。クラウド添付ファイルを使用すれば、同期されたデータでコピーの添付をする動作が早くなります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-876">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="0d5f7-877">利用するには:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-877">Getting Started:</span></span>

<span data-ttu-id="0d5f7-878">OneDrive 同期クライアントを使用している場合は、添付ファイル MRU に重複ファイルが表示されなくなります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-878">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="0d5f7-879">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-879">Scenarios to Try:</span></span>

<span data-ttu-id="0d5f7-880">OneDrive 同期クライアントを有効にして、Outlook デスクトップで [ファイルの添付] メニューを使用する</span><span class="sxs-lookup"><span data-stu-id="0d5f7-880">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="0d5f7-881">フォルダーを多数含むメールボックスでの共有フォルダーの同期が改善されました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-881">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="0d5f7-882">長い間、Outlook での共有メールボックスの同期は、最大で 500 フォルダーに制限されてきました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-882">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="0d5f7-883">この変更により Outlook の改善が行われ、同期をする際の 500 フォルダーの制限がなくなりました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-883">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="0d5f7-884">利用するには:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-884">Getting Started:</span></span>

<span data-ttu-id="0d5f7-885">メールボックスにフォルダーを 1000 個作成し、誰か他のユーザーにそのメールボックスへのアクセスを許可し、このユーザーの Outlook プロファイルを作成します。同期が正常に動作することを確認します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-885">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-886">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-886">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="0d5f7-887">少しだけ消す</span><span class="sxs-lookup"><span data-stu-id="0d5f7-887">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="0d5f7-888">利用するには:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-888">Getting Started:</span></span>

<span data-ttu-id="0d5f7-889">[描画] タブに移動します。 [消しゴム] ドロップダウンを選択します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-889">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="0d5f7-890">[消しゴム (小)] または [消しゴム (中)] を選びます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-890">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="0d5f7-891">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-891">Scenarios to Try:</span></span>

<span data-ttu-id="0d5f7-892">[描画] タブに移動します。ペンを選びます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-892">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="0d5f7-893">インク ストロークを描きます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-893">Draw an ink stroke.</span></span> <span data-ttu-id="0d5f7-894">[消しゴム] ドロップダウンを選択します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-894">Select the Eraser dropdown.</span></span> <span data-ttu-id="0d5f7-895">[消しゴム (小)] または [消しゴム (中)] を選びます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-895">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="0d5f7-896">インク ストロークを少しだけ消してみます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-896">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="0d5f7-897">主な修正:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-897">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="0d5f7-898">すべて</span><span class="sxs-lookup"><span data-stu-id="0d5f7-898">All</span></span> 
- <span data-ttu-id="0d5f7-899">一部のユーザーが PDF として保存できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-899">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="0d5f7-900">32 ビット システムでの大容量ファイルの保存に影響する場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-900">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-901">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-901">Word</span></span> 
- <span data-ttu-id="0d5f7-902">音声入力機能の応答性が大幅に向上されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-902">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-903">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-903">Excel</span></span>
- <span data-ttu-id="0d5f7-904">タッチ スクリーン デバイスでダブルクリック イベントが失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-904">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="0d5f7-905">一部のユーザーが VBA マクロを編集できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-905">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="0d5f7-906">スライサーを使用した際にパフォーマンスに影響する場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-906">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-907">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-907">PowerPoint</span></span>
- <span data-ttu-id="0d5f7-908">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-908">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-909">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-909">Outlook</span></span>
- <span data-ttu-id="0d5f7-910">選択したテンプレートとは異なるテンプレートが表示される場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-910">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-911">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-911">Access</span></span>
- <span data-ttu-id="0d5f7-912">長いリッチ テキストの表示に Zoom Builder を使うと、読みづらくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-912">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="0d5f7-913">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-913">Project</span></span>
- <span data-ttu-id="0d5f7-914">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-914">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="0d5f7-915">2019 年 5 月 10日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-915">May 10, 2019</span></span>
<span data-ttu-id="0d5f7-916">バージョン 1906 (ビルド 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-916">Version 1906 (build 11702.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="0d5f7-917">新機能:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-917">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-918">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-918">Outlook</span></span>

<span data-ttu-id="0d5f7-919">**より多くのメッセージを画面に収める:** [表示] > [より狭い文字間隔を使用] の順に選択し、メッセージの間隔を調整します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-919">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="0d5f7-920">主な修正:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-920">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="0d5f7-921">すべて</span><span class="sxs-lookup"><span data-stu-id="0d5f7-921">All</span></span>
- <span data-ttu-id="0d5f7-922">[名前を付けて保存] ダイアログボックスに誤ったパスが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-922">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-923">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-923">Word</span></span> 
- <span data-ttu-id="0d5f7-924">操作アシストからの一部の選択が挿入されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-924">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-925">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-925">Excel</span></span>
- <span data-ttu-id="0d5f7-926">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-926">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-927">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-927">PowerPoint</span></span>
- <span data-ttu-id="0d5f7-928">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-928">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-929">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-929">Outlook</span></span>
- <span data-ttu-id="0d5f7-930">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-930">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-931">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-931">Access</span></span>
- <span data-ttu-id="0d5f7-932">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-932">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="0d5f7-933">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-933">Project</span></span>
- <span data-ttu-id="0d5f7-934">タスク ID の確認に強調表示が必要となる可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-934">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="0d5f7-935">2019 年 5 月 3日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-935">May 3, 2019</span></span>
<span data-ttu-id="0d5f7-936">バージョン 1906 (ビルド 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-936">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="0d5f7-937">新機能:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-937">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-938">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-938">Outlook</span></span>

<span data-ttu-id="0d5f7-939">**すべての暗号化オプションを1か所で:** [オプション] > [暗号化] の順に移動して、メール メッセージを保護する方法を選択します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-939">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="0d5f7-940">主な修正:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-940">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="0d5f7-941">すべて</span><span class="sxs-lookup"><span data-stu-id="0d5f7-941">All</span></span>
- <span data-ttu-id="0d5f7-942">一部のユーザーが OneDrive for Business との同期で問題が発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-942">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-943">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-943">Word</span></span> 
- <span data-ttu-id="0d5f7-944">Word の起動に時間がかかる場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-944">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-945">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-945">Excel</span></span>
- <span data-ttu-id="0d5f7-946">新しいバージョンの Excel にアップグレードした後、ブックから外部リンクが削除されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-946">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="0d5f7-947">一部のユーザーが新しいワークブックでセルを選択するのが困難な問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-947">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-948">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-948">PowerPoint</span></span>
- <span data-ttu-id="0d5f7-949">図面をテキストに変換するときにフォントサイズが一致しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-949">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-950">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-950">Outlook</span></span>
- <span data-ttu-id="0d5f7-951">a .VCF ファイルから連絡先を保存すると空のフィールドが発生する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-951">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="0d5f7-952">送信されていても、送信トレイ フォルダーにメッセージが残ってしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-952">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="0d5f7-953">DRM メッセージの表示中に Outlook がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-953">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-954">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-954">Access</span></span>
- <span data-ttu-id="0d5f7-955">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-955">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="0d5f7-956">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-956">Project</span></span>
- <span data-ttu-id="0d5f7-957">エディターが中国語から英語に切り替わる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-957">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="0d5f7-958">マスター プロジェクトの公開コピーに未公開タスクが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-958">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="0d5f7-959">2019 年 4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-959">April 26, 2019</span></span>
<span data-ttu-id="0d5f7-960">バージョン 1905 (ビルド 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-960">Version 1905 (build 11617.20002)</span></span>

## <a name="new-features"></a><span data-ttu-id="0d5f7-961">新機能</span><span class="sxs-lookup"><span data-stu-id="0d5f7-961">New Features</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-962">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-962">Outlook</span></span>

<span data-ttu-id="0d5f7-963">**共有カレンダーの更新がより速く**: Office 365 の共有カレンダーの場合、Outlook は REST API を使用してこれらのカレンダーを更新できます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-963">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="0d5f7-964">共有カレンダーのより高速で信頼性の高い更新を行うには、プレビューを有効にします。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-964">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-965">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-965">Excel</span></span>

#### <a name="coauthoring-improvements"></a><span data-ttu-id="0d5f7-966">共同編集の改善</span><span class="sxs-lookup"><span data-stu-id="0d5f7-966">Coauthoring improvements</span></span>

<span data-ttu-id="0d5f7-967">他のユーザーがリアルタイムでコンテンツの変更を受け取れるようにすることで、共同編集のエクスペリエンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-967">Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

### <a name="visio"></a><span data-ttu-id="0d5f7-968">Visio</span><span class="sxs-lookup"><span data-stu-id="0d5f7-968">Visio</span></span>

- <span data-ttu-id="0d5f7-969">**Power BI から Visio ビジュアルをエクスポートする:** PDF、PowerPoint のファイルなどの Power BI レポートをエクスポートするときに、Power BI 用の Visio Visual が正しく表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-969">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="0d5f7-970">主な修正:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-970">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-971">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-971">Word</span></span> 
- <span data-ttu-id="0d5f7-972">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-972">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-973">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-973">Excel</span></span>
- <span data-ttu-id="0d5f7-974">ソルバー マクロの実行が失敗するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-974">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="0d5f7-975">Excel ファイルを SharePoint にインポートできないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-975">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-976">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-976">PowerPoint</span></span>
- <span data-ttu-id="0d5f7-977">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-977">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-978">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-978">Outlook</span></span>
- <span data-ttu-id="0d5f7-979">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-979">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-980">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-980">Access</span></span>
- <span data-ttu-id="0d5f7-981">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-981">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="0d5f7-982">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-982">Project</span></span>
- <span data-ttu-id="0d5f7-983">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-983">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="0d5f7-984">2019 年 4 月 19 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-984">April 19, 2019</span></span>
<span data-ttu-id="0d5f7-985">バージョン 1905 (ビルド 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-985">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="0d5f7-986">新機能:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-986">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-987">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-987">Outlook</span></span>

<span data-ttu-id="0d5f7-988">**人物を検索するときにメールの候補を取得する:** [検索] ボックスに人の名前を入力すると、最も関連性の高いメール メッセージが検索候補に含まれます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-988">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-989">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-989">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="0d5f7-990">データ型を使用した塗り分けマップのエクスペリエンス向上</span><span class="sxs-lookup"><span data-stu-id="0d5f7-990">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="0d5f7-991">この機能は、Excel の地理データ型を使用して、塗り分けされたマップ グラフにプロットするユーザーのための機能強化です。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-991">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="0d5f7-992">エンドユーザーにとっては、機能とエンドユーザーがマップする領域の精度向上とがより高度に統合されたことが利点です。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-992">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="0d5f7-993">さらに、ポリゴンで都市をマッピングする機能も含まれてます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-993">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="0d5f7-994">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-994">Getting Started:</span></span>

- <span data-ttu-id="0d5f7-995">この機能は、Excel 内の既存の機能を改善したものです。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-995">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="0d5f7-996">この改善を使用するには、位置をリッチエンティティに変換し、塗り分けマップでプロットします。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-996">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="0d5f7-997">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-997">Scenarios to Try:</span></span>

- <span data-ttu-id="0d5f7-998">ユーザーは、都市、州、都道府県、国、郵便番号のマッピングを試すことができます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-998">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="0d5f7-999">主な修正:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-999">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="0d5f7-1000">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1000">All Applications</span></span>
- <span data-ttu-id="0d5f7-1001">アプリケーションが起動したときに最初の実行ダイアログが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1001">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="0d5f7-1002">[名前を付けて保存] ダイアログボックス内の SharePoint リンクが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1002">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="0d5f7-1003">ユーザーが [今すぐ修復] ダイアログを誤って表示する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1003">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-1004">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1004">Word</span></span> 
- <span data-ttu-id="0d5f7-1005">フォントの要求時に、一部のユーザーがメモリ不足またはディスク領域のエラーを受信する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1005">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="0d5f7-1006">[コメント] ウィンドウから切り替えたときにウィンドウがフォーカスを失う可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1006">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-1007">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1007">Excel</span></span>
- <span data-ttu-id="0d5f7-1008">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1008">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-1009">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1009">PowerPoint</span></span>
- <span data-ttu-id="0d5f7-1010">ブランド化された図形のサイズ変更ができない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1010">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="0d5f7-1011">保護ビューモードでファイルを開くときに PowerPoint がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1011">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-1012">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1012">Outlook</span></span>
- <span data-ttu-id="0d5f7-1013">一部のユーザーが中国語の単語を選択できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1013">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="0d5f7-1014">有効期限が正しく計算されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1014">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-1015">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1015">Access</span></span>
- <span data-ttu-id="0d5f7-1016">一部のユーザーがマクロ ビルダーを使用できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1016">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="0d5f7-1017">レポートを印刷すると最初のページしか印刷されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1017">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="0d5f7-1018">ハイパーリンクの上にカーソルを置くとアプリケーションがクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1018">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="0d5f7-1019">リレーションシップ ビューを使用すると、一部のアイテムが画面外に表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1019">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="0d5f7-1020">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1020">Project</span></span>
- <span data-ttu-id="0d5f7-1021">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1021">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="0d5f7-1022">2019 年 4 月 12 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1022">April 12, 2019</span></span>
<span data-ttu-id="0d5f7-1023">バージョン 1905 (ビルド 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1023">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="0d5f7-1024">新機能:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1024">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-1025">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1025">Access</span></span>

#### <a name="get-smart-with-microsoft-graph"></a><span data-ttu-id="0d5f7-1026">Microsoft Graph を使用してスマートに作業</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1026">Get smart with Microsoft Graph</span></span>

<span data-ttu-id="0d5f7-1027">インテリジェントなテクノロジを使用して、インテリジェントなデータをインポートしたり、またはデータにリンクしたりして、デスクトップ データベースを作り変えましょう。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1027">Import or link to intelligent data and reinvent your desktop database with Intelligent Technology.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="0d5f7-1028">主な修正:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1028">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="0d5f7-1029">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1029">All Applications</span></span>
 - <span data-ttu-id="0d5f7-1030">一部のユーザーがクラウドの場所にファイルを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1030">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="0d5f7-1031">リボンから間違ったウィンドウが開く問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1031">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-1032">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1032">Word</span></span> 
- <span data-ttu-id="0d5f7-1033">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1033">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-1034">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1034">Excel</span></span>
- <span data-ttu-id="0d5f7-1035">リンクされたデータ型を含まないブックであるにもかかわらず、リンクされたデータ型に対するエラーメッセージが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1035">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="0d5f7-1036">Word 文書内のリンクの URL がオンラインとローカルで表示したときに変更される可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1036">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-1037">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1037">PowerPoint</span></span>
- <span data-ttu-id="0d5f7-1038">[アニメーション] タブで変更を元に戻すと、PowerPoint がクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1038">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-1039">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1039">Outlook</span></span>
- <span data-ttu-id="0d5f7-1040">一部のユーザーがパブリック フォルダー内の連絡先の [メモ] フィールドを変更できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1040">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="0d5f7-1041">失効日と削除日の間に競合が発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1041">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-1042">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1042">Access</span></span>
- <span data-ttu-id="0d5f7-1043">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1043">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="0d5f7-1044">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1044">Project</span></span>
- <span data-ttu-id="0d5f7-1045">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1045">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="0d5f7-1046">2019年4月5日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1046">April 5, 2019</span></span>
<span data-ttu-id="0d5f7-1047">バージョン 1904 (ビルド 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1047">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="0d5f7-1048">新機能:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1048">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-1049">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1049">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="0d5f7-1050">Windows 用の Outlook: 優先受信トレイの設定を設定して共有します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1050">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="0d5f7-1051">優先受信トレイの設定はクラウドに保存されるため、どのコンピューターで Web 上の Outlook for Windows と Outlook を使用しても同じように一貫したエクスペリエンスを楽しめます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1051">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="0d5f7-1052">利用するには:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1052">Getting Started:</span></span>

<span data-ttu-id="0d5f7-1053">[ファイル]、[オプション]、[全般] の順に移動すると、[Outlook の設定をクラウドに保存する] という新しい設定があります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1053">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="0d5f7-1054">ユーザーは、自分の優先受信トレイの設定を他の Outlook Desktop インストールおよび OWA に移動できるようにするには、このチェック ボックスをオンにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1054">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="0d5f7-1055">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1055">Scenarios to Try:</span></span>

<span data-ttu-id="0d5f7-1056">クラウド設定の設定を有効にしているコンピューターで優先受信トレイを変更します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1056">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="0d5f7-1057">OWA に移動して、そこに適用されている設定も確認してください。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1057">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="0d5f7-1058">OWA で優先受信トレイを変更し、デスクトップ Outlook を起動して反映された優先順位を表示します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1058">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-1059">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1059">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="0d5f7-1060">学習ツール モードでは、より多くのページの色が追加でサポートされます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1060">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="0d5f7-1061">Word の学習ツールは、より多くのページ テーマ色を追加し、ページの背景色を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1061">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="0d5f7-1062">多くのユーザーがすべて白、またはすべて黒の背景だと閲覧が難しいという課題があったため、PC と Mac の Word で色の選択肢を拡大しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1062">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="0d5f7-1063">利用するには:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1063">Getting Started:</span></span>

<span data-ttu-id="0d5f7-1064">この操作を行うには、[表示] タブに移動し、[学習ツール]、[ページの色] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1064">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="0d5f7-1065">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1065">Scenarios to Try:</span></span>

<span data-ttu-id="0d5f7-1066">この操作を行うには、[表示] タブに移動し、[学習ツール]、[ページの色] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1066">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-1067">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1067">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="0d5f7-1068">3D アニメーション モデルで創造性を高める</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1068">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="0d5f7-1069">Office では、アニメーションモデルをサポートするようになりました。エディターで再生するので、シートを活用することができます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1069">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="0d5f7-1070">利用するには:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1070">Getting Started:</span></span>

1. <span data-ttu-id="0d5f7-1071">Excel を開く</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1071">Open Excel</span></span>
2. <span data-ttu-id="0d5f7-1072">3D アニメーション モデルを挿入します (まもなく Remix が公開されますが、今はここでアニメーション モデルにアクセスしてください: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1072">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="0d5f7-1073">アニメーション モデルがエディターで再生されるようになります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1073">The animated model will play in the editor!</span></span> <span data-ttu-id="0d5f7-1074">スライドショー モードも再生されるようになりますので、確認してください。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1074">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="0d5f7-1075">[3D 形式] リボンで、モデル内の他のアニメーション シーンを探索する</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1075">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="0d5f7-1076">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1076">Scenarios to Try:</span></span>

1. <span data-ttu-id="0d5f7-1077">アニメーション モデルを挿入し、エディターで再生します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1077">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="0d5f7-1078">アニメーション化されたモデルで使用できるアニメーション シーンについては、シーン ギャラリー ([3D 書式] リボンから利用できます) を参照してください。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1078">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="0d5f7-1079">リボン、フローティング ツール バーまたはスペースバーを介してアニメーションを簡単に再生および一時停止することができます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1079">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="0d5f7-1080">主な修正:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1080">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="0d5f7-1081">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1081">All Applications</span></span>
- <span data-ttu-id="0d5f7-1082">Excel の間違ったアプリ アイコンがコンテキストメニューに表示されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1082">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="0d5f7-1083">アップデートをインストールした後に [ファイル メニュー] ボタンが消えてしまうことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1083">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="0d5f7-1084">ユーザー ライセンスに変更をおよぼす可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1084">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-1085">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1085">Word</span></span> 
- <span data-ttu-id="0d5f7-1086">特定のズーム レベルでテキストが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1086">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-1087">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1087">Excel</span></span>
- <span data-ttu-id="0d5f7-1088">編集後に、ブックを保存するかどうかを確認するメッセージが表示されない問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1088">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="0d5f7-1089">ユーザーがブックを共有している場合に BeforeSave イベントが開始しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1089">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="0d5f7-1090">列のサイズを 6 ピクセル未満に変更すると誤ったエラーメッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1090">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="0d5f7-1091">Excel が Application.Visible フラグを無視する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1091">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="0d5f7-1092">トレースの矢印がアクティブでない固定ウィンドウに残る問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1092">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="0d5f7-1093">ブックを開くときに通貨の日付のセルの書式設定が変わることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1093">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="0d5f7-1094">ツールヒントが突然移動する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1094">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="0d5f7-1095">Power Query エディターのローカライズの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1095">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="0d5f7-1096">ブックを添付ファイルとしてメールで送信するときにブックが削除される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1096">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-1097">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1097">PowerPoint</span></span>
- <span data-ttu-id="0d5f7-1098">図形のコピーに通常以上に時間がかかる問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1098">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-1099">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1099">Outlook</span></span>
- <span data-ttu-id="0d5f7-1100">描画ツールの使用中に Outlook がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1100">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="0d5f7-1101">HTML メールを作成する際のローカライズの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1101">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="0d5f7-1102">下側のウィンドウが選択しにくい問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1102">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-1103">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1103">Access</span></span>
- <span data-ttu-id="0d5f7-1104">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1104">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="0d5f7-1105">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1105">Project</span></span>
- <span data-ttu-id="0d5f7-1106">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1106">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="0d5f7-1107">2019 年 3 月 22 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1107">March 22, 2019</span></span>
<span data-ttu-id="0d5f7-1108">バージョン 1904 (ビルド 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1108">Version 1904 (build 11514.20004)</span></span>

## <a name="new-features"></a><span data-ttu-id="0d5f7-1109">新機能</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1109">New Features</span></span>

- <span data-ttu-id="0d5f7-1110">**プライバシー制御**: 診断データとコネクテッド エクスペリエンス用に新しく更新されて、改善された制御。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1110">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> <span data-ttu-id="0d5f7-1111">詳細 <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span><span class="sxs-lookup"><span data-stu-id="0d5f7-1111">Learn more <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span></span>

- <span data-ttu-id="0d5f7-1112">**新しい外観を備えた Office のアイコン:** シンプルかつ高性能で、インテリジェントな Office のエクスペリエンスを反映するように、Office のアイコンがリニューアルされました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1112">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="0d5f7-1113">主な修正:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1113">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-1114">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1114">Word</span></span> 
- <span data-ttu-id="0d5f7-1115">UI に常に "変更を確認しています" と表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1115">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-1116">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1116">Excel</span></span>
- <span data-ttu-id="0d5f7-1117">ワークシートを移動した後にアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1117">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="0d5f7-1118">PDF 形式で保存した後にアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1118">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="0d5f7-1119">保存ダイアログで韓国語の文字を使用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1119">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-1120">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1120">PowerPoint</span></span>
- <span data-ttu-id="0d5f7-1121">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1121">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-1122">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1122">Outlook</span></span>
- <span data-ttu-id="0d5f7-1123">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1123">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-1124">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1124">Access</span></span>
- <span data-ttu-id="0d5f7-1125">Access で余計なショートカットが作成されるという問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1125">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="0d5f7-1126">リンクされた SharePoint のデータが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1126">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="0d5f7-1127">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1127">Project</span></span>
- <span data-ttu-id="0d5f7-1128">言語設定が中国語から英語に変わる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1128">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="0d5f7-1129">SharePoint に同期するとアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1129">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="0d5f7-1130">2019 年 3 月 15 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1130">March 15, 2019</span></span>
<span data-ttu-id="0d5f7-1131">バージョン 1904 (ビルド 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1131">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="0d5f7-1132">新機能:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1132">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-1133">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1133">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="0d5f7-1134">フォーカス モード</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1134">Focus Mode</span></span>

<span data-ttu-id="0d5f7-1135">気を散らさずに作業に集中するには、[表示]メニューの[フォーカス]に切り替えます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1135">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="0d5f7-1136">Office 365 サブスクリプションが必要です。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1136">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="0d5f7-1137">利用するには:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1137">Getting Started:</span></span>

<span data-ttu-id="0d5f7-1138">リボンのステータス バー [フォーカス] ボタンの [フォーカス] ボタンをタブして表示</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1138">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="0d5f7-1139">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1139">Scenarios to Try:</span></span>

<span data-ttu-id="0d5f7-1140">フォーカス モードにしてフォーカス エクスペリエンスを経験する</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1140">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="0d5f7-1141">主な修正:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1141">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-1142">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1142">Word</span></span> 
- <span data-ttu-id="0d5f7-1143">PDF として保存した文書の画像に間違った DPI が設定される問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1143">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-1144">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1144">Excel</span></span>
- <span data-ttu-id="0d5f7-1145">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1145">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-1146">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1146">PowerPoint</span></span>
- <span data-ttu-id="0d5f7-1147">コメント ウィンドウが正しく開閉しない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1147">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="0d5f7-1148">動画を削除するとアプリケーションがクラッシュする可能性がある問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1148">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="0d5f7-1149">アプリケーションの一部のインスタンスを起動できない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1149">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-1150">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1150">Outlook</span></span>
- <span data-ttu-id="0d5f7-1151">日本語で表示するとき、開封確認が正しく表示されない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1151">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-1152">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1152">Access</span></span>
- <span data-ttu-id="0d5f7-1153">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1153">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="0d5f7-1154">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1154">Project</span></span>
- <span data-ttu-id="0d5f7-1155">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1155">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="0d5f7-1156">2019 年 3 月 8 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1156">March 8, 2019</span></span> 
<span data-ttu-id="0d5f7-1157">バージョン 1903 (ビルド 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1157">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="0d5f7-1158">新機能:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1158">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-1159">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1159">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="0d5f7-1160">探している情報を Microsoft Search で検索する</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1160">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="0d5f7-1161">Microsoft Search を使用して、作業を完了するのに必要なすべてのファイル、操作、連絡先、ヘルプを検索することができます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1161">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="0d5f7-1162">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1162">Getting Started:</span></span>

- <span data-ttu-id="0d5f7-1163">この機能は、ヘッダーの UI の上部に目立つように表示されています。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1163">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="0d5f7-1164">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1164">Scenarios to Try:</span></span>

- <span data-ttu-id="0d5f7-1165">大学、最近使用したドキュメント、最もよく使用するリボン コマンドなどを検索する</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1165">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="0d5f7-1166">トピックや話題を検索して、その詳細情報を取得する</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1166">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="0d5f7-1167">共同編集</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1167">CoAuthoring</span></span>

<span data-ttu-id="0d5f7-1168">マクロの文書を編集できない状況にうんざりしていませんか?</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1168">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="0d5f7-1169">これで OneDrive for Business 上の docm ファイルで複数の作成者による同時編集が可能になります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1169">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="0d5f7-1170">利用するには:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1170">Getting Started:</span></span>

<span data-ttu-id="0d5f7-1171">ユーザーは、この機能にアクセスするために UI のボタンを押す必要はありません。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1171">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="0d5f7-1172">OneDrive for Business の docm ファイルでは、既定で有効になっています。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1172">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="0d5f7-1173">したがって、試すには、ユーザーが docm ファイルを OneDrive for Business に保存しておく必要があります。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1173">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="0d5f7-1174">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1174">Scenarios to Try:</span></span>

<span data-ttu-id="0d5f7-1175">OneDrive for Business で docm ファイルを作成し、同僚と共有して共同作業を行います。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1175">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="0d5f7-1176">主な修正:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1176">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-1177">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1177">Word</span></span> 
- <span data-ttu-id="0d5f7-1178">オプションの表示中に ‘Esc’ キーを押すと発生するクラッシュの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1178">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="0d5f7-1179">コメントに返信するときにクラッシュが発生するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1179">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="0d5f7-1180">Word から PowerPoint Online へのコピーと貼り付けで発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1180">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-1181">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1181">Excel</span></span>
- <span data-ttu-id="0d5f7-1182">保護されたドキュメントや編集可能なドキュメントを開いているときに Excel でセルをコピーすると CPU 使用率が高くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1182">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-1183">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1183">PowerPoint</span></span>
- <span data-ttu-id="0d5f7-1184">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1184">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-1185">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1185">Outlook</span></span>
- <span data-ttu-id="0d5f7-1186">Outlook Search が選択した日付の並べ替えを使用しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1186">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="0d5f7-1187">"このタスクを開く" ワークフロー リボンのボタンが特定のメールで応答しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1187">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="0d5f7-1188">ユーザーが Outlook の会議室の検索で空いている会議室を選択した後、社内の会議室がクリアされなくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1188">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-1189">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1189">Access</span></span>
- <span data-ttu-id="0d5f7-1190">ダーク テーマで白い背景に白いテキストが表示されていた、保存済みのインポート/エクスポートのダイアログを修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1190">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="0d5f7-1191">表のデザインのテキストボックスに [Yes/No] フィールドの DisplayControl プロパティを設定できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1191">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="0d5f7-1192">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1192">Project</span></span>
- <span data-ttu-id="0d5f7-1193">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1193">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="0d5f7-1194">2019 年 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1194">March 1, 2019</span></span> 
<span data-ttu-id="0d5f7-1195">バージョン 1903 (ビルド 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1195">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="0d5f7-1196">新機能</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1196">What's New</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-1197">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1197">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="0d5f7-1198">色の変更履歴、コメントとリアルタイムの共同作業の同期</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1198">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="0d5f7-1199">当社の製品での、コメント、変更履歴と共同作業者のカーソルが同じ色で表示されることについての修正箇所を確認しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1199">Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="0d5f7-1200">利用するには:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1200">Getting Started:</span></span>

<span data-ttu-id="0d5f7-1201">他のユーザーが開いている SharePoint または OneDrive のドキュメントを開きます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1201">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="0d5f7-1202">ユーザーの変更履歴とコメントの色が、ユーザーのカーソルの色と一致することを確認します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1202">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="0d5f7-1203">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1203">Scenarios to Try:</span></span>

<span data-ttu-id="0d5f7-1204">他のユーザーが開いている SharePoint または OneDrive のドキュメントを開きます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1204">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="0d5f7-1205">ユーザーの変更履歴とコメントの色が、ユーザーのカーソルの色と一致することを確認します。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1205">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="0d5f7-1206">主な修正:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1206">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-1207">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1207">Word</span></span> 
- <span data-ttu-id="0d5f7-1208">オプションの表示中に ‘Esc’ キーを押すと発生するクラッシュの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1208">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="0d5f7-1209">Word から PowerPoint Online へのコピーと貼り付けで発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1209">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-1210">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1210">Excel</span></span>
- <span data-ttu-id="0d5f7-1211">保護されたドキュメントや編集可能なドキュメントを開いているときに Excel でセルをコピーすると CPU 使用率が高くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1211">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-1212">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1212">PowerPoint</span></span>
- <span data-ttu-id="0d5f7-1213">PowerPoint で @メンションを使用するときのスライド イメージのサイズに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1213">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-1214">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1214">Outlook</span></span>
- <span data-ttu-id="0d5f7-1215">Outlook Search が選択した日付の並べ替えを使用しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1215">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="0d5f7-1216">"このタスクを開く" ワークフロー リボンのボタンが特定のメールで応答しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1216">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="0d5f7-1217">ユーザーが Outlook の会議室の検索で空いている会議室を選択した後、社内の会議室がクリアされなくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1217">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-1218">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1218">Access</span></span>
- <span data-ttu-id="0d5f7-1219">テーブルとデータソースの再リンクを確認するときに表示されるメッセージを更新しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1219">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="0d5f7-1220">ダーク テーマで白い背景に白いテキストが表示されていた、保存済みのインポート/エクスポートのダイアログを修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1220">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="0d5f7-1221">表のデザインのテキストボックスに [Yes/No] フィールドの表示コントロール プロパティを設定できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1221">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="0d5f7-1222">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1222">Project</span></span>
- <span data-ttu-id="0d5f7-1223">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1223">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="0d5f7-1224">2019 年 2 月 15 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1224">February 15, 2019</span></span> 
<span data-ttu-id="0d5f7-1225">バージョン 1903 (ビルド 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1225">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="0d5f7-1226">新機能:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1226">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-1227">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1227">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="0d5f7-1228">画面切り替え効果の機能強化 - 名前で変形</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1228">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="0d5f7-1229">変形する図形を指定します</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1229">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="0d5f7-1230">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1230">Getting Started:</span></span>

- <span data-ttu-id="0d5f7-1231">[変形] で 2 つのオブジェクトを同じオブジェクトとして扱うために、[選択] ウィンドウを使って図形の名前を変更することができます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1231">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="0d5f7-1232">[変形] で名前を使って既定のマッチング動作を上書きするには、</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1232">The name must be prefaced with “!!”</span></span> <span data-ttu-id="0d5f7-1233">名前の前に "!!" (2 つの感嘆符) を付ける必要があります (例: "!!Name")。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1233">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="0d5f7-1234">名前の先頭に "!!" が付いていない図形の名前変更を続行できます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1234">Users can continue to rename shapes with any name that doesn’t start with “!!”</span></span> <span data-ttu-id="0d5f7-1235">[変形] の動作が変更されることを気にする必要はありません</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1235">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="0d5f7-1236">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1236">Scenarios to Try:</span></span>

- <span data-ttu-id="0d5f7-1237">スライドに図形 (たとえば、四角形) を挿入します</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1237">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="0d5f7-1238">新しいスライドを作成します</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1238">Create a new slide</span></span>
- <span data-ttu-id="0d5f7-1239">2 枚目のスライドに別の図形 (たとえば、三角形) を挿入します</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1239">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="0d5f7-1240">[オブジェクトの選択と表示] でスライド 1 の四角形の名前を "!!shape" に変更し、スライド 2 の三角形の名前を "!!shape" に変更します</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1240">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="0d5f7-1241">2 枚目のスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1241">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="0d5f7-1242">画面切り替え効果の機能強化 - SmartArt</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1242">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="0d5f7-1243">SmartArt の変形をより滑らかに切り替え</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1243">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="0d5f7-1244">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1244">Getting Started:</span></span>

<span data-ttu-id="0d5f7-1245">SmartArt と同様の方法で変形を使用します</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1245">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="0d5f7-1246">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1246">Scenarios to Try:</span></span>

- <span data-ttu-id="0d5f7-1247">スライドに SmartArt を挿入します</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1247">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="0d5f7-1248">スライドを複製します</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1248">Duplicate the Slide</span></span>
- <span data-ttu-id="0d5f7-1249">複製されたスライド上で SmartArt のサイズ変更/変更/移動を行います</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1249">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="0d5f7-1250">複製されたスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1250">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="0d5f7-1251">画面切り替え効果の機能強化 - 表</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1251">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="0d5f7-1252">表の変形をより滑らかに切り替え</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1252">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="0d5f7-1253">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1253">Getting Started:</span></span>
<span data-ttu-id="0d5f7-1254">表と同様の方法で変形を使用します</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1254">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="0d5f7-1255">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1255">Scenarios to Try:</span></span>

- <span data-ttu-id="0d5f7-1256">スライドに表を挿入します</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1256">Insert a Table in a slide</span></span>
- <span data-ttu-id="0d5f7-1257">スライドを複製します</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1257">Duplicate the slide</span></span>
- <span data-ttu-id="0d5f7-1258">複製されたスライド上で表のサイズ変更/変更/移動を行います</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1258">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="0d5f7-1259">複製されたスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1259">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="0d5f7-1260">Word、Excel、PowerPoint、OneNote、Access、Project、Publisher、Visio</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1260">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="0d5f7-1261">アカウントをシームレスに切り替える</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1261">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="0d5f7-1262">新しいアカウント マネージャーでは、仕事用アカウントと個人用アカウントのすべてが 1 か所に表示されます。また、アカウントを自由に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1262">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="0d5f7-1263">この更新されたエクスペリエンスでは、ログイン方法がわかりやすくなりました。また、先にサインアウトしたり複雑なダイアログを操作したりする必要なく、仕事用アカウントと個人用アカウントを切り替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1263">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="0d5f7-1265">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1265">Scenarios to Try:</span></span>
- <span data-ttu-id="0d5f7-1266">アカウントを切り替えます</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1266">Switch between accounts</span></span>
- <span data-ttu-id="0d5f7-1267">新しいアカウントを追加します [注: [ファイル]、[アカウント]、[接続済みサービス] の順に移動してから、仕事用アカウントに接続されている個人用サービス (またはその逆) を削除することができます]</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1267">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="0d5f7-1268">アカウントからサインアウトします</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1268">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="0d5f7-1269">主な修正:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1269">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-1270">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1270">Word</span></span> 
- <span data-ttu-id="0d5f7-1271">表と画像のコンテキスト プレビューに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1271">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-1272">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1272">Excel</span></span>
- <span data-ttu-id="0d5f7-1273">[黒] のテーマでオートフィルターの [検索] フィールドのテキストが白くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1273">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="0d5f7-1274">新しい Office アドインの同意の UI に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1274">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-1275">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1275">PowerPoint</span></span>
- <span data-ttu-id="0d5f7-1276">ノート PC またはタブレットでスライドショーを表示すると、表示が自動的に拡大される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1276">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-1277">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1277">Outlook</span></span>
- <span data-ttu-id="0d5f7-1278">[OneNote に送る] ボタンの表示に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1278">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-1279">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1279">Access</span></span>
- <span data-ttu-id="0d5f7-1280">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1280">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="0d5f7-1281">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1281">Project</span></span>
- <span data-ttu-id="0d5f7-1282">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1282">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="0d5f7-1283">2019 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1283">February 11, 2019</span></span>
<span data-ttu-id="0d5f7-1284">バージョン 1903 (ビルド 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1284">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="0d5f7-1285">主な修正:</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1285">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-1286">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1286">Word</span></span> 
- <span data-ttu-id="0d5f7-1287">一部のカスタマイズされたスタイルを Word Online に適用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1287">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="0d5f7-1288">Word のリッチ オブジェクトでのコンテキスト プレビューに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1288">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="0d5f7-1289">リストを貼り付けると Word がクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1289">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-1290">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1290">Excel</span></span>
- <span data-ttu-id="0d5f7-1291">通貨記号がない場合に、数値の書式の後ろに追加されるスペースが表示されない問題を修正しました特殊文字</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1291">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="0d5f7-1292">株価の自動検出に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1292">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-1293">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1293">PowerPoint</span></span>
- <span data-ttu-id="0d5f7-1294">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1294">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-1295">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1295">Outlook</span></span>
- <span data-ttu-id="0d5f7-1296">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1296">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-1297">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1297">Access</span></span>
- <span data-ttu-id="0d5f7-1298">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1298">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="0d5f7-1299">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1299">Project</span></span>
- <span data-ttu-id="0d5f7-1300">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1300">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="0d5f7-1301">2019 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1301">February 1, 2019</span></span> 
<span data-ttu-id="0d5f7-1302">バージョン 1902 (ビルド 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1302">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="0d5f7-1303">主な修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1303">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="0d5f7-1304">Word</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1304">Word</span></span> 
- <span data-ttu-id="0d5f7-1305">埋め込まれた Excel の表のセルのサイズ変更に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1305">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="0d5f7-1306">描画キャンバス内の図形のコピー/貼り付けの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1306">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="0d5f7-1307">Excel</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1307">Excel</span></span>
- <span data-ttu-id="0d5f7-1308">Excel Web App からファイルを開く際の問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1308">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="0d5f7-1309">CSV ファイルを .XLSX として保存する際にファイル名のサイズが原因で失敗する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1309">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="0d5f7-1310">コンテキスト メニューのオプションの表示に関してコンテキスト メニューを修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1310">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="0d5f7-1311">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1311">PowerPoint</span></span>
- <span data-ttu-id="0d5f7-1312">角かっこを入力するためにユーザーがキーボード ショートカット Ctrl+Alt+7 および Ctrl+Alt+8 を使用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1312">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="0d5f7-1313">ローカル ビデオを PowerPoint に挿入すると C ドライブのディスク領域が減ってしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1313">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="0d5f7-1314">一部のユーザーに表示されていなかった [Microsoft Stream に公開する] ボタンを修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1314">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="0d5f7-1315">Outlook</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1315">Outlook</span></span>
- <span data-ttu-id="0d5f7-1316">カレンダーのタスク ビューでタスクの件名が正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1316">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="0d5f7-1317">Access</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1317">Access</span></span>
- <span data-ttu-id="0d5f7-1318">グラフのスケーリングの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1318">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="0d5f7-1319">Project</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1319">Project</span></span>
- <span data-ttu-id="0d5f7-1320">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="0d5f7-1320">Various performance and stability fixes</span></span>
