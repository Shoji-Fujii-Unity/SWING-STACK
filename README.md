# スイングスタック / SWING STACK / 摇摆高塔

対応言語: 日本語 / English / 中文

## 概要

スイングスタックは、HTML で動作するタイミングアクションゲームです。  
左右にスイングするクレーンから、タップまたはクリックでタイミングよくパーツを落とし、どこまで高く、バランスよく積めるかを競います。

ファイルは index.html 1つで動作します。  
物理エンジンには Matter.js を使用しています。

---

## 日本語

### 動作確認

- PC: ブラウザで index.html を開く
- スマホ: index.html をブラウザで開く
- 画面は縦長表示になります

### 遊び方

- 遊んでいる画面をタップする
- PCではクリック、スペースキーでも操作できます
- クレーンの下でパーツを離し、落とします
- 目標の高さまで積み上げるとステージクリアです
- 落下しすぎると失敗になります

### 操作方法

- タップ: パーツを落とす
- クリック: パーツを落とす
- スペースキー: パーツを落とす
- 戻るボタン: メニューに戻る
- 音ボタン: サウンド ON/OFF
- 言語ボタン: 日本語 / English / 中文 を切り替える

### サウンド

- ゲーム内ボタンで SOUND ON/OFF を切り替えられます
- 初回はタップなど、ユーザー操作後にサウンドが有効になります

### 言語

このゲームは3言語に対応しています。

- 日本語
- English
- 中文

言語はゲームメニューから変更できます。  
言語設定は端末の言語が自動で参照され、保存データに含まれます。

### 保存データ

保存データはローカルブラウザの localStorage に保存されます。

保存される内容

- 解除済みステージ
- 各ステージの最高記録
- サウンド設定
- 言語設定

サーバー送信はありません。

### ステージ

ステージは多く用意しています。

- 初期は安定しやすいパーツ中心
- 進行するほどバランスしにくいパーツが増加
- 目標高さ、クレーンの揺れ速度、揺れ幅が段階的に増加
- クリアすると次のステージが解放されます

### 物理エンジン

このゲームは Matter.js を使用しています。

index.html 内で次のCDNから読み込んでいます。

https://cdnjs.cloudflare.com/ajax/libs/matter-js/0.20.0/matter.min.js

### オフライン利用について

初回読み込み時には通信が必要です。  
オフラインで使う場合は、matter.min.js を index.html と同じフォルダに置いてください。  
その場合、index.html 内のスクリプトパスを変更する必要があります。

### ファイル構成

推奨

- index.html
- README.md
- 任意で matter.min.js

最小

- index.html

---

## English

### Running

- PC: open index.html in a browser
- Mobile: open index.html in a browser
- The game uses a portrait layout

### How to Play

- Tap the game screen to drop the part
- On PC you can also click or press Space
- Release the part under the swinging crane
- Reach the target height to clear the stage
- Drop below the stage limit to fail

### Controls

- Tap: drop the part
- Click: drop the part
- Space key: drop the part
- Back button: return to menu
- Sound button: toggle sound ON/OFF
- Language buttons: switch between Japanese, English, and Chinese

### Sound

- Sound can be toggled from the in-game button
- Audio starts after the first user interaction

### Languages

The game supports three languages:

- Japanese
- English
- Chinese

Language can be changed from the menu.  
The selected language is included in the local save data.

### Save Data

Save data is stored in the browser using localStorage.

Saved data

- Unlocked stages
- Best record for each stage
- Sound setting
- Language setting

No data is sent to a server.

### Stages

Many stages are available.

- Early stages use stable parts
- Later stages introduce harder parts
- Target height and crane motion increase gradually
- Clearing a stage unlocks the next one

### Physics Engine

This game uses Matter.js.

It is loaded from this CDN in index.html.

https://cdnjs.cloudflare.com/ajax/libs/matter-js/0.20.0/matter.min.js

### Offline Use

Internet access is required for first loading.  
For offline use, place matter.min.js in the same folder as index.html.  
Then change the script source in index.html.

### Files

Recommended

- index.html
- README.md
- Optional: matter.min.js

Minimum

- index.html

---

## 中文

### 运行方式

- 电脑: 在浏览器中打开 index.html
- 手机: 在浏览器中打开 index.html
- 游戏使用竖屏画面

### 玩法

- 点击游戏画面即可落下零件
- 电脑也可以点击或用空格键操作
- 在摆动起重机的正下方释放零件
- 达到目标高度即可通过关卡
- 零件掉出画面下方会失败

### 操作

- 点击: 落下零件
- 鼠标点击: 落下零件
- 空格键: 落下零件
- 返回按钮: 返回菜单
- 音效按钮: 切换音效 ON/OFF
- 语言按钮: 切换 日本語 / English / 中文

### 音效

- 游戏内按钮可以切换音效开关
- 首次点击等用户操作后音效才会启用

### 语言

本游戏支持三种语言:

- 日本語
- English
- 中文

可以在菜单中切换语言。  
语言设置会保存到本地存档中。

### 存档数据

存档保存在浏览器的 localStorage 中。

保存内容

- 已解锁关卡
- 每关最高记录
- 音效设置
- 语言设置

不会向服务器发送数据。

### 关卡

关卡数量较多。

- 前期使用容易稳定的零件
- 后期会增加更难堆叠的零件
- 目标高度、起重机速度、摆动幅度会逐渐增加
- 通过关卡会解锁下一关

### 物理引擎

本游戏使用 Matter.js。

index.html 中从下面的 CDN 加载:

https://cdnjs.cloudflare.com/ajax/libs/matter-js/0.20.0/matter.min.js

### 离线使用

首次加载需要网络。  
离线使用时，请将 matter.min.js 放在与 index.html 相同的目录。  
然后修改 index.html 中的脚本路径。

### 文件结构

推荐

- index.html
- README.md
- 可选: matter.min.js

最小

- index.html