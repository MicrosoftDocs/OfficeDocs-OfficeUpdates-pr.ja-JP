---
title: 2020での半期エンタープライズチャネル (プレビュー) リリースのリリースノート
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Microsoft 365 Apps 用の 2020 年の半期チャネル リリース (対象指定) のリリース ノートを IT 担当者に提供します
ms.openlocfilehash: be72a3d95178f0fde5bbe48428abb0895d5afefd
ms.sourcegitcommit: cc48ae789324e085a976c3a7a388353447b10d42
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/12/2020
ms.locfileid: "44724958"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview-releases-in-2020"></a><span data-ttu-id="2da6e-103">2020での半期エンタープライズチャネル (プレビュー) リリースのリリースノート</span><span class="sxs-lookup"><span data-stu-id="2da6e-103">Release notes for Semi-Annual Enterprise Channel (Preview) releases in 2020</span></span>

<span data-ttu-id="2da6e-104">これらのリリースノートでは、2020の「半期エンタープライズチャネル (プレビュー)」の更新プログラム (Microsoft 365 Apps for Enterprise、Microsoft 365 Apps for business)、および Project および Visio 用のデスクトップアプリのサブスクリプションバージョンに含まれる新機能とセキュリティ以外の更新プログラムに関する情報が提供されています。</span><span class="sxs-lookup"><span data-stu-id="2da6e-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="2da6e-105">Microsoft 365 アプリの更新チャネルの更新プログラムチャネルに、新しい更新チャネル (月間エンタープライズ チャネル) の追加や、既存の更新プログラムチャネルの名前の変更など、いくつかの変更を行っています。</span><span class="sxs-lookup"><span data-stu-id="2da6e-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="2da6e-106">詳細については、[こちらの記事を参照](https://go.microsoft.com/fwlink/p/?linkid=2127441)をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="2da6e-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>


## <a name="version-2002-june-09"></a><span data-ttu-id="2da6e-107">バージョン 2002:09 月9日</span><span class="sxs-lookup"><span data-stu-id="2da6e-107">Version 2002: June 09</span></span>
<span data-ttu-id="2da6e-108">*バージョン 2002 (ビルド 12527.20720)*</span><span class="sxs-lookup"><span data-stu-id="2da6e-108">*Version 2002 (Build 12527.20720)*</span></span>

<span data-ttu-id="2da6e-109">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2da6e-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2da6e-111">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2da6e-111">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2da6e-112">Excel</span><span class="sxs-lookup"><span data-stu-id="2da6e-112">Excel</span></span>

- <span data-ttu-id="2da6e-113">ファイルパスが長すぎる場合にファイルを再度開いた後、外部リンクが機能しなくなる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-113">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="2da6e-114">Ctrl + Shift + 方向キーを使用して、Excel ウィンドウが Teams によって共有されている場合に、Excel が応答しなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-114">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="2da6e-115">印刷時にフォーム コントロールのチェックボックスが拡大縮小されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-115">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="2da6e-116">従来の "共有ブック" モードを使用して、ブックの新しいシートに変更を表示しようとすると、クラッシュが発生する可能性があります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-116">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="2da6e-117">フィルター処理されたリストに列を挿入すると、予想よりも長くかかることがあります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-117">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="2da6e-118">数式を開始する @ 記号が暗黙的な交差演算子と見なされるという問題を修正しています。</span><span class="sxs-lookup"><span data-stu-id="2da6e-118">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

### <a name="outlook"></a><span data-ttu-id="2da6e-119">Outlook</span><span class="sxs-lookup"><span data-stu-id="2da6e-119">Outlook</span></span>

- <span data-ttu-id="2da6e-120">ネイティブ Teams クライアントを介した Teams 会議への直接参加を可能にします。</span><span class="sxs-lookup"><span data-stu-id="2da6e-120">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="2da6e-121">Outlook がデータ損失防止ポリシーのヒントを有効にできなかった問題に対処しました。これには、M365 Business Plus プランに参加しているサービスに対して支払いが行われたユーザーに関するヒントがあります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-121">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="2da6e-122">Gmail の認証プロンプトを完了できない場合に、ブラウザーエミュレーションが正しく設定されていないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-122">Addressed an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="2da6e-123">サーバーオペレーティングシステム上の Outlook ユーザーがエラーを表示する原因となった問題に対処しました。 "ウイルス対策の状態: 無効です。"</span><span class="sxs-lookup"><span data-stu-id="2da6e-123">Addressed an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="2da6e-124">このバージョンの Windows は、ウイルス対策の検出をサポートしていますが、ウイルス対策が適切に構成されているにもかかわらず、ウイルス対策が見つかりました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-124">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

### <a name="word"></a><span data-ttu-id="2da6e-125">Word</span><span class="sxs-lookup"><span data-stu-id="2da6e-125">Word</span></span>

- <span data-ttu-id="2da6e-126">クイック印刷を使用して印刷した後に編集しようとしたときに、ドキュメント内の単語の配置が乱れてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-126">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2da6e-127">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2da6e-127">Office Suite</span></span>

- <span data-ttu-id="2da6e-128">この問題は、backstage 内のチャネル名を2020年1月のフォークの新しいチャネル名に更新することによって解決されました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-128">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="2da6e-129">この問題を修正して、デバイスがポリシー管理されている場合、DMS の対象ユーザー API を呼び出すことはありません。</span><span class="sxs-lookup"><span data-stu-id="2da6e-129">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="2da6e-130">単一のトランザクションでアプリを追加または削除すると、不完全な削除がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-130">Resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="2da6e-131">レジストリキー HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth が0に設定されている間にアドインがアクティブ化されると、office ホストが windows でクラッシュしました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-131">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="2da6e-132">この変更により、この問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-132">This change would fix this issue.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-may-12"></a><span data-ttu-id="2da6e-134">バージョン 2002: 5 月12時</span><span class="sxs-lookup"><span data-stu-id="2da6e-134">Version 2002: May 12</span></span>
<span data-ttu-id="2da6e-135">*バージョン 2002 (ビルド 12527.20612)*</span><span class="sxs-lookup"><span data-stu-id="2da6e-135">*Version 2002 (Build 12527.20612)*</span></span>

<span data-ttu-id="2da6e-136">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2da6e-136">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2da6e-138">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2da6e-138">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="2da6e-139">Excel</span><span class="sxs-lookup"><span data-stu-id="2da6e-139">Excel</span></span>

- <span data-ttu-id="2da6e-140">特に非表示ウィンドウで、他の多数のブックへの参照を含むブックを開くと、予想よりも時間がかかることがあります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-140">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="2da6e-141">状況によっては、CSV ファイルを開くのに予想より時間がかかった。</span><span class="sxs-lookup"><span data-stu-id="2da6e-141">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="2da6e-142">Excel は、異なるズームレベルでブックを切り替えるときに、一部の状況でクラッシュすることがあります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-142">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="2da6e-143">範囲に値を書き込む時間が予想より遅くなるという問題を VBA で修正した。</span><span class="sxs-lookup"><span data-stu-id="2da6e-143">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="2da6e-144">色によってフィルター処理された列からコピーしたデータは、適切に貼り付けることができない場合があります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-144">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="2da6e-145">ピボットテーブルを含むシートをコピーした後、Excel がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-145">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="2da6e-146">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-146">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="2da6e-147">グラフ軸の "Value と交差する" プロパティが、ファイルを保存して再度開くときに予期せず変更されるという問題に対処しています。</span><span class="sxs-lookup"><span data-stu-id="2da6e-147">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="2da6e-148">範囲の値と範囲を指定すると、動的な配列として数式が入力されます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-148">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

### <a name="onenote"></a><span data-ttu-id="2da6e-149">OneNote</span><span class="sxs-lookup"><span data-stu-id="2da6e-149">OneNote</span></span>

- <span data-ttu-id="2da6e-150">Localises を使用すると、OneNote のユーザーに対して実行されている一時的な手段の詳細を確認し、同期およびサービスの安定性を向上させることができます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-150">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="2da6e-151">通知を表示します。これにより、OneNote のユーザーに対して実行された一時的な手段の詳細を確認し、同期とサービスの安定性を向上させることができます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-151">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="2da6e-152">OneNote 2016 のバージョン履歴ページの数と同期頻度を一時的に減らすことで、同期およびサービスの安定性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-152">Improved sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="2da6e-153">OneNote 2016 で一時的にごみ箱を無効にすることで、同期およびサービスの安定性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-153">Improved sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="2da6e-154">通常、ごみ箱に送信されるデータをユーザーが削除しようとすると、データを保持するか、完全に削除するかをユーザーに確認するメッセージが表示されます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-154">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="2da6e-155">OneNote 2016 で同期頻度を一時的に調整することで、同期およびサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-155">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="2da6e-156">ユーザーが OneNote 2016 でページに移動するまで、オンラインノートブックに埋め込まれたファイルとイメージのダウンロードを一時的に延期することで、同期およびサービスの安定性が向上します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-156">Improved sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="2da6e-157">OneNote 2016 でアプリ内動画のレコーディングを一時的に無効にすることで、同期およびサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-157">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="2da6e-158">ローカルのノートブックはこの影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="2da6e-158">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="2da6e-159">OneNote 2016 に 50 MB へ埋め込まれた新しい添付ファイルの最大許容サイズが一時的に減少することにより、同期とサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-159">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="2da6e-160">この制限を超えるファイルの場合、ユーザーは OneDrive にファイルをアップロードして、OneNote にリンクを挿入することができます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-160">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

### <a name="outlook"></a><span data-ttu-id="2da6e-161">Outlook</span><span class="sxs-lookup"><span data-stu-id="2da6e-161">Outlook</span></span>

- <span data-ttu-id="2da6e-162">フォルダー ウィンドウの幅が予期せず変更される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-162">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="2da6e-163">Windows update の後に .msg および .oft ファイルを開こうとすると、ユーザーがクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-163">Addressed an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="2da6e-164">大きな HTML メッセージを転送するときに、ユーザーがメッセージ本文の切り捨てを表示する原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-164">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="2da6e-165">この更新プログラムは、メッセージを表示または作成するときに現在の機密ラベルが表示されない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-165">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="2da6e-166">ユーザーが個人の配布リストに電子メールを送信できなくなる原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-166">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2da6e-167">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2da6e-167">PowerPoint</span></span>

- <span data-ttu-id="2da6e-168">改善されたコメントを含むファイルのコピーを開くユーザーに対して、適切なメッセージを中継するための問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-168">Fixed an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="word"></a><span data-ttu-id="2da6e-169">Word</span><span class="sxs-lookup"><span data-stu-id="2da6e-169">Word</span></span>

- <span data-ttu-id="2da6e-170">インストールされている言語によっては、Access と Publisher が正常に起動しない可能性がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-170">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>

- <span data-ttu-id="2da6e-171">編集用に保護されたドキュメントの比較機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-171">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="2da6e-172">2 つのドキュメントを 1 つのドキュメントに結合するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-172">We fixed an issue when merging 2 documents into one document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2da6e-173">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2da6e-173">Office Suite</span></span>

- <span data-ttu-id="2da6e-174">これは、ファイルがクライアントにキャッシュされるときに、プロジェクトアプリがネットワークをブロックしないようにするための修正です。</span><span class="sxs-lookup"><span data-stu-id="2da6e-174">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>

- <span data-ttu-id="2da6e-175">内部操作でエラーが発生し、ログに記録して続行するのではなく、例外がスローされるという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-175">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="2da6e-176">影響を受けるユーザーは、更新プログラムの受信をブロックされることはありません。</span><span class="sxs-lookup"><span data-stu-id="2da6e-176">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="2da6e-177">この変更により、リボンでスケッチアウトラインが正しく動作するようになります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-177">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="2da6e-178">特定のプロキシ構成を使用してオンプレミスの場所からファイルを開くときに問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-178">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="2da6e-179">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-179">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="2da6e-180">この更新プログラムを実行すると、PATH 環境変数で指定されている場所を検索することによって検出された参照を含む Visual Basic for Applications プロジェクトが、実行時に適切に検出されず、VBA ランタイムエラーが発生するという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-180">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="2da6e-181">この更新プログラムは、ラベルポリシーでヘッダーまたはフッターまたはウォーターマークが適用されている場合に、ラベルを変更または削除することによって、機密ラベルの適用時に255文字を超える文字が挿入されていると、Microsoft Word のエラーを修正します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-181">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

- <span data-ttu-id="2da6e-182">Office のハンドオフセッション中のクラッシュを回避し、ユーザー操作での信頼性を向上させる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-182">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>  

- <span data-ttu-id="2da6e-183">このバグは、enhanced configuration service (ECS) url エンドポイントを更新します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-183">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="2da6e-184">この新しいエンドポイントを呼び出すと、ECS からのフェッチの成功率は高くなります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-184">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-april-14"></a><span data-ttu-id="2da6e-186">バージョン 2002: 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2da6e-186">Version 2002: April 14</span></span>
<span data-ttu-id="2da6e-187">*バージョン 2002 (ビルド 12527.20442)*</span><span class="sxs-lookup"><span data-stu-id="2da6e-187">*Version 2002 (Build 12527.20442)*</span></span>

<span data-ttu-id="2da6e-188">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2da6e-188">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


### <a name="feature-updates"></a><span data-ttu-id="2da6e-189">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2da6e-189">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="2da6e-190">Excel</span><span class="sxs-lookup"><span data-stu-id="2da6e-190">Excel</span></span>

- <span data-ttu-id="2da6e-191">**複数の値を返す式を入力する:** 複数の値を返す式をすばやく入力できるようになりました。隣接するセルに自動的に入力されます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-191">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="2da6e-192">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-192">Learn more</span></span>](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="2da6e-193">**6 つの強力な機能:** スプレッドシートを強化する 6 つの新しい関数が追加されました。FILTER、SORT、SORTBY、UNIQUE、SEQUENCE、RANDARRAY です。</span><span class="sxs-lookup"><span data-stu-id="2da6e-193">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span>  [<span data-ttu-id="2da6e-194">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-194">Learn more</span></span>](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="2da6e-195">**左を見て、右を見て... XLOOKUP をご利用いただけます!:** XLOOKUP を使えば、表や範囲内で必要なものは何でも見つけられます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-195">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span>  [<span data-ttu-id="2da6e-196">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-196">Learn more</span></span>](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2da6e-198">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2da6e-198">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2da6e-199">Excel</span><span class="sxs-lookup"><span data-stu-id="2da6e-199">Excel</span></span>

- <span data-ttu-id="2da6e-200">Word または PowerPoint に埋め込まれたブックをもう一度開くと、場合によっては Excel がクラッシュする可能性があります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-200">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="2da6e-201">CSV ファイルとして保存する場合、Excel はすべての列を 1 つの列にマージする場合があります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-201">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="2da6e-202">保護されたシートの範囲で Range.ClearContents を使用すると、予想よりも時間がかかる場合があります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-202">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="2da6e-203">[印刷プレビュー] に表示されるときのフォーム コントロール内のテキストの拡大縮小に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-203">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="2da6e-204">リボンを操作する VBA マクロは、ScreenUpdating が True に設定されていると予期せず実行される場合があります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-204">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="2da6e-205">ソース ブックが閉じていると、外部リンクが塗りつぶし(下方向に塗りつぶし、全体に塗りつぶしなど) 時に更新されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-205">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is closed.</span></span>

- <span data-ttu-id="2da6e-206">VBA の Application.Evaluate が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-206">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="2da6e-207">テンプレートからグラフを作成するときに発生するパフォーマンスの問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-207">Addressed a performance issue when creating charts from templates.</span></span>


### <a name="outlook"></a><span data-ttu-id="2da6e-208">Outlook</span><span class="sxs-lookup"><span data-stu-id="2da6e-208">Outlook</span></span>

- <span data-ttu-id="2da6e-209">一部のシナリオで、グループ ヘッダーが予期せず拡張される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-209">Addressed an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="2da6e-210">特定の検索結果を選択すると、ユーザーがクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-210">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="2da6e-211">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-211">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="2da6e-212">[添付ファイル ​​ツール] に [クラウドに保存] ボタンが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-212">Addressed an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2da6e-213">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2da6e-213">PowerPoint</span></span>

- <span data-ttu-id="2da6e-214">コピーと貼り付けのシナリオを改善しました。PowerPoint スライドでの図形のコピーと、ループ内の他のスライドへの貼り付けが例外で失敗する場合があります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-214">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="2da6e-215">Project</span><span class="sxs-lookup"><span data-stu-id="2da6e-215">Project</span></span>

- <span data-ttu-id="2da6e-216">以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-216">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="2da6e-217">[無効化] ボタンを介してタスクが非アクティブ化/アクティブ化された場合に、ProjectBeforeTaskChange イベントが検出しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-217">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

### <a name="word"></a><span data-ttu-id="2da6e-218">Word</span><span class="sxs-lookup"><span data-stu-id="2da6e-218">Word</span></span>

- <span data-ttu-id="2da6e-219">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-219">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="2da6e-220">表内のテキストに合わせる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-220">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="2da6e-221">水平線の挿入が短くなく、中央に配置されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-221">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-march-10"></a><span data-ttu-id="2da6e-223">バージョン 2002: 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="2da6e-223">Version 2002: March 10</span></span>
<span data-ttu-id="2da6e-224">*バージョン 2002 (ビルド 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="2da6e-224">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="2da6e-225">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2da6e-225">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="2da6e-227">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="2da6e-227">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2da6e-228">Access</span><span class="sxs-lookup"><span data-stu-id="2da6e-228">Access</span></span>

- <span data-ttu-id="2da6e-229">**リンク テーブルをすばやく見つける:** 新しい検索ボックスを使用すると、リンク テーブルを簡単に見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-229">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="2da6e-230">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-230">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="2da6e-231">Excel</span><span class="sxs-lookup"><span data-stu-id="2da6e-231">Excel</span></span>

- <span data-ttu-id="2da6e-232">**\@メンションを使用してユーザーの注意を引く:** コメントで @メンションを使うと、仕事仲間による入力が必要な場合にそのユーザーに知らせることができます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-232">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="2da6e-233">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-233">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="2da6e-234">**探しているものを見つける:** コマンド、ユーザー、ファイル、写真、Web の記事などを検索できます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-234">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="2da6e-235">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-235">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="2da6e-236">**あらましを描く:** ブック内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="2da6e-236">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="2da6e-237">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-237">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="2da6e-238">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-238">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="2da6e-239">**ブラウザーへのバウンスは不要:** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定することができます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-239">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="2da6e-240">**残っている作業に集中する:** [解決] を選択して、コメントを折りたたみ、開いているアイテムを目立たせます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-240">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="2da6e-241">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-241">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="2da6e-242">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-242">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="2da6e-243">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザーがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-243">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="2da6e-244">**データ ビジュアライザー アドイン:** Excel から Visio フローチャートをすばやく作成します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-244">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="2da6e-245">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-245">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="2da6e-246">**すぐに読んで返信する**: ブックを開かずに、メールからコメントやメンションに直接返信します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-246">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="2da6e-247">**ブックの統計を取得する:** ブックの統計情報にはブックの内容の概要が示されるので、コンテンツをより簡単に見つけ出せます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-247">**Get stats on your workbook:** Workbook Statistics provides an overview of the content of a workbook, to help you more easily discover its contents.</span></span>





### <a name="outlook"></a><span data-ttu-id="2da6e-248">Outlook</span><span class="sxs-lookup"><span data-stu-id="2da6e-248">Outlook</span></span>



- <span data-ttu-id="2da6e-249">\*\* Outlook に LinkedIn ネットワークを接続する:\*\* LinkedIn アカウントを Microsoft アカウントに安全に接続して、LinkedIn プロファイルからの情報を [連絡先カード] に直接表示できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-249">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="2da6e-250">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-250">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="2da6e-p119">**すべての暗号化オプションを 1 か所に集約:** [オプション] > [暗号化] の順に移動するだけで、電子メール メッセージを保護する方法を選択できます。[詳細情報](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="2da6e-p119">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="2da6e-253">**テナント管理者によって定義されたアクセス許可を使用して、Outlook の [リンクの挿入] メニューでリンクを挿入する:** Outlook で最近使用されたリンクの挿入 (MRU) のリンクでは、既にそれに対するアクセス許可を持つユーザーのみに動作したリンクが挿入されます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-253">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="2da6e-254">これは、ドキュメントへのアクセス権の付与を求めるユーザー間でのメールの行き来をしばしば引き起こします。</span><span class="sxs-lookup"><span data-stu-id="2da6e-254">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="2da6e-255">このエクスペリエンスが更新されましたので、テナント管理者によって設定される既定のアクセス許可を使用し、リンクを挿入できるようになりました。MSIT の場合、これは「組織は編集可」なので、この方法で共有されるリンクを受信するすべての内部ユーザーもアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-255">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="2da6e-256">**スペルチェックの問題や入力ミスで検索する:** スペルが一致しない場合でも何を検索しているか Outlook が探します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-256">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="2da6e-257">**フィッシング メールの見分けが簡単に:** スパムとフィッシングのメッセージの外観が他とは異なるので、簡単に見分け、受信トレイから削除できます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-257">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="2da6e-258">**攻撃に対する高度な保護:** Office 365 Advanced Threat Protection を用いると、メールの件名、添付メッセージ、署名されたメッセージ、ネットワーク パスなどの範囲内のハイパーリンクを利用した攻撃から保護されます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-258">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="2da6e-259">**自分で描いて表現しましょう:** 画像の上に走り書きするか、描画キャンバスを追加して、インクを用いて自分の考えを送信します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-259">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="2da6e-260">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-260">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="2da6e-261">**検索結果で関連メッセージを確認する:** Outlook では検索条件を分析し、最も関連性の高いメール メッセージを検索結果の上部に表示します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-261">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="2da6e-262">また、[上位の結果] セクションには、すべての結果が日付順に表示されます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-262">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="2da6e-263">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-263">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- <span data-ttu-id="2da6e-264">**場所の候補を取得する:** 予定や会議をスケジュールするときに、[場所] に入力すると、会議室、住所、およびその他の最新の場所が提示されます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-264">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="2da6e-265">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-265">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="2da6e-266">**より多くのメッセージを画面に収める:** [表示] > [より狭い文字間隔を使用] の順に選択し、メッセージの間隔を調整します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-266">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="2da6e-267">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-267">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="2da6e-268">**異なる明るさでメッセージを表示する:** [太陽] または [月] のボタンを使用して、閲覧ウィンドウの明るい背景と暗い背景を切り替えます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-268">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="2da6e-269">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-269">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)



### <a name="powerpoint"></a><span data-ttu-id="2da6e-270">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2da6e-270">PowerPoint</span></span>

- <span data-ttu-id="2da6e-271">**PowerPoint におけるリアルタイム コラボレーションが高速に:** PowerPoint でリアルタイム コラボレーションを高速で行えます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-271">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="2da6e-272">**新しい文書校正ツール:** 記述する内容についてストレスを感じる必要はありません。</span><span class="sxs-lookup"><span data-stu-id="2da6e-272">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="2da6e-273">PowerPoint で、文法や書き方の推奨事項が提示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-273">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="2da6e-274">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-274">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)


- <span data-ttu-id="2da6e-275">**ライブ キャプションと字幕:** 発表者の言葉が、キャプションまたは選択した言語での字幕として自動的に画面に表示されます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-275">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="2da6e-276">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-276">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="2da6e-277">**手書きの数式の自動書式設定:** 手書きの数式を標準の文字に変換することができます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-277">**You compute, we format:** We change hand-drawn math expressions into standard characters.</span></span> <span data-ttu-id="2da6e-278">変換を開始するには、[インクから数式] を選択して、手書きのメモを選択します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-278">Just choose Ink to Math and select your handwritten notes to get started.</span></span> [<span data-ttu-id="2da6e-279">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-279">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="2da6e-280">**探しているものを見つける:**[検索] ボックスを使用して、テキスト、コマンド、ヘルプなどを探します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-280">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="2da6e-281">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-281">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="2da6e-282">**欠落しているスライド タイトルを見つけて修正する:** スライド タイトルは、ピッチにパンチを加え、すべてのユーザーがスライドにアクセスできるようにします。</span><span class="sxs-lookup"><span data-stu-id="2da6e-282">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="2da6e-283">アクセシビリティ ​​チェックは、タイトルがない場所を表示します。これにより、タイトルを簡単に追加できます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-283">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="2da6e-284">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-284">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="2da6e-285">**あらましを描く:** プレゼンテーション内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="2da6e-285">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="2da6e-286">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-286">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="2da6e-287">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-287">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="2da6e-288">**ブラウザーへのバウンスは不要:** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定することができます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-288">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="2da6e-289">**図を SVG として保存する:** グラフ、図形、その他の図を、サイズ変更しても画質が低下しないスケーラブル ベクター グラフィックとして保存できます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-289">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="2da6e-290">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-290">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="2da6e-291">**配布資料にスライド番号を印刷する:** スライド番号は配布資料に自動的に含まれます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-291">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="2da6e-292">それらをオンのままにするか、オフにするか、選択します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-292">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="2da6e-293">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-293">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="2da6e-294">**インクを瞬時に再生:** スライドで手描き入力する場合は、スライド ショー中にアニメーションの再生を適用して、インクの実際の描画が再生されるようにします。</span><span class="sxs-lookup"><span data-stu-id="2da6e-294">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="2da6e-295">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-295">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="2da6e-296">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-296">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

- <span data-ttu-id="2da6e-297">**プレゼンテーションの最適化:** アクセシビリティ チェックを使用すると、スクリーン リーダーを考慮に入れて、スライド上のオブジェクトを配置することができます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-297">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="2da6e-298">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-298">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="2da6e-299">**より安全なビデオ エクスペリエンス:** セキュリティの強化は、より安全なオンライン ビデオ エクスペリエンスを意味します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-299">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="2da6e-300">**再利用しませんか?:** 作成した、または他のユーザーと共有しているスライドを再利用して時間を節約します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-300">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="2da6e-301">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-301">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- <span data-ttu-id="2da6e-302">**手書きのインクを図形やテキスト、または Office 365 の PowerPoint での数式に変換する:** フリーフォームのインクを Office の図形、テキスト、数式に数ストロークで変換します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-302">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="2da6e-303">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-303">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="2da6e-304">**インクで素晴らしいスライドを作成する:** インクを標準的な図形やテキストに変換してから、PowerPoint デザイナーの洗練されたスライドのデザイン アイデアを活用できます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-304">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="2da6e-305">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-305">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

### <a name="visio"></a><span data-ttu-id="2da6e-306">Visio</span><span class="sxs-lookup"><span data-stu-id="2da6e-306">Visio</span></span>

- <span data-ttu-id="2da6e-307">**犯行現場に戻る:** [犯罪現場] 調査テンプレートで新しい [証拠]、[室内]、および [屋外] のステンシルを使用して、犯罪現場を詳細に再現します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-307">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

- <span data-ttu-id="2da6e-308">**Excel で洗練された Visio 図を作成する:** ワークシートにデータを入力して、フロー チャートまたは組織図を作成します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-308">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="2da6e-309">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-309">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="2da6e-310">Word</span><span class="sxs-lookup"><span data-stu-id="2da6e-310">Word</span></span>

- <span data-ttu-id="2da6e-311">**Editor for Resume が LinkedIn 履歴書アシスタントに参加する:** Editor for Resume では履歴書に特化した文法とスタイルのチェックを選択できます。この機能は、より正確かつ専門的に作成するの役立ちます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-311">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="2da6e-312">**3D オブジェクトのマージによって引き起こされるドキュメント破損の問題を修正しました。:** 3D オブジェクトのマージによって引き起こされるドキュメント破損の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-312">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="2da6e-313">**探しているものを見つける:**[検索] ボックスを使用して、テキスト、コマンド、ヘルプなどを探します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-313">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="2da6e-314">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-314">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="2da6e-315">**鮮やかな色で共同作業する:** コメントや変更内容のカラー コードが共同作成者によって指定され、共同作成者のうちのだれによって行われたかが簡単にわかります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-315">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="2da6e-316">**マクロ有効文書を共同作業で編集する:** 文書ファイルを OneDrive for Business に保存し、リアルタイムで共同作成者は編集できます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-316">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

- <span data-ttu-id="2da6e-317">**共同編集の改善**: 変更を追跡したドキュメントで共同編集を行う際の Word のパフォーマンスが改善されました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-317">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="2da6e-318">**自分の気分を表現するアイコンの追加:** 300 個以上の新しいアイコンが追加されました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-318">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="2da6e-319">[挿入]、[アイコン] の順に検索してください。</span><span class="sxs-lookup"><span data-stu-id="2da6e-319">Find them at Insert > Icons.</span></span> [<span data-ttu-id="2da6e-320">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-320">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="2da6e-321">**他のユーザーがすばやく変更を確認する:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-321">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="2da6e-322">**あらましを描く:** ドキュメント内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="2da6e-322">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="2da6e-323">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-323">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="2da6e-324">**精度による消去:** 手描き入力の小さな不備を修正するのに、2 つのサイズの消しゴムから選択できます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-324">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="2da6e-325">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-325">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="2da6e-326">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-326">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="2da6e-327">**ブラウザーへのバウンスは不要:** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定することができます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-327">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="2da6e-328">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-328">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="2da6e-329">**他のユーザーがすばやく変更を確認する:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-329">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="2da6e-330">**共同編集の改善:** 共同編集時の信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-330">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="2da6e-331">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-331">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="2da6e-332">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-332">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="2da6e-333">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-333">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="2da6e-334">**より安全なビデオ エクスペリエンス:** セキュリティの強化は、より安全なオンライン ビデオ エクスペリエンスを意味します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-334">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="2da6e-335">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-335">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="2da6e-336">**図形を画像として保存する:** 簡単なクリック操作で図形、アイコン、その他のオブジェクトを画像ファイルとして保存し、別の場所で再利用することができます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-336">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="2da6e-337">詳細情報</span><span class="sxs-lookup"><span data-stu-id="2da6e-337">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)



[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2da6e-340">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2da6e-340">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2da6e-341">Access</span><span class="sxs-lookup"><span data-stu-id="2da6e-341">Access</span></span>

- <span data-ttu-id="2da6e-342">この更新プログラムにより、更新クエリが実行されるか、SQL で UPDATE ステートメントが使用されるときに &quot;クエリは破損しています&quot; というエラーを発生させる場合のある Microsoft Access の問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-342">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

- <span data-ttu-id="2da6e-343">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-343">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="2da6e-344">この更新プログラムでは、ADODB を使用する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-344">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="2da6e-345">VB コードのれコーター オブジェクトがエラーを誤って報告することがあります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-345">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="2da6e-346">Access テンプレートは、データベース内の添付ファイル列のエラーを発生させることがなくなりました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-346">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="2da6e-347">テンプレートのインスタンス化後に、データベースに添付ファイル フィールドを追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-347">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="2da6e-348">Excel</span><span class="sxs-lookup"><span data-stu-id="2da6e-348">Excel</span></span>

- <span data-ttu-id="2da6e-349">署名の名前を変更したときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-349">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="2da6e-350">この変更は、ソフトウェア レンダリングを活用することにより、特定の Intel グラフィック ドライバーの問題を回避します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-350">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="2da6e-351">はみ出している列挙が含まれるセルで区切り位置を指定するとクラッシュが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-351">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="2da6e-352">この更新によって、数式バーに予期したのとは異なるフォントでテキストが表示される原因となっていた問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-352">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="2da6e-353">一部のロケールにおいて、[Text to Column] 機能が失敗することがあります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-353">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="2da6e-354">非表示の名前付き範囲にアクセスすると、ユーザーにエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-354">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="2da6e-355">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-355">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="2da6e-356">スクロール後にセルを選択すると間違ったセルが選択されることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-356">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="2da6e-357">信頼されていないネットワーク共有から保護されたファイルを編集する際に、Excel にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-357">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="2da6e-358">一部のローカライズにおいて、[Text to Column] 機能が失敗することがあります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-358">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="2da6e-359">非表示の名前付き範囲にアクセスすると、ユーザーにエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-359">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="2da6e-360">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-360">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="2da6e-361">一部のユーザーが埋め込みオブジェクトとリンク オブジェクト (OLE) で経験する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-361">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="2da6e-362">ピボット グラフの右クリック メニューを修正して、[詳細の表示] オプションを有効にしました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-362">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="2da6e-363">ブックが開かれていない状態で最近使用したファイルを検索するときに、クラッシュを発生させる原因となっていた可能性がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-363">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="2da6e-364">ブックで外部リンクがある場合に複数のポップアップ ウィンドウで一部のユーザーに生じる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-364">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="2da6e-365">コンテキスト メニューのコメント コマンドが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-365">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="2da6e-366">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-366">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="2da6e-367">CUBEVALUE 関数が間違った結果を返すことがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-367">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="2da6e-368">Outlook</span><span class="sxs-lookup"><span data-stu-id="2da6e-368">Outlook</span></span>

- <span data-ttu-id="2da6e-369">検索に関するフィードバックのエクスペリエンスで終了する原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-369">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="2da6e-370">ユーザーがクラウド設定を取得する際に Outlook がフリーズする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-370">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="2da6e-371">検索ボックスが高 DPI モードで不適切に表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-371">Addressed an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="2da6e-372">ユーザーが Outlook プロセスでメモリ リークを観測する原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-372">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="2da6e-373">状況によっては、表示された SMTP アドレスと一致しないアドレスに送信されたメールがユーザーに表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-373">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="2da6e-374">この変更により、メッセージ ヘッダーに複数行の件名を表示できる機能が復元されます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-374">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="2da6e-375">WebDAV の場所にファイルを保存できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-375">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="2da6e-376">SMIME アルゴリズムの選択に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-376">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="2da6e-377">サードパーティ製アプリケーションがメールを送信できない原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-377">Addressed an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="2da6e-378">アカウント作成コンテキストからサポートに連絡しようとすると、ユーザーに [&quot;OK&quot;] ボタンのある空のメッセージ ボックスが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-378">Addressed an issue that caused users to see an empty message box with an &quot;OK&quot; button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="2da6e-379">ユーザーがプロフィールの作成中にクラッシュを発生させる原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-379">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="2da6e-380">同期のスライダーが小さい設定に設定されている場合でも、Outlook で予期せずすべてのメールが同期される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-380">Addressed an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="2da6e-381">黒のテーマを持つユーザーが &quot;[差出人]&quot; ドロップダウンを表示すると、白色の背景に白いテキストが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-381">Addressed an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span>

- <span data-ttu-id="2da6e-382">ユーザーがアカウントのセットアップをキャンセルするときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-382">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="2da6e-383">署名の名前を変更したときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-383">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="2da6e-384">フラグ付きアイテムの強調表示を無効にするオプションが一部のシナリオで無視される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-384">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="2da6e-385">ユーザーが [ルール] ダイアログを開くと、「&quot;このコンピューターのルールは、Microsoft Exchange のルールと異なります&quot;」というメッセージが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-385">Addressed an issue that caused users to see a &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="2da6e-386">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-386">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="2da6e-387">非常に長い Outlook セッションでメモリ リークを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-387">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="2da6e-388">複数のウィンドウで同じアイテムを表示するとクラッシュする場合がある問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-388">Addressed an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="2da6e-389">キーボード ショートカットを使用してメールボックス フォルダーを操作すると、ユーザーに顕著な遅延が発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-389">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="2da6e-390">ユーザーが定期的な予定表の一部のインスタンスを開けない原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-390">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="2da6e-391">Exchange 2010 サーバー上にメールボックスを持つユーザーが、予定表の項目に添付ファイルを追加するときに生じる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-391">Addressed an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="2da6e-392">ユーザーがデジタル署名されたメッセージに返信するときに生じる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-392">Addressed an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="2da6e-393">会議の [場所] フィールドが予期せず更新される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-393">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="2da6e-394">会議の [場所] フィールドにあるコンマがセミコロンになる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-394">Addressed an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="2da6e-395">会議をクリアした後、会議の場所が予期せずに会議に追加される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-395">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="2da6e-396">ブラジルのタイムゾーンで設定された会議や予定に関連する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-396">Addressed issues relating to meetings and appointments set in the Brazilia time zone.</span></span>

- <span data-ttu-id="2da6e-397">[アクセシビリティ チェック] ペインを閉じた後に &quot;S&quot; キーを押すと、メールが予期せず送信されたようにユーザーに表示される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-397">Addressed an issue that caused users to see mails unexpectedly send when pressing the &quot;S&quot; key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="2da6e-398">これにより、Python による添付ファイルもブロックされるよう、Outlook の添付ファイルのブロック ロジックが更新されました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-398">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="2da6e-399">Web アドインがデジタル著作権管理 (DRM) メッセージにアクセスする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-399">Addressed an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="2da6e-400">ユーザーがプロフィールの作成中にクラッシュを発生させる原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-400">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="2da6e-401">署名の名前を変更したときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-401">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2da6e-402">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2da6e-402">PowerPoint</span></span>

- <span data-ttu-id="2da6e-403">Shape.Paste メソッドを使用する際に発生する問題を解決しました。Shape.Paste メソッドを使用して図形をコピーして貼り付けるときに、貼り付けられた図形の選択内容が変更するという問題です。</span><span class="sxs-lookup"><span data-stu-id="2da6e-403">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="2da6e-404">従来の PPT コメントでコンテキスト メニューを使用するときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-404">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

### <a name="project"></a><span data-ttu-id="2da6e-405">Project</span><span class="sxs-lookup"><span data-stu-id="2da6e-405">Project</span></span>

- <span data-ttu-id="2da6e-406">読み取り専用のプロジェクトを開いたときに複数のメッセージを取得する可能性があるという問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-406">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="2da6e-407">作業時間固定タイプの達成率 100% のタスクで、達成率が誤って 100% 未満に計算される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-407">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

- <span data-ttu-id="2da6e-408">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-408">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="2da6e-409">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-409">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="2da6e-410">Word</span><span class="sxs-lookup"><span data-stu-id="2da6e-410">Word</span></span>

- <span data-ttu-id="2da6e-411">既存のファイルを保存すると [名前を付けて保存] ダイアログが必ず表示され、ファイルは実際には保存されない場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-411">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="2da6e-412">文書パーツ オーガナイザーに無効なアラートが表示される場合があります。&quot;スタイル、文書パーツを変更しました。&quot;</span><span class="sxs-lookup"><span data-stu-id="2da6e-412">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2da6e-413">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2da6e-413">Office Suite</span></span>

- <span data-ttu-id="2da6e-414">この変更により、マーカー付きの一部の散布図の表示が遅くなる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-414">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="2da6e-415">この変更では、Intel Integrated GPU を使用するグラフィック アダプターに関して報告された問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-415">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="2da6e-416">ODT と GPO の更新期限設定で、相対期限の設定後、初回のみしか機能しないバスが修正されました。修正により、2 回目以降の更新プログラムで相対期限を使用きるようになりました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-416">Fixed a bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="2da6e-417">Office の更新プログラムが、意図したソース (ローカル共有、ネットワーク共有、構成マネージャー
で提供される場所など) からではなく、予期せずに Office CDN からファイルをダウンロードする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-417">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="2da6e-418">同じ SharePoint ライブラリから Word/Excel/PowerPoint で複数のドキュメントが開かれている場合、最初に開いたドキュメントのみがポリシー コンプライアンスでスキャンされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-418">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-february-11"></a><span data-ttu-id="2da6e-420">バージョン 1908: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="2da6e-420">Version 1908: February 11</span></span>
<span data-ttu-id="2da6e-421">*バージョン 1908 (ビルド 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="2da6e-421">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="2da6e-422">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2da6e-422">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2da6e-424">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2da6e-424">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2da6e-425">Excel</span><span class="sxs-lookup"><span data-stu-id="2da6e-425">Excel</span></span>

- <span data-ttu-id="2da6e-426">この更新プログラムは、VBA を使用してグラフのヘッダー/フッターに画像を追加するたびにエラーが発生する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-426">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="2da6e-427">グループ ボックス コントロールの境界線が印刷プレビューまたは印刷時に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-427">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="2da6e-428">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-428">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="2da6e-429">グラフを含むブックを保存すると、グラフ ヘッダーの画像のファイル サイズが大きくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-429">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="2da6e-430">選択範囲を相互参照ブックと同期させ続けることにより、相互参照ブックの DBCS 文字が破損する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-430">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="2da6e-431">自動調整を使用して行の高さを調整するときにチェック ボックスのコントロールが縮小される可能性があるという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-431">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="2da6e-432">Outlook</span><span class="sxs-lookup"><span data-stu-id="2da6e-432">Outlook</span></span>

- <span data-ttu-id="2da6e-433">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-433">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="2da6e-434">競合メッセージの処理中にユーザーに同期エラーが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-434">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="2da6e-435">Outlook の起動時にユーザーが [プロファイルの読み込み中] 画面でハングアップする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-435">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="2da6e-436">ビューを変更すると、断続的なクラッシュが発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-436">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="2da6e-437">Citrix 環境で 30 件を超える予定表を表示したときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-437">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="2da6e-438">[こちら](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)は、以前のバージョンで文書化された個々の KB です。</span><span class="sxs-lookup"><span data-stu-id="2da6e-438">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="2da6e-439">ユーザーが OST と同期している共有予定表フォルダーに問題があり、これらのフォルダーを操作しようとするとアクセス許可エラーが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-439">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2da6e-440">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2da6e-440">PowerPoint</span></span>

- <span data-ttu-id="2da6e-441">PowerPoint スライドでのコピーと貼り付けのシナリオである図形のコピーを改善しました。ループ内の他のスライドに貼り付けると例外で失敗する場合があります。</span><span class="sxs-lookup"><span data-stu-id="2da6e-441">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="2da6e-442">共同作業ユーザー間のパフォーマンスが低下する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-442">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="2da6e-443">増分で開くファイルに、複数のメディア ストリームが埋め込まれたスライドが含まれている場合に発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-443">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="2da6e-444">PowerPoint の初回起動時に、信頼されていないアドインに対してセキュリティ警告メッセージ バーが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-444">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="2da6e-445">プロジェクト</span><span class="sxs-lookup"><span data-stu-id="2da6e-445">Project</span></span>

- <span data-ttu-id="2da6e-446">基本カレンダーが変更されたときにリソース カレンダーが更新されないために、実際の作業がタイムシートとプロジェクト計画の間で異なる場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-446">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="2da6e-447">Word</span><span class="sxs-lookup"><span data-stu-id="2da6e-447">Word</span></span>

- <span data-ttu-id="2da6e-448">非推奨の API から移動することにより、Word でクラッシュが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-448">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2da6e-449">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2da6e-449">Office Suite</span></span>

- <span data-ttu-id="2da6e-450">この変更は、破損したファイルを開いた後の画像の正しいレンダリングに対処します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-450">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-january-14"></a><span data-ttu-id="2da6e-452">バージョン 1908: 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="2da6e-452">Version 1908: January 14</span></span>
<span data-ttu-id="2da6e-453">*バージョン 1908 (ビルド 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="2da6e-453">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="2da6e-454">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2da6e-454">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="2da6e-456">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="2da6e-456">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2da6e-457">Excel</span><span class="sxs-lookup"><span data-stu-id="2da6e-457">Excel</span></span>

- <span data-ttu-id="2da6e-458">ドキュメント タイトルのオランダ語の KeyTip が Alt-G に変更されました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-458">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="2da6e-459">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-459">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="2da6e-460">アドインによって開かれた WPF (Windows Presentation Foundation) フォームのコンボ ボックスからアイテムを選ぶことができない問題が発生しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-460">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="2da6e-461">Outlook</span><span class="sxs-lookup"><span data-stu-id="2da6e-461">Outlook</span></span>

- <span data-ttu-id="2da6e-462">キーボード ショートカットを使用してメールボックス フォルダーを操作すると、ユーザーに顕著な遅延が発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-462">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="2da6e-463">代替送信者を使用しているときに、ポリシーのヒントが表示されない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-463">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="2da6e-464">プレゼンス情報を更新するときに、断続的なクラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-464">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2da6e-465">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2da6e-465">PowerPoint</span></span>

- <span data-ttu-id="2da6e-466">スライドを 1 つのプレゼンテーションから別のプレゼンテーションにコピーすると、重複したマスターが作成される可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-466">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>
- <span data-ttu-id="2da6e-467">最新のコメントを含むファイルを、サポートされていないバージョンで開くと黄色の警告が表示されます</span><span class="sxs-lookup"><span data-stu-id="2da6e-467">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

### <a name="office-suite"></a><span data-ttu-id="2da6e-468">Office スイート</span><span class="sxs-lookup"><span data-stu-id="2da6e-468">Office Suite</span></span>

- <span data-ttu-id="2da6e-469">Office の更新メッセージが、異なる言語で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-469">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="2da6e-470">今後、Office の更新メッセージは Windows の表示言語と一致します。</span><span class="sxs-lookup"><span data-stu-id="2da6e-470">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="2da6e-471">ユーザーが管理者ではなく、システム アカウントにネットワーク接続が確立されていない場合に、更新プログラムが適用されない問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="2da6e-471">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

> [!NOTE]
> <span data-ttu-id="2da6e-473">Office の使用で問題がある場合は、[Microsoft の回答フォーラム](https://answers.microsoft.com/)に関するページまたは「[Microsoft Tech Community](https://techcommunity.microsoft.com/)」に質問を投稿するか、[サポート](https://support.microsoft.com/contactus)に問い合わせてサポートを受けることができます。</span><span class="sxs-lookup"><span data-stu-id="2da6e-473">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
