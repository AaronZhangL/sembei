oscca-sembei : Segmentation-free version of Eigenwords (OSCCA)
===================================================

単語分割を経由しない単語埋め込み手法 *segmentation-free word embeddings (sembei)* [1] の Python 実装．
この実装では，行列分解に基づく単語埋め込み手法 eigenwords (OSCCA) [2] をベースにしている．


## Installation

```sh
git clone https://github.com/shimo-lab/sembei
cd sembei
python setup.py build && python setup.py install
```

## How to use

[\(oscca\-\)sembei の実行例](https://gist.github.com/oshikiri/da68f7b9b2aa9c626280176060266e34)


## Requirements

* anaconda3 (>=4.1.1)
* memory_profiler


## References

1. 押切 孝将, 下平 英寿. 単語分割を経由しない単語埋め込み. 言語処理学会第23回年次大会論文集, pp.258-261. 言語処理学会, 2017年3月.
2. Dhillon, P. S., Foster, D. P., and Ungar, L. H. (2015). Eigenwords: Spectral word embeddings. Journal of Machine Learning Research, 16:3035–3078.
