# Font Cycler

フォントアニメーションツール - 複数のフォントを循環表示し、動画・GIF形式でエクスポートできるWebアプリケーション

A web-based font animation tool that cycles through different fonts and exports the animation as video or GIF files.

## 🚀 ライブデモ / Live Demo

**[Font Cyclerを試す / Try Font Cycler](https://kzhrknt.github.io/fontCycler/)**

## ✨ 機能 / Features

- **40種類のGoogle Fonts** - サンセリフ、セリフ、カーシブなど豊富なフォントスタイル
- **複数形式エクスポート** - WebM、MP4、GIF形式で動画出力
- **リアルタイムプレビュー** - フォントアニメーションをリアルタイムで確認
- **カスタマイズ設定**:
  - テキスト内容
  - フォント色・背景色
  - アニメーション速度（間隔）
  - アスペクト比（16:9、4:3、1:1、9:16、3:4）
- **フォント選択ツール** - 全選択・全選択解除ボタンで簡単管理
- **レスポンシブデザイン** - デスクトップ・モバイル対応

---

- **40 Google Fonts** - Wide variety of fonts including Sans-serif, Serif, and Cursive styles
- **Multi-format Export** - Export animations as WebM, MP4, or GIF
- **Real-time Preview** - See your font animation in real-time
- **Customizable Settings**:
  - Text content
  - Font and background colors
  - Animation speed (interval)
  - Aspect ratio (16:9, 4:3, 1:1, 9:16, 3:4)
- **Font Selection Tools** - Select all/deselect all buttons for easy font management
- **Responsive Design** - Works on desktop and mobile devices

## 🎯 使用例 / Use Cases

- **ロゴデザイン** - ブランドに適したフォントのプレビュー
- **SNSコンテンツ** - 投稿やストーリー用のアニメーションテキスト作成
- **タイポグラフィ探索** - 複数フォントの素早い比較
- **デザインプレゼン** - クライアントへのフォント提案
- **教育コンテンツ** - フォント特性の説明

---

- **Logo Design** - Preview different fonts for your brand
- **Social Media Content** - Create animated text for posts and stories
- **Typography Exploration** - Compare multiple fonts quickly
- **Design Presentations** - Show font options to clients
- **Educational Content** - Demonstrate font characteristics

## 🛠️ 使用方法 / How to Use

1. **テキストを入力** - 入力フィールドにテキストを入力
2. **フォントを選択** - 折りたたみ式フォントリストから選択
   - 「全選択」ボタンで全フォントを選択
   - 「全選択解除」ボタンで選択をクリア
3. **外観をカスタマイズ**:
   - フォント色を選択
   - 背景色を設定（透明も可）
   - アニメーション速度を調整
   - アスペクト比を選択
4. **エクスポート形式を選択**:
   - **WebM**（推奨） - 最高品質・互換性
   - **MP4** - ブラウザ依存、非対応時はWebMにフォールバック
   - **GIF** - gif.jsライブラリを使用したアニメーションGIF
5. **「Record 1 Loop」をクリック** - アニメーションを生成・ダウンロード

---

1. **Enter your text** in the input field
2. **Select fonts** from the collapsible font list
   - Use "全選択" (Select All) to select all fonts
   - Use "全選択解除" (Deselect All) to clear selection
3. **Customize appearance**:
   - Choose font color
   - Set background color (or transparent)
   - Adjust animation speed
   - Select aspect ratio
4. **Choose export format**:
   - **WebM** (Recommended) - Best quality and compatibility
   - **MP4** - Browser dependent, falls back to WebM if unsupported
   - **GIF** - Animated GIF using gif.js library
5. **Click "Record 1 Loop"** to generate and download your animation

## 🔧 技術仕様 / Technical Specifications

### エクスポート形式 / Export Formats
- **WebM**: 1920px幅、30fps、フルHD品質
- **MP4**: 1920px幅、30fps（ブラウザ依存）
- **GIF**: 800px幅、カスタム間隔タイミング

---

- **WebM**: 1920px width, 30fps, Full HD quality
- **MP4**: 1920px width, 30fps (browser dependent)
- **GIF**: 800px width, custom interval timing

### 対応フォント / Supported Fonts
厳選された40種類のGoogle Fontsを収録：

**サンセリフ**: Roboto, Open Sans, Montserrat, Poppins, Lato, Source Sans Pro, Nunito, Raleway, Ubuntu, Inter, Noto Sans, Quicksand, Fira Sans, Work Sans, Oswald

**セリフ**: Playfair Display, Merriweather, Crimson Text, Libre Baskerville, PT Serif, Cormorant Garamond, Vollkorn, Alegreya, Arvo, Bitter, Domine, Zilla Slab

**カーシブ/ディスプレイ**: Lobster, Bebas Neue, Dancing Script, Pacifico, Kaushan Script, Great Vibes, Satisfy, Courgette, Amatic SC, Caveat, Righteous, Comfortaa

**等幅**: Courier Prime

---

The application includes 40 carefully selected Google Fonts:

**Sans-serif**: Roboto, Open Sans, Montserrat, Poppins, Lato, Source Sans Pro, Nunito, Raleway, Ubuntu, Inter, Noto Sans, Quicksand, Fira Sans, Work Sans, Oswald

**Serif**: Playfair Display, Merriweather, Crimson Text, Libre Baskerville, PT Serif, Cormorant Garamond, Vollkorn, Alegreya, Arvo, Bitter, Domine, Zilla Slab

**Cursive/Display**: Lobster, Bebas Neue, Dancing Script, Pacifico, Kaushan Script, Great Vibes, Satisfy, Courgette, Amatic SC, Caveat, Righteous, Comfortaa

**Monospace**: Courier Prime

### 技術スタック / Technology Stack
- **フロントエンド**: React (CDN), HTML5 Canvas, CSS3
- **スタイリング**: Tailwind CSS
- **動画録画**: MediaRecorder API
- **GIF生成**: gif.js library
- **フォント読み込み**: Google Fonts API

---

- **Frontend**: React (CDN), HTML5 Canvas, CSS3
- **Styling**: Tailwind CSS
- **Video Recording**: MediaRecorder API
- **GIF Generation**: gif.js library
- **Font Loading**: Google Fonts API

## 📋 ブラウザ対応 / Browser Compatibility

- **WebMエクスポート**: 全てのモダンブラウザ
- **MP4エクスポート**: Chrome、Edge、Safari（限定的）
- **GIFエクスポート**: 全てのモダンブラウザ
- **キャンバス録画**: Chrome、Firefox、Safari、Edge

---

- **WebM Export**: All modern browsers
- **MP4 Export**: Chrome, Edge, Safari (limited)
- **GIF Export**: All modern browsers
- **Canvas Recording**: Chrome, Firefox, Safari, Edge

## 🚀 開発 / Development

ブラウザで直接実行可能な単一ファイルHTMLアプリケーションです。

### ローカル開発 / Local Development
1. リポジトリをクローン:
   ```bash
   git clone https://github.com/kzhrknt/fontCycler.git
   cd fontCycler
   ```

2. `index.html`をブラウザで開く

### デプロイメント / Deployment
mainブランチへの変更時にGitHub Pagesへ自動デプロイされます。

---

This is a single-file HTML application that can be run directly in any web browser.

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/kzhrknt/fontCycler.git
   cd fontCycler
   ```

2. Open `index.html` in your web browser

### Deployment
The application is automatically deployed to GitHub Pages when changes are pushed to the main branch.

## 📄 ライセンス / License

このプロジェクトはオープンソースで、[MIT License](LICENSE)の下で利用可能です。

This project is open source and available under the [MIT License](LICENSE).

## 🤝 コントリビューション / Contributing

貢献を歓迎します！以下のような形でご協力ください：
- バグ報告
- 新機能の提案
- プルリクエストの送信
- ドキュメントの改善

---

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 🎨 クレジット / Credits

- **フォント**: [Google Fonts](https://fonts.google.com/)
- **GIF生成**: [gif.js](https://github.com/jnordberg/gif.js)
- **スタイリング**: [Tailwind CSS](https://tailwindcss.com/)
- **アイコン**: 絵文字

---

- **Fonts**: [Google Fonts](https://fonts.google.com/)
- **GIF Generation**: [gif.js](https://github.com/jnordberg/gif.js)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Icons**: Emoji characters

---

Built with ❤️ using React and modern web technologies.