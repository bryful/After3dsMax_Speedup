# After3dsMax_Speedup

3dsMaxのシーンからカメラ情報をafter effectsへ渡すプラグイン[After3dsMax](http://after3dsmax.artandgj.com/)のa3dsファイルをインポートするスクリプトです。  
  
付属のスクリプトがあまりにも遅かったので、高速化してみました。  
  
CS6をターゲットとして作成しましたが、CC2018でも動くことは確認してあります。

# Setup

After EffectsのScriptフォルダ内にあるScriptUI Panelsフォルダへコピーしてください。  
例) CS6の場合  
C:\Program Files\Adobe\Adobe After Effects CS6\Support Files\Scripts\ScriptUI Panels  
  
コピー後After Effectsを再起動させてください。

# Usage

ウィンドウメニューにこのスクリプトが表示されているので実行するとパネルウィンドウが表示されます。  
Selectボタンでa3dsファイルのダイアログで選択後、execボタンでインポートが開始されます。  
  
3000フレームのシーンならCS6なら40秒、CC2018では2分程度で完了します。  
付属のスクリプトだと15時間位はかかりますので、かなり早くなっています。  


# License

This software is released under the MIT License, see LICENSE. 

# Authors

bry-ful(Hiroshi Furuhashi) http://bryful.yuzu.bz/  
twitter:[bryful](https://twitter.com/bryful)  
bryful@gmail.com  

# References

After3dsMax http://after3dsmax.artandgj.com/

