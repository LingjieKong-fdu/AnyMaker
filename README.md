<div align="center">
  
## AnyMaker: Zero-shot General Object Customization via Decoupled Dual-Level ID Injection 

</div>

<div align="left">

###  **Core Properties:**

1. **General field:**  Applicable to customization for general objects, including but not limited to: human face, clothes, artificial tools, animal, ...
2. **Fast generation:** Achieve object customization within seconds, without any further fine-tuning
3. **User friendly:** Just one single reference image and a text prompt can meet the customization requirement
4. **Outstanding results:** Ensure high ID fidelity, flexible text editability and high quality.
5. **Various applications:** Diverse applications such as general object customization, virtual try-on, ID-mixing, ...

---

###  **Method Framework:**

AnyMaker consists of three crucial ID processing modules: General ID Extraction Module, Dual-Level ID Injection Module, ID-Aware Decoupling Module.

<p align="center">
  <img src="https://github.com/kongkong12345/test_readme/blob/main/figure/ours-toy%20duck-chongfu-3.jpg?raw=true" height=450>
</p>

---

###  **General ID Dataset:**

To promot the research of the general object customization, we construct the first large-scale general ID dataset, named as Multi-Category ID-Consistent (MC-IDC) dataset. Our dataset consists of approximately 315,000 samples in total with more than 10,000 categories, covering various types such as human faces, animals, clothes, human-made tools, etc. Each sample consists of a reference image, a segmentation mask of the object of interest in the reference image, a target image, and a text caption of the target image. The reference image with its segmentation mask provides ID information, the text caption of the target image offers semantic-level guidance for generation, and the target image serves as the ground truth.

---

###  **Various Applications:**


---


###  **Comparisons with Previous Works:**



---


</div>

###  **Statement:**

Codes and dataset will be released soon!

# BibTeX
If you find PhotoMaker useful for your research and applications, please cite using this BibTeX:

```BibTeX
@inproceedings{li2023photomaker,
  title={PhotoMaker: Customizing Realistic Human Photos via Stacked ID Embedding},
  author={Li, Zhen and Cao, Mingdeng and Wang, Xintao and Qi, Zhongang and Cheng, Ming-Ming and Shan, Ying},
  booktitle={IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2024}
}
