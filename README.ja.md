# Awesome-Selfhosted（日本語版）

[![Awesome](_static/awesome.png)](https://github.com/sindresorhus/awesome)

[English README](README.md) ・ [HTML 版（公式・推奨）](https://awesome-selfhosted.net/) ・ [本家リポジトリ](https://github.com/awesome-selfhosted/awesome-selfhosted)

セルフホスティングとは、[SaaSS](https://www.gnu.org/philosophy/who-does-that-server-really-serve.html) 事業者のサービスを使う代わりに、自分のサーバーでアプリケーションをホストして管理することです。

このリストは、自分のサーバーでホストできる[フリー](https://ja.wikipedia.org/wiki/フリーソフトウェア)ソフトウェアの[ネットワークサービス](https://en.wikipedia.org/wiki/Network_service)と [Web アプリケーション](https://ja.wikipedia.org/wiki/ウェブアプリケーション)をまとめたものです。フリーでないソフトウェアは [Non-Free](https://github.com/awesome-selfhosted/awesome-selfhosted/blob/master/non-free.md) ページに掲載されています。

> **この日本語版について**
> - 本家 [awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) の README（2026-10-12 時点、コミット `dcc5c09`）を Claude（AI）で日本語訳したものです。全 1,261 件の説明文を訳しています。
> - 分量が多いため、カテゴリごとに [`ja/`](ja/) 配下の 12 ファイルに分割しています。下の目次から各カテゴリへ移動できます。
> - プロジェクト名・URL・ライセンス／言語タグ（`MIT` `Docker` など）は原文のままです。訳に疑問がある場合や最新情報は英語版を参照してください。
> - 本家の README はデータリポジトリ（[awesome-selfhosted-data](https://github.com/awesome-selfhosted/awesome-selfhosted-data)）から自動生成されるため、この日本語訳は時間とともに本家と差が出ます。

--------------------

## 目次

- **[01. 分析 〜 ブックマーク・リンク共有](ja/01.md)**
  - [分析](ja/01.md#分析--analytics)
  - [アーカイブ・デジタル保存](ja/01.md#アーカイブデジタル保存--archiving-and-digital-preservation-dp)
  - [自動化](ja/01.md#自動化--automation)
  - [バックアップ](ja/01.md#バックアップ--backup)
  - [ブログプラットフォーム](ja/01.md#ブログプラットフォーム--blogging-platforms)
  - [予約・スケジューリング](ja/01.md#予約スケジューリング--booking-and-scheduling)
  - [ブックマーク・リンク共有](ja/01.md#ブックマークリンク共有--bookmarks-and-link-sharing)
- **[02. カレンダー・連絡先 〜 コミュニケーション：SIP](ja/02.md)**
  - [カレンダー・連絡先](ja/02.md#カレンダー連絡先--calendar--contacts)
  - [コミュニケーション：独自通信システム](ja/02.md#コミュニケーション独自通信システム--communication---custom-communication-systems)
  - [コミュニケーション：メール：統合ソリューション](ja/02.md#コミュニケーションメール統合ソリューション--communication---email---complete-solutions)
  - [コミュニケーション：メール：メール配送エージェント（MDA）](ja/02.md#コミュニケーションメールメール配送エージェントmda--communication---email---mail-delivery-agents)
  - [コミュニケーション：メール：メール転送エージェント（MTA）](ja/02.md#コミュニケーションメールメール転送エージェントmta--communication---email---mail-transfer-agents)
  - [コミュニケーション：メール：メーリングリスト・ニュースレター](ja/02.md#コミュニケーションメールメーリングリストニュースレター--communication---email---mailing-lists-and-newsletters)
  - [コミュニケーション：メール：Web メールクライアント](ja/02.md#コミュニケーションメールweb-メールクライアント--communication---email---webmail-clients)
  - [コミュニケーション：IRC](ja/02.md#コミュニケーションirc--communication---irc)
  - [コミュニケーション：SIP](ja/02.md#コミュニケーションsip--communication---sip)
- **[03. コミュニケーション：SNS・フォーラム 〜 顧客関係管理（CRM）](ja/03.md)**
  - [コミュニケーション：SNS・フォーラム](ja/03.md#コミュニケーションsnsフォーラム--communication---social-networks-and-forums)
  - [コミュニケーション：ビデオ会議](ja/03.md#コミュニケーションビデオ会議--communication---video-conferencing)
  - [コミュニケーション：XMPP：サーバー](ja/03.md#コミュニケーションxmppサーバー--communication---xmpp---servers)
  - [コミュニケーション：XMPP：Web クライアント](ja/03.md#コミュニケーションxmppweb-クライアント--communication---xmpp---web-clients)
  - [地域支援型農業（CSA）](ja/03.md#地域支援型農業csa--community-supported-agriculture-csa)
  - [カンファレンス管理](ja/03.md#カンファレンス管理--conference-management)
  - [コンテンツ管理システム（CMS）](ja/03.md#コンテンツ管理システムcms--content-management-systems-cms)
  - [顧客関係管理（CRM）](ja/03.md#顧客関係管理crm--customer-relationship-management-crm)
- **[04. データベース管理 〜 フィードリーダー](ja/04.md)**
  - [データベース管理](ja/04.md#データベース管理--database-management)
  - [DNS](ja/04.md#dns--dns)
  - [文書管理](ja/04.md#文書管理--document-management)
  - [文書管理：電子書籍](ja/04.md#文書管理電子書籍--document-management---e-books)
  - [文書管理：機関リポジトリ・デジタルライブラリ](ja/04.md#文書管理機関リポジトリデジタルライブラリ--document-management---institutional-repository-and-digital-library-software)
  - [文書管理：図書館システム（ILS）](ja/04.md#文書管理図書館システムils--document-management---integrated-library-systems-ils)
  - [EC（電子商取引）](ja/04.md#ec電子商取引--e-commerce)
  - [フェデレーション ID・認証](ja/04.md#フェデレーション-id認証--federated-identity--authentication)
  - [フィードリーダー](ja/04.md#フィードリーダー--feed-readers)
- **[05. ファイル転送・同期 〜 ゲーム：管理ツール・コントロールパネル](ja/05.md)**
  - [ファイル転送・同期](ja/05.md#ファイル転送同期--file-transfer--synchronization)
  - [ファイル転送：分散ファイルシステム](ja/05.md#ファイル転送分散ファイルシステム--file-transfer---distributed-filesystems)
  - [ファイル転送：オブジェクトストレージ・ファイルサーバー](ja/05.md#ファイル転送オブジェクトストレージファイルサーバー--file-transfer---object-storage--file-servers)
  - [ファイル転送：P2P ファイル共有](ja/05.md#ファイル転送p2p-ファイル共有--file-transfer---peer-to-peer-filesharing)
  - [ファイル転送：ワンクリック・ドラッグ＆ドロップアップロード](ja/05.md#ファイル転送ワンクリックドラッグドロップアップロード--file-transfer---single-click--drag-n-drop-upload)
  - [ファイル転送：Web ファイルマネージャー](ja/05.md#ファイル転送web-ファイルマネージャー--file-transfer---web-based-file-managers)
  - [ゲーム](ja/05.md#ゲーム--games)
  - [ゲーム：管理ツール・コントロールパネル](ja/05.md#ゲーム管理ツールコントロールパネル--games---administrative-utilities--control-panels)
- **[06. 家系図 〜 学習・講座](ja/06.md)**
  - [家系図](ja/06.md#家系図--genealogy)
  - [生成 AI（GenAI）](ja/06.md#生成-aigenai--generative-artificial-intelligence-genai)
  - [グループウェア](ja/06.md#グループウェア--groupware)
  - [健康・フィットネス](ja/06.md#健康フィットネス--health-and-fitness)
  - [人事管理（HRM）](ja/06.md#人事管理hrm--human-resources-management-hrm)
  - [ID 管理](ja/06.md#id-管理--identity-management)
  - [IoT（モノのインターネット）](ja/06.md#iotモノのインターネット--internet-of-things-iot)
  - [在庫管理](ja/06.md#在庫管理--inventory-management)
  - [ナレッジ管理ツール](ja/06.md#ナレッジ管理ツール--knowledge-management-tools)
  - [学習・講座](ja/06.md#学習講座--learning-and-courses)
- **[07. 製造 〜 メディアストリーミング：マルチメディア](ja/07.md)**
  - [製造](ja/07.md#製造--manufacturing)
  - [地図・GPS](ja/07.md#地図gps--maps-and-global-positioning-system-gps)
  - [メディア管理](ja/07.md#メディア管理--media-management)
  - [メディアストリーミング](ja/07.md#メディアストリーミング--media-streaming)
  - [メディアストリーミング：音声](ja/07.md#メディアストリーミング音声--media-streaming---audio-streaming)
  - [メディアストリーミング：マルチメディア](ja/07.md#メディアストリーミングマルチメディア--media-streaming---multimedia-streaming)
- **[08. メディアストリーミング：動画 〜 家計・予算・資金管理](ja/08.md)**
  - [メディアストリーミング：動画](ja/08.md#メディアストリーミング動画--media-streaming---video-streaming)
  - [その他](ja/08.md#その他--miscellaneous)
  - [家計・予算・資金管理](ja/08.md#家計予算資金管理--money-budgeting--management)
- **[09. 監視・ステータスページ 〜 フォトギャラリー](ja/09.md)**
  - [監視・ステータスページ](ja/09.md#監視ステータスページ--monitoring--status-pages)
  - [ネットワークユーティリティ](ja/09.md#ネットワークユーティリティ--network-utilities)
  - [メモ・エディタ](ja/09.md#メモエディタ--note-taking--editors)
  - [オフィススイート](ja/09.md#オフィススイート--office-suites)
  - [パスワードマネージャー](ja/09.md#パスワードマネージャー--password-managers)
  - [ペーストビン](ja/09.md#ペーストビン--pastebins)
  - [個人用ダッシュボード](ja/09.md#個人用ダッシュボード--personal-dashboards)
  - [フォトギャラリー](ja/09.md#フォトギャラリー--photo-galleries)
- **[10. 投票・イベント 〜 セルフホスティング基盤](ja/10.md)**
  - [投票・イベント](ja/10.md#投票イベント--polls-and-events)
  - [プロキシ](ja/10.md#プロキシ--proxy)
  - [レシピ管理](ja/10.md#レシピ管理--recipe-management)
  - [リモートアクセス](ja/10.md#リモートアクセス--remote-access)
  - [リソース計画](ja/10.md#リソース計画--resource-planning)
  - [検索エンジン](ja/10.md#検索エンジン--search-engines)
  - [セルフホスティング基盤](ja/10.md#セルフホスティング基盤--self-hosting-solutions)
- **[11. ソフトウェア開発 〜 タスク管理・ToDo リスト](ja/11.md)**
  - [ソフトウェア開発](ja/11.md#ソフトウェア開発--software-development)
  - [ソフトウェア開発：API 管理](ja/11.md#ソフトウェア開発api-管理--software-development---api-management)
  - [ソフトウェア開発：CI/CD](ja/11.md#ソフトウェア開発cicd--software-development---continuous-integration--deployment)
  - [ソフトウェア開発：FaaS・サーバーレス](ja/11.md#ソフトウェア開発faasサーバーレス--software-development---faas--serverless)
  - [ソフトウェア開発：フィーチャートグル](ja/11.md#ソフトウェア開発フィーチャートグル--software-development---feature-toggle)
  - [ソフトウェア開発：IDE・ツール](ja/11.md#ソフトウェア開発ideツール--software-development---ide--tools)
  - [ソフトウェア開発：ローカライズ](ja/11.md#ソフトウェア開発ローカライズ--software-development---localization)
  - [ソフトウェア開発：ローコード](ja/11.md#ソフトウェア開発ローコード--software-development---low-code)
  - [ソフトウェア開発：プロジェクト管理](ja/11.md#ソフトウェア開発プロジェクト管理--software-development---project-management)
  - [ソフトウェア開発：テスト](ja/11.md#ソフトウェア開発テスト--software-development---testing)
  - [静的サイトジェネレーター](ja/11.md#静的サイトジェネレーター--static-site-generators)
  - [タスク管理・ToDo リスト](ja/11.md#タスク管理todo-リスト--task-management--to-do-lists)
- **[12. チケット管理 〜 Wiki](ja/12.md)**
  - [チケット管理](ja/12.md#チケット管理--ticketing)
  - [時間記録](ja/12.md#時間記録--time-tracking)
  - [旅行計画](ja/12.md#旅行計画--travel-organization)
  - [URL 短縮](ja/12.md#url-短縮--url-shorteners)
  - [監視カメラ（映像監視）](ja/12.md#監視カメラ映像監視--video-surveillance)
  - [VPN](ja/12.md#vpn--vpn)
  - [Web サーバー](ja/12.md#web-サーバー--web-servers)
  - [Wiki](ja/12.md#wiki--wikis)
- [ライセンス一覧](#ライセンス一覧)
- [アンチフィーチャー](#アンチフィーチャー)
- [外部リンク](#外部リンク)
- [コントリビュート](#コントリビュート)
- [ライセンス](#ライセンス)

--------------------

## ライセンス一覧

**[`^ 目次に戻る ^`](#目次)**

各項目の末尾に付いているライセンスタグの一覧です。

- `0BSD` - [BSD Zero-Clause Licence](https://spdx.org/licenses/0BSD.html)
- `AAL` - [Attribution Assurance License](https://spdx.org/licenses/AAL.html)
- `AGPL-3.0` - [GNU Affero General Public License 3.0](https://spdx.org/licenses/AGPL-3.0.html)
- `Apache-2.0` - [Apache, Version 2.0](https://spdx.org/licenses/Apache-2.0.html)
- `APSL-2.0` - [Apple Public Source License, Version 2.0](https://spdx.org/licenses/APSL-2.0.html)
- `Artistic-2.0` - [Artistic License Version 2.0](https://spdx.org/licenses/Artistic-2.0.html)
- `Beerware` - [Beerware License](https://spdx.org/licenses/Beerware.html)
- `BSD-2-Clause` - [BSD 2-clause "Simplified"](https://spdx.org/licenses/BSD-2-Clause.html)
- `BSD-2-Clause-FreeBSD` - [BSD 2-Clause FreeBSD License](https://spdx.org/licenses/BSD-2-Clause-FreeBSD.html)
- `BSD-3-Clause` - [BSD 3-Clause "New" or "Revised"](https://spdx.org/licenses/BSD-3-Clause.html)
- `BSD-3-Clause-Attribution` - [BSD with attribution](https://spdx.org/licenses/BSD-3-Clause-Attribution.html)
- `BSD-4-Clause` - [BSD 4-clause "Original"](https://spdx.org/licenses/BSD-4-Clause.html)
- `CAL-1.0` - [Cryptographic Autonomy License 1.0](https://spdx.org/licenses/CAL-1.0.html)
- `CC-BY-SA-3.0` - [Creative Commons Attribution-ShareAlike 3.0 License](https://spdx.org/licenses/CC-BY-SA-3.0.html)
- `CC-BY-SA-4.0` - [Creative Commons Attribution-ShareAlike 4.0 License](https://spdx.org/licenses/CC-BY-SA-4.0.html)
- `CC0-1.0` - [Public Domain/Creative Common Zero 1.0](https://spdx.org/licenses/CC0-1.0.html)
- `CDDL-1.0` - [Common Development and Distribution License](https://spdx.org/licenses/CDDL-1.0.html)
- `CECILL-B` - [CEA CNRS INRIA Logiciel Libre](https://spdx.org/licenses/CECILL-B.html)
- `CPAL-1.0` - [Common Public Attribution License Version 1.0](https://spdx.org/licenses/CPAL-1.0.html)
- `ECL-2.0` - [Educational Community License, Version 2.0](https://spdx.org/licenses/ECL-2.0.html)
- `EPL-1.0` - [Eclipse Public License, Version 1.0](https://spdx.org/licenses/EPL-1.0.html)
- `EPL-2.0` - [Eclipse Public License, Version 2.0](https://spdx.org/licenses/EPL-2.0.html)
- `EUPL-1.2` - [European Union Public License 1.2](https://spdx.org/licenses/EUPL-1.2.html)
- `GPL-1.0` - [GNU General Public License 1.0](https://spdx.org/licenses/GPL-1.0.html)
- `GPL-2.0` - [GNU General Public License 2.0](https://spdx.org/licenses/GPL-2.0.html)
- `GPL-3.0` - [GNU General Public License 3.0](https://spdx.org/licenses/GPL-3.0.html)
- `IPL-1.0` - [IBM Public License](https://spdx.org/licenses/IPL-1.0.html)
- `ISC` - [Internet Systems Consortium License](https://spdx.org/licenses/ISC.html)
- `LGPL-2.1` - [Lesser General Public License 2.1](https://spdx.org/licenses/LGPL-2.1.html)
- `LGPL-3.0` - [Lesser General Public License 3.0](https://spdx.org/licenses/LGPL-3.0.html)
- `MIT` - [MIT License](https://spdx.org/licenses/MIT.html)
- `MPL-1.1` - [Mozilla Public License Version 1.1](https://spdx.org/licenses/MPL-1.1.html)
- `MPL-2.0` - [Mozilla Public License](https://spdx.org/licenses/MPL-2.0.html)
- `OSL-3.0` - [Open Software License 3.0](https://spdx.org/licenses/OSL-3.0.html)
- `Sendmail` - [Sendmail License](https://spdx.org/licenses/Sendmail.html)
- `Ruby` - [Ruby License](https://spdx.org/licenses/Ruby.html)
- `Unlicense` - [The Unlicense](https://spdx.org/licenses/Unlicense.html)
- `WTFPL` - [Do What the Fuck You Want to Public License](https://spdx.org/licenses/WTFPL.html)
- `Zlib` - [Zlib/libpng License](https://spdx.org/licenses/Zlib.html)
- `ZPL-2.0` - [Zope Public License 2.0](https://spdx.org/licenses/ZPL-2.0.html)

--------------------

## アンチフィーチャー

- `⚠ ` - 利用者が管理できない独自（プロプライエタリ）サービスに依存している

--------------------

## 外部リンク

**[`^ 目次に戻る ^`](#目次)**

- awesome-selfhosted のアプリを探す・絞り込むための別フロントエンド／ポータル: [awweso.me](https://awweso.me/), [awesome-web.theravenhub](https://awesome-web.theravenhub.com/browse.html), [awesomehub.web.app](https://awesomehub.js.org/list/selfhosted)
- [Awesome Sysadmin](https://github.com/awesome-foss/awesome-sysadmin) - オープンソースのシステム管理者向けリソースを集めた厳選リスト。
- 何らかの形でプライバシーや分散化を目指すソフトウェアのリスト: [PRISM Break](https://prism-break.org/en/), [privacytools.io](https://www.privacytools.io/), [Alternative Internet](https://redecentralize.github.io/alternative-internet/), [Libre Projects](https://libreprojects.net/), [Easy Indie App](https://easyindie.app)
- その他の Awesome リスト: [Awesome Big Data](https://github.com/0xnr/awesome-bigdata), [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets)
- ダイナミック DNS サービス: [Afraid.org](https://freedns.afraid.org/domain/registry/), [Pagekite](https://pagekite.net/)
- コミュニティ・フォーラム: [/c/selfhosted on lemmy.world](https://lemmy.world/c/selfhosted), [/c/selfhost on lemmy.ml](https://lemmy.ml/c/selfhost), [/r/selfhosted on reddit](https://old.reddit.com/r/selfhosted/), [/r/selfhosted Matrix Channel](https://matrix.to/#/#selfhosted:selfhosted.chat), [/r/homelab on reddit](https://old.reddit.com/r/homelab/), [IndieWeb](https://indieweb.org/)
- [theme.park](https://theme-park.dev/) - 50 種類のセルフホストアプリ向けテーマ／スキン集。([ソースコード](https://github.com/GilbN/theme.park/)) `MIT` `CSS`

--------------------

## コントリビュート

項目の追加・修正は本家のデータリポジトリで受け付けています。ガイドラインは[こちら](https://github.com/awesome-selfhosted/awesome-selfhosted-data/blob/master/CONTRIBUTING.md)（英語）。日本語訳の誤りはこのフォークの Issue でお知らせください。

## ライセンス

このリストは [Creative Commons Attribution-ShareAlike 3.0 Unported](https://github.com/awesome-selfhosted/awesome-selfhosted/blob/master/LICENSE) ライセンスで提供されています（日本語訳も同ライセンスに従います）。
ライセンスの概要は[こちら](https://creativecommons.org/licenses/by-sa/3.0/deed.ja)。  
作成者の一覧は [AUTHORS](https://github.com/awesome-selfhosted/awesome-selfhosted-data/blob/master/AUTHORS) ファイルにあります。
