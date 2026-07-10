# メゾン・アカデミー ― ブランドバッグ＆ジュエリー検定

高級ブランドのバッグ・ジュエリー・宝飾品にまつわる **全300問** のクイズです。
ブラウザだけで動く1枚のHTMLファイル（依存ライブラリなし）。

👉 **公開ページ:** `https://miyamotono.github.io/brand-bag-jewelry-quiz/`
（下の「公開手順」を実行するとこのURLで遊べるようになります）

---

## 特徴

- **5カテゴリー × 難易度3段階（初級・中級・上級）で各20問、計300問**
  - メゾンの基礎 ― 創業者・本拠地・グループの系譜
  - 代表モデル・アイコン ― バーキンからアルハンブラまで
  - 素材と職人技 ― レザー・貴金属・宝石・技法
  - 歴史とトリビア ― メゾンにまつわる物語
  - 査定・買取の知識 ― 状態評価・付属品・相場
- 回答するたびに **正誤＋豆知識の解説** を表示
- 結果画面はゴールドのゲージと **称号**（メゾン・マスター／コレクター級／愛好家 ほか）
- 「総合ミックス」「おまかせ（全レベル）」出題に対応
- 選択肢は毎回シャッフルされ、正解位置が偏りません
- スマートフォン対応・アニメーション軽減設定にも配慮

---

## ファイル構成

```
.
├── index.html    ← クイズ本体（このHTMLを貼り付ける）
├── README.md     ← この説明ファイル
├── LICENSE       ← ライセンス（MIT）
└── .gitignore
```

> **重要:** クイズのHTMLは必ず `index.html` という名前で保存してください。
> GitHub Pages はリポジトリ直下の `index.html` をトップページとして表示します。

---

## ローカルで動かす

`index.html` をダブルクリックしてブラウザで開くだけです。サーバーもビルドも不要です。

---

## GitHub Pages での公開手順

### 方法A：ブラウザだけで完結（かんたん）

1. GitHubで新しいリポジトリを作成（例：`maison-academy`）。公開は **Public** を選択。
2. 「Add file」→「Create new file」でファイル名を `index.html` にし、用意したHTMLを貼り付けてコミット。
3. 同じ手順で `README.md`・`LICENSE`・`.gitignore` も追加。
4. リポジトリの **Settings → Pages** を開く。
5. 「Build and deployment」の Source を **Deploy from a branch** にし、Branch を `main` /（フォルダは）`/ (root)` に設定して **Save**。
6. 1〜2分待つと、ページ上部に公開URLが表示されます。そこにアクセスすれば完成です。

### 方法B：git コマンドを使う

```bash
# 作業フォルダに index.html / README.md / LICENSE / .gitignore を置いた状態で
git init
git add .
git commit -m "メゾン・アカデミー公開"
git branch -M main
git remote add origin https://github.com/miyamotono/brand-bag-jewelry-quiz.git
git push -u origin main
```

その後、**Settings → Pages** から方法Aの手順4〜6と同じ設定を行ってください。

---

## クレジット・注意

- クイズの内容は一般に知られた情報をもとにした学習用のものです。相場や仕様は時期により変動します。
- ブランド名・商品名は各社の商標です。本プロジェクトは非公式・ファンメイドの学習コンテンツです。

## ライセンス

このリポジトリのコードは [MIT License](./LICENSE) の下で公開されています。
# brand-bag-jewelry-quiz
高級ブランドのバッグ・ジュエリー検定クイズ（全300問・1枚のHTMLで動作）
