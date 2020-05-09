# jetson_nano

## Hardware Setup

- [公式サイト](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit)

- NVIDIA Jetson Nano 開発者キット B01
  - カメラポートx2のB01を使用
  - http://akizukidenshi.com/catalog/g/gM-15021/

- 電源コード
  - Focentto (2本セット) PC マザーボード 用 電源 リセット ボタン スイッチ LED ケーブル コード ATX コンピューター ケース 用 (約66CM)
  - https://www.amazon.co.jp/gp/product/B07C7TPWJ6/ref=ppx_yo_dt_b_asin_title_o02_s00?ie=UTF8&psc=1

- Raspberry Piカメラモジュール V2
  - Camera Serial Interface(CSI-2)
  - 8メガピクセル固定フォーカス
  - 1080p、720p60、VGA90に対応
  - ソニーIMX219PQ CMOS画像センサ
  - http://akizukidenshi.com/catalog/g/gM-10518/

- micro SDカード 128GB

## Jet Pack Install
  - Jetpack4.3以上はopencv4にアップグレードされており、Darknet/Yolov3インストール時にopencv関連エラーが発生する。
    現状、解決策が見当たらないため、Jetpack4.2.3を使用する。[参考](https://qiita.com/nabion/items/8ae33dcaa336e67990b1)
  - [JetPack Archive](https://developer.nvidia.com/embedded/jetpack-archive)
  
  - 日本語インストールは、不具合の起因となる報告があるので、デフォルト(English)版のままとする。キーボードは日本語版選択。
  
## 基本設定

 - パワーモードをMAXN(電源フルパワー)に変更
 
 `sudo nvpmodel -m 0`
 - パワーモードを5Wに戻す場合
 
 `sudo nvpmodel -m `
 - クロックパフォーマンス最大化
 
 `sudo jetson_clocks`
 - クロックパフォーマンス確認
 
 `sudo jetson_clocks --show`
 
## 参考サイト

- 
