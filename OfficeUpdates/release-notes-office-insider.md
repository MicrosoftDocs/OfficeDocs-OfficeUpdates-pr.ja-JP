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
ms.openlocfilehash: 38f26f551be55a7817a993108f598c6a6a9ecdb5
ms.sourcegitcommit: fdc89a96b2ab35af2f08654ef28117dec7657443
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/24/2020
ms.locfileid: "43804897"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="aff82-103">Office Insider のリリース ノート</span><span class="sxs-lookup"><span data-stu-id="aff82-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="aff82-104">この記事には、Windows デスクトップ向け Word、Excel、PowerPoint、Outlook、Access、Project の Insider ビルドのリリース ノートが含まれています。</span><span class="sxs-lookup"><span data-stu-id="aff82-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="aff82-105">Microsoft では、毎週、皆様にお知らせしたい魅力的な新機能、重要な修正プログラム、重大な問題に関する情報を提供しています。</span><span class="sxs-lookup"><span data-stu-id="aff82-105">Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="aff82-106">多くの場合、機能 (場合によっては修正プログラムも) は、特定の期間にわたって Insider にロールアウトされます。</span><span class="sxs-lookup"><span data-stu-id="aff82-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="aff82-107">これにより、Microsoft では、より広範な対象ユーザーに機能をリリースする前に、作業がスムーズに行われていることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="aff82-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="aff82-108">以下に示すものが表示されない場合でも、最終的には入手できますのでご安心ください。</span><span class="sxs-lookup"><span data-stu-id="aff82-108">So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="aff82-109">リリース ノートは毎週投稿され、場合により複数のビルドのコンパイルになります。</span><span class="sxs-lookup"><span data-stu-id="aff82-109">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="aff82-110">リリースノートの発行日は実際のビルドのリリース日と一致しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-110">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (削除しないでください)

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-april-24"></a><span data-ttu-id="aff82-113">バージョン 2005: 4 月 24 日</span><span class="sxs-lookup"><span data-stu-id="aff82-113">Version 2005: April 24</span></span>
<span data-ttu-id="aff82-114">*バージョン 2005 (ビルド 12816.20006)*</span><span class="sxs-lookup"><span data-stu-id="aff82-114">*Version 2005 (Build 12816.20006)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="aff82-118">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="aff82-118">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="aff82-119">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-119">Excel</span></span>
- <span data-ttu-id="aff82-120">この変更により、LINEST 関数が正しい値を返すにもかかわらず (強制的な y 切片のケースの) グラフの近似曲線の R-2 乗値が正しくないという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-120">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>
- <span data-ttu-id="aff82-121">この変更により、カスタマイズされたグラフの近似曲線の書式設定が保存されないことがあるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-121">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-122">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-122">Outlook</span></span>
- <span data-ttu-id="aff82-123">Office リボンのグループ予定表の [分類] ボタンが無効になっているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-123">Fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="aff82-124">グループ フォルダーを実装していないまたは動作させていないエンタープライズ ユーザーに、Outlook で "応答なし" というメッセージが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-124">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-125">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-125">PowerPoint</span></span>
- <span data-ttu-id="aff82-126">アスタリスク (\*) 記号の上にポインターを移動しても、最後にドキュメントを更新した人のユーザー名と日付が表示されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-126">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-127">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-127">Word</span></span>
- <span data-ttu-id="aff82-128">[ブックマークの表示] オプションを有効にしても、ブックマークが表示されませんでした。</span><span class="sxs-lookup"><span data-stu-id="aff82-128">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="aff82-129">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-129">This has been fixed.</span></span>
- <span data-ttu-id="aff82-130">この変更により、[値の代わりにフィールド コードを表示する] オプションが有効になっている場合に、ハイパーリンク付きのテキストが表示されないという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-130">This change fixes an issue where text with hyperlinks may not display if the option "Show field codes instead of their values" was enabled.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2005-april-17"></a><span data-ttu-id="aff82-132">バージョン 2005: 4 月 17 日</span><span class="sxs-lookup"><span data-stu-id="aff82-132">Version 2005: April 17</span></span>
<span data-ttu-id="aff82-133">*バージョン 2005 (ビルド 12810.20002)*</span><span class="sxs-lookup"><span data-stu-id="aff82-133">*Version 2005 (Build 12810.20002)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="aff82-135">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="aff82-135">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="aff82-136">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-136">Excel</span></span>
- <span data-ttu-id="aff82-137">グラフと共に使用される [ユーザー設定の誤差範囲] ダイアログでセル参照エディット コントロールのサイズが大きくなります。</span><span class="sxs-lookup"><span data-stu-id="aff82-137">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>
- <span data-ttu-id="aff82-138">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-138">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>
- <span data-ttu-id="aff82-139">印刷時にフォーム コントロールのチェックボックスが拡大縮小されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-139">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>
- <span data-ttu-id="aff82-140">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="aff82-140">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>
- <span data-ttu-id="aff82-141">この変更により、条件付き書式 (CF) 情報が .XLSB ファイルに正常に保存されなかった問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-141">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="aff82-142">OneNote</span><span class="sxs-lookup"><span data-stu-id="aff82-142">OneNote</span></span>
- <span data-ttu-id="aff82-143">改行が垂直タブとして保存されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-143">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-144">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-144">Outlook</span></span>
- <span data-ttu-id="aff82-145">ユーザーが個人用連絡先グループを会議の出席者として追加できなくなった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="aff82-145">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>
- <span data-ttu-id="aff82-146">スケジュール アシスタントで 2 か月以上離れた会議が会議の件名が表示されないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="aff82-146">Addresses an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>
- <span data-ttu-id="aff82-147">大きな HTML メッセージを転送するとき、ユーザーにメッセージ本文の全体が表示されないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="aff82-147">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>
- <span data-ttu-id="aff82-148">グループ ポリシーを使用して S/MIME の既定の署名構成を適用する機能が追加された。</span><span class="sxs-lookup"><span data-stu-id="aff82-148">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>
- <span data-ttu-id="aff82-149">ユーザーのプライマリ メールボックス以外のメールボックスに対して作成された削除ルールが無効になるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="aff82-149">Addresses an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>
- <span data-ttu-id="aff82-150">暗号化されたメッセージを転送するときに添付ファイルが削除されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="aff82-150">Addresses an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

### <a name="project"></a><span data-ttu-id="aff82-151">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-151">Project</span></span>
- <span data-ttu-id="aff82-152">フォーム ビュー内で先行処理/後続処理データが編集されると、余分の ProjectBeforeTaskChange イベントが発生します。</span><span class="sxs-lookup"><span data-stu-id="aff82-152">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>
- <span data-ttu-id="aff82-153">SharePoint タスク リストに接続されているプロジェクトのボードの状態フィールドを変更すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-153">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>
- <span data-ttu-id="aff82-154">以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-154">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-april-10"></a><span data-ttu-id="aff82-156">バージョン 2004: 4 月 10 日</span><span class="sxs-lookup"><span data-stu-id="aff82-156">Version 2004: April 10</span></span>
<span data-ttu-id="aff82-157">*バージョン 2004 (ビルド 12730.20024)*</span><span class="sxs-lookup"><span data-stu-id="aff82-157">*Version 2004 (Build 12730.20024)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="aff82-159">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-159">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="aff82-160">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-160">Access</span></span>

- <span data-ttu-id="aff82-161">**[テーブルの表示] ダイアログ ボックスをバイパスし、作業ウィンドウに直接移動して、テーブルを効率よくリレーションシップやクエリに追加します。:** 4 つのタブをクリックして、名前を複数選択して、テキストで検索し、作業中に開いたままの作業ウィンドウからドラッグして、テーブルやクエリを追加 ます。</span><span class="sxs-lookup"><span data-stu-id="aff82-161">**Bypass the Show Table dialog box, go directly to a task pane, and streamline adding tables to relationships and queries.:** Add tables and queries by clicking four tabs, multi-selecting names, searching by text, and dragging from a task pane that stays open while you work.</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-162">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-162">Excel</span></span>

- <span data-ttu-id="aff82-163">**M365 Premium Content Picker:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="aff82-163">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="aff82-164">1000 件のロイヤリティフリーのストック画像、アイコン、ステッカーを詳しく見る [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="aff82-164">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-165">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-165">Outlook</span></span>

- <span data-ttu-id="aff82-166">**M365 Premium Content Picker:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="aff82-166">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="aff82-167">1000 件のロイヤリティフリーのストック画像、アイコン、ステッカーを詳しく見る [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="aff82-167">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="aff82-168">**メールの一部として画像を送信するときに、画像を高品質に維持する:** メールの内容の一部として画像を送信するときに、画像の圧縮を制限するための新しい Outlook の設定を使用できます。</span><span class="sxs-lookup"><span data-stu-id="aff82-168">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-169">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-169">PowerPoint</span></span>

- <span data-ttu-id="aff82-170">**M365 Premium Content Picker:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="aff82-170">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="aff82-171">1000 件のロイヤリティフリーのストック画像、アイコン、ステッカーを詳しく見る [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="aff82-171">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="aff82-172">**プレゼンテーション中に変更を同期する:** プレゼンテーションがスライド ショー モードであれば、いつでも変更を同期できます。</span><span class="sxs-lookup"><span data-stu-id="aff82-172">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-173">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-173">Word</span></span>

- <span data-ttu-id="aff82-174">**M365 Premium Content Picker:** ドキュメントに命を吹き込みましょう。</span><span class="sxs-lookup"><span data-stu-id="aff82-174">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="aff82-175">1000 件のロイヤリティフリーのストック画像、アイコン、ステッカーを詳しく見る [詳細情報](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="aff82-175">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="aff82-176">**個人用コピーに注釈を付ける:** 共有ドキュメントの個人用コピーを作成し、自分用の手書きノートを作成します。</span><span class="sxs-lookup"><span data-stu-id="aff82-176">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="aff82-177">[表示] > [個人用コピーの作成] に移動して開始します。</span><span class="sxs-lookup"><span data-stu-id="aff82-177">Go to View > Create a Private Copy to get started.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="aff82-180">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="aff82-180">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="aff82-181">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-181">Access</span></span>

- <span data-ttu-id="aff82-182">作業ウィンドウのテーブルのサイズ変更と更新に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-182">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-183">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-183">Excel</span></span>

- <span data-ttu-id="aff82-184">シートのセル範囲を選択すると、1 つのセルが選択されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-184">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="aff82-185">X 軸の範囲に合わせてグラフのサイズを小さくすると、Excel が応答を停止する可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-185">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="aff82-186">ユーザー定義のグラフ テンプレートを既定として挿入すると、縦棒グラフとして保存されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-186">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="aff82-187">基になるデータ セルにタイトルがない場合に、グラフのデータ ラベルが空白として表示されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-187">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="aff82-188">R1C1 セルの参照が有効になっている Excel シートが共同編集/共有される場合に、R1C1 モードでユーザー プレゼンス アイコンの上にカーソルを移動すると、アクティブセル参照が表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-188">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-189">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-189">Outlook</span></span>

- <span data-ttu-id="aff82-190">メール メッセージからカテゴリが消えることがあるという問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="aff82-190">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="aff82-191">共有メールボックスに対して、異なるコンピューター上の別のフォルダー階層が代理人に表示されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="aff82-191">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="aff82-192">ユーザーが組織フォームのプロパティを表示とするときにクラッシュするという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="aff82-192">Addresses an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="aff82-193">コンピューターのタイムゾーンを変更するときに、一部のリマインダーが発生しないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="aff82-193">Addresses an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-194">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-194">PowerPoint</span></span>

- <span data-ttu-id="aff82-195">この変更により、PowerPoint または Word に OLE オブジェクトとして埋め込まれたレガシ Excel グラフを表示するとき、グラフ タイトルが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-195">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="aff82-196">Excel から PowerPoint にテキストをコピーするときに、書式設定が変更される場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-196">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="aff82-197">この変更により、[完全に一致する単語だけを検索する] を使用して特殊文字を検索するときに、想定どおりに動作しない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-197">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="aff82-198">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-198">Project</span></span>

- <span data-ttu-id="aff82-199">実績作業時間の保護設定を有効にしているときに、ユーザーがタイムフェーズの基準作業時間を入力できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-199">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-200">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-200">Word</span></span>

- <span data-ttu-id="aff82-201">この変更により、ヒントの上にカーソルを移動してもカードが強調表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-201">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="aff82-202">この変更により、なげなわ選択ツールを使用するとき、グループ化された図形のテキストが一時的に非表示になる場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-202">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="aff82-203">この変更により、PowerPoint または Word に OLE オブジェクトとして埋め込まれたレガシ Excel グラフを表示するとき、グラフ タイトルが表示されない場合があるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-203">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="aff82-204">この変更により、コメントを作成するとき、コメント アンカーが表示されない場合があるという 2 ページ表示の問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-204">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="aff82-205">スタイルがリストにリンクされている祖先のスタイルである段落の場合、そのリストの番号が失われる場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-205">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-march-27"></a><span data-ttu-id="aff82-207">バージョン 2004: 3 月 27 日</span><span class="sxs-lookup"><span data-stu-id="aff82-207">Version 2004: March 27</span></span>
<span data-ttu-id="aff82-208">*バージョン 2004 (ビルド 12718.20010)*</span><span class="sxs-lookup"><span data-stu-id="aff82-208">*Version 2004 (Build 12718.20010)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="aff82-210">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-210">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="aff82-211">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-211">Outlook</span></span>

- <span data-ttu-id="aff82-212">**メール作成時の @ メンションの候補表示を無効にするオプションが追加されました。** メンション ピッカーが便利どころか迷惑だと感じていますか?</span><span class="sxs-lookup"><span data-stu-id="aff82-212">**New option to disable @ mention suggestions when composing mail:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="aff82-213">今後は、必要に応じてオフにすることができます。</span><span class="sxs-lookup"><span data-stu-id="aff82-213">Now you can turn it off if you prefer.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="aff82-216">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="aff82-216">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="aff82-217">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-217">Outlook</span></span>
- <span data-ttu-id="aff82-218">[添付ファイル ​​ツール] に [クラウドに保存] ボタンが表示されない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="aff82-218">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>
- <span data-ttu-id="aff82-219">ユーザーが返信メッセージの所有者アクセス許可を持っていない場合、[インスペクタ] ウィンドウから権限がデジタル管理されたメッセージに返信するときに、ユーザーが署名を追加できないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="aff82-219">Addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>
- <span data-ttu-id="aff82-220">以前作成した会議に、Web 上の場所から追加の添付ファイルを追加できないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="aff82-220">Addresses an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-221">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-221">PowerPoint</span></span>
- <span data-ttu-id="aff82-222">この変更により、絵文字を含む PowerPoint ファイルを保存する場合に失敗する可能性があるエラーが修正されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-222">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

### <a name="project"></a><span data-ttu-id="aff82-223">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-223">Project</span></span>
- <span data-ttu-id="aff82-224">CustomFieldValueListGetItem が実行され、ユーザー設定フィールドの参照テーブルが存在しない場合、誤って空の参照テーブルが作成される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-224">Fixed an issue where if 'CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-225">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-225">Word</span></span>
- <span data-ttu-id="aff82-226">この変更により、 [表示] メニューから複数のページを選択すると、[コメント] ウィンドウが空白で表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-226">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-march-20"></a><span data-ttu-id="aff82-228">バージョン 2004: 3 月 20 日</span><span class="sxs-lookup"><span data-stu-id="aff82-228">Version 2004: March 20</span></span>
<span data-ttu-id="aff82-229">*バージョン 2004 (ビルド 12711.20000)*</span><span class="sxs-lookup"><span data-stu-id="aff82-229">*Version 2004 (Build 12711.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="aff82-231">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-231">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="aff82-232">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-232">Outlook</span></span>

- <span data-ttu-id="aff82-233">**予定表デザインの更新:** 昨年、Microsoft ではメール エクスペリエンスを更新しました。今年は予定表のデザインを更新します!</span><span class="sxs-lookup"><span data-stu-id="aff82-233">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar's turn to get a facelift!</span></span> <span data-ttu-id="aff82-234">更新されていますが使い慣れた製品ですので、経験豊富な Outlook ユーザーとして、すぐに使いこなして生産性を高めることができます。</span><span class="sxs-lookup"><span data-stu-id="aff82-234">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

- <span data-ttu-id="aff82-235">**グループ内のデータを保護:** グループを作成するときに選択する秘密度ラベルがグループ メール、ドキュメント、チーム サイトに適用されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-235">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-236">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-236">PowerPoint</span></span>

- <span data-ttu-id="aff82-237">**スライド ショーの実行中にスライドを更新する:** プレゼンテーション中に他の作成者が変更したスライドを更新します。</span><span class="sxs-lookup"><span data-stu-id="aff82-237">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="aff82-240">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="aff82-240">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="aff82-241">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-241">Excel</span></span>

- <span data-ttu-id="aff82-242">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-242">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-243">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-243">Outlook</span></span>

- <span data-ttu-id="aff82-244">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-244">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="aff82-245">この変更により、下書きメールに対する最新の変更が更新されなかった問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-245">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="aff82-246">ファイルを右クリックして [送信] を使用しても機能しなかった問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-246">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="aff82-247">ユーザーがアドレス帳の検索パスをカスタマイズしていた場合に、Outlook の名前解決範囲がグローバル アドレス一覧 (GAL) ではなく、カスタマイズしたパスに制限されていた問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-247">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="aff82-248">返された一連の検索結果の中で、結果をカテゴリ別に並べ替えると、カテゴリ カラーが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-248">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

### <a name="project"></a><span data-ttu-id="aff82-249">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-249">Project</span></span>

- <span data-ttu-id="aff82-250">ユーザーがスケジュール グループ内の [タスク] リボンにある「無効化」ボタンをクリックしたときに 'ProjectBeforeTaskChange' という Visual Basic Applications (VBA) イベントが発生しなかった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-250">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the "Inactivate" button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="aff82-251">[フォームの種類] ビュー内から先行タスクまたは後続タスクの詳細を設定した場合に、ProjectBeforeTaskChange という Visual Basic Applications (VBA) イベントが変更をキャプチャしないことがありました。</span><span class="sxs-lookup"><span data-stu-id="aff82-251">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="aff82-252">たとえば、依存関係を削除し、フォームで [OK] をクリックした場合に、イベントが発生しませんでした。</span><span class="sxs-lookup"><span data-stu-id="aff82-252">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="aff82-253">この動作が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-253">This behavior has been fixed.</span></span>

- <span data-ttu-id="aff82-254">日付の変更などの変更を加えた後に、終了した作業時間の実績コスト (ACWP) の最新の値が表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-254">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="aff82-255">[最近使用した項目 (MRU)] メニューを使用してプロジェクトを開くと、読み取り/書き込みアクセス権を伴ってプロジェクト ファイルが開かれる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-255">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="aff82-256">この変更によって、開始日時を指定した (しかし期間を指定しない) 手動タスクを作成した場合に、タイムライン上に間違った時刻が表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-256">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="aff82-257">イスラム暦予定表を使用してタイムラインを印刷すると、[印刷] ビューで、1 か月スキップされるか、または重複する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-257">Fixed an issue where printing a timeline using Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="aff82-258">この変更により、GDI オブジェクトを使用して Team Planner を操作するときに、GDI オブジェクトの割り当てが過剰になり、メモリ不足状態が発生する問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-258">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-259">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-259">Word</span></span>

- <span data-ttu-id="aff82-260">コメントを投稿する機能が無効になる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-260">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="aff82-261">この変更により、形式に誤りがある、または無効なプロトコル情報を含む画像を処理するときの遅延が解決されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-261">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="aff82-262">この変更により、アカウント マネージャーがサードパーティのアプリケーションを使用してメッセージを送ろうとすると、ハングしてディスパッチできないという問題が解決されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-262">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="aff82-263">この変更により、文書に記載されていない見出しスタイルで目次が更新されるという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-263">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="aff82-264">Word 文書をメール送信するときに、文書に保存されていたデジタル署名が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-264">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2004-march-13"></a><span data-ttu-id="aff82-266">バージョン 2004: 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="aff82-266">Version 2004: March 13</span></span>
<span data-ttu-id="aff82-267">*バージョン 2004 (ビルド 12703.20010)*</span><span class="sxs-lookup"><span data-stu-id="aff82-267">*Version 2004 (Build 12703.20010)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="aff82-269">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-269">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-270">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-270">Excel</span></span>
- <span data-ttu-id="aff82-271">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="aff82-271">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="aff82-272">詳細情報</span><span class="sxs-lookup"><span data-stu-id="aff82-272">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="aff82-273">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-273">PowerPoint</span></span>
- <span data-ttu-id="aff82-274">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="aff82-274">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="aff82-275">詳細情報</span><span class="sxs-lookup"><span data-stu-id="aff82-275">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="aff82-276">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-276">Word</span></span>
- <span data-ttu-id="aff82-277">**秘密度ラベル**: カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="aff82-277">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="aff82-278">詳細情報</span><span class="sxs-lookup"><span data-stu-id="aff82-278">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="aff82-281">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="aff82-281">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="aff82-282">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-282">Access</span></span>
- <span data-ttu-id="aff82-283">Access のインターナショナル バージョンにおいて、ユーザー インターフェイスに英語の文字列が表示されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-283">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-284">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-284">Excel</span></span>
- <span data-ttu-id="aff82-285">プログラムを使って大きいセル範囲を編集するときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-285">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>
- <span data-ttu-id="aff82-286">日本語の環境で CSV ファイルを開くときに発生するパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-286">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-287">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-287">Outlook</span></span>
- <span data-ttu-id="aff82-288">(メニューからではなく) ドラッグ アンド ドロップでメールに添付ファイルを追加したり、メールから添付ファイルを保存したりすると、ファイルの「最終更新日」が更新される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="aff82-288">Addresses an issue that caused the "Last Modified"; date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>
- <span data-ttu-id="aff82-289">展開された [検索] ウィンドウで Enter キーを押しても検索が開始されず、代わりにユーザーが [検索] ボタンをクリックしなければならないという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="aff82-289">Addresses an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>
- <span data-ttu-id="aff82-290">[利用可能な場合はユーザーの写真を表示する] オプションがオフになっている場合、検索結果にユーザーに関する情報が表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-290">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>

### <a name="project"></a><span data-ttu-id="aff82-291">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-291">Project</span></span>
- <span data-ttu-id="aff82-292">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-292">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>
- <span data-ttu-id="aff82-293">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-293">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-294">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-294">Word</span></span>
- <span data-ttu-id="aff82-295">コメントを入力または編集し、Ctrl キーを押しながら A キーを押したときに、コメント カード内のテキストが選択されるのではなく、キャンバスのテキストが選択されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-295">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>
- <span data-ttu-id="aff82-296">クイック印刷を使用して印刷した後に編集しようとしたときに、ドキュメント内の単語の配置が乱れてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-296">We fixed an issue in which the alignment of words in a document gets scrambled when tried to edit after printing using Quick Print.</span></span>
- <span data-ttu-id="aff82-297">2 つのドキュメントを 1 つのドキュメントに結合するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-297">We fixed an issue when merging two documents into one document.</span></span>
- <span data-ttu-id="aff82-298">数式を含む変更履歴をマークすると、ファイルを保存するときにエラーが発生するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-298">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-march-06"></a><span data-ttu-id="aff82-300">バージョン 2003: 3 月 6 日</span><span class="sxs-lookup"><span data-stu-id="aff82-300">Version 2003: March 06</span></span>
<span data-ttu-id="aff82-301">*バージョン 2003 (ビルド 12624.20086)*</span><span class="sxs-lookup"><span data-stu-id="aff82-301">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="aff82-303">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="aff82-303">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="aff82-304">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-304">Outlook</span></span>

- <span data-ttu-id="aff82-305">Outlook Web Access を使用してルールを作成しても Exchange サーバーに保存されず競合が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-305">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="aff82-306">ダーク モードの Outlook の [差出人] フィールドにドロップダウン リストが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-306">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="aff82-307">ファイルが別のアプリケーションで開かれているときに、ユーザーがエクスプローラーでファイルをメール メッセージに添付できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-307">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-308">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-308">PowerPoint</span></span>

- <span data-ttu-id="aff82-309">サムネイルの上にマウスポインターを置くと推奨されるサムネイルが点滅する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-309">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="aff82-310">場合によっては、これにより PowerPoint がクラッシュしてしまう可能性があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-310">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-311">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-311">Word</span></span>

- <span data-ttu-id="aff82-312">編集用に保護されたドキュメントの比較機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-312">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="aff82-313">Office スイート</span><span class="sxs-lookup"><span data-stu-id="aff82-313">Office Suite</span></span>

- <span data-ttu-id="aff82-314">ユーザー プリンシパル名 (UPN) の大文字と小文字が区別されなくなり、SharePoint でファイルを操作するときにはエラーが少なくなるという Word/Excel/PowerPoint の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-314">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="aff82-315">機能に影響はないものの、[ファイル]、[オプション] の順で進んだ後のダイアログの [OK] ボタンが灰色で表示されていた外観上の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-315">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

## <a name="version-2003-february-28"></a><span data-ttu-id="aff82-318">バージョン 2003: 2 月 28 日</span><span class="sxs-lookup"><span data-stu-id="aff82-318">Version 2003: February 28</span></span>
<span data-ttu-id="aff82-319">*バージョン 2003 (ビルド 12619.20002)*</span><span class="sxs-lookup"><span data-stu-id="aff82-319">*Version 2003 (Build 12619.20002)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="aff82-321">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-321">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="aff82-322">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-322">Outlook</span></span>

- <span data-ttu-id="aff82-323">**IT 管理者向けのインシデント通知:** Microsoft 365 テナントのグローバル管理者および Office Apps 管理者は、Outlook for Windows の新しい右側のパネル通知により、ユーザーに影響する Outlook および O365 Exchange インシデントについて通知されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-323">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-324">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-324">PowerPoint</span></span>

- <span data-ttu-id="aff82-325">\*\*インクを図形に変換する作図エクスペリエンスの向上: \*\*より良い図を描いて変換し、Office オブジェクトを操作できるようにします。[詳細情報](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="aff82-325">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="aff82-328">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="aff82-328">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="aff82-329">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-329">Excel</span></span>

- <span data-ttu-id="aff82-330">[印刷プレビュー] でスライサーのテキストが適切に拡大または縮小されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-330">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-331">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-331">Outlook</span></span>

- <span data-ttu-id="aff82-332">(メニューからではなく) ドラッグ アンド ドロップでメールに添付ファイルを追加したり、メールから添付ファイルを保存したりすると、ファイルの「最終更新日」が更新される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="aff82-332">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="aff82-333">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-333">Word</span></span>

- <span data-ttu-id="aff82-334">コメント カードでタブすると、コメント編集ボックスにフォーカスが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-334">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="aff82-335">コントロール (テキスト コンテンツ コントロールなど) を数式に挿入し、ファイルを保存して開くと、読み取り不可能なコンテンツ エラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="aff82-335">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="aff82-336">以前にパスワードで保護されたファイルをクラウド ストレージに保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-336">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="aff82-337">Office スイート</span><span class="sxs-lookup"><span data-stu-id="aff82-337">Office Suite</span></span>

- <span data-ttu-id="aff82-338">同じ SharePoint ライブラリから Word/Excel/PowerPoint で複数のドキュメントが開かれている場合、最初に開いたドキュメントのみがポリシー コンプライアンスでスキャンされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-338">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-february-21"></a><span data-ttu-id="aff82-340">バージョン 2003: 2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="aff82-340">Version 2003: February 21</span></span>
<span data-ttu-id="aff82-341">*バージョン 2003 (ビルド 12615.20000)*</span><span class="sxs-lookup"><span data-stu-id="aff82-341">*Version 2003 (Build 12615.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="aff82-343">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-343">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="aff82-344">Office スイート</span><span class="sxs-lookup"><span data-stu-id="aff82-344">Office Suite</span></span>

- <span data-ttu-id="aff82-345">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキスト ハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="aff82-345">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="aff82-348">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="aff82-348">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-349">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-349">Excel</span></span>
- <span data-ttu-id="aff82-350">ピボット テーブルのメジャーの名前を変更するときにユーザーが経験する可能性のある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-350">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="aff82-351">VBA マクロを使用して範囲の内容をクリアするときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-351">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="aff82-352">ユーザーがリボンを操作するマクロを実行したときに UI が点滅する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-352">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="aff82-353">ファイルの最初の単語が TABLE である場合に CSV ファイルが誤ってロードされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-353">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="aff82-354">ズーム レベルが異なる 2 つのブックを切り替える際にユーザーがクラッシュを経験する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-354">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-355">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-355">Outlook</span></span>
- <span data-ttu-id="aff82-356">Outlook を夜間に実行したままにしておくと、ユーザーがパブリック フォルダー メッセージを開けなくなる問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-356">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="aff82-357">Gmail アカウントを追加する認証ワークフロー中に、[アクセス許可] ページの [許可] および [拒否] ボタンが無効になる競合状態を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-357">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="aff82-358">一部のシナリオで、ログがオフになっている場合でも Outlook が予期せずログ出力を生成する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-358">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-359">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-359">Word</span></span>
- <span data-ttu-id="aff82-360">マウス ポインターをコメント カードの上に置いたときに、コメント カードが常に強調表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-360">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="aff82-361">アクティブなドキュメントの共同編集セッション中に、画像をコメント カードに直接追加すると、タグが追加されている場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-361">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="aff82-362">この問題は修正されています。</span><span class="sxs-lookup"><span data-stu-id="aff82-362">This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="aff82-363">Office スイート</span><span class="sxs-lookup"><span data-stu-id="aff82-363">Office Suite</span></span>
- <span data-ttu-id="aff82-364">Word/Excel/PowerPoint ドキュメントで Multichoice/Lookup/Managed-metadata プロパティを使用し、SharePoint ドキュメント ライブラリに保存する場合、これらのプロパティは以前は 255 文字に制限されていました。</span><span class="sxs-lookup"><span data-stu-id="aff82-364">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="aff82-365">これらのプロパティが 255 文字を超えると、そういったドキュメントは保存することができませんでした。</span><span class="sxs-lookup"><span data-stu-id="aff82-365">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="aff82-366">この変更により、この制限は 2048 文字に増加しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-366">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-february-14"></a><span data-ttu-id="aff82-368">バージョン 2003: 2 月 14 日</span><span class="sxs-lookup"><span data-stu-id="aff82-368">Version 2003: February 14</span></span>
<span data-ttu-id="aff82-369">*バージョン 2003 (ビルド 12607.20000)*</span><span class="sxs-lookup"><span data-stu-id="aff82-369">*Version 2003 (Build 12607.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="aff82-371">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-371">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="aff82-372">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-372">Outlook</span></span>

- <span data-ttu-id="aff82-373">**キャプティブ WiFi ネットワークの新しいエクスペリエンス**: サインインに Web ページを必要とする WiFi ネットワークに参加したことはありませんか ?</span><span class="sxs-lookup"><span data-stu-id="aff82-373">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="aff82-374">Outlook はこれを検出し、接続を支援します。</span><span class="sxs-lookup"><span data-stu-id="aff82-374">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-375">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-375">Word</span></span>

- <span data-ttu-id="aff82-376">**描画ツールボックスでインク エディターを見つける**: [描画] を選択し、[インク エディター] ペンを選択して、指またはデジタル ペンでドキュメントを編集します。</span><span class="sxs-lookup"><span data-stu-id="aff82-376">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="aff82-377">詳細情報</span><span class="sxs-lookup"><span data-stu-id="aff82-377">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="aff82-378">Office スイート</span><span class="sxs-lookup"><span data-stu-id="aff82-378">Office Suite</span></span>

- <span data-ttu-id="aff82-379">**明瞭になったステータス バー アイコン:** ステータス バーのアイコンが見やすくなりました</span><span class="sxs-lookup"><span data-stu-id="aff82-379">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="aff82-382">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="aff82-382">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="aff82-383">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-383">Outlook</span></span>

- <span data-ttu-id="aff82-384">ユーザーが「空き時間情報オプション」予定表のアクセス許可ダイアログにアクセスできなくなる問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-384">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="aff82-385">異なるタイム ゾーンから送信された定期的な会議インスタンスを開くときに「申し訳ございません、このアイテムを開くことができません」というアラートが発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-385">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="aff82-386">メッセージから添付ファイルをドラッグ アンド ドロップした後、ユーザーが .msg ファイルを再度開くことができない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-386">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="aff82-387">Outlook から OneDrive に添付ファイルをアップロードした後、添付ファイルの名前にかっこが含まれているとファイル名が変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-387">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-388">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-388">PowerPoint</span></span>

- <span data-ttu-id="aff82-389">Excel グラフを含む PowerPoint または Word でドキュメントを保存できないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-389">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-390">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-390">Word</span></span>

- <span data-ttu-id="aff82-391">ドキュメントを PDF にエクスポートすると、画像の透明性が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-391">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-february-07"></a><span data-ttu-id="aff82-393">バージョン 2002: 2 月 7 日</span><span class="sxs-lookup"><span data-stu-id="aff82-393">Version 2002: February 07</span></span>
<span data-ttu-id="aff82-394">*バージョン 2002 (ビルド 12527.20040)*</span><span class="sxs-lookup"><span data-stu-id="aff82-394">*Version 2002 (Build 12527.20040)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="aff82-396">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-396">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="aff82-397">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-397">Access</span></span>

- <span data-ttu-id="aff82-398">**クエリ デザイナー、SQL ビュー、およびリレーションシップ ウィンドウでの作業効率の向上:** テーブルを右クリックして、テーブルを開き、デザインし、サイズを変更し、非表示にします。</span><span class="sxs-lookup"><span data-stu-id="aff82-398">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="aff82-399">SQL ビューでテキストを検索および置換します。</span><span class="sxs-lookup"><span data-stu-id="aff82-399">Search and replace text in SQL View.</span></span> <span data-ttu-id="aff82-400">リレーションシップ ウィンドウ内の複数のテーブルを選択します。</span><span class="sxs-lookup"><span data-stu-id="aff82-400">Select multiple tables in the Relationships window.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="aff82-403">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="aff82-403">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="aff82-404">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-404">Access</span></span>

- <span data-ttu-id="aff82-405">この更新プログラムでは、ADODB を使用する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="aff82-405">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="aff82-406">VB コードのレコーダー オブジェクトがエラーを誤って報告することがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-406">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="aff82-407">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-407">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-408">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-408">Excel</span></span>

- <span data-ttu-id="aff82-409">動的配列で [区切り位置] を使用すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-409">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-410">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-410">Outlook</span></span>

- <span data-ttu-id="aff82-411">月ビューで予定表をスクロールしても以前の予定表のイベントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-411">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="aff82-412">Citrix 環境で 30 件を超える予定表を表示したときにクラッシュする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="aff82-412">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-413">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-413">PowerPoint</span></span>

- <span data-ttu-id="aff82-414">ファイルを閉じた後、実行中のイベント ハンドラーがある場合、PowerPoint がファイルを Presentations コレクションからすぐに削除しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-414">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="aff82-415">したがって、オブジェクト モデルによって報告される開いているプレゼンテーションの数は正しくなく、PowerPoint のシャットダウンは防止されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-415">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="aff82-416">蛍光ペンの問題を修正しました。暗い蛍光ペン色の白いテキストはグレースケールで黒として印刷されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-416">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-417">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-417">Word</span></span>

- <span data-ttu-id="aff82-418">目次を更新してスクロールすると、ドキュメント上に灰色の領域が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-418">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="aff82-419">ドキュメントが共同編集されている場合、ルート コメントのドラフト バージョンが保持されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-419">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="aff82-420">コメント カード間を行き来すると、最初に選択されたコメントが選択の強調表示で表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-420">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="aff82-421">コメントが書き込まれたが投稿されず、ユーザーがファイルを保存しようとした場合、「参照」を使用してファイルを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-421">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="aff82-422">SlideTrack を有効にしてコメント ウィンドウを閉じると、Ctrl + Alt + M でコメント ウィンドウが開かない場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-422">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="aff82-423">@メンションをテーブルに追加すると、「このドキュメントのテーブルが破損しました」というエラー メッセージが生成される場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-423">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="aff82-424">Office スイート</span><span class="sxs-lookup"><span data-stu-id="aff82-424">Office Suite</span></span>

- <span data-ttu-id="aff82-425">Norway Nynorsk (nn-no) 校正ツール パッケージが正しくインストールされなかった場合がある問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="aff82-425">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-january-31"></a><span data-ttu-id="aff82-427">バージョン 2002: 1 月 31 日</span><span class="sxs-lookup"><span data-stu-id="aff82-427">Version 2002: January 31</span></span>
<span data-ttu-id="aff82-428">*バージョン 2002 (ビルド 12513.20010)*</span><span class="sxs-lookup"><span data-stu-id="aff82-428">*Version 2002 (Build 12513.20010)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="aff82-430">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-430">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="aff82-431">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-431">Excel</span></span>

- <span data-ttu-id="aff82-432">**すぐに読んで返信する**: ブックを開かずに、メールからコメントやメンションに直接返信します。</span><span class="sxs-lookup"><span data-stu-id="aff82-432">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="aff82-433">**クエリ エディターでのデータ プロファイリング**: 列のデータを一目で分析し、エラーと空の値を識別し、配布ヒストグラムなどを確認します。</span><span class="sxs-lookup"><span data-stu-id="aff82-433">**Data Profiling in Query Editor:** Get-a-glance analysis of the data in your columns, identify error and empty values, see distribution histograms and more.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="aff82-436">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="aff82-436">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="aff82-437">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-437">Outlook</span></span>

- <span data-ttu-id="aff82-438">アイテム保持ポリシーに基づいて期限切れになるメールに 2 つのラベルが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-438">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="aff82-439">メールが 1 日で期限切れになることを示すものと、2 日で期限切れになることを示すものです。</span><span class="sxs-lookup"><span data-stu-id="aff82-439">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-440">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-440">Word</span></span>

- <span data-ttu-id="aff82-441">&quot;反転&quot;] ページ色の読み取りモードでコメントのヒントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-441">Fixed an issue where comment hint was not visible in read mode with &quot;Inverse&quot; page color.</span></span>

- <span data-ttu-id="aff82-442">コメントを編集してテキストをイタリック体し、投稿した後にイタリック体の書式設定が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-442">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>

- <span data-ttu-id="aff82-443">コメント コンテキスト メニューのコメント コマンド (コメントの編集、コメントへの返信、コメントの削除、コメントの解決) が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-443">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-january-17"></a><span data-ttu-id="aff82-445">バージョン 2002: 1 月 17 日</span><span class="sxs-lookup"><span data-stu-id="aff82-445">Version 2002: January 17</span></span>
<span data-ttu-id="aff82-446">*バージョン 2002 (ビルド 12508.20000)*</span><span class="sxs-lookup"><span data-stu-id="aff82-446">*Version 2002 (Build 12508.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="aff82-448">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-448">Feature updates</span></span>
### <a name="word"></a><span data-ttu-id="aff82-449">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-449">Word</span></span>

- <span data-ttu-id="aff82-450">**メンションとコメントの通知メールにプレビューが含まれるようになりました:** メンションとコメントのメール通知には、コメント テキストのプレビューとそれが参照している内容のコンテキストが含まれるようになりました。</span><span class="sxs-lookup"><span data-stu-id="aff82-450">**Mention & comment notification emails now contain previews:** Email notifications for mentions & comments will now include previews of the comment text and context for what it is referring to.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="aff82-453">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="aff82-453">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="aff82-454">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-454">Excel</span></span>

- <span data-ttu-id="aff82-455">アクセシビリティ チェックが図形の推奨事項を表示しないことがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-455">In some cases, the Accessibility checker would not show the recommendations for shapes.</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-456">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-456">Outlook</span></span>

- <span data-ttu-id="aff82-457">左側のナビゲーション ウィンドウで [お気に入り] に保存したフォルダーが断続的に表示されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-457">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-458">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-458">PowerPoint</span></span>

- <span data-ttu-id="aff82-459">インクが PowerPoint のインク アニメーションで使用すると完全にレンダリングされない、またはスキップされることがある問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="aff82-459">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2001-january-10"></a><span data-ttu-id="aff82-461">バージョン 2001: 1 月 10 日</span><span class="sxs-lookup"><span data-stu-id="aff82-461">Version 2001: January 10</span></span>
<span data-ttu-id="aff82-462">*バージョン 2001 (ビルド 12430.20000)*</span><span class="sxs-lookup"><span data-stu-id="aff82-462">*Version 2001 (Build 12430.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="aff82-464">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-464">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="aff82-465">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-465">Excel</span></span>
- <span data-ttu-id="aff82-466">**図形を画像として保存する:** 簡単なクリック操作で図形、アイコン、その他のオブジェクトを画像ファイルとして保存し、別の場所で再利用することができます。</span><span class="sxs-lookup"><span data-stu-id="aff82-466">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="aff82-467">詳細情報</span><span class="sxs-lookup"><span data-stu-id="aff82-467">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

### <a name="outlook"></a><span data-ttu-id="aff82-468">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-468">Outlook</span></span>
- <span data-ttu-id="aff82-469">**Word、Excel、Outlook のオブジェクトを Windows 用の画像として保存できるようになりました。:** PowerPoint で既に提供されていたこの機能を使うとで、ユーザーは Word、Excel、Outlook 内のオブジェクトを画像として保存できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="aff82-469">**User can now save objects in Word/Excel/Outlook as a picture for Windows.:** With the ability already seen in PowerPoint, users can now save objects in Word, Excel and Outlook as a picture.</span></span> <span data-ttu-id="aff82-470">オブジェクトには、図形、アイコン、図などがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-470">Objects include shapes, icons, pictures, and more!</span></span> <span data-ttu-id="aff82-471">右クリックのメニューからアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="aff82-471">This can be accessed through the right-click menu.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-472">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-472">Word</span></span>
- <span data-ttu-id="aff82-473">**周りに図形を描くだけで Word のインク描画を簡単に選択できます。:** [描画] タブのなげなわツールを使用することで、インクで描画されたオブジェクトを選択することができます。</span><span class="sxs-lookup"><span data-stu-id="aff82-473">**Easily select ink in Word by drawing a shape around it.:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="aff82-474">個別のストロークまたは文字全体を選択できます。</span><span class="sxs-lookup"><span data-stu-id="aff82-474">Select individual strokes, or whole words.</span></span> <span data-ttu-id="aff82-475">インク描画が多数ある場合に、その中の一部を操作したい場合に便利です。</span><span class="sxs-lookup"><span data-stu-id="aff82-475">It's handy when you have lots of ink and you only want to work with some of it.</span></span> [<span data-ttu-id="aff82-476">詳細情報</span><span class="sxs-lookup"><span data-stu-id="aff82-476">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="aff82-477">**図形を画像として保存する:** 簡単なクリック操作で図形、アイコン、その他のオブジェクトを画像ファイルとして保存し、別の場所で再利用することができます。</span><span class="sxs-lookup"><span data-stu-id="aff82-477">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="aff82-478">詳細情報</span><span class="sxs-lookup"><span data-stu-id="aff82-478">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="aff82-481">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="aff82-481">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="aff82-482">OneNote</span><span class="sxs-lookup"><span data-stu-id="aff82-482">OneNote</span></span>
- <span data-ttu-id="aff82-483">100% の解像度だと、ページ タブが小さすぎるためにくっついて表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-483">Page tabs may appear too small and close together at 100% resolution.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-484">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-484">Word</span></span>
- <span data-ttu-id="aff82-485">コメントの数が多い場合、コメント一覧の末尾付近のコメントを削除すると、ウィンドウが一番上までスクロールされる場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-485">In a large set of comments, deleting a comment near the end of the list of comments may result in the pane scrolling all the way to the top.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2001-january-03"></a><span data-ttu-id="aff82-487">バージョン 2001: 1 月 3 日</span><span class="sxs-lookup"><span data-stu-id="aff82-487">Version 2001: January 03</span></span>
<span data-ttu-id="aff82-488">*バージョン 2001 (ビルド 12425.20000)*</span><span class="sxs-lookup"><span data-stu-id="aff82-488">*Version 2001 (Build 12425.20000)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="aff82-490">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="aff82-490">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-491">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-491">Excel</span></span>
- <span data-ttu-id="aff82-492">一部の罫線は A4 サイズ用紙に印刷されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-492">Some border lines may not print as expected on A4 size paper.</span></span>
- <span data-ttu-id="aff82-493">VBA を使用してシート上のグラフオブジェクトのヘッダーまたはフッターに画像を追加すると、エラーが発生することがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-493">Adding an image to the header/footer of a chart object on a sheet using VBA may result in an error.</span></span>
- <span data-ttu-id="aff82-494">グラフの軸を書式設定するときにラベルの間隔が 255 に制限されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-494">When formatting a chart axis, the interval between labels was limited to 255.</span></span>
- <span data-ttu-id="aff82-495">データ ソースの URL が切り詰められている XML クエリを更新しようとするとエラーが発生するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-495">Fixed an issue where an error would occur trying to refresh an XML query in which the URL to the datasource was being truncated.</span></span>
- <span data-ttu-id="aff82-496">ブックの統計情報では、個人のマクロ ブックを含め、開いているすべてのブックからマクロの回数が報告されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-496">Workbook Statistics would report a macro count from all open workbooks, including the personal macro workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-497">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-497">Outlook</span></span>
- <span data-ttu-id="aff82-498">フォルダーを切り替えると、メール リスト/メール プレビューに、しばらく白い「フラッシュ」が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-498">Switching folders may result in a brief white 'flash' in the mail list / mail preview.</span></span> <span data-ttu-id="aff82-499">この現象は、ダーク モードでより顕著になりました。</span><span class="sxs-lookup"><span data-stu-id="aff82-499">This behavior was more pronounced in dark mode.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-500">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-500">PowerPoint</span></span>
- <span data-ttu-id="aff82-501">Shape.Paste メソッドを呼び出すと貼り付けられた図形がフォーカスされるオブジェクトモデルの問題を修正しました。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="aff82-501">Fixed an Object Model issue where calling Shape.Paste method would result in the pasted shape receiving focus.&nbsp;</span></span>
- <span data-ttu-id="aff82-502">コピーと貼り付けシナリオの改善: &nbsp;PowerPoint スライドからプログラムによってコピーして、ループ内の別のスライドに貼り付けると、例外エラーが発生する場合があります。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="aff82-502">Improved a copy-paste scenario:&nbsp;Progamatically copying a shape from a PowerPoint slide and pasting it to another slide in a loop could fail with an exception error.&nbsp;</span></span>
- <span data-ttu-id="aff82-503">スライドのセクション ヘッダー内のアニメーションは、セクション ヘッダーを折りたたんで展開した後は、正しくレンダリングされません。</span><span class="sxs-lookup"><span data-stu-id="aff82-503">Animation in the section headers of slides would not render properly after collapsing and expanding section headers.</span></span>

### <a name="project"></a><span data-ttu-id="aff82-504">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-504">Project</span></span>
- <span data-ttu-id="aff82-505">文字列の折り返しが [タスク] ビュー と [リソース配分状況] ビューで機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-505">Fixed an issue where text wrapping wasn't working in the task and resource usage views.</span></span>
- <span data-ttu-id="aff82-506">リソースに複数の原価率がある場合、割り当ての原価価値が正しくない可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-506">Fixed an issue where if a resource has more than one cost rate, cost value on assignments may not be correct.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-507">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-507">Word</span></span>
- <span data-ttu-id="aff82-508">コントロール (テキスト コンテンツ コントロールなど) を数式に挿入し、ファイルを保存して開くと、読み取り不可能なコンテンツ エラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="aff82-508">Inserting a control (such as a Text Content Control) in an equation, then saving and opening the file would result in an un-readable content error.</span></span>
- <span data-ttu-id="aff82-509">共同編集時に、Word Online を使用して追加したコメントが Word デスクトップに表示されません。</span><span class="sxs-lookup"><span data-stu-id="aff82-509">When co-authoring, adding a comment using Word online may not appear in Word desktop.</span></span>

### <a name="office-suite"></a><span data-ttu-id="aff82-510">Office スイート</span><span class="sxs-lookup"><span data-stu-id="aff82-510">Office Suite</span></span>
- <span data-ttu-id="aff82-511">ライセンスを 1 つだけ使用してライセンスを変更しようとしたときに、有効なライセンスの有効期限が誤って表示されなくなりました。</span><span class="sxs-lookup"><span data-stu-id="aff82-511">Removed showing an erroneous expiry date of the valid license when trying to change license with only one license.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2001-december-13"></a><span data-ttu-id="aff82-513">バージョン 2001: 12 月 13 日</span><span class="sxs-lookup"><span data-stu-id="aff82-513">Version 2001: December 13</span></span>
<span data-ttu-id="aff82-514">*バージョン 2001 (ビルド 12410.20000)*</span><span class="sxs-lookup"><span data-stu-id="aff82-514">*Version 2001 (Build 12410.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="aff82-516">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-516">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="aff82-517">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-517">Outlook</span></span>

- <span data-ttu-id="aff82-518">**所有しているグループにメールをドラッグ:** メッセージや会話を受信トレイからドラッグして移動し、コピーします。</span><span class="sxs-lookup"><span data-stu-id="aff82-518">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="aff82-519">ドラッグしたメッセージは、すべてのグループ メンバーと共有されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-519">Messages you drag will be shared with all group members.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="aff82-522">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="aff82-522">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="aff82-523">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-523">Access</span></span>
- <span data-ttu-id="aff82-524">リンクされた ODBC テーブルを参照し、Order By 句を含めるユニオン クエリを実行すると、64ビット版アクセスがクラッシュします。</span><span class="sxs-lookup"><span data-stu-id="aff82-524">Executing a union query that references linked ODBC table(s) and contains an Order By clause crashes 64 bit Access.</span></span>
- <span data-ttu-id="aff82-525">Access (O365) のユニオン クエリからデータを集計すると、10 進型データを切り捨ててしまうことがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-525">Summing of data from union queries in Access (O365) may result in truncation of decimal data.</span></span>
- <span data-ttu-id="aff82-526">ACE の COM インターフェイスは、Office アプリケーションの外部で使用することはできません。</span><span class="sxs-lookup"><span data-stu-id="aff82-526">COM Interfaces for ACE are not exposed for use outside of Office applications.</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-527">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-527">Excel</span></span>
- <span data-ttu-id="aff82-528">3D モデル (アニメーションまたはスタティック) を挿入し、[図として保存] を行おうとしても動作しません。</span><span class="sxs-lookup"><span data-stu-id="aff82-528">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>
- <span data-ttu-id="aff82-529">Backstage からフィードバックを開始するためのショートカットキー (Alt + Ctrl + 7/8) は、AZERTY キーボード (Alt - Gr + 7/8) と競合しています。</span><span class="sxs-lookup"><span data-stu-id="aff82-529">The shortkey (Alt+Ctrl + 7/8)  to launch feedback from backstage is in conflict with AZERTY keyboards (Alt-Gr + 7/8).</span></span> <span data-ttu-id="aff82-530">影響: ユーザーは次のような文字を使用できない場合があります'\'。</span><span class="sxs-lookup"><span data-stu-id="aff82-530">Impact: users may not be able to use some characters such as: '\'.</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-531">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-531">Outlook</span></span>
- <span data-ttu-id="aff82-532">メールが受信者の間違ったアドレスに送信される原因となる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="aff82-532">Addresses an issue that caused email to be sent to the wrong address for the recipient.</span></span>
- <span data-ttu-id="aff82-533">Outlook でメールボックスへの &quot;読み取り&quot; アクセス権のあるユーザーに対して、メッセージの [既読/未読] 状態の変更を誤って許可する原因となる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="aff82-533">Addresses an issue that caused Outlook to incorrectly allow users with &quot;read&quot; access to a mailbox to change the read/unread state of a message.</span></span>
- <span data-ttu-id="aff82-534">Web サイト上のセキュリティ証明書を失効すると、製品サポートによって再度作成することはできません。</span><span class="sxs-lookup"><span data-stu-id="aff82-534">The revocation of the security certificate on the web site is not re-producible by Product Support.</span></span> <span data-ttu-id="aff82-535">この問題の根本原因を解決するには、ログを追加する必要があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-535">Logging needs to be added to help root cause the issue.</span></span>
- <span data-ttu-id="aff82-536">同期エラーが表示されてしまう問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="aff82-536">Addresses an issue that caused users to see synchronization failures.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-537">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-537">PowerPoint</span></span>
- <span data-ttu-id="aff82-538">3D モデル (アニメーションまたはスタティック) を挿入し、[図として保存] を行おうとしても動作しません。</span><span class="sxs-lookup"><span data-stu-id="aff82-538">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="project"></a><span data-ttu-id="aff82-539">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-539">Project</span></span>
- <span data-ttu-id="aff82-540">タスクの作業は、手動スケジュール タスクの Summary roll-up では計算されません。</span><span class="sxs-lookup"><span data-stu-id="aff82-540">Task work is not calculated in Summary roll-up for manually scheduled child tasks.</span></span>
- <span data-ttu-id="aff82-541">サーバーベースのプロジェクトを保存しようとすると、リボン ボタンから呼び出された Project VBA コードが機能しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-541">Project VBA Code invoked from a Ribbon button may not work when trying to save server-based Projects.</span></span>
- <span data-ttu-id="aff82-542">プロジェクトを実行していない場合は、SharePoint ドキュメント ライブラリからプロジェクト ファイルを開くとエラーが表示され、ファイルが開くことはできません。</span><span class="sxs-lookup"><span data-stu-id="aff82-542">Unless Project is already running, opening Project files from a SharePoint document library displays an error and the file will not open.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-543">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-543">Word</span></span>
- <span data-ttu-id="aff82-544">既存のファイルの保存が出来ない場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-544">Saving existing files may not work.</span></span>
- <span data-ttu-id="aff82-545">[スペルチェックと文章校正] ウィンドウで方向キーを使用すると、断続的に画面がちらつくことがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-545">Using arrow keys in the Spelling and Grammar editor window may result in intermittent flickering.</span></span>
- <span data-ttu-id="aff82-546">フォローアップを解決するときに、関連するコメントはポイントのコメントに変換されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-546">When resolving a follow-up, associated comments may not convert to point comments.</span></span>
- <span data-ttu-id="aff82-547">3D モデル (アニメーションまたはスタティック) を挿入し、[図として保存] を行おうとしても動作しません。</span><span class="sxs-lookup"><span data-stu-id="aff82-547">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="aff82-548">Office スイート</span><span class="sxs-lookup"><span data-stu-id="aff82-548">Office Suite</span></span>
- <span data-ttu-id="aff82-549">Office の更新メッセージが、異なる言語で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-549">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="aff82-550">今後、Office の更新メッセージは Windows の表示言語と一致します。</span><span class="sxs-lookup"><span data-stu-id="aff82-550">Going forward, Office update messages will correctly match the Windows display language.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1912-december-06"></a><span data-ttu-id="aff82-552">バージョン 1912: 12 月 6 日</span><span class="sxs-lookup"><span data-stu-id="aff82-552">Version 1912: December 06</span></span>
<span data-ttu-id="aff82-553">*バージョン 1912 (ビルド 12325.20012)*</span><span class="sxs-lookup"><span data-stu-id="aff82-553">*Version 1912 (Build 12325.20012)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="aff82-555">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-555">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="aff82-556">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-556">Outlook</span></span>

- <span data-ttu-id="aff82-557">**高度なグループ メールの設定:** この機能は、グループ ユーザーが受信トレイで受信/フォローするメールまたはイベントを、カスタマイズするのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="aff82-557">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="aff82-558">**グループの名前付けポリシー**: グループの名前付けポリシーを使用すると、IT 管理者は組織内のユーザーが作成するグループの名前の標準化と管理を行えます。</span><span class="sxs-lookup"><span data-stu-id="aff82-558">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="aff82-559">管理者は、グループが作成される際に特定のプレフィックスとサフィックスをグループ名に追加することを要求できます。また、特定の単語の使用を禁止できます。</span><span class="sxs-lookup"><span data-stu-id="aff82-559">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="aff82-560">これにより、グループ名での不適切な単語の使用を最小限に抑えられる他、ディレクトリ内のグループ名の記載を IT 管理者が管理できます。</span><span class="sxs-lookup"><span data-stu-id="aff82-560">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="aff82-561">また、名前付けポリシーを使用することで、チーム サイトを展開する組織は、チーム サイトを部署ごとに分類できるようにもなります。</span><span class="sxs-lookup"><span data-stu-id="aff82-561">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="office-suite"></a><span data-ttu-id="aff82-562">Office スイート</span><span class="sxs-lookup"><span data-stu-id="aff82-562">Office Suite</span></span>

- <span data-ttu-id="aff82-563">**タブ付きのウィンドウ**: アプリの右側にあるタブ UI を使用して、複数のウィンドウ間を切り替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="aff82-563">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="aff82-564">UI は、2 つ以上のウィンドウが開かれている場合にのみ表示されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-564">The UI will only be visible when you have 2+ panes open.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="aff82-567">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="aff82-567">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="aff82-568">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-568">Excel</span></span>
- <span data-ttu-id="aff82-569">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-569">Users may encounter an error when saving changes while using some non-English character sets.</span></span>
- <span data-ttu-id="aff82-570">非表示の名前付き範囲にアクセスすると、ユーザーにエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-570">Users may encounter an error when accessing a hidden named range.</span></span>
- <span data-ttu-id="aff82-571">4K 解像度のハードウェアのグラフィック アクセラレータを無効にすると、スクロールしたときにセルのレンダリングが遅れる場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-571">Disabling hardware graphics acceleration with 4K resolution may result in delayed rendering of cells when scrolling around.</span></span>
- <span data-ttu-id="aff82-572">セルの境界に重なる長い数式をクリアしても、セルの境界を越えて表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-572">Clearing a long formula that overlaps a cell boundary may still display across the cell boundary.</span></span>
- <span data-ttu-id="aff82-573">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-573">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>
- <span data-ttu-id="aff82-574">余白のドロップダウン メニューが正しくレンダリングされない場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-574">Margin dropdown menu may not render correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="aff82-575">OneNote</span><span class="sxs-lookup"><span data-stu-id="aff82-575">OneNote</span></span>
- <span data-ttu-id="aff82-576">OneNote は、「会議ノート」の Outlook アドインを介して開かない場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-576">OneNote may not open via the 'Meeting Notes' Outlook add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-577">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-577">Outlook</span></span>
- <span data-ttu-id="aff82-578">保持ポリシーのラベルには、保持期間がかっこ内に表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-578">Retention policy labels may display the retention time period in parenthesis.</span></span>
- <span data-ttu-id="aff82-579">日本語パックの連絡先カードに空白が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-579">Blank spaces may appear in Contact cards with Japanese language pack.</span></span>
- <span data-ttu-id="aff82-580">Outlook のメール メッセージにインラインで挿入された画像のサイズが変更される場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-580">Images inserted inline to Outlook e-mail messages can sometimes get resized.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-581">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-581">PowerPoint</span></span>
- <span data-ttu-id="aff82-582">クラウド ファイル内のスライドに 2 つ以上の異なるビデオがある場合、ビデオの画像は正しく表示されますが、ユーザーがそれぞれのビデオを再生するためにクリックすると、同一の内容のビデオが再生されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-582">If a user has two (or more) different videos on a slide in a cloud file, the video images are rendered correctly, but when the user clicks on each one to play, the video content is the same.</span></span>
- <span data-ttu-id="aff82-583">場合によっては、タッチ デバイスでのスクロールが機能しないことがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-583">In some cases, scrolling with touch devices will not work.</span></span>
- <span data-ttu-id="aff82-584">余白のドロップダウン メニューが正しくレンダリングされない場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-584">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="aff82-585">ある Office アプリケーションから別の Office アプリケーションへの安全なリンクは、リンクされたアプリケーションを起動しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-585">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="project"></a><span data-ttu-id="aff82-586">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-586">Project</span></span>
- <span data-ttu-id="aff82-587">[プロジェクトの比較] 機能を使用すると、Project がクラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-587">Project may crash when you use the Compare Projects feature.</span></span>
- <span data-ttu-id="aff82-588">ダーク モードの場合、リソースが過剰に割り当てられているタスクのタスク検査パネルに移動すると、表を読み取ることができません。</span><span class="sxs-lookup"><span data-stu-id="aff82-588">If you are in Dark mode, when you go to the task inspector panel on a task with an over allocated resource, you are unable to read the table.</span></span>
- <span data-ttu-id="aff82-589">割り当てのないタスクに作業を設定すると、1 日間に丸められます。</span><span class="sxs-lookup"><span data-stu-id="aff82-589">Setting effort on tasks that have no assignments are rounded to 1 day.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-590">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-590">Word</span></span>
- <span data-ttu-id="aff82-591">差し込み印刷の実行後に、特定の条件下でファイルを保存できない場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-591">Saving a file after doing a mail merge may not work under certain conditions.</span></span>
- <span data-ttu-id="aff82-592">文書パーツ オーガナイザーに無効なアラートが表示される場合があります。&quot;スタイル、文書パーツを変更しました。&quot;</span><span class="sxs-lookup"><span data-stu-id="aff82-592">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>
- <span data-ttu-id="aff82-593">コピーと貼り付けを使用すると、コメント ウィンドウが再読み込みされることがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-593">Comment pane sometimes gets reloaded when using copy/paste.</span></span>
- <span data-ttu-id="aff82-594">コメントが正しい順序で貼り付けられない場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-594">Comments are sometimes not pasted in the correct order.</span></span>
- <span data-ttu-id="aff82-595">カスタム スタイルのマルチレベル リストで構成されるテンプレートを既存のドキュメントに適用すると、特定の条件下でスタイルが保持されない場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-595">Applying a template consisting of a multi-level list with custom styles to existing documents may not preserve the style under certain conditions.</span></span>
- <span data-ttu-id="aff82-596">分割画面の境界のサイズを変更すると、さらに分割画面が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-596">Resizing a split screen border may introduce an additional split screen.</span></span>
- <span data-ttu-id="aff82-597">余白のドロップダウン メニューが正しくレンダリングされない場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-597">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="aff82-598">コメント カードでユーザーをメンションすると、JSON が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-598">At-mentioning a user in a comment card may show JSON.</span></span>
- <span data-ttu-id="aff82-599">ある Office アプリケーションから別の Office アプリケーションへの安全なリンクは、リンクされたアプリケーションを起動しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-599">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="office-suite"></a><span data-ttu-id="aff82-600">Office スイート</span><span class="sxs-lookup"><span data-stu-id="aff82-600">Office Suite</span></span>
- <span data-ttu-id="aff82-601">日本語ベースの製品の場合、アカウント ユーザーの姓と名が誤った順序で表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-601">For Japanese based products, account user first name, last name may appear in incorrect order.</span></span>
- <span data-ttu-id="aff82-602">コメントにマウス ポインターを合わせた際に、コメントの周りにテキストボックスのアウトラインが表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-602">Hovering a mouse pointer over comments may display a textbox outline around the comment.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1912-november-15"></a><span data-ttu-id="aff82-604">バージョン 1912: 11 月 15 日</span><span class="sxs-lookup"><span data-stu-id="aff82-604">Version 1912: November 15</span></span>
<span data-ttu-id="aff82-605">*バージョン 1912 (ビルド 12307.20000)*</span><span class="sxs-lookup"><span data-stu-id="aff82-605">*Version 1912 (Build 12307.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="aff82-607">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-607">Feature updates</span></span>
### <a name="insights-services"></a><span data-ttu-id="aff82-608">インサイト サービス</span><span class="sxs-lookup"><span data-stu-id="aff82-608">Insights Services</span></span>
- <span data-ttu-id="aff82-609">**Excel のアイデアの自然言語のクエリ:** データについて自然言語の質問をする Excel のアイデアの新機能。</span><span class="sxs-lookup"><span data-stu-id="aff82-609">**Natural Language Queries in Ideas in Excel:** Excel Ideas's new capability to ask a natural language question about your data.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="aff82-612">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="aff82-612">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="aff82-613">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-613">Excel</span></span>
- <span data-ttu-id="aff82-614">一部のローカライズにおいて、[Text to Column] 機能が失敗することがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-614">Text to Column functionality may fail for some localizations.</span></span>
- <span data-ttu-id="aff82-615">セル内の動的配列数式を編集すると、セルの境界の外にテキストが並んでしまう場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-615">Editing dynamic array formulas within a cell may result in text being aligned outside of the boundary of the cell.</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-616">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-616">Outlook</span></span>
- <span data-ttu-id="aff82-617">グループ ポリシーを使用して S/MIME 構成を適用する機能が追加されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-617">Added the ability to enforce S/MIME configuration via group policy.</span></span>
- <span data-ttu-id="aff82-618">思ったよりも埋め込み画像が小さく表示されることがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-618">Embedded images may appear smaller than expected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-619">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-619">PowerPoint</span></span>
- <span data-ttu-id="aff82-620">テキストからフォーカスを移動した後、カーソルが表示されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-620">Cursor may disappear after moving focus from text.</span></span>

### <a name="project"></a><span data-ttu-id="aff82-621">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-621">Project</span></span>
- <span data-ttu-id="aff82-622">ユーザーにライセンスに関するエラーが表示されることがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-622">Users may experience an error regarding licensing.</span></span>
- <span data-ttu-id="aff82-623">日付の選択の [今日] ボタンで正しくない日付が設定されることがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-623">The Today button in the date picker may sometimes set the incorrect date.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-624">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-624">Word</span></span>
- <span data-ttu-id="aff82-625">右クリックすると、完全に一致する単語が選択されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-625">Right-clicking can sometimes not result in selecting the whole word.</span></span>
- <span data-ttu-id="aff82-626">提案されたファイル形式に変換した後、カーソルがオブジェクト内でアクティブのままになってしまうことがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-626">The cursor may remain active within an object after converting to a suggested format.</span></span>
- <span data-ttu-id="aff82-627">一部のシナリオでは、メッセージ内の画像が正しく拡大されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-627">Images in messages may be incorrectly scaled in some scenarios.</span></span>
- <span data-ttu-id="aff82-628">一部のテーマでは、どのコメントが選択されているかの判断が困難になることがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-628">Some themes may make it difficult to determine which comment is selected.</span></span>
- <span data-ttu-id="aff82-629">ウィンドウ スイッチャーで非表示のときに、コメントのヒントを選択すると最新のコメント ウィンドウが表示されるようになります。</span><span class="sxs-lookup"><span data-stu-id="aff82-629">Selecting a comment hint should now show the modern comments pane when hidden in pane switcher.</span></span>

### <a name="office-suite"></a><span data-ttu-id="aff82-630">Office スイート</span><span class="sxs-lookup"><span data-stu-id="aff82-630">Office Suite</span></span>
- <span data-ttu-id="aff82-631">コメントに返信すると、テキスト ボックスがウィンドウの端を超えて縦方向に展開されることがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-631">Replying to a comment may cause the textbox to expand vertically beyond the edge of the pane.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1912-november-08"></a><span data-ttu-id="aff82-633">バージョン 1912: 11 月 8 日</span><span class="sxs-lookup"><span data-stu-id="aff82-633">Version 1912: November 08</span></span>
<span data-ttu-id="aff82-634">*バージョン 1912 (ビルド 12231.20000)*</span><span class="sxs-lookup"><span data-stu-id="aff82-634">*Version 1912 (Build 12231.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="aff82-636">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-636">Feature updates</span></span>
### <a name="user-lifecycle"></a><span data-ttu-id="aff82-637">ユーザーのライフサイクル</span><span class="sxs-lookup"><span data-stu-id="aff82-637">User Lifecycle</span></span>
- <span data-ttu-id="aff82-638">**AFO アクティベーションのエクスペリエンスの改善:** 新しい PC にバンドルされている Office のアクティベーション時にお客様に表示される画面の更新。</span><span class="sxs-lookup"><span data-stu-id="aff82-638">**Experience improvements for AFO activation:** Updates to the screens customers see when activating Office that comes bundled with their new PC.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-639">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-639">Word</span></span>
- <span data-ttu-id="aff82-640">**Word の新しい、改善されたオンライン ビデオ エクスペリエンス:** Word での新しいビデオの挿入および既存のビデオの再生に役立つ、新しくより安全なオンライン ビデオ エクスペリエンス。</span><span class="sxs-lookup"><span data-stu-id="aff82-640">**New and improved online video experience in Word:** New and more secure online video experience to help you insert new videos and play existing videos in Word.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="aff82-643">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="aff82-643">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="aff82-644">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-644">Outlook</span></span>
- <span data-ttu-id="aff82-645">クロス フォルダー コンテンツを含む断続的なクラッシュ。</span><span class="sxs-lookup"><span data-stu-id="aff82-645">Intermittent crash involving cross folder content.</span></span>

### <a name="office-suite"></a><span data-ttu-id="aff82-646">Office スイート</span><span class="sxs-lookup"><span data-stu-id="aff82-646">Office Suite</span></span>
- <span data-ttu-id="aff82-647">Excel から PowerPoint にグラフを貼り付けると、グラフのサイズが小さくなる場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-647">Pasting a chart from Excel to PowerPoint can reduce the size of the chart.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1911-november-01"></a><span data-ttu-id="aff82-649">バージョン 1911: 11 月 1 日</span><span class="sxs-lookup"><span data-stu-id="aff82-649">Version 1911: November 01</span></span>
<span data-ttu-id="aff82-650">*バージョン 1911 (ビルド 12228.20020)*</span><span class="sxs-lookup"><span data-stu-id="aff82-650">*Version 1911 (Build 12228.20020)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="aff82-652">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-652">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="aff82-653">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-653">Excel</span></span>
- <span data-ttu-id="aff82-654">**SVG オブジェクトにコンテキストを取り入れる:** 地図やグラフ、その他の SVG ベクターを Office で変換する場合、それらのオブジェクトの中にテキストを保持できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="aff82-654">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="aff82-655">**Surface ペンを使用するときにペンのオプションを確認する:** Word、Excel、PowerPoint で Surface ペンを初めて使用するときに、ペンの色を簡単に選べる [描画] タブがアクティブになります。</span><span class="sxs-lookup"><span data-stu-id="aff82-655">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-656">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-656">PowerPoint</span></span>
- <span data-ttu-id="aff82-657">**SVG オブジェクトにコンテキストを取り入れる:** 地図やグラフ、その他の SVG ベクターを Office で変換する場合、それらのオブジェクトの中にテキストを保持できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="aff82-657">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="aff82-658">**Surface ペンを使用するときにペンのオプションを確認する:** Word、Excel、PowerPoint で Surface ペンを初めて使用するときに、ペンの色を簡単に選べる [描画] タブがアクティブになります。</span><span class="sxs-lookup"><span data-stu-id="aff82-658">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="visio"></a><span data-ttu-id="aff82-659">Visio</span><span class="sxs-lookup"><span data-stu-id="aff82-659">Visio</span></span>
- <span data-ttu-id="aff82-660">**Excel で洗練された Visio 図を作成する:** すばやく簡単に、データを Excel 内の洗練された Visio 図に可視化します。</span><span class="sxs-lookup"><span data-stu-id="aff82-660">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> <span data-ttu-id="aff82-661">[詳細情報](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c) を参照してください。</span><span class="sxs-lookup"><span data-stu-id="aff82-661">[Learn more](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).</span></span>

### <a name="word"></a><span data-ttu-id="aff82-662">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-662">Word</span></span>
- <span data-ttu-id="aff82-663">**Surface ペンを使用するときにペンのオプションを確認する:** Word、Excel、PowerPoint で Surface ペンを初めて使用するときに、ペンの色を簡単に選べる [描画] タブがアクティブになります。</span><span class="sxs-lookup"><span data-stu-id="aff82-663">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

- <span data-ttu-id="aff82-664">**共同編集の改善:** コンテンツの変更をリアルタイムでユーザーが受け取れるようにすることで、共同編集のエクスペリエンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-664">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="aff82-665">**他のユーザーがすばやく変更を確認:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="aff82-665">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="aff82-668">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="aff82-668">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="aff82-669">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-669">Excel</span></span>
- <span data-ttu-id="aff82-670">信頼されていないネットワーク共有から保護されたファイルを編集すると、Excel がクラッシュすることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-670">Resolved an issue where Excel may crash when editing a protected file from an untrusted network share.</span></span>
- <span data-ttu-id="aff82-671">別のシートのデータを参照しているスパークラインを含むシートを削除すると、再びそのファイルを開いた時に破損したファイルとして識別されるという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-671">Resolved an issue where deleting sheets containing sparklines referencing data on another sheet could cause the file to be identified as corrupted when re-opened.</span></span>
- <span data-ttu-id="aff82-672">SQL 表形式サーバーのクエリのピボットテーブルの残りの部分と一緒にレポート フィルターを変換すると、正しい結果が返されないことがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-672">Resolved an Issue where you may get incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span>
- <span data-ttu-id="aff82-673">ナレーターと拡大鏡を同時に使用すると、クラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-673">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="aff82-674">ナレーターと拡大鏡を同時に使用すると、クラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-674">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-675">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-675">Outlook</span></span>
- <span data-ttu-id="aff82-676">メールを転送すると、埋め込み画像がなくなる場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-676">A forwarded e-mail may be missing embedded images.</span></span>
- <span data-ttu-id="aff82-677">会議室の検索ツールで、使用可能な会議室が&quot;なし&quot;と表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-677">Room Finder tool may be displaying &quot;None&quot; for available rooms.</span></span>
- <span data-ttu-id="aff82-678">厳しいテナント制限がある Outlook プロファイルをユーザーが作成できない場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-678">Users may not be able to create Outlook profiles with strict tenant restriction.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-679">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-679">PowerPoint</span></span>
- <span data-ttu-id="aff82-680">ナレーターと拡大鏡を同時に使用すると、クラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-680">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="project"></a><span data-ttu-id="aff82-681">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-681">Project</span></span>
- <span data-ttu-id="aff82-682">ユーザーがタスクを完了としてマークすることができず、99% に設定されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-682">User is unable to mark a task as complete, and it gets set to 99%.</span></span>
- <span data-ttu-id="aff82-683">平準化によって割り当て超過が解決されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-683">Overallocations are not resolved by leveling.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-684">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-684">Word</span></span>
- <span data-ttu-id="aff82-685">ナレーターと拡大鏡を同時に使用すると、クラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-685">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="aff82-686">以前のドキュメントを開いたまま [情報] タブに移動すると、クラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-686">Opening legacy documents and then going to the Info tab can cause a crash.</span></span>
- <span data-ttu-id="aff82-687">文章校正の候補がコンテキスト メニューに表示されません。</span><span class="sxs-lookup"><span data-stu-id="aff82-687">Proofing suggestins are not displaying in contextual menus.</span></span>
- <span data-ttu-id="aff82-688">コンテンツ ポリシーがコメントに正しく適用されません。</span><span class="sxs-lookup"><span data-stu-id="aff82-688">Content policies are being incorrectly applied to comments.</span></span>
- <span data-ttu-id="aff82-689">濃色のテキストで書かれた従来のコメントがダーク モードで表示されません。</span><span class="sxs-lookup"><span data-stu-id="aff82-689">Legacy comments written with dark text is not visible in Dark Mode.</span></span>
- <span data-ttu-id="aff82-690">韓国語/英語のオートコレクトを使用しているときに、間違った文字が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-690">Incorrect characters may appear when using Korean/English autocorrect.</span></span>
- <span data-ttu-id="aff82-691">上位のポリシー ラベルが優先して適用されるべき時に、低いポリシー ラベルが適用されることがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-691">Lower policy labels may be applied when a higher policy label should have taken priority.</span></span>
- <span data-ttu-id="aff82-692">Outlook メッセージ &nbsp; からの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="aff82-692">The links of cid: images from Outlook messages&nbsp;can now be successfully broken when requested.</span></span>
- <span data-ttu-id="aff82-693">ナレーターと拡大鏡を同時に使用すると、クラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-693">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="aff82-694">ナビゲーション ウィンドウから検索できない場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-694">Searching from the Navigation pane may fail.</span></span>

### <a name="office-suite"></a><span data-ttu-id="aff82-695">Office スイート</span><span class="sxs-lookup"><span data-stu-id="aff82-695">Office Suite</span></span>
- <span data-ttu-id="aff82-696">一部の描画がプレビューやスライド ショーに表示されない場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-696">Some drawings may not display in preview or slide shows.</span></span>
- <span data-ttu-id="aff82-697">縦書きのテキスト ボックス内で一部のカタカナが正しく表示されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-697">Some katakana characters may display incorrectly in a vertical text box.</span></span>
- <span data-ttu-id="aff82-698">接続されていないネットワーク共有にファイルを保存しようとすると、クラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-698">Attempting to save a file to a disconnected network share may result in a crash.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1911-october-25"></a><span data-ttu-id="aff82-700">バージョン 1911: 10 月 25 日</span><span class="sxs-lookup"><span data-stu-id="aff82-700">Version 1911: October 25</span></span>
<span data-ttu-id="aff82-701">*バージョン 1911 (ビルド 12215.20006)*</span><span class="sxs-lookup"><span data-stu-id="aff82-701">*Version 1911 (Build 12215.20006)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="aff82-703">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-703">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="aff82-704">Visio</span><span class="sxs-lookup"><span data-stu-id="aff82-704">Visio</span></span>

- <span data-ttu-id="aff82-705">**Excel で洗練された Visio 図を作成する:** すばやく簡単に、データを Excel 内の洗練された Visio 図に可視化します。</span><span class="sxs-lookup"><span data-stu-id="aff82-705">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> [<span data-ttu-id="aff82-706">詳細情報</span><span class="sxs-lookup"><span data-stu-id="aff82-706">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="aff82-707">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-707">Word</span></span>

- <span data-ttu-id="aff82-708">**共同編集の改善:** コンテンツの変更をリアルタイムでユーザーが受け取れるようにすることで、共同編集のエクスペリエンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-708">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="aff82-709">**他のユーザーがすばやく変更を確認:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="aff82-709">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="aff82-712">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="aff82-712">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="aff82-713">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-713">Access</span></span>

- <div><span data-ttu-id="aff82-714"><span>レコードのカウントが正しくないという問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-714"><span>The record count could be incorrect</span></span></span></div>


### <a name="excel"></a><span data-ttu-id="aff82-715">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-715">Excel</span></span>

- <div><span data-ttu-id="aff82-716"><span>結合されたセルで列を削除するパフォーマンスが大幅に改善されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-716"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


- <div><span data-ttu-id="aff82-717"><span>ユーザーが Office 365 の Excel ブック形式で保存できなくなる問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-717"><span>Users could be prevented from saving in Office 365 Excel Workbook format</span></span></span></div>


- <div><span data-ttu-id="aff82-718"><span>チェックボックスで正しく表示できないという問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-718"><span>Checkboxes could not render correctly</span></span></span></div>


- <div><span data-ttu-id="aff82-719"><span>グラフのサイズの変更が保存できないという問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-719"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="aff82-720"><span>VBA 関数の一部で、新しいグラフの種類に関するエラーが返される問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-720"><span>Some VBA functions would return an error on new chart types</span></span></span></div>


- <div><span data-ttu-id="aff82-721"><span>[データ ソースの選択] ダイアログで、一部のフィールドの大文字小文字の区別をしなかった問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-721"><span>Select Data Source dialogs were not case sensitive for some fields</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="aff82-722">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-722">PowerPoint</span></span>

- <div><span data-ttu-id="aff82-723"><span>グラフのサイズの変更が保存できないという問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-723"><span>Changes to a chart size could not be saved</span></span></span></div>


### <a name="publisher"></a><span data-ttu-id="aff82-724">Publisher</span><span class="sxs-lookup"><span data-stu-id="aff82-724">Publisher</span></span>

- <div><span data-ttu-id="aff82-725"><span>図形がグラフィックの境界線の外側に表示される問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-725"><span>Shapes could appear outside of the graphics border</span></span></span></div>


### <a name="word"></a><span data-ttu-id="aff82-726">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-726">Word</span></span>

- <div><span data-ttu-id="aff82-727"><span>図形がグラフィックの境界線の外側に表示される問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-727"><span>Shapes could appear outside of the graphics border</span></span></span></div>


- <div><span data-ttu-id="aff82-728"><span>テキストの強調表示が課題になるという問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-728"><span>Highlighting text could be challenging</span></span></span></div>


- <div><span data-ttu-id="aff82-729"><span>ユーザーがエディターの個々のアイテムに移動できなくなる問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-729"><span>A user could be prevented from navigating to an individual item in the editor</span></span></span></div>


- <div><span data-ttu-id="aff82-730"><span>文法またはスペルのエラーが強調表示されない問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-730"><span>Grammar or spelling errors might not be highlighted</span></span></span></div>


- <div><span data-ttu-id="aff82-731"><span>グラフのサイズの変更が保存できないという問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-731"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="aff82-732"><span>連絡先カードが、@ メンションに書式を設定した後に、開けなくなる問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-732"><span>A contact card could be prevented from opening after apply formatting to an @ mention</span></span></span></div>


- <div><span data-ttu-id="aff82-733"><span>ユーザーが、Word、Excel、PowerPoint のドキュメントを保存できなくなる場合があるという問題が解決されました。&nbsp;この問題は、[保存] アイコンをクリックしたり Ctrl キーを押しながら S キーを押したりした後に、新しいファイルを作成して &quot;[モデル形式で保存] ダイアログ&quot; を表示するユーザーに影響を与えます。</span></span><span class="sxs-lookup"><span data-stu-id="aff82-733"><span>Resolvedan issue where users may be unable to save Word, Excel, and PowerPoint documents.&nbsp; This issue affects users that create a new file and bring up the &quot;Save as Model Dialog&quot; option after clicking on the Save icon or pressing Ctrl + S.</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="aff82-734">Office スイート</span><span class="sxs-lookup"><span data-stu-id="aff82-734">Office Suite</span></span>

- <div><span data-ttu-id="aff82-735"><span>Windows 7 で図形を使用する場合のパフォーマンスの問題</span></span><span class="sxs-lookup"><span data-stu-id="aff82-735"><span>Performance issue when using Shapes on Windows 7</span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1911-october-18"></a><span data-ttu-id="aff82-737">バージョン 1911: 10 月 18 日</span><span class="sxs-lookup"><span data-stu-id="aff82-737">Version 1911: October 18</span></span>
<span data-ttu-id="aff82-738">*バージョン 1911 (ビルド 12209.20010)*</span><span class="sxs-lookup"><span data-stu-id="aff82-738">*Version 1911 (Build 12209.20010)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="aff82-740">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-740">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="aff82-741">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-741">Outlook</span></span>

- <span data-ttu-id="aff82-742">**アクセシビリティ対応のメールを最も必要としている人に送信する:** Outlook では、メールのヒントが表示され、アクセシビリティ対応のコンテンツを必要とするユーザーに送信するときに、コンテンツがアクセシビリティ対応であることを確認できます</span><span class="sxs-lookup"><span data-stu-id="aff82-742">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-743">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-743">PowerPoint</span></span>

- <span data-ttu-id="aff82-744">**プレゼンテーションの最適化:** アクセシビリティ チェックを使用すると、スクリーン リーダーを考慮に入れて、スライド上のオブジェクトを配置することができます。</span><span class="sxs-lookup"><span data-stu-id="aff82-744">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

### <a name="office-suite"></a><span data-ttu-id="aff82-745">Office スイート</span><span class="sxs-lookup"><span data-stu-id="aff82-745">Office Suite</span></span>

- <span data-ttu-id="aff82-746">**アップロード センターは、Files Needing Attention experience に置き換えられます:** アップロード センターは、[ファイル] > [開く] の Office アプリケーション内に表示される Files Needing Attention experience に置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="aff82-746">**The Upload Center is being replaced by the Files Needing Attention experience:** The Upload Center is being replaced by the Files Needing Attention experience that will show up inside the Office applications under File > Open.</span></span> <span data-ttu-id="aff82-747">この新しいエクスペリエンスは、アップロード センターに比べ、最新かつ総合的で、煩わしくありません。</span><span class="sxs-lookup"><span data-stu-id="aff82-747">This new experience is more modern, integrated, and less intrusive compared to the Upload Center.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="aff82-750">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-750">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="aff82-751">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-751">Excel</span></span>

- <div><span data-ttu-id="aff82-752"><span>自動調整を使用して行の高さを調整するときにチェック ボックスのコントロールが縮小されるという問題を解決しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-752"><span>Resolved an issue where check box controls could shrink when using autofit to adjust row height</span></span></span></div>


- <div><span data-ttu-id="aff82-753"><span>スクロール後にセルを選択すると間違ったセルが選択されるという問題を解決しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-753"><span>Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="aff82-754">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-754">Outlook</span></span>

- <div><span data-ttu-id="aff82-755"><span>メールにデジタル署名付きの添付ファイルがある場合にそのメールに署名するとデジタル署名が破損する可能性があるという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-755"><span>Identified an issue which could cause digital signatures to become broken when signing an e-mail with a digitally signed attachment</span></span></span></div>


- <div><span data-ttu-id="aff82-756"><span>長いファイル名がメッセージ本文へのドラッグ アンド ドロップ後に切り捨てられるという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-756"><span>Identified an issue where long filenames were truncated after draging and droping to the message body</span></span></span></div>


- <div><span data-ttu-id="aff82-757">リボンを自動的に非表示にするよう設定されている場合に検索ボックスが消えるという問題を特定しました</span><span class="sxs-lookup"><span data-stu-id="aff82-757">Identified an issue where the search box could disappear when the ribbon is set to hide automatically</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="aff82-758">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-758">PowerPoint</span></span>

- <div><span data-ttu-id="aff82-759"><span>スライド プレビューの縦横比が適切にロック/ロック解除されていないという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-759"><span>Identified an issuewhere aspect ratio for the slide preview was not being properly locked/unlocked</span></span></span></div>

### <a name="project"></a><span data-ttu-id="aff82-760">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-760">Project</span></span>

- <div><span data-ttu-id="aff82-761">タスクの更新を実行中に入力したノートが保存されない可能性があるという問題を特定しました</span><span class="sxs-lookup"><span data-stu-id="aff82-761">Identified an issue where notes might not persist if entered while doing update tasks</span></span><br></div>


- <div><span data-ttu-id="aff82-762">ファイルがユーザーによってロックされている場合に、ユーザー名がエラー メッセージに表示されない可能性があるという問題を特定しました</span><span class="sxs-lookup"><span data-stu-id="aff82-762">Identified an issue where a file could be locked by a user, but no username would be displayed in the error message</span></span></div>


- <div><span data-ttu-id="aff82-763"><span>読み取り専用のプロジェクトを開いたときに複数のメッセージを取得する可能性があるという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-763"><span>Identified an issue where users could get several messages when opening a read-only project</span></span></span></div>


### <a name="word"></a><span data-ttu-id="aff82-764">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-764">Word</span></span>

- <div><span data-ttu-id="aff82-765"><span>スクリーン リーダーを使用中にコメントを表示するときの問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-765"><span>Identified an issue when viewing comments while using a screen reader</span></span></span></div>


- <div><span data-ttu-id="aff82-766"><span>一部の批評がスペルまたは文法の批評と誤って識別されるという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-766"><span>Identified an issue where some critiques were misidentified as being spelling or grammar critiques</span></span></span></div>


- <div><span data-ttu-id="aff82-767"><span>新しいコメント ダイアログがフォーカスを取得できないことがあるという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-767"><span>Identified an issue where a new comment dialog could sometimes not obtain focus</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="aff82-768">Office スイート</span><span class="sxs-lookup"><span data-stu-id="aff82-768">Office Suite</span></span>

- <div><span data-ttu-id="aff82-769"><span>&quot;[別のインストールが進行中です]&quot; という誤ったエラー メッセージによりアップグレードに失敗することがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-769"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="aff82-770"><span>ローカル リソースからクラウド リソースへの同期に影響する可能性がある問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-770"><span>Identified an issue which could affect syncing from a local resource to a cloud resource</span></span></span></div>

- <div><span data-ttu-id="aff82-771"><span>ウェルカム メッセージに無効なリンクが含まれているという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-771"><span>Identified an issue where a welcome message contained an invalid link</span></span></span></div>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-october-11"></a><span data-ttu-id="aff82-773">バージョン 1910: 10 月 11 日</span><span class="sxs-lookup"><span data-stu-id="aff82-773">Version 1910: October 11</span></span>
<span data-ttu-id="aff82-774">*バージョン 1910 (ビルド 12130.20112)*</span><span class="sxs-lookup"><span data-stu-id="aff82-774">*Version 1910 (Build 12130.20112)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)
[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)
[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="aff82-778">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-778">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="aff82-779">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-779">Excel</span></span>

- <div><span data-ttu-id="aff82-780">OneDrive からオブジェクトとしてファイルを挿入する場合の問題が解決されました</span><span class="sxs-lookup"><span data-stu-id="aff82-780">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="aff82-781">ハイパーリンク形式が一部のコンテンツに適切に適用されない場合がある問題が解決されました</span><span class="sxs-lookup"><span data-stu-id="aff82-781">Resolved an issue where the hyperlink format could not be properly applied to some content</span></span></div>


- <div><span data-ttu-id="aff82-782">数式に構造化された絶対参照が含まれる場合に誤って調整される可能性がある問題が解決されました</span><span class="sxs-lookup"><span data-stu-id="aff82-782">Resolved an issue where formulas containing structured absolute references may be adjusted incorrectly</span></span></div>


- <div><span data-ttu-id="aff82-783">Office 現在のバージョンで開いた場合に Excel の停止を引き起こす可能性がある、Office の以前のバージョンで作成されるブックの問題が解決されました</span><span class="sxs-lookup"><span data-stu-id="aff82-783">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office</span></span></div>


- <div><span data-ttu-id="aff82-784">Excel からコピーされたコンテンツを他の Office アプリケーションに貼り付けると、間違って表示されることがある問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-784">Resolved an issue where content copied from Excel could appear incorrect when pasted into other Office applications</span></span></div>


- <div><span data-ttu-id="aff82-785">グラフ テンプレートを使用してグラフを挿入する場合に、プレビューで正しい色が使用されるよう修正します</span><span class="sxs-lookup"><span data-stu-id="aff82-785">Fix to correct colors used in previews when inserting charts using chart templates</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="aff82-786">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-786">PowerPoint</span></span>

- <div><span data-ttu-id="aff82-787">AirSpace WinComp 下で実行しているときに ARC デバイスの接続が失われる問題を特定しました</span><span class="sxs-lookup"><span data-stu-id="aff82-787">Identified an issue where ARC Devices could lose connection when running under AirSpace WinComp</span></span></div>


### <a name="word"></a><span data-ttu-id="aff82-788">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-788">Word</span></span>

- <div><span data-ttu-id="aff82-789">OneDrive からオブジェクトとしてファイルを挿入する場合の問題が解決されました</span><span class="sxs-lookup"><span data-stu-id="aff82-789">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="aff82-790"><span>メールのスレッドからグラフィカル コンテンツが削除される原因となっていた問題を修正&nbsp;</span>するための回復手順が改善されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-790">Improved our recovery steps to f<span>ix an issue that caused graphical content to get deleted from email threads.&nbsp;</span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-october-04"></a><span data-ttu-id="aff82-792">バージョン 1910: 10 月 4 日</span><span class="sxs-lookup"><span data-stu-id="aff82-792">Version 1910: October 04</span></span>
<span data-ttu-id="aff82-793">*バージョン 1910 (ビルド 12126.20000)*</span><span class="sxs-lookup"><span data-stu-id="aff82-793">*Version 1910 (Build 12126.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="aff82-795">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-795">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="aff82-796">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-796">Excel</span></span>

- <span data-ttu-id="aff82-797">**データ ビジュアライザー アドイン:** Excel から Visio フローチャートをすばやく作成します。</span><span class="sxs-lookup"><span data-stu-id="aff82-797">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="aff82-798">詳細情報</span><span class="sxs-lookup"><span data-stu-id="aff82-798">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="aff82-801">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-801">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="aff82-802">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-802">Excel</span></span>

- <div><span data-ttu-id="aff82-803"><span>印刷プレビューの印刷範囲が正しくない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-803"><span>We fixed an issue where the print area in print preview was not correct</span></span></span></div>


- <div><span data-ttu-id="aff82-804"><span>共同編集セッション中にピボット テーブルが更新されないことがあった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-804"><span>We fixed an issue which could have prevented pivot tables from being refreshed during a co-authoring session</span></span></span></div>


### <a name="access"></a><span data-ttu-id="aff82-805">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-805">Access</span></span>

- <div><span data-ttu-id="aff82-806">共有データベースの使用中に、"&quot;矛盾がある状態&quot;" エラーがユーザーに表示されることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-806">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


### <a name="outlook"></a><span data-ttu-id="aff82-807">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-807">Outlook</span></span>

- <div><span data-ttu-id="aff82-808"><span>メール フォルダーの重複を引き起こすことがあった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-808"><span>We fixed an issue which could have caused duplication of mail folders</span></span></span></div>


- <div><span data-ttu-id="aff82-809"><span>S/MIME で暗号化された電子メールを送信しようとしたときに誤ったエラー メッセージが表示されることがあった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-809"><span>We fixed an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail</span></span></span></div>


- <div><span data-ttu-id="aff82-810"><span>ユーザーが Skype から「不在着信した会話」メッセージを受信したときにクラッシュすることがあった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-810"><span>We fixed an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype</span></span></span></div>


- <div><span data-ttu-id="aff82-811"><span>メモリ リークを引き起こすことがあった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-811"><span>We fixed an issue which could have resulted in a memory leak</span></span></span></div>


- <div><span data-ttu-id="aff82-812"><span>下書きとして保存したときに送信者の名前が変更されることがあった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-812"><span>We fixed an issue which could have caused the senders name to change when saved as a draft</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="aff82-813">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-813">PowerPoint</span></span>

- <div><span></span></div><span data-ttu-id="aff82-814">スライド マスターとスライド レイアウトのヘッダー/フッター/スライド番号プレースホルダーにテキストを貼り付けた後、TextRanges が破損することがあった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-814">We fixed an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout</span></span>


- <div><span></span></div><span data-ttu-id="aff82-815">ハイパーリンク付きのテキストを貼り付けるときにハイパーリンクが作成されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-815">We fixed an issue which prevented hyperlink from being created when pasting text with hyperlink</span></span>


- <div><span data-ttu-id="aff82-816">統計が正常に機能しなくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-816">We fixed an issue which would prevent statistics from working correctly</span></span></div>


### <a name="word"></a><span data-ttu-id="aff82-817">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-817">Word</span></span>

- <div><span data-ttu-id="aff82-818"><span>フォントの色がコミットされない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-818"><span>We fixed an issue where font colors were not being committed</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="aff82-819">Office スイート</span><span class="sxs-lookup"><span data-stu-id="aff82-819">Office Suite</span></span>

- <div><span data-ttu-id="aff82-820">この機能が無効になったときにバージョン履歴が表示されることがあった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-820">We fixed an issue which could offer version history when that feature was disabled</span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-september-27"></a><span data-ttu-id="aff82-822">バージョン 1910: 9 月 27 日</span><span class="sxs-lookup"><span data-stu-id="aff82-822">Version 1910: September 27</span></span>
<span data-ttu-id="aff82-823">*バージョン 1910 (ビルド 12119.20000)*</span><span class="sxs-lookup"><span data-stu-id="aff82-823">*Version 1910 (Build 12119.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)
[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)
[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="aff82-827">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-827">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="aff82-828">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-828">Excel</span></span>

- <div><span data-ttu-id="aff82-829"><span>シリーズ コレクションを変更するときに、散布図が適切にレンダリングされない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-829"><span>We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="aff82-830">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-830">Outlook</span></span>

- <div><span data-ttu-id="aff82-831"><span>共有予定表フォルダーを操作するときに、アクセス許可エラーを報告する可能性があった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-831"><span>We fixed an issue which could have reported permission errors when interacting with shared calendar folders</span></span></span></div>


- <div><span data-ttu-id="aff82-832"><span>ユーザーが予定表に添付ファイルを追加できない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-832"><span>We fixed an issue which could have prevented users from adding attachments to calendars</span></span></span></div>


- <div><span data-ttu-id="aff82-833"><span>デジタル署名されたメッセージに返信するときに、エラー メッセージが表示される問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-833"><span>We fixed an issue which caused error messages to display when replying to a digitally signed message</span></span></span></div>


### <a name="word"></a><span data-ttu-id="aff82-834">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-834">Word</span></span>

- <div><span data-ttu-id="aff82-835"><span>Deskjet プリンターへの印刷時に、スケーリングの問題を引き起こす可能性があった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-835"><span>We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="aff82-836">Office スイート</span><span class="sxs-lookup"><span data-stu-id="aff82-836">Office Suite</span></span>

- <div><span data-ttu-id="aff82-837"><span>中太字のテキストのスタイルが正しく表示されない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-837"><span>We fixed an issue where medium bold text could be incorrectly styled</span></span></span></div>


- <div><span data-ttu-id="aff82-838"><span>アップロードが保留されているファイルを閉じるときに、ユーザーに誤ったエラー メッセージが表示される問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-838"><span>We fixed an issue where a user could be given an incorrect error message when closing a file with a pending upload</span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-september-20"></a><span data-ttu-id="aff82-840">バージョン 1910: 9 月 20 日</span><span class="sxs-lookup"><span data-stu-id="aff82-840">Version 1910: September 20</span></span>
<span data-ttu-id="aff82-841">*バージョン 1910 (ビルド 12112.20000)*</span><span class="sxs-lookup"><span data-stu-id="aff82-841">*Version 1910 (Build 12112.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="aff82-845">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-845">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="aff82-846">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-846">Excel</span></span>

- <div><span data-ttu-id="aff82-847"><span>Excel が起動時にハングすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-847"><span>We fixed an issue where Excel could sometimes hang at launch</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="aff82-848">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-848">Outlook</span></span>

- <div><span data-ttu-id="aff82-849"><span>多数の部屋が利用可能な場合の部屋選択のパフォーマンスが大幅に向上しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-849"><span>We significantly improved the performance of room selection when there are a large number of rooms available</span></span></span></div>


- <div><span data-ttu-id="aff82-850"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Office 365 の最新の認証に移行するときに、Outlook に複数のメールボックスを使用しているユーザーのメールボックスの同期を妨げる可能性がある問題を修正しました。</span></span><span class="sxs-lookup"><span data-stu-id="aff82-850"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can prevent mailbox sync for customers with multiple mailboxes in Outlook when migrating to modern authentication in Office 365.</span></span></span><br></div>


- <div><span data-ttu-id="aff82-851"><span>署名ラベルの一部の文字がドロップダウン メニューに表示されない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-851"><span>We fixed an issue where some characters in signature labels would not display in the dropdown menu</span></span></span></div>


### <a name="project"></a><span data-ttu-id="aff82-852">プロジェクト</span><span class="sxs-lookup"><span data-stu-id="aff82-852">Project</span></span>

- <div><span data-ttu-id="aff82-853"><span>エンタープライズ リソースをローカル リソースに置き換えるとクラッシュする可能性がある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-853"><span>We fixed an issue which could cause a crash when replacing an enterprise resource with a local resource</span></span></span></div>


### <a name="word"></a><span data-ttu-id="aff82-854">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-854">Word</span></span>

- <div><span data-ttu-id="aff82-855"><span>下書き表示で同期スクロールが正常に機能しない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-855"><span>We fixed an issue which could prevent synchronous scrolling from working properly in draft view</span></span></span></div>


- <div><span data-ttu-id="aff82-856">ドキュメントを初めて保存した後、ツール ヒントが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-856">We fixed an issue which could prevent Tool Tips from displaying properly after saving a document for the first time</span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-september-13"></a><span data-ttu-id="aff82-858">バージョン 1910: 9 月 13 日</span><span class="sxs-lookup"><span data-stu-id="aff82-858">Version 1910: September 13</span></span>
<span data-ttu-id="aff82-859">*バージョン 1910 (ビルド 12105.20000)*</span><span class="sxs-lookup"><span data-stu-id="aff82-859">*Version 1910 (Build 12105.20000)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="aff82-861">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-861">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="aff82-862">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-862">Excel</span></span>

- <div><span data-ttu-id="aff82-863"><span>一部の保護されたシートにユーザーがハイパーリンクを貼り付けられない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-863"><span>We fixed an issue which could prevent a user from pasting hyperlinks in some protected sheets</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="aff82-864">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-864">Outlook</span></span>

- <div><span data-ttu-id="aff82-865"><span>コンパクト ビューで UI が動かなくなる問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-865"><span>We fixed an issue where the UI could get stuck in a compact view</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="aff82-866">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-866">PowerPoint</span></span>

- <div><span data-ttu-id="aff82-867"><span>PDFへの印刷時、ユーザーにエラーが発生する問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-867"><span>We fixed an issue where a user could experience an error upon printing to PDF</span></span></span></div>


### <a name="project"></a><span data-ttu-id="aff82-868">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-868">Project</span></span>

- <div><span data-ttu-id="aff82-869"><span>問題を修正しました (<span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">保護された作業が有効になっている場合、サマリー タスクの作業値を変更するとクラッシュする</span></span>)</span><span class="sxs-lookup"><span data-stu-id="aff82-869"><span>We fixed an issue where <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">changes to a work value on a summary task could cause a crash if protected work is enabled</span></span></span></span></div>


- <span data-ttu-id="aff82-870"><font size=2 style="background-color:rgb(255, 255, 255);">エンタープライズ カレンダーとイベントを同期する機能を阻害する可能性がある問題を修正しました</font></span><span class="sxs-lookup"><span data-stu-id="aff82-870"><font size=2 style="background-color:rgb(255, 255, 255);">We fixed an issue which could inhibit the ability to sync events with enterprise calendars</font></span></span>


### <a name="office-suite"></a><span data-ttu-id="aff82-871">Office スイート</span><span class="sxs-lookup"><span data-stu-id="aff82-871">Office Suite</span></span>

- <div><span data-ttu-id="aff82-872"><span>ファイルのローカル バージョンの破棄を促す警告が繰り返し発生する可能性がある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-872"><span>We fixed an issue which could cause a repeated warning to discard local versions of a file</span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-september-06"></a><span data-ttu-id="aff82-874">バージョン 1910: 9 月 6 日</span><span class="sxs-lookup"><span data-stu-id="aff82-874">Version 1910: September 06</span></span>
<span data-ttu-id="aff82-875">*バージョン 1910 (ビルド 12030.20004)*</span><span class="sxs-lookup"><span data-stu-id="aff82-875">*Version 1910 (Build 12030.20004)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="aff82-877">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-877">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="aff82-878">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-878">Excel</span></span>

- <span data-ttu-id="aff82-879">**準備ができたら、描画を開始:** Surface ペンを持てば、描画の準備完了です。</span><span class="sxs-lookup"><span data-stu-id="aff82-879">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="aff82-880">詳細情報</span><span class="sxs-lookup"><span data-stu-id="aff82-880">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="powerpoint"></a><span data-ttu-id="aff82-881">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-881">PowerPoint</span></span>

- <span data-ttu-id="aff82-882">**準備ができたら、描画を開始:** Surface ペンを持てば、描画の準備完了です。</span><span class="sxs-lookup"><span data-stu-id="aff82-882">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="aff82-883">詳細情報</span><span class="sxs-lookup"><span data-stu-id="aff82-883">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a><span data-ttu-id="aff82-884">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-884">Word</span></span>

- <span data-ttu-id="aff82-885">**準備ができたら、描画を開始:** Surface ペンを持てば、描画の準備完了です。</span><span class="sxs-lookup"><span data-stu-id="aff82-885">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="aff82-886">詳細情報</span><span class="sxs-lookup"><span data-stu-id="aff82-886">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="aff82-889">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-889">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="aff82-890">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-890">Excel</span></span>

- <div><span data-ttu-id="aff82-891"><span> リボンのフォント名が使用されているフォントと異なることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-891"><span>We fixed an issue which could cause the font name in the ribbon to be different from the font being used</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="aff82-892">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-892">Outlook</span></span>

- <div><span data-ttu-id="aff82-893"><span> Internet Explorer で制限付きサイトの保護モードが無効になると、Outlook により不適切なリソースの使用量になることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-893"><span>We fixed an issue that could result in inappropriate resource consumption by Outlook when Protected Mode is disabled for Restricted Sites in Internet Explorer</span></span></span></div>


- <div><span data-ttu-id="aff82-894"><span>時々、ANSI ソースのテキスト貼り付けるときに Unicode 文字が表示されることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-894"><span>We fixed an issue which could sometimes cause Unicode characters to appear when pasting text from an ANSI source</span></span></span></div>


- <div><span data-ttu-id="aff82-895"><span>グループ スケジュール ビューで一部のユーザーがオフラインとして間違って表示される問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-895"><span>We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span></span></div>


### <a name="word"></a><span data-ttu-id="aff82-896">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-896">Word</span></span>

- <div><span data-ttu-id="aff82-897"><span>テーブルの書式設定が失われることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-897"><span>We fixed an issue where table formatting could be lost</span></span></span></div>


- <div><span data-ttu-id="aff82-898"><span>Ctrl + V ショートカット キーが効かなくなることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-898"><span>We fixed an issue which could break the ctrl+v keyboard shortcut</span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1909-august-30"></a><span data-ttu-id="aff82-900">バージョン 1909: 8 月 30 日</span><span class="sxs-lookup"><span data-stu-id="aff82-900">Version 1909: August 30</span></span>
<span data-ttu-id="aff82-901">*バージョン 1909 (ビルド 12026.20000)*</span><span class="sxs-lookup"><span data-stu-id="aff82-901">*Version 1909 (Build 12026.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="aff82-903">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-903">Feature updates</span></span>

### <a name="access"></a><span data-ttu-id="aff82-904">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-904">Access</span></span>

- <span data-ttu-id="aff82-905">**リンク テーブルの高速検索:** 新しい検索ボックスにより、リンク テーブルを簡単に見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="aff82-905">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-906">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-906">PowerPoint</span></span>

- <span data-ttu-id="aff82-907">**図を SVG として保存する:** グラフ、図形、その他の図を、サイズ変更しても画質が低下しないスケーラブル ベクター グラフィックとして保存できます。</span><span class="sxs-lookup"><span data-stu-id="aff82-907">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="aff82-908">詳細情報</span><span class="sxs-lookup"><span data-stu-id="aff82-908">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="aff82-911">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="aff82-911">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="aff82-912">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-912">Excel</span></span>

- <div><span data-ttu-id="aff82-913"><span>&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">秘密度</span>のキー ヒントが&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">別のキー ヒントと競合している問題が修正されました。</span></span></span><span class="sxs-lookup"><span data-stu-id="aff82-913"><span>We fixed an issue where the keytip for&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">Sensitivity </span>was&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">conflicting with another keytip.</span></span></span></span></div>

- <div><span data-ttu-id="aff82-914"><span>共有ブックでの作業中に保存を行おうとする際に発生する問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="aff82-914"><span>We fixed an issue that occurred while working on a shared workbook when trying to save.</span></span></span></div>

- <div><span data-ttu-id="aff82-915"><span>Excel で、レジストリ値 "\Excel\Add-in Manager" にあるアドインのうち、最初の 16 個しか表示されない問題が修正されました。<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span><span class="sxs-lookup"><span data-stu-id="aff82-915"><span>We fixed an issue where Excel only lists the first 16 addins located in the '\Excel\Add-in Manager' registry values.<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span></span></div>


- <div><span data-ttu-id="aff82-916"><span>関数 Frequency() が誤った結果を返す問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="aff82-916"><span>We fixed an issue where the function Frequency() returns incorrect results.</span></span></span></div>


- <div><span data-ttu-id="aff82-917"><span>色によるフィルター処理のパフォーマンスが大幅に改善されました。</span></span><span class="sxs-lookup"><span data-stu-id="aff82-917"><span>We have significantly improved the performance of filtering by color.</span></span></span></div>


- <div><span data-ttu-id="aff82-918"><span>Surface のユーザーがマウスを動かすと、それがマウス クリックのイベントとして解釈されることがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="aff82-918"><span>We fixed an issue for Surface users where moving the mouse could be interpreted as a mouse click event.</span></span></span></div>


- <div><span data-ttu-id="aff82-919"><span>[検索と置換] ダイアログでキーボードによるナビゲーションを行えない問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-919"><span>We fixed an issue which prevented keyboard navigation in the Find/Replace dialog</span></span></span></div>


- <div><span data-ttu-id="aff82-920"><span>一部のフォント名が正しく表示されない問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-920"><span>We fixed an issue where the name of some fonts were not displayed correctly</span></span></span></div>


- <div><span data-ttu-id="aff82-921"><span>サポートされているファイル形式として CSV が表示されない問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-921"><span>We fixed an issue which prevented CSV from appearing as a supported file type</span></span></span></div>


### <a name="access"></a><span data-ttu-id="aff82-922">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-922">Access</span></span>

- <div><span data-ttu-id="aff82-923">共有データベースの使用中に、"&quot;矛盾がある状態&quot;" エラーがユーザーに表示されることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-923">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


- <div><span data-ttu-id="aff82-924"><span>日付選択カレンダーが表示されるべきではないときに表示されてしまうことがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="aff82-924"><span>We fixed an issue which could cause the date picker to appear when it shouldn't</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="aff82-925">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-925">Outlook</span></span>

- <div><span data-ttu-id="aff82-926"><span>一部の POP3 ユーザーに HTML コンテンツが表示されない問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-926"><span>We fixed an issue which prevented HTML content from appearing for some POP3 users</span></span></span></div>


- <div><span data-ttu-id="aff82-927"><span>Planner を利用できない環境で、連絡先カードのオーバーフロー メニューから機能しない [Planner] リンクを削除するための修正を行いました。</span></span><span class="sxs-lookup"><span data-stu-id="aff82-927"><span>We fixed an issue to remove non-functional 'Planner' link from the overflow menu in the contact card when working in environments where it is not available.</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="aff82-928">OneNote</span><span class="sxs-lookup"><span data-stu-id="aff82-928">OneNote</span></span>

- <div><span data-ttu-id="aff82-929"><span>フォーカスが &nbsp;OneNote のバックグラウンド同期に移動してしまうことがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="aff82-929"><span>We fixed an issue where&nbsp;OneNote background sync was sometimes stealing focus.</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="aff82-930">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-930">PowerPoint</span></span>

- <div><span data-ttu-id="aff82-931"><span>3-D Turntable の回転の向きに影響を与えていた問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="aff82-931"><span>We fixed an issue which would affect the rotation orientation of a 3D Turntable.</span></span></span></div>

- <div><span data-ttu-id="aff82-932"><span>ハイパーリンクに特殊文字が含まれている場合に一部のハイパーリンクが機能しない問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="aff82-932"><span>We fixed an issue which prevented some hyperlinks from working if they contained special characters.</span></span></span></div>

- <div><span data-ttu-id="aff82-933"><span>同時に複数のコメント ウィンドウが開かれる問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="aff82-933"><span>We fixed an issue which caused multiple comment panes to open at the same time.</span></span></span></div>

### <a name="project"></a><span data-ttu-id="aff82-934">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-934">Project</span></span>

- <div><span data-ttu-id="aff82-935"><span>チーム プランナー ビューを印刷した後にクラッシュすることがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="aff82-935"><span>We fixed an issue which could sometimes cause a crash after printing a Team Planner view.</span></span></span></div>

### <a name="word"></a><span data-ttu-id="aff82-936">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-936">Word</span></span>

- <div><span data-ttu-id="aff82-937">閲覧表示で、縦書きテキスト ボックス内の複数バイト文字が重なって表示される問題が<span>修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-937">We f<span>ixed an issue where multi-byte characters in vertical text box are shown overlapped in reading view.</span></span><br></span></div>

- <div><span data-ttu-id="aff82-938"><span>&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">ユーザーがアドイン ウィザードでアクションを実行する際に、日本語のはがきとグリーティング カードに関連するアドインのリソースが見つからない問題が修正されました。</span></span></span><span class="sxs-lookup"><span data-stu-id="aff82-938"><span>We&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">fixed an issue where Japanese post card and greeting card related addin resources are not found when the user takes action in the addin wizard.</span></span></span></span></div>

- <div><span data-ttu-id="aff82-939"><span>保護ビューで表示中に、タイトル バーのユーザー インターフェイスで問題を発生させることがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="aff82-939"><span>We fixed an issue which could cause issues with the Title Bar User Interface when in Protected View</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="aff82-940">Office スイート</span><span class="sxs-lookup"><span data-stu-id="aff82-940">Office Suite</span></span>

- <div><span data-ttu-id="aff82-941"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">標準の図形とコネクタ図形の両方が含まれる選択部分に対して [図形の変更] を適用するとファイルが破損する問題が修正されました。</span></span></span><span class="sxs-lookup"><span data-stu-id="aff82-941"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> We fixed a corrupt file issue when you Change Shape on a selection that contains both a normal shape and a connector shape.</span></span></span></span></div>

- <div><span data-ttu-id="aff82-942"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">複数の外付けモニターからドッキングとドッキングの解除を使用すると、アプリケーションに問題が発生する</span>問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="aff82-942"><span>We fixed an issue that <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">caused a problem in applications when using dock/undock from multiple external displays. </span></span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="august-23-2019br"></a><span data-ttu-id="aff82-944">**2019 年 8 月 23 日**</span><span class="sxs-lookup"><span data-stu-id="aff82-944">**August 23, 2019**</span></span><br/>
<span data-ttu-id="aff82-945">バージョン 1909 (ビルド 12015.20004)</span><span class="sxs-lookup"><span data-stu-id="aff82-945">Version 1909 (Build 12015.20004)</span></span><br/>



## <a name="non-security-updates"></a><span data-ttu-id="aff82-946">セキュリティ以外の更新プログラム:</span><span class="sxs-lookup"><span data-stu-id="aff82-946">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-947">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-947">Excel</span></span>

- <div><span data-ttu-id="aff82-948"><span>結合されたセルで列を削除するパフォーマンスが大幅に改善されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-948"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="aff82-949">Office スイート</span><span class="sxs-lookup"><span data-stu-id="aff82-949">Office Suite</span></span>

- <div><span data-ttu-id="aff82-950"><span>一部の Unicode 文字がブラウザー上で表示されない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-950"><span>We fixed an issue which could prevent some Unicode characters from being displayed when viewed in a browser</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="aff82-951">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-951">Outlook</span></span>

- <div><span data-ttu-id="aff82-952"><span>WebDAV の場所にファイルを保存できないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-952"><span>We fixed an issue which could have prevented files from being saved to a WebDAV location</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="aff82-953">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-953">PowerPoint</span></span>

- <div><span data-ttu-id="aff82-954"><span>ユーザーがあるコメントをクリックすると別のコメントが選択される問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-954"><span>We fixed an issue where a user would click on one comment, but another comment would be selected</span></span></span></div>





## <a name="august-16-2019br"></a><span data-ttu-id="aff82-955">**2019 年 8 月 16 日**</span><span class="sxs-lookup"><span data-stu-id="aff82-955">**August 16, 2019**</span></span><br/>
<span data-ttu-id="aff82-956">バージョン 1909 (ビルド 12013.20000)</span><span class="sxs-lookup"><span data-stu-id="aff82-956">Version 1909 (Build 12013.20000)</span></span><br/>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="aff82-957">PowerPoint 機能の更新:</span><span class="sxs-lookup"><span data-stu-id="aff82-957">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="aff82-958">**配布資料にスライド番号を印刷する:** スライド番号は配布資料に自動的に含まれます。</span><span class="sxs-lookup"><span data-stu-id="aff82-958">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="aff82-959">それらをオンのままにするか、オフにするか、選択します。</span><span class="sxs-lookup"><span data-stu-id="aff82-959">Leave them on, turn them off, it's all up to you.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="aff82-960">セキュリティ以外の更新プログラム:</span><span class="sxs-lookup"><span data-stu-id="aff82-960">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-961">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-961">Excel</span></span>

- <div><span data-ttu-id="aff82-962"><span>自動保存が有効になることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-962"><span>We fixed an issue which could cause AutoSave to become enabled</span></span></span></div>


- <div><span data-ttu-id="aff82-963">セルの高さが不正確に測定されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-963">We fixed an issue which could result in cell heights being measured inaccurately</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="aff82-964">Office スイート</span><span class="sxs-lookup"><span data-stu-id="aff82-964">Office Suite</span></span>

- <div><span data-ttu-id="aff82-965"><span>コメント機能のパフォーマンスを大幅に改善する問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-965"><span>We fixed an issue which significantly improves the performance of the Comments feature</span></span></span></div>


- <div><span data-ttu-id="aff82-966"><span>検索中に方向キーを使用するとクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-966"><span>We fixed an issue which could cause a crash when using arrow keys while in search</span></span></span></div>


- <div><span data-ttu-id="aff82-967"><span>@ 記号が特定の文字の後に配置された場合に @メンションを使用できないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-967"><span>We fixed an issue which could prevent an @ mention if the @ symbol was placed after certain characters</span></span></span></div>


- <div><span data-ttu-id="aff82-968"><span>@メンションを削除するとクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-968"><span>We fixed an issue which could sometimes cause a crash when deleting @ mentions</span></span></span></div>


- <div><span data-ttu-id="aff82-969"><span>コメント カードに絵文字が正しく表示されない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-969"><span>We fixed an issue which prevented emojis from displaying correctly in comment cards</span></span></span></div>


- <div><span data-ttu-id="aff82-970"><span>アクティブ​​ クリップボード​​でクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-970"><span>We fixed an issue with Active Clipboard which could sometimes result in a crash</span></span></span></div>


- <div><span data-ttu-id="aff82-971"><span>クイック アクセス ツール バーのボタンが機能しなくなることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-971"><span>We fixed an issue which could cause the Quick Access Toolbar buttons to stop working</span></span></span></div>


- <div><span data-ttu-id="aff82-972"><span>文書の書式設定プレビュー​​がバックグラウンドに切り替わらないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-972"><span>We fixed an issue which could prevent the Document Formatting Preview from switching to the background</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="aff82-973">OneNote</span><span class="sxs-lookup"><span data-stu-id="aff82-973">OneNote</span></span>

- <span data-ttu-id="aff82-974">Office テーマが黒に設定されている場合、セクションのドロップダウン リストにセクションの名前が空白で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-974">We fixed an issue where the names of sections appear blank in the section dropdown list when Office Theme is set to Black.</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-975">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-975">Outlook</span></span>

- <div><span data-ttu-id="aff82-976"><span>Outlook が繰り返しフォーカスを取得して失うことがある送信イベントに関する問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-976"><span>We fixed an issue with Send Events which could cause Outlook to repeatedly gain and lose focus</span></span></span></div>


- <div><span data-ttu-id="aff82-977"><span>[フォルダーに返信を投稿] ショートカットが機能しない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-977"><span>We fixed an issue which prevented the Post Reply to Folder shortcut from working</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="aff82-978">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-978">PowerPoint</span></span>

- <div><span data-ttu-id="aff82-979"><span>共同作業の際に問題を引き起こすことがある保護ビューの問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-979"><span>We fixed an issue with Protected View which could sometimes cause problems when collaborating</span></span></span></div>


- <div><span data-ttu-id="aff82-980"><span>コメント ウィンドウのタスクが適切に表示されないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-980"><span>We fixed an issue which could prevent tasks in comment panes from displaying properly</span></span></span></div>


- <div><span data-ttu-id="aff82-981"><span>新しいスライドを挿入するときにクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-981"><span>We fixed an issue which could cause a crash when inserting new slides</span></span></span></div>


### <a name="user-lifecycle"></a><span data-ttu-id="aff82-982">ユーザーのライフサイクル</span><span class="sxs-lookup"><span data-stu-id="aff82-982">User Lifecycle</span></span>

- <div><span data-ttu-id="aff82-983"><span>サブスクリプション機能が消えることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-983"><span>We fixed an issue which could sometimes result in subscription features disappearing</span></span></span></div>


### <a name="word"></a><span data-ttu-id="aff82-984">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-984">Word</span></span>

- <div><span data-ttu-id="aff82-985"><span>ハイパーリンクに特定の文字が含まれている場合、ハイパーリンクが壊れることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-985"><span>We fixed an issue where hyperlinks could be broken if the hyperlink contained certain characters</span></span></span></div>


- <div><span data-ttu-id="aff82-986"><span>画像のコメントを表示するときに画像のサイズが不適切になることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-986"><span>We fixed an issue where images could be improperly sized when viewing a comment for that image</span></span></span></div>


- <div><span data-ttu-id="aff82-987"><span>箇条書きのドロップダウン メニューでクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-987"><span>We fixed an issue with the Bullet List drop down menu which could sometimes result in a crash</span></span></span></div>





## <a name="august-09-2019br"></a><span data-ttu-id="aff82-988">**2019 年 8 月 9 日**</span><span class="sxs-lookup"><span data-stu-id="aff82-988">**August 09, 2019**</span></span><br/>
<span data-ttu-id="aff82-989">バージョン 1909 (ビルド 12001.20000)</span><span class="sxs-lookup"><span data-stu-id="aff82-989">Version 1909 (Build 12001.20000)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="aff82-990">Excel 機能の更新</span><span class="sxs-lookup"><span data-stu-id="aff82-990">Excel Feature updates:</span></span>

- <span data-ttu-id="aff82-991">**共同作業がさらに簡単に:** 共同編集の改善とは、条件付き書式、セルのスタイルなどを使用して作業しているときに、ユーザーによる変更がシームレスに共同作業者のそれらと統合されるということを意味します。</span><span class="sxs-lookup"><span data-stu-id="aff82-991">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>


- <span data-ttu-id="aff82-992">**検索して楽しむ:** 目的のアイコンを簡単に検索できるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-992">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="aff82-993">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="aff82-993">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="office-suite-feature-updates"></a><span data-ttu-id="aff82-994">Office スイートの機能の更新</span><span class="sxs-lookup"><span data-stu-id="aff82-994">Office Suite Feature updates:</span></span>

- <span data-ttu-id="aff82-995">**新しい Office アプリのアイコン:** シンプルかつ高性能で、インテリジェントな Office のエクスペリエンスを反映するように、アプリのアイコンがリニューアルされました。</span><span class="sxs-lookup"><span data-stu-id="aff82-995">**New Office app icons:** Redesigned app icons to reflect the simple, powerful, and intelligent experiences of Office</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="aff82-996">Outlook 機能の更新</span><span class="sxs-lookup"><span data-stu-id="aff82-996">Outlook Feature updates:</span></span>

- <span data-ttu-id="aff82-997">**攻撃に対する高度な保護:** Office 365 Advanced Threat Protection を用いると、メールの件名、添付メッセージ、署名されたメッセージ、ネットワーク パスなどの範囲内のハイパーリンクを利用した攻撃から保護されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-997">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>


- <span data-ttu-id="aff82-998">**検索して楽しむ:** 目的のアイコンを簡単に検索できるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-998">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="aff82-999">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="aff82-999">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="aff82-1000">PowerPoint 機能の更新</span><span class="sxs-lookup"><span data-stu-id="aff82-1000">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="aff82-1001">**検索して楽しむ:** 目的のアイコンを簡単に検索できるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1001">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="aff82-1002">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="aff82-1002">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="aff82-1003">Word 機能の更新</span><span class="sxs-lookup"><span data-stu-id="aff82-1003">Word Feature updates:</span></span>

- <span data-ttu-id="aff82-1004">**他のユーザーがすばやく変更を確認する:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1004">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


- <span data-ttu-id="aff82-1005">**検索して楽しむ:** 目的のアイコンを簡単に検索できるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1005">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="aff82-1006">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="aff82-1006">And when you're selecting, the Insert button tells you how many you've picked.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="aff82-1007">セキュリティ以外の更新プログラム:</span><span class="sxs-lookup"><span data-stu-id="aff82-1007">Non-security updates:</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1008">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1008">Outlook</span></span>

- <div><span data-ttu-id="aff82-1009"><span>会議がキャンセルされた後に、会議の受信者が 2 つの通知を受け取る原因となっていた問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-1009"><span>We fixed an issue which caused meeting recipients to receive two notifications after a meeting was cancelled</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="aff82-1010">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1010">PowerPoint</span></span>

- <div><span data-ttu-id="aff82-1011"><span>図形とアイコンの [線なし]、[塗りつぶしなし] をユーザーが選択したときに、クラッシュを引き起こす問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-1011"><span>We fixed an issue which could cause a crash when the user selected No Outline or No Fill for Shapes and Icons</span></span></span></div>





## <a name="august-02-2019br"></a><span data-ttu-id="aff82-1012">**2019 年 8 月 2 日**</span><span class="sxs-lookup"><span data-stu-id="aff82-1012">**August 02, 2019**</span></span><br/>
<span data-ttu-id="aff82-1013">バージョン 1908 (ビルド 11929.20002)</span><span class="sxs-lookup"><span data-stu-id="aff82-1013">Version 1908 (Build 11929.20002)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="aff82-1014">Excel 機能の更新</span><span class="sxs-lookup"><span data-stu-id="aff82-1014">Excel Feature updates:</span></span>

- <span data-ttu-id="aff82-1015">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="aff82-1015">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="aff82-1016">**ドキュメントに機密ラベルを適用する:** ファイルとメールに機密ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="aff82-1016">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="aff82-1017">Outlook 機能の更新</span><span class="sxs-lookup"><span data-stu-id="aff82-1017">Outlook Feature updates:</span></span>

- <span data-ttu-id="aff82-1018">**ドキュメントに機密ラベルを適用する:** ファイルとメールに機密ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="aff82-1018">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="aff82-1019">PowerPoint 機能の更新</span><span class="sxs-lookup"><span data-stu-id="aff82-1019">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="aff82-1020">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="aff82-1020">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="aff82-1021">**ドキュメントに機密ラベルを適用する:** ファイルとメールに機密ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="aff82-1021">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="aff82-1022">Word 機能の更新</span><span class="sxs-lookup"><span data-stu-id="aff82-1022">Word Feature updates:</span></span>

- <span data-ttu-id="aff82-1023">**ファイルを変換してアクセシビリティを向上させる:** ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="aff82-1023">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="aff82-1024">**別の言葉で伝える:** 別の言葉で伝えたいときに、[書き換え] でお助けします。</span><span class="sxs-lookup"><span data-stu-id="aff82-1024">**Say it another way:** When you want to say it differently, Rewrite is there to help.</span></span> <span data-ttu-id="aff82-1025">[書き換え] では、フレーズを洗練させるための別の言葉遣いを提供します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1025">Rewrite offers alternatives for finessing your phrases.</span></span>


- <span data-ttu-id="aff82-1026">**ドキュメントに機密ラベルを適用する:** ファイルとメールに機密ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="aff82-1026">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="aff82-1027">セキュリティ以外の更新プログラム:</span><span class="sxs-lookup"><span data-stu-id="aff82-1027">Non-security updates:</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1028">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1028">Access</span></span>
- <span data-ttu-id="aff82-1029">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1029">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1030">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1030">Excel</span></span>

- <div><span data-ttu-id="aff82-1031"><span>PDF に印刷するときに [&quot;すべてのラベルを繰り返す&quot;] が適用されているかのように表示されていた問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-1031"><span>We fixed an issue which made it appear as though &quot;repeat all labels&quot; was applied when printing to a PDF</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="aff82-1032">Office スイート</span><span class="sxs-lookup"><span data-stu-id="aff82-1032">Office Suite</span></span>

- <div><span data-ttu-id="aff82-1033"><span>デスクトップからドキュメントを開けないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-1033"><span>We fixed an issue which could have prevented users from opening a document from the desktop</span></span></span></div>

- <div><span data-ttu-id="aff82-1034"><span>[&quot;別のインストールが進行中です&quot;] という誤ったエラー メッセージによりアップグレードに失敗することがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-1034"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="aff82-1035"><span>セキュリティ更新プログラムがインストールされるときに、エラー メッセージが表示されることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-1035"><span>We fixed an issue where a user could see error messages when security updates are installed</span></span></span></div>

- <div><span data-ttu-id="aff82-1036"><span>カーソルが消えることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-1036"><span>We fixed an issue which could cause the cursor to disappear</span></span></span></div>

- <div><span data-ttu-id="aff82-1037"><span>既定で [ホーム] タブではなく [描画] タブが設定されていることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-1037"><span>We fixed an issue where a user could be defaulted to the draw tab instead of the home tab</span></span></span></div>

- <div><span data-ttu-id="aff82-1038"><span>大きなツリー ビューがクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-1038"><span>We fixed an issue where large tree views could result in a crash</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="aff82-1039">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1039">Outlook</span></span>

- <div></div><span data-ttu-id="aff82-1040"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">パスワード入力画面が繰り返し表示されることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-1040"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can cause repeated password prompts</span></span></span>

- <div><span data-ttu-id="aff82-1041"><span>メール アドレスが正しくクエリされないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-1041"><span>We fixed an issue which could prevent an email address from being queried correctly</span></span></span></div>

- <div><span data-ttu-id="aff82-1042"><span>以前のバージョンの Outlook で作成した予定表アイテムを開けないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-1042"><span>We fixed an issue which could prevent users from opening calendar items created by legacy versions of Outlook</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1043">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1043">PowerPoint</span></span>

- <div><span data-ttu-id="aff82-1044"><span>一部のアニメーションが開始されないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-1044"><span>We fixed an issue which could prevent some animations from starting</span></span></span></div>

### <a name="project"></a><span data-ttu-id="aff82-1045">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1045">Project</span></span>
- <span data-ttu-id="aff82-1046">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1046">Various performance and stability fixes</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1047">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1047">Word</span></span>

- <div><span data-ttu-id="aff82-1048"><span>コメントへの返信が順番に表示されないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-1048"><span>We fixed an issue where replies to comments could appear out of order</span></span></span></div>

- <div><span data-ttu-id="aff82-1049"><span>状況によって、コメントの代わりにヒントが表示されることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-1049"><span>We fixed an issue where in some situations, hints would be displayed instead of comments</span></span></span></div>

- <div><span data-ttu-id="aff82-1050"><span>新しいコメントを追加しようとしたときに [変更履歴] ウィンドウが表示されることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-1050"><span>We fixed an issue where the Revisions Pane could display when the user tried to add a new comment</span></span></span></div>

- <div><span data-ttu-id="aff82-1051"><span>[元に戻す] ドロップダウン リストが表示されないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-1051"><span>We fixed an issue which could prevent the undo dropdown list from appearing</span></span></span></div>

- <div><span data-ttu-id="aff82-1052"><span>コメントを追加できないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="aff82-1052"><span>We fixed an issue which could prevent comments from being added</span></span></span></div>


## <a name="july-26-2019"></a><span data-ttu-id="aff82-1053">2019 年 7 月 26 日</span><span class="sxs-lookup"><span data-stu-id="aff82-1053">July 26, 2019</span></span>
<span data-ttu-id="aff82-1054">バージョン 1908 (ビルド 11916.20000)</span><span class="sxs-lookup"><span data-stu-id="aff82-1054">Version 1908 (build 11916.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="aff82-1055">新機能:</span><span class="sxs-lookup"><span data-stu-id="aff82-1055">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="aff82-1056">Word、Excel、PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1056">Word, Excel, PowerPoint</span></span>

#### <a name="create-more-accessible-pdfs"></a><span data-ttu-id="aff82-1057">よりアクセシビリティの高い PDF ファイルを作成する</span><span class="sxs-lookup"><span data-stu-id="aff82-1057">Create more accessible PDFs</span></span>

<span data-ttu-id="aff82-1058">PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1058">Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="aff82-1059">主な修正:</span><span class="sxs-lookup"><span data-stu-id="aff82-1059">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="aff82-1060">すべて</span><span class="sxs-lookup"><span data-stu-id="aff82-1060">All</span></span>

- <span data-ttu-id="aff82-1061">Office の更新後に、Office のファイルの種類の関連付けとアイコンが破損する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1061">We fixed an issue where file type association and icons for Office could sometimes break after an Office Update</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1062">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1062">Word</span></span> 
- <span data-ttu-id="aff82-1063">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1063">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1064">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1064">Excel</span></span>
- <span data-ttu-id="aff82-1065">グラフを移動するとクラッシュする場合がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1065">We fixed an issue where moving a chart could sometimes result in a crash</span></span>
- <span data-ttu-id="aff82-1066">グラフの種類を変更した後にグラフ オブジェクトからブック オブジェクトを取得するとエラーが発生することがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1066">We fixed an issue where to get Workbook object from Chart object after changing chart types could sometimes result in an error</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1067">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1067">PowerPoint</span></span>
- <span data-ttu-id="aff82-1068">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1068">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1069">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1069">Outlook</span></span>
- <span data-ttu-id="aff82-1070">シンプル リボンで、無効にしてあるコントロールが淡色表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1070">We fixed an issue where in simplified ribbon, a disabled control could sometimes not be greyed out in the ribbon</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1071">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1071">Access</span></span>
- <span data-ttu-id="aff82-1072">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1072">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="aff82-1073">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1073">Project</span></span>
- <span data-ttu-id="aff82-1074">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1074">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-19-2019"></a><span data-ttu-id="aff82-1075">2019 年 7 月 19 日</span><span class="sxs-lookup"><span data-stu-id="aff82-1075">July 19, 2019</span></span>
<span data-ttu-id="aff82-1076">バージョン 1908 (ビルド 11911.20000)</span><span class="sxs-lookup"><span data-stu-id="aff82-1076">Version 1908 (build 11911.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="aff82-1077">新機能:</span><span class="sxs-lookup"><span data-stu-id="aff82-1077">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1078">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1078">Word</span></span>

#### <a name="learn-what-acronyms-mean-when-you-read-in-word-online"></a><span data-ttu-id="aff82-1079">Word Online の文書で使われている略語の意味を確認する</span><span class="sxs-lookup"><span data-stu-id="aff82-1079">Learn what Acronyms mean when you read in Word Online</span></span>

<span data-ttu-id="aff82-1080">略語を見つけたら、組織内のデータを使用してそれを定義しようとします。</span><span class="sxs-lookup"><span data-stu-id="aff82-1080">When you encounter an Acronym, we'll try to define it using data from within your organization.</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="aff82-1081">主な修正:</span><span class="sxs-lookup"><span data-stu-id="aff82-1081">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1082">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1082">Word</span></span> 
- <span data-ttu-id="aff82-1083">BookMarkEnd タグが欠けているという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1083">We fixed an issue which BookMarkEnd tag was missing.</span></span>
- <span data-ttu-id="aff82-1084">ユーザーが特殊文字を入力しているときに、フォントの選択が変更される場合があるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1084">We fixed an issue where the font selection could change while the user was typing special characters</span></span>
- <span data-ttu-id="aff82-1085">新しいコメント カードに空白の返信が発生することがあるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1085">We fixed an issue which could sometimes cause blank replies to a new comment card</span></span>
- <span data-ttu-id="aff82-1086">メールを共有すると、書式設定が失われる場合があるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1086">We fixed an issue which could cause formatting to be lost when sharing an email</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1087">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1087">Excel</span></span>
- <span data-ttu-id="aff82-1088">範囲の広い配列がクラッシュすることがあるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1088">We fixed an issue where an array with a large range could sometimes cause a crash</span></span>
- <span data-ttu-id="aff82-1089">フィルター処理された範囲からデータをコピーする場合のパフォーマンスを大幅に向上しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1089">We significantly improved the performance of copying data from filtered ranges</span></span>
- <span data-ttu-id="aff82-1090">ファイル名に特殊文字が含まれていると、一部のファイルを開くことができないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1090">We fixed an issue which prevented some files from opening if the filenames contained special characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1091">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1091">PowerPoint</span></span>
- <span data-ttu-id="aff82-1092">PowerPoint で新しく作成したセクションのセクション名が既定で選択されていないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1092">We fixed an issue where section name was not selected by default for newly created section in PowerPoint.</span></span>
- <span data-ttu-id="aff82-1093">4:3 ディスプレイを使用すると、UI の使用が困難になることがあるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1093">We fixed an issue which could cause the UI to become difficult to use when using a 4:3 display</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1094">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1094">Outlook</span></span>
- <span data-ttu-id="aff82-1095">利用可能な会議室がリストに表示されないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1095">We fixed an issue which could prevent available rooms from being listed</span></span>
- <span data-ttu-id="aff82-1096">一部の POP3 ユーザーの HTML 形式を設定できないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1096">We fixed an issue which prevented HTML formatting for some POP3 users</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1097">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1097">Access</span></span>
- <span data-ttu-id="aff82-1098">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1098">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="aff82-1099">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1099">Project</span></span>
- <span data-ttu-id="aff82-1100">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1100">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-12-2019"></a><span data-ttu-id="aff82-1101">2019 年 7 月 12 日</span><span class="sxs-lookup"><span data-stu-id="aff82-1101">July 12, 2019</span></span>
<span data-ttu-id="aff82-1102">バージョン 1907 (ビルド 11901.20038)</span><span class="sxs-lookup"><span data-stu-id="aff82-1102">Version 1907 (build 11901.20038)</span></span>

## <a name="whats-new"></a><span data-ttu-id="aff82-1103">新機能:</span><span class="sxs-lookup"><span data-stu-id="aff82-1103">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1104">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1104">PowerPoint</span></span>
 
#### <a name="use-ink-replay-in-your-presentations"></a><span data-ttu-id="aff82-1105">プレゼンテーションでインクの再生を使用する</span><span class="sxs-lookup"><span data-stu-id="aff82-1105">Use ink replay in your presentations</span></span>
 
<span data-ttu-id="aff82-1106">PowerPoint でインクの再生アニメーションを適用して、プレゼンテーションの表現力とコミュニケーション力を高めます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1106">Apply a replay animation for ink in PowerPoint to express and communicate more in presentations.</span></span> 

## <a name="notable-fixes"></a><span data-ttu-id="aff82-1107">主な修正:</span><span class="sxs-lookup"><span data-stu-id="aff82-1107">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1108">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1108">Word</span></span> 
- <span data-ttu-id="aff82-1109">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1109">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1110">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1110">Excel</span></span>
- <span data-ttu-id="aff82-1111">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1111">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1112">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1112">PowerPoint</span></span>
- <span data-ttu-id="aff82-1113">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1113">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1114">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1114">Outlook</span></span>
- <span data-ttu-id="aff82-1115">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1115">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1116">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1116">Access</span></span>
- <span data-ttu-id="aff82-1117">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1117">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="aff82-1118">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1118">Project</span></span>
- <span data-ttu-id="aff82-1119">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1119">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-5-2019"></a><span data-ttu-id="aff82-1120">2019 年 7 月 5 日</span><span class="sxs-lookup"><span data-stu-id="aff82-1120">July 5, 2019</span></span>
<span data-ttu-id="aff82-1121">バージョン 1907 (ビルド 11901.20018)</span><span class="sxs-lookup"><span data-stu-id="aff82-1121">Version 1907 (build 11901.20018)</span></span>

## <a name="whats-new"></a><span data-ttu-id="aff82-1122">新機能:</span><span class="sxs-lookup"><span data-stu-id="aff82-1122">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="aff82-1123">Word、Excel、PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1123">Word, Excel, PowerPoint</span></span>

#### <a name="sketchy-shapes"></a><span data-ttu-id="aff82-1124">Sketchy で描く!</span><span class="sxs-lookup"><span data-stu-id="aff82-1124">Sketchy Shapes!</span></span>

<span data-ttu-id="aff82-1125">プレゼンテーションを作成中ですか。</span><span class="sxs-lookup"><span data-stu-id="aff82-1125">In the middle of drafting a presentation?</span></span> <span data-ttu-id="aff82-1126">まだ作業中であることを示す Sketchy スタイルを適用します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1126">Apply the sketchy style to show that you're still working on it.</span></span> <span data-ttu-id="aff82-1127">これを使用すると、自由形式や手描きの図形に変えることなく、オブジェクトに個人的なタッチを与えることができます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1127">It gives a personal touch to your objects without turning it into a free form, hand-drawn shapes.</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1128">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1128">Excel</span></span>

- <span data-ttu-id="aff82-1129">**ファイル共有の高速化**: ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1129">**Faster file sharing**: Share your documents right from the recently used list without having to open the file.</span></span>
### <a name="powerpoint"></a><span data-ttu-id="aff82-1130">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1130">PowerPoint</span></span>

- <span data-ttu-id="aff82-1131">**アクセスを容易にするため、[印刷] メニューに [配布資料にスライド番号を印刷する] を移動しました:** 配布資料が指定されているときに、[印刷] > [印刷レイアウト] ドロップダウンの順にクリックすると見つかります。</span><span class="sxs-lookup"><span data-stu-id="aff82-1131">**The setting to Print Slide Numbers in Handouts has been moved to the Print Menu for easier access:**  Find it in the Print > Print Layout dropdown when a Handout layout is selected.</span></span> <span data-ttu-id="aff82-1132">これにより、プレゼンテーションごとに簡単に設定を切り替えることもできます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1132">This also allows the setting to be easily toggled per presentation.</span></span> [<span data-ttu-id="aff82-1133">詳細情報</span><span class="sxs-lookup"><span data-stu-id="aff82-1133">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="aff82-1134">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1134">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1135">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1135">Word</span></span>

- <span data-ttu-id="aff82-1136">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1136">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="aff82-1137">主な修正:</span><span class="sxs-lookup"><span data-stu-id="aff82-1137">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="aff82-1138">すべて</span><span class="sxs-lookup"><span data-stu-id="aff82-1138">All</span></span>
- <span data-ttu-id="aff82-1139">リボンのキー ヒントのパフォーマンスが大幅に改善されました</span><span class="sxs-lookup"><span data-stu-id="aff82-1139">We significantly improved the performance of Ribbon KeyTips</span></span>
- <span data-ttu-id="aff82-1140">「今後のリリース予定を確認」ダイアログが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1140">We fixed an issue which prevented the "See what's coming soon" dialog from being displayed properly</span></span>
- <span data-ttu-id="aff82-1141">共著ギャラリーのポップアップで写真の位置がずれてしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1141">We fixed an issue which could cause Photos to be misaligned in the Co-auth Gallery flyout</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1142">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1142">Word</span></span> 
- <span data-ttu-id="aff82-1143">新しいコメントが追加されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1143">We fixed an issue which could sometimes prevent new comments from being added</span></span>
- <span data-ttu-id="aff82-1144">表がクラッシュすることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1144">We fixed an issue where tables could sometimes cause a crash</span></span>
- <span data-ttu-id="aff82-1145">無効なデータが差し込み印刷の最後に追加されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1145">We fixed an issue where invalid data could sometimes be added to the end of a mail merge</span></span>
- <span data-ttu-id="aff82-1146">一部の LaTeX 数式が正しく表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1146">We fixed an issue which could cause some LaTeX equations to render incorrectly</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1147">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1147">Excel</span></span>
- <span data-ttu-id="aff82-1148">グラフの種類を変更するとランタイム例外が発生することがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1148">We fixed an issue where changing chart types could sometimes result in a runtime exception</span></span>
- <span data-ttu-id="aff82-1149">複数のウィンドウを開いたときに正しくないリボンが表示されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1149">We fixed an issue where the incorrect ribbon could be displayed when multiple windows were open</span></span>
- <span data-ttu-id="aff82-1150">マクロがブックの 2 番目のインスタンスを開いたときにエラーが発生することがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1150">We fixed an issue which could cause an error when a macro opened a second instance of a workbook</span></span>
- <span data-ttu-id="aff82-1151">ブックを開いたり作成したりするとき、またはブックを切り替えるときにクラッシュすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1151">We fixed an issue which could cause a crash when opening or creating a workbook, or switching between workbooks</span></span>
- <span data-ttu-id="aff82-1152">ユーザーが Word で作成した PDF を Teams で開くことができない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1152">We fixed an issue preventing users from opening a PDF created from Word in Teams</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1153">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1153">PowerPoint</span></span>
- <span data-ttu-id="aff82-1154">PDF にエクスポートすると、グラフの品質が低下する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1154">We fixed an issue which would degrade the quality of a chart when exported to a pdf</span></span>
- <span data-ttu-id="aff82-1155">中心までの距離を示すヒントが表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1155">We fixed an issue which prevented a tooltip indicating the distance to center from displaying</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1156">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1156">Outlook</span></span>
- <span data-ttu-id="aff82-1157">ディスクの領域不足エラーが表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1157">We fixed an issue which could sometimes prevent a Disk Full error to be displayed</span></span>
- <span data-ttu-id="aff82-1158">会議出席依頼を更新する際に添付ファイルが複製されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1158">We fixed an issue which could cause attachments to become duplicated when updating a meeting request</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1159">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1159">Access</span></span>
- <span data-ttu-id="aff82-1160">一部のクエリが大きい整数値を返さない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1160">We fixed an issue which prevented some queries from returning large integer values</span></span>
- <span data-ttu-id="aff82-1161">SQL テキストボックスが編集できなくなることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1161">We fixed an issue which could make the sql textbox uneditable</span></span>
- <span data-ttu-id="aff82-1162">一部の高 DPI ディスプレイでは、ヒントが見づらいことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1162">We fixed an issue where tooltips could be difficult to see on some High DPI displays</span></span>

### <a name="project"></a><span data-ttu-id="aff82-1163">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1163">Project</span></span>
- <span data-ttu-id="aff82-1164">新しいタスクでフラグの値が編集できなくなることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1164">We fixed an issue which could cause flag values to become uneditable in new tasks</span></span>
- <span data-ttu-id="aff82-1165">ステータスの更新によって割り当てとタスクの実際の開始日が不適切に設定されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1165">We fixed an issue which could cause a status update to improperly set Actual Start Date on Assignments and Tasks</span></span>
- <span data-ttu-id="aff82-1166">一部のリソースが間違って割り当て超過に表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1166">We fixed an issue which could cause some resources to incorreclty appear overallocated</span></span>
- <span data-ttu-id="aff82-1167">ラグが追加され、小数点の記号がカンマで、サーバーに接続されていると TaskDependencies Add メソッドが失敗することがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1167">We fixed an issue where the TaskDependencies Add method could fail when Lag is added, the decimal separator is a comma, and when connected to a server</span></span>
- <span data-ttu-id="aff82-1168">CSOM を使用してローカル ユーザー設定フィールドの参照テーブルの値を更新すると PCS がクラッシュすることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1168">We fixed an issue where updating local custom field lookup table values via CSOM could crash PCS</span></span>
- <span data-ttu-id="aff82-1169">作業時間の合計値に小数点が含まれる場合に正しく表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1169">We fixed an issue where the total work values may appear incorrect if they contain a decimal</span></span>

</BR></BR>

## <a name="june-28-2019"></a><span data-ttu-id="aff82-1170">2019 年 6 月 28 日</span><span class="sxs-lookup"><span data-stu-id="aff82-1170">June 28, 2019</span></span>
<span data-ttu-id="aff82-1171">バージョン 1907 (ビルド 11819.20002)</span><span class="sxs-lookup"><span data-stu-id="aff82-1171">Version 1907 (build 11819.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="aff82-1172">新機能:</span><span class="sxs-lookup"><span data-stu-id="aff82-1172">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1173">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1173">Excel</span></span>

- <span data-ttu-id="aff82-1174">**Power Query の機能強化を使用して素早くコーディングする:** オートコンプリートと構文の色分けを使用して、素早くコーディングを完了します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1174">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="aff82-1175">関数、列、パラメーターも簡単に見つけることができます</span><span class="sxs-lookup"><span data-stu-id="aff82-1175">Easily discover functions, columns, and parameters, too</span></span>

- <span data-ttu-id="aff82-1176">**類似列のテーブルを結合する:** 取得と変換 (Power Query) では、テーブルを結合するために列を比較するときに、近似テキスト マッチング ロジック (あいまい一致とも呼ばれる) が使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1176">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1177">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1177">Word</span></span>

- <span data-ttu-id="aff82-1178">**共同編集の改善:** 共同編集時の信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1178">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>
 
### <a name="word-excel-powerpoint-and-visio"></a><span data-ttu-id="aff82-1179">Word、Excel、PowerPoint、Visio</span><span class="sxs-lookup"><span data-stu-id="aff82-1179">Word, Excel, PowerPoint, and Visio</span></span>

#### <a name="recommended-documents"></a><span data-ttu-id="aff82-1180">推奨されるドキュメント</span><span class="sxs-lookup"><span data-stu-id="aff82-1180">Recommended Documents</span></span>

<span data-ttu-id="aff82-1181">推奨される関連アクティビティを含むドキュメントをご確認ください。</span><span class="sxs-lookup"><span data-stu-id="aff82-1181">Find documents with relevant activity recommended to you.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="aff82-1182">主な修正:</span><span class="sxs-lookup"><span data-stu-id="aff82-1182">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1183">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1183">Word</span></span> 
- <span data-ttu-id="aff82-1184">一部の .DOC を開くことができない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1184">We fixed an issue which could prevent some .DOC files from opening</span></span>
- <span data-ttu-id="aff82-1185">コメントが正常に読み込まれない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1185">We fixed an issue which could have prevented comments from loading properly</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1186">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1186">Excel</span></span>
- <span data-ttu-id="aff82-1187">Power Query のパフォーマンスが向上しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1187">We improved the performance of Power Queries</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1188">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1188">PowerPoint</span></span>
- <span data-ttu-id="aff82-1189">画面のちらつきの原因となる、Surface デバイスでのペン使用に関連する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1189">We fixed an issue related to using a pen on a Surface device which could cause the screen to flicker</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1190">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1190">Outlook</span></span>
- <span data-ttu-id="aff82-1191">会議に変換すると、予定の空き時間情報が変更される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1191">We fixed an issue which could change the free/busy status of an appointment when converted to a meeting</span></span>
- <span data-ttu-id="aff82-1192">電子メールがアドホック テンプレートで保護されている場合に、不適切なテンプレートと説明が表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1192">We fixed an issue where the wrong template and description would be displayed when an e-mail was protected with an ad-hoc template</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1193">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1193">Access</span></span>
- <span data-ttu-id="aff82-1194">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1194">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="aff82-1195">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1195">Project</span></span>
- <span data-ttu-id="aff82-1196">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1196">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-21-2019"></a><span data-ttu-id="aff82-1197">2019 年 6 月 21 日</span><span class="sxs-lookup"><span data-stu-id="aff82-1197">June 21, 2019</span></span>
<span data-ttu-id="aff82-1198">バージョン 1907 (ビルド 11815.20002)</span><span class="sxs-lookup"><span data-stu-id="aff82-1198">Version 1907 (build 11815.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="aff82-1199">新機能:</span><span class="sxs-lookup"><span data-stu-id="aff82-1199">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1200">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1200">Outlook</span></span>

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a><span data-ttu-id="aff82-1201">Outlook デスクトップにおける黒のテーマでの濃色モード</span><span class="sxs-lookup"><span data-stu-id="aff82-1201">Dark Mode for Black Theme in Outlook Desktop</span></span>

<span data-ttu-id="aff82-1202">[濃色] モードで黒のテーマを使用しているユーザーには、電子メールを読むときに [閲覧] ウィンドウは暗く表示され、メールを作成するときも同様に表示されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1202">With dark mode, users in black theme will now also see the reading pane with a dark background when reading emails, and the compose experience with a dark background when writing emails.</span></span> <span data-ttu-id="aff82-1203">ユーザーが明るい背景でメッセージがどのように見えるかを確認する場合に備えて、[閲覧] ウィンドウとリボンに [太陽/月] トグルがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-1203">There is a sun/moon toggle on the reading pane and in the ribbon in case users want to preview what the message looks like with a light background instead.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="aff82-1204">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="aff82-1204">Getting Started:</span></span>

1. <span data-ttu-id="aff82-1205">[黒のテーマ] に切り替えると、既定では濃色モードになります。</span><span class="sxs-lookup"><span data-stu-id="aff82-1205">Turn on black theme and dark mode will be on by default.</span></span>
2. <span data-ttu-id="aff82-1206">(閲覧ウィンドウとリボンにある) [月/太陽] トグルを使用して、濃色モードでないユーザーにメッセージがどのように見えるかを表示します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1206">Use the moon/sun toggle (in the reading pane and in the ribbon) to preview what the message looks like for users not in dark mode</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="aff82-1207">次の操作を試してみてください</span><span class="sxs-lookup"><span data-stu-id="aff82-1207">Scenarios to Try</span></span>

1. <span data-ttu-id="aff82-1208">濃色モードでメールを読みます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1208">Read emails in dark mode.</span></span> <span data-ttu-id="aff82-1209">何も見えない場合は、[閲覧] ウィンドウの [太陽] トグルを使用して、背景を明るくします。</span><span class="sxs-lookup"><span data-stu-id="aff82-1209">If you are unable to read something, use the sun toggle in the Reading Pane to switch to a light background.</span></span> 
2. <span data-ttu-id="aff82-1210">[濃色] モードでメールを作成します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1210">Compose emails in dark mode.</span></span> <span data-ttu-id="aff82-1211">リボンの [太陽] トグルを使用して、メッセージが明るい背景でどのように見えるかを確認します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1211">Preview what your message will look like with a light background by using the sun toggle in the ribbon.</span></span> 

<span data-ttu-id="aff82-1212">正常に表示されないメールが見つかった場合は、(添付ファイルとして) OutlookDarkModeFail@service.microsoft.com に送信してください</span><span class="sxs-lookup"><span data-stu-id="aff82-1212">If you encounter any emails that don't render properly, please send them (as an attachment) to OutlookDarkModeFail@service.microsoft.com</span></span>

#### <a name="get-location-suggestions"></a><span data-ttu-id="aff82-1213">場所の候補を取得する</span><span class="sxs-lookup"><span data-stu-id="aff82-1213">Get location suggestions</span></span>

<span data-ttu-id="aff82-1214">入力を開始すると、Outlook で一致する場所が検索されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1214">Start typing and Outlook will look for matching locations.</span></span>

<span data-ttu-id="aff82-1215">予定や会議を作成するときは、[場所] フィールドに適用されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1215">This applies to the Location field when creating Appointments and Meetings.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="aff82-1216">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="aff82-1216">Getting Started:</span></span>

- <span data-ttu-id="aff82-1217">Outlook で O365 または Outlook.com の予定表に予定や会議を作成します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1217">Create an Appointment or Meeting on an O365 or Outlook.com calendar in Outlook.</span></span> 
- <span data-ttu-id="aff82-1218">[場所] フィールドをクリックして、入力を開始します...。</span><span class="sxs-lookup"><span data-stu-id="aff82-1218">Click into the Location field and start typing…</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="aff82-1219">次の操作を試してみてください</span><span class="sxs-lookup"><span data-stu-id="aff82-1219">Scenarios to Try</span></span>

<span data-ttu-id="aff82-1220">会議に会議室を追加するときは、[会議室の検索] アドインやアドレス帳を使用するのではなく、[場所] フィールドをクリックします。</span><span class="sxs-lookup"><span data-stu-id="aff82-1220">When adding a conference room to a meeting, click into Location field, rather than using Room Finder add-in or Address Book.</span></span>
<span data-ttu-id="aff82-1221">レストラン、喫茶店、歯科医院といった公共の場所での予定がある場合は、新しいピッカーを使用して正確な位置を見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1221">For appointments at a physical place with a public location - like a restaurant, coffee shop, or even your dentist's office - try finding the exact location using the new picker.</span></span> <span data-ttu-id="aff82-1222">こうすることで、外出するときに Outlook Mobile で通知を受け取ることができます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1222">This way, you'll be able to get notified on Outlook Mobile when it's time to leave.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="aff82-1223">主な修正:</span><span class="sxs-lookup"><span data-stu-id="aff82-1223">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="aff82-1224">すべて</span><span class="sxs-lookup"><span data-stu-id="aff82-1224">All</span></span>
- <span data-ttu-id="aff82-1225">オフラインで [検索] ボックスが有効なままになる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1225">We fixed an issue which would keep the Search Box enabled while offline</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1226">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1226">Word</span></span> 
- <span data-ttu-id="aff82-1227">キーボード フォーカスが表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1227">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>
- <span data-ttu-id="aff82-1228">新しいドキュメントにテキストを貼り付けたときに、テキストが間違えて配置される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1228">We fixed an issue where text pasted into a new document could sometimes have the wrong text alignment</span></span>
- <span data-ttu-id="aff82-1229">コンピューターを中断した後に、一部のユーザーが変更を保存できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1229">We fixed an issue which could prevent some users from saving changes after suspending their computer</span></span>
- <span data-ttu-id="aff82-1230">特定の場合に、選択したページの代わりにドキュメント全体が印刷される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1230">We fixed an issue where in certain cases an entire document would be printed instead of the selected range</span></span>
- <span data-ttu-id="aff82-1231">小さなディスプレイでコメントが読みにくくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1231">We fixed an issue which could make comments difficult to read on smaller displays</span></span>
- <span data-ttu-id="aff82-1232">デバイスにキャプチャするときにクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1232">We fixed an issue which could cause a crash when capturing to a device</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1233">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1233">Excel</span></span>
- <span data-ttu-id="aff82-1234">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1234">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1235">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1235">PowerPoint</span></span>
- <span data-ttu-id="aff82-1236">キーボード フォーカスが表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1236">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1237">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1237">Outlook</span></span>
- <span data-ttu-id="aff82-1238">有効ではないときにアドインが誤って有効になっていると表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1238">We fixed an issue which could incorrectly display an add-in as being enabled when it was not.</span></span>
- <span data-ttu-id="aff82-1239">多数の保持ポリシーが表示されていない場合、ユーザーがすべての保持ポリシーを表示できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1239">We fixed an issue which would prevent a customer from viewing all retention policies if there were a large number of them</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1240">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1240">Access</span></span>
- <span data-ttu-id="aff82-1241">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1241">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="aff82-1242">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1242">Project</span></span>
- <span data-ttu-id="aff82-1243">さまざまなパフォーマンスと安定性に関する修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1243">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-14-2019"></a><span data-ttu-id="aff82-1244">2019 年 6 月 14 日</span><span class="sxs-lookup"><span data-stu-id="aff82-1244">June 14, 2019</span></span>
<span data-ttu-id="aff82-1245">バージョン 1907 (ビルド 11807.20000)</span><span class="sxs-lookup"><span data-stu-id="aff82-1245">Version 1907 (build 11807.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="aff82-1246">主な修正:</span><span class="sxs-lookup"><span data-stu-id="aff82-1246">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1247">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1247">Word</span></span> 
- <span data-ttu-id="aff82-1248">OneDrive に保存しているときにユーザーがサインインするのを妨げていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="aff82-1248">We fixed an issue which could prevent a user from signing in when saving to OneDrive</span></span>
- <span data-ttu-id="aff82-1249">アクセス制限モード中にユーザーによる SharePoint のプロパティの変更が妨げられていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="aff82-1249">We fixed an issue where a user could be prevented from changing SharePoint properties while in restricted access mode</span></span>
- <span data-ttu-id="aff82-1250">余白を調整しているときにヘッダーやフッターの内容が変更されてしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="aff82-1250">We fixed an issue where header and footer content could change when adjusting margins</span></span>
- <span data-ttu-id="aff82-1251">Web ビューに切り替えているときに書式設定が崩れてしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="aff82-1251">We fixed an issue where formatting could break when switching to web view</span></span>
- <span data-ttu-id="aff82-1252">SharePoint で開いたときにユーザーによるカスタム フィールドの使用を妨げていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="aff82-1252">We fixed an issue which could prevent a user from using custom fields when opened from SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1253">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1253">Excel</span></span>
- <span data-ttu-id="aff82-1254">フィルター処理された行を削除するときのパフォーマンスの問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="aff82-1254">We fixed a performance issue when deleting rows of a filtered set</span></span>
- <span data-ttu-id="aff82-1255">時々、保護ビューでマウスをちらつかせる原因になっていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="aff82-1255">We fixed an issue which could sometimes cause the mouse to flicker in protected view</span></span>
- <span data-ttu-id="aff82-1256">系列を削除しているときにクラッシュを引き起こしていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="aff82-1256">We fixed an issue which could have caused a crash when deleting a series</span></span>
- <span data-ttu-id="aff82-1257">利用できなかった場合に一部のユーザーがバージョン履歴を追加するオプションを使用していたところの問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="aff82-1257">We fixed an issue where some users would have the option to add version history when that was not available</span></span>
- <span data-ttu-id="aff82-1258">スプレッドシート比較ツールを使用しているときに例外を引き起こしていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="aff82-1258">We fixed an issue which could have caused an exception when using the Spreadsheet Compare tool</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1259">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1259">PowerPoint</span></span>
- <span data-ttu-id="aff82-1260">SharePoint へのリンクをクリックしたときにクラッシュを発生させていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="aff82-1260">We fixed an issue where a crash could occur when clicking a link to SharePoint</span></span>
- <span data-ttu-id="aff82-1261">ユーザーが Surface ペンを使用して入力しているのに、次のページに切り替わってしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="aff82-1261">We fixed an issue which could switch the user to the next page while typing using a Surface Pen</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1262">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1262">Outlook</span></span>
- <span data-ttu-id="aff82-1263">一部の宛先フィールドが通常より大きくなってしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="aff82-1263">We fixed an issue where in some cases the To field was larger than normal</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1264">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1264">Access</span></span>
- <span data-ttu-id="aff82-1265">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1265">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="aff82-1266">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1266">Project</span></span>
- <span data-ttu-id="aff82-1267">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1267">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-7-2019"></a><span data-ttu-id="aff82-1268">2019 年 6 月 7 日</span><span class="sxs-lookup"><span data-stu-id="aff82-1268">June 7, 2019</span></span>
<span data-ttu-id="aff82-1269">バージョン 1907 (ビルド 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="aff82-1269">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="aff82-1270">主な修正:</span><span class="sxs-lookup"><span data-stu-id="aff82-1270">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1271">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1271">Word</span></span> 
- <span data-ttu-id="aff82-1272">オートコレクトが文の先頭文字を大文字にするように設定されていると Word がクラッシュする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1272">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="aff82-1273">SharePoint でドキュメントを編集する際のパフォーマンスが向上しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1273">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="aff82-1274">Adobe Illustrator で作成されたベクター ベースの画像が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1274">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1275">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1275">Excel</span></span>
- <span data-ttu-id="aff82-1276">マクロを記録するときに、並べ替えフィールドが正しく設定されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1276">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="aff82-1277">配列数式の計算中にハングまたはクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1277">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1278">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1278">PowerPoint</span></span>
- <span data-ttu-id="aff82-1279">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1279">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1280">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1280">Outlook</span></span>
- <span data-ttu-id="aff82-1281">インライン添付ファイルが誤って拡大縮小されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1281">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1282">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1282">Access</span></span>
- <span data-ttu-id="aff82-1283">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1283">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="aff82-1284">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1284">Project</span></span>
- <span data-ttu-id="aff82-1285">固定期間のタイムシートが割り当て終了日を変更するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1285">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="aff82-1286">以前のバージョンからプロジェクトを開くと、[完了率] の値が正しくない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1286">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="aff82-1287">2019 年 5 月 31 日</span><span class="sxs-lookup"><span data-stu-id="aff82-1287">May 31, 2019</span></span>
<span data-ttu-id="aff82-1288">バージョン 1906 (ビルド 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="aff82-1288">Version 1906 (build 11722.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="aff82-1289">新機能:</span><span class="sxs-lookup"><span data-stu-id="aff82-1289">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1290">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1290">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="aff82-1291">サポートに問い合わせるためのダイアログがドッキング可能になり、右側に表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1291">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="aff82-1292">サポートへの問い合わせに使用するダイアログが右側のウィンドウに表示され、最初からドッキングされたウィンドウとして表示されます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1292">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="aff82-1293">メールでインクを使用する</span><span class="sxs-lookup"><span data-stu-id="aff82-1293">Ink in Your Email!</span></span>

<span data-ttu-id="aff82-1294">Outlook メールで画像を描画し、注釈を付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1294">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1295">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1295">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="aff82-1296">ドキュメント リンクを Word で開く</span><span class="sxs-lookup"><span data-stu-id="aff82-1296">Open document links in Word</span></span>

<span data-ttu-id="aff82-1297">Office でドキュメント リンクをクリックしたときに既定で Word アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1297">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="aff82-1298">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1298">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="aff82-1299">詳しくは、以下を参照してください。https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="aff82-1299">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="aff82-1300">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="aff82-1300">Getting Started:</span></span>

<span data-ttu-id="aff82-1301">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="aff82-1301">Feature will default to off.</span></span> <span data-ttu-id="aff82-1302">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-1302">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="aff82-1303">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1303">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="aff82-1304">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1304">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="aff82-1305">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="aff82-1305">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="aff82-1306">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1306">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="aff82-1307">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="aff82-1307">Scenarios to Try:</span></span>

<span data-ttu-id="aff82-1308">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている Word ドキュメントへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="aff82-1308">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="aff82-1309">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="aff82-1309">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1310">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1310">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="aff82-1311">プレゼンテーションへのリンクを PowerPoint で開く</span><span class="sxs-lookup"><span data-stu-id="aff82-1311">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="aff82-1312">Office でプレゼンテーションへのリンクをクリックしたときに既定で PowerPoint アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1312">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="aff82-1313">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1313">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="aff82-1314">詳しくは、以下を参照してください。https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="aff82-1314">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="aff82-1315">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="aff82-1315">Getting Started:</span></span>

<span data-ttu-id="aff82-1316">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="aff82-1316">Feature will default to off.</span></span> <span data-ttu-id="aff82-1317">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-1317">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="aff82-1318">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1318">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="aff82-1319">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1319">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="aff82-1320">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="aff82-1320">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="aff82-1321">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1321">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="aff82-1322">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="aff82-1322">Scenarios to Try:</span></span>

<span data-ttu-id="aff82-1323">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている PowerPoint プレゼンテーションへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="aff82-1323">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="aff82-1324">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="aff82-1324">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1325">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1325">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="aff82-1326">ブックのリンクを Excel で開く</span><span class="sxs-lookup"><span data-stu-id="aff82-1326">Open workbook links in Excel</span></span>

<span data-ttu-id="aff82-1327">Office でブックのリンクをクリックしたときに既定で Excel アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1327">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="aff82-1328">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1328">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="aff82-1329">詳細については、以下を参照してください。https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="aff82-1329">Learn More: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="aff82-1330">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="aff82-1330">Getting Started:</span></span>

<span data-ttu-id="aff82-1331">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="aff82-1331">Feature will default to off.</span></span> <span data-ttu-id="aff82-1332">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="aff82-1332">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="aff82-1333">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1333">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="aff82-1334">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1334">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="aff82-1335">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="aff82-1335">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="aff82-1336">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1336">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="aff82-1337">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="aff82-1337">Scenarios to Try:</span></span>

<span data-ttu-id="aff82-1338">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている Excel ブックへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="aff82-1338">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="aff82-1339">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="aff82-1339">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="aff82-1340">主な修正:</span><span class="sxs-lookup"><span data-stu-id="aff82-1340">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="aff82-1341">すべて</span><span class="sxs-lookup"><span data-stu-id="aff82-1341">All</span></span>
- <span data-ttu-id="aff82-1342">自動保存が無効になっている場合でも、ファイルが自動保存されてしまう場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1342">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1343">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1343">Word</span></span> 
- <span data-ttu-id="aff82-1344">一部のユーザーがファイルを SharePoint に保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1344">We fixed an issue which may have prevented some users from saving to SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1345">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1345">Excel</span></span>
- <span data-ttu-id="aff82-1346">無効なフィルターに間違ったアイコンが表示される場合がある問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="aff82-1346">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1347">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1347">PowerPoint</span></span>
- <span data-ttu-id="aff82-1348">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1348">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1349">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1349">Outlook</span></span>
- <span data-ttu-id="aff82-1350">グループ スケジュール ビューで一部のユーザーがオフラインとして間違って表示される問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="aff82-1350">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="aff82-1351">末尾にスペースが挿入されている URL が SafeLink で解析できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1351">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="aff82-1352">業務時間外に部屋が利用可能と表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1352">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1353">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1353">Access</span></span>
- <span data-ttu-id="aff82-1354">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1354">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="aff82-1355">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1355">Project</span></span>
- <span data-ttu-id="aff82-1356">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1356">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="aff82-1357">2019 年 5 月 24 日</span><span class="sxs-lookup"><span data-stu-id="aff82-1357">May 24, 2019</span></span>
<span data-ttu-id="aff82-1358">バージョン 1906 (ビルド 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="aff82-1358">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="aff82-1359">新機能:</span><span class="sxs-lookup"><span data-stu-id="aff82-1359">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="aff82-1360">ユーザー エクスペリエンスの更新</span><span class="sxs-lookup"><span data-stu-id="aff82-1360">User Experience Updates</span></span>

<span data-ttu-id="aff82-1361">近日公開となっていた更新プログラムが公開されました。この更新には、シンプル リボンおよびフォルダー ウィンドウ、メッセージ一覧、閲覧ウィンドウの外観の更新が含まれます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1361">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="aff82-1362">主な修正:</span><span class="sxs-lookup"><span data-stu-id="aff82-1362">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="aff82-1363">すべて</span><span class="sxs-lookup"><span data-stu-id="aff82-1363">All</span></span>

- <span data-ttu-id="aff82-1364">チャットウィンドウが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1364">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1365">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1365">Word</span></span> 
- <span data-ttu-id="aff82-1366">Word で文法エラーのテキストが誤って強調表示されることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1366">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1367">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1367">Excel</span></span>
- <span data-ttu-id="aff82-1368">誤ったアイコンがグラフ要素に使用されているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1368">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="aff82-1369">同じブックが既に開いているときに、不正なブックが VBA スクリプトでアクティブになるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1369">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1370">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1370">PowerPoint</span></span>
- <span data-ttu-id="aff82-1371">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1371">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1372">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1372">Outlook</span></span>
- <span data-ttu-id="aff82-1373">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1373">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1374">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1374">Access</span></span>
- <span data-ttu-id="aff82-1375">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1375">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="aff82-1376">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1376">Project</span></span>
- <span data-ttu-id="aff82-1377">タスクバーに切り替えた後、Project がクラッシュする可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1377">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="aff82-1378">2019 年 5 月 17 日</span><span class="sxs-lookup"><span data-stu-id="aff82-1378">May 17, 2019</span></span>
<span data-ttu-id="aff82-1379">バージョン 1906 (ビルド 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="aff82-1379">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="aff82-1380">新機能:</span><span class="sxs-lookup"><span data-stu-id="aff82-1380">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1381">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1381">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="aff82-1382">ユーザー エクスペリエンスのアップデート</span><span class="sxs-lookup"><span data-stu-id="aff82-1382">User Experience Updates</span></span>

<span data-ttu-id="aff82-1383">近日公開となっていた更新プログラムが公開されました。この更新には、シンプル リボンおよびフォルダー ウィンドウ、メッセージ一覧、閲覧ウィンドウの外観の更新が含まれます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1383">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="aff82-1384">利用するには:</span><span class="sxs-lookup"><span data-stu-id="aff82-1384">Getting Started:</span></span>

<span data-ttu-id="aff82-1385">これらの変更は、新しい既定の UI の一部になります。この新しい UI は、すべての運用環境ユーザー向けに [近日公開] スイッチで 12 月中旬以来提供されてきました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1385">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="aff82-1386">カスタマイズ可能なシンプル リボン</span><span class="sxs-lookup"><span data-stu-id="aff82-1386">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="aff82-1387">従来のビューとシンプルなビューの切り替えやコマンドの固定または固定解除を簡単にできます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1387">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="aff82-1388">利用するには:</span><span class="sxs-lookup"><span data-stu-id="aff82-1388">Getting Started:</span></span>

<span data-ttu-id="aff82-1389">シンプル リボンを使用するには、まず [近日公開] 機能をオンにし、リボンの山形マークをクリックして従来の複数行のリボンと新しい 1 行のシンプル リボンを切り替えます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1389">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="aff82-1390">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="aff82-1390">Scenarios to Try:</span></span>

<span data-ttu-id="aff82-1391">従来のリボンからシンプル リボンに切り替える</span><span class="sxs-lookup"><span data-stu-id="aff82-1391">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="aff82-1392">お気に入りの操作を選択する</span><span class="sxs-lookup"><span data-stu-id="aff82-1392">Pick your favorite action</span></span>

<span data-ttu-id="aff82-1393">[フラグ] 機能や [削除] 機能はお使いになられていないかもしれません。</span><span class="sxs-lookup"><span data-stu-id="aff82-1393">Don't use Flag and Delete?</span></span> <span data-ttu-id="aff82-1394">アーカイブまたは既読に​​しますか?</span><span class="sxs-lookup"><span data-stu-id="aff82-1394">How about Archive or Mark as Read?</span></span> <span data-ttu-id="aff82-1395">クイック操作メニューをカスタマイズしてよく使うコマンドを追加できます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1395">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="aff82-1396">利用するには:</span><span class="sxs-lookup"><span data-stu-id="aff82-1396">Getting Started:</span></span>

<span data-ttu-id="aff82-1397">希望のクイック操作を選ぶには、メッセージ一覧でメールを右クリックし、コンテキスト メニューを表示します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1397">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="aff82-1398">次に、[クイック操作の設定] をクリックします。</span><span class="sxs-lookup"><span data-stu-id="aff82-1398">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="aff82-1399">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="aff82-1399">Scenarios to Try:</span></span>

<span data-ttu-id="aff82-1400">既定の設定を [フラグ] または [削除] から [アーカイブ]、[移動]、[既読にする]、または [なし] に変更すると、メッセージ一覧をすっきりした外観にできます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1400">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="aff82-1401">レイアウトの間隔を</span><span class="sxs-lookup"><span data-stu-id="aff82-1401">Relaxed or tighter layout?</span></span> <span data-ttu-id="aff82-1402">自由に選べます</span><span class="sxs-lookup"><span data-stu-id="aff82-1402">You choose</span></span>

<span data-ttu-id="aff82-1403">[狭い間隔を使用] オプションを使用すると、アイテム間のスペースを広く取るか、間隔の狭いレイアウトでより多くのアイテムを表示するかを選べます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1403">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="aff82-1404">利用するには:</span><span class="sxs-lookup"><span data-stu-id="aff82-1404">Getting Started:</span></span>

<span data-ttu-id="aff82-1405">従来のリボンの場合、[表示] タブの [メッセージ] グループで、[狭い間隔を使用] チェックボックスをオンにします。シンプル リボンの場合は、[現在のビュー] 設定で [狭い間隔を使用] を選択します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1405">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="aff82-1406">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="aff82-1406">Scenarios to Try:</span></span>

<span data-ttu-id="aff82-1407">Outlook で、この設定をオフにした状態でメッセージをトリアージしたり作成したりしてみます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1407">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="aff82-1408">この機能をオンにすると、1 ページに収まるメッセージの数が増え、新規作成フォームのコントロールの表示がすっきりとします。</span><span class="sxs-lookup"><span data-stu-id="aff82-1408">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="aff82-1409">Onedrive 同期クライアントを使用する際の MRU エントリの重複を除去する</span><span class="sxs-lookup"><span data-stu-id="aff82-1409">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="aff82-1410">クラウド添付ファイルを使用すると、MRU エントリの重複を除去できるため、Onedrive の統合を効率化できます。クラウド添付ファイルを使用すれば、同期されたデータでコピーの添付をする動作が早くなります。</span><span class="sxs-lookup"><span data-stu-id="aff82-1410">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="aff82-1411">利用するには:</span><span class="sxs-lookup"><span data-stu-id="aff82-1411">Getting Started:</span></span>

<span data-ttu-id="aff82-1412">OneDrive 同期クライアントを使用している場合は、添付ファイル MRU に重複ファイルが表示されなくなります。</span><span class="sxs-lookup"><span data-stu-id="aff82-1412">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="aff82-1413">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="aff82-1413">Scenarios to Try:</span></span>

<span data-ttu-id="aff82-1414">OneDrive 同期クライアントを有効にして、Outlook デスクトップで [ファイルの添付] メニューを使用する</span><span class="sxs-lookup"><span data-stu-id="aff82-1414">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="aff82-1415">フォルダーを多数含むメールボックスでの共有フォルダーの同期が改善されました</span><span class="sxs-lookup"><span data-stu-id="aff82-1415">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="aff82-1416">長い間、Outlook での共有メールボックスの同期は、最大で 500 フォルダーに制限されてきました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1416">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="aff82-1417">この変更により Outlook の改善が行われ、同期をする際の 500 フォルダーの制限がなくなりました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1417">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="aff82-1418">利用するには:</span><span class="sxs-lookup"><span data-stu-id="aff82-1418">Getting Started:</span></span>

<span data-ttu-id="aff82-1419">メールボックスにフォルダーを 1000 個作成し、誰か他のユーザーにそのメールボックスへのアクセスを許可し、このユーザーの Outlook プロファイルを作成します。同期が正常に動作することを確認します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1419">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1420">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1420">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="aff82-1421">少しだけ消す</span><span class="sxs-lookup"><span data-stu-id="aff82-1421">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="aff82-1422">利用するには:</span><span class="sxs-lookup"><span data-stu-id="aff82-1422">Getting Started:</span></span>

<span data-ttu-id="aff82-1423">[描画] タブに移動します。 [消しゴム] ドロップダウンを選択します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1423">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="aff82-1424">[消しゴム (小)] または [消しゴム (中)] を選びます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1424">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="aff82-1425">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="aff82-1425">Scenarios to Try:</span></span>

<span data-ttu-id="aff82-1426">[描画] タブに移動します。ペンを選びます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1426">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="aff82-1427">インク ストロークを描きます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1427">Draw an ink stroke.</span></span> <span data-ttu-id="aff82-1428">[消しゴム] ドロップダウンを選択します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1428">Select the Eraser dropdown.</span></span> <span data-ttu-id="aff82-1429">[消しゴム (小)] または [消しゴム (中)] を選びます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1429">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="aff82-1430">インク ストロークを少しだけ消してみます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1430">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="aff82-1431">主な修正:</span><span class="sxs-lookup"><span data-stu-id="aff82-1431">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="aff82-1432">すべて</span><span class="sxs-lookup"><span data-stu-id="aff82-1432">All</span></span> 
- <span data-ttu-id="aff82-1433">一部のユーザーが PDF として保存できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1433">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="aff82-1434">32 ビット システムでの大容量ファイルの保存に影響する場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1434">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1435">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1435">Word</span></span> 
- <span data-ttu-id="aff82-1436">音声入力機能の応答性が大幅に向上されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1436">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1437">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1437">Excel</span></span>
- <span data-ttu-id="aff82-1438">タッチ スクリーン デバイスでダブルクリック イベントが失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1438">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="aff82-1439">一部のユーザーが VBA マクロを編集できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1439">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="aff82-1440">スライサーを使用した際にパフォーマンスに影響する場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1440">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1441">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1441">PowerPoint</span></span>
- <span data-ttu-id="aff82-1442">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1442">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1443">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1443">Outlook</span></span>
- <span data-ttu-id="aff82-1444">選択したテンプレートとは異なるテンプレートが表示される場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1444">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1445">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1445">Access</span></span>
- <span data-ttu-id="aff82-1446">長いリッチ テキストの表示に Zoom Builder を使うと、読みづらくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1446">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="aff82-1447">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1447">Project</span></span>
- <span data-ttu-id="aff82-1448">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1448">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="aff82-1449">2019 年 5 月 10日</span><span class="sxs-lookup"><span data-stu-id="aff82-1449">May 10, 2019</span></span>
<span data-ttu-id="aff82-1450">バージョン 1906 (ビルド 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="aff82-1450">Version 1906 (build 11702.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="aff82-1451">新機能:</span><span class="sxs-lookup"><span data-stu-id="aff82-1451">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1452">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1452">Outlook</span></span>

<span data-ttu-id="aff82-1453">**より多くのメッセージを画面に収める:** [表示] > [より狭い文字間隔を使用] の順に選択し、メッセージの間隔を調整します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1453">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="aff82-1454">主な修正:</span><span class="sxs-lookup"><span data-stu-id="aff82-1454">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="aff82-1455">すべて</span><span class="sxs-lookup"><span data-stu-id="aff82-1455">All</span></span>
- <span data-ttu-id="aff82-1456">[名前を付けて保存] ダイアログボックスに誤ったパスが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1456">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1457">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1457">Word</span></span> 
- <span data-ttu-id="aff82-1458">操作アシストからの一部の選択が挿入されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1458">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1459">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1459">Excel</span></span>
- <span data-ttu-id="aff82-1460">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1460">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1461">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1461">PowerPoint</span></span>
- <span data-ttu-id="aff82-1462">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1462">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1463">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1463">Outlook</span></span>
- <span data-ttu-id="aff82-1464">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1464">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1465">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1465">Access</span></span>
- <span data-ttu-id="aff82-1466">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1466">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="aff82-1467">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1467">Project</span></span>
- <span data-ttu-id="aff82-1468">タスク ID の確認に強調表示が必要となる可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1468">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="aff82-1469">2019 年 5 月 3日</span><span class="sxs-lookup"><span data-stu-id="aff82-1469">May 3, 2019</span></span>
<span data-ttu-id="aff82-1470">バージョン 1906 (ビルド 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="aff82-1470">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="aff82-1471">新機能:</span><span class="sxs-lookup"><span data-stu-id="aff82-1471">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1472">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1472">Outlook</span></span>

<span data-ttu-id="aff82-1473">**すべての暗号化オプションを1か所で:** [オプション] > [暗号化] の順に移動して、メール メッセージを保護する方法を選択します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1473">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="aff82-1474">主な修正:</span><span class="sxs-lookup"><span data-stu-id="aff82-1474">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="aff82-1475">すべて</span><span class="sxs-lookup"><span data-stu-id="aff82-1475">All</span></span>
- <span data-ttu-id="aff82-1476">一部のユーザーが OneDrive for Business との同期で問題が発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1476">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1477">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1477">Word</span></span> 
- <span data-ttu-id="aff82-1478">Word の起動に時間がかかる場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1478">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1479">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1479">Excel</span></span>
- <span data-ttu-id="aff82-1480">新しいバージョンの Excel にアップグレードした後、ブックから外部リンクが削除されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1480">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="aff82-1481">一部のユーザーが新しいワークブックでセルを選択するのが困難な問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1481">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1482">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1482">PowerPoint</span></span>
- <span data-ttu-id="aff82-1483">図面をテキストに変換するときにフォントサイズが一致しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1483">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1484">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1484">Outlook</span></span>
- <span data-ttu-id="aff82-1485">a .VCF ファイルから連絡先を保存すると空のフィールドが発生する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1485">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="aff82-1486">送信されていても、送信トレイ フォルダーにメッセージが残ってしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1486">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="aff82-1487">DRM メッセージの表示中に Outlook がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1487">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1488">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1488">Access</span></span>
- <span data-ttu-id="aff82-1489">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1489">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="aff82-1490">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1490">Project</span></span>
- <span data-ttu-id="aff82-1491">エディターが中国語から英語に切り替わる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1491">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="aff82-1492">マスター プロジェクトの公開コピーに未公開タスクが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1492">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="aff82-1493">2019 年 4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="aff82-1493">April 26, 2019</span></span>
<span data-ttu-id="aff82-1494">バージョン 1905 (ビルド 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="aff82-1494">Version 1905 (build 11617.20002)</span></span>

## <a name="new-features"></a><span data-ttu-id="aff82-1495">新機能</span><span class="sxs-lookup"><span data-stu-id="aff82-1495">New Features</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1496">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1496">Outlook</span></span>

<span data-ttu-id="aff82-1497">**共有カレンダーの更新がより速く**: Office 365 の共有カレンダーの場合、Outlook は REST API を使用してこれらのカレンダーを更新できます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1497">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="aff82-1498">共有カレンダーのより高速で信頼性の高い更新を行うには、プレビューを有効にします。</span><span class="sxs-lookup"><span data-stu-id="aff82-1498">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1499">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1499">Excel</span></span>

#### <a name="coauthoring-improvements"></a><span data-ttu-id="aff82-1500">共同編集の改善</span><span class="sxs-lookup"><span data-stu-id="aff82-1500">Coauthoring improvements</span></span>

<span data-ttu-id="aff82-1501">他のユーザーがリアルタイムでコンテンツの変更を受け取れるようにすることで、共同編集のエクスペリエンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1501">Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

### <a name="visio"></a><span data-ttu-id="aff82-1502">Visio</span><span class="sxs-lookup"><span data-stu-id="aff82-1502">Visio</span></span>

- <span data-ttu-id="aff82-1503">**Power BI から Visio ビジュアルをエクスポートする:** PDF、PowerPoint のファイルなどの Power BI レポートをエクスポートするときに、Power BI 用の Visio Visual が正しく表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1503">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="aff82-1504">主な修正:</span><span class="sxs-lookup"><span data-stu-id="aff82-1504">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1505">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1505">Word</span></span> 
- <span data-ttu-id="aff82-1506">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1506">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1507">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1507">Excel</span></span>
- <span data-ttu-id="aff82-1508">ソルバー マクロの実行が失敗するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1508">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="aff82-1509">Excel ファイルを SharePoint にインポートできないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1509">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1510">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1510">PowerPoint</span></span>
- <span data-ttu-id="aff82-1511">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1511">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1512">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1512">Outlook</span></span>
- <span data-ttu-id="aff82-1513">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1513">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1514">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1514">Access</span></span>
- <span data-ttu-id="aff82-1515">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1515">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="aff82-1516">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1516">Project</span></span>
- <span data-ttu-id="aff82-1517">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1517">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="aff82-1518">2019 年 4 月 19 日</span><span class="sxs-lookup"><span data-stu-id="aff82-1518">April 19, 2019</span></span>
<span data-ttu-id="aff82-1519">バージョン 1905 (ビルド 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="aff82-1519">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="aff82-1520">新機能:</span><span class="sxs-lookup"><span data-stu-id="aff82-1520">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1521">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1521">Outlook</span></span>

<span data-ttu-id="aff82-1522">**人物を検索するときにメールの候補を取得する:** [検索] ボックスに人の名前を入力すると、最も関連性の高いメール メッセージが検索候補に含まれます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1522">**Get email suggestions when you search for a person:** When you type a person's name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1523">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1523">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="aff82-1524">データ型を使用した塗り分けマップのエクスペリエンス向上</span><span class="sxs-lookup"><span data-stu-id="aff82-1524">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="aff82-1525">この機能は、Excel の地理データ型を使用して、塗り分けされたマップ グラフにプロットするユーザーのための機能強化です。</span><span class="sxs-lookup"><span data-stu-id="aff82-1525">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="aff82-1526">エンドユーザーにとっては、機能とエンドユーザーがマップする領域の精度向上とがより高度に統合されたことが利点です。</span><span class="sxs-lookup"><span data-stu-id="aff82-1526">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="aff82-1527">さらに、ポリゴンで都市をマッピングする機能も含まれてます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1527">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="aff82-1528">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="aff82-1528">Getting Started:</span></span>

- <span data-ttu-id="aff82-1529">この機能は、Excel 内の既存の機能を改善したものです。</span><span class="sxs-lookup"><span data-stu-id="aff82-1529">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="aff82-1530">この改善を使用するには、位置をリッチエンティティに変換し、塗り分けマップでプロットします。</span><span class="sxs-lookup"><span data-stu-id="aff82-1530">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="aff82-1531">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="aff82-1531">Scenarios to Try:</span></span>

- <span data-ttu-id="aff82-1532">ユーザーは、都市、州、都道府県、国、郵便番号のマッピングを試すことができます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1532">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="aff82-1533">主な修正:</span><span class="sxs-lookup"><span data-stu-id="aff82-1533">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="aff82-1534">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="aff82-1534">All Applications</span></span>
- <span data-ttu-id="aff82-1535">アプリケーションが起動したときに最初の実行ダイアログが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1535">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="aff82-1536">[名前を付けて保存] ダイアログボックス内の SharePoint リンクが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1536">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="aff82-1537">ユーザーが [今すぐ修復] ダイアログを誤って表示する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1537">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1538">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1538">Word</span></span> 
- <span data-ttu-id="aff82-1539">フォントの要求時に、一部のユーザーがメモリ不足またはディスク領域のエラーを受信する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1539">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="aff82-1540">[コメント] ウィンドウから切り替えたときにウィンドウがフォーカスを失う可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1540">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1541">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1541">Excel</span></span>
- <span data-ttu-id="aff82-1542">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1542">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1543">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1543">PowerPoint</span></span>
- <span data-ttu-id="aff82-1544">ブランド化された図形のサイズ変更ができない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1544">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="aff82-1545">保護ビューモードでファイルを開くときに PowerPoint がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1545">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1546">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1546">Outlook</span></span>
- <span data-ttu-id="aff82-1547">一部のユーザーが中国語の単語を選択できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1547">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="aff82-1548">有効期限が正しく計算されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1548">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1549">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1549">Access</span></span>
- <span data-ttu-id="aff82-1550">一部のユーザーがマクロ ビルダーを使用できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1550">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="aff82-1551">レポートを印刷すると最初のページしか印刷されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1551">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="aff82-1552">ハイパーリンクの上にカーソルを置くとアプリケーションがクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1552">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="aff82-1553">リレーションシップ ビューを使用すると、一部のアイテムが画面外に表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1553">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="aff82-1554">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1554">Project</span></span>
- <span data-ttu-id="aff82-1555">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1555">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="aff82-1556">2019 年 4 月 12 日</span><span class="sxs-lookup"><span data-stu-id="aff82-1556">April 12, 2019</span></span>
<span data-ttu-id="aff82-1557">バージョン 1905 (ビルド 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="aff82-1557">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="aff82-1558">新機能:</span><span class="sxs-lookup"><span data-stu-id="aff82-1558">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1559">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1559">Access</span></span>

#### <a name="get-smart-with-microsoft-graph"></a><span data-ttu-id="aff82-1560">Microsoft Graph を使用してスマートに作業</span><span class="sxs-lookup"><span data-stu-id="aff82-1560">Get smart with Microsoft Graph</span></span>

<span data-ttu-id="aff82-1561">インテリジェントなテクノロジを使用して、インテリジェントなデータをインポートしたり、またはデータにリンクしたりして、デスクトップ データベースを作り変えましょう。</span><span class="sxs-lookup"><span data-stu-id="aff82-1561">Import or link to intelligent data and reinvent your desktop database with Intelligent Technology.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="aff82-1562">主な修正:</span><span class="sxs-lookup"><span data-stu-id="aff82-1562">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="aff82-1563">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="aff82-1563">All Applications</span></span>
 - <span data-ttu-id="aff82-1564">一部のユーザーがクラウドの場所にファイルを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1564">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="aff82-1565">リボンから間違ったウィンドウが開く問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1565">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1566">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1566">Word</span></span> 
- <span data-ttu-id="aff82-1567">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1567">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1568">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1568">Excel</span></span>
- <span data-ttu-id="aff82-1569">リンクされたデータ型を含まないブックであるにもかかわらず、リンクされたデータ型に対するエラーメッセージが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1569">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="aff82-1570">Word 文書内のリンクの URL がオンラインとローカルで表示したときに変更される可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1570">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1571">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1571">PowerPoint</span></span>
- <span data-ttu-id="aff82-1572">[アニメーション] タブで変更を元に戻すと、PowerPoint がクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1572">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1573">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1573">Outlook</span></span>
- <span data-ttu-id="aff82-1574">一部のユーザーがパブリック フォルダー内の連絡先の [メモ] フィールドを変更できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1574">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="aff82-1575">失効日と削除日の間に競合が発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1575">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1576">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1576">Access</span></span>
- <span data-ttu-id="aff82-1577">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1577">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="aff82-1578">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1578">Project</span></span>
- <span data-ttu-id="aff82-1579">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1579">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="aff82-1580">2019年4月5日</span><span class="sxs-lookup"><span data-stu-id="aff82-1580">April 5, 2019</span></span>
<span data-ttu-id="aff82-1581">バージョン 1904 (ビルド 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="aff82-1581">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="aff82-1582">新機能:</span><span class="sxs-lookup"><span data-stu-id="aff82-1582">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1583">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1583">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="aff82-1584">Windows 用の Outlook: 優先受信トレイの設定を設定して共有します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1584">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="aff82-1585">優先受信トレイの設定はクラウドに保存されるため、どのコンピューターで Web 上の Outlook for Windows と Outlook を使用しても同じように一貫したエクスペリエンスを楽しめます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1585">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="aff82-1586">利用するには:</span><span class="sxs-lookup"><span data-stu-id="aff82-1586">Getting Started:</span></span>

<span data-ttu-id="aff82-1587">[ファイル]、[オプション]、[全般] の順に移動すると、[Outlook の設定をクラウドに保存する] という新しい設定があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-1587">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="aff82-1588">ユーザーは、自分の優先受信トレイの設定を他の Outlook Desktop インストールおよび OWA に移動できるようにするには、このチェック ボックスをオンにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-1588">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="aff82-1589">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="aff82-1589">Scenarios to Try:</span></span>

<span data-ttu-id="aff82-1590">クラウド設定の設定を有効にしているコンピューターで優先受信トレイを変更します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1590">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="aff82-1591">OWA に移動して、そこに適用されている設定も確認してください。</span><span class="sxs-lookup"><span data-stu-id="aff82-1591">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="aff82-1592">OWA で優先受信トレイを変更し、デスクトップ Outlook を起動して反映された優先順位を表示します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1592">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1593">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1593">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="aff82-1594">学習ツール モードでは、より多くのページの色が追加でサポートされます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1594">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="aff82-1595">Word の学習ツールは、より多くのページ テーマ色を追加し、ページの背景色を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1595">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="aff82-1596">すべて白またはすべて黒の背景だと読みにくいと感じるユーザーが多かったため、PC と Mac の Word で色の選択肢を拡大しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1596">Many people have challenges reading with an all-white or all-black background, so we've expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="aff82-1597">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="aff82-1597">Getting Started:</span></span>

<span data-ttu-id="aff82-1598">この操作を行うには、[表示] タブに移動し、[学習ツール]、[ページの色] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1598">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="aff82-1599">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="aff82-1599">Scenarios to Try:</span></span>

<span data-ttu-id="aff82-1600">この操作を行うには、[表示] タブに移動し、[学習ツール]、[ページの色] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1600">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1601">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1601">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="aff82-1602">3D アニメーション モデルで創造性を高める</span><span class="sxs-lookup"><span data-stu-id="aff82-1602">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="aff82-1603">Office では、アニメーションモデルをサポートするようになりました。エディターで再生するので、シートを活用することができます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1603">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="aff82-1604">利用するには:</span><span class="sxs-lookup"><span data-stu-id="aff82-1604">Getting Started:</span></span>

1. <span data-ttu-id="aff82-1605">Excel を開く</span><span class="sxs-lookup"><span data-stu-id="aff82-1605">Open Excel</span></span>
2. <span data-ttu-id="aff82-1606">3D アニメーション モデルを挿入します (まもなく Remix が公開されますが、今はここでアニメーション モデルにアクセスしてください: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="aff82-1606">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="aff82-1607">アニメーション モデルがエディターで再生されるようになります。</span><span class="sxs-lookup"><span data-stu-id="aff82-1607">The animated model will play in the editor!</span></span> <span data-ttu-id="aff82-1608">スライドショー モードも再生されるようになりますので、確認してください。</span><span class="sxs-lookup"><span data-stu-id="aff82-1608">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="aff82-1609">[3D 形式] リボンで、モデル内の他のアニメーション シーンを探索する</span><span class="sxs-lookup"><span data-stu-id="aff82-1609">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="aff82-1610">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="aff82-1610">Scenarios to Try:</span></span>

1. <span data-ttu-id="aff82-1611">アニメーション モデルを挿入し、エディターで再生します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1611">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="aff82-1612">アニメーション化されたモデルで使用できるアニメーション シーンについては、シーン ギャラリー ([3D 書式] リボンから利用できます) を参照してください。</span><span class="sxs-lookup"><span data-stu-id="aff82-1612">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="aff82-1613">リボン、フローティング ツール バーまたはスペースバーを介してアニメーションを簡単に再生および一時停止することができます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1613">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="aff82-1614">主な修正:</span><span class="sxs-lookup"><span data-stu-id="aff82-1614">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="aff82-1615">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="aff82-1615">All Applications</span></span>
- <span data-ttu-id="aff82-1616">Excel の間違ったアプリ アイコンがコンテキストメニューに表示されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1616">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="aff82-1617">アップデートをインストールした後に [ファイル メニュー] ボタンが消えてしまうことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1617">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="aff82-1618">ユーザー ライセンスに変更をおよぼす可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1618">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1619">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1619">Word</span></span> 
- <span data-ttu-id="aff82-1620">特定のズーム レベルでテキストが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1620">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1621">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1621">Excel</span></span>
- <span data-ttu-id="aff82-1622">編集後に、ブックを保存するかどうかを確認するメッセージが表示されない問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="aff82-1622">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="aff82-1623">ユーザーがブックを共有している場合に BeforeSave イベントが開始しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1623">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="aff82-1624">列のサイズを 6 ピクセル未満に変更すると誤ったエラーメッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1624">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="aff82-1625">Excel が Application.Visible フラグを無視する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1625">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="aff82-1626">トレースの矢印がアクティブでない固定ウィンドウに残る問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1626">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="aff82-1627">ブックを開くときに通貨の日付のセルの書式設定が変わることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1627">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="aff82-1628">ツールヒントが突然移動する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1628">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="aff82-1629">Power Query エディターのローカライズの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1629">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="aff82-1630">ブックを添付ファイルとしてメールで送信するときにブックが削除される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1630">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1631">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1631">PowerPoint</span></span>
- <span data-ttu-id="aff82-1632">図形のコピーに通常以上に時間がかかる問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="aff82-1632">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1633">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1633">Outlook</span></span>
- <span data-ttu-id="aff82-1634">描画ツールの使用中に Outlook がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1634">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="aff82-1635">HTML メールを作成する際のローカライズの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1635">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="aff82-1636">下側のウィンドウが選択しにくい問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1636">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1637">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1637">Access</span></span>
- <span data-ttu-id="aff82-1638">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1638">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="aff82-1639">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1639">Project</span></span>
- <span data-ttu-id="aff82-1640">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1640">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="aff82-1641">2019 年 3 月 22 日</span><span class="sxs-lookup"><span data-stu-id="aff82-1641">March 22, 2019</span></span>
<span data-ttu-id="aff82-1642">バージョン 1904 (ビルド 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="aff82-1642">Version 1904 (build 11514.20004)</span></span>

## <a name="new-features"></a><span data-ttu-id="aff82-1643">新機能</span><span class="sxs-lookup"><span data-stu-id="aff82-1643">New Features</span></span>

- <span data-ttu-id="aff82-1644">**プライバシー制御**: 診断データとコネクテッド エクスペリエンス用に新しく更新されて、改善された制御。</span><span class="sxs-lookup"><span data-stu-id="aff82-1644">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> <span data-ttu-id="aff82-1645">詳細 <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span><span class="sxs-lookup"><span data-stu-id="aff82-1645">Learn more <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span></span>

- <span data-ttu-id="aff82-1646">**新しい外観を備えた Office のアイコン:** シンプルかつ高性能で、インテリジェントな Office のエクスペリエンスを反映するように、Office のアイコンがリニューアルされました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1646">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="aff82-1647">主な修正:</span><span class="sxs-lookup"><span data-stu-id="aff82-1647">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1648">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1648">Word</span></span> 
- <span data-ttu-id="aff82-1649">UI に常に "変更を確認しています" と表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1649">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1650">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1650">Excel</span></span>
- <span data-ttu-id="aff82-1651">ワークシートを移動した後にアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1651">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="aff82-1652">PDF 形式で保存した後にアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1652">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="aff82-1653">保存ダイアログで韓国語の文字を使用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1653">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1654">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1654">PowerPoint</span></span>
- <span data-ttu-id="aff82-1655">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1655">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1656">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1656">Outlook</span></span>
- <span data-ttu-id="aff82-1657">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1657">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1658">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1658">Access</span></span>
- <span data-ttu-id="aff82-1659">Access で余計なショートカットが作成されるという問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1659">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="aff82-1660">リンクされた SharePoint のデータが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1660">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="aff82-1661">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1661">Project</span></span>
- <span data-ttu-id="aff82-1662">言語設定が中国語から英語に変わる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1662">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="aff82-1663">SharePoint に同期するとアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1663">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="aff82-1664">2019 年 3 月 15 日</span><span class="sxs-lookup"><span data-stu-id="aff82-1664">March 15, 2019</span></span>
<span data-ttu-id="aff82-1665">バージョン 1904 (ビルド 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="aff82-1665">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="aff82-1666">新機能:</span><span class="sxs-lookup"><span data-stu-id="aff82-1666">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1667">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1667">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="aff82-1668">フォーカス モード</span><span class="sxs-lookup"><span data-stu-id="aff82-1668">Focus Mode</span></span>

<span data-ttu-id="aff82-1669">気を散らさずに作業に集中するには、[表示]メニューの[フォーカス]に切り替えます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1669">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="aff82-1670">Office 365 サブスクリプションが必要です。</span><span class="sxs-lookup"><span data-stu-id="aff82-1670">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="aff82-1671">利用するには:</span><span class="sxs-lookup"><span data-stu-id="aff82-1671">Getting Started:</span></span>

<span data-ttu-id="aff82-1672">リボンのステータス バー [フォーカス] ボタンの [フォーカス] ボタンをタブして表示</span><span class="sxs-lookup"><span data-stu-id="aff82-1672">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="aff82-1673">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="aff82-1673">Scenarios to Try:</span></span>

<span data-ttu-id="aff82-1674">フォーカス モードにしてフォーカス エクスペリエンスを経験する</span><span class="sxs-lookup"><span data-stu-id="aff82-1674">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="aff82-1675">主な修正:</span><span class="sxs-lookup"><span data-stu-id="aff82-1675">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1676">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1676">Word</span></span> 
- <span data-ttu-id="aff82-1677">PDF として保存した文書の画像に間違った DPI が設定される問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1677">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1678">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1678">Excel</span></span>
- <span data-ttu-id="aff82-1679">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1679">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1680">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1680">PowerPoint</span></span>
- <span data-ttu-id="aff82-1681">コメント ウィンドウが正しく開閉しない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1681">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="aff82-1682">動画を削除するとアプリケーションがクラッシュする可能性がある問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1682">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="aff82-1683">アプリケーションの一部のインスタンスを起動できない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1683">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1684">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1684">Outlook</span></span>
- <span data-ttu-id="aff82-1685">日本語で表示するとき、開封確認が正しく表示されない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1685">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1686">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1686">Access</span></span>
- <span data-ttu-id="aff82-1687">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1687">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="aff82-1688">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1688">Project</span></span>
- <span data-ttu-id="aff82-1689">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1689">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="aff82-1690">2019 年 3 月 8 日</span><span class="sxs-lookup"><span data-stu-id="aff82-1690">March 8, 2019</span></span> 
<span data-ttu-id="aff82-1691">バージョン 1903 (ビルド 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="aff82-1691">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="aff82-1692">新機能:</span><span class="sxs-lookup"><span data-stu-id="aff82-1692">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1693">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1693">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="aff82-1694">探している情報を Microsoft Search で検索する</span><span class="sxs-lookup"><span data-stu-id="aff82-1694">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="aff82-1695">Microsoft Search を使用して、作業を完了するのに必要なすべてのファイル、操作、連絡先、ヘルプを検索することができます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1695">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="aff82-1696">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="aff82-1696">Getting Started:</span></span>

- <span data-ttu-id="aff82-1697">この機能は、ヘッダーの UI の上部に目立つように表示されています。</span><span class="sxs-lookup"><span data-stu-id="aff82-1697">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="aff82-1698">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="aff82-1698">Scenarios to Try:</span></span>

- <span data-ttu-id="aff82-1699">大学、最近使用したドキュメント、最もよく使用するリボン コマンドなどを検索する</span><span class="sxs-lookup"><span data-stu-id="aff82-1699">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="aff82-1700">トピックや話題を検索して、その詳細情報を取得する</span><span class="sxs-lookup"><span data-stu-id="aff82-1700">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="aff82-1701">共同編集</span><span class="sxs-lookup"><span data-stu-id="aff82-1701">CoAuthoring</span></span>

<span data-ttu-id="aff82-1702">マクロの文書を編集できない状況にうんざりしていませんか?</span><span class="sxs-lookup"><span data-stu-id="aff82-1702">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="aff82-1703">これで OneDrive for Business 上の docm ファイルで複数の作成者による同時編集が可能になります。</span><span class="sxs-lookup"><span data-stu-id="aff82-1703">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="aff82-1704">利用するには:</span><span class="sxs-lookup"><span data-stu-id="aff82-1704">Getting Started:</span></span>

<span data-ttu-id="aff82-1705">ユーザーは、この機能にアクセスするために UI のボタンを押す必要はありません。</span><span class="sxs-lookup"><span data-stu-id="aff82-1705">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="aff82-1706">OneDrive for Business の docm ファイルでは、既定で有効になっています。</span><span class="sxs-lookup"><span data-stu-id="aff82-1706">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="aff82-1707">したがって、試すには、ユーザーが docm ファイルを OneDrive for Business に保存しておく必要があります。</span><span class="sxs-lookup"><span data-stu-id="aff82-1707">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="aff82-1708">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="aff82-1708">Scenarios to Try:</span></span>

<span data-ttu-id="aff82-1709">OneDrive for Business で docm ファイルを作成し、同僚と共有して共同作業を行います。</span><span class="sxs-lookup"><span data-stu-id="aff82-1709">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="aff82-1710">主な修正:</span><span class="sxs-lookup"><span data-stu-id="aff82-1710">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1711">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1711">Word</span></span> 
- <span data-ttu-id="aff82-1712">オプションの表示中に 'Esc' キーを押すと発生するクラッシュの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1712">We fixed a crashing issue that occurred when pressing 'ESC' while in Options</span></span>
- <span data-ttu-id="aff82-1713">コメントに返信するときにクラッシュが発生するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1713">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="aff82-1714">Word から PowerPoint Online へのコピーと貼り付けで発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1714">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1715">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1715">Excel</span></span>
- <span data-ttu-id="aff82-1716">保護されたドキュメントや編集可能なドキュメントを開いているときに Excel でセルをコピーすると CPU 使用率が高くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1716">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1717">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1717">PowerPoint</span></span>
- <span data-ttu-id="aff82-1718">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1718">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1719">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1719">Outlook</span></span>
- <span data-ttu-id="aff82-1720">Outlook Search が選択した日付の並べ替えを使用しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1720">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="aff82-1721">"このタスクを開く" ワークフロー リボンのボタンが特定のメールで応答しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1721">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="aff82-1722">ユーザーが Outlook の会議室の検索で空いている会議室を選択した後、社内の会議室がクリアされなくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1722">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1723">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1723">Access</span></span>
- <span data-ttu-id="aff82-1724">ダーク テーマで白い背景に白いテキストが表示されていた、保存済みのインポート/エクスポートのダイアログを修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1724">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="aff82-1725">表のデザインのテキストボックスに [Yes/No] フィールドの DisplayControl プロパティを設定できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1725">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="aff82-1726">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1726">Project</span></span>
- <span data-ttu-id="aff82-1727">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1727">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="aff82-1728">2019 年 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="aff82-1728">March 1, 2019</span></span> 
<span data-ttu-id="aff82-1729">バージョン 1903 (ビルド 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="aff82-1729">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="aff82-1730">新機能</span><span class="sxs-lookup"><span data-stu-id="aff82-1730">What's New</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1731">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1731">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="aff82-1732">色の変更履歴、コメントとリアルタイムの共同作業の同期</span><span class="sxs-lookup"><span data-stu-id="aff82-1732">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="aff82-1733">当社の製品での、コメント、変更履歴と共同作業者のカーソルが同じ色で表示されることについての修正箇所を確認しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1733">Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="aff82-1734">利用するには:</span><span class="sxs-lookup"><span data-stu-id="aff82-1734">Getting Started:</span></span>

<span data-ttu-id="aff82-1735">他のユーザーが開いている SharePoint または OneDrive のドキュメントを開きます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1735">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="aff82-1736">ユーザーの変更履歴とコメントの色が、ユーザーのカーソルの色と一致することを確認します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1736">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="aff82-1737">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="aff82-1737">Scenarios to Try:</span></span>

<span data-ttu-id="aff82-1738">他のユーザーが開いている SharePoint または OneDrive のドキュメントを開きます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1738">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="aff82-1739">ユーザーの変更履歴とコメントの色が、ユーザーのカーソルの色と一致することを確認します。</span><span class="sxs-lookup"><span data-stu-id="aff82-1739">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="aff82-1740">主な修正:</span><span class="sxs-lookup"><span data-stu-id="aff82-1740">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1741">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1741">Word</span></span> 
- <span data-ttu-id="aff82-1742">オプションの表示中に 'Esc' キーを押すと発生するクラッシュの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1742">We fixed a crashing issue that occurred when pressing 'ESC' while in Options</span></span>
- <span data-ttu-id="aff82-1743">Word から PowerPoint Online へのコピーと貼り付けで発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1743">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1744">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1744">Excel</span></span>
- <span data-ttu-id="aff82-1745">保護されたドキュメントや編集可能なドキュメントを開いているときに Excel でセルをコピーすると CPU 使用率が高くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1745">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1746">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1746">PowerPoint</span></span>
- <span data-ttu-id="aff82-1747">PowerPoint で @メンションを使用するときのスライド イメージのサイズに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1747">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1748">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1748">Outlook</span></span>
- <span data-ttu-id="aff82-1749">Outlook Search が選択した日付の並べ替えを使用しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1749">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="aff82-1750">"このタスクを開く" ワークフロー リボンのボタンが特定のメールで応答しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1750">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="aff82-1751">ユーザーが Outlook の会議室の検索で空いている会議室を選択した後、社内の会議室がクリアされなくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1751">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1752">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1752">Access</span></span>
- <span data-ttu-id="aff82-1753">テーブルとデータソースの再リンクを確認するときに表示されるメッセージを更新しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1753">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="aff82-1754">ダーク テーマで白い背景に白いテキストが表示されていた、保存済みのインポート/エクスポートのダイアログを修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1754">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="aff82-1755">表のデザインのテキストボックスに [Yes/No] フィールドの表示コントロール プロパティを設定できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1755">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="aff82-1756">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1756">Project</span></span>
- <span data-ttu-id="aff82-1757">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1757">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="aff82-1758">2019 年 2 月 15 日</span><span class="sxs-lookup"><span data-stu-id="aff82-1758">February 15, 2019</span></span> 
<span data-ttu-id="aff82-1759">バージョン 1903 (ビルド 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="aff82-1759">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="aff82-1760">新機能:</span><span class="sxs-lookup"><span data-stu-id="aff82-1760">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1761">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1761">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="aff82-1762">画面切り替え効果の機能強化 - 名前で変形</span><span class="sxs-lookup"><span data-stu-id="aff82-1762">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="aff82-1763">変形する図形を指定します</span><span class="sxs-lookup"><span data-stu-id="aff82-1763">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="aff82-1764">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="aff82-1764">Getting Started:</span></span>

- <span data-ttu-id="aff82-1765">[変形] で 2 つのオブジェクトを同じオブジェクトとして扱うために、[選択] ウィンドウを使って図形の名前を変更することができます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1765">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="aff82-1766">[変形] で名前を使って既定のマッチング動作を上書きするには、</span><span class="sxs-lookup"><span data-stu-id="aff82-1766">The name must be prefaced with "!!"</span></span> <span data-ttu-id="aff82-1767">名前の前に "!!" (2 つの感嘆符) を付ける必要があります (例: "!!Name")。</span><span class="sxs-lookup"><span data-stu-id="aff82-1767">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. "!!Name"</span></span>
- <span data-ttu-id="aff82-1768">ユーザーは、名前の先頭に "!!" が付いていない図形の名前変更を続行することができます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1768">Users can continue to rename shapes with any name that doesn't start with "!!"</span></span> <span data-ttu-id="aff82-1769">[変形] の動作が変更されることを気にする必要はありません</span><span class="sxs-lookup"><span data-stu-id="aff82-1769">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="aff82-1770">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="aff82-1770">Scenarios to Try:</span></span>

- <span data-ttu-id="aff82-1771">スライドに図形 (たとえば、四角形) を挿入します</span><span class="sxs-lookup"><span data-stu-id="aff82-1771">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="aff82-1772">新しいスライドを作成します</span><span class="sxs-lookup"><span data-stu-id="aff82-1772">Create a new slide</span></span>
- <span data-ttu-id="aff82-1773">2 枚目のスライドに別の図形 (たとえば、三角形) を挿入します</span><span class="sxs-lookup"><span data-stu-id="aff82-1773">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="aff82-1774">[オブジェクトの選択と表示] でスライド 1 の四角形の名前を "!!shape" に変更し、スライド 2 の三角形の名前を "!!shape" に変更します</span><span class="sxs-lookup"><span data-stu-id="aff82-1774">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="aff82-1775">2 枚目のスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="aff82-1775">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="aff82-1776">画面切り替え効果の機能強化 - SmartArt</span><span class="sxs-lookup"><span data-stu-id="aff82-1776">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="aff82-1777">SmartArt の変形をより滑らかに切り替え</span><span class="sxs-lookup"><span data-stu-id="aff82-1777">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="aff82-1778">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="aff82-1778">Getting Started:</span></span>

<span data-ttu-id="aff82-1779">SmartArt と同様の方法で変形を使用します</span><span class="sxs-lookup"><span data-stu-id="aff82-1779">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="aff82-1780">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="aff82-1780">Scenarios to Try:</span></span>

- <span data-ttu-id="aff82-1781">スライドに SmartArt を挿入します</span><span class="sxs-lookup"><span data-stu-id="aff82-1781">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="aff82-1782">スライドを複製します</span><span class="sxs-lookup"><span data-stu-id="aff82-1782">Duplicate the Slide</span></span>
- <span data-ttu-id="aff82-1783">複製されたスライド上で SmartArt のサイズ変更/変更/移動を行います</span><span class="sxs-lookup"><span data-stu-id="aff82-1783">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="aff82-1784">複製されたスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="aff82-1784">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="aff82-1785">画面切り替え効果の機能強化 - 表</span><span class="sxs-lookup"><span data-stu-id="aff82-1785">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="aff82-1786">表の変形をより滑らかに切り替え</span><span class="sxs-lookup"><span data-stu-id="aff82-1786">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="aff82-1787">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="aff82-1787">Getting Started:</span></span>
<span data-ttu-id="aff82-1788">表と同様の方法で変形を使用します</span><span class="sxs-lookup"><span data-stu-id="aff82-1788">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="aff82-1789">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="aff82-1789">Scenarios to Try:</span></span>

- <span data-ttu-id="aff82-1790">スライドに表を挿入します</span><span class="sxs-lookup"><span data-stu-id="aff82-1790">Insert a Table in a slide</span></span>
- <span data-ttu-id="aff82-1791">スライドを複製します</span><span class="sxs-lookup"><span data-stu-id="aff82-1791">Duplicate the slide</span></span>
- <span data-ttu-id="aff82-1792">複製されたスライド上で表のサイズ変更/変更/移動を行います</span><span class="sxs-lookup"><span data-stu-id="aff82-1792">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="aff82-1793">複製されたスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="aff82-1793">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="aff82-1794">Word、Excel、PowerPoint、OneNote、Access、Project、Publisher、Visio</span><span class="sxs-lookup"><span data-stu-id="aff82-1794">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="aff82-1795">アカウントをシームレスに切り替える</span><span class="sxs-lookup"><span data-stu-id="aff82-1795">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="aff82-1796">新しいアカウント マネージャーでは、仕事用アカウントと個人用アカウントのすべてが 1 か所に表示されます。また、アカウントを自由に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="aff82-1796">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="aff82-1797">この更新されたエクスペリエンスでは、ログイン方法がわかりやすくなりました。また、先にサインアウトしたり複雑なダイアログを操作したりする必要なく、仕事用アカウントと個人用アカウントを切り替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1797">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="aff82-1799">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="aff82-1799">Scenarios to Try:</span></span>
- <span data-ttu-id="aff82-1800">アカウントを切り替えます</span><span class="sxs-lookup"><span data-stu-id="aff82-1800">Switch between accounts</span></span>
- <span data-ttu-id="aff82-1801">新しいアカウントを追加します [注: [ファイル]、[アカウント]、[接続済みサービス] の順に移動してから、仕事用アカウントに接続されている個人用サービス (またはその逆) を削除することができます]</span><span class="sxs-lookup"><span data-stu-id="aff82-1801">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="aff82-1802">アカウントからサインアウトします</span><span class="sxs-lookup"><span data-stu-id="aff82-1802">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="aff82-1803">主な修正:</span><span class="sxs-lookup"><span data-stu-id="aff82-1803">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1804">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1804">Word</span></span> 
- <span data-ttu-id="aff82-1805">表と画像のコンテキスト プレビューに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1805">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1806">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1806">Excel</span></span>
- <span data-ttu-id="aff82-1807">[黒] のテーマでオートフィルターの [検索] フィールドのテキストが白くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1807">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="aff82-1808">新しい Office アドインの同意の UI に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1808">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1809">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1809">PowerPoint</span></span>
- <span data-ttu-id="aff82-1810">ノート PC またはタブレットでスライドショーを表示すると、表示が自動的に拡大される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="aff82-1810">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1811">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1811">Outlook</span></span>
- <span data-ttu-id="aff82-1812">[OneNote に送る] ボタンの表示に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1812">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1813">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1813">Access</span></span>
- <span data-ttu-id="aff82-1814">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1814">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="aff82-1815">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1815">Project</span></span>
- <span data-ttu-id="aff82-1816">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1816">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="aff82-1817">2019 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="aff82-1817">February 11, 2019</span></span>
<span data-ttu-id="aff82-1818">バージョン 1903 (ビルド 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="aff82-1818">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="aff82-1819">主な修正:</span><span class="sxs-lookup"><span data-stu-id="aff82-1819">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1820">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1820">Word</span></span> 
- <span data-ttu-id="aff82-1821">一部のカスタマイズされたスタイルを Word Online に適用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1821">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="aff82-1822">Word のリッチ オブジェクトでのコンテキスト プレビューに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1822">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="aff82-1823">リストを貼り付けると Word がクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1823">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1824">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1824">Excel</span></span>
- <span data-ttu-id="aff82-1825">通貨記号がない場合に、数値の書式の後ろに追加されるスペースが表示されない問題を修正しました特殊文字</span><span class="sxs-lookup"><span data-stu-id="aff82-1825">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="aff82-1826">株価の自動検出に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1826">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1827">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1827">PowerPoint</span></span>
- <span data-ttu-id="aff82-1828">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1828">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1829">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1829">Outlook</span></span>
- <span data-ttu-id="aff82-1830">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1830">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1831">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1831">Access</span></span>
- <span data-ttu-id="aff82-1832">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1832">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="aff82-1833">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1833">Project</span></span>
- <span data-ttu-id="aff82-1834">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1834">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="aff82-1835">2019 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="aff82-1835">February 1, 2019</span></span> 
<span data-ttu-id="aff82-1836">バージョン 1902 (ビルド 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="aff82-1836">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="aff82-1837">主な修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1837">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="aff82-1838">Word</span><span class="sxs-lookup"><span data-stu-id="aff82-1838">Word</span></span> 
- <span data-ttu-id="aff82-1839">埋め込まれた Excel の表のセルのサイズ変更に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1839">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="aff82-1840">描画キャンバス内の図形のコピー/貼り付けの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1840">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="aff82-1841">Excel</span><span class="sxs-lookup"><span data-stu-id="aff82-1841">Excel</span></span>
- <span data-ttu-id="aff82-1842">Excel Web App からファイルを開く際の問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1842">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="aff82-1843">CSV ファイルを .XLSX として保存する際にファイル名のサイズが原因で失敗する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1843">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="aff82-1844">コンテキスト メニューのオプションの表示に関してコンテキスト メニューを修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1844">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="aff82-1845">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="aff82-1845">PowerPoint</span></span>
- <span data-ttu-id="aff82-1846">角かっこを入力するためにユーザーがキーボード ショートカット Ctrl+Alt+7 および Ctrl+Alt+8 を使用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1846">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="aff82-1847">ローカル ビデオを PowerPoint に挿入すると C ドライブのディスク領域が減ってしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1847">We fixed an issue where inserting a local video into the PPT would reduce the 'C' drive disk space</span></span>
- <span data-ttu-id="aff82-1848">一部のユーザーに表示されていなかった [Microsoft Stream に公開する] ボタンを修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1848">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="aff82-1849">Outlook</span><span class="sxs-lookup"><span data-stu-id="aff82-1849">Outlook</span></span>
- <span data-ttu-id="aff82-1850">カレンダーのタスク ビューでタスクの件名が正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1850">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="aff82-1851">Access</span><span class="sxs-lookup"><span data-stu-id="aff82-1851">Access</span></span>
- <span data-ttu-id="aff82-1852">グラフのスケーリングの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="aff82-1852">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="aff82-1853">Project</span><span class="sxs-lookup"><span data-stu-id="aff82-1853">Project</span></span>
- <span data-ttu-id="aff82-1854">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="aff82-1854">Various performance and stability fixes</span></span>
