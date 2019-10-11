---
title: 2019 年の毎月のチャネル リリースのリリース ノート
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Office 365 ProPlus 用の 2019 年の毎月のチャネル リリースのリリース ノートを IT プロフェッショナルに提供します
ms.openlocfilehash: 5171b3c95e42d23c140fe8f662dae84c129b1b4f
ms.sourcegitcommit: b7303cf1e168500bcb2efe71dec23c9096715894
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/09/2019
ms.locfileid: "37427687"
---
# <a name="release-notes-for-monthly-channel-releases-in-2019"></a><span data-ttu-id="55209-103">2019 年の毎月のチャネル リリースのリリース ノート</span><span class="sxs-lookup"><span data-stu-id="55209-103">Release notes for Monthly Channel releases in 2019</span></span>

<span data-ttu-id="55209-104">これらのリリースノートには、2019 年の Office 365 ProPlus、Visio Pro for Office 365、Project Online デスクトップ クライアント、および Office 365 Business の毎月の更新プログラム チャンネルに含まれる新機能およびセキュリティ以外の更新に関する情報が記載されています。</span><span class="sxs-lookup"><span data-stu-id="55209-104">These release notes provide information about new features and non-security updates that are included in Monthly Channel updates to Office 365 ProPlus in 2019, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>
 
 > [!NOTE]
>- <span data-ttu-id="55209-105">Microsoft では多くの場合、一定期間にわたって毎月、機能 (および場合によっては修正プログラム) を展開します。</span><span class="sxs-lookup"><span data-stu-id="55209-105">We often roll out features (and sometimes even fixes) to Monthly over a period of time.</span></span>  <span data-ttu-id="55209-106">ここで説明した内容がすぐに表示されない場合は、間もなく利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="55209-106">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="55209-107">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-107">Learn more</span></span>](https://support.office.com/en-us/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
>- <span data-ttu-id="55209-108">Microsoft Teams の Office 365 ProPlus の既存のインストールについて: 7月の上旬から、Office 365 ProPlus (および Office 365 Business) の更新に Microsoft Teams が含まれます。</span><span class="sxs-lookup"><span data-stu-id="55209-108">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in early July, updates to Office 365 ProPlus (and Office 365 Business) will include Microsoft Teams.</span></span>  <span data-ttu-id="55209-109">Teams が追加される日付は、使用している更新プログラム チャネルによって異なります。</span><span class="sxs-lookup"><span data-stu-id="55209-109">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="55209-110">追加情報については、「[Office 365 ProPlus と同時に Microsoft Teams を展開する](https://docs.microsoft.com/ja-JP/deployoffice/teams-install)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="55209-110">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/ja-JP/deployoffice/teams-install) for additional information.</span></span>

## <a name="version-1909-october-08"></a><span data-ttu-id="55209-111">バージョン 1909: 10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="55209-111">Version 1909: October 08</span></span>
<span data-ttu-id="55209-112">*バージョン 1909 (ビルド 12026.20320)*</span><span class="sxs-lookup"><span data-stu-id="55209-112">*Version 1909 (Build 12026.20000)*</span></span>

<span data-ttu-id="55209-113">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/ja-JP/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="55209-113">Security updates listed [here](https://docs.microsoft.com/ja-JP/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="55209-115">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="55209-115">Non-security updates</span></span>

### <a name="outlook"></a><span data-ttu-id="55209-116">Outlook</span><span class="sxs-lookup"><span data-stu-id="55209-116">Outlook</span></span>

- <span data-ttu-id="55209-117">Outlook の添付ファイルのブロック ロジックが Python による添付ファイルもブロックする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="55209-117">Updated the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="55209-118">ユーザーが定期的な予定表の一部のインスタンスを開けない原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="55209-118">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="55209-119">ユーザーが Outlook プロセスでメモリ リークを観測する原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="55209-119">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="55209-120">ユーザーがプロフィールの作成中にクラッシュを発生させる原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="55209-120">Addressed an issue that caused users to experience a crash during profile creation.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1909-september-30"></a><span data-ttu-id="55209-122">バージョン 1909: 9 月 30 日</span><span class="sxs-lookup"><span data-stu-id="55209-122">Version 1909: September 30</span></span>
<span data-ttu-id="55209-123">*バージョン 1909 (ビルド 12026.20264)*</span><span class="sxs-lookup"><span data-stu-id="55209-123">*Version 1909 (Build 12026.20264)*</span></span>
* <span data-ttu-id="55209-124">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="55209-124">Various bugs and performance fixes.</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="55209-126">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="55209-126">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="55209-127">Access</span><span class="sxs-lookup"><span data-stu-id="55209-127">Access</span></span>

- <span data-ttu-id="55209-128">**リンク テーブルをすばやく見つける:** 新しい検索ボックスを使用すると、リンク テーブルを簡単に見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="55209-128">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="55209-129">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-129">Learn more</span></span>](https://support.office.com/ja-JP/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="55209-130">Excel</span><span class="sxs-lookup"><span data-stu-id="55209-130">Excel</span></span>

- <span data-ttu-id="55209-131">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="55209-131">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="outlook"></a><span data-ttu-id="55209-132">Outlook</span><span class="sxs-lookup"><span data-stu-id="55209-132">Outlook</span></span>

- <span data-ttu-id="55209-133">**テナント管理者によって定義されたアクセス許可を使用して、Outlook の [リンクの挿入] メニューでリンクを挿入する:** Outlook で最近使用されたリンクの挿入 (MRU) のリンクでは、既にそれに対するアクセス許可を持つユーザーのみに動作したリンクが挿入されます。</span><span class="sxs-lookup"><span data-stu-id="55209-133">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="55209-134">これは、ドキュメントへのアクセス権の付与を求めるユーザー間でのメールの行き来をしばしば引き起こします。</span><span class="sxs-lookup"><span data-stu-id="55209-134">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="55209-135">このエクスペリエンスが更新されましたので、テナント管理者によって設定される既定のアクセス許可を使用し、リンクを挿入できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="55209-135">We've updated this experience so now the link is inserted with the default permission set by the tenant admin.</span></span>

- <span data-ttu-id="55209-136">**Outlook の外観の更新:** これは、Outlook で核となるエクスペリエンスの外観の更新の一部であり、閲覧ウィンドウとインスペクターに含まれるメール メッセージのレイアウトを更新しています。</span><span class="sxs-lookup"><span data-stu-id="55209-136">**Outlook visual refresh:** This is part of the visual refresh of core experiences in Outlook, updating how mail messages layout in the reading pane and inspector.</span></span>

- <span data-ttu-id="55209-137">**より高速化した共有カレンダーの更新**: Office 365 の共有カレンダーの場合、Outlook では REST API を使用してこれらのカレンダーを更新します。</span><span class="sxs-lookup"><span data-stu-id="55209-137">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="55209-138">共有カレンダーのより高速で信頼性の高い更新を行うには、プレビューを有効にします。</span><span class="sxs-lookup"><span data-stu-id="55209-138">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="55209-139">**検索結果で関連メッセージを確認する:** Outlook では検索条件を分析し、最も関連性の高いメール メッセージを検索結果の上部に表示します。</span><span class="sxs-lookup"><span data-stu-id="55209-139">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="55209-140">また、[上位の結果] セクションには、すべての結果が日付順に表示されます。</span><span class="sxs-lookup"><span data-stu-id="55209-140">You'll also see all results sorted by date in the Top Results section.</span></span>

- <span data-ttu-id="55209-141">**適切なユーザーにメールを送信する:** [宛先] 行をクリックして、連絡先候補から選択するだけです。</span><span class="sxs-lookup"><span data-stu-id="55209-141">**Send the mail to the right person:** Just click the To: line and choose from suggested contacts.</span></span> <span data-ttu-id="55209-142">画像とプレゼンス インジケーターにより、適切なユーザーを選択することができます。</span><span class="sxs-lookup"><span data-stu-id="55209-142">A picture and presence indicator helps you choose the right person.</span></span>

- <span data-ttu-id="55209-143">**攻撃に対する高度な保護:** Office 365 Advanced Threat Protection を用いると、メールの件名、添付メッセージ、署名されたメッセージ、ネットワーク パスなどの範囲内のハイパーリンクを利用した攻撃から保護されます。</span><span class="sxs-lookup"><span data-stu-id="55209-143">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="55209-144">**異なる明るさでメッセージを表示する:** [太陽] または [月] のボタンを使用して、閲覧ウィンドウの明るい背景と暗い背景を切り替えます。</span><span class="sxs-lookup"><span data-stu-id="55209-144">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="55209-145">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-145">Learn more</span></span>](https://support.office.com/ja-JP/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

### <a name="powerpoint"></a><span data-ttu-id="55209-146">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="55209-146">PowerPoint</span></span>

- <span data-ttu-id="55209-147">**図を SVG として保存する:** グラフ、図形、その他の図を、サイズ変更しても画質が低下しないスケーラブル ベクター グラフィックとして保存できます。</span><span class="sxs-lookup"><span data-stu-id="55209-147">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="55209-148">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-148">Learn more</span></span>](https://support.office.com/ja-JP/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="55209-149">**インクを瞬時に再生:** インク描画にアニメーション効果を適用して、スライド ショーの間中、それが進んだり戻ったりして再生されるようにします。</span><span class="sxs-lookup"><span data-stu-id="55209-149">**Ink-stant replay:** Animate an ink drawing so that it replays forward or backward during your slide show.</span></span> [<span data-ttu-id="55209-150">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-150">Learn more</span></span>](https://support.office.com/ja-JP/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="55209-151">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="55209-151">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="visio"></a><span data-ttu-id="55209-152">Visio</span><span class="sxs-lookup"><span data-stu-id="55209-152">Visio</span></span>

- <span data-ttu-id="55209-153">**Microsoft Flow と Visio を使用したビジネス ワークフローの設計と自動化:** Visio を使用してワークフロー図を設計し、Microsoft Flow にエクスポートして自動化します。</span><span class="sxs-lookup"><span data-stu-id="55209-153">**Design and automate business workflows using Microsoft Flow and Visio:** Use Visio to design workflow diagram and export it to Microsoft Flow to automate.</span></span>

### <a name="word"></a><span data-ttu-id="55209-154">Word</span><span class="sxs-lookup"><span data-stu-id="55209-154">Word</span></span>

- <span data-ttu-id="55209-155">**別の言葉で伝える:** 別の言葉で伝えたいときに、[書き換え] でお助けします。</span><span class="sxs-lookup"><span data-stu-id="55209-155">**Say it another way:** When you want to say it differently, Rewrite is there to help.</span></span> <span data-ttu-id="55209-156">[書き換え] では、フレーズを洗練させるための別の言葉遣いを提供します。</span><span class="sxs-lookup"><span data-stu-id="55209-156">Rewrite offers alternatives for finessing your phrases.</span></span>

- <span data-ttu-id="55209-157">**共同編集の改善:** 共同編集時の信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="55209-157">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="55209-158">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="55209-158">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="55209-159">**他のユーザーがすばやく変更を確認:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="55209-159">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="55209-162">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="55209-162">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="55209-163">Excel</span><span class="sxs-lookup"><span data-stu-id="55209-163">Excel</span></span>

- <div><span data-ttu-id="55209-164"><span style="background-color:rgb(255, 255, 255);display:inline !important;">一部の保護されたシートにハイパーリンクが貼り付けられない問題が解決されました。</span></span><span class="sxs-lookup"><span data-stu-id="55209-164"><span style="background-color:rgb(255, 255, 255);display:inline !important;">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span></span><br></div>


- <div><span data-ttu-id="55209-165">&nbsp;<span style="font-size:13.3333px;background-color:rgb(255, 255, 255);display:inline !important;">アドイン マネジャーで参照するときに</span>、16 個以上のアドインを表示できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="55209-165">Enabled more than 16 add-ins to show&nbsp;<span style="font-size:13.3333px;background-color:rgb(255, 255, 255);display:inline !important;">when browsing in the add-in manager.</span></span></span></div>
- <div><span data-ttu-id="55209-166">Win32 クライアントの [アイデア] ボタンをクリックしてアドインを読み込むときにエラーが発生するという Excel のアイデア機能の問題を修正します。&nbsp;</span><span class="sxs-lookup"><span data-stu-id="55209-166">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.&nbsp;</span></span></div>

### <a name="outlook"></a><span data-ttu-id="55209-167">Outlook</span><span class="sxs-lookup"><span data-stu-id="55209-167">Outlook</span></span>

- <div><span data-ttu-id="55209-168">一部の safelinks に対して簡易的なホバーの URL が正しく表示されなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="55209-168">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span></div>


- <span data-ttu-id="55209-169"><span style="background-color:rgb(255, 255, 255);display:inline !important;">Python による添付ファイルもブロックされるよう、Outlook の添付ファイルのブロック ロジックが更新されました。</span></span><span class="sxs-lookup"><span data-stu-id="55209-169"><span style="background-color:rgb(255, 255, 255);display:inline !important;">Updated the attachment blocking logic in Outlook to also block python attachments.</span></span></span>


- <span data-ttu-id="55209-170"><span style="background-color:rgb(255, 255, 255);display:inline !important;">ユーザーによって確認される Outlook のプロセスのメモリ リークを引き起こす問題が修正されました。</span></span><span class="sxs-lookup"><span data-stu-id="55209-170"><span style="background-color:rgb(255, 255, 255);display:inline !important;">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span></span>

- <span data-ttu-id="55209-171">WebDAV の場所にファイルを保存できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="55209-171">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>


### <a name="office-suite"></a><span data-ttu-id="55209-172">Office スイート</span><span class="sxs-lookup"><span data-stu-id="55209-172">Office Suite</span></span>

- <div><p style="margin:0in 0in 0.0001pt;font-size:11pt;font-family:Calibri, sans-serif;"><span data-ttu-id="55209-173">ファイルを開くときにユーザーが直面していた問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="55209-173">We fixed an issue users were hitting when opening a file.</span></span></p></div>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-september-10"></a><span data-ttu-id="55209-175">バージョン 1908: 9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="55209-175">Version 1908: September 10</span></span>
<span data-ttu-id="55209-176">*バージョン 1908 (ビルド 11929.20300)*</span><span class="sxs-lookup"><span data-stu-id="55209-176">*Version 1908 (Build 11929.20300)*</span></span>

<span data-ttu-id="55209-177">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/ja-JP/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="55209-177">Security updates listed [here](https://docs.microsoft.com/ja-JP/officeupdates/office365-proplus-security-updates)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="55209-179">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="55209-179">Non-security updates</span></span>
### <a name="outlook"></a><span data-ttu-id="55209-180">Outlook</span><span class="sxs-lookup"><span data-stu-id="55209-180">Outlook</span></span>

- <span data-ttu-id="55209-181">スクリーン リーダーからユーザーが場所の候補にアクセスできない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="55209-181">Fixed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="55209-182">一部のユーザーが Outlook のクラウド設定を取得しようとすると、認証エラーが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="55209-182">Fixed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="55209-183">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="55209-183">PowerPoint</span></span>

- <span data-ttu-id="55209-184">PowerPoint ビデオ コントロールのアクセス可能な名前を復元する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="55209-184">Fixed an issue to restore the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="55209-185">一部のアニメーションが開始できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="55209-185">Fixed an issue which could prevent some animations from starting.</span></span>

### <a name="word"></a><span data-ttu-id="55209-186">Word</span><span class="sxs-lookup"><span data-stu-id="55209-186">Word</span></span>

- <span data-ttu-id="55209-187">SharePoint 2016 に保存されているファイルを共有しようとすると、"申し訳ございません。何かがこのファイルの共有を妨げています。" というメッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="55209-187">Fixed an issue which caused users to get the message "Sorry, something is preventing us from sharing this"  when trying to share files stored on SharePoint 2016.</span></span>

### <a name="office-suite"></a><span data-ttu-id="55209-188">Office スイート</span><span class="sxs-lookup"><span data-stu-id="55209-188">Office Suite</span></span>

- <span data-ttu-id="55209-189">大きなツリー ビューの表示に失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="55209-189">Fixed an issue where large tree views were failing.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-august-26"></a><span data-ttu-id="55209-191">バージョン 1908: 8 月 26 日</span><span class="sxs-lookup"><span data-stu-id="55209-191">Version 1908: August 26</span></span>
<span data-ttu-id="55209-192">*バージョン 1908 (ビルド 11929.20254)*</span><span class="sxs-lookup"><span data-stu-id="55209-192">*Version 1908 (Build 11929.20254)*</span></span>
* <span data-ttu-id="55209-193">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="55209-193">Various bugs and performance fixes.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="55209-194">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-194">Excel: Feature updates</span></span>

- <span data-ttu-id="55209-195">**あらましを描く:** ブック内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="55209-195">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="55209-196">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-196">Learn more</span></span>](https://support.office.com/ja-JP/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="55209-197">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="55209-197">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="55209-198">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="55209-198">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="55209-199">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-199">Learn more</span></span>](https://support.office.com/ja-JP/article/e2459f17-3996-4795-996e-b9a13486fa79)

- <span data-ttu-id="55209-200">**残っている作業に集中する:** [解決] を選択して、コメントを折りたたみ、開いているアイテムを目立たせます。</span><span class="sxs-lookup"><span data-stu-id="55209-200">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

### <a name="office-suite-feature-updates"></a><span data-ttu-id="55209-201">Office スイート: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-201">Office Suite: Feature updates</span></span>

- <span data-ttu-id="55209-202">**新しい外観を備えた Office のアイコン:** シンプルかつ高性能で、インテリジェントな Office のエクスペリエンスを反映するように、Office のアイコンがリニューアルされました。</span><span class="sxs-lookup"><span data-stu-id="55209-202">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="55209-203">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-203">Outlook: Feature updates</span></span>

- <span data-ttu-id="55209-204">**場所の候補を取得する:** 予定や会議をスケジュールするときに、[場所] に入力すると、会議室、住所、およびその他の最新の場所が提示されます。</span><span class="sxs-lookup"><span data-stu-id="55209-204">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="55209-205">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-205">Learn more</span></span>](https://support.office.com/ja-JP/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="55209-206">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="55209-206">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="55209-207">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="55209-207">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="55209-208">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-208">Learn more</span></span>](https://support.office.com/ja-JP/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="55209-209">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-209">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="55209-210">**あらましを描く:** プレゼンテーション内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="55209-210">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="55209-211">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-211">Learn more</span></span>](https://support.office.com/ja-JP/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="55209-212">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="55209-212">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="55209-213">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="55209-213">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="55209-214">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-214">Learn more</span></span>](https://support.office.com/ja-JP/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="word-feature-updates"></a><span data-ttu-id="55209-215">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-215">Word: Feature updates</span></span>

- <span data-ttu-id="55209-216">**あらましを描く:** ドキュメント内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="55209-216">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="55209-217">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-217">Learn more</span></span>](https://support.office.com/ja-JP/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="55209-218">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="55209-218">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="55209-219">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="55209-219">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="55209-220">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-220">Learn more</span></span>](https://support.office.com/ja-JP/article/e2459f17-3996-4795-996e-b9a13486fa79)

## <a name="version-1907-august-13"></a><span data-ttu-id="55209-221">バージョン 1907: 8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="55209-221">Version 1907: August 13</span></span>
<span data-ttu-id="55209-222">*バージョン 1907 (ビルド 11901.20218)*</span><span class="sxs-lookup"><span data-stu-id="55209-222">*Version 1907 (Build 11901.20218)*</span></span>

<span data-ttu-id="55209-223">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/ja-JP/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="55209-223">Security updates listed [here](https://docs.microsoft.com/ja-JP/officeupdates/office365-proplus-security-updates)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="55209-224">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="55209-224">Excel: Non-security updates</span></span>

 - <span data-ttu-id="55209-225">ピボットテーブルの並べ替え方法を変更し、他のユーザーとの共同編集セッション中にそれを更新する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="55209-225">Fixed an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="55209-226">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="55209-226">Outlook: Non-security updates</span></span>
  - <span data-ttu-id="55209-227">メールボックスを基本認証から最新認証にアップグレードしたユーザーが、Outlook プロファイルに関連付けられた正しくないアカウントで終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="55209-227">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

## <a name="version-1907-july-29"></a><span data-ttu-id="55209-228">バージョン 1907: (7 月 29 日)</span><span class="sxs-lookup"><span data-stu-id="55209-228">Version 1907: July 29</span></span>
<span data-ttu-id="55209-229">*バージョン 1907 (ビルド 11901.20176)*</span><span class="sxs-lookup"><span data-stu-id="55209-229">*Version 1907 (Build 11901.20176)*</span></span>
* <span data-ttu-id="55209-230">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="55209-230">Various bugs and performance fixes.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="55209-231">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-231">Excel: Feature updates</span></span>

- <span data-ttu-id="55209-232">**ブラウザーへのバウンスは不要:** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定することができます。</span><span class="sxs-lookup"><span data-stu-id="55209-232">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="55209-233">**Power Query の機能強化を使用して素早くコーディングする:** オートコンプリートおよび構文の色分けによって素早くコーディングを完了できます。</span><span class="sxs-lookup"><span data-stu-id="55209-233">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="55209-234">関数、列、パラメーターも簡単に見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="55209-234">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="55209-235">**マップ グラフを作成する:** この機能は、Excel の地理データ型を使用して、塗り分けされたマップ グラフにプロットするユーザーのための機能強化です。</span><span class="sxs-lookup"><span data-stu-id="55209-235">**Create a Map chart:** This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="55209-236">エンドユーザーにとっては、機能とエンドユーザーがマップする領域の精度向上とがより高度に統合されたことが利点です。</span><span class="sxs-lookup"><span data-stu-id="55209-236">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="55209-237">さらに、ポリゴンで都市をマッピングする機能も含まれてます。</span><span class="sxs-lookup"><span data-stu-id="55209-237">Additional benefits include - ability to map city polygons.</span></span> [<span data-ttu-id="55209-238">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-238">Learn more</span></span>](https://support.office.com/ja-JP/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="55209-239">**類似列のテーブルを結合する:** 取得と変換 (Power Query) では、テーブルを統合するために列を比較するときに、近似文字列マッチング ロジック (あいまい一致とも呼ばれる) が使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="55209-239">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="55209-240">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-240">Learn more</span></span>](https://support.office.com/ja-JP/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

### <a name="outlook-feature-updates"></a><span data-ttu-id="55209-241">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-241">Outlook: Feature updates</span></span>

- <span data-ttu-id="55209-242">**あなたが人を検索するときに電子メールの提案を得ます:** [検索]ボックスにその人の名前を入力すると、最も関連性の高い電子メールメッセージが検索結果に含まれます。</span><span class="sxs-lookup"><span data-stu-id="55209-242">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="55209-243">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-243">Learn more</span></span>](https://support.office.com/ja-JP/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="55209-244">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-244">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="55209-245">**ブラウザーへのバウンスは不要:** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定することができます。</span><span class="sxs-lookup"><span data-stu-id="55209-245">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="55209-246">**オンライン ビデオの新しい保存場所:** Microsoft Stream にビデオを保存すれば、組織内のすべてのユーザーが視聴できます。</span><span class="sxs-lookup"><span data-stu-id="55209-246">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="55209-247">ビデオのリンクを挿入すれば、小さなファイル サイズでマルチメディア プレゼンテーションをご利用いただけます。</span><span class="sxs-lookup"><span data-stu-id="55209-247">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="55209-248">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-248">Learn more</span></span>](https://support.office.com/ja-JP/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="55209-249">**マップ グラフを作成する:** この機能は、Excel の地理データ型を使用して、塗り分けされたマップ グラフにプロットするユーザーのための機能強化です。</span><span class="sxs-lookup"><span data-stu-id="55209-249">**Create a Map chart:** This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="55209-250">エンドユーザーにとっては、機能とエンドユーザーがマップする領域の精度向上とがより高度に統合されたことが利点です。</span><span class="sxs-lookup"><span data-stu-id="55209-250">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="55209-251">さらに、ポリゴンで都市をマッピングする機能も含まれてます。</span><span class="sxs-lookup"><span data-stu-id="55209-251">Additional benefits include - ability to map city polygons.</span></span> [<span data-ttu-id="55209-252">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-252">Learn more</span></span>](https://support.office.com/ja-JP/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="55209-253">**スライドのタイトルを追加してプレゼンテーションをアクセス可能にする:** アクセシビリティ チェックは、不足しているスライドのタイトルを見つけて修正するのに役立ちます。</span><span class="sxs-lookup"><span data-stu-id="55209-253">**Add Slide Titles to make your presentations accessible:** Accessibility Checker helps you find and fix missing slide titles.</span></span> [<span data-ttu-id="55209-254">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-254">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="55209-255">**アクセスを容易にするため、[印刷] メニューに [配布資料にスライド番号を印刷する] を移動しました:** 配布資料を指定したら、[印刷]、[印刷レイアウト] ドロップダウンの順にクリックすれば見つかります。</span><span class="sxs-lookup"><span data-stu-id="55209-255">**The setting to Print Slide Numbers in Handouts has been moved to the Print Menu for easier access:**  Find it in the Print > Print Layout dropdown when a Handout layout is selected.</span></span> <span data-ttu-id="55209-256">これにより、プレゼンテーションごとに簡単に設定を切り替えることもできます。</span><span class="sxs-lookup"><span data-stu-id="55209-256">This also allows the setting to be easily toggled per presentation.</span></span> [<span data-ttu-id="55209-257">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-257">Learn more</span></span>](https://support.office.com/ja-JP/article/194d4320-aa03-478b-9300-df25f0d15dc4)

### <a name="word-feature-updates"></a><span data-ttu-id="55209-258">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-258">Word: Feature updates</span></span>

- <span data-ttu-id="55209-259">**作業の邪魔をするものにさよならしましょう:** Mac のお気に入りの機能が Windows にも登場します。</span><span class="sxs-lookup"><span data-stu-id="55209-259">**Say goodbye to distractions:** A favorite Mac feature comes to Windows.</span></span> <span data-ttu-id="55209-260">気を散らさずに作業に集中するには、[表示]メニューの[フォーカス]に切り替えます。</span><span class="sxs-lookup"><span data-stu-id="55209-260">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> [<span data-ttu-id="55209-261">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-261">Learn more</span></span>](https://support.office.com/ja-JP/article/51af2fb2-194f-424b-ab7e-b65de9ec9292)

- <span data-ttu-id="55209-262">**ブラウザーへのバウンスは不要:** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定することができます。</span><span class="sxs-lookup"><span data-stu-id="55209-262">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="55209-263">**マップ グラフを作成する:** この機能は、Excel の地理データ型を使用して、塗り分けされたマップ グラフにプロットするユーザーのための機能強化です。</span><span class="sxs-lookup"><span data-stu-id="55209-263">**Create a Map chart:** This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="55209-264">エンドユーザーにとっては、機能とエンドユーザーがマップする領域の精度向上とがより高度に統合されたことが利点です。</span><span class="sxs-lookup"><span data-stu-id="55209-264">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="55209-265">さらに、ポリゴンで都市をマッピングする機能も含まれてます。</span><span class="sxs-lookup"><span data-stu-id="55209-265">Additional benefits include - ability to map city polygons.</span></span> [<span data-ttu-id="55209-266">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-266">Learn more</span></span>](https://support.office.com/ja-JP/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="55209-267">**精度による消去:** 手描き入力の小さな不備を修正するのに、2 つのサイズの消しゴムから選択できます。</span><span class="sxs-lookup"><span data-stu-id="55209-267">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="55209-268">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-268">Learn more</span></span>](https://support.office.com/ja-JP/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

## <a name="version-1906-july-09"></a><span data-ttu-id="55209-269">バージョン 1906: 7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="55209-269">Version 1906: July 09</span></span>
<span data-ttu-id="55209-270">*バージョン 1906 (ビルド 11727.20244)*</span><span class="sxs-lookup"><span data-stu-id="55209-270">*Version 1906 (Build 11727.20244)*</span></span>

<span data-ttu-id="55209-271">セキュリティ更新プログラムの一覧は「[こちら](https://docs.microsoft.com/ja-JP/officeupdates/office365-proplus-security-updates)」</span><span class="sxs-lookup"><span data-stu-id="55209-271">Security updates listed [here](https://docs.microsoft.com/ja-JP/officeupdates/office365-proplus-security-updates)</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="55209-272">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="55209-272">Outlook: Non-security updates</span></span>

- <span data-ttu-id="55209-273">現在のフォルダー検索で断続的な失敗を引き起こす問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="55209-273">Addresses an issue that caused current folder search to intermittently fail.</span></span>

## <a name="version-1906-june-27"></a><span data-ttu-id="55209-274">バージョン 1906: 6 月 27 日</span><span class="sxs-lookup"><span data-stu-id="55209-274">Version 1906: June 27</span></span>
<span data-ttu-id="55209-275">*バージョン 1906 (ビルド 11727.20230)*</span><span class="sxs-lookup"><span data-stu-id="55209-275">*Version 1906 (Build 11727.20230)*</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="55209-276">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="55209-276">Outlook: Non-security updates</span></span>

- <span data-ttu-id="55209-277">設定に関係なく、POP3 ユーザーの一部がプレーンテキストで書式設定されたすべてのメールを表示する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="55209-277">Addresses an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span>  <span data-ttu-id="55209-278">この修正プログラムでは、HTML 形式のメッセージの表示が復元されます。</span><span class="sxs-lookup"><span data-stu-id="55209-278">This fix will restore the view of the HTML formatted messages.</span></span>

## <a name="version-1906-june-26"></a><span data-ttu-id="55209-279">バージョン 1906: 6 月 26 日</span><span class="sxs-lookup"><span data-stu-id="55209-279">Version 1906: June 26</span></span>
<span data-ttu-id="55209-280">*バージョン 1906 (ビルド 11727.20224)*</span><span class="sxs-lookup"><span data-stu-id="55209-280">*Version 1906 (Build 11727.20224)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="55209-281">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="55209-281">Excel: Non-security updates</span></span>

- <span data-ttu-id="55209-282">図形やフォームコントロールに割り当てられているマクロが間違ったエラーメッセージとして表示される、または間違った対象範囲で動作する問題が Excel で修正されました。</span><span class="sxs-lookup"><span data-stu-id="55209-282">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>
- <span data-ttu-id="55209-283">テーブルの横にある切り取りと貼り付けの操作を、他のユーザーと共同編集しているときに失敗する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="55209-283">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="55209-284">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="55209-284">Outlook: Non-security updates</span></span>

- <span data-ttu-id="55209-285">代理人が特定の会議出席依頼に既に返信したかどうかに関係なく、管理者が不明瞭になる問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="55209-285">Addresses an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

## <a name="version-1906-june-24"></a><span data-ttu-id="55209-286">バージョン 1906: 6 月24 日</span><span class="sxs-lookup"><span data-stu-id="55209-286">Version 1906: June 24</span></span>
<span data-ttu-id="55209-287">*バージョン 1906 (ビルド 11727.20210)*</span><span class="sxs-lookup"><span data-stu-id="55209-287">*Version 1906 (Build 11727.20210)*</span></span>
* <span data-ttu-id="55209-288">さまざまなバグとパフォーマンスの修正。</span><span class="sxs-lookup"><span data-stu-id="55209-288">Various bugs and performance fixes.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="55209-289">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-289">Excel: Feature updates</span></span>

- <span data-ttu-id="55209-290">**ワークシートが生まれ変わりました：** ワークブックを使ってアニメーション 3D グラフィックスを挿入し、心臓の鼓動、惑星軌道、そして T-Rex の大暴れを見ることができます。</span><span class="sxs-lookup"><span data-stu-id="55209-290">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="55209-291">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-291">Learn more</span></span>](https://support.office.com/ja-JP/article/6f08009a-3da5-400d-a706-8e23f304cd72)

### <a name="outlook-feature-updates"></a><span data-ttu-id="55209-292">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-292">Outlook: Feature updates</span></span>

- <span data-ttu-id="55209-293">**カスタマイズも可能、シンプルになったリボン：** 最もよく使うボタンが単一行にまとめられ、使いやすくなりました。</span><span class="sxs-lookup"><span data-stu-id="55209-293">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="55209-294">簡単に従来のビューとシンプルなビューを切り替えたり、コマンドを固定または固定解除できます。</span><span class="sxs-lookup"><span data-stu-id="55209-294">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="55209-295">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-295">Learn more</span></span>](https://support.office.com/ja-JP/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="55209-296">**お気に入りのアクションを選びましょう：** フラグや、削除機能を使いますか？</span><span class="sxs-lookup"><span data-stu-id="55209-296">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="55209-297">アーカイブまたは既読に​​しますか?</span><span class="sxs-lookup"><span data-stu-id="55209-297">How about Archive or Mark as Read?</span></span> <span data-ttu-id="55209-298">クイック操作メニューをカスタマイズしてよく使うコマンドを追加できます。</span><span class="sxs-lookup"><span data-stu-id="55209-298">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="55209-299">**多数のフォルダを持つメールボックスの共有フォルダ同期の向上：** 共有メールボックスを同期するとき、Outlook は長年にわたって最大 500 個のフォルダに制限されていました。</span><span class="sxs-lookup"><span data-stu-id="55209-299">**Improved shared folder synchronization for mailboxes with many folders:** For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="55209-300">この変更により Outlook の改善が行われ、同期をする際の 500 フォルダーの制限がなくなりました。</span><span class="sxs-lookup"><span data-stu-id="55209-300">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

- <span data-ttu-id="55209-301">**集中受信トレイの設定がデバイス間で変わらなくなります：** 集中受信トレイの設定はクラウドに保存されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="55209-301">**Focused Inbox settings remain the same across devices:** Your Focused Inbox preferences are now stored in the cloud.</span></span> <span data-ttu-id="55209-302">どのコンピューターの Windows 版 Outlook や Outlook on the web でも、同じ機能をご利用いただけます。</span><span class="sxs-lookup"><span data-stu-id="55209-302">Enjoy the same experience when you use Outlook for Windows on any computer and Outlook on the web.</span></span> [<span data-ttu-id="55209-303">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-303">Learn more</span></span>](https://support.office.com/ja-JP/article/d77a442e-a86c-4bf8-b3dd-5571ae556986)

- <span data-ttu-id="55209-304">**ゆったりとしたレイアウト、まとめたレイアウト？自由に決めましょう：** 狭い間隔で、アイテム間の間隔をより広くしたり、レイアウトを狭くして表示量をより多くできます。</span><span class="sxs-lookup"><span data-stu-id="55209-304">**Relaxed or tighter layout? You choose:** Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

- <span data-ttu-id="55209-305">\*\* Outlook のユーザー エクスペリエンスを更新しました：\*\* これまで Coming Soon でプレビューできていた、最も重要なことに集中できるようにするためのシンプルな操作性です。</span><span class="sxs-lookup"><span data-stu-id="55209-305">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="55209-306">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-306">Learn more</span></span>](https://support.office.com/ja-JP/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="55209-307">**自分で描いて表現しましょう:** 画像の上に走り書きするか、描画キャンバスを追加して、インクを用いて自分の考えを送信します。</span><span class="sxs-lookup"><span data-stu-id="55209-307">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="55209-308">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-308">Learn more</span></span>](https://support.office.com/ja-JP/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

### <a name="word-feature-updates"></a><span data-ttu-id="55209-309">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-309">Word: Feature updates</span></span>

- <span data-ttu-id="55209-310">\*\* 共同編集：\*\* マクロを使用したドキュメントから締め出されるのにうんざりしていませんか。</span><span class="sxs-lookup"><span data-stu-id="55209-310">**CoAuthoring:** Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="55209-311">これで OneDrive for Business 上の docm ファイルで複数の作成者による同時編集が可能になります。</span><span class="sxs-lookup"><span data-stu-id="55209-311">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="55209-312">Skype for Business: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="55209-312">Skype for Business: Non-security updates</span></span> 

 - <span data-ttu-id="55209-313">モニタの倍率が 100 ％を超えたときに、会議で Polycom CX5500 および関連デバイスからのすべてのカメラストリームを表示するように修正しました。</span><span class="sxs-lookup"><span data-stu-id="55209-313">Fix to display all camera streams from Polycom CX5500 and related devices in a meeting when your monitor is scaled more than 100%</span></span>

- <span data-ttu-id="55209-314">[会議のビデオをトリミングして中央揃えにする] 設定が有効になっている場合、4Kモニタで会議のビデオを正しくトリミングします</span><span class="sxs-lookup"><span data-stu-id="55209-314">Correctly crop video in a meeting on a 4K monitor when the "Crop and Center my video in meetings" setting is enabled</span></span>

- <span data-ttu-id="55209-315">複数のネットワークアダプタを備えた Windows 10 コンピュータから従来の Office Communicator クライアントへのファイル転送を許可します。</span><span class="sxs-lookup"><span data-stu-id="55209-315">Allow transferring files to legacy Office Communicator clients from a Windows 10 computer with multiple network adapters.</span></span> [<span data-ttu-id="55209-316">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-316">Learn more</span></span>](https://support.microsoft.com/help/4508477)

- <span data-ttu-id="55209-317">Skype for Business と Microsoft Teams の参加者間のコミュニケーションのしやすさが向上</span><span class="sxs-lookup"><span data-stu-id="55209-317">Improved experience for communication between Skype for Business and Microsoft Teams participants</span></span>


## <a name="version-1905-june-11"></a><span data-ttu-id="55209-318">バージョン 1905: 6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="55209-318">Version 1905: June 11</span></span>
<span data-ttu-id="55209-319">*バージョン 1905 (ビルド 11629.20246)*</span><span class="sxs-lookup"><span data-stu-id="55209-319">*Version 1905 (Build 11629.20246)*</span></span>
<br/><span data-ttu-id="55209-320">[こちら](https://docs.microsoft.com/ja-JP/officeupdates/office365-proplus-security-updates)にセキュリティ更新プログラムが記載されています</span><span class="sxs-lookup"><span data-stu-id="55209-320">Security updates listed [here](https://docs.microsoft.com/ja-JP/officeupdates/office365-proplus-security-updates)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="55209-321">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="55209-321">Excel: Non-security updates</span></span>

- <span data-ttu-id="55209-322">セルが挿入または削除されたときに、ウォーターフォール図とじょうごグラフがテーブルと同期しなくなる原因となっていた問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="55209-322">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="55209-323">PowerPoint: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="55209-323">PowerPoint: Non-security updates</span></span>

- <span data-ttu-id="55209-324">一部のアドインがグラフの図形に対して予期しないエラーをスローさせる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="55209-324">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

### <a name="visio-non-security-updates"></a><span data-ttu-id="55209-325">Visio: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="55209-325">Visio: Non-security updates</span></span>

- <span data-ttu-id="55209-326">Visio から SVG へのエクスポートは、さまざまな図形に対して機能しませんでした。</span><span class="sxs-lookup"><span data-stu-id="55209-326">Export to SVG from Visio was not working for a variety of shapes.</span></span>

## <a name="version-1905-june-3"></a><span data-ttu-id="55209-327">バージョン 1905: 6 月 3 日</span><span class="sxs-lookup"><span data-stu-id="55209-327">Version 1905: June 3</span></span>
<span data-ttu-id="55209-328">*バージョン 1905 (ビルド 11629.20214)*</span><span class="sxs-lookup"><span data-stu-id="55209-328">*Version 1905 (Build 11629.20214)*</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="55209-329">PowerPoint: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="55209-329">PowerPoint: Non-security updates</span></span>

- <span data-ttu-id="55209-330">一部のアドインがグラフの図形に対して予期しないエラーをスローさせる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="55209-330">Fixed an issue where some addins would throw unexpected errors around shapes in charts.</span></span>

## <a name="version-1905-may-29"></a><span data-ttu-id="55209-331">バージョン 1905: 5 月 29 日</span><span class="sxs-lookup"><span data-stu-id="55209-331">Version 1905: May 29</span></span>
<span data-ttu-id="55209-332">*バージョン 1905 (ビルド 11629.20196)*</span><span class="sxs-lookup"><span data-stu-id="55209-332">*Version 1905 (Build 11629.20196)*</span></span>

### <a name="access-feature-updates"></a><span data-ttu-id="55209-333">Access: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-333">Access: Feature updates</span></span>

- <span data-ttu-id="55209-334">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="55209-334">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="55209-335">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="55209-335">Switching between them has never been easier.</span></span> [<span data-ttu-id="55209-336">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-336">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="excel-feature-updates"></a><span data-ttu-id="55209-337">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-337">Excel: Feature updates</span></span>

- <span data-ttu-id="55209-338">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="55209-338">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="55209-339">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="55209-339">Switching between them has never been easier.</span></span> [<span data-ttu-id="55209-340">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-340">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="55209-341">**近日公開予定:** 近日公開予定の Office に対する魅力あふれる変更点を確認してお試しいただき、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="55209-341">**Coming Soon:** See what exciting changes are Coming Soon to Office, try them out and give us feedback.</span></span> [<span data-ttu-id="55209-342">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-342">Learn more</span></span>](https://support.office.com/article/7800e0cf0-812f-475a-80aa-d47376e076f2)

- <span data-ttu-id="55209-343">**コメント内で @メンションを使用してより効率的に共同作業を行う:** 共同作業がとても簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="55209-343">**Collaborate more effectively with @Mentions in Comments:** Collaboration just became a whole lot easier!</span></span> <span data-ttu-id="55209-344">ドキュメントのコメント内でチームメートを @メンションできるようになりました。ドキュメントに案内するメール通知が自動的にチームメートに送られます。</span><span class="sxs-lookup"><span data-stu-id="55209-344">Now you can @mention teammates in document comments and they will automatically receive an email notification drawing them into the document.</span></span>

- <span data-ttu-id="55209-345">**共同編集の結合の改善:** 条件付き書式、セルのスタイル、範囲の保護、グリッド線の表示、シート間の切り取り/貼り付けを使用する際に、共同編集での結合の成功率が改善されました。</span><span class="sxs-lookup"><span data-stu-id="55209-345">**Coauthoring merge improvements:** Coauthoring has improved the merge success rate when working with conditional formatting, cell styles, range protection, view gridlines, and cross-sheet cut/paste.</span></span> 

### <a name="outlook"></a><span data-ttu-id="55209-346">Outlook</span><span class="sxs-lookup"><span data-stu-id="55209-346">Outlook</span></span>

- <span data-ttu-id="55209-347">**より簡単なアカウントの追加方法:** アカウントのセットアップの改善により、2 要素認証を使用する Outlook.com と Gmail のアカウントを Outlook に追加することが以前よりも簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="55209-347">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="55209-348">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-348">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="55209-349">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-349">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="55209-350">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="55209-350">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="55209-351">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="55209-351">Switching between them has never been easier.</span></span> [<span data-ttu-id="55209-352">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-352">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="55209-353">**ライブ キャプションと字幕:** 発表者の言葉が、キャプションまたは選択した言語での字幕として自動的に画面に表示されます。</span><span class="sxs-lookup"><span data-stu-id="55209-353">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="55209-354">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-354">Learn more</span></span>](https://support.office.com/article/d68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="55209-355">**近日公開予定:** 近日公開予定の Office に対する魅力あふれる変更点を確認してお試しいただき、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="55209-355">**Coming Soon:** See what exciting changes are Coming Soon to Office, try them out and give us feedback.</span></span> [<span data-ttu-id="55209-356">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-356">Learn more</span></span>](https://support.office.com/article/7800e0cf0-812f-475a-80aa-d47376e076f2)

- <span data-ttu-id="55209-357">**コメント内で @メンションを使用してより効率的に共同作業を行う:** 共同作業がとても簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="55209-357">**Collaborate more effectively with @Mentions in Comments:** Collaboration just became a whole lot easier!</span></span> <span data-ttu-id="55209-358">ドキュメントのコメント内でチームメートを @メンションできるようになりました。ドキュメントに案内するメール通知が自動的にチームメートに送られます。</span><span class="sxs-lookup"><span data-stu-id="55209-358">Now you can @mention teammates in document comments and they will automatically receive an email notification drawing them into the document.</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="55209-359">Project: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-359">Project: Feature updates</span></span>

- <span data-ttu-id="55209-360">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="55209-360">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="55209-361">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="55209-361">Switching between them has never been easier.</span></span> [<span data-ttu-id="55209-362">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-362">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio-feature-updates"></a><span data-ttu-id="55209-363">Visio: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-363">Visio: Feature updates</span></span>

- <span data-ttu-id="55209-364">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="55209-364">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="55209-365">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="55209-365">Switching between them has never been easier.</span></span> [<span data-ttu-id="55209-366">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-366">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="55209-367">**PDF または PPT にエクスポートされた、またはメール サブスクリプションをセットアップした Power BI レポートで、Visio Visual もサポートされるようになりました:** Power BI レポートを PDF または PPT にエクスポート、またはメール サブスクリプションにセットアップした場合、Visio Visual はこれらのエクスポート先の形式でシームレスにレンダリングされます。</span><span class="sxs-lookup"><span data-stu-id="55209-367">**Power BI reports exported to PDF, PPT or set up for email subscription will now feature Visio Visual as well:** If you export your Power BI reports to PDF, PPT or set up an email subscription for them, Visio Visual will render in these exported formats seamlessly.</span></span> [<span data-ttu-id="55209-368">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-368">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word-feature-updates"></a><span data-ttu-id="55209-369">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-369">Word: Feature updates</span></span>  

- <span data-ttu-id="55209-370">**コメント内で @メンションを使用してより効率的に共同作業を行う:** 共同作業がとても簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="55209-370">**Collaborate more effectively with @Mentions in Comments:** Collaboration just became a whole lot easier!</span></span> <span data-ttu-id="55209-371">ドキュメントのコメント内でチームメートを @メンションできるようになりました。ドキュメントに案内するメール通知が自動的にチームメートに送られます。</span><span class="sxs-lookup"><span data-stu-id="55209-371">Now you can @mention teammates in document comments and they will automatically receive an email notification drawing them into the document.</span></span>

- <span data-ttu-id="55209-372">**シームレスな切り替え:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用アカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="55209-372">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="55209-373">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="55209-373">Switching between them has never been easier.</span></span> [<span data-ttu-id="55209-374">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-374">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="55209-375">**[学習ツール] モードで、ページで使用できる色が増えました:** Word の学習ツールでは、より多くのページ テーマ色が追加され、ページの背景色を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="55209-375">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="55209-376">すべて白またはすべて黒の背景だと読みにくいと感じるユーザーは少なくないため、PC と Mac の Word で色の選択肢を拡大しました。</span><span class="sxs-lookup"><span data-stu-id="55209-376">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="55209-377">**近日公開予定:** 近日公開予定の Office に対する魅力あふれる変更点を確認してお試しいただき、フィードバックをお寄せください。</span><span class="sxs-lookup"><span data-stu-id="55209-377">**Coming Soon:** See what exciting changes are Coming Soon to Office, try them out and give us feedback.</span></span> [<span data-ttu-id="55209-378">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-378">Learn more</span></span>](https://support.office.com/article/7800e0cf0-812f-475a-80aa-d47376e076f2)

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="55209-379">Skype for Business: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="55209-379">Skype for Business: Non-security updates</span></span>

- <span data-ttu-id="55209-380">"ユーザーに自分を知ってもらうのに役立つ、写真の追加" コンテキストのヒントを無効にするオプションを Skype for Business Online ユーザーに提供します。</span><span class="sxs-lookup"><span data-stu-id="55209-380">Provides the option to Skype for Business Online users to disable the "Add your photo - it'll help people get to know you" contextual tip.</span></span> <span data-ttu-id="55209-381">この修正を有効にするには、[詳細情報](https://support.microsoft.com/help/4503469)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="55209-381">To enable this fix, you can [Learn more](https://support.microsoft.com/help/4503469).</span></span>

- <span data-ttu-id="55209-382">Skype for Business の再起動後に、セカンダリ呼び出しの設定が常に有効になるのを防ぎます。</span><span class="sxs-lookup"><span data-stu-id="55209-382">Prevents secondary ringer setting from always being enabled after restarting Skype for Business.</span></span> <span data-ttu-id="55209-383">この修正を有効にするには、[詳細情報](https://support.microsoft.com/help/4503470)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="55209-383">To enable this fix, you can [Learn more](https://support.microsoft.com/help/4503470).</span></span>

 - <span data-ttu-id="55209-384">Lync SDK ベースのアプリケーションを使用しながら、大規模な会議に参加するときに Skype for Business の応答を停止させる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="55209-384">Fix for an issue that made Skype for Business stop responding when joining a large meeting while also using a Lync SDK-based application.</span></span> <span data-ttu-id="55209-385">この修正を有効にするには、[詳細情報](https://support.microsoft.com/help/4503472)を確認してください。</span><span class="sxs-lookup"><span data-stu-id="55209-385">To enable this fix, you can [Learn more](https://support.microsoft.com/help/4503472).</span></span>

## <a name="version-1904-may-22"></a><span data-ttu-id="55209-386">バージョン 1904: 5 月 22 日</span><span class="sxs-lookup"><span data-stu-id="55209-386">Version 1904: May 22</span></span>
<span data-ttu-id="55209-387">*バージョン 1904 (ビルド 11601.20230)*</span><span class="sxs-lookup"><span data-stu-id="55209-387">*Version 1904 (Build 11601.20230)*</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="55209-388">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="55209-388">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="55209-389">これにより、ユーザーがプライバシー レベルを選択して確認した後も、アプリケーションが起動される度に新しいプライバシー プロンプトが表示される問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="55209-389">This addresses an issue where users see the new Privacy Prompt on every application launch even after selecting and committing a choice for their privacy level.</span></span>

## <a name="version-1904-may-14"></a><span data-ttu-id="55209-390">バージョン 1904: 5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="55209-390">Version 1904: May 14</span></span> 
<span data-ttu-id="55209-391">*バージョン 1904 (ビルド 11601.20204)*</span><span class="sxs-lookup"><span data-stu-id="55209-391">*Version 1904 (Build 11601.20204)*</span></span>

 - <span data-ttu-id="55209-392">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/ja-JP/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="55209-392">Security updates listed [here](https://docs.microsoft.com/ja-JP/officeupdates/office365-proplus-security-updates)</span></span>

## <a name="version-1904-may-8"></a><span data-ttu-id="55209-393">バージョン 1904: 5 月 8 日</span><span class="sxs-lookup"><span data-stu-id="55209-393">Version 1904: May 8</span></span>
<span data-ttu-id="55209-394">*バージョン 1904 (ビルド 11601.20178)*</span><span class="sxs-lookup"><span data-stu-id="55209-394">*Version 1904 (Build 11601.20178)*</span></span>

- <span data-ttu-id="55209-395">さまざまなバグやパフォーマンスが修正されました。</span><span class="sxs-lookup"><span data-stu-id="55209-395">Various bugs and performances fixes.</span></span>

## <a name="version-1904-april-29"></a><span data-ttu-id="55209-396">バージョン 1904: 4 月 29 日</span><span class="sxs-lookup"><span data-stu-id="55209-396">Version 1904: April 29</span></span>
<span data-ttu-id="55209-397">*バージョン 1904 (ビルド 11601.20144)*</span><span class="sxs-lookup"><span data-stu-id="55209-397">*Version 1904 (Build 11601.20144)*</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="55209-398">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-398">Excel: Feature updates</span></span>

- <span data-ttu-id="55209-399">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="55209-399">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="55209-400">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="55209-400">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="55209-401">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-401">Outlook: Feature updates</span></span>

- <span data-ttu-id="55209-402">\*\* Outlook に LinkedIn ネットワークを接続する:\*\* LinkedIn アカウントを Microsoft アカウントに安全に接続して、LinkedIn プロファイルからの情報を [連絡先カード] に直接表示できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="55209-402">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="55209-403">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-403">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="55209-404">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-404">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="55209-405">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="55209-405">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="55209-406">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="55209-406">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="55209-407">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-407">Word: Feature updates</span></span>

- <span data-ttu-id="55209-408">**色の変更履歴、コメントとリアルタイムの共同作業の同期:** 当社の製品での、コメント、変更履歴と共同作業者のカーソルが同じ色で表示されることについての修正箇所を確認しました。</span><span class="sxs-lookup"><span data-stu-id="55209-408">**Colors for Track Changes, Comments and Real-Time Collaboration in Sync:** Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

- <span data-ttu-id="55209-409">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="55209-409">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="55209-410">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="55209-410">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="55209-411">Visio: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-411">Visio: Feature updates</span></span>

- <span data-ttu-id="55209-412">**プロセス図を Word にエクスポート:** Word 文書に図形やメタデータなどのグラフ コンテンツを自動的に追加します。</span><span class="sxs-lookup"><span data-stu-id="55209-412">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="55209-413">その後に、文書をカスタマイズしてプロセスに関するガイドラインや操作マニュアルを作成できます。</span><span class="sxs-lookup"><span data-stu-id="55209-413">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="55209-414">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-414">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

### <a name="office-suite-feature-updates"></a><span data-ttu-id="55209-415">Office スイート: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-415">Office Suite: Feature updates</span></span>

- <span data-ttu-id="55209-416">**新しいアイコン:** フィードバックに基づいて、300 を超える新しいアイコンが追加されました。</span><span class="sxs-lookup"><span data-stu-id="55209-416">**New icons:** We've added over 300 new icons based on your feedback.</span></span> <span data-ttu-id="55209-417">[アイコン] ボタンを使用して、リボンの [挿入] タブに表示されます。</span><span class="sxs-lookup"><span data-stu-id="55209-417">You'll find them using the Icons button on the Insert tab of the ribbon.</span></span>

- <span data-ttu-id="55209-418">**プライバシー制御**: 診断データおよび関連するエクスペリエンスに関する新しく更新されて改善された制御。</span><span class="sxs-lookup"><span data-stu-id="55209-418">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="55209-419">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-419">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

### <a name="outlook-non-security-updates"></a><span data-ttu-id="55209-420">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="55209-420">Outlook: Non-security updates</span></span>

- <span data-ttu-id="55209-421">件名が極端に小さくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="55209-421">Fixed an issue causing the subject to show extremely small.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="55209-422">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="55209-422">Office Suite: Non-security updates</span></span>
- <span data-ttu-id="55209-423">新時代の名前である「Reiwa」のひらがなと漢字をスペルミスまたは間違った文法として誤って識別していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="55209-423">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="55209-424">プロキシ認証がシステムとして実行されたときに Office の更新プログラムがブロックされるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="55209-424">Fixed an issue that blocked Office Updates when proxy authentication runs as SYSTEM.</span></span>

## <a name="version-1903-april-23"></a><span data-ttu-id="55209-425">バージョン 1903: 4 月 23 日</span><span class="sxs-lookup"><span data-stu-id="55209-425">Version 1903: April 23</span></span>
<span data-ttu-id="55209-426">*バージョン 1903 (ビルド 11425.20244)*</span><span class="sxs-lookup"><span data-stu-id="55209-426">*Version 1903 (Build 11425.20244)*</span></span>

- <span data-ttu-id="55209-427">さまざまなバグやパフォーマンスが修正されました。</span><span class="sxs-lookup"><span data-stu-id="55209-427">Various bugs and performances fixes.</span></span>

## <a name="version-1903-april-17"></a><span data-ttu-id="55209-428">バージョン 1903: 4 月 17 日</span><span class="sxs-lookup"><span data-stu-id="55209-428">Version 1903: April 17</span></span>
<span data-ttu-id="55209-429">*バージョン 1903 (ビルド 11425.20228)*</span><span class="sxs-lookup"><span data-stu-id="55209-429">*Version 1903 (Build 11425.20228)*</span></span>

- <span data-ttu-id="55209-430">さまざまなバグやパフォーマンスが修正されました。</span><span class="sxs-lookup"><span data-stu-id="55209-430">Various bugs and performances fixes.</span></span>

## <a name="version-1903-april-16"></a><span data-ttu-id="55209-431">バージョン 1903: 4 月 16 日</span><span class="sxs-lookup"><span data-stu-id="55209-431">Version 1903: April 16</span></span>
<span data-ttu-id="55209-432">*バージョン 1903 (ビルド 11425.20218)*</span><span class="sxs-lookup"><span data-stu-id="55209-432">*Version 1903 (Build 11425.20218)*</span></span>

- <span data-ttu-id="55209-433">さまざまなバグやパフォーマンスが修正されました。</span><span class="sxs-lookup"><span data-stu-id="55209-433">Various bugs and performances fixes.</span></span>

## <a name="version-1903-april-9"></a><span data-ttu-id="55209-434">バージョン 1903: 4 月 9 日</span><span class="sxs-lookup"><span data-stu-id="55209-434">Version 1903: April 9</span></span>
<span data-ttu-id="55209-435">*バージョン 1903 (ビルド 11425.20204)*</span><span class="sxs-lookup"><span data-stu-id="55209-435">*Version 1903 (Build 11425.20204)*</span></span> 

- <span data-ttu-id="55209-436">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/ja-JP/officeupdates/office365-proplus-security-updates)</span><span class="sxs-lookup"><span data-stu-id="55209-436">Security updates listed [here](https://docs.microsoft.com/ja-JP/officeupdates/office365-proplus-security-updates)</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="55209-437">Skype for Business: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="55209-437">Skype for Business: Non-security updates</span></span>
- <span data-ttu-id="55209-438">Lync (Skype for Business) で、参加者が 7 人以上のオンライン ミーティングのミーティング ウィンドウが表示されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="55209-438">Fixed an issue in Lync (Skype for Business) where for any online meeting with more 7+ participants, the meeting window can disappear.</span></span>

## <a name="version-1903-april-01"></a><span data-ttu-id="55209-439">バージョン 1903: 4 月 1 日</span><span class="sxs-lookup"><span data-stu-id="55209-439">Version 1903: April 01</span></span>
<span data-ttu-id="55209-440">*Version 1903 (Build 11425.20202)*</span><span class="sxs-lookup"><span data-stu-id="55209-440">*Version 1903 (Build 11425.20202)*</span></span> 

### <a name="excel-feature-updates"></a><span data-ttu-id="55209-441">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-441">Excel: Feature updates</span></span>

- <span data-ttu-id="55209-442">**Excel のインサイト:** インサイトには、ユーザーの範囲に値が用意されています。</span><span class="sxs-lookup"><span data-stu-id="55209-442">**Insights in Excel:** Insights provides value to a range of users.</span></span> <span data-ttu-id="55209-443">インサイトは、データ分析にソフトなアプローチを提供し、データに他からの違う視点を提供します。</span><span class="sxs-lookup"><span data-stu-id="55209-443">Insights provides a softer approach to data analysis and for others it provides a different perspective to your data.</span></span> [<span data-ttu-id="55209-444">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-444">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)


- <span data-ttu-id="55209-445">**コンテンツのリーチを拡大:** アクセシビリティの高いスプレッドシートを作成する必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="55209-445">**Increase the reach of your content:**  Need to make your spreadsheets accessible?</span></span> <span data-ttu-id="55209-446">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="55209-446">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="55209-447">[校閲] > [アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="55209-447">Try it by clicking Review > Check Accessibility and we’ll tell you when we find something you need to look at in the status bar.</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="55209-448">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-448">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="55209-449">**よりよい変形操作:** 図形に名前を付けると、変形するときにより細かく制御できます。</span><span class="sxs-lookup"><span data-stu-id="55209-449">**Better shapeshifting:**  Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="55209-450">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-450">Learn more</span></span>](https://support.office.com/article/9bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="55209-451">**コンテンツのリーチを拡大:** アクセシビリティの高いプレゼンテーションを作成する必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="55209-451">**Increase the reach of your content:**  Need to make your presentations accessible?</span></span> <span data-ttu-id="55209-452">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="55209-452">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="55209-453">[校閲]>[アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="55209-453">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="55209-454">**再利用できる場合、新たに作成し直しますか?**</span><span class="sxs-lookup"><span data-stu-id="55209-454">**Why reinvent when you can re-use?**</span></span>  <span data-ttu-id="55209-455">作成した、または他のユーザーと共有しているスライドを再利用して時間を節約します。</span><span class="sxs-lookup"><span data-stu-id="55209-455">Save time by re-using slides that you created or that others have shared with you.</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="55209-456">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="55209-456">Excel: Non-security updates</span></span>

- <span data-ttu-id="55209-457">Excel では、ユーザーが変更を取得するためにブックを再び開くよう要求される結果となるマージ競合の問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="55209-457">Fixed a merge conflict issue in Excel  that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="55209-458">Skype for Business: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="55209-458">Skype for Business: Non-security updates</span></span>

- <span data-ttu-id="55209-459">サード パーティの SfB/Lync SDK アプリが存在する場合に、Skype for Business のチャット通知への応答が停止される原因となった問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="55209-459">Fix for issue that caused Skype for Business to stop responding when responding to chat notifications if 3rd party SfB/Lync SDK app present.</span></span>
- <span data-ttu-id="55209-460">チャットに特定のクリップボードの内容を貼り付けるときにアプリがクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="55209-460">Fix for app crash when specific clipboard content is pasted into a chat.</span></span>
- <span data-ttu-id="55209-461">いずれかの通話エージェントが受信した呼び出しキューの呼び出しの "受け入れ担当者" 情報が表示されるのを妨げている問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="55209-461">Fix for issue that prevented display of the "accepted by" information for a Call Queue call that's picked up by one of the call agents.</span></span>
- <span data-ttu-id="55209-462">Teams のユーザーが Skype for Business 会議に参加したときに通話アイコンが非表示になる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="55209-462">Fixed issue that hid call icons when a Teams user joins a Skype for Business meeting.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="55209-463">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-463">Word: Feature updates</span></span>

- <span data-ttu-id="55209-464">**コンテンツのリーチを拡大:** アクセシビリティの高いドキュメントを作成する必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="55209-464">**Increase the reach of your content:**  Need to make your documents accessible?</span></span> <span data-ttu-id="55209-465">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="55209-465">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="55209-466">[校閲]>[アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="55209-466">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

## <a name="version-1902-march-25"></a><span data-ttu-id="55209-467">バージョン 1902: 3 月 25 日</span><span class="sxs-lookup"><span data-stu-id="55209-467">Version 1902: March 25</span></span>
<span data-ttu-id="55209-468">*バージョン 1902 (ビルド 11328.20222)*</span><span class="sxs-lookup"><span data-stu-id="55209-468">*Version 1902 (Build 11328.20222)*</span></span>

- <span data-ttu-id="55209-469">さまざまなバグやパフォーマンスが修正されました。</span><span class="sxs-lookup"><span data-stu-id="55209-469">Various bugs and performances fixes.</span></span>

## <a name="version-1902-march-12"></a><span data-ttu-id="55209-470">バージョン 1902: 3 月 12 日</span><span class="sxs-lookup"><span data-stu-id="55209-470">Version 1902: March 12</span></span>
<span data-ttu-id="55209-471">*バージョン 1902 (ビルド 11328.20158)*</span><span class="sxs-lookup"><span data-stu-id="55209-471">*Version 1902 (Build 11328.20158)*</span></span> 

- <span data-ttu-id="55209-472">さまざまなバグやパフォーマンスが修正されました。</span><span class="sxs-lookup"><span data-stu-id="55209-472">Various bugs and performances fixes.</span></span>

## <a name="version-1902-march-4"></a><span data-ttu-id="55209-473">バージョン 1902: 3 月 4 日</span><span class="sxs-lookup"><span data-stu-id="55209-473">Version 1902: March 4</span></span>
<span data-ttu-id="55209-474">*バージョン 1902 (ビルド 11328.20146)*</span><span class="sxs-lookup"><span data-stu-id="55209-474">*Version 1902 (Build 11328.20146)*</span></span> 

### <a name="access-feature-updates"></a><span data-ttu-id="55209-475">Access: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-475">Access: Feature updates</span></span>

- <span data-ttu-id="55209-476">**データベース オブジェクトをタブで管理する:** アクティブなタブが分かりやすく表示され、簡単にタブをドラッグして再配置し、ワンクリックでデータベース オブジェクトを閉じることができます。</span><span class="sxs-lookup"><span data-stu-id="55209-476">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>
- <span data-ttu-id="55209-477">**より大きい [ズーム] ボックス:** [ズーム] ボックスがより大きく表示され、そこでフォントを変更することができます。変更内容はすべて [ズーム] ボックス内に記憶されます。</span><span class="sxs-lookup"><span data-stu-id="55209-477">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="55209-478">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-478">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel-feature-updates"></a><span data-ttu-id="55209-479">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-479">Excel: Feature updates</span></span>

- <span data-ttu-id="55209-480">**\@メンションを使用してユーザーの注意を引く:** コメントで @メンションを使うと、仕事仲間による入力が必要な場合にそのユーザーに知らせることができます。</span><span class="sxs-lookup"><span data-stu-id="55209-480">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="55209-481">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-481">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)
- <span data-ttu-id="55209-482">**データの詳細を検出する:** 新しいアイデア ボタンは、データのパターンを探し、それを使用してインテリジェントな個人向けの提案を作成します。</span><span class="sxs-lookup"><span data-stu-id="55209-482">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions.</span></span> [<span data-ttu-id="55209-483">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-483">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)
- <span data-ttu-id="55209-484">**変更が発生したときに変更内容を自動的に保存する:** 変更が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="55209-484">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>
- <span data-ttu-id="55209-485">**フィルターが適用された SVG を挿入する機能:** Office ユーザーは、フィルターが適用された SVG を挿入できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="55209-485">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them.</span></span> [<span data-ttu-id="55209-486">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-486">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook-feature-updates"></a><span data-ttu-id="55209-487">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-487">Outlook: Feature updates</span></span>

- <span data-ttu-id="55209-488">**連続する会議の合間に時間を組み込む:** 既定で 5 分から 10 分早く会議を終了するように設定することで、出席者に休憩時間や場所の移動時間を与えることができます。</span><span class="sxs-lookup"><span data-stu-id="55209-488">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span> [<span data-ttu-id="55209-489">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-489">Learn more</span></span>](https://support.office.com/ja-JP/article/Schedule-a-meeting-with-other-people-5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F#BKMK_endmeetingsearly)
- <span data-ttu-id="55209-490">**音声読み上げを使用してメールの内容を聞く:** Outlook では、メールのテキストを読み上げながら強調表示することができます。</span><span class="sxs-lookup"><span data-stu-id="55209-490">**Use Read Aloud to listen to your email:** Outlook can read your email aloud, highlighting text as it's read.</span></span> <span data-ttu-id="55209-491">読み上げ機能をオンにするには、[簡単操作] の設定に移動します。</span><span class="sxs-lookup"><span data-stu-id="55209-491">To turn on Read Aloud, go to the Ease of Access settings.</span></span> [<span data-ttu-id="55209-492">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-492">Learn more</span></span>](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)
- <span data-ttu-id="55209-493">**フィルターが適用された SVG を挿入する機能:** Office ユーザーは、フィルターが適用された SVG を挿入できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="55209-493">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them.</span></span> [<span data-ttu-id="55209-494">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-494">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="55209-495">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-495">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="55209-496">**これまで以上に簡単にオンライン ビデオを挿入できるようになりました:** Vimeo または YouTube からビデオをスライドに挿入する場合は、</span><span class="sxs-lookup"><span data-stu-id="55209-496">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide?</span></span> <span data-ttu-id="55209-497">ビデオ ページへのリンクがあれば簡単に行えます。</span><span class="sxs-lookup"><span data-stu-id="55209-497">The video page link is all you need.</span></span> [<span data-ttu-id="55209-498">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-498">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)
- <span data-ttu-id="55209-499">**手書きの数式の自動書式設定:** 手書きの数式を標準の文字に変換することができます。</span><span class="sxs-lookup"><span data-stu-id="55209-499">**You compute, we format:** We change hand-drawn math expressions into standard characters.</span></span> <span data-ttu-id="55209-500">変換を開始するには、[インクから数式] を選択して、手書きのメモを選択します。</span><span class="sxs-lookup"><span data-stu-id="55209-500">Just choose Ink to Math and select your handwritten notes to get started.</span></span> [<span data-ttu-id="55209-501">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-501">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- <span data-ttu-id="55209-502">**変更が発生したときに変更内容を自動的に保存する:** 変更が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="55209-502">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>
- <span data-ttu-id="55209-503">**フィルターが適用された SVG を挿入する機能:** Office ユーザーは、フィルターが適用された SVG を挿入できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="55209-503">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them.</span></span> [<span data-ttu-id="55209-504">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-504">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- <span data-ttu-id="55209-505">**大きなファイルがより速く開くようになりました:** OneDrive または SharePoint に保存されているファイルを開くと、画像、ビデオ、およびその他の大きな要素がバックグラウンドでダウンロードされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="55209-505">**Large files now open faster:** Images, videos, and other large elements now download in the background when opening files stored on OneDrive or SharePoint.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="55209-506">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-506">Word: Feature updates</span></span>

- <span data-ttu-id="55209-507">**変更が発生したときに変更内容を自動的に保存する:** 変更が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="55209-507">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>
- <span data-ttu-id="55209-508">**自動保存がオンになっていない理由を確認する**</span><span class="sxs-lookup"><span data-stu-id="55209-508">**Find out why AutoSave isn't on!**</span></span> <span data-ttu-id="55209-509">自動保存がオフになっているときに自動保存トグルをクリックすると、吹き出しが表示されるようになりました。自動保存がオフになっている理由も示されます。</span><span class="sxs-lookup"><span data-stu-id="55209-509">Clicking on the AutoSave toggle when it's off will now either display a helpful callout with reasons why AutoSave might be off.</span></span> <span data-ttu-id="55209-510">ドキュメントが OneDrive または SharePoint 上に存在しないという理由で自動保存ができない場合でも、1 つのボタンをクリックするだけでドキュメントを移動することができるようになります。</span><span class="sxs-lookup"><span data-stu-id="55209-510">In the case where the only reason preventing AutoSave is the fact that the document is not on OneDrive or SharePoint, we will offer to move the document conveniently with one button click!</span></span>
- <span data-ttu-id="55209-511">**フィルターが適用された SVG を挿入する機能:** Office ユーザーは、フィルターが適用された SVG を挿入できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="55209-511">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them.</span></span> [<span data-ttu-id="55209-512">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-512">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
 
### <a name="office-suite-feature-updates"></a><span data-ttu-id="55209-513">Office スイート: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-513">Office Suite: Feature updates</span></span>

- <span data-ttu-id="55209-514">**Microsoft Teams のインストール:** Microsoft Teams は、Office 365 ProPlus の新規インストール用に既定でインストールされています。</span><span class="sxs-lookup"><span data-stu-id="55209-514">**Installation of Microsoft Teams:**  Microsoft Teams is installed by default for new installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="55209-515">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-515">Learn More</span></span>](https://docs.microsoft.com/ja-JP/deployoffice/teams-install)

## <a name="version-1901-february-12"></a><span data-ttu-id="55209-516">バージョン 1901: 2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="55209-516">Version 1901: February 12</span></span>
<span data-ttu-id="55209-517">*バージョン 1901 (ビルド 11231.20174)*</span><span class="sxs-lookup"><span data-stu-id="55209-517">*Version 1901 (Build 11231.20174)*</span></span> 

<span data-ttu-id="55209-518">セキュリティ更新プログラムの一覧は[こちら](office365-proplus-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="55209-518">Security updates listed [here](office365-proplus-security-updates.md)</span></span>

## <a name="version-1901-january-31"></a><span data-ttu-id="55209-519">バージョン 1901: 1 月 31 日</span><span class="sxs-lookup"><span data-stu-id="55209-519">Version 1901: January 31</span></span>
<span data-ttu-id="55209-520">*バージョン 1901 (ビルド 11231.20130)*</span><span class="sxs-lookup"><span data-stu-id="55209-520">*Version 1901 (Build 11231.20130)*</span></span> 

### <a name="excel-feature-updates"></a><span data-ttu-id="55209-521">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-521">Excel: Feature updates</span></span>

- <span data-ttu-id="55209-p186">**コメントを利用して共同作業を行う:** 返信ボックスが組み込まれているので、スプレッドシートで直接会話を続けることができます。[詳細情報](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)</span><span class="sxs-lookup"><span data-stu-id="55209-p186">**Collaborate with comments:** Keep the conversation going right in your spreadsheet with the built-in reply box. [Learn more](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="55209-524">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-524">Outlook: Feature updates</span></span>

- <span data-ttu-id="55209-p187">**ミームが表示される:** テキストまたは静的イメージだけでは十分ではない場合、アニメーション GIF を使用して要点を示すことができます。[詳細情報](https://support.office.com/article/114BB251-861F-41CD-B20F-7E7289630C5B)</span><span class="sxs-lookup"><span data-stu-id="55209-p187">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114BB251-861F-41CD-B20F-7E7289630C5B)</span></span>
 
### <a name="visio-feature-updates"></a><span data-ttu-id="55209-527">Visio: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-527">Visio: Feature updates</span></span>

- <span data-ttu-id="55209-528">**ダブル テイク オン データ フローチャート:** データ ビジュアライザーのフローチャート用の新しいレイアウトは、きれいで鮮明でとても分かりやすいです。</span><span class="sxs-lookup"><span data-stu-id="55209-528">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> [<span data-ttu-id="55209-529">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-529">Learn more</span></span>](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)

- <span data-ttu-id="55209-530">**Azure ステンシルが組み込まれました:** 豊富な Azure ステンシルを使用してクラウド アプリの設計やアーキテクチャの計画を行うことができます。</span><span class="sxs-lookup"><span data-stu-id="55209-530">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="55209-531">詳細情報</span><span class="sxs-lookup"><span data-stu-id="55209-531">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word-feature-updates"></a><span data-ttu-id="55209-532">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-532">Word: Feature updates</span></span>

- <span data-ttu-id="55209-p190">**静的なドキュメントから魅力的なドキュメントへの変換:** ドキュメントを、すべてのデバイスに対応する対話型の使いやすい Web ページに変換します。[詳細情報](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="55209-p190">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

### <a name="office-suite-feature-updates"></a><span data-ttu-id="55209-535">Office スイート: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-535">Office Suite: Feature updates</span></span>

- <span data-ttu-id="55209-p191">**Office のサード パーティ アプリケーションでは office.js api を使用した SVG の挿入をサポート:** Office アドインとも呼ばれるサード パーティ アプリケーションで SVG を挿入できるようになりました。ユーザーは、個人の SVG コレクションを Office に結び付けることができます。開発者は、Office.js API を使用してこの機能を利用できます。</span><span class="sxs-lookup"><span data-stu-id="55209-p191">**Office 3rd Party Applications now have insert SVG support using the office.js api:** 3rd party applications also known as add-ins in Office now have the ability to insert SVG's. Users can now connect their personal collection of SVG's to Office. Developers can use this feature by using the Office.js API.</span></span>


## <a name="version-1812-january-14"></a><span data-ttu-id="55209-539">バージョン 1812: 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="55209-539">Version 1812: January 14</span></span>
<span data-ttu-id="55209-540">*バージョン 1812 (ビルド 11126.20266)*</span><span class="sxs-lookup"><span data-stu-id="55209-540">*Version 1812 (Build 11126.20266)*</span></span> 

<span data-ttu-id="55209-541">パフォーマンス上の問題に対処するセキュリティ関連ではない更新プログラムのみ。</span><span class="sxs-lookup"><span data-stu-id="55209-541">Non-security updates only, addressing performance issues.</span></span>

## <a name="version-1812-january-8"></a><span data-ttu-id="55209-542">バージョン 1812: 1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="55209-542">Version 1812: January 8</span></span>
<span data-ttu-id="55209-543">*バージョン 1812 (ビルド 11126.20196)*</span><span class="sxs-lookup"><span data-stu-id="55209-543">*Version 1812 (Build 11126.20196)*</span></span> 

### <a name="project-non-security-updates"></a><span data-ttu-id="55209-544">Project: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="55209-544">Project: Non-security updates</span></span>
- <span data-ttu-id="55209-545">ガント チャートの [クリティカル]、[遅延]、[余裕期間] バー スタイルをオンにした後でオフにできない問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="55209-545">Fixed an issue where you couldn't uncheck the Critical, Late and Slack bar styles for the Gantt chart after you checked one.</span></span>

## <a name="version-1812-january-3"></a><span data-ttu-id="55209-546">バージョン 1812: 1 月 3 日</span><span class="sxs-lookup"><span data-stu-id="55209-546">Version 1812: January 3</span></span>
<span data-ttu-id="55209-547">*バージョン 1812 (ビルド 11126.20188)*</span><span class="sxs-lookup"><span data-stu-id="55209-547">*Version 1812 (Build 11126.20188)*</span></span> 

### <a name="excel-feature-updates"></a><span data-ttu-id="55209-548">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-548">Excel: Feature updates</span></span>

- <span data-ttu-id="55209-p192">**作業中にアクセシビリティ チェックを実行したままにする:** アクセシビリティ チェックを常に開いたままにしなくても、ドキュメントのアクセシビリティの問題を追跡できます。スペルチェックの場合のように、ステータス バーのインジケーターを介して、作業中に見つかったアクセシビリティの問題に Excel が自動的にフラグを付けます。</span><span class="sxs-lookup"><span data-stu-id="55209-p192">**Keep accessibility checker running while you work:** Keep track of accessibility issues in your document without needing the accessibility checker always open. Via an indicator in the status bar, much like spellcheck, Excel flags found accessibility issues while you are working.</span></span> 

### <a name="outlook-feature-updates"></a><span data-ttu-id="55209-551">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-551">Outlook: Feature updates</span></span>

- <span data-ttu-id="55209-p193">**すべての暗号化オプションを 1 か所に集約:** [オプション] > [暗号化] の順に移動するだけで、電子メール メッセージを保護する方法を選択できます。[詳細情報](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="55209-p193">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="55209-554">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-554">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="55209-p194">**インクで素晴らしいスライドを作成:** インクを標準的な図形とテキストに変換し、PowerPoint デザイナーからスマートなスライド デザイン アイデアを入手します。[詳細情報](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)</span><span class="sxs-lookup"><span data-stu-id="55209-p194">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer. [Learn more](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)</span></span>
- <span data-ttu-id="55209-p195">**作業中にアクセシビリティ チェックを実行したままにする:** アクセシビリティ チェックを常に開いたままにしなくても、ドキュメントのアクセシビリティの問題を追跡できます。スペルチェックの場合のように、ステータス バーのインジケーターを介して、作業中に見つかったアクセシビリティの問題に PowerPoint が自動的にフラグを付けます。</span><span class="sxs-lookup"><span data-stu-id="55209-p195">**Keep accessibility checker running while you work:** Keep track of accessibility issues in your document without needing the accessibility checker always open. Via an indicator in the status bar, much like spellcheck, PowerPoint flags found accessibility issues while you are working.</span></span> 

### <a name="word-feature-updates"></a><span data-ttu-id="55209-559">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-559">Word: Feature updates</span></span>

- <span data-ttu-id="55209-p196">**行フォーカスによる読解力の向上:** ドキュメント内で行ごとの移動をスムーズに行います。一度に 1 行か、3 行か、5 行かを表示するようフォーカスを調整できます。[詳細情報](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="55209-p196">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>
- <span data-ttu-id="55209-p197">**作業中にアクセシビリティ チェックを実行したままにする:** アクセシビリティ チェックを常に開いたままにしなくても、ドキュメントのアクセシビリティの問題を追跡できます。スペルチェックの場合のように、ステータス バーのインジケーターを介して、作業中に見つかったアクセシビリティの問題に Word が自動的にフラグを付けます。</span><span class="sxs-lookup"><span data-stu-id="55209-p197">**Keep accessibility checker running while you work:** Keep track of accessibility issues in your document without needing the accessibility checker always open. Via an indicator in the status bar, much like spellcheck, Word flags found accessibility issues while you are working.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="55209-565">Visio: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-565">Visio: Feature updates</span></span>

- <span data-ttu-id="55209-p198">**壊れた Excel リンクの問題を解消:** データ ビジュアライザーの図にリンクされているはずの Excel ブックが見つかりませんか? 再リンクして、すぐに業務を再開できます。[詳細情報](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="55209-p198">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

### <a name="office-suite-feature-updates"></a><span data-ttu-id="55209-569">Office スイート: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="55209-569">Office Suite: Feature updates</span></span>

- <span data-ttu-id="55209-570">**[新機能] ウィンドウ:** [新機能] はヘルプ ウィンドウに移行しました。そのため、最新の更新プログラムにより簡単にアクセスして最新情報を入手できます。</span><span class="sxs-lookup"><span data-stu-id="55209-570">**What's New Pane:** The What's New experience has moved to the Help Pane, so you can more easily access and stay up to date with our latest updates.</span></span>

> [!NOTE]
> <span data-ttu-id="55209-571">Office の使用で問題がある場合は、[Microsoft の回答フォーラム](https://answers.microsoft.com/)に関するページまたは「[Microsoft Tech Community](https://techcommunity.microsoft.com/)」に質問を投稿するか、[サポート](https://support.microsoft.com/contactus)に問い合わせてサポートを受けることができます。</span><span class="sxs-lookup"><span data-stu-id="55209-571">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>