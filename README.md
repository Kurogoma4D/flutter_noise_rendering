# noise_test

Flutter での画像生成とアニメーションの例．

# 参考文献

Render Treeのみを使った描画例

https://github.com/flutter/flutter/blob/master/examples/layers/rendering/spinning_square.dart

Flutter内でのピクセル単位処理とそれを使った画像生成

https://gist.github.com/ds84182/6a949816f860a2344735383afe43e261#file-main-dart

"How do I Render Individual Pixels in Flutter?"  
ピクセル単位処理に関する stack overflow の質問  
結論： `CustomPainter` で1ピクセルずつ描画するより `dart:ui` に入ってる `decodeImageFromPixels` を使ったほうがいいよ

https://stackoverflow.com/questions/55844043/how-do-i-render-individual-pixels-in-flutter

# 動画
## FBMノイズアニメーション生成
[![thumbnail](https://pbs.twimg.com/ext_tw_video_thumb/1208695372509396992/pu/img/cATSOm7mM37_QRr1.jpg)](https://twitter.com/Krgm4D/status/1208695590818697216)

## シンプルなアニメーション
[![thumbnail](https://pbs.twimg.com/ext_tw_video_thumb/1208591972941697024/pu/img/FpVpkv-TyBYUqpI1.jpg)](https://twitter.com/Krgm4D/status/1208592011420266498?ref_src=twsrc%5Etfw)
