# game-filters

**game-filters** は、広告フィルタ環境 (AdGuard Home / uBlock Origin など) で  
モバイルゲームの「広告視聴による報酬」を正しく受け取るために必要な **ホワイトリスト設定** をまとめたリポジトリです。

---

## 背景

広告ブロッカーを利用していると、  
- 動画広告が再生されない  
- 広告視聴による報酬が受け取れない  

といった問題が発生することがあります。  
このリポジトリでは、ゲーム内広告が動作するように必要最低限のドメインをホワイトリスト化しています。

---

## 対応ゲーム
- 白猫プロジェクト (Shironeko Project)

---

## 使用方法

### AdGuard Home
1. 管理画面にアクセス
2. 「フィルタ」→「カスタムルール」に移動
3. 以下のリンクを追加  
   👉 [設定リンクはこちら](https://raw.githubusercontent.com/FilterNeko/game-filters/refs/heads/main/game-filter.txt)
4. 保存して反映

### uBlock Origin
1. 拡張機能の「設定」→「マイフィルター」へ移動
2. 以下のリンクを追加  
   👉 [設定リンクはこちら](https://raw.githubusercontent.com/FilterNeko/game-filters/refs/heads/main/game-filter.txt)
3. 保存して反映

---

## ファイル構成
- `game-filter.txt`  
  → ゲームの広告再生に必要なホワイトリストドメイン一覧

---

## 注意事項
- 本リポジトリは **ゲーム内で必要な広告だけ** を許可することを目的としています。  
- 環境やフィルタアプリのバージョンによって挙動が異なる場合があります。  
- 自己責任でご利用ください。

---

## ライセンス
MIT License

