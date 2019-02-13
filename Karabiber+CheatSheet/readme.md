Mac USキーボードユーザーの方へ。  
`Karabiner-Elements`と`CheatSheet`を同時に使うためのプラグインです。

## 〜導入と設定の手順〜  
### Jsonファイルを指定のフォルダに追加（インポート）
>`Finder` → `移動` → `フォルダへ移動` →
>`~/.config/karabiner/assets/complex_modifications/`  
>上記のフォルダの中にダウンロードしたJsonファイルを入れます。

### Karabiner-Elementsでルールを追加
>`Karabiner-Elementsを起動` → `Complex Modifications` → `Add rule` →  
>`Commandキー { 短押し => 英数/かな切替(トグル式), 長押し => >Cheatsheet }` → `Enable`  
>これでRulesに追加されます。  

<br>

各Commandキーを押して試してみましょう。  
トグル式になっているのでどちらを押しても、英数/かな切り替えができます。
長押しするとCheatSheetも起動します。

このままでも問題ないですが、CheatSheetの起動を少し早くすると使い勝手も良くなります。  
CheatSheetを表示させた状態で  
`右下の歯車マーク` → `Delay` → `Short`  
起動が早くなっていい感じになりました。

以上で導入と設定は終わりです。