# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## プロジェクト概要

このリポジトリは、シンプルなHTML/CSS/JavaScriptによるWebアプリケーションです。現在はHello Worldを表示する基本的なWebページが実装されています。

## アーキテクチャ

- **フロントエンド**: 純粋なHTML5、CSS3、JavaScript（フレームワーク無し）
- **スタイリング**: インラインCSS、モダンなCSS機能（Flexbox、グラデーション、シャドウ）を使用
- **言語**: 日本語対応のUI

## 開発コマンド

### アプリケーションの実行
```bash
# ブラウザでHTMLファイルを開く
open index.html
```

### 開発時の注意点
- このプロジェクトはフレームワークを使用していないため、ビルドやコンパイルは不要
- HTMLファイルを直接ブラウザで開いて動作確認を行う
- スタイルはindex.html内の`<style>`タグで管理

## ファイル構成

- `index.html` - メインのWebページ（HTML、CSS、JavaScriptを含む）

## 開発ガイドライン

- 日本語でのUI表記を維持する
- モダンなCSS機能を活用したデザイン
- レスポンシブデザインに対応（viewport設定済み）
- シンプルで理解しやすいコード構造を保つ