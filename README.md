# プロジェクト池袋 - 不動産管理会社ホームページ

地域に根ざした不動産管理のプロフェッショナル

## 概要

プロジェクト池袋は、池袋を中心とした地域密着型の不動産管理会社です。このリポジトリには、当社の公式ホームページのソースコードが含まれています。

## 特徴

- **モダンなデザイン**: グラスモーフィズムとグラデーションを活用した洗練されたUI
- **レスポンシブ対応**: デスクトップ、タブレット、モバイルに完全対応
- **アニメーション**: スムーズなスクロールアニメーションとホバーエフェクト
- **マスコットキャラクター**: 着物姿のキャラクターがページを彩る

## サービス内容

1. 賃貸不動産運営
2. 物件管理
3. 清掃サービス
4. 客付けサポート
5. トラブル対応
6. 総合コンサルティング

## ファイル構成

```
projectIkebukuro/
├── index.html          # メインHTMLファイル
├── style.css           # スタイルシート
├── script.js           # JavaScript（インタラクション）
├── logo.png            # 会社ロゴ
├── hero-bg.jpg         # ヒーロー背景画像
├── ceo-photo.jpg       # 代表取締役写真
├── mascot.png          # マスコットキャラクター
└── README.md           # このファイル
```

## ローカル開発

### 必要な環境

- Node.js（推奨: v18以上）
- npm または yarn

### セットアップ

1. リポジトリをクローン
```bash
git clone https://github.com/eshimi/projectIkebukuro.git
cd projectIkebukuro
```

2. 開発サーバーを起動
```bash
npx serve -l 8080
```

3. ブラウザで `http://localhost:8080` を開く

## デプロイ

### GitHub Pages

このプロジェクトはGitHub Pagesで簡単にデプロイできます。

1. GitHubリポジトリの Settings > Pages に移動
2. Source を `main` ブランチに設定
3. 数分後、`https://eshimi.github.io/projectIkebukuro/` でアクセス可能

### その他のホスティング

- **Netlify**: リポジトリを接続するだけで自動デプロイ
- **Vercel**: 同様に簡単にデプロイ可能
- **AWS S3 + CloudFront**: 本番環境向け

## 技術スタック

- **HTML5**: セマンティックなマークアップ
- **CSS3**: カスタムプロパティ、Flexbox、Grid
- **Vanilla JavaScript**: フレームワークなしの軽量実装
- **Google Fonts**: Noto Sans JP、Inter

## デザインコンセプト

### カラーパレット

- **Primary Blue**: #1e3a8a
- **Primary Teal**: #0d9488
- **Accent Green**: #10b981
- **Dark Navy**: #0f172a
- **Light Gray**: #f1f5f9

### デザイン原則

1. **信頼感**: プロフェッショナルな配色とレイアウト
2. **親しみやすさ**: マスコットキャラクターと温かみのあるデザイン
3. **地域性**: 池袋の都市的な雰囲気と日本的な要素の融合

## ブラウザサポート

- Chrome（最新版）
- Firefox（最新版）
- Safari（最新版）
- Edge（最新版）

## ライセンス

© 2025 プロジェクト池袋. All rights reserved.

## お問い合わせ

- **住所**: 〒171-0022 東京都豊島区南池袋2-1-1
- **電話**: 03-1234-5678
- **メール**: info@project-ikebukuro.jp
- **営業時間**: 9:00-18:00（平日）

---

Made with ❤️ by プロジェクト池袋
