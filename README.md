# macOS mi Style

このテーマは、macOS用 日本語テキストエディタ **mi** のスタイルと**ダークターミナル**を組み合わせた VSCode 用カラーテーマです。  
This is a combination of my favorite app **"mi"** style color theme and **dark terminal**.

## Features

### 🎨 Laravel + Livewire + Blade に最適化
**Laravel開発に特化したカラーリング！**
- **Blade ディレクティブ** (`@if`, `@foreach`, `@extends` など) を視覚的に識別しやすく
- **Livewire コンポーネント** (`wire:model`, `wire:click` など) のシンタックスハイライト対応
- **Blade 内の PHP コード** や文字列を適切に色分け
- **Alpine.js** (`x-data`, `x-show` など) との組み合わせも見やすく

### 📝 日本語入力時の未確定文字の問題を解決！

VSCode では `"editor.lineHighlightBackground"` の色が特定の色だと、日本語入力時に未確定文字が太くなる問題が発生します。

**解決策**
- **ライトテーマの場合** → `"#f0f0f0"` などの明るい色 or `#00000000`（完全透明）
- **ダークテーマの場合** → `"#202020"` などの暗い色 or `#00000000`（完全透明）

#### **🚀 本テーマではこの問題を完全解決済み！**
**✅ ライト・ダークどちらのテーマでも安心して使えます！**

## Screenshot
**Laravel Blade + Livewire**
![Laravel Blade](./images/demo-blade.png "Laravel Blade のスクリーンショット")

**PHP**
![Screenshot１](./images/demo-php.png "sample - PHPのスクリーンショット")
![Screenshot２](./images/demo-php-terminal.png "sample - PHPとTerminalのスクリーンショット")
**HTML/CSS**
![Screenshot4](./images/demo-html-css.png "JSとTerminalのスクリーンショット")
**HTML/JavaScript**
![Screenshot3](./images/demo-html.png "sample - HTML/SCRIPTのスクリーンショット")
**JavaScript**
![Screenshot4](./images/demo-js-terminal.png "JSとTerminalのスクリーンショット")

## インストール方法
1. VSCode の拡張機能タブを開く。
2. `macOS mi Style` を検索する。
3. インストールボタンをクリックする。

## 使用方法
1. メニューから「表示」→「コマンドパレット」を選択。
2. 推奨設定（Laravel開発向け）
Laravel + Livewire + Blade での開発をさらに快適にするため、以下の拡張機能との併用をおすすめします：

- **Laravel Blade Snippets** - Bladeの入力補完
- **Laravel Blade Spacer** - Bladeのフォーマット
- **Laravel Extra Intellisense** - Laravelの入力支援
- **Livewire Goto** - Livewireコンポーネントへのジャンプ

## `Preferences: Color Theme` と入力して選択。
3. `macOS mi Style` を選ぶ。

## 貢献方法
バグ報告や機能提案は、Issue や Pull Request を通じてお願いします。

## ライセンス
このプロジェクトは MIT ライセンスの下で公開されています。

## About mi

- **[macOS 用 日本語テキストエディタ mi](https://www.mimikaki.net/)**

