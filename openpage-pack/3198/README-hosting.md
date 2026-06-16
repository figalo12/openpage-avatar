# OpenPage Hosting Guide

このパックは `figalo12/openpage-avatar` の GitHub Pages 配信を前提にしています。

## 公開先
- Repository: `figalo12/openpage-avatar`
- GitHub Pages base URL: `https://figalo12.github.io/openpage-avatar/`

## このフォルダの配置先
この `3198` フォルダは、リポジトリ内で次の場所に置きます。

```text
openpage-pack/3198/
```

## OpenPage 登録に使う URL
1. MML URL
   - `https://figalo12.github.io/openpage-avatar/openpage-pack/3198/3198.mml`
   - OpenPage にはこの `.mml` URL を登録します
   - `.glb` 直リンクは登録しません
2. GLB URL
   - `https://figalo12.github.io/openpage-avatar/openpage-pack/3198/3198.glb`
   - これは MML の `src` から参照されます
3. Animation URL
   - 現時点では未設定です
   - 必要なら `idle.glb` などを同じフォルダに置いて追加してください
4. VRM URL
   - 任意です
   - 未所持なら空欄で問題ありません

## 現在の MML
`3198.mml` は相対パスで `./3198.glb` を参照しています。
GitHub Pages 上では `3198.mml` と `3198.glb` が同じフォルダにあれば動作します。

## OpenPage 側で手動で行うもの
- アイコン / PFP / サムネイル画像のアップロード
- 名前と説明の入力
- 価格、供給数、公開期間などの設定

## 事前条件
- Community Page
- Community Vault
- Create Units

## 公開確認
登録前に、ログアウト状態のブラウザで次の URL が 200 で開くことを確認してください。
- `https://figalo12.github.io/openpage-avatar/openpage-pack/3198/3198.mml`
- `https://figalo12.github.io/openpage-avatar/openpage-pack/3198/3198.glb`
