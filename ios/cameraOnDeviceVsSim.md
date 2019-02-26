# カメラを使うアプリの挙動の違い

## シミュレーターの場合

`AVCaptureDevice` にnilが入ってしまうようだ。

下手をすればアプリが落ちる。

## 実機の場合

`AVCaptureDevice` には `AVCaptureDeviceInput` にうまく渡せるような値が入っている

## 結論

実機でテストしよう。
