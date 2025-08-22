# AI Learning Assistant

AIを活用した学習支援アプリケーションです。プログラミングの質問、技術概念の説明、アイデア出しなど、様々な学習シーンで活用できます。

## 🚀 機能

- **🤖 AIチャット**: OpenAI GPT-3.5-turboを使用した対話型学習
- **💬 会話履歴**: チャットの履歴を保存・表示
- **📱 レスポンシブ**: モバイル・デスクトップ対応
- **🎨 モダンUI**: Tailwind CSSによる美しいデザイン

## 🛠️ 技術スタック

- **Frontend**: Next.js 15, React 19, TypeScript
- **Styling**: Tailwind CSS
- **AI**: OpenAI API (GPT-3.5-turbo)
- **Deployment**: Vercel (推奨)

## 📦 セットアップ

### 1. リポジトリのクローン
```bash
git clone https://github.com/yourusername/ai-learning-app.git
cd ai-learning-app
```

### 2. 依存関係のインストール
```bash
npm install
```

### 3. 環境変数の設定
`.env`ファイルを作成し、OpenAI APIキーを設定：
```env
OPENAI_API_KEY=your_openai_api_key_here
```

### 4. 開発サーバーの起動
```bash
npm run dev
```

ブラウザで [http://localhost:3000](http://localhost:3000) にアクセス

## 🔑 APIキーの取得

1. [OpenAI Platform](https://platform.openai.com/api-keys) にアクセス
2. アカウントを作成・ログイン
3. **Create new secret key** をクリック
4. 生成されたキーを`.env`ファイルに設定

## 🚀 デプロイ

### Vercelでのデプロイ
1. [Vercel](https://vercel.com) にアクセス
2. GitHubアカウントでログイン
3. **New Project** をクリック
4. `ai-learning-app`リポジトリを選択
5. 環境変数`OPENAI_API_KEY`を設定
6. **Deploy** をクリック

## 📱 使用方法

1. アプリケーションにアクセス
2. 質問や相談を入力
3. **送信**ボタンをクリック
4. AIからの回答を確認

### 質問例
- 「JavaScriptの配列操作を教えて」
- 「Next.jsの使い方を説明して」
- 「Webアプリのアイデアを出して」
- 「Pythonでデータ分析を始めるには？」

## 🤝 コントリビューション

1. このリポジトリをフォーク
2. フィーチャーブランチを作成 (`git checkout -b feature/amazing-feature`)
3. 変更をコミット (`git commit -m 'Add amazing feature'`)
4. ブランチにプッシュ (`git push origin feature/amazing-feature`)
5. プルリクエストを作成

## 📄 ライセンス

このプロジェクトはMITライセンスの下で公開されています。

## 🆘 サポート

問題が発生した場合：
1. [Issues](https://github.com/yourusername/ai-learning-app/issues) で報告
2. または、`.chat/team-chat.md`に記録

---

**Happy Learning! 🎓**
