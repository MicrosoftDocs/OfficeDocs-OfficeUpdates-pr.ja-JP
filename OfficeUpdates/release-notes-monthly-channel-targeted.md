---
title: リリース ノートの月次チャネル (対象指定)
ms.author: anankani
author: v-lislo
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Insider Slow の対象ユーザーに主な新機能、修正プログラム、既知の問題の最新リストを提供します
ms.openlocfilehash: e7fc9ff0ba68aca9d73873c7c299fed4e7668236
ms.sourcegitcommit: 18190a7f0d562d254300120529a4dfd0d47d26d9
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/14/2019
ms.locfileid: "40023622"
---
# <a name="release-notes-for-office-monthly-channel-targeted"></a><span data-ttu-id="f29a0-103">Office 月次チャネルのリリース ノート (対象指定)</span><span class="sxs-lookup"><span data-stu-id="f29a0-103">Release Notes for Office Monthly Channel (Targeted)</span></span>

<span data-ttu-id="f29a0-104">この記事には、Windows デスクトップ向け Word、Excel、PowerPoint、Outlook、Access、Project の月次チャネル (対象指定) ビルドのリリース ノートが含まれています。</span><span class="sxs-lookup"><span data-stu-id="f29a0-104">This article contains release notes for Monthly Channel (Targeted) builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="f29a0-105">Microsoft では、毎週、皆様にお知らせしたい魅力的な新機能、重要な修正プログラム、重大な問題に関する情報を提供しています。</span><span class="sxs-lookup"><span data-stu-id="f29a0-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="f29a0-106">多くの場合、機能 (場合によっては修正プログラムも) は、特定の期間にわたって月次チャネル (対象指定) に展開されることに注意してください。</span><span class="sxs-lookup"><span data-stu-id="f29a0-106">Note that we often roll out features (and sometimes even fixes) to Monthly Channel (Targeted) over a period of time.</span></span> <span data-ttu-id="f29a0-107">これにより、Microsoft では、より広範な対象ユーザーに機能をリリースする前に、作業がスムーズに行われていることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="f29a0-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="f29a0-108">したがって、下記のものが表示されない場合でも、心配する必要はなく、いずれは表示されます。</span><span class="sxs-lookup"><span data-stu-id="f29a0-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="f29a0-109">リリースノートの発行日は実際のビルドのリリース日と一致しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-109">The release notes publication date may not match the actual build release date.</span></span>
> - <span data-ttu-id="f29a0-110">Microsoft Teams に関連する既存の Office 365 ProPlus のインストール - 6 月の下旬から、これらの更新プログラムのインストール時に、Microsoft Teams が既存の Office 365 ProPlus (Office 365 Business) のインストールの中に含められます。</span><span class="sxs-lookup"><span data-stu-id="f29a0-110">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="f29a0-111">Teams が追加される日にちは、使用している更新プログラム チャネルによって異なります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-111">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="f29a0-112">追加情報については、「[Office 365 ProPlus と同時に Microsoft Teams を展開する](https://docs.microsoft.com/deployoffice/teams-install)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="f29a0-112">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install) for additional information.</span></span>

[//]: # (削除しないでください)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1912-december-12"></a><span data-ttu-id="f29a0-116">バージョン 1912: 12 月 12 日</span><span class="sxs-lookup"><span data-stu-id="f29a0-116">Version 1912: December 06</span></span>
<span data-ttu-id="f29a0-117">*バージョン 1912 (ビルド 12325.20172)*</span><span class="sxs-lookup"><span data-stu-id="f29a0-117">*Version 1912 (Build 12325.20012)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="f29a0-119">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="f29a0-119">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="f29a0-120">Excel</span><span class="sxs-lookup"><span data-stu-id="f29a0-120">Excel</span></span>

- <span data-ttu-id="f29a0-121">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-121">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="f29a0-122">セル内の動的配列数式を編集すると、その結果、セルの境界の外にテキストが並んでしまう可能性がある</span><span class="sxs-lookup"><span data-stu-id="f29a0-122">Editing dynamic array formulas within a cell may result in text being aligned outside of the boundary of the cell</span></span>

- <span data-ttu-id="f29a0-123">一部のローカライズにおいて、[Text to Column] 機能が失敗することがある</span><span class="sxs-lookup"><span data-stu-id="f29a0-123">Text to Column functionality may fail for some localizations</span></span>

- <span data-ttu-id="f29a0-124">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-124">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="f29a0-125">非表示の名前付き範囲にアクセスすると、ユーザーにエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-125">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="f29a0-126">余白のドロップダウン メニューが正しくレンダリングされない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-126">Margin dropdown menu may not render correctly.</span></span>

- <span data-ttu-id="f29a0-127">4K 解像度のハードウェアのグラフィック アクセラレータを無効にすると、スクロールしたときにセルのレンダリングが遅れる場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-127">Disabling hardware graphics acceleration with 4K resolution may result in delayed rendering of cells when scrolling around.</span></span>

- <span data-ttu-id="f29a0-128">この変更は、ソフトウェア レンダリングを活用することにより、特定の Intel グラフィック ドライバーの問題を回避します。</span><span class="sxs-lookup"><span data-stu-id="f29a0-128">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

### <a name="onenote"></a><span data-ttu-id="f29a0-129">OneNote</span><span class="sxs-lookup"><span data-stu-id="f29a0-129">OneNote</span></span>

- <span data-ttu-id="f29a0-130">OneNote は、「会議ノート」の Outlook アドインを介して開かない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-130">OneNote may not open via the 'Meeting Notes' Outlook add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="f29a0-131">Outlook</span><span class="sxs-lookup"><span data-stu-id="f29a0-131">Outlook</span></span>

- <span data-ttu-id="f29a0-132">クロス フォルダー コンテンツを含む断続的なクラッシュ。</span><span class="sxs-lookup"><span data-stu-id="f29a0-132">Intermittent crash involving cross folder content</span></span>

- <span data-ttu-id="f29a0-133">Outlook のメール メッセージにインラインで挿入された画像のサイズが変更される場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-133">Images inserted inline to Outlook e-mail messages can sometimes get resized.</span></span>

- <span data-ttu-id="f29a0-134">グループ ポリシーを使用して S/MIME の既定の署名構成を適用する機能が追加された。</span><span class="sxs-lookup"><span data-stu-id="f29a0-134">Added the ability to enforce S/MIME configuration via group policy</span></span>

- <span data-ttu-id="f29a0-135">予想よりも埋め込み画像が小さく表示されることがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-135">Embedded images may appear smaller than expected</span></span>

- <span data-ttu-id="f29a0-136">保持ポリシーのラベルには、保持期間がかっこ内に表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-136">Retention policy labels may display the retention time period in parenthesis.</span></span>

- <span data-ttu-id="f29a0-137">代替送信者の使用中にポリシーのヒントが表示されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="f29a0-137">Addresses an issue that caused Policy tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="f29a0-138">日本語パックの連絡先カードに空白が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-138">Blank spaces may appear in Contact cards with Japanese language pack.</span></span>

- <span data-ttu-id="f29a0-139">会議をクリアした後、会議の場所が予期せずに会議に追加される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="f29a0-139">Addresses an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f29a0-140">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f29a0-140">PowerPoint</span></span>

- <span data-ttu-id="f29a0-141">テキストからフォーカスを移動した後、カーソルが表示されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-141">Cursor may disappear after moving focus from text</span></span>

- <span data-ttu-id="f29a0-142">ある Office アプリケーションから別の Office アプリケーションへの安全なリンクは、リンクされたアプリケーションを起動しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-142">Safelinks from one Office application to another may not launch the linked application.</span></span>

- <span data-ttu-id="f29a0-143">場合によっては、タッチ デバイスでのスクロールが機能しないことがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-143">In some cases, scrolling with touch devices will not work.</span></span>

- <span data-ttu-id="f29a0-144">クラウド ファイル内のスライドに 2 つ以上の異なるビデオがある場合、ビデオの画像は正しく表示されますが、ユーザーがそれぞれのビデオを再生するためにクリックすると、同一の内容のビデオが再生されます。</span><span class="sxs-lookup"><span data-stu-id="f29a0-144">If a user has two (or more) different videos on a slide in a cloud file, the video images are rendered correctly, but when the user clicks on each one to play, the video content is the same.</span></span>

- <span data-ttu-id="f29a0-145">余白のドロップダウン メニューが正しくレンダリングされない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-145">Margin dropdown menu may not render correctly.</span></span>

### <a name="project"></a><span data-ttu-id="f29a0-146">Project</span><span class="sxs-lookup"><span data-stu-id="f29a0-146">Project</span></span>

- <span data-ttu-id="f29a0-147">ダーク モードの場合、リソースが過剰に割り当てられているタスクのタスク検査パネルに移動すると、表を読み取ることができません。</span><span class="sxs-lookup"><span data-stu-id="f29a0-147">If you are in Dark mode, when you go to the task inspector panel on a task with an over allocated resource, you are unable to read the table.</span></span>

- <span data-ttu-id="f29a0-148">ユーザーにライセンスに関するエラーが表示されることがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-148">Users may experience an error regarding licensing</span></span>

- <span data-ttu-id="f29a0-149">日付の選択の [今日] ボタンで正しくない日付が設定されることがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-149">The Today button in the date picker may sometimes set the incorrect date</span></span>

- <span data-ttu-id="f29a0-150">[プロジェクトの比較] 機能を使用すると、Project がクラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-150">Project may crash when you use the Compare Projects feature.</span></span>

- <span data-ttu-id="f29a0-151">割り当てのないタスクに作業を設定すると、1 日間に丸められます。</span><span class="sxs-lookup"><span data-stu-id="f29a0-151">Setting effort on tasks that have no assignments are rounded to 1 day.</span></span>

### <a name="word"></a><span data-ttu-id="f29a0-152">Word</span><span class="sxs-lookup"><span data-stu-id="f29a0-152">Word</span></span>

- <span data-ttu-id="f29a0-153">ウィンドウ スイッチャーが非表示のときに、コメントのヒントを選択すると最新のコメント ウィンドウが表示されるようになります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-153">Selecting a comment hint should now show the modern comments pane when hidden in pane switcher</span></span>

- <span data-ttu-id="f29a0-154">右クリックすると、完全に一致する単語が選択されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-154">Right-clicking can sometimes not result in selecting the whole word</span></span>

- <span data-ttu-id="f29a0-155">ある Office アプリケーションから別の Office アプリケーションへの安全なリンクは、リンクされたアプリケーションを起動しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-155">Safelinks from one Office application to another may not launch the linked application.</span></span>

- <span data-ttu-id="f29a0-156">文書パーツ オーガナイザーに無効なアラートが表示される場合があります。&quot;スタイル、文書パーツを変更しました。&quot;</span><span class="sxs-lookup"><span data-stu-id="f29a0-156">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>

- <span data-ttu-id="f29a0-157">一部のテーマでは、どのコメントが選択されているかの判断が困難になることがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-157">Some themes may make it difficult to determine which comment is selected</span></span>

- <span data-ttu-id="f29a0-158">提案されたファイル形式に変換した後、カーソルがオブジェクト内でアクティブのままになっている可能性があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-158">The cursor may remain active within an object after converting to a suggested format</span></span>

- <span data-ttu-id="f29a0-159">一部のシナリオでは、メッセージ内の画像が正しく拡大されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-159">Images in messages may be incorrectly scaled in some scenarios</span></span>

- <span data-ttu-id="f29a0-160">コピーと貼り付けを使用すると、コメント ウィンドウが再読み込みされることがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-160">Comment pane sometimes gets reloaded when using copy/paste.</span></span>

- <span data-ttu-id="f29a0-161">コメントが正しい順序で貼り付けられない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-161">Comments are sometimes not pasted in the correct order.</span></span>

- <span data-ttu-id="f29a0-162">コメント カードでユーザーをメンションすると、JSON が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-162">At-mentioning a user in a comment card may show JSON.</span></span>

- <span data-ttu-id="f29a0-163">余白のドロップダウン メニューが正しくレンダリングされない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-163">Margin dropdown menu may not render correctly.</span></span>

- <span data-ttu-id="f29a0-164">分割画面の境界のサイズを変更すると、さらに分割画面が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-164">Resizing a split screen border may introduce an additional split screen.</span></span>

- <span data-ttu-id="f29a0-165">カスタム スタイルのマルチレベル リストで構成されるテンプレートを既存のドキュメントに適用すると、特定の条件下でスタイルが保持されない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-165">Applying a template consisting of a multi-level list with custom styles to existing documents may not preserve the style under certain conditions.</span></span>

- <span data-ttu-id="f29a0-166">差し込み印刷の実行後に、特定の条件下でファイルを保存できない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-166">Saving a file after doing a mail merge may not work under certain conditions.</span></span>

### <a name="office-suite"></a><span data-ttu-id="f29a0-167">Office スイート</span><span class="sxs-lookup"><span data-stu-id="f29a0-167">Office Suite</span></span>

- <span data-ttu-id="f29a0-168">Excel から PowerPoint にグラフを貼り付けると、グラフのサイズが小さくなる場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-168">Pasting a chart from Excel to PowerPoint can reduce the size of the chart</span></span>

- <span data-ttu-id="f29a0-169">コメントに返信すると、テキストボックスがウィンドウの端を超えて縦方向に展開されることがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-169">Replying to a comment may cause the textbox to expand vertically beyond the edge of the pane</span></span>

- <span data-ttu-id="f29a0-170">日本語ベースの製品の場合、アカウント ユーザーの姓と名が誤った順序で表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-170">For Japanese based products, account user first name, last name may appear in incorrect order.</span></span>

- <span data-ttu-id="f29a0-171">ODT と GPO の更新期限設定で、相対期限の設定後、初回のみしか機能しないバスが修正されました。修正により、2 回目以降の更新プログラムで相対期限を使用きるようになりました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-171">Fixed an issue in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="f29a0-172">コメントにマウス ポインターを合わせた際に、コメントの周りにテキストボックスのアウトラインが表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-172">Hovering a mouse pointer over comments may display a textbox outline around the comment.</span></span>

- <span data-ttu-id="f29a0-173">Office の更新プログラムが、意図したソース (ローカル共有、ネットワーク共有、構成マネージャー
で提供される場所など) からではなく、予期せずに Office CDN からファイルをダウンロードする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-173">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1911-december-10"></a><span data-ttu-id="f29a0-175">バージョン 1911: 12 月 10 日</span><span class="sxs-lookup"><span data-stu-id="f29a0-175">Version 1911: December 10</span></span>
<span data-ttu-id="f29a0-176">*バージョン 1911 (ビルド 12228.20364)*</span><span class="sxs-lookup"><span data-stu-id="f29a0-176">*Version 1911 (Build 12228.20364)*</span></span>

<span data-ttu-id="f29a0-177">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="f29a0-177">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="f29a0-179">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="f29a0-179">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="f29a0-180">Excel</span><span class="sxs-lookup"><span data-stu-id="f29a0-180">Excel</span></span>

- <span data-ttu-id="f29a0-181">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-181">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="f29a0-182">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="f29a0-182">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="f29a0-183">詳細情報</span><span class="sxs-lookup"><span data-stu-id="f29a0-183">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

### <a name="outlook"></a><span data-ttu-id="f29a0-184">Outlook</span><span class="sxs-lookup"><span data-stu-id="f29a0-184">Outlook</span></span>

- <span data-ttu-id="f29a0-185">**グループの名前付けポリシー**: グループの名前付けポリシーを使用すると、IT 管理者は組織内のユーザーが作成するグループの名前の標準化と管理を行えます。</span><span class="sxs-lookup"><span data-stu-id="f29a0-185">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="f29a0-186">管理者は、グループが作成される際に特定のプレフィックスとサフィックスをグループ名に追加することを要求できます。また、特定の単語の使用を禁止できます。</span><span class="sxs-lookup"><span data-stu-id="f29a0-186">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="f29a0-187">これにより、グループ名での不適切な単語の使用を最小限に抑えられる他、ディレクトリ内のグループ名の記載を IT 管理者が管理できます。</span><span class="sxs-lookup"><span data-stu-id="f29a0-187">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="f29a0-188">また、名前付けポリシーを使用することで、チーム サイトを展開する組織は、チーム サイトを部署ごとに分類できるようにもなります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-188">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f29a0-189">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f29a0-189">PowerPoint</span></span>

- <span data-ttu-id="f29a0-190">**インクを瞬時に再生:** スライドで手描き入力する場合は、スライド ショー中にアニメーションの再生を適用して、インクの実際の描画が再生されるようにします。</span><span class="sxs-lookup"><span data-stu-id="f29a0-190">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="f29a0-191">詳細情報</span><span class="sxs-lookup"><span data-stu-id="f29a0-191">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="f29a0-192">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-192">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="f29a0-193">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="f29a0-193">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

### <a name="word"></a><span data-ttu-id="f29a0-194">Word</span><span class="sxs-lookup"><span data-stu-id="f29a0-194">Word</span></span>

- <span data-ttu-id="f29a0-195">**他のユーザーがすばやく変更を確認:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="f29a0-195">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="f29a0-196">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-196">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="f29a0-197">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="f29a0-197">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="f29a0-198">詳細情報</span><span class="sxs-lookup"><span data-stu-id="f29a0-198">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

## <a name="resolved-issues"></a><span data-ttu-id="f29a0-199">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="f29a0-199">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="f29a0-200">Excel</span><span class="sxs-lookup"><span data-stu-id="f29a0-200">Excel</span></span>

- <span data-ttu-id="f29a0-201">この変更は、ソフトウェア レンダリングを活用することにより、特定の Intel グラフィック ドライバーの問題を回避します。</span><span class="sxs-lookup"><span data-stu-id="f29a0-201">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="f29a0-202">ピボット グラフの右クリック メニューを修正して、[詳細の表示] オプションを有効にしました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-202">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

### <a name="outlook"></a><span data-ttu-id="f29a0-203">Outlook</span><span class="sxs-lookup"><span data-stu-id="f29a0-203">Outlook</span></span>

- <span data-ttu-id="f29a0-204">Web アドインがデジタル著作権管理 (DRM) メッセージにアクセスする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="f29a0-204">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1911-november-20"></a><span data-ttu-id="f29a0-206">バージョン 1911: 11 月 20 日</span><span class="sxs-lookup"><span data-stu-id="f29a0-206">Version 1911: November 20</span></span>
<span data-ttu-id="f29a0-207">*バージョン 1911 (ビルド 12228.20250)*</span><span class="sxs-lookup"><span data-stu-id="f29a0-207">*Version 1911 (Build 12228.20250)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="f29a0-209">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="f29a0-209">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="f29a0-210">Outlook</span><span class="sxs-lookup"><span data-stu-id="f29a0-210">Outlook</span></span>

- <span data-ttu-id="f29a0-211">**高度なグループ メールの設定:** この機能は、グループ ユーザーが受信トレイで受信/フォローするメールまたはイベントを、カスタマイズするのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="f29a0-211">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1911-november-15"></a><span data-ttu-id="f29a0-213">バージョン 1911: 11 月 15 日</span><span class="sxs-lookup"><span data-stu-id="f29a0-213">Version 1911: November 15</span></span>
<span data-ttu-id="f29a0-214">*バージョン 1911 (ビルド 12228.20206)*</span><span class="sxs-lookup"><span data-stu-id="f29a0-214">*Version 1911 (Build 12228.20206)*</span></span>

## <a name="version-1911-november-12"></a><span data-ttu-id="f29a0-215">バージョン 1911: 11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="f29a0-215">Version 1911: November 12</span></span>
<span data-ttu-id="f29a0-216">*バージョン 1911 (ビルド 12228.20120)*</span><span class="sxs-lookup"><span data-stu-id="f29a0-216">*Version 1911 (Build 12228.20120)*</span></span>

<span data-ttu-id="f29a0-217">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="f29a0-217">Security updates listed [here](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="f29a0-219">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="f29a0-219">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="f29a0-220">Excel</span><span class="sxs-lookup"><span data-stu-id="f29a0-220">Excel</span></span>

- <span data-ttu-id="f29a0-221">**データ ビジュアライザー アドイン:** Excel から Visio フローチャートをすばやく作成します。</span><span class="sxs-lookup"><span data-stu-id="f29a0-221">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="f29a0-222">詳細情報</span><span class="sxs-lookup"><span data-stu-id="f29a0-222">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a><span data-ttu-id="f29a0-223">Outlook</span><span class="sxs-lookup"><span data-stu-id="f29a0-223">Outlook</span></span>

- <span data-ttu-id="f29a0-224">**アクセシビリティ対応のメールを最も必要としている人に送信する:** Outlook では、メールのヒントが表示され、アクセシビリティ対応のコンテンツを必要とするユーザーに送信するときに、コンテンツがアクセシビリティ対応であることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="f29a0-224">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f29a0-225">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f29a0-225">PowerPoint</span></span>

- <span data-ttu-id="f29a0-226">**プレゼンテーションの最適化:** アクセシビリティ チェックを使用すると、スクリーン リーダーを考慮に入れて、スライド上のオブジェクトを配置することができます。</span><span class="sxs-lookup"><span data-stu-id="f29a0-226">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

### <a name="visio"></a><span data-ttu-id="f29a0-227">Visio</span><span class="sxs-lookup"><span data-stu-id="f29a0-227">Visio</span></span>

- <span data-ttu-id="f29a0-228">**Excel で洗練された Visio 図を作成する:** すばやく簡単に、データを Excel 内の洗練された Visio 図に可視化します。</span><span class="sxs-lookup"><span data-stu-id="f29a0-228">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> [<span data-ttu-id="f29a0-229">詳細情報</span><span class="sxs-lookup"><span data-stu-id="f29a0-229">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="f29a0-230">Word</span><span class="sxs-lookup"><span data-stu-id="f29a0-230">Word</span></span>

- <span data-ttu-id="f29a0-231">**共同編集の改善:** コンテンツの変更をリアルタイムでユーザーが受け取れるようにすることで、共同編集のエクスペリエンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-231">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

### <a name="office-suite"></a><span data-ttu-id="f29a0-232">Office スイート</span><span class="sxs-lookup"><span data-stu-id="f29a0-232">Office Suite</span></span>

- <span data-ttu-id="f29a0-233">**アップロード センターは、Files Needing Attention experience に置き換えられます:** アップロード センターは、[ファイル] > [開く] の Office アプリケーション内に表示される Files Needing Attention experience に置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="f29a0-233">**The Upload Center is being replaced by the Files Needing Attention experience:** The Upload Center is being replaced by the Files Needing Attention experience that will show up inside the Office applications under File > Open.</span></span> <span data-ttu-id="f29a0-234">この新しいエクスペリエンスは、アップロード センターに比べ、最新かつ総合的で、煩わしくありません。</span><span class="sxs-lookup"><span data-stu-id="f29a0-234">This new experience is more modern, integrated, and less intrusive compared to the Upload Center.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="f29a0-237">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="f29a0-237">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="f29a0-238">Access</span><span class="sxs-lookup"><span data-stu-id="f29a0-238">Access</span></span>

- <span data-ttu-id="f29a0-239">レコードのカウントが正しくないことがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-239">The record count could be incorrect.</span></span>

### <a name="excel"></a><span data-ttu-id="f29a0-240">Excel</span><span class="sxs-lookup"><span data-stu-id="f29a0-240">Excel</span></span>

- <span data-ttu-id="f29a0-241">別のシートのデータを参照しているスパークラインを含むシートを削除すると、再びそのファイルを開いた時に破損したファイルとして識別されるという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-241">Resolved an issue where deleting sheets containing sparklines referencing data on another sheet could cause the file to be identified as corrupted when re-opened.</span></span>
- <span data-ttu-id="f29a0-242">グラフのサイズの変更が保存できないことがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-242">Changes to a chart size could not be saved.</span></span>
- <span data-ttu-id="f29a0-243">チェックボックスで正しく表示できないことがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-243">Checkboxes could not render correctly.</span></span>
- <span data-ttu-id="f29a0-244">[データ ソースの選択] ダイアログで、一部のフィールドで大文字と小文字が区別されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-244">Select Data Source dialogs were not case sensitive for some fields.</span></span>
- <span data-ttu-id="f29a0-245">VBA 関数の一部で、新しいグラフに関するエラーが返されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-245">Some VBA functions would return an error on new chart.</span></span>
- <span data-ttu-id="f29a0-246">ユーザーが Office 365 の Excel ブック形式で保存できなくなることがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-246">Users could be prevented from saving in Office 365 Excel Workbook format.</span></span>
- <span data-ttu-id="f29a0-247">自動調整を使用して行の高さを調整するときにチェック ボックスのコントロールが縮小されることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-247">Resolved an issue where check box controls could shrink when using autofit to adjust row height.</span></span>
- <span data-ttu-id="f29a0-248">SQL 表形式サーバーのクエリのピボットテーブルの残りの部分と一緒にレポート フィルターを変換すると、正しい結果が返されないことがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-248">Resolved an Issue where you may get incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span>
- <span data-ttu-id="f29a0-249">信頼されていないネットワーク共有から保護されたファイルを編集すると、Excel にエラーが発生することがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-249">Resolved an issue where Excel may fail when editing a protected file from an untrusted network share.</span></span>
- <span data-ttu-id="f29a0-250">ナレーターと拡大鏡を同時に使用すると、エラーが発生することがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-250">Using Narrator and Magnifier at the same time may result in a failure.</span></span>
- <span data-ttu-id="f29a0-251">スクロール後にセルを選択すると間違ったセルが選択されることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-251">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>
- <span data-ttu-id="f29a0-252">結合されたセルで列を削除するパフォーマンスが大幅に改善されました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-252">We significantly improved the performance of deleting columns with merged cells.</span></span>

### <a name="onenote"></a><span data-ttu-id="f29a0-253">OneNote</span><span class="sxs-lookup"><span data-stu-id="f29a0-253">OneNote</span></span>

- <span data-ttu-id="f29a0-254">ローカル リソースからクラウド リソースへの同期に影響する可能性がある問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-254">Identified an issue which could affect syncing from a local resource to a cloud resource.</span></span>

### <a name="outlook"></a><span data-ttu-id="f29a0-255">Outlook</span><span class="sxs-lookup"><span data-stu-id="f29a0-255">Outlook</span></span>

- <span data-ttu-id="f29a0-256">会議室の検索ツールで、使用可能な会議室が&quot;なし&quot;と表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-256">Room Finder tool may be displaying &quot;None&quot; for available rooms.</span></span>
- <span data-ttu-id="f29a0-257">リボンを自動的に非表示にするよう設定されている場合に検索ボックスが消えるという問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-257">Identified an issue where the search box could disappear when the ribbon is set to hide automatically.</span></span>
- <span data-ttu-id="f29a0-258">メールにデジタル署名付きの添付ファイルがある場合にそのメールに署名するとデジタル署名が破損する可能性がある問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-258">Identified an issue which could cause digital signatures to become broken when signing an e-mail with a digitally signed attachment.</span></span>
- <span data-ttu-id="f29a0-259">メールを転送すると、埋め込み画像がなくなる場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-259">A forwarded e-mail may be missing embedded images.</span></span>
- <span data-ttu-id="f29a0-260">厳しいテナント制限がある Outlook プロファイルをユーザーが作成できない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-260">Users may not be able to create Outlook profiles with strict tenant restriction.</span></span>
- <span data-ttu-id="f29a0-261">長いファイル名がメッセージ本文へのドラッグ アンド ドロップ後に切り捨てられる問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-261">Identified an issue where long filenames were truncated after draging and droping to the message body.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f29a0-262">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f29a0-262">PowerPoint</span></span>

- <span data-ttu-id="f29a0-263">グラフのサイズの変更が保存できないことがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-263">Changes to a chart size could not be saved.</span></span>
- <span data-ttu-id="f29a0-264">ナレーターと拡大鏡を同時に使用すると、エラーが発生することがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-264">Using Narrator and Magnifier at the same time may result in a failure.</span></span>
- <span data-ttu-id="f29a0-265">スライド プレビューの縦横比が適切にロック/ロック解除されていない問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-265">Identified an issue where aspect ratio for the slide preview was not being properly locked/unlocked.</span></span>

### <a name="project"></a><span data-ttu-id="f29a0-266">Project</span><span class="sxs-lookup"><span data-stu-id="f29a0-266">Project</span></span>

- <span data-ttu-id="f29a0-267">タスクの更新を実行中に入力したノートが保存されない可能性がある問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-267">Identified an issue where notes might not persist if entered while doing update tasks.</span></span>
- <span data-ttu-id="f29a0-268">ユーザーがタスクを完了としてマークすることができず、99% に設定されます。</span><span class="sxs-lookup"><span data-stu-id="f29a0-268">User is unable to mark a task as complete, and it gets set to 99%.</span></span>
- <span data-ttu-id="f29a0-269">平準化によって割り当て超過が解決されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-269">Overallocations are not resolved by leveling.</span></span>
- <span data-ttu-id="f29a0-270">読み取り専用のプロジェクトを開いたときに複数のメッセージを取得する可能性があるという問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-270">Identified an issue where users could get several messages when opening a read-only project.</span></span>
- <span data-ttu-id="f29a0-271">ファイルがユーザーによってロックされている場合に、ユーザー名がエラー メッセージに表示されない可能性がある問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-271">Identified an issue where a file could be locked by a user, but no username would be displayed in the error message.</span></span>

### <a name="publisher"></a><span data-ttu-id="f29a0-272">Publisher</span><span class="sxs-lookup"><span data-stu-id="f29a0-272">Publisher</span></span>

- <span data-ttu-id="f29a0-273">図形がグラフィックの境界線の外側に表示されることがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-273">Shapes could appear outside of the graphics border.</span></span>

### <a name="word"></a><span data-ttu-id="f29a0-274">Word</span><span class="sxs-lookup"><span data-stu-id="f29a0-274">Word</span></span>

- <span data-ttu-id="f29a0-275">文章校正の候補がコンテキスト メニューに表示されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-275">Proofing suggestions are not displaying in contextual menus.</span></span>
- <span data-ttu-id="f29a0-276">グラフのサイズの変更が保存できないことがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-276">Changes to a chart size could not be saved.</span></span>
- <span data-ttu-id="f29a0-277">図形がグラフィックの境界線の外側に表示されることがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-277">Shapes could appear outside of the graphics border.</span></span>
- <span data-ttu-id="f29a0-278">スクリーン リーダーを使用中にコメントを表示するときの問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-278">Identified an issue when viewing comments while using a screen reader.</span></span>
- <span data-ttu-id="f29a0-279">一部の批評がスペルまたは文法の批評と誤って識別される問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-279">Identified an issue where some critiques were misidentified as being spelling or grammar critiques.</span></span>
- <span data-ttu-id="f29a0-280">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-280">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>
- <span data-ttu-id="f29a0-281">韓国語/英語のオートコレクトを使用しているときに、間違った文字が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-281">Incorrect characters may appear when using Korean/English autocorrect.</span></span>
- <span data-ttu-id="f29a0-282">ナビゲーション ウィンドウから検索できない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-282">Searching from the Navigation pane may fail.</span></span>
- <span data-ttu-id="f29a0-283">ナレーターと拡大鏡を同時に使用すると、エラーが発生することがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-283">Using Narrator and Magnifier at the same time may result in a failure.</span></span>
- <span data-ttu-id="f29a0-284">コンテンツ ポリシーがコメントに正しく適用されません。</span><span class="sxs-lookup"><span data-stu-id="f29a0-284">Content policies are being incorrectly applied to comments.</span></span>
- <span data-ttu-id="f29a0-285">上位のポリシー ラベルが優先して適用されるべき時に、低いポリシー ラベルが適用されることがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-285">Lower policy labels may be applied when a higher policy label should have taken priority.</span></span>
- <span data-ttu-id="f29a0-286">以前のドキュメントを開いたまま [情報] タブに移動すると、エラーが発生することがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-286">Opening legacy documents and then going to the Info tab can cause a failure.</span></span>
- <span data-ttu-id="f29a0-287">新しいコメント ダイアログがフォーカスを取得できないことがある問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-287">Identified an issue where a new comment dialog could sometimes not obtain focus.</span></span>
- <span data-ttu-id="f29a0-288">連絡先カードが、@ メンションに書式を設定した後に、開けなくなることがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-288">A contact card could be prevented from opening after apply formatting to an @ mention.</span></span>
- <span data-ttu-id="f29a0-289">テキストの強調表示は難しいことがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-289">Highlighting text could be challenging.</span></span>
- <span data-ttu-id="f29a0-290">ユーザーが Word、Excel、および PowerPoint のドキュメントを保存できなくなることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-290">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="f29a0-291">この問題は、[保存] アイコンをクリックしたり Ctrl キーを押しながら S キーを押したりした後に、新しいファイルを作成して [名前を付けて保存] オプションを表示するユーザーに影響を与えます。</span><span class="sxs-lookup"><span data-stu-id="f29a0-291">This issue affects users that create a new file and bring up the "Save as" option after clicking on the Save icon or pressing Ctrl + S.</span></span>
- <span data-ttu-id="f29a0-292">濃色のテキストで書かれた従来のコメントがダーク モードで表示されません。</span><span class="sxs-lookup"><span data-stu-id="f29a0-292">Legacy comments written with dark text is not visible in Dark Mode.</span></span>
- <span data-ttu-id="f29a0-293">ユーザーがエディターの個々のアイテムに移動できなくなることがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-293">A user could be prevented from navigating to an individual item in the editor.</span></span>
- <span data-ttu-id="f29a0-294">文法またはスペルのエラーが強調表示されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-294">Grammar or spelling errors might not be highlighted.</span></span>

### <a name="office-suite"></a><span data-ttu-id="f29a0-295">Office スイート</span><span class="sxs-lookup"><span data-stu-id="f29a0-295">Office Suite</span></span>

- <span data-ttu-id="f29a0-296">一部の描画がプレビューやスライド ショーに表示されない場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-296">Some drawings may not display in preview or slide shows.</span></span>
- <span data-ttu-id="f29a0-297">[別のインストールが進行中です] という誤ったエラー メッセージによりアップグレードに失敗することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="f29a0-297">We fixed an issue where an upgrade could be prevented by a incorrect error message of "Another install in progress".</span></span>
- <span data-ttu-id="f29a0-298">縦書きのテキスト ボックス内で一部のカタカナが正しく表示されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-298">Some katakana characters may display incorrectly in a vertical text box.</span></span>
- <span data-ttu-id="f29a0-299">接続されていないネットワーク共有にファイルを保存しようとすると、エラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="f29a0-299">Attempting to save a file to a disconnected network share may result in a filure.</span></span>
- <span data-ttu-id="f29a0-300">Windows 7 で図形を使用する場合のパフォーマンスの問題</span><span class="sxs-lookup"><span data-stu-id="f29a0-300">Performance issue when using Shapes on Windows 7.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

