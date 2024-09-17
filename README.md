<p align="center">
  <h2 align="center"><strong>TextureDiffusion: Target Prompt Disentangled<br> Editing for Various Texture Transfer</strong></h2>

<p align="center">
    <a href="https://github.com/Sugewud">Zihan Su</a>,
    <a href="https://github.com/zhuang2002">Junhao Zhuang</a>,
    <a href="https://github.com/ppcd401d2">Chun Yuan</a>
    <br>
    <b>Tsinghua University</b>
</p>

<div align="center">

<a href='https://arxiv.org/abs/2409.09610'><img src='https://img.shields.io/badge/arXiv-2409.09610-b31b1b.svg'></a> 

</div>




<p align="center">
    <img src="image/teaser.png" alt="TexutreDiffusion" width="1000" height="auto">
</p>

## Release
- [09/16] Initial Preview Release 🔥 Coming Soon!

## Contents
- [Release](#release)
- [Contents](#contents)
- [🐶 Introduction](#-introduction)
- [📆 TODO](#-todo)
- [🙌🏻 Acknowledgement](#-acknowledgement)
- [📖 BibTeX](#-bibtex)

## 🐶 Introduction
Recently, text-guided image editing has achieved significant success. However, existing methods can only apply simple textures like wood or gold when changing the texture of an object. Complex textures such as cloud or fire pose a challenge. This limitation stems from that the target prompt needs to contain both the input image content and \<texture\>, restricting the texture representation. In this paper, we propose TextureDiffusion, a tuning-free image editing method applied to various texture transfer. 

![pipeline](image/pipeline.png)
<br><br> 
![qualitative_comparison](image/qualitative_comparison.png)
![quantitative_comparison.jpg](image/quantitative_comparison.png)

## 📆 TODO
The repo is still being under construction, thanks for your patience. 
- [ ] Release of code.


## 🙌🏻 Acknowledgement
Our code is based on these awesome repos:
* [PnPInversion](https://arxiv.org/abs/2310.01506) [[code](https://github.com/cure-lab/PnPInversion/tree/main)]
* [MasaCtrl](https://arxiv.org/abs/2304.08465) [[code](https://github.com/TencentARC/MasaCtrl)]

## 📖 BibTeX
If you find our repo helpful, please consider leaving a star or cite our paper :)
```bibtex
@article{su2024texturediffusion,
  title={TextureDiffusion: Target Prompt Disentangled Editing for Various Texture Transfer},
  author={Zihan Su, Junhao Zhuang, Chun Yuan},
  journal={arXiv preprint arXiv:2409.09610},
  year={2024}
}


