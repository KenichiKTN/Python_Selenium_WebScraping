```markdown
# Python_Selenium_WebScraping

## ■ Seleniumのしくみ

```

\[ユーザーのPythonスクリプト]
↓
\[Seleniumライブラリ（Pythonモジュール）]
↓
\[WebDriver（ChromeDriver, MSEdgeDriverなど）]
↓
\[ブラウザアプリ（Chrome, Edge, Firefox...）]

```

---

## ■ 活用例

```

\[ユーザーの日常UIからPythonファイル呼出]
↓
\[PythonによるSelenium\_Scraping]
↓
\[CSVファイル・JPEGファイルを結果として出力]
↓
\[日常UIがファイルを取込]

```

---

## ■ 使用例

- ブラウザ版ChatGPTを、Python経由で活用する  
  [ChatGPT-AutoChat（GitHub）](https://github.com/nitin-kumar101/ChatGPT-AutoChat/blob/main/chat_with_chatgpt.py)  
  ※これは**非API利用**。正式な使い方は**APIの活用**です。

---

## ■ ブラウザの情報取得方法

### ＜非Selenium＞
- △ **RPAで動かす（UiPath、PowerAutomate）**  
　　→ 費用、認証の制限あり

### ＜Selenium＞
- ◯ **Pythonで動かす**  
　　→ プロキシ接続、HTML構造の理解が必要
- ◯ **コマンドライン**  
　　→ レスポンスの処理方法の工夫が必要
- ◯ **VBAで動かす**  
　　→ SeleniumBasicのインストールが必要
- ◯ **Zapierを利用**（Zapierはトリガー）  
　　→ 要Python対応

---

## ※ 注意点

- **ChromeDriverのバージョン**は、**Chromeブラウザと一致**させる必要あり  
- Webページの構造が変わると**スクリプトが動かなくなる可能性**あり  
- Seleniumでも**動的要素に対応できるが、万能ではない**  
- Webサイトの**利用規約（ロボット禁止など）を遵守**すること
```
