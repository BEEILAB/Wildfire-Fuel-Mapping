# L2HFuelNet: Weakly supervised large-scale wildfire fuel mapping from multi-source remote sensing data
Accurate large-scale wildfire fuel mapping is critical for assessing fire risk and supporting ecosystem management. However, conventional approaches remain limited by the dependence on high-resolution training labels, which are costly and scarce. To overcome this challenge, a novel deep learning framework, L2HFuelNet, is introduced to generate 10 m resolution fuel maps from coarse 30 m supervisory labels by leveraging multi-source remote sensing data. The framework integrates Sentinel-2 multispectral bands, Sentinel-1 SAR backscatter, and topographic variables within a dual-encoder backbone that combines a Swin Transformer and atrous spatial pyramid pooling (ASPP) to extract complementary spectral, structural, and terrain features. A hybrid low-to-high (L2H) loss function, composed of cross-entropy, IoU, and confidence–vague distance terms, is employed to mitigate uncertainty and label noise caused by resolution mismatch. The framework was implemented across Alberta, Canada, a heterogeneous region with diverse fuel classes. Results demonstrate superior performance compared with state-of-the-art baselines, achieving an overall accuracy of 0.91 and notable improvements in spectrally similar classes such as Mixedwood, Pine, and Aspen. Uncertainty analysis using class disagreement further confirmed robustness in fragmented and transitional landscapes. The wildfire fuel map of Alberta is publicly available at https://drive.google.com/file/d/1pUbL4otj7svdgqNFlagK1RDtfHEcjlEt/view?usp=sharing.


![10mFuelMap](https://github.com/user-attachments/assets/3cc18996-8678-40ec-b471-e0f79f32e469)

## Citation
If you use this material in your research, please cite the following paper:

```bibtex
@article{paper,
  title={L2HFuelNet: Weakly supervised large-scale wildfire fuel mapping from multi-source remote sensing data},
  author={Name and Co-Authors},
  journal={Journal Name},
  year={2025},
  volume={X},
  pages={X-Y},
  doi={XX.XXXX/XXXXXX}
}
