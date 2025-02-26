# Awesome SecML Papers

A list of interesting papers linking *Machine Learning* (ML) and *Cybersecurity*. We list papers focusing on the security issues arising in ML models, as well as papers about ML application in security systems.


## Security of ML Models

### Adversarial Attacks

#### Attack Papers

- Croce et al. [**"Mind the Box: L1-APGD for Sparse Adversarial Attacks on Image Classifiers"**]() @ **ICML 2021**.

#### Defense Papers

- Muravev et al. [**"Certified Robustness via Randomized Smoothing over Multiplicative Parameters of Input Transformations"**](https://arxiv.org/pdf/2106.14432) @ **IJCAI 2022**.
- Shao et al. [**"On the Adversarial Robustness of Vision Transformers"**](https://arxiv.org/pdf/2103.15670) @ **TMLR 2022**.
- Cohen et al. [**"Certified Adversarial Robustness via Randomized Smoothing"**](https://proceedings.mlr.press/v97/cohen19c/cohen19c.pdf) @ **ICML 2019**.

#### Theory-driven Papers

- Zhang et al. [**"On the Duality Between Sharpness-Aware Minimization and Adversarial Training"**](https://arxiv.org/pdf/2402.15152) @ **ICML 2024**.
- Ilyas et al. [**"Adversarial Examples Are Not Bugs, They Are Features"**](https://proceedings.neurips.cc/paper/2019/file/e2c420d928d4bf8ce0ff2ec19b371514-Paper.pdf) @ **NeurIPS 2019**.
- Shafani et al. [**"Are adversarial examples inevitable?"**](https://arxiv.org/pdf/1809.02104) @ **ICLR 2019**.
- Zhang et al. [**"Theoretically Principled Trade-off between Robustness and Accuracy"**](https://proceedings.mlr.press/v97/zhang19p/zhang19p.pdf) @ **ICML 2019**.

### Backdoor Attacks

#### Attack Papers

- Zhu et al. [**"Breaking the False Sense of Security in Backdoor Defense through Re-Activation Attack"**](https://arxiv.org/pdf/2405.16134) @ **Arxiv 2024**
- Dong et al. [**"FDNet: Imperceptible backdoor attacks via frequency domain steganography and negative sampling"**](https://www.sciencedirect.com/science/article/pii/S0925231224003175) @ **Neurocomputing 2024**.
- Li et al. [**"3DFed: Adaptive and Extensible Framework for Covert Backdoor Attack in Federated Learning"**](https://www.sciencedirect.com/science/article/pii/S0925231224003175) @ **S&P 2023**.
- Xiang et al. [**"Reverse engineering imperceptible backdoor attacks on deep neural networks for detection and training set cleansing"**](https://www.sciencedirect.com/science/article/pii/S0167404821001048) @ **Computer & Security 2021**.
- Wang et al. [**"Attack of the Tails: Yes, You Really Can Backdoor Federated Learning"**](https://proceedings.neurips.cc/paper_files/paper/2020/file/b8ffa41d4e492f0fad2f13e29e1762eb-Paper.pdf) @ **NeurIPS 2020**.

#### Defense Papers

- Yang et al. [**"Distributed Backdoor Attacks on Federated Graph Learning and Certified Defenses"**](https://arxiv.org/abs/2407.08935) @ **CCS 2024**.
- Wang et al. [**"MM-BD: Post-Training Detection of Backdoor Attacks with Arbitrary Backdoor Pattern Types Using a Maximum Margin Statistic"**](https://www.computer.org/csdl/proceedings-article/sp/2024/313000a015/1RjE9SU7Kz6) @ **S&P 2024**.
- Ning et al. [**"Interpretation-Empowered Neural Cleanse for Backdoor Attacks"**](https://dl.acm.org/doi/pdf/10.1145/3589335.3651525) @ **WWW 2024**.
- Zhang et al. [**"Reliable Poisoned Sample Detection against Backdoor Attacks Enhanced by Sharpness Aware Minimization"**](https://arxiv.org/pdf/2411.11525?) @ **Arxiv 2024**.
- Zhu et al. [**"NeuralSanitizer: Detecting Backdoors in Neural Networks"**](https://ieeexplore.ieee.org/iel7/10206/4358835/10504286.pdf) @ **TIFS 2024**.
- Kumari et al. [**"BayBFed: Bayesian Backdoor Defense for Federated Learning"**](https://www.computer.org/csdl/proceedings-article/sp/2023/933600b747/1OXGYHynfQA) @ **S&P 2023**.
- Gao et al. [**"Backdoor Defense via Adaptively Splitting Poisoned Dataset"**](https://openaccess.thecvf.com/content/CVPR2023/papers/Gao_Backdoor_Defense_via_Adaptively_Splitting_Poisoned_Dataset_CVPR_2023_paper.pdf) @ **CVPR 2023**.
- Pang et al. [**"Backdoor Cleansing with Unlabeled Data"**](https://openaccess.thecvf.com/content/CVPR2023/papers/Pang_Backdoor_Cleansing_With_Unlabeled_Data_CVPR_2023_paper.pdf) @ **CVPR 2023**.
- Mu et al. [**"Progressive Backdoor Erasing via Connecting Backdoor and Adversarial Attacks"**](https://openaccess.thecvf.com/content/CVPR2023/html/Mu_Progressive_Backdoor_Erasing_via_Connecting_Backdoor_and_Adversarial_Attacks_CVPR_2023_paper.html) @ **CVPR 2023**.
- Zhu et al. [**"Enhancing Fine-Tuning based Backdoor Defense with Sharpness-Aware Minimization"**](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhu_Enhancing_Fine-Tuning_Based_Backdoor_Defense_with_Sharpness-Aware_Minimization_ICCV_2023_paper.pdf) @ **ICCV 2023**.
- Gao et al. [**"On the Effectiveness of Adversarial Training Against Backdoor Attacks"**](https://arxiv.org/abs/2202.10627) @ **TNNLS 2023**.
- Huang et al. [**"Backdoor Defense via Decoupling the Training Process"**](https://arxiv.org/pdf/2202.03423) @ **ICLR 2022**.
- Nguyen et al. [**"FLAME: Taming Backdoors in Federated Learning"**](https://www.usenix.net/system/files/sec22fall_nguyen.pdf) @ **USENIX Security 2022**.
- Shejwalkar et al. [**"Back to the Drawing Board: A Critical Evaluation of Poisoning Attacks on Production Federated Learning"**](https://www.computer.org/csdl/proceedings-article/sp/2022/131600b117/1FlQIrc96Ew) @ **S&P 2022**.
- Rieger et al. [**"DeepSight: Mitigating Backdoor Attacks in Federated Learning Through Deep Model Inspection"**](https://arxiv.org/pdf/2201.00763) @ **NDSS 2022**.
- Zheng et al. [**"Data-free Backdoor Removal based on Channel Lipschitzness"**](https://arxiv.org/pdf/2208.03111) @ **ECCV 2022**.
- Zhang et al. [**"FLDetector: Defending Federated Learning Against Model Poisoning Attacks via Detecting Malicious Clients"**](https://dl.acm.org/doi/abs/10.1145/3534678.3539231) @ **KDD 2022**.
- Zhao et al.  [**"FedInv: Byzantine-Robust Federated Learning by Inversing Local Model Updates"**](https://ojs.aaai.org/index.php/AAAI/article/view/20903) @ **AAAI 2022**.
- Li et al. [**"Anti-Backdoor Learning: Training Clean Models on Poisoned Data"**](https://proceedings.neurips.cc/paper/2021/file/7d38b1e9bd793d3f45e0e212a729a93c-Paper.pdf) @ **NeurIPS 2021**.
- Sun et al. [**"FL-WBC: Enhancing Robustness against Model Poisoning Attacks in Federated Learning from a Client Perspective"**](https://arxiv.org/abs/2110.13864) @ **NeurIPS 2021**.
- Xie et al. [**"CRFL: Certifiably Robust Federated Learning against Backdoor Attacks"**](http://proceedings.mlr.press/v139/xie21a/xie21a.pdf) @ **ICML 2021**.
- Zhu et al. [**"CLEAR: Clean-up Sample-Targeted Backdoor in Neural Networks"**](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhu_CLEAR_Clean-Up_Sample-Targeted_Backdoor_in_Neural_Networks_ICCV_2021_paper.pdf) @ **ICCV 2021**.
- Cao et al. [**"FLTrust: Byzantine-robust Federated Learning via Trust Bootstrapping"**](https://www.ndss-symposium.org/ndss-paper/fltrust-byzantine-robust-federated-learning-via-trust-bootstrapping/) @ **NDSS 2021**.
- Zhu et al. [**"GangSweep: Sweep out Neural Backdoors by GAN"**](https://dl.acm.org/doi/pdf/10.1145/3394171.3413546) @ **MM 2020**.
- Wang et al. [**"Neural Cleanse: Identifying and Mitigating Backdoor Attacks in Neural Networks"**](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8835365) @ **S&P 2019**.

#### Theory-driven Papers

- Li et al. [**"A Theoretical Analysis of Backdoor Poisoning Attacks in Convolutional Neural Networks"**](https://openreview.net/pdf?id=SfcB4cVvPz) @ **ICML 2024**.


### Membership Inference Attacks


## ML for Security Systems