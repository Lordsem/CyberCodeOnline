## 戦闘

各駅から行くことのできるロケーションには, 「近くの敵」と入場可能な3つのダンジョンのリストが表示されます. ロケーションはレベルグループごとに分かれています. 新しいエリアのロックを解除するためには, ダンジョンにある3つのキーのかけらを集める必要があります. ターミナルにて, 集めたキーのかけらを使ってデータ解析を行うことで, 次のエリアのキーを獲得することができます.
  
近くの敵と戦うには, リストにある敵を選んで戦闘を開始します. 近くの敵との戦闘中は回復することができませんが, HPが尽きそうになったら左上の「逃走」をクリックしてください. ダンジョン内では, エイリアンのマークで表される敵をクリックすると, その敵との戦闘になります。

## 戦闘画面
戦闘画面では, 自分と相手のHPやシールドの量, 各武器の残弾数, およそのダメージ量が表示されます. 

## メインウェポンでの攻撃（main）
装備したメインウェポンで敵を攻撃します. この武器は弾薬を消費しませんが, 同レベル・同レアリティの他の種類の武器と比べると, 最も低いダメージしか与えられません. 

## スペシャルウェポンでの攻撃（special）
装備したスペシャルウェポンで敵を攻撃します. 敵の装備しているシールドに対しては120%のダメージを与えるほか, シールドを削りきってHPにもダメージを与える場合, そのダメージにも補正がかかります. この武器は1発につき**エネルギーセル**を1つ消費します. 同レベル・同レアリティの他の武器と比較した場合, メインウェポンより与えるダメージが高く, 量子兵器よりは低いです. 

## 量子兵器での攻撃（Destructive）
装備した量子兵器で敵を攻撃します. この攻撃はシールドに対しては50%のダメージしか与えられないほか, シールドを削りきってHPにもダメージを与える場合, そのダメージも半減したままです. この武器は1発につき**アンチマターチャージ**を1つ消費しますが, 同レベル・同レアリティの他の種類の武器よりも高いダメージを与えることができます（シールドを持った敵を除く）.

## アイテムの使用
アイテムを使用するクイックスロットが3つあります. このスロットには回復アイテム, 支援クレート, エクスペリエンスメモリーを装備しておくことができますが, 戦闘中に使用する必要があるのは回復アイテムだけなので, 他のアイテムを装備することはないでしょう. また, クイックスロットには自動ソート機能はありません.

## 逃走
左上の「逃走」をクリックすると, 戦闘からの離脱を試みることができます. ダンジョン外での逃走の成功率は常に100％です. しかし, ダンジョン内の戦闘からの逃走を試みる場合, その成功率は装備とアップグレードモジュールの逃走成功率（escape）のステータスに基づいて決定されます. 逃走に失敗した場合, ダメージを与えられないまま敵の攻撃を受けることになります.

## 死亡
「心停止」とも呼ばれる状態です. プレイヤーは少しの間何もできなくなります. 死亡してもアイテムは失われませんが, レベルが11以上の場合, 所持しているビットコインとプレイヤーEXPの10%が失われてしまいます. EXPの減少によって現在のレベルの必要量を下回った場合, レベルは下がってしまいます.

## 敵の追加効果
  
敵には追加効果があり, 敵の名前の前に形容詞で表示されます（例：**Mad** 大きな荷物を担いだゴブリン）. これらの効果は以下の通りです.
  
 - Mad - （怒り狂った）：敵から受けるダメージ量が+10％になります.
 - Angry - （怒れる）：敵から受けるダメージ量が+10％になります.
 - Tough - （頑丈な）：プレイヤーが与えるダメージが-20%になります.  
   - また, ゲーム内での記述はありませんが, 敵のHPが大幅に上昇し, ダメージもやや高くなります.  
 - Agile - （素早い）：敵に+20%のスタン回避率のステータスとシールドを付与します.  
   - シールドの数値は敵のHPの半分の値です.  
 - Shielded - （シールドを備えた）：敵に高いシールド量を持つシールドを付与します.  
   - シールドの数値は敵のHPの2倍の値です.  
   - その代わり, HP自体はやや低めになっています.  
 - Precise - （精密射撃の）：敵が10%の確率でクリティカルヒットを繰り出すようになり, その際のダメージは+40%になります.  
   - また, ゲーム内での記述はありませんが, シールドも付与されています.  
 - Berserker - （狂戦士）：敵のHPとこちらが受けるダメージ量が大幅に上昇し, またシールドも付与されます.  
   - ゲーム内での記述はありませんが, シールドとHPがかなり高くなっているので（ボスを除き, この二つは同じぐらいの数値になっています）気付きやすいでしょう.  

追加効果に関する重要な点

1. 敵から受けるダメージは, 上記の要素に応じて乗算された後, あなたの装備による軽減を受けてHPに影響します. この仕様により, 追加効果のない敵と比較した際にかなり大きなダメージを受ける場合があります. 
2. 「Tough」な敵を倒すには, 通常よりもかなり多く攻撃しなければならない場合があるでしょう.
3. 「Agile」な敵は "回避率" （プレイヤーの攻撃が確実に当たるとは限らない）ではなく "スタン回避率" にボーナスを受けています（プレイヤーのスタン率のパラメータの80%しか機能しない.　例：プレイヤーのスタン率が20%の時, 「Agile」を持つ敵がスタンする確率は16%）. もし敵をスタンさせる戦法を取っているのであれば, このような敵と対峙する際はいつもより多めに回復するようにしましょう.  

## プレイヤーの追加効果
  
プレイヤーもまた, ダンジョン内でクエストNPCに話しかけることで追加効果を得ることができます. クエストは「?」で表されるマスで受けることができます. 効果は以下の通りです.

### Overcharged（オーバーチャージ）
プレイヤーの攻撃力を強化します. プレイヤーが与えるダメージ量の強化割合は以下の通り.

|名称|効果|
|--|--|
|Overcharged I|与ダメージ量+5%|
|Overcharged II|与ダメージ量+10%|
|Overcharged III|与ダメージ量+15%|
|Overcharged V|与ダメージ量+20%|

### Reinforced（リーンフォース：「補強する」「強固にする」等の意）
プレイヤーの受けるHPダメージを減少させます. プレイヤーの防御力の強化割合は以下の通り.

|名称|効果|
|--|--|
|Reinforced I|防御力+5%|
|Reinforced II|防御力+10%|
|Reinforced III|防御力+15%|
|Reinforced V|防御力+20%|

###  Shield Enhance（シールドエンハンス）
プレイヤーのシールドを強化します. プレイヤーのシールド倍率の強化割合は以下の通り.

|名称|効果|
|--|--|
|Shield Enhance I|シールド倍率+5%|
|Shield Enhance II|シールド倍率+10%|
|Shield Enhance III|シールド倍率+15%|
|Shield Enhance V|シールド倍率+20%|

これらの追加効果は, クエストタブから依頼されたアイテムを渡し, クエストを達成した瞬間からカウントダウンが始まります（達成可能なクエストは黄色で表示されます）. ダンジョン内でクエストを受注しておいて, 後から任意のタイミングで追加効果を発動させることができます. 報酬として得られる追加効果はクエストごとに提示されています.

また, プレイヤーへの追加効果はレベルの違うものであれば重複します. 例えばOvercharged IとOvercharged IIは同時に発動させることができ, 合計で+15%のダメージ補正になります. ただし既に発動している効果を再び発動した場合（例えばOvercharged Iを2回発動させた場合）には重複はせず, 代わりに効果の持続時間がリセットされます.