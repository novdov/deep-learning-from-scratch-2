# ゼロから作る Deep Learning ❷
# 밑바닥부터 시작하는 딥러닝 ❷ - 자연어처리편

- 원서 구매 후 학습/사용 편의를 위해 직접 번역해서 사용하고 있습니다.
- 구매처: [O'Reilly Japan](https://www.oreilly.co.jp/books/9784873118369/) (ebook으로 구매, DRM Free)

---

![表紙](https://raw.githubusercontent.com/oreilly-japan/deep-learning-from-scratch-2/images/deep-learning-from-scratch-2.png)

---

이 저장소는 Oreilly Japan에서 발행한 도서 『[ゼロから作る Deep Learning ❷](https://www.oreilly.co.jp/books/9784873118369/)』의 학습을 위한 저장소입니다.

## 폴더 구성

|폴더명 |설명                         |
|:--        |:--                          |
|ch01       |1장에서 사용되는 소스 코드    |
|ch02       |2장에서 사용되는 소스 코드    |
|...        |...                          |
|ch08       |8장에서 사용되는 소스 코드    |
|common     |공통으로 사용되는 소스 코드   |
|dataset    |데이터셋용 소스 코드 | 

소스 코드의 설명은 도서를 참고하시기 바랍니다.

> 학습 완료된 가중치(6, 7장에서 사용)는 아래 URL에서 다운로드 가능합니다.
> <https://www.oreilly.co.jp/pub/9784873118369/BetterRnnlm.pkl>

## Dependency
소스코드를 실행하기 위해서는 아래의 라이브러리가 필요합니다.

* Python 3.x
* NumPy
* Matplotlib
* [CuPy](https://github.com/cupy/cupy) (옵션, NumPy-like API accelerated with CUDA)

※ Python은 3.x 버전을 사용합니다.

## 실행 방법

각 장의 폴더로 이동해서 파이썬 코드를 실행합니다.

```
$ cd ch01
$ python train.py

$ cd ../ch05
$ python train_custom_loop.py
```

## 라이센스

이 repo의 소스 코드는 [MIT 라이센스](http://www.opensource.org/licenses/MIT)를 따릅니다.
상업・비상업 관계 없이 자유롭게 사용 가능합니다.

## 정오표

본 도서의 정오표는 아래에 공개되어 있습니다.

https://github.com/oreilly-japan/deep-learning-from-scratch-2/wiki/errata

위의 페이지에 게재되어 있지 않은 오식이나 오류를 발견한 분은 [japan＠oreilly.co.jp](<mailto:japan＠oreilly.co.jp>)으로 제보해주시기 바랍니다.
