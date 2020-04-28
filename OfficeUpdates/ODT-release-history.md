---
title: Office 展開ツール (ODT) のリリース履歴
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: IT プロフェッショナルに、Office 展開ツール (ODT) のリリース履歴を提供します
ms.openlocfilehash: 70e000f7cbdc597bde156257fc7e4b2a1e6e69eb
ms.sourcegitcommit: 58d55cf532d1d02cca85772920a6dd71089b071d
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/22/2020
ms.locfileid: "43781570"
---
# <a name="release-history-for-office-deployment-tool"></a>Office 展開ツールのリリース履歴

Office 展開ツール (ODT) はコマンドライン ツールです。これを使用すると、Microsoft 365 アプリなどのクイック実行バージョンの Office をクライアント コンピューターにダウンロードして展開することができます。 


ODT により、Office インストール環境をより詳細に制御できるようになります。 具体的には、インストールする製品や言語の種類、それらの製品の更新方法、インストール操作をユーザーに表示するかどうかを制御できます。 ODT の使用方法については、[Office 展開ツールの概要](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)を参照してください。

 **サポートされるオペレーティング システム**: Windows 10、Windows 7、Windows 8、Windows 8.1、Windows Server 2008 R2、Windows Server 2012、Windows Server 2012 R2 
 
 **インストール方法**: 自己解凍実行ファイルをダウンロードして実行します。このファイルには、Office 展開ツールの実行可能ファイル (setup.exe) およびサンプル構成ファイル (configuration.xml) が含まれています。 

[Office 展開ツールのダウンロード](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="april-15-2020"></a>2020 年 4 月 15 日

バージョン 16.0.12624.20320 (バージョン 16.0.12624.20290)
- Windows 7 固有のサポート終了 Office バージョンを追加する
- カスタマイズ設定が期待どおりに適用されない場合がある問題を修正します
- 不要な .cat ファイルが予期せずダウンロードされることがある問題を修正します

## <a name="january-16-2020"></a>2020年 1 月 16 日

バージョン 16.0.12325.20288
- 複数の言語がインストールされている場合に Office のインストール UI が正しい言語で表示されないことがある問題を修正します
- 特定の校正ツール パッケージがインストールされていると、Office のインストールが予期せず失敗することがある問題を修正します
- [Bing 機能での Microsoft Search](https://go.microsoft.com/fwlink/p/?linkid=2109345) の初期展開をオプションで制御するサポートを追加します


## <a name="october-31-2019"></a>2019 年 10 月 31 日

バージョン 16.0.12130.20272
- 問題を修正して、Skype for Business Basic 2019 による 2019 の永続的な大企業向けボリューム ライセンスの製品のインストールができるようにします
- プロキシを使用すると、特定の状況で ODT ダウンロード モードの予期しない失敗が引き起こされるという問題を修正します
- ODT ダウンロード モードで、ポート 80 以外のポートを使用して HTTP 経由でのダウンロードをできるようにする新機能


## <a name="july-10-2019"></a>2019 年 7 月 10 日

バージョン 16.0.11901.20022
- Office 2019 と共にインストールされる次の製品のサポートが追加されました。Access Runtime、Skype for Business Basic
- MSI からアップグレードされる場合のスタンドアロン製品の条件付きインストールのサポートが追加されました。

## <a name="april-23-2019"></a>2019 年 4 月 23 日

バージョン 16.0.11617.33601
- 関連するレジストリ設定をクリーンアップするように RemoveMSI=True のバグを修正しました。
- 予期しない障害 (E_UNEXPECTED) の追加情報を提供するようにエラー コードを更新しました。

## <a name="april-16-2019"></a>2019 年 4 月 16 日

バージョン 16.0.11615.33602
- 新しい MigrateArch 属性で 32 ビット C2R から 64 ビット C2R へのアップグレードをサポート。
- Web 上の場所 (http および https) に保存されている構成 XML ファイルへのアクセスを可能にする /configure のロジックを更新しました。
- 新しい属性 MatchInstalled が追加されました。これにより ODT では、製品や言語を追加するときに既存のバージョンをマッチングできます。

## <a name="march-13-2019"></a>2019 年 3 月 13 日

バージョン 16.0.11509.33604
- アップグレードと移行のシナリオの改善。

## <a name="january-14-2019"></a>2019 年 1 月 14 日

バージョン 16.0.11306.33602
- 展開構成用のロギングとテレメトリの改善。


## <a name="related-links"></a>関連リンク

[ODT ダウンロード センター](https://www.microsoft.com/en-us/download/details.aspx?id=49117)