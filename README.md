# 焼き菓子商用講座 ランディングページ

20年の実績を持つ料理教室の焼き菓子商用講座のランディングページです。

## 🎯 プロジェクト概要

高級感と品格、親しみやすさを兼ね備えた料理教室のLPです。
- **ターゲット**: 焼き菓子で起業・副業を考えている方
- **特徴**: 20年の実績、1000人以上の指導経験
- **コース**: 3段階の料金プラン（¥178,000〜¥398,000）

## ✨ 主な機能

- **レスポンシブデザイン**: スマートフォン・タブレット・PC対応
- **高級感のあるデザイン**: 深いクリーム×ゴールドの配色
- **問い合わせフォーム**: 完全統合型フォーム
- **日程・タイムスケジュール**: 平日・週末クラス対応
- **LINE公式アカウント連携**: フッターに配置

## 🛠 技術スタック

- **フレームワーク**: React 19.1.0
- **ビルドツール**: Vite 6.3.5
- **スタイリング**: Tailwind CSS + カスタムCSS
- **UI コンポーネント**: shadcn/ui
- **フォント**: Noto Serif JP（明朝体）

## 📁 プロジェクト構造

```
kanae-cooking-lp/
├── src/
│   ├── components/          # UIコンポーネント
│   ├── assets/             # 画像ファイル
│   ├── App.jsx             # メインコンポーネント
│   ├── App.css             # カスタムスタイル
│   └── main.jsx            # エントリーポイント
├── public/                 # 静的ファイル
├── dist/                   # ビルド済みファイル
└── package.json            # 依存関係
```

## 🚀 セットアップ手順

### 1. 依存関係のインストール
```bash
npm install
```

### 2. 開発サーバーの起動
```bash
npm run dev
```

### 3. 本番ビルド
```bash
npm run build
```

### 4. プレビュー
```bash
npm run preview
```

## 🎨 デザインコンセプト

### カラーパレット
- **メインカラー**: クリーム (#FAF8F5)
- **アクセントカラー**: ゴールド (#C9A961)
- **テキストカラー**: ダークブラウン (#2C2C2C)
- **サブカラー**: ベージュ (#F0EBE3)

### フォント
- **メインフォント**: Noto Serif JP（明朝体）
- **文字間隔**: 0.08em（高級感演出）
- **行間**: 1.8（読みやすさ重視）

## 📱 レスポンシブ対応

- **モバイル**: 375px〜
- **タブレット**: 768px〜
- **デスクトップ**: 1024px〜

## 🔧 カスタマイズ

### 色の変更
`src/App.css`の`:root`セクションでカスタムカラーを変更できます。

### コンテンツの変更
`src/App.jsx`でテキストや画像を変更できます。

### 画像の変更
`src/assets/`フォルダ内の画像を差し替えてください。

## 📞 お問い合わせ機能

- **フォーム**: 名前、メール、電話、希望コース、メッセージ
- **LINE連携**: フッターにLINE公式アカウントボタン
- **無料相談**: 個別相談セクション

## 🌟 特徴的な機能

1. **高級感のあるアニメーション**: ホバーエフェクト、フェードイン
2. **スムーススクロール**: セクション間の滑らかな移動
3. **カード型レイアウト**: 情報の整理と視認性向上
4. **CTA最適化**: 複数の問い合わせ導線

## 📈 SEO対策

- **メタタグ**: 適切なタイトルとディスクリプション
- **構造化データ**: セマンティックHTML
- **画像最適化**: alt属性とファイルサイズ最適化

## 🚀 デプロイ方法

### GitHub Pages
1. GitHubリポジトリを作成
2. `npm run build`でビルド
3. `dist`フォルダをデプロイ

### Vercel
1. Vercelアカウント作成
2. GitHubリポジトリ連携
3. 自動デプロイ設定

### Netlify
1. Netlifyアカウント作成
2. ドラッグ&ドロップでデプロイ
3. 独自ドメイン設定

## 📝 ライセンス

このプロジェクトは個人利用・商用利用ともに自由にご利用いただけます。

## 🤝 サポート

ご質問やカスタマイズのご相談がございましたら、お気軽にお問い合わせください。

---

**制作**: 2025年7月
**バージョン**: 1.0.0
**最終更新**: 2025年7月9日

