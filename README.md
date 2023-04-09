# Gender-Classification CNN Model

## Objective
The objective of this project is to develop a Convolutional Neural Network (CNN) model that achieves the highest accuracy in classifying images of males and females. We will explore various neural network architectures and experiment with different optimizers to select the one with the highest accuracy for predicting the testing data. Additionally, we will evaluate the performance of a transfer learning model, specifically the VGG16 architecture, on this task. By doing so, we aim to provide insights into the effectiveness of different neural network architectures for gender classification and offer a comparative analysis of the performance of our proposed CNN model and the transfer learning model.


As a visual representation of our data, we provide samples of five male images from our dataset, as shown in Figure 1.

![Sample male images from the dataset](<https://lh3.googleusercontent.com/rXcBUdqpHSutju9AaM5jqMpWwOWp6POHbysF0IpBHJG3k5tFqwOLyZ1GrDLyuTabdhtnw_c_fkdAhRRaFX5tiMhyii9t8hW9ayVC1YzkNy24hhAPwNzqyOAF_VmtEdHaZeS-sC23MlGolFl59G8ekRdxO2ZOHK9uMTDjIq_0X_IfhocPTQkOPKS3C7uOiiKqxanoGGpv45OdULYsgMPUvH-0D9nFj-OE6JSXe6th4gq9vTykyAAQh7Gge81JgveTN89g-Cm2u1kH_IG3XTropj32CvDNscd8v2BKHhVL_h61cGYu1Dops79JB_XG8slKtcOKDhbxc8UnTCwbLywmEG5HyCkCmF4dhdUU0J5YMpu-TmyCFFnNErYUJfXa_WHgYVIfoYLsbvinB-Vxdcim3BCOYexLyTleE0Zy8lTFRPJdrWwTc-Qq2JmhO8MD0sXtK_Rz7qMgq_pnv1UAO1ZSLM30ktfzEMvC7BDXyOhy9UZJPWTtRO1oDDgGm3HezjLMVZOq6FOOxLx9X7W920_EXW4MNcJO15q2TYXLPSSy64k3zQ8EniIbOPhzlNfcKZwnDrtLA3oRzh4xDcOa7A8xNRe_szGvUzhI5AnbAqEmpohdKPAsNjkAdZTWs15oz6LkbDNQK1ujE9NzXQmHOFOQLvWd3yK7KrRMh79nI3xAr9pJR5tFhpY7bI2Br0UByFAjejubyQ1G2XefdFQWnGea2TxemHKSqwuFXKp2MKSO5pHoxJCsnN_gW8pT2gIYq_wOTaQ-F_KO7Spfsfdh3r9mv5FprWw4TGxDkef6l3CN8Ro6RrtqSYHhtQKeD_AOE80hdxf3UH_q8f-ffxIcxepK0Lv25wA7K2nZdxWAptV6vx3rzm629qHdvFwPX_oHeJMJkRwyaPV92i4Epyy6hZcbQl7ucEDJtkHJUCepor7kZSFyWfRTYudqAPM6bqsYh9psQhC9n5fa3Es70kIdfA8=w859-h222-s-no?authuser=0>)


Similarly, we also provide samples of five female images from our dataset, as shown in Figure 2.

![Sample female images from the dataset](<https://drive.google.com/file/d/1PRNYzcCVVkF-t0I9QpnNHiP9f2Q8-R2A/view?usp=sharing
)




## Results
We achieved satisfactory accuracy using both Adam and RMSprop optimizers, with an accuracy above 90%. However, using the SGD optimizer resulted in lower accuracy compared to the other two. The RMSprop optimizer provided the best accuracy and maintained a good balance between training and validation accuracy.

Here is the evaluation curve of the CNN model with RMSprop optimizer, which shows good performance:
![Evaluation curves of the CNN model with RMSprop optimizer](<https://drive.google.com/file/d/13iysYXk9GR7gdOlaFEpXK3DydQ2XRUAE/view?usp=sharing>)


Although our model has good accuracy, it still fails to predict a specific condition in some cases. Therefore, we will explore deeper and more accurate models to improve our results.

So we evaluated our data using a transfer learning technique, specifically the widely used VGG16 model. The average training score is 85%, which was a slight improvement. However, this result indicates that our model performance is consistent since the training score and validation score are similar.

![Evaluation curves of the VGG16 model](>https://drive.google.com/file/d/1qBmXBRhGrMfm9nmUKaSFeHjXdKkPFixy/view?usp=sharing>)

As we tested our project on random photos to predict their gender, we can conclude that the model correctly identified their gender despite different facial expressions and the presence of glasses. 
We present below three photos that were correctly predicted as men 

<table>
  <tr>
    <td><img src="https://drive.google.com/file/d/1HQL-IA0RlbypVuhR4vRbyNZxrdpHZTwL/view?usp=sharing"></td>
    <td><img src="https://drive.google.com/file/d/1HctO5Lw-wIB_9mmKTyPXoJmRG8_5oT5J/view?usp=sharing"></td>
    <td><img src="https://drive.google.com/file/d/1-1agVdPf40FTxG0dfM8CLV9btAWdh5qv/view?usp=sharing"></td>
  </tr>
</table>


and three photos that were correctly predicted as women.
<table>
  <tr>
    <td><img src="https://drive.google.com/file/d/1r0gU3uVjXkp0owf38v3PuwjqfdA-yUZa/view?usp=sharing"></td>
    <td><img src="https://drive.google.com/file/d/1ojNCZ53Lp4sh8zWdfQvQq0Zsc0adkW4x/view?usp=sharing"></td>
    <td><img src="https://drive.google.com/file/d/1gh3viQ8X89L8dC97zqjBmKDTvNFpGMEn/view?usp=sharing"></td>
  </tr>
</table>

##Conclusion 
In conclusion, we have developed a Convolutional Neural Network model using various architectures and optimizers to classify male and female images. The best accuracy was achieved using the RMSprop optimizer. We also experimented with transfer learning using VGG16 and saw a slight improvement in performance. The model was able to accurately predict gender even with varying facial expressions and the presence of glasses. This project can be further improved by exploring additional techniques such as data augmentation and fine-tuning
