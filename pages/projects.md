---
layout: page
title: "Projects & Experience"
permalink: /projects/
---

This page documents my research experience, technical projects, and organizational 
involvement. My work spans robotics, control systems, big data, and theoretical 
computer science.


---

## Research Experience and Projects

### Formation Control for Robotic Blimp Swarms

Under the direction of the CKSRI Director, I joined a research group led by doctoral 
students investigating control systems in robotic design. My contributions include:

- Researching frontier works in control theory and robotic design
- Deepening understanding of current robotics academia and industry landscape
- Co-authoring a published paper with graduate researchers on innovative control approaches
* Designed a **dynamic leader-switching algorithm** for a 3-blimp indoor swarm, 
  allowing any blimp to assume the leader role during sharp turns to distribute 
  maneuvering demands and maintain formation stability
* Implemented **monocular camera-based relative position estimation** combined with 
  a laser altimeter, eliminating the need for expensive external localization systems 
  such as OptiTrack
* Achieved **100% turn completion success rate** with leader-switching enabled, 
  compared to 33.3% without, with area RMSE reduced from 2.06–2.56 to 0.14–0.28

![](/Portfolio/assets/images/blimp.png)

---

### Information Theory & Theoretical Computer Science

Selected for a competitive faculty mentoring program conducting independent research 
under graduate student mentorship. Key contributions:

- Conducted an independent study on Information Theory and Shannon Entropy
- Analyzed theoretical limits of communication and data compression in distributed 
  computing environments
- Synthesized mathematical proofs and presented a comprehensive technical review on 
  the convergence of information theory and algorithmic complexity to the mathematics 
  department


<img src="https://m.media-amazon.com/images/I/51Fba-4k7lL.jpg" style="height: 300px;">
<img src="/Portfolio/assets/images/informatics.png" style="height: 300px;">
  

---
## Discovery Project
### Analytical Auto differentiation Application and Its Surroundings

Idea

-   Encountered automatic differentiation in ML coursework but found no textbook treated it with sufficient mathematical depth
-   Set out to understand AD completely from theory to implementation, and to answer why reverse-mode dominates modern ML

Progress

-   Built theoretical foundation from computational graphs and chain rule up
-   Implemented both forward-mode and reverse-mode AD within a single unified framework, with operator overloading to build the graph naturally
-   Used PyTorch tensors purely as a CUDA backend — all differentiation logic hand-written
-   Designed controlled experiments comparing both modes; verified full Jacobian correctness numerically
    ![](/Portfolio/assets/images/ad_comparison.png)
-   Visualized forward and backward propagation simultaneously on a [4→6→6→1] MLP
    ![](/Portfolio/assets/images/ad_mlp.gif)

Successes and Failures

-   Successfully reproduced a GPU-accelerated autograd engine with both modes, operator overloading, and unified graph structure
-   Finding physically meaningful benchmark cases that honestly demonstrated the computational trade-off required significant iteration — several candidates including Burgers equation and wave superposition had structural issues

ECE Skills Gained

-   Computational graph design · Jacobian-vector product derivation · Complexity analysis
-   GPU-aware programming
-   Controlled benchmark design · Numerical precision handling · Scientific visualisation · Engineering practicity analysis 

### Reproduction of Classical CNN Models: A Storyline from Image Classification to Object Detection
* Constructed a systematic framework that traces the architectural evolution of Computer Vision, analyzing the transition from classical convolutional stacking to residual learning paradigms to understand how deep networks overcome optimization hurdles.
* Implemented the ResNet-18 architecture from first principles using PyTorch, specifically engineering custom identity shortcuts and residual blocks to address the degradation problem and ensure efficient gradient flow across deep layers.
* Engineered a robust deep learning workflow incorporating sophisticated data augmentation (Torchvision), stochastic optimization, and regularization techniques to maximize model generalization and training stability across diverse image datasets.
* Conducted in-depth diagnostic analytics on training dynamics, leveraging mathematical rigor to interpret loss convergence and accuracy metrics, which informed precise hyperparameter tuning and validated the model’s reliability.
* Established a scalable evaluation framework designed to bridge the gap between image classification and high-level perception tasks, providing a foundation for transitioning toward high-precision object detection and localization architectures.

---

---



## Organization Involvement

### Developer's Club
**Founder & President** · Shenzhen, China · 2020–2023

Founded and led a club of 10+ programming enthusiasts focused on building technical 
projects bridging schoolwork and technology. Projects ranged from customizing and 
distributing AI systems to experimenting with computing system architectures.

---

### Oxford Chinese Student Association (OCSA)
**Editor, Technology & Media Department** · Emory University · 2023–2024

Responsible for content creation and editing for the sole major Chinese Student 
Association at Oxford College of Emory University. Worked to foster international 
connections and promote Chinese culture within the campus community.
