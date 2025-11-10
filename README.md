# Cosmic Ray rejection with attention augmented deep learning
For any queries, please contact at srinadhml99@gmail.com

This work has been accepted to the Elsevier Journal of Astronomy and Computing, 2022 https://www.sciencedirect.com/science/article/abs/pii/S2213133722000488. 

For more details on code and trained models, please visit our LFOVIA lab webpage here [[https://github.com/lfovia/Attention-Augmented-Cosmic-Ray-Detection-in-Astronomical-Images](https://github.com/lfovia/Attention-Augmented-Cosmic-Ray-Detection-in-Astronomical-Images/tree/main)](url).


## 🌐 Web App

We have developed an interactive **web application** to automatically identify and visualize large **cosmic ray (CR) hits** for close inspection.
The app provides:

* **Live CR mask visualization** over the input FITS images
* **Manual editing support** for refining the CR masks
* **Dynamic threshold tuning** for adapting to various observational datasets

<p align="center">
  <img src="AttentionUNet_webapp.png" alt="Attention U-Net Web App" width="80%">
  <br>
  <em>Figure: Interactive CR mask visualization interface of the Attention U-Net web application.</em>
</p>
  
This tool is handy for astronomers to fine-tune **detection thresholds** and **interactively inspect CR contamination patterns**.

🚀 **Upcoming Update:**
We are actively adding new features — the final version, featuring transformer-based CR segmentation and analysis, will be released soon!



## 📖 Citation

If you find this project useful in your research, please consider citing:

```bibtex
@article{bhavanam2022cosmic,
  title   = {Cosmic Ray rejection with attention augmented deep learning},
  author  = {Bhavanam, Srinadh Reddy and Channappayya, Sumohana S and Srijith, P. K. and Desai, Shantanu},
  journal = {Astronomy and Computing},
  volume  = {40},
  pages   = {100625},
  year    = {2022},
  publisher = {Elsevier}
}
