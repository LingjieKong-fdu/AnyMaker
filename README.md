<div align="center">
  
## AnyMaker: Zero-shot General Object Customization via Decoupled Dual-Level ID Injection 

<p align="center">
  <img src="https://github.com/kongkong12345/AnyMaker/blob/main/fig/overview-new.png?raw=true" width="90%">
</p>

</div>

<div align="left">


###  **Core Properties:**

1. **General field:**  Applicable to general objects, including but not limited to: human face, clothes, tools, animal, ...
2. **Fast generation:** Achieve object customization within seconds, without any further fine-tuning.
3. **User friendly:** Just one single reference image and a text prompt can meet the customization requirement.
4. **Outstanding results:** Ensure high ID fidelity, flexible text editability and high quality.
5. **Various applications:** Diverse applications such as general object customization, virtual try-on, ID-mixing, ...

---


###  **Method Framework:**

AnyMaker consists of three crucial ID processing modules: General ID Extraction Module, Dual-Level ID Injection Module, ID-Aware Decoupling Module.

<p align="center">
  <img src="https://github.com/kongkong12345/AnyMaker/blob/main/fig/method1.png?raw=true" width="97%">
</p>

---




###  **Comparisons with Previous Works:**

The AnyMaker exhibits outstanding capabilities of high-quality customization for general objects, and even beat task-specialized methods in the specific domains, such as human customization and virtual try-on, in terms of ID fidelity and text editability.

<p align="center">
  <img src="https://github.com/kongkong12345/AnyMaker/blob/main/fig/compare.png?raw=true" width="80%">
</p>

---

###  **General ID Dataset:**

To promot the research of the general object customization, we construct the first large-scale general ID dataset, named as Multi-Category ID-Consistent (MC-IDC) dataset. Our dataset consists of approximately 315,000 samples in total with more than 10,000 categories, covering various types such as human faces, animals, clothes, human-made tools, etc. Each sample consists of a reference image, a segmentation mask of the object of interest in the reference image, a target image, and a text caption of the target image. The reference image with its segmentation mask provides ID information, the text caption of the target image offers semantic-level guidance for generation, and the target image serves as the ground truth.

<p align="center">
  <img src="https://github.com/kongkong12345/AnyMaker/blob/main/fig/dataset.png?raw=true" width="90%">
</p>





</div>

##  Statement

Codes and dataset will be released soon!

## BibTeX
If you find AnyMaker useful for your research and applications, please cite using this BibTeX:

```BibTeX
@misc{kong2024anymaker,
      title={AnyMaker: Zero-shot General Object Customization via Decoupled Dual-Level ID Injection}, 
      author={Lingjie Kong and Kai Wu and Xiaobin Hu and Wenhui Han and Jinlong Peng and Chengming Xu and Donghao Luo and Jiangning Zhang and Chengjie Wang and Yanwei Fu},
      year={2024},
      eprint={2406.11643},
      archivePrefix={arXiv},
      primaryClass={id='cs.CV' full_name='Computer Vision and Pattern Recognition' is_active=True alt_name=None in_archive='cs' is_general=False description='Covers image processing, computer vision, pattern recognition, and scene understanding. Roughly includes material in ACM Subject Classes I.2.10, I.4, and I.5.'}
}
