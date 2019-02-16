---
<span data-ttu-id="88ea1-101">タイトル: 「Release Notes for Office insider」 (執筆者向け) andrewmo: mikho manager: andrewmo ms. date: 2/15/2019 ミリ秒: Win32 Fast ms. トピック: リファレンス: proplus-送受信: RelNotes_ProPlus (::説明: "主要な新機能、修正プログラム、既知の問題の最新リストを、insider Fast ユーザーに提供します。</span><span class="sxs-lookup"><span data-stu-id="88ea1-101">title: "Release Notes for Office Insiders" ms.author: andrewmo author: mikho manager: andrewmo ms.date: 2/15/2019 ms.audience: Win32 Fast ms.topic: reference ms.service: o365-proplus- localization_priority: Critical ms.collection: RelNotes_ProPlus description: "Provides Insiders Fast audience with the latest list of key new features, fixes or known issues</span></span>
---

# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="88ea1-102">Office insider のリリースノート</span><span class="sxs-lookup"><span data-stu-id="88ea1-102">Release Notes for Office Insiders</span></span>

<span data-ttu-id="88ea1-p101">この記事には、Windows デスクトップ用の Word、Excel、PowerPoint、Outlook、Access、Project の Insider ビルドのリリースノートが記載されています。毎週、興味深い新機能、重要な解決策、および重要な問題については強調します。多くの場合、機能 (および場合によっては修正) は、長期間にわたって公開者にロールアウトされます。これにより、機能をより幅広い対象ユーザーに公開する前に、円滑に機能することができます。そのため、以下のような情報が表示されない場合でも、最終的には取得しないようにしてください。</span><span class="sxs-lookup"><span data-stu-id="88ea1-p101">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop. Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about. Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time. This allows us to ensure that things are working smoothly before releasing the feature to a wider audience. So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

## <a name="february-12-2019-version-1902-build-1133020014"></a><span data-ttu-id="88ea1-108">12 2019 年2月バージョン 1902 (ビルド 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="88ea1-108">February 12 2019 Version 1902 (build 11330.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="88ea1-109">新機能:</span><span class="sxs-lookup"><span data-stu-id="88ea1-109">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="88ea1-110">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="88ea1-110">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="88ea1-111">変形遷移の拡張機能-名前別の変形</span><span class="sxs-lookup"><span data-stu-id="88ea1-111">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="88ea1-112">変形する図形を指定する</span><span class="sxs-lookup"><span data-stu-id="88ea1-112">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="88ea1-113">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="88ea1-113">Getting Started:</span></span>

- <span data-ttu-id="88ea1-114">2つのオブジェクトを同じオブジェクトとして扱うように変形を取得するには、選択ウィンドウを使用して図形の名前を変更します。</span><span class="sxs-lookup"><span data-stu-id="88ea1-114">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="88ea1-p102">名前の先頭に "!!" を付ける必要があります。(2 つの感嘆符) を使用して、既定の一致動作を上書きします。たとえば、"!!拡張子</span><span class="sxs-lookup"><span data-stu-id="88ea1-p102">The name must be prefaced with “!!” (two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="88ea1-p103">ユーザーは、"!!" で始まらない任意の名前を使用して図形の名前を変更できます。</span><span class="sxs-lookup"><span data-stu-id="88ea1-p103">Users can continue to rename shapes with any name that doesn’t start with “!!” without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="88ea1-119">次のシナリオを試してみてください。</span><span class="sxs-lookup"><span data-stu-id="88ea1-119">Scenarios to Try:</span></span>

- <span data-ttu-id="88ea1-120">スライドに図形を挿入する (たとえば四角形)</span><span class="sxs-lookup"><span data-stu-id="88ea1-120">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="88ea1-121">新しいスライドを作成する</span><span class="sxs-lookup"><span data-stu-id="88ea1-121">Create a new slide</span></span>
- <span data-ttu-id="88ea1-122">2番目のスライドに別の図形を挿入する (三角形の音声)</span><span class="sxs-lookup"><span data-stu-id="88ea1-122">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="88ea1-123">selectionpane を開き、slide 1 の四角形の名前をに変更します。図形 "、スライド2の三角形の名前を"!!図形</span><span class="sxs-lookup"><span data-stu-id="88ea1-123">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="88ea1-124">2番目のスライドに変形を適用する</span><span class="sxs-lookup"><span data-stu-id="88ea1-124">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="88ea1-125">変形遷移の拡張機能-SmartArt</span><span class="sxs-lookup"><span data-stu-id="88ea1-125">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="88ea1-126">滑らかな遷移を伴う SmartArt の変形</span><span class="sxs-lookup"><span data-stu-id="88ea1-126">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="88ea1-127">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="88ea1-127">Getting Started:</span></span>

<span data-ttu-id="88ea1-128">SmartArt と同じ方法で変形を使用する</span><span class="sxs-lookup"><span data-stu-id="88ea1-128">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="88ea1-129">次のシナリオを試してみてください。</span><span class="sxs-lookup"><span data-stu-id="88ea1-129">Scenarios to Try:</span></span>

- <span data-ttu-id="88ea1-130">スライドに SmartArt を挿入する</span><span class="sxs-lookup"><span data-stu-id="88ea1-130">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="88ea1-131">スライドを複製する</span><span class="sxs-lookup"><span data-stu-id="88ea1-131">Duplicate the Slide</span></span>
- <span data-ttu-id="88ea1-132">複製したスライドの SmartArt のサイズ変更/変更/移動</span><span class="sxs-lookup"><span data-stu-id="88ea1-132">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="88ea1-133">複製したスライドに変形を適用する</span><span class="sxs-lookup"><span data-stu-id="88ea1-133">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="88ea1-134">変形遷移の強化-表</span><span class="sxs-lookup"><span data-stu-id="88ea1-134">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="88ea1-135">滑らかな遷移を含むテーブルの変形</span><span class="sxs-lookup"><span data-stu-id="88ea1-135">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="88ea1-136">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="88ea1-136">Getting Started:</span></span>
<span data-ttu-id="88ea1-137">表と同じ方法で変形を使用します。</span><span class="sxs-lookup"><span data-stu-id="88ea1-137">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="88ea1-138">次のシナリオを試してみてください。</span><span class="sxs-lookup"><span data-stu-id="88ea1-138">Scenarios to Try:</span></span>

- <span data-ttu-id="88ea1-139">スライドに表を挿入する</span><span class="sxs-lookup"><span data-stu-id="88ea1-139">Insert a Table in a slide</span></span>
- <span data-ttu-id="88ea1-140">スライドを複製する</span><span class="sxs-lookup"><span data-stu-id="88ea1-140">Duplicate the slide</span></span>
- <span data-ttu-id="88ea1-141">複製したスライドの表のサイズ変更/変更/移動</span><span class="sxs-lookup"><span data-stu-id="88ea1-141">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="88ea1-142">複製したスライドに変形を適用する</span><span class="sxs-lookup"><span data-stu-id="88ea1-142">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="88ea1-143">Word、Excel、PowerPoint、OneNote、Access、Project、Publisher & Visio</span><span class="sxs-lookup"><span data-stu-id="88ea1-143">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="88ea1-144">アカウントをシームレスに切り替える</span><span class="sxs-lookup"><span data-stu-id="88ea1-144">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="88ea1-p104">新しいアカウントマネージャーは、すべての仕事と個人のアカウントを1つの場所に表示し、それらを切り替えることができるようにします。この更新された操作により、ログインしている方法が明確になります。また、最初にサインインしなくても、または複雑なダイアログを使用して仕事と個人のアカウントを切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="88ea1-p104">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them. This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>



#### <a name="scenarios-to-try"></a><span data-ttu-id="88ea1-147">次のシナリオを試してみてください。</span><span class="sxs-lookup"><span data-stu-id="88ea1-147">Scenarios to Try:</span></span>
- <span data-ttu-id="88ea1-148">アカウントを切り替える</span><span class="sxs-lookup"><span data-stu-id="88ea1-148">Switch between accounts</span></span>
- <span data-ttu-id="88ea1-149">新しいアカウントを追加する [メモ: 最初にファイルに移動しますか?]アカウント |接続されたサービスと、勤務先のアカウントに接続されているすべての個人用サービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="88ea1-149">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="88ea1-150">アカウントからサインアウトする</span><span class="sxs-lookup"><span data-stu-id="88ea1-150">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="88ea1-151">注目すべき修正:</span><span class="sxs-lookup"><span data-stu-id="88ea1-151">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="88ea1-152">Word</span><span class="sxs-lookup"><span data-stu-id="88ea1-152">Word</span></span> 
- <span data-ttu-id="88ea1-153">表 & の画像のコンテキストプレビューに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="88ea1-153">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="88ea1-154">Excel</span><span class="sxs-lookup"><span data-stu-id="88ea1-154">Excel</span></span>
- <span data-ttu-id="88ea1-155">オートフィルター検索フィールドのテキストが黒のテーマで白になっているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="88ea1-155">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="88ea1-156">新しい Office アドインに関する同意 UI の問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="88ea1-156">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="88ea1-157">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="88ea1-157">PowerPoint</span></span>
- <span data-ttu-id="88ea1-158">ラップトップまたはタブレットでスライドショーを提示する際に、自動的に表示が拡張される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="88ea1-158">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="88ea1-159">Outlook</span><span class="sxs-lookup"><span data-stu-id="88ea1-159">Outlook</span></span>
- <span data-ttu-id="88ea1-160">[OneNote に送る] ボタンの表示に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="88ea1-160">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="88ea1-161">Access</span><span class="sxs-lookup"><span data-stu-id="88ea1-161">Access</span></span>
- <span data-ttu-id="88ea1-162">さまざまなパフォーマンスと安定性の修正</span><span class="sxs-lookup"><span data-stu-id="88ea1-162">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="88ea1-163">Project</span><span class="sxs-lookup"><span data-stu-id="88ea1-163">Project</span></span>
- <span data-ttu-id="88ea1-164">さまざまなパフォーマンスと安定性の修正</span><span class="sxs-lookup"><span data-stu-id="88ea1-164">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-9-2019-version-1902-build-1133020014"></a><span data-ttu-id="88ea1-165">9 2019 年2月バージョン 1902 (ビルド 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="88ea1-165">February 9 2019 Version 1902 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="88ea1-166">注目すべき修正:</span><span class="sxs-lookup"><span data-stu-id="88ea1-166">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="88ea1-167">Word</span><span class="sxs-lookup"><span data-stu-id="88ea1-167">Word</span></span> 
- <span data-ttu-id="88ea1-168">カスタマイズしたスタイルが word online に適用されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="88ea1-168">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="88ea1-169">Word のリッチオブジェクトに関するコンテキストプレビューの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="88ea1-169">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="88ea1-170">リストを貼り付けると Word がクラッシュするという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="88ea1-170">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="88ea1-171">Excel</span><span class="sxs-lookup"><span data-stu-id="88ea1-171">Excel</span></span>
- <span data-ttu-id="88ea1-172">通貨記号が表示されていない場合に、数字形式の後にスペースを追加すると、問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="88ea1-172">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="88ea1-173">株式の自動検出に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="88ea1-173">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="88ea1-174">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="88ea1-174">PowerPoint</span></span>
- <span data-ttu-id="88ea1-175">さまざまなパフォーマンスと安定性の修正</span><span class="sxs-lookup"><span data-stu-id="88ea1-175">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="88ea1-176">Outlook</span><span class="sxs-lookup"><span data-stu-id="88ea1-176">Outlook</span></span>
- <span data-ttu-id="88ea1-177">さまざまなパフォーマンスと安定性の修正</span><span class="sxs-lookup"><span data-stu-id="88ea1-177">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="88ea1-178">Access</span><span class="sxs-lookup"><span data-stu-id="88ea1-178">Access</span></span>
- <span data-ttu-id="88ea1-179">さまざまなパフォーマンスと安定性の修正</span><span class="sxs-lookup"><span data-stu-id="88ea1-179">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="88ea1-180">Project</span><span class="sxs-lookup"><span data-stu-id="88ea1-180">Project</span></span>
- <span data-ttu-id="88ea1-181">さまざまなパフォーマンスと安定性の修正</span><span class="sxs-lookup"><span data-stu-id="88ea1-181">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="january-30-2019-version-1902-build-1132620000"></a><span data-ttu-id="88ea1-182">2019年1月30日バージョン 1902 (ビルド 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="88ea1-182">January 30, 2019 Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="88ea1-183">注目すべき修正</span><span class="sxs-lookup"><span data-stu-id="88ea1-183">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="88ea1-184">Word</span><span class="sxs-lookup"><span data-stu-id="88ea1-184">Word</span></span> 
- <span data-ttu-id="88ea1-185">埋め込まれた Excel テーブルのセルのサイズを変更すると、問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="88ea1-185">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="88ea1-186">描画キャンバスで図形のコピーと貼り付けを行うと、問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="88ea1-186">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="88ea1-187">Excel</span><span class="sxs-lookup"><span data-stu-id="88ea1-187">Excel</span></span>
- <span data-ttu-id="88ea1-188">Excel Web app からファイルを開くときに問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="88ea1-188">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="88ea1-189">CSV ファイルをとして保存するという問題が修正されました。ファイル名のサイズが原因で、.xlsx が失敗しました</span><span class="sxs-lookup"><span data-stu-id="88ea1-189">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="88ea1-190">ショートカットメニューのオプションを表示するようにコンテキストメニューを修正しました。</span><span class="sxs-lookup"><span data-stu-id="88ea1-190">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="88ea1-191">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="88ea1-191">PowerPoint</span></span>
- <span data-ttu-id="88ea1-192">ユーザーがキーボードショートカット ctrl + alt + 7/ctrl + alt + 8 を使用して角かっこを入力できなかったという発行を修正しました。</span><span class="sxs-lookup"><span data-stu-id="88ea1-192">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="88ea1-193">ローカルビデオを PPT に挿入すると、「C」ドライブのディスク容量が減少するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="88ea1-193">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="88ea1-194">一部のユーザーに表示されていない [Microsoft Stream への発行] ボタンを修正しました</span><span class="sxs-lookup"><span data-stu-id="88ea1-194">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="88ea1-195">Outlook</span><span class="sxs-lookup"><span data-stu-id="88ea1-195">Outlook</span></span>
- <span data-ttu-id="88ea1-196">予定表のタスクビューで、タスクの件名が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="88ea1-196">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="88ea1-197">Access</span><span class="sxs-lookup"><span data-stu-id="88ea1-197">Access</span></span>
- <span data-ttu-id="88ea1-198">グラフのスケーリングの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="88ea1-198">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="88ea1-199">Project</span><span class="sxs-lookup"><span data-stu-id="88ea1-199">Project</span></span>
- <span data-ttu-id="88ea1-200">さまざまなパフォーマンスと安定性の修正</span><span class="sxs-lookup"><span data-stu-id="88ea1-200">Various performance and stability fixes</span></span>
