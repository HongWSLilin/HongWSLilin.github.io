# 👋 マイパーソナルページへようこそ

**言語 / Languages / 语言 / 繁體中文:**

- 🇬🇧 [English](https://github.com/HongWSLilin/HongWSLilin.github.io#-welcome-to-my-personal-page)
- 🇨🇳 [简体中文](./README_ZH_CN.md)
- 🇹🇼 [繁體中文](./README_ZH_TW.md)
- 🇯🇵 [日本語](./README_JA.md) (現在の言語)

---

こんにちは！私は**ヨウ　キンりょう(HongWSLilin)** で、情熱的な**Javaバックエンドエンジニア**です。

> 📍 海南大学（NIIT）ソフトウェア工学専攻在学 | 🎯 高品質なバックエンドシステム構築に取り組む | 💡 オープンソース愛好家

---

## 👨‍💼 自己紹介

- 🎓 **学歴**: 海南大学 ソフトウェア工学（2023.09 - 2027.06）、GPA: 3.35/4.0
- 💻 **キャリア目標**: Javaバックエンドエンジニア
- 📞 **連絡先**: 15896500973 | 📧 2041813480@qq.com
- 🏆 **取得資格/受賞歴**: 英語CET-6証明書、国家奨学金（三等）、C1種運転免許証

---

## 🛠️ 技術スタック

### プログラミング言語 & 基礎知識
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=java&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)

### バックエンドフレームワーク
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=spring-boot&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=spring&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=flat)

### キャッシュ & メッセージキュー
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Vertx](https://img.shields.io/badge/Vert.x-92D400?style=flat)

### ツール & バージョン管理
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat&logo=apache-maven&logoColor=white)
![IDEA](https://img.shields.io/badge/IDEA-000000?style=flat&logo=intellij-idea&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)

### コアスキル
- ✅ **Javaコア**: コレクション、IO、例外処理、リフレクション、コンカレンシー、デザインパターン
- ✅ **共通ツール**: Hutool、Jackson/Json、HttpClient、Logback
- ✅ **Web開発**: Spring Boot + MyBatisスタック、RESTful API開発
- ✅ **データベース**: Redisキャッシュ設計、MySQL最適化
- ✅ **開発ツール**: Gitバージョン管理、Mavenビルド、IDEA IDE、Markdownドキュメンテーション

---

## 💼 インターンシップ経験

### 🚀 Javaバックエンドエンジニアインターン（2026.01 - 2026.02）
**上海アナイテクノロジー株式会社**

#### 主な職務内容
- オンライン動画学習プラットフォームの開発に参加し、バックエンドJavaモジュールの設計と実装を担当
- Spring Bootフレームワークに基づいて学習プラットフォームを開発し、授業管理、学習進捗追跡、パフォーマンス最適化機能などを実装
- MySQLを活用して動的テーブルストレージ構造を設計し、複数種類の学習データの柔軟な拡張をサポート
- コースコンテンツ品質管理システムの開発を補佐し、学習進捗の自動同期機能を実装。包括的なロギング監視と単体テストを実施し、モジュールの安定性を確保

---

## 📂 プロジェクト経験

### 🎯 KananRPC - Vert.xに基づく軽量イベント駆動型RPCフレームワーク
**プロジェクト期間**: 2025.9 - 2026.1

#### プロジェクト概要
本フレームワークはJavaで構築され、EtcdとVert.x技術を統合し、カスタムプロトコル拡張を実現しています。Spring Boot Starter依存関係を通じて迅速に統合でき、アノテーションベースの設定に対応しています。SPIメカニズムを採用して柔軟な動的機能拡張を実現し、ロードバランシング戦略、リトライロジック、フォールトトレランスメカニズムなどのコア機能を実装しています。

#### コア技術実装
- 🔧 **メッセージキュー & 処理**: 高コンカレンシー呼び出しの処理、データのシリアライズ/デシリアライズ、ネットワークサービスの管理、サービス関係の宣言
- 🌐 **HTTPサービス**: Vert.xに基づいてHTTPサービスを構築し、非同期かつ双方向の通信をサポートし、高いパフォーマンスを実現
- 🔐 **コンカレンシーセーフティ**: スレッドセーフなConcurrentHashMapをローカルサービスマッピングに活用し、名前に基づくサービス検索とコンカレントデシリアライズをサポート
- 📦 **動的シリアライズ**: 拡張性のためにジェネリックインターフェースを定義し、JavaリフレクションとByteArrayストリームに基づくJdkSerializerを実装し、ネットワークオブジェクト伝送を実現
- ⚡ **リクエスト処理**: Vert.x Handlerを使用してリクエストを非同期で処理し、デシリアライズを実行し、サービス実装を判断し、リフレクションを介して呼び出しを実行
- 🔄 **HTTPプロキシ**: JDKダイナミックプロキシを使用してサービスインターフェース用のファクトリスタイルのHTTPプロキシを生成し、シームレスなリモート呼び出しを実現

---

## 🎓 学歴

| 項目 | 詳細 |
|------|---------|
| **大学** | 海南大学（211プロジェクト、双一流大学） |
| **専攻** | ソフトウェア工学（NIIT）- 学士号 |
| **在学期間** | 2023.09 - 2027.06 |
| **GPA** | 3.35/4.0 |
| **取得資格/受賞歴** | 英語CET-6証明書、国家奨学金（三等）、C1種運転免許証 |
| **主要科目** | Java、Linux、データベース、データ構造、アルゴリズム設計と分析、オペレーティングシステム、コンパイラ原理、ソフトウェア工学、コンピュータ組織とアーキテクチャなど |

---

## 📊 GitHub統計

[![HongWSLilin's GitHub Stats](https://github-readme-stats.vercel.app/api?username=HongWSLilin&show_icons=true&theme=dark)](https://github.com/HongWSLilin)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=HongWSLilin&layout=compact&theme=dark)](https://github.com/HongWSLilin)

---

## 🤝 連絡先

- 📧 **メール**: [2041813480@qq.com](mailto:2041813480@qq.com)
- 💼 **GitHub**: [@HongWSLilin](https://github.com/HongWSLilin)
- 🌐 **個人ウェブサイト**: [HongWSLilin.github.io](https://HongWSLilin.github.io)

---

## 🎯 キャリア目標

- 🚀 高コンカレンシー・分散システム設計をマスターする
- 🏗️ 更多のオープンソースJavaフレームワークとユーティリティライブラリを開発する
- 📚 技術的な洞察と学習経験を共有する
- 🌟 優れたバックエンドアーキテクトになる

---

## 💡 コア能力

| 強み | 説明 |
|----------|-------------|
| **堅牢な基礎** | Javaコア構文、コレクションフレームワーク、コンカレントプログラミングなどの基礎知識をマスター |
| **フレームワーク専門知識** | Spring Boot、MyBatisなどの主流フレームワークの原理を深く理解 |
| **プロジェクト経験** | 完全なバックエンドシステム開発とRPCフレームワーク設計に参加 |
| **学習能力** | 新しい技術を迅速に習得し、独立した問題解決能力が強い |
| **コード品質** | コード規範、パフォーマンス最適化、システム安定性を重視 |

---

## 🌟 主な特徴

- ✅ 堅牢なJavaバックエンド開発基盤
- ✅ 実践的なプロジェクト経験（KananRPCフレームワーク）
- ✅ 包括的な技術スタック
- ✅ 明確なキャリアプランニング
- ✅ 優れた学歴背景（211プロジェクト大学、国家奨学金受賞）

---

<div align="center">

⭐️ もし私の作品が気に入ったら、スターを付けてください！

**ヨウ　キンりょう(HongWSLilin)** が❤️を込めて作成しました

**コラボレーションと交流を心よりお待ちしています！** 🚀

</div>
