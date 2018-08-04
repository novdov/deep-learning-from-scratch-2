# ゼロから作る Deep Learning ❷
# 밑바닥부터 시작하는 딥러닝 ❷ - 자연어처리편

- 원서 구매 후 사용 편의를 위해 직접 번역하는 repo
- 구매처: [O'Reilly Japan](https://www.oreilly.co.jp/books/9784873118369/) (ebook으로 구매, DRM Free)

---

![表紙](https://raw.githubusercontent.com/oreilly-japan/deep-learning-from-scratch-2/images/deep-learning-from-scratch-2.png)

---

本リポジトリはオライリー・ジャパン発行書籍『[ゼロから作る Deep Learning ❷](https://www.oreilly.co.jp/books/9784873118369/)』のサポートサイトです。

## 폴더 구성

|폴더명 |설명                         |
|:--        |:--                          |
|ch01       |1장에서 사용되는 소스 코드    |
|ch02       |2장에서 사용되는 소스 코드    |
|...        |...                          |
|ch08       |8장에서 사용되는 소스 코드    |
|common     |공통으로 사용되는 소스 코드   |
|dataset    |데이터셋용 소스 코드 | 

소스 코드의 설명은 도서를 참고

> 학습 완료된 가중치(6, 7장에서 사용)는 아래 URL에서 다운로드 가능 
> <https://www.oreilly.co.jp/pub/9784873118369/BetterRnnlm.pkl>

## Dependency
ソースコードを実行するには、下記のソフトウェアがインストールされている必要があります。

* Python 3.x
* NumPy
* Matplotlib
* [CuPy](https://github.com/cupy/cupy) (옵션, NumPy-like API accelerated with CUDA)

※ Python 버전은 3.x 사용.

## 실행 방법

각 장의 폴더로 이동해서 파이썬 코드를 실행

```
$ cd ch01
$ python train.py

$ cd ../ch05
$ python train_custom_loop.py
```

## 라이센스

이 repo의 소스 코드는 [MIT 라이센스](http://www.opensource.org/licenses/MIT)를 따름.
상업・비상업 관계 없이 자유롭게 사용 가능

## 정오표

본 도서의 정오표는 아래에 공개되어 있음

https://github.com/oreilly-japan/deep-learning-from-scratch-2/wiki/errata

本ページに掲載されていない誤植など間違いを見つけた方は、[japan＠oreilly.co.jp](<mailto:japan＠oreilly.co.jp>)までお知らせください。
