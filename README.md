# DriViDOC
Driving from Vision through Differentiable Optimal Control

 This repository complements the main paper "Learning from Visual Demonstrations through Differentiable Nonlinear MPC for Personalized Autonomous Driving," submitted to IROS 2024, to enhance the transparency and reproducibility of the research presented.

## Paper abstract
Human-like autonomous driving controllers have the potential to enhance passenger perception of autonomous vehicles. This paper proposes DriViDOC: a model for Driving from Vision through Differentiable Optimal Control, and its application to learn personalized autonomous driving controllers from human demonstrations. 
DriViDOC combines the automatic inference of relevant features from camera frames with the properties of nonlinear model predictive control (NMPC), such as constraint satisfaction.
Our approach leverages the differentiability of parametric NMPC, allowing for end-to-end learning of the driving model from images to control. The model is trained on an offline dataset comprising various driving styles collected on a motion-base driving simulator. During online testing, the model demonstrates successful imitation of different driving styles, and the interpreted NMPC parameters provide insights into the achievement of specific driving behaviors. Our experimental results show that DriViDOC outperforms other methods involving NMPC and neural networks, exhibiting an average improvement of 20\% in imitation scores. 



## Authors:
- [Flavia Sofia Acerbo](mailto:flavia.acerbo@siemens.com) (Siemens Digital Industries Software, KU Leuven)
- Jan Swevers (KU Leuven)
- Tinne Tuytelaars (KU Leuven)
- Son Tong (Siemens Digital Industries Software)