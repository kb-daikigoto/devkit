# DEVKIT — エンジニアの道具箱

依存ゼロ・完全オフラインの単一HTML製デベロッパーツール集。
データは一切外部に送信されず、すべてブラウザ内で完結します。

🔗 **公開サイト**: https://kb-daikigoto.github.io/devkit/

## ツール（8種）

JSON整形/パス検索・JWTデコード/署名検証・正規表現テスター・テキストdiff(LCS)・
Base64/URL/HTML/Hexエンコード・SHAハッシュ/UUID生成・epoch時刻変換・cron式の解説と次回実行計算。

## 使い勝手

- 🌗 **ライト / ダークテーマ**（システム設定に追従・記憶）
- 🔗 **ディープリンク**（`#json` などツール毎のURL・ブラウザの戻る/進む対応）
- 📂 **ドラッグ&ドロップ**でファイルを各ツールに読み込み
- ⌨️ `⌘K` コマンドパレット / `⌘1`〜`⌘8` ツール切替 / `?` ショートカット一覧
- 💾 入力は localStorage に自動保存

## 開発

単一ファイルなので、`index.html` を編集してコミット・プッシュするだけでサイトが更新されます。
ビルド・サーバー・依存パッケージは不要です。

```bash
git add -A && git commit -m "update" && git push
```

🤖 Generated with [Claude Code](https://claude.com/claude-code)
