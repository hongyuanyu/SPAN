# SPAN - ESR

<div align="center">

<h2><a href="https://arxiv.org/abs/2311.12770">Swift Parameter-free Attention Network for Efficient Super-Resolution</a></h2>

[Cheng Wan](https://jornywan.github.io), [Hongyuan Yu](https://hongyuanyu.github.io/), [Zhiqi Li](https://zhiqili-cg.github.io/), Yihang Chen, Yajun Zou, Yuqing Liu, Xuanwu Yin and Kunlong Zuo

[![Paper](https://img.shields.io/badge/cs.CV-2403.06977-b31b1b?logo=arxiv&logoColor=red)](https://arxiv.org/abs/2311.12770)

</div>

<div align="center">
  <img src="assets/demo.gif" width="800px" />
  <!-- <p>cell.</p> -->
</div>

## 🚀 Updates
- \[2024.06.11\] 🎉 SPAN is selected for an Oral Presentation at CVPR 2024, NTIRE Workshop!
- \[2024.04.09\] 🎉 Our [paper](https://arxiv.org/abs/2311.12770) is accepted to CVPR 2024 Workshop!
- \[2024.03.21\] 🏆 SPAN won the **1st place** in CVPR 2024 NTIRE's Efficient Super-Resolution Challenge(ESR) -> [Challenge Report](https://arxiv.org/abs/2404.10343)
- \[2023.03.10\] Release ✅ checkpoints for our different pretrained models -> [Google Drive](https://drive.google.com/file/d/1iYUA2TzKuxI0vzmA-UXr_nB43XgPOXUg/view?usp=sharing).
- \[2023.11.23\] Upload ✅ SPAN codes here.
  
## 📖 Introduction:
The official pytorch implementation of the paper **[Swift Parameter-free Attention Network for Efficient Super-Resolution](https://arxiv.org/pdf/2311.12770.pdf)**

>Single Image Super-Resolution (SISR) is a crucial task in low-level computer vision, aiming to reconstruct high-resolution images from low-resolution counterparts. Conventional attention mechanisms have significantly improved SISR performance but often result in complex network structures and large number of parameters, leading to slow inference speed and large model size. To address this issue, we propose the Swift Parameter-free Attention Network (SPAN), a highly efficient SISR model that balances parameter count, inference speed, and image quality. SPAN employs a novel parameter-free attention mechanism, which leverages symmetric activation functions and residual connections to enhance high-contribution information and suppress redundant information. Our theoretical analysis demonstrates the effectiveness of this design in achieving the attention mechanism's purpose. We evaluate SPAN on multiple benchmarks, showing that it outperforms existing efficient super-resolution models in terms of both image quality and inference speed, achieving a significant quality-speed trade-off. This makes SPAN highly suitable for real-world applications, particularly in resource-constrained scenarios. Notably, our model attains the best PSNR of 27.09 dB, and the test runtime of our team is reduced by 7.08ms in the NTIRE 2023 efficient super-resolution challenge.

<div align="center">
  <img src="assets/model.png" width="800px" />
  <!-- <p>cell.</p> -->
</div>


## 🔧 Installation:
This implementation based on [BasicSR](https://github.com/xinntao/BasicSR). Please refer to BasicSR for training and testing.
You can obtain all the checkpoints and results from [[Google Drive](https://drive.google.com/file/d/1iYUA2TzKuxI0vzmA-UXr_nB43XgPOXUg/view?usp=sharing)].

```python
python 3.9.5
pytorch 1.11.0
cuda 11.3
```

```
git clone this repo
cd SPAN
pip install -r requirements.txt
python setup.py develop --no_cuda_ext
```


## 📈 Results
<div align="center">
  <img src="assets/results.png" width="400px" />
  <!-- <p>cell.</p> -->
</div>

<div align="center">
  <img src="assets/vis.png" width="800px" />
  <!-- <p>cell.</p> -->
</div>


## 📍 Citation

If our work is useful to you, please use the following BibTeX for citation.

```latex
@inproceedings{wan2024swift,
  title={Swift Parameter-free Attention Network for Efficient Super-Resolution},
  author={Wan, Cheng and Yu, Hongyuan and Li, Zhiqi and Chen, Yihang and Zou, Yajun and Liu, Yuqing and Yin, Xuanwu and Zuo, Kunlong},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={6246--6256},
  year={2024}
}
```



## 📜 License and Acknowledgement

This project is released under the [Apache 2.0 license](LICENSE.txt).<br>
More details about **license** and **acknowledgement** are in [LICENSE](LICENSE/README.md).
