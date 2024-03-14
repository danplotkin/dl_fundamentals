# Fundamentals of Feed-Forward Neural Networks: A Practical Introduction to Deep Learning

>[1 - Introduction to Deep Learning](#scrollTo=nfUG0z1QuwI9)

>>[A. AL vs ML vs DL: Understanding the Paradigms](#scrollTo=j9oeQxnqw79A)

>>[B. Why Deep Learning is Dominating?](#scrollTo=9e32O0zJz-iP)

>[2 - Introduction to the Artifical Neural Network](#scrollTo=wwqIKKud4JaF)

>>[A. Basic Architecture of an FFN](#scrollTo=jTg2vFQ-4j3l)

>>[B. Weights and Biases](#scrollTo=GtPT6yho65z9)

>>[C. Activation Functions](#scrollTo=elf1MzfdK7T4)

>[4 - Training an FFN](#scrollTo=uJDevWcP5-8j)

>>[A. Weight Initialization](#scrollTo=QfUa-8ArWzPK)

>>[A. Forward Propagation](#scrollTo=DOl-zCT1FoJk)

>>>[I. Forward Pass Algorithm](#scrollTo=DrkTy_umZUIj)

>>>[II. Loss Calculation](#scrollTo=cEa9sk5eZakp)

>>[B. Backpropagation](#scrollTo=gd4XCyIHadqM)

>>>[I. Compute Gradients](#scrollTo=OSR3Bphyzy1g)

>>>[II. Gradient Descent](#scrollTo=VP6pO2EUOt75)

>>[C. Mini-Batch Processing](#scrollTo=3gz-6tVHc3sn)

>>[D. Epochs](#scrollTo=GEWA-19JoXDj)

>>[E. Minotoring Optimality](#scrollTo=Y46DZN8sIs6v)

>>[F. Full Training Loop](#scrollTo=oOfB1uUYod_-)

>[5 - Common Activation Functions](#scrollTo=f5ol9Gij4H08)

>>[A. Rectified Linear Unit (ReLU)](#scrollTo=qllGyzsE42hv)

>>>[I. Visualizing ReLU](#scrollTo=qVe_4RmY_n4P)

>>>[II. Dying ReLU Problem](#scrollTo=kCVP13o1_Z7p)

>>[B. Leaky ReLU](#scrollTo=MmEXxdo99tul)

>>>[I. Visualizing Leaky ReLU](#scrollTo=IgX_KKrxBbyb)

>>[C. Sigmoid](#scrollTo=68XDVc6Z7bTT)

>>[D. Hyperbolic Tangent (Tanh)](#scrollTo=3y5jdUuD9pkX)

>>>[I. Visualizing Tanh](#scrollTo=rwjzk8oIEMyT)

>>[E. Softmax](#scrollTo=Hm9MAGPKFDoR)

>>>[I. Visualizing Softmax](#scrollTo=zEPOBWeUGCau)

>[6 - Challenges in Neural Network Training](#scrollTo=qs65aBzKHKAO)

>>[A. Overfitting vs Underfitting](#scrollTo=T6dldQlsHxTq)

>>>[I. Overfitting](#scrollTo=0E3nj_o45rWO)

>>>>[a. L1/L2 Regularization](#scrollTo=f4-PzPGk6KVS)

>>>>[b. Dropout Layer](#scrollTo=DY6V56B2DUbO)

>>>>[c. Early Stopping](#scrollTo=1dXRwmvmG0HF)

>>>>[d. Use More Data](#scrollTo=El9SvTwtLMNK)

>>>[II. Underfitting](#scrollTo=2EiESIZVMAd-)

>>>>[a. Add Network Complexity](#scrollTo=fyFd857CMVjI)

>>[B. Vanishing and Exploding Gradients](#scrollTo=aGKmoQRMH1FR)

>>>[I. Gradient Clipping](#scrollTo=xLVZZtowL8vT)

>>>[II. Batch Normalization](#scrollTo=_MTvggvdOBxe)

>>>[III. Weight Initialization](#scrollTo=HAKArH9DRjgO)

>>>[IV. Use ReLU and Leaky ReLU](#scrollTo=yDDcCoBJZOPm)

>>[C. Computational Resources](#scrollTo=RQTTI8GOH-yI)

>>[D. Learning Rate Selection](#scrollTo=zyngRUs7IUJ3)

>>>>[I. Learning Rate Scheduler](#scrollTo=RkioXj1rc6Mn)



### About

In this notebook, we will talk about the difference between Deep Learning and Machine Learning, we will talk about the architecture of a Feed-Forward Network (FFN), the algorithms to train one, and some of the challenges in Deep Learning training.
