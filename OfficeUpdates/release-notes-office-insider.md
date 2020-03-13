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
ms.openlocfilehash: 98f2ec2386cc214cbe5912d428b781610d953aca
ms.sourcegitcommit: 4be8cb98eca74452720348595f0b8cfeaba4cef8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/09/2020
ms.locfileid: "42568863"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="a8210-103">Office Insider のリリース ノート</span><span class="sxs-lookup"><span data-stu-id="a8210-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="a8210-104">この記事には、Windows デスクトップ向け Word、Excel、PowerPoint、Outlook、Access、Project の Insider ビルドのリリース ノートが含まれています。</span><span class="sxs-lookup"><span data-stu-id="a8210-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="a8210-105">Microsoft では、毎週、皆様にお知らせしたい魅力的な新機能、重要な修正プログラム、重大な問題に関する情報を提供しています。</span><span class="sxs-lookup"><span data-stu-id="a8210-105">Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="a8210-106">多くの場合、機能 (場合によっては修正プログラムも) は、特定の期間にわたって Insider にロールアウトされます。</span><span class="sxs-lookup"><span data-stu-id="a8210-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="a8210-107">これにより、Microsoft では、より広範な対象ユーザーに機能をリリースする前に、作業がスムーズに行われていることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="a8210-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="a8210-108">以下に示すものが表示されない場合でも、最終的には入手できますのでご安心ください。</span><span class="sxs-lookup"><span data-stu-id="a8210-108">So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="a8210-109">リリース ノートは毎週投稿され、場合により複数のビルドのコンパイルになります。</span><span class="sxs-lookup"><span data-stu-id="a8210-109">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="a8210-110">リリースノートの発行日は実際のビルドのリリース日と一致しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-110">The release notes publication date may not match the actual build release date.</span></span>
> - <span data-ttu-id="a8210-111">Microsoft Teams に関連する既存の Office 365 ProPlus のインストール - 6 月の下旬から、これらの更新プログラムのインストール時に、Microsoft Teams が既存の Office 365 ProPlus (Office 365 Business) のインストールの中に含められます。</span><span class="sxs-lookup"><span data-stu-id="a8210-111">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="a8210-112">Teams が追加される日にちは、使用している更新プログラム チャネルによって異なります。</span><span class="sxs-lookup"><span data-stu-id="a8210-112">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="a8210-113">追加情報については、「[Office 365 ProPlus と同時に Microsoft Teams を展開する](https://docs.microsoft.com/deployoffice/teams-install)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a8210-113">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install) for additional information.</span></span>

[//]: # (削除しないでください)

## <a name="version-2003-march-06"></a><span data-ttu-id="a8210-115">バージョン 2003: 3 月 6 日</span><span class="sxs-lookup"><span data-stu-id="a8210-115">Version 2003: March 06</span></span>
<span data-ttu-id="a8210-116">*バージョン 2003 (ビルド 12624.20086)*</span><span class="sxs-lookup"><span data-stu-id="a8210-116">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="a8210-118">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="a8210-118">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a8210-119">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-119">Outlook</span></span>

- <span data-ttu-id="a8210-120">Outlook Web Access を使用してルールを作成しても Exchange サーバーに保存されず競合が発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-120">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="a8210-121">ダーク モードの Outlook の [差出人] フィールドにドロップダウン リストが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-121">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="a8210-122">ファイルが別のアプリケーションで開かれているときに、ユーザーがエクスプローラーでファイルをメール メッセージに添付できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-122">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-123">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-123">PowerPoint</span></span>

- <span data-ttu-id="a8210-124">サムネイルの上にマウスポインターを置くと推奨されるサムネイルが点滅する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-124">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="a8210-125">場合によっては、これにより PowerPoint がクラッシュしてしまう可能性があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-125">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="a8210-126">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-126">Word</span></span>

- <span data-ttu-id="a8210-127">編集用に保護されたドキュメントの比較機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-127">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a8210-128">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a8210-128">Office Suite</span></span>

- <span data-ttu-id="a8210-129">ユーザー プリンシパル名 (UPN) の大文字と小文字が区別されなくなり、SharePoint でファイルを操作するときにはエラーが少なくなるという Word/Excel/PowerPoint の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-129">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="a8210-130">機能に影響はないものの、[ファイル]、[オプション] の順で進んだ後のダイアログの [OK] ボタンが灰色で表示されていた外観上の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-130">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

## <a name="version-2003-february-28"></a><span data-ttu-id="a8210-133">バージョン 2003: 2 月 28 日</span><span class="sxs-lookup"><span data-stu-id="a8210-133">Version 2003: February 28</span></span>
<span data-ttu-id="a8210-134">*バージョン 2003 (ビルド 12619.20002)*</span><span class="sxs-lookup"><span data-stu-id="a8210-134">*Version 2003 (Build 12619.20002)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="a8210-136">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-136">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a8210-137">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-137">Outlook</span></span>

- <span data-ttu-id="a8210-138">**IT 管理者向けのインシデント通知:** Microsoft 365 テナントのグローバル管理者および Office Apps 管理者は、Outlook for Windows の新しい右側のパネル通知により、ユーザーに影響する Outlook および O365 Exchange インシデントについて通知されます。</span><span class="sxs-lookup"><span data-stu-id="a8210-138">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-139">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-139">PowerPoint</span></span>

- <span data-ttu-id="a8210-140">\*\*インクを図形に変換する作図エクスペリエンスの向上: \*\*より良い図を描いて変換し、Office オブジェクトを操作できるようにします。[詳細情報](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="a8210-140">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="a8210-143">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="a8210-143">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a8210-144">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-144">Excel</span></span>

- <span data-ttu-id="a8210-145">[印刷プレビュー] でスライサーのテキストが適切に拡大または縮小されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-145">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-146">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-146">Outlook</span></span>

- <span data-ttu-id="a8210-147">(メニューからではなく) ドラッグ アンド ドロップでメールに添付ファイルを追加したり、メールから添付ファイルを保存したりすると、ファイルの「最終更新日」が更新される問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="a8210-147">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="a8210-148">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-148">Word</span></span>

- <span data-ttu-id="a8210-149">コメント カードでタブすると、コメント編集ボックスにフォーカスが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-149">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="a8210-150">コントロール (テキスト コンテンツ コントロールなど) を数式に挿入し、ファイルを保存して開くと、読み取り不可能なコンテンツ エラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="a8210-150">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="a8210-151">以前にパスワードで保護されたファイルをクラウド ストレージに保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-151">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a8210-152">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a8210-152">Office Suite</span></span>

- <span data-ttu-id="a8210-153">同じ SharePoint ライブラリから Word/Excel/PowerPoint で複数のドキュメントが開かれている場合、最初に開いたドキュメントのみがポリシー コンプライアンスでスキャンされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-153">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-february-21"></a><span data-ttu-id="a8210-155">バージョン 2003: 2 月 21 日</span><span class="sxs-lookup"><span data-stu-id="a8210-155">Version 2003: February 21</span></span>
<span data-ttu-id="a8210-156">*バージョン 2003 (ビルド 12615.20000)*</span><span class="sxs-lookup"><span data-stu-id="a8210-156">*Version 2003 (Build 12615.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="a8210-158">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-158">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="a8210-159">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a8210-159">Office Suite</span></span>

- <span data-ttu-id="a8210-160">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキスト ハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="a8210-160">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="a8210-163">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="a8210-163">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-164">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-164">Excel</span></span>
- <span data-ttu-id="a8210-165">ピボット テーブルのメジャーの名前を変更するときにユーザーが経験する可能性のある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-165">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="a8210-166">VBA マクロを使用して範囲の内容をクリアするときにユーザーが経験する可能性のあるパフォーマンスの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-166">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="a8210-167">ユーザーがリボンを操作するマクロを実行したときに UI が点滅する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-167">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="a8210-168">ファイルの最初の単語が TABLE である場合に CSV ファイルが誤ってロードされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-168">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="a8210-169">ズーム レベルが異なる 2 つのブックを切り替える際にユーザーがクラッシュを経験する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-169">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-170">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-170">Outlook</span></span>
- <span data-ttu-id="a8210-171">Outlook を夜間に実行したままにしておくと、ユーザーがパブリック フォルダー メッセージを開けなくなる問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-171">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="a8210-172">Gmail アカウントを追加する認証ワークフロー中に、[アクセス許可] ページの [許可] および [拒否] ボタンが無効になる競合状態を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-172">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="a8210-173">一部のシナリオで、ログがオフになっている場合でも Outlook が予期せずログ出力を生成する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-173">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="a8210-174">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-174">Word</span></span>
- <span data-ttu-id="a8210-175">マウス ポインターをコメント カードの上に置いたときに、コメント カードが常に強調表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-175">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="a8210-176">アクティブなドキュメントの共同編集セッション中に、画像をコメント カードに直接追加すると、タグが追加されている場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-176">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="a8210-177">この問題は修正されています。</span><span class="sxs-lookup"><span data-stu-id="a8210-177">This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a8210-178">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a8210-178">Office Suite</span></span>
- <span data-ttu-id="a8210-179">Word/Excel/PowerPoint ドキュメントで Multichoice/Lookup/Managed-metadata プロパティを使用し、SharePoint ドキュメント ライブラリに保存する場合、これらのプロパティは以前は 255 文字に制限されていました。</span><span class="sxs-lookup"><span data-stu-id="a8210-179">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="a8210-180">これらのプロパティが 255 文字を超えると、そういったドキュメントは保存することができませんでした。</span><span class="sxs-lookup"><span data-stu-id="a8210-180">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="a8210-181">この変更により、この制限は 2048 文字に増加しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-181">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2003-february-14"></a><span data-ttu-id="a8210-183">バージョン 2003: 2 月 14 日</span><span class="sxs-lookup"><span data-stu-id="a8210-183">Version 2003: February 14</span></span>
<span data-ttu-id="a8210-184">*バージョン 2003 (ビルド 12607.20000)*</span><span class="sxs-lookup"><span data-stu-id="a8210-184">*Version 2003 (Build 12607.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="a8210-186">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-186">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a8210-187">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-187">Outlook</span></span>

- <span data-ttu-id="a8210-188">**キャプティブ WiFi ネットワークの新しいエクスペリエンス**: サインインに Web ページを必要とする WiFi ネットワークに参加したことはありませんか ?</span><span class="sxs-lookup"><span data-stu-id="a8210-188">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="a8210-189">Outlook はこれを検出し、接続を支援します。</span><span class="sxs-lookup"><span data-stu-id="a8210-189">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="a8210-190">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-190">Word</span></span>

- <span data-ttu-id="a8210-191">**描画ツールボックスでインク エディターを見つける**: [描画] を選択し、[インク エディター] ペンを選択して、指またはデジタル ペンでドキュメントを編集します。</span><span class="sxs-lookup"><span data-stu-id="a8210-191">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="a8210-192">詳細情報</span><span class="sxs-lookup"><span data-stu-id="a8210-192">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="a8210-193">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a8210-193">Office Suite</span></span>

- <span data-ttu-id="a8210-194">**明瞭になったステータス バー アイコン:** ステータス バーのアイコンが見やすくなりました</span><span class="sxs-lookup"><span data-stu-id="a8210-194">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="a8210-197">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="a8210-197">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a8210-198">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-198">Outlook</span></span>

- <span data-ttu-id="a8210-199">ユーザーが「空き時間情報オプション」予定表のアクセス許可ダイアログにアクセスできなくなる問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-199">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="a8210-200">異なるタイム ゾーンから送信された定期的な会議インスタンスを開くときに「申し訳ございません、このアイテムを開くことができません」というアラートが発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-200">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="a8210-201">メッセージから添付ファイルをドラッグ アンド ドロップした後、ユーザーが .msg ファイルを再度開くことができない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-201">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="a8210-202">Outlook から OneDrive に添付ファイルをアップロードした後、添付ファイルの名前にかっこが含まれているとファイル名が変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-202">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-203">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-203">PowerPoint</span></span>

- <span data-ttu-id="a8210-204">Excel グラフを含む PowerPoint または Word でドキュメントを保存できないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-204">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="a8210-205">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-205">Word</span></span>

- <span data-ttu-id="a8210-206">ドキュメントを PDF にエクスポートすると、画像の透明性が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-206">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-february-07"></a><span data-ttu-id="a8210-208">バージョン 2002: 2 月 7 日</span><span class="sxs-lookup"><span data-stu-id="a8210-208">Version 2002: February 07</span></span>
<span data-ttu-id="a8210-209">*バージョン 2002 (ビルド 12527.20040)*</span><span class="sxs-lookup"><span data-stu-id="a8210-209">*Version 2002 (Build 12527.20040)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="a8210-211">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-211">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="a8210-212">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-212">Access</span></span>

- <span data-ttu-id="a8210-213">**クエリ デザイナー、SQL ビュー、およびリレーションシップ ウィンドウでの作業効率の向上:** テーブルを右クリックして、テーブルを開き、デザインし、サイズを変更し、非表示にします。</span><span class="sxs-lookup"><span data-stu-id="a8210-213">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="a8210-214">SQL ビューでテキストを検索および置換します。</span><span class="sxs-lookup"><span data-stu-id="a8210-214">Search and replace text in SQL View.</span></span> <span data-ttu-id="a8210-215">リレーションシップ ウィンドウ内の複数のテーブルを選択します。</span><span class="sxs-lookup"><span data-stu-id="a8210-215">Select multiple tables in the Relationships window.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="a8210-218">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="a8210-218">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a8210-219">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-219">Access</span></span>

- <span data-ttu-id="a8210-220">この更新プログラムでは、ADODB を使用する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="a8210-220">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="a8210-221">VB コードのれコーター オブジェクトがエラーを誤って報告することがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-221">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="a8210-222">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="a8210-222">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-223">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-223">Excel</span></span>

- <span data-ttu-id="a8210-224">動的配列で [区切り位置] を使用すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-224">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-225">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-225">Outlook</span></span>

- <span data-ttu-id="a8210-226">月ビューで予定表をスクロールしても以前の予定表のイベントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-226">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="a8210-227">Citrix 環境で 30 件を超える予定表を表示したときにクラッシュする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="a8210-227">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-228">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-228">PowerPoint</span></span>

- <span data-ttu-id="a8210-229">ファイルを閉じた後、実行中のイベント ハンドラーがある場合、PowerPoint がファイルを Presentations コレクションからすぐに削除しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-229">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="a8210-230">したがって、オブジェクト モデルによって報告される開いているプレゼンテーションの数は正しくなく、PowerPoint のシャットダウンは防止されます。</span><span class="sxs-lookup"><span data-stu-id="a8210-230">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="a8210-231">蛍光ペンの問題を修正しました。暗い蛍光ペン色の白いテキストはグレースケールで黒として印刷されます。</span><span class="sxs-lookup"><span data-stu-id="a8210-231">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="a8210-232">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-232">Word</span></span>

- <span data-ttu-id="a8210-233">目次を更新してスクロールすると、ドキュメント上に灰色の領域が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-233">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="a8210-234">ドキュメントが共同編集されている場合、ルート コメントのドラフト バージョンが保持されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-234">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="a8210-235">コメント カード間を行き来すると、最初に選択されたコメントが選択の強調表示で表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-235">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="a8210-236">コメントが書き込まれたが投稿されず、ユーザーがファイルを保存しようとした場合、「参照」を使用してファイルを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-236">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="a8210-237">SlideTrack を有効にしてコメント ウィンドウを閉じると、Ctrl + Alt + M でコメント ウィンドウが開かない場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-237">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="a8210-238">@メンションをテーブルに追加すると、「このドキュメントのテーブルが破損しました」というエラー メッセージが生成される場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-238">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a8210-239">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a8210-239">Office Suite</span></span>

- <span data-ttu-id="a8210-240">Norway Nynorsk (nn-no) 校正ツール パッケージが正しくインストールされなかった場合がある問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="a8210-240">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-january-31"></a><span data-ttu-id="a8210-242">バージョン 2002: 1 月 31 日</span><span class="sxs-lookup"><span data-stu-id="a8210-242">Version 2002: January 31</span></span>
<span data-ttu-id="a8210-243">*バージョン 2002 (ビルド 12513.20010)*</span><span class="sxs-lookup"><span data-stu-id="a8210-243">*Version 2002 (Build 12513.20010)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="a8210-245">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-245">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8210-246">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-246">Excel</span></span>

- <span data-ttu-id="a8210-247">**すぐに読んで返信する**: ブックを開かずに、メールからコメントやメンションに直接返信します。</span><span class="sxs-lookup"><span data-stu-id="a8210-247">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="a8210-248">**クエリ エディターでのデータ プロファイリング**: 列のデータを一目で分析し、エラーと空の値を識別し、配布ヒストグラムなどを確認します。</span><span class="sxs-lookup"><span data-stu-id="a8210-248">**Data Profiling in Query Editor:** Get-a-glance analysis of the data in your columns, identify error and empty values, see distribution histograms and more.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="a8210-251">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="a8210-251">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a8210-252">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-252">Outlook</span></span>

- <span data-ttu-id="a8210-253">アイテム保持ポリシーに基づいて期限切れになるメールに 2 つのラベルが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-253">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="a8210-254">メールが 1 日で期限切れになることを示すものと、2 日で期限切れになることを示すものです。</span><span class="sxs-lookup"><span data-stu-id="a8210-254">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>

### <a name="word"></a><span data-ttu-id="a8210-255">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-255">Word</span></span>

- <span data-ttu-id="a8210-256">&quot;反転&quot;] ページ色の読み取りモードでコメントのヒントが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-256">Fixed an issue where comment hint was not visible in read mode with &quot;Inverse&quot; page color.</span></span>

- <span data-ttu-id="a8210-257">コメントを編集してテキストをイタリック体し、投稿した後にイタリック体の書式設定が失われる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-257">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>

- <span data-ttu-id="a8210-258">コメント コンテキスト メニューのコメント コマンド (コメントの編集、コメントへの返信、コメントの削除、コメントの解決) が表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-258">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-january-17"></a><span data-ttu-id="a8210-260">バージョン 2002: 1 月 17 日</span><span class="sxs-lookup"><span data-stu-id="a8210-260">Version 2002: January 17</span></span>
<span data-ttu-id="a8210-261">*バージョン 2002 (ビルド 12508.20000)*</span><span class="sxs-lookup"><span data-stu-id="a8210-261">*Version 2002 (Build 12508.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="a8210-263">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-263">Feature updates</span></span>
### <a name="word"></a><span data-ttu-id="a8210-264">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-264">Word</span></span>

- <span data-ttu-id="a8210-265">**メンションとコメントの通知メールにプレビューが含まれるようになりました:** メンションとコメントのメール通知には、コメント テキストのプレビューとそれが参照している内容のコンテキストが含まれるようになりました。</span><span class="sxs-lookup"><span data-stu-id="a8210-265">**Mention & comment notification emails now contain previews:** Email notifications for mentions & comments will now include previews of the comment text and context for what it is referring to.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="a8210-268">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="a8210-268">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a8210-269">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-269">Excel</span></span>

- <span data-ttu-id="a8210-270">アクセシビリティ チェックが図形の推奨事項を表示しないことがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-270">In some cases, the Accessibility checker would not show the recommendations for shapes.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-271">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-271">Outlook</span></span>

- <span data-ttu-id="a8210-272">左側のナビゲーション ウィンドウで [お気に入り] に保存したフォルダーが断続的に表示されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-272">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-273">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-273">PowerPoint</span></span>

- <span data-ttu-id="a8210-274">インクが PowerPoint のインク アニメーションで使用すると完全にレンダリングされない、またはスキップされることがある問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="a8210-274">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2001-january-10"></a><span data-ttu-id="a8210-276">バージョン 2001: 1 月 10 日</span><span class="sxs-lookup"><span data-stu-id="a8210-276">Version 2001: January 10</span></span>
<span data-ttu-id="a8210-277">*バージョン 2001 (ビルド 12430.20000)*</span><span class="sxs-lookup"><span data-stu-id="a8210-277">*Version 2001 (Build 12430.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="a8210-279">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-279">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8210-280">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-280">Excel</span></span>
- <span data-ttu-id="a8210-281">**図形を画像として保存する:** 簡単なクリック操作で図形、アイコン、その他のオブジェクトを画像ファイルとして保存し、別の場所で再利用することができます。</span><span class="sxs-lookup"><span data-stu-id="a8210-281">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="a8210-282">詳細情報</span><span class="sxs-lookup"><span data-stu-id="a8210-282">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

### <a name="outlook"></a><span data-ttu-id="a8210-283">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-283">Outlook</span></span>
- <span data-ttu-id="a8210-284">**Word、Excel、Outlook のオブジェクトを Windows 用の画像として保存できるようになりました。:** PowerPoint で既に提供されていたこの機能を使うとで、ユーザーは Word、Excel、Outlook 内のオブジェクトを画像として保存できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="a8210-284">**User can now save objects in Word/Excel/Outlook as a picture for Windows.:** With the ability already seen in PowerPoint, users can now save objects in Word, Excel and Outlook as a picture.</span></span> <span data-ttu-id="a8210-285">オブジェクトには、図形、アイコン、図などがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-285">Objects include shapes, icons, pictures, and more!</span></span> <span data-ttu-id="a8210-286">右クリックのメニューからアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="a8210-286">This can be accessed through the right-click menu.</span></span>

### <a name="word"></a><span data-ttu-id="a8210-287">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-287">Word</span></span>
- <span data-ttu-id="a8210-288">**周りに図形を描くだけで Word のインク描画を簡単に選択できます。:** [描画] タブのなげなわツールを使用することで、インクで描画されたオブジェクトを選択することができます。</span><span class="sxs-lookup"><span data-stu-id="a8210-288">**Easily select ink in Word by drawing a shape around it.:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="a8210-289">個別のストロークまたは文字全体を選択できます。</span><span class="sxs-lookup"><span data-stu-id="a8210-289">Select individual strokes, or whole words.</span></span> <span data-ttu-id="a8210-290">インク描画が多数ある場合に、その中の一部を操作したい場合に便利です。</span><span class="sxs-lookup"><span data-stu-id="a8210-290">It's handy when you have lots of ink and you only want to work with some of it.</span></span> [<span data-ttu-id="a8210-291">詳細情報</span><span class="sxs-lookup"><span data-stu-id="a8210-291">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="a8210-292">**図形を画像として保存する:** 簡単なクリック操作で図形、アイコン、その他のオブジェクトを画像ファイルとして保存し、別の場所で再利用することができます。</span><span class="sxs-lookup"><span data-stu-id="a8210-292">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="a8210-293">詳細情報</span><span class="sxs-lookup"><span data-stu-id="a8210-293">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="a8210-296">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="a8210-296">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="a8210-297">OneNote</span><span class="sxs-lookup"><span data-stu-id="a8210-297">OneNote</span></span>
- <span data-ttu-id="a8210-298">100% の解像度だと、ページ タブが小さすぎるためにくっついて表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-298">Page tabs may appear too small and close together at 100% resolution.</span></span>

### <a name="word"></a><span data-ttu-id="a8210-299">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-299">Word</span></span>
- <span data-ttu-id="a8210-300">コメントの数が多い場合、コメント一覧の末尾付近のコメントを削除すると、ウィンドウが一番上までスクロールされる場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-300">In a large set of comments, deleting a comment near the end of the list of comments may result in the pane scrolling all the way to the top.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2001-january-03"></a><span data-ttu-id="a8210-302">バージョン 2001: 1 月 3 日</span><span class="sxs-lookup"><span data-stu-id="a8210-302">Version 2001: January 03</span></span>
<span data-ttu-id="a8210-303">*バージョン 2001 (ビルド 12425.20000)*</span><span class="sxs-lookup"><span data-stu-id="a8210-303">*Version 2001 (Build 12425.20000)*</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="a8210-305">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="a8210-305">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-306">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-306">Excel</span></span>
- <span data-ttu-id="a8210-307">一部の罫線は A4 サイズ用紙に印刷されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-307">Some border lines may not print as expected on A4 size paper.</span></span>
- <span data-ttu-id="a8210-308">VBA を使用してシート上のグラフオブジェクトのヘッダーまたはフッターに画像を追加すると、エラーが発生することがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-308">Adding an image to the header/footer of a chart object on a sheet using VBA may result in an error.</span></span>
- <span data-ttu-id="a8210-309">グラフの軸を書式設定するときにラベルの間隔が 255 に制限されます。</span><span class="sxs-lookup"><span data-stu-id="a8210-309">When formatting a chart axis, the interval between labels was limited to 255.</span></span>
- <span data-ttu-id="a8210-310">データ ソースの URL が切り詰められている XML クエリを更新しようとするとエラーが発生するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-310">Fixed an issue where an error would occur trying to refresh an XML query in which the URL to the datasource was being truncated.</span></span>
- <span data-ttu-id="a8210-311">ブックの統計情報では、個人のマクロ ブックを含め、開いているすべてのブックからマクロの回数が報告されます。</span><span class="sxs-lookup"><span data-stu-id="a8210-311">Workbook Statistics would report a macro count from all open workbooks, including the personal macro workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-312">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-312">Outlook</span></span>
- <span data-ttu-id="a8210-313">フォルダーを切り替えると、メール リスト/メール プレビューに、しばらく白い「フラッシュ」が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-313">Switching folders may result in a brief white 'flash' in the mail list / mail preview.</span></span> <span data-ttu-id="a8210-314">この現象は、ダーク モードでより顕著になりました。</span><span class="sxs-lookup"><span data-stu-id="a8210-314">This behavior was more pronounced in dark mode.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-315">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-315">PowerPoint</span></span>
- <span data-ttu-id="a8210-316">Shape.Paste メソッドを呼び出すと貼り付けられた図形がフォーカスされるオブジェクトモデルの問題を修正しました。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="a8210-316">Fixed an Object Model issue where calling Shape.Paste method would result in the pasted shape receiving focus.&nbsp;</span></span>
- <span data-ttu-id="a8210-317">コピーと貼り付けシナリオの改善: &nbsp;PowerPoint スライドからプログラムによってコピーして、ループ内の別のスライドに貼り付けると、例外エラーが発生する場合があります。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="a8210-317">Improved a copy-paste scenario:&nbsp;Progamatically copying a shape from a PowerPoint slide and pasting it to another slide in a loop could fail with an exception error.&nbsp;</span></span>
- <span data-ttu-id="a8210-318">スライドのセクション ヘッダー内のアニメーションは、セクション ヘッダーを折りたたんで展開した後は、正しくレンダリングされません。</span><span class="sxs-lookup"><span data-stu-id="a8210-318">Animation in the section headers of slides would not render properly after collapsing and expanding section headers.</span></span>

### <a name="project"></a><span data-ttu-id="a8210-319">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-319">Project</span></span>
- <span data-ttu-id="a8210-320">文字列の折り返しが [タスク] ビュー と [リソース配分状況] ビューで機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-320">Fixed an issue where text wrapping wasn't working in the task and resource usage views.</span></span>
- <span data-ttu-id="a8210-321">リソースに複数の原価率がある場合、割り当ての原価価値が正しくない可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-321">Fixed an issue where if a resource has more than one cost rate, cost value on assignments may not be correct.</span></span>

### <a name="word"></a><span data-ttu-id="a8210-322">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-322">Word</span></span>
- <span data-ttu-id="a8210-323">コントロール (テキスト コンテンツ コントロールなど) を数式に挿入し、ファイルを保存して開くと、読み取り不可能なコンテンツ エラーが発生します。</span><span class="sxs-lookup"><span data-stu-id="a8210-323">Inserting a control (such as a Text Content Control) in an equation, then saving and opening the file would result in an un-readable content error.</span></span>
- <span data-ttu-id="a8210-324">共同編集時に、Word Online を使用して追加したコメントが Word デスクトップに表示されません。</span><span class="sxs-lookup"><span data-stu-id="a8210-324">When co-authoring, adding a comment using Word online may not appear in Word desktop.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a8210-325">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a8210-325">Office Suite</span></span>
- <span data-ttu-id="a8210-326">ライセンスを 1 つだけ使用してライセンスを変更しようとしたときに、有効なライセンスの有効期限が誤って表示されなくなりました。</span><span class="sxs-lookup"><span data-stu-id="a8210-326">Removed showing an erroneous expiry date of the valid license when trying to change license with only one license.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2001-december-13"></a><span data-ttu-id="a8210-328">バージョン 2001: 12 月 13 日</span><span class="sxs-lookup"><span data-stu-id="a8210-328">Version 2001: December 13</span></span>
<span data-ttu-id="a8210-329">*バージョン 2001 (ビルド 12410.20000)*</span><span class="sxs-lookup"><span data-stu-id="a8210-329">*Version 2001 (Build 12410.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="a8210-331">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-331">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a8210-332">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-332">Outlook</span></span>

- <span data-ttu-id="a8210-333">**所有しているグループにメールをドラッグ:** メッセージや会話を受信トレイからドラッグして移動し、コピーします。</span><span class="sxs-lookup"><span data-stu-id="a8210-333">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="a8210-334">ドラッグしたメッセージは、すべてのグループ メンバーと共有されます。</span><span class="sxs-lookup"><span data-stu-id="a8210-334">Messages you drag will be shared with all group members.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="a8210-337">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="a8210-337">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a8210-338">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-338">Access</span></span>
- <span data-ttu-id="a8210-339">リンクされた ODBC テーブルを参照し、Order By 句を含めるユニオン クエリを実行すると、64ビット版アクセスがクラッシュします。</span><span class="sxs-lookup"><span data-stu-id="a8210-339">Executing a union query that references linked ODBC table(s) and contains an Order By clause crashes 64 bit Access.</span></span>
- <span data-ttu-id="a8210-340">Access (O365) のユニオン クエリからデータを集計すると、10 進型データを切り捨ててしまうことがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-340">Summing of data from union queries in Access (O365) may result in truncation of decimal data.</span></span>
- <span data-ttu-id="a8210-341">ACE の COM インターフェイスは、Office アプリケーションの外部で使用することはできません。</span><span class="sxs-lookup"><span data-stu-id="a8210-341">COM Interfaces for ACE are not exposed for use outside of Office applications.</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-342">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-342">Excel</span></span>
- <span data-ttu-id="a8210-343">3D モデル (アニメーションまたはスタティック) を挿入し、[図として保存] を行おうとしても動作しません。</span><span class="sxs-lookup"><span data-stu-id="a8210-343">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>
- <span data-ttu-id="a8210-344">Backstage からフィードバックを開始するためのショートカットキー (Alt + Ctrl + 7/8) は、AZERTY キーボード (Alt - Gr + 7/8) と競合しています。</span><span class="sxs-lookup"><span data-stu-id="a8210-344">The shortkey (Alt+Ctrl + 7/8)  to launch feedback from backstage is in conflict with AZERTY keyboards (Alt-Gr + 7/8).</span></span> <span data-ttu-id="a8210-345">影響: ユーザーは次のような文字を使用できない場合があります'\'。</span><span class="sxs-lookup"><span data-stu-id="a8210-345">Impact: users may not be able to use some characters such as: '\'.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-346">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-346">Outlook</span></span>
- <span data-ttu-id="a8210-347">メールが受信者の間違ったアドレスに送信される原因となる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="a8210-347">Addresses an issue that caused email to be sent to the wrong address for the recipient.</span></span>
- <span data-ttu-id="a8210-348">Outlook でメールボックスへの &quot;読み取り&quot; アクセス権のあるユーザーに対して、メッセージの [既読/未読] 状態の変更を誤って許可する原因となる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="a8210-348">Addresses an issue that caused Outlook to incorrectly allow users with &quot;read&quot; access to a mailbox to change the read/unread state of a message.</span></span>
- <span data-ttu-id="a8210-349">Web サイト上のセキュリティ証明書を失効すると、製品サポートによって再度作成することはできません。</span><span class="sxs-lookup"><span data-stu-id="a8210-349">The revocation of the security certificate on the web site is not re-producible by Product Support.</span></span> <span data-ttu-id="a8210-350">この問題の根本原因を解決するには、ログを追加する必要があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-350">Logging needs to be added to help root cause the issue.</span></span>
- <span data-ttu-id="a8210-351">同期エラーが表示されてしまう問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="a8210-351">Addresses an issue that caused users to see synchronization failures.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-352">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-352">PowerPoint</span></span>
- <span data-ttu-id="a8210-353">3D モデル (アニメーションまたはスタティック) を挿入し、[図として保存] を行おうとしても動作しません。</span><span class="sxs-lookup"><span data-stu-id="a8210-353">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="project"></a><span data-ttu-id="a8210-354">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-354">Project</span></span>
- <span data-ttu-id="a8210-355">タスクの作業は、手動スケジュール タスクの Summary roll-up では計算されません。</span><span class="sxs-lookup"><span data-stu-id="a8210-355">Task work is not calculated in Summary roll-up for manually scheduled child tasks.</span></span>
- <span data-ttu-id="a8210-356">サーバーベースのプロジェクトを保存しようとすると、リボン ボタンから呼び出された Project VBA コードが機能しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-356">Project VBA Code invoked from a Ribbon button may not work when trying to save server-based Projects.</span></span>
- <span data-ttu-id="a8210-357">プロジェクトを実行していない場合は、SharePoint ドキュメント ライブラリからプロジェクト ファイルを開くとエラーが表示され、ファイルが開くことはできません。</span><span class="sxs-lookup"><span data-stu-id="a8210-357">Unless Project is already running, opening Project files from a SharePoint document library displays an error and the file will not open.</span></span>

### <a name="word"></a><span data-ttu-id="a8210-358">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-358">Word</span></span>
- <span data-ttu-id="a8210-359">既存のファイルの保存が出来ない場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-359">Saving existing files may not work.</span></span>
- <span data-ttu-id="a8210-360">[スペルチェックと文章校正] ウィンドウで方向キーを使用すると、断続的に画面がちらつくことがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-360">Using arrow keys in the Spelling and Grammar editor window may result in intermittent flickering.</span></span>
- <span data-ttu-id="a8210-361">フォローアップを解決するときに、関連するコメントはポイントのコメントに変換されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-361">When resolving a follow-up, associated comments may not convert to point comments.</span></span>
- <span data-ttu-id="a8210-362">3D モデル (アニメーションまたはスタティック) を挿入し、[図として保存] を行おうとしても動作しません。</span><span class="sxs-lookup"><span data-stu-id="a8210-362">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a8210-363">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a8210-363">Office Suite</span></span>
- <span data-ttu-id="a8210-364">Office の更新メッセージが、異なる言語で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-364">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="a8210-365">今後、Office の更新メッセージは Windows の表示言語と一致します。</span><span class="sxs-lookup"><span data-stu-id="a8210-365">Going forward, Office update messages will correctly match the Windows display language.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1912-december-06"></a><span data-ttu-id="a8210-367">バージョン 1912: 12 月 6 日</span><span class="sxs-lookup"><span data-stu-id="a8210-367">Version 1912: December 06</span></span>
<span data-ttu-id="a8210-368">*バージョン 1912 (ビルド 12325.20012)*</span><span class="sxs-lookup"><span data-stu-id="a8210-368">*Version 1912 (Build 12325.20012)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="a8210-370">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-370">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a8210-371">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-371">Outlook</span></span>

- <span data-ttu-id="a8210-372">**高度なグループ メールの設定:** この機能は、グループ ユーザーが受信トレイで受信/フォローするメールまたはイベントを、カスタマイズするのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="a8210-372">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="a8210-373">**グループの名前付けポリシー**: グループの名前付けポリシーを使用すると、IT 管理者は組織内のユーザーが作成するグループの名前の標準化と管理を行えます。</span><span class="sxs-lookup"><span data-stu-id="a8210-373">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="a8210-374">管理者は、グループが作成される際に特定のプレフィックスとサフィックスをグループ名に追加することを要求できます。また、特定の単語の使用を禁止できます。</span><span class="sxs-lookup"><span data-stu-id="a8210-374">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="a8210-375">これにより、グループ名での不適切な単語の使用を最小限に抑えられる他、ディレクトリ内のグループ名の記載を IT 管理者が管理できます。</span><span class="sxs-lookup"><span data-stu-id="a8210-375">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="a8210-376">また、名前付けポリシーを使用することで、チーム サイトを展開する組織は、チーム サイトを部署ごとに分類できるようにもなります。</span><span class="sxs-lookup"><span data-stu-id="a8210-376">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a8210-377">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a8210-377">Office Suite</span></span>

- <span data-ttu-id="a8210-378">**タブ付きのウィンドウ**: アプリの右側にあるタブ UI を使用して、複数のウィンドウ間を切り替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="a8210-378">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="a8210-379">UI は、2 つ以上のウィンドウが開かれている場合にのみ表示されます。</span><span class="sxs-lookup"><span data-stu-id="a8210-379">The UI will only be visible when you have 2+ panes open.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="a8210-382">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="a8210-382">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a8210-383">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-383">Excel</span></span>
- <span data-ttu-id="a8210-384">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-384">Users may encounter an error when saving changes while using some non-English character sets.</span></span>
- <span data-ttu-id="a8210-385">非表示の名前付き範囲にアクセスすると、ユーザーにエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-385">Users may encounter an error when accessing a hidden named range.</span></span>
- <span data-ttu-id="a8210-386">4K 解像度のハードウェアのグラフィック アクセラレータを無効にすると、スクロールしたときにセルのレンダリングが遅れる場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-386">Disabling hardware graphics acceleration with 4K resolution may result in delayed rendering of cells when scrolling around.</span></span>
- <span data-ttu-id="a8210-387">セルの境界に重なる長い数式をクリアしても、セルの境界を越えて表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-387">Clearing a long formula that overlaps a cell boundary may still display across the cell boundary.</span></span>
- <span data-ttu-id="a8210-388">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-388">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>
- <span data-ttu-id="a8210-389">余白のドロップダウン メニューが正しくレンダリングされない場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-389">Margin dropdown menu may not render correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="a8210-390">OneNote</span><span class="sxs-lookup"><span data-stu-id="a8210-390">OneNote</span></span>
- <span data-ttu-id="a8210-391">OneNote は、「会議ノート」の Outlook アドインを介して開かない場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-391">OneNote may not open via the 'Meeting Notes' Outlook add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-392">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-392">Outlook</span></span>
- <span data-ttu-id="a8210-393">保持ポリシーのラベルには、保持期間がかっこ内に表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-393">Retention policy labels may display the retention time period in parenthesis.</span></span>
- <span data-ttu-id="a8210-394">日本語パックの連絡先カードに空白が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-394">Blank spaces may appear in Contact cards with Japanese language pack.</span></span>
- <span data-ttu-id="a8210-395">Outlook のメール メッセージにインラインで挿入された画像のサイズが変更される場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-395">Images inserted inline to Outlook e-mail messages can sometimes get resized.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-396">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-396">PowerPoint</span></span>
- <span data-ttu-id="a8210-397">クラウド ファイル内のスライドに 2 つ以上の異なるビデオがある場合、ビデオの画像は正しく表示されますが、ユーザーがそれぞれのビデオを再生するためにクリックすると、同一の内容のビデオが再生されます。</span><span class="sxs-lookup"><span data-stu-id="a8210-397">If a user has two (or more) different videos on a slide in a cloud file, the video images are rendered correctly, but when the user clicks on each one to play, the video content is the same.</span></span>
- <span data-ttu-id="a8210-398">場合によっては、タッチ デバイスでのスクロールが機能しないことがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-398">In some cases, scrolling with touch devices will not work.</span></span>
- <span data-ttu-id="a8210-399">余白のドロップダウン メニューが正しくレンダリングされない場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-399">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="a8210-400">ある Office アプリケーションから別の Office アプリケーションへの安全なリンクは、リンクされたアプリケーションを起動しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-400">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="project"></a><span data-ttu-id="a8210-401">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-401">Project</span></span>
- <span data-ttu-id="a8210-402">[プロジェクトの比較] 機能を使用すると、Project がクラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-402">Project may crash when you use the Compare Projects feature.</span></span>
- <span data-ttu-id="a8210-403">ダーク モードの場合、リソースが過剰に割り当てられているタスクのタスク検査パネルに移動すると、表を読み取ることができません。</span><span class="sxs-lookup"><span data-stu-id="a8210-403">If you are in Dark mode, when you go to the task inspector panel on a task with an over allocated resource, you are unable to read the table.</span></span>
- <span data-ttu-id="a8210-404">割り当てのないタスクに作業を設定すると、1 日間に丸められます。</span><span class="sxs-lookup"><span data-stu-id="a8210-404">Setting effort on tasks that have no assignments are rounded to 1 day.</span></span>

### <a name="word"></a><span data-ttu-id="a8210-405">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-405">Word</span></span>
- <span data-ttu-id="a8210-406">差し込み印刷の実行後に、特定の条件下でファイルを保存できない場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-406">Saving a file after doing a mail merge may not work under certain conditions.</span></span>
- <span data-ttu-id="a8210-407">文書パーツ オーガナイザーに無効なアラートが表示される場合があります。&quot;スタイル、文書パーツを変更しました。&quot;</span><span class="sxs-lookup"><span data-stu-id="a8210-407">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>
- <span data-ttu-id="a8210-408">コピーと貼り付けを使用すると、コメント ウィンドウが再読み込みされることがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-408">Comment pane sometimes gets reloaded when using copy/paste.</span></span>
- <span data-ttu-id="a8210-409">コメントが正しい順序で貼り付けられない場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-409">Comments are sometimes not pasted in the correct order.</span></span>
- <span data-ttu-id="a8210-410">カスタム スタイルのマルチレベル リストで構成されるテンプレートを既存のドキュメントに適用すると、特定の条件下でスタイルが保持されない場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-410">Applying a template consisting of a multi-level list with custom styles to existing documents may not preserve the style under certain conditions.</span></span>
- <span data-ttu-id="a8210-411">分割画面の境界のサイズを変更すると、さらに分割画面が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-411">Resizing a split screen border may introduce an additional split screen.</span></span>
- <span data-ttu-id="a8210-412">余白のドロップダウン メニューが正しくレンダリングされない場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-412">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="a8210-413">コメント カードでユーザーをメンションすると、JSON が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-413">At-mentioning a user in a comment card may show JSON.</span></span>
- <span data-ttu-id="a8210-414">ある Office アプリケーションから別の Office アプリケーションへの安全なリンクは、リンクされたアプリケーションを起動しない場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-414">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a8210-415">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a8210-415">Office Suite</span></span>
- <span data-ttu-id="a8210-416">日本語ベースの製品の場合、アカウント ユーザーの姓と名が誤った順序で表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-416">For Japanese based products, account user first name, last name may appear in incorrect order.</span></span>
- <span data-ttu-id="a8210-417">コメントにマウス ポインターを合わせた際に、コメントの周りにテキストボックスのアウトラインが表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-417">Hovering a mouse pointer over comments may display a textbox outline around the comment.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1912-november-15"></a><span data-ttu-id="a8210-419">バージョン 1912: 11 月 15 日</span><span class="sxs-lookup"><span data-stu-id="a8210-419">Version 1912: November 15</span></span>
<span data-ttu-id="a8210-420">*バージョン 1912 (ビルド 12307.20000)*</span><span class="sxs-lookup"><span data-stu-id="a8210-420">*Version 1912 (Build 12307.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="a8210-422">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-422">Feature updates</span></span>
### <a name="insights-services"></a><span data-ttu-id="a8210-423">インサイト サービス</span><span class="sxs-lookup"><span data-stu-id="a8210-423">Insights Services</span></span>
- <span data-ttu-id="a8210-424">**Excel のアイデアの自然言語のクエリ:** データについて自然言語の質問をする Excel のアイデアの新機能。</span><span class="sxs-lookup"><span data-stu-id="a8210-424">**Natural Language Queries in Ideas in Excel:** Excel Ideas's new capability to ask a natural language question about your data.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="a8210-427">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="a8210-427">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a8210-428">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-428">Excel</span></span>
- <span data-ttu-id="a8210-429">一部のローカライズにおいて、[Text to Column] 機能が失敗することがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-429">Text to Column functionality may fail for some localizations.</span></span>
- <span data-ttu-id="a8210-430">セル内の動的配列数式を編集すると、セルの境界の外にテキストが並んでしまう場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-430">Editing dynamic array formulas within a cell may result in text being aligned outside of the boundary of the cell.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-431">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-431">Outlook</span></span>
- <span data-ttu-id="a8210-432">グループ ポリシーを使用して S/MIME 構成を適用する機能が追加されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-432">Added the ability to enforce S/MIME configuration via group policy.</span></span>
- <span data-ttu-id="a8210-433">思ったよりも埋め込み画像が小さく表示されることがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-433">Embedded images may appear smaller than expected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-434">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-434">PowerPoint</span></span>
- <span data-ttu-id="a8210-435">テキストからフォーカスを移動した後、カーソルが表示されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-435">Cursor may disappear after moving focus from text.</span></span>

### <a name="project"></a><span data-ttu-id="a8210-436">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-436">Project</span></span>
- <span data-ttu-id="a8210-437">ユーザーにライセンスに関するエラーが表示されることがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-437">Users may experience an error regarding licensing.</span></span>
- <span data-ttu-id="a8210-438">日付の選択の [今日] ボタンで正しくない日付が設定されることがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-438">The Today button in the date picker may sometimes set the incorrect date.</span></span>

### <a name="word"></a><span data-ttu-id="a8210-439">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-439">Word</span></span>
- <span data-ttu-id="a8210-440">右クリックすると、完全に一致する単語が選択されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-440">Right-clicking can sometimes not result in selecting the whole word.</span></span>
- <span data-ttu-id="a8210-441">提案されたファイル形式に変換した後、カーソルがオブジェクト内でアクティブのままになってしまうことがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-441">The cursor may remain active within an object after converting to a suggested format.</span></span>
- <span data-ttu-id="a8210-442">一部のシナリオでは、メッセージ内の画像が正しく拡大されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-442">Images in messages may be incorrectly scaled in some scenarios.</span></span>
- <span data-ttu-id="a8210-443">一部のテーマでは、どのコメントが選択されているかの判断が困難になることがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-443">Some themes may make it difficult to determine which comment is selected.</span></span>
- <span data-ttu-id="a8210-444">ウィンドウ スイッチャーで非表示のときに、コメントのヒントを選択すると最新のコメント ウィンドウが表示されるようになります。</span><span class="sxs-lookup"><span data-stu-id="a8210-444">Selecting a comment hint should now show the modern comments pane when hidden in pane switcher.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a8210-445">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a8210-445">Office Suite</span></span>
- <span data-ttu-id="a8210-446">コメントに返信すると、テキスト ボックスがウィンドウの端を超えて縦方向に展開されることがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-446">Replying to a comment may cause the textbox to expand vertically beyond the edge of the pane.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1912-november-08"></a><span data-ttu-id="a8210-448">バージョン 1912: 11 月 8 日</span><span class="sxs-lookup"><span data-stu-id="a8210-448">Version 1912: November 08</span></span>
<span data-ttu-id="a8210-449">*バージョン 1912 (ビルド 12231.20000)*</span><span class="sxs-lookup"><span data-stu-id="a8210-449">*Version 1912 (Build 12231.20000)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="a8210-451">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-451">Feature updates</span></span>
### <a name="user-lifecycle"></a><span data-ttu-id="a8210-452">ユーザーのライフサイクル</span><span class="sxs-lookup"><span data-stu-id="a8210-452">User Lifecycle</span></span>
- <span data-ttu-id="a8210-453">**AFO アクティベーションのエクスペリエンスの改善:** 新しい PC にバンドルされている Office のアクティベーション時にお客様に表示される画面の更新。</span><span class="sxs-lookup"><span data-stu-id="a8210-453">**Experience improvements for AFO activation:** Updates to the screens customers see when activating Office that comes bundled with their new PC.</span></span>

### <a name="word"></a><span data-ttu-id="a8210-454">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-454">Word</span></span>
- <span data-ttu-id="a8210-455">**Word の新しい、改善されたオンライン ビデオ エクスペリエンス:** Word での新しいビデオの挿入および既存のビデオの再生に役立つ、新しくより安全なオンライン ビデオ エクスペリエンス。</span><span class="sxs-lookup"><span data-stu-id="a8210-455">**New and improved online video experience in Word:** New and more secure online video experience to help you insert new videos and play existing videos in Word.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="a8210-458">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="a8210-458">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a8210-459">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-459">Outlook</span></span>
- <span data-ttu-id="a8210-460">クロス フォルダー コンテンツを含む断続的なクラッシュ。</span><span class="sxs-lookup"><span data-stu-id="a8210-460">Intermittent crash involving cross folder content.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a8210-461">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a8210-461">Office Suite</span></span>
- <span data-ttu-id="a8210-462">Excel から PowerPoint にグラフを貼り付けると、グラフのサイズが小さくなる場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-462">Pasting a chart from Excel to PowerPoint can reduce the size of the chart.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1911-november-01"></a><span data-ttu-id="a8210-464">バージョン 1911: 11 月 1 日</span><span class="sxs-lookup"><span data-stu-id="a8210-464">Version 1911: November 01</span></span>
<span data-ttu-id="a8210-465">*バージョン 1911 (ビルド 12228.20020)*</span><span class="sxs-lookup"><span data-stu-id="a8210-465">*Version 1911 (Build 12228.20020)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="a8210-467">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-467">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8210-468">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-468">Excel</span></span>
- <span data-ttu-id="a8210-469">**SVG オブジェクトにコンテキストを取り入れる:** 地図やグラフ、その他の SVG ベクターを Office で変換する場合、それらのオブジェクトの中にテキストを保持できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="a8210-469">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="a8210-470">**Surface ペンを使用するときにペンのオプションを確認する:** Word、Excel、PowerPoint で Surface ペンを初めて使用するときに、ペンの色を簡単に選べる [描画] タブがアクティブになります。</span><span class="sxs-lookup"><span data-stu-id="a8210-470">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-471">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-471">PowerPoint</span></span>
- <span data-ttu-id="a8210-472">**SVG オブジェクトにコンテキストを取り入れる:** 地図やグラフ、その他の SVG ベクターを Office で変換する場合、それらのオブジェクトの中にテキストを保持できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="a8210-472">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="a8210-473">**Surface ペンを使用するときにペンのオプションを確認する:** Word、Excel、PowerPoint で Surface ペンを初めて使用するときに、ペンの色を簡単に選べる [描画] タブがアクティブになります。</span><span class="sxs-lookup"><span data-stu-id="a8210-473">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="visio"></a><span data-ttu-id="a8210-474">Visio</span><span class="sxs-lookup"><span data-stu-id="a8210-474">Visio</span></span>
- <span data-ttu-id="a8210-475">**Excel で洗練された Visio 図を作成する:** すばやく簡単に、データを Excel 内の洗練された Visio 図に可視化します。</span><span class="sxs-lookup"><span data-stu-id="a8210-475">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> <span data-ttu-id="a8210-476">[詳細情報](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c) を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a8210-476">[Learn more](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).</span></span>

### <a name="word"></a><span data-ttu-id="a8210-477">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-477">Word</span></span>
- <span data-ttu-id="a8210-478">**Surface ペンを使用するときにペンのオプションを確認する:** Word、Excel、PowerPoint で Surface ペンを初めて使用するときに、ペンの色を簡単に選べる [描画] タブがアクティブになります。</span><span class="sxs-lookup"><span data-stu-id="a8210-478">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

- <span data-ttu-id="a8210-479">**共同編集の改善:** コンテンツの変更をリアルタイムでユーザーが受け取れるようにすることで、共同編集のエクスペリエンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-479">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="a8210-480">**他のユーザーがすばやく変更を確認:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="a8210-480">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="a8210-483">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="a8210-483">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a8210-484">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-484">Excel</span></span>
- <span data-ttu-id="a8210-485">信頼されていないネットワーク共有から保護されたファイルを編集すると、Excel がクラッシュすることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-485">Resolved an issue where Excel may crash when editing a protected file from an untrusted network share.</span></span>
- <span data-ttu-id="a8210-486">別のシートのデータを参照しているスパークラインを含むシートを削除すると、再びそのファイルを開いた時に破損したファイルとして識別されるという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-486">Resolved an issue where deleting sheets containing sparklines referencing data on another sheet could cause the file to be identified as corrupted when re-opened.</span></span>
- <span data-ttu-id="a8210-487">SQL 表形式サーバーのクエリのピボットテーブルの残りの部分と一緒にレポート フィルターを変換すると、正しい結果が返されないことがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-487">Resolved an Issue where you may get incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span>
- <span data-ttu-id="a8210-488">ナレーターと拡大鏡を同時に使用すると、クラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-488">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="a8210-489">ナレーターと拡大鏡を同時に使用すると、クラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-489">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-490">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-490">Outlook</span></span>
- <span data-ttu-id="a8210-491">メールを転送すると、埋め込み画像がなくなる場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-491">A forwarded e-mail may be missing embedded images.</span></span>
- <span data-ttu-id="a8210-492">会議室の検索ツールで、使用可能な会議室が&quot;なし&quot;と表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-492">Room Finder tool may be displaying &quot;None&quot; for available rooms.</span></span>
- <span data-ttu-id="a8210-493">厳しいテナント制限がある Outlook プロファイルをユーザーが作成できない場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-493">Users may not be able to create Outlook profiles with strict tenant restriction.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-494">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-494">PowerPoint</span></span>
- <span data-ttu-id="a8210-495">ナレーターと拡大鏡を同時に使用すると、クラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-495">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="project"></a><span data-ttu-id="a8210-496">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-496">Project</span></span>
- <span data-ttu-id="a8210-497">ユーザーがタスクを完了としてマークすることができず、99% に設定されます。</span><span class="sxs-lookup"><span data-stu-id="a8210-497">User is unable to mark a task as complete, and it gets set to 99%.</span></span>
- <span data-ttu-id="a8210-498">平準化によって割り当て超過が解決されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-498">Overallocations are not resolved by leveling.</span></span>

### <a name="word"></a><span data-ttu-id="a8210-499">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-499">Word</span></span>
- <span data-ttu-id="a8210-500">ナレーターと拡大鏡を同時に使用すると、クラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-500">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="a8210-501">以前のドキュメントを開いたまま [情報] タブに移動すると、クラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-501">Opening legacy documents and then going to the Info tab can cause a crash.</span></span>
- <span data-ttu-id="a8210-502">文章校正の候補がコンテキスト メニューに表示されません。</span><span class="sxs-lookup"><span data-stu-id="a8210-502">Proofing suggestins are not displaying in contextual menus.</span></span>
- <span data-ttu-id="a8210-503">コンテンツ ポリシーがコメントに正しく適用されません。</span><span class="sxs-lookup"><span data-stu-id="a8210-503">Content policies are being incorrectly applied to comments.</span></span>
- <span data-ttu-id="a8210-504">濃色のテキストで書かれた従来のコメントがダーク モードで表示されません。</span><span class="sxs-lookup"><span data-stu-id="a8210-504">Legacy comments written with dark text is not visible in Dark Mode.</span></span>
- <span data-ttu-id="a8210-505">韓国語/英語のオートコレクトを使用しているときに、間違った文字が表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-505">Incorrect characters may appear when using Korean/English autocorrect.</span></span>
- <span data-ttu-id="a8210-506">上位のポリシー ラベルが優先して適用されるべき時に、低いポリシー ラベルが適用されることがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-506">Lower policy labels may be applied when a higher policy label should have taken priority.</span></span>
- <span data-ttu-id="a8210-507">Outlook メッセージ &nbsp; からの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="a8210-507">The links of cid: images from Outlook messages&nbsp;can now be successfully broken when requested.</span></span>
- <span data-ttu-id="a8210-508">ナレーターと拡大鏡を同時に使用すると、クラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-508">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="a8210-509">ナビゲーション ウィンドウから検索できない場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-509">Searching from the Navigation pane may fail.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a8210-510">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a8210-510">Office Suite</span></span>
- <span data-ttu-id="a8210-511">一部の描画がプレビューやスライド ショーに表示されない場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-511">Some drawings may not display in preview or slide shows.</span></span>
- <span data-ttu-id="a8210-512">縦書きのテキスト ボックス内で一部のカタカナが正しく表示されないことがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-512">Some katakana characters may display incorrectly in a vertical text box.</span></span>
- <span data-ttu-id="a8210-513">接続されていないネットワーク共有にファイルを保存しようとすると、クラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-513">Attempting to save a file to a disconnected network share may result in a crash.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1911-october-25"></a><span data-ttu-id="a8210-515">バージョン 1911: 10 月 25 日</span><span class="sxs-lookup"><span data-stu-id="a8210-515">Version 1911: October 25</span></span>
<span data-ttu-id="a8210-516">*バージョン 1911 (ビルド 12215.20006)*</span><span class="sxs-lookup"><span data-stu-id="a8210-516">*Version 1911 (Build 12215.20006)*</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="a8210-518">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-518">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="a8210-519">Visio</span><span class="sxs-lookup"><span data-stu-id="a8210-519">Visio</span></span>

- <span data-ttu-id="a8210-520">**Excel で洗練された Visio 図を作成する:** すばやく簡単に、データを Excel 内の洗練された Visio 図に可視化します。</span><span class="sxs-lookup"><span data-stu-id="a8210-520">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> [<span data-ttu-id="a8210-521">詳細情報</span><span class="sxs-lookup"><span data-stu-id="a8210-521">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="a8210-522">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-522">Word</span></span>

- <span data-ttu-id="a8210-523">**共同編集の改善:** コンテンツの変更をリアルタイムでユーザーが受け取れるようにすることで、共同編集のエクスペリエンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-523">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="a8210-524">**他のユーザーがすばやく変更を確認:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="a8210-524">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="a8210-527">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="a8210-527">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a8210-528">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-528">Access</span></span>

- <div><span data-ttu-id="a8210-529"><span>レコードのカウントが正しくないという問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-529"><span>The record count could be incorrect</span></span></span></div>


### <a name="excel"></a><span data-ttu-id="a8210-530">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-530">Excel</span></span>

- <div><span data-ttu-id="a8210-531"><span>結合されたセルで列を削除するパフォーマンスが大幅に改善されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-531"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


- <div><span data-ttu-id="a8210-532"><span>ユーザーが Office 365 の Excel ブック形式で保存できなくなる問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-532"><span>Users could be prevented from saving in Office 365 Excel Workbook format</span></span></span></div>


- <div><span data-ttu-id="a8210-533"><span>チェックボックスで正しく表示できないという問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-533"><span>Checkboxes could not render correctly</span></span></span></div>


- <div><span data-ttu-id="a8210-534"><span>グラフのサイズの変更が保存できないという問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-534"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="a8210-535"><span>VBA 関数の一部で、新しいグラフの種類に関するエラーが返される問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-535"><span>Some VBA functions would return an error on new chart types</span></span></span></div>


- <div><span data-ttu-id="a8210-536"><span>[データ ソースの選択] ダイアログで、一部のフィールドの大文字小文字の区別をしなかった問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-536"><span>Select Data Source dialogs were not case sensitive for some fields</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="a8210-537">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-537">PowerPoint</span></span>

- <div><span data-ttu-id="a8210-538"><span>グラフのサイズの変更が保存できないという問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-538"><span>Changes to a chart size could not be saved</span></span></span></div>


### <a name="publisher"></a><span data-ttu-id="a8210-539">Publisher</span><span class="sxs-lookup"><span data-stu-id="a8210-539">Publisher</span></span>

- <div><span data-ttu-id="a8210-540"><span>図形がグラフィックの境界線の外側に表示される問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-540"><span>Shapes could appear outside of the graphics border</span></span></span></div>


### <a name="word"></a><span data-ttu-id="a8210-541">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-541">Word</span></span>

- <div><span data-ttu-id="a8210-542"><span>図形がグラフィックの境界線の外側に表示される問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-542"><span>Shapes could appear outside of the graphics border</span></span></span></div>


- <div><span data-ttu-id="a8210-543"><span>テキストの強調表示が課題になるという問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-543"><span>Highlighting text could be challenging</span></span></span></div>


- <div><span data-ttu-id="a8210-544"><span>ユーザーがエディターの個々のアイテムに移動できなくなる問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-544"><span>A user could be prevented from navigating to an individual item in the editor</span></span></span></div>


- <div><span data-ttu-id="a8210-545"><span>文法またはスペルのエラーが強調表示されない問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-545"><span>Grammar or spelling errors might not be highlighted</span></span></span></div>


- <div><span data-ttu-id="a8210-546"><span>グラフのサイズの変更が保存できないという問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-546"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="a8210-547"><span>連絡先カードが、@ メンションに書式を設定した後に、開けなくなる問題が解決されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-547"><span>A contact card could be prevented from opening after apply formatting to an @ mention</span></span></span></div>


- <div><span data-ttu-id="a8210-548"><span>ユーザーが、Word、Excel、PowerPoint のドキュメントを保存できなくなる場合があるという問題が解決されました。&nbsp;この問題は、[保存] アイコンをクリックしたり Ctrl キーを押しながら S キーを押したりした後に、新しいファイルを作成して &quot;[モデル形式で保存] ダイアログ&quot; を表示するユーザーに影響を与えます。</span></span><span class="sxs-lookup"><span data-stu-id="a8210-548"><span>Resolvedan issue where users may be unable to save Word, Excel, and PowerPoint documents.&nbsp; This issue affects users that create a new file and bring up the &quot;Save as Model Dialog&quot; option after clicking on the Save icon or pressing Ctrl + S.</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="a8210-549">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a8210-549">Office Suite</span></span>

- <div><span data-ttu-id="a8210-550"><span>Windows 7 で図形を使用する場合のパフォーマンスの問題</span></span><span class="sxs-lookup"><span data-stu-id="a8210-550"><span>Performance issue when using Shapes on Windows 7</span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1911-october-18"></a><span data-ttu-id="a8210-552">バージョン 1911: 10 月 18 日</span><span class="sxs-lookup"><span data-stu-id="a8210-552">Version 1911: October 18</span></span>
<span data-ttu-id="a8210-553">*バージョン 1911 (ビルド 12209.20010)*</span><span class="sxs-lookup"><span data-stu-id="a8210-553">*Version 1911 (Build 12209.20010)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="a8210-555">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-555">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a8210-556">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-556">Outlook</span></span>

- <span data-ttu-id="a8210-557">**アクセシビリティ対応のメールを最も必要としている人に送信する:** Outlook では、メールのヒントが表示され、アクセシビリティ対応のコンテンツを必要とするユーザーに送信するときに、コンテンツがアクセシビリティ対応であることを確認できます</span><span class="sxs-lookup"><span data-stu-id="a8210-557">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-558">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-558">PowerPoint</span></span>

- <span data-ttu-id="a8210-559">**プレゼンテーションの最適化:** アクセシビリティ チェックを使用すると、スクリーン リーダーを考慮に入れて、スライド上のオブジェクトを配置することができます。</span><span class="sxs-lookup"><span data-stu-id="a8210-559">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a8210-560">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a8210-560">Office Suite</span></span>

- <span data-ttu-id="a8210-561">**アップロード センターは、Files Needing Attention experience に置き換えられます:** アップロード センターは、[ファイル] > [開く] の Office アプリケーション内に表示される Files Needing Attention experience に置き換えられます。</span><span class="sxs-lookup"><span data-stu-id="a8210-561">**The Upload Center is being replaced by the Files Needing Attention experience:** The Upload Center is being replaced by the Files Needing Attention experience that will show up inside the Office applications under File > Open.</span></span> <span data-ttu-id="a8210-562">この新しいエクスペリエンスは、アップロード センターに比べ、最新かつ総合的で、煩わしくありません。</span><span class="sxs-lookup"><span data-stu-id="a8210-562">This new experience is more modern, integrated, and less intrusive compared to the Upload Center.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="a8210-565">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-565">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8210-566">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-566">Excel</span></span>

- <div><span data-ttu-id="a8210-567"><span>自動調整を使用して行の高さを調整するときにチェック ボックスのコントロールが縮小されるという問題を解決しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-567"><span>Resolved an issue where check box controls could shrink when using autofit to adjust row height</span></span></span></div>


- <div><span data-ttu-id="a8210-568"><span>スクロール後にセルを選択すると間違ったセルが選択されるという問題を解決しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-568"><span>Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="a8210-569">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-569">Outlook</span></span>

- <div><span data-ttu-id="a8210-570"><span>メールにデジタル署名付きの添付ファイルがある場合にそのメールに署名するとデジタル署名が破損する可能性があるという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-570"><span>Identified an issue which could cause digital signatures to become broken when signing an e-mail with a digitally signed attachment</span></span></span></div>


- <div><span data-ttu-id="a8210-571"><span>長いファイル名がメッセージ本文へのドラッグ アンド ドロップ後に切り捨てられるという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-571"><span>Identified an issue where long filenames were truncated after draging and droping to the message body</span></span></span></div>


- <div><span data-ttu-id="a8210-572">リボンを自動的に非表示にするよう設定されている場合に検索ボックスが消えるという問題を特定しました</span><span class="sxs-lookup"><span data-stu-id="a8210-572">Identified an issue where the search box could disappear when the ribbon is set to hide automatically</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="a8210-573">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-573">PowerPoint</span></span>

- <div><span data-ttu-id="a8210-574"><span>スライド プレビューの縦横比が適切にロック/ロック解除されていないという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-574"><span>Identified an issuewhere aspect ratio for the slide preview was not being properly locked/unlocked</span></span></span></div>

### <a name="project"></a><span data-ttu-id="a8210-575">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-575">Project</span></span>

- <div><span data-ttu-id="a8210-576">タスクの更新を実行中に入力したノートが保存されない可能性があるという問題を特定しました</span><span class="sxs-lookup"><span data-stu-id="a8210-576">Identified an issue where notes might not persist if entered while doing update tasks</span></span><br></div>


- <div><span data-ttu-id="a8210-577">ファイルがユーザーによってロックされている場合に、ユーザー名がエラー メッセージに表示されない可能性があるという問題を特定しました</span><span class="sxs-lookup"><span data-stu-id="a8210-577">Identified an issue where a file could be locked by a user, but no username would be displayed in the error message</span></span></div>


- <div><span data-ttu-id="a8210-578"><span>読み取り専用のプロジェクトを開いたときに複数のメッセージを取得する可能性があるという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-578"><span>Identified an issue where users could get several messages when opening a read-only project</span></span></span></div>


### <a name="word"></a><span data-ttu-id="a8210-579">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-579">Word</span></span>

- <div><span data-ttu-id="a8210-580"><span>スクリーン リーダーを使用中にコメントを表示するときの問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-580"><span>Identified an issue when viewing comments while using a screen reader</span></span></span></div>


- <div><span data-ttu-id="a8210-581"><span>一部の批評がスペルまたは文法の批評と誤って識別されるという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-581"><span>Identified an issue where some critiques were misidentified as being spelling or grammar critiques</span></span></span></div>


- <div><span data-ttu-id="a8210-582"><span>新しいコメント ダイアログがフォーカスを取得できないことがあるという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-582"><span>Identified an issue where a new comment dialog could sometimes not obtain focus</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="a8210-583">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a8210-583">Office Suite</span></span>

- <div><span data-ttu-id="a8210-584"><span>&quot;[別のインストールが進行中です]&quot; という誤ったエラー メッセージによりアップグレードに失敗することがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-584"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="a8210-585"><span>ローカル リソースからクラウド リソースへの同期に影響する可能性がある問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-585"><span>Identified an issue which could affect syncing from a local resource to a cloud resource</span></span></span></div>

- <div><span data-ttu-id="a8210-586"><span>ウェルカム メッセージに無効なリンクが含まれているという問題を特定しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-586"><span>Identified an issue where a welcome message contained an invalid link</span></span></span></div>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-october-11"></a><span data-ttu-id="a8210-588">バージョン 1910: 10 月 11 日</span><span class="sxs-lookup"><span data-stu-id="a8210-588">Version 1910: October 11</span></span>
<span data-ttu-id="a8210-589">*バージョン 1910 (ビルド 12130.20112)*</span><span class="sxs-lookup"><span data-stu-id="a8210-589">*Version 1910 (Build 12130.20112)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)
[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)
[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="a8210-593">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-593">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8210-594">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-594">Excel</span></span>

- <div><span data-ttu-id="a8210-595">OneDrive からオブジェクトとしてファイルを挿入する場合の問題が解決されました</span><span class="sxs-lookup"><span data-stu-id="a8210-595">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="a8210-596">ハイパーリンク形式が一部のコンテンツに適切に適用されない場合がある問題が解決されました</span><span class="sxs-lookup"><span data-stu-id="a8210-596">Resolved an issue where the hyperlink format could not be properly applied to some content</span></span></div>


- <div><span data-ttu-id="a8210-597">数式に構造化された絶対参照が含まれる場合に誤って調整される可能性がある問題が解決されました</span><span class="sxs-lookup"><span data-stu-id="a8210-597">Resolved an issue where formulas containing structured absolute references may be adjusted incorrectly</span></span></div>


- <div><span data-ttu-id="a8210-598">Office 現在のバージョンで開いた場合に Excel の停止を引き起こす可能性がある、Office の以前のバージョンで作成されるブックの問題が解決されました</span><span class="sxs-lookup"><span data-stu-id="a8210-598">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office</span></span></div>


- <div><span data-ttu-id="a8210-599">Excel からコピーされたコンテンツを他の Office アプリケーションに貼り付けると、間違って表示されることがある問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-599">Resolved an issue where content copied from Excel could appear incorrect when pasted into other Office applications</span></span></div>


- <div><span data-ttu-id="a8210-600">グラフ テンプレートを使用してグラフを挿入する場合に、プレビューで正しい色が使用されるよう修正します</span><span class="sxs-lookup"><span data-stu-id="a8210-600">Fix to correct colors used in previews when inserting charts using chart templates</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="a8210-601">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-601">PowerPoint</span></span>

- <div><span data-ttu-id="a8210-602">AirSpace WinComp 下で実行しているときに ARC デバイスの接続が失われる問題を特定しました</span><span class="sxs-lookup"><span data-stu-id="a8210-602">Identified an issue where ARC Devices could lose connection when running under AirSpace WinComp</span></span></div>


### <a name="word"></a><span data-ttu-id="a8210-603">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-603">Word</span></span>

- <div><span data-ttu-id="a8210-604">OneDrive からオブジェクトとしてファイルを挿入する場合の問題が解決されました</span><span class="sxs-lookup"><span data-stu-id="a8210-604">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="a8210-605"><span>メールのスレッドからグラフィカル コンテンツが削除される原因となっていた問題を修正&nbsp;</span>するための回復手順が改善されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-605">Improved our recovery steps to f<span>ix an issue that caused graphical content to get deleted from email threads.&nbsp;</span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-october-04"></a><span data-ttu-id="a8210-607">バージョン 1910: 10 月 4 日</span><span class="sxs-lookup"><span data-stu-id="a8210-607">Version 1910: October 04</span></span>
<span data-ttu-id="a8210-608">*バージョン 1910 (ビルド 12126.20000)*</span><span class="sxs-lookup"><span data-stu-id="a8210-608">*Version 1910 (Build 12126.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="a8210-610">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-610">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8210-611">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-611">Excel</span></span>

- <span data-ttu-id="a8210-612">**データ ビジュアライザー アドイン:** Excel から Visio フローチャートをすばやく作成します。</span><span class="sxs-lookup"><span data-stu-id="a8210-612">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="a8210-613">詳細情報</span><span class="sxs-lookup"><span data-stu-id="a8210-613">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="a8210-616">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-616">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8210-617">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-617">Excel</span></span>

- <div><span data-ttu-id="a8210-618"><span>印刷プレビューの印刷範囲が正しくない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-618"><span>We fixed an issue where the print area in print preview was not correct</span></span></span></div>


- <div><span data-ttu-id="a8210-619"><span>共同編集セッション中にピボット テーブルが更新されないことがあった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-619"><span>We fixed an issue which could have prevented pivot tables from being refreshed during a co-authoring session</span></span></span></div>


### <a name="access"></a><span data-ttu-id="a8210-620">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-620">Access</span></span>

- <div><span data-ttu-id="a8210-621">共有データベースの使用中に、"&quot;矛盾がある状態&quot;" エラーがユーザーに表示されることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-621">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


### <a name="outlook"></a><span data-ttu-id="a8210-622">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-622">Outlook</span></span>

- <div><span data-ttu-id="a8210-623"><span>メール フォルダーの重複を引き起こすことがあった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-623"><span>We fixed an issue which could have caused duplication of mail folders</span></span></span></div>


- <div><span data-ttu-id="a8210-624"><span>S/MIME で暗号化された電子メールを送信しようとしたときに誤ったエラー メッセージが表示されることがあった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-624"><span>We fixed an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail</span></span></span></div>


- <div><span data-ttu-id="a8210-625"><span>ユーザーが Skype から「不在着信した会話」メッセージを受信したときにクラッシュすることがあった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-625"><span>We fixed an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype</span></span></span></div>


- <div><span data-ttu-id="a8210-626"><span>メモリ リークを引き起こすことがあった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-626"><span>We fixed an issue which could have resulted in a memory leak</span></span></span></div>


- <div><span data-ttu-id="a8210-627"><span>下書きとして保存したときに送信者の名前が変更されることがあった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-627"><span>We fixed an issue which could have caused the senders name to change when saved as a draft</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="a8210-628">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-628">PowerPoint</span></span>

- <div><span></span></div><span data-ttu-id="a8210-629">スライド マスターとスライド レイアウトのヘッダー/フッター/スライド番号プレースホルダーにテキストを貼り付けた後、TextRanges が破損することがあった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-629">We fixed an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout</span></span>


- <div><span></span></div><span data-ttu-id="a8210-630">ハイパーリンク付きのテキストを貼り付けるときにハイパーリンクが作成されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-630">We fixed an issue which prevented hyperlink from being created when pasting text with hyperlink</span></span>


- <div><span data-ttu-id="a8210-631">統計が正常に機能しなくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-631">We fixed an issue which would prevent statistics from working correctly</span></span></div>


### <a name="word"></a><span data-ttu-id="a8210-632">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-632">Word</span></span>

- <div><span data-ttu-id="a8210-633"><span>フォントの色がコミットされない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-633"><span>We fixed an issue where font colors were not being committed</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="a8210-634">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a8210-634">Office Suite</span></span>

- <div><span data-ttu-id="a8210-635">この機能が無効になったときにバージョン履歴が表示されることがあった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-635">We fixed an issue which could offer version history when that feature was disabled</span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-september-27"></a><span data-ttu-id="a8210-637">バージョン 1910: 9 月 27 日</span><span class="sxs-lookup"><span data-stu-id="a8210-637">Version 1910: September 27</span></span>
<span data-ttu-id="a8210-638">*バージョン 1910 (ビルド 12119.20000)*</span><span class="sxs-lookup"><span data-stu-id="a8210-638">*Version 1910 (Build 12119.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)
[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)
[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="a8210-642">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-642">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8210-643">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-643">Excel</span></span>

- <div><span data-ttu-id="a8210-644"><span>シリーズ コレクションを変更するときに、散布図が適切にレンダリングされない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-644"><span>We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="a8210-645">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-645">Outlook</span></span>

- <div><span data-ttu-id="a8210-646"><span>共有予定表フォルダーを操作するときに、アクセス許可エラーを報告する可能性があった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-646"><span>We fixed an issue which could have reported permission errors when interacting with shared calendar folders</span></span></span></div>


- <div><span data-ttu-id="a8210-647"><span>ユーザーが予定表に添付ファイルを追加できない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-647"><span>We fixed an issue which could have prevented users from adding attachments to calendars</span></span></span></div>


- <div><span data-ttu-id="a8210-648"><span>デジタル署名されたメッセージに返信するときに、エラー メッセージが表示される問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-648"><span>We fixed an issue which caused error messages to display when replying to a digitally signed message</span></span></span></div>


### <a name="word"></a><span data-ttu-id="a8210-649">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-649">Word</span></span>

- <div><span data-ttu-id="a8210-650"><span>Deskjet プリンターへの印刷時に、スケーリングの問題を引き起こす可能性があった問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-650"><span>We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="a8210-651">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a8210-651">Office Suite</span></span>

- <div><span data-ttu-id="a8210-652"><span>中太字のテキストのスタイルが正しく表示されない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-652"><span>We fixed an issue where medium bold text could be incorrectly styled</span></span></span></div>


- <div><span data-ttu-id="a8210-653"><span>アップロードが保留されているファイルを閉じるときに、ユーザーに誤ったエラー メッセージが表示される問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-653"><span>We fixed an issue where a user could be given an incorrect error message when closing a file with a pending upload</span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-september-20"></a><span data-ttu-id="a8210-655">バージョン 1910: 9 月 20 日</span><span class="sxs-lookup"><span data-stu-id="a8210-655">Version 1910: September 20</span></span>
<span data-ttu-id="a8210-656">*バージョン 1910 (ビルド 12112.20000)*</span><span class="sxs-lookup"><span data-stu-id="a8210-656">*Version 1910 (Build 12112.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="a8210-660">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-660">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8210-661">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-661">Excel</span></span>

- <div><span data-ttu-id="a8210-662"><span>Excel が起動時にハングすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-662"><span>We fixed an issue where Excel could sometimes hang at launch</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="a8210-663">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-663">Outlook</span></span>

- <div><span data-ttu-id="a8210-664"><span>多数の部屋が利用可能な場合の部屋選択のパフォーマンスが大幅に向上しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-664"><span>We significantly improved the performance of room selection when there are a large number of rooms available</span></span></span></div>


- <div><span data-ttu-id="a8210-665"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Office 365 の最新の認証に移行するときに、Outlook に複数のメールボックスを使用しているユーザーのメールボックスの同期を妨げる可能性がある問題を修正しました。</span></span><span class="sxs-lookup"><span data-stu-id="a8210-665"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can prevent mailbox sync for customers with multiple mailboxes in Outlook when migrating to modern authentication in Office 365.</span></span></span><br></div>


- <div><span data-ttu-id="a8210-666"><span>署名ラベルの一部の文字がドロップダウン メニューに表示されない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-666"><span>We fixed an issue where some characters in signature labels would not display in the dropdown menu</span></span></span></div>


### <a name="project"></a><span data-ttu-id="a8210-667">プロジェクト</span><span class="sxs-lookup"><span data-stu-id="a8210-667">Project</span></span>

- <div><span data-ttu-id="a8210-668"><span>エンタープライズ リソースをローカル リソースに置き換えるとクラッシュする可能性がある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-668"><span>We fixed an issue which could cause a crash when replacing an enterprise resource with a local resource</span></span></span></div>


### <a name="word"></a><span data-ttu-id="a8210-669">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-669">Word</span></span>

- <div><span data-ttu-id="a8210-670"><span>下書き表示で同期スクロールが正常に機能しない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-670"><span>We fixed an issue which could prevent synchronous scrolling from working properly in draft view</span></span></span></div>


- <div><span data-ttu-id="a8210-671">ドキュメントを初めて保存した後、ツール ヒントが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-671">We fixed an issue which could prevent Tool Tips from displaying properly after saving a document for the first time</span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-september-13"></a><span data-ttu-id="a8210-673">バージョン 1910: 9 月 13 日</span><span class="sxs-lookup"><span data-stu-id="a8210-673">Version 1910: September 13</span></span>
<span data-ttu-id="a8210-674">*バージョン 1910 (ビルド 12105.20000)*</span><span class="sxs-lookup"><span data-stu-id="a8210-674">*Version 1910 (Build 12105.20000)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="a8210-676">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-676">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8210-677">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-677">Excel</span></span>

- <div><span data-ttu-id="a8210-678"><span>一部の保護されたシートにユーザーがハイパーリンクを貼り付けられない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-678"><span>We fixed an issue which could prevent a user from pasting hyperlinks in some protected sheets</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="a8210-679">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-679">Outlook</span></span>

- <div><span data-ttu-id="a8210-680"><span>コンパクト ビューで UI が動かなくなる問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-680"><span>We fixed an issue where the UI could get stuck in a compact view</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="a8210-681">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-681">PowerPoint</span></span>

- <div><span data-ttu-id="a8210-682"><span>PDFへの印刷時、ユーザーにエラーが発生する問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-682"><span>We fixed an issue where a user could experience an error upon printing to PDF</span></span></span></div>


### <a name="project"></a><span data-ttu-id="a8210-683">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-683">Project</span></span>

- <div><span data-ttu-id="a8210-684"><span>問題を修正しました (<span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">保護された作業が有効になっている場合、サマリー タスクの作業値を変更するとクラッシュする</span></span>)</span><span class="sxs-lookup"><span data-stu-id="a8210-684"><span>We fixed an issue where <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">changes to a work value on a summary task could cause a crash if protected work is enabled</span></span></span></span></div>


- <span data-ttu-id="a8210-685"><font size=2 style="background-color:rgb(255, 255, 255);">エンタープライズ カレンダーとイベントを同期する機能を阻害する可能性がある問題を修正しました</font></span><span class="sxs-lookup"><span data-stu-id="a8210-685"><font size=2 style="background-color:rgb(255, 255, 255);">We fixed an issue which could inhibit the ability to sync events with enterprise calendars</font></span></span>


### <a name="office-suite"></a><span data-ttu-id="a8210-686">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a8210-686">Office Suite</span></span>

- <div><span data-ttu-id="a8210-687"><span>ファイルのローカル バージョンの破棄を促す警告が繰り返し発生する可能性がある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-687"><span>We fixed an issue which could cause a repeated warning to discard local versions of a file</span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-september-06"></a><span data-ttu-id="a8210-689">バージョン 1910: 9 月 6 日</span><span class="sxs-lookup"><span data-stu-id="a8210-689">Version 1910: September 06</span></span>
<span data-ttu-id="a8210-690">*バージョン 1910 (ビルド 12030.20004)*</span><span class="sxs-lookup"><span data-stu-id="a8210-690">*Version 1910 (Build 12030.20004)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="a8210-692">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-692">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8210-693">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-693">Excel</span></span>

- <span data-ttu-id="a8210-694">**準備ができたら、描画を開始:** Surface ペンを持てば、描画の準備完了です。</span><span class="sxs-lookup"><span data-stu-id="a8210-694">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="a8210-695">詳細情報</span><span class="sxs-lookup"><span data-stu-id="a8210-695">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="powerpoint"></a><span data-ttu-id="a8210-696">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-696">PowerPoint</span></span>

- <span data-ttu-id="a8210-697">**準備ができたら、描画を開始:** Surface ペンを持てば、描画の準備完了です。</span><span class="sxs-lookup"><span data-stu-id="a8210-697">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="a8210-698">詳細情報</span><span class="sxs-lookup"><span data-stu-id="a8210-698">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a><span data-ttu-id="a8210-699">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-699">Word</span></span>

- <span data-ttu-id="a8210-700">**準備ができたら、描画を開始:** Surface ペンを持てば、描画の準備完了です。</span><span class="sxs-lookup"><span data-stu-id="a8210-700">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="a8210-701">詳細情報</span><span class="sxs-lookup"><span data-stu-id="a8210-701">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="a8210-704">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-704">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8210-705">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-705">Excel</span></span>

- <div><span data-ttu-id="a8210-706"><span> リボンのフォント名が使用されているフォントと異なることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-706"><span>We fixed an issue which could cause the font name in the ribbon to be different from the font being used</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="a8210-707">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-707">Outlook</span></span>

- <div><span data-ttu-id="a8210-708"><span> Internet Explorer で制限付きサイトの保護モードが無効になると、Outlook により不適切なリソースの使用量になることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-708"><span>We fixed an issue that could result in inappropriate resource consumption by Outlook when Protected Mode is disabled for Restricted Sites in Internet Explorer</span></span></span></div>


- <div><span data-ttu-id="a8210-709"><span>時々、ANSI ソースのテキスト貼り付けるときに Unicode 文字が表示されることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-709"><span>We fixed an issue which could sometimes cause Unicode characters to appear when pasting text from an ANSI source</span></span></span></div>


- <div><span data-ttu-id="a8210-710"><span>グループ スケジュール ビューで一部のユーザーがオフラインとして間違って表示される問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-710"><span>We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span></span></div>


### <a name="word"></a><span data-ttu-id="a8210-711">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-711">Word</span></span>

- <div><span data-ttu-id="a8210-712"><span>テーブルの書式設定が失われることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-712"><span>We fixed an issue where table formatting could be lost</span></span></span></div>


- <div><span data-ttu-id="a8210-713"><span>Ctrl + V ショートカット キーが効かなくなることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-713"><span>We fixed an issue which could break the ctrl+v keyboard shortcut</span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1909-august-30"></a><span data-ttu-id="a8210-715">バージョン 1909: 8 月 30 日</span><span class="sxs-lookup"><span data-stu-id="a8210-715">Version 1909: August 30</span></span>
<span data-ttu-id="a8210-716">*バージョン 1909 (ビルド 12026.20000)*</span><span class="sxs-lookup"><span data-stu-id="a8210-716">*Version 1909 (Build 12026.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="a8210-718">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-718">Feature updates</span></span>

### <a name="access"></a><span data-ttu-id="a8210-719">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-719">Access</span></span>

- <span data-ttu-id="a8210-720">**リンク テーブルの高速検索:** 新しい検索ボックスにより、リンク テーブルを簡単に見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="a8210-720">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-721">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-721">PowerPoint</span></span>

- <span data-ttu-id="a8210-722">**図を SVG として保存する:** グラフ、図形、その他の図を、サイズ変更しても画質が低下しないスケーラブル ベクター グラフィックとして保存できます。</span><span class="sxs-lookup"><span data-stu-id="a8210-722">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="a8210-723">詳細情報</span><span class="sxs-lookup"><span data-stu-id="a8210-723">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="a8210-726">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="a8210-726">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a8210-727">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-727">Excel</span></span>

- <div><span data-ttu-id="a8210-728"><span>&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">秘密度</span>のキー ヒントが&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">別のキー ヒントと競合している問題が修正されました。</span></span></span><span class="sxs-lookup"><span data-stu-id="a8210-728"><span>We fixed an issue where the keytip for&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">Sensitivity </span>was&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">conflicting with another keytip.</span></span></span></span></div>

- <div><span data-ttu-id="a8210-729"><span>共有ブックでの作業中に保存を行おうとする際に発生する問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="a8210-729"><span>We fixed an issue that occurred while working on a shared workbook when trying to save.</span></span></span></div>

- <div><span data-ttu-id="a8210-730"><span>Excel で、レジストリ値 "\Excel\Add-in Manager" にあるアドインのうち、最初の 16 個しか表示されない問題が修正されました。<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span><span class="sxs-lookup"><span data-stu-id="a8210-730"><span>We fixed an issue where Excel only lists the first 16 addins located in the '\Excel\Add-in Manager' registry values.<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span></span></div>


- <div><span data-ttu-id="a8210-731"><span>関数 Frequency() が誤った結果を返す問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="a8210-731"><span>We fixed an issue where the function Frequency() returns incorrect results.</span></span></span></div>


- <div><span data-ttu-id="a8210-732"><span>色によるフィルター処理のパフォーマンスが大幅に改善されました。</span></span><span class="sxs-lookup"><span data-stu-id="a8210-732"><span>We have significantly improved the performance of filtering by color.</span></span></span></div>


- <div><span data-ttu-id="a8210-733"><span>Surface のユーザーがマウスを動かすと、それがマウス クリックのイベントとして解釈されることがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="a8210-733"><span>We fixed an issue for Surface users where moving the mouse could be interpreted as a mouse click event.</span></span></span></div>


- <div><span data-ttu-id="a8210-734"><span>[検索と置換] ダイアログでキーボードによるナビゲーションを行えない問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-734"><span>We fixed an issue which prevented keyboard navigation in the Find/Replace dialog</span></span></span></div>


- <div><span data-ttu-id="a8210-735"><span>一部のフォント名が正しく表示されない問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-735"><span>We fixed an issue where the name of some fonts were not displayed correctly</span></span></span></div>


- <div><span data-ttu-id="a8210-736"><span>サポートされているファイル形式として CSV が表示されない問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-736"><span>We fixed an issue which prevented CSV from appearing as a supported file type</span></span></span></div>


### <a name="access"></a><span data-ttu-id="a8210-737">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-737">Access</span></span>

- <div><span data-ttu-id="a8210-738">共有データベースの使用中に、"&quot;矛盾がある状態&quot;" エラーがユーザーに表示されることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-738">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


- <div><span data-ttu-id="a8210-739"><span>日付選択カレンダーが表示されるべきではないときに表示されてしまうことがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="a8210-739"><span>We fixed an issue which could cause the date picker to appear when it shouldn't</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="a8210-740">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-740">Outlook</span></span>

- <div><span data-ttu-id="a8210-741"><span>一部の POP3 ユーザーに HTML コンテンツが表示されない問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-741"><span>We fixed an issue which prevented HTML content from appearing for some POP3 users</span></span></span></div>


- <div><span data-ttu-id="a8210-742"><span>Planner を利用できない環境で、連絡先カードのオーバーフロー メニューから機能しない [Planner] リンクを削除するための修正を行いました。</span></span><span class="sxs-lookup"><span data-stu-id="a8210-742"><span>We fixed an issue to remove non-functional 'Planner' link from the overflow menu in the contact card when working in environments where it is not available.</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="a8210-743">OneNote</span><span class="sxs-lookup"><span data-stu-id="a8210-743">OneNote</span></span>

- <div><span data-ttu-id="a8210-744"><span>フォーカスが &nbsp;OneNote のバックグラウンド同期に移動してしまうことがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="a8210-744"><span>We fixed an issue where&nbsp;OneNote background sync was sometimes stealing focus.</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="a8210-745">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-745">PowerPoint</span></span>

- <div><span data-ttu-id="a8210-746"><span>3-D Turntable の回転の向きに影響を与えていた問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="a8210-746"><span>We fixed an issue which would affect the rotation orientation of a 3D Turntable.</span></span></span></div>

- <div><span data-ttu-id="a8210-747"><span>ハイパーリンクに特殊文字が含まれている場合に一部のハイパーリンクが機能しない問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="a8210-747"><span>We fixed an issue which prevented some hyperlinks from working if they contained special characters.</span></span></span></div>

- <div><span data-ttu-id="a8210-748"><span>同時に複数のコメント ウィンドウが開かれる問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="a8210-748"><span>We fixed an issue which caused multiple comment panes to open at the same time.</span></span></span></div>

### <a name="project"></a><span data-ttu-id="a8210-749">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-749">Project</span></span>

- <div><span data-ttu-id="a8210-750"><span>チーム プランナー ビューを印刷した後にクラッシュすることがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="a8210-750"><span>We fixed an issue which could sometimes cause a crash after printing a Team Planner view.</span></span></span></div>

### <a name="word"></a><span data-ttu-id="a8210-751">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-751">Word</span></span>

- <div><span data-ttu-id="a8210-752">閲覧表示で、縦書きテキスト ボックス内の複数バイト文字が重なって表示される問題が<span>修正されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-752">We f<span>ixed an issue where multi-byte characters in vertical text box are shown overlapped in reading view.</span></span><br></span></div>

- <div><span data-ttu-id="a8210-753"><span>&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">ユーザーがアドイン ウィザードでアクションを実行する際に、日本語のはがきとグリーティング カードに関連するアドインのリソースが見つからない問題が修正されました。</span></span></span><span class="sxs-lookup"><span data-stu-id="a8210-753"><span>We&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">fixed an issue where Japanese post card and greeting card related addin resources are not found when the user takes action in the addin wizard.</span></span></span></span></div>

- <div><span data-ttu-id="a8210-754"><span>保護ビューで表示中に、タイトル バーのユーザー インターフェイスで問題を発生させることがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="a8210-754"><span>We fixed an issue which could cause issues with the Title Bar User Interface when in Protected View</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="a8210-755">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a8210-755">Office Suite</span></span>

- <div><span data-ttu-id="a8210-756"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">標準の図形とコネクタ図形の両方が含まれる選択部分に対して [図形の変更] を適用するとファイルが破損する問題が修正されました。</span></span></span><span class="sxs-lookup"><span data-stu-id="a8210-756"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> We fixed a corrupt file issue when you Change Shape on a selection that contains both a normal shape and a connector shape.</span></span></span></span></div>

- <div><span data-ttu-id="a8210-757"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">複数の外付けモニターからドッキングとドッキングの解除を使用すると、アプリケーションに問題が発生する</span>問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="a8210-757"><span>We fixed an issue that <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">caused a problem in applications when using dock/undock from multiple external displays. </span></span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="august-23-2019br"></a><span data-ttu-id="a8210-759">**2019 年 8 月 23 日**</span><span class="sxs-lookup"><span data-stu-id="a8210-759">**August 23, 2019**</span></span><br/>
<span data-ttu-id="a8210-760">バージョン 1909 (ビルド 12015.20004)</span><span class="sxs-lookup"><span data-stu-id="a8210-760">Version 1909 (Build 12015.20004)</span></span><br/>



## <a name="non-security-updates"></a><span data-ttu-id="a8210-761">セキュリティ以外の更新プログラム:</span><span class="sxs-lookup"><span data-stu-id="a8210-761">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-762">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-762">Excel</span></span>

- <div><span data-ttu-id="a8210-763"><span>結合されたセルで列を削除するパフォーマンスが大幅に改善されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-763"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="a8210-764">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a8210-764">Office Suite</span></span>

- <div><span data-ttu-id="a8210-765"><span>一部の Unicode 文字がブラウザー上で表示されない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-765"><span>We fixed an issue which could prevent some Unicode characters from being displayed when viewed in a browser</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="a8210-766">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-766">Outlook</span></span>

- <div><span data-ttu-id="a8210-767"><span>WebDAV の場所にファイルを保存できないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-767"><span>We fixed an issue which could have prevented files from being saved to a WebDAV location</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="a8210-768">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-768">PowerPoint</span></span>

- <div><span data-ttu-id="a8210-769"><span>ユーザーがあるコメントをクリックすると別のコメントが選択される問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-769"><span>We fixed an issue where a user would click on one comment, but another comment would be selected</span></span></span></div>





## <a name="august-16-2019br"></a><span data-ttu-id="a8210-770">**2019 年 8 月 16 日**</span><span class="sxs-lookup"><span data-stu-id="a8210-770">**August 16, 2019**</span></span><br/>
<span data-ttu-id="a8210-771">バージョン 1909 (ビルド 12013.20000)</span><span class="sxs-lookup"><span data-stu-id="a8210-771">Version 1909 (Build 12013.20000)</span></span><br/>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="a8210-772">PowerPoint 機能の更新:</span><span class="sxs-lookup"><span data-stu-id="a8210-772">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="a8210-773">**配布資料にスライド番号を印刷する:** スライド番号は配布資料に自動的に含まれます。</span><span class="sxs-lookup"><span data-stu-id="a8210-773">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="a8210-774">それらをオンのままにするか、オフにするか、選択します。</span><span class="sxs-lookup"><span data-stu-id="a8210-774">Leave them on, turn them off, it's all up to you.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="a8210-775">セキュリティ以外の更新プログラム:</span><span class="sxs-lookup"><span data-stu-id="a8210-775">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-776">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-776">Excel</span></span>

- <div><span data-ttu-id="a8210-777"><span>自動保存が有効になることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-777"><span>We fixed an issue which could cause AutoSave to become enabled</span></span></span></div>


- <div><span data-ttu-id="a8210-778">セルの高さが不正確に測定されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-778">We fixed an issue which could result in cell heights being measured inaccurately</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="a8210-779">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a8210-779">Office Suite</span></span>

- <div><span data-ttu-id="a8210-780"><span>コメント機能のパフォーマンスを大幅に改善する問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-780"><span>We fixed an issue which significantly improves the performance of the Comments feature</span></span></span></div>


- <div><span data-ttu-id="a8210-781"><span>検索中に方向キーを使用するとクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-781"><span>We fixed an issue which could cause a crash when using arrow keys while in search</span></span></span></div>


- <div><span data-ttu-id="a8210-782"><span>@ 記号が特定の文字の後に配置された場合に @メンションを使用できないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-782"><span>We fixed an issue which could prevent an @ mention if the @ symbol was placed after certain characters</span></span></span></div>


- <div><span data-ttu-id="a8210-783"><span>@メンションを削除するとクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-783"><span>We fixed an issue which could sometimes cause a crash when deleting @ mentions</span></span></span></div>


- <div><span data-ttu-id="a8210-784"><span>コメント カードに絵文字が正しく表示されない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-784"><span>We fixed an issue which prevented emojis from displaying correctly in comment cards</span></span></span></div>


- <div><span data-ttu-id="a8210-785"><span>アクティブ​​ クリップボード​​でクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-785"><span>We fixed an issue with Active Clipboard which could sometimes result in a crash</span></span></span></div>


- <div><span data-ttu-id="a8210-786"><span>クイック アクセス ツール バーのボタンが機能しなくなることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-786"><span>We fixed an issue which could cause the Quick Access Toolbar buttons to stop working</span></span></span></div>


- <div><span data-ttu-id="a8210-787"><span>文書の書式設定プレビュー​​がバックグラウンドに切り替わらないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-787"><span>We fixed an issue which could prevent the Document Formatting Preview from switching to the background</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="a8210-788">OneNote</span><span class="sxs-lookup"><span data-stu-id="a8210-788">OneNote</span></span>

- <span data-ttu-id="a8210-789">Office テーマが黒に設定されている場合、セクションのドロップダウン リストにセクションの名前が空白で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-789">We fixed an issue where the names of sections appear blank in the section dropdown list when Office Theme is set to Black.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-790">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-790">Outlook</span></span>

- <div><span data-ttu-id="a8210-791"><span>Outlook が繰り返しフォーカスを取得して失うことがある送信イベントに関する問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-791"><span>We fixed an issue with Send Events which could cause Outlook to repeatedly gain and lose focus</span></span></span></div>


- <div><span data-ttu-id="a8210-792"><span>[フォルダーに返信を投稿] ショートカットが機能しない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-792"><span>We fixed an issue which prevented the Post Reply to Folder shortcut from working</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="a8210-793">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-793">PowerPoint</span></span>

- <div><span data-ttu-id="a8210-794"><span>共同作業の際に問題を引き起こすことがある保護ビューの問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-794"><span>We fixed an issue with Protected View which could sometimes cause problems when collaborating</span></span></span></div>


- <div><span data-ttu-id="a8210-795"><span>コメント ウィンドウのタスクが適切に表示されないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-795"><span>We fixed an issue which could prevent tasks in comment panes from displaying properly</span></span></span></div>


- <div><span data-ttu-id="a8210-796"><span>新しいスライドを挿入するときにクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-796"><span>We fixed an issue which could cause a crash when inserting new slides</span></span></span></div>


### <a name="user-lifecycle"></a><span data-ttu-id="a8210-797">ユーザーのライフサイクル</span><span class="sxs-lookup"><span data-stu-id="a8210-797">User Lifecycle</span></span>

- <div><span data-ttu-id="a8210-798"><span>サブスクリプション機能が消えることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-798"><span>We fixed an issue which could sometimes result in subscription features disappearing</span></span></span></div>


### <a name="word"></a><span data-ttu-id="a8210-799">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-799">Word</span></span>

- <div><span data-ttu-id="a8210-800"><span>ハイパーリンクに特定の文字が含まれている場合、ハイパーリンクが壊れることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-800"><span>We fixed an issue where hyperlinks could be broken if the hyperlink contained certain characters</span></span></span></div>


- <div><span data-ttu-id="a8210-801"><span>画像のコメントを表示するときに画像のサイズが不適切になることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-801"><span>We fixed an issue where images could be improperly sized when viewing a comment for that image</span></span></span></div>


- <div><span data-ttu-id="a8210-802"><span>箇条書きのドロップダウン メニューでクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-802"><span>We fixed an issue with the Bullet List drop down menu which could sometimes result in a crash</span></span></span></div>





## <a name="august-09-2019br"></a><span data-ttu-id="a8210-803">**2019 年 8 月 9 日**</span><span class="sxs-lookup"><span data-stu-id="a8210-803">**August 09, 2019**</span></span><br/>
<span data-ttu-id="a8210-804">バージョン 1909 (ビルド 12001.20000)</span><span class="sxs-lookup"><span data-stu-id="a8210-804">Version 1909 (Build 12001.20000)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="a8210-805">Excel 機能の更新</span><span class="sxs-lookup"><span data-stu-id="a8210-805">Excel Feature updates:</span></span>

- <span data-ttu-id="a8210-806">**共同作業がさらに簡単に:** 共同編集の改善とは、条件付き書式、セルのスタイルなどを使用して作業しているときに、ユーザーによる変更がシームレスに共同作業者のそれらと統合されるということを意味します。</span><span class="sxs-lookup"><span data-stu-id="a8210-806">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>


- <span data-ttu-id="a8210-807">**検索して楽しむ:** 目的のアイコンを簡単に検索できるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-807">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="a8210-808">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="a8210-808">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="office-suite-feature-updates"></a><span data-ttu-id="a8210-809">Office スイートの機能の更新</span><span class="sxs-lookup"><span data-stu-id="a8210-809">Office Suite Feature updates:</span></span>

- <span data-ttu-id="a8210-810">**新しい Office アプリのアイコン:** シンプルかつ高性能で、インテリジェントな Office のエクスペリエンスを反映するように、アプリのアイコンがリニューアルされました。</span><span class="sxs-lookup"><span data-stu-id="a8210-810">**New Office app icons:** Redesigned app icons to reflect the simple, powerful, and intelligent experiences of Office</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="a8210-811">Outlook 機能の更新</span><span class="sxs-lookup"><span data-stu-id="a8210-811">Outlook Feature updates:</span></span>

- <span data-ttu-id="a8210-812">**攻撃に対する高度な保護:** Office 365 Advanced Threat Protection を用いると、メールの件名、添付メッセージ、署名されたメッセージ、ネットワーク パスなどの範囲内のハイパーリンクを利用した攻撃から保護されます。</span><span class="sxs-lookup"><span data-stu-id="a8210-812">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>


- <span data-ttu-id="a8210-813">**検索して楽しむ:** 目的のアイコンを簡単に検索できるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-813">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="a8210-814">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="a8210-814">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="a8210-815">PowerPoint 機能の更新</span><span class="sxs-lookup"><span data-stu-id="a8210-815">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="a8210-816">**検索して楽しむ:** 目的のアイコンを簡単に検索できるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-816">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="a8210-817">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="a8210-817">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="a8210-818">Word 機能の更新</span><span class="sxs-lookup"><span data-stu-id="a8210-818">Word Feature updates:</span></span>

- <span data-ttu-id="a8210-819">**他のユーザーがすばやく変更を確認する:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="a8210-819">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


- <span data-ttu-id="a8210-820">**検索して楽しむ:** 目的のアイコンを簡単に検索できるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-820">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="a8210-821">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="a8210-821">And when you're selecting, the Insert button tells you how many you've picked.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="a8210-822">セキュリティ以外の更新プログラム:</span><span class="sxs-lookup"><span data-stu-id="a8210-822">Non-security updates:</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-823">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-823">Outlook</span></span>

- <div><span data-ttu-id="a8210-824"><span>会議がキャンセルされた後に、会議の受信者が 2 つの通知を受け取る原因となっていた問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-824"><span>We fixed an issue which caused meeting recipients to receive two notifications after a meeting was cancelled</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="a8210-825">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-825">PowerPoint</span></span>

- <div><span data-ttu-id="a8210-826"><span>図形とアイコンの [線なし]、[塗りつぶしなし] をユーザーが選択したときに、クラッシュを引き起こす問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-826"><span>We fixed an issue which could cause a crash when the user selected No Outline or No Fill for Shapes and Icons</span></span></span></div>





## <a name="august-02-2019br"></a><span data-ttu-id="a8210-827">**2019 年 8 月 2 日**</span><span class="sxs-lookup"><span data-stu-id="a8210-827">**August 02, 2019**</span></span><br/>
<span data-ttu-id="a8210-828">バージョン 1908 (ビルド 11929.20002)</span><span class="sxs-lookup"><span data-stu-id="a8210-828">Version 1908 (Build 11929.20002)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="a8210-829">Excel 機能の更新</span><span class="sxs-lookup"><span data-stu-id="a8210-829">Excel Feature updates:</span></span>

- <span data-ttu-id="a8210-830">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="a8210-830">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="a8210-831">**ドキュメントに機密ラベルを適用する:** ファイルとメールに機密ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="a8210-831">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="a8210-832">Outlook 機能の更新</span><span class="sxs-lookup"><span data-stu-id="a8210-832">Outlook Feature updates:</span></span>

- <span data-ttu-id="a8210-833">**ドキュメントに機密ラベルを適用する:** ファイルとメールに機密ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="a8210-833">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="a8210-834">PowerPoint 機能の更新</span><span class="sxs-lookup"><span data-stu-id="a8210-834">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="a8210-835">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="a8210-835">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="a8210-836">**ドキュメントに機密ラベルを適用する:** ファイルとメールに機密ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="a8210-836">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="a8210-837">Word 機能の更新</span><span class="sxs-lookup"><span data-stu-id="a8210-837">Word Feature updates:</span></span>

- <span data-ttu-id="a8210-838">**ファイルを変換してアクセシビリティを向上させる:** ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="a8210-838">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="a8210-839">**別の言葉で伝える:** 別の言葉で伝えたいときに、[書き換え] でお助けします。</span><span class="sxs-lookup"><span data-stu-id="a8210-839">**Say it another way:** When you want to say it differently, Rewrite is there to help.</span></span> <span data-ttu-id="a8210-840">[書き換え] では、フレーズを洗練させるための別の言葉遣いを提供します。</span><span class="sxs-lookup"><span data-stu-id="a8210-840">Rewrite offers alternatives for finessing your phrases.</span></span>


- <span data-ttu-id="a8210-841">**ドキュメントに機密ラベルを適用する:** ファイルとメールに機密ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="a8210-841">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="a8210-842">セキュリティ以外の更新プログラム:</span><span class="sxs-lookup"><span data-stu-id="a8210-842">Non-security updates:</span></span>

### <a name="access"></a><span data-ttu-id="a8210-843">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-843">Access</span></span>
- <span data-ttu-id="a8210-844">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-844">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-845">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-845">Excel</span></span>

- <div><span data-ttu-id="a8210-846"><span>PDF に印刷するときに [&quot;すべてのラベルを繰り返す&quot;] が適用されているかのように表示されていた問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-846"><span>We fixed an issue which made it appear as though &quot;repeat all labels&quot; was applied when printing to a PDF</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="a8210-847">Office スイート</span><span class="sxs-lookup"><span data-stu-id="a8210-847">Office Suite</span></span>

- <div><span data-ttu-id="a8210-848"><span>デスクトップからドキュメントを開けないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-848"><span>We fixed an issue which could have prevented users from opening a document from the desktop</span></span></span></div>

- <div><span data-ttu-id="a8210-849"><span>[&quot;別のインストールが進行中です&quot;] という誤ったエラー メッセージによりアップグレードに失敗することがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-849"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="a8210-850"><span>セキュリティ更新プログラムがインストールされるときに、エラー メッセージが表示されることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-850"><span>We fixed an issue where a user could see error messages when security updates are installed</span></span></span></div>

- <div><span data-ttu-id="a8210-851"><span>カーソルが消えることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-851"><span>We fixed an issue which could cause the cursor to disappear</span></span></span></div>

- <div><span data-ttu-id="a8210-852"><span>既定で [ホーム] タブではなく [描画] タブが設定されていることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-852"><span>We fixed an issue where a user could be defaulted to the draw tab instead of the home tab</span></span></span></div>

- <div><span data-ttu-id="a8210-853"><span>大きなツリー ビューがクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-853"><span>We fixed an issue where large tree views could result in a crash</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="a8210-854">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-854">Outlook</span></span>

- <div></div><span data-ttu-id="a8210-855"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">パスワード入力画面が繰り返し表示されることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-855"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can cause repeated password prompts</span></span></span>

- <div><span data-ttu-id="a8210-856"><span>メール アドレスが正しくクエリされないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-856"><span>We fixed an issue which could prevent an email address from being queried correctly</span></span></span></div>

- <div><span data-ttu-id="a8210-857"><span>以前のバージョンの Outlook で作成した予定表アイテムを開けないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-857"><span>We fixed an issue which could prevent users from opening calendar items created by legacy versions of Outlook</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="a8210-858">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-858">PowerPoint</span></span>

- <div><span data-ttu-id="a8210-859"><span>一部のアニメーションが開始されないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-859"><span>We fixed an issue which could prevent some animations from starting</span></span></span></div>

### <a name="project"></a><span data-ttu-id="a8210-860">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-860">Project</span></span>
- <span data-ttu-id="a8210-861">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-861">Various performance and stability fixes</span></span>

### <a name="word"></a><span data-ttu-id="a8210-862">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-862">Word</span></span>

- <div><span data-ttu-id="a8210-863"><span>コメントへの返信が順番に表示されないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-863"><span>We fixed an issue where replies to comments could appear out of order</span></span></span></div>

- <div><span data-ttu-id="a8210-864"><span>状況によって、コメントの代わりにヒントが表示されることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-864"><span>We fixed an issue where in some situations, hints would be displayed instead of comments</span></span></span></div>

- <div><span data-ttu-id="a8210-865"><span>新しいコメントを追加しようとしたときに [変更履歴] ウィンドウが表示されることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-865"><span>We fixed an issue where the Revisions Pane could display when the user tried to add a new comment</span></span></span></div>

- <div><span data-ttu-id="a8210-866"><span>[元に戻す] ドロップダウン リストが表示されないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-866"><span>We fixed an issue which could prevent the undo dropdown list from appearing</span></span></span></div>

- <div><span data-ttu-id="a8210-867"><span>コメントを追加できないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="a8210-867"><span>We fixed an issue which could prevent comments from being added</span></span></span></div>


## <a name="july-26-2019"></a><span data-ttu-id="a8210-868">2019 年 7 月 26 日</span><span class="sxs-lookup"><span data-stu-id="a8210-868">July 26, 2019</span></span>
<span data-ttu-id="a8210-869">バージョン 1908 (ビルド 11916.20000)</span><span class="sxs-lookup"><span data-stu-id="a8210-869">Version 1908 (build 11916.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a8210-870">新機能:</span><span class="sxs-lookup"><span data-stu-id="a8210-870">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="a8210-871">Word、Excel、PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-871">Word, Excel, PowerPoint</span></span>

#### <a name="create-more-accessible-pdfs"></a><span data-ttu-id="a8210-872">よりアクセシビリティの高い PDF ファイルを作成する</span><span class="sxs-lookup"><span data-stu-id="a8210-872">Create more accessible PDFs</span></span>

<span data-ttu-id="a8210-873">PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="a8210-873">Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a8210-874">主な修正:</span><span class="sxs-lookup"><span data-stu-id="a8210-874">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="a8210-875">すべて</span><span class="sxs-lookup"><span data-stu-id="a8210-875">All</span></span>

- <span data-ttu-id="a8210-876">Office の更新後に、Office のファイルの種類の関連付けとアイコンが破損する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-876">We fixed an issue where file type association and icons for Office could sometimes break after an Office Update</span></span>

### <a name="word"></a><span data-ttu-id="a8210-877">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-877">Word</span></span> 
- <span data-ttu-id="a8210-878">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-878">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-879">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-879">Excel</span></span>
- <span data-ttu-id="a8210-880">グラフを移動するとクラッシュする場合がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-880">We fixed an issue where moving a chart could sometimes result in a crash</span></span>
- <span data-ttu-id="a8210-881">グラフの種類を変更した後にグラフ オブジェクトからブック オブジェクトを取得するとエラーが発生することがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-881">We fixed an issue where to get Workbook object from Chart object after changing chart types could sometimes result in an error</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-882">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-882">PowerPoint</span></span>
- <span data-ttu-id="a8210-883">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-883">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-884">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-884">Outlook</span></span>
- <span data-ttu-id="a8210-885">シンプル リボンで、無効にしてあるコントロールが淡色表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-885">We fixed an issue where in simplified ribbon, a disabled control could sometimes not be greyed out in the ribbon</span></span>

### <a name="access"></a><span data-ttu-id="a8210-886">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-886">Access</span></span>
- <span data-ttu-id="a8210-887">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="a8210-887">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a8210-888">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-888">Project</span></span>
- <span data-ttu-id="a8210-889">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-889">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-19-2019"></a><span data-ttu-id="a8210-890">2019 年 7 月 19 日</span><span class="sxs-lookup"><span data-stu-id="a8210-890">July 19, 2019</span></span>
<span data-ttu-id="a8210-891">バージョン 1908 (ビルド 11911.20000)</span><span class="sxs-lookup"><span data-stu-id="a8210-891">Version 1908 (build 11911.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a8210-892">新機能:</span><span class="sxs-lookup"><span data-stu-id="a8210-892">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="a8210-893">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-893">Word</span></span>

#### <a name="learn-what-acronyms-mean-when-you-read-in-word-online"></a><span data-ttu-id="a8210-894">Word Online の文書で使われている略語の意味を確認する</span><span class="sxs-lookup"><span data-stu-id="a8210-894">Learn what Acronyms mean when you read in Word Online</span></span>

<span data-ttu-id="a8210-895">略語を見つけたら、組織内のデータを使用してそれを定義しようとします。</span><span class="sxs-lookup"><span data-stu-id="a8210-895">When you encounter an Acronym, we'll try to define it using data from within your organization.</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="a8210-896">主な修正:</span><span class="sxs-lookup"><span data-stu-id="a8210-896">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a8210-897">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-897">Word</span></span> 
- <span data-ttu-id="a8210-898">BookMarkEnd タグが欠けているという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-898">We fixed an issue which BookMarkEnd tag was missing.</span></span>
- <span data-ttu-id="a8210-899">ユーザーが特殊文字を入力しているときに、フォントの選択が変更される場合があるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-899">We fixed an issue where the font selection could change while the user was typing special characters</span></span>
- <span data-ttu-id="a8210-900">新しいコメント カードに空白の返信が発生することがあるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-900">We fixed an issue which could sometimes cause blank replies to a new comment card</span></span>
- <span data-ttu-id="a8210-901">メールを共有すると、書式設定が失われる場合があるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-901">We fixed an issue which could cause formatting to be lost when sharing an email</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-902">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-902">Excel</span></span>
- <span data-ttu-id="a8210-903">範囲の広い配列がクラッシュすることがあるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-903">We fixed an issue where an array with a large range could sometimes cause a crash</span></span>
- <span data-ttu-id="a8210-904">フィルター処理された範囲からデータをコピーする場合のパフォーマンスを大幅に向上しました</span><span class="sxs-lookup"><span data-stu-id="a8210-904">We significantly improved the performance of copying data from filtered ranges</span></span>
- <span data-ttu-id="a8210-905">ファイル名に特殊文字が含まれていると、一部のファイルを開くことができないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-905">We fixed an issue which prevented some files from opening if the filenames contained special characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-906">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-906">PowerPoint</span></span>
- <span data-ttu-id="a8210-907">PowerPoint で新しく作成したセクションのセクション名が既定で選択されていないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-907">We fixed an issue where section name was not selected by default for newly created section in PowerPoint.</span></span>
- <span data-ttu-id="a8210-908">4:3 ディスプレイを使用すると、UI の使用が困難になることがあるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-908">We fixed an issue which could cause the UI to become difficult to use when using a 4:3 display</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-909">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-909">Outlook</span></span>
- <span data-ttu-id="a8210-910">利用可能な会議室がリストに表示されないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-910">We fixed an issue which could prevent available rooms from being listed</span></span>
- <span data-ttu-id="a8210-911">一部の POP3 ユーザーの HTML 形式を設定できないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-911">We fixed an issue which prevented HTML formatting for some POP3 users</span></span>

### <a name="access"></a><span data-ttu-id="a8210-912">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-912">Access</span></span>
- <span data-ttu-id="a8210-913">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="a8210-913">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a8210-914">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-914">Project</span></span>
- <span data-ttu-id="a8210-915">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-915">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-12-2019"></a><span data-ttu-id="a8210-916">2019 年 7 月 12 日</span><span class="sxs-lookup"><span data-stu-id="a8210-916">July 12, 2019</span></span>
<span data-ttu-id="a8210-917">バージョン 1907 (ビルド 11901.20038)</span><span class="sxs-lookup"><span data-stu-id="a8210-917">Version 1907 (build 11901.20038)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a8210-918">新機能:</span><span class="sxs-lookup"><span data-stu-id="a8210-918">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-919">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-919">PowerPoint</span></span>
 
#### <a name="use-ink-replay-in-your-presentations"></a><span data-ttu-id="a8210-920">プレゼンテーションでインクの再生を使用する</span><span class="sxs-lookup"><span data-stu-id="a8210-920">Use ink replay in your presentations</span></span>
 
<span data-ttu-id="a8210-921">PowerPoint でインクの再生アニメーションを適用して、プレゼンテーションの表現力とコミュニケーション力を高めます。</span><span class="sxs-lookup"><span data-stu-id="a8210-921">Apply a replay animation for ink in PowerPoint to express and communicate more in presentations.</span></span> 

## <a name="notable-fixes"></a><span data-ttu-id="a8210-922">主な修正:</span><span class="sxs-lookup"><span data-stu-id="a8210-922">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a8210-923">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-923">Word</span></span> 
- <span data-ttu-id="a8210-924">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-924">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-925">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-925">Excel</span></span>
- <span data-ttu-id="a8210-926">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-926">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-927">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-927">PowerPoint</span></span>
- <span data-ttu-id="a8210-928">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-928">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-929">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-929">Outlook</span></span>
- <span data-ttu-id="a8210-930">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-930">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="a8210-931">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-931">Access</span></span>
- <span data-ttu-id="a8210-932">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="a8210-932">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a8210-933">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-933">Project</span></span>
- <span data-ttu-id="a8210-934">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-934">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-5-2019"></a><span data-ttu-id="a8210-935">2019 年 7 月 5 日</span><span class="sxs-lookup"><span data-stu-id="a8210-935">July 5, 2019</span></span>
<span data-ttu-id="a8210-936">バージョン 1907 (ビルド 11901.20018)</span><span class="sxs-lookup"><span data-stu-id="a8210-936">Version 1907 (build 11901.20018)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a8210-937">新機能:</span><span class="sxs-lookup"><span data-stu-id="a8210-937">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="a8210-938">Word、Excel、PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-938">Word, Excel, PowerPoint</span></span>

#### <a name="sketchy-shapes"></a><span data-ttu-id="a8210-939">Sketchy で描く!</span><span class="sxs-lookup"><span data-stu-id="a8210-939">Sketchy Shapes!</span></span>

<span data-ttu-id="a8210-940">プレゼンテーションを作成中ですか。</span><span class="sxs-lookup"><span data-stu-id="a8210-940">In the middle of drafting a presentation?</span></span> <span data-ttu-id="a8210-941">まだ作業中であることを示す Sketchy スタイルを適用します。</span><span class="sxs-lookup"><span data-stu-id="a8210-941">Apply the sketchy style to show that you're still working on it.</span></span> <span data-ttu-id="a8210-942">これを使用すると、自由形式や手描きの図形に変えることなく、オブジェクトに個人的なタッチを与えることができます。</span><span class="sxs-lookup"><span data-stu-id="a8210-942">It gives a personal touch to your objects without turning it into a free form, hand-drawn shapes.</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-943">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-943">Excel</span></span>

- <span data-ttu-id="a8210-944">**ファイル共有の高速化**: ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="a8210-944">**Faster file sharing**: Share your documents right from the recently used list without having to open the file.</span></span>
### <a name="powerpoint"></a><span data-ttu-id="a8210-945">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-945">PowerPoint</span></span>

- <span data-ttu-id="a8210-946">**アクセスを容易にするため、[印刷] メニューに [配布資料にスライド番号を印刷する] を移動しました:** 配布資料が指定されているときに、[印刷] > [印刷レイアウト] ドロップダウンの順にクリックすると見つかります。</span><span class="sxs-lookup"><span data-stu-id="a8210-946">**The setting to Print Slide Numbers in Handouts has been moved to the Print Menu for easier access:**  Find it in the Print > Print Layout dropdown when a Handout layout is selected.</span></span> <span data-ttu-id="a8210-947">これにより、プレゼンテーションごとに簡単に設定を切り替えることもできます。</span><span class="sxs-lookup"><span data-stu-id="a8210-947">This also allows the setting to be easily toggled per presentation.</span></span> [<span data-ttu-id="a8210-948">詳細情報</span><span class="sxs-lookup"><span data-stu-id="a8210-948">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="a8210-949">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="a8210-949">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="word"></a><span data-ttu-id="a8210-950">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-950">Word</span></span>

- <span data-ttu-id="a8210-951">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="a8210-951">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a8210-952">主な修正:</span><span class="sxs-lookup"><span data-stu-id="a8210-952">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="a8210-953">すべて</span><span class="sxs-lookup"><span data-stu-id="a8210-953">All</span></span>
- <span data-ttu-id="a8210-954">リボンのキー ヒントのパフォーマンスが大幅に改善されました</span><span class="sxs-lookup"><span data-stu-id="a8210-954">We significantly improved the performance of Ribbon KeyTips</span></span>
- <span data-ttu-id="a8210-955">「今後のリリース予定を確認」ダイアログが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-955">We fixed an issue which prevented the "See what's coming soon" dialog from being displayed properly</span></span>
- <span data-ttu-id="a8210-956">共著ギャラリーのポップアップで写真の位置がずれてしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-956">We fixed an issue which could cause Photos to be misaligned in the Co-auth Gallery flyout</span></span>

### <a name="word"></a><span data-ttu-id="a8210-957">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-957">Word</span></span> 
- <span data-ttu-id="a8210-958">新しいコメントが追加されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-958">We fixed an issue which could sometimes prevent new comments from being added</span></span>
- <span data-ttu-id="a8210-959">表がクラッシュすることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-959">We fixed an issue where tables could sometimes cause a crash</span></span>
- <span data-ttu-id="a8210-960">無効なデータが差し込み印刷の最後に追加されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-960">We fixed an issue where invalid data could sometimes be added to the end of a mail merge</span></span>
- <span data-ttu-id="a8210-961">一部の LaTeX 数式が正しく表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-961">We fixed an issue which could cause some LaTeX equations to render incorrectly</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-962">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-962">Excel</span></span>
- <span data-ttu-id="a8210-963">グラフの種類を変更するとランタイム例外が発生することがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-963">We fixed an issue where changing chart types could sometimes result in a runtime exception</span></span>
- <span data-ttu-id="a8210-964">複数のウィンドウを開いたときに正しくないリボンが表示されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-964">We fixed an issue where the incorrect ribbon could be displayed when multiple windows were open</span></span>
- <span data-ttu-id="a8210-965">マクロがブックの 2 番目のインスタンスを開いたときにエラーが発生することがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-965">We fixed an issue which could cause an error when a macro opened a second instance of a workbook</span></span>
- <span data-ttu-id="a8210-966">ブックを開いたり作成したりするとき、またはブックを切り替えるときにクラッシュすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-966">We fixed an issue which could cause a crash when opening or creating a workbook, or switching between workbooks</span></span>
- <span data-ttu-id="a8210-967">ユーザーが Word で作成した PDF を Teams で開くことができない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-967">We fixed an issue preventing users from opening a PDF created from Word in Teams</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-968">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-968">PowerPoint</span></span>
- <span data-ttu-id="a8210-969">PDF にエクスポートすると、グラフの品質が低下する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-969">We fixed an issue which would degrade the quality of a chart when exported to a pdf</span></span>
- <span data-ttu-id="a8210-970">中心までの距離を示すヒントが表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-970">We fixed an issue which prevented a tooltip indicating the distance to center from displaying</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-971">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-971">Outlook</span></span>
- <span data-ttu-id="a8210-972">ディスクの領域不足エラーが表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-972">We fixed an issue which could sometimes prevent a Disk Full error to be displayed</span></span>
- <span data-ttu-id="a8210-973">会議出席依頼を更新する際に添付ファイルが複製されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-973">We fixed an issue which could cause attachments to become duplicated when updating a meeting request</span></span>

### <a name="access"></a><span data-ttu-id="a8210-974">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-974">Access</span></span>
- <span data-ttu-id="a8210-975">一部のクエリが大きい整数値を返さない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-975">We fixed an issue which prevented some queries from returning large integer values</span></span>
- <span data-ttu-id="a8210-976">SQL テキストボックスが編集できなくなることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-976">We fixed an issue which could make the sql textbox uneditable</span></span>
- <span data-ttu-id="a8210-977">一部の高 DPI ディスプレイでは、ヒントが見づらいことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-977">We fixed an issue where tooltips could be difficult to see on some High DPI displays</span></span>

### <a name="project"></a><span data-ttu-id="a8210-978">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-978">Project</span></span>
- <span data-ttu-id="a8210-979">新しいタスクでフラグの値が編集できなくなることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-979">We fixed an issue which could cause flag values to become uneditable in new tasks</span></span>
- <span data-ttu-id="a8210-980">ステータスの更新によって割り当てとタスクの実際の開始日が不適切に設定されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-980">We fixed an issue which could cause a status update to improperly set Actual Start Date on Assignments and Tasks</span></span>
- <span data-ttu-id="a8210-981">一部のリソースが間違って割り当て超過に表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-981">We fixed an issue which could cause some resources to incorreclty appear overallocated</span></span>
- <span data-ttu-id="a8210-982">ラグが追加され、小数点の記号がカンマで、サーバーに接続されていると TaskDependencies Add メソッドが失敗することがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-982">We fixed an issue where the TaskDependencies Add method could fail when Lag is added, the decimal separator is a comma, and when connected to a server</span></span>
- <span data-ttu-id="a8210-983">CSOM を使用してローカル ユーザー設定フィールドの参照テーブルの値を更新すると PCS がクラッシュすることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-983">We fixed an issue where updating local custom field lookup table values via CSOM could crash PCS</span></span>
- <span data-ttu-id="a8210-984">作業時間の合計値に小数点が含まれる場合に正しく表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-984">We fixed an issue where the total work values may appear incorrect if they contain a decimal</span></span>

</BR></BR>

## <a name="june-28-2019"></a><span data-ttu-id="a8210-985">2019 年 6 月 28 日</span><span class="sxs-lookup"><span data-stu-id="a8210-985">June 28, 2019</span></span>
<span data-ttu-id="a8210-986">バージョン 1907 (ビルド 11819.20002)</span><span class="sxs-lookup"><span data-stu-id="a8210-986">Version 1907 (build 11819.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a8210-987">新機能:</span><span class="sxs-lookup"><span data-stu-id="a8210-987">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-988">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-988">Excel</span></span>

- <span data-ttu-id="a8210-989">**Power Query の機能強化を使用して素早くコーディングする:** オートコンプリートと構文の色分けを使用して、素早くコーディングを完了します。</span><span class="sxs-lookup"><span data-stu-id="a8210-989">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="a8210-990">関数、列、パラメーターも簡単に見つけることができます</span><span class="sxs-lookup"><span data-stu-id="a8210-990">Easily discover functions, columns, and parameters, too</span></span>

- <span data-ttu-id="a8210-991">**類似列のテーブルを結合する:** 取得と変換 (Power Query) では、テーブルを結合するために列を比較するときに、近似テキスト マッチング ロジック (あいまい一致とも呼ばれる) が使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="a8210-991">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span>

### <a name="word"></a><span data-ttu-id="a8210-992">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-992">Word</span></span>

- <span data-ttu-id="a8210-993">**共同編集の改善:** 共同編集時の信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-993">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>
 
### <a name="word-excel-powerpoint-and-visio"></a><span data-ttu-id="a8210-994">Word、Excel、PowerPoint、Visio</span><span class="sxs-lookup"><span data-stu-id="a8210-994">Word, Excel, PowerPoint, and Visio</span></span>

#### <a name="recommended-documents"></a><span data-ttu-id="a8210-995">推奨されるドキュメント</span><span class="sxs-lookup"><span data-stu-id="a8210-995">Recommended Documents</span></span>

<span data-ttu-id="a8210-996">推奨される関連アクティビティを含むドキュメントをご確認ください。</span><span class="sxs-lookup"><span data-stu-id="a8210-996">Find documents with relevant activity recommended to you.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a8210-997">主な修正:</span><span class="sxs-lookup"><span data-stu-id="a8210-997">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a8210-998">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-998">Word</span></span> 
- <span data-ttu-id="a8210-999">一部の .DOC を開くことができない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-999">We fixed an issue which could prevent some .DOC files from opening</span></span>
- <span data-ttu-id="a8210-1000">コメントが正常に読み込まれない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1000">We fixed an issue which could have prevented comments from loading properly</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-1001">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-1001">Excel</span></span>
- <span data-ttu-id="a8210-1002">Power Query のパフォーマンスが向上しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1002">We improved the performance of Power Queries</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-1003">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-1003">PowerPoint</span></span>
- <span data-ttu-id="a8210-1004">画面のちらつきの原因となる、Surface デバイスでのペン使用に関連する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1004">We fixed an issue related to using a pen on a Surface device which could cause the screen to flicker</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1005">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1005">Outlook</span></span>
- <span data-ttu-id="a8210-1006">会議に変換すると、予定の空き時間情報が変更される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1006">We fixed an issue which could change the free/busy status of an appointment when converted to a meeting</span></span>
- <span data-ttu-id="a8210-1007">電子メールがアドホック テンプレートで保護されている場合に、不適切なテンプレートと説明が表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1007">We fixed an issue where the wrong template and description would be displayed when an e-mail was protected with an ad-hoc template</span></span>

### <a name="access"></a><span data-ttu-id="a8210-1008">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-1008">Access</span></span>
- <span data-ttu-id="a8210-1009">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1009">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a8210-1010">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-1010">Project</span></span>
- <span data-ttu-id="a8210-1011">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1011">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-21-2019"></a><span data-ttu-id="a8210-1012">2019 年 6 月 21 日</span><span class="sxs-lookup"><span data-stu-id="a8210-1012">June 21, 2019</span></span>
<span data-ttu-id="a8210-1013">バージョン 1907 (ビルド 11815.20002)</span><span class="sxs-lookup"><span data-stu-id="a8210-1013">Version 1907 (build 11815.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a8210-1014">新機能:</span><span class="sxs-lookup"><span data-stu-id="a8210-1014">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1015">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1015">Outlook</span></span>

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a><span data-ttu-id="a8210-1016">Outlook デスクトップにおける黒のテーマでの濃色モード</span><span class="sxs-lookup"><span data-stu-id="a8210-1016">Dark Mode for Black Theme in Outlook Desktop</span></span>

<span data-ttu-id="a8210-1017">[濃色] モードで黒のテーマを使用しているユーザーには、電子メールを読むときに [閲覧] ウィンドウは暗く表示され、メールを作成するときも同様に表示されます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1017">With dark mode, users in black theme will now also see the reading pane with a dark background when reading emails, and the compose experience with a dark background when writing emails.</span></span> <span data-ttu-id="a8210-1018">ユーザーが明るい背景でメッセージがどのように見えるかを確認する場合に備えて、[閲覧] ウィンドウとリボンに [太陽/月] トグルがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-1018">There is a sun/moon toggle on the reading pane and in the ribbon in case users want to preview what the message looks like with a light background instead.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a8210-1019">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="a8210-1019">Getting Started:</span></span>

1. <span data-ttu-id="a8210-1020">[黒のテーマ] に切り替えると、既定では濃色モードになります。</span><span class="sxs-lookup"><span data-stu-id="a8210-1020">Turn on black theme and dark mode will be on by default.</span></span>
2. <span data-ttu-id="a8210-1021">(閲覧ウィンドウとリボンにある) [月/太陽] トグルを使用して、濃色モードでないユーザーにメッセージがどのように見えるかを表示します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1021">Use the moon/sun toggle (in the reading pane and in the ribbon) to preview what the message looks like for users not in dark mode</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a8210-1022">次の操作を試してみてください</span><span class="sxs-lookup"><span data-stu-id="a8210-1022">Scenarios to Try</span></span>

1. <span data-ttu-id="a8210-1023">濃色モードでメールを読みます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1023">Read emails in dark mode.</span></span> <span data-ttu-id="a8210-1024">何も見えない場合は、[閲覧] ウィンドウの [太陽] トグルを使用して、背景を明るくします。</span><span class="sxs-lookup"><span data-stu-id="a8210-1024">If you are unable to read something, use the sun toggle in the Reading Pane to switch to a light background.</span></span> 
2. <span data-ttu-id="a8210-1025">[濃色] モードでメールを作成します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1025">Compose emails in dark mode.</span></span> <span data-ttu-id="a8210-1026">リボンの [太陽] トグルを使用して、メッセージが明るい背景でどのように見えるかを確認します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1026">Preview what your message will look like with a light background by using the sun toggle in the ribbon.</span></span> 

<span data-ttu-id="a8210-1027">正常に表示されないメールが見つかった場合は、(添付ファイルとして) OutlookDarkModeFail@service.microsoft.com に送信してください</span><span class="sxs-lookup"><span data-stu-id="a8210-1027">If you encounter any emails that don't render properly, please send them (as an attachment) to OutlookDarkModeFail@service.microsoft.com</span></span>

#### <a name="get-location-suggestions"></a><span data-ttu-id="a8210-1028">場所の候補を取得する</span><span class="sxs-lookup"><span data-stu-id="a8210-1028">Get location suggestions</span></span>

<span data-ttu-id="a8210-1029">入力を開始すると、Outlook で一致する場所が検索されます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1029">Start typing and Outlook will look for matching locations.</span></span>

<span data-ttu-id="a8210-1030">予定や会議を作成するときは、[場所] フィールドに適用されます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1030">This applies to the Location field when creating Appointments and Meetings.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a8210-1031">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="a8210-1031">Getting Started:</span></span>

- <span data-ttu-id="a8210-1032">Outlook で O365 または Outlook.com の予定表に予定や会議を作成します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1032">Create an Appointment or Meeting on an O365 or Outlook.com calendar in Outlook.</span></span> 
- <span data-ttu-id="a8210-1033">[場所] フィールドをクリックして、入力を開始します...。</span><span class="sxs-lookup"><span data-stu-id="a8210-1033">Click into the Location field and start typing…</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a8210-1034">次の操作を試してみてください</span><span class="sxs-lookup"><span data-stu-id="a8210-1034">Scenarios to Try</span></span>

<span data-ttu-id="a8210-1035">会議に会議室を追加するときは、[会議室の検索] アドインやアドレス帳を使用するのではなく、[場所] フィールドをクリックします。</span><span class="sxs-lookup"><span data-stu-id="a8210-1035">When adding a conference room to a meeting, click into Location field, rather than using Room Finder add-in or Address Book.</span></span>
<span data-ttu-id="a8210-1036">レストラン、喫茶店、歯科医院といった公共の場所での予定がある場合は、新しいピッカーを使用して正確な位置を見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1036">For appointments at a physical place with a public location - like a restaurant, coffee shop, or even your dentist's office - try finding the exact location using the new picker.</span></span> <span data-ttu-id="a8210-1037">こうすることで、外出するときに Outlook Mobile で通知を受け取ることができます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1037">This way, you'll be able to get notified on Outlook Mobile when it's time to leave.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a8210-1038">主な修正:</span><span class="sxs-lookup"><span data-stu-id="a8210-1038">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="a8210-1039">すべて</span><span class="sxs-lookup"><span data-stu-id="a8210-1039">All</span></span>
- <span data-ttu-id="a8210-1040">オフラインで [検索] ボックスが有効なままになる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1040">We fixed an issue which would keep the Search Box enabled while offline</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1041">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1041">Word</span></span> 
- <span data-ttu-id="a8210-1042">キーボード フォーカスが表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1042">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>
- <span data-ttu-id="a8210-1043">新しいドキュメントにテキストを貼り付けたときに、テキストが間違えて配置される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1043">We fixed an issue where text pasted into a new document could sometimes have the wrong text alignment</span></span>
- <span data-ttu-id="a8210-1044">コンピューターを中断した後に、一部のユーザーが変更を保存できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1044">We fixed an issue which could prevent some users from saving changes after suspending their computer</span></span>
- <span data-ttu-id="a8210-1045">特定の場合に、選択したページの代わりにドキュメント全体が印刷される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1045">We fixed an issue where in certain cases an entire document would be printed instead of the selected range</span></span>
- <span data-ttu-id="a8210-1046">小さなディスプレイでコメントが読みにくくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1046">We fixed an issue which could make comments difficult to read on smaller displays</span></span>
- <span data-ttu-id="a8210-1047">デバイスにキャプチャするときにクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1047">We fixed an issue which could cause a crash when capturing to a device</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-1048">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-1048">Excel</span></span>
- <span data-ttu-id="a8210-1049">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1049">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-1050">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-1050">PowerPoint</span></span>
- <span data-ttu-id="a8210-1051">キーボード フォーカスが表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1051">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1052">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1052">Outlook</span></span>
- <span data-ttu-id="a8210-1053">有効ではないときにアドインが誤って有効になっていると表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1053">We fixed an issue which could incorrectly display an add-in as being enabled when it was not.</span></span>
- <span data-ttu-id="a8210-1054">多数の保持ポリシーが表示されていない場合、ユーザーがすべての保持ポリシーを表示できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1054">We fixed an issue which would prevent a customer from viewing all retention policies if there were a large number of them</span></span>

### <a name="access"></a><span data-ttu-id="a8210-1055">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-1055">Access</span></span>
- <span data-ttu-id="a8210-1056">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1056">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a8210-1057">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-1057">Project</span></span>
- <span data-ttu-id="a8210-1058">さまざまなパフォーマンスと安定性に関する修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1058">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-14-2019"></a><span data-ttu-id="a8210-1059">2019 年 6 月 14 日</span><span class="sxs-lookup"><span data-stu-id="a8210-1059">June 14, 2019</span></span>
<span data-ttu-id="a8210-1060">バージョン 1907 (ビルド 11807.20000)</span><span class="sxs-lookup"><span data-stu-id="a8210-1060">Version 1907 (build 11807.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a8210-1061">主な修正:</span><span class="sxs-lookup"><span data-stu-id="a8210-1061">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1062">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1062">Word</span></span> 
- <span data-ttu-id="a8210-1063">OneDrive に保存しているときにユーザーがサインインするのを妨げていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="a8210-1063">We fixed an issue which could prevent a user from signing in when saving to OneDrive</span></span>
- <span data-ttu-id="a8210-1064">アクセス制限モード中にユーザーによる SharePoint のプロパティの変更が妨げられていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="a8210-1064">We fixed an issue where a user could be prevented from changing SharePoint properties while in restricted access mode</span></span>
- <span data-ttu-id="a8210-1065">余白を調整しているときにヘッダーやフッターの内容が変更されてしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="a8210-1065">We fixed an issue where header and footer content could change when adjusting margins</span></span>
- <span data-ttu-id="a8210-1066">Web ビューに切り替えているときに書式設定が崩れてしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="a8210-1066">We fixed an issue where formatting could break when switching to web view</span></span>
- <span data-ttu-id="a8210-1067">SharePoint で開いたときにユーザーによるカスタム フィールドの使用を妨げていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="a8210-1067">We fixed an issue which could prevent a user from using custom fields when opened from SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-1068">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-1068">Excel</span></span>
- <span data-ttu-id="a8210-1069">フィルター処理された行を削除するときのパフォーマンスの問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="a8210-1069">We fixed a performance issue when deleting rows of a filtered set</span></span>
- <span data-ttu-id="a8210-1070">時々、保護ビューでマウスをちらつかせる原因になっていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="a8210-1070">We fixed an issue which could sometimes cause the mouse to flicker in protected view</span></span>
- <span data-ttu-id="a8210-1071">系列を削除しているときにクラッシュを引き起こしていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="a8210-1071">We fixed an issue which could have caused a crash when deleting a series</span></span>
- <span data-ttu-id="a8210-1072">利用できなかった場合に一部のユーザーがバージョン履歴を追加するオプションを使用していたところの問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="a8210-1072">We fixed an issue where some users would have the option to add version history when that was not available</span></span>
- <span data-ttu-id="a8210-1073">スプレッドシート比較ツールを使用しているときに例外を引き起こしていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="a8210-1073">We fixed an issue which could have caused an exception when using the Spreadsheet Compare tool</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-1074">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-1074">PowerPoint</span></span>
- <span data-ttu-id="a8210-1075">SharePoint へのリンクをクリックしたときにクラッシュを発生させていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="a8210-1075">We fixed an issue where a crash could occur when clicking a link to SharePoint</span></span>
- <span data-ttu-id="a8210-1076">ユーザーが Surface ペンを使用して入力しているのに、次のページに切り替わってしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="a8210-1076">We fixed an issue which could switch the user to the next page while typing using a Surface Pen</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1077">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1077">Outlook</span></span>
- <span data-ttu-id="a8210-1078">一部の宛先フィールドが通常より大きくなってしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="a8210-1078">We fixed an issue where in some cases the To field was larger than normal</span></span>

### <a name="access"></a><span data-ttu-id="a8210-1079">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-1079">Access</span></span>
- <span data-ttu-id="a8210-1080">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1080">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a8210-1081">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-1081">Project</span></span>
- <span data-ttu-id="a8210-1082">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1082">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-7-2019"></a><span data-ttu-id="a8210-1083">2019 年 6 月 7 日</span><span class="sxs-lookup"><span data-stu-id="a8210-1083">June 7, 2019</span></span>
<span data-ttu-id="a8210-1084">バージョン 1907 (ビルド 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="a8210-1084">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a8210-1085">主な修正:</span><span class="sxs-lookup"><span data-stu-id="a8210-1085">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1086">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1086">Word</span></span> 
- <span data-ttu-id="a8210-1087">オートコレクトが文の先頭文字を大文字にするように設定されていると Word がクラッシュする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1087">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="a8210-1088">SharePoint でドキュメントを編集する際のパフォーマンスが向上しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1088">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="a8210-1089">Adobe Illustrator で作成されたベクター ベースの画像が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1089">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-1090">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-1090">Excel</span></span>
- <span data-ttu-id="a8210-1091">マクロを記録するときに、並べ替えフィールドが正しく設定されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1091">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="a8210-1092">配列数式の計算中にハングまたはクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1092">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-1093">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-1093">PowerPoint</span></span>
- <span data-ttu-id="a8210-1094">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1094">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1095">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1095">Outlook</span></span>
- <span data-ttu-id="a8210-1096">インライン添付ファイルが誤って拡大縮小されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1096">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="a8210-1097">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-1097">Access</span></span>
- <span data-ttu-id="a8210-1098">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1098">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a8210-1099">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-1099">Project</span></span>
- <span data-ttu-id="a8210-1100">固定期間のタイムシートが割り当て終了日を変更するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1100">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="a8210-1101">以前のバージョンからプロジェクトを開くと、[完了率] の値が正しくない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1101">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="a8210-1102">2019 年 5 月 31 日</span><span class="sxs-lookup"><span data-stu-id="a8210-1102">May 31, 2019</span></span>
<span data-ttu-id="a8210-1103">バージョン 1906 (ビルド 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="a8210-1103">Version 1906 (build 11722.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a8210-1104">新機能:</span><span class="sxs-lookup"><span data-stu-id="a8210-1104">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1105">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1105">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="a8210-1106">サポートに問い合わせるためのダイアログがドッキング可能になり、右側に表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1106">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="a8210-1107">サポートへの問い合わせに使用するダイアログが右側のウィンドウに表示され、最初からドッキングされたウィンドウとして表示されます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1107">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="a8210-1108">メールでインクを使用する</span><span class="sxs-lookup"><span data-stu-id="a8210-1108">Ink in Your Email!</span></span>

<span data-ttu-id="a8210-1109">Outlook メールで画像を描画し、注釈を付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1109">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1110">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1110">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="a8210-1111">ドキュメント リンクを Word で開く</span><span class="sxs-lookup"><span data-stu-id="a8210-1111">Open document links in Word</span></span>

<span data-ttu-id="a8210-1112">Office でドキュメント リンクをクリックしたときに既定で Word アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1112">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="a8210-1113">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1113">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="a8210-1114">詳しくは、以下を参照してください。https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="a8210-1114">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a8210-1115">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="a8210-1115">Getting Started:</span></span>

<span data-ttu-id="a8210-1116">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="a8210-1116">Feature will default to off.</span></span> <span data-ttu-id="a8210-1117">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-1117">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="a8210-1118">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1118">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="a8210-1119">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1119">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="a8210-1120">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="a8210-1120">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="a8210-1121">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1121">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="a8210-1122">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="a8210-1122">Scenarios to Try:</span></span>

<span data-ttu-id="a8210-1123">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている Word ドキュメントへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="a8210-1123">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="a8210-1124">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="a8210-1124">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-1125">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-1125">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="a8210-1126">プレゼンテーションへのリンクを PowerPoint で開く</span><span class="sxs-lookup"><span data-stu-id="a8210-1126">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="a8210-1127">Office でプレゼンテーションへのリンクをクリックしたときに既定で PowerPoint アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1127">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="a8210-1128">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1128">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="a8210-1129">詳しくは、以下を参照してください。https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="a8210-1129">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a8210-1130">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="a8210-1130">Getting Started:</span></span>

<span data-ttu-id="a8210-1131">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="a8210-1131">Feature will default to off.</span></span> <span data-ttu-id="a8210-1132">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-1132">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="a8210-1133">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1133">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="a8210-1134">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1134">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="a8210-1135">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="a8210-1135">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="a8210-1136">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1136">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="a8210-1137">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="a8210-1137">Scenarios to Try:</span></span>

<span data-ttu-id="a8210-1138">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている PowerPoint プレゼンテーションへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="a8210-1138">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="a8210-1139">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="a8210-1139">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-1140">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-1140">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="a8210-1141">ブックのリンクを Excel で開く</span><span class="sxs-lookup"><span data-stu-id="a8210-1141">Open workbook links in Excel</span></span>

<span data-ttu-id="a8210-1142">Office でブックのリンクをクリックしたときに既定で Excel アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1142">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="a8210-1143">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1143">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="a8210-1144">詳細については、以下を参照してください。https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="a8210-1144">Learn More: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a8210-1145">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="a8210-1145">Getting Started:</span></span>

<span data-ttu-id="a8210-1146">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="a8210-1146">Feature will default to off.</span></span> <span data-ttu-id="a8210-1147">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="a8210-1147">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="a8210-1148">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1148">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="a8210-1149">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1149">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="a8210-1150">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="a8210-1150">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="a8210-1151">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1151">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="a8210-1152">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="a8210-1152">Scenarios to Try:</span></span>

<span data-ttu-id="a8210-1153">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている Excel ブックへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="a8210-1153">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="a8210-1154">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="a8210-1154">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a8210-1155">主な修正:</span><span class="sxs-lookup"><span data-stu-id="a8210-1155">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="a8210-1156">すべて</span><span class="sxs-lookup"><span data-stu-id="a8210-1156">All</span></span>
- <span data-ttu-id="a8210-1157">自動保存が無効になっている場合でも、ファイルが自動保存されてしまう場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1157">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1158">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1158">Word</span></span> 
- <span data-ttu-id="a8210-1159">一部のユーザーがファイルを SharePoint に保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1159">We fixed an issue which may have prevented some users from saving to SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-1160">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-1160">Excel</span></span>
- <span data-ttu-id="a8210-1161">無効なフィルターに間違ったアイコンが表示される場合がある問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="a8210-1161">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-1162">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-1162">PowerPoint</span></span>
- <span data-ttu-id="a8210-1163">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1163">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1164">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1164">Outlook</span></span>
- <span data-ttu-id="a8210-1165">グループ スケジュール ビューで一部のユーザーがオフラインとして間違って表示される問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="a8210-1165">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="a8210-1166">末尾にスペースが挿入されている URL が SafeLink で解析できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1166">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="a8210-1167">業務時間外に部屋が利用可能と表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1167">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="a8210-1168">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-1168">Access</span></span>
- <span data-ttu-id="a8210-1169">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1169">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a8210-1170">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-1170">Project</span></span>
- <span data-ttu-id="a8210-1171">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1171">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="a8210-1172">2019 年 5 月 24 日</span><span class="sxs-lookup"><span data-stu-id="a8210-1172">May 24, 2019</span></span>
<span data-ttu-id="a8210-1173">バージョン 1906 (ビルド 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="a8210-1173">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a8210-1174">新機能:</span><span class="sxs-lookup"><span data-stu-id="a8210-1174">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="a8210-1175">ユーザー エクスペリエンスの更新</span><span class="sxs-lookup"><span data-stu-id="a8210-1175">User Experience Updates</span></span>

<span data-ttu-id="a8210-1176">近日公開となっていた更新プログラムが公開されました。この更新には、シンプル リボンおよびフォルダー ウィンドウ、メッセージ一覧、閲覧ウィンドウの外観の更新が含まれます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1176">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a8210-1177">主な修正:</span><span class="sxs-lookup"><span data-stu-id="a8210-1177">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="a8210-1178">すべて</span><span class="sxs-lookup"><span data-stu-id="a8210-1178">All</span></span>

- <span data-ttu-id="a8210-1179">チャットウィンドウが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1179">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1180">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1180">Word</span></span> 
- <span data-ttu-id="a8210-1181">Word で文法エラーのテキストが誤って強調表示されることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1181">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-1182">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-1182">Excel</span></span>
- <span data-ttu-id="a8210-1183">誤ったアイコンがグラフ要素に使用されているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1183">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="a8210-1184">同じブックが既に開いているときに、不正なブックが VBA スクリプトでアクティブになるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1184">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-1185">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-1185">PowerPoint</span></span>
- <span data-ttu-id="a8210-1186">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1186">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1187">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1187">Outlook</span></span>
- <span data-ttu-id="a8210-1188">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1188">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="a8210-1189">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-1189">Access</span></span>
- <span data-ttu-id="a8210-1190">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1190">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a8210-1191">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-1191">Project</span></span>
- <span data-ttu-id="a8210-1192">タスクバーに切り替えた後、Project がクラッシュする可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1192">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="a8210-1193">2019 年 5 月 17 日</span><span class="sxs-lookup"><span data-stu-id="a8210-1193">May 17, 2019</span></span>
<span data-ttu-id="a8210-1194">バージョン 1906 (ビルド 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="a8210-1194">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a8210-1195">新機能:</span><span class="sxs-lookup"><span data-stu-id="a8210-1195">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1196">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1196">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="a8210-1197">ユーザー エクスペリエンスのアップデート</span><span class="sxs-lookup"><span data-stu-id="a8210-1197">User Experience Updates</span></span>

<span data-ttu-id="a8210-1198">近日公開となっていた更新プログラムが公開されました。この更新には、シンプル リボンおよびフォルダー ウィンドウ、メッセージ一覧、閲覧ウィンドウの外観の更新が含まれます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1198">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a8210-1199">利用するには:</span><span class="sxs-lookup"><span data-stu-id="a8210-1199">Getting Started:</span></span>

<span data-ttu-id="a8210-1200">これらの変更は、新しい既定の UI の一部になります。この新しい UI は、すべての運用環境ユーザー向けに [近日公開] スイッチで 12 月中旬以来提供されてきました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1200">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="a8210-1201">カスタマイズ可能なシンプル リボン</span><span class="sxs-lookup"><span data-stu-id="a8210-1201">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="a8210-1202">従来のビューとシンプルなビューの切り替えやコマンドの固定または固定解除を簡単にできます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1202">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a8210-1203">利用するには:</span><span class="sxs-lookup"><span data-stu-id="a8210-1203">Getting Started:</span></span>

<span data-ttu-id="a8210-1204">シンプル リボンを使用するには、まず [近日公開] 機能をオンにし、リボンの山形マークをクリックして従来の複数行のリボンと新しい 1 行のシンプル リボンを切り替えます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1204">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="a8210-1205">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="a8210-1205">Scenarios to Try:</span></span>

<span data-ttu-id="a8210-1206">従来のリボンからシンプル リボンに切り替える</span><span class="sxs-lookup"><span data-stu-id="a8210-1206">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="a8210-1207">お気に入りの操作を選択する</span><span class="sxs-lookup"><span data-stu-id="a8210-1207">Pick your favorite action</span></span>

<span data-ttu-id="a8210-1208">[フラグ] 機能や [削除] 機能はお使いになられていないかもしれません。</span><span class="sxs-lookup"><span data-stu-id="a8210-1208">Don't use Flag and Delete?</span></span> <span data-ttu-id="a8210-1209">アーカイブまたは既読に​​しますか?</span><span class="sxs-lookup"><span data-stu-id="a8210-1209">How about Archive or Mark as Read?</span></span> <span data-ttu-id="a8210-1210">クイック操作メニューをカスタマイズしてよく使うコマンドを追加できます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1210">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a8210-1211">利用するには:</span><span class="sxs-lookup"><span data-stu-id="a8210-1211">Getting Started:</span></span>

<span data-ttu-id="a8210-1212">希望のクイック操作を選ぶには、メッセージ一覧でメールを右クリックし、コンテキスト メニューを表示します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1212">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="a8210-1213">次に、[クイック操作の設定] をクリックします。</span><span class="sxs-lookup"><span data-stu-id="a8210-1213">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="a8210-1214">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="a8210-1214">Scenarios to Try:</span></span>

<span data-ttu-id="a8210-1215">既定の設定を [フラグ] または [削除] から [アーカイブ]、[移動]、[既読にする]、または [なし] に変更すると、メッセージ一覧をすっきりした外観にできます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1215">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="a8210-1216">レイアウトの間隔を</span><span class="sxs-lookup"><span data-stu-id="a8210-1216">Relaxed or tighter layout?</span></span> <span data-ttu-id="a8210-1217">自由に選べます</span><span class="sxs-lookup"><span data-stu-id="a8210-1217">You choose</span></span>

<span data-ttu-id="a8210-1218">[狭い間隔を使用] オプションを使用すると、アイテム間のスペースを広く取るか、間隔の狭いレイアウトでより多くのアイテムを表示するかを選べます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1218">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a8210-1219">利用するには:</span><span class="sxs-lookup"><span data-stu-id="a8210-1219">Getting Started:</span></span>

<span data-ttu-id="a8210-1220">従来のリボンの場合、[表示] タブの [メッセージ] グループで、[狭い間隔を使用] チェックボックスをオンにします。シンプル リボンの場合は、[現在のビュー] 設定で [狭い間隔を使用] を選択します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1220">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="a8210-1221">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="a8210-1221">Scenarios to Try:</span></span>

<span data-ttu-id="a8210-1222">Outlook で、この設定をオフにした状態でメッセージをトリアージしたり作成したりしてみます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1222">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="a8210-1223">この機能をオンにすると、1 ページに収まるメッセージの数が増え、新規作成フォームのコントロールの表示がすっきりとします。</span><span class="sxs-lookup"><span data-stu-id="a8210-1223">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="a8210-1224">Onedrive 同期クライアントを使用する際の MRU エントリの重複を除去する</span><span class="sxs-lookup"><span data-stu-id="a8210-1224">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="a8210-1225">クラウド添付ファイルを使用すると、MRU エントリの重複を除去できるため、Onedrive の統合を効率化できます。クラウド添付ファイルを使用すれば、同期されたデータでコピーの添付をする動作が早くなります。</span><span class="sxs-lookup"><span data-stu-id="a8210-1225">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a8210-1226">利用するには:</span><span class="sxs-lookup"><span data-stu-id="a8210-1226">Getting Started:</span></span>

<span data-ttu-id="a8210-1227">OneDrive 同期クライアントを使用している場合は、添付ファイル MRU に重複ファイルが表示されなくなります。</span><span class="sxs-lookup"><span data-stu-id="a8210-1227">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="a8210-1228">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="a8210-1228">Scenarios to Try:</span></span>

<span data-ttu-id="a8210-1229">OneDrive 同期クライアントを有効にして、Outlook デスクトップで [ファイルの添付] メニューを使用する</span><span class="sxs-lookup"><span data-stu-id="a8210-1229">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="a8210-1230">フォルダーを多数含むメールボックスでの共有フォルダーの同期が改善されました</span><span class="sxs-lookup"><span data-stu-id="a8210-1230">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="a8210-1231">長い間、Outlook での共有メールボックスの同期は、最大で 500 フォルダーに制限されてきました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1231">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="a8210-1232">この変更により Outlook の改善が行われ、同期をする際の 500 フォルダーの制限がなくなりました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1232">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a8210-1233">利用するには:</span><span class="sxs-lookup"><span data-stu-id="a8210-1233">Getting Started:</span></span>

<span data-ttu-id="a8210-1234">メールボックスにフォルダーを 1000 個作成し、誰か他のユーザーにそのメールボックスへのアクセスを許可し、このユーザーの Outlook プロファイルを作成します。同期が正常に動作することを確認します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1234">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1235">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1235">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="a8210-1236">少しだけ消す</span><span class="sxs-lookup"><span data-stu-id="a8210-1236">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a8210-1237">利用するには:</span><span class="sxs-lookup"><span data-stu-id="a8210-1237">Getting Started:</span></span>

<span data-ttu-id="a8210-1238">[描画] タブに移動します。 [消しゴム] ドロップダウンを選択します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1238">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="a8210-1239">[消しゴム (小)] または [消しゴム (中)] を選びます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1239">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="a8210-1240">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="a8210-1240">Scenarios to Try:</span></span>

<span data-ttu-id="a8210-1241">[描画] タブに移動します。ペンを選びます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1241">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="a8210-1242">インク ストロークを描きます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1242">Draw an ink stroke.</span></span> <span data-ttu-id="a8210-1243">[消しゴム] ドロップダウンを選択します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1243">Select the Eraser dropdown.</span></span> <span data-ttu-id="a8210-1244">[消しゴム (小)] または [消しゴム (中)] を選びます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1244">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="a8210-1245">インク ストロークを少しだけ消してみます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1245">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a8210-1246">主な修正:</span><span class="sxs-lookup"><span data-stu-id="a8210-1246">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="a8210-1247">すべて</span><span class="sxs-lookup"><span data-stu-id="a8210-1247">All</span></span> 
- <span data-ttu-id="a8210-1248">一部のユーザーが PDF として保存できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1248">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="a8210-1249">32 ビット システムでの大容量ファイルの保存に影響する場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1249">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1250">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1250">Word</span></span> 
- <span data-ttu-id="a8210-1251">音声入力機能の応答性が大幅に向上されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1251">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-1252">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-1252">Excel</span></span>
- <span data-ttu-id="a8210-1253">タッチ スクリーン デバイスでダブルクリック イベントが失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1253">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="a8210-1254">一部のユーザーが VBA マクロを編集できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1254">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="a8210-1255">スライサーを使用した際にパフォーマンスに影響する場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1255">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-1256">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-1256">PowerPoint</span></span>
- <span data-ttu-id="a8210-1257">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1257">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1258">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1258">Outlook</span></span>
- <span data-ttu-id="a8210-1259">選択したテンプレートとは異なるテンプレートが表示される場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1259">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="a8210-1260">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-1260">Access</span></span>
- <span data-ttu-id="a8210-1261">長いリッチ テキストの表示に Zoom Builder を使うと、読みづらくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1261">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="a8210-1262">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-1262">Project</span></span>
- <span data-ttu-id="a8210-1263">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1263">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="a8210-1264">2019 年 5 月 10日</span><span class="sxs-lookup"><span data-stu-id="a8210-1264">May 10, 2019</span></span>
<span data-ttu-id="a8210-1265">バージョン 1906 (ビルド 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="a8210-1265">Version 1906 (build 11702.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a8210-1266">新機能:</span><span class="sxs-lookup"><span data-stu-id="a8210-1266">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1267">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1267">Outlook</span></span>

<span data-ttu-id="a8210-1268">**より多くのメッセージを画面に収める:** [表示] > [より狭い文字間隔を使用] の順に選択し、メッセージの間隔を調整します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1268">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a8210-1269">主な修正:</span><span class="sxs-lookup"><span data-stu-id="a8210-1269">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="a8210-1270">すべて</span><span class="sxs-lookup"><span data-stu-id="a8210-1270">All</span></span>
- <span data-ttu-id="a8210-1271">[名前を付けて保存] ダイアログボックスに誤ったパスが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1271">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1272">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1272">Word</span></span> 
- <span data-ttu-id="a8210-1273">操作アシストからの一部の選択が挿入されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1273">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-1274">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-1274">Excel</span></span>
- <span data-ttu-id="a8210-1275">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1275">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-1276">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-1276">PowerPoint</span></span>
- <span data-ttu-id="a8210-1277">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1277">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1278">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1278">Outlook</span></span>
- <span data-ttu-id="a8210-1279">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1279">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="a8210-1280">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-1280">Access</span></span>
- <span data-ttu-id="a8210-1281">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1281">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a8210-1282">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-1282">Project</span></span>
- <span data-ttu-id="a8210-1283">タスク ID の確認に強調表示が必要となる可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1283">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="a8210-1284">2019 年 5 月 3日</span><span class="sxs-lookup"><span data-stu-id="a8210-1284">May 3, 2019</span></span>
<span data-ttu-id="a8210-1285">バージョン 1906 (ビルド 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="a8210-1285">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a8210-1286">新機能:</span><span class="sxs-lookup"><span data-stu-id="a8210-1286">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1287">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1287">Outlook</span></span>

<span data-ttu-id="a8210-1288">**すべての暗号化オプションを1か所で:** [オプション] > [暗号化] の順に移動して、メール メッセージを保護する方法を選択します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1288">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a8210-1289">主な修正:</span><span class="sxs-lookup"><span data-stu-id="a8210-1289">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="a8210-1290">すべて</span><span class="sxs-lookup"><span data-stu-id="a8210-1290">All</span></span>
- <span data-ttu-id="a8210-1291">一部のユーザーが OneDrive for Business との同期で問題が発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1291">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1292">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1292">Word</span></span> 
- <span data-ttu-id="a8210-1293">Word の起動に時間がかかる場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1293">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-1294">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-1294">Excel</span></span>
- <span data-ttu-id="a8210-1295">新しいバージョンの Excel にアップグレードした後、ブックから外部リンクが削除されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1295">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="a8210-1296">一部のユーザーが新しいワークブックでセルを選択するのが困難な問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1296">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-1297">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-1297">PowerPoint</span></span>
- <span data-ttu-id="a8210-1298">図面をテキストに変換するときにフォントサイズが一致しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1298">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1299">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1299">Outlook</span></span>
- <span data-ttu-id="a8210-1300">a .VCF ファイルから連絡先を保存すると空のフィールドが発生する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1300">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="a8210-1301">送信されていても、送信トレイ フォルダーにメッセージが残ってしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1301">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="a8210-1302">DRM メッセージの表示中に Outlook がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1302">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="a8210-1303">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-1303">Access</span></span>
- <span data-ttu-id="a8210-1304">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1304">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a8210-1305">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-1305">Project</span></span>
- <span data-ttu-id="a8210-1306">エディターが中国語から英語に切り替わる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1306">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="a8210-1307">マスター プロジェクトの公開コピーに未公開タスクが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1307">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="a8210-1308">2019 年 4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="a8210-1308">April 26, 2019</span></span>
<span data-ttu-id="a8210-1309">バージョン 1905 (ビルド 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="a8210-1309">Version 1905 (build 11617.20002)</span></span>

## <a name="new-features"></a><span data-ttu-id="a8210-1310">新機能</span><span class="sxs-lookup"><span data-stu-id="a8210-1310">New Features</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1311">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1311">Outlook</span></span>

<span data-ttu-id="a8210-1312">**共有カレンダーの更新がより速く**: Office 365 の共有カレンダーの場合、Outlook は REST API を使用してこれらのカレンダーを更新できます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1312">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="a8210-1313">共有カレンダーのより高速で信頼性の高い更新を行うには、プレビューを有効にします。</span><span class="sxs-lookup"><span data-stu-id="a8210-1313">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-1314">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-1314">Excel</span></span>

#### <a name="coauthoring-improvements"></a><span data-ttu-id="a8210-1315">共同編集の改善</span><span class="sxs-lookup"><span data-stu-id="a8210-1315">Coauthoring improvements</span></span>

<span data-ttu-id="a8210-1316">他のユーザーがリアルタイムでコンテンツの変更を受け取れるようにすることで、共同編集のエクスペリエンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1316">Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

### <a name="visio"></a><span data-ttu-id="a8210-1317">Visio</span><span class="sxs-lookup"><span data-stu-id="a8210-1317">Visio</span></span>

- <span data-ttu-id="a8210-1318">**Power BI から Visio ビジュアルをエクスポートする:** PDF、PowerPoint のファイルなどの Power BI レポートをエクスポートするときに、Power BI 用の Visio Visual が正しく表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1318">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a8210-1319">主な修正:</span><span class="sxs-lookup"><span data-stu-id="a8210-1319">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1320">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1320">Word</span></span> 
- <span data-ttu-id="a8210-1321">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1321">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-1322">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-1322">Excel</span></span>
- <span data-ttu-id="a8210-1323">ソルバー マクロの実行が失敗するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1323">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="a8210-1324">Excel ファイルを SharePoint にインポートできないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1324">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-1325">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-1325">PowerPoint</span></span>
- <span data-ttu-id="a8210-1326">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1326">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1327">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1327">Outlook</span></span>
- <span data-ttu-id="a8210-1328">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1328">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="a8210-1329">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-1329">Access</span></span>
- <span data-ttu-id="a8210-1330">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1330">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a8210-1331">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-1331">Project</span></span>
- <span data-ttu-id="a8210-1332">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1332">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="a8210-1333">2019 年 4 月 19 日</span><span class="sxs-lookup"><span data-stu-id="a8210-1333">April 19, 2019</span></span>
<span data-ttu-id="a8210-1334">バージョン 1905 (ビルド 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="a8210-1334">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a8210-1335">新機能:</span><span class="sxs-lookup"><span data-stu-id="a8210-1335">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1336">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1336">Outlook</span></span>

<span data-ttu-id="a8210-1337">**人物を検索するときにメールの候補を取得する:** [検索] ボックスに人の名前を入力すると、最も関連性の高いメール メッセージが検索候補に含まれます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1337">**Get email suggestions when you search for a person:** When you type a person's name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-1338">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-1338">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="a8210-1339">データ型を使用した塗り分けマップのエクスペリエンス向上</span><span class="sxs-lookup"><span data-stu-id="a8210-1339">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="a8210-1340">この機能は、Excel の地理データ型を使用して、塗り分けされたマップ グラフにプロットするユーザーのための機能強化です。</span><span class="sxs-lookup"><span data-stu-id="a8210-1340">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="a8210-1341">エンドユーザーにとっては、機能とエンドユーザーがマップする領域の精度向上とがより高度に統合されたことが利点です。</span><span class="sxs-lookup"><span data-stu-id="a8210-1341">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="a8210-1342">さらに、ポリゴンで都市をマッピングする機能も含まれてます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1342">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a8210-1343">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="a8210-1343">Getting Started:</span></span>

- <span data-ttu-id="a8210-1344">この機能は、Excel 内の既存の機能を改善したものです。</span><span class="sxs-lookup"><span data-stu-id="a8210-1344">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="a8210-1345">この改善を使用するには、位置をリッチエンティティに変換し、塗り分けマップでプロットします。</span><span class="sxs-lookup"><span data-stu-id="a8210-1345">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="a8210-1346">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="a8210-1346">Scenarios to Try:</span></span>

- <span data-ttu-id="a8210-1347">ユーザーは、都市、州、都道府県、国、郵便番号のマッピングを試すことができます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1347">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="a8210-1348">主な修正:</span><span class="sxs-lookup"><span data-stu-id="a8210-1348">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="a8210-1349">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="a8210-1349">All Applications</span></span>
- <span data-ttu-id="a8210-1350">アプリケーションが起動したときに最初の実行ダイアログが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1350">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="a8210-1351">[名前を付けて保存] ダイアログボックス内の SharePoint リンクが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1351">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="a8210-1352">ユーザーが [今すぐ修復] ダイアログを誤って表示する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1352">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1353">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1353">Word</span></span> 
- <span data-ttu-id="a8210-1354">フォントの要求時に、一部のユーザーがメモリ不足またはディスク領域のエラーを受信する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1354">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="a8210-1355">[コメント] ウィンドウから切り替えたときにウィンドウがフォーカスを失う可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1355">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-1356">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-1356">Excel</span></span>
- <span data-ttu-id="a8210-1357">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1357">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-1358">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-1358">PowerPoint</span></span>
- <span data-ttu-id="a8210-1359">ブランド化された図形のサイズ変更ができない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1359">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="a8210-1360">保護ビューモードでファイルを開くときに PowerPoint がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1360">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1361">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1361">Outlook</span></span>
- <span data-ttu-id="a8210-1362">一部のユーザーが中国語の単語を選択できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1362">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="a8210-1363">有効期限が正しく計算されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1363">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="a8210-1364">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-1364">Access</span></span>
- <span data-ttu-id="a8210-1365">一部のユーザーがマクロ ビルダーを使用できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1365">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="a8210-1366">レポートを印刷すると最初のページしか印刷されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1366">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="a8210-1367">ハイパーリンクの上にカーソルを置くとアプリケーションがクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1367">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="a8210-1368">リレーションシップ ビューを使用すると、一部のアイテムが画面外に表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1368">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="a8210-1369">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-1369">Project</span></span>
- <span data-ttu-id="a8210-1370">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1370">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="a8210-1371">2019 年 4 月 12 日</span><span class="sxs-lookup"><span data-stu-id="a8210-1371">April 12, 2019</span></span>
<span data-ttu-id="a8210-1372">バージョン 1905 (ビルド 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="a8210-1372">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a8210-1373">新機能:</span><span class="sxs-lookup"><span data-stu-id="a8210-1373">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="a8210-1374">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-1374">Access</span></span>

#### <a name="get-smart-with-microsoft-graph"></a><span data-ttu-id="a8210-1375">Microsoft Graph を使用してスマートに作業</span><span class="sxs-lookup"><span data-stu-id="a8210-1375">Get smart with Microsoft Graph</span></span>

<span data-ttu-id="a8210-1376">インテリジェントなテクノロジを使用して、インテリジェントなデータをインポートしたり、またはデータにリンクしたりして、デスクトップ データベースを作り変えましょう。</span><span class="sxs-lookup"><span data-stu-id="a8210-1376">Import or link to intelligent data and reinvent your desktop database with Intelligent Technology.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a8210-1377">主な修正:</span><span class="sxs-lookup"><span data-stu-id="a8210-1377">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="a8210-1378">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="a8210-1378">All Applications</span></span>
 - <span data-ttu-id="a8210-1379">一部のユーザーがクラウドの場所にファイルを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1379">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="a8210-1380">リボンから間違ったウィンドウが開く問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1380">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1381">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1381">Word</span></span> 
- <span data-ttu-id="a8210-1382">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1382">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-1383">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-1383">Excel</span></span>
- <span data-ttu-id="a8210-1384">リンクされたデータ型を含まないブックであるにもかかわらず、リンクされたデータ型に対するエラーメッセージが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1384">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="a8210-1385">Word 文書内のリンクの URL がオンラインとローカルで表示したときに変更される可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1385">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-1386">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-1386">PowerPoint</span></span>
- <span data-ttu-id="a8210-1387">[アニメーション] タブで変更を元に戻すと、PowerPoint がクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1387">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1388">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1388">Outlook</span></span>
- <span data-ttu-id="a8210-1389">一部のユーザーがパブリック フォルダー内の連絡先の [メモ] フィールドを変更できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1389">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="a8210-1390">失効日と削除日の間に競合が発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1390">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="a8210-1391">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-1391">Access</span></span>
- <span data-ttu-id="a8210-1392">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1392">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a8210-1393">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-1393">Project</span></span>
- <span data-ttu-id="a8210-1394">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1394">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="a8210-1395">2019年4月5日</span><span class="sxs-lookup"><span data-stu-id="a8210-1395">April 5, 2019</span></span>
<span data-ttu-id="a8210-1396">バージョン 1904 (ビルド 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="a8210-1396">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a8210-1397">新機能:</span><span class="sxs-lookup"><span data-stu-id="a8210-1397">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1398">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1398">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="a8210-1399">Windows 用の Outlook: 優先受信トレイの設定を設定して共有します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1399">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="a8210-1400">優先受信トレイの設定はクラウドに保存されるため、どのコンピューターで Web 上の Outlook for Windows と Outlook を使用しても同じように一貫したエクスペリエンスを楽しめます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1400">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a8210-1401">利用するには:</span><span class="sxs-lookup"><span data-stu-id="a8210-1401">Getting Started:</span></span>

<span data-ttu-id="a8210-1402">[ファイル]、[オプション]、[全般] の順に移動すると、[Outlook の設定をクラウドに保存する] という新しい設定があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-1402">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="a8210-1403">ユーザーは、自分の優先受信トレイの設定を他の Outlook Desktop インストールおよび OWA に移動できるようにするには、このチェック ボックスをオンにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-1403">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a8210-1404">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="a8210-1404">Scenarios to Try:</span></span>

<span data-ttu-id="a8210-1405">クラウド設定の設定を有効にしているコンピューターで優先受信トレイを変更します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1405">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="a8210-1406">OWA に移動して、そこに適用されている設定も確認してください。</span><span class="sxs-lookup"><span data-stu-id="a8210-1406">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="a8210-1407">OWA で優先受信トレイを変更し、デスクトップ Outlook を起動して反映された優先順位を表示します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1407">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1408">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1408">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="a8210-1409">学習ツール モードでは、より多くのページの色が追加でサポートされます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1409">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="a8210-1410">Word の学習ツールは、より多くのページ テーマ色を追加し、ページの背景色を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1410">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="a8210-1411">すべて白またはすべて黒の背景だと読みにくいと感じるユーザーが多かったため、PC と Mac の Word で色の選択肢を拡大しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1411">Many people have challenges reading with an all-white or all-black background, so we've expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a8210-1412">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="a8210-1412">Getting Started:</span></span>

<span data-ttu-id="a8210-1413">この操作を行うには、[表示] タブに移動し、[学習ツール]、[ページの色] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1413">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a8210-1414">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="a8210-1414">Scenarios to Try:</span></span>

<span data-ttu-id="a8210-1415">この操作を行うには、[表示] タブに移動し、[学習ツール]、[ページの色] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1415">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-1416">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-1416">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="a8210-1417">3D アニメーション モデルで創造性を高める</span><span class="sxs-lookup"><span data-stu-id="a8210-1417">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="a8210-1418">Office では、アニメーションモデルをサポートするようになりました。エディターで再生するので、シートを活用することができます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1418">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a8210-1419">利用するには:</span><span class="sxs-lookup"><span data-stu-id="a8210-1419">Getting Started:</span></span>

1. <span data-ttu-id="a8210-1420">Excel を開く</span><span class="sxs-lookup"><span data-stu-id="a8210-1420">Open Excel</span></span>
2. <span data-ttu-id="a8210-1421">3D アニメーション モデルを挿入します (まもなく Remix が公開されますが、今はここでアニメーション モデルにアクセスしてください: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="a8210-1421">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="a8210-1422">アニメーション モデルがエディターで再生されるようになります。</span><span class="sxs-lookup"><span data-stu-id="a8210-1422">The animated model will play in the editor!</span></span> <span data-ttu-id="a8210-1423">スライドショー モードも再生されるようになりますので、確認してください。</span><span class="sxs-lookup"><span data-stu-id="a8210-1423">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="a8210-1424">[3D 形式] リボンで、モデル内の他のアニメーション シーンを探索する</span><span class="sxs-lookup"><span data-stu-id="a8210-1424">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a8210-1425">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="a8210-1425">Scenarios to Try:</span></span>

1. <span data-ttu-id="a8210-1426">アニメーション モデルを挿入し、エディターで再生します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1426">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="a8210-1427">アニメーション化されたモデルで使用できるアニメーション シーンについては、シーン ギャラリー ([3D 書式] リボンから利用できます) を参照してください。</span><span class="sxs-lookup"><span data-stu-id="a8210-1427">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="a8210-1428">リボン、フローティング ツール バーまたはスペースバーを介してアニメーションを簡単に再生および一時停止することができます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1428">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a8210-1429">主な修正:</span><span class="sxs-lookup"><span data-stu-id="a8210-1429">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="a8210-1430">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="a8210-1430">All Applications</span></span>
- <span data-ttu-id="a8210-1431">Excel の間違ったアプリ アイコンがコンテキストメニューに表示されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1431">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="a8210-1432">アップデートをインストールした後に [ファイル メニュー] ボタンが消えてしまうことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1432">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="a8210-1433">ユーザー ライセンスに変更をおよぼす可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1433">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1434">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1434">Word</span></span> 
- <span data-ttu-id="a8210-1435">特定のズーム レベルでテキストが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1435">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-1436">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-1436">Excel</span></span>
- <span data-ttu-id="a8210-1437">編集後に、ブックを保存するかどうかを確認するメッセージが表示されない問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="a8210-1437">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="a8210-1438">ユーザーがブックを共有している場合に BeforeSave イベントが開始しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1438">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="a8210-1439">列のサイズを 6 ピクセル未満に変更すると誤ったエラーメッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1439">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="a8210-1440">Excel が Application.Visible フラグを無視する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1440">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="a8210-1441">トレースの矢印がアクティブでない固定ウィンドウに残る問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1441">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="a8210-1442">ブックを開くときに通貨の日付のセルの書式設定が変わることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1442">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="a8210-1443">ツールヒントが突然移動する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1443">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="a8210-1444">Power Query エディターのローカライズの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1444">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="a8210-1445">ブックを添付ファイルとしてメールで送信するときにブックが削除される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1445">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-1446">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-1446">PowerPoint</span></span>
- <span data-ttu-id="a8210-1447">図形のコピーに通常以上に時間がかかる問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="a8210-1447">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1448">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1448">Outlook</span></span>
- <span data-ttu-id="a8210-1449">描画ツールの使用中に Outlook がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1449">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="a8210-1450">HTML メールを作成する際のローカライズの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1450">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="a8210-1451">下側のウィンドウが選択しにくい問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1451">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="a8210-1452">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-1452">Access</span></span>
- <span data-ttu-id="a8210-1453">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1453">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a8210-1454">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-1454">Project</span></span>
- <span data-ttu-id="a8210-1455">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1455">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="a8210-1456">2019 年 3 月 22 日</span><span class="sxs-lookup"><span data-stu-id="a8210-1456">March 22, 2019</span></span>
<span data-ttu-id="a8210-1457">バージョン 1904 (ビルド 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="a8210-1457">Version 1904 (build 11514.20004)</span></span>

## <a name="new-features"></a><span data-ttu-id="a8210-1458">新機能</span><span class="sxs-lookup"><span data-stu-id="a8210-1458">New Features</span></span>

- <span data-ttu-id="a8210-1459">**プライバシー制御**: 診断データとコネクテッド エクスペリエンス用に新しく更新されて、改善された制御。</span><span class="sxs-lookup"><span data-stu-id="a8210-1459">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> <span data-ttu-id="a8210-1460">詳細 <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span><span class="sxs-lookup"><span data-stu-id="a8210-1460">Learn more <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span></span>

- <span data-ttu-id="a8210-1461">**新しい外観を備えた Office のアイコン:** シンプルかつ高性能で、インテリジェントな Office のエクスペリエンスを反映するように、Office のアイコンがリニューアルされました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1461">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a8210-1462">主な修正:</span><span class="sxs-lookup"><span data-stu-id="a8210-1462">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1463">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1463">Word</span></span> 
- <span data-ttu-id="a8210-1464">UI に常に "変更を確認しています" と表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1464">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-1465">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-1465">Excel</span></span>
- <span data-ttu-id="a8210-1466">ワークシートを移動した後にアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1466">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="a8210-1467">PDF 形式で保存した後にアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1467">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="a8210-1468">保存ダイアログで韓国語の文字を使用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1468">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-1469">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-1469">PowerPoint</span></span>
- <span data-ttu-id="a8210-1470">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1470">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1471">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1471">Outlook</span></span>
- <span data-ttu-id="a8210-1472">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1472">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="a8210-1473">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-1473">Access</span></span>
- <span data-ttu-id="a8210-1474">Access で余計なショートカットが作成されるという問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1474">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="a8210-1475">リンクされた SharePoint のデータが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1475">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="a8210-1476">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-1476">Project</span></span>
- <span data-ttu-id="a8210-1477">言語設定が中国語から英語に変わる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1477">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="a8210-1478">SharePoint に同期するとアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1478">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="a8210-1479">2019 年 3 月 15 日</span><span class="sxs-lookup"><span data-stu-id="a8210-1479">March 15, 2019</span></span>
<span data-ttu-id="a8210-1480">バージョン 1904 (ビルド 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="a8210-1480">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a8210-1481">新機能:</span><span class="sxs-lookup"><span data-stu-id="a8210-1481">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1482">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1482">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="a8210-1483">フォーカス モード</span><span class="sxs-lookup"><span data-stu-id="a8210-1483">Focus Mode</span></span>

<span data-ttu-id="a8210-1484">気を散らさずに作業に集中するには、[表示]メニューの[フォーカス]に切り替えます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1484">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="a8210-1485">Office 365 サブスクリプションが必要です。</span><span class="sxs-lookup"><span data-stu-id="a8210-1485">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a8210-1486">利用するには:</span><span class="sxs-lookup"><span data-stu-id="a8210-1486">Getting Started:</span></span>

<span data-ttu-id="a8210-1487">リボンのステータス バー [フォーカス] ボタンの [フォーカス] ボタンをタブして表示</span><span class="sxs-lookup"><span data-stu-id="a8210-1487">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a8210-1488">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="a8210-1488">Scenarios to Try:</span></span>

<span data-ttu-id="a8210-1489">フォーカス モードにしてフォーカス エクスペリエンスを経験する</span><span class="sxs-lookup"><span data-stu-id="a8210-1489">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a8210-1490">主な修正:</span><span class="sxs-lookup"><span data-stu-id="a8210-1490">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1491">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1491">Word</span></span> 
- <span data-ttu-id="a8210-1492">PDF として保存した文書の画像に間違った DPI が設定される問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1492">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-1493">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-1493">Excel</span></span>
- <span data-ttu-id="a8210-1494">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1494">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-1495">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-1495">PowerPoint</span></span>
- <span data-ttu-id="a8210-1496">コメント ウィンドウが正しく開閉しない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1496">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="a8210-1497">動画を削除するとアプリケーションがクラッシュする可能性がある問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1497">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="a8210-1498">アプリケーションの一部のインスタンスを起動できない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1498">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1499">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1499">Outlook</span></span>
- <span data-ttu-id="a8210-1500">日本語で表示するとき、開封確認が正しく表示されない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1500">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="a8210-1501">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-1501">Access</span></span>
- <span data-ttu-id="a8210-1502">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1502">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a8210-1503">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-1503">Project</span></span>
- <span data-ttu-id="a8210-1504">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1504">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="a8210-1505">2019 年 3 月 8 日</span><span class="sxs-lookup"><span data-stu-id="a8210-1505">March 8, 2019</span></span> 
<span data-ttu-id="a8210-1506">バージョン 1903 (ビルド 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="a8210-1506">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a8210-1507">新機能:</span><span class="sxs-lookup"><span data-stu-id="a8210-1507">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1508">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1508">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="a8210-1509">探している情報を Microsoft Search で検索する</span><span class="sxs-lookup"><span data-stu-id="a8210-1509">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="a8210-1510">Microsoft Search を使用して、作業を完了するのに必要なすべてのファイル、操作、連絡先、ヘルプを検索することができます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1510">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a8210-1511">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="a8210-1511">Getting Started:</span></span>

- <span data-ttu-id="a8210-1512">この機能は、ヘッダーの UI の上部に目立つように表示されています。</span><span class="sxs-lookup"><span data-stu-id="a8210-1512">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a8210-1513">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="a8210-1513">Scenarios to Try:</span></span>

- <span data-ttu-id="a8210-1514">大学、最近使用したドキュメント、最もよく使用するリボン コマンドなどを検索する</span><span class="sxs-lookup"><span data-stu-id="a8210-1514">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="a8210-1515">トピックや話題を検索して、その詳細情報を取得する</span><span class="sxs-lookup"><span data-stu-id="a8210-1515">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="a8210-1516">共同編集</span><span class="sxs-lookup"><span data-stu-id="a8210-1516">CoAuthoring</span></span>

<span data-ttu-id="a8210-1517">マクロの文書を編集できない状況にうんざりしていませんか?</span><span class="sxs-lookup"><span data-stu-id="a8210-1517">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="a8210-1518">これで OneDrive for Business 上の docm ファイルで複数の作成者による同時編集が可能になります。</span><span class="sxs-lookup"><span data-stu-id="a8210-1518">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a8210-1519">利用するには:</span><span class="sxs-lookup"><span data-stu-id="a8210-1519">Getting Started:</span></span>

<span data-ttu-id="a8210-1520">ユーザーは、この機能にアクセスするために UI のボタンを押す必要はありません。</span><span class="sxs-lookup"><span data-stu-id="a8210-1520">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="a8210-1521">OneDrive for Business の docm ファイルでは、既定で有効になっています。</span><span class="sxs-lookup"><span data-stu-id="a8210-1521">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="a8210-1522">したがって、試すには、ユーザーが docm ファイルを OneDrive for Business に保存しておく必要があります。</span><span class="sxs-lookup"><span data-stu-id="a8210-1522">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a8210-1523">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="a8210-1523">Scenarios to Try:</span></span>

<span data-ttu-id="a8210-1524">OneDrive for Business で docm ファイルを作成し、同僚と共有して共同作業を行います。</span><span class="sxs-lookup"><span data-stu-id="a8210-1524">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a8210-1525">主な修正:</span><span class="sxs-lookup"><span data-stu-id="a8210-1525">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1526">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1526">Word</span></span> 
- <span data-ttu-id="a8210-1527">オプションの表示中に 'Esc' キーを押すと発生するクラッシュの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1527">We fixed a crashing issue that occurred when pressing 'ESC' while in Options</span></span>
- <span data-ttu-id="a8210-1528">コメントに返信するときにクラッシュが発生するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1528">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="a8210-1529">Word から PowerPoint Online へのコピーと貼り付けで発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1529">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-1530">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-1530">Excel</span></span>
- <span data-ttu-id="a8210-1531">保護されたドキュメントや編集可能なドキュメントを開いているときに Excel でセルをコピーすると CPU 使用率が高くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1531">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-1532">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-1532">PowerPoint</span></span>
- <span data-ttu-id="a8210-1533">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1533">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1534">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1534">Outlook</span></span>
- <span data-ttu-id="a8210-1535">Outlook Search が選択した日付の並べ替えを使用しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1535">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="a8210-1536">"このタスクを開く" ワークフロー リボンのボタンが特定のメールで応答しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1536">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="a8210-1537">ユーザーが Outlook の会議室の検索で空いている会議室を選択した後、社内の会議室がクリアされなくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1537">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="a8210-1538">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-1538">Access</span></span>
- <span data-ttu-id="a8210-1539">ダーク テーマで白い背景に白いテキストが表示されていた、保存済みのインポート/エクスポートのダイアログを修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1539">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="a8210-1540">表のデザインのテキストボックスに [Yes/No] フィールドの DisplayControl プロパティを設定できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1540">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="a8210-1541">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-1541">Project</span></span>
- <span data-ttu-id="a8210-1542">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1542">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="a8210-1543">2019 年 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="a8210-1543">March 1, 2019</span></span> 
<span data-ttu-id="a8210-1544">バージョン 1903 (ビルド 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="a8210-1544">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a8210-1545">新機能</span><span class="sxs-lookup"><span data-stu-id="a8210-1545">What's New</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1546">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1546">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="a8210-1547">色の変更履歴、コメントとリアルタイムの共同作業の同期</span><span class="sxs-lookup"><span data-stu-id="a8210-1547">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="a8210-1548">当社の製品での、コメント、変更履歴と共同作業者のカーソルが同じ色で表示されることについての修正箇所を確認しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1548">Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a8210-1549">利用するには:</span><span class="sxs-lookup"><span data-stu-id="a8210-1549">Getting Started:</span></span>

<span data-ttu-id="a8210-1550">他のユーザーが開いている SharePoint または OneDrive のドキュメントを開きます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1550">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="a8210-1551">ユーザーの変更履歴とコメントの色が、ユーザーのカーソルの色と一致することを確認します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1551">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a8210-1552">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="a8210-1552">Scenarios to Try:</span></span>

<span data-ttu-id="a8210-1553">他のユーザーが開いている SharePoint または OneDrive のドキュメントを開きます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1553">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="a8210-1554">ユーザーの変更履歴とコメントの色が、ユーザーのカーソルの色と一致することを確認します。</span><span class="sxs-lookup"><span data-stu-id="a8210-1554">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a8210-1555">主な修正:</span><span class="sxs-lookup"><span data-stu-id="a8210-1555">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1556">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1556">Word</span></span> 
- <span data-ttu-id="a8210-1557">オプションの表示中に 'Esc' キーを押すと発生するクラッシュの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1557">We fixed a crashing issue that occurred when pressing 'ESC' while in Options</span></span>
- <span data-ttu-id="a8210-1558">Word から PowerPoint Online へのコピーと貼り付けで発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1558">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-1559">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-1559">Excel</span></span>
- <span data-ttu-id="a8210-1560">保護されたドキュメントや編集可能なドキュメントを開いているときに Excel でセルをコピーすると CPU 使用率が高くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1560">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-1561">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-1561">PowerPoint</span></span>
- <span data-ttu-id="a8210-1562">PowerPoint で @メンションを使用するときのスライド イメージのサイズに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1562">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1563">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1563">Outlook</span></span>
- <span data-ttu-id="a8210-1564">Outlook Search が選択した日付の並べ替えを使用しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1564">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="a8210-1565">"このタスクを開く" ワークフロー リボンのボタンが特定のメールで応答しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1565">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="a8210-1566">ユーザーが Outlook の会議室の検索で空いている会議室を選択した後、社内の会議室がクリアされなくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1566">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="a8210-1567">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-1567">Access</span></span>
- <span data-ttu-id="a8210-1568">テーブルとデータソースの再リンクを確認するときに表示されるメッセージを更新しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1568">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="a8210-1569">ダーク テーマで白い背景に白いテキストが表示されていた、保存済みのインポート/エクスポートのダイアログを修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1569">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="a8210-1570">表のデザインのテキストボックスに [Yes/No] フィールドの表示コントロール プロパティを設定できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1570">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="a8210-1571">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-1571">Project</span></span>
- <span data-ttu-id="a8210-1572">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1572">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="a8210-1573">2019 年 2 月 15 日</span><span class="sxs-lookup"><span data-stu-id="a8210-1573">February 15, 2019</span></span> 
<span data-ttu-id="a8210-1574">バージョン 1903 (ビルド 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="a8210-1574">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a8210-1575">新機能:</span><span class="sxs-lookup"><span data-stu-id="a8210-1575">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-1576">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-1576">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="a8210-1577">画面切り替え効果の機能強化 - 名前で変形</span><span class="sxs-lookup"><span data-stu-id="a8210-1577">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="a8210-1578">変形する図形を指定します</span><span class="sxs-lookup"><span data-stu-id="a8210-1578">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a8210-1579">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="a8210-1579">Getting Started:</span></span>

- <span data-ttu-id="a8210-1580">[変形] で 2 つのオブジェクトを同じオブジェクトとして扱うために、[選択] ウィンドウを使って図形の名前を変更することができます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1580">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="a8210-1581">[変形] で名前を使って既定のマッチング動作を上書きするには、</span><span class="sxs-lookup"><span data-stu-id="a8210-1581">The name must be prefaced with "!!"</span></span> <span data-ttu-id="a8210-1582">名前の前に "!!" (2 つの感嘆符) を付ける必要があります (例: "!!Name")。</span><span class="sxs-lookup"><span data-stu-id="a8210-1582">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. "!!Name"</span></span>
- <span data-ttu-id="a8210-1583">ユーザーは、名前の先頭に "!!" が付いていない図形の名前変更を続行することができます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1583">Users can continue to rename shapes with any name that doesn't start with "!!"</span></span> <span data-ttu-id="a8210-1584">[変形] の動作が変更されることを気にする必要はありません</span><span class="sxs-lookup"><span data-stu-id="a8210-1584">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a8210-1585">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="a8210-1585">Scenarios to Try:</span></span>

- <span data-ttu-id="a8210-1586">スライドに図形 (たとえば、四角形) を挿入します</span><span class="sxs-lookup"><span data-stu-id="a8210-1586">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="a8210-1587">新しいスライドを作成します</span><span class="sxs-lookup"><span data-stu-id="a8210-1587">Create a new slide</span></span>
- <span data-ttu-id="a8210-1588">2 枚目のスライドに別の図形 (たとえば、三角形) を挿入します</span><span class="sxs-lookup"><span data-stu-id="a8210-1588">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="a8210-1589">[オブジェクトの選択と表示] でスライド 1 の四角形の名前を "!!shape" に変更し、スライド 2 の三角形の名前を "!!shape" に変更します</span><span class="sxs-lookup"><span data-stu-id="a8210-1589">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="a8210-1590">2 枚目のスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="a8210-1590">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="a8210-1591">画面切り替え効果の機能強化 - SmartArt</span><span class="sxs-lookup"><span data-stu-id="a8210-1591">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="a8210-1592">SmartArt の変形をより滑らかに切り替え</span><span class="sxs-lookup"><span data-stu-id="a8210-1592">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a8210-1593">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="a8210-1593">Getting Started:</span></span>

<span data-ttu-id="a8210-1594">SmartArt と同様の方法で変形を使用します</span><span class="sxs-lookup"><span data-stu-id="a8210-1594">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a8210-1595">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="a8210-1595">Scenarios to Try:</span></span>

- <span data-ttu-id="a8210-1596">スライドに SmartArt を挿入します</span><span class="sxs-lookup"><span data-stu-id="a8210-1596">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="a8210-1597">スライドを複製します</span><span class="sxs-lookup"><span data-stu-id="a8210-1597">Duplicate the Slide</span></span>
- <span data-ttu-id="a8210-1598">複製されたスライド上で SmartArt のサイズ変更/変更/移動を行います</span><span class="sxs-lookup"><span data-stu-id="a8210-1598">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="a8210-1599">複製されたスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="a8210-1599">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="a8210-1600">画面切り替え効果の機能強化 - 表</span><span class="sxs-lookup"><span data-stu-id="a8210-1600">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="a8210-1601">表の変形をより滑らかに切り替え</span><span class="sxs-lookup"><span data-stu-id="a8210-1601">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a8210-1602">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="a8210-1602">Getting Started:</span></span>
<span data-ttu-id="a8210-1603">表と同様の方法で変形を使用します</span><span class="sxs-lookup"><span data-stu-id="a8210-1603">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a8210-1604">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="a8210-1604">Scenarios to Try:</span></span>

- <span data-ttu-id="a8210-1605">スライドに表を挿入します</span><span class="sxs-lookup"><span data-stu-id="a8210-1605">Insert a Table in a slide</span></span>
- <span data-ttu-id="a8210-1606">スライドを複製します</span><span class="sxs-lookup"><span data-stu-id="a8210-1606">Duplicate the slide</span></span>
- <span data-ttu-id="a8210-1607">複製されたスライド上で表のサイズ変更/変更/移動を行います</span><span class="sxs-lookup"><span data-stu-id="a8210-1607">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="a8210-1608">複製されたスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="a8210-1608">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="a8210-1609">Word、Excel、PowerPoint、OneNote、Access、Project、Publisher、Visio</span><span class="sxs-lookup"><span data-stu-id="a8210-1609">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="a8210-1610">アカウントをシームレスに切り替える</span><span class="sxs-lookup"><span data-stu-id="a8210-1610">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="a8210-1611">新しいアカウント マネージャーでは、仕事用アカウントと個人用アカウントのすべてが 1 か所に表示されます。また、アカウントを自由に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="a8210-1611">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="a8210-1612">この更新されたエクスペリエンスでは、ログイン方法がわかりやすくなりました。また、先にサインアウトしたり複雑なダイアログを操作したりする必要なく、仕事用アカウントと個人用アカウントを切り替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1612">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="a8210-1614">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="a8210-1614">Scenarios to Try:</span></span>
- <span data-ttu-id="a8210-1615">アカウントを切り替えます</span><span class="sxs-lookup"><span data-stu-id="a8210-1615">Switch between accounts</span></span>
- <span data-ttu-id="a8210-1616">新しいアカウントを追加します [注: [ファイル]、[アカウント]、[接続済みサービス] の順に移動してから、仕事用アカウントに接続されている個人用サービス (またはその逆) を削除することができます]</span><span class="sxs-lookup"><span data-stu-id="a8210-1616">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="a8210-1617">アカウントからサインアウトします</span><span class="sxs-lookup"><span data-stu-id="a8210-1617">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="a8210-1618">主な修正:</span><span class="sxs-lookup"><span data-stu-id="a8210-1618">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1619">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1619">Word</span></span> 
- <span data-ttu-id="a8210-1620">表と画像のコンテキスト プレビューに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1620">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-1621">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-1621">Excel</span></span>
- <span data-ttu-id="a8210-1622">[黒] のテーマでオートフィルターの [検索] フィールドのテキストが白くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1622">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="a8210-1623">新しい Office アドインの同意の UI に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1623">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-1624">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-1624">PowerPoint</span></span>
- <span data-ttu-id="a8210-1625">ノート PC またはタブレットでスライドショーを表示すると、表示が自動的に拡大される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="a8210-1625">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1626">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1626">Outlook</span></span>
- <span data-ttu-id="a8210-1627">[OneNote に送る] ボタンの表示に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1627">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="a8210-1628">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-1628">Access</span></span>
- <span data-ttu-id="a8210-1629">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1629">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a8210-1630">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-1630">Project</span></span>
- <span data-ttu-id="a8210-1631">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1631">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="a8210-1632">2019 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="a8210-1632">February 11, 2019</span></span>
<span data-ttu-id="a8210-1633">バージョン 1903 (ビルド 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="a8210-1633">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="a8210-1634">主な修正:</span><span class="sxs-lookup"><span data-stu-id="a8210-1634">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1635">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1635">Word</span></span> 
- <span data-ttu-id="a8210-1636">一部のカスタマイズされたスタイルを Word Online に適用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1636">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="a8210-1637">Word のリッチ オブジェクトでのコンテキスト プレビューに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1637">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="a8210-1638">リストを貼り付けると Word がクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1638">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-1639">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-1639">Excel</span></span>
- <span data-ttu-id="a8210-1640">通貨記号がない場合に、数値の書式の後ろに追加されるスペースが表示されない問題を修正しました特殊文字</span><span class="sxs-lookup"><span data-stu-id="a8210-1640">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="a8210-1641">株価の自動検出に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1641">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-1642">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-1642">PowerPoint</span></span>
- <span data-ttu-id="a8210-1643">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1643">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1644">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1644">Outlook</span></span>
- <span data-ttu-id="a8210-1645">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1645">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="a8210-1646">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-1646">Access</span></span>
- <span data-ttu-id="a8210-1647">パフォーマンスと安定性のさまざまな問題の修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1647">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a8210-1648">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-1648">Project</span></span>
- <span data-ttu-id="a8210-1649">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1649">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="a8210-1650">2019 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="a8210-1650">February 1, 2019</span></span> 
<span data-ttu-id="a8210-1651">バージョン 1902 (ビルド 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="a8210-1651">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="a8210-1652">主な修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1652">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="a8210-1653">Word</span><span class="sxs-lookup"><span data-stu-id="a8210-1653">Word</span></span> 
- <span data-ttu-id="a8210-1654">埋め込まれた Excel の表のセルのサイズ変更に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1654">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="a8210-1655">描画キャンバス内の図形のコピー/貼り付けの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1655">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="a8210-1656">Excel</span><span class="sxs-lookup"><span data-stu-id="a8210-1656">Excel</span></span>
- <span data-ttu-id="a8210-1657">Excel Web App からファイルを開く際の問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1657">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="a8210-1658">CSV ファイルを .XLSX として保存する際にファイル名のサイズが原因で失敗する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1658">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="a8210-1659">コンテキスト メニューのオプションの表示に関してコンテキスト メニューを修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1659">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a8210-1660">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a8210-1660">PowerPoint</span></span>
- <span data-ttu-id="a8210-1661">角かっこを入力するためにユーザーがキーボード ショートカット Ctrl+Alt+7 および Ctrl+Alt+8 を使用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1661">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="a8210-1662">ローカル ビデオを PowerPoint に挿入すると C ドライブのディスク領域が減ってしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1662">We fixed an issue where inserting a local video into the PPT would reduce the 'C' drive disk space</span></span>
- <span data-ttu-id="a8210-1663">一部のユーザーに表示されていなかった [Microsoft Stream に公開する] ボタンを修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1663">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="a8210-1664">Outlook</span><span class="sxs-lookup"><span data-stu-id="a8210-1664">Outlook</span></span>
- <span data-ttu-id="a8210-1665">カレンダーのタスク ビューでタスクの件名が正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1665">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="a8210-1666">Access</span><span class="sxs-lookup"><span data-stu-id="a8210-1666">Access</span></span>
- <span data-ttu-id="a8210-1667">グラフのスケーリングの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="a8210-1667">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="a8210-1668">Project</span><span class="sxs-lookup"><span data-stu-id="a8210-1668">Project</span></span>
- <span data-ttu-id="a8210-1669">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="a8210-1669">Various performance and stability fixes</span></span>
