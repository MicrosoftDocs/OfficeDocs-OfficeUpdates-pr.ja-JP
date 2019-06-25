---
title: Office Insider のリリース ノート
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.date: 6/21/2019
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Insider Fast の対象ユーザーに主な新機能、修正プログラム、既知の問題の最新リストを提供します
ms.openlocfilehash: d59dfd6abece5cefb49d2da86bf28ac24d1cebc7
ms.sourcegitcommit: 61132166c48f967340a1579185728b5c3acd7bd8
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/21/2019
ms.locfileid: "35130646"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="8a2ef-103">Office Insider のリリース ノート</span><span class="sxs-lookup"><span data-stu-id="8a2ef-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="8a2ef-104">この記事には、Windows デスクトップ向け Word、Excel、PowerPoint、Outlook、Access、Project の Insider ビルドのリリース ノートが含まれています。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="8a2ef-105">Microsoft では、毎週、皆様にお知らせしたい魅力的な新機能、重要な修正プログラム、重大な問題に関する情報を提供しています。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="8a2ef-106">多くの場合、機能 (場合によっては修正プログラムも) は、特定の期間にわたって Insider にロールアウトされます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="8a2ef-107">これにより、Microsoft では、より広範な対象ユーザーに機能をリリースする前に、作業がスムーズに行われていることを確認できます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="8a2ef-108">したがって、下記のものが表示されない場合でも、心配する必要はなく、いずれは表示されます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="8a2ef-109">リリース ノートは毎週投稿され、場合により複数のビルドのコンパイルになります</span><span class="sxs-lookup"><span data-stu-id="8a2ef-109">Release notes are posted weekly and may be a compilation of multiple builds</span></span>
> - <span data-ttu-id="8a2ef-110">リリースノートの発行日は実際のビルドのリリース日と一致しない場合があります</span><span class="sxs-lookup"><span data-stu-id="8a2ef-110">The release notes publication date may not match the actual build release date</span></span>

 > [!NOTE]
> - <span data-ttu-id="8a2ef-111">Microsoft Teams に関連する既存の Office 365 ProPlus のインストール - 6 月の下旬から、これらの更新プログラムのインストール時に、Microsoft Teams が既存の Office 365 ProPlus (Office 365 Business) のインストールの中に含められます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-111">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="8a2ef-112">Teams が追加される日にちは、使用している更新プログラム チャネルによって異なります。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-112">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="8a2ef-113">追加情報については、「[Office 365 ProPlus で Microsoft Teams を展開する](https://docs.microsoft.com/ja-JP/deployoffice/teams-install)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-113">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/en-us/deployoffice/teams-install) for additional information.</span></span>

## <a name="june-21-2019"></a><span data-ttu-id="8a2ef-114">2019 年 6 月 21 日</span><span class="sxs-lookup"><span data-stu-id="8a2ef-114">June 21, 2019</span></span>
<span data-ttu-id="8a2ef-115">バージョン 1907 (ビルド 11815.20002)</span><span class="sxs-lookup"><span data-stu-id="8a2ef-115">Version 1907 (build 11815.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="8a2ef-116">新機能:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-116">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="8a2ef-117">Outlook</span><span class="sxs-lookup"><span data-stu-id="8a2ef-117">Outlook</span></span>

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a><span data-ttu-id="8a2ef-118">Outlook デスクトップにおける黒のテーマでの濃色モード</span><span class="sxs-lookup"><span data-stu-id="8a2ef-118">Dark Mode for Black Theme in Outlook Desktop</span></span>

<span data-ttu-id="8a2ef-119">[濃色] モードで黒のテーマを使用しているユーザーには、電子メールを読むときに [閲覧] ウィンドウは暗く表示され、メールを作成するときも同様に表示されます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-119">With dark mode, users in black theme will now also see the reading pane with a dark background when reading emails, and the compose experience with a dark background when writing emails.</span></span> <span data-ttu-id="8a2ef-120">ユーザーが明るい背景でメッセージがどのように見えるかを確認する場合に備えて、[閲覧] ウィンドウとリボンに [太陽/月] トグルがあります。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-120">There is a sun/moon toggle on the reading pane and in the ribbon in case users want to preview what the message looks like with a light background instead.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="8a2ef-121">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-121">Getting Started:</span></span>

1. <span data-ttu-id="8a2ef-122">[黒のテーマ] に切り替えると、既定では濃色モードになります。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-122">Turn on black theme and dark mode will be on by default.</span></span>
2. <span data-ttu-id="8a2ef-123">(閲覧ウィンドウとリボンにある) [月/太陽] トグルを使用して、濃色モードでないユーザーにメッセージがどのように見えるかを表示します。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-123">Use the moon/sun toggle (in the reading pane and in the ribbon) to preview what the message looks like for users not in dark mode</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="8a2ef-124">次の操作を試してみてください</span><span class="sxs-lookup"><span data-stu-id="8a2ef-124">Scenarios to Try:</span></span>

1. <span data-ttu-id="8a2ef-125">濃色モードでメールを読みます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-125">Read emails in dark mode.</span></span> <span data-ttu-id="8a2ef-126">何も見えない場合は、[閲覧] ウィンドウの [太陽] トグルを使用して、背景を明るくします。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-126">If you are unable to read something, use the sun toggle in the Reading Pane to switch to a light background.</span></span> 
2. <span data-ttu-id="8a2ef-127">[濃色] モードでメールを作成します。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-127">Compose emails in dark mode.</span></span> <span data-ttu-id="8a2ef-128">リボンの [太陽] トグルを使用して、メッセージが明るい背景でどのように見えるかを確認します。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-128">Preview what your message will look like with a light background by using the sun toggle in the ribbon.</span></span> 

<span data-ttu-id="8a2ef-129">正常に表示されないメールが見つかった場合は、(添付ファイルとして) OutlookDarkModeFail に送信してください。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-129">If you encounter any emails that don't render properly, please send them (as an attachment) to the OutlookDarkModeFail,</span></span>

#### <a name="get-location-suggestions"></a><span data-ttu-id="8a2ef-130">場所の候補を取得する</span><span class="sxs-lookup"><span data-stu-id="8a2ef-130">Get location suggestions</span></span>

<span data-ttu-id="8a2ef-131">入力を開始すると、Outlook で一致する場所が検索されます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-131">Start typing and Outlook will look for matching locations.</span></span>

<span data-ttu-id="8a2ef-132">予定や会議を作成するときは、[場所] フィールドに適用されます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-132">This applies to the Location field when creating Appointments and Meetings.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="8a2ef-133">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-133">Getting Started:</span></span>

- <span data-ttu-id="8a2ef-134">Outlook で O365 または Outlook.com の予定表に予定や会議を作成します。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-134">Create an Appointment or Meeting on an O365 or Outlook.com calendar in Outlook.</span></span> 
- <span data-ttu-id="8a2ef-135">[場所] フィールドをクリックして、入力を開始します...。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-135">Click into the Location field and start typing…</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="8a2ef-136">次の操作を試してみてください</span><span class="sxs-lookup"><span data-stu-id="8a2ef-136">Scenarios to Try:</span></span>

<span data-ttu-id="8a2ef-137">会議に会議室を追加するときは、[会議室の検索] アドインやアドレス帳を使用するのではなく、[場所] フィールドをクリックします。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-137">When adding a conference room to a meeting, click into Location field, rather than using Room Finder add-in or Address Book.</span></span>
<span data-ttu-id="8a2ef-138">レストラン、喫茶店、歯科医院といった公共の場所での予定がある場合は、新しいピッカーを使用して正確な位置を見つけることができます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-138">For appointments at a physical place with a public location - like a restaurant, coffee shop, or even your dentist's office - try finding the exact location using the new picker.</span></span> <span data-ttu-id="8a2ef-139">こうすることで、外出するときに Outlook Mobile で通知を受け取ることができます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-139">This way, you'll be able to get notified on Outlook Mobile when it's time to leave.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="8a2ef-140">主な修正:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-140">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="8a2ef-141">すべて</span><span class="sxs-lookup"><span data-stu-id="8a2ef-141">All</span></span>
- <span data-ttu-id="8a2ef-142">オフラインで [検索] ボックスが有効なままになる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-142">We fixed an issue which would keep the Search Box enabled while offline</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-143">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-143">Word</span></span> 
- <span data-ttu-id="8a2ef-144">キーボード フォーカスが表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-144">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>
- <span data-ttu-id="8a2ef-145">新しいドキュメントにテキストを貼り付けたときに、テキストが間違えて配置される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-145">We fixed an issue where text pasted into a new document could sometimes have the wrong text alignment</span></span>
- <span data-ttu-id="8a2ef-146">コンピューターを中断した後に、一部のユーザーが変更を保存できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-146">We fixed an issue which could prevent some users from saving changes after suspending their computer</span></span>
- <span data-ttu-id="8a2ef-147">特定の場合に、選択したページの代わりにドキュメント全体が印刷される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-147">We fixed an issue where in certain cases an entire document would be printed instead of the selected range</span></span>
- <span data-ttu-id="8a2ef-148">小さなディスプレイでコメントが読みにくくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-148">We fixed an issue which could make comments difficult to read on smaller displays</span></span>
- <span data-ttu-id="8a2ef-149">デバイスにキャプチャするときにクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-149">We fixed an issue which could cause a crash when capturing to a device</span></span>

### <a name="excel"></a><span data-ttu-id="8a2ef-150">Excel</span><span class="sxs-lookup"><span data-stu-id="8a2ef-150">Excel</span></span>
- <span data-ttu-id="8a2ef-151">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-151">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8a2ef-152">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8a2ef-152">PowerPoint</span></span>
- <span data-ttu-id="8a2ef-153">キーボード フォーカスが表示されないことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-153">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>

### <a name="outlook"></a><span data-ttu-id="8a2ef-154">Outlook</span><span class="sxs-lookup"><span data-stu-id="8a2ef-154">Outlook</span></span>
- <span data-ttu-id="8a2ef-155">有効ではないときにアドインが誤って有効になっていると表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-155">We fixed an issue which could incorrectly display an add-in as being enabled when it was not.</span></span>
- <span data-ttu-id="8a2ef-156">多数の保持ポリシーが表示されていない場合、ユーザーがすべての保持ポリシーを表示できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-156">We fixed an issue which would prevent a customer from viewing all retention policies if there were a large number of them</span></span>

### <a name="access"></a><span data-ttu-id="8a2ef-157">Access</span><span class="sxs-lookup"><span data-stu-id="8a2ef-157">Access</span></span>
- <span data-ttu-id="8a2ef-158">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-158">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="8a2ef-159">Project</span><span class="sxs-lookup"><span data-stu-id="8a2ef-159">Project</span></span>
- <span data-ttu-id="8a2ef-160">さまざまなパフォーマンスと安定性に関する修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-160">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-14-2019"></a><span data-ttu-id="8a2ef-161">2019 年 6 月 14 日</span><span class="sxs-lookup"><span data-stu-id="8a2ef-161">June 14, 2019</span></span>
<span data-ttu-id="8a2ef-162">バージョン 1907 (ビルド 11807.20000)</span><span class="sxs-lookup"><span data-stu-id="8a2ef-162">Version 1907 (build 11807.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="8a2ef-163">主な修正:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-163">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-164">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-164">Word</span></span> 
- <span data-ttu-id="8a2ef-165">OneDrive に保存しているときにユーザーがサインインするのを妨げていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-165">We fixed an issue which could prevent a user from signing in when saving to OneDrive</span></span>
- <span data-ttu-id="8a2ef-166">アクセス制限モード中にユーザーによる SharePoint のプロパティの変更が妨げられていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-166">We fixed an issue where a user could be prevented from changing SharePoint properties while in restricted access mode</span></span>
- <span data-ttu-id="8a2ef-167">余白を調整しているときにヘッダーやフッターの内容が変更されてしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-167">We fixed an issue where header and footer content could change when adjusting margins</span></span>
- <span data-ttu-id="8a2ef-168">Web ビューに切り替えているときに書式設定が崩れてしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-168">We fixed an issue where formatting could break when switching to web view</span></span>
- <span data-ttu-id="8a2ef-169">SharePoint で開いたときにユーザーによるカスタム フィールドの使用を妨げていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-169">We fixed an issue which could prevent a user from using custom fields when opened from SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="8a2ef-170">Excel</span><span class="sxs-lookup"><span data-stu-id="8a2ef-170">Excel</span></span>
- <span data-ttu-id="8a2ef-171">フィルター処理された行を削除するときのパフォーマンスの問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-171">We fixed a performance issue when deleting rows of a filtered set</span></span>
- <span data-ttu-id="8a2ef-172">時々、保護ビューでマウスをちらつかせる原因になっていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-172">We fixed an issue which could sometimes cause the mouse to flicker in protected view</span></span>
- <span data-ttu-id="8a2ef-173">系列を削除しているときにクラッシュを引き起こしていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-173">We fixed an issue which could have caused a crash when deleting a series</span></span>
- <span data-ttu-id="8a2ef-174">利用できなかった場合に一部のユーザーがバージョン履歴を追加するオプションを使用していたところの問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-174">We fixed an issue where some users would have the option to add version history when that was not available</span></span>
- <span data-ttu-id="8a2ef-175">スプレッドシート比較ツールを使用しているときに例外を引き起こしていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-175">We fixed an issue which could have caused an exception when using the Spreadsheet Compare tool</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8a2ef-176">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8a2ef-176">PowerPoint</span></span>
- <span data-ttu-id="8a2ef-177">SharePoint へのリンクをクリックしたときにクラッシュを発生させていた問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-177">We fixed an issue where a crash could occur when clicking a link to SharePoint</span></span>
- <span data-ttu-id="8a2ef-178">ユーザーが Surface ペンを使用して入力しているのに、次のページに切り替わってしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-178">We fixed an issue which could switch the user to the next page while typing using a Surface Pen</span></span>

### <a name="outlook"></a><span data-ttu-id="8a2ef-179">Outlook</span><span class="sxs-lookup"><span data-stu-id="8a2ef-179">Outlook</span></span>
- <span data-ttu-id="8a2ef-180">一部の宛先フィールドが通常より大きくなってしまう問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-180">We fixed an issue where in some cases the To field was larger than normal</span></span>

### <a name="access"></a><span data-ttu-id="8a2ef-181">Access</span><span class="sxs-lookup"><span data-stu-id="8a2ef-181">Access</span></span>
- <span data-ttu-id="8a2ef-182">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-182">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="8a2ef-183">Project</span><span class="sxs-lookup"><span data-stu-id="8a2ef-183">Project</span></span>
- <span data-ttu-id="8a2ef-184">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-184">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-7-2019"></a><span data-ttu-id="8a2ef-185">2019 年 6 月 7 日</span><span class="sxs-lookup"><span data-stu-id="8a2ef-185">June 7, 2019</span></span>
<span data-ttu-id="8a2ef-186">バージョン 1907 (ビルド 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="8a2ef-186">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="8a2ef-187">主な修正:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-187">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-188">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-188">Word</span></span> 
- <span data-ttu-id="8a2ef-189">オートコレクトが文の先頭文字を大文字にするように設定されていると Word がクラッシュする場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-189">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="8a2ef-190">SharePoint でドキュメントを編集する際のパフォーマンスが向上しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-190">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="8a2ef-191">Adobe Illustrator で作成されたベクター ベースの画像が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-191">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="8a2ef-192">Excel</span><span class="sxs-lookup"><span data-stu-id="8a2ef-192">Excel</span></span>
- <span data-ttu-id="8a2ef-193">マクロを記録するときに、並べ替えフィールドが正しく設定されない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-193">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="8a2ef-194">配列数式の計算中にハングまたはクラッシュする問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-194">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8a2ef-195">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8a2ef-195">PowerPoint</span></span>
- <span data-ttu-id="8a2ef-196">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-196">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="8a2ef-197">Outlook</span><span class="sxs-lookup"><span data-stu-id="8a2ef-197">Outlook</span></span>
- <span data-ttu-id="8a2ef-198">インライン添付ファイルが誤って拡大縮小されることがある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-198">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="8a2ef-199">Access</span><span class="sxs-lookup"><span data-stu-id="8a2ef-199">Access</span></span>
- <span data-ttu-id="8a2ef-200">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-200">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="8a2ef-201">Project</span><span class="sxs-lookup"><span data-stu-id="8a2ef-201">Project</span></span>
- <span data-ttu-id="8a2ef-202">固定期間のタイムシートが割り当て終了日を変更するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-202">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="8a2ef-203">以前のバージョンからプロジェクトを開くと、[完了率] の値が正しくない場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-203">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="8a2ef-204">2019 年 5 月 31 日</span><span class="sxs-lookup"><span data-stu-id="8a2ef-204">May 31, 2019</span></span>
<span data-ttu-id="8a2ef-205">バージョン 1906 (ビルド 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="8a2ef-205">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="8a2ef-206">新機能:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-206">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="8a2ef-207">Outlook</span><span class="sxs-lookup"><span data-stu-id="8a2ef-207">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="8a2ef-208">サポートに問い合わせるためのダイアログがドッキング可能になり、右側に表示されるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-208">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="8a2ef-209">サポートへの問い合わせに使用するダイアログが右側のウィンドウに表示され、最初からドッキングされたウィンドウとして表示されます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-209">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="8a2ef-210">メールでインクを使用する</span><span class="sxs-lookup"><span data-stu-id="8a2ef-210">Ink in Your Email!</span></span>

<span data-ttu-id="8a2ef-211">Outlook メールで画像を描画し、注釈を付けることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-211">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-212">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-212">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="8a2ef-213">ドキュメント リンクを Word で開く</span><span class="sxs-lookup"><span data-stu-id="8a2ef-213">Open document links in Word</span></span>

<span data-ttu-id="8a2ef-214">Office でドキュメント リンクをクリックしたときに既定で Word アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-214">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="8a2ef-215">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-215">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="8a2ef-216">詳しくは、以下を参照してください。https://support.office.com/ja-JP/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="8a2ef-216">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="8a2ef-217">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-217">Getting Started:</span></span>

<span data-ttu-id="8a2ef-218">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-218">Feature will default to off.</span></span> <span data-ttu-id="8a2ef-219">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-219">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="8a2ef-220">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-220">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="8a2ef-221">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-221">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="8a2ef-222">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="8a2ef-222">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="8a2ef-223">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-223">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="8a2ef-224">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-224">Scenarios to Try:</span></span>

<span data-ttu-id="8a2ef-225">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている Word ドキュメントへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-225">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="8a2ef-226">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-226">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8a2ef-227">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8a2ef-227">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="8a2ef-228">プレゼンテーションへのリンクを PowerPoint で開く</span><span class="sxs-lookup"><span data-stu-id="8a2ef-228">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="8a2ef-229">Office でプレゼンテーションへのリンクをクリックしたときに既定で PowerPoint アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-229">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="8a2ef-230">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-230">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="8a2ef-231">詳しくは、以下を参照してください。https://support.office.com/ja-JP/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="8a2ef-231">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="8a2ef-232">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-232">Getting Started:</span></span>

<span data-ttu-id="8a2ef-233">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-233">Feature will default to off.</span></span> <span data-ttu-id="8a2ef-234">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-234">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="8a2ef-235">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-235">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="8a2ef-236">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-236">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="8a2ef-237">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="8a2ef-237">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="8a2ef-238">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-238">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="8a2ef-239">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-239">Scenarios to Try:</span></span>

<span data-ttu-id="8a2ef-240">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている PowerPoint プレゼンテーションへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-240">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="8a2ef-241">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-241">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="8a2ef-242">Excel</span><span class="sxs-lookup"><span data-stu-id="8a2ef-242">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="8a2ef-243">ブックのリンクを Excel で開く</span><span class="sxs-lookup"><span data-stu-id="8a2ef-243">Open the workbook in Excel.</span></span>

<span data-ttu-id="8a2ef-244">Office でブックのリンクをクリックしたときに既定で Excel アプリで開くように設定を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-244">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="8a2ef-245">設定を更新するには、[ファイル ] > [オプション] > [詳細設定] > [リンクの処理] の順に移動します。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-245">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="8a2ef-246">詳細については、以下を参照してください。https://support.office.com/ja-JP/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="8a2ef-246">https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="8a2ef-247">作業を開始する:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-247">Getting Started:</span></span>

<span data-ttu-id="8a2ef-248">この機能は既定でオフになっています。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-248">Feature will default to off.</span></span> <span data-ttu-id="8a2ef-249">有効化するには、[オプション] > [詳細設定] > [リンクの処理] の設定経由でオンにする方法と、Win32 WXP アプリでオプトイン機能が動作中にオプトインする方法とがあります。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-249">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="8a2ef-250">OneDrive/OneDrive for Business/SharePoint に保存されている Word/PowerPoint/Excel ファイルへのリンクを Outlook/Word/PowerPoint/ Excel でクリックすると、既定で、これらのリンクがブラウザーではなく、適切な Office アプリケーションで開きます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-250">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="8a2ef-251">この既定の設定を変更するには、Outlook/Word/Excel/PowerPoint で次の設定を更新します。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-251">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="8a2ef-252">[ファイル ] > [オプション] > [詳細設定] > [リンクの処理]</span><span class="sxs-lookup"><span data-stu-id="8a2ef-252">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="8a2ef-253">この設定は、Outlook/Word/PowerPoint/Excel の間で共有され、いずれのアプリからでも設定できます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-253">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="8a2ef-254">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-254">Scenarios to Try:</span></span>

<span data-ttu-id="8a2ef-255">オプトイン機能をトリガーするには、OneDrive/SharePoint に保存されている Excel ブックへのリンクを Outlook/Word/PowerPoint/Excel から開き、[Office Online からクライアントで開く] をクリックします。この操作を 30 日以内に 2 回行います。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-255">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="8a2ef-256">オプトイン後は、リンクは既定で Win32 アプリで起動するようになります。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-256">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="8a2ef-257">主な修正:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-257">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="8a2ef-258">すべて</span><span class="sxs-lookup"><span data-stu-id="8a2ef-258">All</span></span>
- <span data-ttu-id="8a2ef-259">自動保存が無効になっている場合でも、ファイルが自動保存されてしまう場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-259">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-260">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-260">Word</span></span> 
- <span data-ttu-id="8a2ef-261">一部のユーザーがファイルを SharePoint に保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-261">We fixed an issue which prevented some users from saving files to cloud locations</span></span>

### <a name="excel"></a><span data-ttu-id="8a2ef-262">Excel</span><span class="sxs-lookup"><span data-stu-id="8a2ef-262">Excel</span></span>
- <span data-ttu-id="8a2ef-263">無効なフィルターに間違ったアイコンが表示される場合がある問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-263">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8a2ef-264">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8a2ef-264">PowerPoint</span></span>
- <span data-ttu-id="8a2ef-265">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-265">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="8a2ef-266">Outlook</span><span class="sxs-lookup"><span data-stu-id="8a2ef-266">Outlook</span></span>
- <span data-ttu-id="8a2ef-267">グループ スケジュール ビューで一部のユーザーがオフラインとして間違って表示される問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-267">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="8a2ef-268">末尾にスペースが挿入されている URL が SafeLink で解析できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-268">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="8a2ef-269">業務時間外に部屋が利用可能と表示される問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-269">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="8a2ef-270">Access</span><span class="sxs-lookup"><span data-stu-id="8a2ef-270">Access</span></span>
- <span data-ttu-id="8a2ef-271">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-271">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="8a2ef-272">Project</span><span class="sxs-lookup"><span data-stu-id="8a2ef-272">Project</span></span>
- <span data-ttu-id="8a2ef-273">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-273">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="8a2ef-274">2019 年 5 月 24 日</span><span class="sxs-lookup"><span data-stu-id="8a2ef-274">May 24, 2019</span></span>
<span data-ttu-id="8a2ef-275">バージョン 1906 (ビルド 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="8a2ef-275">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="8a2ef-276">新機能:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-276">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="8a2ef-277">ユーザー エクスペリエンスの更新</span><span class="sxs-lookup"><span data-stu-id="8a2ef-277">User Experience Updates</span></span>

<span data-ttu-id="8a2ef-278">近日公開となっていた更新プログラムが公開されました。この更新には、シンプル リボンおよびフォルダー ウィンドウ、メッセージ一覧、閲覧ウィンドウの外観の更新が含まれます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-278">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="8a2ef-279">主な修正:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-279">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="8a2ef-280">すべて</span><span class="sxs-lookup"><span data-stu-id="8a2ef-280">All</span></span>

- <span data-ttu-id="8a2ef-281">チャットウィンドウが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-281">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-282">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-282">Word</span></span> 
- <span data-ttu-id="8a2ef-283">Word で文法エラーのテキストが誤って強調表示されることがある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-283">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="8a2ef-284">Excel</span><span class="sxs-lookup"><span data-stu-id="8a2ef-284">Excel</span></span>
- <span data-ttu-id="8a2ef-285">誤ったアイコンがグラフ要素に使用されているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-285">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="8a2ef-286">同じブックが既に開いているときに、不正なブックが VBA スクリプトでアクティブになるという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-286">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8a2ef-287">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8a2ef-287">PowerPoint</span></span>
- <span data-ttu-id="8a2ef-288">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-288">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="8a2ef-289">Outlook</span><span class="sxs-lookup"><span data-stu-id="8a2ef-289">Outlook</span></span>
- <span data-ttu-id="8a2ef-290">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-290">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="8a2ef-291">Access</span><span class="sxs-lookup"><span data-stu-id="8a2ef-291">Access</span></span>
- <span data-ttu-id="8a2ef-292">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-292">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="8a2ef-293">Project</span><span class="sxs-lookup"><span data-stu-id="8a2ef-293">Project</span></span>
- <span data-ttu-id="8a2ef-294">タスクバーに切り替えた後、Project がクラッシュする可能性がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-294">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="8a2ef-295">2019 年 5 月 17 日</span><span class="sxs-lookup"><span data-stu-id="8a2ef-295">May 17, 2019</span></span>
<span data-ttu-id="8a2ef-296">バージョン 1906 (ビルド 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="8a2ef-296">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="8a2ef-297">新機能:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-297">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="8a2ef-298">Outlook</span><span class="sxs-lookup"><span data-stu-id="8a2ef-298">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="8a2ef-299">ユーザー エクスペリエンスのアップデート</span><span class="sxs-lookup"><span data-stu-id="8a2ef-299">User Experience Updates</span></span>

<span data-ttu-id="8a2ef-300">近日公開となっていた更新プログラムが公開されました。この更新には、シンプル リボンおよびフォルダー ウィンドウ、メッセージ一覧、閲覧ウィンドウの外観の更新が含まれます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-300">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="8a2ef-301">利用するには:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-301">Getting Started:</span></span>

<span data-ttu-id="8a2ef-302">これらの変更は、新しい既定の UI の一部になります。この新しい UI は、すべての運用環境ユーザー向けに [近日公開] スイッチで 12 月中旬以来提供されてきました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-302">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="8a2ef-303">カスタマイズ可能なシンプル リボン</span><span class="sxs-lookup"><span data-stu-id="8a2ef-303">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="8a2ef-304">従来のビューとシンプルなビューの切り替えやコマンドの固定または固定解除を簡単にできます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-304">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="8a2ef-305">利用するには:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-305">Getting Started:</span></span>

<span data-ttu-id="8a2ef-306">シンプル リボンを使用するには、まず [近日公開] 機能をオンにし、リボンの山形マークをクリックして従来の複数行のリボンと新しい 1 行のシンプル リボンを切り替えます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-306">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="8a2ef-307">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-307">Scenarios to Try:</span></span>

<span data-ttu-id="8a2ef-308">従来のリボンからシンプル リボンに切り替える</span><span class="sxs-lookup"><span data-stu-id="8a2ef-308">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="8a2ef-309">お気に入りの操作を選択する</span><span class="sxs-lookup"><span data-stu-id="8a2ef-309">Pick your favorite action</span></span>

<span data-ttu-id="8a2ef-310">[フラグ] 機能や [削除] 機能はお使いになられていないかもしれません。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-310">Don't use Flag and Delete?</span></span> <span data-ttu-id="8a2ef-311">アーカイブまたは既読に​​しますか?</span><span class="sxs-lookup"><span data-stu-id="8a2ef-311">How about Archive or Mark as Read?</span></span> <span data-ttu-id="8a2ef-312">クイック操作メニューをカスタマイズしてよく使うコマンドを追加できます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-312">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="8a2ef-313">利用するには:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-313">Getting Started:</span></span>

<span data-ttu-id="8a2ef-314">希望のクイック操作を選ぶには、メッセージ一覧でメールを右クリックし、コンテキスト メニューを表示します。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-314">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="8a2ef-315">次に、[クイック操作の設定] をクリックします。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-315">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="8a2ef-316">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-316">Scenarios to Try:</span></span>

<span data-ttu-id="8a2ef-317">既定の設定を [フラグ] または [削除] から [アーカイブ]、[移動]、[既読にする]、または [なし] に変更すると、メッセージ一覧をすっきりした外観にできます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-317">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="8a2ef-318">レイアウトの間隔を</span><span class="sxs-lookup"><span data-stu-id="8a2ef-318">Relaxed or tighter layout?</span></span> <span data-ttu-id="8a2ef-319">自由に選べます</span><span class="sxs-lookup"><span data-stu-id="8a2ef-319">You choose</span></span>

<span data-ttu-id="8a2ef-320">[狭い間隔を使用] オプションを使用すると、アイテム間のスペースを広く取るか、間隔の狭いレイアウトでより多くのアイテムを表示するかを選べます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-320">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="8a2ef-321">利用するには:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-321">Getting Started:</span></span>

<span data-ttu-id="8a2ef-322">従来のリボンの場合、[表示] タブの [メッセージ] グループで、[狭い間隔を使用] チェックボックスをオンにします。シンプル リボンの場合は、[現在のビュー] 設定で [狭い間隔を使用] を選択します。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-322">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="8a2ef-323">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-323">Scenarios to Try:</span></span>

<span data-ttu-id="8a2ef-324">Outlook で、この設定をオフにした状態でメッセージをトリアージしたり作成したりしてみます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-324">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="8a2ef-325">この機能をオンにすると、1 ページに収まるメッセージの数が増え、新規作成フォームのコントロールの表示がすっきりとします。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-325">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="8a2ef-326">Onedrive 同期クライアントを使用する際の MRU エントリの重複を除去する</span><span class="sxs-lookup"><span data-stu-id="8a2ef-326">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="8a2ef-327">クラウド添付ファイルを使用すると、MRU エントリの重複を除去できるため、Onedrive の統合を効率化できます。クラウド添付ファイルを使用すれば、同期されたデータでコピーの添付をする動作が早くなります。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-327">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="8a2ef-328">利用するには:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-328">Getting Started:</span></span>

<span data-ttu-id="8a2ef-329">OneDrive 同期クライアントを使用している場合は、添付ファイル MRU に重複ファイルが表示されなくなります。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-329">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="8a2ef-330">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-330">Scenarios to Try:</span></span>

<span data-ttu-id="8a2ef-331">OneDrive 同期クライアントを有効にして、Outlook デスクトップで [ファイルの添付] メニューを使用する</span><span class="sxs-lookup"><span data-stu-id="8a2ef-331">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="8a2ef-332">フォルダーを多数含むメールボックスでの共有フォルダーの同期が改善されました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-332">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="8a2ef-333">長い間、Outlook での共有メールボックスの同期は、最大で 500 フォルダーに制限されてきました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-333">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="8a2ef-334">この変更により Outlook の改善が行われ、同期をする際の 500 フォルダーの制限がなくなりました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-334">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="8a2ef-335">利用するには:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-335">Getting Started:</span></span>

<span data-ttu-id="8a2ef-336">メールボックスにフォルダーを 1000 個作成し、誰か他のユーザーにそのメールボックスへのアクセスを許可し、このユーザーの Outlook プロファイルを作成します。同期が正常に動作することを確認します。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-336">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-337">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-337">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="8a2ef-338">少しだけ消す</span><span class="sxs-lookup"><span data-stu-id="8a2ef-338">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="8a2ef-339">利用するには:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-339">Getting Started:</span></span>

<span data-ttu-id="8a2ef-340">[描画] タブに移動します。 [消しゴム] ドロップダウンを選択します。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-340">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="8a2ef-341">[消しゴム (小)] または [消しゴム (中)] を選びます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-341">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="8a2ef-342">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-342">Scenarios to Try:</span></span>

<span data-ttu-id="8a2ef-343">[描画] タブに移動します。ペンを選びます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-343">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="8a2ef-344">インク ストロークを描きます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-344">Draw an ink stroke.</span></span> <span data-ttu-id="8a2ef-345">[消しゴム] ドロップダウンを選択します。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-345">Select the Eraser dropdown.</span></span> <span data-ttu-id="8a2ef-346">[消しゴム (小)] または [消しゴム (中)] を選びます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-346">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="8a2ef-347">インク ストロークを少しだけ消してみます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-347">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="8a2ef-348">主な修正:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-348">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="8a2ef-349">すべて</span><span class="sxs-lookup"><span data-stu-id="8a2ef-349">All</span></span> 
- <span data-ttu-id="8a2ef-350">一部のユーザーが PDF として保存できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-350">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="8a2ef-351">32 ビット システムでの大容量ファイルの保存に影響する場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-351">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-352">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-352">Word</span></span> 
- <span data-ttu-id="8a2ef-353">音声入力機能の応答性が大幅に向上されました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-353">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="8a2ef-354">Excel</span><span class="sxs-lookup"><span data-stu-id="8a2ef-354">Excel</span></span>
- <span data-ttu-id="8a2ef-355">タッチ スクリーン デバイスでダブルクリック イベントが失敗する問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-355">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="8a2ef-356">一部のユーザーが VBA マクロを編集できない問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-356">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="8a2ef-357">スライサーを使用した際にパフォーマンスに影響する場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-357">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8a2ef-358">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8a2ef-358">PowerPoint</span></span>
- <span data-ttu-id="8a2ef-359">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-359">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="8a2ef-360">Outlook</span><span class="sxs-lookup"><span data-stu-id="8a2ef-360">Outlook</span></span>
- <span data-ttu-id="8a2ef-361">選択したテンプレートとは異なるテンプレートが表示される場合がある問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-361">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="8a2ef-362">Access</span><span class="sxs-lookup"><span data-stu-id="8a2ef-362">Access</span></span>
- <span data-ttu-id="8a2ef-363">長いリッチ テキストの表示に Zoom Builder を使うと、読みづらくなる問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-363">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="8a2ef-364">Project</span><span class="sxs-lookup"><span data-stu-id="8a2ef-364">Project</span></span>
- <span data-ttu-id="8a2ef-365">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-365">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="8a2ef-366">2019 年 5 月 10日</span><span class="sxs-lookup"><span data-stu-id="8a2ef-366">May 10, 2019</span></span>
<span data-ttu-id="8a2ef-367">バージョン 1906 (ビルド 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="8a2ef-367">Version 1906 (build 11702.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="8a2ef-368">主な修正:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-368">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="8a2ef-369">すべて</span><span class="sxs-lookup"><span data-stu-id="8a2ef-369">All</span></span>
- <span data-ttu-id="8a2ef-370">[名前を付けて保存] ダイアログボックスに誤ったパスが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-370">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-371">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-371">Word</span></span> 
- <span data-ttu-id="8a2ef-372">操作アシストからの一部の選択が挿入されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-372">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="8a2ef-373">Excel</span><span class="sxs-lookup"><span data-stu-id="8a2ef-373">Excel</span></span>
- <span data-ttu-id="8a2ef-374">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-374">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8a2ef-375">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8a2ef-375">PowerPoint</span></span>
- <span data-ttu-id="8a2ef-376">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-376">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="8a2ef-377">Outlook</span><span class="sxs-lookup"><span data-stu-id="8a2ef-377">Outlook</span></span>
- <span data-ttu-id="8a2ef-378">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-378">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="8a2ef-379">Access</span><span class="sxs-lookup"><span data-stu-id="8a2ef-379">Access</span></span>
- <span data-ttu-id="8a2ef-380">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-380">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="8a2ef-381">Project</span><span class="sxs-lookup"><span data-stu-id="8a2ef-381">Project</span></span>
- <span data-ttu-id="8a2ef-382">タスク ID の確認に強調表示が必要となる可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-382">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="8a2ef-383">2019 年 5 月 3日</span><span class="sxs-lookup"><span data-stu-id="8a2ef-383">May 3, 2019</span></span>
<span data-ttu-id="8a2ef-384">バージョン 1906 (ビルド 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="8a2ef-384">Version 1906 (build 11629.20008)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="8a2ef-385">主な修正:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-385">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="8a2ef-386">すべて</span><span class="sxs-lookup"><span data-stu-id="8a2ef-386">All</span></span>
- <span data-ttu-id="8a2ef-387">一部のユーザーが OneDrive for Business との同期で問題が発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-387">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-388">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-388">Word</span></span> 
- <span data-ttu-id="8a2ef-389">Word の起動に時間がかかる場合がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-389">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="8a2ef-390">Excel</span><span class="sxs-lookup"><span data-stu-id="8a2ef-390">Excel</span></span>
- <span data-ttu-id="8a2ef-391">新しいバージョンの Excel にアップグレードした後、ブックから外部リンクが削除されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-391">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="8a2ef-392">一部のユーザーが新しいワークブックでセルを選択するのが困難な問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-392">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8a2ef-393">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8a2ef-393">PowerPoint</span></span>
- <span data-ttu-id="8a2ef-394">図面をテキストに変換するときにフォントサイズが一致しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-394">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="8a2ef-395">Outlook</span><span class="sxs-lookup"><span data-stu-id="8a2ef-395">Outlook</span></span>
- <span data-ttu-id="8a2ef-396">a .VCF ファイルから連絡先を保存すると空のフィールドが発生する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-396">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="8a2ef-397">送信されていても、送信トレイ フォルダーにメッセージが残ってしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-397">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="8a2ef-398">DRM メッセージの表示中に Outlook がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-398">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="8a2ef-399">Access</span><span class="sxs-lookup"><span data-stu-id="8a2ef-399">Access</span></span>
- <span data-ttu-id="8a2ef-400">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-400">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="8a2ef-401">Project</span><span class="sxs-lookup"><span data-stu-id="8a2ef-401">Project</span></span>
- <span data-ttu-id="8a2ef-402">エディターが中国語から英語に切り替わる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-402">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="8a2ef-403">マスター プロジェクトの公開コピーに未公開タスクが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-403">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="8a2ef-404">2019 年 4 月 26 日</span><span class="sxs-lookup"><span data-stu-id="8a2ef-404">April 26, 2019</span></span>
<span data-ttu-id="8a2ef-405">バージョン 1905 (ビルド 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="8a2ef-405">Version 1905 (build 11617.20002)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="8a2ef-406">主な修正:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-406">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-407">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-407">Word</span></span> 
- <span data-ttu-id="8a2ef-408">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-408">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="8a2ef-409">Excel</span><span class="sxs-lookup"><span data-stu-id="8a2ef-409">Excel</span></span>
- <span data-ttu-id="8a2ef-410">ソルバー マクロの実行が失敗するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-410">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="8a2ef-411">Excel ファイルを SharePoint にインポートできないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-411">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8a2ef-412">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8a2ef-412">PowerPoint</span></span>
- <span data-ttu-id="8a2ef-413">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-413">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="8a2ef-414">Outlook</span><span class="sxs-lookup"><span data-stu-id="8a2ef-414">Outlook</span></span>
- <span data-ttu-id="8a2ef-415">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-415">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="8a2ef-416">Access</span><span class="sxs-lookup"><span data-stu-id="8a2ef-416">Access</span></span>
- <span data-ttu-id="8a2ef-417">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-417">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="8a2ef-418">Project</span><span class="sxs-lookup"><span data-stu-id="8a2ef-418">Project</span></span>
- <span data-ttu-id="8a2ef-419">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-419">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="8a2ef-420">2019 年 4 月 19 日</span><span class="sxs-lookup"><span data-stu-id="8a2ef-420">April 19, 2019</span></span>
<span data-ttu-id="8a2ef-421">バージョン 1905 (ビルド 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="8a2ef-421">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="8a2ef-422">新機能:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-422">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="8a2ef-423">Excel</span><span class="sxs-lookup"><span data-stu-id="8a2ef-423">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="8a2ef-424">データ型を使用した塗り分けマップのエクスペリエンス向上</span><span class="sxs-lookup"><span data-stu-id="8a2ef-424">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="8a2ef-425">この機能は、Excel の地理データ型を使用して、塗り分けされたマップ グラフにプロットするユーザーのための機能強化です。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-425">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="8a2ef-426">エンドユーザーにとっては、機能とエンドユーザーがマップする領域の精度向上とがより高度に統合されたことが利点です。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-426">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="8a2ef-427">さらに、ポリゴンで都市をマッピングする機能も含まれてます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-427">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="8a2ef-428">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-428">Getting Started:</span></span>

- <span data-ttu-id="8a2ef-429">この機能は、Excel 内の既存の機能を改善したものです。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-429">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="8a2ef-430">この改善を使用するには、位置をリッチエンティティに変換し、塗り分けマップでプロットします。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-430">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="8a2ef-431">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-431">Scenarios to Try:</span></span>

- <span data-ttu-id="8a2ef-432">ユーザーは、都市、州、都道府県、国、郵便番号のマッピングを試すことができます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-432">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="8a2ef-433">主な修正:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-433">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="8a2ef-434">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="8a2ef-434">All Applications</span></span>
- <span data-ttu-id="8a2ef-435">アプリケーションが起動したときに最初の実行ダイアログが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-435">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="8a2ef-436">[名前を付けて保存] ダイアログボックス内の SharePoint リンクが表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-436">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="8a2ef-437">ユーザーが [今すぐ修復] ダイアログを誤って表示する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-437">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-438">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-438">Word</span></span> 
- <span data-ttu-id="8a2ef-439">フォントの要求時に、一部のユーザーがメモリ不足またはディスク領域のエラーを受信する可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-439">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="8a2ef-440">[コメント] ウィンドウから切り替えたときにウィンドウがフォーカスを失う可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-440">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="8a2ef-441">Excel</span><span class="sxs-lookup"><span data-stu-id="8a2ef-441">Excel</span></span>
- <span data-ttu-id="8a2ef-442">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-442">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8a2ef-443">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8a2ef-443">PowerPoint</span></span>
- <span data-ttu-id="8a2ef-444">ブランド化された図形のサイズ変更ができない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-444">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="8a2ef-445">保護ビューモードでファイルを開くときに PowerPoint がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-445">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="8a2ef-446">Outlook</span><span class="sxs-lookup"><span data-stu-id="8a2ef-446">Outlook</span></span>
- <span data-ttu-id="8a2ef-447">一部のユーザーが中国語の単語を選択できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-447">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="8a2ef-448">有効期限が正しく計算されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-448">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="8a2ef-449">Access</span><span class="sxs-lookup"><span data-stu-id="8a2ef-449">Access</span></span>
- <span data-ttu-id="8a2ef-450">一部のユーザーがマクロ ビルダーを使用できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-450">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="8a2ef-451">レポートを印刷すると最初のページしか印刷されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-451">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="8a2ef-452">ハイパーリンクの上にカーソルを置くとアプリケーションがクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-452">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="8a2ef-453">リレーションシップ ビューを使用すると、一部のアイテムが画面外に表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-453">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="8a2ef-454">Project</span><span class="sxs-lookup"><span data-stu-id="8a2ef-454">Project</span></span>
- <span data-ttu-id="8a2ef-455">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-455">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="8a2ef-456">2019 年 4 月 12 日</span><span class="sxs-lookup"><span data-stu-id="8a2ef-456">April 12, 2019</span></span>
<span data-ttu-id="8a2ef-457">バージョン 1905 (ビルド 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="8a2ef-457">Version 1905 (build 11601.20042)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="8a2ef-458">主な修正:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-458">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="8a2ef-459">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="8a2ef-459">All Applications</span></span>
 - <span data-ttu-id="8a2ef-460">一部のユーザーがクラウドの場所にファイルを保存できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-460">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="8a2ef-461">リボンから間違ったウィンドウが開く問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-461">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-462">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-462">Word</span></span> 
- <span data-ttu-id="8a2ef-463">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-463">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="8a2ef-464">Excel</span><span class="sxs-lookup"><span data-stu-id="8a2ef-464">Excel</span></span>
- <span data-ttu-id="8a2ef-465">リンクされたデータ型を含まないブックであるにもかかわらず、リンクされたデータ型に対するエラーメッセージが表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-465">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="8a2ef-466">Word 文書内のリンクの URL がオンラインとローカルで表示したときに変更される可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-466">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8a2ef-467">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8a2ef-467">PowerPoint</span></span>
- <span data-ttu-id="8a2ef-468">[アニメーション] タブで変更を元に戻すと、PowerPoint がクラッシュする可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-468">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="8a2ef-469">Outlook</span><span class="sxs-lookup"><span data-stu-id="8a2ef-469">Outlook</span></span>
- <span data-ttu-id="8a2ef-470">一部のユーザーがパブリック フォルダー内の連絡先の [メモ] フィールドを変更できない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-470">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="8a2ef-471">失効日と削除日の間に競合が発生する可能性がある問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-471">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="8a2ef-472">Access</span><span class="sxs-lookup"><span data-stu-id="8a2ef-472">Access</span></span>
- <span data-ttu-id="8a2ef-473">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-473">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="8a2ef-474">Project</span><span class="sxs-lookup"><span data-stu-id="8a2ef-474">Project</span></span>
- <span data-ttu-id="8a2ef-475">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-475">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="8a2ef-476">2019年4月5日</span><span class="sxs-lookup"><span data-stu-id="8a2ef-476">April 5, 2019</span></span>
<span data-ttu-id="8a2ef-477">バージョン 1904 (ビルド 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="8a2ef-477">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="8a2ef-478">新機能:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-478">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="8a2ef-479">Outlook</span><span class="sxs-lookup"><span data-stu-id="8a2ef-479">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="8a2ef-480">Windows 用の Outlook: 優先受信トレイの設定を設定して共有します。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-480">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="8a2ef-481">優先受信トレイの設定はクラウドに保存されるため、どのコンピューターで Web 上の Outlook for Windows と Outlook を使用しても同じように一貫したエクスペリエンスを楽しめます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-481">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="8a2ef-482">利用するには:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-482">Getting Started:</span></span>

<span data-ttu-id="8a2ef-483">[ファイル]、[オプション]、[全般] の順に移動すると、[Outlook の設定をクラウドに保存する] という新しい設定があります。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-483">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="8a2ef-484">ユーザーは、自分の優先受信トレイの設定を他の Outlook Desktop インストールおよび OWA に移動できるようにするには、このチェック ボックスをオンにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-484">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="8a2ef-485">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-485">Scenarios to Try:</span></span>

<span data-ttu-id="8a2ef-486">クラウド設定の設定を有効にしているコンピューターで優先受信トレイを変更します。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-486">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="8a2ef-487">OWA に移動して、そこに適用されている設定も確認してください。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-487">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="8a2ef-488">OWA で優先受信トレイを変更し、デスクトップ Outlook を起動して反映された優先順位を表示します。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-488">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-489">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-489">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="8a2ef-490">学習ツール モードでは、より多くのページの色が追加でサポートされます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-490">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="8a2ef-491">Word の学習ツールは、より多くのページ テーマ色を追加し、ページの背景色を変更できるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-491">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="8a2ef-492">多くのユーザーがすべて白、またはすべて黒の背景だと閲覧が難しいという課題があったため、PC と Mac の Word で色の選択肢を拡大しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-492">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="8a2ef-493">利用するには:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-493">Getting Started:</span></span>

<span data-ttu-id="8a2ef-494">この操作を行うには、[表示] タブに移動し、[学習ツール]、[ページの色] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-494">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="8a2ef-495">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-495">Scenarios to Try:</span></span>

<span data-ttu-id="8a2ef-496">この操作を行うには、[表示] タブに移動し、[学習ツール]、[ページの色] の順に選択します。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-496">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="8a2ef-497">Excel</span><span class="sxs-lookup"><span data-stu-id="8a2ef-497">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="8a2ef-498">3D アニメーション モデルで創造性を高める</span><span class="sxs-lookup"><span data-stu-id="8a2ef-498">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="8a2ef-499">Office では、アニメーションモデルをサポートするようになりました。エディターで再生するので、シートを活用することができます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-499">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="8a2ef-500">利用するには:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-500">Getting Started:</span></span>

1. <span data-ttu-id="8a2ef-501">Excel を開く</span><span class="sxs-lookup"><span data-stu-id="8a2ef-501">Open Excel.</span></span>
2. <span data-ttu-id="8a2ef-502">3D アニメーション モデルを挿入します (まもなく Remix が公開されますが、今はここでアニメーション モデルにアクセスしてください: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="8a2ef-502">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="8a2ef-503">アニメーション モデルがエディターで再生されるようになります。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-503">The animated model will play in the editor!</span></span> <span data-ttu-id="8a2ef-504">スライドショー モードも再生されるようになりますので、確認してください。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-504">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="8a2ef-505">[3D 形式] リボンで、モデル内の他のアニメーション シーンを探索する</span><span class="sxs-lookup"><span data-stu-id="8a2ef-505">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="8a2ef-506">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-506">Scenarios to Try:</span></span>

1. <span data-ttu-id="8a2ef-507">アニメーション モデルを挿入し、エディターで再生します。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-507">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="8a2ef-508">アニメーション化されたモデルで使用できるアニメーション シーンについては、シーン ギャラリー ([3D 書式] リボンから利用できます) を参照してください。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-508">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="8a2ef-509">リボン、フローティング ツール バーまたはスペースバーを介してアニメーションを簡単に再生および一時停止することができます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-509">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="8a2ef-510">主な修正:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-510">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="8a2ef-511">すべてのアプリケーション</span><span class="sxs-lookup"><span data-stu-id="8a2ef-511">All Applications</span></span>
- <span data-ttu-id="8a2ef-512">Excel の間違ったアプリ アイコンがコンテキストメニューに表示されることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-512">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="8a2ef-513">アップデートをインストールした後に [ファイル メニュー] ボタンが消えてしまうことがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-513">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="8a2ef-514">ユーザー ライセンスに変更をおよぼす可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-514">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-515">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-515">Word</span></span> 
- <span data-ttu-id="8a2ef-516">特定のズーム レベルでテキストが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-516">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="8a2ef-517">Excel</span><span class="sxs-lookup"><span data-stu-id="8a2ef-517">Excel</span></span>
- <span data-ttu-id="8a2ef-518">編集後に、ブックを保存するかどうかを確認するメッセージが表示されない問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-518">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="8a2ef-519">ユーザーがブックを共有している場合に BeforeSave イベントが開始しない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-519">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="8a2ef-520">列のサイズを 6 ピクセル未満に変更すると誤ったエラーメッセージが表示される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-520">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="8a2ef-521">Excel が Application.Visible フラグを無視する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-521">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="8a2ef-522">トレースの矢印がアクティブでない固定ウィンドウに残る問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-522">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="8a2ef-523">ブックを開くときに通貨の日付のセルの書式設定が変わることがある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-523">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="8a2ef-524">ツールヒントが突然移動する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-524">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="8a2ef-525">Power Query エディターのローカライズの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-525">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="8a2ef-526">ブックを添付ファイルとしてメールで送信するときにブックが削除される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-526">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8a2ef-527">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8a2ef-527">PowerPoint</span></span>
- <span data-ttu-id="8a2ef-528">図形のコピーに通常以上に時間がかかる問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-528">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="8a2ef-529">Outlook</span><span class="sxs-lookup"><span data-stu-id="8a2ef-529">Outlook</span></span>
- <span data-ttu-id="8a2ef-530">描画ツールの使用中に Outlook がクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-530">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="8a2ef-531">HTML メールを作成する際のローカライズの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-531">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="8a2ef-532">下側のウィンドウが選択しにくい問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-532">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="8a2ef-533">Access</span><span class="sxs-lookup"><span data-stu-id="8a2ef-533">Access</span></span>
- <span data-ttu-id="8a2ef-534">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-534">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="8a2ef-535">Project</span><span class="sxs-lookup"><span data-stu-id="8a2ef-535">Project</span></span>
- <span data-ttu-id="8a2ef-536">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-536">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="8a2ef-537">2019 年 3 月 22 日</span><span class="sxs-lookup"><span data-stu-id="8a2ef-537">March 22, 2019</span></span>
<span data-ttu-id="8a2ef-538">バージョン 1904 (ビルド 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="8a2ef-538">Version 1904 (build 11514.20004)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="8a2ef-539">主な修正:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-539">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-540">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-540">Word</span></span> 
- <span data-ttu-id="8a2ef-541">UI に常に "変更を確認しています" と表示される問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-541">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="8a2ef-542">Excel</span><span class="sxs-lookup"><span data-stu-id="8a2ef-542">Excel</span></span>
- <span data-ttu-id="8a2ef-543">ワークシートを移動した後にアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-543">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="8a2ef-544">PDF 形式で保存した後にアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-544">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="8a2ef-545">保存ダイアログで韓国語の文字を使用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-545">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8a2ef-546">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8a2ef-546">PowerPoint</span></span>
- <span data-ttu-id="8a2ef-547">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-547">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="8a2ef-548">Outlook</span><span class="sxs-lookup"><span data-stu-id="8a2ef-548">Outlook</span></span>
- <span data-ttu-id="8a2ef-549">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-549">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="8a2ef-550">Access</span><span class="sxs-lookup"><span data-stu-id="8a2ef-550">Access</span></span>
- <span data-ttu-id="8a2ef-551">Access で余計なショートカットが作成されるという問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-551">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="8a2ef-552">リンクされた SharePoint のデータが正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-552">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="8a2ef-553">Project</span><span class="sxs-lookup"><span data-stu-id="8a2ef-553">Project</span></span>
- <span data-ttu-id="8a2ef-554">言語設定が中国語から英語に変わる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-554">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="8a2ef-555">SharePoint に同期するとアプリケーションがクラッシュする可能性がある問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-555">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="8a2ef-556">2019 年 3 月 15 日</span><span class="sxs-lookup"><span data-stu-id="8a2ef-556">March 15, 2019</span></span>
<span data-ttu-id="8a2ef-557">バージョン 1904 (ビルド 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="8a2ef-557">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="8a2ef-558">新機能:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-558">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-559">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-559">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="8a2ef-560">フォーカス モード</span><span class="sxs-lookup"><span data-stu-id="8a2ef-560">Focus mode</span></span>

<span data-ttu-id="8a2ef-561">気を散らさずに作業に集中するには、[表示]メニューの[フォーカス]に切り替えます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-561">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="8a2ef-562">Office 365 サブスクリプションが必要です。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-562">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="8a2ef-563">利用するには:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-563">Getting Started:</span></span>

<span data-ttu-id="8a2ef-564">リボンのステータス バー [フォーカス] ボタンの [フォーカス] ボタンをタブして表示</span><span class="sxs-lookup"><span data-stu-id="8a2ef-564">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="8a2ef-565">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-565">Scenarios to Try:</span></span>

<span data-ttu-id="8a2ef-566">フォーカス モードにしてフォーカス エクスペリエンスを経験する</span><span class="sxs-lookup"><span data-stu-id="8a2ef-566">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="8a2ef-567">主な修正:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-567">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-568">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-568">Word</span></span> 
- <span data-ttu-id="8a2ef-569">PDF として保存した文書の画像に間違った DPI が設定される問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-569">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="8a2ef-570">Excel</span><span class="sxs-lookup"><span data-stu-id="8a2ef-570">Excel</span></span>
- <span data-ttu-id="8a2ef-571">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-571">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8a2ef-572">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8a2ef-572">PowerPoint</span></span>
- <span data-ttu-id="8a2ef-573">コメント ウィンドウが正しく開閉しない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-573">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="8a2ef-574">動画を削除するとアプリケーションがクラッシュする可能性がある問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-574">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="8a2ef-575">アプリケーションの一部のインスタンスを起動できない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-575">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="8a2ef-576">Outlook</span><span class="sxs-lookup"><span data-stu-id="8a2ef-576">Outlook</span></span>
- <span data-ttu-id="8a2ef-577">日本語で表示するとき、開封確認が正しく表示されない問題を解決しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-577">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="8a2ef-578">Access</span><span class="sxs-lookup"><span data-stu-id="8a2ef-578">Access</span></span>
- <span data-ttu-id="8a2ef-579">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-579">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="8a2ef-580">Project</span><span class="sxs-lookup"><span data-stu-id="8a2ef-580">Project</span></span>
- <span data-ttu-id="8a2ef-581">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-581">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="8a2ef-582">2019 年 3 月 8 日</span><span class="sxs-lookup"><span data-stu-id="8a2ef-582">March 8, 2019</span></span> 
<span data-ttu-id="8a2ef-583">バージョン 1903 (ビルド 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="8a2ef-583">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="8a2ef-584">新機能:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-584">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-585">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-585">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="8a2ef-586">探している情報を Microsoft Search で検索する</span><span class="sxs-lookup"><span data-stu-id="8a2ef-586">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="8a2ef-587">Microsoft Search を使用して、作業を完了するのに必要なすべてのファイル、操作、連絡先、ヘルプを検索することができます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-587">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="8a2ef-588">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-588">Getting Started:</span></span>

- <span data-ttu-id="8a2ef-589">この機能は、ヘッダーの UI の上部に目立つように表示されています。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-589">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="8a2ef-590">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-590">Scenarios to Try:</span></span>

- <span data-ttu-id="8a2ef-591">大学、最近使用したドキュメント、最もよく使用するリボン コマンドなどを検索する</span><span class="sxs-lookup"><span data-stu-id="8a2ef-591">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="8a2ef-592">トピックや話題を検索して、その詳細情報を取得する</span><span class="sxs-lookup"><span data-stu-id="8a2ef-592">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="8a2ef-593">共同編集</span><span class="sxs-lookup"><span data-stu-id="8a2ef-593">Coauthoring</span></span>

<span data-ttu-id="8a2ef-594">マクロの文書を編集できない状況にうんざりしていませんか?</span><span class="sxs-lookup"><span data-stu-id="8a2ef-594">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="8a2ef-595">これで OneDrive for Business 上の docm ファイルで複数の作成者による同時編集が可能になります。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-595">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="8a2ef-596">利用するには:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-596">Getting Started:</span></span>

<span data-ttu-id="8a2ef-597">ユーザーは、この機能にアクセスするために UI のボタンを押す必要はありません。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-597">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="8a2ef-598">OneDrive for Business の docm ファイルでは、既定で有効になっています。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-598">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="8a2ef-599">したがって、試すには、ユーザーが docm ファイルを OneDrive for Business に保存しておく必要があります。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-599">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="8a2ef-600">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-600">Scenarios to Try:</span></span>

<span data-ttu-id="8a2ef-601">OneDrive for Business で docm ファイルを作成し、同僚と共有して共同作業を行います。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-601">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="8a2ef-602">主な修正:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-602">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-603">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-603">Word</span></span> 
- <span data-ttu-id="8a2ef-604">オプションの表示中に ‘Esc’ キーを押すと発生するクラッシュの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-604">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="8a2ef-605">コメントに返信するときにクラッシュが発生するという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-605">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="8a2ef-606">Word から PowerPoint Online へのコピーと貼り付けで発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-606">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="8a2ef-607">Excel</span><span class="sxs-lookup"><span data-stu-id="8a2ef-607">Excel</span></span>
- <span data-ttu-id="8a2ef-608">保護されたドキュメントや編集可能なドキュメントを開いているときに Excel でセルをコピーすると CPU 使用率が高くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-608">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8a2ef-609">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8a2ef-609">PowerPoint</span></span>
- <span data-ttu-id="8a2ef-610">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-610">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="8a2ef-611">Outlook</span><span class="sxs-lookup"><span data-stu-id="8a2ef-611">Outlook</span></span>
- <span data-ttu-id="8a2ef-612">Outlook Search が選択した日付の並べ替えを使用しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-612">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="8a2ef-613">"このタスクを開く" ワークフロー リボンのボタンが特定のメールで応答しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-613">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="8a2ef-614">ユーザーが Outlook の会議室の検索で空いている会議室を選択した後、社内の会議室がクリアされなくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-614">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="8a2ef-615">Access</span><span class="sxs-lookup"><span data-stu-id="8a2ef-615">Access</span></span>
- <span data-ttu-id="8a2ef-616">ダーク テーマで白い背景に白いテキストが表示されていた、保存済みのインポート/エクスポートのダイアログを修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-616">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="8a2ef-617">表のデザインのテキストボックスに [Yes/No] フィールドの DisplayControl プロパティを設定できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-617">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="8a2ef-618">Project</span><span class="sxs-lookup"><span data-stu-id="8a2ef-618">Project</span></span>
- <span data-ttu-id="8a2ef-619">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-619">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="8a2ef-620">2019 年 3 月 1 日</span><span class="sxs-lookup"><span data-stu-id="8a2ef-620">March 1, 2019</span></span> 
<span data-ttu-id="8a2ef-621">バージョン 1903 (ビルド 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="8a2ef-621">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="8a2ef-622">新機能</span><span class="sxs-lookup"><span data-stu-id="8a2ef-622">What's New</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-623">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-623">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="8a2ef-624">色の変更履歴、コメントとリアルタイムの共同作業の同期</span><span class="sxs-lookup"><span data-stu-id="8a2ef-624">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="8a2ef-625">当社の製品での、コメント、変更履歴と共同作業者のカーソルが同じ色で表示されることについての修正箇所を確認しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-625">Colors for Track Changes, Comments and Real-Time Collaboration in Sync: Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="8a2ef-626">利用するには:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-626">Getting Started:</span></span>

<span data-ttu-id="8a2ef-627">他のユーザーが開いている SharePoint または OneDrive のドキュメントを開きます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-627">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="8a2ef-628">ユーザーの変更履歴とコメントの色が、ユーザーのカーソルの色と一致することを確認します。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-628">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="8a2ef-629">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-629">Scenarios to Try:</span></span>

<span data-ttu-id="8a2ef-630">他のユーザーが開いている SharePoint または OneDrive のドキュメントを開きます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-630">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="8a2ef-631">ユーザーの変更履歴とコメントの色が、ユーザーのカーソルの色と一致することを確認します。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-631">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="8a2ef-632">主な修正:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-632">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-633">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-633">Word</span></span> 
- <span data-ttu-id="8a2ef-634">オプションの表示中に ‘Esc’ キーを押すと発生するクラッシュの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-634">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="8a2ef-635">Word から PowerPoint Online へのコピーと貼り付けで発生する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-635">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="8a2ef-636">Excel</span><span class="sxs-lookup"><span data-stu-id="8a2ef-636">Excel</span></span>
- <span data-ttu-id="8a2ef-637">保護されたドキュメントや編集可能なドキュメントを開いているときに Excel でセルをコピーすると CPU 使用率が高くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-637">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8a2ef-638">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8a2ef-638">PowerPoint</span></span>
- <span data-ttu-id="8a2ef-639">PowerPoint で @メンションを使用するときのスライド イメージのサイズに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-639">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="8a2ef-640">Outlook</span><span class="sxs-lookup"><span data-stu-id="8a2ef-640">Outlook</span></span>
- <span data-ttu-id="8a2ef-641">Outlook Search が選択した日付の並べ替えを使用しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-641">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="8a2ef-642">"このタスクを開く" ワークフロー リボンのボタンが特定のメールで応答しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-642">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="8a2ef-643">ユーザーが Outlook の会議室の検索で空いている会議室を選択した後、社内の会議室がクリアされなくなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-643">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="8a2ef-644">Access</span><span class="sxs-lookup"><span data-stu-id="8a2ef-644">Access</span></span>
- <span data-ttu-id="8a2ef-645">テーブルとデータソースの再リンクを確認するときに表示されるメッセージを更新しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-645">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="8a2ef-646">ダーク テーマで白い背景に白いテキストが表示されていた、保存済みのインポート/エクスポートのダイアログを修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-646">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="8a2ef-647">表のデザインのテキストボックスに [Yes/No] フィールドの表示コントロール プロパティを設定できなかった問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-647">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="8a2ef-648">Project</span><span class="sxs-lookup"><span data-stu-id="8a2ef-648">Project</span></span>
- <span data-ttu-id="8a2ef-649">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-649">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="8a2ef-650">2019 年 2 月 15 日</span><span class="sxs-lookup"><span data-stu-id="8a2ef-650">February 15, 2019</span></span> 
<span data-ttu-id="8a2ef-651">バージョン 1903 (ビルド 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="8a2ef-651">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="8a2ef-652">新機能:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-652">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8a2ef-653">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8a2ef-653">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="8a2ef-654">画面切り替え効果の機能強化 - 名前で変形</span><span class="sxs-lookup"><span data-stu-id="8a2ef-654">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="8a2ef-655">変形する図形を指定します</span><span class="sxs-lookup"><span data-stu-id="8a2ef-655">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="8a2ef-656">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-656">Getting Started:</span></span>

- <span data-ttu-id="8a2ef-657">[変形] で 2 つのオブジェクトを同じオブジェクトとして扱うために、[選択] ウィンドウを使って図形の名前を変更することができます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-657">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="8a2ef-658">[変形] で名前を使って既定のマッチング動作を上書きするには、</span><span class="sxs-lookup"><span data-stu-id="8a2ef-658">The name must be prefaced with “!!”</span></span> <span data-ttu-id="8a2ef-659">名前の前に "!!" (2 つの感嘆符) を付ける必要があります (例: "!!Name")。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-659">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="8a2ef-660">名前の先頭に "!!" が付いていない図形の名前変更を続行できます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-660">Users can continue to rename shapes with any name that doesn’t start with “!!”</span></span> <span data-ttu-id="8a2ef-661">[変形] の動作が変更されることを気にする必要はありません</span><span class="sxs-lookup"><span data-stu-id="8a2ef-661">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="8a2ef-662">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-662">Scenarios to Try:</span></span>

- <span data-ttu-id="8a2ef-663">スライドに図形 (たとえば、四角形) を挿入します</span><span class="sxs-lookup"><span data-stu-id="8a2ef-663">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="8a2ef-664">新しいスライドを作成します</span><span class="sxs-lookup"><span data-stu-id="8a2ef-664">Create a new slide</span></span>
- <span data-ttu-id="8a2ef-665">2 枚目のスライドに別の図形 (たとえば、三角形) を挿入します</span><span class="sxs-lookup"><span data-stu-id="8a2ef-665">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="8a2ef-666">[オブジェクトの選択と表示] でスライド 1 の四角形の名前を "!!shape" に変更し、スライド 2 の三角形の名前を "!!shape" に変更します</span><span class="sxs-lookup"><span data-stu-id="8a2ef-666">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="8a2ef-667">2 枚目のスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="8a2ef-667">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="8a2ef-668">画面切り替え効果の機能強化 - SmartArt</span><span class="sxs-lookup"><span data-stu-id="8a2ef-668">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="8a2ef-669">SmartArt の変形をより滑らかに切り替え</span><span class="sxs-lookup"><span data-stu-id="8a2ef-669">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="8a2ef-670">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-670">Getting Started:</span></span>

<span data-ttu-id="8a2ef-671">SmartArt と同様の方法で変形を使用します</span><span class="sxs-lookup"><span data-stu-id="8a2ef-671">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="8a2ef-672">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-672">Scenarios to Try:</span></span>

- <span data-ttu-id="8a2ef-673">スライドに SmartArt を挿入します</span><span class="sxs-lookup"><span data-stu-id="8a2ef-673">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="8a2ef-674">スライドを複製します</span><span class="sxs-lookup"><span data-stu-id="8a2ef-674">Duplicate the Slide</span></span>
- <span data-ttu-id="8a2ef-675">複製されたスライド上で SmartArt のサイズ変更/変更/移動を行います</span><span class="sxs-lookup"><span data-stu-id="8a2ef-675">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="8a2ef-676">複製されたスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="8a2ef-676">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="8a2ef-677">画面切り替え効果の機能強化 - 表</span><span class="sxs-lookup"><span data-stu-id="8a2ef-677">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="8a2ef-678">表の変形をより滑らかに切り替え</span><span class="sxs-lookup"><span data-stu-id="8a2ef-678">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="8a2ef-679">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-679">Getting Started:</span></span>
<span data-ttu-id="8a2ef-680">表と同様の方法で変形を使用します</span><span class="sxs-lookup"><span data-stu-id="8a2ef-680">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="8a2ef-681">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-681">Scenarios to Try:</span></span>

- <span data-ttu-id="8a2ef-682">スライドに表を挿入します</span><span class="sxs-lookup"><span data-stu-id="8a2ef-682">Insert a Table in a slide</span></span>
- <span data-ttu-id="8a2ef-683">スライドを複製します</span><span class="sxs-lookup"><span data-stu-id="8a2ef-683">Duplicate the slide</span></span>
- <span data-ttu-id="8a2ef-684">複製されたスライド上で表のサイズ変更/変更/移動を行います</span><span class="sxs-lookup"><span data-stu-id="8a2ef-684">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="8a2ef-685">複製されたスライドに [変形] を適用します</span><span class="sxs-lookup"><span data-stu-id="8a2ef-685">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="8a2ef-686">Word、Excel、PowerPoint、OneNote、Access、Project、Publisher、Visio</span><span class="sxs-lookup"><span data-stu-id="8a2ef-686">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="8a2ef-687">アカウントをシームレスに切り替える</span><span class="sxs-lookup"><span data-stu-id="8a2ef-687">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="8a2ef-688">新しいアカウント マネージャーでは、仕事用アカウントと個人用アカウントのすべてが 1 か所に表示されます。また、アカウントを自由に切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-688">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="8a2ef-689">この更新されたエクスペリエンスでは、ログイン方法がわかりやすくなりました。また、先にサインアウトしたり複雑なダイアログを操作したりする必要なく、仕事用アカウントと個人用アカウントを切り替えることができるようになりました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-689">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="8a2ef-691">次の操作を試してみてください:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-691">Scenarios to Try:</span></span>
- <span data-ttu-id="8a2ef-692">アカウントを切り替えます</span><span class="sxs-lookup"><span data-stu-id="8a2ef-692">Switch between accounts</span></span>
- <span data-ttu-id="8a2ef-693">新しいアカウントを追加します [注: [ファイル]、[アカウント]、[接続済みサービス] の順に移動してから、仕事用アカウントに接続されている個人用サービス (またはその逆) を削除することができます]</span><span class="sxs-lookup"><span data-stu-id="8a2ef-693">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="8a2ef-694">アカウントからサインアウトします</span><span class="sxs-lookup"><span data-stu-id="8a2ef-694">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="8a2ef-695">主な修正:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-695">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-696">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-696">Word</span></span> 
- <span data-ttu-id="8a2ef-697">表と画像のコンテキスト プレビューに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-697">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="8a2ef-698">Excel</span><span class="sxs-lookup"><span data-stu-id="8a2ef-698">Excel</span></span>
- <span data-ttu-id="8a2ef-699">[黒] のテーマでオートフィルターの [検索] フィールドのテキストが白くなる問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-699">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="8a2ef-700">新しい Office アドインの同意の UI に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-700">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8a2ef-701">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8a2ef-701">PowerPoint</span></span>
- <span data-ttu-id="8a2ef-702">ノート PC またはタブレットでスライドショーを表示すると、表示が自動的に拡大される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="8a2ef-702">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="8a2ef-703">Outlook</span><span class="sxs-lookup"><span data-stu-id="8a2ef-703">Outlook</span></span>
- <span data-ttu-id="8a2ef-704">[OneNote に送る] ボタンの表示に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-704">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="8a2ef-705">Access</span><span class="sxs-lookup"><span data-stu-id="8a2ef-705">Access</span></span>
- <span data-ttu-id="8a2ef-706">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-706">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="8a2ef-707">Project</span><span class="sxs-lookup"><span data-stu-id="8a2ef-707">Project</span></span>
- <span data-ttu-id="8a2ef-708">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-708">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="8a2ef-709">2019 年 2 月 11 日</span><span class="sxs-lookup"><span data-stu-id="8a2ef-709">February 11, 2019</span></span>
<span data-ttu-id="8a2ef-710">バージョン 1903 (ビルド 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="8a2ef-710">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="8a2ef-711">主な修正:</span><span class="sxs-lookup"><span data-stu-id="8a2ef-711">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-712">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-712">Word</span></span> 
- <span data-ttu-id="8a2ef-713">一部のカスタマイズされたスタイルを Word Online に適用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-713">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="8a2ef-714">Word のリッチ オブジェクトでのコンテキスト プレビューに関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-714">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="8a2ef-715">リストを貼り付けると Word がクラッシュする問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-715">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="8a2ef-716">Excel</span><span class="sxs-lookup"><span data-stu-id="8a2ef-716">Excel</span></span>
- <span data-ttu-id="8a2ef-717">通貨記号がない場合に、数値の書式の後ろに追加されるスペースが表示されない問題を修正しました特殊文字</span><span class="sxs-lookup"><span data-stu-id="8a2ef-717">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="8a2ef-718">株価の自動検出に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-718">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8a2ef-719">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8a2ef-719">PowerPoint</span></span>
- <span data-ttu-id="8a2ef-720">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-720">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="8a2ef-721">Outlook</span><span class="sxs-lookup"><span data-stu-id="8a2ef-721">Outlook</span></span>
- <span data-ttu-id="8a2ef-722">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-722">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="8a2ef-723">Access</span><span class="sxs-lookup"><span data-stu-id="8a2ef-723">Access</span></span>
- <span data-ttu-id="8a2ef-724">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-724">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="8a2ef-725">Project</span><span class="sxs-lookup"><span data-stu-id="8a2ef-725">Project</span></span>
- <span data-ttu-id="8a2ef-726">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-726">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="8a2ef-727">2019 年 2 月 1 日</span><span class="sxs-lookup"><span data-stu-id="8a2ef-727">February 1, 2019</span></span> 
<span data-ttu-id="8a2ef-728">バージョン 1902 (ビルド 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="8a2ef-728">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="8a2ef-729">主な修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-729">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="8a2ef-730">Word</span><span class="sxs-lookup"><span data-stu-id="8a2ef-730">Word</span></span> 
- <span data-ttu-id="8a2ef-731">埋め込まれた Excel の表のセルのサイズ変更に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-731">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="8a2ef-732">描画キャンバス内の図形のコピー/貼り付けの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-732">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="8a2ef-733">Excel</span><span class="sxs-lookup"><span data-stu-id="8a2ef-733">Excel</span></span>
- <span data-ttu-id="8a2ef-734">Excel Web App からファイルを開く際の問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-734">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="8a2ef-735">CSV ファイルを .XLSX として保存する際にファイル名のサイズが原因で失敗する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-735">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="8a2ef-736">コンテキスト メニューのオプションの表示に関してコンテキスト メニューを修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-736">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="8a2ef-737">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="8a2ef-737">PowerPoint</span></span>
- <span data-ttu-id="8a2ef-738">角かっこを入力するためにユーザーがキーボード ショートカット Ctrl+Alt+7 および Ctrl+Alt+8 を使用できない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-738">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="8a2ef-739">ローカル ビデオを PowerPoint に挿入すると C ドライブのディスク領域が減ってしまう問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-739">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="8a2ef-740">一部のユーザーに表示されていなかった [Microsoft Stream に公開する] ボタンを修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-740">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="8a2ef-741">Outlook</span><span class="sxs-lookup"><span data-stu-id="8a2ef-741">Outlook</span></span>
- <span data-ttu-id="8a2ef-742">カレンダーのタスク ビューでタスクの件名が正しく表示されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-742">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="8a2ef-743">Access</span><span class="sxs-lookup"><span data-stu-id="8a2ef-743">Access</span></span>
- <span data-ttu-id="8a2ef-744">グラフのスケーリングの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="8a2ef-744">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="8a2ef-745">Project</span><span class="sxs-lookup"><span data-stu-id="8a2ef-745">Project</span></span>
- <span data-ttu-id="8a2ef-746">パフォーマンスと安定性のさまざまな問題を修正</span><span class="sxs-lookup"><span data-stu-id="8a2ef-746">Various performance and stability fixes</span></span>
