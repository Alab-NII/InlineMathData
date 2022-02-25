# InlineMathData

We released annotated data for in-line mathematical expression detection.

## Description
If a word is a mathematical expression, the span of the word has the `data-math` attribute, whose value is `B-Math` or `I-Math`. These tags are based on simple BIO-tags, but `O-Math` is not annotated.

## Licence

Licence of the data is the same as the licence of each paper. Most papers are licensed under CC-BY-NC-SA 3.0; the rest CC-BY 4.0. See [LICENSE](LICENSE) for the detail.

## Citation

Our paper: [Detecting In-Line Mathematical Expressions in Scientific Documents](https://dl.acm.org/doi/10.1145/3103010.3121041)

```bibtex
@inproceedings{10.1145/3103010.3121041,
author = {Iwatsuki, Kenichi and Sagara, Takeshi and Hara, Tadayoshi and Aizawa, Akiko},
title = {Detecting In-Line Mathematical Expressions in Scientific Documents},
year = {2017},
isbn = {9781450346894},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3103010.3121041},
doi = {10.1145/3103010.3121041},
booktitle = {Proceedings of the 2017 ACM Symposium on Document Engineering},
pages = {141–-144},
numpages = {4},
location = {Valletta, Malta},
}
```
