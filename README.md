# blog

## これはなに
はやまんさんの[競技プログラミング練習問題集](https://blog.hamayanhamayan.com/entry/2100/01/01/000000)のように、競技プログラミングの典型をまとめたブログを目指してる.

いわゆる、考察典型といったものなどを、類題をしめしつつ、箇条書き形式ではあるがまとめていくことを目指す.

## localで読むには
[Bundler](https://bundler.io/)を使うと読めるはず.

## メモ
Mac OSの競技プログラマーの多くは、clangではなくg++が使えるようにしている人も多いと思うが(`#include<bits/stdc++.h>`を使うため)、これが原因でjekyllやbundlerをinstallしようとしても失敗する.対処法は以下のようなオプションをつけて実行すると良い.

```
gem install jekyll -- --with-cxxflags=-std=c++11
```