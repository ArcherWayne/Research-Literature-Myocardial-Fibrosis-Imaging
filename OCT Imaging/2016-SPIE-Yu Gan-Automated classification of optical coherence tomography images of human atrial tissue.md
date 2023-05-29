# Automated classification of optical coherence tomography images of human atrial tissue

## Yu Gan, David Tsay, Syed B. Amir, Charles C. Marboe, Christine P. Hendon

### Columbia University, Columbia NY Presbyterian Hospital, Columbia University Medical Center

该论文指出心肌纤维化的扩散会导致心脏硬度增加, 因此心肌纤维化是心血管疾病的重要表征. 
本文开发了一种基于区域的自动化方法来对 OCT 图像中人类心房样本中的组织成分进行分类,在没有关于组织结构的先验信息的情况下分割区域信息，随后在每个分割区域内提取特征。
作者的分类算法在识别脂肪、心肌、纤维化心肌(fibrotic myocardium)和胶原组织成分方面的平均准确度为 80.41%。

本文使用的是商业OCT Telesto I (Thorlabs GmbH, Germany)系统. 中心波长 1325 nm, 带宽为 150 nm. 轴向和横向分辨率分别为 6.5 和 15 μm. 成像范围4 mm × 4 mm × 2.51 mm. 
样本为15个离体人心脏. 

根据视场范围对样本进行组织病理学处理, 平行于 B 扫描方向对样品进行切片. 在福尔马林中固定约24小时, 然后置于乙醇 (20%) 中约 24 小时. 样品采用Masson Trichrome 染色. 对于 33.3% 的样本，每 2 毫米进行一次组织学检查，以确保组织学与 OCT 图像集之间的多重匹配.

