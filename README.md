# NSS Result Tracker

Nintendo Switch Sports サッカー の戦績を自動で記録・可視化するプロジェクトです。

---

## 開発環境のセットアップ (Development Setup)

このプロジェクトを開発する際は、まず仮想環境を有効化してください。

**Windows (PowerShell / コマンドプロンプト):**

```bash
.\venv\Scripts\activate
```

**macOS / Linux:**

```bash
source venv/bin/activate
```

ターミナルの行頭に (venv) と表示されれば、仮想環境に入れています。

---

## 依存ライブラリ（Dependencies）

このプロジェクトで利用している Python ライブラリは requirements.txt に記載されています。
以下のコマンドで、必要なライブラリをすべてインストールできます。

```bash
pip install -r requirements.txt
```

## 使い方（Usage）

(ここに、将来的にアプリケーションを実行するためのコマンドを記述します。)

```python
python main.py
```

## 機能（Features）

- ゲーム画面のリアルタイムキャプチャ
- リザルト画面の自動検知とスクリーンショット撮影
- 画像から勝敗とスコアを OCR で抽出
- 結果を CSV ファイルに保存
- 戦績データをグラフで可視化

## 注意事項（Notes）

- このプログラムを実行するには、別途 [[https://github.com/tesseract-ocr/tesseract | Tesseract OCR]] のインストールが必要です。
