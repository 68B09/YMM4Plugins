# YMM4Plugins
YMM4用プラグインモジュール

ここで提供しているプラグインを使用した事により発生した不具合・損害などについて当方は一切関知しません。  
使用される場合はその旨十分ご理解された上でお願いいたします。  
<br>
プラグインのインストール方法は[<a href="https://manjubox.net/" target="_blank">饅頭遣いのおもちゃ箱</a>]-[<a href="https://manjubox.net/ymm4/" target="_blank">ゆっくりMovieMaker4</a>]-[<a href="https://manjubox.net/ymm4/faq/plugin/how_to_use/" target="_blank">プラグインを使用する</a>]を参照してください。
****
## [BlinkEffects]
指定秒数で表示と非表示を繰り返すプラグインです。  
<a href="https://twitter.com/MB68B09/status/1728731961144066362" target="_blank">Sample(twitter)</a>  
	<table>
		<tr>
			<td>
				<img src="https://github.com/68B09/YMM4Plugins/blob/main/docs/ymm4plugin_blink1.png">
			</td>
			<td valign="top">
				[映像エフェクト]－[アニメーション]－[点滅]<br>
				<br>
				【点滅時間】<br>
					表示・非表示の持続時間を秒数で指定します。<br>
					0秒を指定した場合は点滅しません。<br>
				<br>
				【非表示で開始】<br>
					有効にすると非表示から開始します。<br>
					消えた状態からスタートしたい場合に使用します。<br>
			</td>
		</tr>
	</table>
   
内部では、非表示期間はOpacity(不透明度)を0に、表示期間はOpacityは操作せずそのままスルーしています。  
不透明度を操作している他の映像エフェクトと同時に使用する際には「エフェクトの適用順」に注意してください。  
本エフェクトは一番最後に適用されるエフェクトとして使うのが一番安全(?)だと思います。  
  
ダウンロード  
BlinkEffects/BlinkEffects.zip  
(install ex)...\YukkuriMovieMaker4\user\plugin\BlinkEffects\BlinkEffects.dll  

___
## ライセンス
YMM4が指定しているライセンスに従います。  
指定がない場合、MITライセンスとします。  
___
## 履歴
2023/11/26 68B09  
First release.
