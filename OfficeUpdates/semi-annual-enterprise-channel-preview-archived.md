---
title: 2019 年半期チャネル (対象指定) リリースのアーカイブ済みリリース ノート
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Office 365 ProPlus 用の 2019 年半期チャネル (対象指定) リリースのリリース ノートを IT プロフェッショナルに提供します
ms.openlocfilehash: 72e2402dff445b9ec4b03c7241f93ee85b16bee2
ms.sourcegitcommit: 596cdb3423140df0324a952157fbc39ebedc12b9
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2021
ms.locfileid: "52278124"
---
# <a name="archived-release-notes-for-semi-annual-enterprise-channel-preview"></a><span data-ttu-id="8e8f4-103">半期エンタープライズ チャネル (プレビュー) のアーカイブ済みリリース ノート</span><span class="sxs-lookup"><span data-stu-id="8e8f4-103">Archived Release notes for Semi-Annual Enterprise Channel (Preview)</span></span>

<span data-ttu-id="8e8f4-104">これらのリリース ノートには、Visio Pro for Office 365、Project Online Desktop Client、Office 365 Business を含む、Office 365 ProPlus の半期エンタープライズ チャネル (プレビュー) の更新プログラムに含まれる新機能およびセキュリティ以外の更新に関する情報が記載されています。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates to Office 365 ProPlus, Visio Pro for Office 365, Project Online Desktop Client and Office 365 Business.</span></span>

> [!NOTE]
> - <span data-ttu-id="8e8f4-105">多くの場合、機能 (場合によっては修正プログラムも) は、特定の期間にわたって半期エンタープライズ チャネル (プレビュー) にロールアウトされます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-105">We often roll out features (and sometimes even fixes) to Semi-Annual Enterprise Channel (Preview) over a period of time.</span></span> <span data-ttu-id="8e8f4-106">ここで説明した内容がすぐに表示されない場合は、間もなく利用できるようになります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-106">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="8e8f4-107">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-107">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)


## <a name="version-2008-december-08"></a><span data-ttu-id="8e8f4-108">バージョン 2008: 12 月 08 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-108">Version 2008: December 08</span></span>
<span data-ttu-id="8e8f4-109">*バージョン 2008 (ビルド 13127.20910)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-109">*Version 2008 (Build 13127.20910)*</span></span>

<span data-ttu-id="8e8f4-110">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-110">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="8e8f4-112">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="8e8f4-112">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="8e8f4-113">Access</span><span class="sxs-lookup"><span data-stu-id="8e8f4-113">Access</span></span>

- <span data-ttu-id="8e8f4-114">ODBC DSNBuilder を使用しようとしたときに発生するエラーの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8e8f4-114">We fixed an error issue when trying to use ODBC DSN builder</span></span>


### <a name="excel"></a><span data-ttu-id="8e8f4-115">Excel</span><span class="sxs-lookup"><span data-stu-id="8e8f4-115">Excel</span></span>

- <span data-ttu-id="8e8f4-116">プロジェクト計画からエクスポートした場合、ピボットテーブルを編集できず、ワークブックを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-116">Fixed an issue where pivot tables could not be edited and workbooks could not be saved if they were exported from Project plan.</span></span>


- <span data-ttu-id="8e8f4-117">ファイルを読み取り専用モードで開いたときに、複数のメッセージ バーが表示される場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-117">We fixed an issue where in some cases, multiple message bars were appearing when a file was opened in read-only mode.</span></span>


- <span data-ttu-id="8e8f4-118">列ヘッダーの値が重複していると、アウトラインの小計が機能しなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-118">We fixed an issue where outline sub-totals could stop working when there were many duplicate column header values.</span></span>


- <span data-ttu-id="8e8f4-119">マルチ スレッドの再計算中にグループ ポリシー オブジェクトの更新 (リモート グループ ポリシーの更新など) が行われた場合に Excel が機能しなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-119">We fixed an issue where Excel would stop working when there is a Group Policy Object update (e.g. via Remote Group Policy Refresh) during multithreaded recalc.</span></span>


- <span data-ttu-id="8e8f4-120">ユーザーが 255 を超える列で subtotal 関数を使用すると、Excel が機能しなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-120">We fixed an issue where Excel would stop working when users use the subtotal function on more than 255 columns.</span></span>


- <span data-ttu-id="8e8f4-121">PowerPoint でコンテンツを Excel からコピーし、Embed オプションを使用して PowerPoint に貼り付けたときのテキスト カーニングを改善しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-121">Improved text kerning in PowerPoint when when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="8e8f4-122">PowerPivot のテーブルプレビューとクエリエディターからの切り替えができなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-122">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="8e8f4-123">ユーザーが SharePoint から .atomsvc (UTF8 + BOM) ファイルを直接開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-123">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="8e8f4-124">問題が修正され、Power Pivot がタブ区切り文字を正常に認識するようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-124">We fixed an issue where Power Pivot will now successfully recognize tab delimiter.</span></span>


### <a name="outlook"></a><span data-ttu-id="8e8f4-125">Outlook</span><span class="sxs-lookup"><span data-stu-id="8e8f4-125">Outlook</span></span>

- <span data-ttu-id="8e8f4-126">タスクのステータスレポートを送信するときに To: フィールドが空白になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-126">We fixed an issue that caused the To: field to be empty when sending a status report on a Task.</span></span>


- <span data-ttu-id="8e8f4-127">MailItem.BeforeAttachmentAdd イベントの破損原因となった問題が修正されました。 </span><span class="sxs-lookup"><span data-stu-id="8e8f4-127">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="8e8f4-128">Outlook 以外のアプリケーションから Outlook メールを送信するときに、一部のユーザーのアプリケーションが予期せず閉じる原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-128">We fixed an issue that was causing some users to experience the application to close unexpectedly when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="8e8f4-129">オンライン モードでフォルダ間で複数のメール アイテムを移動すると、ユーザーのパフォーマンスが低下する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-129">We fixed an issue that caused users to experience degraded performance when moving multiple mail items between folders in online mode.</span></span>


- <span data-ttu-id="8e8f4-130">IDataObject 操作 (つまりクリップボードのドラッグやドロップ) で、ユーザーが添付ファイルに対して filetime の付加を無効にできるように、regkey を追加しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-130">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="8e8f4-131">HKCU \ SOFTWARE \ Microsoft \ Office \ 16.0 \ Outlook \ Attachments REG_DWORD IncludeFileTimesInDataObject 0 = filetimes は除外されます 1 = (既定)filetimes が含まれます</span><span class="sxs-lookup"><span data-stu-id="8e8f4-131">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes are excluded  1 = (default) filetimes are included</span></span>


- <span data-ttu-id="8e8f4-132">Azure Information Protection の保護ラベルを使用してメッセージに返信するときに、インライン画像が消えるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-132">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="8e8f4-133">Azure Protected Voicemail を送信するときにユーザー名が電話番号として表示され、Outlook Desktop ユーザーが外部ユーザーからのボイス メールを開くことができなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-133">We fixed an issue that caused the user name to be displayed as a phone number when sending an Azure Protected Voicemail, causing Outlook Desktop users to be unable to open voicemails from external users.</span></span>


- <span data-ttu-id="8e8f4-134">OME構成を設定すると、DecryptAttachmentsForEncryptOnly オプションがサービス側で設定されていても、メールアイテムに無関係な添付ファイルが追加され、Outlook がメッセージを暗号化するように強制される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-134">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though the DecryptAttachmentsForEncryptOnly option was setup on the service side.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8e8f4-135">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8e8f4-135">PowerPoint</span></span>

- <span data-ttu-id="8e8f4-136">ユーザーがソース パスをローカルの OneDrive フォルダーに変更すると、リンクされた Excel グラフが誤って Excel シートに変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-136">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="8e8f4-137">「Welcome back!」機能が原因で発生した問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-137">We fixed an issue due to which the feature ‘Welcome back!</span></span> <span data-ttu-id="8e8f4-138">PowerPoint で機能していなかったオフィスで中断したところから再開します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-138">Pick up where you left off in the office' was not working in the PowerPoint .</span></span>


### <a name="visio"></a><span data-ttu-id="8e8f4-139">Visio</span><span class="sxs-lookup"><span data-stu-id="8e8f4-139">Visio</span></span>

- <span data-ttu-id="8e8f4-140">問題が修正され、ユーザーが Visio for Office 365 のコネクタを使用して、ユーザー設定の Visio ステンシルと組み込みのテンプレートの両方で直線を作成できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-140">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="8e8f4-141">Word</span><span class="sxs-lookup"><span data-stu-id="8e8f4-141">Word</span></span>

- <span data-ttu-id="8e8f4-142">ドキュメントを HTML 形式に保存するときに、長いリンクが折り返されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-142">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="8e8f4-143">拡張子リストにない拡張子がある親コメントに返信すると、返信に同じ拡張子が含まれる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-143">We fixed an issue where if you reply to a parent comment that has unknown extensions in an extension list, the reply will get those same extensions.</span></span>


- <span data-ttu-id="8e8f4-144">メッセージが [転送しない] に設定される Outlook の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-144">We fixed an issue with Outlook with message set to Do not forward.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8e8f4-145">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8e8f4-145">Office Suite</span></span>

- <span data-ttu-id="8e8f4-146">ADAL が無効になっているときにユーザーが SPO リストをインポートできない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-146">Addresses an issue that prevented users from importing SPO Lists when ADAL was disabled.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-november-10"></a><span data-ttu-id="8e8f4-148">バージョン 2008: 11 月 10 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-148">Version 2008: November 10</span></span>
<span data-ttu-id="8e8f4-149">*バージョン 2008 (ビルド 13127.20760)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-149">*Version 2008 (Build 13127.20760)*</span></span>

<span data-ttu-id="8e8f4-150">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-150">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="8e8f4-152">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="8e8f4-152">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="8e8f4-153">Excel</span><span class="sxs-lookup"><span data-stu-id="8e8f4-153">Excel</span></span>

- <span data-ttu-id="8e8f4-154">ブックをロードした後、特定の関数の結果が不正確であるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-154">We fixed an issue where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="8e8f4-155">XLAM アドイン参照と名前付き範囲に関連するアプリケーションが予期せず終了する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-155">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="8e8f4-156">マクロを使用して、範囲の FormulaR1C1 プロパティを設定する問題を修正しました。グラフ シートがアクティブ シートである場合、セル参照が正しくありませんでした。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-156">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="8e8f4-157">Excel で 1 つまたは複数の数式を計算しようとする際に発生する、Excelはリソース不足になりましたというエラーが生じる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-157">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="8e8f4-158">Office の言語がスペイン語に設定されているときに、データ検証リストにすべてのアイテムが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-158">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="8e8f4-159">OLAP ピボットテーブルを更新するときにハングする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-159">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>

### <a name="outlook"></a><span data-ttu-id="8e8f4-160">Outlook</span><span class="sxs-lookup"><span data-stu-id="8e8f4-160">Outlook</span></span>

- <span data-ttu-id="8e8f4-161">Outlook の IRM (Information Rights Management) を他の Office アプリケーションで無効にすることなく無効にできる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-161">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="8e8f4-162">ユーザーが代理人に編集者権限を付与できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-162">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="8e8f4-163">ユーザーが検索結果を選択したときにアプリケーションが予期せず終了する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-163">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="8e8f4-164">グループ予定表で検索結果が返されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-164">We fixed an issue that caused searches in Group calendars fail to return any results.</span></span>


- <span data-ttu-id="8e8f4-165">代理人が別のメールボックスで共有フォルダーを開くと、断続的にエラーが表示される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-165">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="8e8f4-166">件名が空白の場合、一部の自動的に生成されたメールの本文が空で送信される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-166">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="8e8f4-167">返信または転送時に中国語メッセージのヘッダーが文字化けする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-167">We fixed an issue that caused the headers of Chinese messages to get garbled when replying or forwarding.</span></span>

- <span data-ttu-id="8e8f4-168">オプションの接続エクスペリエンスが Web アドインの読み込みをブロックする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-168">We fixed an issue where optional connected experiences blocked web add-ins from loading.</span></span>  <br /><span data-ttu-id="8e8f4-169">
  [ブログの投稿](https://developer.microsoft.com/ja-JP/office/blogs/outlook-add-ins-and-optional-connected-experiences/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="8e8f4-169">See details in [blog post](https://developer.microsoft.com/ja-JP/office/blogs/outlook-add-ins-and-optional-connected-experiences/)</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8e8f4-170">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8e8f4-170">PowerPoint</span></span>

- <span data-ttu-id="8e8f4-171">ユーザーが別のスライドをクリックして表示するまで、Forms コンテンツ アドインが挿入後にレンダリングされない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-171">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8e8f4-172">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8e8f4-172">Office Suite</span></span>

- <span data-ttu-id="8e8f4-173">Microsoft 365 エンドポイントのデータ損失防止を使用して Office Update に System Center Configuration Manager またはその他の管理ツールを利用する商用顧客の問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-173">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>

- <span data-ttu-id="8e8f4-174">Office アドインのメッセージング API が機能しない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-174">Fix an issue that the Messaging API for Office Add-ins is not working.</span></span>



[//]: # (BUGDETAILS コンテンツ エンドを削除しないでください。終了)

## <a name="version-2008-october-13"></a><span data-ttu-id="8e8f4-176">バージョン 2008: 10 月 13 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-176">Version 2008: October 13</span></span>
<span data-ttu-id="8e8f4-177">*バージョン 2008 (Build 13127.20638)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-177">*Version 2008 (Build 13127.20638)*</span></span>

<span data-ttu-id="8e8f4-178">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-178">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="8e8f4-180">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="8e8f4-180">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8e8f4-181">Excel</span><span class="sxs-lookup"><span data-stu-id="8e8f4-181">Excel</span></span>

- <span data-ttu-id="8e8f4-182">' 前 ' と ' 後 ' のフィルター条件が逆転する バグをPivotDateFilter Api で修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-182">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


- <span data-ttu-id="8e8f4-183">Analysis Services データベースに既に存在しない値に設定されているために、ユーザーがピボットテーブル フィルターを変更できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-183">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="8e8f4-184">シートの一番上の行を固定した後にクイック分析を使用すると Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-184">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="8e8f4-185">IFNA () を使用する数式が含まれている場合、破損したワークブックに関する警告を発する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-185">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="8e8f4-186">Outlook</span><span class="sxs-lookup"><span data-stu-id="8e8f4-186">Outlook</span></span>

- <span data-ttu-id="8e8f4-187">隅にある [X] をクリックして共有の予定表を閉じることができない問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-187">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="8e8f4-188">[共有予定表の機能を有効にする] 設定が既存の共有予定表に適用されないことがある問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-188">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="8e8f4-189">クラウドの添付ファイルを開くときに、開こうとしていたドキュメントの代わりに、安全なリンクの ページにエラーが表示される原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-189">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="8e8f4-190">添付ファイルのアップロードのパフォーマンスの問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-190">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8e8f4-191">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8e8f4-191">PowerPoint</span></span>

- <span data-ttu-id="8e8f4-192">この変更により、[エクスポート] ボタンをクリックしてもエクスポートされないという [アニメーション GIF にエクスポート] 機能の問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-192">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="8e8f4-193">セキュリティ修正プログラムを適用して、保護ビューで PowerPoint ファイルを開くと、 IRM による保護が無効になる問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-193">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>

- <span data-ttu-id="8e8f4-194">PowerPoint アプリでクラッシュの原因となったオブジェクトの動作設定の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-194">We have fixed an issue in Action Settings dialog which was causing a crash in PowerPoint app.</span></span>

### <a name="visio"></a><span data-ttu-id="8e8f4-195">Visio</span><span class="sxs-lookup"><span data-stu-id="8e8f4-195">Visio</span></span>

- <span data-ttu-id="8e8f4-196">テキストの配置でリアルタイムのプレビュー表示がクラッシュするという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-196">We fixed an issue that caused the Live preview to crash on text alignment.</span></span>


### <a name="word"></a><span data-ttu-id="8e8f4-197">Word</span><span class="sxs-lookup"><span data-stu-id="8e8f4-197">Word</span></span>

- <span data-ttu-id="8e8f4-198">サイズが非常に大きい特定のメールを開くとクラッシュが発生する問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-198">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="8e8f4-199">ドキュメントを開くときに、ユーザーがクラッシュする可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-199">We fixed an issue which user might experience crash when opening a document.</span></span>


- <span data-ttu-id="8e8f4-200">Word を起動するときにクラッシュの原因となっている可能性のあった問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-200">Resolved an issue that may have caused a crash when booting Word.</span></span>


- <span data-ttu-id="8e8f4-201">スタイル ギャラリー ダイアログの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-201">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8e8f4-202">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8e8f4-202">Office Suite</span></span>

- <span data-ttu-id="8e8f4-p104">Office からインクジェット プリンターでドキュメントやファイルを印刷するとき、プリンターのインク残量が少ない場合、インクジェット プリンターではトナーは使用されないにもかかわらず、[トナー残量: 少] または [トナーなし] と表示されます。このメッセージが [トナー/インク残量: 少] と [トナー/インクなし] に変更されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p104">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners. Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="8e8f4-205">GIF/アニメーション model3D を使用したアイドル時の高い CPU 使用率を修正</span><span class="sxs-lookup"><span data-stu-id="8e8f4-205">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="8e8f4-206">この変更は、 d2d1.dll の読み込みに失敗したために、Office アプリを起動したときにクラッシュする場合があった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-206">This change addresses a crash when launching Office apps due to failing to load d2d1.dll.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2008-september-08"></a><span data-ttu-id="8e8f4-208">バージョン 2008: 9 月 08 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-208">Version 2008: September 08</span></span>
<span data-ttu-id="8e8f4-209">*バージョン 2008(ビルド13127.20408)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-209">*Version 2008 (Build 13127.20408)*</span></span>

<span data-ttu-id="8e8f4-210">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-210">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="8e8f4-212">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-212">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="8e8f4-213">Access</span><span class="sxs-lookup"><span data-stu-id="8e8f4-213">Access</span></span>

- <span data-ttu-id="8e8f4-214">**クエリ デザイナー、SQL ビュー、およびリレーションシップ ウィンドウでの作業効率の向上:** テーブルを右クリックして、テーブルを開き、デザインし、サイズを変更し、非表示にします。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-214">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="8e8f4-215">SQL ビューでテキストを検索および置換します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-215">Search and replace text in SQL View.</span></span> <span data-ttu-id="8e8f4-216">リレーションシップ ウィンドウ内の複数のテーブルを選択します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-216">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="8e8f4-217">**数回クリックするだけで表を追加する:** [テーブルの追加] 作業ウィンドウを使用すると、作業中も開いたまま、リレーションシップやクエリにテーブルを追加できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-217">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="8e8f4-218">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-218">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="8e8f4-219">Excel</span><span class="sxs-lookup"><span data-stu-id="8e8f4-219">Excel</span></span>

- <span data-ttu-id="8e8f4-220">**改善されたマップ グラフ:** マップ グラフを Excel の地理のデータの種類と統合することにより、マップ グラフを改善しました。これにより、マップされた場所に関する豊富な情報を明らかにすることができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-220">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="8e8f4-221">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-221">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="8e8f4-222">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-222">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="8e8f4-223">[ブログの投稿](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="8e8f4-223">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="8e8f4-224">**Excel で Power BI のデータセットからピボットテーブルを作成する:** Power BI に保存されているデータセットに接続されている Excel のピボットテーブルを数回のクリックで作成できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-224">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="8e8f4-225">これにより、ピボットテーブルと Power BI の両方を最大限に活用できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-225">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="8e8f4-226">セキュリティで保護された Power BI データセットからピボットテーブルを使って、データの計算、集計、分析を行います。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-226">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="8e8f4-227">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-227">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="8e8f4-228">[ブログの投稿](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="8e8f4-228">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="8e8f4-229">**お気に入りの Excel 関数が速くなりました：** SUMIFS、AVERAGEIFS、COUNTIFS、MAXIFS、および MINIFS 関数がこれまでよりもはるかに高速になりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-229">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="8e8f4-230">もっと素早く一番下に移動します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-230">Get to the bottom line more quickly.</span></span> <span data-ttu-id="8e8f4-231">今すぐお試しください。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-231">Try one now.</span></span>

- <span data-ttu-id="8e8f4-232">**Realtimedata (RTD) の改善:** Office 365 バージョン 2002 の月間チャネル以降、ExcelのRealTimeData (RTD) 関数は、Excel 2010 のスプレッドシートのデータ計算よりもはるかに高速になります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-232">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="8e8f4-233">基盤となるメモリとデータ構造のボトルネックを取り除き、マルチスレッド再計算  (MTR) の使用可能なすべてのスレッドで計算できるようにスレッドセーフにしました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-233">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="8e8f4-234">Outlook</span><span class="sxs-lookup"><span data-stu-id="8e8f4-234">Outlook</span></span>

- <span data-ttu-id="8e8f4-235">**共有カレンダーの更新がより速く**: Office 365 の共有カレンダーの場合、Outlook は REST API を使用してこれらのカレンダーを更新できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-235">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="8e8f4-236">共有カレンダーのより高速で信頼性の高い更新を行うには、プレビューを有効にします。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-236">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="8e8f4-237">**より迅速かつ適切な結果:** 検索機能が更新され、よりスマート、迅速、かつ信頼性が高くなりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-237">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="8e8f4-238">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-238">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="8e8f4-239">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-239">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="8e8f4-240">[ブログの投稿](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="8e8f4-240">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="8e8f4-241">**所有しているグループにメールをドラッグ:** メッセージや会話を受信トレイからドラッグして移動し、コピーします。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-241">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="8e8f4-242">ドラッグしたメッセージは、すべてのグループ メンバーと共有されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-242">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="8e8f4-243">[ブログの投稿](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/) の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="8e8f4-243">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="8e8f4-244">**予定表が一新されます:** 予定表を簡単に読みやすくなるビジュアル アップデートをご覧ください。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-244">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="8e8f4-245">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-245">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="8e8f4-246">[ブログの投稿](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="8e8f4-246">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="8e8f4-247">**受信トレイを離れずに会議に参加する:** オンライン会議に参加するために、予定表に切り替える必要はありません。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-247">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="8e8f4-248">[To Do] ウィンドウに固定された予定表を使用して、ワンクリックで任意の会議に参加します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-248">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span> [<span data-ttu-id="8e8f4-249">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-249">Learn more</span></span>](https://support.office.com/article/d8baa9d5-0645-41b8-9f36-b498a6c36064 )

- <span data-ttu-id="8e8f4-250">**キャプティブ WiFi ネットワークの新しいエクスペリエンス**: サインインに Web ページを必要とする WiFi ネットワークに参加したことはありませんか ?</span><span class="sxs-lookup"><span data-stu-id="8e8f4-250">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="8e8f4-251">Outlook はこれを検出し、接続を支援します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-251">Outlook now detects this and helps you get connected.</span></span><br /><span data-ttu-id="8e8f4-252">[ブログの投稿](https://insider.office.com/ja-JP/blog/outlook-on-public-wi-fi-networks-just-got-easier)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="8e8f4-252">See details in [blog post](https://insider.office.com/ja-JP/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span></span>

- <span data-ttu-id="8e8f4-253">**人物を検索するときにメールの候補を取得する:** [検索] ボックスに人の名前を入力すると、最も関連性の高いメール メッセージが検索候補に含まれます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-253">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="8e8f4-254">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-254">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint"></a><span data-ttu-id="8e8f4-255">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8e8f4-255">PowerPoint</span></span>

- <span data-ttu-id="8e8f4-p118">**\@@メンションを使用してユーザーの注意を引く:** コメントで @メンションを使うと、仕事仲間によるインプットが必要な場合にそのユーザーに知らせることができます。[詳細情報](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p118">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input. [Learn more](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)</span></span>

- <span data-ttu-id="8e8f4-258">**改善されたマップ グラフ:** マップ グラフを Excel の地理のデータの種類と統合することにより、マップ グラフを改善しました。これにより、マップされた場所に関する豊富な情報を明らかにすることができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-258">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="8e8f4-259">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-259">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="8e8f4-260">**簡単な GIF:** 1 つのスライド、1 つのフレーム。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-260">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="8e8f4-261">PowerPoint でループ GIF を簡単に作成できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-261">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="8e8f4-262">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-262">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="8e8f4-263">[ブログの投稿](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="8e8f4-263">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="8e8f4-264">**図の向上: コネクタが改善されており、インクの滑らかな変換のプロセスが** によって、アイデアをより自信のあるインクにすることができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-264">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="8e8f4-265">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-265">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="8e8f4-266">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-266">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="8e8f4-267">[ブログの投稿](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="8e8f4-267">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="8e8f4-268">**コメント:** PowerPoint の新しいコメント機能により、ドキュメントにコメントをすばやく簡単に見つけて追加できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-268">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="8e8f4-269">コメントの固定、解決、タスク、改善された通知などの新機能を使用して、コラボレーションワークフローを最新のものにします。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-269">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span> [<span data-ttu-id="8e8f4-270">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-270">Learn more</span></span>](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

- <span data-ttu-id="8e8f4-271">**プレゼンテーション中に変更を同期する:** プレゼンテーションがスライド ショー モードであっても、いつでも変更を同期できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-271">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="8e8f4-272">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-272">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="8e8f4-273">[ブログの投稿](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="8e8f4-273">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="8e8f4-274">**スライドへのリンク:** 同僚にスライド デッキへの投稿を依頼し、ヘルプが必要なスライド上で直接開始します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-274">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span> [<span data-ttu-id="8e8f4-275">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-275">Learn more</span></span>](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br /><span data-ttu-id="8e8f4-276">[ブログの投稿](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="8e8f4-276">See details in [blog post](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span></span>

- <span data-ttu-id="8e8f4-277">**PowerPoint でのストリーム ビデオのパフォーマンス向上:**、ビデオの読み込み時間を最小限に抑え、快適な表示を実現するために Microsoft Stream ビデオの再生パフォーマンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-277">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="8e8f4-278">お客様の社内ビデオを使用して、Microsoft Stream でより適切なプレゼンテーションを作成します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-278">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>


### <a name="word"></a><span data-ttu-id="8e8f4-279">Word</span><span class="sxs-lookup"><span data-stu-id="8e8f4-279">Word</span></span>

- <span data-ttu-id="8e8f4-280">**改善されたマップ グラフ:** マップ グラフを Excel の地理のデータの種類と統合することにより、マップ グラフを改善しました。これにより、マップされた場所に関する豊富な情報を明らかにすることができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-280">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="8e8f4-281">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-281">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="8e8f4-282">**インクのなげなわ:** [描画] タブのなげなわツールを使用すると、インクで描かれたオブジェクトを選択できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-282">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="8e8f4-283">個別のストロークまたは文字全体を選択できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-283">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="8e8f4-284">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-284">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="8e8f4-285">**最適な色を選択する:** 16 進数カラーコードを使用して、フォントやテキストのハイライトなどに使用する色を正確に選びます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-285">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="8e8f4-286">[ブログの投稿](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="8e8f4-286">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="8e8f4-287">**スクリーン リーダーでの操作の確認:** 操作の確認は、重要なアクセシビリティ要件です。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-287">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="8e8f4-288">Windows からの新しい通知 API の導入により、操作の成功をスクリーン リーダーのユーザーに通知できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-288">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="8e8f4-289">切り取り、コピー、貼り付け、太字、斜体、下線、元に戻す、やり直し、自動修正、および自動大文字化が、Win32 Word のナレーター ユーザーにすべて通知されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-289">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="8e8f4-290">この機能を有効にするには、Windows + Ctrl + Enter キーを押してナレーターをオンにします。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-290">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span><br /><span data-ttu-id="8e8f4-291">[ブログの投稿](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)の詳細情報をご覧ください</span><span class="sxs-lookup"><span data-stu-id="8e8f4-291">See details in [blog post](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="8e8f4-292">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8e8f4-292">Office Suite</span></span>

- <span data-ttu-id="8e8f4-293">**秘密度ラベル:** カスタム アクセス許可を求められるように組織で構成された秘密度ラベルを適用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-293">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="8e8f4-296">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="8e8f4-296">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="8e8f4-297">アクセス</span><span class="sxs-lookup"><span data-stu-id="8e8f4-297">Access</span></span>

- <span data-ttu-id="8e8f4-298">ID (オートナンバーなど) フィールドが含まれるリンク付きの SQL 表を挿入する場合についての問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-298">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

- <span data-ttu-id="8e8f4-299">クエリの実行に予想よりも約 2 倍の時間がかかっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-299">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="8e8f4-300">アプリケーションのクラッシュを発生させずに、Date/Time Extended データ型をコードに呼び出すことができるように問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-300">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span>

- <span data-ttu-id="8e8f4-301">この問題は修正されて、最新の Access バージョンに戻し、 DAO/VBA を使用して 10 進数データ型を管理および編集することができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-301">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>

- <span data-ttu-id="8e8f4-302">この修正プログラムでは、特定のクエリを実行しようとすると、"クエリが複雑すぎます" というエラーメッセージが表示される問題に対処しています。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-302">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="8e8f4-303">Access では、現在の問題が修正されていますが、この問題が解決するように、追加のインターフェイスを調査しています。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-303">Access has fixed this current issue, but will be investigating our additional interfaces to ensure that this problem does not persist.</span></span> <span data-ttu-id="8e8f4-304">今後の更新情報でさらにご案内いたします。ご不便をおかけして申し訳ございません。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-304">The team will inform you with future updates; we appreciate your patience.</span></span>

- <span data-ttu-id="8e8f4-305">この問題は解決されました。これで、Office のクイック実行アプリケーション以外でも ODBC ドライバーを使用できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-305">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="8e8f4-306">Excel</span><span class="sxs-lookup"><span data-stu-id="8e8f4-306">Excel</span></span>

- <span data-ttu-id="8e8f4-307">読み取り専用モードのブックに対して、ドキュメント分類を自動的に行った可能性があります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-307">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="8e8f4-308">アカウントからサインアウトした場合にデータ接続を作成しようとすると発生する可能性があるクラッシュを修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-308">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

- <span data-ttu-id="8e8f4-309">ピボットテーブルをチャート シートに挿入しようとしたときに Excel がクラッシュする場合がある問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-309">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

- <span data-ttu-id="8e8f4-310">LET () 関数を使用して、数式を含むファイルを保存しようとすると、エラーが発生することがあります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-310">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="8e8f4-311">Format Painter を使用すると、特定の状況で Excel がクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-311">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>

- <span data-ttu-id="8e8f4-312">SharePoint/OneDrive に保存すると、ユーザー設定のリボンタブの CustomUI XML が削除されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-312">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="8e8f4-313">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-313">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="8e8f4-314">同じブック内の場所へのハイパーリンクをクリックすると、ブックが非表示になることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-314">Fixed an issue where in some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

- <span data-ttu-id="8e8f4-315">ファイル パスが長すぎる場合にファイルをもう一度開くと、外部リンクが機能しなくなった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-315">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="8e8f4-316">Application.Evaluate (VBA) が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-316">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="8e8f4-317">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-317">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="8e8f4-318">ピボットテーブルを含むシートをコピーした後、Excel がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-318">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="8e8f4-319">これは、以前のバージョンの Office で SQL データプロバイダーによって作成された接続が内部テーブルのプロパティを Office 365 とは別に設定する問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-319">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="8e8f4-320">これにより、Office 365 を使用して開かれた以前のバージョンの Office で作成された接続を持つファイルに対して、[テーブルのプレビュー / クエリエディター] のドロップダウンが無効になりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-320">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>

- <span data-ttu-id="8e8f4-321">ソース ブックが閉じていると、外部リンクが塗りつぶし時に更新されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-321">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="8e8f4-322">手描き入力で Excel が応答しなくなる可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-322">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>

### <a name="onenote"></a><span data-ttu-id="8e8f4-323">OneNote</span><span class="sxs-lookup"><span data-stu-id="8e8f4-323">OneNote</span></span>

- <span data-ttu-id="8e8f4-324">全世界でサービス使用量が高まった際に、同期とサービスの可用性を改善できる、Microsoft OneNote の一時的な調整に関して、情報バーを介してユーザーに通知します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-324">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

- <span data-ttu-id="8e8f4-325">OneNote 2016 で同期頻度を一時的に調整することで、同期およびサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-325">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="8e8f4-326">リソースの使用率を低下させて、共同編集状態の検出機能を改善します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-326">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="8e8f4-327">OneNote 2016 に 50 MB へ埋め込まれた新しい添付ファイルの最大許容サイズが一時的に減少することにより、同期とサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-327">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="8e8f4-328">この制限を超えるファイルの場合、ユーザーは OneDrive にファイルをアップロードして、OneNote にリンクを挿入することができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-328">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="8e8f4-329">OneNote 2016 でアプリ内動画のレコーディングを一時的に無効にすることで、同期およびサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-329">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="8e8f4-330">ローカルのノートブックはこの影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-330">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="8e8f4-331">ページのバージョン履歴を作成する頻度を一時的に変更することで、同期およびサービスの安定性が改善されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-331">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>

- <span data-ttu-id="8e8f4-332">ごみ箱へのページの移動を一時的に無効にすることにより、同期およびサーバーの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-332">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="8e8f4-333">代わりに、ページを削除するユーザーにはページを完全に削除するか確認するダイアログが表示されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-333">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>

### <a name="outlook"></a><span data-ttu-id="8e8f4-334">Outlook</span><span class="sxs-lookup"><span data-stu-id="8e8f4-334">Outlook</span></span>

- <span data-ttu-id="8e8f4-335">プロファイルに追加されたサブ アカウントから会議出席依頼を作成しようとした場合に、ユーザーのメール アドレスの代わりに空欄の From: フィールドが表示されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-335">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="8e8f4-336">共有メールボックスを追加した後に、ユーザーがパブリック フォルダーに接続できない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-336">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="8e8f4-337">特定の状況で代理人が会議を辞退したときに、マネージャーのカレンダーから削除されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-337">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="8e8f4-338">共有カレンダーの改善機能を使用している一部のユーザーが、新しく追加された共有カレンダーを表示できない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-338">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="8e8f4-339">クラウドの添付ファイルを操作するときに、ユーザーに時折クラッシュが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-339">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="8e8f4-340">保護されたコンテキストから保護されていないコンテキストに返信するとき、送信元アドレスを切り替えると、CLP のユーザーにクラッシュが発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-340">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>

- <span data-ttu-id="8e8f4-341">M365 Business Plus プランのサービスを利用していたユーザーがデータ損失防止の保護ポリシー ヒントを有効にできない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-341">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="8e8f4-342">CLP の監査イベントで、返信/転送ラベルの問題に対応しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-342">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="8e8f4-343">フォルダー ウィンドウの幅が予期せず変更される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-343">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="8e8f4-344">ドラッグ アンド ドロップによってファイル システムにコピーされた添付ファイルの作成日が、4501年1月1日に設定される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-344">Addressed an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>

- <span data-ttu-id="8e8f4-345">SharePoint ファイルに Smart Link を追加すると、一部の文字セットのユーザーにファイル名が正しく表示されないという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-345">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="8e8f4-346">ユーザーが Outlook のルールを更新すると、「このコンピューターのルールは、Microsoft Exchange のルールと異なります」というメッセージが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-346">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="8e8f4-347">Outlook で検索候補を取得できない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-347">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>

- <span data-ttu-id="8e8f4-348">共有された予定表の改良版のユーザーに予定表のエラーが表示される問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-348">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>

- <span data-ttu-id="8e8f4-349">一部のシナリオで、断続的なハングやクラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-349">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>

- <span data-ttu-id="8e8f4-350">[ヘッダーのみダウンロード] オプションが選択されている POP アカウントから 4 件以上のメールを削除しようとするとクラッシュするという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-350">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="8e8f4-351">[共有フォルダーのダウンロード] がチェックされていない場合、共有された予定表の会議の [返信オプション] に [転送を許可する] オプションが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-351">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="8e8f4-352">管理者のカレンダー上で既存のカレンダーの予定を編集するときに代理人がエラーを受け取る問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-352">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="8e8f4-353">サードパーティ製の MAPI アプリケーションでクラッシュが発生した問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-353">Addressed an issue that caused users to experience crashes in third party MAPI applications.</span></span>

- <span data-ttu-id="8e8f4-354">Windows の更新後に、ローカルに保存された .msg または .oft ファイルを開くと Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-354">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="8e8f4-355">Windows の一部のビルドで Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-355">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="8e8f4-356">Windows 10 サーバー バージョンのユーザーに、以下の警告が表示される問題に対処しました。「アンチウイルスの状態が無効です。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-356">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="8e8f4-357">このバージョンの Windows はウイルス対策ソフト検出をサポートしていますが、ウイルス対策ソフトが見つかりませんでした」という警告が、アンチウイルスが正しくインストールされているにもかかわらず表示されていました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-357">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="8e8f4-358">Windows の更新後に、ローカルに保存された .msg または .oft ファイルを開くと Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-358">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="8e8f4-359">Windows の一部のビルドで Outlook がクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-359">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="8e8f4-360">Outlook で、受信トレイ修復ツールを実行するように促す表示が継続的に発生していた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-360">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>

- <span data-ttu-id="8e8f4-361">マウスで ”X” ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-361">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="8e8f4-362">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカルコンピューターに保存できない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-362">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="8e8f4-363">スケジュール アシスタント ページが表示されない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-363">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="8e8f4-364">一部のユーザーにスケジュール アシスタント ページが表示されない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-364">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="8e8f4-365">ユーザーがペルソナ情報を取得しようとしたときにクラッシュする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-365">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>

- <span data-ttu-id="8e8f4-366">これにより、受信者を編集しているときに不定期にクラッシュする問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-366">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="8e8f4-367">コンパクト ビューを使用するときに異常が表示される原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-367">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="8e8f4-368">Outlook ユーザーにコンパクト ビューでのナビゲーションの問題が表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-368">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>

- <span data-ttu-id="8e8f4-369">右クリックのコンテキストメニューが検索コントロールに表示されない問題の原因を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-369">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="8e8f4-370">ユーザーが新しいメールに返信または作成するときに次のエラーを受け取る原因となった問題に対処します。「この Web ページのファイルの一部が予期された場所にありません。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-370">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="8e8f4-371">この Web ページをダウンロードする必要がありますか? </span><span class="sxs-lookup"><span data-stu-id="8e8f4-371">Do you want to download them anyway?</span></span> <span data-ttu-id="8e8f4-372">Web ページが信頼できるソースからのものであることを確認したら、[はい] をクリックします。」</span><span class="sxs-lookup"><span data-stu-id="8e8f4-372">If you’re sure the Web page is from a trusted source, click Yes"</span></span>

- <span data-ttu-id="8e8f4-373">Outlook の終了中に応答停止が発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-373">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>

- <span data-ttu-id="8e8f4-374">Suggest a Feature で機能を検索しても結果が返されず、ユーザーが新しい機能のアイデアを提出するオプションがないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-374">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>

- <span data-ttu-id="8e8f4-375">インシデント通知アラートのフォーマットの問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-375">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

- <span data-ttu-id="8e8f4-376">ユーザーが管理者通知からフィードバックを送信する場合にクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-376">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

- <span data-ttu-id="8e8f4-377">SVG 画像のコピーと貼り付けの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-377">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="8e8f4-378">これにより、受信者を編集しているときに不定期にクラッシュする問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-378">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="8e8f4-379">SVG 画像のコピーと貼り付けの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-379">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8e8f4-380">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8e8f4-380">PowerPoint</span></span>

- <span data-ttu-id="8e8f4-381">ユーザーがファイルに最新のコメントと従来のコメントの両方を持っていると、コメントのアップグレードが開始されるクラッシュを修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-381">Fixed a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

- <span data-ttu-id="8e8f4-382">PowerPoint アプリでクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-382">We have fixed a crash issue with PowerPoint app.</span></span>

- <span data-ttu-id="8e8f4-383">提案ウィンドウでクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-383">We have fixed a crash issue with suggestion pane.</span></span>

### <a name="project"></a><span data-ttu-id="8e8f4-384">Project</span><span class="sxs-lookup"><span data-stu-id="8e8f4-384">Project</span></span>

- <span data-ttu-id="8e8f4-385">先行処理 / 後続処理データがフォームビュー内で編集されると、追加の ProjectBeforeTaskChange イベントが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-385">Fixed an issue when Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="8e8f4-386">以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-386">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="8e8f4-387">実績作業時間の保護設定を有効にしているときに、ユーザーがタイムフェーズの基準作業時間を入力できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-387">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

- <span data-ttu-id="8e8f4-388">タスクを完了とマークした後に、タスクの達成率が 100% 完了より小さい値に誤って変更される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-388">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="8e8f4-389">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-389">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="8e8f4-390">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-390">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="8e8f4-391">[無効化] ボタンを介してタスクが非アクティブ化/アクティブ化された場合に、ProjectBeforeTaskChange イベントが検出しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-391">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="8e8f4-392">Project Web App に接続されている Project を使用していて小数点の記号がカンマの場合に、依存関係のタイム ラグを生じさせようとすると TaskDependencies Add メソッドが失敗する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-392">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

- <span data-ttu-id="8e8f4-393">URL の末尾が「.com」の場合に、Project Web App から Project デスクトップ クライアントでプロジェクトを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-393">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>

- <span data-ttu-id="8e8f4-394">複数の依存関係があるタスクを貼り付けると、すべての依存関係が正しくコピーされるわけではない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-394">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="8e8f4-395">Project から SharePoint ドキュメント ライブラリに PDF/XPS を保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-395">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>

- <span data-ttu-id="8e8f4-396">100% 完了とマークされているタスクが、100% 未満のタスクに間違って変更されてしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-396">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="8e8f4-397">プロジェクトのサマリータスクで、[プロジェクトの開始日] フィールドまたは [タスク] フィールドのいずれかに変更があった場合、ProjectBeforeTaskChange イベントが発生しない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-397">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="8e8f4-398">リソースに複数のコスト単価表が定義されている場合に、残りのコストが正しく計算されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-398">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

- <span data-ttu-id="8e8f4-399">SharePoint タスクリストに接続されているプロジェクトのプロジェクト終了日が更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-399">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="8e8f4-400">[リソースの割り当て] ダイアログ ボックスで選択されているタスクが、[タスク ボード] ビューで選択したタスクと異なる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-400">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="8e8f4-401">正常ではない状態になったプロジェクトを開くことができない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-401">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>

### <a name="skype"></a><span data-ttu-id="8e8f4-402">Skype</span><span class="sxs-lookup"><span data-stu-id="8e8f4-402">Skype</span></span>

- <span data-ttu-id="8e8f4-403">ユーザーが Teams Only に移動するポリシーを与えられた場合は、Skype for Business Outlook アドインを使用して会議をスケジュールできます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-403">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="8e8f4-404">この更新プログラムを適用すると、クライアントは Teams Only を対象としていることを示すポリシーをユーザーが読んでから会議参加のみのモードに入った後に、Skype for Business 会議のスケジュールを設定できなくなります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-404">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="8e8f4-405">また、skype for business Outlook アドインは、Skype for business クライアントが 「会議の参加のみ」 モードであることを確認した場合に起動した場合、自動的にアクティブ化されることはありません。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-405">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="8e8f4-406">ダンス絵文字の肌の色を中間色に変更しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-406">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="8e8f4-407">Word</span><span class="sxs-lookup"><span data-stu-id="8e8f4-407">Word</span></span>

- <span data-ttu-id="8e8f4-408">URL にクエリ コンポーネントが含まれている場合にカスタム ドキュメント配信 (aspx) から Word ドキュメントを開く問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-408">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="8e8f4-409">この変更により、以前の共同編集セッションの後に Office アプリケーションがサイレント保存の失敗状態に陥ることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-409">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="8e8f4-410">新しいメールに返信、または新しいメールを作成するときにユーザーにクラッシュが発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-410">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="8e8f4-411">マウスで ”X” ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-411">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="8e8f4-412">SVG 画像のコピーと貼り付けの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-412">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="8e8f4-413">図形のサイズを変更すると、ユーザーがコンテンツを失う可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-413">We fixed an issue where the user might lose content when resize a shape.</span></span>

- <span data-ttu-id="8e8f4-414">基本スタイルが標準スタイルで更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-414">We fixed an issue which the base styles are not updated with Normal style.</span></span>

- <span data-ttu-id="8e8f4-415">マクロ AutoOpen が AutoExec の前に実行されてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-415">We fixed an issue where macro AutoOpen runs before AutoExec.</span></span>

- <span data-ttu-id="8e8f4-416">SVG 画像のコピーと貼り付けの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-416">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="8e8f4-417">一部のアプリケーションからコンテンツをドラッグしたときにクラッシュする問題の原因となっていた可能性がある問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-417">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8e8f4-418">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8e8f4-418">Office Suite</span></span>

- <span data-ttu-id="8e8f4-p137">以前の Web サービス ベースの [共有] ウィンドウで、[共有] ウィンドウが開いているときに文書を閉じるとクラッシュする場合があります。この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p137">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash. This is now fixed.</span></span>

- <span data-ttu-id="8e8f4-421">タイミングの問題で、Office ファイルを閉じるときにクラッシュすることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8e8f4-421">Fixed a timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="8e8f4-422">Bing アドオンのインストール検証を既定で true に設定し、MSI のリターン成功をインストール成功とみなすことで、ValidateInstall のエラー率の問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-422">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>

- <span data-ttu-id="8e8f4-423">以前の AppV51 の回帰を修正するために、新しい AppV51 drop をバックポートします。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-423">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="8e8f4-424">シンボリック リンクのハード リンクを試みる際に、更新の失敗を引き起こしていたクイック実行の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-424">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>

- <span data-ttu-id="8e8f4-425">製品版への移行が完了した場合でも、ランタイムメッセージが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-425">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="8e8f4-426">この問題の修正では、サービスが追加された製品を適切に計算するようにしました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-426">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="8e8f4-427">新たに追加された製品をフィルターで除外し (新しい構成に存在することも確認)、既存の製品リリース ID の最後に追加しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-427">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>

- <span data-ttu-id="8e8f4-428">特定の状況下で UI 要素またはコンテンツが表示されない問題を修正しました。特に、発表者ツールのオン/オフ、または複数のモニターの使用に関して発生しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-428">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>

- <span data-ttu-id="8e8f4-429">この変更により、Gif や3D モデルなどのアニメーション コンテンツを読み込んだり、再生したりするときに、ハングする可能性があります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-429">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>

- <span data-ttu-id="8e8f4-430">この変更では、[図の圧縮] ダイアログで一部のユーザー設定が保持されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-430">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>

- <span data-ttu-id="8e8f4-431">この更新プログラムでは、Microsoft Office で PATH 環境変数で指定した場所を検索することによって参照される可能性がある Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA ランタイムエラーが発生するという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-431">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="8e8f4-432">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-432">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="8e8f4-433">この修正プログラムで、アクセスの制限と、パスワードによるファイルの保護が同時に行えないというエラーが解決されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-433">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="8e8f4-434">レジストリ TabProcGrowth の値がREG_SZ型でアドインがアクティブ化されている場合に、Windows の Office ホストがクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-434">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="8e8f4-p139">HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth のレジストリ キーが0に設定されている場合、アドインがアクティブになり、Windows で Office ホストがクラッシュしました。この変更により、この問題は修正されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p139">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero. This change would fix this issue.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-august-11"></a><span data-ttu-id="8e8f4-438">バージョン 2002: 8 月 11 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-438">Version 2002: August 11</span></span>
<span data-ttu-id="8e8f4-439">*バージョン 2002 (ビルド 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-439">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="8e8f4-440">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-440">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="8e8f4-442">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="8e8f4-442">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8e8f4-443">Excel</span><span class="sxs-lookup"><span data-stu-id="8e8f4-443">Excel</span></span>

- <span data-ttu-id="8e8f4-444">「読み取り専用推奨」として開かれたファイルの編集に切り替えられない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-444">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="8e8f4-445">OneNote</span><span class="sxs-lookup"><span data-stu-id="8e8f4-445">OneNote</span></span>

- <span data-ttu-id="8e8f4-446">リソースの使用率を低下させるための冗長な ID 呼び出しが削除されました</span><span class="sxs-lookup"><span data-stu-id="8e8f4-446">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="8e8f4-447">リソースの使用率を低下させて、共同編集状態の検出機能を改善します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-447">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="8e8f4-448">エラーを検出する機能が改善され、同期環境の品質が向上しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-448">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="8e8f4-449">Outlook</span><span class="sxs-lookup"><span data-stu-id="8e8f4-449">Outlook</span></span>

- <span data-ttu-id="8e8f4-450">一部のテナントで Outlook を起動したときに重大なパフォーマンスの問題が発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-450">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="8e8f4-451">Skype</span><span class="sxs-lookup"><span data-stu-id="8e8f4-451">Skype</span></span>

- <span data-ttu-id="8e8f4-452">数日間稼働した後に、32 ビット版の Skype for Business クライアントで画面共有を開始できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-452">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8e8f4-453">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8e8f4-453">Office Suite</span></span>

- <span data-ttu-id="8e8f4-454">グループ ポリシーを介して自動保存が無効にされた場合に、ユーザーが [利用可能な更新] をクリックするまで一部のドキュメントで最新のサーバー コンテンツが表示されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-454">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-july-14"></a><span data-ttu-id="8e8f4-456">バージョン 2002: 7 月 14 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-456">Version 2002: July 14</span></span>
<span data-ttu-id="8e8f4-457">*バージョン 2002 (ビルド 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-457">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="8e8f4-458">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-458">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="8e8f4-460">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="8e8f4-460">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8e8f4-461">Excel</span><span class="sxs-lookup"><span data-stu-id="8e8f4-461">Excel</span></span>

- <span data-ttu-id="8e8f4-462">ローカルの OneDrive フォルダーで使用できるファイルの読み込み速度を向上します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-462">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="8e8f4-463">SharePoint/OneDrive に保存すると、ユーザー設定のリボン タブの CustomUI XML が削除されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-463">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="8e8f4-464">アドインが、ユーザーが指定した順番ではなくアルファベット順に読み込まれていたため、「このブックは現在別のユーザーに参照されており、閉じることができません」というエラー メッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-464">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="8e8f4-465">既に開いているブック内の場所へのハイパーリンクをクリックすると、ブックが非表示になることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-465">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="8e8f4-466">コピー & ペーストされたグラフのリンクの一部で、ユニバーサル アドレスではなくマップされたドライブ アドレスが使用されていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-466">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="8e8f4-467">結合されたセルを持つ列を削除するときのパフォーマンスを改善しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-467">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="8e8f4-468">[印刷] ダイアログ ボックスのプリンターの一覧にプリンター名が繰り返されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-468">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="8e8f4-469">定義された名前を持つ複数の数式を含むワークシートがファイルを保存するときに時間がかかる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-469">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>


### <a name="outlook"></a><span data-ttu-id="8e8f4-470">Outlook</span><span class="sxs-lookup"><span data-stu-id="8e8f4-470">Outlook</span></span>

- <span data-ttu-id="8e8f4-471">解像度の異なる複数のモニターを使用している場合に、IME(Input Method Editor)ウィンドウで入力されたテキストが重なってしまう問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-471">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="8e8f4-472">タイムゾーンの定義を変更するときに、定期的な予定や会議が誤った時間に表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-472">Addressed an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="8e8f4-473">ユーザーが Outlook のルールを更新すると、「このコンピューターのルールは、Microsoft Exchange のルールと異なります」というメッセージが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-473">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="8e8f4-474">[共有フォルダーのダウンロード] がチェックされていない場合、共有された予定表の会議の [返信オプション] に [転送を許可する] オプションが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-474">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="8e8f4-475">メール メッセージからカテゴリが消えることがあるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-475">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="8e8f4-476">共有メールボックスに対して、異なるマシン上の別のフォルダー階層が代理人に表示されるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-476">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="8e8f4-477">管理者のカレンダー上で既存のカレンダーの予定を編集するときに代理人がエラーを受け取る問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-477">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="8e8f4-478">件名を編集した後、NDR メッセージの本文が Unicode から ASCII に変更される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-478">Addressed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="8e8f4-479">2 つのアドインが同じリボン グループにボタンを追加するときにユーザーにクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-479">Addressed an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="8e8f4-480">ユーザーが個人用配布リストにメールを送信できなくなった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-480">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="8e8f4-481">テナントの既定のアクセス許可が「全員」として構成されている場合に、適切なテナントの既定のアクセス許可を使用して、リンクがメールに追加されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-481">Addressed an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as"anyone".</span></span>

- <span data-ttu-id="8e8f4-482">セキュリティ ダイアログ ボックスで [保存] オプションを選択したときに、ユーザーがテナント外の OneDrive の添付ファイルをローカルコンピューターに保存できない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-482">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="word"></a><span data-ttu-id="8e8f4-483">Word</span><span class="sxs-lookup"><span data-stu-id="8e8f4-483">Word</span></span>

- <span data-ttu-id="8e8f4-484">ポリシー FileBlick\Word2007Files を有効にしたときの共同編集に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-484">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="8e8f4-485">名前が変更されたルックアップ フィールドを追加するときに Word QuickPart が機能しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-485">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8e8f4-486">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8e8f4-486">Office Suite</span></span>

- <span data-ttu-id="8e8f4-487">大規模な PowerPoint ファイルの共同編集中に、ユーザーがネットワークと CPU の使用率が過剰になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-487">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="8e8f4-488">以前の AppV51 の回帰を修正するために、新しい AppV51 drop をバックポートします。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-488">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="8e8f4-489">レジストリ TabProcGrowth の値がREG_SZ型でアドインがアクティブ化されている場合に、Windows の Office ホストがクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-489">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-june-09"></a><span data-ttu-id="8e8f4-491">バージョン 2002: 6 月 9 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-491">Version 2002: June 09</span></span>
<span data-ttu-id="8e8f4-492">*バージョン 2002 (ビルド 12527.20720)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-492">*Version 2002 (Build 12527.20720)*</span></span>

<span data-ttu-id="8e8f4-493">セキュリティ更新プログラムのリストは[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-493">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="8e8f4-495">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="8e8f4-495">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8e8f4-496">Excel</span><span class="sxs-lookup"><span data-stu-id="8e8f4-496">Excel</span></span>

- <span data-ttu-id="8e8f4-497">ファイル パスが長すぎる場合にファイルをもう一度開くと、外部リンクが機能しなくなった問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-497">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="8e8f4-498">Excel ウィンドウが Teams と共有されているときに、Ctrl キーと Shift キーを押しながら方向キーを押した後、Excel が応答しなくなる可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-498">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="8e8f4-499">印刷時にフォーム コントロールのチェックボックスが拡大縮小されるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-499">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="8e8f4-500">従来の "共有ブック" モードを使用して、ブックの新しいシートに変更を一覧表示しようとすると、クラッシュが発生する場合がありました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-500">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="8e8f4-501">フィルター処理されたリストに列を挿入すると、通常よりも時間がかかっていました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-501">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="8e8f4-502">数式を開始する @ 記号が暗黙的な論理積演算子と見なされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-502">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

### <a name="outlook"></a><span data-ttu-id="8e8f4-503">Outlook</span><span class="sxs-lookup"><span data-stu-id="8e8f4-503">Outlook</span></span>

- <span data-ttu-id="8e8f4-504">ネイティブの Teams クライアントを介して Teams 会議に直接参加できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-504">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="8e8f4-505">M365 Business Plus プランのサービスを利用していたユーザーがデータ損失防止の保護ポリシー ヒントを有効にできない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-505">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="8e8f4-506">間違ったブラウザー エミュレーション設定でユーザーが Gmail の認証プロンプトを完了できなくなるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-506">Addressed an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="8e8f4-507">サーバー オペレーティング システムの Outlook ユーザーに「ウイルス対策ステータス: 無効」のエラーを表示する原因となっていた問題に対処しました。 </span><span class="sxs-lookup"><span data-stu-id="8e8f4-507">Addressed an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="8e8f4-508">このバージョンの Windows はウイルス検出をサポートしていますが、ウイルス対策を適切に構成してもウイルス対策ソフトウェアが見つかりませんでした。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-508">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

### <a name="word"></a><span data-ttu-id="8e8f4-509">Word</span><span class="sxs-lookup"><span data-stu-id="8e8f4-509">Word</span></span>

- <span data-ttu-id="8e8f4-510">クイック印刷を使用して印刷した後に編集しようとしたときに、ドキュメント内の単語の配置が乱れてしまうという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-510">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8e8f4-511">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8e8f4-511">Office Suite</span></span>

- <span data-ttu-id="8e8f4-512">この問題を解決するため、Backstage のチャネル名を 2020 年 1 月のフォークにある新しいチャネル名に更新しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-512">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="8e8f4-513">この問題は修正されましたが、今後、デバイスがポリシー管理されている場合、DMS の対象ユーザー API は呼び出されません。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-513">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="8e8f4-514">単一のトランザクションでアプリを追加および削除したときに、削除が不完全になるという問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-514">Resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="8e8f4-p141">HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth のレジストリ キーが0に設定されている場合、アドインがアクティブになり、Windows で Office ホストがクラッシュしました。この変更により、この問題は修正されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p141">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero. This change would fix this issue.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-may-12"></a><span data-ttu-id="8e8f4-518">バージョン 2002: 5 月 12 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-518">Version 2002: May 12</span></span>
<span data-ttu-id="8e8f4-519">*バージョン 2002 (ビルド 12527.20612)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-519">*Version 2002 (Build 12527.20612)*</span></span>

<span data-ttu-id="8e8f4-520">セキュリティ更新プログラムのリストは[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-520">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="8e8f4-522">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="8e8f4-522">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="8e8f4-523">Excel</span><span class="sxs-lookup"><span data-stu-id="8e8f4-523">Excel</span></span>

- <span data-ttu-id="8e8f4-524">特に非表示のウィンドウで、多数のその他のブックを参照しながらブックを開くと、予想よりも時間がかかります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-524">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="8e8f4-525">状況によっては、CSV ファイルを開くのに予想より時間がかかっていました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-525">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="8e8f4-526">Excel では、異なる拡大レベルでブックを切り替えるとクラッシュすることがあります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-526">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="8e8f4-527">値の範囲への入力に予想より時間がかかる VBA の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-527">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="8e8f4-528">色でフィルター処理された列からコピーしたデータは、正しく貼り付けられない場合があります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-528">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="8e8f4-529">ピボットテーブルを含むシートをコピーした後、Excel がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-529">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="8e8f4-530">Excel 2016 でデジタル署名を使用して保存したブックを現在のバージョンの Excel で開くと、署名が無効になる可能性があります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-530">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="8e8f4-531">グラフの軸の "Value Crosses At" プロパティが、ファイルを保存してもう一度開くときに予期せず変更されるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-531">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="8e8f4-532">Range.Value と Range.Value2 (VBA) を使用すると、数式は動的配列として入力されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-532">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

### <a name="onenote"></a><span data-ttu-id="8e8f4-533">OneNote</span><span class="sxs-lookup"><span data-stu-id="8e8f4-533">OneNote</span></span>

- <span data-ttu-id="8e8f4-534">同期およびサービスの安定性を改善するために、OneNote ユーザー エクスペリエンスで実行されている一時的な手段についての詳細情報をユーザーが学べるようにする通知をローカライズします。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-534">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="8e8f4-535">同期およびサービスの安定性を改善するために、OneNote ユーザー エクスペリエンスで実行されている一時的な手段についての詳細情報をユーザーが学べるようにする通知を表示します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-535">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="8e8f4-536">OneNote 2016 のバージョン履歴ページの数と同期頻度を一時的に減らすことで、同期およびサービスの安定性を改善しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-536">Improved sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="8e8f4-p142">OneNote 2016 のごみ箱を一時的に無効にすることにより、同期およびサービスの安定性を改善しました。ユーザーが、通常はごみ箱に送られるデータを削除しようとすると、データを保持するか、完全に削除するかを確認するメッセージが表示されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p142">Improved sync and service stability by temporarily disabling the recycle bin in OneNote 2016. When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="8e8f4-539">OneNote 2016 で同期頻度を一時的に調整することで、同期およびサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-539">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="8e8f4-540">ユーザーが OneNote 2016 のページに移動するまで、オンライン ノートブックの埋め込みファイルおよび画像のダウンロードを一時的に遅らせることで、同期およびサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-540">Improved sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="8e8f4-541">OneNote 2016 でアプリ内動画のレコーディングを一時的に無効にすることで、同期およびサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-541">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="8e8f4-542">ローカルのノートブックはこの影響を受けません。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-542">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="8e8f4-543">OneNote 2016 に 50 MB へ埋め込まれた新しい添付ファイルの最大許容サイズが一時的に減少することにより、同期とサービスの安定性が改善されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-543">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="8e8f4-544">この制限を超えるファイルの場合、ユーザーは OneDrive にファイルをアップロードして、OneNote にリンクを挿入することができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-544">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

### <a name="outlook"></a><span data-ttu-id="8e8f4-545">Outlook</span><span class="sxs-lookup"><span data-stu-id="8e8f4-545">Outlook</span></span>

- <span data-ttu-id="8e8f4-546">フォルダー ウィンドウの幅が予期せず変更される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-546">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="8e8f4-547">ユーザーが Windows Update の後に .msg および .oft ファイルを開こうとするとクラッシュが起きるという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-547">Addressed an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="8e8f4-548">大きな HTML メッセージを転送するとき、ユーザーにメッセージ本文の全体が表示されないという問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-548">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="8e8f4-549">この更新プログラムでは、メッセージの表示または作成時に Microsoft Outlook で現在の機密ラベルが表示されないという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-549">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="8e8f4-550">ユーザーが個人用配布リストにメールを送信できなくなった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-550">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8e8f4-551">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8e8f4-551">PowerPoint</span></span>

- <span data-ttu-id="8e8f4-552">問題の修正により、改善済みのコメントが入ったファイルのコピーを開くユーザーに正しいメッセージを送れるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-552">Fixed an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="word"></a><span data-ttu-id="8e8f4-553">Word</span><span class="sxs-lookup"><span data-stu-id="8e8f4-553">Word</span></span>

- <span data-ttu-id="8e8f4-554">インストールされている言語によって Access と Publisher が正常に起動しなかった問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-554">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>

- <span data-ttu-id="8e8f4-555">編集用に保護されたドキュメントの比較機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-555">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="8e8f4-556">2 つのドキュメントを 1 つのドキュメントに結合するときの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-556">We fixed an issue when merging 2 documents into one document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8e8f4-557">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8e8f4-557">Office Suite</span></span>

- <span data-ttu-id="8e8f4-558">これは、ファイルがクライアントにキャッシュされるときに Project アプリがネットワークをブロックしないようにするための修正プログラムです。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-558">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>

- <span data-ttu-id="8e8f4-559">ログ記録して続行するのではなく、内部操作により失敗時に例外がスローされていた問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-559">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="8e8f4-560">影響を受けるユーザーは、更新プログラムの受信をブロックされなくなります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-560">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="8e8f4-561">この変更により、リボンのスケッチされたアウトラインは正常に機能するようになります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-561">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="8e8f4-562">特定のプロキシの構成でオンプレミスの場所からファイルを開く際の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-562">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="8e8f4-563">この更新プログラムを適用すると、Microsoft Office の Visual Basic for Applications で、ライブラリ名またはライブラリ パスに DBCS 文字を含むコード ライブラリへの参照が含まれている特定の VBA プロジェクトが、読み込み時に破損していると Office アプリケーションで表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-563">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="8e8f4-564">この更新プログラムでは、Microsoft Office で PATH 環境変数で指定した場所を検索することによって参照される可能性がある Visual Basic for Applications プロジェクトが実行時に正しく検出されず、VBA ランタイムエラーが発生するという問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-564">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="8e8f4-565">この更新プログラムでは、Microsoft Word で、ラベル ポリシーにヘッダーやフッターまたは透かしが適用されている場合にラベルを変更または削除すると、 255 文字を超える文字の挿入されたテキストが識別および削除できなかった問題が修正されています。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-565">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

- <span data-ttu-id="8e8f4-566">問題を解決し、Office のハンドオフ セッション中のクラッシュを解消し、ユーザー エクスペリエンスの信頼性を向上させました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-566">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>  

- <span data-ttu-id="8e8f4-567">このバグは、Enhanced Configuration Service (ECS) url エンドポイントを更新します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-567">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="8e8f4-568">この新しいエンドポイントを呼び出すと、ECS からのフェッチ成功率が高くなります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-568">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

[//]: # (バグの詳細コンテンツを削除しないでください。終了)

## <a name="version-2002-april-14"></a><span data-ttu-id="8e8f4-570">バージョン 2002: 4 月 14 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-570">Version 2002: April 14</span></span>
<span data-ttu-id="8e8f4-571">*バージョン 2002 (ビルド 12527.20442)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-571">*Version 2002 (Build 12527.20442)*</span></span>

<span data-ttu-id="8e8f4-572">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-572">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


### <a name="feature-updates"></a><span data-ttu-id="8e8f4-573">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-573">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="8e8f4-574">Excel</span><span class="sxs-lookup"><span data-stu-id="8e8f4-574">Excel</span></span>

- <span data-ttu-id="8e8f4-575">**複数の値を返す式を入力する:** 複数の値を返す式を素早く入力できるようになりました。隣接するセルに自動的に入力されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-575">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="8e8f4-576">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-576">Learn more</span></span>](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="8e8f4-577">**6 つの強力な機能:** スプレッドシートを強化する 6 つの新しい関数が追加されました。FILTER、SORT、SORTBY、UNIQUE、SEQUENCE、RANDARRAY です。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-577">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span>  [<span data-ttu-id="8e8f4-578">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-578">Learn more</span></span>](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="8e8f4-579">**左を見て、右を見て... XLOOKUP をご利用いただけます!** XLOOKUP を使えば、表や範囲内で必要なものは何でも見つけられます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-579">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span>  <span data-ttu-id="8e8f4-580">
  [詳細情報](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-580">[Learn more](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="8e8f4-582">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="8e8f4-582">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8e8f4-583">Excel</span><span class="sxs-lookup"><span data-stu-id="8e8f4-583">Excel</span></span>

- <span data-ttu-id="8e8f4-584">Word または PowerPoint に埋め込まれたブックをもう一度開くと、場合によっては Excel がクラッシュする可能性があります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-584">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="8e8f4-585">CSV ファイルとして保存する場合、Excel はすべての列を 1 つの列にマージする場合があります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-585">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="8e8f4-586">保護されたシートの範囲で Range.ClearContents を使用すると、予想よりも時間がかかる場合があります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-586">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="8e8f4-587">[印刷プレビュー] に表示されるときのフォーム コントロール内のテキストの拡大縮小に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-587">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="8e8f4-588">リボンを操作する VBA マクロは、ScreenUpdating が True に設定されていると予期せず実行される場合があります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-588">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="8e8f4-589">ソース ブックが閉じていると、外部リンクが塗りつぶし(下方向に塗りつぶし、全体に塗りつぶしなど) 時に更新されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-589">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is closed.</span></span>

- <span data-ttu-id="8e8f4-590">VBA の Application.Evaluate が、ユーザー定義関数では動作しない場合がありました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-590">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="8e8f4-591">テンプレートからグラフを作成するときに発生するパフォーマンスの問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-591">Addressed a performance issue when creating charts from templates.</span></span>


### <a name="outlook"></a><span data-ttu-id="8e8f4-592">Outlook</span><span class="sxs-lookup"><span data-stu-id="8e8f4-592">Outlook</span></span>

- <span data-ttu-id="8e8f4-593">一部のシナリオで、グループ ヘッダーが予期せず拡張される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-593">Addressed an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="8e8f4-594">特定の検索結果を選択すると、ユーザーがクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-594">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="8e8f4-595">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-595">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="8e8f4-596">[添付ファイル ​​ツール] に [クラウドに保存] ボタンが表示されない問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-596">Addressed an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8e8f4-597">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8e8f4-597">PowerPoint</span></span>

- <span data-ttu-id="8e8f4-598">コピーと貼り付けのシナリオを改善しました。PowerPoint スライドでの図形のコピーと、ループ内の他のスライドへの貼り付けが例外で失敗する場合があります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-598">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="8e8f4-599">Project</span><span class="sxs-lookup"><span data-stu-id="8e8f4-599">Project</span></span>

- <span data-ttu-id="8e8f4-600">以前のバージョンの Project で作成したプロジェクトを保存すると、Project がクラッシュする場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-600">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="8e8f4-601">[無効化] ボタンを介してタスクが非アクティブ化/アクティブ化された場合に、ProjectBeforeTaskChange イベントが検出しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-601">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

### <a name="word"></a><span data-ttu-id="8e8f4-602">Word</span><span class="sxs-lookup"><span data-stu-id="8e8f4-602">Word</span></span>

- <span data-ttu-id="8e8f4-603">マウスで X ボタンを使用しているときにクラッシュが生じる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-603">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="8e8f4-604">表内のテキストに合わせる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-604">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="8e8f4-605">水平線の挿入が短くなく、中央に配置されないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-605">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-2002-march-10"></a><span data-ttu-id="8e8f4-607">バージョン 2002: 3 月 10 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-607">Version 2002: March 10</span></span>
<span data-ttu-id="8e8f4-608">*バージョン 2002 (ビルド 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-608">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="8e8f4-609">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-609">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="8e8f4-611">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-611">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="8e8f4-612">Access</span><span class="sxs-lookup"><span data-stu-id="8e8f4-612">Access</span></span>

- <span data-ttu-id="8e8f4-613">**リンク テーブルをすばやく見つける:** 新しい検索ボックスを使用すると、リンク テーブルを簡単に見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-613">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="8e8f4-614">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-614">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="8e8f4-615">Excel</span><span class="sxs-lookup"><span data-stu-id="8e8f4-615">Excel</span></span>

- <span data-ttu-id="8e8f4-p151">**\@@メンションを使用してユーザーの注意を引く:** コメントで @メンションを使うと、仕事仲間によるインプットが必要な場合にそのユーザーに知らせることができます。[詳細情報](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p151">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input. [Learn more](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)</span></span>

- <span data-ttu-id="8e8f4-618">**探しているものを見つける:** コマンド、ユーザー、ファイル、写真、Web の記事などを検索できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-618">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="8e8f4-619">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-619">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="8e8f4-620">**あらましを描く:** ブック内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-620">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="8e8f4-621">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-621">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="8e8f4-622">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-622">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="8e8f4-623">**ブラウザーへのバウンスは不要:** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定することができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-623">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="8e8f4-624">**残っている作業に集中する:** [解決] を選択して、コメントを折りたたみ、開いているアイテムを目立たせます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-624">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="8e8f4-625">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-625">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="8e8f4-626">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-626">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="8e8f4-627">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-627">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="8e8f4-628">**データ ビジュアライザー アドイン:** Excel から Visio フローチャートをすばやく作成します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-628">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="8e8f4-629">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-629">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="8e8f4-630">**すぐに読んで返信する**: ブックを開かずに、メールからコメントやメンションに直接返信します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-630">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="8e8f4-631">**ブックの統計を取得する:** ブックの統計情報にはブックの内容の概要が示されるので、コンテンツをより簡単に見つけ出せます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-631">**Get stats on your workbook:** Workbook Statistics provides an overview of the content of a workbook, to help you more easily discover its contents.</span></span>

- <span data-ttu-id="8e8f4-632">**自分の気分を表現するアイコンの追加:** 300 個以上の新しいアイコンが追加されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-632">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="8e8f4-633">[挿入]、[アイコン] の順に検索してください。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-633">Find them at Insert > Icons.</span></span> [<span data-ttu-id="8e8f4-634">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-634">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a><span data-ttu-id="8e8f4-635">Outlook</span><span class="sxs-lookup"><span data-stu-id="8e8f4-635">Outlook</span></span>

- <span data-ttu-id="8e8f4-636">**Outlook に LinkedIn ネットワークを接続する:** LinkedIn アカウントを Microsoft アカウントに安全に接続して、LinkedIn プロファイルからの情報を [連絡先カード] に直接表示できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-636">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="8e8f4-637">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-637">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="8e8f4-p158">**すべての暗号化オプションを 1 か所に集約:** [オプション] > [暗号化] の順に移動するだけで、電子メール メッセージを保護する方法を選択できます。[詳細情報](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p158">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="8e8f4-640">**テナント管理者によって定義されたアクセス許可を使用して、Outlook の [リンクの挿入] メニューでリンクを挿入する:** Outlook で最近使用されたリンクの挿入 (MRU) のリンクでは、既にそれに対するアクセス許可を持つユーザーのみに動作したリンクが挿入されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-640">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="8e8f4-641">これは、ドキュメントへのアクセス権の付与を求めるユーザー間でのメールの行き来をしばしば引き起こします。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-641">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="8e8f4-642">このエクスペリエンスが更新されましたので、テナント管理者によって設定される既定のアクセス許可を使用し、リンクを挿入できるようになりました。MSIT の場合、これは「組織は編集可」なので、この方法で共有されるリンクを受信するすべての内部ユーザーもアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-642">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="8e8f4-643">**スペルチェックの問題や入力ミスで検索する:** スペルが一致しない場合でも何を検索しているか Outlook が探します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-643">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="8e8f4-644">**フィッシング メールの見分けが簡単に:** スパムとフィッシングのメッセージの外観が他とは異なるので、簡単に見分け、受信トレイから削除できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-644">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="8e8f4-645">**攻撃に対する高度な保護:** Office 365 Advanced Threat Protection を用いると、メールの件名、添付メッセージ、署名されたメッセージ、ネットワーク パスなどの範囲内のハイパーリンクを利用した攻撃から保護されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-645">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="8e8f4-646">**自分で描いて表現しましょう:** 画像の上に走り書きするか、描画キャンバスを追加して、インクを用いて自分の考えを送信します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-646">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="8e8f4-647">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-647">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="8e8f4-648">**検索結果で関連メッセージを確認する:** Outlook では検索条件を分析し、最も関連性の高いメール メッセージを検索結果の上部に表示します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-648">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="8e8f4-649">また、[上位の結果] セクションには、すべての結果が日付順に表示されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-649">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="8e8f4-650">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-650">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- <span data-ttu-id="8e8f4-651">**場所の候補を取得する:** 予定や会議をスケジュールするときに、[場所] に入力すると、会議室、住所、およびその他の最新の場所が提示されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-651">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="8e8f4-652">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-652">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="8e8f4-653">**より多くのメッセージを画面に収める:** [表示] > [より狭い文字間隔を使用] の順に選択し、メッセージの間隔を調整します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-653">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="8e8f4-654">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-654">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="8e8f4-655">**異なる明るさでメッセージを表示する:** [太陽] または [月] のボタンを使用して、閲覧ウィンドウの明るい背景と暗い背景を切り替えます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-655">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="8e8f4-656">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-656">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="8e8f4-657">**自分の気分を表現するアイコンの追加:** 300 個以上の新しいアイコンが追加されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-657">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="8e8f4-658">[挿入]、[アイコン] の順に検索してください。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-658">Find them at Insert > Icons.</span></span> [<span data-ttu-id="8e8f4-659">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-659">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a><span data-ttu-id="8e8f4-660">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8e8f4-660">PowerPoint</span></span>

- <span data-ttu-id="8e8f4-661">**PowerPoint におけるリアルタイム コラボレーションが高速に:** PowerPoint でリアルタイム コラボレーションを高速で行えます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-661">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="8e8f4-662">**新しい文書校正ツール:** 記述する内容についてストレスを感じる必要はありません。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-662">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="8e8f4-663">PowerPoint で、文法や書き方の推奨事項が提示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-663">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="8e8f4-664">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-664">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="8e8f4-665">**ライブ キャプションと字幕:** 発表者の言葉が、キャプションまたは選択した言語での字幕として自動的に画面に表示されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-665">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="8e8f4-666">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-666">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="8e8f4-667">**手書きの数式の自動書式設定:** 手書きの数式を標準の文字に変換することができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-667">**You compute, we format:** We change hand-drawn math expressions into standard characters.</span></span> <span data-ttu-id="8e8f4-668">変換を開始するには、[インクから数式] を選択して、手書きのメモを選択します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-668">Just choose Ink to Math and select your handwritten notes to get started.</span></span> [<span data-ttu-id="8e8f4-669">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-669">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="8e8f4-670">**探しているものを見つける:**[検索] ボックスを使用して、テキスト、コマンド、ヘルプなどを探します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-670">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="8e8f4-671">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-671">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="8e8f4-672">**欠落しているスライド タイトルを見つけて修正する:** スライド タイトルは、ピッチにパンチを加え、すべてのユーザーがスライドにアクセスできるようにします。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-672">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="8e8f4-673">アクセシビリティ ​​チェックは、タイトルがない場所を表示します。これにより、タイトルを簡単に追加できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-673">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="8e8f4-674">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-674">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="8e8f4-675">**あらましを描く:** プレゼンテーション内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-675">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="8e8f4-676">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-676">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="8e8f4-677">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-677">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="8e8f4-678">**ブラウザーへのバウンスは不要:** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定することができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-678">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="8e8f4-679">**図を SVG として保存する:** グラフ、図形、その他の図を、サイズ変更しても画質が低下しないスケーラブル ベクター グラフィックとして保存できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-679">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="8e8f4-680">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-680">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="8e8f4-681">**配布資料にスライド番号を印刷する:** スライド番号は配布資料に自動的に含まれます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-681">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="8e8f4-682">それらをオンのままにするか、オフにするか、選択します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-682">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="8e8f4-683">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-683">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="8e8f4-684">**インクを瞬時に再生:** スライドで手描き入力する場合は、スライド ショー中にアニメーションの再生を適用して、インクの実際の描画が再生されるようにします。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-684">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="8e8f4-685">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-685">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="8e8f4-686">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-686">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

- <span data-ttu-id="8e8f4-687">**プレゼンテーションの最適化:** アクセシビリティ チェックを使用すると、スクリーン リーダーを考慮に入れて、スライド上のオブジェクトを配置することができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-687">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="8e8f4-688">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-688">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="8e8f4-689">**より安全なビデオ エクスペリエンス:** セキュリティの強化は、より安全なオンライン ビデオ エクスペリエンスを意味します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-689">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="8e8f4-690">**再利用しませんか?:** 作成した、または他のユーザーと共有しているスライドを再利用して時間を節約します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-690">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="8e8f4-691">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-691">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- <span data-ttu-id="8e8f4-692">**手書きのインクを図形やテキスト、または Office 365 の PowerPoint での数式に変換する:** フリーフォームのインクを Office の図形、テキスト、数式に数ストロークで変換します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-692">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="8e8f4-693">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-693">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="8e8f4-p177">**インクで素晴らしいスライドを作成:** インクを標準的な図形とテキストに変換し、PowerPoint デザイナーからスマートなスライド デザイン アイデアを入手します。[詳細情報](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p177">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer. [Learn more](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)</span></span>

- <span data-ttu-id="8e8f4-696">**自分の気分を表現するアイコンの追加:** 300 個以上の新しいアイコンが追加されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-696">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="8e8f4-697">[挿入]、[アイコン] の順に検索してください。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-697">Find them at Insert > Icons.</span></span> [<span data-ttu-id="8e8f4-698">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-698">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a><span data-ttu-id="8e8f4-699">Visio</span><span class="sxs-lookup"><span data-stu-id="8e8f4-699">Visio</span></span>

- <span data-ttu-id="8e8f4-700">**犯行現場に戻る:** [犯罪現場] 調査テンプレートで新しい [証拠]、[室内]、および [屋外] のステンシルを使用して、犯罪現場を詳細に再現します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-700">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

- <span data-ttu-id="8e8f4-701">**Excel で洗練された Visio 図を作成する:** ワークシートにデータを入力して、フロー チャートまたは組織図を作成します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-701">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="8e8f4-702">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-702">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="8e8f4-703">Word</span><span class="sxs-lookup"><span data-stu-id="8e8f4-703">Word</span></span>

- <span data-ttu-id="8e8f4-704">**Editor for Resume が LinkedIn 履歴書アシスタントに参加する:** Editor for Resume では履歴書に特化した文法とスタイルのチェックを選択できます。この機能は、より正確かつ専門的に作成するの役立ちます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-704">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="8e8f4-705">**3D オブジェクトのマージによって引き起こされるドキュメント破損の問題を修正しました。:** 3D オブジェクトのマージによって引き起こされるドキュメント破損の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-705">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="8e8f4-706">**探しているものを見つける:**[検索] ボックスを使用して、テキスト、コマンド、ヘルプなどを探します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-706">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="8e8f4-707">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-707">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="8e8f4-708">**鮮やかな色で共同作業する:** コメントや変更内容のカラー コードが共同作成者によって指定され、共同作成者のうちのだれによって行われたかが簡単にわかります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-708">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="8e8f4-709">**マクロ有効文書を共同作業で編集する:** 文書ファイルを OneDrive for Business に保存し、リアルタイムで共同作成者は編集できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-709">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

- <span data-ttu-id="8e8f4-710">**共同編集の改善**: 変更を追跡したドキュメントで共同編集を行う際の Word のパフォーマンスが改善されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-710">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="8e8f4-711">**自分の気分を表現するアイコンの追加:** 300 個以上の新しいアイコンが追加されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-711">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="8e8f4-712">[挿入]、[アイコン] の順に検索してください。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-712">Find them at Insert > Icons.</span></span> [<span data-ttu-id="8e8f4-713">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-713">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="8e8f4-714">**他のユーザーがすばやく変更を確認する:** 共同編集の改善とは、これまでになく迅速に、共同作業者がユーザーによる変更を確認できることを意味します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-714">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="8e8f4-715">**あらましを描く:** ドキュメント内の Office の図形をカジュアルな手描き風にします。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-715">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="8e8f4-716">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-716">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="8e8f4-717">**精度による消去:** 手描き入力の小さな不備を修正するのに、2 つのサイズの消しゴムから選択できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-717">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="8e8f4-718">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-718">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="8e8f4-719">**ファイル共有の高速化:** ファイルを開かなくても、最近使用したファイルの一覧からドキュメントを直接共有できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-719">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="8e8f4-720">**ブラウザーへのバウンスは不要** ブラウザーまたはアプリで Office ドキュメントへのリンクを開く方法を決定します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-720">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="8e8f4-721">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-721">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="8e8f4-722">**共同編集の改善:** 共同編集時の信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-722">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="8e8f4-723">**よりアクセシビリティの高い PDF ファイルを作成する:** PDF を作成すると、アクセシビリティ チェックが、保存する前に修正するアクセシビリティの問題を指摘します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-723">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="8e8f4-724">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-724">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="8e8f4-725">**ファイルを変換してアクセシビリティを向上させる**: ファイルを最新の形式にアップグレードすると、すべてのユーザがアクセスできるようになります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-725">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="8e8f4-726">**より安全なビデオ エクスペリエンス:** セキュリティの強化は、より安全なオンライン ビデオ エクスペリエンスを意味します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-726">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="8e8f4-727">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-727">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="8e8f4-730">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="8e8f4-730">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="8e8f4-731">Access</span><span class="sxs-lookup"><span data-stu-id="8e8f4-731">Access</span></span>

- <span data-ttu-id="8e8f4-732">この更新プログラムにより、更新クエリが実行されるか、SQL で UPDATE ステートメントが使用されるときに "クエリは破損しています" というエラーを発生させる場合のある Microsoft Access の問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-732">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

- <span data-ttu-id="8e8f4-733">この更新プログラムでは、Microsoft Access がリンクされた SQL Server テーブル内の ID 列を識別できない原因となり、行が削除されたと誤って報告される原因となる問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-733">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="8e8f4-p187">この更新は、ADODB を使用する問題を修正します。 VB コードのレコーダー オブジェクトでエラーが誤って報告される場合があります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p187">This update fixes an issue where using an ADODB. Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="8e8f4-736">Access テンプレートは、データベース内の添付ファイル列のエラーを発生させることがなくなりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-736">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="8e8f4-737">テンプレートのインスタンス化後に、データベースに添付ファイル フィールドを追加できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-737">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="8e8f4-738">Excel</span><span class="sxs-lookup"><span data-stu-id="8e8f4-738">Excel</span></span>

- <span data-ttu-id="8e8f4-739">署名の名前を変更したときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-739">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="8e8f4-740">この変更は、ソフトウェア レンダリングを活用することにより、特定の Intel グラフィック ドライバーの問題を回避します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-740">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="8e8f4-741">はみ出している列挙が含まれるセルで区切り位置を指定するとクラッシュが発生することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-741">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="8e8f4-742">この更新によって、数式バーに予期したのとは異なるフォントでテキストが表示される原因となっていた問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-742">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="8e8f4-743">一部のロケールにおいて、[Text to Column] 機能が失敗することがあります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-743">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="8e8f4-744">非表示の名前付き範囲にアクセスすると、ユーザーにエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-744">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="8e8f4-745">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-745">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="8e8f4-746">スクロール後にセルを選択すると間違ったセルが選択されることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-746">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="8e8f4-747">信頼されていないネットワーク共有から保護されたファイルを編集する際に、Excel にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-747">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="8e8f4-748">一部のローカライズにおいて、[Text to Column] 機能が失敗することがあります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-748">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="8e8f4-749">非表示の名前付き範囲にアクセスすると、ユーザーにエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-749">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="8e8f4-750">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-750">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="8e8f4-751">一部のユーザーが埋め込みオブジェクトとリンク オブジェクト (OLE) で経験する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-751">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="8e8f4-752">ピボット グラフの右クリック メニューを修正して、[詳細の表示] オプションを有効にしました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-752">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="8e8f4-753">ブックが開かれていない状態で最近使用したファイルを検索するときに、クラッシュを発生させる原因となっていた可能性がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-753">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="8e8f4-754">ブックで外部リンクがある場合に複数のポップアップ ウィンドウで一部のユーザーに生じる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-754">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="8e8f4-755">コンテキスト メニューのコメント コマンドが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-755">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="8e8f4-756">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-756">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="8e8f4-757">CUBEVALUE 関数が間違った結果を返すことがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-757">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="8e8f4-758">Outlook</span><span class="sxs-lookup"><span data-stu-id="8e8f4-758">Outlook</span></span>

- <span data-ttu-id="8e8f4-759">検索に関するフィードバックのエクスペリエンスで終了する原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-759">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="8e8f4-760">ユーザーがクラウド設定を取得する際に Outlook がフリーズする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-760">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="8e8f4-761">検索ボックスが高 DPI モードで不適切に表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-761">Addressed an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="8e8f4-762">ユーザーが Outlook プロセスでメモリ リークを観測する原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-762">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="8e8f4-763">状況によっては、表示された SMTP アドレスと一致しないアドレスに送信されたメールがユーザーに表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-763">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="8e8f4-764">この変更により、メッセージ ヘッダーに複数行の件名を表示できる機能が復元されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-764">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="8e8f4-765">WebDAV の場所にファイルを保存できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-765">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="8e8f4-766">SMIME アルゴリズムの選択に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-766">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="8e8f4-767">サードパーティ製アプリケーションがメールを送信できない原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-767">Addressed an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="8e8f4-768">アカウント作成コンテキストからサポートに連絡しようとすると、ユーザーに [OK] ボタンのある空のメッセージ ボックスが表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-768">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="8e8f4-769">ユーザーがプロフィールの作成中にクラッシュを発生させる原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-769">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="8e8f4-770">同期のスライダーが小さい設定に設定されている場合でも、Outlook で予期せずすべてのメールが同期される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-770">Addressed an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="8e8f4-771">黒のテーマを持つユーザーが [差出人] ドロップダウンを表示すると、白色の背景に白いテキストが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-771">Addressed an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="8e8f4-772">ユーザーがアカウントのセットアップをキャンセルするときにクラッシュする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-772">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="8e8f4-773">署名の名前を変更したときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-773">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="8e8f4-774">フラグ付きアイテムの強調表示を無効にするオプションが一部のシナリオで無視される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-774">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="8e8f4-775">ユーザーが [ルール] ダイアログを開くと、"このコンピューターのルールは、Microsoft Exchange のルールと異なります" というメッセージが表示される原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-775">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="8e8f4-776">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-776">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="8e8f4-777">非常に長い Outlook セッションでメモリ リークを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-777">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="8e8f4-778">複数のウィンドウで同じアイテムを表示するとクラッシュする場合がある問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-778">Addressed an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="8e8f4-779">キーボード ショートカットを使用してメールボックス フォルダーを操作すると、ユーザーに顕著な遅延が発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-779">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="8e8f4-780">ユーザーが定期的な予定表の一部のインスタンスを開けない原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-780">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="8e8f4-781">Exchange 2010 サーバー上にメールボックスを持つユーザーが、予定表の項目に添付ファイルを追加するときに生じる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-781">Addressed an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="8e8f4-782">ユーザーがデジタル署名されたメッセージに返信するときに生じる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-782">Addressed an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="8e8f4-783">会議の [場所] フィールドが予期せず更新される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-783">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="8e8f4-784">会議の [場所] フィールドにあるコンマがセミコロンになる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-784">Addressed an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="8e8f4-785">会議をクリアした後、会議の場所が予期せずに会議に追加される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-785">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="8e8f4-786">ブラジルのタイムゾーンで設定された会議や予定に関連する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-786">Addressed issues relating to meetings and appointments set in the Brazilia time zone.</span></span>

- <span data-ttu-id="8e8f4-787">[アクセシビリティ チェック] ペインを閉じた後に「S」キーを押すと、メールが予期せず送信されたようにユーザーに表示される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-787">Addressed an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="8e8f4-788">これにより、Python による添付ファイルもブロックされるよう、Outlook の添付ファイルのブロック ロジックが更新されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-788">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="8e8f4-789">Web アドインがデジタル著作権管理 (DRM) メッセージにアクセスする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-789">Addressed an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="8e8f4-790">ユーザーがプロフィールの作成中にクラッシュを発生させる原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-790">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="8e8f4-791">署名の名前を変更したときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-791">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8e8f4-792">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8e8f4-792">PowerPoint</span></span>

- <span data-ttu-id="8e8f4-793">Shape.Paste メソッドを使用する際に発生する問題を解決しました。Shape.Paste メソッドを使用して図形をコピーして貼り付けるときに、貼り付けられた図形の選択内容が変更するという問題です。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-793">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="8e8f4-794">従来の PPT コメントでコンテキスト メニューを使用するときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-794">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

### <a name="project"></a><span data-ttu-id="8e8f4-795">Project</span><span class="sxs-lookup"><span data-stu-id="8e8f4-795">Project</span></span>

- <span data-ttu-id="8e8f4-796">読み取り専用のプロジェクトを開いたときに複数のメッセージを取得する可能性があるという問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-796">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="8e8f4-797">作業時間固定タイプの達成率 100% のタスクで、達成率が誤って 100% 未満に計算される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-797">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

- <span data-ttu-id="8e8f4-798">サマリー タスクの日付の計算に常に誤りが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-798">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="8e8f4-799">OnUndoOrRedo イベントが、OpenUndoTransaction メソッドを最初に実行しないと起動しないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-799">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="8e8f4-800">Word</span><span class="sxs-lookup"><span data-stu-id="8e8f4-800">Word</span></span>

- <span data-ttu-id="8e8f4-801">既存のファイルを保存すると [名前を付けて保存] ダイアログが必ず表示され、ファイルは実際には保存されない場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-801">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="8e8f4-802">文書パーツ オーガナイザーに 「スタイル、文書パーツを変更しました」 という無効なアラートが表示される場合があります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-802">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="8e8f4-803">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8e8f4-803">Office Suite</span></span>

- <span data-ttu-id="8e8f4-804">この変更により、マーカー付きの一部の散布図の表示が遅くなる問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-804">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="8e8f4-805">この変更では、Intel Integrated GPU を使用するグラフィック アダプターに関して報告された問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-805">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="8e8f4-806">ODT と GPO の更新期限設定で、相対期限の設定後、初回のみしか機能しないバスが修正されました。修正により、2 回目以降の更新プログラムで相対期限を使用きるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-806">Fixed a bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="8e8f4-807">Office の更新プログラムが、意図したソース (ローカル共有、ネットワーク共有、構成マネージャー
で提供される場所など) からではなく、予期せずに Office CDN からファイルをダウンロードする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-807">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="8e8f4-808">同じ SharePoint ライブラリから Word/Excel/PowerPoint で複数のドキュメントが開かれている場合、最初に開いたドキュメントのみがポリシー コンプライアンスでスキャンされる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-808">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-february-11"></a><span data-ttu-id="8e8f4-810">バージョン 1908: 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-810">Version 1908: February 11</span></span>
<span data-ttu-id="8e8f4-811">*バージョン 1908 (ビルド 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-811">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="8e8f4-812">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-812">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="8e8f4-814">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="8e8f4-814">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8e8f4-815">Excel</span><span class="sxs-lookup"><span data-stu-id="8e8f4-815">Excel</span></span>

- <span data-ttu-id="8e8f4-816">この更新プログラムは、VBA を使用してグラフのヘッダー/フッターに画像を追加するたびにエラーが発生する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-816">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="8e8f4-817">グループ ボックス コントロールの境界線が印刷プレビューまたは印刷時に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-817">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="8e8f4-818">英語以外の文字セットを使用している場合に、ユーザーが変更を保存する際にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-818">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="8e8f4-819">グラフを含むブックを保存すると、グラフ ヘッダーの画像のファイル サイズが大きくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-819">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="8e8f4-820">選択範囲を相互参照ブックと同期させ続けることにより、相互参照ブックの DBCS 文字が破損する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-820">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="8e8f4-821">自動調整を使用して行の高さを調整するときにチェック ボックスのコントロールが縮小される可能性があるという問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-821">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="8e8f4-822">Outlook</span><span class="sxs-lookup"><span data-stu-id="8e8f4-822">Outlook</span></span>

- <span data-ttu-id="8e8f4-823">無効な差出人アドレスを指定するとクラッシュが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-823">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="8e8f4-824">競合メッセージの処理中にユーザーに同期エラーが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-824">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="8e8f4-825">Outlook の起動時にユーザーが [プロファイルの読み込み中] 画面でハングアップする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-825">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="8e8f4-826">ビューを変更すると、断続的なクラッシュが発生する問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-826">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="8e8f4-827">Citrix 環境で 30 件を超える予定表を表示したときにクラッシュする原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-827">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="8e8f4-828">[こちら](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)は、以前のバージョンで文書化された個々の KB です。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-828">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="8e8f4-829">ユーザーが OST と同期している共有予定表フォルダーに問題があり、これらのフォルダーを操作しようとするとアクセス許可エラーが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-829">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8e8f4-830">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8e8f4-830">PowerPoint</span></span>

- <span data-ttu-id="8e8f4-831">PowerPoint スライドでのコピーと貼り付けのシナリオである図形のコピーを改善しました。ループ内の他のスライドに貼り付けると例外で失敗する場合があります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-831">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="8e8f4-832">共同作業ユーザー間のパフォーマンスが低下する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-832">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="8e8f4-833">増分で開くファイルに、複数のメディア ストリームが埋め込まれたスライドが含まれている場合に発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-833">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="8e8f4-834">PowerPoint の初回起動時に、信頼されていないアドインに対してセキュリティ警告メッセージ バーが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-834">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="8e8f4-835">Project</span><span class="sxs-lookup"><span data-stu-id="8e8f4-835">Project</span></span>

- <span data-ttu-id="8e8f4-836">基本カレンダーが変更されたときにリソース カレンダーが更新されないために、実際の作業がタイムシートとプロジェクト計画の間で異なる場合があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-836">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="8e8f4-837">Word</span><span class="sxs-lookup"><span data-stu-id="8e8f4-837">Word</span></span>

- <span data-ttu-id="8e8f4-838">非推奨の API から移動することにより、Word でクラッシュが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-838">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8e8f4-839">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8e8f4-839">Office Suite</span></span>

- <span data-ttu-id="8e8f4-840">この変更は、破損したファイルを開いた後の画像の正しいレンダリングに対処します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-840">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-january-14"></a><span data-ttu-id="8e8f4-842">バージョン 1908: 1 月 14 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-842">Version 1908: January 14</span></span>
<span data-ttu-id="8e8f4-843">*バージョン 1908 (ビルド 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-843">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="8e8f4-844">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-844">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="8e8f4-846">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="8e8f4-846">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="8e8f4-847">Excel</span><span class="sxs-lookup"><span data-stu-id="8e8f4-847">Excel</span></span>

- <span data-ttu-id="8e8f4-848">ドキュメント タイトルのオランダ語の KeyTip が Alt-G に変更されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-848">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="8e8f4-849">埋め込まれたブックを開くときにリボンのカスタマイズが読み込まれない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-849">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="8e8f4-850">アドインによって開かれた WPF (Windows Presentation Foundation) フォームのコンボ ボックスからアイテムを選ぶことができない問題が発生しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-850">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="8e8f4-851">Outlook</span><span class="sxs-lookup"><span data-stu-id="8e8f4-851">Outlook</span></span>

- <span data-ttu-id="8e8f4-852">キーボード ショートカットを使用してメールボックス フォルダーを操作すると、ユーザーに顕著な遅延が発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-852">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="8e8f4-853">代替送信者を使用しているときに、ポリシーのヒントが表示されない原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-853">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="8e8f4-854">プレゼンス情報を更新するときに、断続的なクラッシュを発生させる原因となっていた問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-854">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8e8f4-855">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8e8f4-855">PowerPoint</span></span>

- <span data-ttu-id="8e8f4-856">スライドを 1 つのプレゼンテーションから別のプレゼンテーションにコピーすると、重複したマスターが作成される可能性があるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-856">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>
- <span data-ttu-id="8e8f4-857">最新のコメントを含むファイルを、サポートされていないバージョンで開くと黄色の警告が表示されます</span><span class="sxs-lookup"><span data-stu-id="8e8f4-857">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

### <a name="office-suite"></a><span data-ttu-id="8e8f4-858">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8e8f4-858">Office Suite</span></span>

- <span data-ttu-id="8e8f4-859">Office の更新メッセージが、異なる言語で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-859">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="8e8f4-860">今後、Office の更新メッセージは Windows の表示言語と一致します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-860">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="8e8f4-861">ユーザーが管理者ではなく、システム アカウントにネットワーク接続が確立されていない場合に、更新プログラムが適用されない問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-861">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>



## <a name="version-1908-december-10"></a><span data-ttu-id="8e8f4-862">バージョン 1908: 12 月 10 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-862">Version 1908: December 10</span></span>
<span data-ttu-id="8e8f4-863">*バージョン 1908 (ビルド 11929.20516)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-863">*Version 1908 (Build 11929.20516)*</span></span>

<span data-ttu-id="8e8f4-864">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-864">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="8e8f4-866">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="8e8f4-866">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="8e8f4-867">Access</span><span class="sxs-lookup"><span data-stu-id="8e8f4-867">Access</span></span>

- <span data-ttu-id="8e8f4-868">リモート テーブル (SQL Server テーブルなど) への参照を含むユニオン クエリにより Access が閉じて再起動する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-868">Fixed an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="8e8f4-869">Sum などの集計が結果を整数値に切り捨てる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-869">Fixed an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

### <a name="excel"></a><span data-ttu-id="8e8f4-870">Excel</span><span class="sxs-lookup"><span data-stu-id="8e8f4-870">Excel</span></span>

- <span data-ttu-id="8e8f4-871">スクロール後にセルを選択すると間違ったセルが選択されることがある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-871">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="8e8f4-872">OLAP ピボットテーブルのフィルターがキューブから削除された値に設定された場合の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-872">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="8e8f4-873">この変更は、ソフトウェア レンダリングを活用することにより、特定の Intel グラフィック ドライバーの問題を回避します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-873">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="8e8f4-874">Lookup 関数がエラーを返す問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-874">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="8e8f4-875">結合されたセルで列を削除するパフォーマンスが大幅に改善されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-875">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="8e8f4-876">最小化されたウィンドウをアクティブにするマクロ実行時エラーの原因となる問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-876">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

### <a name="outlook"></a><span data-ttu-id="8e8f4-877">Outlook</span><span class="sxs-lookup"><span data-stu-id="8e8f4-877">Outlook</span></span>

- <span data-ttu-id="8e8f4-878">SMIME アルゴリズムの選択に関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-878">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="8e8f4-879">ユーザーが [ルール] ダイアログを開くと、「&quot;このコンピューターのルールは、Microsoft Exchange のルールと異なります&quot;」というメッセージが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-879">Addressed an issue that caused users to see a &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="8e8f4-880">Web アドインがデジタル著作権管理 (DRM) メッセージにアクセスするべきではないときにアクセスする原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-880">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

### <a name="word"></a><span data-ttu-id="8e8f4-881">Word</span><span class="sxs-lookup"><span data-stu-id="8e8f4-881">Word</span></span>

- <span data-ttu-id="8e8f4-882">無限ループになることがあるトラック変更の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-882">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8e8f4-883">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8e8f4-883">Office Suite</span></span>

- <span data-ttu-id="8e8f4-884">PowerPoint の垂直テキストボックスで半角カタカナ文字が適切に回転しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-884">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="8e8f4-885">Office の更新プログラムが、意図したソース (ローカル共有、ネットワーク共有、構成マネージャー
で提供される場所など) からではなく、予期せずに Office CDN からファイルをダウンロードする場合がある問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-885">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="8e8f4-886">Office ユーザーのセキュリティを保護するために、Microsoft Office の更新プログラムは SHA-2 アルゴリズムのみを使用して署名されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-886">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>



[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-november-22"></a><span data-ttu-id="8e8f4-888">バージョン 1908: 11 月 22 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-888">Version 1908: November 22</span></span>
<span data-ttu-id="8e8f4-889">*バージョン 1908 (ビルド 11929.20494)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-889">*Version 1908 (Build 11929.20494)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="8e8f4-891">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="8e8f4-891">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="8e8f4-892">Access</span><span class="sxs-lookup"><span data-stu-id="8e8f4-892">Access</span></span>

- <span data-ttu-id="8e8f4-893">更新クエリを実行すると "クエリが破損しています" という誤ったエラー メッセージが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-893">Fixed an issue where running an Update query would incorrectly give an error message: "Query is corrupt".</span></span>

### <a name="excel"></a><span data-ttu-id="8e8f4-894">Excel</span><span class="sxs-lookup"><span data-stu-id="8e8f4-894">Excel</span></span>

- <span data-ttu-id="8e8f4-895">ファイルに広範な条件付き書式が設定されている場合に、[フォントの色] ボタンをクリックするとパフォーマンスが低下する問題。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-895">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="8e8f4-896">印刷プレビューの印刷範囲が正しくないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-896">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="8e8f4-897">信頼されていないネットワーク共有から保護されたファイルを編集する際に、Excel にエラーが発生する場合があります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-897">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="8e8f4-898">ブックが開かれていない状態で最近使用したファイルを検索する際にクラッシュが発生する可能性がある問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-898">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

### <a name="outlook"></a><span data-ttu-id="8e8f4-899">Outlook</span><span class="sxs-lookup"><span data-stu-id="8e8f4-899">Outlook</span></span>

- <span data-ttu-id="8e8f4-900">アカウント作成コンテキストからサポートに連絡しようとすると、ユーザーに [&quot;OK&quot;] ボタンのある空のメッセージ ボックスが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-900">Addressed an issue that caused users to see an empty message box with an &quot;OK&quot; button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="8e8f4-p191">UPN 経由で自動検出の認証プロンプトに提供される電子メール アカウントの方を選択するために、ポリシーを管理者が有効にできるよう変更が行われました。既定では、使用可能な場合に、自動検出ではアカウント UPN の方が選択されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p191">Made a change that allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN. By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="8e8f4-903">最新のグループに対し、検索の失敗がユーザーに表示される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-903">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="8e8f4-904">&quot;不在着信した会話&quot; メッセージのルールを作成しようとするときに、クラッシュを発生させる原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-904">Addressed an issue that caused users to experience a crash when attempting to create a rule from a &quot;Missed Conversation&quot; message.</span></span>

- <span data-ttu-id="8e8f4-905">最新のグループに対し、検索の失敗がユーザーに表示される原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-905">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

### <a name="word"></a><span data-ttu-id="8e8f4-906">Word</span><span class="sxs-lookup"><span data-stu-id="8e8f4-906">Word</span></span>

- <span data-ttu-id="8e8f4-907">Deskjet プリンターへの印刷時にスケーリングの問題を引き起こす可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-907">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8e8f4-908">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8e8f4-908">Office Suite</span></span>

- <span data-ttu-id="8e8f4-909">オンライン プレゼンテーションを行おうとするときに、PowerPoint ユーザーにエラーが発生しないように問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-909">Fixed an issue to prevent PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="8e8f4-910">レジストリ整合性に関する Office 更新プロセスの信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-910">Improved reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="8e8f4-911">従量制課金ネットワークで更新プログラムが予期せずブロックされる可能性があるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-911">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="8e8f4-912">相対期限が初めて設定されるときのみ機能するところの ODT と GPO の更新期限の設定に関する問題が修正されました。修正により、2 回目以降の更新プログラムに相対期限を使用することができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-912">Fixed an issue in ODT and GPO Updae Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-november-12"></a><span data-ttu-id="8e8f4-914">バージョン 1908: 11 月 12 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-914">Version 1908: November 12</span></span>
<span data-ttu-id="8e8f4-915">*バージョン 1908 (ビルド 11929.20436)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-915">*Version 1908 (Build 11929.20436)*</span></span>

<span data-ttu-id="8e8f4-916">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-916">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="resolved-issues"></a><span data-ttu-id="8e8f4-918">解決済みの問題</span><span class="sxs-lookup"><span data-stu-id="8e8f4-918">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="8e8f4-919">Excel</span><span class="sxs-lookup"><span data-stu-id="8e8f4-919">Excel</span></span>

- <span data-ttu-id="8e8f4-920">グラフ テンプレートを使用してグラフを挿入する場合に、プレビューで正しい色が使用されるよう修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-920">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>
- <span data-ttu-id="8e8f4-921">シリーズ コレクションを変更するときに、散布図が適切にレンダリングされない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-921">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>
- <span data-ttu-id="8e8f4-922">実行中のマクロでカスタム プロパティを変更すると、共同編集の中断を引き起こす問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-922">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>
- <span data-ttu-id="8e8f4-923">非同期のユーザー定義関数が同期して実行されるパフォーマンスの問題を解決ました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-923">We resolved an performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>
- <span data-ttu-id="8e8f4-924">色によるフィルタリングのパフォーマンスが大幅に向上しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-924">We have significantly improved the performance of filtering by color.</span></span>
- <span data-ttu-id="8e8f4-925">Office 現在のバージョンで開いた場合に Excel の停止を引き起こす可能性がある、Office の以前のバージョンで作成されるブックの問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-925">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>
- <span data-ttu-id="8e8f4-926">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-926">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

### <a name="outlook"></a><span data-ttu-id="8e8f4-927">Outlook</span><span class="sxs-lookup"><span data-stu-id="8e8f4-927">Outlook</span></span>

- <span data-ttu-id="8e8f4-928">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-928">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>
- <span data-ttu-id="8e8f4-929">プライマリ予定表からグループ予定表にアイテムをコピーするときに、ユーザーに権限エラーが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-929">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>
- <span data-ttu-id="8e8f4-930">非常に長い Outlook セッションでメモリ リークが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-930">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>
- <span data-ttu-id="8e8f4-931">特定のセーフリンクを操作すると、Outlook でユーザーにエラーが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-931">Addressed an issue that would cause users to experience a failure in Outlook when interacting with certain safelinks.</span></span>
- <span data-ttu-id="8e8f4-932">一部の AutoDiscover の応答の処理中にユーザーにエラーが発生する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-932">Addressed an issue that caused users to experience a failure when processing some AutoDiscover responses.</span></span>
- <span data-ttu-id="8e8f4-933">一部のユーザーに、セカンダリ Exchange アカウントを追加するときに作成された重複した特別なフォルダーが表示される問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-933">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>
- <span data-ttu-id="8e8f4-934">検索に関するフィードバックのエクスペリエンスでハングアップする問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-934">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8e8f4-935">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8e8f4-935">PowerPoint</span></span>

- <span data-ttu-id="8e8f4-936">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-936">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>
- <span data-ttu-id="8e8f4-937">信頼性の修正: サード パーティのアドインが PowerPoint を失敗させることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-937">Reliability fix: Fixed an issue where third party add-in might cause PowerPoint to fail.</span></span>

### <a name="project"></a><span data-ttu-id="8e8f4-938">Project</span><span class="sxs-lookup"><span data-stu-id="8e8f4-938">Project</span></span>

- <span data-ttu-id="8e8f4-939">[すべて平準化] コマンドがリソースの割り当て超過を適切に解決していなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-939">Fixed an issue where the Level All command wasn't properly resolving a resource overallocation.</span></span>
- <span data-ttu-id="8e8f4-940">タスクの作業がゼロの割り当てがある場合、タスクに完了のマークを付けることができず、常に 99％ で表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-940">Fixed an issue where if you have an assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>
- <span data-ttu-id="8e8f4-941">読み取り専用のプロジェクトを開いたときに複数のメッセージを取得する可能性があるという問題を特定しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-941">Identified an issue where users could get several messages when opening a read-only project.</span></span>

### <a name="word"></a><span data-ttu-id="8e8f4-942">Word</span><span class="sxs-lookup"><span data-stu-id="8e8f4-942">Word</span></span>

- <span data-ttu-id="8e8f4-943">Outlook メッセージからの cid: 画像のリンクが、要求があったときに正常に分割できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-943">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>
- <span data-ttu-id="8e8f4-944">シャットダウン時にアプリがハングアップすることがあるさまざまな問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-944">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="8e8f4-945">特定のアドインに関連する問題も修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-945">Also fixed certain add-in related failures.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8e8f4-946">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8e8f4-946">Office Suite</span></span>

- <span data-ttu-id="8e8f4-947">サード パーティ製プラグインのテキスト ボックスと図形の AutoFit に関連する問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-947">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="october-15"></a><span data-ttu-id="8e8f4-949">10 月 15 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-949">October 15</span></span>

### <a name="non-security-updates"></a><span data-ttu-id="8e8f4-950">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-950">Non-security updates</span></span>

### <a name="office-suite"></a><span data-ttu-id="8e8f4-951">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8e8f4-951">Office Suite</span></span>
- <span data-ttu-id="8e8f4-p193">16.0.11929.20396 よりも古いビルドで 2019 年 10 月 14 日に投稿された保存の問題を解決するために、一時的に [クラウド保存] ダイアログを無効にしました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p193">We have temporarily disabled the Cloud Save dialog to address the saving issue we posted on October 14, 2019 for builds older than 16.0.11929.20396. This feature will be re-enabled soon.</span></span>

## <a name="version-1908-october-14"></a><span data-ttu-id="8e8f4-954">バージョン 1908: 10 月 14 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-954">Version 1908: October 14</span></span>
<span data-ttu-id="8e8f4-955">*バージョン 1908 (ビルド 11929.20396)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-955">*Version 1908 (Build 11929.20396)*</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="8e8f4-957">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-957">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="8e8f4-958">Excel</span><span class="sxs-lookup"><span data-stu-id="8e8f4-958">Excel</span></span>

- <div><span data-ttu-id="8e8f4-959">最初の項目を検索した後に、ダイアログでフォーカスが位置づけられていた場所を変更する検索と置換についての問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-959">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span></div>

### <a name="office-suite"></a><span data-ttu-id="8e8f4-960">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8e8f4-960">Office Suite</span></span>

- <span data-ttu-id="8e8f4-p194">ユーザーが、Word、Excel、およびビルド 16.0.11929.20396 以前の PowerPoint 2019 のドキュメントを保存できなくなる場合があるという問題が解決されました。この問題は、[保存] アイコンをクリックしたり Ctrl キーを押しながら S キーを押したりした後に、新しいファイルを作成して [名前を付けて保存] ダイアログを表示するユーザーに影響を与えます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p194">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint 2019 documents for builds older than 16.0.11929.20396.  This issue affects users that create a new file and bring up the “Save As” dialog after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="8e8f4-963">特定の状況で、更新後に Office ショートカットが消えてしまう場合があるという問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-963">Resolved an issue where in certain circumstances, Office shortcuts may disappear following an update.</span></span>  <span data-ttu-id="8e8f4-964">この更新プログラムでは、Office ショートカットを公開するときの信頼性を向上します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-964">This update improves reliability when publishing of Office shortcuts.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-october-08"></a><span data-ttu-id="8e8f4-966">バージョン 1908: 10 月 8 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-966">Version 1908: October 08</span></span>
<span data-ttu-id="8e8f4-967">*バージョン 1908 (ビルド 11929.20388)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-967">*Version 1908 (Build 11929.20388)*</span></span>

<span data-ttu-id="8e8f4-968">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-968">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="8e8f4-970">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-970">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="8e8f4-971">Excel</span><span class="sxs-lookup"><span data-stu-id="8e8f4-971">Excel</span></span>

- <span data-ttu-id="8e8f4-972">一部の保護されたシートにハイパーリンクが貼り付けられない問題を解決しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-972">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="8e8f4-973">アドイン マネジャーで参照するときに、16 個以上のアドインを表示できる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-973">Fixed an issue to enable more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="8e8f4-974">Win32 クライアントの [アイデア] ボタンをクリックしてアドインを読み込むときにエラーが発生するという Excel のアイデア機能の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-974">Fixed issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="8e8f4-975">Outlook</span><span class="sxs-lookup"><span data-stu-id="8e8f4-975">Outlook</span></span>

- <span data-ttu-id="8e8f4-976">一部の safelinks に対して簡易的なホバーの URL が正しく表示されなくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-976">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="8e8f4-977">Python による添付ファイルもブロックされるよう、Outlook の添付ファイルのブロック ロジックを更新しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-977">Updated the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="8e8f4-978">ユーザーが Outlook プロセスでメモリ リークを観測する原因となった問題に対処しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-978">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8e8f4-979">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8e8f4-979">PowerPoint</span></span>

- <span data-ttu-id="8e8f4-980">PowerPoint での共同編集とオフライン編集の両方を含むセッションでデータの損失を引き起こす可能性のある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-980">Fixed an issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

### <a name="office-suite"></a><span data-ttu-id="8e8f4-981">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8e8f4-981">Office Suite</span></span>

- <span data-ttu-id="8e8f4-982">ユーザーがファイルを開くときに発生する可能性のあるクラッシュの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-982">Fixed an issue for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="8e8f4-983">Backstage の Info Place のスラブにアクセシビリティ情報が表示されていない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-983">Fixed an issue where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="8e8f4-984">以前に中断された可能性のあるダウンロードを再開することにより、Office の更新プログラムをダウンロードするときの信頼性が向上しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-984">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="8e8f4-985">Office ユーザーのセキュリティを保護するために、Microsoft Office の更新プログラムは SHA-2 アルゴリズムのみを使用して署名されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-985">To protect Office customer’s security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1908-september-10"></a><span data-ttu-id="8e8f4-987">バージョン 1908: 9 月 10 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-987">Version 1908: September 10</span></span>
<span data-ttu-id="8e8f4-988">*バージョン 1908 (ビルド 11929.20300)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-988">*Version 1908 (Build 11929.20300)*</span></span>

<span data-ttu-id="8e8f4-989">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-989">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (FEATUREDETAILS コンテンツを削除しないでください。開始)

### <a name="feature-updates"></a><span data-ttu-id="8e8f4-991">機能の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-991">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="8e8f4-992">Access</span><span class="sxs-lookup"><span data-stu-id="8e8f4-992">Access</span></span>

- <span data-ttu-id="8e8f4-993">**より大きい [ズーム] ボックス:** [ズーム] ボックスがより大きく表示され、そこでフォントを変更することができます。変更内容はすべて [ズーム] ボックス内に記憶されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-993">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="8e8f4-994">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-994">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

- <span data-ttu-id="8e8f4-995">**データベース オブジェクトをタブで管理する:** アクティブなタブが分かりやすく表示され、簡単にタブをドラッグして再配置し、ワンクリックでデータベース オブジェクトを閉じることができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-995">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="8e8f4-996">**シームレスに切り替える:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用のアカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-996">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="8e8f4-997">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-997">Switching between them has never been easier.</span></span> [<span data-ttu-id="8e8f4-998">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-998">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="excel"></a><span data-ttu-id="8e8f4-999">Excel</span><span class="sxs-lookup"><span data-stu-id="8e8f4-999">Excel</span></span>

- <span data-ttu-id="8e8f4-1000">**データの詳細を検出する:** 新しいアイデア ボタンは、データのパターンを探し、それを使用してインテリジェントな個人向けの提案を作成します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1000">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions.</span></span> [<span data-ttu-id="8e8f4-1001">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1001">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- <span data-ttu-id="8e8f4-1002">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1002">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="8e8f4-1003">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1003">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="8e8f4-1004">**コンテンツのリーチを拡大する:** プレゼンテーションのアクセシビリティを高める必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1004">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="8e8f4-1005">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1005">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="8e8f4-1006">[校閲]>[アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1006">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="8e8f4-1007">**シームレスに切り替える:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用のアカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1007">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="8e8f4-1008">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1008">Switching between them has never been easier.</span></span> [<span data-ttu-id="8e8f4-1009">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1009">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="8e8f4-1010">**ワークシートに生気を吹き込む:** アニメーション 3D グラフィックスを挿入して、鼓動する心臓、周回する惑星、暴れまわるティラノサウルスをワークブックに表示できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1010">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="8e8f4-1011">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1011">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="8e8f4-1012">**共同作業がさらに簡単に:** 共同編集の改善とは、条件付き書式、セルのスタイルなどを使用して作業しているときに、ユーザーによる変更がシームレスに共同作業者の変更と統合されるということです。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1012">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="8e8f4-1013">**類似列のテーブルを結合する:** 取得と変換 (Power Query) では、テーブルを統合するために列を比較するときに、近似文字列マッチング ロジック (あいまい一致とも呼ばれる) が使用できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1013">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="8e8f4-1014">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1014">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="8e8f4-1015">**Power Query の機能強化を使用して素早くコーディングする:** オートコンプリートと構文の色分けを使用して、素早くコーディングを完了できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1015">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="8e8f4-1016">関数、列、パラメーターも簡単に見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1016">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="8e8f4-1017">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1017">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="8e8f4-1018">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1018">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="8e8f4-1019">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1019">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="8e8f4-1020">Outlook</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1020">Outlook</span></span>

- <span data-ttu-id="8e8f4-1021">**メッセージの移動中も作業が可能:** Outlook では、メッセージの移動がバックグラウンドで行われるようになったため、フォルダー間で多数のメッセージの移動が行われている間も作業を続けることができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1021">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="8e8f4-1022">**連続する会議の合間に時間を組み込む:** 既定で 5 分から 10 分早く会議を終了するように設定することで、出席者に休憩時間や場所の移動時間を与えることができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1022">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="8e8f4-p206">**ミームが表示される:** テキストまたは静的イメージだけでは十分ではない場合、アニメーション GIF を使用して要点を示すことができます。[詳細情報](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p206">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="8e8f4-1025">**Outlook のユーザー エクスペリエンスを更新しました:** 以前にプレビューを行い近日公開予定とされていたシンプルなエクスペリエンスで、最も重要な作業に集中できるように設計されています。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1025">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="8e8f4-1026">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1026">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="8e8f4-1027">**ゆったりとしたレイアウト、まとまったレイアウト? 自由に決めましょう:** 狭いスペースでアイテム間の間隔を広くするか、レイアウトの間隔を狭くして表示量を増やすことができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1027">**Relaxed or tighter layout? You choose:** Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

- <span data-ttu-id="8e8f4-1028">**シンプルになったリボンでカスタマイズも可能:** 最もよく使うボタンが 1 行にまとめられ、使いやすくなりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1028">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="8e8f4-1029">簡単に従来のビューとシンプルなビューを切り替えたり、コマンドを固定または固定解除できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1029">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="8e8f4-1030">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1030">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="8e8f4-1031">**より簡単なアカウントの追加方法:** アカウント設定の改善により、2 要素認証を使用する Outlook.com と Gmail のアカウントの Outlook への追加が以前よりも簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1031">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="8e8f4-1032">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1032">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="8e8f4-1033">**お気に入りのアクションを選びましょう：** フラグや、削除機能を使いますか？</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1033">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="8e8f4-1034">アーカイブまたは既読に​​しますか?</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1034">How about Archive or Mark as Read?</span></span> <span data-ttu-id="8e8f4-1035">よく使うコマンドでクイック操作メニューをカスタマイズします。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1035">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="8e8f4-1036">**同期制限にさよならしましょう:** Outlook の改善によりフォルダーの制限が解消され、そのまま共有メールボックスが同期されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1036">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="8e8f4-1037">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1037">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="8e8f4-1038">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1038">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="8e8f4-1039">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1039">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="8e8f4-1040">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1040">PowerPoint</span></span>

- <span data-ttu-id="8e8f4-p212">**ユーザーへのテストやアンケート:** テストやアンケートをスライドに配置します。Office で応答が自動的に収集され、保存されます。[詳細情報](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p212">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="8e8f4-1044">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1044">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="8e8f4-1045">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1045">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="8e8f4-1046">**コンテンツのリーチを拡大する:** プレゼンテーションのアクセシビリティを高める必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1046">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="8e8f4-1047">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1047">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="8e8f4-1048">[校閲]>[アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1048">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="8e8f4-1049">**変更時に変更内容を保存する:** すべての更新が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1049">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="8e8f4-1050">**これまで以上に簡単にオンライン ビデオを挿入できるようになりました:** Vimeo または YouTube からビデオをスライドに挿入する場合は、</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1050">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide?</span></span> <span data-ttu-id="8e8f4-1051">ビデオ ページへのリンクがあれば簡単に行えます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1051">The video page link is all you need.</span></span> [<span data-ttu-id="8e8f4-1052">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1052">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="8e8f4-1053">**よりよい変形操作:** 図形に名前を付けると、変形するときにより細かく制御できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1053">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="8e8f4-1054">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1054">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="8e8f4-1055">**シームレスに切り替える:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用のアカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1055">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="8e8f4-1056">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1056">Switching between them has never been easier.</span></span> [<span data-ttu-id="8e8f4-1057">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1057">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="8e8f4-1058">**オンライン ビデオの新しい保存場所:** Microsoft Stream にビデオを保存すれば、組織内のすべてのユーザーが視聴できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1058">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="8e8f4-1059">ビデオのリンクを挿入すれば、小さなファイル サイズでマルチメディア プレゼンテーションをご利用いただけます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1059">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="8e8f4-1060">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1060">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="8e8f4-1061">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1061">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="8e8f4-1062">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1062">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="8e8f4-1063">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1063">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="8e8f4-1064">Project</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1064">Project</span></span>

- <span data-ttu-id="8e8f4-1065">**シームレスに切り替える:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用のアカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1065">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="8e8f4-1066">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1066">Switching between them has never been easier.</span></span> [<span data-ttu-id="8e8f4-1067">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1067">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="8e8f4-1068">Visio</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1068">Visio</span></span>

- <span data-ttu-id="8e8f4-p221">**壊れた Excel リンクの問題を解消:** データ ビジュアライザーの図にリンクされているはずの Excel ブックが見つかりませんか? 再リンクして、すぐに業務を再開できます。[詳細情報](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p221">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="8e8f4-p222">**Azure ステンシルが組み込まれている:** 多数の Azure ステンシルを使用してクラウド アプリの設計やアーキテクチャの計画を行うことができます。[詳細情報](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p222">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils. [Learn more](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)</span></span>

- <span data-ttu-id="8e8f4-1074">**はっとするようなデータ フローチャート:** データ ビジュアライザーのフローチャートの見事な新しいレイアウトがすっきり、はっきり、わかりやすくなりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1074">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="8e8f4-1075">オプションの [デザイン] タブをクリックします。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1075">Click the Design tab for options.</span></span>

- <span data-ttu-id="8e8f4-1076">**シームレスに切り替える:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用のアカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1076">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="8e8f4-1077">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1077">Switching between them has never been easier.</span></span> [<span data-ttu-id="8e8f4-1078">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1078">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="8e8f4-1079">**プロセス図を Word にエクスポート:** Word 文書に図形やメタデータなどのグラフ コンテンツを自動的に追加します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1079">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="8e8f4-1080">その後に、文書をカスタマイズしてプロセスに関するガイドラインや操作マニュアルを作成できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1080">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="8e8f4-1081">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1081">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="8e8f4-1082">**Power BI から Visio ビジュアルをエクスポートする:** Power BI レポートを PDF、PowerPoint などのファイルとしてエクスポートするときに、Power BI 用の Visio ビジュアルが正しく表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1082">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="8e8f4-1083">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1083">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="8e8f4-1084">Word</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1084">Word</span></span>

- <span data-ttu-id="8e8f4-p227">**インク エディターを使った自然な編集:** ペンを使って 1 ストローク描くだけで、単語の分割や結合、新しい線の追加、単語の挿入などができます。[詳細情報](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p227">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="8e8f4-p228">**静的なドキュメントから魅力的なドキュメントへの変換:** ドキュメントを、すべてのデバイスに対応する対話型の使いやすい Web ページに変換します。[詳細情報](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p228">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="8e8f4-1089">**\@メンションを使用してユーザーの注意を引く:** コメントで @メンションを使うと、他のユーザーによる入力が必要な場合にそのユーザーに知らせることができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1089">**Get Their Attention with \@Mentions:** Use @mentions in comments to let others know when you need their input.</span></span> [<span data-ttu-id="8e8f4-1090">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1090">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="8e8f4-p230">**行フォーカスによる読解力の向上:** ドキュメント内で行ごとの移動をスムーズに行います。一度に 1 行か、3 行か、5 行かを表示するようフォーカスを調整できます。[詳細情報](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p230">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="8e8f4-1094">**特定のファイルをすばやく見つける**: 最近作業を行ったファイルを探している場合は?</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1094">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="8e8f4-1095">[ファイル] > [ホーム ページ] タブの検索ボックスに入力するだけで、目的のファイルを見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1095">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="8e8f4-1096">**変更時に変更内容を保存する:** すべての更新が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1096">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="8e8f4-1097">**コンテンツのリーチを拡大する:** ドキュメントのアクセシビリティを高める必要がありますか?</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1097">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="8e8f4-1098">アクセシビリティ チェックを使用すると、アクセシビリティの問題を自動的に監視できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1098">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="8e8f4-1099">[校閲]>[アクセシビリティ チェック] をクリックすると、何か問題が見つかった場合に、ステータス バーに通知が表示されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1099">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="8e8f4-1100">**[学習ツール] モードで、ページで使用できる色が増えました:** Word の学習ツールでは、より多くのページ テーマ色が追加され、ページの背景色を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1100">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="8e8f4-1101">すべて白またはすべて黒の背景だと読みにくいと感じるユーザーは少なくないため、PC と Mac の Word で色の選択肢を拡大しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1101">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="8e8f4-1102">**シームレスに切り替える:** 新しいアカウント マネージャーでは、Office 365 の職場用と個人用のアカウントがすべて 1 か所に表示されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1102">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="8e8f4-1103">アカウント間の切り替えがより簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1103">Switching between them has never been easier.</span></span> [<span data-ttu-id="8e8f4-1104">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1104">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)


- <span data-ttu-id="8e8f4-1105">**検索して楽しむ:** 目的のアイコンが簡単に見つかるように、アイコンを挿入するための検索が追加されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1105">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="8e8f4-1106">選択しているときに、[挿入] ボタンではユーザーによって選択された数をお知らせします。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1106">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="8e8f4-1107">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1107">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="8e8f4-1108">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1108">Office Suite</span></span>

- <span data-ttu-id="8e8f4-1109">**Microsoft Teams のインストール**: Teams は、Office 365 ProPlus の既存のインストールに追加されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1109">**Installation of Microsoft Teams:** Teams is added to existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="8e8f4-1110">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1110">Learn more</span></span>](/deployoffice/teams-install)

- <span data-ttu-id="8e8f4-1111">**変更が発生したときに変更内容を自動的に保存する:** 変更が自動的に保存されるように、ファイルを OneDrive にアップロードしましょう。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1111">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="8e8f4-1112">**プライバシー制御**: 診断データとコネクテッド エクスペリエンス用に新しく更新されて、改善された制御。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1112">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="8e8f4-1113">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1113">Learn more</span></span>](/DeployOffice/privacy/overview-privacy-controls?toc=%2fdeployoffice%2ftoc.json)

- <span data-ttu-id="8e8f4-1114">**新しい外観を備えた Office のアイコン:** シンプルかつ高性能で、インテリジェントな Office のエクスペリエンスを反映するように、Office のアイコンがリニューアルされました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1114">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="8e8f4-1115">**Microsoft Teams のインストール:** Microsoft Teams は、Office 365 ProPlus の既存のインストールに既定でインストールされています。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1115">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="8e8f4-1116">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1116">Learn more</span></span>](/DeployOffice/teams-install)


[//]: # (FEATUREDETAILS コンテンツを削除しないでください。終了)

<br/>

[//]: # (BUGDETAILS コンテンツを削除しないでください。開始)

### <a name="non-security-updates"></a><span data-ttu-id="8e8f4-1119">セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1119">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="8e8f4-1120">Excel</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1120">Excel</span></span>

- <span data-ttu-id="8e8f4-1121">図形やフォーム コントロールに割り当てられているマクロが間違ったエラー メッセージとして表示される、または間違った対象範囲で動作する問題が Excel で修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1121">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="8e8f4-1122">ピボットテーブルの並べ替え方法を変更し、他のユーザーとの共同編集セッション中にエラーを発生させる可能性のある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1122">Fixed an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could cause it to fail.</span></span>

- <span data-ttu-id="8e8f4-1123">セルが挿入または削除されたときに、ウォーターフォール図とじょうごグラフがテーブルと同期しなくなる原因となっていた問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1123">Fixed an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="8e8f4-1124">Excel では、ユーザーが変更を取得するためにブックを再び開くよう要求される結果となるマージ競合の問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1124">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="8e8f4-1125">テーブルの横にある切り取りと貼り付けの操作を、他のユーザーと共同編集しているときに失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1125">Fixed an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

### <a name="outlook"></a><span data-ttu-id="8e8f4-1126">Outlook</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1126">Outlook</span></span>

- <span data-ttu-id="8e8f4-1127">メールボックスを基本認証から最新認証にアップグレードしたユーザーが、Outlook プロファイルに関連付けられた正しくないアカウントで終了する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1127">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="8e8f4-1128">設定に関係なく、POP3 ユーザーの一部がプレーンテキストで書式設定されたすべてのメールを表示する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1128">Fixed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="8e8f4-1129">この修正プログラムでは、HTML 形式のメッセージの表示が復元されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1129">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="8e8f4-1130">スクリーン リーダーからユーザーが保管場所の候補にアクセスできない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1130">Fixed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="8e8f4-1131">一部のユーザーが Outlook のクラウド設定を取得しようとすると、認証エラーが発生する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1131">Fixed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="8e8f4-1132">代理人が特定の会議出席依頼に既に返信したかどうかに関係なく、管理者が不明瞭になる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1132">Fixed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="8e8f4-1133">Outlook ユーザーが特定のシナリオで "パスワードを要求している" 状態で停止する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1133">Fixed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="8e8f4-1134">現在のフォルダー検索で断続的な失敗を引き起こす問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1134">Fixed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="8e8f4-1135">会議室の空き時間外に発生した会議のために会議室がユーザーに提案されるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1135">Fixed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="8e8f4-1136">ユーザーにエラー "このファイルが見つかりません" が表示される一時的なサービスに関する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1136">Fixed temporary service issue that caused users to see the error "Cannot find this file.</span></span> <span data-ttu-id="8e8f4-1137">クラウドの添付ファイルを使用している場合は、パスとファイル名が正しいことを確認します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1137">Verify the path and file name are correct" when using cloud attachments.</span></span> [<span data-ttu-id="8e8f4-1138">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1138">Learn More</span></span>](https://support.office.com/article/outlook-unable-to-attach-onedrive-or-sharepoint-files-to-emails-136951bb-60dc-478a-b916-6ee39e62c37a)

- <span data-ttu-id="8e8f4-1139">ユーザーに Outlook から OneDrive または Sharepoint にアップロードしたファイルが表示される問題が修正されました。ファイル名が変更され、複数の文字が下線で置き換えられました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1139">Fixed an issue that caused users to see uploaded files from Outlook to OneDrive or Sharepoint have the file name changed where several characters replaced by underscores.</span></span>

- <span data-ttu-id="8e8f4-1140">メールの件名が非常に小さくなる英語以外の言語を使用するユーザーの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1140">Fixed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="8e8f4-1141">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1141">PowerPoint</span></span>

- <span data-ttu-id="8e8f4-1142">一部のアドインがグラフの図形に対して予期しないエラーをスローさせる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1142">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="8e8f4-1143">PowerPoint ビデオ コントロールのアクセシビリティの高い名前を復元する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1143">Fixed an issue to restore the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="8e8f4-1144">一部のアニメーションが開始されないことがある問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1144">Fixed an issue which could prevent some animations from starting</span></span>

### <a name="project"></a><span data-ttu-id="8e8f4-1145">Project</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1145">Project</span></span>

- <span data-ttu-id="8e8f4-1146">Windows 7 のユーザーが Project Web App および SharePoint サイトからプロジェクトを開くことができるように問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1146">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>


### <a name="visio"></a><span data-ttu-id="8e8f4-1147">Visio</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1147">Visio</span></span>

- <span data-ttu-id="8e8f4-1148">Visio から SVG へのエクスポートは、さまざまな図形に対しては機能しませんでした。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1148">Export to SVG from Visio was not working for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="8e8f4-1149">Word</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1149">Word</span></span>

- <span data-ttu-id="8e8f4-1150">ユーザーが Word ドキュメントで他のユーザーと共同作業しているときに、エラー メッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1150">Fixed an issue where users would get error messages while collaborating with others on a Word document.</span></span>

- <span data-ttu-id="8e8f4-1151">SharePoint 2016 に保存されているファイルを共有しようとすると、"申し訳ございません。何かがこのファイルの共有を妨げています。" というメッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1151">Fixed an issue which caused users to get the message "Sorry, something is preventing us from sharing this"  when trying to share files stored on SharePoint 2016.</span></span>


### <a name="office-suite"></a><span data-ttu-id="8e8f4-1152">Office スイート</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1152">Office Suite</span></span>

- <span data-ttu-id="8e8f4-1153">同期エンジンでバックアップされた sharepoint ファイルに '保存済み' と表示されますが、場合によっては実際に変更が保存されない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1153">Fixed an issue where in some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes.</span></span>

- <span data-ttu-id="8e8f4-1154">大きなツリー ビューにエラーが発生していた問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1154">Fixed an issue where large tree views were failing.</span></span>

- <span data-ttu-id="8e8f4-1155">新元号の「Reiwa」のひらがなと漢字をスペルミスまたは間違った文法として誤って識別していた問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1155">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>


[//]: # (BUGDETAILS コンテンツを削除しないでください。終了)

## <a name="version-1902-august-13"></a><span data-ttu-id="8e8f4-1157">バージョン 1902: 8 月 13 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1157">Version 1902: August 13</span></span>
<span data-ttu-id="8e8f4-1158">*バージョン 1902 (ビルド 11328.20392)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1158">*Version 1902 (Build 11328.20392)*</span></span>

<span data-ttu-id="8e8f4-1159">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1159">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="8e8f4-1160">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1160">Excel: Non-security updates</span></span>
- <span data-ttu-id="8e8f4-1161">テーブルのフィルター処理ありのスライサーとフィルター処理なしのスライサーの両方に、[フィルターのクリア] アイコンが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1161">Fixed an issue where the clear filter icon was shown for both filtered and unfiltered Slicers in tables.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="8e8f4-1162">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1162">Outlook: Non-security updates</span></span>
- <span data-ttu-id="8e8f4-1163">ユーザーがメールボックスを基本認証から最新認証にアップグレードすると、関連付けられた正しくないアカウントで終了する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1163">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="8e8f4-1164">PowerPoint: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1164">PowerPoint: Non-security updates</span></span>
- <span data-ttu-id="8e8f4-1165">他のユーザーとドキュメントの共同作業を行っている間に、アプリケーションが予期せず終了する可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1165">Fixed an issue where the application could unexpectedly terminate while collaborating on a document with other users.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="8e8f4-1166">Word: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1166">Word: Non-security updates</span></span>
- <span data-ttu-id="8e8f4-1167">VBA のフィールド更新が遅い問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1167">Fixed an issue which VBA updating fields were slow.</span></span>
- <span data-ttu-id="8e8f4-1168">一部の DOC ファイルを開くと、破損していると表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1168">Fixed in issue when opening some DOC file, it says it is corrupt.</span></span>
- <span data-ttu-id="8e8f4-1169">他のユーザーとドキュメントの共同作業を行っている間に、アプリケーションが予期せず終了することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1169">Fixed an issue where the application could unexpectedly terminate while collaborating on a document with other users.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="8e8f4-1170">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1170">Office Suite: Non-security updates</span></span>
- <span data-ttu-id="8e8f4-1171">特定のシナリオで Office JavaScript ライブラリ の Setting API が機能しなくなる問題を修正しました ([詳細情報](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551))</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1171">Fixed an issue in which Setting API doesn't work in the Office JavaScript library in certain scenarios [Learn More](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)</span></span>

## <a name="version-1902-july-09"></a><span data-ttu-id="8e8f4-1172">バージョン 1902: 7 月 9 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1172">Version 1902: July 09</span></span>
<span data-ttu-id="8e8f4-1173">*バージョン 1902 (ビルド 11328.20368)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1173">*Version 1902 (Build 11328.20368)*</span></span>

<span data-ttu-id="8e8f4-1174">セキュリティ更新プログラムの一覧は[こちら](./microsoft365-apps-security-updates.md)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1174">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


### <a name="excel-non-security-updates"></a><span data-ttu-id="8e8f4-1175">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1175">Excel: Non-security updates</span></span>
- <span data-ttu-id="8e8f4-1176">フィルター処理された Excel 行を削除するときの動作が極端に遅くなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1176">Fixed extreme slowness Issue in deleting filtered excel rows.</span></span>
- <span data-ttu-id="8e8f4-1177">2 本の指でスクロールするとワークシート上にグレーの四角形が描かれて Excel がハングアップするという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1177">Fixed two finger scrolling causes grey rectangles to be drawn over worksheet and Excel to hang.</span></span>


### <a name="outlook-non-security-updates"></a><span data-ttu-id="8e8f4-1178">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1178">Outlook: Non-security updates</span></span>
- <span data-ttu-id="8e8f4-1179">Outlook で、中国語の単語を選ぶ IME 候補ウィンドウが開いたままになる代わりに、英語の PinYin 文字が挿入される場合があるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1179">Addresses an issue that caused users to occasionally see Outlook inserting English pinyin letters rather than keeping the IME candidate window open to allow the selection of Chinese words.</span></span>
- <span data-ttu-id="8e8f4-1180">会議室の空き時間外にスケジュールされた会議のためにその会議室がユーザーに提案されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1180">Addresses an issue that caused users to see rooms being suggested for meetings that were scheduled outside of that room's availability.</span></span>
- <span data-ttu-id="8e8f4-1181">会議シリーズの例外を開こうとしたときに代わりにマスター シリーズが開くという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1181">Addresses an issue that caused users attempting to open an exception to a meeting series to instead open the master series.</span></span>
- <span data-ttu-id="8e8f4-1182">[削除済みアイテム] フォルダー内のアイテムの有効期限日が誤って計算されて表示されるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1182">Addresses an issue that caused users to see expiry dates being calculated incorrectly for items in Deleted Items folder.</span></span>


### <a name="teams-non-security-updates"></a><span data-ttu-id="8e8f4-1183">Teams: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1183">Teams: Non-security updates</span></span>

- <span data-ttu-id="8e8f4-1184">Teams インストーラーで、インストール完了後の自動起動をオフにするポリシーが使用可能になりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1184">Teams installer has now available Policy to turn off auto-launch after installation is completed.</span></span>


### <a name="visio-non-security-updates"></a><span data-ttu-id="8e8f4-1185">Visio: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1185">Visio: Non-security updates</span></span>

- <span data-ttu-id="8e8f4-1186">Visio 用の ActiveX ソリューションが Office 365 と連動しないことに関連する問題に対処します。この問題は、「riched20.dll が見つからない」というエラー メッセージとして出現します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1186">Addresses issue related to ActiveX solutions for Visio not working with Office 365, expressed as an error message stating that riched20.dll can't be found.</span></span>


### <a name="word--non-security-updates"></a><span data-ttu-id="8e8f4-1187">Word: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1187">Word:  Non-security updates</span></span>

- <span data-ttu-id="8e8f4-1188">テンプレート検索バーを無効にする GPO 設定を修正しました</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1188">Fixed GPO setting to disable template search bar</span></span>
- <span data-ttu-id="8e8f4-1189">オフラインになった後、サーバーのみのドキュメントをユーザーが編集すると変更内容の一部が失われることがあるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1189">Fixed an issue where users could lose some of their changes after being offline and editing a document that was server-only.</span></span>
- <span data-ttu-id="8e8f4-1190">文書のクイックパーツ プロパティを有効にしたときのパフォーマンスが向上しました</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1190">Improved performance when enabling Quick Parts for Document properties</span></span>
- <span data-ttu-id="8e8f4-1191">サーバーからの初回ダウンロード リビジョンが失敗する場合があるという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1191">Fixed an issue where first download revision from the server might fail</span></span>


### <a name="office-suite--non-security-updates"></a><span data-ttu-id="8e8f4-1192">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1192">Office Suite:  Non-security updates</span></span>

- <span data-ttu-id="8e8f4-1193">追加の Office 製品や言語パックをインストールすると、共有コンピューターのライセンス認証を使用しているデバイスが、予期せずユーザーベースのライセンス認証に戻ることがあるという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1193">Addressed an issue where devices using shared computer activation may unexpectedly revert to user-based activation upon installation of additional Office products or language packs.</span></span>
- <span data-ttu-id="8e8f4-1194">プロキシ認証がシステムとして実行されたときに Office の更新プログラムがブロックされるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1194">Fixed an issue that blocked Office Updates when proxy authentication runs as SYSTEM.</span></span>
- <span data-ttu-id="8e8f4-1195">ユーザー プロファイルの変更によって Office アドインが表示されなくなる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1195">Fixes to address Office add-ins disappearing on user profile changes.</span></span>


## <a name="version-1902-june-11"></a><span data-ttu-id="8e8f4-1196">バージョン 1902: 6 月 11 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1196">Version 1902: June 11</span></span>
<span data-ttu-id="8e8f4-1197">*バージョン 1902 (ビルド 11328.20318)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1197">*Version 1902 (Build 11328.20318)*</span></span>
<br/><span data-ttu-id="8e8f4-1198">[こちら](./microsoft365-apps-security-updates.md)にセキュリティ更新プログラムが記載されています</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1198">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="8e8f4-1199">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1199">Excel: Non-security updates</span></span>
 - <span data-ttu-id="8e8f4-1200">PDF にマッピングする XML を含むファイルを保存するときにクラッシュの原因となっていた問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1200">Resolved an issue that caused a crash when saving a file containing an XML map to PDF.</span></span>
 - <span data-ttu-id="8e8f4-1201">無効なシート名を含むブックを読み込むときに外部リンクが削除される原因となっていた問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1201">Resolved an issue that caused external links to be removed when workbooks containing invalid sheet names are loaded.</span></span>
 - <span data-ttu-id="8e8f4-1202">Excel でカメラ ツールを使用するとスプレッドシートが終了する原因となっていた問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1202">Fixed an issue where using the Camera tool in Excel could cause the spreadsheet to hang.</span></span>
 - <span data-ttu-id="8e8f4-1203">セルが挿入または削除されたときに、ウォーターフォール図とじょうごグラフがテーブルと同期しなくなる原因となっていた問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1203">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>
 - <span data-ttu-id="8e8f4-1204">テーブルに依存する別のシートで配列計算を用いて Worksheet Calculate を動作させている間に、データ テーブルが再計算されるとクラッシュする問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1204">Resolved a crash when a data table is recalculated during Worksheet Calculate with an array formula on another sheet depending on the table.</span></span> 
 - <span data-ttu-id="8e8f4-1205">最初にファイルをチェックアウトしないと、パスワードで保護されたブックを SharePoint から開けなかった問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1205">Resolved an issue that prevented password protected workbooks from being opened from SharePoint without checking out file first.</span></span>
 - <span data-ttu-id="8e8f4-1206">自動保存の共有または切り替えが行われているときに BeforeSave イベントの処理を確保する変更が行われました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1206">A change was made to ensure the BeforeSave event is handled when sharing or toggling AutoSave.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="8e8f4-1207">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1207">Outlook: Non-security updates</span></span>
 - <span data-ttu-id="8e8f4-1208">"Group by" に 2 番目の条件を追加するとお客様に表示するタスクが表示されなくなる原因となっていた問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1208">Addressed an issue that caused customers to see their tasks seem to disappear when adding a 2nd condition to "Group by".</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="8e8f4-1209">Word: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1209">Word: Non-security updates</span></span>
 - <span data-ttu-id="8e8f4-1210">.asd 拡張子が含まれる添付ファイルを生成するドキュメントとして現在共同作成しているドキュメントの共有を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1210">Fixed when sharing a document which is currently being collaborated upon the document produces attachment with .asd extension.</span></span>
 - <span data-ttu-id="8e8f4-1211">ランダムな作成者に起因したコメントに関する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1211">Fixed an issue with comments get attributed to random authors.</span></span>
 - <span data-ttu-id="8e8f4-1212">ドキュメントをチェックアウトするときに発生する署名の削除の問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1212">Fixed an issue in the remove signature when checking out a document.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="8e8f4-1213">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1213">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="8e8f4-1214">"元に戻す" 操作の後に VBA が不正確な図形の塗り潰しのステータスを報告する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1214">This fixed a bug in VBA reporting incorrect shape fill state after an "undo" action.</span></span>


## <a name="version-1902-may-14"></a><span data-ttu-id="8e8f4-1215">バージョン 1902: 5 月 14 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1215">Version 1902: May 14</span></span>
<span data-ttu-id="8e8f4-1216">*バージョン 1902 (ビルド 11328.20286)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1216">*Version 1902 (Build 11328.20286)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="8e8f4-1217">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1217">Excel: Non-security updates</span></span>
 -  <span data-ttu-id="8e8f4-1218">Excel でカメラ ツールを使用するとスプレッドシートが終了する原因となっていた問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1218">Fixed an issue where using the Camera tool in Excel could cause the spreadsheet to hang.</span></span>
 - <span data-ttu-id="8e8f4-1219">グラフ シートのある非アクティブ ウィンドウでマウス スクロール ホイールを使用するとクラッシュする問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1219">An issue that caused a crash when using the mouse scroll wheel on an in-active window with a chart sheet was fixed.</span></span>
 - <span data-ttu-id="8e8f4-1220">SharePoint でスプレッドシートをインポートするときに「予期しないエラー」メッセージが表示される問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1220">A problem that caused an "Unexpected Error" message to appear when importing a spreadsheet in SharePoint has been resolved.</span></span>
 - <span data-ttu-id="8e8f4-1221">ルールの名前を使用する条件付き書式を含むブックを開くときに、Excel がクラッシュし、ユーザー設定のビューが適用される問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1221">A problem that caused Excel to crash when opening a workbook containing conditional formatting that uses a Name for its rule and a custom view is applied has been resolved.</span></span>
 - <span data-ttu-id="8e8f4-p241">255 文字より長い数式でマクロがデータの入力規則を使用すると、実行時エラーが発生する場合があります。この問題は修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p241">Macros using data validation with formulas longer than 255 characters may have produced run-time errors. This issue has now been corrected.</span></span>
 - <span data-ttu-id="8e8f4-p242">他のブックにリンクされているピボットテーブルを含むファイルの読み込み速度が低下する問題。この問題は解決されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p242">A problem which caused files containing PivotTables linked to other workbooks to load slowly. This issue has been resolved.</span></span>
 - <span data-ttu-id="8e8f4-1226">HTML ファイルを開くと「ファイル形式と拡張子が一致しない」というエラーが発生する問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1226">An issue with opening HTML files and receiving a "file format and extension do not match" error has been resolved.</span></span>
 - <span data-ttu-id="8e8f4-1227">非アクティブのウィンドウでのマウス ホイール スクロールによる問題を解決するために変更が行われました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1227">A change has been made to resolve issues with mouse-wheel scrolling on inactive windows.</span></span>  

### <a name="outlook-non-security-updates"></a><span data-ttu-id="8e8f4-1228">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1228">Outlook: Non-security updates</span></span>
 - <span data-ttu-id="8e8f4-1229">移行されたアイテムの一部のフィールドをお客様が編集できなくなる問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1229">Addresses an issue that caused customers to be unable to edit some fields on items that had been migrated.</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="8e8f4-1230">PowerPoint: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1230">PowerPoint: Non-Security updates</span></span>
- <span data-ttu-id="8e8f4-1231">PowerPoint がクラウドへのユーザー変更のアップロードを停止することがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1231">Fixed an issue that PowerPoint stops uploading user changes to the cloud in rare situations.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="8e8f4-1232">Skype for Business: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1232">Skype for Business: Non-security updates</span></span>
 - <span data-ttu-id="8e8f4-1233">Lync (Skype for Business) で、参加者が 7 人以上のオンライン ミーティングのミーティング ウィンドウが表示されないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1233">Fixed an issue in Lync (Skype for Business) where for any online meeting with more 7+ participants, the meeting window can disappear.</span></span>
 - <span data-ttu-id="8e8f4-1234">別の Office アプリケーションにサインインするために使用された資格情報で Skype for Business にサインインします。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1234">Sign into Skype for Business with credentials used to sign into another Office application.</span></span>
 - <span data-ttu-id="8e8f4-1235">共有コンピューターのライセンス認証でインストールした場合は、Skype for Business アプリを正しくライセンス認証します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1235">Properly activate the Skype for Business app when installed with shared computer activation.</span></span>

### <a name="visio-non-security-updates"></a><span data-ttu-id="8e8f4-1236">Visio: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1236">Visio: Non-security updates</span></span>
 - <span data-ttu-id="8e8f4-1237">動的 DPI 機能を無効にして Visio を拡張するサードパーティ ソリューションで、ウィンドウ階層が壊れる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1237">Fixed an issue which was causing broken window hierarchy issues for 3rd party solutions extending Visio by disabling Dynamic DPI feature.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="8e8f4-1238">Word: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1238">Word: Non-Security updates</span></span>
 - <span data-ttu-id="8e8f4-1239">SharePoint によって追加された関係者を編集する際にクラッシュする場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1239">Fixed an issue where editing a Related Person added by SharePoint could crash.</span></span>
 - <span data-ttu-id="8e8f4-1240">Word の起動時に [リソースを読み込めませんでした] ダイアログが表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1240">Fixed where the "Failed to load resource" dialog when Word launches.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="8e8f4-1241">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1241">Office Suite: Non-security updates</span></span>
 - <span data-ttu-id="8e8f4-1242">これは、ファイルを Apache WebDAV フォルダーに保存できない問題の修正プログラムです。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1242">This is a fix for an issue where files cannot be saved to Apache WebDAV folders.</span></span>
 - <span data-ttu-id="8e8f4-1243">ユーザーがクラウドに保存したファイルを開くと、Office が突然終了する問題の修正です。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1243">Fixes an issue where Office closes abruptly when customers open some cloud-stored files.</span></span>
 - <span data-ttu-id="8e8f4-1244">新時代の名前である「Reiwa」のひらがなと漢字をスペルミスまたは間違った文法として誤って識別していた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1244">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>
 - <span data-ttu-id="8e8f4-1245">Windows 10 の多くのユーザーに対して最近のファイル リストがクリアされているように見えた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1245">Fixed an issue where the recent files list appeared to have been cleared for many users on Windows 10.</span></span>
 - <span data-ttu-id="8e8f4-1246">管理者による更新が進行中であっても、エンドユーザーに Office Update のビジネス バーが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1246">Fixed an issue that caused an end-user to see an Office Update business bar, even though there is an Admin-triggered update in progress.</span></span>
 - <span data-ttu-id="8e8f4-1247">断続的な空白のサインインプロンプトに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1247">Fixed an issues related to intermittent blank sign-in prompts.</span></span>
 

## <a name="version-1902-april-9"></a><span data-ttu-id="8e8f4-1248">バージョン 1902:4月9日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1248">Version 1902: April 9</span></span>
<span data-ttu-id="8e8f4-1249">*バージョン 1902 (ビルド 11328.20230)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1249">*Version 1902 (Build 11328.20230)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="8e8f4-1250">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1250">Excel: Non-Security updates</span></span>

- <span data-ttu-id="8e8f4-1251">定義された名前で終わる数式が含まれるセルにいる場合、Tab キーを押しても次のセルに移動できないという問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1251">Resolved an issue where pressing the Tab key would not move to the next cell when in a cell containing a formula ending in a defined name.</span></span>
- <span data-ttu-id="8e8f4-1252">セルの書式設定が原因でファイルのサイズが必要以上に大きくなるという問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1252">Resolved an issue where cell formatting was causing the file size to grow unnecessarily.</span></span>
- <span data-ttu-id="8e8f4-1253">ブック間でピボットテーブルをカット アンド ペーストすると、共同作業している他のユーザーのピボットテーブルを含まずにデータが貼り付けられるという問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1253">Resolved an issue where cutting and pasting a PivotTable between workbooks may result in the data being pasted, without a PivotTable for others you are collaborating with.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="8e8f4-1254">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1254">Outlook: Non-Security updates</span></span>

- <span data-ttu-id="8e8f4-1255">システムタスクバーを画面の左または上に置いたときにウィンドウが正しい場所に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1255">Fixed an issue in which windows would not appear in the correct location when the system task bar was kept at the left or top of the screen.</span></span>
- <span data-ttu-id="8e8f4-1256">顧客の連絡先カード上の画像の読み込み中にクラッシュが発生する原因となった問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1256">Addresses an issue that caused customers to experience a crash when loading pictures on the contact card.</span></span>
- <span data-ttu-id="8e8f4-1257">一部の顧客がOffice アプリケーションの起動時にクラッシュするという問題に対処します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1257">Addresses an issue that caused some customers to experience crashes when starting office applications.</span></span>
- <span data-ttu-id="8e8f4-1258">システムタスクバーを画面の左または上に置いたときにウィンドウが正しい場所に表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1258">Fixed an issue in which windows would not appear in the correct location when the system task bar was kept at the left or top of the screen.</span></span>
- <span data-ttu-id="8e8f4-1259">移行されたアイテムの一部のフィールドを顧客が編集できない問題が解決されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1259">Addresses an issue that caused customers to be unable to edit some fields on items that had been migrated.</span></span>

### <a name="visio-non-security-updates"></a><span data-ttu-id="8e8f4-1260">Visio: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1260">Visio: Non-Security updates</span></span>

- <span data-ttu-id="8e8f4-1261">動的 DPI 機能を無効して Visio を拡張するサードパーティ ソリューションで、ウィンドウ階層が壊れる原因となっていた問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1261">Fixed an issue which was causing broken window hierarchy issues for 3rd party solutions extending Visio by disabling the Dynamic DPI feature.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="8e8f4-1262">Word: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1262">Word: Non-Security updates</span></span>

- <span data-ttu-id="8e8f4-1263">ファイルが読み取り専用モードで開かれているときに[情報]枠から[名前を付けて保存]をクリックすると、保存UIが表示されるように問題が修正されています。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1263">If a file is opened in read-only mode and you click 'Save As' from the 'Info' pane, fixes issue so that the save UI is displayed.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="8e8f4-1264">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1264">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="8e8f4-1265">Office の更新プログラムの一部で配信の最適化のピア キャッシュを使用しないという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1265">Fixed an issue where parts of an Office update do not use Delivery Optimization peer caching.</span></span> [<span data-ttu-id="8e8f4-1266">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1266">Learn more</span></span>](/windows/deployment/update/waas-delivery-optimization)
- <span data-ttu-id="8e8f4-1267">Office が Office 展開ツールを使用してインストールされ、大文字/小文字が一致しない場合、製品が削除されたり、アクティブ化されなかったりする可能性があるバグが修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1267">Fix to a bug that could lead to products being removed or not activated if Office was installed using the Office Deployment Tool and there was a case mis-match.</span></span>
- <span data-ttu-id="8e8f4-1268">Windows 10（バージョン1803以降）のデバイスで過剰なサインインプロンプトを引き起こしていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1268">Fixed an issue which was causing excessive sign-in prompts on Windows 10 (version 1803 or later) devices.</span></span>
- <span data-ttu-id="8e8f4-1269">リンクされた写真をダウンロードするときにハングする原因となる退行を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1269">Fixed regression that causes hangs when downloading linked pictures.</span></span>
- <span data-ttu-id="8e8f4-1270">Word、Excel、PowerPointに貼り付けられた大きなEMFファイルのぼやけを修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1270">Fixed blurriness of large EMF files pasted in Word, Excel, PowerPoint.</span></span>
- <span data-ttu-id="8e8f4-1271">バージョン履歴の解析ロジックで、ドキュメントが読み取り専用で開かれることがあったケースを修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1271">Fixed the bug in version history parsing logic that in few cases caused the documents to be opened in read-only.</span></span>

## <a name="version-1902-march-12"></a><span data-ttu-id="8e8f4-1272">バージョン 1902: 3 月 12 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1272">Version 1902: March 12</span></span>
<span data-ttu-id="8e8f4-1273">*バージョン 1902 (ビルド 11328.20158)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1273">*Version 1902 (Build 11328.20158)*</span></span>

### <a name="access-feature-updates"></a><span data-ttu-id="8e8f4-1274">Access: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1274">Access: Feature updates</span></span>

- <span data-ttu-id="8e8f4-p244">**リンク テーブルを更新、再リンク、または削除する:** 更新されたリンク テーブル マネージャーで、すべてのデータ ソースとリンク テーブルを管理できます。[詳細情報](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p244">**Refresh, relink, or remove linked tables:** The updated Linked Table Manager is the location for managing all data sources and linked tables. [Learn more](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)</span></span>
- <span data-ttu-id="8e8f4-p245">**黒にペイントする、灰色にペイントする:** アクセスの外観を好きなだけ変更します。次の 4 つのテーマを選択: カラフル、濃い灰色、黒、白のいずれか。[詳細情報](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p245">**Paint it black, paint it gray:** Change the look of Access as often as you like. Four themes to choose from: Colorful, Dark Gray, Black, or White. [Learn more](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)</span></span>
- <span data-ttu-id="8e8f4-1280">**Office の外観が新しくなる:** Office アプリに、よりシンプルでアクセスしやすい最新のアイコンが加わり、リボンの外観が、Office アプリで使用可能な豊富なコラボレーション機能を強調するように更新されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1280">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="8e8f4-1281">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1281">Excel: Feature updates</span></span>

- <span data-ttu-id="8e8f4-1282">**すばやく始めましょう** 新しくデザインされたスタートページは、最近開いたドキュメントを前面と中央に配置します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1282">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="8e8f4-1283">以前より少ないクリック数でファイルにアクセスし、そこからすぐアカウント設定またはオプションを開きます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1283">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="8e8f4-p247">**コメントを利用して共同作業を行う:** 返信ボックスが組み込まれているので、スプレッドシートで直接会話を続けることができます。[詳細情報](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p247">**Collaborate with comments:** Keep the conversation going right in your spreadsheet with the built-in reply box. [Learn more](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)</span></span>
- <span data-ttu-id="8e8f4-p248">**新しい見た目のリボン アイコン:** 機能に変化はないので、心配はいりません。さらに、どのサイズの画面でも、見た目がきれいです。[詳細情報](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p248">**Your ribbon icons have a new look:** Don’t worry, everything works the same. Plus, they look great on screens of all sizes. [Learn more](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span></span>
- <span data-ttu-id="8e8f4-1289">**フィルターが適用された SVG を挿入する機能:** Office ユーザーは、フィルターが適用された SVG を挿入できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1289">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them.</span></span> [<span data-ttu-id="8e8f4-1290">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1290">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- <span data-ttu-id="8e8f4-p250">**画像の背後を見えるようにする:** ワークシートに画像を挿入し、既定の設定から選択して、透明度の変化を確認するだけです。[詳細情報](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p250">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="8e8f4-p251">**データの取得と変換をご利用の皆様:** データの取得と変換をよく利用していただいているユーザーの皆様に、例からの列の機能が改善されたことをお知らせします。また、多くのコネクタも強化されました。[詳細情報](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p251">**Calling all Get & Transform fans:** If you use Get & Transform a lot, you'll be happy to know that the Column From Example feature has been improved. And, many connectors have been improved as well. [Learn more](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)</span></span>
- <span data-ttu-id="8e8f4-p252">**改善された高解像度ディスプレイのサポート**: 複数のモニター、またはドッキングでラップトップを使用する場合、各ディスプレイの倍率設定が異なっていても Office アプリがすべてのディスプレイで鮮明に表示されるようになります。 [詳細情報](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p252">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings. [Learn more](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span></span>
- <span data-ttu-id="8e8f4-p253">**迅速な検索:** VLOOKUP、HLOOKUP、MATCH 計算が強化され、解答をすばやく取得できるようになりました。[詳細情報](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p253">**Speedy Lookup** We've turbo-charged your VLOOKUP, HLOOKUP, and MATCH calculations so you can get answers faster. [Learn more](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="8e8f4-1301">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1301">Outlook: Feature updates</span></span>

- <span data-ttu-id="8e8f4-1302">**音声読み上げを使用してメールの内容を聞く:** Outlook では、メールのテキストを読み上げながら強調表示することができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1302">**Use Read Aloud to listen to your email:** Outlook can read your email aloud, highlighting text as it's read.</span></span> <span data-ttu-id="8e8f4-1303">読み上げ機能をオンにするには、[簡単操作] の設定に移動します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1303">To turn on Read Aloud, go to the Ease of Access settings.</span></span> [<span data-ttu-id="8e8f4-1304">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1304">Learn more</span></span>](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)
- <span data-ttu-id="8e8f4-1305">**ハンズフリーで入力:** マイクは用意しましたか。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1305">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="8e8f4-1306">[ディクテーション] をクリックして、発話すると Outlook によって入力されるのを確認してください。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1306">Click Dictate and watch Outlook type while you talk.</span></span> [<span data-ttu-id="8e8f4-1307">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1307">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="8e8f4-p256">**新しい見た目のリボン アイコン:** 機能に変化はないので、心配はいりません。さらに、どのサイズの画面でも、見た目がきれいです。[詳細情報](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p256">**Your ribbon icons have a new look:** Don’t worry, everything works the same. Plus, they look great on screens of all sizes. [Learn more](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span></span>
- <span data-ttu-id="8e8f4-p257">**SMIME の暗号化および署名されたメールでは、既定で外部コンテンツのダウンロードをブロック:** SMIME プロトコルに脆弱性があるため、Outlook が SMIME の暗号化または署名されたメッセージへの外部コンテンツのダウンロードをブロックします。セキュリティ上の脆弱性保護の観点から、ユーザーは Outlook UI において外部コンテンツをワンクリックでダウンロードすることはできません。[オプション] ダイアログには、ユーザーが以前の動作に戻すことができる新しいオプションが用意されています。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p257">**Block download of external content by default in SMIME encrypted and signed emails:** Due to a vulnerability in the SMIME protocol - Outlook will block download of external content on messages that have been encrypted or signed over SMIME. Users will not be able to single-click download external content through Outlook UI to protect from the security vulnerability. There is a new option in the Options dialog to allow for users to revert to old behavior.</span></span>
- <span data-ttu-id="8e8f4-p258">**会議の転送を無効にする:** 出席者が会議を他のユーザーに転送できないようにします。リボンに移動して、[応答オプション] をクリックするだけです。[詳細情報](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p258">**Turn off forwarding for a meeting:** Prevent attendees from forwarding your meeting to others. Just go to the ribbon and click Response Options. [Learn more](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)</span></span>
- <span data-ttu-id="8e8f4-p259">**スケジュール アシスタントでの候補ユーザーの表示:** 会議のスケジュールを設定するときに、追加する出席者の候補が表示されます。スケジュール アシスタントと [宛先] 行を何度も切り替える必要はありません。[詳細情報](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p259">**People suggestions in the Scheduling Assistant:** See recommendations for attendees to add when you schedule a meeting. No more switching back and forth between the Scheduling Assistant and the To line. [Learn more](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)</span></span>
- <span data-ttu-id="8e8f4-1320">**会議室の予約がさらに簡単に:** 複数の会議室のリストを使用して、会議室を検索します。選択した会議室を失うことなく、リストを切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1320">**Reserving a room just got easier:** Look for a conference room using more than one room list - and switch lists without losing rooms you've selected.</span></span>
- <span data-ttu-id="8e8f4-1321">**期間の新しい既定値:** [定期的なアイテム] ダイアログでは、期間に [終了日未定] の既定値が使われていました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1321">**New default for range of recurrence:** For the Recurrence dialog, the range of recurrence used to default for "No end date".</span></span> <span data-ttu-id="8e8f4-1322">これにより、長期間実行される定期的なアイテムが作成され、時間と共に破損する可能性がありました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1322">This facilitated the creation of long-running recurring series, which can become corrupted over time.</span></span> <span data-ttu-id="8e8f4-1323">既定値が予定表作成の推奨されるベスト プラクティスに一致するように、[定期的なアイテム] ダイアログ ボックスの既定値を [終了日] に更新します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1323">We are updating the default for the Recurrence dialog to "End by", such that our default value matches recommended best practices for calendaring.</span></span>
- <span data-ttu-id="8e8f4-p261">**Outlook のアラーム ダイアログから Teams 会議に参加する:** Outlook が今後の会議についてユーザーに通知する際、会議が Teams のオンライン会議の場合には、[オンラインで参加] ボタンが表示されます。これは、Outlook のアラート ダイアログから Skype for Business 会議に参加する場合に似ています。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p261">**Join Teams meetings from the Outlook Reminders dialog:** When Outlook reminds users of an upcoming meeting, it will show a Join Online button if the upcoming meeting is a Teams online meeting. This is similar to the experience of joining a Skype for Business meeting from the Outlook Reminders dialog.</span></span>
- <span data-ttu-id="8e8f4-p262">**過去のイベントのリマインダーの表示を停止:** 終了したイベントのリマインダーを自動的に破棄するようにカレンダーを設定することができます。[詳細情報](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p262">**Stop seeing reminders for past events:** You can set your calendar to automatically dismiss reminders for events after they've ended. [Learn more](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)</span></span>
- <span data-ttu-id="8e8f4-1328">**安全なリンクの背後にある URL を表示する:** 安全なリンクは、メールで受け取った悪意のある URL からユーザーを保護しますが、元の URL は非表示になります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1328">**See the URL behind Safe Links:** Safe Links protects you from malicious URLS received in email but they hide the original URL.</span></span> <span data-ttu-id="8e8f4-1329">元の URL を確認するには、URL をマウスでポイントします。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1329">To see the original, hover your mouse over the URL.</span></span> <span data-ttu-id="8e8f4-1330">Advanced Threat Protection のライセンスが必要です。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1330">Requires an Advanced Threat Protection license.</span></span> [<span data-ttu-id="8e8f4-1331">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1331">Learn more</span></span>](https://products.office.com/exchange/advance-threat-protection)
- <span data-ttu-id="8e8f4-p264">**ズームとスティック:** メッセージを読むたびにズームを調整するのではなく、すべてのメッセージに使用する既定値を選択します。[詳細情報](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p264">**Zoom and stick:** Instead of adjusting Zoom each time you read a message, choose a default to use for all your messages. [Learn more](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)</span></span>
- <span data-ttu-id="8e8f4-1334">**メッセージ暗号化: 暗号化のみ IRM ポリシー:** 新しい暗号化のみオプションは、Office 365 Message Encryption ユーザーの [オプション] > [アクセス許可] に表示されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1334">**Message Encryption: encrypt-only IRM policy:** New encrypt-only option appears in the Options > Permissions menu for Office 365 Message Encryption users.</span></span> <span data-ttu-id="8e8f4-1335">このオプションを使用すると、メッセージを暗号化して、組織の内外のユーザーに送信できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1335">This option allows you to encrypt a message and send it to anyone, inside or outside your organization.</span></span>
- <span data-ttu-id="8e8f4-1336">**BCC で受け取った場合の警告:** ブラインド カーボン コピーで受け取ったメールに対し、誤って全員に返信する前に、BCC のヒントで警告されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1336">**Warning when you've been BCC'ed:** The BCC infotip will warn you before you accidentally reply all to a mail that you've been blind carbon copied on.</span></span>
- <span data-ttu-id="8e8f4-1337">**洗練された [宛先] 行:** メッセージの宛先を指定するために [宛先] 行をクリックすると、選択されそうな受信者の候補が表示されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1337">**A smarter To: line:** When you click the To: line to address a message, we suggest recipients you're likely to choose.</span></span> <span data-ttu-id="8e8f4-1338">さらに、ユーザーの画像が表示されるので、正しいユーザーに送信しようとしていることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1338">Plus, you can see their picture, so you know yo’re sending to the right person.</span></span> [<span data-ttu-id="8e8f4-1339">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1339">Learn more</span></span>](https://support.office.com/article/147208AF-CA8E-4CDF-B71F-77BA81A54069)
- <span data-ttu-id="8e8f4-1340">**フィルターが適用された SVG を挿入する機能:** Office ユーザーは、フィルターが適用された SVG を挿入できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1340">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them.</span></span> [<span data-ttu-id="8e8f4-1341">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1341">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- <span data-ttu-id="8e8f4-p268">**改善された高解像度ディスプレイのサポート**: 複数のモニター、またはドッキングでラップトップを使用する場合、各ディスプレイの倍率設定が異なっていても Office アプリがすべてのディスプレイで鮮明に表示されるようになります。 [詳細情報](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p268">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings. [Learn more](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="8e8f4-1344">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1344">PowerPoint: Feature updates</span></span>

- <span data-ttu-id="8e8f4-1345">**すばやく始めましょう** 新しくデザインされたスタートページは、最近開いたドキュメントを前面と中央に配置します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1345">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="8e8f4-1346">以前より少ないクリック数でファイルにアクセスし、そこからすぐアカウント設定またはオプションを開きます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1346">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="8e8f4-1347">**ハンズフリーで入力:** マイクは用意しましたか。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1347">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="8e8f4-1348">[ディクテーション] をクリックして、発話すると PowerPoint によって入力されるのを確認してください。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1348">Click Dictate and watch PowerPoint type while you talk.</span></span> [<span data-ttu-id="8e8f4-1349">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1349">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="8e8f4-p271">**新しい見た目のリボン アイコン:** 機能に変化はないので、心配はいりません。さらに、どのサイズの画面でも、見た目がきれいです。[詳細情報](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p271">**Your ribbon icons have a new look:** Don’t worry, everything works the same. Plus, they look great on screens of all sizes. [Learn more](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span></span>
- <span data-ttu-id="8e8f4-p272">**改善された高解像度ディスプレイのサポート**: 複数のモニター、またはドッキングでラップトップを使用する場合、各ディスプレイの倍率設定が異なっていても Office アプリがすべてのディスプレイで鮮明に表示されるようになります。 [詳細情報](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p272">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings. [Learn more](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span></span>
- <span data-ttu-id="8e8f4-1355">**ハイパーリンクの色の設定:** ハイパーリンクの色は青だけではなくなりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1355">**Hyperlinks in living color:** Hyperlinks aren't just blue anymore.</span></span> <span data-ttu-id="8e8f4-1356">お好みのフォント色を適用してください。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1356">Apply any font color you like.</span></span> [<span data-ttu-id="8e8f4-1357">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1357">Learn more</span></span>](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)
- <span data-ttu-id="8e8f4-p274">**スライドが活気のあるものに:** アニメーション 3D グラフィックを挿入して、心臓の鼓動、惑星の軌道、画面を暴れまわる T レックスを表示します。[詳細情報](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p274">**Watch your slides come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage across the screen. [Learn more](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span></span>
- <span data-ttu-id="8e8f4-p275">**スケッチするだけで自動的に洗練される:** 手書きのテキストや図形が洗練された図表に変更されます。インク ストロークを選ぶだけで機能を利用できます。[詳細情報](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p275">**You sketch, we polish:** We change hand-drawn text and shapes into refined diagrams. Just select your ink strokes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>
- <span data-ttu-id="8e8f4-p276">**画像の背後を見えるようにする:** ワークシートに画像を挿入し、既定の設定から選択して、透明度の変化を確認するだけです。[詳細情報](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p276">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="8e8f4-1366">**Microsoft Stream に公開:** Microsoft Stream を使用して、組織内でより安全にビデオとプレゼンテーションを共有できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1366">**Publish to Microsoft Stream:** Share a presentation as a video more securely within your organization by using Microsoft Stream.</span></span> [<span data-ttu-id="8e8f4-1367">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1367">Learn more</span></span>](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- <span data-ttu-id="8e8f4-1368">**4K ビデオにエクスポート:** プレゼンテーションをビデオにエクスポートするときに、4K の解像度がオプションになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1368">**Export to 4K video:** When you export a presentation to video, 4K resolution is now an option.</span></span>  [<span data-ttu-id="8e8f4-1369">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1369">Learn more</span></span>](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- <span data-ttu-id="8e8f4-1370">**フィルターが適用された SVG を挿入する機能:** Office ユーザーは、フィルターが適用された SVG を挿入できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1370">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them.</span></span> [<span data-ttu-id="8e8f4-1371">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1371">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- <span data-ttu-id="8e8f4-1372">**大きなファイルがより速く開くようになりました:** OneDrive または SharePoint に保存されているファイルを開くと、画像、ビデオ、およびその他の大きな要素がバックグラウンドでダウンロードされるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1372">**Large files now open faster:** Images, videos, and other large elements now download in the background when opening files stored on OneDrive or SharePoint.</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="8e8f4-1373">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1373">Word: Feature updates</span></span>

- <span data-ttu-id="8e8f4-1374">**すばやく始めましょう** 新しくデザインされたスタートページは、最近開いたドキュメントを前面と中央に配置します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1374">**Get a faster start** The newly designed Start Page puts your recently opened documents front and center.</span></span> <span data-ttu-id="8e8f4-1375">以前より少ないクリック数でファイルにアクセスし、そこからすぐアカウント設定またはオプションを開きます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1375">Get to files in fewer clicks, and open Account settings or Options right from here.</span></span>
- <span data-ttu-id="8e8f4-1376">**ハンズフリーで入力:** マイクは用意しましたか。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1376">**Type hands-free:** Got a microphone?</span></span> <span data-ttu-id="8e8f4-1377">[ディクテーション] をクリックして、発話すると Word によって入力されるのを確認してください。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1377">Click Dictate and watch Word type while you talk.</span></span> [<span data-ttu-id="8e8f4-1378">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1378">Learn more</span></span>](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- <span data-ttu-id="8e8f4-p282">**文書を活気づかせる:** アニメーション 3D グラフィックスを挿入して、鼓動する心臓、周回する惑星、暴れ回るティラノサウルスをページ上に表示できます。[詳細情報](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p282">**Watch your documents come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage across the page. [Learn more](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)</span></span>
- <span data-ttu-id="8e8f4-p283">**新しい見た目のリボン アイコン:** 機能に変化はないので、心配はいりません。さらに、どのサイズの画面でも、見た目がきれいです。[詳細情報](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p283">**Your ribbon icons have a new look:** Don’t worry, everything works the same. Plus, they look great on screens of all sizes. [Learn more](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)</span></span>
- <span data-ttu-id="8e8f4-p284">**画像の背後を見えるようにする:** ワークシートに画像を挿入し、既定の設定から選択して、透明度の変化を確認するだけです。[詳細情報](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p284">**Reveal what's behind a picture:** Put a picture in a worksheet, pick your preset, and watch the transparency change. That's it! [Learn more](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)</span></span>
- <span data-ttu-id="8e8f4-1387">**フィルターが適用された SVG を挿入する機能:** Office ユーザーは、フィルターが適用された SVG を挿入できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1387">**Ability to insert SVG's with filters applied:** Office users now have the ability to insert SVG's that have filters applied to them.</span></span> [<span data-ttu-id="8e8f4-1388">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1388">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- <span data-ttu-id="8e8f4-p286">**改善された高解像度ディスプレイのサポート**: 複数のモニター、またはドッキングでラップトップを使用する場合、各ディスプレイの倍率設定が異なっていても Office アプリがすべてのディスプレイで鮮明に表示されるようになります。 [詳細情報](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p286">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings. [Learn more](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span></span>
- <span data-ttu-id="8e8f4-p287">**LinkedIn を活用して、最適な履歴書または CV を作成します:** 履歴書アシスタントを使用して、特定の役割に関する職歴、提案されているスキルなどを表示できます。 [詳細情報](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p287">**Write your best resume or CV with help from LinkedIn:** With Resume Assistant, see work experiences, suggested skills, and more for a given role. [Learn more](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="8e8f4-1393">Project: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1393">Project: Feature updates</span></span>

- <span data-ttu-id="8e8f4-p288">**タスク ボード カードに詳細を表示する:** タイトルだけでは内容が伝わらない場合は、最も重要な詳細がすべて表示されるようにタスク ボード カードをカスタマイズできます。[詳細情報](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p288">**See more info on Task Board cards:** When the title alone doesn’t tell the story, customize your Task Board cards to show all the most important details. [Learn more](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)</span></span>
- <span data-ttu-id="8e8f4-1396">**Office の外観が新しくなる:** Office アプリに、よりシンプルでアクセスしやすい最新のアイコンが加わり、リボンの外観が、Office アプリで使用可能な豊富なコラボレーション機能を強調するように更新されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1396">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="publisher-feature-updates"></a><span data-ttu-id="8e8f4-1397">Publisher: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1397">Publisher: Feature updates</span></span>

- <span data-ttu-id="8e8f4-1398">**Office の外観が新しくなる:** Office アプリに、よりシンプルでアクセスしやすい最新のアイコンが加わり、リボンの外観が、Office アプリで使用可能な豊富なコラボレーション機能を強調するように更新されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1398">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="8e8f4-1399">Visio: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1399">Visio: Feature updates</span></span>

- <span data-ttu-id="8e8f4-1400">**新しい図面でアイコンを楽しむ:** 分析、アート、お祝い、顔文字、スポーツなどのアイコンが含まれる 26 種類の新しいステンシルから選択できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1400">**Enjoy an iconic moment in your next diagram:** Pick from 26 new stencils with icons for analytics, arts, celebration, faces, sports, and more.</span></span>
- <span data-ttu-id="8e8f4-1401">**Office の外観が新しくなる:** Office アプリに、よりシンプルでアクセスしやすい最新のアイコンが加わり、リボンの外観が、Office アプリで使用可能な豊富なコラボレーション機能を強調するように更新されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1401">**Office has a new look:**  Office apps now have modern icons that are simpler and more accessible, and the ribbon has updated visuals that highlight the rich collaboration features available in Office apps.</span></span>

### <a name="office-suite-feature-updates"></a><span data-ttu-id="8e8f4-1402">Office スイート: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1402">Office Suite: Feature updates</span></span>

- <span data-ttu-id="8e8f4-p289">**Office のサード パーティ アプリケーションでは office.js api を使用した SVG の挿入をサポート:** Office アドインとも呼ばれるサード パーティ アプリケーションで SVG を挿入できるようになりました。ユーザーは、個人の SVG コレクションを Office に結び付けることができます。開発者は、Office.js API を使用してこの機能を利用できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p289">**Office 3rd Party Applications now have insert SVG support using the office.js api:** 3rd party applications also known as add-ins in Office now have the ability to insert SVG's. Users can now connect their personal collection of SVG's to Office. Developers can use this feature by using the Office.js API.</span></span>
- <span data-ttu-id="8e8f4-1406">**Microsoft Teams のインストール:** Microsoft Teams は、Office 365 ProPlus の既存のインストールに既定でインストールされています。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1406">**Installation of Microsoft Teams:**  Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="8e8f4-1407">詳細情報</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1407">Learn more</span></span>](/DeployOffice/teams-install)

### <a name="skype-for-business-feature-updates"></a><span data-ttu-id="8e8f4-1408">Skype for Business: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1408">Skype for Business: Feature updates</span></span>

- <span data-ttu-id="8e8f4-p291">**改善された高解像度ディスプレイのサポート**: 複数のモニター、またはドッキングでラップトップを使用する場合、各ディスプレイの倍率設定が異なっていても Office アプリがすべてのディスプレイで鮮明に表示されるようになります。 [詳細情報](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p291">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings. [Learn more](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span></span>

### <a name="teams-feature-updates"></a><span data-ttu-id="8e8f4-1411">Access: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1411">Teams: Feature updates</span></span>

- <span data-ttu-id="8e8f4-p292">**改善された高解像度ディスプレイのサポート**: 複数のモニター、またはドッキングでラップトップを使用する場合、各ディスプレイの倍率設定が異なっていても Office アプリがすべてのディスプレイで鮮明に表示されるようになります。 [詳細情報](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p292">**Improved support for high definition displays:** If you use multiple monitors or a laptop dock, Office apps will now look crisp on every display, even if the displays have different scaling settings. [Learn more](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)</span></span>

## <a name="version-1808-february-12"></a><span data-ttu-id="8e8f4-1414">バージョン 1808: 2 月 12 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1414">Version 1808: February 12</span></span>
<span data-ttu-id="8e8f4-1415">*バージョン 1808 (ビルド 10730.20280)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1415">*Version 1808 (Build 10730.20280)*</span></span> 

### <a name="access-non-security-updates"></a><span data-ttu-id="8e8f4-1416">Access: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1416">Access: Non-Security updates</span></span> 

- <span data-ttu-id="8e8f4-1417">この更新プログラムでは、Access に日本の新元号のサポートを追加します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1417">This update adds support for new Japanese eras to Access.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="8e8f4-1418">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1418">Outlook: Non-Security updates</span></span> 

- <span data-ttu-id="8e8f4-1419">存在しなくなったフォルダーを参照するルールで、ルールを管理しようとしたときにエラーが表示される問題と、クライアント側のルールの実行に失敗する問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1419">Addresses an issue that caused users with rules that refer to a folder that no longer exist to see an error when trying to manage rules and to see client-side rules fail to run.</span></span>
- <span data-ttu-id="8e8f4-1420">キャッシュされた代理メールボックスが予測不可能な間隔で頻繁にハングする問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1420">Addresses an issue that caused users with cached delegate mailboxes to encounter frequent hangs at unpredictable intervals.</span></span>
- <span data-ttu-id="8e8f4-1421">会議の終了時間が翌日の午前 0 時に設定されていると、いくつかのビューで「終日会議」が意図したものよりも 1 日長く表示される問題を解決します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1421">Addresses an issue that caused All Day Meetings to appear to span one more day than intended in some views due to the end time of the meeting being set to midnight of the following day.</span></span>
- <span data-ttu-id="8e8f4-1422">日本の元号を参照する新しい予約または会議を作成するとハングする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1422">Fixed a hang when creating new appointments or meetings that reference Japanese eras.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="8e8f4-1423">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1423">Office Suite: Non-security updates</span></span>

- <span data-ttu-id="8e8f4-1424">[Office 365 の一元展開](/office/dev/add-ins/publish/centralized-deployment)を使用して展開したアドインが機能停止して使用できなくなる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1424">Fixed issue where Add-ins, deployed using [O365 Office centralized deployment](/office/dev/add-ins/publish/centralized-deployment), were freezing and unusable.</span></span>


## <a name="version-1808-january-8"></a><span data-ttu-id="8e8f4-1425">バージョン 1808: 1 月 8 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1425">Version 1808: January 8</span></span>
<span data-ttu-id="8e8f4-1426">*バージョン 1808 (ビルド 10730.20264)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1426">*Version 1808 (Build 10730.20264)*</span></span> 

### <a name="outlook-non-security-updates"></a><span data-ttu-id="8e8f4-1427">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1427">Outlook: Non-security updates</span></span> 

- <span data-ttu-id="8e8f4-1428">空き時間検索でエラーの原因となる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1428">Fixed an issue that caused users to experience calendar synchronization errors.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="8e8f4-1429">Word: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1429">Word: Non-security updates</span></span>

- <span data-ttu-id="8e8f4-1430">オープン パフォーマンスが向上します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1430">Improve open performance.</span></span>

## <a name="version-1808-december-11"></a><span data-ttu-id="8e8f4-1431">バージョン 1808: 12 月 11 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1431">Version 1808: December 11</span></span>
<span data-ttu-id="8e8f4-1432">*バージョン 1808 (ビルド 10730.20262)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1432">*Version 1808 (Build 10730.20262)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="8e8f4-1433">Excel: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1433">Excel: Security updates</span></span> 

-   <span data-ttu-id="8e8f4-1434">[CVE-2018-8597](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8597): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1434">[CVE-2018-8597](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8597): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="8e8f4-1435">[CVE-2018-8598](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8598): Microsoft Excel の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1435">[CVE-2018-8598](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8598): Microsoft Excel Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="8e8f4-1436">[CVE-2018-8627](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8627): Microsoft Excel の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1436">[CVE-2018-8627](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8627): Microsoft Excel Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="8e8f4-1437">[CVE-2018-8636](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8636): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1437">[CVE-2018-8636](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8636): Microsoft Excel Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="8e8f4-1438">Outlook: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1438">Outlook: Security updates</span></span> 

-   <span data-ttu-id="8e8f4-1439">[CVE-2018-8587](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8587): Microsoft Outlook のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1439">[CVE-2018-8587](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8587): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 

### <a name="powerpoint-security-updates"></a><span data-ttu-id="8e8f4-1440">PowerPoint: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1440">PowerPoint: Security updates</span></span> 

-   <span data-ttu-id="8e8f4-1441">[CVE-2018-8628](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8628): Microsoft PowerPoint のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1441">[CVE-2018-8628](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8628): Microsoft PowerPoint Remote Code Execution Vulnerability</span></span> 

### <a name="excel-non-security-updates"></a><span data-ttu-id="8e8f4-1442">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1442">Excel: Non-Security updates</span></span> 

- <span data-ttu-id="8e8f4-1443">共同編集セッションで、他のユーザーがスライサー内のデータに列フィルターを適用した後で、そのスライサーが適切に更新されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1443">Fixed an issue in coauthoring sessions where a slicer is not properly updated after another user applies a column filter to the data in that slicer.</span></span>
- <span data-ttu-id="8e8f4-1444">共同編集セッションで、いずれかのユーザーがスライサーのキャプションをクリアすると、その共同編集セッションに参加している別のユーザーの Excel がクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1444">Fixed an issue in a coauthoring session where one of the users clears the caption for a slicer and this causes another user in the coauthoring session to experience an Excel crash.</span></span>
- <span data-ttu-id="8e8f4-1445">同じデータの列にバインドされた複数のテーブル スライサーを作成した後で、そのデータの列を削除するとクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1445">Fixed possible crash when creating multiple table slicers bound to the same column of data and then deleting that column of data.</span></span>
- <span data-ttu-id="8e8f4-1446">列幅の自動調整オプションがオフになっているときに、フィルター処理されたクエリ テーブルにセルで折り返されたテキストが含まれていると、そのクエリ テーブルを最新の情報に更新しているときに Excel がクラッシュすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1446">Fixed an issue where Excel would sometimes crash while refreshing a filtered query table that contains wrapped text in cells when the option to automatically adjust column widths was off.</span></span>
- <span data-ttu-id="8e8f4-1447">Excel 2007 で保存したスライサーを新しいバージョンの Excel で開いたときに、そのスライサーに表示される項目数を変更するとクラッシュが発生する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1447">Fixed an issue where slicers saved in Excel 2007 can trigger a crash when opened in newer versions of Excel if the number of items shown in the slicer changes.</span></span>
- <span data-ttu-id="8e8f4-1448">サポート要求を簡単に調査できるようにする、[診断の取得] ボタンのサポートを導入しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1448">Introduces support for the Get Diagnostics button to simplify the investigation of support requests.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="8e8f4-1449">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1449">Outlook: Non-Security updates</span></span>

- <span data-ttu-id="8e8f4-1450">[ルールと通知の管理] ダイアログ ボックスを起動するとユーザーにエラーが表示される原因になっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1450">Fixed an issue that caused users to see an error when launching the "Manage Rules and Alerts" dialog.</span></span>
- <span data-ttu-id="8e8f4-1451">従量制課金接続を使用しているときに、ユーザーが自分のメールボックスに DirectAccess 経由で接続できなくなる原因になっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1451">Fixed an issue that caused users to be unable to connect to their mailboxes over DirectAccess when using a metered connection.</span></span>
- <span data-ttu-id="8e8f4-1452">パブリック フォルダーに保存されているフリー ドキュメントが誤って「保護されたビュー」で開かれてユーザーに表示される原因になっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1452">Fixed an issue that caused users to see free docs stored in Public Folders erroneously open in "Protected View".</span></span>
- <span data-ttu-id="8e8f4-1453">インライン添付でアイテムを転送するときに、ユーザーに予期しない添付ファイルが表示される原因になっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1453">Fixed an issue that caused users to see unexpected attachments when forwarding items with inline attachments.</span></span>
- <span data-ttu-id="8e8f4-1454">OFT ファイルが添付ファイルとして送信された後に不完全にレンダリングされる原因になっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1454">Fixed an issue that caused OFT files to render poorly after being sent as an attachment.</span></span>
- <span data-ttu-id="8e8f4-1455">共有予定表に会議を追加したときに、一部のアドイン ユーザーにクラッシュが発生する原因になっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1455">Fixed an issue that caused some add in users to experience crashes when adding a meeting to a shared calendar.</span></span>
- <span data-ttu-id="8e8f4-1456">[会話の履歴] フォルダーを開いているときにユーザーに応答停止が発生する原因になっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1456">Fixed an issue that caused users to experience hangs when opening the Conversation History folder.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="8e8f4-1457">Project: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1457">Project: Non-Security updates</span></span>

- <span data-ttu-id="8e8f4-1458">Project の新しいベネズエラ通貨のサポートに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1458">Fixed an issue around supporting a new Venezuelan currency in Project.</span></span>
- <span data-ttu-id="8e8f4-1459">外部モニターに接続した Surface 4 を使用しているときに Project が応答停止することがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1459">Fixed an issue where Project may hang when using a Surface 4 that is connected to an external monitor.</span></span>
- <span data-ttu-id="8e8f4-1460">プロジェクトを XML 形式に保存するときに、Project がクラッシュすることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1460">Fixed an issue where Project may crash when saving the project to the XML format.</span></span>
- <span data-ttu-id="8e8f4-1461">リソース カレンダーの編集後に、エンタープライズ リソース カスタム フィールドが削除される可能性のある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1461">Fixed an issue where enterprise resource custom fields may be deleted after editing a resource's calendar.</span></span>
- <span data-ttu-id="8e8f4-1462">韓国語の表示名を検索しているときに、ユーザーにクラッシュが発生する原因になっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1462">Fixed an issue that caused users to experience crashes when searching for Korean display names.</span></span>

## <a name="version-1808-november-13"></a><span data-ttu-id="8e8f4-1463">バージョン 1808: 11 月 13 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1463">Version 1808: November 13</span></span>
<span data-ttu-id="8e8f4-1464">*バージョン 1808 (ビルド 10730.20205)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1464">*Version 1808 (Build 10730.20205)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="8e8f4-1465">Excel: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1465">Excel: Security updates</span></span>

-   <span data-ttu-id="8e8f4-1466">[CVE-2018-8574](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8574): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1466">[CVE-2018-8574](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8574): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="8e8f4-1467">[CVE-2018-8577](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8577): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1467">[CVE-2018-8577](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8577): Microsoft Excel Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="8e8f4-1468">Outlook: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1468">Outlook: Security updates</span></span> 

-   <span data-ttu-id="8e8f4-1469">[CVE-2018-8522](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8522): Microsoft Outlook のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1469">[CVE-2018-8522](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8522): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="8e8f4-1470">[CVE-2018-8524](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8524): Microsoft Outlook のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1470">[CVE-2018-8524](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8524): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="8e8f4-1471">[CVE-2018-8558](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8558): Microsoft Outlook の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1471">[CVE-2018-8558](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8558): Microsoft Outlook Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="8e8f4-1472">[CVE-2018-8576](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8576): Microsoft Outlook のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1472">[CVE-2018-8576](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8576): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="8e8f4-1473">[CVE-2018-8579](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8579): Microsoft Outlook の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1473">[CVE-2018-8579](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8579): Microsoft Outlook Information Disclosure Vulnerability</span></span> 
-   <span data-ttu-id="8e8f4-1474">[CVE-2018-8582](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8582): Microsoft Outlook のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1474">[CVE-2018-8582](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8582): Microsoft Outlook Remote Code Execution Vulnerability</span></span> 

### <a name="project-security-updates"></a><span data-ttu-id="8e8f4-1475">Project: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1475">Project: Security updates</span></span> 

-   <span data-ttu-id="8e8f4-1476">[CVE-2018-8575](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8575): Microsoft Project のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1476">[CVE-2018-8575](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8575): Microsoft Project Remote Code Execution Vulnerability</span></span> 

### <a name="word-security-updates"></a><span data-ttu-id="8e8f4-1477">Word: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1477">Word: Security updates</span></span> 

-   <span data-ttu-id="8e8f4-1478">[CVE-2018-8573](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8573): Microsoft Word のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1478">[CVE-2018-8573](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8573): Microsoft Word Remote Code Execution Vulnerability</span></span> 

### <a name="skype-for-business-security-updates"></a><span data-ttu-id="8e8f4-1479">Skype for Business: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1479">Skype for Business: Security updates</span></span> 

-   <span data-ttu-id="8e8f4-1480">[CVE-2018-8546](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8546): Microsoft Skype for Business のサービス拒否攻撃の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1480">[CVE-2018-8546](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8546): Microsoft Skype for Business Denial of Service Vulnerability</span></span> 

### <a name="excel-non-security-updates"></a><span data-ttu-id="8e8f4-1481">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1481">Excel: Non-security updates</span></span> 

- <span data-ttu-id="8e8f4-1482">一部のビルド/バージョンで Power Pivot が表示されなかったバグを修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1482">Fixed a bug where Power Pivot did not appear in some builds/versions.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="8e8f4-1483">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1483">Outlook: Non-security updates</span></span> 

- <span data-ttu-id="8e8f4-1484">ユーザーがアカウント コントロール ボタンを使用してユーザー設定のフォームでアカウントを正常に切り替えることができない原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1484">Fixed an issue that caused users to be unable to successfully use the Accounts control button to switch between accounts on custom forms.</span></span>
- <span data-ttu-id="8e8f4-1485">ユーザーが ScanPST を使用して OST/PST ファイルを修復するとクラッシュが発生する原因となっていた問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1485">Fixed an issue that caused users to experience a crash when using ScanPST to repair an OST/PST file.</span></span>
- <span data-ttu-id="8e8f4-1486">オンライン モード プロファイルを使用するユーザーに対して特定のメール メッセージの CC: フィールドが表示されなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1486">Fixed an issue that caused the CC: field on certain mail messages to fail to display for users with online mode profiles.</span></span>

### <a name="onenote-non-security-updates"></a><span data-ttu-id="8e8f4-1487">OneNote: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1487">OneNote: Non-security updates</span></span> 

- <span data-ttu-id="8e8f4-1488">同期や、削除済みセクションへの移動に関係して生じる可能性がある安定性の問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1488">Fixed a stability issue that can occur involving sync and navigating to a deleted section.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="8e8f4-1489">Project: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1489">Project: Non-security updates</span></span> 

- <span data-ttu-id="8e8f4-1490">新しい先進エクスペリエンスで SharePoint ドキュメント ライブラリ上の Project ファイルの作業を行っている場合、チェックアウトが必要な操作および読み取り専用の操作に正しく従っていない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1490">Fixed an issue where if you were working with Project files on a SharePoint document library that was in the new modern experience, the Check-Out Required and Read-Only actions aren't being correctly followed.</span></span>


## <a name="version-1808-october-9"></a><span data-ttu-id="8e8f4-1491">バージョン 1808: 10 月 9 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1491">Version 1808: October 9</span></span>
<span data-ttu-id="8e8f4-1492">*バージョン 1808 (ビルド 10730.20155)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1492">*Version 1808 (Build 10730.20155)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="8e8f4-1493">Excel: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1493">Excel: Security updates</span></span>
-   <span data-ttu-id="8e8f4-1494">[CVE-2018-8502](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8502): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1494">[CVE-2018-8502](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8502): Microsoft Excel Remote Code Execution Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="8e8f4-1495">Outlook: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1495">Outlook: Security updates</span></span> 
-   <span data-ttu-id="8e8f4-1496">[ADV180026](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/ADV180026): Microsoft Office の高度な防御の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1496">[ADV180026](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/ADV180026): Microsoft Office Defense in Depth Update</span></span> 

### <a name="powerpoint-security-updates"></a><span data-ttu-id="8e8f4-1497">PowerPoint: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1497">PowerPoint: Security updates</span></span> 
-   <span data-ttu-id="8e8f4-1498">[CVE-2018-8501](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8501): Microsoft PowerPoint のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1498">[CVE-2018-8501](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8501): Microsoft PowerPoint Remote Code Execution Vulnerability</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="8e8f4-1499">Word: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1499">Word: Security updates</span></span> 
-   <span data-ttu-id="8e8f4-1500">[CVE-2018-8504](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8504): Microsoft Word のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1500">[CVE-2018-8504](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8504): Microsoft Word Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="8e8f4-1501">[ADV180026](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/ADV180026): Microsoft Office の高度な防御の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1501">[ADV180026](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/ADV180026): Microsoft Office Defense in Depth Update</span></span> 

### <a name="office-suite-security-updates"></a><span data-ttu-id="8e8f4-1502">Office スイート: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1502">Office suite: Security updates</span></span> 
-   <span data-ttu-id="8e8f4-1503">[CVE-2018-8432](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8432): Microsoft グラフィック コンポーネントのリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1503">[CVE-2018-8432](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8432): Microsoft Graphics Components Remote Code Execution Vulnerability</span></span> 

### <a name="excel-non-security-updates"></a><span data-ttu-id="8e8f4-1504">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1504">Excel: Non-Security updates</span></span> 
-   <span data-ttu-id="8e8f4-p293">範囲 2190 から 2194 の記号が Cambria Math に切り替えられるときの問題を修正しました。これにより、Excel のセルの高さが 3 倍になります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p293">Fixed the issue when symbols in the range 2190...2194 are switched to Cambria Math. This is causing the Excel cell height to increase by 3 times.</span></span>
-   <span data-ttu-id="8e8f4-1507">これにより、多くの定義名を持つブックの書式設定オプションにユーザーがマウス ポインターを重ねると Excel が応答しなくなったり、オプションでリアルタイムのプレビューが無効になっていてもクイック分析ツールで Excel が応答しなくなったりする場合のある Excel の問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1507">This fixes the issue in Excel wherein Excel may become unresponsive when the user hovers over formatting options in a workbook with many defined names, and where Excel may become unresponsive in the Quick Analysis tool even when Live Preview was disabled in options.</span></span>
-   <span data-ttu-id="8e8f4-p294">Excel アプリケーション ウィンドウを別のデスクトップに移動するとパフォーマンスが低下する問題は現在調査中です。それまでの間、このパフォーマンス低下が発生したら、[ファイル オプション] ダイアログ ボックスの [全般] タブの [複数ディスプレイを使用する場合] で [互換性に対応した最適化] を選択して回避してください。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p294">We are currently investigating slow performance when moving the Excel Application Window from one desktop to another. In the meantime, if you do notice this slowness then a work around to consider is to select "Optimize for compatibility" for "When using multiple displays" in the "General" tab in the File Options dialog.</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="8e8f4-1510">PowerPoint: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1510">PowerPoint: Non-Security updates</span></span>
-   <span data-ttu-id="8e8f4-1511">ActiveX コンテンツを含むファイルを保存すると、ファイルが壊れる可能性のある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1511">Fixed an issue of potential file corruptions when saving files with ActiveX content.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="8e8f4-1512">Word: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1512">Word: Non-Security updates</span></span>
-   <span data-ttu-id="8e8f4-1513">Word 文書オブジェクトを挿入すると、数式エディターが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1513">Fixed an issue that when inserting a Word Document object, the equation editor would appear.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="8e8f4-1514">Project: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1514">Project: Non-Security updates</span></span>
-   <span data-ttu-id="8e8f4-1515">プリントアウトにヘッダーまたはフッターを設定した場合、次回プロジェクトを印刷するときに変更が保持されなかった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1515">Fixed an issue where if you set a header or footer for a print-out, the change wasn't persisted the next time you went to print your project.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="8e8f4-1516">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1516">Office Suite: Non-Security updates</span></span>
-   <span data-ttu-id="8e8f4-1517">アクセシビリティとパフォーマンスの設定でアニメーションをオフにしてもアニメーションが表示されてしまうアプリの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1517">Fixed issue of apps showing animations despite turning off animations through accessibility and performance settings.</span></span> 
-   <span data-ttu-id="8e8f4-1518">蛍光ペン描画ツールを使用すると背景が空白になる問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1518">Fixed issue of background turning blank when using highlighter drawing tool.</span></span>

## <a name="version-1808-september-11"></a><span data-ttu-id="8e8f4-1519">バージョン 1808: 9 月 11 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1519">Version 1808: September 11</span></span>
<span data-ttu-id="8e8f4-1520">*バージョン 1808 (ビルド 10730.20102)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1520">*Version 1808 (Build 10730.20102)*</span></span>

### <a name="access-feature-updates"></a><span data-ttu-id="8e8f4-1521">Access: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1521">Access: Feature Updates</span></span>
 - <span data-ttu-id="8e8f4-p295">**新しいグラフを使用したデータの視覚化:** 11 種類のグラフから選択してフォームやレポートに追加することにより、データが見やすくなり、十分な情報に基づいて決定を下すことができます。[詳細情報](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p295">**Visualize data with new charts:** Choose from 11 charts and add one to your forms and reports to better visualize the data and make informed decisions. [Learn more](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)</span></span>
 
 ### <a name="access-security-updates"></a><span data-ttu-id="8e8f4-1524">Access: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1524">Access: Security updates</span></span>
-   <span data-ttu-id="8e8f4-1525">[CVE-2018-8312](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8312): Microsoft Access のリモート コード実行の Use After Free 脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1525">[CVE-2018-8312](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8312): Microsoft Access Remote Code Execution Use After Free Vulnerability</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="8e8f4-1526">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1526">Excel: Feature updates</span></span>
 - <span data-ttu-id="8e8f4-p296">**共同編集:** ブック内で他のユーザーと同時に作業します。[詳細情報](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p296">**Collaborative editing:** Work with others at the same time in your workbook. [Learn more](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)</span></span>
 - <span data-ttu-id="8e8f4-p297">**クラウド ファイルの自動保存が既定で有効になる:** 2018 年 9 月の半期チャネル (対象指定) リリースでは、自動保存が既定で有効になります。これにより、OneDrive または SharePoint Online に保存されるドキュメントで変更が失われることをユーザーは心配する必要がありません。変更はクラウドに自動的に保存されるので、ユーザーは明示的に Ctrl + S キーを押すか、[保存] ボタンをクリックする必要はありません。ただし、ユーザーは、この動作の変更を理解し、ドキュメントを誤って変更しないように注意する必要があります。ユーザーは、画面の上部にある [自動保存] トグルを使用して自動保存をオフにできます。この変更についてユーザーに通知し、Office 365 でこの新機能を最大限に利用する方法について説明することをお勧めします。[自動保存の詳細](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5)、[IT 管理者が自動保存について知っておくべきことの詳細](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p297">**AutoSave for cloud files is now enabled by default:** AutoSave is enabled by default in the September 2018 Semi-Annual Channel (Targeted) release. This change means users won’t have to worry about losing their changes in documents stored on OneDrive or SharePoint Online. Changes will be saved in the cloud automatically, and users will no longer have to explicitly press Ctrl + S or the Save button. However, they will have to understand this change in behavior so they don’t make accidental changes to documents. Note that users can turn off AutoSave using the AutoSave toggle at the top of the screen. We recommend that you notify your users about this upcoming change and educate them about how to best take advantage of this new feature in Office 365. [Learn more about AutoSave](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Learn more about what IT admins should know about AutoSave](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span></span>
- <span data-ttu-id="8e8f4-p298">**セルおよび数式バーの編集の強化:** Ctrl + A キーを押して、セルまたは数式バーのテキストを選択できるようになりました。絵文字とその他の複雑な文字のサポートも強化されました。[詳細情報](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p298">**Improved cell and formula bar editing:** You can now use CTRL+A to select text in a cell or the formula bar. There's also improved support for emojis and other complex characters.[Learn more](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)</span></span>
- <span data-ttu-id="8e8f4-p299">**アクセシビリティ チェックの改善:** アクセシビリティ チェックで、ブックのアクセシビリティを向上させるための国際標準と推奨事項のサポートが更新されました。[詳細情報](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p299">**Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your workbooks more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span></span>
- <span data-ttu-id="8e8f4-p300">**不要な編集の回避:** 誤って変更されないように、読み取り専用でブックが開くように設定します。[ファイル]、[情報]、[ブックの保護]、[常に読み取り専用で開く] の順に移動します</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p300">**Avoid unwanted edits:** Set your workbooks to open as read-only to prevent accidental changes. Go to File > Info > Protect Workbook > Always Open Read-Only</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="8e8f4-1542">Excel: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1542">Excel: Security updates</span></span>
-   <span data-ttu-id="8e8f4-1543">[CVE-2018-8331](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8331): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1543">[CVE-2018-8331](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8331): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1544">[CVE-2018-8429](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8429): Microsoft Excel の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1544">[CVE-2018-8429](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8429): Microsoft Excel Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1545">[CVE-2018-8375](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8375): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1545">[CVE-2018-8375](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8375): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="8e8f4-1546">[CVE-2018-8379](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8379): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1546">[CVE-2018-8379](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8379): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="8e8f4-1547">[CVE-2018-8382](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8382): Microsoft Excel の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1547">[CVE-2018-8382](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8382): Microsoft Excel Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1548">[CVE-2018-8246](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8246): Microsoft Excel の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1548">[CVE-2018-8246](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8246): Microsoft Excel Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1549">[CVE-2018-8248](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8248): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1549">[CVE-2018-8248](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8248): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1550">[CVE-2018-8147](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8147): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1550">[CVE-2018-8147](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8147): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1551">[CVE-2018-8148](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8148): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1551">[CVE-2018-8148](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8148): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1552">[CVE-2018-8162](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8162): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1552">[CVE-2018-8162](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8162): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1553">[CVE-2018-8163](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8163): Microsoft Excel の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1553">[CVE-2018-8163](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8163): Microsoft Excel Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1554">[CVE-2018-1029](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-1029): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1554">[CVE-2018-1029](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-1029): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="8e8f4-1555">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1555">Excel: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1556">元のセルのセットからグラフのソース データを変更すると Excel がクラッシュすることのある問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1556">Fix an issue where Excel may crash when changing a chart's source data from its original set of cells.</span></span>
-   <span data-ttu-id="8e8f4-1557">FullCalcOnLoad プロパティが設定されている場合でも、ファイルを開いたときに再計算されないことのある問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1557">Fix an issue where recalculation may not happen on open even if the FullCalcOnLoad property is set.</span></span>  
-   <span data-ttu-id="8e8f4-1558">日付のセル書式設定で和暦を使用すると、間違った年が表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1558">Fix an issue where the wrong year is shown when Japanese Era calendar is used in date cell format.</span></span>
-   <span data-ttu-id="8e8f4-p301">Excel データ モデルにデータをインポートするとき、負のゼロの値を受け取るとエラーになりました。修正後は、そのような値はゼロとしてインポートされます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p301">When importing data into the Excel Data Model, incoming values of negative zero would result in an error.  The fix imports such values as zero.</span></span>
-   <span data-ttu-id="8e8f4-1561">Excel のピボット テーブルでグループ化 (またはグループ解除) 操作を行うとクラッシュを引き起こす可能性がある問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1561">Fix an issue where a group (or ungroup) operation in an Excel PivotTable could sometimes trigger a crash.</span></span>
-   <span data-ttu-id="8e8f4-1562">グラフの操作によって Excel がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1562">Fix an issue where charting actions could cause Excel to crash.</span></span>
-   <span data-ttu-id="8e8f4-1563">一部のユーザーに対し、Power View のアドインが誤って無効になるの問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1563">Fix an issue where the Power View add-in is inadvertently disabled for some users.</span></span>
-   <span data-ttu-id="8e8f4-1564">ドキュメントの回復中に作成された一時的な自動回復ファイルがクリーンアップされないという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1564">Fix an issue where temporary auto-recovery files created during document recovery are never cleaned up.</span></span>
-   <span data-ttu-id="8e8f4-1565">保護されたブックでテキスト ファイルに新しい接続を作成しようとすると、「ブックは保護されており、変更できません」というエラー メッセージが出るという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1565">Fix an issue where attempting to make a new connection to a text file in a protected workbook results in getting a "Workbook is protected and cannot be changed" error message.</span></span>
-   <span data-ttu-id="8e8f4-1566">Outlook メールに添付された Excel ブックのクイック印刷が機能しないことのある問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1566">Fix an issue where Quick Print of an Excel workbook attached to an Outlook email may not print.</span></span>
-   <span data-ttu-id="8e8f4-1567">ハイパーリンクをクリックすると Excel がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1567">Fix an issue where clicking on a hyperlink may cause Excel to crash.</span></span>
-   <span data-ttu-id="8e8f4-1568">キューブ関数を使用すると、Excel がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1568">Fix an issue where using cube functions causes Excel to crash.</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="8e8f4-1569">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1569">Outlook: Feature updates</span></span>
 - <span data-ttu-id="8e8f4-p302">**アクセシビリティ チェックの改善:** アクセシビリティ チェックで、メッセージのアクセシビリティを向上させるための国際標準と推奨事項のサポートが更新されました。[詳細情報](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p302">**Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your messages more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span></span>
 - <span data-ttu-id="8e8f4-p303">**プロファイルの選択からのプロファイルの管理:** Outlook 起動時にプロファイルの選択を使用した場合、コントロール パネルに移動しなくても変更を行うことができます。プロファイルの作成と削除や、設定の変更など、すべてをプロファイルの選択から実行できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p303">**Manage Profiles from the Profile Picker:** If you use the Profile Picker when Outlook starts up, you can now make changes without going to the control panel. Create and delete profiles, change settings, all from the Profile Picker.</span></span>
- <span data-ttu-id="8e8f4-1574">**アクセシビリティの組み込み:** 画像にわかりやすい代替テキストを追加することで、すべてのユーザーにアクセシビリティの高いメッセージを作成します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1574">**Accessibility built right in:** Make your messages accessible to everyone by adding descriptive alt text to your images.</span></span>
- <span data-ttu-id="8e8f4-p304">**Outlook アドインの警告:** Outlook COM アドインでは、Outlook の他の部分の速度を遅くする問題が発生する場合があります。これらの問題は、Outlook フォルダー間の切り替え、新規メールの受信、予定表アイテムを開くなどのイベントの遅延が原因の可能性があります。このような問題が発生した場合、Outlook では通知バーに警告が表示されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p304">**Outlook add-in warnings:** Occasionally an Outlook COM add-in can encounter problems that slows down the rest of Outlook. These problems could be due to latency of events such as switching between Outlook folders, arrival of new emails, opening Calendar items, etc. When such issues arise, Outlook will display a warning in the notification bar.</span></span>
- <span data-ttu-id="8e8f4-1577">**会議出席者を確認する:** 自分が開催者ではない場合でも、会議出席依頼への他のユーザーの回答を確認できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1577">**Know who you'll be meeting with:** You can see other people's responses to a meeting request, even if you aren't the organizer.</span></span>
- <span data-ttu-id="8e8f4-p305">**アラームを見落とさない:** 作業中のウィンドウ上にポップアップ表示されるように、アラームを設定できます。設定しない場合でも、Outlook がタスク バーで点滅してユーザーの注意を引きます。[詳細情報](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p305">**Never miss a reminder:** Set reminders to pop up over windows you're working in. Otherwise, Outlook will blink in the taskbar to get your attention.[Learn more](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)</span></span>
- <span data-ttu-id="8e8f4-p306">**削除済みアイテムを開封済みに:** 削除したメッセージすべてを開封済みとして設定できるようになりました。[ファイル] \> [オプション] \> [メール] \> [その他] の順に移動して、オプトインします。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p306">**Mark deleted items as read:** You can now set any message that you delete as read. Opt in by going to File \> Options \> Mail \> Other.</span></span>
- <span data-ttu-id="8e8f4-p307">**3 タイムゾーン表示:** タイム ゾーン間で会議をスケジュールする必要がありますか? 複数のタイム ゾーンをカレンダーに追加すると、全員の予定を確認し、全員が可能な時間を選択することが簡単になります。[詳細情報](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p307">**View three time zones:** Need to schedule a meeting across time zones? Add multiple time zones to your calendar to easily see everyone's availability and pick a time that works for all. [Learn more](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)</span></span>
- <span data-ttu-id="8e8f4-1585">**グループ作成のユーザー エクスペリエンスの改善:** グループ作成のユーザー エクスペリエンスを改善し、最新のわかりやすいものにしました。[詳細情報](https://support.office.com/article/04d0c9cf-6864-423c-a380-4fa858f27102)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1585">**Refined user experience for creating a group:** We have refined the user experience for the create group to make it look more modern and clutter-free.[Learn more](https://support.office.com/article/04d0c9cf-6864-423c-a380-4fa858f27102)</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="8e8f4-1586">Outlook: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1586">Outlook: Security updates</span></span>
-   <span data-ttu-id="8e8f4-1587">[CVE-2018-8310](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8310): Microsoft Office 改ざんの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1587">[CVE-2018-8310](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8310): Microsoft Office Tampering Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1588">[CVE-2018-8244](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8244): Microsoft Outlook 特権の昇格の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1588">[CVE-2018-8244](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8244): Microsoft Outlook Elevation of Privilege Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1589">[CVE-2018-8150](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8150): Microsoft Outlook のセキュリティ機能のバイパスの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1589">[CVE-2018-8150](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8150): Microsoft Outlook Security Feature Bypass Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1590">[ADV180021](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/ADV180021): Microsoft Office の高度な防御の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1590">[ADV180021](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/ADV180021): Microsoft Office Defense in Depth Update</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="8e8f4-1591">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1591">Outlook: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1592">Outlook 内に読み込み、システム言語を日本語に切り替えて VBA IDE に日本語の文字を入力しようとするとフリーズする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1592">Fix an issue where if you switch the system language to Japanese and attempt to type Japanese characters into the VBA IDE when loaded within Outlook, it freezes.</span></span>
-   <span data-ttu-id="8e8f4-1593">[送信トレイ] または [送信済みアイテム] フォルダーに切り替えると、Outlook がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1593">Fix an issue where switching to the Outbox or Sent Items folder causes Outlook to crash.</span></span>
-   <span data-ttu-id="8e8f4-1594">会議の本文や添付ファイルを変更すると、会議の更新情報の出席者への送信がオプションになる代わりに、すべての出席者が会議の更新を受信する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1594">Fix an issue where all attendees receive meeting updates when the meeting body or attachments change, instead of sending a meeting update to the attendees being optional.</span></span>
-   <span data-ttu-id="8e8f4-1595">ユーザー エージェント文字列が変更されたために、ユーザーが EWS エンドポイントおよび REST エンドポイントに接続できなくなる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1595">Fix an issue that causes users to be unable to connect to EWS and REST endpoints because of a change in the User-Agent string.</span></span>
-   <span data-ttu-id="8e8f4-1596">出席者に対する会議場所の更新に、新しい場所ではなく、古い場所が表示される問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1596">Fix an issue where a meeting location update to attendees shows the old location instead of the new location.</span></span>
-   <span data-ttu-id="8e8f4-1597">ユーザーが閲覧ウィンドウで添付ファイルをプレビューすると、エラーが表示される問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1597">Fix an issue where the user sees an error when previewing an attachment in the reading pane.</span></span>
-   <span data-ttu-id="8e8f4-1598">ユーザーが電子メールを作成中に、表示名が電子メール アドレスに解決されると、Outlook がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1598">Fix an issue where Outlook crashes when resolving display names to email addresses when the user is composing an email.</span></span>
-   <span data-ttu-id="8e8f4-1599">一部のユーザーがテナント管理者によって有効にされたサポート機能を受信しない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1599">Fix an issue where some users don't receive support features that have been enabled by their tenant admin.</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="8e8f4-1600">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1600">PowerPoint: Feature updates</span></span> 
- <span data-ttu-id="8e8f4-p308">**クラウド ファイルの自動保存が既定で有効になる:** 2018 年 9 月の半期チャネル (対象指定) リリースでは、自動保存が既定で有効になります。これにより、OneDrive または SharePoint Online に保存されるドキュメントで変更が失われることをユーザーは心配する必要がありません。変更はクラウドに自動的に保存されるので、ユーザーは明示的に Ctrl + S キーを押すか、[保存] ボタンをクリックする必要はありません。ただし、ユーザーは、この動作の変更を理解し、プレゼンテーションを誤って変更しないように注意する必要があります。ユーザーは、画面の上部にある [自動保存] トグルを使用して自動保存をオフにできます。この変更についてユーザーに通知し、Office 365 でこの新機能を最大限に利用する方法について説明することをお勧めします。[自動保存の詳細](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5)、[IT 管理者が自動保存について知っておくべきことの詳細](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p308">**AutoSave for cloud files is now enabled by default:** AutoSave is enabled by default in the September 2018 Semi-Annual Channel (Targeted) release. This change means users won’t have to worry about losing their changes in documents stored on OneDrive or SharePoint Online. Changes will be saved in the cloud automatically, and users will no longer have to explicitly press Ctrl + S or the Save button. However, they will have to understand this change in behavior so they don’t make accidental changes to presentations. Note that users can turn off AutoSave using the AutoSave toggle at the top of the screen. We recommend that you notify your users about this upcoming change and educate them about how to best take advantage of this new feature in Office 365. [Learn more about AutoSave](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Learn more about what IT admins should know about AutoSave](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)</span></span>
- <span data-ttu-id="8e8f4-p309">**手書き内容の変換:** フリーハンドのメモや描画を読みやすいテキストや整った図形に変換して、洗練されたプレゼンテーションを作成します。 [詳細情報](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p309">**Convert your ink:** Take scribbled notes and drawings, and convert them into readable text and crisp shapes to create a polished presentation. [Learn more](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)</span></span>
- <span data-ttu-id="8e8f4-p310">**SVG サポートの強化:** フィルターが適用された SVG を挿入できます。[詳細情報](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p310">**Improved SVG support:** You can insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>
- <span data-ttu-id="8e8f4-p311">**ペンでスライドにタイトルを付ける:** ペンを使用してタイトルをインク入力すると、PowerPoint でテキストに変換されます。[詳細情報](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p311">**Title your slides with a pen:** Use your pen to ink in a title, and watch PowerPoint convert it to text. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>
- <span data-ttu-id="8e8f4-p312">**不要な編集の回避:** 誤って変更されないように、読み取り専用でブックが開くように設定します。[ファイル]、[情報]、[ブックの保護]、[常に読み取り専用で開く] の順に移動します</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p312">**Avoid unwanted edits:** Set your workbooks to open as read-only to prevent accidental changes. Go to File > Info > Protect Workbook > Always Open Read-Only</span></span>
- <span data-ttu-id="8e8f4-p313">**アクセシビリティ チェックの改善:** アクセシビリティ チェックで、プレゼンテーションのアクセシビリティを向上させるための国際標準と推奨事項のサポートが更新されました。[詳細情報](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p313">**Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your presentations more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="8e8f4-1618">PowerPoint: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1618">PowerPoint: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1619">太線罫線を使用する表が正しく表示されない問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1619">Fix an issue where tables are rendered incorrectly with thick borders.</span></span>
-   <span data-ttu-id="8e8f4-1620">Shape.Visibile プロパティを変更するとクラッシュが発生する可能性がある問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1620">Fix an issue where a potential crash could occur when changing the Shape.Visibile property.</span></span>
-   <span data-ttu-id="8e8f4-1621">共同編集されているドキュメントの変更を反映できない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1621">Fix an issue where changes in co-authored documents fail to merge.</span></span>
-   <span data-ttu-id="8e8f4-1622">ActiveX コントロールを含むドキュメントの共同編集が失敗する原因となる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1622">Fix an issue where documents containing ActiveX controls would cause co-authoring to fail.</span></span>
-   <span data-ttu-id="8e8f4-1623">図形内でスペルを修正すると PowerPoint がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1623">Fix an issue where spelling correction in shapes causes PowerPoint to crash.</span></span>
-   <span data-ttu-id="8e8f4-1624">SharePoint Online からファイルを開くと PowerPoint がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1624">Fix an issue where PowerPoint crashes when opening a file from SharePoint Online.</span></span>
-   <span data-ttu-id="8e8f4-1625">自動保存が有効な場合に回復ウィンドウが誤って表示される問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1625">Fix an issue where the Recovery Pane incorrectly appears when AutoSave is on.</span></span>
-   <span data-ttu-id="8e8f4-1626">サインインが表示されないためにユーザーがファイルにアクセスできない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1626">Fix an issue where sign-in isn't shown preventing a user from accessing a file.</span></span>
-   <span data-ttu-id="8e8f4-1627">複数のユーザーが同じプレゼンテーションを共同編集すると、スライド マスターに正しくない重複が発生する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1627">Fix an issue where multiple users co-authoring on the same presentation results in an incorrect duplication of slides masters.</span></span>
-   <span data-ttu-id="8e8f4-1628">OneDrive に保存されているファイルを開いた際、保護ビューを終了すると PowerPoint がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1628">Fix an issue where opening a file saved on OneDrive results in PowerPoint crashing when exiting Protected View.</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="8e8f4-1629">Project: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1629">Project: Feature updates</span></span> 
- <span data-ttu-id="8e8f4-1630">**スプリントの管理:** アジャイル スプリントを簡単に追加、更新、削除します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1630">**Sprint management:** Quickly add, update, or delete agile sprints.</span></span>
- <span data-ttu-id="8e8f4-1631">**タスク ボードのフィルター処理:** 主なリソースまたはサマリー タスクをフィルター処理して、タスク ボードを効率化します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1631">**Task board filtering:** Streamline your task boards by filtering on key resources or summary tasks.</span></span>
- <span data-ttu-id="8e8f4-1632">**タスク ボードから達成率を設定:** 各列の達成率を選択し、ドラッグ アンド ドロップでタスクの完了を更新します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1632">**Set percent complete from a task board:** Choose a percent complete for each column, and then update task completion with drag-and-drop.</span></span>
- <span data-ttu-id="8e8f4-1633">**スプリント ナビゲーション:** スプリント表示を切り替えて、タスクをスプリント間ですばやく移動します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1633">**Sprint navigation:** Switch from one sprint view to another, and quickly move tasks between sprints.</span></span>
- <span data-ttu-id="8e8f4-p314">**スプリントを管理する新しい方法:** アジャイルな方法でタスク ボードを使用できます。[スプリントの管理] に移動して、プロジェクトの拡大に伴って、スプリントを追加したり、削除したりできます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p314">**A new way to manage sprints:** Take an agile approach to working with Task Boards. Go to Manage Sprints to add and remove sprints as your project evolves.</span></span>
- <span data-ttu-id="8e8f4-p315">**最近使用したファイルの保存場所の整理:** Project では、他のプロジェクトを保存した場所に関する最新のリストを保持します。プロジェクトを保存する準備ができたら、最近使用したファイルの保存場所の 1 つを選択し、それ以上気にする必要はありません。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p315">**Stay organized with Recent save locations:** Project keeps a running list of where you've saved other projects. When you're ready to save your project, just choose one of your Recent save locations and get on with your day.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="8e8f4-1638">Project のセキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1638">Project non-security updates</span></span>
- <span data-ttu-id="8e8f4-1639">マスター プロジェクトのコンテキストでサブ プロジェクトの作業を行うと、サブ プロジェクトを保存できない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1639">Fix an issue where you are blocked from saving a sub project when working with them through the context of a master project.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="8e8f4-1640">Skype for Business: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1640">Skype for Business: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-p316">TLS 1.2 のサポートに関連する問題を修正します (注: これは 4 月 10 日のノートで説明したものと同じ修正であり、9 月ロールアップの一部として再掲します)。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p316">Fix an issue related to TLS 1.2 support. (Note: This is the same fix that was mentioned in the April 10 notes and is mentioned here again as part of the September rollup.)</span></span>
-   <span data-ttu-id="8e8f4-1643">会議で [Skype 通話] を選択してユーザーを追加するとエラーが発生する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1643">Fix an issue where adding users by selecting 'Skype Call' in a meeting causes an error.</span></span>
-   <span data-ttu-id="8e8f4-1644">Skype Room が場所として追加され、会議に既にチーム会議の座標が含まれている場合、会議に Skype 座標を追加するかどうかを確認するユーザー プロンプトを削除します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1644">Remove prompt asking user to add Skype coordinates to a meeting, if a Skype Room is added as the location and the meeting already contains Teams meeting coordinates.</span></span>
-   <span data-ttu-id="8e8f4-1645">UseLocationForE911Only が true に設定されている場合でも、場所が設定されるという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1645">Fix an issue where location is populated even when UseLocationForE911Only is set to true.</span></span>
-   <span data-ttu-id="8e8f4-1646">"会議センターを使用して通話する" オプションを使用して参加者一覧にあるユーザーを招待する際に、Skype for Business が停止する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1646">Fix an issue where Skype for Business hangs when using the "call using conference center" option to invite users from the roster.</span></span>
-   <span data-ttu-id="8e8f4-1647">Skype for Business 会議の作成中に、ターミナル サーバー上で動作している Outlook がフリーズする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1647">Fix an issue where Outlook running on terminal server freezes while creating a Skype for Business meeting.</span></span>
-   <span data-ttu-id="8e8f4-1648">EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket の既定値を TRUE に変更します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1648">Change the default value of EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket to TRUE.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="8e8f4-1649">Visio: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1649">Visio: Feature updates</span></span>
- <span data-ttu-id="8e8f4-1650">**ダイアグラムとソースの同期を維持:** Visio でデータ ビジュアライザーのダイアグラムを編集する場合、リンクされた Excel ソース データを最新のダイアグラム コンテンツに更新することができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1650">**Keep your diagram and source in sync:** When you edit a Data Visualizer diagram in Visio, you have the option to update the linked Excel source data with the latest diagram content.</span></span>
- <span data-ttu-id="8e8f4-1651">**データ ビジュアライザー監査テンプレート:** Excel からコンテンツをインポートし、金融取引や在庫管理などの監査図を作成します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1651">**Data Visualizer audit template:** Import content from Excel and create audit diagrams for financial transactions, inventory management, and more.</span></span>
- <span data-ttu-id="8e8f4-1652">**スターター図面:** 組織図、ブレーンストーミング、SDL のテンプレートに新しいダイアグラムが追加され、すばやく開始して実行することができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1652">**Starter diagrams:** The Organization Chart, Brainstorming, and SDL templates have new starter diagrams to get you up and running quickly.</span></span>
 - <span data-ttu-id="8e8f4-p317">**Visio 図形から Word 文書を作成する:** 図形やメタデータなどのダイアグラム コンテンツを Word 文書に自動的に追加します。次にその文書をカスタマイズして、プロセス ガイドラインや操作マニュアルを作成します。[詳細情報](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p317">**Build a Word document out of Visio shapes** Automatically add diagram content, including shapes and metadata, to a Word document. Then customize the document to create process guidelines and operation manuals. [Learn more](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="8e8f4-1656">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1656">Word: Feature updates</span></span>
- <span data-ttu-id="8e8f4-p318">**クラウド ファイルの自動保存が既定で有効になる:** 2018 年 9 月の半期チャネル (対象指定) リリースでは、自動保存が既定で有効になります。これにより、OneDrive または SharePoint Online に保存されるドキュメントで変更が失われることをユーザーは心配する必要がありません。変更はクラウドに自動的に保存されるので、ユーザーは明示的に Ctrl + S キーを押すか、[保存] ボタンをクリックする必要はありません。ただし、ユーザーは、この動作の変更を理解し、プレゼンテーションを誤って変更しないように注意する必要があります。ユーザーは、画面の上部にある [自動保存] トグルを使用して自動保存をオフにできます。この変更についてユーザーに通知し、Office 365 でこの新機能を最大限に利用する方法について説明することをお勧めします。[自動保存の詳細](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5)、IT 管理者が自動保存について知っておくべきことの詳細</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p318">**AutoSave for cloud files is now enabled by default:** AutoSave is enabled by default in the September 2018 Semi-Annual Channel (Targeted) release. This change means users won’t have to worry about losing their changes in documents stored on OneDrive or SharePoint Online. Changes will be saved in the cloud automatically, and users will no longer have to explicitly press Ctrl + S or the Save button. However, they will have to understand this change in behavior so they don’t make accidental changes to presentations. Note that users can turn off AutoSave using the AutoSave toggle at the top of the screen. We recommend that you notify your users about this upcoming change and educate them about how to best take advantage of this new feature in Office 365. [Learn more about AutoSave](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Learn more about what IT admins should know about AutoSave]</span></span>
- <span data-ttu-id="8e8f4-p319">**アクセシビリティ チェックの改善:** アクセシビリティ チェックで、文書のアクセシビリティを向上させるための国際標準と推奨事項のサポートが更新されました。[詳細情報](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p319">**Accessibility Checker improvements:** The Accessibility Checker has updated support for international standards and recommendations to make your documents more accessible. [Learn more](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)</span></span>
- <span data-ttu-id="8e8f4-p320">**SVG サポートの強化:** フィルターが適用された SVG を挿入できます。[詳細情報](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p320">**Improved SVG support:** You can insert SVG's that have filters applied to them. [Learn more](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="8e8f4-1668">Word: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1668">Word: Security updates</span></span>
-   <span data-ttu-id="8e8f4-1669">[CVE-2018-8430](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8430): Windows PDF のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1669">[CVE-2018-8430](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8430): Word PDF Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1670">[CVE-2018-0919](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0919): Microsoft Office の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1670">[CVE-2018-0919](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0919): Microsoft Office Information Disclosure Vulnerability</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="8e8f4-1671">Word: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1671">Word: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1672">メモリ不足を示すメッセージが表示される原因となる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1672">Fix an issue that causes an insufficient memory message to appear.</span></span>
-   <span data-ttu-id="8e8f4-1673">一部のユーザーが他の組織のユーザーと共有していた IRM 保護文書やメールを開くの妨げていた一連の問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1673">Fixed a set of issues that prevented some users from opening IRM-protected documents & emails that were shared with them by people in other organizations.</span></span>
-   <span data-ttu-id="8e8f4-1674">いくつかのパフォーマンスの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1674">Fixed some performance issues.</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="8e8f4-1675">Office スイート: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1675">Office Suite: Security updates</span></span>
-   <span data-ttu-id="8e8f4-1676">[CVE-2018-8332](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8332): Win32k Graphics のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1676">[CVE-2018-8332](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8332): Win32k Graphics Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1677">[CVE-2018-8378](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8378): Microsoft Office の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1677">[CVE-2018-8378](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8378): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1678">[CVE-2018-8281](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8281): Microsoft Office のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1678">[CVE-2018-8281](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8281): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1679">[CVE-2018-8157](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8157): Microsoft Office のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1679">[CVE-2018-8157](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8157): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1680">[CVE-2018-8158](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8158): Microsoft Office のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1680">[CVE-2018-8158](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8158): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1681">[CVE-2018-0950](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0950): Microsoft Office の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1681">[CVE-2018-0950](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0950): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1682">[CVE-2018-1026](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-1026): Microsoft Office のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1682">[CVE-2018-1026](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-1026): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1683">[CVE-2018-1030](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-1030): Microsoft Office のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1683">[CVE-2018-1030](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-1030): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-p321">
  \*\*セキュリティ上の理由から、Office での Flash、Silverlight、および Shockwave のコントロールのアクティブ化がブロックされる:\*\* セキュリティ上の理由から、Windows 上の Microsoft Office for Office 365 の新しいビルドでは、Flash、Silverlight、および Shockwave のコントロールのアクティブ化がブロックされます。詳細については、[こちら](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729)および[こちら](https://support.office.com/en-us/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1?ui=en-US&rs=en-US&ad=US)をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p321">**Flash, Silverlight and Shockwave controls blocked from activating in Office for security reasons:** For security reasons new builds of Microsoft Office for Office 365 on Windows block activation of Flash, Silverlight, and Shockwave controls. Learn more [here](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729) and [here](https://support.office.com/en-us/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1?ui=en-US&rs=en-US&ad=US).</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="8e8f4-1686">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1686">Office Suite: Non-security updates</span></span>
-  <span data-ttu-id="8e8f4-1687">特定のシナリオで更新プログラムのインストールが長くかかる原因となった問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1687">Fixed an issue that caused update install to take a long time in certain scenarios.</span></span>
-  <span data-ttu-id="8e8f4-1688">ユーザーがアプリケーションを開いたときに、セーフ モードでの起動に関するメッセージが表示され、アプリケーションが起動しない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1688">Fix an issue where, when opening an application, the user might see a message about launching in Safe mode and then the application fails to open.</span></span>
-  <span data-ttu-id="8e8f4-1689">いくつかのパフォーマンスの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1689">Fixed some performance issues.</span></span>

## <a name="version-1803-august-14"></a><span data-ttu-id="8e8f4-1690">バージョン 1803: 8 月 14 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1690">Version 1803: August 14</span></span>
<span data-ttu-id="8e8f4-1691">*バージョン 1803 (ビルド 9126.2275)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1691">*Version 1803 (Build 9126.2275)*</span></span>

### <a name="access-security-updates"></a><span data-ttu-id="8e8f4-1692">Access: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1692">Access: Security updates</span></span>
-   <span data-ttu-id="8e8f4-1693">[CVE-2018-8312](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8312): Microsoft Access のリモート コード実行の Use After Free 脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1693">[CVE-2018-8312](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8312): Microsoft Access Remote Code Execution Use After Free Vulnerability</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="8e8f4-1694">Excel: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1694">Excel: Security updates</span></span>
-   <span data-ttu-id="8e8f4-1695">[CVE-2018-8375](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8375): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1695">[CVE-2018-8375](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8375): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="8e8f4-1696">[CVE-2018-8379](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8379): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1696">[CVE-2018-8379](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8379): Microsoft Excel Remote Code Execution Vulnerability</span></span> 
-   <span data-ttu-id="8e8f4-1697">[CVE-2018-8382](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8382): Microsoft Excel の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1697">[CVE-2018-8382](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8382): Microsoft Excel Information Disclosure Vulnerability</span></span> 

### <a name="outlook-security-updates"></a><span data-ttu-id="8e8f4-1698">Outlook: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1698">Outlook: Security updates</span></span>
-   <span data-ttu-id="8e8f4-1699">[ADV180021](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/ADV180021): Microsoft Office の高度な防御の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1699">[ADV180021](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/ADV180021): Microsoft Office Defense in Depth Update</span></span> 

### <a name="office-suite-security-updates"></a><span data-ttu-id="8e8f4-1700">Office スイート: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1700">Office Suite: Security updates</span></span>
-   <span data-ttu-id="8e8f4-1701">[CVE-2018-8378](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8378): Microsoft Office の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1701">[CVE-2018-8378](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8378): Microsoft Office Information Disclosure Vulnerability</span></span> 

## <a name="version-1803-july-10"></a><span data-ttu-id="8e8f4-1702">バージョン 1803: 7 月 10 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1702">Version 1803: July 10</span></span>
<span data-ttu-id="8e8f4-1703">*バージョン 1803 (ビルド 9126.2259)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1703">*Version 1803 (Build 9126.2259)*</span></span>

### <a name="access-security-updates"></a><span data-ttu-id="8e8f4-1704">Access: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1704">Access: Security updates</span></span>
-   <span data-ttu-id="8e8f4-1705">[CVE-2018-8312](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8312): Microsoft Access のリモート コード実行の Use After Free 脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1705">[CVE-2018-8312](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8312): Microsoft Access Remote Code Execution Use After Free Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="8e8f4-1706">Outlook: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1706">Outlook: Security updates</span></span>
-   <span data-ttu-id="8e8f4-1707">[CVE-2018-8310](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8310): Microsoft Office 改ざんの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1707">[CVE-2018-8310](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8310): Microsoft Office Tampering Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="8e8f4-1708">Office スイート: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1708">Office Suite: Security updates</span></span>
-   <span data-ttu-id="8e8f4-1709">[CVE-2018-8281](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8281): Microsoft Office のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1709">[CVE-2018-8281](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8281): Microsoft Office Remote Code Execution Vulnerability</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="8e8f4-1710">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1710">Excel: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1711">日付のセル書式設定で和暦を使用すると、間違った年が表示される問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1711">Fix an issue where the wrong year is shown when Japanese Era calendar is used in date cell format.</span></span>
-   <span data-ttu-id="8e8f4-p322">Excel データ モデルにデータをインポートするとき、負のゼロの値を受け取るとエラーになりました。修正後は、そのような値はゼロとしてインポートされます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p322">When importing data into the Excel Data Model, incoming values of negative zero would result in an error.  The fix imports such values as zero.</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="8e8f4-1714">PowerPoint: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1714">PowerPoint: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1715">太線罫線を使用する表が正しく表示されない問題が修正されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1715">Fixes issue where tables are rendered incorrectly with thick borders.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="8e8f4-1716">Project: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1716">Project: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1717">コスト型リソースでタスクが分割されている場合、コスト型リソースが正しく更新されず、コストが失われるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1717">Fixed an issue where if a task is split with a cost resource, the cost resource isn't correctly updated and the cost is lost.</span></span>
-   <span data-ttu-id="8e8f4-1718">タイムライン ビューで既存のタスクをタイムライン ダイアログに追加すると、最初のサマリー タスクのタスクしか表示されない問題を修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1718">Fixed an issue where in the Timeline view - Add Existing Tasks to the Timeline dialog, only tasks from the first summary task would show up.</span></span>
-   <span data-ttu-id="8e8f4-1719">XML として保存すると、Project Online または Project Server のマスター プロジェクトでエラーが発生するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1719">Fixed an issue where saving as XML may fail for master projects from Project Online or Project Server.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="8e8f4-1720">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1720">Office Suite: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1721">特定のシナリオで更新プログラムのインストールが長くかかる原因となったバグを修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1721">Fix a bug that caused update install to take a long time in certain scenarios.</span></span> 
-   <span data-ttu-id="8e8f4-1722">SVG テストが失敗するという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1722">Fix an issue where SVG tests are failing</span></span>
-   <span data-ttu-id="8e8f4-1723">Office アプリケーションが実行されているクライアントに Configuration Manager を使用して更新プログラムを展開した場合、Office アプリケーションの実行中にデバイスを再起動すると更新プログラムが適用されない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1723">Fix an issue where, when deploying updates using Configuration Manager to a client that has running Office applications the update is not applied after restarting the device while Office applications are running.</span></span>


## <a name="version-1803-june-12"></a><span data-ttu-id="8e8f4-1724">バージョン 1803: 6 月 12 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1724">Version 1803: June 12</span></span>
<span data-ttu-id="8e8f4-1725">*バージョン 1803 (ビルド 9126.2227)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1725">*Version 1803 (Build 9126.2227)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="8e8f4-1726">Excel: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1726">Excel: Security updates</span></span>
-   <span data-ttu-id="8e8f4-1727">[CVE-2018-8246](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8246): Microsoft Excel の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1727">[CVE-2018-8246](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8246): Microsoft Excel Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1728">[CVE-2018-8248](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8248): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1728">[CVE-2018-8248](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8248): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="8e8f4-1729">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1729">Excel: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1730">Excel のピボット テーブルでグループ化 (またはグループ解除) 操作を行うとクラッシュを引き起こす可能性がある問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1730">Fix an issue where a group (or ungroup) operation in an Excel PivotTable could sometimes trigger a crash.</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="8e8f4-1731">Outlook: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1731">Outlook: Security updates</span></span>
-   <span data-ttu-id="8e8f4-1732">[CVE-2018-8244](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8244): Microsoft Outlook 特権の昇格の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1732">[CVE-2018-8244](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8244): Microsoft Outlook Elevation of Privilege Vulnerability</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="8e8f4-1733">PowerPoint: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1733">PowerPoint: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1734">Shape.Visibile プロパティを変更するとクラッシュが発生する可能性がある問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1734">Fix an issue where a potential crash could occur when changing the Shape.Visibile property.</span></span>
-   <span data-ttu-id="8e8f4-1735">共同編集されているドキュメントの変更を反映できない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1735">Fix an issue where changes in co-authored documents fail to merge.</span></span>
-   <span data-ttu-id="8e8f4-1736">ActiveX コントロールを含むドキュメントの共同編集が失敗する原因となる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1736">Fix an issue where documents containing ActiveX controls would cause co-authoring to fail.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="8e8f4-1737">Project: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1737">Project: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1738">タイムライン ビューで既存のタスクをタイムライン ダイアログに追加すると、最初のサマリー タスクのタスクしか表示されない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1738">Fix an issue where in the Timeline view - Add Existing Tasks to the Timeline dialog, only tasks from the first summary task would show up.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="8e8f4-1739">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1739">Office Suite: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1740">Office アプリケーションが実行されているクライアントに Configuration Manager を使用して更新プログラムを展開した場合、Office アプリケーションの実行中にデバイスを再起動すると更新プログラムが適用されない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1740">Fix an issue where, when deploying updates using Configuration Manager to a client that has running Office applications the update is not applied after restarting the device while Office applications are running.</span></span>



## <a name="version-1803-may-18"></a><span data-ttu-id="8e8f4-1741">バージョン 1803: 5 月 18 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1741">Version 1803: May 18</span></span>
<span data-ttu-id="8e8f4-1742">*バージョン 1803 (ビルド 9126.2210)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1742">*Version 1803 (Build 9126.2210)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="8e8f4-1743">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1743">Excel: Non-security updates</span></span>
- <span data-ttu-id="8e8f4-1744">グラフの操作によって Excel がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1744">Fix an issue where charting actions could cause Excel to crash.</span></span>
- <span data-ttu-id="8e8f4-1745">一部のユーザーに対し、Power View のアドインが誤って無効になるの問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1745">Fix an issue where the Power View add-in is inadvertently disabled for some users.</span></span>
- <span data-ttu-id="8e8f4-1746">ドキュメントの回復中に作成された一時的な自動回復ファイルがクリーンアップされないという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1746">Fix an issue where temporary auto-recovery files created during document recovery are never cleaned up.</span></span>
- <span data-ttu-id="8e8f4-1747">保護されたブックでテキスト ファイルに新しい接続を作成しようとすると、「ブックは保護されており、変更できません」というエラー メッセージが出るという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1747">Fix an issue where attempting to make a new connection to a text file in a protected workbook results in getting a "Workbook is protected and cannot be changed" error message.</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="8e8f4-1748">PowerPoint: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1748">PowerPoint: Non-security updates</span></span>
- <span data-ttu-id="8e8f4-1749">図形内でスペルを修正すると PowerPoint がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1749">Fix an issue where spelling correction in shapes causes PowerPoint to crash.</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="8e8f4-1750">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1750">Office suite: Non-security updates</span></span>
- <span data-ttu-id="8e8f4-1751">ユーザーがアプリケーションを開いたときに、セーフ モードでの起動に関するメッセージが表示され、アプリケーションが起動しない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1751">Fix an issue where, when opening an application, the user might see a message about launching in Safe mode and then the application fails to open.</span></span>



## <a name="version-1803-may-8"></a><span data-ttu-id="8e8f4-1752">バージョン 1803: 5 月 8 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1752">Version 1803: May 8</span></span>
<span data-ttu-id="8e8f4-1753">*バージョン 1803 (ビルド 9126.2191)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1753">*Version 1803 (Build 9126.2191)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="8e8f4-1754">Excel: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1754">Excel: Security updates</span></span>
-   <span data-ttu-id="8e8f4-1755">[CVE-2018-8147](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8147): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1755">[CVE-2018-8147](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8147): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1756">[CVE-2018-8148](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8148): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1756">[CVE-2018-8148](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8148): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1757">[CVE-2018-8162](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8162): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1757">[CVE-2018-8162](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8162): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1758">[CVE-2018-8163](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8163): Microsoft Excel の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1758">[CVE-2018-8163](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8163): Microsoft Excel Information Disclosure Vulnerability</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="8e8f4-1759">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1759">Excel: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1760">SharePoint Online からファイルを開くと Excel がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1760">Fix an issue where Excel crashes when opening a file from SharePoint Online.</span></span>
-   <span data-ttu-id="8e8f4-1761">印刷または印刷プレビューで、ワークシートの一部だけが印刷または表示され、ワークシート上のスライサーでコンテンツが切り詰められる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1761">Fix a problem where print or print preview only prints or displays a portion of the worksheet, with the content being truncated at a slicer on the worksheet.</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="8e8f4-1762">Outlook: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1762">Outlook: Security updates</span></span>
-   <span data-ttu-id="8e8f4-1763">[CVE-2018-8150](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8150): Microsoft Outlook のセキュリティ機能のバイパスの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1763">[CVE-2018-8150](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8150): Microsoft Outlook Security Feature Bypass Vulnerability</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="8e8f4-1764">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1764">Outlook: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1765">[送信トレイ] または [送信済みアイテム] フォルダーに切り替えると、Outlook がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1765">Fix an issue where switching to the Outbox or Sent Items folder causes Outlook to crash.</span></span>
-   <span data-ttu-id="8e8f4-1766">会議の本文や添付ファイルを変更すると、会議の更新情報の出席者への送信がオプションになる代わりに、すべての出席者が会議の更新を受信する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1766">Fix an issue where all attendees receive meeting updates when the meeting body or attachments change, instead of sending a meeting update to the attendees being optional.</span></span>
-   <span data-ttu-id="8e8f4-1767">ユーザー エージェント文字列が変更されたために、ユーザーが EWS エンドポイントおよび REST エンドポイントに接続できなくなる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1767">Fix an issue that causes users to be unable to connect to EWS and REST endpoints because of a change in the User-Agent string.</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="8e8f4-1768">PowerPoint: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1768">PowerPoint: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1769">SharePoint Online からファイルを開くと PowerPoint がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1769">Fix an issue where PowerPoint crashes when opening a file from SharePoint Online.</span></span>
-   <span data-ttu-id="8e8f4-1770">自動保存が有効な場合に回復ウィンドウが誤って表示される問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1770">Fix an issue where the Recovery Pane incorrectly appears when AutoSave is on.</span></span>
-   <span data-ttu-id="8e8f4-1771">サインインが表示されないためにユーザーがファイルにアクセスできない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1771">Fix an issue where sign-in isn't shown preventing a user from accessing a file.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="8e8f4-1772">Project: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1772">Project: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1773">日付列のオートフィルター ドロップダウンを使用すると、プロジェクト内のすべてのタスクが非表示になる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1773">Fix an issue where using the AutoFilter dropdown on a date column causes all tasks in the project to be hidden.</span></span>
-   <span data-ttu-id="8e8f4-1774">タイムライン ビューで既存のタスクをタイムラインに追加すると、最初のサマリー タスクのタスクのみがダイアログ ボックスに表示される問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1774">Fix an issue where only tasks from the first summary task show up in the dialog box when adding existing tasks to a timeline when in Timeline view.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="8e8f4-1775">Word: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1775">Word: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1776">SharePoint Online からファイルを開くと Word がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1776">Fix an issue where Word crashes when opening a file from SharePoint Online.</span></span>
-   <span data-ttu-id="8e8f4-1777">小文字のローマ数字ページ番号が誤って大文字に変更される問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1777">Fix an issue where lower-case Roman number page numbers are incorrectly changed to upper case.</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="8e8f4-1778">Office スイート: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1778">Office suite: Security updates</span></span>
-   <span data-ttu-id="8e8f4-1779">[CVE-2018-8157](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8157): Microsoft Office のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1779">[CVE-2018-8157](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8157): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1780">[CVE-2018-8158](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8158): Microsoft Office のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1780">[CVE-2018-8158](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-8158): Microsoft Office Remote Code Execution Vulnerability</span></span>



## <a name="version-1803-april-10"></a><span data-ttu-id="8e8f4-1781">バージョン 1803: 4 月 10 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1781">Version 1803: April 10</span></span>
<span data-ttu-id="8e8f4-1782">*バージョン 1803 (ビルド 9126.2152)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1782">*Version 1803 (Build 9126.2152)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="8e8f4-1783">Excel: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1783">Excel: Security updates</span></span>
-   <span data-ttu-id="8e8f4-1784">[CVE-2018-1029](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-1029): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1784">[CVE-2018-1029](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-1029): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="8e8f4-1785">PowerPoint: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1785">PowerPoint: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1786">複数のユーザーが同じプレゼンテーションを共同編集すると、スライド マスターに正しくない重複が発生する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1786">Fix an issue where multiple users co-authoring on the same presentation results in an incorrect duplication of slides masters.</span></span>
-   <span data-ttu-id="8e8f4-1787">OneDrive に保存されているファイルを開いた際、保護ビューを終了すると PowerPoint がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1787">Fix an issue where opening a file saved on OneDrive results in PowerPoint crashing when exiting Protected View.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="8e8f4-1788">Skype for Business: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1788">Skype for Business: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1789">TLS 1.2 サポートに関連する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1789">Fix an issue related to TLS 1.2 support.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="8e8f4-1790">Word: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1790">Word: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1791">メモリ不足を示すメッセージが表示される原因となる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1791">Fix an issue that causes an insufficient memory message to appear.</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="8e8f4-1792">Office スイート: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1792">Office suite: Security updates</span></span>
-   <span data-ttu-id="8e8f4-1793">[CVE-2018-0950](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0950): Microsoft Office の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1793">[CVE-2018-0950](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0950): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1794">[CVE-2018-1026](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-1026): Microsoft Office のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1794">[CVE-2018-1026](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-1026): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1795">[CVE-2018-1030](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-1030): Microsoft Office のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1795">[CVE-2018-1030](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-1030): Microsoft Office Remote Code Execution Vulnerability</span></span>



## <a name="version-1803-march-20"></a><span data-ttu-id="8e8f4-1796">バージョン 1803: 3 月 20 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1796">Version 1803: March 20</span></span>
<span data-ttu-id="8e8f4-1797">*バージョン 1803 (ビルド 9126.2098)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1797">*Version 1803 (Build 9126.2098)*</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="8e8f4-1798">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1798">Excel: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1799">Outlook メールに添付された Excel ブックのクイック印刷が機能しない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1799">Fix an issue where Quick Print of an Excel workbook attached to an Outlook email may not print.</span></span>
-   <span data-ttu-id="8e8f4-1800">ハイパーリンクをクリックすると Excel がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1800">Fix an issue where clicking on a hyperlink may cause Excel to crash.</span></span>
-   <span data-ttu-id="8e8f4-1801">キューブ関数を使用すると、Excel がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1801">Fix an issue where using cube functions causes Excel to crash.</span></span>

### <a name="onedrive-for-business-non-security-updates"></a><span data-ttu-id="8e8f4-1802">OneDrive for Business: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1802">OneDrive for Business: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1803">延長期間にタスク マネージャーで OneDrive for Business (Groove.exe) が 1 つの CPU コアの CPU の価値を消費する (4 コア CPU の 25% など) 問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1803">Fix an issue where OneDrive for Business (Groove.exe) consumes one CPU core’s worth of CPU (for example, 25% on a 4 core CPU) in Task Manager for extended periods of time.</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="8e8f4-1804">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1804">Outlook: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1805">出席者に対する会議場所の更新に、新しい場所ではなく、古い場所が表示される問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1805">Fix an issue where a meeting location update to attendees shows the old location instead of the new location.</span></span>
-   <span data-ttu-id="8e8f4-1806">ユーザーが閲覧ウィンドウで添付ファイルをプレビューすると、エラーが表示される問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1806">Fix an issue where the user sees an error when previewing an attachment in the reading pane.</span></span>
-   <span data-ttu-id="8e8f4-1807">ユーザーが電子メールを作成中に、表示名が電子メール アドレスに解決されると、Outlook がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1807">Fix an issue where Outlook crashes when resolving display names to email addresses when the user is composing an email.</span></span>
-   <span data-ttu-id="8e8f4-1808">一部のユーザーがテナント管理者によって有効にされたサポート機能を受信しない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1808">Fix an issue where some users don't receive support features that have been enabled by their tenant admin.</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="8e8f4-1809">Word: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1809">Word: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1810">カスタマ－ エクスペリエンスと診断テレメトリに関する更新プログラムがインストールされていない、Windows 7 を [実行しているコンピューターで Word が開かない問題を](https://support.microsoft.com/help/3080149/update-for-customer-experience-and-diagnostic-telemetry)修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1810">Fix an issue where Word won’t open on a computer running Windows 7 that doesn't have the [update for customer experience and diagnostic telemetry](https://support.microsoft.com/help/3080149/update-for-customer-experience-and-diagnostic-telemetry) installed.</span></span>
-   <span data-ttu-id="8e8f4-1811">リスト内の行頭文字が印刷されない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1811">Fix an issue where bullets in lists don’t print.</span></span>



## <a name="version-1803-march-13"></a><span data-ttu-id="8e8f4-1812">バージョン 1803: 3 月 13 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1812">Version 1803: March 13</span></span>
<span data-ttu-id="8e8f4-1813">*バージョン 1803 (ビルド 9126.2072)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1813">*Version 1803 (Build 9126.2072)*</span></span>

### <a name="access-security-updates"></a><span data-ttu-id="8e8f4-1814">Access: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1814">Access: Security updates</span></span>
-   <span data-ttu-id="8e8f4-1815">[CVE-2018-0903](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0903): Microsoft Access のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1815">[CVE-2018-0903](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0903): Microsoft Access Remote Code Execution Vulnerability</span></span>

### <a name="access-non-security-updates"></a><span data-ttu-id="8e8f4-1816">Access: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1816">Access: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1817">Access ランタイム アプリケーション (.accde ファイル) を開くと、"データベースの形式を認識できません" というエラー メッセージが表示され、アプリケーションが開かない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1817">Fix an issue where opening an Access runtime application (.accde file) results in a "This database is in an unrecognized format" error message and the application won’t open.</span></span>
-   <span data-ttu-id="8e8f4-1818">テキスト ボックスまたはコンボ ボックスでテキストを選択しようとすると、指示されたものが選択されるのではなく、すべてのテキストが選択されるという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1818">Fix an issue where attempting to select text in a text box or combo box appears to select all the text, rather than the indication selection.</span></span>

### <a name="excel-feature-updates"></a><span data-ttu-id="8e8f4-1819">Excel: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1819">Excel: Feature updates</span></span>
-   <span data-ttu-id="8e8f4-p323">**Microsoft Translator:** Microsoft Translator を使用して、単語、フレーズ、または文章を別の言語に翻訳します。これは、リボンの [校閲] タブから実行できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p323">**Microsoft Translator:** Translate words, phrases or sentences to another language with Microsoft Translator. You can do this from the Review tab in the ribbon.</span></span>
-   <span data-ttu-id="8e8f4-1822">**SVG アイコンを図形に変換する:** すべての SVG の画像とアイコンを Office の図形に変換して、色、サイズ、テクスチャを変更できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1822">**Convert SVG icons to shapes:** Transform all SVG pictures and icons into Office shapes so you can change their color, size, or texture.</span></span>
-   <span data-ttu-id="8e8f4-1823">**セルを選択解除する:** ワークシートで選択を行い、間違ってクリックしたセルを選択解除します。最初からやり直す必要はありません。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1823">**Deselect cells:** Make selections in your worksheet and deselect cells that you accidentally clicked without having to start over.</span></span>
-   <span data-ttu-id="8e8f4-1824">**サイトおよびグループへすばやくアクセス:**[ファイル] メニューを使用して、よく使用するサイトやグループに格納されているドキュメントを操作できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1824">**Quickly access your sites and groups:** Use the File menu to work with documents stored in your frequently used sites and groups.</span></span>
-   <span data-ttu-id="8e8f4-p324">**デジタル鉛筆:** 新しい鉛筆のテクスチャで、アイデアを書き込んだり、スケッチしたりします。サポートされているデジタル ペンを傾けるだけで網かけができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p324">**Digital Pencil:** Write or sketch out ideas with our new pencil texture. Simply tilt to do shading with supported digital pens.</span></span>
-   <span data-ttu-id="8e8f4-p325">**LinkedIn 機能の設定:** [ファイル] \> [オプション] \> [全般] と移動して、Office アプリケーションで LinkedIn 機能が表示されるかどうかを制御します。[詳細情報](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p325">**LinkedIn features setting:** Go to File \> Options \> General to control whether LinkedIn features are shown in your Office applications. [Learn more](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span></span>
-   <span data-ttu-id="8e8f4-p326">**3D モデル:** 3D を使用して、ブックを、より視覚的かつ独創的なものにすることができます。3D モデルの挿入も簡単で、360 度回転させることができます。 [詳細情報](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p326">**3D models:** Use 3D to increase the visual and creative impact of your workbooks.  Easily insert a 3D model, then you can rotate it through 360 degrees. [Learn more](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span></span>
-   <span data-ttu-id="8e8f4-1832">**新しいインク効果:** メタリック ペンを使用し、ゴールド、シルバーあるいは虹、銀河、溶岩、海などを連想させる色などのインクの効果を活用して、アイデアの表現の幅を広めましょう。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1832">**New ink effects:** Express your ideas with flair using metallic pens and ink effects like rainbow, galaxy, lava, ocean, gold, silver and more.</span></span>
-   <span data-ttu-id="8e8f4-p327">**ファイル共有 UI:** OneDrive for Business または SharePoint のファイルの場合、リボンの右上隅にある [共有] ボタンをクリック、または [ファイル] \> [共有] の順に移動することにより、簡略化され改良された [共有] ダイアログが起動されます。新規のファイル、またはローカルに保存されたファイルの場合、この UI によって、ユーザーはファイルを OneDrive に簡単にアップロードし、共同作業を開始できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p327">**Sharing files UI:** For OneDrive for Business or SharePoint files, clicking the Share button in the upper right-hand corner of the ribbon or going to File \> Share launches a simplified and improved Share dialog. For new or locally-saved files, the UI allows users to easily upload their files to OneDrive to start collaborating.</span></span>
-   <span data-ttu-id="8e8f4-p328">**危険な拡張子をブロック:** リスクが高いとみなされ、OLE パッケージ オブジェクトとして埋め込まれている拡張子は、既定ではアクティブ化されないようにブロックされています。たとえば、.exe、.vbs、.js などがこれに該当します。[詳細情報](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p328">**Block dangerous extensions:** Extensions that are considered to be high risk, and are embedded as OLE package objects, are blocked, by default, from activating. For example, .exe, .vbs, and .js. [Learn more](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span></span>
-   <span data-ttu-id="8e8f4-p329">**アクセシビリティを向上させるのに役に立つサウンド:** 音声キューを有効にすると、作業中に操作を指示してもらうことができます。[ファイル] \> [オプション] \> [簡単操作] の順に選択すると見つかります。アドインは必要ありません。 [詳細情報](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p329">**Helpful sounds improve accessibility:** Turn on audio cues to guide you as you work. Find it in File \> Options \> Ease of Access. No add-in needed. [Learn more](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span></span>
-   <span data-ttu-id="8e8f4-1842">**アカウントごとのファイルの場所:** ファイルを開くときや保存する場合、場所のリストは、その場所に関連付けられたアカウントによって整理されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1842">**File locations by account:** When opening or saving a file, the list of places is organized by the account associated with them.</span></span>
-   <span data-ttu-id="8e8f4-p330">**ペンのカスタマイズ:** 手描き入力についてペンと蛍光ペンの個人用設定を選択します。カスタマイズした設定は、お使いのすべての Windows PC でご利用いただけます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p330">**Pen customization:** Choose a personal set of pens and highlighters for inking. Your customized set is available on all your Windows PCs.</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="8e8f4-1845">Excel: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1845">Excel: Security updates</span></span>
-   <span data-ttu-id="8e8f4-1846">[CVE-2017-11877](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2017-11877): Microsoft Excel のセキュリティ機能のバイパスの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1846">[CVE-2017-11877](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2017-11877): Microsoft Excel Security Feature Bypass Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1847">[CVE-2017-11878](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2017-11878): Microsoft Excel のメモリ破損の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1847">[CVE-2017-11878](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2017-11878): Microsoft Excel Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1848">[CVE-2017-11884](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2017-11884): Microsoft Office のメモリ破損の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1848">[CVE-2017-11884](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2017-11884): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1849">[CVE-2018-0796](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0796): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1849">[CVE-2018-0796](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0796): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1850">[CVE-2018-0841](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0841): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1850">[CVE-2018-0841](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0841): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1851">[CVE-2018-0907](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0907): Microsoft Office Excel のセキュリティ機能のバイパス</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1851">[CVE-2018-0907](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0907): Microsoft Office Excel Security Feature Bypass</span></span>
-   <span data-ttu-id="8e8f4-1852">[アドバイザリ 170021](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/ADV170021): Microsoft Office 多層防御の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1852">[Advisory 170021](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/ADV170021): Microsoft Office Defense in Depth Update</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="8e8f4-1853">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1853">Excel: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1854">Excel で、編集の言語が日本語、中国語、韓国語のいずれかの場合に、[ホーム] タブで新しいフォントを選ぼうとしたり、編集したりするときにフリーズするという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1854">Fix an issue where, if your editing language is Japanese, Chinese, or Korean, Excel may freeze when you try to choose a new font on the Home tab or when you edit.</span></span>
-   <span data-ttu-id="8e8f4-1855">Excel が最小化されているときにブックを開くとスクロールバーが表示されない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1855">Fix an issue where the scroll bars are missing when a workbook is opened when Excel is minimized.</span></span>
-   <span data-ttu-id="8e8f4-1856">ファイル エクスプローラーでファイル名をダブルクリックして複数のブックを開くときに、ブックの参照が失敗する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1856">Fix an issue where workbook references fail when opening multiple workbooks by double-clicking on the file names in File Explorer.</span></span>
-   <span data-ttu-id="8e8f4-1857">ピボットテーブルのプログラムによる作成の後にプログラムによる更新が行われると、Excel がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1857">Fix an issue where the programmatic creation of a PivotTable followed by a programmatic refresh causes Excel to crash.</span></span>
-   <span data-ttu-id="8e8f4-1858">プログラムで Workbook.Open() を呼び出すと、Excel がクラッシュする可能性がある問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1858">Fix an issue where programmatically calling Workbook.Open() may cause Excel to crash.</span></span>
-   <span data-ttu-id="8e8f4-1859">ユーザーが、マクロを含む Office 2007 以前のブック (.xls または .xla) を開くと、"致命的なエラー" のエラー メッセージが誤って表示される問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1859">Fix an issue where the user incorrectly sees a "catastrophic failure" error message when opening an Office 2007 or older workbook (.xls or .xla) with macros.</span></span>
-   <span data-ttu-id="8e8f4-1860">ユーザーがコンテキスト メニューを開くときに Excel がクラッシュする可能性がある問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1860">Fix an issue where Excel might crash when a user opens a context menu.</span></span>
-   <span data-ttu-id="8e8f4-1861">ユーザーが既存のブックにオブジェクトを挿入しようとする場合に [参照] をクリックすると、Excel がクラッシュするという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1861">Fix an issue where, when the user tries to insert an object in an existing workbook, Excel crashes when the user clicks Browse.</span></span>
-   <span data-ttu-id="8e8f4-1862">範囲をパスワードで保護している場合に、範囲のロックを解除するパスワードを入力するダイアログ ボックスが表示されない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1862">Fix an issue where, when protecting a range with a password, the dialog box to enter the password to unlock the range isn't visible.</span></span>
-   <span data-ttu-id="8e8f4-1863">ファイル名に角かっこが含まれている場合に、ユーザーが保護ビューでブックを閉じることができない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1863">Fix an issue where the user can't close a workbook in protected view when the file name contains square brackets.</span></span>
-   <span data-ttu-id="8e8f4-1864">ドラッグまたはドラッグ フィルを実行するとヒントの配置がずれる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1864">Fix an issue where placement of the tooltip is misaligned when dragging or drag filling.</span></span>
-   <span data-ttu-id="8e8f4-1865">[ファイル] \> [名前をつけて保存] を使用してブックを保存するときに、ピリオドを含むファイル名がファイル保存ダイアログで空白になるか切り詰められて見える問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1865">Fix an issue where, when saving a workbook by using File \> Save As, a file name that contains periods appears blank or truncated in the file save dialog.</span></span>
-   <span data-ttu-id="8e8f4-p331">同期し直したファイルを保存するときに、Office でディスクへの書き込みが失敗しても、OneDrive へのファイルのアップロードは続行されるという問題を修正します。この修正により、ユーザーにエラー メッセージが表示され、アップロードが続行されなくなります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p331">Fix an issue where, when saving a sync-backed file, Office fails to write to disk, but Office keeps uploading the file to OneDrive. With this fix, user will now see an error message and the upload won't proceed.</span></span>

### <a name="outlook-feature-updates"></a><span data-ttu-id="8e8f4-1868">Outlook: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1868">Outlook: Feature updates</span></span>
-   <span data-ttu-id="8e8f4-1869">**簡単にメールを並べ替える:** フィードバックにお答えし、メッセージ一覧の上に並べ替えを戻し、優先受信トレイを使用していないユーザーのために未読フィルターを戻しました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1869">**Sort your email with ease:** Thanks to your feedback, we've brought back sorting above the message list and the Unread filter for people who don't use Focused Inbox.</span></span>
-   <span data-ttu-id="8e8f4-1870">**SVG アイコンを図形に変換する:** すべての SVG の画像とアイコンを Office の図形に変換して、色、サイズ、テクスチャを変更できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1870">**Convert SVG icons to shapes:** Transform all SVG pictures and icons into Office shapes so you can change their color, size, or texture.</span></span>
-   <span data-ttu-id="8e8f4-1871">**Office 365 グループの機能強化:** グループ メッセージをダブルクリックして、独自のウィンドウで開くことができるので、これまで以上にグループ会話を読んで返信することが簡単になりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1871">**Improvements to Office 365 groups:** It’s easier than ever to read and reply to group conversations because you can double-click on a group message to open it in its own window.</span></span>
-   <span data-ttu-id="8e8f4-p332">**LinkedIn 機能の設定:** [ファイル] \> [オプション] \> [全般] と移動して、Office アプリケーションで LinkedIn 機能が表示されるかどうかを制御します。[詳細情報](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p332">**LinkedIn features setting:** Go to File \> Options \> General to control whether LinkedIn features are shown in your Office applications. [Learn more](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span></span>
-   <span data-ttu-id="8e8f4-p333">**3D モデル:** 3D を使用して、電子メールを、より視覚的かつ独創的なものにすることができます。3D モデルの挿入も簡単で、360 度回転させることができます。 [詳細情報](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p333">**3D models:** Use 3D to increase the visual and creative impact of your email.  Easily insert a 3D model, then you can rotate it through 360 degrees. [Learn more](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span></span>
-   <span data-ttu-id="8e8f4-1877">**プロファイル カード:** デスクトップ、Web、モバイル アプリのいずれかを使用している場合でも、ユーザーとグループに関する最も関連性の高い詳細を表示します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1877">**Profile card:** Shows you the most relevant details about people and groups, whether you’re on the desktop, the web, or using a mobile app.</span></span>
-   <span data-ttu-id="8e8f4-1878">**グループ予定表への予定の追加:** グループ内のメンバー全員に、メールで会議を送信せずに、会議の欠席について知らせることができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1878">**Add an appointment to a group calendar:** Now you can let everyone in your group know when you’ll be away without sending a meeting in email.</span></span>
-   <span data-ttu-id="8e8f4-1879">**クラウド添付ファイルのダウンロード:** OneDrive の添付ファイルをコンピューターに保存またはドラッグ アンド ドロップすると、ファイルがダウンロードされます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1879">**Downloading cloud attachments:** When you save or drag and drop OneDrive attachments to your computer, we download the file for you.</span></span>
-   <span data-ttu-id="8e8f4-p334">**アクセシビリティを向上させるのに役に立つサウンド:** 音声キューを有効にすると、作業中に操作を指示してもらうことができます。[ファイル] \> [オプション] \> [簡単操作] の順に選択すると見つかります。アドインは必要ありません。 [詳細情報](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p334">**Helpful sounds improve accessibility:** Turn on audio cues to guide you as you work. Find it in File \> Options \> Ease of Access. No add-in needed. [Learn more](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span></span>
-   <span data-ttu-id="8e8f4-p335">**優先受信トレイ:** 受信トレイは、[優先] と [その他] の 2 つのタブに分かれています。メッセージの分類は、メッセージの内容と、一番やりとりの多い相手がだれかに基づいて行われます。 [詳細情報](https://support.office.com/article/f445ad7f-02f4-4294-a82e-71d8964e3978)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p335">**Focused Inbox:** The Inbox is separated into two tabs – Focused and Other. Messages are sorted based on the content of the message and who you interact with most often. [Learn more](https://support.office.com/article/f445ad7f-02f4-4294-a82e-71d8964e3978)</span></span>
-   <span data-ttu-id="8e8f4-1887">**最も頻繁に使用するグループにすばやくアクセスする:** 一番やりとりの多いグループが、[フォルダー] ウィンドウの [グループ] のリストの先頭に表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1887">**Quickly access the groups you use most:** Groups you're most likely to interact with now appear at the top of the list under Groups in the Folder pane.</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="8e8f4-1888">Outlook: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1888">Outlook: Security updates</span></span>
-   <span data-ttu-id="8e8f4-1889">[CVE-2017-11939](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2017-11939): Microsoft Office の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1889">[CVE-2017-11939](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2017-11939): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1890">[CVE-2018-0791](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0791): Microsoft Outlook のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1890">[CVE-2018-0791](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0791): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1891">[CVE-2018-0793](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1891">[CVE-2018-0793](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1892">[CVE-2018-0850](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0850): Microsoft Outlook 特権の昇格の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1892">[CVE-2018-0850](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0850): Microsoft Outlook Elevation of Privilege Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-1893">[CVE-2018-0852](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0852): Microsoft Outlook のメモリ破損の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1893">[CVE-2018-0852](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0852): Microsoft Outlook Memory Corruption Vulnerability</span></span>

### <a name="outlook-non-security-updates"></a><span data-ttu-id="8e8f4-1894">Outlook: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1894">Outlook: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1895">検索範囲がすべてのメールボックスの場合、「一致する項目が見つかりませんでした」と表示されて検索できない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1895">Fix an issue where search fails with “No matches found” when search is scoped to All Mailboxes.</span></span>
-   <span data-ttu-id="8e8f4-1896">Accessible Event Watcher (AccEvent.exe) を使用して監視する場合に、フォルダーを切り替えたときに Outlook がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1896">Fix an issue where, when monitoring using Accessible Event Watcher (AccEvent.exe), Outlook crashes when switching folders.</span></span>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="8e8f4-1897">PowerPoint: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1897">PowerPoint: Feature updates</span></span>
-   <span data-ttu-id="8e8f4-p336">**Microsoft Translator:** Microsoft Translator を使用して、単語、フレーズ、または文章を別の言語に翻訳します。これは、リボンの [校閲] タブから実行できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p336">**Microsoft Translator:** Translate words, phrases or sentences to another language with Microsoft Translator. You can do this from the Review tab in the ribbon.</span></span>
-   <span data-ttu-id="8e8f4-1900">**3D アニメーション:** 優しく揺らしたり、ジャンプして回転させたりするなど、アニメーションを使用して 3D モデルを生き生きとしたものにできます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1900">**3D animations:** Bring your 3D models to life with animations such as swinging gently or jumping and turning.</span></span>
-   <span data-ttu-id="8e8f4-1901">**SVG アイコンを図形に変換する:** すべての SVG の画像とアイコンを Office の図形に変換して、色、サイズ、テクスチャを変更できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1901">**Convert SVG icons to shapes:** Transform all SVG pictures and icons into Office shapes so you can change their color, size, or texture.</span></span>
-   <span data-ttu-id="8e8f4-1902">**リビジョン進捗管理情報のローミング:** 他のユーザーによって変更された共有スライドを強調表示するための既読/未読のステータスは、この情報を複数のデバイスまたはプラットフォームで同期できるように、ローミング サービス (ユーザーのローカル コンピューターではない) に保存されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1902">**Roaming of revision tracking info:** The read/unread status for highlighting shared slides that have been modified by others is now stored in a roaming service (instead of on the user's local computer) so that this information can be synchronized across multiple devices or platforms.</span></span>
-   <span data-ttu-id="8e8f4-1903">**サイトおよびグループへすばやくアクセス:**[ファイル] メニューを使用して、よく使用するサイトやグループに格納されているドキュメントを操作できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1903">**Quickly access your sites and groups:** Use the File menu to work with documents stored in your frequently used sites and groups.</span></span>
-   <span data-ttu-id="8e8f4-p337">**デジタル鉛筆:** 新しい鉛筆のテクスチャで、アイデアを書き込んだり、スケッチしたりします。サポートされているデジタル ペンを傾けるだけで網かけができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p337">**Digital Pencil:** Write or sketch out ideas with our new pencil texture. Simply tilt to do shading with supported digital pens.</span></span>
-   <span data-ttu-id="8e8f4-p338">**LinkedIn 機能の設定:** [ファイル] \> [オプション] \> [全般] と移動して、Office アプリケーションで LinkedIn 機能が表示されるかどうかを制御します。[詳細情報](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p338">**LinkedIn features setting:** Go to File \> Options \> General to control whether LinkedIn features are shown in your Office applications. [Learn more](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span></span>
-   <span data-ttu-id="8e8f4-p339">**デジタル ペンを使用してスライド ショーを実行します:** Surface ペン、または Bluetooth ボタンのあるその他のペンを使用し、高度なスライドを作成しましょう。Windows 10 Fall Creators Update が必要です。 [詳細情報](https://support.office.com/article/e36da834-7d34-4b71-aafd-071727549f7a)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p339">**Run a slide show with your digital pen:** Use your Surface Pen, or other pen with a Bluetooth button, to advance your slides. Windows 10 Fall Creators Update is required. [Learn more](https://support.office.com/article/e36da834-7d34-4b71-aafd-071727549f7a)</span></span>
-   <span data-ttu-id="8e8f4-p340">**3D モデル:** 3D を使用して、プレゼンテーションを、より視覚的かつ独創的なものにすることができます。スライド間で映画のようなアニメーションを生み出す画面切り替え効果を生かして、3D モデルをプレゼンテーションで活用しましょう。 [詳細情報](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p340">**3D models:** Use 3D to increase the visual and creative impact of your presentations. Bring 3D models to life in your presentations with transitions like Morph that create cinematic animations between slides. [Learn more](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span></span>
-   <span data-ttu-id="8e8f4-1914">**新しいインク効果:** メタリック ペンを使用し、ゴールド、シルバーあるいは虹、銀河、溶岩、海などを連想させる色などのインクの効果を活用して、アイデアの表現の幅を広めましょう。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1914">**New ink effects:** Express your ideas with flair using metallic pens and ink effects like rainbow, galaxy, lava, ocean, gold, silver and more.</span></span>
-   <span data-ttu-id="8e8f4-p341">**ファイル共有 UI:** OneDrive for Business または SharePoint のファイルの場合、リボンの右上隅にある [共有] ボタンをクリック、または [ファイル] \> [共有] の順に移動することにより、簡略化され改良された [共有] ダイアログが起動されます。新規のファイル、またはローカルに保存されたファイルの場合、この UI によって、ユーザーはファイルを OneDrive に簡単にアップロードし、共同作業を開始できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p341">**Sharing files UI:** For OneDrive for Business or SharePoint files, clicking the Share button in the upper right-hand corner of the ribbon or going to File \> Share launches a simplified and improved Share dialog. For new or locally-saved files, the UI allows users to easily upload their files to OneDrive to start collaborating.</span></span>
-   <span data-ttu-id="8e8f4-p342">**危険な拡張子をブロック:** リスクが高いとみなされ、OLE パッケージ オブジェクトとして埋め込まれている拡張子は、既定ではアクティブ化されないようにブロックされています。たとえば、.exe、.vbs、.js などがこれに該当します。[詳細情報](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p342">**Block dangerous extensions:** Extensions that are considered to be high risk, and are embedded as OLE package objects, are blocked, by default, from activating. For example, .exe, .vbs, and .js. [Learn more](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span></span>
-   <span data-ttu-id="8e8f4-1920">**リビジョンの強調表示:** 他のユーザーによって変更されたスライドが強調表示されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1920">**Revision highlighting:** Slides that have been modified by other users are highlighted.</span></span>
-   <span data-ttu-id="8e8f4-1921">**最近の変更:** PowerPoint は、共有のプレゼンテーションへの前回のアクセス以降、だれが編集したか表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1921">**While you were away:** PowerPoint shows you who edited your shared presentation since your last visit.</span></span>
-   <span data-ttu-id="8e8f4-1922">**デザイナーの機能強化:** デザイナーで、タイムラインのお勧めのデザイン アイデアが箇条書きで提案されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1922">**Designer improvement:** Designer now recommends design ideas for timelines in a bulleted list.</span></span>
-   <span data-ttu-id="8e8f4-p343">**アクセシビリティを向上させるのに役に立つサウンド:** 音声キューを有効にすると、作業中に操作を指示してもらうことができます。[ファイル] \> [オプション] \> [簡単操作] の順に選択すると見つかります。アドインは必要ありません。 [詳細情報](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p343">**Helpful sounds improve accessibility:** Turn on audio cues to guide you as you work. Find it in File \> Options \> Ease of Access. No add-in needed. [Learn more](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span></span>
-   <span data-ttu-id="8e8f4-1927">**アカウントごとのファイルの場所:** ファイルを開くときや保存する場合、場所のリストは、その場所に関連付けられたアカウントによって整理されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1927">**File locations by account:** When opening or saving a file, the list of places is organized by the account associated with them.</span></span>
-   <span data-ttu-id="8e8f4-p344">**ペンのカスタマイズ:** 手描き入力についてペンと蛍光ペンの個人用設定を選択します。カスタマイズした設定は、お使いのすべての Windows PC でご利用いただけます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p344">**Pen customization:** Choose a personal set of pens and highlighters for inking. Your customized set is available on all your Windows PCs.</span></span>
-   <span data-ttu-id="8e8f4-1930">**デザイナーの機能強化:** デザイナーが、スライドに追加されたグラフのデザイン アイデアを提案するようになりました。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1930">**Designer improvement:** Designer now recommends design ideas for charts added to your slides.</span></span>
-   <span data-ttu-id="8e8f4-p345">**QuickStarter:** アウトラインを自動的に作成し、ユーザーの選択対象に対して調査を開始できるようにします。[詳細情報](https://support.office.com/article/4784f273-0b2c-456c-9c89-24e5b977c224)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p345">**QuickStarter:** Automatically builds an outline to help users get started researching a subject of their choosing. [Learn more](https://support.office.com/article/4784f273-0b2c-456c-9c89-24e5b977c224)</span></span>
-   <span data-ttu-id="8e8f4-p346">**デジタル ルーラー:** タッチ スクリーンを備えたデバイスで、[描画] \> [ルーラー] の順に移動し、ペンや指で直線を描画したり、オブジェクトのセットを配置したりできます。 [詳細情報](https://support.office.com/article/6222c9b4-2fdf-48f7-a3fd-1687fbe2bf84)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p346">**Digital ruler:** On devices that have touch screens, go to Draw \> Ruler, then use your pen or finger to draw straight lines or to align a set of objects. [Learn more](https://support.office.com/article/6222c9b4-2fdf-48f7-a3fd-1687fbe2bf84)</span></span>

### <a name="powerpoint-security-updates"></a><span data-ttu-id="8e8f4-1935">PowerPoint: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1935">PowerPoint: Security updates</span></span>
-   <span data-ttu-id="8e8f4-1936">[CVE-2017-11934](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2017-11934): Microsoft PowerPoint の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1936">[CVE-2017-11934](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2017-11934): Microsoft PowerPoint Information Disclosure Vulnerability</span></span>

### <a name="powerpoint-non-security-updates"></a><span data-ttu-id="8e8f4-1937">PowerPoint: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1937">PowerPoint: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1938">ドキュメント プロパティと個人情報を削除すると、SharePoint への保存が失敗する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1938">Fix an issue where removing document properties and personal information causes saving to SharePoint to fail.</span></span>
-   <span data-ttu-id="8e8f4-p347">Flash Player ベースの YouTube 埋め込みコードを参照すると、新しいウィンドウが開いて動画が再生される問題を修正します。現在、古い埋め込みコードは HTML5 ベースの YouTube 動画を参照するようにアップグレードされており、正しく再生されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p347">Fix an issue where references to Flash Player based YouTube embed codes result in a new window opening to play the video. Old embed codes are now upgraded to reference HTML5 based YouTube videos so that they correctly play in place.</span></span>
-   <span data-ttu-id="8e8f4-p348">同期し直したファイルを保存するときに、Office でディスクへの書き込みが失敗しても、OneDrive へのファイルのアップロードは続行されるという問題を修正します。この修正により、ユーザーにエラー メッセージが表示され、アップロードが続行されなくなります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p348">Fix an issue where, when saving a sync-backed file, Office fails to write to disk, but Office keeps uploading the file to OneDrive. With this fix, user will now see an error message and the upload won't proceed.</span></span>

### <a name="project-feature-updates"></a><span data-ttu-id="8e8f4-1943">Project: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1943">Project: Feature updates</span></span>
-   <span data-ttu-id="8e8f4-p349">**タスク ボード ビュー:** タスク ボード ビューでカードのタスクを並べ替えます。アジャイル プロジェクトと同様に、カードを並べ替え、ボード上の列の間で移動させます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p349">**Task Board view:** Sort tasks on cards in the Task Board view. Reorder and move cards between columns on the board just like in Agile projects.</span></span>
-   <span data-ttu-id="8e8f4-p350">**アジャイル プロジェクト:** バックログ、タスク ボード、スプリントなどを使用して、アジャイル プロジェクトを管理します。スクラムまたはかんばんの両方の方法論がサポートされています。[詳細情報](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p350">**Agile projects:** Manage your Agile projects using backlogs, task boards, sprints, and more. Both Scrum or Kanban methodologies are supported. [Learn more](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)</span></span>  
-   <span data-ttu-id="8e8f4-p351">**Planner でのタスクの管理:** Planner にプロジェクト タスクをリンクし、計画を作成します。タスクをサブタスクに分割し、チームを追加し、タスクを割り当て、タスク ボード上で作業を管理します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p351">**Manage a task in Planner:** Link a Project task to Planner and create a plan for it. Break the task into subtasks, add a team, assign tasks, and manage the work on a task board.</span></span>

### <a name="project-non-security-updates"></a><span data-ttu-id="8e8f4-1951">Project: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1951">Project: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1952">あるセッションで複数のベースラインを設定すると、MOD\_DATE の値が同じになるという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1952">Fix an issue where setting more than one baseline in a session sets the MOD\_DATE value as the same.</span></span>
-   <span data-ttu-id="8e8f4-1953">[共有用に保存] セッションで実績作業時間が削除された後にも、実績作業時間がレポート テーブルに表示されるという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1953">Fix an issue where Actual Work is still shown in the reporting tables after being removed in a Save for Sharing session.</span></span>
-   <span data-ttu-id="8e8f4-1954">スケジュール設定するときに週の日付形式を使用するとエラーが返されるというドイツ語での問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1954">Fix an issue in the German language version where using a Weeks date format returns an error when scheduling.</span></span>
-   <span data-ttu-id="8e8f4-1955">スケジュール Web パーツで終了日を編集すると、タスクが時間範囲で配分されるのではなく、1 日に 8 時間ずつ割り当てられるという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1955">Fix an issue where, when editing finish dates in Schedule Web Part, tasks stay at 8 hours per day instead of being spread over time.</span></span>
-   <span data-ttu-id="8e8f4-1956">"進捗点の形状" が予期しない場所に描画されるという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1956">Fix an issue where "Progress point shape" is drawn at an unexpected location.</span></span>
-   <span data-ttu-id="8e8f4-1957">VBA コードがプロジェクトから失われる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1957">Fix an issue where VBA code gets lost from projects.</span></span>
-   <span data-ttu-id="8e8f4-1958">残存作業時間がある場合でも、タスクが終了と表示される問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1958">Fix an issue where tasks show as complete even when there is remaining work.</span></span>
-   <span data-ttu-id="8e8f4-1959">タスク パス機能を使用しているときに Project が停止する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1959">Fix an issue where Project hangs when using the Task Path feature.</span></span>
-   <span data-ttu-id="8e8f4-1960">タイムスケールにタイムスケールのラベルが表示されない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1960">Fix an issue where the timescale doesn't show the timescale labels.</span></span>
-   <span data-ttu-id="8e8f4-1961">ビジュアル レポートが不完全な情報を表示するか、完全に失敗する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1961">Fix an issue where visual reports show incomplete information or fail completely.</span></span>
-   <span data-ttu-id="8e8f4-1962">保存に失敗するとファイルが破損して Project を開くときにクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1962">Fix an issue where a failed save can corrupt a file and cause Project to crash on open.</span></span>
-   <span data-ttu-id="8e8f4-1963">タイムラインとチーム プランナー ビューでタスクをドラッグできない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1963">Fix an issue where you can't drag tasks in the Timeline and Team Planner view.</span></span>
-   <span data-ttu-id="8e8f4-1964">Team Builder でリソースの可用性が表示されない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1964">Fix an issue where resource availability isn't shown in Team Builder.</span></span>
-   <span data-ttu-id="8e8f4-1965">マークが正しく表示されない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1965">Fix an issue where graphical indicators aren't displaying correctly.</span></span>
-   <span data-ttu-id="8e8f4-1966">時間単位または日単位で平準化している間に Project が停止する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1966">Fix an issue where Project hangs while leveling on hour-by-hour or day-by-day basis.</span></span>
-   <span data-ttu-id="8e8f4-1967">SharePoint ドキュメント ライブラリからマスター/サブ プロジェクトを操作する際の問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1967">Fix an issue for working with master/sub projects from a SharePoint Document library.</span></span>
-   <span data-ttu-id="8e8f4-1968">期間固定のタスクに割り当てを追加したときに、名前のないリソースになる可能性がある問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1968">Fix an issue where, when you add assignments to a fixed duration task, you may end up with a nameless resource.</span></span>
-   <span data-ttu-id="8e8f4-1969">保護された作業での変更について、誤ったエラー メッセージが生成される問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1969">Fix an issue that produces an incorrect error message of change on protected work.</span></span>
-   <span data-ttu-id="8e8f4-1970">いくつかの画像を含むレポートに移動すると Project がクラッシュする可能性がある問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1970">Fix an issue where Project might crash when going to reports that contain several images.</span></span>

### <a name="publisher-feature-updates"></a><span data-ttu-id="8e8f4-1971">Publisher: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1971">Publisher: Feature updates</span></span>
-   <span data-ttu-id="8e8f4-p352">**危険な拡張子をブロック:** リスクが高いとみなされ、OLE パッケージ オブジェクトとして埋め込まれている拡張子は、既定ではアクティブ化されないようにブロックされています。たとえば、.exe、.vbs、.js などがこれに該当します。[詳細情報](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p352">**Block dangerous extensions:** Extensions that are considered to be high risk, and are embedded as OLE package objects, are blocked, by default, from activating. For example, .exe, .vbs, and .js. [Learn more](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span></span>

### <a name="publisher-non-security-updates"></a><span data-ttu-id="8e8f4-1975">Publisher: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1975">Publisher: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1976">差し込み印刷ウィザードを実行しているときに、Null (空) 値を含むデータ ソース フィールドでのフィルター処理が失敗する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1976">Fix an issue where filtering on data source fields containing null (empty) values fails when running the Mail Merge wizard.</span></span>

### <a name="skype-for-business-non-security-updates"></a><span data-ttu-id="8e8f4-1977">Skype for Business: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1977">Skype for Business: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-1978">会議で [Skype 通話] を選択してユーザーを追加するとエラーが発生する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1978">Fix an issue where adding users by selecting 'Skype Call' in a meeting causes an error.</span></span>
-   <span data-ttu-id="8e8f4-1979">Skype Room が場所として追加され、会議に既にチーム会議の座標が含まれている場合、会議に Skype 座標を追加するかどうかを確認するユーザー プロンプトを削除します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1979">Remove prompt asking user to add Skype coordinates to a meeting, if a Skype Room is added as the location and the meeting already contains Teams meeting coordinates.</span></span>
-   <span data-ttu-id="8e8f4-1980">UseLocationForE911Only が true に設定されている場合でも、場所が設定されるという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1980">Fix an issue where location is populated even when UseLocationForE911Only is set to true.</span></span>
-   <span data-ttu-id="8e8f4-1981">"会議センターを使用して通話する" オプションを使用して参加者一覧にあるユーザーを招待する際に、Skype for Business が停止する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1981">Fix an issue where Skype for Business hangs when using the "call using conference center" option to invite users from the roster.</span></span>
-   <span data-ttu-id="8e8f4-1982">Skype for Business 会議の作成中に、ターミナル サーバー上で動作している Outlook がフリーズする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1982">Fix an issue where Outlook running on terminal server freezes while creating a Skype for Business meeting.</span></span>
-   <span data-ttu-id="8e8f4-1983">EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket の既定値を TRUE に変更します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1983">Change the default value of EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket to TRUE.</span></span>
-   <span data-ttu-id="8e8f4-1984">会議が全画面表示モードの場合に [その他のオプション] ボタンと [さらに参加者を招待] ボタンが非表示になる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1984">Fix an issue where "More Options" and "Invite More People" buttons are hidden when a meeting is in full-screen mode.</span></span>
-   <span data-ttu-id="8e8f4-1985">P2P 音声通話ウィンドウまたは電話会議ウィンドウが、参加しようとすると透明になるという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1985">Fix an issue where the P2P audio call window or conference call window becomes transparent when you attempt to join.</span></span>
-   <span data-ttu-id="8e8f4-1986">近日開催される Skype 会議が [会議] タブに表示されない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1986">Fix an issue where upcoming Skype meetings do not show up in the meetings tab.</span></span>
-   <span data-ttu-id="8e8f4-1987">Skype for Business が音声なしの状態で会議に参加するよう構成されている場合、会議に音声を追加しようとすると、既存の会議に音声が追加されるのではなく、自分自身への新たな P2P 通話が開始される問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1987">Fix an issue where, when Skype for Business is configured to join meetings without audio, adding audio to a meeting initiates a new P2P call to the user itself rather than adding audio to the existing meeting.</span></span>
-   <span data-ttu-id="8e8f4-1988">Outlook から会議出席依頼の [Skype 会議への参加] リンクをクリックすると、「この Skype 会議が見つかりませんでした」というエラー メッセージが表示される問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1988">Fix an issue where user receives the error message "We couldn't find this Skype meeting" when clicking 'Join Skype Meeting' link in a meeting request from Outlook.</span></span>
-   <span data-ttu-id="8e8f4-1989">着信の PSTN 呼び出しのトースト UI に通話の転送ボタンを追加します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1989">Add call transfer button in the toast UI for incoming PSTN calls.</span></span>
-   <span data-ttu-id="8e8f4-1990">ChatDefaultClient と CallDefaultClient がチームに設定されているとき、通話とチャットがチームに送信されていることをユーザーに通知します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1990">Notify users that calls and chat are being sent to Teams when ChatDefaultClient and CallDefaultClient are set to Teams.</span></span>
-   <span data-ttu-id="8e8f4-1991">会議に参加しておらず、Skype for Business で無効になっており、会議参加エクスペリエンスが [Native Limited Client] に設定されているユーザーの場合、ユーザーのプレゼンスは [オフライン] と表示されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1991">Show user's presence as Offline when user is not in a meeting and disabled from Skype for Business and meeting join experience is set to Native Limited Client.</span></span>
-   <span data-ttu-id="8e8f4-1992">Skype for Business が通知エリアに最小化されているときに、[開く] および [終了] 以外のすべてのオプションを無効にします。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1992">Disable all options except Open and Exit when Skype for Business is minimized to the notification area.</span></span>
-   <span data-ttu-id="8e8f4-1993">Aries の電話と RedirectClient とのペアリングが有効である場合、新しい通話と会話を表示しません。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1993">Suppress new calls and conversations when paired with Aries phones and RedirectClient is enabled.</span></span>
-   <span data-ttu-id="8e8f4-1994">日付形式が US 形式 (mm/dd/yy) 以外の場合、日付を使った PChat のメッセージの検索が失敗する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1994">Fix an issue where searching messages in PChat by date fails when the date format is other than US format (mm/dd/yy).</span></span>
-   <span data-ttu-id="8e8f4-1995">EnableExternalP2PFileTransfer ポリシーが false に設定されている場合でも、ユーザーが引き続き会議にファイルを添付できる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1995">Fix an issue where, when EnableExternalP2PFileTransfer policy is set to false, users are still able to attach files in meetings.</span></span>
-   <span data-ttu-id="8e8f4-p353">会話履歴で、呼び出し先ではなく呼び出し元が表示される問題を修正します。これは、Active Directory を使用して呼び出し先の勤務先番号が変更された場合に発生します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p353">Fix an issue where, in Conversation History, the caller is shown instead of the called person. This happens when the called person's work number is modified using Active Directory.</span></span>
-   <span data-ttu-id="8e8f4-1998">携帯電話番号に PSTN 通話を発信するときに、会話履歴内の通話履歴に受信者情報が表示されない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1998">Fix an issue where, for outgoing PSTN calls to mobile numbers, recipient information is missing in the call history in conversation history.</span></span>
-   <span data-ttu-id="8e8f4-1999">Outlook の電子メールから IM を開始するときに、電子メールの件名が IM の件名に含まれない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-1999">Fix an issue where, when initiating an IM from an email in Outlook, the subject line of the email is not included in the subject of the IM.</span></span>
-   <span data-ttu-id="8e8f4-2000">IM の会話ウィンドウが片面にスナップされると、会話が二重にスタックされて表示される問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2000">Fix an issue where, when IM conversation windows are snapped to one side, conversations appear double stacked.</span></span>
-   <span data-ttu-id="8e8f4-2001">VDIv2 環境で、VbSS 画面共有要求が RDP ベースの要求として表示される問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2001">Fix an issue where, in a VDIv2 environment, VbSS screen sharing requests appear as RDP-based requests.</span></span>
-   <span data-ttu-id="8e8f4-2002">通話転送が失敗したときに、失敗通知に、不在の受信者ではなく呼び出し元が表示される問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2002">Fix an issue where, in a failed call transfer, the caller is listed in the failure notification, instead of the missed recipient.</span></span>
-   <span data-ttu-id="8e8f4-2003">クライアント アップグレード リダイレクト バナー内で [Teams の使用を開始] ボタンが表示されない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2003">Fix an issue where the "Start using Teams" button is hidden within the client upgrade redirect banner.</span></span>
-   <span data-ttu-id="8e8f4-2004">IM ウィンドウの DPI スケールの問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2004">Fix DPI scaling issues in IM windows.</span></span>
-   <span data-ttu-id="8e8f4-2005">LinkedIn データが Skype for Business 連絡先カードに表示されない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2005">Fix an issue where LinkedIn data does not appear in the Skype for Business Contact Card.</span></span>
-   <span data-ttu-id="8e8f4-2006">ユーザーがハント グループの代わりに通話の受信を停止する機能を追加します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2006">Add the ability for users to stop receiving calls on behalf of a hunt group.</span></span>
-   <span data-ttu-id="8e8f4-2007">Skype for Business または Teams で通話中に、新たな通話を受信または開始したときに、通話を自動的に保留する機能を追加します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2007">Add the ability to automatically hold calls when a call is active in Skype for Business or Teams and a new call is received or initiated.</span></span>
-   <span data-ttu-id="8e8f4-2008">全画面共有後に、ユーザーが IM を使用できなくなる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2008">Fix an issue where users are unable to IM after full screen sharing.</span></span>
-   <span data-ttu-id="8e8f4-2009">ロビーにいるユーザーが会議に参加することを拒否されたときに、通知されないという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2009">Fix an issue where users in the lobby aren't notified when they're denied from entering the meeting.</span></span>
-   <span data-ttu-id="8e8f4-2010">通話中に自動ゲイン制御が次第に制御できなくなる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2010">Fix an issue where automatic gain control increases uncontrollably during calls.</span></span>
-   <span data-ttu-id="8e8f4-2011">会議の招待に会議室のリソース メールボックスを追加すると、ユーザーが会議のオプションで発表者を選択できなくなる問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2011">Fix an issue where users are unable to select a presenter in Meeting Options when a conference room resource mailbox is added to a meeting invite.</span></span>
-   <span data-ttu-id="8e8f4-2012">AllowlPVideo が False に設定されているとピアツーピアのビデオ通話中にデスクトップの共有ボタンが淡色表示される問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2012">Fix an issue where the desktop sharing button is dimmed during a peer-to-peer video call if AllowlPVideo is set to False.</span></span>
-   <span data-ttu-id="8e8f4-2013">[IM を無効にする] の設定で作成した既存の会議について会議のオプション設定を [IM を有効にする] に変更しても、IM が無効のままである問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2013">Fix an issue where IM stays disabled after changing the Meeting Option setting to Enable IM for existing meetings created with Disable IM.</span></span>
-   <span data-ttu-id="8e8f4-2014">チャット ウィンドウで [リンクの挿入] ボタンの上にカーソルを置くとヒントが表示されない問題と、ボタンを選択したときにアクセシビリティ名がない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2014">Fix an issue where the tooltip isn't shown when hovering over the "Insert Link" button in the chat window, and there isn't an accessibility name when the button is selected.</span></span>

### <a name="visio-feature-updates"></a><span data-ttu-id="8e8f4-2015">Visio: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2015">Visio: Feature updates</span></span>
-   <span data-ttu-id="8e8f4-p354">**組み込みのデータベース モデル図:** 新しいデータベース モデルのテンプレートを使用して、データベースを Visio 図面として正確にモデル化します。アドインは必要ありません。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p354">**Built-in database model diagrams:** Use the new Database Model Diagram template to accurately model your database as a Visio diagram. No add-in required.</span></span>
-   <span data-ttu-id="8e8f4-2018">**ビジネス用ダイアグラムのその他のステンシル:** 現代的な図形を使用して、データをベン図表と比較対照したり、循環、マトリックス、ピラミッド型図表を描いたりして、考えをわかりやすく伝えることができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2018">**More stencils for business diagrams:** Using modern shapes, compare and contrast data with a Venn diagram, or draw Cycle, Matrix, or Pyramid diagrams to help tell your story.</span></span>
-   <span data-ttu-id="8e8f4-p355">**Web サイトのワイヤーフレーム図の作成:** インターフェイス、ナビゲーション、それらの連携方法を含む Web サイトのワイヤーフレーム図を速やかに作成します。 [詳細情報](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p355">**Create a wireframe diagram for a website:** Quickly create a wireframe diagram of a website including interface, navigation, and how they work together. [Learn more](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)</span></span>
-   <span data-ttu-id="8e8f4-p356">**モバイル アプリケーションのワイヤーフレームの作成:** テンプレートを使用して、モバイル アプリケーションのワイヤーフレームを作成します。[詳細情報](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p356">**Create a wireframe of your mobile application:** Use a template to create a wireframe of your mobile application. [Learn more](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)</span></span>
-   <span data-ttu-id="8e8f4-p357">**データ ビジュアライザーの図にデータ グラフィックが適用されます。** 図形データをデータ グラフィックとして自動的に適用してデータ ビジュアライザーの図を作成し、時間を節約しましょう。 [詳細情報](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6?#apply_dg)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p357">**Apply data graphics to Data Visualizer diagrams:** Save time when you create a Data Visualizer diagram by automatically applying shape data as data graphics. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6?#apply_dg)</span></span>
-   <span data-ttu-id="8e8f4-p358">**描画の共同作業:** OneDrive for Business または SharePoint Online で描画を共有して、他のユーザーと同時に作業します。誰が描画しているかを確認したり、コメントを追加したり、ファイル アクティビティを確認したりできます。 [詳細情報](https://support.office.com/article/413c0b5a-0d52-4ace-af85-8b9bf115bbbf)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p358">**Collaborate on drawings:** Work with others by sharing your drawings on OneDrive for Business or SharePoint Online. You can see who is working on the drawing, add comments, and see file activity. [Learn more](https://support.office.com/article/413c0b5a-0d52-4ace-af85-8b9bf115bbbf)</span></span>
-   <span data-ttu-id="8e8f4-p359">**危険な拡張子をブロック:** リスクが高いとみなされ、OLE パッケージ オブジェクトとして埋め込まれている拡張子は、既定ではアクティブ化されないようにブロックされています。たとえば、.exe、.vbs、.js などがこれに該当します。[詳細情報](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p359">**Block dangerous extensions:** Extensions that are considered to be high risk, and are embedded as OLE package objects, are blocked, by default, from activating. For example, .exe, .vbs, and .js. [Learn more](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span></span>

### <a name="word-feature-updates"></a><span data-ttu-id="8e8f4-2031">Word: 機能の更新</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2031">Word: Feature updates</span></span>
-   <span data-ttu-id="8e8f4-2032">**SVG アイコンを図形に変換する:** すべての SVG の画像とアイコンを Office の図形に変換して、色、サイズ、テクスチャを変更できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2032">**Convert SVG icons to shapes:** Transform all SVG pictures and icons into Office shapes so you can change their color, size, or texture.</span></span>
-   <span data-ttu-id="8e8f4-p360">**文字数:** 入力時にステータス バーに文字数を表示します。カスタマイズ ステータス バー メニューから、これを有効にできます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p360">**Character count:** Display the character count on the status bar as you type. You can enable this from the Customize Status Bar menu.</span></span>
-   <span data-ttu-id="8e8f4-2035">**サイトおよびグループへすばやくアクセス:** [ファイル] メニューを使用して、よく使用するサイトやグループに格納されているドキュメントを操作できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2035">**Quickly access your sites and groups:** Use the File menu to work with documents stored in your frequently used sites and groups.</span></span>
-   <span data-ttu-id="8e8f4-p361">**Microsoft Translator:** Word で Microsoft Translator を使用して、単語、語句、ドキュメント全体を別の言語に翻訳します。[詳細情報](https://support.office.com/article/24a987b3-03a1-4c17-8c1b-54495fca6b17)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p361">**Microsoft Translator:** Translate words, phrases, or the whole document into another language using Microsoft Translator, right in Word. [Learn more](https://support.office.com/article/24a987b3-03a1-4c17-8c1b-54495fca6b17)</span></span>
-   <span data-ttu-id="8e8f4-p362">**デジタル鉛筆:** 新しい鉛筆のテクスチャで、アイデアを書き込んだり、スケッチしたりします。サポートされているデジタル ペンを傾けるだけで網かけができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p362">**Digital Pencil:** Write or sketch out ideas with our new pencil texture. Simply tilt to do shading with supported digital pens.</span></span>
-   <span data-ttu-id="8e8f4-p363">**LinkedIn 機能の設定:** [ファイル] \> [オプション] \> [全般] と移動して、Office アプリケーションで LinkedIn 機能が表示されるかどうかを制御します。[詳細情報](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p363">**LinkedIn features setting:** Go to File \> Options \> General to control whether LinkedIn features are shown in your Office applications. [Learn more](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)</span></span>
-   <span data-ttu-id="8e8f4-p364">**SharePoint プロパティ パネル:** ドキュメント内で SharePoint ドキュメント ライブラリ列の値を表示し、編集します。[表示] タブのリボン ボタンからパネルに簡単にアクセスが可能で、SharePoint 管理者はドキュメント ライブラリの設定を使用して [プロパティ] パネルを自動的に開くことができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p364">**SharePoint property panel:** Display and edit SharePoint document library column values from within a document. A ribbon button on the View tab provides easy access to the panel and SharePoint admins can use a document library setting to automatically open the property panel.</span></span>
-   <span data-ttu-id="8e8f4-p365">**3D モデル:** 3D を使用して、ドキュメントを、より視覚的かつ独創的なものにすることができます。3D モデルの挿入も簡単で、360 度回転させることができます。 [詳細情報](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p365">**3D models:** Use 3D to increase the visual and creative impact of your documents.  Easily insert a 3D model, then you can rotate it through 360 degrees. [Learn more](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)</span></span>
-   <span data-ttu-id="8e8f4-2047">**新しいインク効果:** メタリック ペンを使用し、ゴールド、シルバーあるいは虹、銀河、溶岩、海などを連想させる色などのインクの効果を活用して、アイデアの表現の幅を広めましょう。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2047">**New ink effects:** Express your ideas with flair using metallic pens and ink effects like rainbow, galaxy, lava, ocean, gold, silver and more.</span></span>
-   <span data-ttu-id="8e8f4-p366">**ファイル共有 UI:** OneDrive for Business または SharePoint のファイルの場合、リボンの右上隅にある [共有] ボタンをクリック、または [ファイル] \> [共有] の順に移動することにより、簡略化され改良された [共有] ダイアログが起動されます。新規のファイル、またはローカルに保存されたファイルの場合、この UI によって、ユーザーはファイルを OneDrive に簡単にアップロードし、共同作業を開始できます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p366">**Sharing files UI:** For OneDrive for Business or SharePoint files, clicking the Share button in the upper right-hand corner of the ribbon or going to File \> Share launches a simplified and improved Share dialog. For new or locally-saved files, the UI allows users to easily upload their files to OneDrive to start collaborating.</span></span>
-   <span data-ttu-id="8e8f4-p367">**危険な拡張子をブロック:** リスクが高いとみなされ、OLE パッケージ オブジェクトとして埋め込まれている拡張子は、既定ではアクティブ化されないようにブロックされています。たとえば、.exe、.vbs、.js などがこれに該当します。[詳細情報](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p367">**Block dangerous extensions:** Extensions that are considered to be high risk, and are embedded as OLE package objects, are blocked, by default, from activating. For example, .exe, .vbs, and .js. [Learn more](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)</span></span>
-   <span data-ttu-id="8e8f4-p368">**学習ツールを使用した編集:** Word の Web レイアウトで学習ツールを使用できるようになりました。テキストの間隔を調整し、編集時に音節を表示します。任意のビューで、文書が読み上げられるときに単語が強調表示されていることを確認してください。 [詳細情報](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p368">**Edit using Learning Tools:** Learning Tools is now available in Word's Web Layout. Adjust your text spacing and show syllables while you edit. In any view, see each word highlighted as the document is read aloud. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>
-   <span data-ttu-id="8e8f4-2057">**LaTeX 構文:** LaTeX 構文を使用して数式を作成および編集します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2057">**LaTeX syntax:** Create and edit math equations using LaTeX syntax.</span></span>
-   <span data-ttu-id="8e8f4-p369">**アクセシビリティを向上させるのに役に立つサウンド:** 音声キューを有効にすると、作業中に操作を指示してもらうことができます。[ファイル] \> [オプション] \> [簡単操作] の順に選択すると見つかります。アドインは必要ありません。 [詳細情報](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p369">**Helpful sounds improve accessibility:** Turn on audio cues to guide you as you work. Find it in File \> Options \> Ease of Access. No add-in needed. [Learn more](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)</span></span>
-   <span data-ttu-id="8e8f4-2062">**アカウントごとのファイルの場所:** ファイルを開くときや保存する場合、場所のリストは、その場所に関連付けられたアカウントによって整理されます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2062">**File locations by account:** When opening or saving a file, the list of places is organized by the account associated with them.</span></span>
-   <span data-ttu-id="8e8f4-p370">**ペンのカスタマイズ:** 手描き入力についてペンと蛍光ペンの個人用設定を選択します。カスタマイズした設定は、お使いのすべての Windows PC でご利用いただけます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p370">**Pen customization:** Choose a personal set of pens and highlighters for inking. Your customized set is available on all your Windows PCs.</span></span>
-   <span data-ttu-id="8e8f4-p371">**強化された [エディター] ウィンドウでの文書作成支援:** [エディター] ウィンドウは、高度なスペル チェック、文章校正、文章のスタイルの推奨に使用します。支援技術の高度なサポートにより、アクセスできるように作成されています。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p371">**Enhanced writing assistance with Editor pane:** Use the Editor pane for advanced spelling, grammar and writing style recommendations. It’s built to be accessible with improved support for assistive technologies.</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="8e8f4-2067">Word: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2067">Word: Security updates</span></span>
-   <span data-ttu-id="8e8f4-2068">[CVE-2018-0792](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0792): Microsoft Word のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2068">[CVE-2018-0792](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0792): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2069">[CVE-2018-0793](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2069">[CVE-2018-0793](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2070">[CVE-2018-0794](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0794): Microsoft Word のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2070">[CVE-2018-0794](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0794): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2071">[CVE-2018-0798](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0798): Microsoft Office のメモリ破損の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2071">[CVE-2018-0798](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0798): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2072">[CVE-2018-0801](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0801): Microsoft Office のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2072">[CVE-2018-0801](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0801): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2073">[CVE-2018-0802](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0802): Microsoft Office のメモリ破損の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2073">[CVE-2018-0802](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0802): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2074">[CVE-2018-0804](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0804): Microsoft Word のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2074">[CVE-2018-0804](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0804): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2075">[CVE-2018-0805](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0805): Microsoft Word のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2075">[CVE-2018-0805](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0805): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2076">[CVE-2018-0806](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0806): Microsoft Word のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2076">[CVE-2018-0806](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0806): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2077">[CVE-2018-0807](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0807): Microsoft Word のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2077">[CVE-2018-0807](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0807): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2078">[CVE-2018-0812](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0812): Microsoft Word のメモリ破損の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2078">[CVE-2018-0812](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0812): Microsoft Word Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2079">[CVE-2018-0919](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0919): Microsoft Office の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2079">[CVE-2018-0919](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0919): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2080">[アドバイザリ 170020](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/ADV170020): Microsoft Office 多層防御の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2080">[Advisory 170020](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/ADV170020): Microsoft Office Defense in Depth Update</span></span>

### <a name="word-non-security-updates"></a><span data-ttu-id="8e8f4-2081">Word: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2081">Word: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-2082">ユーザーが OneDrive for Business で既存のドキュメントに対して [名前をつけて保存] をしようとしてから、その保存をキャンセルするか、既存の変更をマージしようすると Word がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2082">Fix an issue where Word crashes when a user tries to do a Save As to an existing document on OneDrive for Business and then cancels the save or tries to merge existing changes.</span></span>
-   <span data-ttu-id="8e8f4-2083">差し込み印刷ウィザードを実行しているときに、Null (空) 値を含むデータ ソース フィールドでのフィルター処理が失敗する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2083">Fix an issue where filtering on data source fields containing null (empty) values fails when running the Mail Merge wizard.</span></span>
-   <span data-ttu-id="8e8f4-p372">同期し直したファイルを保存するときに、Office でディスクへの書き込みが失敗しても、OneDrive へのファイルのアップロードは続行されるという問題を修正します。この修正により、ユーザーにエラー メッセージが表示され、アップロードが続行されなくなります。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-p372">Fix an issue where, when saving a sync-backed file, Office fails to write to disk, but Office keeps uploading the file to OneDrive. With this fix, user will now see an error message and the upload won't proceed.</span></span>
-   <span data-ttu-id="8e8f4-2086">ドキュメントで IRM 保護を削除しても保護が削除されない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2086">Fix an issue where removing IRM protection on a document doesn’t remove the protection.</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="8e8f4-2087">Office スイート: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2087">Office suite: Security updates</span></span>
-   <span data-ttu-id="8e8f4-2088">[CVE-2017-11882](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2017-11882): Microsoft Office のメモリ破損の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2088">[CVE-2017-11882](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2017-11882): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2089">[CVE-2018-0795](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0795): Microsoft Office のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2089">[CVE-2018-0795](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0795): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2090">[CVE-2018-0851](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0851): Microsoft Office のメモリ破損の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2090">[CVE-2018-0851](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0851): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2091">[CVE-2018-0853](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0853): Microsoft Office の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2091">[CVE-2018-0853](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0853): Microsoft Office Information Disclosure Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2092">[アドバイザリ 180003](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/ADV180003): Microsoft Office 多層防御の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2092">[Advisory 180003](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/ADV180003): Microsoft Office Defense in Depth Update</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="8e8f4-2093">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2093">Office suite: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-2094">ユーザーがアプリケーションを開いたときに、セーフ モードでの起動に関するメッセージが表示され、アプリケーションが起動しない問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2094">Fix an issue where, when opening an application, the user might see a message about launching in Safe mode and then the application fails to open.</span></span>
-   <span data-ttu-id="8e8f4-2095">Office 365 クライアントの更新が Configuration Manager によって管理されるように、Office COM オブジェクトが有効になっている場合は、[ファイル] \> [アカウント] \> [更新オプション] で [今すぐ更新] オプションが非表示になっています。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2095">The Update Now option is hidden from File \> Account \> Update Options when an Office COM object is enabled so that Office 365 client updates are managed by Configuration Manager.</span></span>
-   <span data-ttu-id="8e8f4-2096">ユーザーが [Office ライセンス認証] ダイアログ ボックスを使用して Office のライセンス認証をしようとすると、Office アプリがクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2096">Fix an issue where the Office app crashes when the user tries to activate Office using the Activate Office dialog box.</span></span>
-   <span data-ttu-id="8e8f4-2097">動的 DPI 環境下における Office アドインのズームとスケーリングに関する問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2097">Fix an issue with zooming and scaling in Office Add-ins under dynamic DPI environment.</span></span>
-   <span data-ttu-id="8e8f4-2098">Office 365 ProPlus が現在インストールされている場合でも、Office 構成サービス プロバイダー (CSP) の CurrentStatus ノードが空の文字列を返す問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2098">Fix an issue where the CurrentStatus node of the Office configuration service provider (CSP) returns an empty string even if Office 365 ProPlus is currently installed.</span></span>
-   <span data-ttu-id="8e8f4-2099">.box ファイルが同じコンピューターの Office アプリのすべてのバージョンで共有されるために、box ファイルの形式の変更を引き起こし、その変更が同じコンピューターにインストールされている古いバージョンの Office の機能に影響を与える問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2099">Fix an issue that causes .box file format changes, which impacts functionality of older versions of Office installed on the same computer, because .box files are shared across all versions of an Office app on the same computer.</span></span>



## <a name="version-1708-february-13"></a><span data-ttu-id="8e8f4-2100">バージョン 1708: 2 月 13 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2100">Version 1708: February 13</span></span>
<span data-ttu-id="8e8f4-2101">*バージョン 1708 (ビルド 8431.2215)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2101">*Version 1708 (Build 8431.2215)*</span></span>

### <a name="access-non-security-updates"></a><span data-ttu-id="8e8f4-2102">Access: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2102">Access: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-2103">複数の項目のフォームを使って、マウス ホイールまたはスクロールバーのつまみを調整してもフォームに表示される項目が変化しないという問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2103">Fix an issue where, when using a multiple items form, adjusting the position of the mouse wheel or the scrollbar thumb doesn't change the items that are displayed in the form.</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="8e8f4-2104">Excel: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2104">Excel: Security updates</span></span>
-   <span data-ttu-id="8e8f4-2105">[CVE-2018-0841](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0841): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2105">[CVE-2018-0841](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0841): Microsoft Excel Remote Code Execution Vulnerability</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="8e8f4-2106">Outlook: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2106">Outlook: Security updates</span></span>
-   <span data-ttu-id="8e8f4-2107">[CVE-2018-0850](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0850): Microsoft Outlook 特権の昇格の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2107">[CVE-2018-0850](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0850): Microsoft Outlook Elevation of Privilege Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2108">[CVE-2018-0852](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0852): Microsoft Outlook のメモリ破損の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2108">[CVE-2018-0852](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0852): Microsoft Outlook Memory Corruption Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="8e8f4-2109">Office スイート: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2109">Office suite: Security updates</span></span>
-   <span data-ttu-id="8e8f4-2110">[CVE-2018-0851](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0851): Microsoft Office のメモリ破損の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2110">[CVE-2018-0851](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0851): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2111">[CVE-2018-0853](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0853): Microsoft Office の情報漏えいの脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2111">[CVE-2018-0853](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0853): Microsoft Office Information Disclosure Vulnerability</span></span>



## <a name="version-1708-january-9"></a><span data-ttu-id="8e8f4-2112">バージョン 1708: 1 月 9 日</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2112">Version 1708: January 9</span></span>
<span data-ttu-id="8e8f4-2113">*バージョン 1708 (ビルド 8431.2153)*</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2113">*Version 1708 (Build 8431.2153)*</span></span>

### <a name="excel-security-updates"></a><span data-ttu-id="8e8f4-2114">Excel: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2114">Excel: Security updates</span></span>
-   <span data-ttu-id="8e8f4-2115">[CVE-2018-0796](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0796): Microsoft Excel のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2115">[CVE-2018-0796](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0796): Microsoft Excel Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2116">[アドバイザリ 170021](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/ADV170021): Microsoft Office 多層防御の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2116">[Advisory 170021](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/ADV170021): Microsoft Office Defense in Depth Update</span></span>

### <a name="excel-non-security-updates"></a><span data-ttu-id="8e8f4-2117">Excel: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2117">Excel: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-2118">ピボットテーブルのプログラムによる作成の後にプログラムによる更新が行われると、Excel がクラッシュする問題を修正します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2118">Fix an issue where the programmatic creation of a PivotTable followed by a programmatic refresh causes Excel to crash.</span></span>

### <a name="outlook-security-updates"></a><span data-ttu-id="8e8f4-2119">Outlook: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2119">Outlook: Security updates</span></span>
-   <span data-ttu-id="8e8f4-2120">[CVE-2018-0791](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0791): Microsoft Outlook のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2120">[CVE-2018-0791](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0791): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2121">[CVE-2018-0793](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2121">[CVE-2018-0793](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook Remote Code Execution Vulnerability</span></span>

### <a name="word-security-updates"></a><span data-ttu-id="8e8f4-2122">Word: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2122">Word: Security updates</span></span>
-   <span data-ttu-id="8e8f4-2123">[CVE-2018-0792](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0792): Microsoft Word のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2123">[CVE-2018-0792](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0792): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2124">[CVE-2018-0793](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2124">[CVE-2018-0793](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2125">[CVE-2018-0794](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0794): Microsoft Word のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2125">[CVE-2018-0794](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0794): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2126">[CVE-2018-0798](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0798): Microsoft Office のメモリ破損の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2126">[CVE-2018-0798](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0798): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2127">[CVE-2018-0801](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0801): Microsoft Office のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2127">[CVE-2018-0801](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0801): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2128">[CVE-2018-0802](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0802): Microsoft Office のメモリ破損の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2128">[CVE-2018-0802](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0802): Microsoft Office Memory Corruption Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2129">[CVE-2018-0804](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0804): Microsoft Word のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2129">[CVE-2018-0804](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0804): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2130">[CVE-2018-0805](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0805): Microsoft Word のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2130">[CVE-2018-0805](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0805): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2131">[CVE-2018-0806](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0806): Microsoft Word のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2131">[CVE-2018-0806](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0806): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2132">[CVE-2018-0807](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0807): Microsoft Word のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2132">[CVE-2018-0807](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0807): Microsoft Word Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2133">[CVE-2018-0812](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0812): Microsoft Word のメモリ破損の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2133">[CVE-2018-0812](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0812): Microsoft Word Memory Corruption Vulnerability</span></span>

### <a name="office-suite-security-updates"></a><span data-ttu-id="8e8f4-2134">Office スイート: セキュリティ更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2134">Office suite: Security updates</span></span>
-   <span data-ttu-id="8e8f4-2135">[CVE-2018-0795](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0795): Microsoft Office のリモート コード実行の脆弱性</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2135">[CVE-2018-0795](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/CVE-2018-0795): Microsoft Office Remote Code Execution Vulnerability</span></span>
-   <span data-ttu-id="8e8f4-2136">[アドバイザリ 180003](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/ADV180003): Microsoft Office 多層防御の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2136">[Advisory 180003](https://portal.msrc.microsoft.com/ja-JP/security-guidance/advisory/ADV180003): Microsoft Office Defense in Depth Update</span></span>

### <a name="office-suite-non-security-updates"></a><span data-ttu-id="8e8f4-2137">Office スイート: セキュリティ以外の更新プログラム</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2137">Office suite: Non-security updates</span></span>
-   <span data-ttu-id="8e8f4-2138">ID がオンプレミスの Active Directory とフェデレーションされている Office 365 Germany プランのドメイン ユーザーに、シングル サインオン (SSO) のサポートを追加します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2138">Add support for single sign-on (SSO) for domain users for Office 365 Germany plans where the identity is federated with an on-premises Active Directory.</span></span>
-   <span data-ttu-id="8e8f4-2139">Office ストアから入手する Office アドインを、未成年者が取得してアクティブ化することを防止する機能を追加します。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2139">Add functionality to prevent minors from acquiring and activating Office Add-ins that come from the Office Store.</span></span>


> [!NOTE]
> <span data-ttu-id="8e8f4-2140">Office の使用で問題がある場合は、[Microsoft の回答フォーラム](https://answers.microsoft.com/)に関するページまたは「[Microsoft Tech Community](https://techcommunity.microsoft.com/)」に質問を投稿するか、[サポート](https://support.microsoft.com/contactus)に問い合わせてサポートを受けることができます。</span><span class="sxs-lookup"><span data-stu-id="8e8f4-2140">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
