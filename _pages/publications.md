---
layout: archive
title: "Publications"
permalink: /publications/
# permalink: /
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

__Gu, Yongbin__, and Lizhong Chen. "[CART: Cache Access Reordering Tree for Efficient Cache and Memory Accesses in GPUs.](https://gyb1325.github.io//files/2018_ICCD_CART.pdf)" 2018 IEEE 36th International Conference on Computer Design (ICCD). IEEE, 2018.    
* *Abstract*: Graphics processing units (GPUs) have been increasingly used to accelerate general purpose computing. Thousands of concurrently running threads in a GPU demand a highly efficient memory subsystem for data supply. A key factor that affects the memory subsystem is the order of memory accesses. While reordering memory accesses at L2 cache has large potential benefits to both cache and DRAM, little work has been conducted to exploit this. In this paper, we investigate the largely unexplored opportunity of L2 cache access reordering. We propose Cache Access Reordering Tree (CART), a novel architecture that can improve memory subsystem efficiency by actively reordering memory accesses at L2 cache to be cache-friendly and DRAM-friendly. Evaluation results using a wide range of benchmarks show that, the proposed CART is able to improve the average IPC of memory intensive benchmarks by 34.2% with only 1.7% area overhead.  

<!-- Citation:  
@inproceedings{gu2018cart,  
  title={CART: Cache Access Reordering Tree for Efficient Cache and Memory Accesses in GPUs},  
  author={Gu, Yongbin and Chen, Lizhong},  
  booktitle={2018 IEEE 36th International Conference on Computer Design (ICCD)},  
  year={2018}  
}   -->

Azizimazreah, Arash*, __Yongbin Gu__*, Xiang Gu, and Lizhong Chen. "[Tolerating Soft Errors in Deep Learning Accelerators with Reliable On-Chip Memory Designs.](https://gyb1325.github.io/files/2018_NAS_Reliable_Accelerators.pdf)" 2018 IEEE International Conference on Networking, Architecture and Storage (NAS). IEEE, 2018. (Contribute Equally)(**Best Paper Candidate**)  
* *Abstract*: Deep learning neural network (DNN) accelerators have been increasingly deployed in many fields recently, including safety-critical applications such as autonomous vehicles and unmanned aircrafts. Meanwhile, the vulnerability of DNN accelerators to soft errors (e.g., caused by high-energy particle strikes) rapidly increases as manufacturing technology continues to scale down. A failure in the operation of DNN accelerators may lead to catastrophic consequences. Among the existing reliability techniques that can be applied to DNN accelerators, fully-hardened SRAM cells are more attractive due to their low overhead in terms of area, power and delay. However, current fully-hardened SRAM cells can only tolerate soft errors produced by single-node-upsets (SNUs), and cannot fully resist the soft errors caused by multiple-node-upsets (MNUs). In this paper, a Zero-Biased MNU-Aware SRAM Cell (ZBMA) is proposed for DNN accelerators based on two observations: first, the data (feature maps, weights) in DNNs has a strong bias towards zero; second, data flipping from zero to one is more likely to cause a failure of DNN outputs. The proposed memory cell provides a robust immunity against node upsets, and reduces the leakage current dramatically when zero is stored in the cell. Evaluation results show that when the proposed memory cell is integrated in a DNN accelerator, the total static power of the accelerator is reduced by 2.6X and 1.79X compared with the one based on the conventional and on state-of-the-art full-hardened memory cells, respectively. In terms of reliability, the DNN accelerator based on the proposed memory cell can reduce 99.99% of false outputs caused by soft errors across different DNNs.  

<!-- Citation:  
@inproceedings{2018tolerating,  
  title={Tolerating Soft Errors in Deep Learning Accelerators with Reliable On-Chip Memory Designs},  
  author={Azizimazreah, Arash and Gu, Yongbin and Gu, Xiang and Chen, Lizhong},  
  booktitle={2018 IEEE International Conference on Networking, Architecture and Storage (NAS)},  
  year={2018}  
}   -->

Yang, Yongliang, **Yongbin Gu**, Shengxiang Ge, Zhanghong Tang, and Xianbo Qiu. "[Development of a quantifiable optical reader for lateral flow immunoassay.](https://gyb1325.github.io/files/2015_POC_Device.pdf)" 2015 8th International Conference on Biomedical Engineering and Informatics (BMEI). IEEE, 2015.  
* *Abstract*: An optimized optical reader was developed for quantitative fluorescence detection of lateral flow immunoassay in point-of-care test (POCT). Different from existing readers for qualitative test, the developed reader is able to perform quantitative test with a line-shaped excitation beam to obtain the distribution of fluorescence signal intensity along the lateral flow strip. To reduce system complexity, a custom Y-shaped optical fiber, instead of one set of optical lenses, was adopted to couple the excitation and emission channels. A high power Light Emitting Diode (LED) with a specific wavelength interfaced with one of the two split ends of the optical fiber for excitation, while a highly sensitive photodiode with the other split end for detection. A linear stage with high resolution, which was driven by a step motor, was incorporated to facilitate strip scanning. Considering the inhomogeneous nature of lateral flow immunoassay, an optimized global searching algorithm was developed to identify test and control peaks and their boundaries, which further improves reader's sensitivity and specificity. Finally, a calibration model was built into the reader to report the concentration of the test sample. As an example, quantitative CRP (C - reactive protein) test was performed on this reader achieving a reasonable clinical diagnostics range from 1 μg/mL to 200 μg/mL. With its machine reading function, simplicity and relatively low cost, the optical reader could play an important role in POCT.  

<!-- Citation:  
@inproceedings{yang2015development,  
  title={Development of a quantifiable optical reader for lateral flow immunoassay},  
  author={Yang, Yongliang and Gu, Yongbin and Ge, Shengxiang and Tang, Zhanghong and Qiu, Xianbo},  
  booktitle={2015 8th International Conference on Biomedical Engineering and Informatics (BMEI)},  
  year={2015}  
}   -->

__Gu, Yongbin__, Yongliang Yang, Jing Zhang, ShengXiang Ge, Zhanghong Tang, and Xianbo Qiu. "[Point-of-care test for C-reactive protein by a fluorescence-based lateral flow immunoassay.](https://gyb1325.github.io/files/2014_POC_Device.pdf)" Instrumentation Science & Technology 42.6 (2014): 635-645.  
* *Abstract*:An innovative, portable fluorescence reader was developed for the determination of C-reactive protein based on a lateral flow immunoassay. The C-reactive protein concentration was proportional to the intensity of the test line which was calibrated relative to the control line. To quantify the fluorescence intensity of the lateral flow strip, a custom illumination module, which concentrated the excitation beam from an ultraviolet light-emitting diode, was developed for strip scanning. Accordingly, a high sensitive photodiode with a preamplifier was chosen as the detector for fluorescence. For good repeatability, the strip scanning resolution was set to 5 μm between data points by controlling a linear stage actuated by a stepper motor. Four double-logistic calibration models were compared. The sensitivity for C-reactive protein was 0.1 mg/L and the linear dynamic range extended to 400 mg/L. The optical reader provides a new and simple approach for the determination of C-reactive protein and may be modified for other similar biomarkers.    

<!-- Citation:  
@article{gu2014point,  
  title={Point-of-care test for C-reactive protein by a fluorescence-based lateral flow immunoassay},  
  author={Gu, Yongbin and Yang, Yongliang and Zhang, Jing and Ge,   ShengXiang and Tang, Zhanghong and Qiu, Xianbo},  
  journal={Instrumentation Science \& Technology},  
  pages={635--645},  
  year={2014}  
}   -->