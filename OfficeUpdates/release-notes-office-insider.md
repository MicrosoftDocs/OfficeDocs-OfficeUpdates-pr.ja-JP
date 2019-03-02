---
<span data-ttu-id="c14d6-101">タイトル: 「Release Notes for Office insider」 (執筆者向け) andrewmo: mikho manager: andrewmo ms. date: 3/1/2019 ミリ秒: Win32 Fast ms. トピック: リファレンス: proplus-送受信: RelNotes_ProPlus (::説明: "主要な新機能、修正プログラム、既知の問題の最新リストを、insider Fast ユーザーに提供します。</span><span class="sxs-lookup"><span data-stu-id="c14d6-101">title: "Release Notes for Office Insiders" ms.author: andrewmo author: mikho manager: andrewmo ms.date: 3/1/2019 ms.audience: Win32 Fast ms.topic: reference ms.service: o365-proplus- localization_priority: Critical ms.collection: RelNotes_ProPlus description: "Provides Insiders Fast audience with the latest list of key new features, fixes or known issues</span></span>
---

# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="c14d6-102">Office insider のリリースノート</span><span class="sxs-lookup"><span data-stu-id="c14d6-102">Release Notes for Office Insiders</span></span>

<span data-ttu-id="c14d6-p101">この記事には、Windows デスクトップ用の Word、Excel、PowerPoint、Outlook、Access、Project の Insider ビルドのリリースノートが記載されています。毎週、興味深い新機能、重要な解決策、および重要な問題については強調します。多くの場合、機能 (および場合によっては修正) は、長期間にわたって公開者にロールアウトされます。これにより、機能をより幅広い対象ユーザーに公開する前に、円滑に機能することができます。そのため、以下のような情報が表示されない場合でも、最終的には取得しないようにしてください。</span><span class="sxs-lookup"><span data-stu-id="c14d6-p101">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop. Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about. Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time. This allows us to ensure that things are working smoothly before releasing the feature to a wider audience. So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

## <a name="february-25-2019-version-1903-build-1133020014"></a><span data-ttu-id="c14d6-108">2019年2月25日バージョン 1903 (ビルド 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="c14d6-108">February 25, 2019 Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="c14d6-109">注目すべき修正:</span><span class="sxs-lookup"><span data-stu-id="c14d6-109">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c14d6-110">Word</span><span class="sxs-lookup"><span data-stu-id="c14d6-110">Word</span></span> 
- <span data-ttu-id="c14d6-111">[オプション] で [ESC] を押したときに発生したクラッシュの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="c14d6-111">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="c14d6-112">Word から PowerPoint Online にコピー & 貼り付けを行うと、問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c14d6-112">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="c14d6-113">Excel</span><span class="sxs-lookup"><span data-stu-id="c14d6-113">Excel</span></span>
- <span data-ttu-id="c14d6-114">保護されたドキュメントおよび編集可能なドキュメントが開かれたときに、Excel のセルをコピーすると CPU 使用率が高くなるという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c14d6-114">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c14d6-115">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c14d6-115">PowerPoint</span></span>
- <span data-ttu-id="c14d6-116">PowerPoint で @Mentions を使用すると、スライドイメージサイズの問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c14d6-116">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="c14d6-117">Outlook</span><span class="sxs-lookup"><span data-stu-id="c14d6-117">Outlook</span></span>
- <span data-ttu-id="c14d6-118">選択した時系列の並べ替えが Outlook の検索に許可されていないという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c14d6-118">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="c14d6-119">特定の電子メールに対して [このタスクを開く] ワークフローリボンボタンが応答しない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="c14d6-119">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="c14d6-120">ユーザーが会議室のファインダーで利用可能な会議室を選択した後に Outlook がオンプレミスルームでクリアされなかったという問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c14d6-120">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="c14d6-121">Access</span><span class="sxs-lookup"><span data-stu-id="c14d6-121">Access</span></span>
- <span data-ttu-id="c14d6-122">datasource を使用して再リンクテーブルを確認するときに表示されるプロンプトテキストを更新しました</span><span class="sxs-lookup"><span data-stu-id="c14d6-122">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="c14d6-123">白の背景に白いテキストを含む保存済みのインポート/エクスポートダイアログを暗いテーマで修正しました</span><span class="sxs-lookup"><span data-stu-id="c14d6-123">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="c14d6-124">Yes/No 型フィールドの Display コントロールプロパティをテーブルデザインのテキストボックスに設定できないという問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="c14d6-124">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="c14d6-125">Project</span><span class="sxs-lookup"><span data-stu-id="c14d6-125">Project</span></span>
- <span data-ttu-id="c14d6-126">さまざまなパフォーマンスと安定性の修正</span><span class="sxs-lookup"><span data-stu-id="c14d6-126">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-12-2019-version-1903-build-1133020014"></a><span data-ttu-id="c14d6-127">12 2019 年2月バージョン 1903 (ビルド 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="c14d6-127">February 12 2019 Version 1903 (build 11330.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="c14d6-128">新機能:</span><span class="sxs-lookup"><span data-stu-id="c14d6-128">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c14d6-129">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c14d6-129">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="c14d6-130">変形遷移の拡張機能-名前別の変形</span><span class="sxs-lookup"><span data-stu-id="c14d6-130">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="c14d6-131">変形する図形を指定する</span><span class="sxs-lookup"><span data-stu-id="c14d6-131">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c14d6-132">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="c14d6-132">Getting Started:</span></span>

- <span data-ttu-id="c14d6-133">2つのオブジェクトを同じオブジェクトとして扱うように変形を取得するには、選択ウィンドウを使用して図形の名前を変更します。</span><span class="sxs-lookup"><span data-stu-id="c14d6-133">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="c14d6-p102">名前の先頭に "!!" を付ける必要があります。(2 つの感嘆符) を使用して、既定の一致動作を上書きします。たとえば、"!!拡張子</span><span class="sxs-lookup"><span data-stu-id="c14d6-p102">The name must be prefaced with “!!” (two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="c14d6-p103">ユーザーは、"!!" で始まらない任意の名前を使用して図形の名前を変更できます。</span><span class="sxs-lookup"><span data-stu-id="c14d6-p103">Users can continue to rename shapes with any name that doesn’t start with “!!” without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c14d6-138">次のシナリオを試してみてください。</span><span class="sxs-lookup"><span data-stu-id="c14d6-138">Scenarios to Try:</span></span>

- <span data-ttu-id="c14d6-139">スライドに図形を挿入する (たとえば四角形)</span><span class="sxs-lookup"><span data-stu-id="c14d6-139">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="c14d6-140">新しいスライドを作成する</span><span class="sxs-lookup"><span data-stu-id="c14d6-140">Create a new slide</span></span>
- <span data-ttu-id="c14d6-141">2番目のスライドに別の図形を挿入する (三角形の音声)</span><span class="sxs-lookup"><span data-stu-id="c14d6-141">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="c14d6-142">selectionpane を開き、slide 1 の四角形の名前をに変更します。図形 "、スライド2の三角形の名前を"!!図形</span><span class="sxs-lookup"><span data-stu-id="c14d6-142">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="c14d6-143">2番目のスライドに変形を適用する</span><span class="sxs-lookup"><span data-stu-id="c14d6-143">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="c14d6-144">変形遷移の拡張機能-SmartArt</span><span class="sxs-lookup"><span data-stu-id="c14d6-144">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="c14d6-145">滑らかな遷移を伴う SmartArt の変形</span><span class="sxs-lookup"><span data-stu-id="c14d6-145">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c14d6-146">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="c14d6-146">Getting Started:</span></span>

<span data-ttu-id="c14d6-147">SmartArt と同じ方法で変形を使用する</span><span class="sxs-lookup"><span data-stu-id="c14d6-147">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c14d6-148">次のシナリオを試してみてください。</span><span class="sxs-lookup"><span data-stu-id="c14d6-148">Scenarios to Try:</span></span>

- <span data-ttu-id="c14d6-149">スライドに SmartArt を挿入する</span><span class="sxs-lookup"><span data-stu-id="c14d6-149">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="c14d6-150">スライドを複製する</span><span class="sxs-lookup"><span data-stu-id="c14d6-150">Duplicate the Slide</span></span>
- <span data-ttu-id="c14d6-151">複製したスライドの SmartArt のサイズ変更/変更/移動</span><span class="sxs-lookup"><span data-stu-id="c14d6-151">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="c14d6-152">複製したスライドに変形を適用する</span><span class="sxs-lookup"><span data-stu-id="c14d6-152">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="c14d6-153">変形遷移の強化-表</span><span class="sxs-lookup"><span data-stu-id="c14d6-153">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="c14d6-154">滑らかな遷移を含むテーブルの変形</span><span class="sxs-lookup"><span data-stu-id="c14d6-154">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="c14d6-155">作業の開始:</span><span class="sxs-lookup"><span data-stu-id="c14d6-155">Getting Started:</span></span>
<span data-ttu-id="c14d6-156">表と同じ方法で変形を使用します。</span><span class="sxs-lookup"><span data-stu-id="c14d6-156">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="c14d6-157">次のシナリオを試してみてください。</span><span class="sxs-lookup"><span data-stu-id="c14d6-157">Scenarios to Try:</span></span>

- <span data-ttu-id="c14d6-158">スライドに表を挿入する</span><span class="sxs-lookup"><span data-stu-id="c14d6-158">Insert a Table in a slide</span></span>
- <span data-ttu-id="c14d6-159">スライドを複製する</span><span class="sxs-lookup"><span data-stu-id="c14d6-159">Duplicate the slide</span></span>
- <span data-ttu-id="c14d6-160">複製したスライドの表のサイズ変更/変更/移動</span><span class="sxs-lookup"><span data-stu-id="c14d6-160">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="c14d6-161">複製したスライドに変形を適用する</span><span class="sxs-lookup"><span data-stu-id="c14d6-161">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="c14d6-162">Word、Excel、PowerPoint、OneNote、Access、Project、Publisher & Visio</span><span class="sxs-lookup"><span data-stu-id="c14d6-162">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="c14d6-163">アカウントをシームレスに切り替える</span><span class="sxs-lookup"><span data-stu-id="c14d6-163">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="c14d6-p104">新しいアカウントマネージャーは、すべての仕事と個人のアカウントを1つの場所に表示し、それらを切り替えることができるようにします。この更新された操作により、ログインしている方法が明確になります。また、最初にサインインしなくても、または複雑なダイアログを使用して仕事と個人のアカウントを切り替えることができます。</span><span class="sxs-lookup"><span data-stu-id="c14d6-p104">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them. This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="c14d6-167">次のシナリオを試してみてください。</span><span class="sxs-lookup"><span data-stu-id="c14d6-167">Scenarios to Try:</span></span>
- <span data-ttu-id="c14d6-168">アカウントを切り替える</span><span class="sxs-lookup"><span data-stu-id="c14d6-168">Switch between accounts</span></span>
- <span data-ttu-id="c14d6-169">新しいアカウントを追加する [メモ: 最初にファイルに移動しますか?]アカウント |接続されたサービスと、勤務先のアカウントに接続されているすべての個人用サービスを削除します。</span><span class="sxs-lookup"><span data-stu-id="c14d6-169">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="c14d6-170">アカウントからサインアウトする</span><span class="sxs-lookup"><span data-stu-id="c14d6-170">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="c14d6-171">注目すべき修正:</span><span class="sxs-lookup"><span data-stu-id="c14d6-171">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c14d6-172">Word</span><span class="sxs-lookup"><span data-stu-id="c14d6-172">Word</span></span> 
- <span data-ttu-id="c14d6-173">表 & の画像のコンテキストプレビューに関する問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c14d6-173">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="c14d6-174">Excel</span><span class="sxs-lookup"><span data-stu-id="c14d6-174">Excel</span></span>
- <span data-ttu-id="c14d6-175">オートフィルター検索フィールドのテキストが黒のテーマで白になっているという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c14d6-175">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="c14d6-176">新しい Office アドインに関する同意 UI の問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="c14d6-176">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c14d6-177">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c14d6-177">PowerPoint</span></span>
- <span data-ttu-id="c14d6-178">ラップトップまたはタブレットでスライドショーを提示する際に、自動的に表示が拡張される問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c14d6-178">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="c14d6-179">Outlook</span><span class="sxs-lookup"><span data-stu-id="c14d6-179">Outlook</span></span>
- <span data-ttu-id="c14d6-180">[OneNote に送る] ボタンの表示に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="c14d6-180">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="c14d6-181">Access</span><span class="sxs-lookup"><span data-stu-id="c14d6-181">Access</span></span>
- <span data-ttu-id="c14d6-182">さまざまなパフォーマンスと安定性の修正</span><span class="sxs-lookup"><span data-stu-id="c14d6-182">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c14d6-183">Project</span><span class="sxs-lookup"><span data-stu-id="c14d6-183">Project</span></span>
- <span data-ttu-id="c14d6-184">さまざまなパフォーマンスと安定性の修正</span><span class="sxs-lookup"><span data-stu-id="c14d6-184">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-9-2019-version-1903-build-1133020014"></a><span data-ttu-id="c14d6-185">9 2019 年2月バージョン 1903 (ビルド 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="c14d6-185">February 9 2019 Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="c14d6-186">注目すべき修正:</span><span class="sxs-lookup"><span data-stu-id="c14d6-186">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="c14d6-187">Word</span><span class="sxs-lookup"><span data-stu-id="c14d6-187">Word</span></span> 
- <span data-ttu-id="c14d6-188">カスタマイズしたスタイルが word online に適用されない問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="c14d6-188">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="c14d6-189">Word のリッチオブジェクトに関するコンテキストプレビューの問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c14d6-189">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="c14d6-190">リストを貼り付けると Word がクラッシュするという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c14d6-190">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="c14d6-191">Excel</span><span class="sxs-lookup"><span data-stu-id="c14d6-191">Excel</span></span>
- <span data-ttu-id="c14d6-192">通貨記号が表示されていない場合に、数字形式の後にスペースを追加すると、問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c14d6-192">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="c14d6-193">株式の自動検出に関する問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="c14d6-193">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c14d6-194">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c14d6-194">PowerPoint</span></span>
- <span data-ttu-id="c14d6-195">さまざまなパフォーマンスと安定性の修正</span><span class="sxs-lookup"><span data-stu-id="c14d6-195">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="c14d6-196">Outlook</span><span class="sxs-lookup"><span data-stu-id="c14d6-196">Outlook</span></span>
- <span data-ttu-id="c14d6-197">さまざまなパフォーマンスと安定性の修正</span><span class="sxs-lookup"><span data-stu-id="c14d6-197">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="c14d6-198">Access</span><span class="sxs-lookup"><span data-stu-id="c14d6-198">Access</span></span>
- <span data-ttu-id="c14d6-199">さまざまなパフォーマンスと安定性の修正</span><span class="sxs-lookup"><span data-stu-id="c14d6-199">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="c14d6-200">Project</span><span class="sxs-lookup"><span data-stu-id="c14d6-200">Project</span></span>
- <span data-ttu-id="c14d6-201">さまざまなパフォーマンスと安定性の修正</span><span class="sxs-lookup"><span data-stu-id="c14d6-201">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="january-30-2019-version-1902-build-1132620000"></a><span data-ttu-id="c14d6-202">2019年1月30日バージョン 1902 (ビルド 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="c14d6-202">January 30, 2019 Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="c14d6-203">注目すべき修正</span><span class="sxs-lookup"><span data-stu-id="c14d6-203">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="c14d6-204">Word</span><span class="sxs-lookup"><span data-stu-id="c14d6-204">Word</span></span> 
- <span data-ttu-id="c14d6-205">埋め込まれた Excel テーブルのセルのサイズを変更すると、問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c14d6-205">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="c14d6-206">描画キャンバスで図形のコピーと貼り付けを行うと、問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c14d6-206">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="c14d6-207">Excel</span><span class="sxs-lookup"><span data-stu-id="c14d6-207">Excel</span></span>
- <span data-ttu-id="c14d6-208">Excel Web app からファイルを開くときに問題が修正されました</span><span class="sxs-lookup"><span data-stu-id="c14d6-208">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="c14d6-209">CSV ファイルをとして保存するという問題が修正されました。ファイル名のサイズが原因で、.xlsx が失敗しました</span><span class="sxs-lookup"><span data-stu-id="c14d6-209">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="c14d6-210">ショートカットメニューのオプションを表示するようにコンテキストメニューを修正しました。</span><span class="sxs-lookup"><span data-stu-id="c14d6-210">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="c14d6-211">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="c14d6-211">PowerPoint</span></span>
- <span data-ttu-id="c14d6-212">ユーザーがキーボードショートカット ctrl + alt + 7/ctrl + alt + 8 を使用して角かっこを入力できなかったという発行を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c14d6-212">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="c14d6-213">ローカルビデオを PPT に挿入すると、「C」ドライブのディスク容量が減少するという問題が修正されました。</span><span class="sxs-lookup"><span data-stu-id="c14d6-213">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="c14d6-214">一部のユーザーに表示されていない [Microsoft Stream への発行] ボタンを修正しました</span><span class="sxs-lookup"><span data-stu-id="c14d6-214">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="c14d6-215">Outlook</span><span class="sxs-lookup"><span data-stu-id="c14d6-215">Outlook</span></span>
- <span data-ttu-id="c14d6-216">予定表のタスクビューで、タスクの件名が正しく表示されない問題を修正しました。</span><span class="sxs-lookup"><span data-stu-id="c14d6-216">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="c14d6-217">Access</span><span class="sxs-lookup"><span data-stu-id="c14d6-217">Access</span></span>
- <span data-ttu-id="c14d6-218">グラフのスケーリングの問題を修正しました</span><span class="sxs-lookup"><span data-stu-id="c14d6-218">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="c14d6-219">Project</span><span class="sxs-lookup"><span data-stu-id="c14d6-219">Project</span></span>
- <span data-ttu-id="c14d6-220">さまざまなパフォーマンスと安定性の修正</span><span class="sxs-lookup"><span data-stu-id="c14d6-220">Various performance and stability fixes</span></span>
