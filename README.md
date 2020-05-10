# admobtest
admobtest

テスト環境　2019.3.5.f1
AdMobSDK　v5.0.1

参考サイト
https://developers.google.com/admob/unity/start?hl=ja

● 試した流れ

Mobile Ads Unity プラグインをダウンロード
https://github.com/googleads/googleads-mobile-unity/releases/tag/v5.0.1

Switch Platform > Android

[Assets] > [Play Services Resolver] > [Android Resolver] > [Resolve] で各種ファイルをインストール

[Assets] > [Google Mobile Ads] > [Settings] 

Enabledにチェック  　
テスト用IDを設定  
  
#UNITY_ANDROID  
string adUnitId = "ca-app-pub-3940256099942544/6300978111";  

#UNITY_IPHONE  
string adUnitId = "ca-app-pub-3940256099942544/2934735716";


AdMobTest.csを作成

空のオブジェクトにAdMobTest.csをアタッチ

AdMobTest.csに下記RequestBannerあたりまで記述
https://developers.google.com/admob/unity/banner?hl=ja
