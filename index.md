---
title: Adversarially Based Virtual CT Workflow for Evaluation of AI Imaging
subtitle: The goal is to develop an FDA workflow evaluating, approving, and monitoring AI imaging software
layout: page
callouts: example_callouts
show_sidebar: true
---

## Abstract
<div style="text-align: justify">
The World Health Organization reported that cancer is the second leading cause of death globally and is responsible for 9.6 million deaths in 2018. Approximately 50% of all cancer patients receive radiation therapy (RT). Many of them have metal implants, which induce image artifacts in the treatment planning CT images and compromise or preclude treatment in an estimated 15% of all radiation therapy patients. Despite extensive CT metal artifact reduction (MAR) research it remains one of the long-standing challenges in the CT field, without a clinically satisfactory solution.
</div>

<div style="text-align: justify">
The overall goal of this project is to develop cutting-edge deep learning imaging methods and software solutions for commercial CT scanners to eliminate CT metal artifacts in general and improve RT in particular. We propose a three-pronged approach to systematically tackle this challenge in three specific aims: (1) adversarial learning techniques for estimation of sinogram missing data and metal traces; (2) constrained disentanglement (CODE) networks to remove CT image artifacts during image reconstruction, through post-processing, and in both data and image domains; and (3) systematic evaluation of our proposed CT MAR techniques and clinical translation into robust RT planning methods to maximize the RT treatment planning accuracy and thus improve patient outcomes. Our synergistic track records in CT MAR research, especially with deep imaging methods over the past three years, promises an unprecedented opportunity for a brand-new solution to CT MAR. For the first time we will integrate contemporary AI innovations in data preprocessing, image reconstruction, post-processing, observer studies and treatment planning synergistically in a unified data-driven framework, positioning this project uniquely to eliminate metal artifacts and their complications in radiation therapy.
</div>

<!--
![MeTAI ecosystem with four major healthcare applications.](./img/20230114193241.png#pic_center)
<div style="text-align: justify">
The above figure is the <b>MeTAI ecosystem with four major healthcare applications</b>. a, Virtual comparative scanning (to find the best imaging technology in a specific situation). b, Raw data sharing (to allow controlled open access to tomographic raw data). c, Augmented regulatory science (to extend virtual clinical trials in terms of scope and duration). d, ‘Metaversed’ medical intervention (to perform medical intervention aided by metaverse). In an exemplary implementation of the MeTAI ecosystem, before a patient undergoes a real CT scan, his/her scans are first simulated on various virtual machines to find the best imaging result (a). On the basis of this knowledge, a real scan is performed. Then, the metaverse images are transferred to the patient’s medical care team, and upon the patient’s agreement and under secure computation protocols, the images and tomographic raw data can be made available to researchers (b). All these real and simulated images and data as well as other medically relevant information can be integrated in the metaverse and utilized in augmented clinical trials (c). Finally, if it is clinically indicated, the patient will undergo a remote robotic surgery aided by the metaverse and followed up in the metaverse for rehabilitation (d). Each of the four applications is further described in the main text.
</div>
--!>

## Timeline
![Timeline.](./img/20230114213827.png#pic_center)

<!-- <table border="1">
<caption> Timeline keyed to each aim and associated sub-aims, where the shading differences indicate relative efforts.
    <tr>
        <td width=20px></td>
        <td width=300px style="text-align: center"><b>Aim/Task</b></td>
        <td colspan="4" style="text-align: center"><b>Year 1</b></td>
        <td colspan="4" style="text-align: center"><b>Year 2</b></td>
        <td colspan="4" style="text-align: center"><b>Year 3</b></td>
        <td colspan="4"><b>Year 4</b></td>
    <tr>
        <td ><b>1</b></td>
        <td><b>Diverse Patient Modeling</b></td>
        <td colspan="16"><b>Leader: Klaus Mueller</b></td>    
    <tr>
        <td>1.1</td>
        <td>Semantic Mask Generation</td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
    <tr>
        <td>1.2</td>
        <td>Realistic Image Synthesis</td>
        <td></td>
        <td></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
    <tr>
        <td>1.3</td>
        <td>Pathological Feature Simulation</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
    <tr>
        <td><b>2</b></td>
        <td><b>Virtual CT Scanning</b></td>
        <td colspan="16"><b>Leader: Xun Jia</b></td>
    <tr>
        <td>2.1</td>
        <td>Sinogram Synthesis</td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
    <tr>
        <td>2.2</td>
        <td>Adversarial Improvement</td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
    <tr>
        <td>2.3</td>
        <td>Adversarial Perturbation</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
    <tr>
        <td><b>3</b></td>
        <td><b>Deep CT Imaging</b></td>
        <td colspan="16"><b>Leader: Ge Wang</b></td>
    <tr>
        <td>3.1</td>
        <td>Deep CT Reconstruction</td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
    <tr>
        <td>3.2</td>
        <td>Deep Image Analysis</td>
        <td></td>
        <td></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
    <tr>
        <td>3.3</td>
        <td>Network Evolution</td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
    <tr>
        <td><b>4</b></td>
        <td><b>Virtual Workflow Validation</b></td>
        <td colspan="16"><b>Leader: Rongping Zeng</b></td>
    <tr>
        <td>4.1</td>
        <td>Framework Development</td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
    <tr>
        <td>4.2</td>
        <td>Task-based Assessment</td>
        <td></td>
        <td></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
    <tr>
        <td>4.3</td>
        <td>AI-specific Assessment</td>
        <td></td>
        <td></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
    <tr>
        <td><b>5</b></td>
        <td><b>ABC System Dissemination</b></td>
        <td colspan="16"><b>Leader: All MPIs</b></td>
    <tr>
        <td>5.1</td>
        <td>Website Integration</td>
        <td></td>
        <td></td>
        <td></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
    <tr>
        <td>5.2</td>
        <td>Tool Development</td>
        <td></td>
        <td></td>
        <td></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#FCE4D6"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
        <td style="background-color:#C65911"></td>
</table> -->

<!-- ## Publication
1. <div style="text-align: justify">Wu W, Hu D, Cong W, et al. Stabilizing deep tomographic reconstruction: Part A. Hybrid framework and experimental results. Patterns (N Y). 2022 Apr 6;3(5):100474. PMID: 35607623; PMCID: PMC9122961.</div>
2.	<div style="text-align: justify">Wu W, Hu D, Cong W, et al. Stabilizing deep tomographic reconstruction: Part B. Convergence analysis and adversarial attacks. Patterns (N Y). 2022 Apr 6;3(5):100475. PMID: 35607615; PMCID: PMC9122974.</div>
3.	<div style="text-align: justify">Niu, C, Li, M, Fan, F, Wu, W, Guo, X, Lyu, Q. and Wang, G. Suppression of correlated noise with similarity-based unsupervised deep learning. arXiv:2011.03384, 2022. Minor revision, IEEE Transactions on Medical Imaging.</div>
4.	<div style="text-align: justify">Niu C, Wang G. Unsupervised contrastive learning based transformer for lung nodule detection. Phys Med Biol. 2022 Oct 7;67(20). doi: 10.1088/1361-6560/ac92ba. PMID: 36113445.</div>
5.	<div style="text-align: justify">Niu C, Shan H, Wang G. SPICE: Semantic Pseudo-Labeling for Image Clustering. IEEE Trans Image Process. 2022 Nov 15;PP. doi: 10.1109/TIP.2022.3221290. Epub ahead of print. PMID: 36378790.</div>
6.	<div style="text-align: justify">Wang G, Badal A, Jia X, Maltz JS, Mueller K, Myers KJ, Niu C, Vannier MW, Yan PK, Yu Z, Zeng RP: Development of Metaverse for Intelligent Healthcare. Nature Machine Intelligence 4:922-929, https://doi.org/10.1038/s42256-022-00549-6, 2022.</div> -->
