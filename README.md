# ADE_normalization_to_MedDRA
Connect extracted ADE term to MedDRA terms


# How to decode the ipynb file
1. First run the one time process. it will create some preprocessing models or information we do not need to generate again.

2. Keep all data provided in the shared task, in the same folder the notebook is

3. Some time I use my local laptop (6 GB basic NVIDIA GPU), SPARTAN (University provided high end GPU, A100, 80GB, however, we do not need that much) and colab (as sometime I need to avoid download all models to my local to save space). You can run entire code in a GPU which has 24 GB GPU (I tried it too with NVIDIA A40 \approx 24 GP GPU).

4. Please be careful about the file names, as I run in in three different machine, and I need to combine all output, so I have to use different names.

5. You can run the entire file sequentially, it will work fine. There are some redundant blocks, which was used during development. If you run those no issue, you can skip them too.

6. The final block is my rough work, I used that for development and checking. I am still keeping it, if you want to explore. But those may be irrelvant.

7. Have fun


# Citation
```
@inproceedings{naskar2025hybrid,
  title={A Hybrid System for Comprehensive and Consistent Automated MedDRA Coding of Adverse Drug Events},
  author={Naskar, Abir and Chen, Liuliu and Kang, Jemima and Conway, Mike},
  booktitle={Proceedings to the 2025 Australasian Language Technology Workshop (ALTA 2025), Sydney},
  year={2025}
}
```
