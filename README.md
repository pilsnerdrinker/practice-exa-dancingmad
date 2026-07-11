# P5 エクサ練習（混沌の終末） - 絶妖星乱舞

FF14「絶妖星乱舞」P5 混沌の終末（エクサ）用の非公式練習ページです。

6レーンのうち2レーンずつ飛んでくるエクサを、左・中・右パターンの直線攻撃として判別する練習ができます。

- 公開ページ: https://pilsnerdrinker.github.io/practice-exa-dancingmad/
- 英語表示: https://pilsnerdrinker.github.io/practice-exa-dancingmad/?lang=en
- リポジトリ: https://github.com/pilsnerdrinker/practice-exa-dancingmad
- [English README](#english-readme)

## できること

- 位置確認モードで、予兆と直線攻撃の流れを7枚のスライドで確認
- 位置確認のマップをクリックして安地判定
- 実践練習モードで、緑のキャラを動かして回避練習
- マウス・タッチ・WASD・矢印キー・ゲームパッドで操作
- エクサ発動速度を `2.5s` から `5.0s` まで調整
- マーカー配置を `2341` / `1234` で切り替え
- 表示を右45度 / 左45度に回転
- 前の問題、同じ問題、新しい問題の切り替え
- 一問ごとモードと連続モードの切り替え
- 終了時に `パーフェクト！` またはヒット数をマップ上に表示
- 右上の `JA / EN` スイッチで日本語と英語を切り替え

## モード

### 位置確認

エクサの予兆と直線攻撃を7枚のスライドで確認します。

| スライド | 表示内容 |
| --- | --- |
| 1 | 1回目予兆 |
| 2 | 1回目直線 + 2回目予兆 |
| 3 | 2回目直線 + 3回目予兆 |
| 4 | 3回目直線 + 4回目予兆 |
| 5 | 4回目直線 + 5回目予兆 |
| 6 | 5回目直線 + 6回目予兆 |
| 7 | 6回目直線 |

マップをクリックすると、その位置が安全か確認できます。

予兆の段階は踏んでもセーフです。直線攻撃の範囲を踏むと誤答扱いになります。

連続モードでは、安地を選ぶと正解表示後に次のスライドへ自動で進みます。最後のスライドが終わると、次の問題へ進みます。

一問ごとモードでは自動で進まず、右上の `＜` / `＞` でスライドを移動します。

### 実践練習

3カウント後にエクサが開始します。緑のキャラを動かして、全6回のエクサを回避します。

- 予兆時間: `3.7s`
- エクサ発動速度: 初期値 `3.6s`
- 速度バー: `2.5s` から `5.0s`
- エクサ: 1レーンにつき7回発動
- 全6回

終了時には、0ヒットなら `パーフェクト！`、被弾した場合は `2ヒット` のように結果をマップ上へ表示します。

連続モードでは、結果を3秒表示したあと、次の問題の3カウントが自動で始まります。

一問ごとモードでは、結果を表示した状態で停止します。

## パターン

各方向ごとに左・中・右の3パターンが1回ずつ出ます。

同じ方向内で同じパターンは重複しません。合計6回の出現順と各パターンは、問題ごとに生成されます。

## 操作

### 共通

- `前の問題`: 直前の問題へ戻る
- `新しい問題`: 新しいパターンを生成
- `一問ごと`: 自動送り / 自動次問を停止
- `2341` / `1234`: フィールドマーカー番号を切り替え
- `45度`: 通常 → 右45度 → 通常 → 左45度 の順で表示を回転
- `JA / EN`: 表示言語を切り替え

### 実践練習

- マウス / タッチ: マップ上で移動先を指定
- キーボード: `WASD` または矢印キー
- ゲームパッド: 左スティックまたは十字キー
- `同じ問題`: 同じパターンをもう一度開始
- `速度`: エクサの1個目から7個目までの発動時間を調整
- `⏸ 一時停止` / `▶ 再開`: 実践練習を一時停止または再開

## 言語切り替え

右上の `JA / EN` スイッチで表示言語を切り替えられます。

選択した言語はブラウザに保存されます。英語版を直接開く場合は、URLの末尾に `?lang=en` を付けてください。

## 更新履歴

### 2026-07-12

- WASD・ゲームパッドに対応
- 英語版を追加

## 注意

- このページは個人制作の非公式練習ページです。
- 実際の処理やコールは、参加するパーティーの方針に合わせてください。

---

<a id="english-readme"></a>

# English README

# P5 Exaflare Practice (Stray Apocalypse) -Dancing Mad (Ultimate)

This is an unofficial practice page for the P5 Stray Apocalypse Exaflare mechanic in Dancing Mad (Ultimate).

It helps you recognize the left, center, and right patterns of two Exaflare lanes selected from six lanes.

- Practice page: https://pilsnerdrinker.github.io/practice-exa-dancingmad/?lang=en
- Japanese page: https://pilsnerdrinker.github.io/practice-exa-dancingmad/
- Repository: https://github.com/pilsnerdrinker/practice-exa-dancingmad

## Features

- Review the telegraphs and line attacks in a seven-slide Position Check mode
- Click the arena in Position Check mode to test whether a location is safe
- Move the green character and dodge the mechanic in Practice mode
- Control the character with mouse, touch, WASD, arrow keys, or a gamepad
- Adjust the Exaflare activation time from `2.5s` to `5.0s`
- Switch field marker numbering between `2341` and `1234`
- Rotate the arena view 45 degrees to the right or left
- Return to the previous problem, retry the same problem, or generate a new problem
- Switch between Continuous and One-by-one modes
- Show `Perfect!` or the number of hits on the arena after each run
- Switch between Japanese and English with the `JA / EN` switch

## Modes

### Position Check

Review the telegraphs and line attacks across seven slides.

| Slide | Display |
| --- | --- |
| 1 | First telegraph |
| 2 | First line attack + second telegraph |
| 3 | Second line attack + third telegraph |
| 4 | Third line attack + fourth telegraph |
| 5 | Fourth line attack + fifth telegraph |
| 6 | Fifth line attack + sixth telegraph |
| 7 | Sixth line attack |

Click the arena to check whether the selected location is safe.

Standing in a telegraph is safe at the preview stage. Only an active line attack is treated as an incorrect answer.

In Continuous mode, selecting a safe location shows the result and automatically advances to the next slide. After the final slide, a new problem begins.

In One-by-one mode, the slides do not advance automatically. Use the `＜` / `＞` buttons in the upper-right corner.

### Practice

After a three-second countdown, the Exaflares begin. Move the green character and dodge all six waves.

- Telegraph time: `3.7s`
- Default Exaflare activation time: `3.6s`
- Speed range: `2.5s` to `5.0s`
- Activations per lane: 7
- Total waves: 6

At the end of a run, the arena displays `Perfect!` for zero hits or a result such as `2 Hits`.

In Continuous mode, the result remains visible for three seconds, then the countdown for the next problem begins automatically.

In One-by-one mode, the page stops on the result screen.

## Patterns

Each direction uses the left, center, and right patterns exactly once.

The same pattern is not repeated within the same direction. Each problem generates a six-wave sequence.

## Controls

### Common controls

- `Previous`: Return to the previous problem
- `New Problem`: Generate a new pattern
- `One-by-one`: Disable automatic slide and problem advancement
- `2341` / `1234`: Change field marker numbering
- `45°`: Cycle through normal → right 45° → normal → left 45°
- `JA / EN`: Change the display language

### Practice controls

- Mouse / touch: Select a movement destination on the arena
- Keyboard: `WASD` or arrow keys
- Gamepad: Left stick or D-pad
- `Same Problem`: Restart the current pattern
- `Speed`: Adjust the activation time from the first to the seventh Exaflare
- `⏸ Pause` / `▶ Resume`: Pause or resume the practice run

## Language

Use the `JA / EN` switch in the upper-right corner to change the display language.

The selected language is stored in your browser. Add `?lang=en` to the page URL to open the English version directly.

## Update History

### 2026-07-12

- Added WASD and gamepad controls
- Added the English version

## Notes

- This is an unofficial fan-made practice page.
- Follow the strategy and callouts used by your own party.
