# じゃんけん

## DEMO

  - https://sakisuematsu.github.io/janken/

## 紹介と使い方

  - コンピューター相手の一対一じゃんけん
  - 勝った時のみ他のゲームで遊べる

## 工夫した点
  - ヘッダーのじゃんけんにhoverした時にランダムで色が変わる  
  - じゃんけんの手を絵に置き換え  
  - じゃんけんの手をhoverした時に少し大きくなる効果をつける
  - ホバーしたら「じゃんけん」、クリックしたら「ぽん」の音を鳴らす  
  - muteボタンの設置  
  - muteが効いてるかどうか、色と文字でわかるようにした
  - じゃんけん結果の表示する時、選んでない手を非表示にする  
  - もう一回じゃんけんをするボタンでリロードして初期画面に戻る  
  - 勝った時のみ、写経したミニゲームを選択できる  
  - ミニゲーム画面からもじゃんけん画面に戻れるようにした  
  - 一度じゃんけんをした後、再度じゃんけんの手（img）を押してもじゃんけんできないようにした   
  - 一度じゃんけんをした後、再度じゃんけんの手（img）のhoverの効果を消した 

## 苦戦した点

  - じゃんけん改造のアイデア出し。何も思いつかず丸一日経ちました。。。  
  - じゃんけん結果の手と勝ち・負け・あいこの並びのバランス
  - じゃんけんの2度押し防止の実装のために、htmlとcssを書き換えることになって冷や汗かきました
  - ひとつのmuteボタンで、「じゃんけん」「ぽん」の両方の音をミュートにするところ  

## 苦戦している点、積み残し

  - ミニゲーム選択ボタンで遊ぶ  
  - ミニゲームブロック崩しの実装（写経）  
 
  
## 参考にした web サイトなど

  - リロード https://developer.mozilla.org/ja/docs/Web/API/Location/reload
  - 音を鳴らす・ミュートする https://kakechimaru.com/btn_audio/
  - 音声の変換 https://www.apowersoft.jp/free-online-video-converter
  - hoverの消し方 https://kouhekikyozou.com/css_hover_cancel
  - ボタンの2度押し防止 https://dainamo.jp/btn_disabled/

  ### 写経したミニゲーム
  - マルバツゲーム https://qiita.com/dai_designing/items/c37a6baeecf0216303ec
  - テトリス https://joytas.net/programming/tetris1
  - ぷよぷよ https://edu.monaca.io/puyo
  - ブロック崩し https://developer.mozilla.org/ja/docs/Games/Tutorials/2D_Breakout_game_pure_JavaScript