## プロジェクト要件

### 概要
ダークモードでモダンなデザインのプロフィールサイトに、日記を投稿できるミニブログ機能を実装する。

### デザイン要件
- ダークモードをデフォルトとしたモダンなUI
- レスポンシブデザイン対応
- スムーズなアニメーションとトランジション
- 視認性の高いカラーパレット（ダーク背景に映えるアクセントカラー）

### 機能要件
1. **プロフィール機能**
   - 自己紹介セクション
   - スキル・技術スタック表示
   - ソーシャルリンク

2. **ミニブログ機能**
   - 日記の投稿・編集・削除
   - マークダウン対応
   - タグ機能
   - 日付別アーカイブ
   - 検索機能

### 技術スタック（推奨）
- フロントエンド: React/Next.js
- スタイリング: Tailwind CSS
- データベース: SQLite/PostgreSQL
- 認証: NextAuth.js（管理者用）

## TODO リスト

### 初期セットアップ
- [ ] プロジェクトの技術スタック決定
- [ ] 開発環境のセットアップ
- [ ] 基本的なプロジェクト構造の作成

### デザイン実装
- [ ] ダークモードのカラーパレット定義
- [ ] レイアウトコンポーネントの作成
- [ ] ナビゲーションバーの実装
- [ ] レスポンシブデザインの適用

### プロフィール機能
- [ ] プロフィールページの作成
- [ ] 自己紹介セクションの実装
- [ ] スキル表示コンポーネントの作成

- [ ] ソーシャルリンクの追加

### ミニブログ機能
- [ ] データベーススキーマの設計
- [ ] ブログ投稿フォームの作成
- [ ] 投稿一覧ページの実装
- [ ] 個別投稿ページの作成
- [ ] マークダウンレンダリングの実装
- [ ] タグシステムの構築
- [ ] 検索機能の実装
- [ ] 管理者認証の設定

### 最終調整
- [ ] パフォーマンス最適化
- [ ] SEO対策
- [ ] デプロイ準備
- [ ] テストの実装