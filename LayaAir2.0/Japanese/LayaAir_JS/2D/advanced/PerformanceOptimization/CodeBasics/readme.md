# 运行时代码执行基本原理

​

LayaAirエンジンはAS 3、Type Script、JavaScriptの3つの言語の開発をサポートしていますが、どの開発言語を採用しても、最終的に実行されるのはJavaScriptコードです。見た画面はすべてエンジンで作成され、更新周波数は開発者が指定したFPS、例えば指定フレーム周波数は60 FPSであれば、実行時の各フレームの実行時間は60分の1秒となるので、フレーム速度が高いほど視覚的に滑らかになり、60フレームはフルフレームである。

実際の動作環境はブラウザにあるので、JavaScript解釈器の効率にも依存しています。指定されたFPSフレームレートは、低性能インタプリタでは達成できないかもしれません。だから、この部分は開発者が決定できるものではなく、開発者ができるものは、できるだけ優れたものにして、ローエンドデバイスまたは低性能ブラウザで、FPSフレームレートを向上させます。

LayaAirエンジンは、フレーム毎に塗り替えられますが、パフォーマンス最適化の際には、フレーム毎の論理コード実行によるCPU消費に注目するほか、描画コマンドの呼び出し数やGPUのテクスチャの提出回数にも注意が必要です。


 

 