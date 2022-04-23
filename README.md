# Experiment using Unet

- Unetアーキテクチャが精度良く検出できるパターンを調べる

## Issue Tree

- 検出対象
  - 羊 (Pascal VOC 2012) [#1](issue001/README.md)
- ハイパーパラメータ
- 構成されるBlock, Module
- 事前学習の有/無

## 参考文献

## 用語（私見）

- Layer：深層学習モデルを構成する最小の関数
  - ex) Convolution layer, Pooling layer, Padding layer, etc.
- Block：Layerを組み合わせて構成されるひとまとまりの関数
  - ex) Residual block, SE block, MBConv Block, etc.
- Module：LayerやBlockを組み合わせて構成される関数
  - ex) Inception module, etc.
- Network：Layer, Block, Moduleを組み合わせて構成される深層学習モデル
  - ex) VGG, ResNet, Inception, EfficientNet, etc.
- Architecture：Networkの骨組みとなる構造
  - ex) Unet, etc.
