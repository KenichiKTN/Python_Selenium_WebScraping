# Python_Selenium_WebScraping

■ Seleniumのしくみ
[ユーザーのPythonスクリプト]  
      ↓  
[Seleniumライブラリ（Pythonモジュール）]  
      ↓  
[WebDriver（ChromeDriver, MSEdgeDriverなど）]  
      ↓  
[ブラウザアプリ（Chrome, Edge, Firefox...）]  


■ 活用例
[ユーザーの日常UIからPythonファイル呼出]  
      ↓  
[Python(Selenium)によるHTML取得（JavaScript含む）]  
      ↓  
[Beautiful SoupでHTML解析]  
      ↓  
[CSVファイル・JPEGファイルを結果として出力]  
      ↓  
[日常UIがファイルを取込]  



■ 使用例

・ブラウザ版ChatGPTを、Python経由で活用する  
  https://github.com/nitin-kumar101/ChatGPT-AutoChat/blob/main/chat_with_chatgpt.py  
  ※これは非API利用。正式な使い方はAPIを活用する。

■ ブラウザの情報取得方法

＜非Selenium＞  
△RPAで動かす（UiPath、PowerAutomate）・・・費用、認証

＜Selenium＞  
◯pythonで動かす・・・・・・・・・・・・・・プロキシ接続、HTML構造  
◯コマンドライン・・・・・・・・・・・・・・レスポンスの処理方法  
◯VBAで動かす・・・・・・・・・・・・・・・SeleniumBasicのインストール  
◯zappirを利用（Zappierはトリガー）・・・・要Python

※注意点  
・ChromeDriverを使う＝Chromeとのバージョンの一致  
・Webページ構造の変更  
・Seleniumでも動的要素は対応できるが弱い  
・利用規約（ロボット禁止など）
