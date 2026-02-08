# Project Status

このリポジトリは**ドキュメント中心の準備段階**です。ビルドや配布はまだ行えません。

## 今できること

- 方向性の議論（Issue での提案・検討）
- ドキュメントの整理（README / ROADMAP / CONTRIBUTING）
- upstream 候補の選定（Paper / Purpur / Folia の比較）

## できていないこと

- ソース同期の確定
- パッチ適用の仕組み
- CI でのビルド検証

## 直近の優先事項

1. upstream の決定
2. 最小ビルド構成の確立
3. CI の導入

## Definition of Done (MVP)

- `./gradlew applyPatches` が成功する
- `./gradlew createReobfPaperclipJar` が成功する
- GitHub Actions でビルドが通る
- README に再現手順が記載されている
