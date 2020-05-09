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

##

# Setup
## Jetson Nano OS Install
- OSインストール：[公式サイト](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit) 参照
- アップデート&アップグレード&各種ツールインストール

```
sudo apt update
sudo apt upgrade
sudo apt install gedit gcc git wget ssh
```
