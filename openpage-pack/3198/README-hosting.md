# OpenPage Hosting Guide

このパックは OpenPage の MML互換アバター登録用です。

## 前提
- Community Page
- Community Vault
- Create Units

## 公開するファイル
- 3198.mml
- 3198.glb
- animation.glb または既存のアニメーションGLB
- VRM がある場合のみ .vrm

## 登録時のURL項目
1. MML URL
   - https://example.com/openpage-pack/3198/3198.mml
   - .mml を返す安定URLにしてください
   - GLB直リンクは不可です
2. Animation URL
   - https://example.com/openpage-pack/3198/animation.glb
   - OpenPage の 3D Avatar URLs の Animation URL 欄に入力します
3. VRM URL
   - 任意です。未所持なら空欄で問題ありません

## MML内の src
- MML の src は https://example.com/openpage-pack/3198/3198.glb を想定しています
- 実ホスティング先に合わせて差し替えてください

## 提出時の注意
- サムネイルは 2000x2000px 以上の正方形 JPG/PNG
- 名前・説明・サムネイルはオリジナルのみ
- URL はログアウト状態でも参照できることを確認してください
