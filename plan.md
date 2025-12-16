HAGAKURE PROGRAMMING塾 エージェントコーディング勉強会 資料作成プラン
概要
「HAGAKURE PROGRAMMING塾 2025.12.20 エージェントコーディング勉強会」のための資料を作成します。 「Antigravity」をテーマにし、hero.png の温かみのあるコミュニティ感を活かしたモダンなスライドにします。和風のキャラクター（侍/忍者）を装飾として取り入れ、学びと交流の場を表現します。

コンテンツ構成案 (全12枚想定)

1. タイトル
イベント名: HAGAKURE PROGRAMMING塾 2025.12.20
タイトル: Antigravityではじめるエージェントコーディング
ヒーローセクション: hero.png を使用（勉強会・コラボレーションの雰囲気）
サブ: かつてない「ペアプログラミング」体験へ

2. エージェントコーディングとは？
従来: 人間が書いて、AIが補完する (Autocomplete)
これから: AIが「エージェント」としてタスクを自律的に遂行する (Agentic)
イメージ: voice-ninja1.png (影のように働く有能なアシスタント)

3. Antigravityの紹介
Antigravityとは何か (Google DeepMind発の先進的エージェント)
何ができるのか (全ファイル操作、ターミナル実行、ブラウザ操作、自己修正)

4. 準備とセットアップ (ダウンロード)
必要な環境 (VS Code等)
Antigravityの導入 (インストール手順のイメージ)
ワークスペースの設定

5. 【重要】リスクと安全対策 (News & Warning)
事例紹介: 「AI誤処理でHDD内データ全消去」のニュース
- 記事リンク
- ユーザー「すべてのファイルを消して」→ AI「分かりました（全消去）」
教訓:
- AIは強力な権限を持っている
- 指示は具体的かつ慎重に
- 破壊的なコマンド（削除、上書き）の前には必ず確認を
Antigravityの安全機能:
- 承認プロセス (User Approval) の徹底
- SafeToAutoRun の適切な運用

6. カスタマイズ設定: あなた好みのエージェントに
回答を日本語にしてもらう方法:
- Agentパネル右上の「…」から「Customizations → Rules → +Global」
- 「日本語で回答してください」と設定
Global設定で自分用のルールを追加できる
イメージ: voice-ninja2.png

7. 基本ワークフロー: 3つのモード
The Create Loop
- Planning: 計画と設計 (implementation_plan.md)
- Execution: 実装と変更
- Verification: 検証とテスト (walkthrough.md)

8. 重要な概念: アーティファクト
エージェントとの「共通言語」としてのドキュメント
- task.md: 進捗管理の要
- implementation_plan.md: 設計図

9. ハンズオン: Hello World
ダウンロード: https://antigravity.google/download
最初のタスク: 「HTMLでHello Worldを表示するページを作って」
- ファイル作成
- 基本的なHTML構造
- ブラウザで確認
→ エージェントとの最初の対話を体験

10. もっと試してみよう: 次のステップ
慣れてきたら、こんなタスクにも挑戦：

📝 シンプル系:
「カウンターアプリを作って。+ボタンと-ボタンで数を増減」

🎨 デザイン系:
「和風デザインの都道府県クイズアプリを作って」

📊 データ処理系:
「CSVファイルから表を生成してHTMLで表示して」

🔧 リファクタリング系:
「このコードを読みやすくリファクタリングして」

→ あなたのアイデアをエージェントに伝えてみよう

11. 推奨環境: ブラウザ拡張機能
Chrome Extension: Antigravity Browser Extension
- URL: Chrome Web Store Link
- ブラウザ操作をよりスムーズに

12. まとめとBest Practices
エージェントは「魔法」ではなく「優秀な同僚」
明確な指示とレビューが重要
Enjoy Agentic Coding!

🍲 Let's Share!
「お鍋を食べながら、今日の成果物を見せ合いましょう！」
→ コミュニティでの学びと交流を楽しもう
イメージ: hero.png の右側（お鍋を囲む様子）を強調
デザイン・技術要件
共通ヘッダー/フッター: 「HAGAKURE PROGRAMMING塾 2025.12.20」を全スライドに配置
カラーパレット: hero.png から抽出した温かみのある色合い
ベース: クリーム色 (#F5F3E8) / ベージュ (#E8E5D8)
背景: 淡いブルーグレー (#B8C5D6)
テキスト: ダークグレー (#3A3A3A) / チャコール (#4A4A4A)
アクセント1: 温かい茶色 (#A67C52) - 見出し、重要項目
アクセント2: ソフトブルー (#7BA5C8) - リンク、補助情報
アクセント3: ソフトグリーン (#8FB88F) - ポジティブなメッセージ、成功例
アクセント4: ソフトイエロー (#F4D58D) - ハイライト、注目ポイント
警告色: ソフトコーラル (#E89B8E) - 注意事項、リスク対策
画像配置:
ヒーローセクション: hero.png はタイトルページで大きく使用（フルワイド、height: 400px程度）
装飾画像: voice-samurai.png, voice-ninja1.png, voice-ninja2.png, machi-musume.png はアイコンサイズ（max-height: 120px程度）
レイアウト: hero.png の世界観を活かした温かみのあるデザイン。コミュニティ感を演出。
voice-samurai.png: 力強いメッセージのページ
voice-ninja1.png / voice-ninja2.png: 機能紹介やTechnicalなページ
machi-musume.png: まとめのページ等
形式: Single File HTML (index.html)
スタイル: モダン × 和風 (CSS Grid/Flexbox, Custom Properties)
制約: スライド1枚の高さ max 800px
検証計画
ブラウザで開き、全スライドが表示されるか確認
800pxの高さ制約内に収まっているか確認
ページネーション動作確認