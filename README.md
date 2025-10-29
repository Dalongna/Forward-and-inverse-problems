Forward and inverse problems in the characterization of self-healing process of asphalt mixture using air-coupled nonlinear ultrasonic technique

Long Lia*, Wentao Zhangb, Jiaxuan Lic

a State Key Laboratory of Green Building Materials, China Building Materials Academy, Guanzhuangdongli 1, Chaoyang District, Beijing 100024, China, Email: lilongbhu@buaa.edu.cn

b School of Transportation Science and Engineering, Beihang University, Xueyuan Road 37, Haidian District, Beijing 100191, China, Email: wentaozhang@buaa.edu.cn

c State Key Laboratory of Green Building Materials, China Building Materials Academy, Guanzhuangdongli 1, Chaoyang District, Beijing 100024, China, Email:
lijiaxuan1215@163.com

*Corresponding author

 
Abstract：

Characterizing the self-healing process of asphalt mixture using air-coupled nonlinear ultrasonic techniques faces two major challenges: (1) accurately predicting ultrasonic signals in response to material damage parameters (forward problem), and (2) determining critical mechanical parameters from a single nonlinear parameter (inverse problem). Traditional ultrasonic techniques, such as linear ultrasonic testing (LUT), lack the sensitivity to detect micro-damage, while nonlinear ultrasonic detection equipment is complex and inefficient for rapid pavement assessment. To address the forward problem, this paper proposes a deep learning framework that integrates Convolutional Autoencoder with Physics-Informed deep learning (CAE-PIDL). The CAE-PIDL model not only captures time-domain information in signals through convolutional layers but also incorporates the loss of frequency-domain physical information into the training process. This unique integration allows the model to achieve a significant reduction in frequency-domain loss, with a training loss that is approximately 8 times lower and a validation loss that is approximately 5 times lower than those of the traditional Mean Squared Error (CAE-MSE) model. This demonstrates superior generalization and robustness compared to traditional methods that focus solely on time-domain accuracy. For the inverse problem, For the inverse problem, a CAE-Multilevel Discrete Wavelet Decomposition (CAE-MDWT) model is developed to accurately determine multiple mechanical parameters from a single ultrasonic signal by leveraging both spatial and temporal information. The high prediction accuracy of CAE-MDWT is attributed to the crucial role of fundamental and harmonic signals in characterizing the self-healing process. The inclusion of these signals significantly enhances the ability of CAE-MDWT to provide precise and reliable assessments of the self-healing process. The study shows that the proposed deep learning framework significantly enhances the efficiency and accuracy of ultrasonic testing for asphalt mixture self-healing assessment.
