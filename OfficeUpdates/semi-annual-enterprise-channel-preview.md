---
title: 2020 年の半期エンタープライズ チャネル (プレビュー) リリースのリリース ノート
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Microsoft 365 Apps 用の 2020 年の半期チャネル リリース (対象指定) のリリース ノートを IT 担当者に提供します
ms.openlocfilehash: b8c02c43cc0c510bb6d64cb66c563e600961c3f7
ms.sourcegitcommit: 34bca539ddfe0e06b772aaa294f4e992630b2a41
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/28/2021
ms.locfileid: "50032304"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview"></a><span data-ttu-id="3f580-103">半期エンタープライズ チャネル (プレビュー) のリリース ノート</span><span class="sxs-lookup"><span data-stu-id="3f580-103">Release notes for Semi-Annual Enterprise Channel (Preview)</span></span>

<span data-ttu-id="3f580-104">このリリース ノートには、半期エンタープライズ チャネル (プレビュー) の更新プログラムに含まれる新機能と、セキュリティ以外の更新プログラムに関する情報が記載されています。対象となるのは、Microsoft 365 Apps for enterprise、Microsoft 365 Apps for business、および Project と Visio のデスクトップ アプリのサブスクリプション版です。</span><span class="sxs-lookup"><span data-stu-id="3f580-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="3f580-105">現在、Microsoft 365 Apps の更新プログラム チャネルに、新しい更新プログラム チャネル (月次エンタープライズ チャネル) の追加や既存の更新プログラム チャネル名の変更など、いくつかの変更を進めています。</span><span class="sxs-lookup"><span data-stu-id="3f580-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="3f580-106">詳細については、[こちらの記事](https://go.microsoft.com/fwlink/p/?linkid=2127441)を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3f580-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>


## <a name="version-2008-january-12"></a><span data-ttu-id="3f580-107">バージョン 2008: 1 月 12 日</span><span class="sxs-lookup"><span data-stu-id="3f580-107">Version 2008: January 12</span></span>
<span data-ttu-id="3f580-108">*バージョン 2008 (ビルド 13127.21064)*</span><span class="sxs-lookup"><span data-stu-id="3f580-108">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="3f580-109">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f580-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="3f580-111">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="3f580-111">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3f580-112">Excel</span><span class="sxs-lookup"><span data-stu-id="3f580-112">Excel</span></span>

- <span data-ttu-id="3f580-113">読み取り専用のブックを開いたときに、ピボット テーブルのデータが更新されなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-113">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="3f580-114">この変更により、次の問題が修正されます: OneDrive ローカル同期フォルダーからファイルを挿入すると、Excel の [オブジェクトの挿入] に正しいアイコンが表示されない。</span><span class="sxs-lookup"><span data-stu-id="3f580-114">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="3f580-115">共同編集のときに、新しいバージョンのファイルに関する通知が誤って送信される可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-115">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="3f580-116">Overwrite モードで IME を使用するときに、余計な文字を誤って前に進めてしまうという編集に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-116">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="3f580-117">リアルタイム データをマルチスレッドの再計算機能と組み合わせて使用するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-117">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="3f580-118">特定の Windows セキュリティのエクスプロイト保護設定 (SimExec、CallerCheck) を使用している場合に、Excel の起動に失敗したり、予期せず終了したりしてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-118">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


### <a name="outlook"></a><span data-ttu-id="3f580-119">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f580-119">Outlook</span></span>

- <span data-ttu-id="3f580-120">下書きに保存したときに SmartLinks の書式設定が失われるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-120">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="3f580-121">ポリシーを上書きするときに、正当化テキストをカスタマイズする方法をユーザーに提供してしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-121">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="3f580-122">OFT ファイルとして保存するときに、中国語の文字が疑問符に変更されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-122">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="3f580-123">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f580-123">PowerPoint</span></span>

- <span data-ttu-id="3f580-124">Slide.Shapes.AddMediaObject2 が従来のビデオ形式 (.MPG-1、Mpeg-2) で予期せず終了してしまう可能性がある VBA の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-124">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="3f580-125">ドキュメントの修復操作の後であっても、一部の破損した PowerPoint ファイルを正常に開くことができないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-125">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="3f580-126">Project</span><span class="sxs-lookup"><span data-stu-id="3f580-126">Project</span></span>

- <span data-ttu-id="3f580-127">リソースの配分状況が特定の方法で指定されている場合に、Project が予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-127">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="3f580-128">Skype</span><span class="sxs-lookup"><span data-stu-id="3f580-128">Skype</span></span>

- <span data-ttu-id="3f580-129">ユーザの TLS-DSK 証明書が期待通りの時間に更新されず、有効期間が 12 時間未満の場合にのみ更新されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-129">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="3f580-130">Office にまだライセンスが付与されていない場合、サインイン後に Skype for Business UI が空白で表示されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-130">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="3f580-131">Office スイート</span><span class="sxs-lookup"><span data-stu-id="3f580-131">Office Suite</span></span>

- <span data-ttu-id="3f580-132">この変更により、従来の図面を含むファイルを開くことに関連する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="3f580-132">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="3f580-133">この変更により、SVG フォールバック プロキシでアクセス違反が発生する問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="3f580-133">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-december-08"></a><span data-ttu-id="3f580-135">バージョン 2008: 12 月 08 日</span><span class="sxs-lookup"><span data-stu-id="3f580-135">Version 2008: December 08</span></span>
<span data-ttu-id="3f580-136">*バージョン 2008 (ビルド 13127.20910)*</span><span class="sxs-lookup"><span data-stu-id="3f580-136">*Version 2008 (Build 13127.20910)*</span></span>

<span data-ttu-id="3f580-137">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f580-137">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="3f580-139">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="3f580-139">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="3f580-140">Access</span><span class="sxs-lookup"><span data-stu-id="3f580-140">Access</span></span>

- <span data-ttu-id="3f580-141">ODBC DSNBuilder を使用しようとしたときに発生するエラーの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="3f580-141">We fixed an error issue when trying to use ODBC DSN builder</span></span>


### <a name="excel"></a><span data-ttu-id="3f580-142">Excel</span><span class="sxs-lookup"><span data-stu-id="3f580-142">Excel</span></span>

- <span data-ttu-id="3f580-143">プロジェクト計画からエクスポートした場合、ピボットテーブルを編集できず、ワークブックを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-143">Fixed an issue where pivot tables could not be edited and workbooks could not be saved if they were exported from Project plan.</span></span>


- <span data-ttu-id="3f580-144">ファイルを読み取り専用モードで開いたときに、複数のメッセージ バーが表示される場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-144">We fixed an issue where in some cases, multiple message bars were appearing when a file was opened in read-only mode.</span></span>


- <span data-ttu-id="3f580-145">列ヘッダーの値が重複していると、アウトラインの小計が機能しなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-145">We fixed an issue where outline sub-totals could stop working when there were many duplicate column header values.</span></span>


- <span data-ttu-id="3f580-146">マルチ スレッドの再計算中にグループ ポリシー オブジェクトの更新 (リモート グループ ポリシーの更新など) が行われた場合に Excel が機能しなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-146">We fixed an issue where Excel would stop working when there is a Group Policy Object update (e.g. via Remote Group Policy Refresh) during multithreaded recalc.</span></span>


- <span data-ttu-id="3f580-147">ユーザーが 255 を超える列で subtotal 関数を使用すると、Excel が機能しなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-147">We fixed an issue where Excel would stop working when users use the subtotal function on more than 255 columns.</span></span>


- <span data-ttu-id="3f580-148">PowerPoint でコンテンツを Excel からコピーし、Embed オプションを使用して PowerPoint に貼り付けたときのテキスト カーニングを改善しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-148">Improved text kerning in PowerPoint when when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="3f580-149">PowerPivot のテーブルプレビューとクエリエディターからの切り替えができなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-149">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="3f580-150">ユーザーが SharePoint から .atomsvc (UTF8 + BOM) ファイルを直接開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-150">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="3f580-151">問題が修正され、Power Pivot がタブ区切り文字を正常に認識するようになりました。</span><span class="sxs-lookup"><span data-stu-id="3f580-151">We fixed an issue where Power Pivot will now successfully recognize tab delimiter.</span></span>


### <a name="outlook"></a><span data-ttu-id="3f580-152">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f580-152">Outlook</span></span>

- <span data-ttu-id="3f580-153">タスクのステータスレポートを送信するときに To: フィールドが空白になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-153">We fixed an issue that caused the To: field to be empty when sending a status report on a Task.</span></span>


- <span data-ttu-id="3f580-154">MailItem.BeforeAttachmentAdd イベントの破損原因となった問題が修正されました。 </span><span class="sxs-lookup"><span data-stu-id="3f580-154">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="3f580-155">Outlook 以外のアプリケーションから Outlook メールを送信するときに、一部のユーザーのアプリケーションが予期せず閉じる原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-155">We fixed an issue that was causing some users to experience the application to close unexpectedly when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="3f580-156">オンライン モードでフォルダ間で複数のメール アイテムを移動すると、ユーザーのパフォーマンスが低下する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-156">We fixed an issue that caused users to experience degraded performance when moving multiple mail items between folders in online mode.</span></span>


- <span data-ttu-id="3f580-157">IDataObject 操作 (つまりクリップボードのドラッグやドロップ) で、ユーザーが添付ファイルに対して filetime の付加を無効にできるように、regkey を追加しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-157">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="3f580-158">HKCU \ SOFTWARE \ Microsoft \ Office \ 16.0 \ Outlook \ Attachments REG_DWORD IncludeFileTimesInDataObject 0 = filetimes は除外されます 1 = (既定)filetimes が含まれます</span><span class="sxs-lookup"><span data-stu-id="3f580-158">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes are excluded  1 = (default) filetimes are included</span></span>


- <span data-ttu-id="3f580-159">Azure Information Protection の保護ラベルを使用してメッセージに返信するときに、インライン画像が消えるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-159">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="3f580-160">Azure Protected Voicemail を送信するときにユーザー名が電話番号として表示され、Outlook Desktop ユーザーが外部ユーザーからのボイス メールを開くことができなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-160">We fixed an issue that caused the user name to be displayed as a phone number when sending an Azure Protected Voicemail, causing Outlook Desktop users to be unable to open voicemails from external users.</span></span>


- <span data-ttu-id="3f580-161">OME構成を設定すると、DecryptAttachmentsForEncryptOnly オプションがサービス側で設定されていても、メールアイテムに無関係な添付ファイルが追加され、Outlook がメッセージを暗号化するように強制される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-161">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though the DecryptAttachmentsForEncryptOnly option was setup on the service side.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="3f580-162">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f580-162">PowerPoint</span></span>

- <span data-ttu-id="3f580-163">ユーザーがソース パスをローカルの OneDrive フォルダーに変更すると、リンクされた Excel グラフが誤って Excel シートに変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-163">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="3f580-164">「Welcome back!」機能が原因で発生した問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-164">We fixed an issue due to which the feature ‘Welcome back!</span></span> <span data-ttu-id="3f580-165">PowerPoint で機能していなかったオフィスで中断したところから再開します。</span><span class="sxs-lookup"><span data-stu-id="3f580-165">Pick up where you left off in the office' was not working in the PowerPoint .</span></span>


### <a name="visio"></a><span data-ttu-id="3f580-166">Visio</span><span class="sxs-lookup"><span data-stu-id="3f580-166">Visio</span></span>

- <span data-ttu-id="3f580-167">問題が修正され、ユーザーが Visio for Office 365 のコネクタを使用して、ユーザー設定の Visio ステンシルと組み込みのテンプレートの両方で直線を作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="3f580-167">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="3f580-168">Word</span><span class="sxs-lookup"><span data-stu-id="3f580-168">Word</span></span>

- <span data-ttu-id="3f580-169">ドキュメントを HTML 形式に保存するときに、長いリンクが折り返されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-169">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="3f580-170">拡張子リストにない拡張子がある親コメントに返信すると、返信に同じ拡張子が含まれる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-170">We fixed an issue where if you reply to a parent comment that has unknown extensions in an extension list, the reply will get those same extensions.</span></span>


- <span data-ttu-id="3f580-171">メッセージが [転送しない] に設定される Outlook の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-171">We fixed an issue with Outlook with message set to Do not forward.</span></span>


### <a name="office-suite"></a><span data-ttu-id="3f580-172">Office スイート</span><span class="sxs-lookup"><span data-stu-id="3f580-172">Office Suite</span></span>

- <span data-ttu-id="3f580-173">ADAL が無効になっているときにユーザーが SPO リストをインポートできない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="3f580-173">Addresses an issue that prevented users from importing SPO Lists when ADAL was disabled.</span></span>



[//]: # (BUGDETAILS コンテンツ エンドを削除しないでください。終了)

## <a name="version-2008-november-10"></a><span data-ttu-id="3f580-175">バージョン 2008: 11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="3f580-175">Version 2008: November 10</span></span>
<span data-ttu-id="3f580-176">*バージョン 2008 (ビルド 13127.20760)*</span><span class="sxs-lookup"><span data-stu-id="3f580-176">*Version 2008 (Build 13127.20760)*</span></span>

<span data-ttu-id="3f580-177">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f580-177">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="3f580-179">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="3f580-179">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="3f580-180">Excel</span><span class="sxs-lookup"><span data-stu-id="3f580-180">Excel</span></span>

- <span data-ttu-id="3f580-181">ブックをロードした後、特定の関数の結果が不正確であるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-181">We fixed an issue where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="3f580-182">XLAM アドイン参照と名前付き範囲に関連するアプリケーションが予期せず終了する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-182">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="3f580-183">マクロを使用して、範囲の FormulaR1C1 プロパティを設定する問題を修正しました。グラフ シートがアクティブ シートである場合、セル参照が正しくありませんでした。</span><span class="sxs-lookup"><span data-stu-id="3f580-183">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="3f580-184">Excel で 1 つまたは複数の数式を計算しようとする際に発生する、Excelはリソース不足になりましたというエラーが生じる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-184">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="3f580-185">Office の言語がスペイン語に設定されているときに、データ検証リストにすべてのアイテムが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-185">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="3f580-186">OLAP ピボットテーブルを更新するときにハングする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-186">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>

### <a name="outlook"></a><span data-ttu-id="3f580-187">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f580-187">Outlook</span></span>

- <span data-ttu-id="3f580-188">Outlook の IRM (Information Rights Management) を他の Office アプリケーションで無効にすることなく無効にできる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-188">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="3f580-189">ユーザーが代理人に編集者権限を付与できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-189">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="3f580-190">ユーザーが検索結果を選択したときにアプリケーションが予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-190">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="3f580-191">グループ予定表で検索結果が返されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-191">We fixed an issue that caused searches in Group calendars fail to return any results.</span></span>


- <span data-ttu-id="3f580-192">代理人が別のメールボックスで共有フォルダーを開くと、断続的にエラーが表示される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-192">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="3f580-193">件名が空白の場合、一部の自動的に生成されたメールの本文が空で送信される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-193">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="3f580-194">返信または転送時に中国語メッセージのヘッダーが文字化けする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-194">We fixed an issue that caused the headers of Chinese messages to get garbled when replying or forwarding.</span></span>

- <span data-ttu-id="3f580-195">オプションの接続エクスペリエンスが Web アドインの読み込みをブロックする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-195">We fixed an issue where optional connected experiences blocked web add-ins from loading.</span></span>  <br /><span data-ttu-id="3f580-196">
  [ブログの投稿](https://developer.microsoft.com/ja-JP/office/blogs/outlook-add-ins-and-optional-connected-experiences/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="3f580-196">See details in [blog post](https://developer.microsoft.com/ja-JP/office/blogs/outlook-add-ins-and-optional-connected-experiences/)</span></span>


### <a name="powerpoint"></a><span data-ttu-id="3f580-197">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f580-197">PowerPoint</span></span>

- <span data-ttu-id="3f580-198">ユーザーが別のスライドをクリックして表示するまで、Forms コンテンツ アドインが挿入後にレンダリングされない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-198">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>


### <a name="office-suite"></a><span data-ttu-id="3f580-199">Office スイート</span><span class="sxs-lookup"><span data-stu-id="3f580-199">Office Suite</span></span>

- <span data-ttu-id="3f580-200">Microsoft 365 エンドポイントのデータ損失防止を使用して Office Update に System Center Configuration Manager またはその他の管理ツールを利用する商用顧客の問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-200">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>

- <span data-ttu-id="3f580-201">Office アドインのメッセージング API が機能しない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="3f580-201">Fix an issue that the Messaging API for Office Add-ins is not working.</span></span>



[//]: # (BUGDETAILS コンテンツ エンドを削除しないでください。終了)

## <a name="version-2008-october-13"></a><span data-ttu-id="3f580-203">バージョン 2008: 10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="3f580-203">Version 2008: October 13</span></span>
<span data-ttu-id="3f580-204">*バージョン 2008 (Build 13127.20638)*</span><span class="sxs-lookup"><span data-stu-id="3f580-204">*Version 2008 (Build 13127.20638)*</span></span>

<span data-ttu-id="3f580-205">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f580-205">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="3f580-207">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="3f580-207">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3f580-208">Excel</span><span class="sxs-lookup"><span data-stu-id="3f580-208">Excel</span></span>

- <span data-ttu-id="3f580-209">' 前 ' と ' 後 ' のフィルター条件が逆転する バグをPivotDateFilter Api で修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-209">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


- <span data-ttu-id="3f580-210">Analysis Services データベースに既に存在しない値に設定されているために、ユーザーがピボットテーブル フィルターを変更できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-210">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="3f580-211">シートの一番上の行を固定した後にクイック分析を使用すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-211">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="3f580-212">IFNA () を使用する数式が含まれている場合、破損したワークブックに関する警告を発する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-212">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="3f580-213">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f580-213">Outlook</span></span>

- <span data-ttu-id="3f580-214">隅にある [X] をクリックして共有の予定表を閉じることができない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="3f580-214">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="3f580-215">[共有予定表の機能を有効にする] 設定が既存の共有予定表に適用されないことがある問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="3f580-215">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="3f580-216">クラウドの添付ファイルを開くときに、開こうとしていたドキュメントの代わりに、安全なリンクの ページにエラーが表示される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="3f580-216">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="3f580-217">添付ファイルのアップロードのパフォーマンスの問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="3f580-217">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="3f580-218">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f580-218">PowerPoint</span></span>

- <span data-ttu-id="3f580-219">この変更により、[エクスポート] ボタンをクリックしてもエクスポートされないという [アニメーション GIF にエクスポート] 機能の問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="3f580-219">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="3f580-220">セキュリティ修正プログラムを適用して、保護ビューで PowerPoint ファイルを開くと、 IRM による保護が無効になる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="3f580-220">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>

- <span data-ttu-id="3f580-221">PowerPoint アプリでクラッシュの原因となったオブジェクトの動作設定の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-221">We have fixed an issue in Action Settings dialog which was causing a crash in PowerPoint app.</span></span>

### <a name="visio"></a><span data-ttu-id="3f580-222">Visio</span><span class="sxs-lookup"><span data-stu-id="3f580-222">Visio</span></span>

- <span data-ttu-id="3f580-223">テキストの配置でリアルタイムのプレビュー表示がクラッシュするという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-223">We fixed an issue that caused the Live preview to crash on text alignment.</span></span>


### <a name="word"></a><span data-ttu-id="3f580-224">Word</span><span class="sxs-lookup"><span data-stu-id="3f580-224">Word</span></span>

- <span data-ttu-id="3f580-225">サイズが非常に大きい特定のメールを開くとクラッシュが発生する問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="3f580-225">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="3f580-226">ドキュメントを開くときに、ユーザーがクラッシュする可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-226">We fixed an issue which user might experience crash when opening a document.</span></span>


- <span data-ttu-id="3f580-227">Word を起動するときにクラッシュの原因となっている可能性のあった問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-227">Resolved an issue that may have caused a crash when booting Word.</span></span>


- <span data-ttu-id="3f580-228">スタイル ギャラリー ダイアログの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-228">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="3f580-229">Office スイート</span><span class="sxs-lookup"><span data-stu-id="3f580-229">Office Suite</span></span>

- <span data-ttu-id="3f580-230">Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。</span><span class="sxs-lookup"><span data-stu-id="3f580-230">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="3f580-231">このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。</span><span class="sxs-lookup"><span data-stu-id="3f580-231">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="3f580-232">GIF/アニメーション model3D を使用したアイドル時の高い CPU 使用率を修正</span><span class="sxs-lookup"><span data-stu-id="3f580-232">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="3f580-233">この変更は、 d2d1.dll の読み込みに失敗したために、Office アプリを起動したときにクラッシュする場合があった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="3f580-233">This change addresses a crash when launching Office apps due to failing to load d2d1.dll.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-september-08"></a><span data-ttu-id="3f580-235">バージョン 2008: 9 月 08 日</span><span class="sxs-lookup"><span data-stu-id="3f580-235">Version 2008: September 08</span></span>
<span data-ttu-id="3f580-236">*バージョン 2008(ビルド13127.20408)*</span><span class="sxs-lookup"><span data-stu-id="3f580-236">*Version 2008 (Build 13127.20408)*</span></span>

<span data-ttu-id="3f580-237">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f580-237">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="3f580-239">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="3f580-239">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="3f580-240">Access</span><span class="sxs-lookup"><span data-stu-id="3f580-240">Access</span></span>

- <span data-ttu-id="3f580-241">**クエリ デザイナー、SQL ビュー、およびリレーションシップ ウィンドウでの作業効率の向上:** テーブルを右クリックして、テーブルを開き、デザインし、サイズを変更し、非表示にします。</span><span class="sxs-lookup"><span data-stu-id="3f580-241">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="3f580-242">SQL ビューでテキストを検索および置換します。</span><span class="sxs-lookup"><span data-stu-id="3f580-242">Search and replace text in SQL View.</span></span> <span data-ttu-id="3f580-243">リレーションシップ ウィンドウ内の複数のテーブルを選択します。</span><span class="sxs-lookup"><span data-stu-id="3f580-243">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="3f580-244">**数回クリックするだけで表を追加する:** [テーブルの追加] 作業ウィンドウを使用すると、作業中も開いたまま、リレーションシップやクエリにテーブルを追加できます。</span><span class="sxs-lookup"><span data-stu-id="3f580-244">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="3f580-245">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-245">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="3f580-246">Excel</span><span class="sxs-lookup"><span data-stu-id="3f580-246">Excel</span></span>

- <span data-ttu-id="3f580-247">**改善されたマップ グラフ:** マップ グラフを Excel の地理のデータの種類と統合することにより、マップ グラフを改善しました。これにより、マップされた場所に関する豊富な情報を明らかにすることができます。</span><span class="sxs-lookup"><span data-stu-id="3f580-247">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="3f580-248">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-248">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="3f580-249">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="3f580-249">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="3f580-250">[ブログの投稿](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="3f580-250">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="3f580-251">**Excel で Power BI のデータセットからピボットテーブルを作成する:** Power BI に保存されているデータセットに接続されている Excel のピボットテーブルを数回のクリックで作成できます。</span><span class="sxs-lookup"><span data-stu-id="3f580-251">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="3f580-252">これにより、ピボットテーブルと Power BI の両方を最大限に活用できます。</span><span class="sxs-lookup"><span data-stu-id="3f580-252">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="3f580-253">セキュリティで保護された Power BI データセットからピボットテーブルを使って、データの計算、集計、分析を行います。</span><span class="sxs-lookup"><span data-stu-id="3f580-253">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="3f580-254">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-254">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="3f580-255">[ブログの投稿](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="3f580-255">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="3f580-256">**お気に入りの Excel 関数が速くなりました：** SUMIFS、AVERAGEIFS、COUNTIFS、MAXIFS、および MINIFS 関数がこれまでよりもはるかに高速になりました。</span><span class="sxs-lookup"><span data-stu-id="3f580-256">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="3f580-257">もっと素早く一番下に移動します。</span><span class="sxs-lookup"><span data-stu-id="3f580-257">Get to the bottom line more quickly.</span></span> <span data-ttu-id="3f580-258">今すぐお試しください。</span><span class="sxs-lookup"><span data-stu-id="3f580-258">Try one now.</span></span>

- <span data-ttu-id="3f580-259">**Realtimedata (RTD) の改善:** Office 365 バージョン 2002 の月間チャネル以降、ExcelのRealTimeData (RTD) 関数は、Excel 2010 のスプレッドシートのデータ計算よりもはるかに高速になります。</span><span class="sxs-lookup"><span data-stu-id="3f580-259">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="3f580-260">基盤となるメモリとデータ構造のボトルネックを取り除き、マルチスレッド再計算  (MTR) の使用可能なすべてのスレッドで計算できるようにスレッドセーフにしました。</span><span class="sxs-lookup"><span data-stu-id="3f580-260">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="3f580-261">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f580-261">Outlook</span></span>

- <span data-ttu-id="3f580-262">**共有カレンダーの更新がより速く**: Office 365 の共有カレンダーの場合、Outlook は REST API を使用してこれらのカレンダーを更新できます。</span><span class="sxs-lookup"><span data-stu-id="3f580-262">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="3f580-263">共有カレンダーのより高速で信頼性の高い更新を行うには、プレビューを有効にします。</span><span class="sxs-lookup"><span data-stu-id="3f580-263">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="3f580-264">**より迅速かつ適切な結果:** 検索機能が更新され、よりスマート、迅速、かつ信頼性が高くなりました。</span><span class="sxs-lookup"><span data-stu-id="3f580-264">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="3f580-265">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-265">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="3f580-266">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="3f580-266">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="3f580-267">[ブログの投稿](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="3f580-267">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="3f580-268">**所有しているグループにメールをドラッグ:** メッセージや会話を受信トレイからドラッグして移動し、コピーします。</span><span class="sxs-lookup"><span data-stu-id="3f580-268">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="3f580-269">ドラッグしたメッセージは、すべてのグループ メンバーと共有されます。</span><span class="sxs-lookup"><span data-stu-id="3f580-269">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="3f580-270">[ブログの投稿](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="3f580-270">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="3f580-271">**予定表が一新されます:** 予定表を簡単に読みやすくなるビジュアル アップデートをご覧ください。</span><span class="sxs-lookup"><span data-stu-id="3f580-271">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="3f580-272">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-272">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="3f580-273">[ブログの投稿](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="3f580-273">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="3f580-274">**受信トレイを離れずに会議に参加する:** オンライン会議に参加するために、予定表に切り替える必要はありません。</span><span class="sxs-lookup"><span data-stu-id="3f580-274">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="3f580-275">[To Do] ウィンドウに固定された予定表を使用して、ワンクリックで任意の会議に参加します。</span><span class="sxs-lookup"><span data-stu-id="3f580-275">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span> [<span data-ttu-id="3f580-276">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-276">Learn more</span></span>](https://support.office.com/article/d8baa9d5-0645-41b8-9f36-b498a6c36064 )

- <span data-ttu-id="3f580-277">**キャプティブ WiFi ネットワークの新しいエクスペリエンス**: サインインに Web ページを必要とする WiFi ネットワークに参加したことはありませんか ?</span><span class="sxs-lookup"><span data-stu-id="3f580-277">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="3f580-278">Outlook はこれを検出し、接続を支援します。</span><span class="sxs-lookup"><span data-stu-id="3f580-278">Outlook now detects this and helps you get connected.</span></span><br /><span data-ttu-id="3f580-279">[ブログの投稿](https://insider.office.com/ja-JP/blog/outlook-on-public-wi-fi-networks-just-got-easier)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="3f580-279">See details in [blog post](https://insider.office.com/ja-JP/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span></span>

- <span data-ttu-id="3f580-280">**人物を検索するときにメールの候補を取得する:** [検索] ボックスに人の名前を入力すると、最も関連性の高いメール メッセージが検索候補に含まれます。</span><span class="sxs-lookup"><span data-stu-id="3f580-280">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="3f580-281">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-281">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint"></a><span data-ttu-id="3f580-282">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f580-282">PowerPoint</span></span>

- <span data-ttu-id="3f580-283">**\@メンションを使用してユーザーの注意を引く:** コメントで @メンションを使うと、仕事仲間による入力が必要な場合にそのユーザーに知らせることができます。</span><span class="sxs-lookup"><span data-stu-id="3f580-283">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="3f580-284">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-284">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="3f580-285">**改善されたマップ グラフ:** マップ グラフを Excel の地理のデータの種類と統合することにより、マップ グラフを改善しました。これにより、マップされた場所に関する豊富な情報を明らかにすることができます。</span><span class="sxs-lookup"><span data-stu-id="3f580-285">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="3f580-286">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-286">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="3f580-287">**簡単な GIF:** 1 つのスライド、1 つのフレーム。</span><span class="sxs-lookup"><span data-stu-id="3f580-287">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="3f580-288">PowerPoint でループ GIF を簡単に作成できます。</span><span class="sxs-lookup"><span data-stu-id="3f580-288">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="3f580-289">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-289">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="3f580-290">[ブログの投稿](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="3f580-290">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="3f580-291">**図の向上: コネクタが改善されており、インクの滑らかな変換のプロセスが** によって、アイデアをより自信のあるインクにすることができます。</span><span class="sxs-lookup"><span data-stu-id="3f580-291">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="3f580-292">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-292">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="3f580-293">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="3f580-293">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="3f580-294">[ブログの投稿](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="3f580-294">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="3f580-295">**コメント:** PowerPoint の新しいコメント機能により、ドキュメントにコメントをすばやく簡単に見つけて追加できます。</span><span class="sxs-lookup"><span data-stu-id="3f580-295">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="3f580-296">コメントの固定、解決、タスク、改善された通知などの新機能を使用して、コラボレーションワークフローを最新のものにします。</span><span class="sxs-lookup"><span data-stu-id="3f580-296">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span> [<span data-ttu-id="3f580-297">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-297">Learn more</span></span>](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

- <span data-ttu-id="3f580-298">**プレゼンテーション中に変更を同期する:** プレゼンテーションがスライド ショー モードであっても、いつでも変更を同期できます。</span><span class="sxs-lookup"><span data-stu-id="3f580-298">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="3f580-299">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-299">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="3f580-300">[ブログの投稿](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="3f580-300">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="3f580-301">**スライドへのリンク:** 同僚にスライド デッキへの投稿を依頼し、ヘルプが必要なスライド上で直接開始します。</span><span class="sxs-lookup"><span data-stu-id="3f580-301">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span> [<span data-ttu-id="3f580-302">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-302">Learn more</span></span>](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br /><span data-ttu-id="3f580-303">[ブログの投稿](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="3f580-303">See details in [blog post](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span></span>

- <span data-ttu-id="3f580-304">**PowerPoint でのストリーム ビデオのパフォーマンス向上:**、ビデオの読み込み時間を最小限に抑え、快適な表示を実現するために Microsoft Stream ビデオの再生パフォーマンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-304">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="3f580-305">お客様の社内ビデオを使用して、Microsoft Stream でより適切なプレゼンテーションを作成します。</span><span class="sxs-lookup"><span data-stu-id="3f580-305">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>


### <a name="word"></a><span data-ttu-id="3f580-306">Word</span><span class="sxs-lookup"><span data-stu-id="3f580-306">Word</span></span>

- <span data-ttu-id="3f580-307">**改善されたマップ グラフ:** マップ グラフを Excel の地理のデータの種類と統合することにより、マップ グラフを改善しました。これにより、マップされた場所に関する豊富な情報を明らかにすることができます。</span><span class="sxs-lookup"><span data-stu-id="3f580-307">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="3f580-308">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-308">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="3f580-309">**インクのなげなわ:** [描画] タブのなげなわツールを使用すると、インクで描かれたオブジェクトを選択できます。</span><span class="sxs-lookup"><span data-stu-id="3f580-309">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="3f580-310">個別のストロークまたは文字全体を選択できます。</span><span class="sxs-lookup"><span data-stu-id="3f580-310">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="3f580-311">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-311">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="3f580-312">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="3f580-312">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="3f580-313">[ブログの投稿](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="3f580-313">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="3f580-314">**スクリーン リーダーでの操作の確認:** 操作の確認は、重要なアクセシビリティ要件です。</span><span class="sxs-lookup"><span data-stu-id="3f580-314">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="3f580-315">Windows からの新しい通知 API の導入により、操作の成功をスクリーン リーダーのユーザーに通知できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="3f580-315">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="3f580-316">切り取り、コピー、貼り付け、太字、斜体、下線、元に戻す、やり直し、自動修正、および自動大文字化が、Win32 Word のナレーター ユーザーにすべて通知されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="3f580-316">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="3f580-317">この機能を有効にするには、Windows + Ctrl + Enter キーを押してナレーターをオンにします。</span><span class="sxs-lookup"><span data-stu-id="3f580-317">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span><br /><span data-ttu-id="3f580-318">[ブログの投稿](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="3f580-318">See details in [blog post](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="3f580-319">Office スイート</span><span class="sxs-lookup"><span data-stu-id="3f580-319">Office Suite</span></span>

- <span data-ttu-id="3f580-320">**秘密度ラベル:** カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="3f580-320">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="3f580-323">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="3f580-323">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="3f580-324">アクセス</span><span class="sxs-lookup"><span data-stu-id="3f580-324">Access</span></span>

- <span data-ttu-id="3f580-325">ID (オートナンバーなど) フィールドが含まれるリンク付きの SQL 表を挿入する場合についての問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-325">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

- <span data-ttu-id="3f580-326">クエリの実行に予想よりも約 2 倍の時間がかかっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-326">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="3f580-327">アプリケーションのクラッシュを発生させずに、Date/Time Extended データ型をコードに呼び出すことができるように問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-327">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span>

- <span data-ttu-id="3f580-328">この問題は修正されて、最新の Access バージョンに戻し、 DAO/VBA を使用して 10 進数データ型を管理および編集することができます。</span><span class="sxs-lookup"><span data-stu-id="3f580-328">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>

- <span data-ttu-id="3f580-329">この修正プログラムでは、特定のクエリを実行しようとすると、"クエリが複雑すぎます" というエラーメッセージが表示される問題に対処しています。</span><span class="sxs-lookup"><span data-stu-id="3f580-329">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="3f580-330">Access では、現在の問題が修正されていますが、この問題が解決するように、追加のインターフェイスを調査しています。</span><span class="sxs-lookup"><span data-stu-id="3f580-330">Access has fixed this current issue, but will be investigating our additional interfaces to ensure that this problem does not persist.</span></span> <span data-ttu-id="3f580-331">今後の更新情報でさらにご案内いたします。ご不便をおかけして申し訳ございません。</span><span class="sxs-lookup"><span data-stu-id="3f580-331">The team will inform you with future updates; we appreciate your patience.</span></span>

- <span data-ttu-id="3f580-332">この問題は解決されました。これで、Office のクイック実行アプリケーション以外でも ODBC ドライバーを使用できます。</span><span class="sxs-lookup"><span data-stu-id="3f580-332">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="3f580-333">Excel</span><span class="sxs-lookup"><span data-stu-id="3f580-333">Excel</span></span>

- <span data-ttu-id="3f580-334">読み取り専用モードのブックに対して、ドキュメント分類を自動的に行った可能性があります。</span><span class="sxs-lookup"><span data-stu-id="3f580-334">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="3f580-335">アカウントからサインアウトした場合にデータ接続を作成しようとすると発生する可能性があるクラッシュを修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-335">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

- <span data-ttu-id="3f580-336">ピボットテーブルをチャート シートに挿入しようとしたときに Excel がクラッシュする場合がある問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-336">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

- <span data-ttu-id="3f580-337">LET () 関数を使用して、数式を含むファイルを保存しようとすると、エラーが発生することがあります。</span><span class="sxs-lookup"><span data-stu-id="3f580-337">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="3f580-338">Format Painter を使用すると、特定の状況で Excel がクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-338">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>

- <span data-ttu-id="3f580-339">SharePoint/OneDrive に保存すると、ユーザー設定のリボンタブの CustomUI XML が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-339">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="3f580-340">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-340">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="3f580-341">同じブック内の場所へのハイパーリンクをクリックすると、ブックが非表示になることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-341">Fixed an issue where in some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

- <span data-ttu-id="3f580-342">ファイル パスが長すぎる場合にファイルをもう一度開くと、外部リンクが機能しなくなった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-342">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="3f580-343">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="3f580-343">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="3f580-344">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="3f580-344">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="3f580-345">ピボットテーブルを含むシートをコピーした後、Excel がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-345">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="3f580-346">これは、以前のバージョンの Office で SQL データプロバイダーによって作成された接続が内部テーブルのプロパティを Office 365 とは別に設定する問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="3f580-346">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="3f580-347">これにより、Office 365 を使用して開かれた以前のバージョンの Office で作成された接続を持つファイルに対して、[テーブルのプレビュー / クエリエディター] のドロップダウンが無効になりました。</span><span class="sxs-lookup"><span data-stu-id="3f580-347">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>

- <span data-ttu-id="3f580-348">ソース ブックが閉じていると、外部リンクが塗りつぶし時に更新されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-348">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="3f580-349">手描き入力で Excel が応答しなくなる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-349">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>

### <a name="onenote"></a><span data-ttu-id="3f580-350">OneNote</span><span class="sxs-lookup"><span data-stu-id="3f580-350">OneNote</span></span>

- <span data-ttu-id="3f580-351">全世界でサービス使用量が高まった際に、同期とサービスの可用性を改善できる、Microsoft OneNote の一時的な調整に関して、情報バーを介してユーザーに通知します。</span><span class="sxs-lookup"><span data-stu-id="3f580-351">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

- <span data-ttu-id="3f580-352">OneNote 2016 で同期頻度を一時的に調整することで、同期およびサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-352">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="3f580-353">リソースの使用率を低下させて、共同編集状態の検出機能を改善します。</span><span class="sxs-lookup"><span data-stu-id="3f580-353">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="3f580-354">OneNote 2016 に 50 MB へ埋め込まれた新しい添付ファイルの最大許容サイズが一時的に減少することにより、同期とサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-354">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="3f580-355">この制限を超えるファイルの場合、ユーザーは OneDrive にファイルをアップロードして、OneNote にリンクを挿入することができます。</span><span class="sxs-lookup"><span data-stu-id="3f580-355">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="3f580-356">OneNote 2016 でアプリ内動画のレコーディングを一時的に無効にすることで、同期およびサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-356">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="3f580-357">ローカルのノートブックはこの影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="3f580-357">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="3f580-358">ページのバージョン履歴を作成する頻度を一時的に変更することで、同期およびサービスの安定性が改善されます。</span><span class="sxs-lookup"><span data-stu-id="3f580-358">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>

- <span data-ttu-id="3f580-359">ごみ箱へのページの移動を一時的に無効にすることにより、同期およびサーバーの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-359">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="3f580-360">代わりに、ページを削除するユーザーにはページを完全に削除するか確認するダイアログが表示されます。</span><span class="sxs-lookup"><span data-stu-id="3f580-360">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>

### <a name="outlook"></a><span data-ttu-id="3f580-361">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f580-361">Outlook</span></span>

- <span data-ttu-id="3f580-362">プロファイルに追加されたサブ アカウントから会議出席依頼を作成しようとした場合に、ユーザーのメール アドレスの代わりに空欄の From: フィールドが表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-362">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="3f580-363">共有メールボックスを追加した後に、ユーザーがパブリック フォルダーに接続できない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-363">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="3f580-364">特定の状況で代理人が会議を辞退したときに、マネージャーのカレンダーから削除されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-364">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="3f580-365">共有カレンダーの改善機能を使用している一部のユーザーが、新しく追加された共有カレンダーを表示できない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-365">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="3f580-366">クラウドの添付ファイルを操作するときに、ユーザーに時折クラッシュが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-366">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="3f580-367">保護されたコンテキストから保護されていないコンテキストに返信するとき、送信元アドレスを切り替えると、CLP のユーザーにクラッシュが発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-367">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>

- <span data-ttu-id="3f580-368">M365 Business Plus プランのサービスを利用していたユーザーがデータ損失防止の保護ポリシー ヒントを有効にできない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-368">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="3f580-369">CLP の監査イベントで、返信/転送ラベルの問題に対応しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-369">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="3f580-370">フォルダー ウィンドウの幅が予期せず変更される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-370">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="3f580-371">ドラッグ アンド ドロップによってファイル システムにコピーされた添付ファイルの作成日が、4501年1月1日に設定される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-371">Addressed an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>

- <span data-ttu-id="3f580-372">SharePoint ファイルに Smart Link を追加すると、一部の文字セットのユーザーにファイル名が正しく表示されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-372">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="3f580-373">ユーザーが Outlook のルールを更新すると、「このコンピューターのルールは、Microsoft Exchange のルールと異なります」というメッセージが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-373">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="3f580-374">Outlook で検索候補を取得できない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-374">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>

- <span data-ttu-id="3f580-375">共有された予定表の改良版のユーザーに予定表のエラーが表示される問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-375">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>

- <span data-ttu-id="3f580-376">一部のシナリオで、断続的なハングやクラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-376">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>

- <span data-ttu-id="3f580-377">[ヘッダーのみダウンロード] オプションが選択されている POP アカウントから 4 件以上のメールを削除しようとするとクラッシュするという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-377">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="3f580-378">[共有フォルダーのダウンロード] がチェックされていない場合、共有された予定表の会議の [返信オプション] に [転送を許可する] オプションが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-378">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="3f580-379">管理者のカレンダー上で既存のカレンダーの予定を編集するときに代理人がエラーを受け取る問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-379">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="3f580-380">サードパーティ製の MAPI アプリケーションでクラッシュが発生した問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-380">Addressed an issue that caused users to experience crashes in third party MAPI applications.</span></span>

- <span data-ttu-id="3f580-381">Windows の更新後に、ローカルに保存された .msg または .oft ファイルを開くと Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-381">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="3f580-382">Windows の一部のビルドで Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-382">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="3f580-383">Windows 10 サーバー バージョンのユーザーに、以下の警告が表示される問題に対処しました。「アンチウイルスの状態が無効です。</span><span class="sxs-lookup"><span data-stu-id="3f580-383">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="3f580-384">このバージョンの Windows はウイルス対策ソフト検出をサポートしていますが、ウイルス対策ソフトが見つかりませんでした」という警告が、アンチウイルスが正しくインストールされているにもかかわらず表示されていました。</span><span class="sxs-lookup"><span data-stu-id="3f580-384">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="3f580-385">Windows の更新後に、ローカルに保存された .msg または .oft ファイルを開くと Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-385">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="3f580-386">Windows の一部のビルドで Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-386">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="3f580-387">Outlook で、受信トレイ修復ツールを実行するように促す表示が継続的に発生していた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-387">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>

- <span data-ttu-id="3f580-388">マウスで ”X” ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-388">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="3f580-389">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカルコンピューターに保存できない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-389">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="3f580-390">スケジュール アシスタント ページが表示されない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-390">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="3f580-391">一部のユーザーにスケジュール アシスタント ページが表示されない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-391">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="3f580-392">ユーザーがペルソナ情報を取得しようとしたときにクラッシュする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-392">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>

- <span data-ttu-id="3f580-393">これにより、受信者を編集しているときに不定期にクラッシュする問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-393">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="3f580-394">コンパクト ビューを使用するときに異常が表示される原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-394">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="3f580-395">Outlook ユーザーにコンパクト ビューでのナビゲーションの問題が表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-395">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>

- <span data-ttu-id="3f580-396">右クリックのコンテキストメニューが検索コントロールに表示されない問題の原因を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-396">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="3f580-397">ユーザーが新しいメールに返信または作成するときに次のエラーを受け取る原因となった問題に対処します。「この Web ページのファイルの一部が予期された場所にありません。</span><span class="sxs-lookup"><span data-stu-id="3f580-397">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="3f580-398">この Web ページをダウンロードする必要がありますか? </span><span class="sxs-lookup"><span data-stu-id="3f580-398">Do you want to download them anyway?</span></span> <span data-ttu-id="3f580-399">Web ページが信頼できるソースからのものであることを確認したら、[はい] をクリックします。」</span><span class="sxs-lookup"><span data-stu-id="3f580-399">If you’re sure the Web page is from a trusted source, click Yes"</span></span>

- <span data-ttu-id="3f580-400">Outlook の終了中に応答停止が発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-400">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>

- <span data-ttu-id="3f580-401">Suggest a Feature で機能を検索しても結果が返されず、ユーザーが新しい機能のアイデアを提出するオプションがないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-401">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>

- <span data-ttu-id="3f580-402">インシデント通知アラートのフォーマットの問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-402">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

- <span data-ttu-id="3f580-403">ユーザーが管理者通知からフィードバックを送信する場合にクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-403">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

- <span data-ttu-id="3f580-404">SVG 画像のコピーと貼り付けの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-404">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="3f580-405">これにより、受信者を編集しているときに不定期にクラッシュする問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-405">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="3f580-406">SVG 画像のコピーと貼り付けの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-406">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="3f580-407">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f580-407">PowerPoint</span></span>

- <span data-ttu-id="3f580-408">ユーザーがファイルに最新のコメントと従来のコメントの両方を持っていると、コメントのアップグレードが開始されるクラッシュを修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-408">Fixed a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

- <span data-ttu-id="3f580-409">PowerPoint アプリでクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-409">We have fixed a crash issue with PowerPoint app.</span></span>

- <span data-ttu-id="3f580-410">提案ウィンドウでクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-410">We have fixed a crash issue with suggestion pane.</span></span>

### <a name="project"></a><span data-ttu-id="3f580-411">Project</span><span class="sxs-lookup"><span data-stu-id="3f580-411">Project</span></span>

- <span data-ttu-id="3f580-412">先行処理 / 後続処理データがフォームビュー内で編集されると、追加の ProjectBeforeTaskChange イベントが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-412">Fixed an issue when Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="3f580-413">以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-413">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="3f580-414">実績作業時間の保護設定を有効にしているときに、ユーザーがタイムフェーズの基準作業時間を入力できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-414">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

- <span data-ttu-id="3f580-415">タスクを完了とマークした後に、タスクの達成率が 100% 完了より小さい値に誤って変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-415">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="3f580-416">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-416">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="3f580-417">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-417">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="3f580-418">[無効化] ボタンを介してタスクが非アクティブ化/アクティブ化された場合に、ProjectBeforeTaskChange イベントが検出しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-418">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="3f580-419">Project Web App に接続されている Project を使用していて小数点の記号がカンマの場合に、依存関係のタイム ラグを生じさせようとすると TaskDependencies Add メソッドが失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-419">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

- <span data-ttu-id="3f580-420">URL の末尾が「.com」の場合に、Project Web App から Project デスクトップ クライアントでプロジェクトを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-420">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>

- <span data-ttu-id="3f580-421">複数の依存関係があるタスクを貼り付けると、すべての依存関係が正しくコピーされるわけではない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-421">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="3f580-422">Project から SharePoint ドキュメント ライブラリに PDF/XPS を保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-422">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>

- <span data-ttu-id="3f580-423">100% 完了とマークされているタスクが、100% 未満のタスクに間違って変更されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-423">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="3f580-424">プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-424">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="3f580-425">リソースに複数のコスト単価表が定義されている場合に、残りのコストが正しく計算されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-425">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

- <span data-ttu-id="3f580-426">SharePoint タスクリストに接続されているプロジェクトのプロジェクト終了日が更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-426">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="3f580-427">[リソースの割り当て] ダイアログ ボックスで選択されているタスクが、[タスク ボード] ビューで選択したタスクと異なる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-427">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="3f580-428">正常ではない状態になったプロジェクトを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-428">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>

### <a name="skype"></a><span data-ttu-id="3f580-429">Skype</span><span class="sxs-lookup"><span data-stu-id="3f580-429">Skype</span></span>

- <span data-ttu-id="3f580-430">ユーザーが Teams Only に移動するポリシーを与えられた場合は、Skype for Business Outlook アドインを使用して会議をスケジュールできます。</span><span class="sxs-lookup"><span data-stu-id="3f580-430">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="3f580-431">この更新プログラムを適用すると、クライアントは Teams Only を対象としていることを示すポリシーをユーザーが読んでから会議参加のみのモードに入った後に、Skype for Business 会議のスケジュールを設定できなくなります。</span><span class="sxs-lookup"><span data-stu-id="3f580-431">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="3f580-432">また、skype for business Outlook アドインは、Skype for business クライアントが 「会議の参加のみ」 モードであることを確認した場合に起動した場合、自動的にアクティブ化されることはありません。</span><span class="sxs-lookup"><span data-stu-id="3f580-432">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="3f580-433">ダンス絵文字の肌の色を中間色に変更しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-433">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="3f580-434">Word</span><span class="sxs-lookup"><span data-stu-id="3f580-434">Word</span></span>

- <span data-ttu-id="3f580-435">URL にクエリ コンポーネントが含まれている場合にカスタム ドキュメント配信 (aspx) から Word ドキュメントを開く問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-435">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="3f580-436">この変更により、以前の共同編集セッションの後に Office アプリケーションがサイレント保存の失敗状態に陥ることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-436">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="3f580-437">新しいメールに返信、または新しいメールを作成するときにユーザーにクラッシュが発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-437">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="3f580-438">マウスで ”X” ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-438">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="3f580-439">SVG 画像のコピーと貼り付けの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-439">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="3f580-440">図形のサイズを変更すると、ユーザーがコンテンツを失う可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-440">We fixed an issue where the user might lose content when resize a shape.</span></span>

- <span data-ttu-id="3f580-441">基本スタイルが標準スタイルで更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-441">We fixed an issue which the base styles are not updated with Normal style.</span></span>

- <span data-ttu-id="3f580-442">マクロ AutoOpen が AutoExec の前に実行されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-442">We fixed an issue where macro AutoOpen runs before AutoExec.</span></span>

- <span data-ttu-id="3f580-443">SVG 画像のコピーと貼り付けの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-443">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="3f580-444">一部のアプリケーションからコンテンツをドラッグしたときにクラッシュする問題の原因となっていた可能性がある問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-444">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="3f580-445">Office スイート</span><span class="sxs-lookup"><span data-stu-id="3f580-445">Office Suite</span></span>

- <span data-ttu-id="3f580-446">以前の Web サービス ベースの [共有] ウィンドウで、[共有] ウィンドウが開いているときに文書を閉じるとクラッシュする場合があります。</span><span class="sxs-lookup"><span data-stu-id="3f580-446">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="3f580-447">この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-447">This is now fixed.</span></span>

- <span data-ttu-id="3f580-448">タイミングの問題で、Office ファイルを閉じるときにクラッシュすることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="3f580-448">Fixed a timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="3f580-449">Bing アドオンのインストール検証を既定で true に設定し、MSI のリターン成功をインストール成功とみなすことで、ValidateInstall のエラー率の問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-449">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>

- <span data-ttu-id="3f580-450">以前の AppV51 の回帰を修正するために、新しい AppV51 drop をバックポートします。</span><span class="sxs-lookup"><span data-stu-id="3f580-450">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="3f580-451">シンボリック リンクのハード リンクを試みる際に、更新の失敗を引き起こしていたクイック実行の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-451">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>

- <span data-ttu-id="3f580-452">製品版への移行が完了した場合でも、ランタイムメッセージが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-452">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="3f580-453">この問題の修正では、サービスが追加された製品を適切に計算するようにしました。</span><span class="sxs-lookup"><span data-stu-id="3f580-453">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="3f580-454">新たに追加された製品をフィルターで除外し (新しい構成に存在することも確認)、既存の製品リリース ID の最後に追加しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-454">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>

- <span data-ttu-id="3f580-455">特定の状況下で UI 要素またはコンテンツが表示されない問題を修正しました。特に、発表者ツールのオン/オフ、または複数のモニターの使用に関して発生しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-455">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>

- <span data-ttu-id="3f580-456">この変更により、Gif や3D モデルなどのアニメーション コンテンツを読み込んだり、再生したりするときに、ハングする可能性があります。</span><span class="sxs-lookup"><span data-stu-id="3f580-456">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>

- <span data-ttu-id="3f580-457">この変更では、[図の圧縮] ダイアログで一部のユーザー設定が保持されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-457">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>

- <span data-ttu-id="3f580-458">この更新プログラムでは、Microsoft Office で PATH 環境変数で指定した場所を検索することによって参照される可能性がある Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA ランタイムエラーが発生するという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="3f580-458">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="3f580-459">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="3f580-459">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="3f580-460">この修正プログラムで、アクセスの制限と、パスワードによるファイルの保護が同時に行えないというエラーが解決されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-460">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="3f580-461">レジストリ TabProcGrowth の値がREG_SZ型でアドインがアクティブ化されている場合に、Windows の Office ホストがクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-461">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="3f580-462">HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth のレジストリ キーが0に設定されている場合、アドインがアクティブになり、Windows で Office ホストがクラッシュしました。</span><span class="sxs-lookup"><span data-stu-id="3f580-462">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="3f580-463">この変更により、この問題は修正されます。</span><span class="sxs-lookup"><span data-stu-id="3f580-463">This change would fix this issue.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-august-11"></a><span data-ttu-id="3f580-465">バージョン 2002: 8 月 11 日</span><span class="sxs-lookup"><span data-stu-id="3f580-465">Version 2002: August 11</span></span>
<span data-ttu-id="3f580-466">*バージョン 2002 (ビルド 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="3f580-466">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="3f580-467">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f580-467">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="3f580-469">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="3f580-469">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3f580-470">Excel</span><span class="sxs-lookup"><span data-stu-id="3f580-470">Excel</span></span>

- <span data-ttu-id="3f580-471">「読み取り専用推奨」として開かれたファイルの編集に切り替えられない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-471">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="3f580-472">OneNote</span><span class="sxs-lookup"><span data-stu-id="3f580-472">OneNote</span></span>

- <span data-ttu-id="3f580-473">リソースの使用率を低下させるための冗長な ID 呼び出しが削除されました</span><span class="sxs-lookup"><span data-stu-id="3f580-473">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="3f580-474">リソースの使用率を低下させて、共同編集状態の検出機能を改善します。</span><span class="sxs-lookup"><span data-stu-id="3f580-474">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="3f580-475">エラーを検出する機能が改善され、同期環境の品質が向上しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-475">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="3f580-476">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f580-476">Outlook</span></span>

- <span data-ttu-id="3f580-477">一部のテナントで Outlook を起動したときに重大なパフォーマンスの問題が発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-477">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="3f580-478">Skype</span><span class="sxs-lookup"><span data-stu-id="3f580-478">Skype</span></span>

- <span data-ttu-id="3f580-479">数日間稼働した後に、32 ビット版の Skype for Business クライアントで画面共有を開始できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-479">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="3f580-480">Office スイート</span><span class="sxs-lookup"><span data-stu-id="3f580-480">Office Suite</span></span>

- <span data-ttu-id="3f580-481">グループ ポリシーを介して自動保存が無効にされた場合に、ユーザーが [利用可能な更新] をクリックするまで一部のドキュメントで最新のサーバー コンテンツが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-481">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-july-14"></a><span data-ttu-id="3f580-483">バージョン 2002: 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="3f580-483">Version 2002: July 14</span></span>
<span data-ttu-id="3f580-484">*バージョン 2002 (ビルド 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="3f580-484">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="3f580-485">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f580-485">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="3f580-487">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="3f580-487">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3f580-488">Excel</span><span class="sxs-lookup"><span data-stu-id="3f580-488">Excel</span></span>

- <span data-ttu-id="3f580-489">ローカルの OneDrive フォルダーで使用できるファイルの読み込み速度を向上します。</span><span class="sxs-lookup"><span data-stu-id="3f580-489">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="3f580-490">SharePoint/OneDrive に保存すると、ユーザー設定のリボン タブの CustomUI XML が削除されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-490">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="3f580-491">アドインが、ユーザーが指定した順番ではなくアルファベット順に読み込まれていたため、「このブックは現在別のユーザーに参照されており、閉じることができません」というエラー メッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-491">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="3f580-492">既に開いているブック内の場所へのハイパーリンクをクリックすると、ブックが非表示になることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-492">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="3f580-493">コピー & ペーストされたグラフのリンクの一部で、ユニバーサル アドレスではなくマップされたドライブ アドレスが使用されていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-493">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="3f580-494">結合されたセルを持つ列を削除するときのパフォーマンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-494">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="3f580-495">[印刷] ダイアログ ボックスのプリンターの一覧にプリンター名が繰り返されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-495">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="3f580-496">定義された名前を持つ複数の数式を含むワークシートがファイルを保存するときに時間がかかる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-496">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>


### <a name="outlook"></a><span data-ttu-id="3f580-497">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f580-497">Outlook</span></span>

- <span data-ttu-id="3f580-498">解像度の異なる複数のモニターを使用している場合に、IME(Input Method Editor)ウィンドウで入力されたテキストが重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-498">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="3f580-499">タイムゾーンの定義を変更するときに、定期的な予定や会議が誤った時間に表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-499">Addressed an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="3f580-500">ユーザーが Outlook のルールを更新すると、「このコンピューターのルールは、Microsoft Exchange のルールと異なります」というメッセージが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-500">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="3f580-501">[共有フォルダーのダウンロード] がチェックされていない場合、共有された予定表の会議の [返信オプション] に [転送を許可する] オプションが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-501">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="3f580-502">メール メッセージからカテゴリが消えることがあるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-502">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="3f580-503">共有メールボックスに対して、異なるマシン上の別のフォルダー階層が代理人に表示されるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-503">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="3f580-504">管理者のカレンダー上で既存のカレンダーの予定を編集するときに代理人がエラーを受け取る問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-504">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="3f580-505">件名を編集した後、NDR メッセージの本文が Unicode から ASCII に変更される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-505">Addressed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="3f580-506">2 つのアドインが同じリボン グループにボタンを追加するときにユーザーにクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-506">Addressed an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="3f580-507">ユーザーが個人用配布リストにメールを送信できなくなった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-507">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="3f580-508">テナントの既定のアクセス許可が「全員」として構成されている場合に、適切なテナントの既定のアクセス許可を使用して、リンクがメールに追加されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-508">Addressed an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as"anyone".</span></span>

- <span data-ttu-id="3f580-509">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカルコンピューターに保存できない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-509">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="word"></a><span data-ttu-id="3f580-510">Word</span><span class="sxs-lookup"><span data-stu-id="3f580-510">Word</span></span>

- <span data-ttu-id="3f580-511">ポリシー FileBlick\Word2007Files を有効にしたときの共同編集に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-511">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="3f580-512">名前が変更されたルックアップ フィールドを追加するときに Word QuickPart が機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-512">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="3f580-513">Office スイート</span><span class="sxs-lookup"><span data-stu-id="3f580-513">Office Suite</span></span>

- <span data-ttu-id="3f580-514">大規模な PowerPoint ファイルの共同編集中に、ユーザーがネットワークと CPU の使用率が過剰になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-514">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="3f580-515">以前の AppV51 の回帰を修正するために、新しい AppV51 drop をバックポートします。</span><span class="sxs-lookup"><span data-stu-id="3f580-515">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="3f580-516">レジストリ TabProcGrowth の値がREG_SZ型でアドインがアクティブ化されている場合に、Windows の Office ホストがクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-516">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-june-09"></a><span data-ttu-id="3f580-518">バージョン 2002: 6 月 9 日</span><span class="sxs-lookup"><span data-stu-id="3f580-518">Version 2002: June 09</span></span>
<span data-ttu-id="3f580-519">*バージョン 2002 (ビルド 12527.20720)*</span><span class="sxs-lookup"><span data-stu-id="3f580-519">*Version 2002 (Build 12527.20720)*</span></span>

<span data-ttu-id="3f580-520">セキュリティ更新プログラムのリストは[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f580-520">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="3f580-522">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="3f580-522">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3f580-523">Excel</span><span class="sxs-lookup"><span data-stu-id="3f580-523">Excel</span></span>

- <span data-ttu-id="3f580-524">ファイル パスが長すぎる場合にファイルをもう一度開くと、外部リンクが機能しなくなった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-524">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="3f580-525">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-525">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="3f580-526">印刷時にフォーム コントロールのチェックボックスが拡大縮小されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-526">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="3f580-527">従来の "共有ブック" モードを使用して、ブックの新しいシートに変更を一覧表示しようとすると、クラッシュが発生する場合がありました。</span><span class="sxs-lookup"><span data-stu-id="3f580-527">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="3f580-528">フィルター処理されたリストに列を挿入すると、通常よりも時間がかかっていました。</span><span class="sxs-lookup"><span data-stu-id="3f580-528">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="3f580-529">数式を開始する @ 記号が暗黙的な論理積演算子と見なされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-529">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

### <a name="outlook"></a><span data-ttu-id="3f580-530">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f580-530">Outlook</span></span>

- <span data-ttu-id="3f580-531">ネイティブの Teams クライアントを介して Teams 会議に直接参加できます。</span><span class="sxs-lookup"><span data-stu-id="3f580-531">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="3f580-532">M365 Business Plus プランのサービスを利用していたユーザーがデータ損失防止の保護ポリシー ヒントを有効にできない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-532">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="3f580-533">間違ったブラウザー エミュレーション設定でユーザーが Gmail の認証プロンプトを完了できなくなるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-533">Addressed an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="3f580-534">サーバー オペレーティング システムの Outlook ユーザーに「ウイルス対策ステータス: 無効」のエラーを表示する原因となっていた問題に対処しました。 </span><span class="sxs-lookup"><span data-stu-id="3f580-534">Addressed an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="3f580-535">このバージョンの Windows はウイルス検出をサポートしていますが、ウイルス対策を適切に構成してもウイルス対策ソフトウェアが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="3f580-535">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

### <a name="word"></a><span data-ttu-id="3f580-536">Word</span><span class="sxs-lookup"><span data-stu-id="3f580-536">Word</span></span>

- <span data-ttu-id="3f580-537">クイック印刷を使用して印刷した後に編集しようとしたときに、ドキュメント内の単語の配置が乱れてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-537">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

### <a name="office-suite"></a><span data-ttu-id="3f580-538">Office スイート</span><span class="sxs-lookup"><span data-stu-id="3f580-538">Office Suite</span></span>

- <span data-ttu-id="3f580-539">この問題を解決するため、Backstage のチャネル名を 2020 年 1 月のフォークにある新しいチャネル名に更新しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-539">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="3f580-540">この問題は修正されましたが、今後、デバイスがポリシー管理されている場合、DMS の対象ユーザー API は呼び出されません。</span><span class="sxs-lookup"><span data-stu-id="3f580-540">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="3f580-541">単一のトランザクションでアプリを追加および削除したときに、削除が不完全になるという問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-541">Resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="3f580-542">HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth のレジストリ キーが0に設定されている場合、アドインがアクティブになり、Windows で Office ホストがクラッシュしました。</span><span class="sxs-lookup"><span data-stu-id="3f580-542">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="3f580-543">この変更により、この問題は修正されます。</span><span class="sxs-lookup"><span data-stu-id="3f580-543">This change would fix this issue.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-may-12"></a><span data-ttu-id="3f580-545">バージョン 2002: 5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="3f580-545">Version 2002: May 12</span></span>
<span data-ttu-id="3f580-546">*バージョン 2002 (ビルド 12527.20612)*</span><span class="sxs-lookup"><span data-stu-id="3f580-546">*Version 2002 (Build 12527.20612)*</span></span>

<span data-ttu-id="3f580-547">セキュリティ更新プログラムのリストは[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f580-547">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="3f580-549">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="3f580-549">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="3f580-550">Excel</span><span class="sxs-lookup"><span data-stu-id="3f580-550">Excel</span></span>

- <span data-ttu-id="3f580-551">特に非表示のウィンドウで、多数のその他のブックを参照しながらブックを開くと、予想よりも時間がかかります。</span><span class="sxs-lookup"><span data-stu-id="3f580-551">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="3f580-552">状況によっては、CSV ファイルを開くのに予想より時間がかかっていました。</span><span class="sxs-lookup"><span data-stu-id="3f580-552">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="3f580-553">Excel では、異なる拡大レベルでブックを切り替えるとクラッシュすることがあります。</span><span class="sxs-lookup"><span data-stu-id="3f580-553">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="3f580-554">値の範囲への入力に予想より時間がかかる VBA の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-554">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="3f580-555">色でフィルター処理された列からコピーしたデータは、正しく貼り付けられない場合があります。</span><span class="sxs-lookup"><span data-stu-id="3f580-555">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="3f580-556">ピボットテーブルを含むシートをコピーした後、Excel がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-556">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="3f580-557">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="3f580-557">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="3f580-558">グラフの軸の "Value Crosses At" プロパティが、ファイルを保存してもう一度開くときに予期せず変更されるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-558">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="3f580-559">Range.Value と Range.Value2 (VBA) を使用すると、数式は動的配列として入力されます。</span><span class="sxs-lookup"><span data-stu-id="3f580-559">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

### <a name="onenote"></a><span data-ttu-id="3f580-560">OneNote</span><span class="sxs-lookup"><span data-stu-id="3f580-560">OneNote</span></span>

- <span data-ttu-id="3f580-561">同期およびサービスの安定性を改善するために、OneNote ユーザー エクスペリエンスで実行されている一時的な手段についての詳細情報をユーザーが学べるようにする通知をローカライズします。</span><span class="sxs-lookup"><span data-stu-id="3f580-561">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="3f580-562">同期およびサービスの安定性を改善するために、OneNote ユーザー エクスペリエンスで実行されている一時的な手段についての詳細情報をユーザーが学べるようにする通知を表示します。</span><span class="sxs-lookup"><span data-stu-id="3f580-562">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="3f580-563">OneNote 2016 のバージョン履歴ページの数と同期頻度を一時的に減らすことで、同期およびサービスの安定性を改善しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-563">Improved sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="3f580-564">OneNote 2016 のごみ箱を一時的に無効にすることにより、同期およびサービスの安定性を改善しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-564">Improved sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="3f580-565">ユーザーが、通常はごみ箱に送られるデータを削除しようとすると、データを保持するか、完全に削除するかを確認するメッセージが表示されます。</span><span class="sxs-lookup"><span data-stu-id="3f580-565">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="3f580-566">OneNote 2016 で同期頻度を一時的に調整することで、同期およびサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-566">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="3f580-567">ユーザーが OneNote 2016 のページに移動するまで、オンライン ノートブックの埋め込みファイルおよび画像のダウンロードを一時的に遅らせることで、同期およびサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-567">Improved sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="3f580-568">OneNote 2016 でアプリ内動画のレコーディングを一時的に無効にすることで、同期およびサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-568">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="3f580-569">ローカルのノートブックはこの影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="3f580-569">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="3f580-570">OneNote 2016 に 50 MB へ埋め込まれた新しい添付ファイルの最大許容サイズが一時的に減少することにより、同期とサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-570">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="3f580-571">この制限を超えるファイルの場合、ユーザーは OneDrive にファイルをアップロードして、OneNote にリンクを挿入することができます。</span><span class="sxs-lookup"><span data-stu-id="3f580-571">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

### <a name="outlook"></a><span data-ttu-id="3f580-572">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f580-572">Outlook</span></span>

- <span data-ttu-id="3f580-573">フォルダー ウィンドウの幅が予期せず変更される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-573">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="3f580-574">ユーザーが Windows Update の後に .msg および .oft ファイルを開こうとするとクラッシュが起きるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-574">Addressed an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="3f580-575">大きな HTML メッセージを転送するとき、ユーザーにメッセージ本文の全体が表示されないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-575">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="3f580-576">この更新プログラムでは、メッセージの表示または作成時に Microsoft Outlook で現在の機密ラベルが表示されないという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="3f580-576">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="3f580-577">ユーザーが個人用配布リストにメールを送信できなくなった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-577">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="3f580-578">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f580-578">PowerPoint</span></span>

- <span data-ttu-id="3f580-579">問題の修正により、改善済みのコメントが入ったファイルのコピーを開くユーザーに正しいメッセージを送れるようになりました。</span><span class="sxs-lookup"><span data-stu-id="3f580-579">Fixed an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="word"></a><span data-ttu-id="3f580-580">Word</span><span class="sxs-lookup"><span data-stu-id="3f580-580">Word</span></span>

- <span data-ttu-id="3f580-581">インストールされている言語によって Access と Publisher が正常に起動しなかった問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-581">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>

- <span data-ttu-id="3f580-582">編集用に保護されたドキュメントの比較機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-582">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="3f580-583">2 つのドキュメントを 1 つのドキュメントに結合するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-583">We fixed an issue when merging 2 documents into one document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="3f580-584">Office スイート</span><span class="sxs-lookup"><span data-stu-id="3f580-584">Office Suite</span></span>

- <span data-ttu-id="3f580-585">これは、ファイルがクライアントにキャッシュされるときに Project アプリがネットワークをブロックしないようにするための修正プログラムです。</span><span class="sxs-lookup"><span data-stu-id="3f580-585">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>

- <span data-ttu-id="3f580-586">ログ記録して続行するのではなく、内部操作により失敗時に例外がスローされていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-586">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="3f580-587">影響を受けるユーザーは、更新プログラムの受信をブロックされなくなります。</span><span class="sxs-lookup"><span data-stu-id="3f580-587">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="3f580-588">この変更により、リボンのスケッチされたアウトラインは正常に機能するようになります。</span><span class="sxs-lookup"><span data-stu-id="3f580-588">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="3f580-589">特定のプロキシの構成でオンプレミスの場所からファイルを開く際の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-589">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="3f580-590">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="3f580-590">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="3f580-591">この更新プログラムでは、Microsoft Office で PATH 環境変数で指定した場所を検索することによって参照される可能性がある Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA ランタイムエラーが発生するという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="3f580-591">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="3f580-592">この更新プログラムでは、Microsoft Word で、ラベル ポリシーにヘッダーやフッターまたは透かしが適用されている場合にラベルを変更または削除すると、 255 文字を超える文字の挿入されたテキストが識別および削除できなかった問題が修正されています。</span><span class="sxs-lookup"><span data-stu-id="3f580-592">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

- <span data-ttu-id="3f580-593">問題を解決し、Office のハンドオフ セッション中のクラッシュを解消し、ユーザー エクスペリエンスの信頼性を向上させました。</span><span class="sxs-lookup"><span data-stu-id="3f580-593">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>  

- <span data-ttu-id="3f580-594">このバグは、Enhanced Configuration Service (ECS) url エンドポイントを更新します。</span><span class="sxs-lookup"><span data-stu-id="3f580-594">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="3f580-595">この新しいエンドポイントを呼び出すと、ECS からのフェッチ成功率が高くなります。</span><span class="sxs-lookup"><span data-stu-id="3f580-595">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

[//]: # (バグの詳細コンテンツを削除しないでください。終了)

## <a name="version-2002-april-14"></a><span data-ttu-id="3f580-597">バージョン 2002: 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="3f580-597">Version 2002: April 14</span></span>
<span data-ttu-id="3f580-598">*バージョン 2002 (ビルド 12527.20442)*</span><span class="sxs-lookup"><span data-stu-id="3f580-598">*Version 2002 (Build 12527.20442)*</span></span>

<span data-ttu-id="3f580-599">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f580-599">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


### <a name="feature-updates"></a><span data-ttu-id="3f580-600">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="3f580-600">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="3f580-601">Excel</span><span class="sxs-lookup"><span data-stu-id="3f580-601">Excel</span></span>

- <span data-ttu-id="3f580-602">**複数の値を返す式を入力する:** 複数の値を返す式を素早く入力できるようになりました。隣接するセルに自動的に入力されます。</span><span class="sxs-lookup"><span data-stu-id="3f580-602">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="3f580-603">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-603">Learn more</span></span>](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="3f580-604">**6 つの強力な機能:** スプレッドシートを強化する 6 つの新しい関数が追加されました。FILTER、SORT、SORTBY、UNIQUE、SEQUENCE、RANDARRAY です。</span><span class="sxs-lookup"><span data-stu-id="3f580-604">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span>  [<span data-ttu-id="3f580-605">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-605">Learn more</span></span>](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="3f580-606">**左を見て、右を見て... XLOOKUP をご利用いただけます!** XLOOKUP を使えば、表や範囲内で必要なものは何でも見つけられます。</span><span class="sxs-lookup"><span data-stu-id="3f580-606">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span>  <span data-ttu-id="3f580-607">
  [詳細情報](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span><span class="sxs-lookup"><span data-stu-id="3f580-607">[Learn more](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="3f580-609">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="3f580-609">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3f580-610">Excel</span><span class="sxs-lookup"><span data-stu-id="3f580-610">Excel</span></span>

- <span data-ttu-id="3f580-611">Word または PowerPoint に埋め込まれたブックをもう一度開くと、場合によっては Excel がクラッシュする可能性があります。</span><span class="sxs-lookup"><span data-stu-id="3f580-611">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="3f580-612">CSV ファイルとして保存する場合、Excel はすべての列を 1 つの列にマージする場合があります。</span><span class="sxs-lookup"><span data-stu-id="3f580-612">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="3f580-613">保護されたシートの範囲で Range.ClearContents を使用すると、予想よりも時間がかかる場合があります。</span><span class="sxs-lookup"><span data-stu-id="3f580-613">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="3f580-614">[印刷プレビュー] に表示されるときのフォーム コントロール内のテキストの拡大縮小に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-614">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="3f580-615">リボンを操作する VBA マクロは、ScreenUpdating が True に設定されていると予期せず実行される場合があります。</span><span class="sxs-lookup"><span data-stu-id="3f580-615">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="3f580-616">ソース ブックが閉じていると、外部リンクが塗りつぶし(下方向に塗りつぶし、全体に塗りつぶしなど) 時に更新されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-616">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is closed.</span></span>

- <span data-ttu-id="3f580-617">VBA の Application.Evaluate が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="3f580-617">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="3f580-618">テンプレートからグラフを作成するときに発生するパフォーマンスの問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-618">Addressed a performance issue when creating charts from templates.</span></span>


### <a name="outlook"></a><span data-ttu-id="3f580-619">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f580-619">Outlook</span></span>

- <span data-ttu-id="3f580-620">一部のシナリオで、グループ ヘッダーが予期せず拡張される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-620">Addressed an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="3f580-621">特定の検索結果を選択すると、ユーザーがクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-621">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="3f580-622">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-622">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="3f580-623">[添付ファイル ​​ツール] に [クラウドに保存] ボタンが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-623">Addressed an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="3f580-624">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f580-624">PowerPoint</span></span>

- <span data-ttu-id="3f580-625">コピーと貼り付けのシナリオを改善しました。PowerPoint スライドでの図形のコピーと、ループ内の他のスライドへの貼り付けが例外で失敗する場合があります。</span><span class="sxs-lookup"><span data-stu-id="3f580-625">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="3f580-626">Project</span><span class="sxs-lookup"><span data-stu-id="3f580-626">Project</span></span>

- <span data-ttu-id="3f580-627">以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-627">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="3f580-628">[無効化] ボタンを介してタスクが非アクティブ化/アクティブ化された場合に、ProjectBeforeTaskChange イベントが検出しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-628">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

### <a name="word"></a><span data-ttu-id="3f580-629">Word</span><span class="sxs-lookup"><span data-stu-id="3f580-629">Word</span></span>

- <span data-ttu-id="3f580-630">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-630">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="3f580-631">表内のテキストに合わせる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-631">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="3f580-632">水平線の挿入が短くなく、中央に配置されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-632">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-march-10"></a><span data-ttu-id="3f580-634">バージョン 2002: 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="3f580-634">Version 2002: March 10</span></span>
<span data-ttu-id="3f580-635">*バージョン 2002 (ビルド 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="3f580-635">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="3f580-636">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f580-636">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="3f580-638">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="3f580-638">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="3f580-639">Access</span><span class="sxs-lookup"><span data-stu-id="3f580-639">Access</span></span>

- <span data-ttu-id="3f580-640">**リンク テーブルをすばやく見つける:** 新しい検索ボックスを使用すると、リンク テーブルを簡単に見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="3f580-640">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="3f580-641">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-641">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="3f580-642">Excel</span><span class="sxs-lookup"><span data-stu-id="3f580-642">Excel</span></span>

- <span data-ttu-id="3f580-643">**\@メンションを使用してユーザーの注意を引く:** コメントで @メンションを使うと、仕事仲間による入力が必要な場合にそのユーザーに知らせることができます。</span><span class="sxs-lookup"><span data-stu-id="3f580-643">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="3f580-644">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-644">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="3f580-645">**探しているものを見つける:** コマンド、ユーザー、ファイル、写真、Web の記事などを検索できます。</span><span class="sxs-lookup"><span data-stu-id="3f580-645">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="3f580-646">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-646">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="3f580-647">**あらましを描く:** ブック内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="3f580-647">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="3f580-648">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-648">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="3f580-649">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="3f580-649">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="3f580-650">**ブラウザーへのバウンスは不要:** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定することができます。</span><span class="sxs-lookup"><span data-stu-id="3f580-650">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="3f580-651">**残っている作業に集中する:** [解決] を選択して、コメントを折りたたみ、開いているアイテムを目立たせます。</span><span class="sxs-lookup"><span data-stu-id="3f580-651">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="3f580-652">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="3f580-652">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="3f580-653">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-653">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="3f580-654">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="3f580-654">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="3f580-655">**データ ビジュアライザー アドイン:** Excel から Visio フローチャートをすばやく作成します。</span><span class="sxs-lookup"><span data-stu-id="3f580-655">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="3f580-656">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-656">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="3f580-657">**すぐに読んで返信する**: ブックを開かずに、メールからコメントやメンションに直接返信します。</span><span class="sxs-lookup"><span data-stu-id="3f580-657">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="3f580-658">**ブックの統計を取得する:** ブックの統計情報にはブックの内容の概要が示されるので、コンテンツをより簡単に見つけ出せます。</span><span class="sxs-lookup"><span data-stu-id="3f580-658">**Get stats on your workbook:** Workbook Statistics provides an overview of the content of a workbook, to help you more easily discover its contents.</span></span>

- <span data-ttu-id="3f580-659">**自分の気分を表現するアイコンの追加:** 300 個以上の新しいアイコンが追加されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-659">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="3f580-660">[挿入]、[アイコン] の順に検索してください。</span><span class="sxs-lookup"><span data-stu-id="3f580-660">Find them at Insert > Icons.</span></span> [<span data-ttu-id="3f580-661">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-661">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a><span data-ttu-id="3f580-662">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f580-662">Outlook</span></span>

- <span data-ttu-id="3f580-663">**Outlook に LinkedIn ネットワークを接続する:** LinkedIn アカウントを Microsoft アカウントに安全に接続して、LinkedIn プロファイルからの情報を [連絡先カード] に直接表示できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="3f580-663">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="3f580-664">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-664">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="3f580-p158">**すべての暗号化オプションを 1 か所に集約:** [オプション] > [暗号化] の順に移動するだけで、電子メール メッセージを保護する方法を選択できます。[詳細情報](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="3f580-p158">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="3f580-667">**テナント管理者によって定義されたアクセス許可を使用して、Outlook の [リンクの挿入] メニューでリンクを挿入する:** Outlook で最近使用されたリンクの挿入 (MRU) のリンクでは、既にそれに対するアクセス許可を持つユーザーのみに動作したリンクが挿入されます。</span><span class="sxs-lookup"><span data-stu-id="3f580-667">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="3f580-668">これは、ドキュメントへのアクセス権の付与を求めるユーザー間でのメールの行き来をしばしば引き起こします。</span><span class="sxs-lookup"><span data-stu-id="3f580-668">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="3f580-669">このエクスペリエンスが更新されましたので、テナント管理者によって設定される既定のアクセス許可を使用し、リンクを挿入できるようになりました。MSIT の場合、これは「組織は編集可」なので、この方法で共有されるリンクを受信するすべての内部ユーザーもアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="3f580-669">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="3f580-670">**スペルチェックの問題や入力ミスで検索する:** スペルが一致しない場合でも何を検索しているか Outlook が探します。</span><span class="sxs-lookup"><span data-stu-id="3f580-670">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="3f580-671">**フィッシング メールの見分けが簡単に:** スパムとフィッシングのメッセージの外観が他とは異なるので、簡単に見分け、受信トレイから削除できます。</span><span class="sxs-lookup"><span data-stu-id="3f580-671">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="3f580-672">**攻撃に対する高度な保護:** Office 365 Advanced Threat Protection を用いると、メールの件名、添付メッセージ、署名されたメッセージ、ネットワーク パスなどの範囲内のハイパーリンクを利用した攻撃から保護されます。</span><span class="sxs-lookup"><span data-stu-id="3f580-672">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="3f580-673">**自分で描いて表現しましょう:** 画像の上に走り書きするか、描画キャンバスを追加して、インクを用いて自分の考えを送信します。</span><span class="sxs-lookup"><span data-stu-id="3f580-673">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="3f580-674">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-674">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="3f580-675">**検索結果で関連メッセージを確認する:** Outlook では検索条件を分析し、最も関連性の高いメール メッセージを検索結果の上部に表示します。</span><span class="sxs-lookup"><span data-stu-id="3f580-675">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="3f580-676">また、[上位の結果] セクションには、すべての結果が日付順に表示されます。</span><span class="sxs-lookup"><span data-stu-id="3f580-676">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="3f580-677">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-677">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- <span data-ttu-id="3f580-678">**場所の候補を取得する:** 予定や会議をスケジュールするときに、[場所] に入力すると、会議室、住所、およびその他の最新の場所が提示されます。</span><span class="sxs-lookup"><span data-stu-id="3f580-678">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="3f580-679">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-679">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="3f580-680">**より多くのメッセージを画面に収める:** [表示] > [より狭い文字間隔を使用] の順に選択し、メッセージの間隔を調整します。</span><span class="sxs-lookup"><span data-stu-id="3f580-680">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="3f580-681">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-681">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="3f580-682">**異なる明るさでメッセージを表示する:** [太陽] または [月] のボタンを使用して、閲覧ウィンドウの明るい背景と暗い背景を切り替えます。</span><span class="sxs-lookup"><span data-stu-id="3f580-682">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="3f580-683">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-683">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="3f580-684">**自分の気分を表現するアイコンの追加:** 300 個以上の新しいアイコンが追加されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-684">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="3f580-685">[挿入]、[アイコン] の順に検索してください。</span><span class="sxs-lookup"><span data-stu-id="3f580-685">Find them at Insert > Icons.</span></span> [<span data-ttu-id="3f580-686">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-686">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a><span data-ttu-id="3f580-687">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f580-687">PowerPoint</span></span>

- <span data-ttu-id="3f580-688">**PowerPoint におけるリアルタイム コラボレーションが高速に:** PowerPoint でリアルタイム コラボレーションを高速で行えます。</span><span class="sxs-lookup"><span data-stu-id="3f580-688">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="3f580-689">**新しい文書校正ツール:** 記述する内容についてストレスを感じる必要はありません。</span><span class="sxs-lookup"><span data-stu-id="3f580-689">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="3f580-690">PowerPoint で、文法や書き方の推奨事項が提示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="3f580-690">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="3f580-691">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-691">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="3f580-692">**ライブ キャプションと字幕:** 発表者の言葉が、キャプションまたは選択した言語での字幕として自動的に画面に表示されます。</span><span class="sxs-lookup"><span data-stu-id="3f580-692">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="3f580-693">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-693">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="3f580-694">**手書きの数式の自動書式設定:** 手書きの数式を標準の文字に変換することができます。</span><span class="sxs-lookup"><span data-stu-id="3f580-694">**You compute, we format:** We change hand-drawn math expressions into standard characters.</span></span> <span data-ttu-id="3f580-695">変換を開始するには、[インクから数式] を選択して、手書きのメモを選択します。</span><span class="sxs-lookup"><span data-stu-id="3f580-695">Just choose Ink to Math and select your handwritten notes to get started.</span></span> [<span data-ttu-id="3f580-696">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-696">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="3f580-697">**探しているものを見つける:**[検索] ボックスを使用して、テキスト、コマンド、ヘルプなどを探します。</span><span class="sxs-lookup"><span data-stu-id="3f580-697">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="3f580-698">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-698">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="3f580-699">**欠落しているスライド タイトルを見つけて修正する:** スライド タイトルは、ピッチにパンチを加え、すべてのユーザーがスライドにアクセスできるようにします。</span><span class="sxs-lookup"><span data-stu-id="3f580-699">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="3f580-700">アクセシビリティ ​​チェックは、タイトルがない場所を表示します。これにより、タイトルを簡単に追加できます。</span><span class="sxs-lookup"><span data-stu-id="3f580-700">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="3f580-701">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-701">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="3f580-702">**あらましを描く:** プレゼンテーション内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="3f580-702">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="3f580-703">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-703">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="3f580-704">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="3f580-704">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="3f580-705">**ブラウザーへのバウンスは不要:** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定することができます。</span><span class="sxs-lookup"><span data-stu-id="3f580-705">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="3f580-706">**図を SVG として保存する:** グラフ、図形、その他の図を、サイズ変更しても画質が低下しないスケーラブル ベクター グラフィックとして保存できます。</span><span class="sxs-lookup"><span data-stu-id="3f580-706">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="3f580-707">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-707">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="3f580-708">**配布資料にスライド番号を印刷する:** スライド番号は配布資料に自動的に含まれます。</span><span class="sxs-lookup"><span data-stu-id="3f580-708">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="3f580-709">それらをオンのままにするか、オフにするか、選択します。</span><span class="sxs-lookup"><span data-stu-id="3f580-709">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="3f580-710">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-710">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="3f580-711">**インクを瞬時に再生:** スライドで手描き入力する場合は、スライド ショー中にアニメーションの再生を適用して、インクの実際の描画が再生されるようにします。</span><span class="sxs-lookup"><span data-stu-id="3f580-711">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="3f580-712">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-712">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="3f580-713">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="3f580-713">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

- <span data-ttu-id="3f580-714">**プレゼンテーションの最適化:** アクセシビリティ チェックを使用すると、スクリーン リーダーを考慮に入れて、スライド上のオブジェクトを配置することができます。</span><span class="sxs-lookup"><span data-stu-id="3f580-714">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="3f580-715">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="3f580-715">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="3f580-716">**より安全なビデオ エクスペリエンス:** セキュリティの強化は、より安全なオンライン ビデオ エクスペリエンスを意味します。</span><span class="sxs-lookup"><span data-stu-id="3f580-716">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="3f580-717">**再利用しませんか?:** 作成した、または他のユーザーと共有しているスライドを再利用して時間を節約します。</span><span class="sxs-lookup"><span data-stu-id="3f580-717">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="3f580-718">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-718">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- <span data-ttu-id="3f580-719">**手書きのインクを図形やテキスト、または Office 365 の PowerPoint での数式に変換する:** フリーフォームのインクを Office の図形、テキスト、数式に数ストロークで変換します。</span><span class="sxs-lookup"><span data-stu-id="3f580-719">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="3f580-720">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-720">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="3f580-721">**インクで素晴らしいスライドを作成する:** インクを標準的な図形やテキストに変換してから、PowerPoint デザイナーの洗練されたスライドのデザイン アイデアを活用できます。</span><span class="sxs-lookup"><span data-stu-id="3f580-721">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="3f580-722">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-722">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="3f580-723">**自分の気分を表現するアイコンの追加:** 300 個以上の新しいアイコンが追加されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-723">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="3f580-724">[挿入]、[アイコン] の順に検索してください。</span><span class="sxs-lookup"><span data-stu-id="3f580-724">Find them at Insert > Icons.</span></span> [<span data-ttu-id="3f580-725">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-725">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a><span data-ttu-id="3f580-726">Visio</span><span class="sxs-lookup"><span data-stu-id="3f580-726">Visio</span></span>

- <span data-ttu-id="3f580-727">**犯行現場に戻る:** [犯罪現場] 調査テンプレートで新しい [証拠]、[室内]、および [屋外] のステンシルを使用して、犯罪現場を詳細に再現します。</span><span class="sxs-lookup"><span data-stu-id="3f580-727">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

- <span data-ttu-id="3f580-728">**Excel で洗練された Visio 図を作成する:** ワークシートにデータを入力して、フロー チャートまたは組織図を作成します。</span><span class="sxs-lookup"><span data-stu-id="3f580-728">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="3f580-729">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-729">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="3f580-730">Word</span><span class="sxs-lookup"><span data-stu-id="3f580-730">Word</span></span>

- <span data-ttu-id="3f580-731">**Editor for Resume が LinkedIn 履歴書アシスタントに参加する:** Editor for Resume では履歴書に特化した文法とスタイルのチェックを選択できます。この機能は、より正確かつ専門的に作成するの役立ちます。</span><span class="sxs-lookup"><span data-stu-id="3f580-731">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="3f580-732">**3D オブジェクトのマージによって引き起こされるドキュメント破損の問題を修正しました。:** 3D オブジェクトのマージによって引き起こされるドキュメント破損の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-732">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="3f580-733">**探しているものを見つける:**[検索] ボックスを使用して、テキスト、コマンド、ヘルプなどを探します。</span><span class="sxs-lookup"><span data-stu-id="3f580-733">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="3f580-734">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-734">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="3f580-735">**鮮やかな色で共同作業する:** コメントや変更内容のカラー コードが共同作成者によって指定され、共同作成者のうちのだれによって行われたかが簡単にわかります。</span><span class="sxs-lookup"><span data-stu-id="3f580-735">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="3f580-736">**マクロ有効文書を共同作業で編集する:** 文書ファイルを OneDrive for Business に保存し、リアルタイムで共同作成者は編集できます。</span><span class="sxs-lookup"><span data-stu-id="3f580-736">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

- <span data-ttu-id="3f580-737">**共同編集の改善**: 変更を追跡したドキュメントで共同編集を行う際の Word のパフォーマンスが改善されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-737">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="3f580-738">**自分の気分を表現するアイコンの追加:** 300 個以上の新しいアイコンが追加されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-738">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="3f580-739">[挿入]、[アイコン] の順に検索してください。</span><span class="sxs-lookup"><span data-stu-id="3f580-739">Find them at Insert > Icons.</span></span> [<span data-ttu-id="3f580-740">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-740">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="3f580-741">**他のユーザーがすばやく変更を確認する:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="3f580-741">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="3f580-742">**あらましを描く:** ドキュメント内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="3f580-742">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="3f580-743">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-743">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="3f580-744">**精度による消去:** 手描き入力の小さな不備を修正するのに、2 つのサイズの消しゴムから選択できます。</span><span class="sxs-lookup"><span data-stu-id="3f580-744">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="3f580-745">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-745">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="3f580-746">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="3f580-746">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="3f580-747">**ブラウザーへのバウンスは不要** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定します。</span><span class="sxs-lookup"><span data-stu-id="3f580-747">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="3f580-748">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-748">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="3f580-749">**共同編集の改善:** 共同編集時の信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-749">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="3f580-750">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="3f580-750">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="3f580-751">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-751">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="3f580-752">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="3f580-752">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="3f580-753">**より安全なビデオ エクスペリエンス:** セキュリティの強化は、より安全なオンライン ビデオ エクスペリエンスを意味します。</span><span class="sxs-lookup"><span data-stu-id="3f580-753">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="3f580-754">詳細情報</span><span class="sxs-lookup"><span data-stu-id="3f580-754">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="3f580-757">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="3f580-757">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="3f580-758">Access</span><span class="sxs-lookup"><span data-stu-id="3f580-758">Access</span></span>

- <span data-ttu-id="3f580-759">この更新プログラムにより、更新クエリが実行されるか、SQL で UPDATE ステートメントが使用されるときに "クエリは破損しています" というエラーを発生させる場合のある Microsoft Access の問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="3f580-759">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

- <span data-ttu-id="3f580-760">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="3f580-760">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="3f580-761">この更新プログラムでは、ADODB を使用する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="3f580-761">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="3f580-762">VB コードのれコーター オブジェクトがエラーを誤って報告することがあります。</span><span class="sxs-lookup"><span data-stu-id="3f580-762">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="3f580-763">Access テンプレートは、データベース内の添付ファイル列のエラーを発生させることがなくなりました。</span><span class="sxs-lookup"><span data-stu-id="3f580-763">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="3f580-764">テンプレートのインスタンス化後に、データベースに添付ファイル フィールドを追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="3f580-764">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="3f580-765">Excel</span><span class="sxs-lookup"><span data-stu-id="3f580-765">Excel</span></span>

- <span data-ttu-id="3f580-766">署名の名前を変更したときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-766">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="3f580-767">この変更は、ソフトウェア レンダリングを活用することにより、特定の Intel グラフィック ドライバーの問題を回避します。</span><span class="sxs-lookup"><span data-stu-id="3f580-767">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="3f580-768">はみ出している列挙が含まれるセルで区切り位置を指定するとクラッシュが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-768">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="3f580-769">この更新によって、数式バーに予期したのとは異なるフォントでテキストが表示される原因となっていた問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-769">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="3f580-770">一部のロケールにおいて、[Text to Column] 機能が失敗することがあります。</span><span class="sxs-lookup"><span data-stu-id="3f580-770">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="3f580-771">非表示の名前付き範囲にアクセスすると、ユーザーにエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="3f580-771">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="3f580-772">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="3f580-772">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="3f580-773">スクロール後にセルを選択すると間違ったセルが選択されることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-773">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="3f580-774">信頼されていないネットワーク共有から保護されたファイルを編集する際に、Excel にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="3f580-774">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="3f580-775">一部のローカライズにおいて、[Text to Column] 機能が失敗することがあります。</span><span class="sxs-lookup"><span data-stu-id="3f580-775">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="3f580-776">非表示の名前付き範囲にアクセスすると、ユーザーにエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="3f580-776">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="3f580-777">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="3f580-777">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="3f580-778">一部のユーザーが埋め込みオブジェクトとリンク オブジェクト (OLE) で経験する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-778">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="3f580-779">ピボット グラフの右クリック メニューを修正して、[詳細の表示] オプションを有効にしました。</span><span class="sxs-lookup"><span data-stu-id="3f580-779">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="3f580-780">ブックが開かれていない状態で最近使用したファイルを検索するときに、クラッシュを発生させる原因となっていた可能性がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-780">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="3f580-781">ブックで外部リンクがある場合に複数のポップアップ ウィンドウで一部のユーザーに生じる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-781">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="3f580-782">コンテキスト メニューのコメント コマンドが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-782">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="3f580-783">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-783">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="3f580-784">CUBEVALUE 関数が間違った結果を返すことがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-784">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="3f580-785">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f580-785">Outlook</span></span>

- <span data-ttu-id="3f580-786">検索に関するフィードバックのエクスペリエンスで終了する原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-786">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="3f580-787">ユーザーがクラウド設定を取得する際に Outlook がフリーズする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-787">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="3f580-788">検索ボックスが高 DPI モードで不適切に表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-788">Addressed an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="3f580-789">ユーザーが Outlook プロセスでメモリ リークを観測する原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-789">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="3f580-790">状況によっては、表示された SMTP アドレスと一致しないアドレスに送信されたメールがユーザーに表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-790">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="3f580-791">この変更により、メッセージ ヘッダーに複数行の件名を表示できる機能が復元されます。</span><span class="sxs-lookup"><span data-stu-id="3f580-791">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="3f580-792">WebDAV の場所にファイルを保存できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-792">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="3f580-793">SMIME アルゴリズムの選択に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-793">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="3f580-794">サードパーティ製アプリケーションがメールを送信できない原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-794">Addressed an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="3f580-795">アカウント作成コンテキストからサポートに連絡しようとすると、ユーザーに [OK] ボタンのある空のメッセージ ボックスが表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-795">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="3f580-796">ユーザーがプロフィールの作成中にクラッシュを発生させる原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-796">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="3f580-797">同期のスライダーが小さい設定に設定されている場合でも、Outlook で予期せずすべてのメールが同期される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-797">Addressed an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="3f580-798">黒のテーマを持つユーザーが [差出人] ドロップダウンを表示すると、白色の背景に白いテキストが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-798">Addressed an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="3f580-799">ユーザーがアカウントのセットアップをキャンセルするときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-799">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="3f580-800">署名の名前を変更したときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-800">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="3f580-801">フラグ付きアイテムの強調表示を無効にするオプションが一部のシナリオで無視される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-801">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="3f580-802">ユーザーが [ルール] ダイアログを開くと、"このコンピューターのルールは、Microsoft Exchange のルールと異なります" というメッセージが表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-802">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="3f580-803">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-803">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="3f580-804">非常に長い Outlook セッションでメモリ リークを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-804">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="3f580-805">複数のウィンドウで同じアイテムを表示するとクラッシュする場合がある問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-805">Addressed an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="3f580-806">キーボード ショートカットを使用してメールボックス フォルダーを操作すると、ユーザーに顕著な遅延が発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-806">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="3f580-807">ユーザーが定期的な予定表の一部のインスタンスを開けない原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-807">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="3f580-808">Exchange 2010 サーバー上にメールボックスを持つユーザーが、予定表の項目に添付ファイルを追加するときに生じる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-808">Addressed an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="3f580-809">ユーザーがデジタル署名されたメッセージに返信するときに生じる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-809">Addressed an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="3f580-810">会議の [場所] フィールドが予期せず更新される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-810">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="3f580-811">会議の [場所] フィールドにあるコンマがセミコロンになる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-811">Addressed an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="3f580-812">会議をクリアした後、会議の場所が予期せずに会議に追加される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-812">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="3f580-813">ブラジルのタイムゾーンで設定された会議や予定に関連する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-813">Addressed issues relating to meetings and appointments set in the Brazilia time zone.</span></span>

- <span data-ttu-id="3f580-814">[アクセシビリティ チェック] ペインを閉じた後に「S」キーを押すと、メールが予期せず送信されたようにユーザーに表示される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-814">Addressed an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="3f580-815">これにより、Python による添付ファイルもブロックされるよう、Outlook の添付ファイルのブロック ロジックが更新されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-815">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="3f580-816">Web アドインがデジタル著作権管理 (DRM) メッセージにアクセスする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-816">Addressed an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="3f580-817">ユーザーがプロフィールの作成中にクラッシュを発生させる原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-817">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="3f580-818">署名の名前を変更したときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-818">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="3f580-819">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f580-819">PowerPoint</span></span>

- <span data-ttu-id="3f580-820">Shape.Paste メソッドを使用する際に発生する問題を解決しました。Shape.Paste メソッドを使用して図形をコピーして貼り付けるときに、貼り付けられた図形の選択内容が変更するという問題です。</span><span class="sxs-lookup"><span data-stu-id="3f580-820">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="3f580-821">従来の PPT コメントでコンテキスト メニューを使用するときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-821">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

### <a name="project"></a><span data-ttu-id="3f580-822">Project</span><span class="sxs-lookup"><span data-stu-id="3f580-822">Project</span></span>

- <span data-ttu-id="3f580-823">読み取り専用のプロジェクトを開いたときに複数のメッセージを取得する可能性があるという問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-823">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="3f580-824">作業時間固定タイプの達成率 100% のタスクで、達成率が誤って 100% 未満に計算される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-824">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

- <span data-ttu-id="3f580-825">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-825">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="3f580-826">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-826">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="3f580-827">Word</span><span class="sxs-lookup"><span data-stu-id="3f580-827">Word</span></span>

- <span data-ttu-id="3f580-828">既存のファイルを保存すると [名前を付けて保存] ダイアログが必ず表示され、ファイルは実際には保存されない場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-828">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="3f580-829">文書パーツ オーガナイザーに 「スタイル、文書パーツを変更しました」 という無効なアラートが表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="3f580-829">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="3f580-830">Office スイート</span><span class="sxs-lookup"><span data-stu-id="3f580-830">Office Suite</span></span>

- <span data-ttu-id="3f580-831">この変更により、マーカー付きの一部の散布図の表示が遅くなる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-831">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="3f580-832">この変更では、Intel Integrated GPU を使用するグラフィック アダプターに関して報告された問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="3f580-832">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="3f580-833">ODT と GPO の更新期限設定で、相対期限の設定後、初回のみしか機能しないバスが修正されました。修正により、2 回目以降の更新プログラムで相対期限を使用きるようになりました。</span><span class="sxs-lookup"><span data-stu-id="3f580-833">Fixed a bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="3f580-834">Office の更新プログラムが、意図したソース (ローカル共有、ネットワーク共有、構成マネージャー
で提供される場所など) からではなく、予期せずに Office CDN からファイルをダウンロードする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-834">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="3f580-835">同じ SharePoint ライブラリから Word/Excel/PowerPoint で複数のドキュメントが開かれている場合、最初に開いたドキュメントのみがポリシー コンプライアンスでスキャンされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-835">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-february-11"></a><span data-ttu-id="3f580-837">バージョン 1908: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="3f580-837">Version 1908: February 11</span></span>
<span data-ttu-id="3f580-838">*バージョン 1908 (ビルド 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="3f580-838">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="3f580-839">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f580-839">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="3f580-841">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="3f580-841">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3f580-842">Excel</span><span class="sxs-lookup"><span data-stu-id="3f580-842">Excel</span></span>

- <span data-ttu-id="3f580-843">この更新プログラムは、VBA を使用してグラフのヘッダー/フッターに画像を追加するたびにエラーが発生する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="3f580-843">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="3f580-844">グループ ボックス コントロールの境界線が印刷プレビューまたは印刷時に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-844">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="3f580-845">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="3f580-845">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="3f580-846">グラフを含むブックを保存すると、グラフ ヘッダーの画像のファイル サイズが大きくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-846">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="3f580-847">選択範囲を相互参照ブックと同期させ続けることにより、相互参照ブックの DBCS 文字が破損する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-847">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="3f580-848">自動調整を使用して行の高さを調整するときにチェック ボックスのコントロールが縮小される可能性があるという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-848">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="3f580-849">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f580-849">Outlook</span></span>

- <span data-ttu-id="3f580-850">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-850">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="3f580-851">競合メッセージの処理中にユーザーに同期エラーが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-851">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="3f580-852">Outlook の起動時にユーザーが [プロファイルの読み込み中] 画面でハングアップする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-852">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="3f580-853">ビューを変更すると、断続的なクラッシュが発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-853">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="3f580-854">Citrix 環境で 30 件を超える予定表を表示したときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-854">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="3f580-855">[こちら](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)は、以前のバージョンで文書化された個々の KB です。</span><span class="sxs-lookup"><span data-stu-id="3f580-855">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="3f580-856">ユーザーが OST と同期している共有予定表フォルダーに問題があり、これらのフォルダーを操作しようとするとアクセス許可エラーが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-856">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="3f580-857">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f580-857">PowerPoint</span></span>

- <span data-ttu-id="3f580-858">PowerPoint スライドでのコピーと貼り付けのシナリオである図形のコピーを改善しました。ループ内の他のスライドに貼り付けると例外で失敗する場合があります。</span><span class="sxs-lookup"><span data-stu-id="3f580-858">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="3f580-859">共同作業ユーザー間のパフォーマンスが低下する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-859">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="3f580-860">増分で開くファイルに、複数のメディア ストリームが埋め込まれたスライドが含まれている場合に発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-860">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="3f580-861">PowerPoint の初回起動時に、信頼されていないアドインに対してセキュリティ警告メッセージ バーが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-861">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="3f580-862">Project</span><span class="sxs-lookup"><span data-stu-id="3f580-862">Project</span></span>

- <span data-ttu-id="3f580-863">基本カレンダーが変更されたときにリソース カレンダーが更新されないために、実際の作業がタイムシートとプロジェクト計画の間で異なる場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-863">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="3f580-864">Word</span><span class="sxs-lookup"><span data-stu-id="3f580-864">Word</span></span>

- <span data-ttu-id="3f580-865">非推奨の API から移動することにより、Word でクラッシュが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-865">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="3f580-866">Office スイート</span><span class="sxs-lookup"><span data-stu-id="3f580-866">Office Suite</span></span>

- <span data-ttu-id="3f580-867">この変更は、破損したファイルを開いた後の画像の正しいレンダリングに対処します。</span><span class="sxs-lookup"><span data-stu-id="3f580-867">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-january-14"></a><span data-ttu-id="3f580-869">バージョン 1908: 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="3f580-869">Version 1908: January 14</span></span>
<span data-ttu-id="3f580-870">*バージョン 1908 (ビルド 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="3f580-870">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="3f580-871">セキュリティ更新プログラムの一覧は[こちら](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="3f580-871">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="3f580-873">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="3f580-873">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="3f580-874">Excel</span><span class="sxs-lookup"><span data-stu-id="3f580-874">Excel</span></span>

- <span data-ttu-id="3f580-875">ドキュメント タイトルのオランダ語の KeyTip が Alt-G に変更されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-875">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="3f580-876">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-876">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="3f580-877">アドインによって開かれた WPF (Windows Presentation Foundation) フォームのコンボ ボックスからアイテムを選ぶことができない問題が発生しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-877">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="3f580-878">Outlook</span><span class="sxs-lookup"><span data-stu-id="3f580-878">Outlook</span></span>

- <span data-ttu-id="3f580-879">キーボード ショートカットを使用してメールボックス フォルダーを操作すると、ユーザーに顕著な遅延が発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-879">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="3f580-880">代替送信者を使用しているときに、ポリシーのヒントが表示されない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-880">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="3f580-881">プレゼンス情報を更新するときに、断続的なクラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-881">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="3f580-882">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="3f580-882">PowerPoint</span></span>

- <span data-ttu-id="3f580-883">スライドを 1 つのプレゼンテーションから別のプレゼンテーションにコピーすると、重複したマスターが作成される可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-883">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>
- <span data-ttu-id="3f580-884">最新のコメントを含むファイルを、サポートされていないバージョンで開くと黄色の警告が表示されます</span><span class="sxs-lookup"><span data-stu-id="3f580-884">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

### <a name="office-suite"></a><span data-ttu-id="3f580-885">Office スイート</span><span class="sxs-lookup"><span data-stu-id="3f580-885">Office Suite</span></span>

- <span data-ttu-id="3f580-886">Office の更新メッセージが、異なる言語で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="3f580-886">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="3f580-887">今後、Office の更新メッセージは Windows の表示言語と一致します。</span><span class="sxs-lookup"><span data-stu-id="3f580-887">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="3f580-888">ユーザーが管理者ではなく、システム アカウントにネットワーク接続が確立されていない場合に、更新プログラムが適用されない問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="3f580-888">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

> [!NOTE]
> <span data-ttu-id="3f580-890">Office の使用で問題がある場合は、[Microsoft の回答フォーラム](https://answers.microsoft.com/)に関するページまたは「[Microsoft Tech Community](https://techcommunity.microsoft.com/)」に質問を投稿するか、[サポート](https://support.microsoft.com/contactus)に問い合わせてサポートを受けることができます。</span><span class="sxs-lookup"><span data-stu-id="3f580-890">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (管理センターのメタデータのコンテンツを変更しないでください。開始)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21064|version-2008-january-12|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20910|version-2008-december-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20760|version-2008-november-10|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20638|version-2008-october-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20408|version-2008-september-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20880|version-2002-july-14|)
[//]: # (管理センターのメタデータのコンテンツ エンドを変更しないでください)
