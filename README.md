# AD7SGPR-TokyoWeather
Qiitaの記事用に作成したWEBAppのリポジトリです。  

### 特徴  
OpenWeatherMap APIを使用して東京の現在の気温を取得  
取得した気温をブラウザ上で表示  
Web Serial APIを使用して、取得した気温をシリアル通信で送信  
  
### 必要なもの  
OpenWeatherMap APIのAPIキー  
Web Serial APIに対応したブラウザ (例: Google Chrome)
  
### 使用方法  
[WebApp](https://bit-trade-one.github.io/AD7SGPR-TokyoWeather/)を開きます。  
OpenWeatherMap APIのAPIキーを入力します。  
取得開始 ボタンをクリックします。  
指定したインターバル（秒）ごとに東京の気温を取得し、ブラウザ上に表示します。  
シリアル接続 ボタンをクリックすると、取得した気温がシリアル通信で送信されます。  
