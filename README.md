# Human-Activity-Recognition
Human activity recognition (HAR) can be described as the task of establishing connections between a series of specific human actions at a detailed level and corresponding data stored in a database. Human Activity Recognition (HAR) has evolved significantly over the past few decades. Initially rooted in simple sensor-based systems, the field has expanded to incorporate more complex methodologies, including machine learning algorithms and, more recently, neural networks. HAR has applications in a variety of domains, such as healthcare for patient monitoring, sports analytics, and smart home systems for energy efficiency and security. However,  the fundamental building blocks of intricate tasks can produce characteristics that exhibit temporal evolution   Consequently, the process of selecting features necessitates a meticulous balance between ensuring differentiability and fostering generalizability. Another problem is in real life, heavyweight traditional classifiers can create issues in hardware constraints, latency, scalability, or memory consumption issues during production. This problem can ultimately result in suboptimal deployment performance when employing conventional classifiers in contrast to light-weight classifiers. 

This project incorporates to use of neural network techniques for accuracy and also introduces lightweight classifiers to make deployment feasible. 

\begin{itemize}
    \item Balancing differentiability and generalizability in the feature selection process: In traditional machine
learning feature selection process can select features only based on training data which may lead to
overfitting. However, neural networks can enable feature selection in an end-to-end manner automatically. For example, the convolution layers can select special features while LSTM can extract the most appropriate ones. 

\item Introducing lightweight classifiers: In the real world, embedded systems, and IoT devices have tight hardware
constraints on memory, compute power, and energy consumption. To solve the issue, I would like to
implement a few lightweight classifiers by reducing model size, and latency maintaining efficiency with
traditional ML systems. Type-I and Type-II errors are analyzed to understand which models do well and perform poorly.

\end{itemize}
