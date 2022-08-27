# mandelbrot-rust

Rustでマンデルブロ集合を描画するプログラム

参考: [プログラミングRust](https://www.oreilly.co.jp/books/9784873119786/)

## 実行時間(40000x30000)

- シングルスレッド

```time
real    3m45.049s
user    3m44.752s
sys     0m0.263s
```

- crossbeam(24スレッド)

```time
real    0m28.773s
user    4m24.217s
sys     0m0.343s
```
