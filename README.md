# Structural Analysis with Graph Neural Networks (StructGNN)

## Abstract
Structural analysis is indispensable to understanding structural behavior subject to complex loading. In this study, we explore novel and rapid surrogates for structural analysis engines using machine-learning methods. Graph neural network (GNN) is chosen for its capacity to describe structural geometry and force transmission paths between structural elements and to model structural responses under external loadings. A Structural GNN (StructGNN) framework is proposed to embody the rigid slab constraints into the GNN model for predicting accurate behavior. After training the model with randomly generated steel structures with different numbers of stories, spans, and element lengths under random-valued lateral forces, StructGNN not only shows that the GNN model can achieve high engineering accuracy in predicting the distribution of forces and deformations, but also exhibits a high generalizability to taller, unseen structures. With high interpretability in its message passing mechanism and high-speed computation with GPU parallelism, GNN is a fast alternative to traditional structural analysis engines and has a high potential to solve more complex structural engineering problems.