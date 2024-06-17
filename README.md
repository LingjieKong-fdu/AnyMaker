<div align="center">
  
## AnyMaker: Zero-shot General Object Customization via Decoupled Dual-Level ID Injection 

</div>

<div align="left">




###  **Core Properties:**

<p align="center">
  <img src="https://github.com/kongkong12345/AnyMaker/blob/main/fig/advantage.png?raw=true" width="90%">
</p>

---

###  **Various Applications:**

The AnyMaker has desirable performance on diverse customization applications, such as realistic human customization, cartoon character customization, ID mixing, story generation, virtual try-on, etc.

<p align="center">
  <img src="https://github.com/kongkong12345/AnyMaker/blob/main/fig/diverse_applications.png?raw=true" width="90%">
</p>

<p align="center">
  <img src="https://github.com/kongkong12345/AnyMaker/blob/main/fig/idconsistent.png?raw=true" width="90%">
</p>

---


###  **Method Framework:**

AnyMaker consists of three crucial ID processing modules: General ID Extraction Module, Dual-Level ID Injection Module, ID-Aware Decoupling Module.

<p align="center">
  <img src="https://github.com/kongkong12345/AnyMaker/blob/main/fig/method.png?raw=true" width="90%">
</p>

---

###  **General ID Dataset:**

To promot the research of the general object customization, we construct the first large-scale general ID dataset, named as Multi-Category ID-Consistent (MC-IDC) dataset. Our dataset consists of approximately 315,000 samples in total with more than 10,000 categories, covering various types such as human faces, animals, clothes, human-made tools, etc. Each sample consists of a reference image, a segmentation mask of the object of interest in the reference image, a target image, and a text caption of the target image. The reference image with its segmentation mask provides ID information, the text caption of the target image offers semantic-level guidance for generation, and the target image serves as the ground truth.

<p align="center">
  <img src="https://github.com/kongkong12345/AnyMaker/blob/main/fig/dataset.png?raw=true" width="90%">
</p>

---




###  **Comparisons with Previous Works:**

The AnyMaker exhibits outstanding capabilities of high-quality customization for general objects, and even beat task-specialized methods in the specific domains, such as human customization and virtual try-on.

<p align="center">
  <img src="https://github.com/kongkong12345/AnyMaker/blob/main/fig/compare.png?raw=true" width="90%">
</p>



---


</div>

###  **Statement:**

Codes and dataset will be released soon!

# BibTeX
If you find AnyMaker useful for your research and applications, please cite using this BibTeX:

```BibTeX
xxx
