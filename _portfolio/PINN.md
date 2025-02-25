---
title: "Fast and Reliable Flow Reconstruction from Sparse Data with physics priori embedded Transformer"
excerpt: "Physics Reliable Flow Reconstruction<br/><img src='https://raw.githubusercontent.com/CHTiansweet/CHTian/master/images/PINN_physics.png'>"
collection: portfolio
---

Physics-Informed Neural Networks (PINNs) typically incorporate physics constraints by adding physical loss terms to the overall loss function. However, this approach requires the model to explore solutions within a highly complex state space, 
often leading to conflicts between the gradients of physical loss and pixel-level loss. These inconsistencies introduce instability in training and significantly increase computational costs.

To address these challenges, we are developing a transformer architecture that embeds prior physical rules directly into the model. Instead of relying on a physics loss function, our model first generates tool functions, 
which are then used to compute the flow field based on predefined physical principles. By shifting the burden of physics compliance from the optimization process to the model’s structural design, we ensure that the generated solutions inherently adhere to physical laws. 
This dramatically reduces the search space to only physically feasible states, improving both the efficiency and reliability of PINN training.
