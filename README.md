# OTSim (OT-Tone Simulator)

[日本語]  
ユニークな「おたまじゃくし型」の電子楽器 **OT-Tone** をブラウザ上で体験できる、Webベースのシミュレータアプリ（非公式）です。  
タッチ操作やマウスドラッグによる直感的なスライド演奏や、楽譜に合わせた「曲の練習モード」を搭載しています。

[English]  
A web-based simulation app (unofficial) that lets you play a unique, "tadpole-shaped" slide synthesizer (**OT-Tone**) right in your browser.  
It features intuitive touch/drag controls and a "Song Practice Mode" to help you learn classic melodies.

👉 **Play Now / 今すぐ演奏する:** [https://otamaninja.github.io](https://otamaninja.github.io)

---

## ✨ 主な機能 / Features

### 🇯🇵 日本語
*   **直感的なスライド演奏**: 画面のバーをタッチ・ドラッグすることで、ピッチ（周波数）をシームレスに変更しながら演奏できます。音に合わせてキャラクターの口が可愛く開閉します。
*   **3段階の音域設定**: `LOW`・`MID`・`HIGH` の3つの音域（オクターブ）へワンタッチで切り替えが可能です。
*   **曲の練習モード**: 
    *   「かえるのうた 🐸」「きらきら星 ⭐」「ふるさと 🏔️」の3曲を搭載。
    *   テンポ（とてもゆっくり〜ふつう）をシニアや初心者向けに合わせて調整可能。
    *   画面上にガイドハイライトとドレミ表記が表示され、ガイドに沿って演奏を練習できます。
*   **カスタマイズ性**:
    *   本体カラー変更（黒、白、ピンク、青）
    *   背景テーマの選択 ＆ **お好みの背景写真アップロード機能**
    *   利き手に合わせて操作バーを左右に切り替える「反転（ミラー）」機能
    *   音量調整、デバッグ用周波数（Hz）リアルタイム表示

### 🇺🇸 English
*   **Intuitive Slide Controls**: Touch or drag the slider bar to smoothly change the pitch. The character's mouth opens and closes dynamically as you play.
*   **3 Octave Ranges**: Easily switch between `LOW`, `MID`, and `HIGH` registers to fit your favorite songs.
*   **Interactive Song Practice Mode**:
    *   Includes three classic songs: "Frog Song 🐸", "Twinkle Twinkle ⭐", and "Furusato 🏔️".
    *   Adjustable speeds (Very Slow, Slow, Normal)—perfect for beginners and seniors.
    *   Visual guides with highlighted note positions and Japanese Solfège ("Do-Re-Mi") labels to help you follow along.
*   **Rich Customization**:
    *   Change body colors (Black, White, Pink, Blue).
    *   Choose preset background colors or **upload your own background photo**.
    *   "Mirror" toggle button to flip the control bar left/right for left-handed players.
    *   Volume slider and debug mode to display real-time frequency (Hz).

---

## 🛠️ 技術スタック / Tech Stack

*   **Frontend**: HTML5 / CSS3 / Vanilla JavaScript (No frameworks)
*   **Audio Generation**: Web Audio API (Sine wave oscillator synthesis)
*   **Design**: Responsive layout & CSS animations (wagging tail, countdown effects, etc.)
*   **Hosting**: GitHub Pages

---

## 💻 ローカル環境での動作方法 / Local Development

### 🇯🇵 日本語
このプロジェクトは、フレームワークや外部依存ライブラリを使用しないシンプルな **Single Page Application (SPA)** です。

1. **リポジトリをクローンする**
   ```bash
   git clone [https://github.com/otamaninja/otamaninja.github.io.git](https://github.com/otamaninja/otamaninja.github.io.git)
   cd otamaninja.github.io
