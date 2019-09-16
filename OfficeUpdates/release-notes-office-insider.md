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
ms.openlocfilehash: 372816fa81f0f5284a795f02edd9b1b4bb00c3f6
ms.sourcegitcommit: d92c236702bae7efd84bd21b539cb7343b6973ba
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/13/2019
ms.locfileid: "36980453"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="fe245-103">Office Insider のリリース ノート</span><span class="sxs-lookup"><span data-stu-id="fe245-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="fe245-104">この記事には、Windows デスクトップ向け Word、Excel、PowerPoint、Outlook、Access、Project の Insider ビルドのリリース ノートが含まれています。</span><span class="sxs-lookup"><span data-stu-id="fe245-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="fe245-105">Microsoft では、毎週、皆様にお知らせしたい魅力的な新機能、重要な修正プログラム、重大な問題に関する情報を提供しています。</span><span class="sxs-lookup"><span data-stu-id="fe245-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="fe245-106">多くの場合、機能 (場合によっては修正プログラムも) は、特定の期間にわたって Insider にロールアウトされます。</span><span class="sxs-lookup"><span data-stu-id="fe245-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="fe245-107">これにより、Microsoft では、より広範な対象ユーザーに機能をリリースする前に、作業がスムーズに行われていることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="fe245-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="fe245-108">したがって、下記のものが表示されない場合でも、心配する必要はなく、いずれは表示されます。</span><span class="sxs-lookup"><span data-stu-id="fe245-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="fe245-109">リリース ノートは毎週投稿され、場合により複数のビルドのコンパイルになります</span><span class="sxs-lookup"><span data-stu-id="fe245-109">Release notes are posted weekly and may be a compilation of multiple builds</span></span>
> - <span data-ttu-id="fe245-110">リリースノートの発行日は実際のビルドのリリース日と一致しない場合があります</span><span class="sxs-lookup"><span data-stu-id="fe245-110">The release notes publication date may not match the actual build release date</span></span>

 > [!NOTE]
> - <span data-ttu-id="fe245-111">Microsoft Teams に関連する既存の Office 365 ProPlus のインストール - 6 月の下旬から、これらの更新プログラムのインストール時に、Microsoft Teams が既存の Office 365 ProPlus (Office 365 Business) のインストールの中に含められます。</span><span class="sxs-lookup"><span data-stu-id="fe245-111">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="fe245-112">Teams が追加される日にちは、使用している更新プログラム チャネルによって異なります。</span><span class="sxs-lookup"><span data-stu-id="fe245-112">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="fe245-113">追加情報については、「[Office 365 ProPlus と同時に Microsoft Teams を展開する](https://docs.microsoft.com/ja-JP/deployoffice/teams-install)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="fe245-113">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/ja-JP/deployoffice/teams-install) for additional information.</span></span>

[//]: # (削除しないでください)


## <a name="version-1910-september-13"></a><span data-ttu-id="fe245-115">バージョン 1910: 9 月 13 日</span><span class="sxs-lookup"><span data-stu-id="fe245-115">Version 1910: September 13</span></span>
<span data-ttu-id="fe245-116">*バージョン 1910 (ビルド 12105.20000)*</span><span class="sxs-lookup"><span data-stu-id="fe245-116">*Version 1910 (Build 12105.20000)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="fe245-118">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="fe245-118">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="fe245-119">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-119">Excel</span></span>

- <div><span data-ttu-id="fe245-120"><span>一部の保護されたシートにユーザーがハイパーリンクを貼り付けられない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-120"><span>We fixed an issue which could prevent a user from pasting hyperlinks in some protected sheets</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="fe245-121">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-121">Outlook</span></span>

- <div><span data-ttu-id="fe245-122"><span>コンパクト ビューで UI が動かなくなる問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-122"><span>We fixed an issue where the UI could get stuck in a compact view</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="fe245-123">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-123">PowerPoint</span></span>

- <div><span data-ttu-id="fe245-124"><span>PDFへの印刷時、ユーザーにエラーが発生する問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-124"><span>We fixed an issue where a user could experience an error upon printing to PDF</span></span></span></div>


### <a name="project"></a><span data-ttu-id="fe245-125">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-125">Project</span></span>

- <div><span data-ttu-id="fe245-126"><span>問題を修正しました (<span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">保護された作業が有効になっている場合、サマリー タスクの作業値を変更するとクラッシュする</span></span>)</span><span class="sxs-lookup"><span data-stu-id="fe245-126"><span>We fixed an issue where <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">changes to a work value on a summary task could cause a crash if protected work is enabled</span></span></span></span></div>


- <span data-ttu-id="fe245-127"><font size=2 style="background-color:rgb(255, 255, 255);">エンタープライズ カレンダーとイベントを同期する機能を阻害する可能性がある問題を修正しました</font></span><span class="sxs-lookup"><span data-stu-id="fe245-127"><font size=2 style="background-color:rgb(255, 255, 255);">We fixed an issue which could inhibit the ability to sync events with enterprise calendars</font></span></span>


### <a name="office-suite"></a><span data-ttu-id="fe245-128">Office スイート</span><span class="sxs-lookup"><span data-stu-id="fe245-128">Office Suite</span></span>

- <div><span data-ttu-id="fe245-129"><span>ファイルのローカル バージョンの破棄を促す警告が繰り返し発生する可能性がある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-129"><span>We fixed an issue which could cause a repeated warning to discard local versions of a file</span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1910-september-06"></a><span data-ttu-id="fe245-131">バージョン 1910: 9 月 6 日</span><span class="sxs-lookup"><span data-stu-id="fe245-131">Version 1910: September 06</span></span>
<span data-ttu-id="fe245-132">*バージョン 1910 (ビルド 12030.20004)*</span><span class="sxs-lookup"><span data-stu-id="fe245-132">*Version 1910 (Build 12030.20004)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="fe245-134">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="fe245-134">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="fe245-135">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-135">Excel</span></span>

- <span data-ttu-id="fe245-136">**準備ができたら、描画を開始:** Surface ペンを持てば、描画の準備完了です。</span><span class="sxs-lookup"><span data-stu-id="fe245-136">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="fe245-137">詳細情報</span><span class="sxs-lookup"><span data-stu-id="fe245-137">Learn more</span></span>](https://support.office.com/ja-JP/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="powerpoint"></a><span data-ttu-id="fe245-138">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-138">PowerPoint</span></span>

- <span data-ttu-id="fe245-139">**準備ができたら、描画を開始:** Surface ペンを持てば、描画の準備完了です。</span><span class="sxs-lookup"><span data-stu-id="fe245-139">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="fe245-140">詳細情報</span><span class="sxs-lookup"><span data-stu-id="fe245-140">Learn more</span></span>](https://support.office.com/ja-JP/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a><span data-ttu-id="fe245-141">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-141">Word</span></span>

- <span data-ttu-id="fe245-142">**準備ができたら、描画を開始:** Surface ペンを持てば、描画の準備完了です。</span><span class="sxs-lookup"><span data-stu-id="fe245-142">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="fe245-143">詳細情報</span><span class="sxs-lookup"><span data-stu-id="fe245-143">Learn more</span></span>](https://support.office.com/ja-JP/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="fe245-146">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="fe245-146">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="fe245-147">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-147">Excel</span></span>

- <div><span data-ttu-id="fe245-148"><span> リボンのフォント名が使用されているフォントと異なることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-148"><span>We fixed an issue which could cause the font name in the ribbon to be different from the font being used</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="fe245-149">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-149">Outlook</span></span>

- <div><span data-ttu-id="fe245-150"><span> Internet Explorer で制限付きサイトの保護モードが無効になると、Outlook により不適切なリソースの使用量になることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-150"><span>We fixed an issue that could result in inappropriate resource consumption by Outlook when Protected Mode is disabled for Restricted Sites in Internet Explorer</span></span></span></div>


- <div><span data-ttu-id="fe245-151"><span>時々、ANSI ソースのテキスト貼り付けるときに Unicode 文字が表示されることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-151"><span>We fixed an issue which could sometimes cause Unicode characters to appear when pasting text from an ANSI source</span></span></span></div>


- <div><span data-ttu-id="fe245-152"><span>グループ スケジュール ビューで一部のユーザーがオフラインとして間違って表示される問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-152"><span>We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span></span></div>


### <a name="word"></a><span data-ttu-id="fe245-153">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-153">Word</span></span>

- <div><span data-ttu-id="fe245-154"><span>テーブルの書式設定が失われることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-154"><span>We fixed an issue where table formatting could be lost</span></span></span></div>


- <div><span data-ttu-id="fe245-155"><span>Ctrl + V ショートカット キーが効かなくなることがある問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-155"><span>We fixed an issue which could break the ctrl+v keyboard shortcut</span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1909-august-30"></a><span data-ttu-id="fe245-157">バージョン 1909: 8 月 30 日</span><span class="sxs-lookup"><span data-stu-id="fe245-157">Version 1909: August 30</span></span>
<span data-ttu-id="fe245-158">*バージョン 1909 (ビルド 12026.20000)*</span><span class="sxs-lookup"><span data-stu-id="fe245-158">*Version 1909 (Build 12026.20000)*</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="fe245-160">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="fe245-160">Feature updates</span></span>

### <a name="access"></a><span data-ttu-id="fe245-161">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-161">Access</span></span>

- <span data-ttu-id="fe245-162">**リンク テーブルの高速検索:** 新しい検索ボックスにより、リンク テーブルを簡単に見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="fe245-162">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-163">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-163">PowerPoint</span></span>

- <span data-ttu-id="fe245-164">**図を SVG として保存する:** グラフ、図形、その他の図を、サイズ変更しても画質が低下しないスケーラブル ベクター グラフィックとして保存できます。</span><span class="sxs-lookup"><span data-stu-id="fe245-164">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="fe245-165">詳細情報</span><span class="sxs-lookup"><span data-stu-id="fe245-165">Learn more</span></span>](https://support.office.com/ja-JP/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="fe245-168">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="fe245-168">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="fe245-169">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-169">Excel</span></span>

- <div><span data-ttu-id="fe245-170"><span>&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">秘密度</span>のキー ヒントが&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">別のキー ヒントと競合している問題が修正されました。</span></span></span><span class="sxs-lookup"><span data-stu-id="fe245-170"><span>We fixed an issue where the keytip for&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">Sensitivity </span>was&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">conflicting with another keytip.</span></span></span></span></div>

- <div><span data-ttu-id="fe245-171"><span>共有ブックでの作業中に保存を行おうとする際に発生する問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="fe245-171"><span>We fixed an issue that occurred while working on a shared workbook when trying to save.</span></span></span></div>

- <div><span data-ttu-id="fe245-172"><span>Excel で、レジストリ値 "\Excel\Add-in Manager" にあるアドインのうち、最初の 16 個しか表示されない問題が修正されました。<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span><span class="sxs-lookup"><span data-stu-id="fe245-172"><span>We fixed an issue where Excel only lists the first 16 addins located in the '\Excel\Add-in Manager' registry values.<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span></span></div>


- <div><span data-ttu-id="fe245-173"><span>関数 Frequency() が誤った結果を返す問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="fe245-173"><span>We fixed an issue where the function Frequency() returns incorrect results.</span></span></span></div>


- <div><span data-ttu-id="fe245-174"><span>色によるフィルター処理のパフォーマンスが大幅に改善されました。</span></span><span class="sxs-lookup"><span data-stu-id="fe245-174"><span>We have significantly improved the performance of filtering by color.</span></span></span></div>


- <div><span data-ttu-id="fe245-175"><span>Surface のユーザーがマウスを動かすと、それがマウス クリックのイベントとして解釈されることがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="fe245-175"><span>We fixed an issue for Surface users where moving the mouse could be interpreted as a mouse click event.</span></span></span></div>


- <div><span data-ttu-id="fe245-176"><span>[検索と置換] ダイアログでキーボードによるナビゲーションを行えない問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-176"><span>We fixed an issue which prevented keyboard navigation in the Find/Replace dialog</span></span></span></div>


- <div><span data-ttu-id="fe245-177"><span>一部のフォント名が正しく表示されない問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-177"><span>We fixed an issue where the name of some fonts were not displayed correctly</span></span></span></div>


- <div><span data-ttu-id="fe245-178"><span>サポートされているファイル形式として CSV が表示されない問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-178"><span>We fixed an issue which prevented CSV from appearing as a supported file type</span></span></span></div>


### <a name="access"></a><span data-ttu-id="fe245-179">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-179">Access</span></span>

- <div><span data-ttu-id="fe245-180">共有データベースの使用中に、"&quot;矛盾がある状態&quot;" エラーがユーザーに表示されることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="fe245-180">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


- <div><span data-ttu-id="fe245-181"><span>日付選択カレンダーが表示されるべきではないときに表示されてしまうことがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="fe245-181"><span>We fixed an issue which could cause the date picker to appear when it shouldn't</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="fe245-182">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-182">Outlook</span></span>

- <div><span data-ttu-id="fe245-183"><span>一部の POP3 ユーザーに HTML コンテンツが表示されない問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-183"><span>We fixed an issue which prevented HTML content from appearing for some POP3 users</span></span></span></div>


- <div><span data-ttu-id="fe245-184"><span>Planner を利用できない環境で、連絡先カードのオーバーフロー メニューから機能しない [Planner] リンクを削除するための修正を行いました。</span></span><span class="sxs-lookup"><span data-stu-id="fe245-184"><span>We fixed an issue to remove non-functional 'Planner' link from the overflow menu in the contact card when working in environments where it is not available.</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="fe245-185">OneNote</span><span class="sxs-lookup"><span data-stu-id="fe245-185">OneNote</span></span>

- <div><span data-ttu-id="fe245-186"><span>フォーカスが &nbsp;OneNote のバックグラウンド同期に移動してしまうことがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="fe245-186"><span>We fixed an issue where&nbsp;OneNote background sync was sometimes stealing focus.</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="fe245-187">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-187">PowerPoint</span></span>

- <div><span data-ttu-id="fe245-188"><span>3-D Turntable の回転の向きに影響を与えていた問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="fe245-188"><span>We fixed an issue which would affect the rotation orientation of a 3D Turntable.</span></span></span></div>

- <div><span data-ttu-id="fe245-189"><span>ハイパーリンクに特殊文字が含まれている場合に一部のハイパーリンクが機能しない問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="fe245-189"><span>We fixed an issue which prevented some hyperlinks from working if they contained special characters.</span></span></span></div>

- <div><span data-ttu-id="fe245-190"><span>同時に複数のコメント ウィンドウが開かれる問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="fe245-190"><span>We fixed an issue which caused multiple comment panes to open at the same time.</span></span></span></div>

### <a name="project"></a><span data-ttu-id="fe245-191">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-191">Project</span></span>

- <div><span data-ttu-id="fe245-192"><span>チーム プランナー ビューを印刷した後にクラッシュすることがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="fe245-192"><span>We fixed an issue which could sometimes cause a crash after printing a Team Planner view.</span></span></span></div>

### <a name="word"></a><span data-ttu-id="fe245-193">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-193">Word</span></span>

- <div><span data-ttu-id="fe245-194">閲覧表示で、縦書きテキスト ボックス内の複数バイト文字が重なって表示される問題が<span>修正されました。</span><span class="sxs-lookup"><span data-stu-id="fe245-194">We f<span>ixed an issue where multi-byte characters in vertical text box are shown overlapped in reading view.</span></span><br></span></div>

- <div><span data-ttu-id="fe245-195"><span>&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">ユーザーがアドイン ウィザードでアクションを実行する際に、日本語のはがきとグリーティング カードに関連するアドインのリソースが見つからない問題が修正されました。</span></span></span><span class="sxs-lookup"><span data-stu-id="fe245-195"><span>We&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">fixed an issue where Japanese post card and greeting card related addin resources are not found when the user takes action in the addin wizard.</span></span></span></span></div>

- <div><span data-ttu-id="fe245-196"><span>保護ビューで表示中に、タイトル バーのユーザー インターフェイスで問題を発生させることがある問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="fe245-196"><span>We fixed an issue which could cause issues with the Title Bar User Interface when in Protected View</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="fe245-197">Office スイート</span><span class="sxs-lookup"><span data-stu-id="fe245-197">Office Suite</span></span>

- <div><span data-ttu-id="fe245-198"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">標準の図形とコネクタ図形の両方が含まれる選択部分に対して [図形の変更] を適用するとファイルが破損する問題が修正されました。</span></span></span><span class="sxs-lookup"><span data-stu-id="fe245-198"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> We fixed a corrupt file issue when you Change Shape on a selection that contains both a normal shape and a connector shape.</span></span></span></span></div>

- <div><span data-ttu-id="fe245-199"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">複数の外付けモニターからドッキングとドッキングの解除を使用すると、アプリケーションに問題が発生する</span>問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="fe245-199"><span>We fixed an issue that <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">caused a problem in applications when using dock/undock from multiple external displays. </span></span></span></span></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="august-23-2019br"></a><span data-ttu-id="fe245-201">**2019 年 8 月 23 日**</span><span class="sxs-lookup"><span data-stu-id="fe245-201">**August 23, 2019**</span></span><br/>
<span data-ttu-id="fe245-202">バージョン 1909 (ビルド 12015.20004)</span><span class="sxs-lookup"><span data-stu-id="fe245-202">Version 1909 (Build 12015.20004)</span></span><br/>



## <a name="non-security-updates"></a><span data-ttu-id="fe245-203">セキュリティ以外の更新プログラム:</span><span class="sxs-lookup"><span data-stu-id="fe245-203">Non-security updates</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-204">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-204">Excel</span></span>

- <div><span data-ttu-id="fe245-205"><span>結合されたセルで列を削除するパフォーマンスが大幅に改善されました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-205"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="fe245-206">Office スイート</span><span class="sxs-lookup"><span data-stu-id="fe245-206">Office Suite</span></span>

- <div><span data-ttu-id="fe245-207"><span>一部の Unicode 文字がブラウザー上で表示されない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-207"><span>We fixed an issue which could prevent some Unicode characters from being displayed when viewed in a browser</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="fe245-208">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-208">Outlook</span></span>

- <div><span data-ttu-id="fe245-209"><span>WebDAV の場所にファイルを保存できないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-209"><span>We fixed an issue which could have prevented files from being saved to a WebDAV location</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="fe245-210">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-210">PowerPoint</span></span>

- <div><span data-ttu-id="fe245-211"><span>ユーザーがあるコメントをクリックすると別のコメントが選択される問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-211"><span>We fixed an issue where a user would click on one comment, but another comment would be selected</span></span></span></div>





## <a name="august-16-2019br"></a><span data-ttu-id="fe245-212">**2019 年 8 月 16 日**</span><span class="sxs-lookup"><span data-stu-id="fe245-212">**August 16, 2019**</span></span><br/>
<span data-ttu-id="fe245-213">バージョン 1909 (ビルド 12013.20000)</span><span class="sxs-lookup"><span data-stu-id="fe245-213">Version 1909 (Build 12013.20000)</span></span><br/>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="fe245-214">PowerPoint 機能の更新:</span><span class="sxs-lookup"><span data-stu-id="fe245-214">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="fe245-215">**配布資料にスライド番号を印刷する:** スライド番号は配布資料に自動的に含まれます。</span><span class="sxs-lookup"><span data-stu-id="fe245-215">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="fe245-216">それらをオンのままにするか、オフにするか、選択します。</span><span class="sxs-lookup"><span data-stu-id="fe245-216">Leave them on, turn them off, it's all up to you.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="fe245-217">セキュリティ以外の更新プログラム:</span><span class="sxs-lookup"><span data-stu-id="fe245-217">Non-security updates</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-218">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-218">Excel</span></span>

- <div><span data-ttu-id="fe245-219"><span>自動保存が有効になることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-219"><span>We fixed an issue which could cause AutoSave to become enabled</span></span></span></div>


- <div><span data-ttu-id="fe245-220">セルの高さが不正確に測定されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-220">We fixed an issue which could result in cell heights being measured inaccurately</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="fe245-221">Office スイート</span><span class="sxs-lookup"><span data-stu-id="fe245-221">Office Suite</span></span>

- <div><span data-ttu-id="fe245-222"><span>コメント機能のパフォーマンスを大幅に改善する問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-222"><span>We fixed an issue which significantly improves the performance of the Comments feature</span></span></span></div>


- <div><span data-ttu-id="fe245-223"><span>検索中に方向キーを使用するとクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-223"><span>We fixed an issue which could cause a crash when using arrow keys while in search</span></span></span></div>


- <div><span data-ttu-id="fe245-224"><span>@ 記号が特定の文字の後に配置された場合に @メンションを使用できないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-224"><span>We fixed an issue which could prevent an @ mention if the @ symbol was placed after certain characters</span></span></span></div>


- <div><span data-ttu-id="fe245-225"><span>@メンションを削除するとクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-225"><span>We fixed an issue which could sometimes cause a crash when deleting @ mentions</span></span></span></div>


- <div><span data-ttu-id="fe245-226"><span>コメント カードに絵文字が正しく表示されない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-226"><span>We fixed an issue which prevented emojis from displaying correctly in comment cards</span></span></span></div>


- <div><span data-ttu-id="fe245-227"><span>アクティブ​​ クリップボード​​でクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-227"><span>We fixed an issue with Active Clipboard which could sometimes result in a crash</span></span></span></div>


- <div><span data-ttu-id="fe245-228"><span>クイック アクセス ツール バーのボタンが機能しなくなることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-228"><span>We fixed an issue which could cause the Quick Access Toolbar buttons to stop working</span></span></span></div>


- <div><span data-ttu-id="fe245-229"><span>文書の書式設定プレビュー​​がバックグラウンドに切り替わらないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-229"><span>We fixed an issue which could prevent the Document Formatting Preview from switching to the background</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="fe245-230">OneNote</span><span class="sxs-lookup"><span data-stu-id="fe245-230">OneNote</span></span>

- <span data-ttu-id="fe245-231">Office テーマが黒に設定されている場合、セクションのドロップダウン リストにセクションの名前が空白で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-231">We fixed an issue where the names of sections appear blank in the section dropdown list when Office Theme is set to Black.</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-232">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-232">Outlook</span></span>

- <div><span data-ttu-id="fe245-233"><span>Outlook が繰り返しフォーカスを取得して失うことがある送信イベントに関する問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-233"><span>We fixed an issue with Send Events which could cause Outlook to repeatedly gain and lose focus</span></span></span></div>


- <div><span data-ttu-id="fe245-234"><span>[フォルダーに返信を投稿] ショートカットが機能しない問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-234"><span>We fixed an issue which prevented the Post Reply to Folder shortcut from working</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="fe245-235">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-235">PowerPoint</span></span>

- <div><span data-ttu-id="fe245-236"><span>共同作業の際に問題を引き起こすことがある保護ビューの問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-236"><span>We fixed an issue with Protected View which could sometimes cause problems when collaborating</span></span></span></div>


- <div><span data-ttu-id="fe245-237"><span>コメント ウィンドウのタスクが適切に表示されないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-237"><span>We fixed an issue which could prevent tasks in comment panes from displaying properly</span></span></span></div>


- <div><span data-ttu-id="fe245-238"><span>新しいスライドを挿入するときにクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-238"><span>We fixed an issue which could cause a crash when inserting new slides</span></span></span></div>


### <a name="user-lifecycle"></a><span data-ttu-id="fe245-239">ユーザーのライフサイクル</span><span class="sxs-lookup"><span data-stu-id="fe245-239">User Lifecycle</span></span>

- <div><span data-ttu-id="fe245-240"><span>サブスクリプション機能が消えることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-240"><span>We fixed an issue which could sometimes result in subscription features disappearing</span></span></span></div>


### <a name="word"></a><span data-ttu-id="fe245-241">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-241">Word</span></span>

- <div><span data-ttu-id="fe245-242"><span>ハイパーリンクに特定の文字が含まれている場合、ハイパーリンクが壊れることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-242"><span>We fixed an issue where hyperlinks could be broken if the hyperlink contained certain characters</span></span></span></div>


- <div><span data-ttu-id="fe245-243"><span>画像のコメントを表示するときに画像のサイズが不適切になることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-243"><span>We fixed an issue where images could be improperly sized when viewing a comment for that image</span></span></span></div>


- <div><span data-ttu-id="fe245-244"><span>箇条書きのドロップダウン メニューでクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-244"><span>We fixed an issue with the Bullet List drop down menu which could sometimes result in a crash</span></span></span></div>





## <a name="august-09-2019br"></a><span data-ttu-id="fe245-245">**2019 年 8 月 9 日**</span><span class="sxs-lookup"><span data-stu-id="fe245-245">**August 09, 2019**</span></span><br/>
<span data-ttu-id="fe245-246">バージョン 1909 (ビルド 12001.20000)</span><span class="sxs-lookup"><span data-stu-id="fe245-246">Version 1909 (Build 12001.20000)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="fe245-247">Excel 機能の更新</span><span class="sxs-lookup"><span data-stu-id="fe245-247">Excel: Feature updates</span></span>

- <span data-ttu-id="fe245-248">**共同作業がさらに簡単に:** 共同編集の改善とは、条件付き書式、セルのスタイルなどを使用して作業しているときに、ユーザーによる変更がシームレスに共同作業者のそれらと統合されるということを意味します。</span><span class="sxs-lookup"><span data-stu-id="fe245-248">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>


- <span data-ttu-id="fe245-249">**検索して楽しむ:** 目的のアイコンを簡単に検索できるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="fe245-249">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="fe245-250">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="fe245-250">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="office-suite-feature-updates"></a><span data-ttu-id="fe245-251">Office スイートの機能の更新</span><span class="sxs-lookup"><span data-stu-id="fe245-251">Office Suite: Feature updates</span></span>

- <span data-ttu-id="fe245-252">**新しい Office アプリのアイコン:** シンプルかつ高性能で、インテリジェントな Office のエクスペリエンスを反映するように、アプリのアイコンがリニューアルされました。</span><span class="sxs-lookup"><span data-stu-id="fe245-252">**New Office App Icons:** Redesigned app icons to reflect the simple, powerful, and intelligent experiences of Office.</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="fe245-253">Outlook 機能の更新</span><span class="sxs-lookup"><span data-stu-id="fe245-253">Outlook: Feature updates</span></span>

- <span data-ttu-id="fe245-254">**攻撃に対する高度な保護:** Office 365 Advanced Threat Protection を用いると、メールの件名、添付メッセージ、署名されたメッセージ、ネットワーク パスなどの範囲内のハイパーリンクを利用した攻撃から保護されます。</span><span class="sxs-lookup"><span data-stu-id="fe245-254">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>


- <span data-ttu-id="fe245-255">**検索して楽しむ:** 目的のアイコンを簡単に検索できるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="fe245-255">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="fe245-256">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="fe245-256">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="fe245-257">PowerPoint 機能の更新</span><span class="sxs-lookup"><span data-stu-id="fe245-257">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="fe245-258">**検索して楽しむ:** 目的のアイコンを簡単に検索できるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="fe245-258">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="fe245-259">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="fe245-259">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="fe245-260">Word 機能の更新</span><span class="sxs-lookup"><span data-stu-id="fe245-260">Word: Feature updates</span></span>

- <span data-ttu-id="fe245-261">**他のユーザーがすばやく変更を確認する:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="fe245-261">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


- <span data-ttu-id="fe245-262">**検索して楽しむ:** 目的のアイコンを簡単に検索できるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="fe245-262">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="fe245-263">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="fe245-263">And when you're selecting, the Insert button tells you how many you've picked.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="fe245-264">セキュリティ以外の更新プログラム:</span><span class="sxs-lookup"><span data-stu-id="fe245-264">Non-security updates</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-265">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-265">Outlook</span></span>

- <div><span data-ttu-id="fe245-266"><span>会議がキャンセルされた後に、会議の受信者が 2 つの通知を受け取る原因となっていた問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-266"><span>We fixed an issue which caused meeting recipients to receive two notifications after a meeting was cancelled</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="fe245-267">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-267">PowerPoint</span></span>

- <div><span data-ttu-id="fe245-268"><span>図形とアイコンの [線なし]、[塗りつぶしなし] をユーザーが選択したときに、クラッシュを引き起こす問題が修正されました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-268"><span>We fixed an issue which could cause a crash when the user selected No Outline or No Fill for Shapes and Icons</span></span></span></div>





## <a name="august-02-2019br"></a><span data-ttu-id="fe245-269">**2019 年 8 月 2 日**</span><span class="sxs-lookup"><span data-stu-id="fe245-269">**August 02, 2019**</span></span><br/>
<span data-ttu-id="fe245-270">バージョン 1908 (ビルド 11929.20002)</span><span class="sxs-lookup"><span data-stu-id="fe245-270">Version 1908 (Build 11929.20002)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="fe245-271">Excel 機能の更新</span><span class="sxs-lookup"><span data-stu-id="fe245-271">Excel: Feature updates</span></span>

- <span data-ttu-id="fe245-272">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="fe245-272">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="fe245-273">**ドキュメントに機密ラベルを適用する:** ファイルとメールに機密ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="fe245-273">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your documents to keep them compliant with your organization's information protection policies.  Learn More</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="fe245-274">Outlook 機能の更新</span><span class="sxs-lookup"><span data-stu-id="fe245-274">Outlook: Feature updates</span></span>

- <span data-ttu-id="fe245-275">**ドキュメントに機密ラベルを適用する:** ファイルとメールに機密ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="fe245-275">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your documents to keep them compliant with your organization's information protection policies.  Learn More</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="fe245-276">PowerPoint 機能の更新</span><span class="sxs-lookup"><span data-stu-id="fe245-276">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="fe245-277">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="fe245-277">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="fe245-278">**ドキュメントに機密ラベルを適用する:** ファイルとメールに機密ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="fe245-278">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your documents to keep them compliant with your organization's information protection policies.  Learn More</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="fe245-279">Word 機能の更新</span><span class="sxs-lookup"><span data-stu-id="fe245-279">Word: Feature updates</span></span>

- <span data-ttu-id="fe245-280">**ファイルを変換してアクセシビリティを向上させる:** ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="fe245-280">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="fe245-281">**別の言葉で伝える:** 別の言葉で伝えたいときに、[書き換え] でお助けします。</span><span class="sxs-lookup"><span data-stu-id="fe245-281">**Say it another way:** When you want to say it differently, Rewrite is there to help.</span></span> <span data-ttu-id="fe245-282">[書き換え] では、フレーズを洗練させるための別の言葉遣いを提供します。</span><span class="sxs-lookup"><span data-stu-id="fe245-282">Rewrite offers alternatives for finessing your phrases.</span></span>


- <span data-ttu-id="fe245-283">**ドキュメントに機密ラベルを適用する:** ファイルとメールに機密ラベルを適用すると、ドキュメントは組織の情報保護ポリシーに準拠したものになります。</span><span class="sxs-lookup"><span data-stu-id="fe245-283">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your documents to keep them compliant with your organization's information protection policies.  Learn More</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="fe245-284">セキュリティ以外の更新プログラム:</span><span class="sxs-lookup"><span data-stu-id="fe245-284">Non-security updates</span></span>

### <a name="access"></a><span data-ttu-id="fe245-285">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-285">Access</span></span>
- <span data-ttu-id="fe245-286">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-286">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-287">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-287">Excel</span></span>

- <div><span data-ttu-id="fe245-288"><span>PDF に印刷するときに [&quot;すべてのラベルを繰り返す&quot;] が適用されているかのように表示されていた問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-288"><span>We fixed an issue which made it appear as though &quot;repeat all labels&quot; was applied when printing to a PDF</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="fe245-289">Office スイート</span><span class="sxs-lookup"><span data-stu-id="fe245-289">Office Suite</span></span>

- <div><span data-ttu-id="fe245-290"><span>デスクトップからドキュメントを開けないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-290"><span>We fixed an issue which could have prevented users from opening a document from the desktop</span></span></span></div>

- <div><span data-ttu-id="fe245-291"><span>[&quot;別のインストールが進行中です&quot;] という誤ったエラー メッセージによりアップグレードに失敗することがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-291"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="fe245-292"><span>セキュリティ更新プログラムがインストールされるときに、エラー メッセージが表示されることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-292"><span>We fixed an issue where a user could see error messages when security updates are installed</span></span></span></div>

- <div><span data-ttu-id="fe245-293"><span>カーソルが消えることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-293"><span>We fixed an issue which could cause the cursor to disappear</span></span></span></div>

- <div><span data-ttu-id="fe245-294"><span>既定で [ホーム] タブではなく [描画] タブが設定されていることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-294"><span>We fixed an issue where a user could be defaulted to the draw tab instead of the home tab</span></span></span></div>

- <div><span data-ttu-id="fe245-295"><span>大きなツリー ビューがクラッシュすることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-295"><span>We fixed an issue where large tree views could result in a crash</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="fe245-296">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-296">Outlook</span></span>

- <div></div><span data-ttu-id="fe245-297"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">パスワード入力画面が繰り返し表示されることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-297"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can cause repeated password prompts</span></span></span>

- <div><span data-ttu-id="fe245-298"><span>メール アドレスが正しくクエリされないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-298"><span>We fixed an issue which could prevent an email address from being queried correctly</span></span></span></div>

- <div><span data-ttu-id="fe245-299"><span>以前のバージョンの Outlook で作成した予定表アイテムを開けないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-299"><span>We fixed an issue which could prevent users from opening calendar items created by legacy versions of Outlook</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="fe245-300">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-300">PowerPoint</span></span>

- <div><span data-ttu-id="fe245-301"><span>一部のアニメーションが開始されないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-301"><span>We fixed an issue which could prevent some animations from starting</span></span></span></div>

### <a name="project"></a><span data-ttu-id="fe245-302">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-302">Project</span></span>
- <span data-ttu-id="fe245-303">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-303">Various performance and stability fixes</span></span>

### <a name="word"></a><span data-ttu-id="fe245-304">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-304">Word</span></span>

- <div><span data-ttu-id="fe245-305"><span>コメントへの返信が順番に表示されないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-305"><span>We fixed an issue where replies to comments could appear out of order</span></span></span></div>

- <div><span data-ttu-id="fe245-306"><span>状況によって、コメントの代わりにヒントが表示されることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-306"><span>We fixed an issue where in some situations, hints would be displayed instead of comments</span></span></span></div>

- <div><span data-ttu-id="fe245-307"><span>新しいコメントを追加しようとしたときに [変更履歴] ウィンドウが表示されることがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-307"><span>We fixed an issue where the Revisions Pane could display when the user tried to add a new comment</span></span></span></div>

- <div><span data-ttu-id="fe245-308"><span>[元に戻す] ドロップダウン リストが表示されないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-308"><span>We fixed an issue which could prevent the undo dropdown list from appearing</span></span></span></div>

- <div><span data-ttu-id="fe245-309"><span>コメントを追加できないことがある問題を修正しました</span></span><span class="sxs-lookup"><span data-stu-id="fe245-309"><span>We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span></span></div>


## <a name="july-26-2019"></a><span data-ttu-id="fe245-310">2019 年 7 月 26 日</span><span class="sxs-lookup"><span data-stu-id="fe245-310">July 26, 2019</span></span>
<span data-ttu-id="fe245-311">バージョン 1908 (ビルド 11916.20000)</span><span class="sxs-lookup"><span data-stu-id="fe245-311">Version 1908 (build 11916.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="fe245-312">新機能:</span><span class="sxs-lookup"><span data-stu-id="fe245-312">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="fe245-313">Word、Excel、PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-313">Word, Excel, PowerPoint</span></span>

#### <a name="create-more-accessible-pdfs"></a><span data-ttu-id="fe245-314">よりアクセシビリティの高い PDF ファイルを作成する</span><span class="sxs-lookup"><span data-stu-id="fe245-314">Create more accessible PDFs</span></span>

<span data-ttu-id="fe245-315">PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="fe245-315">Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="fe245-316">主な修正:</span><span class="sxs-lookup"><span data-stu-id="fe245-316">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="fe245-317">すべて</span><span class="sxs-lookup"><span data-stu-id="fe245-317">All</span></span>

- <span data-ttu-id="fe245-318">Office の更新後に、Office のファイルの種類の関連付けとアイコンが破損する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-318">We fixed an issue where file type association and icons for Office could sometimes break after an Office Update</span></span>

### <a name="word"></a><span data-ttu-id="fe245-319">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-319">Word</span></span> 
- <span data-ttu-id="fe245-320">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-320">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-321">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-321">Excel</span></span>
- <span data-ttu-id="fe245-322">グラフを移動するとクラッシュする場合がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-322">We fixed an issue where moving a chart could sometimes result in a crash</span></span>
- <span data-ttu-id="fe245-323">グラフの種類を変更した後にグラフ オブジェクトからブック オブジェクトを取得するとエラーが発生することがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-323">We fixed an issue where to get Workbook object from Chart object after changing chart types could sometimes result in an error</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-324">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-324">PowerPoint</span></span>
- <span data-ttu-id="fe245-325">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-325">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-326">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-326">Outlook</span></span>
- <span data-ttu-id="fe245-327">シンプル リボンで、無効にしてあるコントロールが淡色表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-327">We fixed an issue where in simplified ribbon, a disabled control could sometimes not be greyed out in the ribbon</span></span>

### <a name="access"></a><span data-ttu-id="fe245-328">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-328">Access</span></span>
- <span data-ttu-id="fe245-329">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-329">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="fe245-330">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-330">Project</span></span>
- <span data-ttu-id="fe245-331">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-331">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-19-2019"></a><span data-ttu-id="fe245-332">2019 年 7 月 19 日</span><span class="sxs-lookup"><span data-stu-id="fe245-332">July 19, 2019</span></span>
<span data-ttu-id="fe245-333">バージョン 1908 (ビルド 11911.20000)</span><span class="sxs-lookup"><span data-stu-id="fe245-333">Version 1908 (build 11911.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="fe245-334">新機能:</span><span class="sxs-lookup"><span data-stu-id="fe245-334">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="fe245-335">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-335">Word</span></span>

#### <a name="learn-what-acronyms-mean-when-you-read-in-word-online"></a><span data-ttu-id="fe245-336">Word Online の文書で使われている略語の意味を確認する</span><span class="sxs-lookup"><span data-stu-id="fe245-336">Learn what Acronyms mean when you read in Word Online</span></span>

<span data-ttu-id="fe245-337">略語を見つけたら、組織内のデータを使用してそれを定義しようとします。</span><span class="sxs-lookup"><span data-stu-id="fe245-337">When you encounter an Acronym, we'll try to define it using data from within your organization.</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="fe245-338">主な修正:</span><span class="sxs-lookup"><span data-stu-id="fe245-338">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="fe245-339">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-339">Word</span></span> 
- <span data-ttu-id="fe245-340">BookMarkEnd タグが欠けているという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-340">We fixed an issue which BookMarkEnd tag was missing.</span></span>
- <span data-ttu-id="fe245-341">ユーザーが特殊文字を入力しているときに、フォントの選択が変更される場合があるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-341">We fixed an issue where the font selection could change while the user was typing special characters</span></span>
- <span data-ttu-id="fe245-342">新しいコメント カードに空白の返信が発生することがあるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-342">We fixed an issue which could sometimes cause blank replies to a new comment card</span></span>
- <span data-ttu-id="fe245-343">メールを共有すると、書式設定が失われる場合があるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-343">We fixed an issue which could cause formatting to be lost when sharing an email</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-344">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-344">Excel</span></span>
- <span data-ttu-id="fe245-345">範囲の広い配列がクラッシュすることがあるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-345">We fixed an issue where an array with a large range could sometimes cause a crash</span></span>
- <span data-ttu-id="fe245-346">フィルター処理された範囲からデータをコピーする場合のパフォーマンスを大幅に向上しました</span><span class="sxs-lookup"><span data-stu-id="fe245-346">We significantly improved the performance of copying data from filtered ranges</span></span>
- <span data-ttu-id="fe245-347">ファイル名に特殊文字が含まれていると、一部のファイルを開くことができないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-347">We fixed an issue which prevented some files from opening if the filenames contained special characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-348">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-348">PowerPoint</span></span>
- <span data-ttu-id="fe245-349">PowerPoint で新しく作成したセクションのセクション名が既定で選択されていないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-349">We fixed an issue where section name was not selected by default for newly created section in PowerPoint.</span></span>
- <span data-ttu-id="fe245-350">4:3 ディスプレイを使用すると、UI の使用が困難になることがあるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-350">We fixed an issue which could cause the UI to become difficult to use when using a 4:3 display</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-351">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-351">Outlook</span></span>
- <span data-ttu-id="fe245-352">利用可能な会議室がリストに表示されないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-352">We fixed an issue which could prevent available rooms from being listed</span></span>
- <span data-ttu-id="fe245-353">一部の POP3 ユーザーの HTML 形式を設定できないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-353">We fixed an issue which prevented HTML formatting for some POP3 users</span></span>

### <a name="access"></a><span data-ttu-id="fe245-354">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-354">Access</span></span>
- <span data-ttu-id="fe245-355">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-355">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="fe245-356">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-356">Project</span></span>
- <span data-ttu-id="fe245-357">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-357">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-12-2019"></a><span data-ttu-id="fe245-358">2019 年 7 月 12 日</span><span class="sxs-lookup"><span data-stu-id="fe245-358">July 12, 2019</span></span>
<span data-ttu-id="fe245-359">バージョン 1907 (ビルド 11901.20038)</span><span class="sxs-lookup"><span data-stu-id="fe245-359">Version 1907 (build 11901.20038)</span></span>

## <a name="whats-new"></a><span data-ttu-id="fe245-360">新機能:</span><span class="sxs-lookup"><span data-stu-id="fe245-360">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-361">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-361">PowerPoint</span></span>
 
#### <a name="use-ink-replay-in-your-presentations"></a><span data-ttu-id="fe245-362">プレゼンテーションでインクの再生を使用する</span><span class="sxs-lookup"><span data-stu-id="fe245-362">Use ink replay in your presentations</span></span>
 
<span data-ttu-id="fe245-363">PowerPoint でインクの再生アニメーションを適用して、プレゼンテーションの表現力とコミュニケーション力を高めます。</span><span class="sxs-lookup"><span data-stu-id="fe245-363">Apply a replay animation for ink in PowerPoint to express and communicate more in presentations.</span></span> 

## <a name="notable-fixes"></a><span data-ttu-id="fe245-364">主な修正:</span><span class="sxs-lookup"><span data-stu-id="fe245-364">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="fe245-365">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-365">Word</span></span> 
- <span data-ttu-id="fe245-366">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-366">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-367">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-367">Excel</span></span>
- <span data-ttu-id="fe245-368">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-368">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-369">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-369">PowerPoint</span></span>
- <span data-ttu-id="fe245-370">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-370">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-371">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-371">Outlook</span></span>
- <span data-ttu-id="fe245-372">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-372">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="fe245-373">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-373">Access</span></span>
- <span data-ttu-id="fe245-374">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-374">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="fe245-375">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-375">Project</span></span>
- <span data-ttu-id="fe245-376">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-376">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-5-2019"></a><span data-ttu-id="fe245-377">2019 年 7 月 5 日</span><span class="sxs-lookup"><span data-stu-id="fe245-377">July 5, 2019</span></span>
<span data-ttu-id="fe245-378">バージョン 1907 (ビルド 11901.20018)</span><span class="sxs-lookup"><span data-stu-id="fe245-378">Version 1907 (build 11901.20018)</span></span>

## <a name="whats-new"></a><span data-ttu-id="fe245-379">新機能:</span><span class="sxs-lookup"><span data-stu-id="fe245-379">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="fe245-380">Word、Excel、PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-380">Word, Excel, PowerPoint</span></span>

#### <a name="sketchy-shapes"></a><span data-ttu-id="fe245-381">Sketchy で描く!</span><span class="sxs-lookup"><span data-stu-id="fe245-381">Sketchy Shapes!</span></span>

<span data-ttu-id="fe245-382">プレゼンテーションを作成中ですか。</span><span class="sxs-lookup"><span data-stu-id="fe245-382">In the middle of drafting a presentation?</span></span> <span data-ttu-id="fe245-383">まだ作業中であることを示す Sketchy スタイルを適用します。</span><span class="sxs-lookup"><span data-stu-id="fe245-383">Apply the sketchy style to show that you're still working on it.</span></span> <span data-ttu-id="fe245-384">これを使用すると、自由形式や手描きの図形に変えることなく、オブジェクトに個人的なタッチを与えることができます。</span><span class="sxs-lookup"><span data-stu-id="fe245-384">It gives a personal touch to your objects without turning it into a free form, hand-drawn shapes.</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-385">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-385">Excel</span></span>

- <span data-ttu-id="fe245-386">**ファイル共有の高速化**: ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="fe245-386">**Faster file sharing**: Share your documents right from the recently used list without having to open the file.</span></span>
### <a name="powerpoint"></a><span data-ttu-id="fe245-387">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-387">PowerPoint</span></span>

- <span data-ttu-id="fe245-388">**アクセスを容易にするため、[印刷] メニューに [配布資料にスライド番号を印刷する] を移動しました:** 配布資料が指定されているときに、[印刷] > [印刷レイアウト] ドロップダウンの順にクリックすると見つかります。</span><span class="sxs-lookup"><span data-stu-id="fe245-388">**The setting to Print Slide Numbers in Handouts has been moved to the Print Menu for easier access:**  Find it in the Print > Print Layout dropdown when a Handout layout is selected.</span></span> <span data-ttu-id="fe245-389">これにより、プレゼンテーションごとに簡単に設定を切り替えることもできます。</span><span class="sxs-lookup"><span data-stu-id="fe245-389">This also allows the setting to be easily toggled per presentation.</span></span> [<span data-ttu-id="fe245-390">詳細情報</span><span class="sxs-lookup"><span data-stu-id="fe245-390">Learn more</span></span>](https://support.office.com/ja-JP/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="fe245-391">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="fe245-391">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="word"></a><span data-ttu-id="fe245-392">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-392">Word</span></span>

- <span data-ttu-id="fe245-393">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="fe245-393">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="fe245-394">主な修正:</span><span class="sxs-lookup"><span data-stu-id="fe245-394">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="fe245-395">すべて</span><span class="sxs-lookup"><span data-stu-id="fe245-395">All</span></span>
- <span data-ttu-id="fe245-396">リボンのキー ヒントのパフォーマンスが大幅に改善されました</span><span class="sxs-lookup"><span data-stu-id="fe245-396">We significantly improved the performance of Ribbon KeyTips</span></span>
- <span data-ttu-id="fe245-397">「今後のリリース予定を確認」ダイアログが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-397">We fixed an issue which prevented the "See what's coming soon" dialog from being displayed properly</span></span>
- <span data-ttu-id="fe245-398">共著ギャラリーのポップアップで写真の位置がずれてしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-398">We fixed an issue which could cause Photos to be misaligned in the Co-auth Gallery flyout</span></span>

### <a name="word"></a><span data-ttu-id="fe245-399">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-399">Word</span></span> 
- <span data-ttu-id="fe245-400">新しいコメントが追加されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-400">We fixed an issue which could sometimes prevent new comments from being added</span></span>
- <span data-ttu-id="fe245-401">表がクラッシュすることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-401">We fixed an issue where tables could sometimes cause a crash</span></span>
- <span data-ttu-id="fe245-402">無効なデータが差し込み印刷の最後に追加されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-402">We fixed an issue where invalid data could sometimes be added to the end of a mail merge</span></span>
- <span data-ttu-id="fe245-403">一部の LaTeX 数式が正しく表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-403">We fixed an issue which could cause some LaTeX equations to render incorrectly</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-404">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-404">Excel</span></span>
- <span data-ttu-id="fe245-405">グラフの種類を変更するとランタイム例外が発生することがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-405">We fixed an issue where changing chart types could sometimes result in a runtime exception</span></span>
- <span data-ttu-id="fe245-406">複数のウィンドウを開いたときに正しくないリボンが表示されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-406">We fixed an issue where the incorrect ribbon could be displayed when multiple windows were open</span></span>
- <span data-ttu-id="fe245-407">マクロがブックの 2 番目のインスタンスを開いたときにエラーが発生することがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-407">We fixed an issue which could cause an error when a macro opened a second instance of a workbook</span></span>
- <span data-ttu-id="fe245-408">ブックを開いたり作成したりするとき、またはブックを切り替えるときにクラッシュすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-408">We fixed an issue which could cause a crash when opening or creating a workbook, or switching between workbooks</span></span>
- <span data-ttu-id="fe245-409">ユーザーが Word で作成した PDF を Teams で開くことができない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-409">We fixed an issue preventing users from opening a PDF created from Word in Teams</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-410">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-410">PowerPoint</span></span>
- <span data-ttu-id="fe245-411">PDF にエクスポートすると、グラフの品質が低下する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-411">We fixed an issue which would degrade the quality of a chart when exported to a pdf</span></span>
- <span data-ttu-id="fe245-412">中心までの距離を示すヒントが表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-412">We fixed an issue which prevented a tooltip indicating the distance to center from displaying</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-413">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-413">Outlook</span></span>
- <span data-ttu-id="fe245-414">ディスクの領域不足エラーが表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-414">We fixed an issue which could sometimes prevent a Disk Full error to be displayed</span></span>
- <span data-ttu-id="fe245-415">会議出席依頼を更新する際に添付ファイルが複製されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-415">We fixed an issue which could cause attachments to become duplicated when updating a meeting request</span></span>

### <a name="access"></a><span data-ttu-id="fe245-416">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-416">Access</span></span>
- <span data-ttu-id="fe245-417">一部のクエリが大きい整数値を返さない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-417">We fixed an issue which prevented some queries from returning large integer values</span></span>
- <span data-ttu-id="fe245-418">SQL テキストボックスが編集できなくなることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-418">We fixed an issue which could make the sql textbox uneditable</span></span>
- <span data-ttu-id="fe245-419">一部の高 DPI ディスプレイでは、ヒントが見づらいことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-419">We fixed an issue where tooltips could be difficult to see on some High DPI displays</span></span>

### <a name="project"></a><span data-ttu-id="fe245-420">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-420">Project</span></span>
- <span data-ttu-id="fe245-421">新しいタスクでフラグの値が編集できなくなることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-421">We fixed an issue which could cause flag values to become uneditable in new tasks</span></span>
- <span data-ttu-id="fe245-422">ステータスの更新によって割り当てとタスクの実際の開始日が不適切に設定されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-422">We fixed an issue which could cause a status update to improperly set Actual Start Date on Assignments and Tasks</span></span>
- <span data-ttu-id="fe245-423">一部のリソースが間違って割り当て超過に表示されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-423">We fixed an issue which could cause some resources to incorreclty appear overallocated</span></span>
- <span data-ttu-id="fe245-424">ラグが追加され、小数点の記号がカンマで、サーバーに接続されていると TaskDependencies Add メソッドが失敗することがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-424">We fixed an issue where the TaskDependencies Add method could fail when Lag is added, the decimal separator is a comma, and when connected to a server</span></span>
- <span data-ttu-id="fe245-425">CSOM を使用してローカル ユーザー設定フィールドの参照テーブルの値を更新すると PCS がクラッシュすることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-425">We fixed an issue where updating local custom field lookup table values via CSOM could crash PCS</span></span>
- <span data-ttu-id="fe245-426">作業時間の合計値に小数点が含まれる場合に正しく表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-426">We fixed an issue where the total work values may appear incorrect if they contain a decimal</span></span>

</BR></BR>

## <a name="june-28-2019"></a><span data-ttu-id="fe245-427">2019 年 6 月 28 日</span><span class="sxs-lookup"><span data-stu-id="fe245-427">June 28, 2019</span></span>
<span data-ttu-id="fe245-428">バージョン 1907 (ビルド 11819.20002)</span><span class="sxs-lookup"><span data-stu-id="fe245-428">Version 1907 (build 11819.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="fe245-429">新機能:</span><span class="sxs-lookup"><span data-stu-id="fe245-429">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-430">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-430">Excel</span></span>

- <span data-ttu-id="fe245-431">**Power Query の機能強化を使用して素早くコーディングする:** オートコンプリートと構文の色分けを使用して、素早くコーディングを完了します。</span><span class="sxs-lookup"><span data-stu-id="fe245-431">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="fe245-432">関数、列、パラメーターも簡単に見つけることができます</span><span class="sxs-lookup"><span data-stu-id="fe245-432">Easily discover functions, columns, and parameters, too</span></span>

- <span data-ttu-id="fe245-433">**類似列のテーブルを結合する:** 取得と変換 (Power Query) では、テーブルを結合するために列を比較するときに、近似テキスト マッチング ロジック (あいまい一致とも呼ばれる) が使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="fe245-433">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span>

### <a name="word"></a><span data-ttu-id="fe245-434">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-434">Word</span></span>

- <span data-ttu-id="fe245-435">**共同編集の改善:** 共同編集時の信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-435">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>
 
### <a name="word-excel-powerpoint-and-visio"></a><span data-ttu-id="fe245-436">Word、Excel、PowerPoint、Visio</span><span class="sxs-lookup"><span data-stu-id="fe245-436">Word, Excel, PowerPoint, and Project.</span></span>

#### <a name="recommended-documents"></a><span data-ttu-id="fe245-437">推奨されるドキュメント</span><span class="sxs-lookup"><span data-stu-id="fe245-437">Recommended Documents</span></span>

<span data-ttu-id="fe245-438">推奨される関連アクティビティを含むドキュメントをご確認ください。</span><span class="sxs-lookup"><span data-stu-id="fe245-438">Find documents with relevant activity recommended to you.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="fe245-439">主な修正:</span><span class="sxs-lookup"><span data-stu-id="fe245-439">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="fe245-440">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-440">Word</span></span> 
- <span data-ttu-id="fe245-441">一部の .DOC を開くことができない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-441">We fixed an issue which could prevent some .DOC files from opening</span></span>
- <span data-ttu-id="fe245-442">コメントが正常に読み込まれない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-442">We fixed an issue which could have prevented comments from loading properly</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-443">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-443">Excel</span></span>
- <span data-ttu-id="fe245-444">Power Query のパフォーマンスが向上しました</span><span class="sxs-lookup"><span data-stu-id="fe245-444">We improved the performance of Power Queries</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-445">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-445">PowerPoint</span></span>
- <span data-ttu-id="fe245-446">画面のちらつきの原因となる、Surface デバイスでのペン使用に関連する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-446">We fixed an issue related to using a pen on a Surface device which could cause the screen to flicker</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-447">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-447">Outlook</span></span>
- <span data-ttu-id="fe245-448">会議に変換すると、予定の空き時間情報が変更される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-448">We fixed an issue which could change the free/busy status of an appointment when converted to a meeting</span></span>
- <span data-ttu-id="fe245-449">電子メールがアドホック テンプレートで保護されている場合に、不適切なテンプレートと説明が表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-449">We fixed an issue where the wrong template and description would be displayed when an e-mail was protected with an ad-hoc template</span></span>

### <a name="access"></a><span data-ttu-id="fe245-450">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-450">Access</span></span>
- <span data-ttu-id="fe245-451">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-451">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="fe245-452">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-452">Project</span></span>
- <span data-ttu-id="fe245-453">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-453">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-21-2019"></a><span data-ttu-id="fe245-454">2019 年 6 月 21 日</span><span class="sxs-lookup"><span data-stu-id="fe245-454">June 21, 2019</span></span>
<span data-ttu-id="fe245-455">バージョン 1907 (ビルド 11815.20002)</span><span class="sxs-lookup"><span data-stu-id="fe245-455">Version 1907 (build 11815.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="fe245-456">新機能:</span><span class="sxs-lookup"><span data-stu-id="fe245-456">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-457">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-457">Outlook</span></span>

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a><span data-ttu-id="fe245-458">Outlook デスクトップにおける黒のテーマでの濃色モード</span><span class="sxs-lookup"><span data-stu-id="fe245-458">Dark Mode for Black Theme in Outlook Desktop</span></span>

<span data-ttu-id="fe245-459">[濃色] モードで黒のテーマを使用しているユーザーには、電子メールを読むときに [閲覧] ウィンドウは暗く表示され、メールを作成するときも同様に表示されます。</span><span class="sxs-lookup"><span data-stu-id="fe245-459">With dark mode, users in black theme will now also see the reading pane with a dark background when reading emails, and the compose experience with a dark background when writing emails.</span></span> <span data-ttu-id="fe245-460">ユーザーが明るい背景でメッセージがどのように見えるかを確認する場合に備えて、[閲覧] ウィンドウとリボンに [太陽/月] トグルがあります。</span><span class="sxs-lookup"><span data-stu-id="fe245-460">There is a sun/moon toggle on the reading pane and in the ribbon in case users want to preview what the message looks like with a light background instead.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="fe245-461">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="fe245-461">Getting Started:</span></span>

1. <span data-ttu-id="fe245-462">[黒のテーマ] に切り替えると、既定では濃色モードになります。</span><span class="sxs-lookup"><span data-stu-id="fe245-462">Turn on black theme and dark mode will be on by default.</span></span>
2. <span data-ttu-id="fe245-463">(閲覧ウィンドウとリボンにある) [月/太陽] トグルを使用して、濃色モードでないユーザーにメッセージがどのように見えるかを表示します。</span><span class="sxs-lookup"><span data-stu-id="fe245-463">Use the moon/sun toggle (in the reading pane and in the ribbon) to preview what the message looks like for users not in dark mode</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="fe245-464">次の操作を試してみてください</span><span class="sxs-lookup"><span data-stu-id="fe245-464">Scenarios to Try:</span></span>

1. <span data-ttu-id="fe245-465">濃色モードでメールを読みます。</span><span class="sxs-lookup"><span data-stu-id="fe245-465">Read emails in dark mode.</span></span> <span data-ttu-id="fe245-466">何も見えない場合は、[閲覧] ウィンドウの [太陽] トグルを使用して、背景を明るくします。</span><span class="sxs-lookup"><span data-stu-id="fe245-466">If you are unable to read something, use the sun toggle in the Reading Pane to switch to a light background.</span></span> 
2. <span data-ttu-id="fe245-467">[濃色] モードでメールを作成します。</span><span class="sxs-lookup"><span data-stu-id="fe245-467">Compose emails in dark mode.</span></span> <span data-ttu-id="fe245-468">リボンの [太陽] トグルを使用して、メッセージが明るい背景でどのように見えるかを確認します。</span><span class="sxs-lookup"><span data-stu-id="fe245-468">Preview what your message will look like with a light background by using the sun toggle in the ribbon.</span></span> 

<span data-ttu-id="fe245-469">正常に表示されないメールが見つかった場合は、(添付ファイルとして) OutlookDarkModeFail@service.microsoft.com に送信してください</span><span class="sxs-lookup"><span data-stu-id="fe245-469">If you encounter any emails that don't render properly, please send them (as an attachment) to OutlookDarkModeFail@service.microsoft.com</span></span>

#### <a name="get-location-suggestions"></a><span data-ttu-id="fe245-470">場所の候補を取得する</span><span class="sxs-lookup"><span data-stu-id="fe245-470">Get location suggestions</span></span>

<span data-ttu-id="fe245-471">入力を開始すると、Outlook で一致する場所が検索されます。</span><span class="sxs-lookup"><span data-stu-id="fe245-471">Start typing and Outlook will look for matching locations.</span></span>

<span data-ttu-id="fe245-472">予定や会議を作成するときは、[場所] フィールドに適用されます。</span><span class="sxs-lookup"><span data-stu-id="fe245-472">This applies to the Location field when creating Appointments and Meetings.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="fe245-473">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="fe245-473">Getting Started:</span></span>

- <span data-ttu-id="fe245-474">Outlook で O365 または Outlook.com の予定表に予定や会議を作成します。</span><span class="sxs-lookup"><span data-stu-id="fe245-474">Create an Appointment or Meeting on an O365 or Outlook.com calendar in Outlook.</span></span> 
- <span data-ttu-id="fe245-475">[場所] フィールドをクリックして、入力を開始します...。</span><span class="sxs-lookup"><span data-stu-id="fe245-475">Click into the Location field and start typing…</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="fe245-476">次の操作を試してみてください</span><span class="sxs-lookup"><span data-stu-id="fe245-476">Scenarios to Try:</span></span>

<span data-ttu-id="fe245-477">会議に会議室を追加するときは、[会議室の検索] アドインやアドレス帳を使用するのではなく、[場所] フィールドをクリックします。</span><span class="sxs-lookup"><span data-stu-id="fe245-477">When adding a conference room to a meeting, click into Location field, rather than using Room Finder add-in or Address Book.</span></span>
<span data-ttu-id="fe245-478">レストラン、喫茶店、歯科医院といった公共の場所での予定がある場合は、新しいピッカーを使用して正確な位置を見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="fe245-478">For appointments at a physical place with a public location - like a restaurant, coffee shop, or even your dentist's office - try finding the exact location using the new picker.</span></span> <span data-ttu-id="fe245-479">こうすることで、外出するときに Outlook Mobile で通知を受け取ることができます。</span><span class="sxs-lookup"><span data-stu-id="fe245-479">This way, you'll be able to get notified on Outlook Mobile when it's time to leave.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="fe245-480">主な修正:</span><span class="sxs-lookup"><span data-stu-id="fe245-480">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="fe245-481">すべて</span><span class="sxs-lookup"><span data-stu-id="fe245-481">All</span></span>
- <span data-ttu-id="fe245-482">オフラインで [検索] ボックスが有効なままになる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-482">We fixed an issue which would keep the Search Box enabled while offline</span></span>

### <a name="word"></a><span data-ttu-id="fe245-483">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-483">Word</span></span> 
- <span data-ttu-id="fe245-484">キーボード フォーカスが表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-484">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>
- <span data-ttu-id="fe245-485">新しいドキュメントにテキストを貼り付けたときに、テキストが間違えて配置される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-485">We fixed an issue where text pasted into a new document could sometimes have the wrong text alignment</span></span>
- <span data-ttu-id="fe245-486">コンピューターを中断した後に、一部のユーザーが変更を保存できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-486">We fixed an issue which could prevent some users from saving changes after suspending their computer</span></span>
- <span data-ttu-id="fe245-487">特定の場合に、選択したページの代わりにドキュメント全体が印刷される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-487">We fixed an issue where in certain cases an entire document would be printed instead of the selected range</span></span>
- <span data-ttu-id="fe245-488">小さなディスプレイでコメントが読みにくくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-488">We fixed an issue which could make comments difficult to read on smaller displays</span></span>
- <span data-ttu-id="fe245-489">デバイスにキャプチャするときにクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-489">We fixed an issue which could cause a crash when capturing to a device</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-490">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-490">Excel</span></span>
- <span data-ttu-id="fe245-491">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-491">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-492">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-492">PowerPoint</span></span>
- <span data-ttu-id="fe245-493">キーボード フォーカスが表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-493">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-494">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-494">Outlook</span></span>
- <span data-ttu-id="fe245-495">有効ではないときにアドインが誤って有効になっていると表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-495">We fixed an issue which could incorrectly display an add-in as being enabled when it was not.</span></span>
- <span data-ttu-id="fe245-496">多数の保持ポリシーが表示されていない場合、ユーザーがすべての保持ポリシーを表示できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-496">We fixed an issue which would prevent a customer from viewing all retention policies if there were a large number of them</span></span>

### <a name="access"></a><span data-ttu-id="fe245-497">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-497">Access</span></span>
- <span data-ttu-id="fe245-498">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-498">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="fe245-499">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-499">Project</span></span>
- <span data-ttu-id="fe245-500">さまざまなパフォーマンスと安定性に関する修正</span><span class="sxs-lookup"><span data-stu-id="fe245-500">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-14-2019"></a><span data-ttu-id="fe245-501">2019 年 6 月 14 日</span><span class="sxs-lookup"><span data-stu-id="fe245-501">June 14, 2019</span></span>
<span data-ttu-id="fe245-502">バージョン 1907 (ビルド 11807.20000)</span><span class="sxs-lookup"><span data-stu-id="fe245-502">Version 1907 (build 11807.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="fe245-503">主な修正:</span><span class="sxs-lookup"><span data-stu-id="fe245-503">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="fe245-504">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-504">Word</span></span> 
- <span data-ttu-id="fe245-505">OneDrive に保存しているときにユーザーがサインインするのを妨げていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="fe245-505">We fixed an issue which could prevent a user from signing in when saving to OneDrive</span></span>
- <span data-ttu-id="fe245-506">アクセス制限モード中にユーザーによる SharePoint のプロパティの変更が妨げられていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="fe245-506">We fixed an issue where a user could be prevented from changing SharePoint properties while in restricted access mode</span></span>
- <span data-ttu-id="fe245-507">余白を調整しているときにヘッダーやフッターの内容が変更されてしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="fe245-507">We fixed an issue where header and footer content could change when adjusting margins</span></span>
- <span data-ttu-id="fe245-508">Web ビューに切り替えているときに書式設定が崩れてしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="fe245-508">We fixed an issue where formatting could break when switching to web view</span></span>
- <span data-ttu-id="fe245-509">SharePoint で開いたときにユーザーによるカスタム フィールドの使用を妨げていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="fe245-509">We fixed an issue which could prevent a user from using custom fields when opened from SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-510">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-510">Excel</span></span>
- <span data-ttu-id="fe245-511">フィルター処理された行を削除するときのパフォーマンスの問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="fe245-511">We fixed a performance issue when deleting rows of a filtered set</span></span>
- <span data-ttu-id="fe245-512">時々、保護ビューでマウスをちらつかせる原因になっていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="fe245-512">We fixed an issue which could sometimes cause the mouse to flicker in protected view</span></span>
- <span data-ttu-id="fe245-513">系列を削除しているときにクラッシュを引き起こしていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="fe245-513">We fixed an issue which could have caused a crash when deleting a series</span></span>
- <span data-ttu-id="fe245-514">利用できなかった場合に一部のユーザーがバージョン履歴を追加するオプションを使用していたところの問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="fe245-514">We fixed an issue where some users would have the option to add version history when that was not available</span></span>
- <span data-ttu-id="fe245-515">スプレッドシート比較ツールを使用しているときに例外を引き起こしていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="fe245-515">We fixed an issue which could have caused an exception when using the Spreadsheet Compare tool</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-516">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-516">PowerPoint</span></span>
- <span data-ttu-id="fe245-517">SharePoint へのリンクをクリックしたときにクラッシュを発生させていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="fe245-517">We fixed an issue where a crash could occur when clicking a link to SharePoint</span></span>
- <span data-ttu-id="fe245-518">ユーザーが Surface ペンを使用して入力しているのに、次のページに切り替わってしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="fe245-518">We fixed an issue which could switch the user to the next page while typing using a Surface Pen</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-519">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-519">Outlook</span></span>
- <span data-ttu-id="fe245-520">一部の宛先フィールドが通常より大きくなってしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="fe245-520">We fixed an issue where in some cases the To field was larger than normal</span></span>

### <a name="access"></a><span data-ttu-id="fe245-521">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-521">Access</span></span>
- <span data-ttu-id="fe245-522">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-522">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="fe245-523">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-523">Project</span></span>
- <span data-ttu-id="fe245-524">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-524">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-7-2019"></a><span data-ttu-id="fe245-525">2019 年 6 月 7 日</span><span class="sxs-lookup"><span data-stu-id="fe245-525">June 7, 2019</span></span>
<span data-ttu-id="fe245-526">バージョン 1907 (ビルド 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="fe245-526">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="fe245-527">主な修正:</span><span class="sxs-lookup"><span data-stu-id="fe245-527">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="fe245-528">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-528">Word</span></span> 
- <span data-ttu-id="fe245-529">オートコレクトが文の先頭文字を大文字にするように設定されていると Word がクラッシュする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-529">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="fe245-530">SharePoint でドキュメントを編集する際のパフォーマンスが向上しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-530">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="fe245-531">Adobe Illustrator で作成されたベクター ベースの画像が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-531">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-532">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-532">Excel</span></span>
- <span data-ttu-id="fe245-533">マクロを記録するときに、並べ替えフィールドが正しく設定されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-533">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="fe245-534">配列数式の計算中にハングまたはクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-534">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-535">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-535">PowerPoint</span></span>
- <span data-ttu-id="fe245-536">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-536">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-537">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-537">Outlook</span></span>
- <span data-ttu-id="fe245-538">インライン添付ファイルが誤って拡大縮小されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-538">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="fe245-539">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-539">Access</span></span>
- <span data-ttu-id="fe245-540">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-540">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="fe245-541">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-541">Project</span></span>
- <span data-ttu-id="fe245-542">固定期間のタイムシートが割り当て終了日を変更するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-542">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="fe245-543">以前のバージョンからプロジェクトを開くと、[完了率] の値が正しくない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-543">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="fe245-544">2019 年 5 月 31 日</span><span class="sxs-lookup"><span data-stu-id="fe245-544">May 31, 2019</span></span>
<span data-ttu-id="fe245-545">バージョン 1906 (ビルド 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="fe245-545">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="fe245-546">新機能:</span><span class="sxs-lookup"><span data-stu-id="fe245-546">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-547">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-547">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="fe245-548">サポートに問い合わせるためのダイアログがドッキング可能になり、右側に表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="fe245-548">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="fe245-549">サポートへの問い合わせに使用するダイアログが右側のウィンドウに表示され、最初からドッキングされたウィンドウとして表示されます。</span><span class="sxs-lookup"><span data-stu-id="fe245-549">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="fe245-550">メールでインクを使用する</span><span class="sxs-lookup"><span data-stu-id="fe245-550">Ink in Your Email!</span></span>

<span data-ttu-id="fe245-551">Outlook メールで画像を描画し、注釈を付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="fe245-551">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="fe245-552">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-552">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="fe245-553">ドキュメント リンクを Word で開く</span><span class="sxs-lookup"><span data-stu-id="fe245-553">Open document links in Word</span></span>

<span data-ttu-id="fe245-554">Office でドキュメント リンクをクリックしたときに既定で Word アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="fe245-554">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="fe245-555">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="fe245-555">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="fe245-556">詳しくは、以下を参照してください。https://support.office.com/ja-JP/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="fe245-556">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="fe245-557">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="fe245-557">Getting Started:</span></span>

<span data-ttu-id="fe245-558">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="fe245-558">Feature will default to off.</span></span> <span data-ttu-id="fe245-559">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="fe245-559">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="fe245-560">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="fe245-560">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="fe245-561">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="fe245-561">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="fe245-562">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="fe245-562">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="fe245-563">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="fe245-563">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="fe245-564">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="fe245-564">Scenarios to Try:</span></span>

<span data-ttu-id="fe245-565">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている Word ドキュメントへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="fe245-565">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="fe245-566">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="fe245-566">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-567">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-567">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="fe245-568">プレゼンテーションへのリンクを PowerPoint で開く</span><span class="sxs-lookup"><span data-stu-id="fe245-568">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="fe245-569">Office でプレゼンテーションへのリンクをクリックしたときに既定で PowerPoint アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="fe245-569">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="fe245-570">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="fe245-570">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="fe245-571">詳しくは、以下を参照してください。https://support.office.com/ja-JP/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="fe245-571">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="fe245-572">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="fe245-572">Getting Started:</span></span>

<span data-ttu-id="fe245-573">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="fe245-573">Feature will default to off.</span></span> <span data-ttu-id="fe245-574">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="fe245-574">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="fe245-575">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="fe245-575">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="fe245-576">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="fe245-576">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="fe245-577">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="fe245-577">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="fe245-578">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="fe245-578">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="fe245-579">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="fe245-579">Scenarios to Try:</span></span>

<span data-ttu-id="fe245-580">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている PowerPoint プレゼンテーションへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="fe245-580">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="fe245-581">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="fe245-581">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-582">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-582">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="fe245-583">ブックのリンクを Excel で開く</span><span class="sxs-lookup"><span data-stu-id="fe245-583">Open the workbook in Excel.</span></span>

<span data-ttu-id="fe245-584">Office でブックのリンクをクリックしたときに既定で Excel アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="fe245-584">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="fe245-585">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="fe245-585">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="fe245-586">詳細については、以下を参照してください。https://support.office.com/ja-JP/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="fe245-586">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="fe245-587">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="fe245-587">Getting Started:</span></span>

<span data-ttu-id="fe245-588">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="fe245-588">Feature will default to off.</span></span> <span data-ttu-id="fe245-589">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="fe245-589">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="fe245-590">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="fe245-590">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="fe245-591">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="fe245-591">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="fe245-592">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="fe245-592">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="fe245-593">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="fe245-593">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="fe245-594">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="fe245-594">Scenarios to Try:</span></span>

<span data-ttu-id="fe245-595">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている Excel ブックへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="fe245-595">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="fe245-596">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="fe245-596">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="fe245-597">主な修正:</span><span class="sxs-lookup"><span data-stu-id="fe245-597">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="fe245-598">すべて</span><span class="sxs-lookup"><span data-stu-id="fe245-598">All</span></span>
- <span data-ttu-id="fe245-599">自動保存が無効になっている場合でも、ファイルが自動保存されてしまう場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="fe245-599">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="fe245-600">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-600">Word</span></span> 
- <span data-ttu-id="fe245-601">一部のユーザーがファイルを SharePoint に保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-601">We fixed an issue which prevented some users from saving files to cloud locations</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-602">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-602">Excel</span></span>
- <span data-ttu-id="fe245-603">無効なフィルターに間違ったアイコンが表示される場合がある問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="fe245-603">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-604">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-604">PowerPoint</span></span>
- <span data-ttu-id="fe245-605">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-605">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-606">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-606">Outlook</span></span>
- <span data-ttu-id="fe245-607">グループ スケジュール ビューで一部のユーザーがオフラインとして間違って表示される問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="fe245-607">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="fe245-608">末尾にスペースが挿入されている URL が SafeLink で解析できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="fe245-608">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="fe245-609">業務時間外に部屋が利用可能と表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="fe245-609">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="fe245-610">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-610">Access</span></span>
- <span data-ttu-id="fe245-611">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-611">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="fe245-612">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-612">Project</span></span>
- <span data-ttu-id="fe245-613">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-613">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="fe245-614">2019 年 5 月 24 日</span><span class="sxs-lookup"><span data-stu-id="fe245-614">May 24, 2019</span></span>
<span data-ttu-id="fe245-615">バージョン 1906 (ビルド 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="fe245-615">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="fe245-616">新機能:</span><span class="sxs-lookup"><span data-stu-id="fe245-616">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="fe245-617">ユーザー エクスペリエンスの更新</span><span class="sxs-lookup"><span data-stu-id="fe245-617">User Experience Updates</span></span>

<span data-ttu-id="fe245-618">近日公開となっていた更新プログラムが公開されました。この更新には、シンプル リボンおよびフォルダー ウィンドウ、メッセージ一覧、閲覧ウィンドウの外観の更新が含まれます。</span><span class="sxs-lookup"><span data-stu-id="fe245-618">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="fe245-619">主な修正:</span><span class="sxs-lookup"><span data-stu-id="fe245-619">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="fe245-620">すべて</span><span class="sxs-lookup"><span data-stu-id="fe245-620">All</span></span>

- <span data-ttu-id="fe245-621">チャットウィンドウが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-621">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="fe245-622">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-622">Word</span></span> 
- <span data-ttu-id="fe245-623">Word で文法エラーのテキストが誤って強調表示されることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="fe245-623">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-624">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-624">Excel</span></span>
- <span data-ttu-id="fe245-625">誤ったアイコンがグラフ要素に使用されているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="fe245-625">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="fe245-626">同じブックが既に開いているときに、不正なブックが VBA スクリプトでアクティブになるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="fe245-626">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-627">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-627">PowerPoint</span></span>
- <span data-ttu-id="fe245-628">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-628">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-629">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-629">Outlook</span></span>
- <span data-ttu-id="fe245-630">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-630">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="fe245-631">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-631">Access</span></span>
- <span data-ttu-id="fe245-632">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-632">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="fe245-633">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-633">Project</span></span>
- <span data-ttu-id="fe245-634">タスクバーに切り替えた後、Project がクラッシュする可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="fe245-634">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="fe245-635">2019 年 5 月 17 日</span><span class="sxs-lookup"><span data-stu-id="fe245-635">May 17, 2019</span></span>
<span data-ttu-id="fe245-636">バージョン 1906 (ビルド 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="fe245-636">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="fe245-637">新機能:</span><span class="sxs-lookup"><span data-stu-id="fe245-637">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-638">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-638">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="fe245-639">ユーザー エクスペリエンスのアップデート</span><span class="sxs-lookup"><span data-stu-id="fe245-639">User Experience Updates</span></span>

<span data-ttu-id="fe245-640">近日公開となっていた更新プログラムが公開されました。この更新には、シンプル リボンおよびフォルダー ウィンドウ、メッセージ一覧、閲覧ウィンドウの外観の更新が含まれます。</span><span class="sxs-lookup"><span data-stu-id="fe245-640">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="fe245-641">利用するには:</span><span class="sxs-lookup"><span data-stu-id="fe245-641">Getting Started:</span></span>

<span data-ttu-id="fe245-642">これらの変更は、新しい既定の UI の一部になります。この新しい UI は、すべての運用環境ユーザー向けに [近日公開] スイッチで 12 月中旬以来提供されてきました。</span><span class="sxs-lookup"><span data-stu-id="fe245-642">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="fe245-643">カスタマイズ可能なシンプル リボン</span><span class="sxs-lookup"><span data-stu-id="fe245-643">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="fe245-644">従来のビューとシンプルなビューの切り替えやコマンドの固定または固定解除を簡単にできます。</span><span class="sxs-lookup"><span data-stu-id="fe245-644">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="fe245-645">利用するには:</span><span class="sxs-lookup"><span data-stu-id="fe245-645">Getting Started:</span></span>

<span data-ttu-id="fe245-646">シンプル リボンを使用するには、まず [近日公開] 機能をオンにし、リボンの山形マークをクリックして従来の複数行のリボンと新しい 1 行のシンプル リボンを切り替えます。</span><span class="sxs-lookup"><span data-stu-id="fe245-646">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="fe245-647">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="fe245-647">Scenarios to Try:</span></span>

<span data-ttu-id="fe245-648">従来のリボンからシンプル リボンに切り替える</span><span class="sxs-lookup"><span data-stu-id="fe245-648">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="fe245-649">お気に入りの操作を選択する</span><span class="sxs-lookup"><span data-stu-id="fe245-649">Pick your favorite action</span></span>

<span data-ttu-id="fe245-650">[フラグ] 機能や [削除] 機能はお使いになられていないかもしれません。</span><span class="sxs-lookup"><span data-stu-id="fe245-650">Don't use Flag and Delete?</span></span> <span data-ttu-id="fe245-651">アーカイブまたは既読に​​しますか?</span><span class="sxs-lookup"><span data-stu-id="fe245-651">How about Archive or Mark as Read?</span></span> <span data-ttu-id="fe245-652">クイック操作メニューをカスタマイズしてよく使うコマンドを追加できます。</span><span class="sxs-lookup"><span data-stu-id="fe245-652">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="fe245-653">利用するには:</span><span class="sxs-lookup"><span data-stu-id="fe245-653">Getting Started:</span></span>

<span data-ttu-id="fe245-654">希望のクイック操作を選ぶには、メッセージ一覧でメールを右クリックし、コンテキスト メニューを表示します。</span><span class="sxs-lookup"><span data-stu-id="fe245-654">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="fe245-655">次に、[クイック操作の設定] をクリックします。</span><span class="sxs-lookup"><span data-stu-id="fe245-655">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="fe245-656">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="fe245-656">Scenarios to Try:</span></span>

<span data-ttu-id="fe245-657">既定の設定を [フラグ] または [削除] から [アーカイブ]、[移動]、[既読にする]、または [なし] に変更すると、メッセージ一覧をすっきりした外観にできます。</span><span class="sxs-lookup"><span data-stu-id="fe245-657">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="fe245-658">レイアウトの間隔を</span><span class="sxs-lookup"><span data-stu-id="fe245-658">Relaxed or tighter layout?</span></span> <span data-ttu-id="fe245-659">自由に選べます</span><span class="sxs-lookup"><span data-stu-id="fe245-659">You choose</span></span>

<span data-ttu-id="fe245-660">[狭い間隔を使用] オプションを使用すると、アイテム間のスペースを広く取るか、間隔の狭いレイアウトでより多くのアイテムを表示するかを選べます。</span><span class="sxs-lookup"><span data-stu-id="fe245-660">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="fe245-661">利用するには:</span><span class="sxs-lookup"><span data-stu-id="fe245-661">Getting Started:</span></span>

<span data-ttu-id="fe245-662">従来のリボンの場合、[表示] タブの [メッセージ] グループで、[狭い間隔を使用] チェックボックスをオンにします。シンプル リボンの場合は、[現在のビュー] 設定で [狭い間隔を使用] を選択します。</span><span class="sxs-lookup"><span data-stu-id="fe245-662">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="fe245-663">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="fe245-663">Scenarios to Try:</span></span>

<span data-ttu-id="fe245-664">Outlook で、この設定をオフにした状態でメッセージをトリアージしたり作成したりしてみます。</span><span class="sxs-lookup"><span data-stu-id="fe245-664">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="fe245-665">この機能をオンにすると、1 ページに収まるメッセージの数が増え、新規作成フォームのコントロールの表示がすっきりとします。</span><span class="sxs-lookup"><span data-stu-id="fe245-665">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="fe245-666">Onedrive 同期クライアントを使用する際の MRU エントリの重複を除去する</span><span class="sxs-lookup"><span data-stu-id="fe245-666">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="fe245-667">クラウド添付ファイルを使用すると、MRU エントリの重複を除去できるため、Onedrive の統合を効率化できます。クラウド添付ファイルを使用すれば、同期されたデータでコピーの添付をする動作が早くなります。</span><span class="sxs-lookup"><span data-stu-id="fe245-667">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="fe245-668">利用するには:</span><span class="sxs-lookup"><span data-stu-id="fe245-668">Getting Started:</span></span>

<span data-ttu-id="fe245-669">OneDrive 同期クライアントを使用している場合は、添付ファイル MRU に重複ファイルが表示されなくなります。</span><span class="sxs-lookup"><span data-stu-id="fe245-669">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="fe245-670">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="fe245-670">Scenarios to Try:</span></span>

<span data-ttu-id="fe245-671">OneDrive 同期クライアントを有効にして、Outlook デスクトップで [ファイルの添付] メニューを使用する</span><span class="sxs-lookup"><span data-stu-id="fe245-671">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="fe245-672">フォルダーを多数含むメールボックスでの共有フォルダーの同期が改善されました</span><span class="sxs-lookup"><span data-stu-id="fe245-672">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="fe245-673">長い間、Outlook での共有メールボックスの同期は、最大で 500 フォルダーに制限されてきました。</span><span class="sxs-lookup"><span data-stu-id="fe245-673">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="fe245-674">この変更により Outlook の改善が行われ、同期をする際の 500 フォルダーの制限がなくなりました。</span><span class="sxs-lookup"><span data-stu-id="fe245-674">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="fe245-675">利用するには:</span><span class="sxs-lookup"><span data-stu-id="fe245-675">Getting Started:</span></span>

<span data-ttu-id="fe245-676">メールボックスにフォルダーを 1000 個作成し、誰か他のユーザーにそのメールボックスへのアクセスを許可し、このユーザーの Outlook プロファイルを作成します。同期が正常に動作することを確認します。</span><span class="sxs-lookup"><span data-stu-id="fe245-676">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="fe245-677">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-677">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="fe245-678">少しだけ消す</span><span class="sxs-lookup"><span data-stu-id="fe245-678">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="fe245-679">利用するには:</span><span class="sxs-lookup"><span data-stu-id="fe245-679">Getting Started:</span></span>

<span data-ttu-id="fe245-680">[描画] タブに移動します。 [消しゴム] ドロップダウンを選択します。</span><span class="sxs-lookup"><span data-stu-id="fe245-680">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="fe245-681">[消しゴム (小)] または [消しゴム (中)] を選びます。</span><span class="sxs-lookup"><span data-stu-id="fe245-681">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="fe245-682">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="fe245-682">Scenarios to Try:</span></span>

<span data-ttu-id="fe245-683">[描画] タブに移動します。ペンを選びます。</span><span class="sxs-lookup"><span data-stu-id="fe245-683">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="fe245-684">インク ストロークを描きます。</span><span class="sxs-lookup"><span data-stu-id="fe245-684">Draw an ink stroke.</span></span> <span data-ttu-id="fe245-685">[消しゴム] ドロップダウンを選択します。</span><span class="sxs-lookup"><span data-stu-id="fe245-685">Select the Eraser dropdown.</span></span> <span data-ttu-id="fe245-686">[消しゴム (小)] または [消しゴム (中)] を選びます。</span><span class="sxs-lookup"><span data-stu-id="fe245-686">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="fe245-687">インク ストロークを少しだけ消してみます。</span><span class="sxs-lookup"><span data-stu-id="fe245-687">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="fe245-688">主な修正:</span><span class="sxs-lookup"><span data-stu-id="fe245-688">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="fe245-689">すべて</span><span class="sxs-lookup"><span data-stu-id="fe245-689">All</span></span> 
- <span data-ttu-id="fe245-690">一部のユーザーが PDF として保存できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="fe245-690">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="fe245-691">32 ビット システムでの大容量ファイルの保存に影響する場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="fe245-691">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="fe245-692">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-692">Word</span></span> 
- <span data-ttu-id="fe245-693">音声入力機能の応答性が大幅に向上されました。</span><span class="sxs-lookup"><span data-stu-id="fe245-693">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-694">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-694">Excel</span></span>
- <span data-ttu-id="fe245-695">タッチ スクリーン デバイスでダブルクリック イベントが失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="fe245-695">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="fe245-696">一部のユーザーが VBA マクロを編集できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="fe245-696">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="fe245-697">スライサーを使用した際にパフォーマンスに影響する場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="fe245-697">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-698">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-698">PowerPoint</span></span>
- <span data-ttu-id="fe245-699">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-699">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-700">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-700">Outlook</span></span>
- <span data-ttu-id="fe245-701">選択したテンプレートとは異なるテンプレートが表示される場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="fe245-701">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="fe245-702">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-702">Access</span></span>
- <span data-ttu-id="fe245-703">長いリッチ テキストの表示に Zoom Builder を使うと、読みづらくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="fe245-703">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="fe245-704">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-704">Project</span></span>
- <span data-ttu-id="fe245-705">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-705">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="fe245-706">2019 年 5 月 10日</span><span class="sxs-lookup"><span data-stu-id="fe245-706">May 10, 2019</span></span>
<span data-ttu-id="fe245-707">バージョン 1906 (ビルド 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="fe245-707">Version 1906 (build 11702.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="fe245-708">新機能:</span><span class="sxs-lookup"><span data-stu-id="fe245-708">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-709">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-709">Outlook</span></span>

<span data-ttu-id="fe245-710">**より多くのメッセージを画面に収める:** [表示] > [より狭い文字間隔を使用] の順に選択し、メッセージの間隔を調整します。</span><span class="sxs-lookup"><span data-stu-id="fe245-710">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="fe245-711">主な修正:</span><span class="sxs-lookup"><span data-stu-id="fe245-711">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="fe245-712">すべて</span><span class="sxs-lookup"><span data-stu-id="fe245-712">All</span></span>
- <span data-ttu-id="fe245-713">[名前を付けて保存] ダイアログボックスに誤ったパスが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-713">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="fe245-714">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-714">Word</span></span> 
- <span data-ttu-id="fe245-715">操作アシストからの一部の選択が挿入されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-715">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-716">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-716">Excel</span></span>
- <span data-ttu-id="fe245-717">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-717">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-718">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-718">PowerPoint</span></span>
- <span data-ttu-id="fe245-719">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-719">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-720">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-720">Outlook</span></span>
- <span data-ttu-id="fe245-721">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-721">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="fe245-722">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-722">Access</span></span>
- <span data-ttu-id="fe245-723">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-723">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="fe245-724">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-724">Project</span></span>
- <span data-ttu-id="fe245-725">タスク ID の確認に強調表示が必要となる可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-725">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="fe245-726">2019 年 5 月 3日</span><span class="sxs-lookup"><span data-stu-id="fe245-726">May 3, 2019</span></span>
<span data-ttu-id="fe245-727">バージョン 1906 (ビルド 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="fe245-727">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="fe245-728">新機能:</span><span class="sxs-lookup"><span data-stu-id="fe245-728">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-729">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-729">Outlook</span></span>

<span data-ttu-id="fe245-730">**すべての暗号化オプションを1か所で:** [オプション] > [暗号化] の順に移動して、メール メッセージを保護する方法を選択します。</span><span class="sxs-lookup"><span data-stu-id="fe245-730">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. Learn more</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="fe245-731">主な修正:</span><span class="sxs-lookup"><span data-stu-id="fe245-731">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="fe245-732">すべて</span><span class="sxs-lookup"><span data-stu-id="fe245-732">All</span></span>
- <span data-ttu-id="fe245-733">一部のユーザーが OneDrive for Business との同期で問題が発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-733">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="fe245-734">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-734">Word</span></span> 
- <span data-ttu-id="fe245-735">Word の起動に時間がかかる場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-735">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-736">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-736">Excel</span></span>
- <span data-ttu-id="fe245-737">新しいバージョンの Excel にアップグレードした後、ブックから外部リンクが削除されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-737">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="fe245-738">一部のユーザーが新しいワークブックでセルを選択するのが困難な問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-738">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-739">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-739">PowerPoint</span></span>
- <span data-ttu-id="fe245-740">図面をテキストに変換するときにフォントサイズが一致しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-740">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-741">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-741">Outlook</span></span>
- <span data-ttu-id="fe245-742">a .VCF ファイルから連絡先を保存すると空のフィールドが発生する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-742">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="fe245-743">送信されていても、送信トレイ フォルダーにメッセージが残ってしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-743">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="fe245-744">DRM メッセージの表示中に Outlook がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-744">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="fe245-745">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-745">Access</span></span>
- <span data-ttu-id="fe245-746">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-746">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="fe245-747">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-747">Project</span></span>
- <span data-ttu-id="fe245-748">エディターが中国語から英語に切り替わる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-748">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="fe245-749">マスター プロジェクトの公開コピーに未公開タスクが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-749">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="fe245-750">2019 年 4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="fe245-750">April 26, 2019</span></span>
<span data-ttu-id="fe245-751">バージョン 1905 (ビルド 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="fe245-751">Version 1905 (build 11617.20002)</span></span>

## <a name="new-features"></a><span data-ttu-id="fe245-752">新機能</span><span class="sxs-lookup"><span data-stu-id="fe245-752">New Features</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-753">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-753">Outlook</span></span>

<span data-ttu-id="fe245-754">**共有カレンダーの更新がより速く**: Office 365 の共有カレンダーの場合、Outlook は REST API を使用してこれらのカレンダーを更新できます。</span><span class="sxs-lookup"><span data-stu-id="fe245-754">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="fe245-755">共有カレンダーのより高速で信頼性の高い更新を行うには、プレビューを有効にします。</span><span class="sxs-lookup"><span data-stu-id="fe245-755">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-756">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-756">Excel</span></span>

#### <a name="coauthoring-improvements"></a><span data-ttu-id="fe245-757">共同編集の改善</span><span class="sxs-lookup"><span data-stu-id="fe245-757">Coauthoring improvements</span></span>

<span data-ttu-id="fe245-758">他のユーザーがリアルタイムでコンテンツの変更を受け取れるようにすることで、共同編集のエクスペリエンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-758">Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

### <a name="visio"></a><span data-ttu-id="fe245-759">Visio</span><span class="sxs-lookup"><span data-stu-id="fe245-759">Visio</span></span>

- <span data-ttu-id="fe245-760">**Power BI から Visio ビジュアルをエクスポートする:** PDF、PowerPoint のファイルなどの Power BI レポートをエクスポートするときに、Power BI 用の Visio Visual が正しく表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="fe245-760">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="fe245-761">主な修正:</span><span class="sxs-lookup"><span data-stu-id="fe245-761">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="fe245-762">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-762">Word</span></span> 
- <span data-ttu-id="fe245-763">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-763">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-764">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-764">Excel</span></span>
- <span data-ttu-id="fe245-765">ソルバー マクロの実行が失敗するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="fe245-765">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="fe245-766">Excel ファイルを SharePoint にインポートできないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-766">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-767">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-767">PowerPoint</span></span>
- <span data-ttu-id="fe245-768">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-768">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-769">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-769">Outlook</span></span>
- <span data-ttu-id="fe245-770">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-770">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="fe245-771">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-771">Access</span></span>
- <span data-ttu-id="fe245-772">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-772">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="fe245-773">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-773">Project</span></span>
- <span data-ttu-id="fe245-774">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-774">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="fe245-775">2019 年 4 月 19 日</span><span class="sxs-lookup"><span data-stu-id="fe245-775">April 19, 2019</span></span>
<span data-ttu-id="fe245-776">バージョン 1905 (ビルド 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="fe245-776">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="fe245-777">新機能:</span><span class="sxs-lookup"><span data-stu-id="fe245-777">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-778">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-778">Outlook</span></span>

<span data-ttu-id="fe245-779">**人物を検索するときにメールの候補を取得する:** [検索] ボックスに人の名前を入力すると、最も関連性の高いメール メッセージが検索候補に含まれます。</span><span class="sxs-lookup"><span data-stu-id="fe245-779">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-780">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-780">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="fe245-781">データ型を使用した塗り分けマップのエクスペリエンス向上</span><span class="sxs-lookup"><span data-stu-id="fe245-781">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="fe245-782">この機能は、Excel の地理データ型を使用して、塗り分けされたマップ グラフにプロットするユーザーのための機能強化です。</span><span class="sxs-lookup"><span data-stu-id="fe245-782">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="fe245-783">エンドユーザーにとっては、機能とエンドユーザーがマップする領域の精度向上とがより高度に統合されたことが利点です。</span><span class="sxs-lookup"><span data-stu-id="fe245-783">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="fe245-784">さらに、ポリゴンで都市をマッピングする機能も含まれてます。</span><span class="sxs-lookup"><span data-stu-id="fe245-784">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="fe245-785">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="fe245-785">Getting Started:</span></span>

- <span data-ttu-id="fe245-786">この機能は、Excel 内の既存の機能を改善したものです。</span><span class="sxs-lookup"><span data-stu-id="fe245-786">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="fe245-787">この改善を使用するには、位置をリッチエンティティに変換し、塗り分けマップでプロットします。</span><span class="sxs-lookup"><span data-stu-id="fe245-787">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="fe245-788">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="fe245-788">Scenarios to Try:</span></span>

- <span data-ttu-id="fe245-789">ユーザーは、都市、州、都道府県、国、郵便番号のマッピングを試すことができます。</span><span class="sxs-lookup"><span data-stu-id="fe245-789">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="fe245-790">主な修正:</span><span class="sxs-lookup"><span data-stu-id="fe245-790">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="fe245-791">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="fe245-791">All Applications</span></span>
- <span data-ttu-id="fe245-792">アプリケーションが起動したときに最初の実行ダイアログが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-792">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="fe245-793">[名前を付けて保存] ダイアログボックス内の SharePoint リンクが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-793">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="fe245-794">ユーザーが [今すぐ修復] ダイアログを誤って表示する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-794">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="fe245-795">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-795">Word</span></span> 
- <span data-ttu-id="fe245-796">フォントの要求時に、一部のユーザーがメモリ不足またはディスク領域のエラーを受信する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-796">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="fe245-797">[コメント] ウィンドウから切り替えたときにウィンドウがフォーカスを失う可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-797">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-798">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-798">Excel</span></span>
- <span data-ttu-id="fe245-799">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-799">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-800">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-800">PowerPoint</span></span>
- <span data-ttu-id="fe245-801">ブランド化された図形のサイズ変更ができない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-801">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="fe245-802">保護ビューモードでファイルを開くときに PowerPoint がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-802">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-803">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-803">Outlook</span></span>
- <span data-ttu-id="fe245-804">一部のユーザーが中国語の単語を選択できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-804">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="fe245-805">有効期限が正しく計算されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-805">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="fe245-806">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-806">Access</span></span>
- <span data-ttu-id="fe245-807">一部のユーザーがマクロ ビルダーを使用できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-807">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="fe245-808">レポートを印刷すると最初のページしか印刷されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-808">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="fe245-809">ハイパーリンクの上にカーソルを置くとアプリケーションがクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-809">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="fe245-810">リレーションシップ ビューを使用すると、一部のアイテムが画面外に表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-810">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="fe245-811">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-811">Project</span></span>
- <span data-ttu-id="fe245-812">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-812">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="fe245-813">2019 年 4 月 12 日</span><span class="sxs-lookup"><span data-stu-id="fe245-813">April 12, 2019</span></span>
<span data-ttu-id="fe245-814">バージョン 1905 (ビルド 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="fe245-814">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="fe245-815">新機能:</span><span class="sxs-lookup"><span data-stu-id="fe245-815">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="fe245-816">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-816">Access</span></span>

#### <a name="get-smart-with-microsoft-graph"></a><span data-ttu-id="fe245-817">Microsoft Graph を使用してスマートに作業</span><span class="sxs-lookup"><span data-stu-id="fe245-817">Get started with Microsoft Graph</span></span>

<span data-ttu-id="fe245-818">インテリジェントなテクノロジを使用して、インテリジェントなデータをインポートしたり、またはデータにリンクしたりして、デスクトップ データベースを作り変えましょう。</span><span class="sxs-lookup"><span data-stu-id="fe245-818">Import or link to intelligent data and reinvent your desktop database with Intelligent Technology.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="fe245-819">主な修正:</span><span class="sxs-lookup"><span data-stu-id="fe245-819">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="fe245-820">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="fe245-820">All Applications</span></span>
 - <span data-ttu-id="fe245-821">一部のユーザーがクラウドの場所にファイルを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-821">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="fe245-822">リボンから間違ったウィンドウが開く問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-822">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="fe245-823">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-823">Word</span></span> 
- <span data-ttu-id="fe245-824">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-824">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-825">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-825">Excel</span></span>
- <span data-ttu-id="fe245-826">リンクされたデータ型を含まないブックであるにもかかわらず、リンクされたデータ型に対するエラーメッセージが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-826">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="fe245-827">Word 文書内のリンクの URL がオンラインとローカルで表示したときに変更される可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-827">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-828">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-828">PowerPoint</span></span>
- <span data-ttu-id="fe245-829">[アニメーション] タブで変更を元に戻すと、PowerPoint がクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-829">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-830">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-830">Outlook</span></span>
- <span data-ttu-id="fe245-831">一部のユーザーがパブリック フォルダー内の連絡先の [メモ] フィールドを変更できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-831">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="fe245-832">失効日と削除日の間に競合が発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-832">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="fe245-833">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-833">Access</span></span>
- <span data-ttu-id="fe245-834">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-834">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="fe245-835">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-835">Project</span></span>
- <span data-ttu-id="fe245-836">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-836">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="fe245-837">2019年4月5日</span><span class="sxs-lookup"><span data-stu-id="fe245-837">April 5, 2019</span></span>
<span data-ttu-id="fe245-838">バージョン 1904 (ビルド 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="fe245-838">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="fe245-839">新機能:</span><span class="sxs-lookup"><span data-stu-id="fe245-839">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-840">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-840">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="fe245-841">Windows 用の Outlook: 優先受信トレイの設定を設定して共有します。</span><span class="sxs-lookup"><span data-stu-id="fe245-841">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="fe245-842">優先受信トレイの設定はクラウドに保存されるため、どのコンピューターで Web 上の Outlook for Windows と Outlook を使用しても同じように一貫したエクスペリエンスを楽しめます。</span><span class="sxs-lookup"><span data-stu-id="fe245-842">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="fe245-843">利用するには:</span><span class="sxs-lookup"><span data-stu-id="fe245-843">Getting Started:</span></span>

<span data-ttu-id="fe245-844">[ファイル]、[オプション]、[全般] の順に移動すると、[Outlook の設定をクラウドに保存する] という新しい設定があります。</span><span class="sxs-lookup"><span data-stu-id="fe245-844">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="fe245-845">ユーザーは、自分の優先受信トレイの設定を他の Outlook Desktop インストールおよび OWA に移動できるようにするには、このチェック ボックスをオンにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="fe245-845">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="fe245-846">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="fe245-846">Scenarios to Try:</span></span>

<span data-ttu-id="fe245-847">クラウド設定の設定を有効にしているコンピューターで優先受信トレイを変更します。</span><span class="sxs-lookup"><span data-stu-id="fe245-847">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="fe245-848">OWA に移動して、そこに適用されている設定も確認してください。</span><span class="sxs-lookup"><span data-stu-id="fe245-848">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="fe245-849">OWA で優先受信トレイを変更し、デスクトップ Outlook を起動して反映された優先順位を表示します。</span><span class="sxs-lookup"><span data-stu-id="fe245-849">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="fe245-850">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-850">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="fe245-851">学習ツール モードでは、より多くのページの色が追加でサポートされます。</span><span class="sxs-lookup"><span data-stu-id="fe245-851">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="fe245-852">Word の学習ツールは、より多くのページ テーマ色を追加し、ページの背景色を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="fe245-852">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="fe245-853">多くのユーザーがすべて白、またはすべて黒の背景だと閲覧が難しいという課題があったため、PC と Mac の Word で色の選択肢を拡大しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-853">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="fe245-854">利用するには:</span><span class="sxs-lookup"><span data-stu-id="fe245-854">Getting Started:</span></span>

<span data-ttu-id="fe245-855">この操作を行うには、[表示] タブに移動し、[学習ツール]、[ページの色] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="fe245-855">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="fe245-856">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="fe245-856">Scenarios to Try:</span></span>

<span data-ttu-id="fe245-857">この操作を行うには、[表示] タブに移動し、[学習ツール]、[ページの色] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="fe245-857">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-858">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-858">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="fe245-859">3D アニメーション モデルで創造性を高める</span><span class="sxs-lookup"><span data-stu-id="fe245-859">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="fe245-860">Office では、アニメーションモデルをサポートするようになりました。エディターで再生するので、シートを活用することができます。</span><span class="sxs-lookup"><span data-stu-id="fe245-860">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="fe245-861">利用するには:</span><span class="sxs-lookup"><span data-stu-id="fe245-861">Getting Started:</span></span>

1. <span data-ttu-id="fe245-862">Excel を開く</span><span class="sxs-lookup"><span data-stu-id="fe245-862">Open Excel.</span></span>
2. <span data-ttu-id="fe245-863">3D アニメーション モデルを挿入します (まもなく Remix が公開されますが、今はここでアニメーション モデルにアクセスしてください: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="fe245-863">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="fe245-864">アニメーション モデルがエディターで再生されるようになります。</span><span class="sxs-lookup"><span data-stu-id="fe245-864">The animated model will play in the editor!</span></span> <span data-ttu-id="fe245-865">スライドショー モードも再生されるようになりますので、確認してください。</span><span class="sxs-lookup"><span data-stu-id="fe245-865">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="fe245-866">[3D 形式] リボンで、モデル内の他のアニメーション シーンを探索する</span><span class="sxs-lookup"><span data-stu-id="fe245-866">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="fe245-867">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="fe245-867">Scenarios to Try:</span></span>

1. <span data-ttu-id="fe245-868">アニメーション モデルを挿入し、エディターで再生します。</span><span class="sxs-lookup"><span data-stu-id="fe245-868">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="fe245-869">アニメーション化されたモデルで使用できるアニメーション シーンについては、シーン ギャラリー ([3D 書式] リボンから利用できます) を参照してください。</span><span class="sxs-lookup"><span data-stu-id="fe245-869">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="fe245-870">リボン、フローティング ツール バーまたはスペースバーを介してアニメーションを簡単に再生および一時停止することができます。</span><span class="sxs-lookup"><span data-stu-id="fe245-870">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="fe245-871">主な修正:</span><span class="sxs-lookup"><span data-stu-id="fe245-871">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="fe245-872">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="fe245-872">All Applications</span></span>
- <span data-ttu-id="fe245-873">Excel の間違ったアプリ アイコンがコンテキストメニューに表示されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-873">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="fe245-874">アップデートをインストールした後に [ファイル メニュー] ボタンが消えてしまうことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-874">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="fe245-875">ユーザー ライセンスに変更をおよぼす可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-875">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="fe245-876">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-876">Word</span></span> 
- <span data-ttu-id="fe245-877">特定のズーム レベルでテキストが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-877">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-878">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-878">Excel</span></span>
- <span data-ttu-id="fe245-879">編集後に、ブックを保存するかどうかを確認するメッセージが表示されない問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="fe245-879">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="fe245-880">ユーザーがブックを共有している場合に BeforeSave イベントが開始しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-880">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="fe245-881">列のサイズを 6 ピクセル未満に変更すると誤ったエラーメッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-881">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="fe245-882">Excel が Application.Visible フラグを無視する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-882">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="fe245-883">トレースの矢印がアクティブでない固定ウィンドウに残る問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-883">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="fe245-884">ブックを開くときに通貨の日付のセルの書式設定が変わることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-884">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="fe245-885">ツールヒントが突然移動する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-885">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="fe245-886">Power Query エディターのローカライズの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-886">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="fe245-887">ブックを添付ファイルとしてメールで送信するときにブックが削除される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-887">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-888">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-888">PowerPoint</span></span>
- <span data-ttu-id="fe245-889">図形のコピーに通常以上に時間がかかる問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="fe245-889">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-890">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-890">Outlook</span></span>
- <span data-ttu-id="fe245-891">描画ツールの使用中に Outlook がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-891">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="fe245-892">HTML メールを作成する際のローカライズの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-892">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="fe245-893">下側のウィンドウが選択しにくい問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-893">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="fe245-894">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-894">Access</span></span>
- <span data-ttu-id="fe245-895">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-895">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="fe245-896">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-896">Project</span></span>
- <span data-ttu-id="fe245-897">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-897">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="fe245-898">2019 年 3 月 22 日</span><span class="sxs-lookup"><span data-stu-id="fe245-898">March 22, 2019</span></span>
<span data-ttu-id="fe245-899">バージョン 1904 (ビルド 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="fe245-899">Version 1904 (build 11514.20004)</span></span>

## <a name="new-features"></a><span data-ttu-id="fe245-900">新機能</span><span class="sxs-lookup"><span data-stu-id="fe245-900">New Features</span></span>

- <span data-ttu-id="fe245-901">**プライバシー制御**: 診断データとコネクテッド エクスペリエンス用に新しく更新されて、改善された制御。</span><span class="sxs-lookup"><span data-stu-id="fe245-901">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> <span data-ttu-id="fe245-902">詳細 <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span><span class="sxs-lookup"><span data-stu-id="fe245-902"><https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span></span>

- <span data-ttu-id="fe245-903">**新しい外観を備えた Office のアイコン:** シンプルかつ高性能で、インテリジェントな Office のエクスペリエンスを反映するように、Office のアイコンがリニューアルされました。</span><span class="sxs-lookup"><span data-stu-id="fe245-903">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="fe245-904">主な修正:</span><span class="sxs-lookup"><span data-stu-id="fe245-904">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="fe245-905">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-905">Word</span></span> 
- <span data-ttu-id="fe245-906">UI に常に "変更を確認しています" と表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-906">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-907">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-907">Excel</span></span>
- <span data-ttu-id="fe245-908">ワークシートを移動した後にアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-908">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="fe245-909">PDF 形式で保存した後にアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-909">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="fe245-910">保存ダイアログで韓国語の文字を使用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-910">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-911">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-911">PowerPoint</span></span>
- <span data-ttu-id="fe245-912">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-912">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-913">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-913">Outlook</span></span>
- <span data-ttu-id="fe245-914">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-914">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="fe245-915">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-915">Access</span></span>
- <span data-ttu-id="fe245-916">Access で余計なショートカットが作成されるという問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="fe245-916">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="fe245-917">リンクされた SharePoint のデータが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-917">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="fe245-918">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-918">Project</span></span>
- <span data-ttu-id="fe245-919">言語設定が中国語から英語に変わる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-919">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="fe245-920">SharePoint に同期するとアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-920">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="fe245-921">2019 年 3 月 15 日</span><span class="sxs-lookup"><span data-stu-id="fe245-921">March 15, 2019</span></span>
<span data-ttu-id="fe245-922">バージョン 1904 (ビルド 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="fe245-922">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="fe245-923">新機能:</span><span class="sxs-lookup"><span data-stu-id="fe245-923">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="fe245-924">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-924">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="fe245-925">フォーカス モード</span><span class="sxs-lookup"><span data-stu-id="fe245-925">Focus mode</span></span>

<span data-ttu-id="fe245-926">気を散らさずに作業に集中するには、[表示]メニューの[フォーカス]に切り替えます。</span><span class="sxs-lookup"><span data-stu-id="fe245-926">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="fe245-927">Office 365 サブスクリプションが必要です。</span><span class="sxs-lookup"><span data-stu-id="fe245-927">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="fe245-928">利用するには:</span><span class="sxs-lookup"><span data-stu-id="fe245-928">Getting Started:</span></span>

<span data-ttu-id="fe245-929">リボンのステータス バー [フォーカス] ボタンの [フォーカス] ボタンをタブして表示</span><span class="sxs-lookup"><span data-stu-id="fe245-929">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="fe245-930">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="fe245-930">Scenarios to Try:</span></span>

<span data-ttu-id="fe245-931">フォーカス モードにしてフォーカス エクスペリエンスを経験する</span><span class="sxs-lookup"><span data-stu-id="fe245-931">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="fe245-932">主な修正:</span><span class="sxs-lookup"><span data-stu-id="fe245-932">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="fe245-933">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-933">Word</span></span> 
- <span data-ttu-id="fe245-934">PDF として保存した文書の画像に間違った DPI が設定される問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="fe245-934">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-935">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-935">Excel</span></span>
- <span data-ttu-id="fe245-936">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-936">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-937">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-937">PowerPoint</span></span>
- <span data-ttu-id="fe245-938">コメント ウィンドウが正しく開閉しない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="fe245-938">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="fe245-939">動画を削除するとアプリケーションがクラッシュする可能性がある問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="fe245-939">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="fe245-940">アプリケーションの一部のインスタンスを起動できない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="fe245-940">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-941">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-941">Outlook</span></span>
- <span data-ttu-id="fe245-942">日本語で表示するとき、開封確認が正しく表示されない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="fe245-942">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="fe245-943">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-943">Access</span></span>
- <span data-ttu-id="fe245-944">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-944">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="fe245-945">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-945">Project</span></span>
- <span data-ttu-id="fe245-946">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-946">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="fe245-947">2019 年 3 月 8 日</span><span class="sxs-lookup"><span data-stu-id="fe245-947">March 8, 2019</span></span> 
<span data-ttu-id="fe245-948">バージョン 1903 (ビルド 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="fe245-948">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="fe245-949">新機能:</span><span class="sxs-lookup"><span data-stu-id="fe245-949">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="fe245-950">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-950">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="fe245-951">探している情報を Microsoft Search で検索する</span><span class="sxs-lookup"><span data-stu-id="fe245-951">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="fe245-952">Microsoft Search を使用して、作業を完了するのに必要なすべてのファイル、操作、連絡先、ヘルプを検索することができます。</span><span class="sxs-lookup"><span data-stu-id="fe245-952">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="fe245-953">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="fe245-953">Getting Started:</span></span>

- <span data-ttu-id="fe245-954">この機能は、ヘッダーの UI の上部に目立つように表示されています。</span><span class="sxs-lookup"><span data-stu-id="fe245-954">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="fe245-955">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="fe245-955">Scenarios to Try:</span></span>

- <span data-ttu-id="fe245-956">大学、最近使用したドキュメント、最もよく使用するリボン コマンドなどを検索する</span><span class="sxs-lookup"><span data-stu-id="fe245-956">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="fe245-957">トピックや話題を検索して、その詳細情報を取得する</span><span class="sxs-lookup"><span data-stu-id="fe245-957">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="fe245-958">共同編集</span><span class="sxs-lookup"><span data-stu-id="fe245-958">Coauthoring</span></span>

<span data-ttu-id="fe245-959">マクロの文書を編集できない状況にうんざりしていませんか?</span><span class="sxs-lookup"><span data-stu-id="fe245-959">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="fe245-960">これで OneDrive for Business 上の docm ファイルで複数の作成者による同時編集が可能になります。</span><span class="sxs-lookup"><span data-stu-id="fe245-960">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="fe245-961">利用するには:</span><span class="sxs-lookup"><span data-stu-id="fe245-961">Getting Started:</span></span>

<span data-ttu-id="fe245-962">ユーザーは、この機能にアクセスするために UI のボタンを押す必要はありません。</span><span class="sxs-lookup"><span data-stu-id="fe245-962">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="fe245-963">OneDrive for Business の docm ファイルでは、既定で有効になっています。</span><span class="sxs-lookup"><span data-stu-id="fe245-963">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="fe245-964">したがって、試すには、ユーザーが docm ファイルを OneDrive for Business に保存しておく必要があります。</span><span class="sxs-lookup"><span data-stu-id="fe245-964">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="fe245-965">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="fe245-965">Scenarios to Try:</span></span>

<span data-ttu-id="fe245-966">OneDrive for Business で docm ファイルを作成し、同僚と共有して共同作業を行います。</span><span class="sxs-lookup"><span data-stu-id="fe245-966">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="fe245-967">主な修正:</span><span class="sxs-lookup"><span data-stu-id="fe245-967">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="fe245-968">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-968">Word</span></span> 
- <span data-ttu-id="fe245-969">オプションの表示中に ‘Esc’ キーを押すと発生するクラッシュの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-969">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="fe245-970">コメントに返信するときにクラッシュが発生するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-970">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="fe245-971">Word から PowerPoint Online へのコピーと貼り付けで発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-971">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-972">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-972">Excel</span></span>
- <span data-ttu-id="fe245-973">保護されたドキュメントや編集可能なドキュメントを開いているときに Excel でセルをコピーすると CPU 使用率が高くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-973">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-974">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-974">PowerPoint</span></span>
- <span data-ttu-id="fe245-975">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-975">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-976">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-976">Outlook</span></span>
- <span data-ttu-id="fe245-977">Outlook Search が選択した日付の並べ替えを使用しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-977">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="fe245-978">"このタスクを開く" ワークフロー リボンのボタンが特定のメールで応答しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-978">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="fe245-979">ユーザーが Outlook の会議室の検索で空いている会議室を選択した後、社内の会議室がクリアされなくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-979">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="fe245-980">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-980">Access</span></span>
- <span data-ttu-id="fe245-981">ダーク テーマで白い背景に白いテキストが表示されていた、保存済みのインポート/エクスポートのダイアログを修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-981">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="fe245-982">表のデザインのテキストボックスに [Yes/No] フィールドの DisplayControl プロパティを設定できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-982">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="fe245-983">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-983">Project</span></span>
- <span data-ttu-id="fe245-984">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-984">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="fe245-985">2019 年 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="fe245-985">March 1, 2019</span></span> 
<span data-ttu-id="fe245-986">バージョン 1903 (ビルド 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="fe245-986">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="fe245-987">新機能</span><span class="sxs-lookup"><span data-stu-id="fe245-987">What's New</span></span>

### <a name="word"></a><span data-ttu-id="fe245-988">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-988">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="fe245-989">色の変更履歴、コメントとリアルタイムの共同作業の同期</span><span class="sxs-lookup"><span data-stu-id="fe245-989">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="fe245-990">当社の製品での、コメント、変更履歴と共同作業者のカーソルが同じ色で表示されることについての修正箇所を確認しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-990">Colors for Track Changes, Comments and Real-Time Collaboration in Sync: Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="fe245-991">利用するには:</span><span class="sxs-lookup"><span data-stu-id="fe245-991">Getting Started:</span></span>

<span data-ttu-id="fe245-992">他のユーザーが開いている SharePoint または OneDrive のドキュメントを開きます。</span><span class="sxs-lookup"><span data-stu-id="fe245-992">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="fe245-993">ユーザーの変更履歴とコメントの色が、ユーザーのカーソルの色と一致することを確認します。</span><span class="sxs-lookup"><span data-stu-id="fe245-993">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="fe245-994">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="fe245-994">Scenarios to Try:</span></span>

<span data-ttu-id="fe245-995">他のユーザーが開いている SharePoint または OneDrive のドキュメントを開きます。</span><span class="sxs-lookup"><span data-stu-id="fe245-995">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="fe245-996">ユーザーの変更履歴とコメントの色が、ユーザーのカーソルの色と一致することを確認します。</span><span class="sxs-lookup"><span data-stu-id="fe245-996">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="fe245-997">主な修正:</span><span class="sxs-lookup"><span data-stu-id="fe245-997">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="fe245-998">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-998">Word</span></span> 
- <span data-ttu-id="fe245-999">オプションの表示中に ‘Esc’ キーを押すと発生するクラッシュの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-999">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="fe245-1000">Word から PowerPoint Online へのコピーと貼り付けで発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1000">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-1001">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-1001">Excel</span></span>
- <span data-ttu-id="fe245-1002">保護されたドキュメントや編集可能なドキュメントを開いているときに Excel でセルをコピーすると CPU 使用率が高くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1002">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-1003">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-1003">PowerPoint</span></span>
- <span data-ttu-id="fe245-1004">PowerPoint で @メンションを使用するときのスライド イメージのサイズに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1004">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-1005">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-1005">Outlook</span></span>
- <span data-ttu-id="fe245-1006">Outlook Search が選択した日付の並べ替えを使用しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1006">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="fe245-1007">"このタスクを開く" ワークフロー リボンのボタンが特定のメールで応答しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1007">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="fe245-1008">ユーザーが Outlook の会議室の検索で空いている会議室を選択した後、社内の会議室がクリアされなくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1008">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="fe245-1009">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-1009">Access</span></span>
- <span data-ttu-id="fe245-1010">テーブルとデータソースの再リンクを確認するときに表示されるメッセージを更新しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1010">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="fe245-1011">ダーク テーマで白い背景に白いテキストが表示されていた、保存済みのインポート/エクスポートのダイアログを修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1011">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="fe245-1012">表のデザインのテキストボックスに [Yes/No] フィールドの表示コントロール プロパティを設定できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1012">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="fe245-1013">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-1013">Project</span></span>
- <span data-ttu-id="fe245-1014">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-1014">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="fe245-1015">2019 年 2 月 15 日</span><span class="sxs-lookup"><span data-stu-id="fe245-1015">February 15, 2019</span></span> 
<span data-ttu-id="fe245-1016">バージョン 1903 (ビルド 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="fe245-1016">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="fe245-1017">新機能:</span><span class="sxs-lookup"><span data-stu-id="fe245-1017">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-1018">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-1018">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="fe245-1019">画面切り替え効果の機能強化 - 名前で変形</span><span class="sxs-lookup"><span data-stu-id="fe245-1019">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="fe245-1020">変形する図形を指定します</span><span class="sxs-lookup"><span data-stu-id="fe245-1020">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="fe245-1021">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="fe245-1021">Getting Started:</span></span>

- <span data-ttu-id="fe245-1022">[変形] で 2 つのオブジェクトを同じオブジェクトとして扱うために、[選択] ウィンドウを使って図形の名前を変更することができます。</span><span class="sxs-lookup"><span data-stu-id="fe245-1022">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="fe245-1023">[変形] で名前を使って既定のマッチング動作を上書きするには、</span><span class="sxs-lookup"><span data-stu-id="fe245-1023">The name must be prefaced with “!!”</span></span> <span data-ttu-id="fe245-1024">名前の前に "!!" (2 つの感嘆符) を付ける必要があります (例: "!!Name")。</span><span class="sxs-lookup"><span data-stu-id="fe245-1024">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="fe245-1025">名前の先頭に "!!" が付いていない図形の名前変更を続行できます。</span><span class="sxs-lookup"><span data-stu-id="fe245-1025">Users can continue to rename shapes with any name that doesn’t start with “!!”</span></span> <span data-ttu-id="fe245-1026">[変形] の動作が変更されることを気にする必要はありません</span><span class="sxs-lookup"><span data-stu-id="fe245-1026">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="fe245-1027">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="fe245-1027">Scenarios to Try:</span></span>

- <span data-ttu-id="fe245-1028">スライドに図形 (たとえば、四角形) を挿入します</span><span class="sxs-lookup"><span data-stu-id="fe245-1028">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="fe245-1029">新しいスライドを作成します</span><span class="sxs-lookup"><span data-stu-id="fe245-1029">Create a new slide</span></span>
- <span data-ttu-id="fe245-1030">2 枚目のスライドに別の図形 (たとえば、三角形) を挿入します</span><span class="sxs-lookup"><span data-stu-id="fe245-1030">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="fe245-1031">[オブジェクトの選択と表示] でスライド 1 の四角形の名前を "!!shape" に変更し、スライド 2 の三角形の名前を "!!shape" に変更します</span><span class="sxs-lookup"><span data-stu-id="fe245-1031">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="fe245-1032">2 枚目のスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="fe245-1032">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="fe245-1033">画面切り替え効果の機能強化 - SmartArt</span><span class="sxs-lookup"><span data-stu-id="fe245-1033">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="fe245-1034">SmartArt の変形をより滑らかに切り替え</span><span class="sxs-lookup"><span data-stu-id="fe245-1034">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="fe245-1035">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="fe245-1035">Getting Started:</span></span>

<span data-ttu-id="fe245-1036">SmartArt と同様の方法で変形を使用します</span><span class="sxs-lookup"><span data-stu-id="fe245-1036">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="fe245-1037">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="fe245-1037">Scenarios to Try:</span></span>

- <span data-ttu-id="fe245-1038">スライドに SmartArt を挿入します</span><span class="sxs-lookup"><span data-stu-id="fe245-1038">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="fe245-1039">スライドを複製します</span><span class="sxs-lookup"><span data-stu-id="fe245-1039">Duplicate the Slide</span></span>
- <span data-ttu-id="fe245-1040">複製されたスライド上で SmartArt のサイズ変更/変更/移動を行います</span><span class="sxs-lookup"><span data-stu-id="fe245-1040">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="fe245-1041">複製されたスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="fe245-1041">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="fe245-1042">画面切り替え効果の機能強化 - 表</span><span class="sxs-lookup"><span data-stu-id="fe245-1042">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="fe245-1043">表の変形をより滑らかに切り替え</span><span class="sxs-lookup"><span data-stu-id="fe245-1043">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="fe245-1044">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="fe245-1044">Getting Started:</span></span>
<span data-ttu-id="fe245-1045">表と同様の方法で変形を使用します</span><span class="sxs-lookup"><span data-stu-id="fe245-1045">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="fe245-1046">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="fe245-1046">Scenarios to Try:</span></span>

- <span data-ttu-id="fe245-1047">スライドに表を挿入します</span><span class="sxs-lookup"><span data-stu-id="fe245-1047">Insert a Table in a slide</span></span>
- <span data-ttu-id="fe245-1048">スライドを複製します</span><span class="sxs-lookup"><span data-stu-id="fe245-1048">Duplicate the slide</span></span>
- <span data-ttu-id="fe245-1049">複製されたスライド上で表のサイズ変更/変更/移動を行います</span><span class="sxs-lookup"><span data-stu-id="fe245-1049">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="fe245-1050">複製されたスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="fe245-1050">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="fe245-1051">Word、Excel、PowerPoint、OneNote、Access、Project、Publisher、Visio</span><span class="sxs-lookup"><span data-stu-id="fe245-1051">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="fe245-1052">アカウントをシームレスに切り替える</span><span class="sxs-lookup"><span data-stu-id="fe245-1052">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="fe245-1053">新しいアカウント マネージャーでは、仕事用アカウントと個人用アカウントのすべてが 1 か所に表示されます。また、アカウントを自由に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="fe245-1053">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="fe245-1054">この更新されたエクスペリエンスでは、ログイン方法がわかりやすくなりました。また、先にサインアウトしたり複雑なダイアログを操作したりする必要なく、仕事用アカウントと個人用アカウントを切り替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="fe245-1054">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="fe245-1056">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="fe245-1056">Scenarios to Try:</span></span>
- <span data-ttu-id="fe245-1057">アカウントを切り替えます</span><span class="sxs-lookup"><span data-stu-id="fe245-1057">Switch between accounts</span></span>
- <span data-ttu-id="fe245-1058">新しいアカウントを追加します [注: [ファイル]、[アカウント]、[接続済みサービス] の順に移動してから、仕事用アカウントに接続されている個人用サービス (またはその逆) を削除することができます]</span><span class="sxs-lookup"><span data-stu-id="fe245-1058">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="fe245-1059">アカウントからサインアウトします</span><span class="sxs-lookup"><span data-stu-id="fe245-1059">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="fe245-1060">主な修正:</span><span class="sxs-lookup"><span data-stu-id="fe245-1060">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="fe245-1061">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-1061">Word</span></span> 
- <span data-ttu-id="fe245-1062">表と画像のコンテキスト プレビューに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1062">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-1063">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-1063">Excel</span></span>
- <span data-ttu-id="fe245-1064">[黒] のテーマでオートフィルターの [検索] フィールドのテキストが白くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1064">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="fe245-1065">新しい Office アドインの同意の UI に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1065">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-1066">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-1066">PowerPoint</span></span>
- <span data-ttu-id="fe245-1067">ノート PC またはタブレットでスライドショーを表示すると、表示が自動的に拡大される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="fe245-1067">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-1068">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-1068">Outlook</span></span>
- <span data-ttu-id="fe245-1069">[OneNote に送る] ボタンの表示に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1069">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="fe245-1070">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-1070">Access</span></span>
- <span data-ttu-id="fe245-1071">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-1071">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="fe245-1072">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-1072">Project</span></span>
- <span data-ttu-id="fe245-1073">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-1073">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="fe245-1074">2019 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="fe245-1074">February 11, 2019</span></span>
<span data-ttu-id="fe245-1075">バージョン 1903 (ビルド 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="fe245-1075">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="fe245-1076">主な修正:</span><span class="sxs-lookup"><span data-stu-id="fe245-1076">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="fe245-1077">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-1077">Word</span></span> 
- <span data-ttu-id="fe245-1078">一部のカスタマイズされたスタイルを Word Online に適用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1078">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="fe245-1079">Word のリッチ オブジェクトでのコンテキスト プレビューに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1079">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="fe245-1080">リストを貼り付けると Word がクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1080">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-1081">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-1081">Excel</span></span>
- <span data-ttu-id="fe245-1082">通貨記号がない場合に、数値の書式の後ろに追加されるスペースが表示されない問題を修正しました特殊文字</span><span class="sxs-lookup"><span data-stu-id="fe245-1082">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="fe245-1083">株価の自動検出に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1083">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-1084">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-1084">PowerPoint</span></span>
- <span data-ttu-id="fe245-1085">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-1085">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-1086">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-1086">Outlook</span></span>
- <span data-ttu-id="fe245-1087">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-1087">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="fe245-1088">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-1088">Access</span></span>
- <span data-ttu-id="fe245-1089">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-1089">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="fe245-1090">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-1090">Project</span></span>
- <span data-ttu-id="fe245-1091">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-1091">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="fe245-1092">2019 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="fe245-1092">February 1, 2019</span></span> 
<span data-ttu-id="fe245-1093">バージョン 1902 (ビルド 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="fe245-1093">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="fe245-1094">主な修正</span><span class="sxs-lookup"><span data-stu-id="fe245-1094">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="fe245-1095">Word</span><span class="sxs-lookup"><span data-stu-id="fe245-1095">Word</span></span> 
- <span data-ttu-id="fe245-1096">埋め込まれた Excel の表のセルのサイズ変更に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1096">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="fe245-1097">描画キャンバス内の図形のコピー/貼り付けの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1097">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="fe245-1098">Excel</span><span class="sxs-lookup"><span data-stu-id="fe245-1098">Excel</span></span>
- <span data-ttu-id="fe245-1099">Excel Web App からファイルを開く際の問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1099">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="fe245-1100">CSV ファイルを .XLSX として保存する際にファイル名のサイズが原因で失敗する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1100">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="fe245-1101">コンテキスト メニューのオプションの表示に関してコンテキスト メニューを修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1101">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="fe245-1102">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="fe245-1102">PowerPoint</span></span>
- <span data-ttu-id="fe245-1103">角かっこを入力するためにユーザーがキーボード ショートカット Ctrl+Alt+7 および Ctrl+Alt+8 を使用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1103">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="fe245-1104">ローカル ビデオを PowerPoint に挿入すると C ドライブのディスク領域が減ってしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1104">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="fe245-1105">一部のユーザーに表示されていなかった [Microsoft Stream に公開する] ボタンを修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1105">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="fe245-1106">Outlook</span><span class="sxs-lookup"><span data-stu-id="fe245-1106">Outlook</span></span>
- <span data-ttu-id="fe245-1107">カレンダーのタスク ビューでタスクの件名が正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1107">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="fe245-1108">Access</span><span class="sxs-lookup"><span data-stu-id="fe245-1108">Access</span></span>
- <span data-ttu-id="fe245-1109">グラフのスケーリングの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="fe245-1109">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="fe245-1110">Project</span><span class="sxs-lookup"><span data-stu-id="fe245-1110">Project</span></span>
- <span data-ttu-id="fe245-1111">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="fe245-1111">Various performance and stability fixes</span></span>
