# VertexPurpur

> **Yatopiaの意志を継ぐ、究極の1.19.4専用Minecraftサーバー**

[![License](https://img.shields.io/badge/license-GPL--3.0-blue.svg)](LICENSE)
[![Minecraft](https://img.shields.io/badge/minecraft-1.19.4-brightgreen.svg)](https://www.minecraft.net/)
[![Java](https://img.shields.io/badge/java-17+-orange.svg)](https://adoptium.net/)

## ATTENTION!このサーバーは未完成です！完成するかもわかりません！ごめんね！！

## 🚀 What is VertexPurpur?

VertexPurpurは、かつてのYatopiaが目指した「極限までの最適化」という理念を受け継ぎ、さらにその先へ進化させた**究極のMinecraftサーバーソフトウェア**です。

### ✨ 特徴

- **⚡ 究極の軽量化** - 数多の最適化パッチを統合し、徹底的なパフォーマンスチューニング
- **🧵 Foliaライクなマルチスレッド** - 複数コアを活用しながら、既存プラグインとの互換性をほぼ維持
- **🎯 1.19.4特化** - 単一バージョンに集中することで、安定性とパフォーマンスを追求
- **💡 Yatopiaの遺伝子** - 伝説的な最適化プロジェクトの思想を現代に継承
- **🔧 プラグイン互換性** - Foliaと違い、既存のプラグインがほぼそのまま動作

---

## 🎯 Why VertexPurpur?

### 他のサーバーソフトとの違い

| 特徴 | Paper | Purpur | Folia | **VertexPurpur** |
|------|-------|--------|-------|------------------|
| 軽量化 | ⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐⭐⭐ |
| マルチスレッド | ❌ | ❌ | ✅ | ✅ |
| プラグイン互換性 | ✅ | ✅ | ⚠️ 限定的 | ✅ ほぼ完全 |
| 安定性 | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐ | ⭐ |
| 1.19.4対応 | ✅ | ✅ | ✅ | ✅ |

**VertexPurpurは、Foliaの革新的なマルチスレッドと、従来サーバーの安定性・互換性のいいとこ取りを実現しました。**

---

## 📥 Download & Installation

### Requirements / 必要環境

- Java 17 or higher
- 1.19.4 Minecraft client
- 最低 2GB RAM（推奨 4GB+）

## ⚙️ Configuration / 設定

VertexPurpurは以下の設定ファイルをサポートします：

- `purpur.yml` - Purpur互換設定
- `paper-world-defaults.yml` - Paper互換設定
- `spigot.yml` - Spigot互換設定
- `bukkit.yml` - Bukkit互換設定
- `purpur.yml` - Purpur互換設定
- ここに書かれていないコード元ソフト互換設定

---

## 🔌 Plugin Compatibility / プラグイン互換性

VertexPurpurは既存のBukkit/Spigot/Paper/Purpurプラグインとほぼ完全に互換性があります。

**動作確認済み:**
- EssentialsX ✅
- WorldEdit ✅
- Vault ✅
- LuckPerms ✅
- CoreProtect ✅

**注意が必要:**
- 非同期処理を適切に扱っていないプラグイン
- チャンクロード周りでタイミングに依存するプラグイン

問題があれば [Issues](https://github.com/wisemanjr4/VertexPurpur-1.19.4/issues) で報告してください！

---

## 🏗️ Building from Source / ソースからビルド

```bash
# Clone the repository
git clone https://github.com/yourusername/VertexPurpur.git
cd VertexPurpur

# Build
./gradlew applyPatches
./gradlew createReobfPaperclipJar

# Output: build/libs/vertexpurpur-paperclip-1.19.4-R0.1-SNAPSHOT-reobf.jar
```

---

## 🤝 Contributing / 貢献

VertexPurpurはコミュニティの力で成長します！

### 貢献方法

1. **🐛 バグ報告** - [Issues](https://github.com/wisemanjr4/VertexPurpur-1.19.4/issues) でバグを報告
2. **💡 最適化の共有** - あなたの発見した最適化技術をぜひ共有してください！
3. **🔧 Pull Request** - コードの改善を提案
4. **📖 ドキュメント** - Wiki の充実にご協力を

**素晴らしい最適化を見つけたら、独り占めせずにコミュニティと共有しましょう！** 私たちは先人の肩の上に立っています。

詳しくは [CONTRIBUTING.md](CONTRIBUTING.md) をご覧ください。

---

## ⚠️ Disclaimer / 免責事項

VertexPurpurは**実験的プロジェクト**です。

- Yatopiaと同様、極限の最適化を追求するため、予期しない動作が発生する可能性があります
- 本番環境での使用前に、十分なテストを推奨します
- データのバックアップを必ず取ってください
- サポートはベストエフォートです

**使用は自己責任でお願いします。**

---

## 📜 License

VertexPurpur is licensed under [GPL-3.0](LICENSE).

本プロジェクトは、Yatopia、DivineMC、PlazmaMC、その他多くの素晴らしいプロジェクトの成果に基づいています。すべての貢献者に感謝します。

---

## 🙏 Credits / クレジット

VertexPurpurは以下のプロジェクトなしには存在しませんでした：

- **Yatopia** - Inspiration and optimization philosophy
- **DivineMC** - Performance patches
- **PlazmaMC** - Optimization techniques
- **Paper / Purpur / Pufferfish** - Upstream projects
- **Folia** - Multi-threading architecture inspiration

そして、マイクラサーバー最適化コミュニティのすべての方々へ。

---

## 💬 Community / コミュニティ

- **Discord**: [Join our Discord]() (準備中)
- **Issues**: [GitHub Issues](https://github.com/wisemanjr4/VertexPurpur-1.19.4/issues)
- **Wiki**: [Documentation](https://github.com/wisemanjr4/VertexPurpur-1.19.4/wiki)

---

<p align="center">
  <i>...こんなこと書いてるけど挫折したらどうしよ。</i>
</p>

<p align="center">
  Made with ❤️ for the Minecraft community
</p>
