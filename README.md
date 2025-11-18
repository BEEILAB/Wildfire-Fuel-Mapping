# A Weakly Supervised Deep Learning Framework for 10 m Wildfire Fuel Mapping from Multi-source Remote Sensing Data
Accurate large-scale wildfire fuel mapping is essential for fire risk assessment and ecosystem management. However, existing methods are often constrained by the limited availability and high cost of high-resolution training data. This study introduces L2HFuelNet, a novel weakly supervised deep learning framework designed to generate 10 m resolution wildfire fuel maps from coarse 30 m supervisory labels. The proposed framework integrates multi-source remote sensing data, including Sentinel-2 multispectral imagery, Sentinel-1 SAR backscatter, and topographic variables. Its dualencoder architecture combines a Swin Transformer and an atrous spatial pyramid pooling (ASPP)-based convolutional encoder to jointly capture spectral, structural, and terrain features. A hybrid low-to-high (L2H) loss function, composed of cross-entropy, intersection-over-union (IoU), and confidence–vague distance (CVD) terms, mitigates uncertainty and label noise arising from resolution mismatches. The framework was applied to the entire of Alberta province, Canada, a large and heterogeneous region encompassing diverse fuel types. L2HFuelNet achieved an overall accuracy of 0.91, outperforming state-of-the-art baselines and showing substantial improvements for spectrally similar classes such as Mixedwood, Pine, and Aspen. Uncertainty analysis based on class disagreement further demonstrated robustness in fragmented and transitional landscapes. This work demonstrates the feasibility of high-resolution wildfire fuel mapping using only coarse supervisory data, offering a scalable and costeffective solution for fire management and ecological monitoring. The wildfire fuel map of Alberta is publicly available at https://drive.google.com/file/d/1pUbL4otj7svdgqNFlagK1RDtfHEcjlEt/view?usp=sharing.


![10mFuelMap](https://github.com/user-attachments/assets/3cc18996-8678-40ec-b471-e0f79f32e469)

## Citation
If you use this material in your research, please cite the following paper:

```bibtex
@article{paper,
  title={A Weakly Supervised Deep Learning Framework for 10 m Wildfire Fuel Mapping from Multi-source Remote Sensing Data},
  author={Name and Co-Authors},
  journal={Journal Name},
  year={2025},
  volume={X},
  pages={X-Y},
  doi={XX.XXXX/XXXXXX}
}
