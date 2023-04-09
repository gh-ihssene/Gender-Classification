# Gender-Classification CNN Model

## Objective
The objective of this project is to develop a Convolutional Neural Network (CNN) model that achieves the highest accuracy in classifying images of males and females. We will explore various neural network architectures and experiment with different optimizers to select the one with the highest accuracy for predicting the testing data. Additionally, we will evaluate the performance of a transfer learning model, specifically the VGG16 architecture, on this task. By doing so, we aim to provide insights into the effectiveness of different neural network architectures for gender classification and offer a comparative analysis of the performance of our proposed CNN model and the transfer learning model.


As a visual representation of our data, we provide samples of five male images from our dataset, as shown in Figure 1.

![Sample male images from the dataset](<https://lh3.googleusercontent.com/rXcBUdqpHSutju9AaM5jqMpWwOWp6POHbysF0IpBHJG3k5tFqwOLyZ1GrDLyuTabdhtnw_c_fkdAhRRaFX5tiMhyii9t8hW9ayVC1YzkNy24hhAPwNzqyOAF_VmtEdHaZeS-sC23MlGolFl59G8ekRdxO2ZOHK9uMTDjIq_0X_IfhocPTQkOPKS3C7uOiiKqxanoGGpv45OdULYsgMPUvH-0D9nFj-OE6JSXe6th4gq9vTykyAAQh7Gge81JgveTN89g-Cm2u1kH_IG3XTropj32CvDNscd8v2BKHhVL_h61cGYu1Dops79JB_XG8slKtcOKDhbxc8UnTCwbLywmEG5HyCkCmF4dhdUU0J5YMpu-TmyCFFnNErYUJfXa_WHgYVIfoYLsbvinB-Vxdcim3BCOYexLyTleE0Zy8lTFRPJdrWwTc-Qq2JmhO8MD0sXtK_Rz7qMgq_pnv1UAO1ZSLM30ktfzEMvC7BDXyOhy9UZJPWTtRO1oDDgGm3HezjLMVZOq6FOOxLx9X7W920_EXW4MNcJO15q2TYXLPSSy64k3zQ8EniIbOPhzlNfcKZwnDrtLA3oRzh4xDcOa7A8xNRe_szGvUzhI5AnbAqEmpohdKPAsNjkAdZTWs15oz6LkbDNQK1ujE9NzXQmHOFOQLvWd3yK7KrRMh79nI3xAr9pJR5tFhpY7bI2Br0UByFAjejubyQ1G2XefdFQWnGea2TxemHKSqwuFXKp2MKSO5pHoxJCsnN_gW8pT2gIYq_wOTaQ-F_KO7Spfsfdh3r9mv5FprWw4TGxDkef6l3CN8Ro6RrtqSYHhtQKeD_AOE80hdxf3UH_q8f-ffxIcxepK0Lv25wA7K2nZdxWAptV6vx3rzm629qHdvFwPX_oHeJMJkRwyaPV92i4Epyy6hZcbQl7ucEDJtkHJUCepor7kZSFyWfRTYudqAPM6bqsYh9psQhC9n5fa3Es70kIdfA8=w859-h222-s-no?authuser=0>)


Similarly, we also provide samples of five female images from our dataset, as shown in Figure 2.

![Sample female images from the dataset](<https://lh3.googleusercontent.com/Who5UoOx4skSs874RbL_upbTDjl78YzlbrtQzgXYTox6srXtAYB4HkoSJcLQSPj8C__2aLT15boVJTv8a165szrXo3uXluLUGGNv3VMYeFPAE4aYd35GeRkHViI01L7M7FnjO208CV2-6crF5m_6QJPj2iEydjBQ271ZamdtXcn70BWs0BilEYnFLxX28eiMPOjTIy9m9tzD7ea8E3baczczx65CAYBmbdYG2pgTPmu9WLcvY6X06FJNXDp2mYRZeNU7Xy1CufN2o1CXBqc0IrUp7iD2RUNL9GuA52BC61DZCN6c2FtR6jswKSa1HgPhHA2PlkIsmHSHSekn_kID65tP7wJ5X8hYOUE1PcN3DyXlB7UJQ4GIeK7-rKuyizQxZsaeJPZ8TswpA5pKPmEqP53dlPNZGk4a2i8NmaHKtth8zW4D-Y7yucS04uqKpNQ2vwsfVqiTV-H1sKJYYAoUWdCsBRi66PrBkndCu0gaDZ5ngAfZoQll70z0yLSlk-jKIrMz7FhL9rnwqdgsu7OmGuddvuGoOFgkpqGzoQ5zBSP_xP7yo1aR30u_LAxSx68UESZHXpCVuJ_VLfS5k2Pakl0Qtw4uAZrL_aBkYxduCfdVNusUc1Lo-amAXfnhntBWEksnC3wTnng_HuDX4Rec_I-pTmrdcH2f_wIhRXWE1NnQJXCKgbaKxtbAxRsRoUKElsOur9wWxU07g1t3LAZV7D7Cxziuq1JGkN_BjtL_BjEAF4_fbBTx70WyQVhce8qIypFWd1JMpDDxdTpDmVJPY7gOeGVHRBDcjzcf-5rKarnBlnrdP6kO7vDgQm1qlQt5JaNSGaOAqLFUNB5hLN8-eAgn4GbiHl8PYb9Tpxj6WaKfeMXteaMPaVkTRFCRXFn2zPSR8T_5EmA_v8pNVYpAQcO4EHoQlF9H449aRJu6Ps9cASL9BGolATeUKCifIfITlBm9aWuTJIcvSR85qPg=w853-h197-s-no?authuser=0>)




## Results
We achieved satisfactory accuracy using both Adam and RMSprop optimizers, with an accuracy above 90%. However, using the SGD optimizer resulted in lower accuracy compared to the other two. The RMSprop optimizer provided the best accuracy and maintained a good balance between training and validation accuracy.

Here is the evaluation curve of the CNN model with RMSprop optimizer, which shows good performance:
![Evaluation curves of the CNN model with RMSprop optimizer](<https://lh3.googleusercontent.com/pYfICR7XDxwNlX7e6YUF85VvHVb172WsNs9uM3-PEnUTLwZ1whQLqjRAzNTMeywYHE0VoY-blOGWiQnW_NlILGgJKTTAQHKjQyX1I9s0tlbJ-lng1pDCPGLAsMIPhkbTQ4YDnDkFXg2sOUR25isiLaJzWNJrtwnkECoLaXxrB19b_3fo0E38c0-CzM66pEnZ7grSb-0tfXhboXbt2vhU8yAUUPeBsMUT2LU2laLv9saCHXOoHcVaQAlmplePnWBb_s9yX4mF3mer6emphI2Da79NBN9TVpdaLG0O-B67pcwDTcekIWAXzCKZzdkFC_2VQxqVdF7eGjavUwpRqqPIf_OoNzQUCOTCywhYTdoi3QuuGPccTX2OLASpGMLz9ICdSFd_OSE_R0rcy2hh0072BqkvzIOmdlYJ5NUH4Rc0r-adHf_n-NdYbs7EpV9890riwYPqY7EIAT3TSmx8zLxCUa2nZ3jCLRxLMqETpCim2Z5JObCCSpUPec5MIbfR5I9NpMfMHAl9u5WGR8Pv9jfESYGtK_R8cJEtja5zYFEPJBbb6JN7cEK5oIOEb_oG-GW4GvZJSLvS2rKgNQcU4BNWp5_etkrJem9xtRAza9cNmmK-4dxJxW1iOJHyp_WEveByaCBqUmJ05ds7N_n66g19P1obFGcv23ta2AD8TpTuiC9SL6BgAJSVUQ80jaY2SahjnWPH7XT2M9yrfC9659BrMLzLHjXso7DJIONNPyVozbA9C4aC0VOMnXZtEN6SFyU-NCmm4rXVOiDNRdYRfQsEqo6sDoaJL0oxpZAkzkVA1rbKGR_EiUM_GlcwNMMZAXYLWh5XjhLG3vHnslof8_vwV80uOW4MlEB4ug-NciVpOu-7htRUjb1kTkTaJOIG85NXu8gGqSF8QRqexkstp-3bqNRrTURVnsN4aEFjP_xvCyV8JsgXWmfdR4aQQBbem73NaHYPi5YD9Eo9CPScQvM=w1178-h321-s-no?authuser=0>)


Although our model has good accuracy, it still fails to predict a specific condition in some cases. Therefore, we will explore deeper and more accurate models to improve our results.

So we evaluated our data using a transfer learning technique, specifically the widely used VGG16 model. The average training score is 85%, which was a slight improvement. However, this result indicates that our model performance is consistent since the training score and validation score are similar.

![Evaluation curves of the VGG16 model](<https://lh3.googleusercontent.com/IVKk3fXxCjsny7dYbHHmm_xe3Zz-iSQyj4uj-zrZkeB4YoOGkclNXLDtchVfVeeLKEbLeKxQPusbvZLjewOGM1PgfOVDrYiyPGmPIecjw9UpOYXyMOqusM28we9Bz2iVsGo0skk3c0IEsLnoj84j02aMR2d7hTWMxtC4CaOZH9b-EUVQeSW4pN3dm68ZSA-DR5sugbljWtoGRHexm2igBIcpIPW_T52dA_3R_C09veNorANLZosoxlKNHTDHgz78L4xF1thU_d1QM3SKsO9dlehr8kcJ9BLdSDpYRAI5XgZdUng_XYB67DGE_XvgZAyq37wo5pLOrCmpcaMzPGJm_4FfPst66TzHkFLo0p5nVuShemaNP4_E7KYJK65ZDzKsp6z_LyejxQKnzQGIutmYTmX5oJL5v0z8XknZe3bMtBNalQYnI2gQozInAaNUluV68W05Nz_rYoEotXdK9PJfPs2yck1KLx1cnhGqd_V-XkaGUfadQJyAWUXwya_c3Y6Rulc9SXvDFHNtgRoedmifNs9rZlROlJw2LgcOoEMBYeaqwjHCdcbv_QkDLf0d86NGBEIL2m17rlUpUOiJgxUH6NCafzHgSEsCd-cprnr86EN6ywoYKhZXewXe-Zp0vpnjyt-XCCTDXw3W_BwA5FtKQ23ZWpDKkOXtzO98nLPaI6N_AlVz41ylDLiOiju9_GJiS9WoIAvupvfAXilJcVt0kVrQTRb1dzMsroBPWqaLmqVlWxcDGonsDFdm9Cb9Pmnevqhvhr8iopAFL676w39IEFt8kZFYEtvWHpfQPPhLii_DEwpbtstm5Qnu9V3dxtZk5DRRKv6Nv8Il7-D13jRJQEiuvQAZKvrXrUOnU2-lV6l9TJul3SJVXyiWIyhOQA-pAfKyNPlEr2tWXtDjJOOBoT-T1Nioqobq9PweFBwkcptkrVK5jGYXV9dBm1P6Bl4cyGPMLIqExzbeotUbgLs=w1170-h333-s-no?authuser=0>)

As we tested our project on random photos to predict their gender, we can conclude that the model correctly identified their gender despite different facial expressions and the presence of glasses. 
We present below three photos that were correctly predicted as men 

<table>
  <tr>
    <td><img src="[https://drive.google.com/file/d/1HQL-IA0RlbypVuhR4vRbyNZxrdpHZTwL/view?usp=sharing](https://lh3.googleusercontent.com/PZAQToXBAaDUfs7h8mwTv8Q47IFJhHCWp42qHsjvVpWaCDQaPx99JxG8fHduo_IA_8kBv_cLpUHosTGkrLcOSpzmumWwUIbMGN-WRIx36A9ZH2hFPMCbjs0SYxNEvMeduCaHrApLJzoSn4XRddflTdYaEW94fmIwjiPmt4--QYJiF4egjuQY6AoLDOTDoS0qZdCAKQSXrsgtZ1eEVEvIO2MeZxc7mt8Epko7-5yUWmqBrGgt-h2wdgkBBVw59QlT9OahINMM16tJmcIaw8cM__5bJkGYynv_cJlvHx_TYkvdwbaqo4yEKC9r2pPRLqMSKMaRr7Q8QsWm7Z5IeztVarsVUssAdZGzs0EbP4e55_5ZApnWGUVNsdGfGHLqQCMxCZzcJC7CWPg8fJbQ3S2og89VreIwb_LGGLw10tjkufqjLwCLlCyr7sr76UGmoIjN4k15kIXzkGI_f8y7qzixHbwPGXNniipqbx0qx_qjpTNCbubp28bNzkVdaXQa0YpzYQ7uGUJvwWnZkxag0eXb5rmSpwcrUJRHHm4M68nhemioxgEPNQ-GFKdNoW5zNmCyPpMwgVf0zX2xa_DmPvhdqsELL2RA2S_xewTNhDbAW1S3DvdqKh6qdvHGpXPi2rbdFlTTHVwc-dkT6_-5WTCbhfQ0yOZrdcYY1LPdQzIkhG49ytdED6UAFRBwPX1KfwxUiwMteTZNa27Y9vxOZYec6S2gVcEm6Raj26LYr5NfkzX43YI1fclgvfh7YlvMAs0L6NtRmJiSLt6EHsnqBFtqI92_rUrNYvSPp5_vEjY6auGvDyTVKme_MaYrdPIEUjajjCCfirXJ0UO4kQzAIbXpRLQ0WMoJZGJW8P6cdxjYIOXAyJEmkDbMz-QX_Xijo0Si7CpiROfwCG3Fdk4Tor3ArrMP6Jwxsr2oOvMJNBBEu44Bv_I6pbJ8PRKDFobfJnV0MSUaiUeY8QS7ryo58yw=w250-h252-s-no?authuser=0)"></td>
    <td><img src="[https://drive.google.com/file/d/1HctO5Lw-wIB_9mmKTyPXoJmRG8_5oT5J/view?usp=sharing](https://lh3.googleusercontent.com/fPhdCDYV4O6ydvwb8NlwzYprwZ3FvN1DhTyaa6787DMJZmeN4javymjzapCEapvcfXLQn9wsgmsVKlhTCkt9fs_gtS8uTwohTNH0AdhD3Mmuskwj1ukzHc7T7_QEJsGuxriT0xkLba8dj4YI09HhXMLpcYnVBWj2QI-6DwG3bqGI0v8XQIwPryBekpm-JhKiDF8IccTpyjYBuDImLUTAQyNdmXypEWXZL3iFpjV34lBLY3CU3tHXQde_ypb8UPJFKzEkXaxvoF2G4Wnbl7E8f3aFD5qGvox1jbsoerGVxgVYO4liBY6wo0i5d8sgW5jSUnb_1ARIN-iRg8AceIEG9oFsgPwxiXjPhiDF2bAH3YwOmYCP1paCfSUUr-01Lg_ecGRS7puSBB5Joga8eatsQsFaHVwSDwLJO8QCd_9JftqID-uJu3xrWwVC0Bq1XozKJik51xhmbGSOCtvRCmQtpy2g20jJWpyv-BQrf8YX9B9Pf0HX1apKMFm8P_wndM1SQlz24nf5olh6G9TpaKFHAY8fqkB5MEx-LIX7k87rWSvPyFGvT2BHHZZCsurYHutMxtT0FKO4ex3GE_IUftRForScHyX5sVBDDVc21IFfwuzj5FpcdIfamB8mT5QyVJdM8-ndfHi7My9lR16iDiE0USALmpXOOx3pUbYXkOfvfHvxtSk7rnwbrwx9O7Cfx1MkyYl5S7HN0YQ-Pux8BazHOc-N1nvEiDQolTu_PTYpiaqNMZ07hzjWG6QvU3QCW3cnFwmEEnsv4H3rpQjrCKNtnANRP6X7nXHBPJJCKpMPAhmCgvqPRhwYqplhXnfxFnjD98rdEeqabyD3lLL1FSUXSFs5ocW3wo9ld-awmVYj1LiVeQhTJ3gHcNqrNwMYpC2oJ37mWPWURxRAScoxdVU1Vp0fGOK2wxTNFrmU03llfNyS_oFycUfyEv-6Y91gaoRlZ7dIDayCHy8xgjMnNbo=w253-h249-s-no?authuser=0)"></td>
    <td><img src="[https://drive.google.com/file/d/1-1agVdPf40FTxG0dfM8CLV9btAWdh5qv/view?usp=sharing](https://lh3.googleusercontent.com/aV_wizcHYMG7oBMIv2DZaBXCebdFBZdmfQ0HtPjEMSjbe_wQndvQMNglk9_PaImZ4eG_lw0gQRK9Rku1XdrNBORxPfLSFimfEIiNbFmCbjGay72ZpBsGLhzPKyziqs1PpgDiSYNAw2FMkfNmsD_kmTuJbAd_ymKB6Fs8fvIwQRyu8fwVytvhwzELkGHUHFxxw131MszN2KRuob_cF79geYr2z7A4tMhqu7TwZaDu1DmB-Lq-f_ECgyorgPE7YKWkXSEh3FjcW64RV7vnI_v_JZeOhZdX_kgWHrqIBSrqmFh4VniAYe-LjGiyRPUggVQHTweVng-HjIPq80LFxALZCEqSh7UB8zLuA4G0r1JB6m_CPsQLYx3NH5OgkFx7fBhLz5UtahfnuoIO2vDcO8WSOFPAQVQpsq8Ojv43WCCMBGcsZwZ2auO0U_elWZgGEcVE_4WmDxVnUmyzL5kThV9htOhUfrLDQcYFcZoRsX_I5CpDFOv6K6s_uAF75mpDZ6srzK6nF_y7krg78SGEfmtV9DR9RBL5d2hYXFYJNZfifO54RHRI4j21h8BBctaN5X0x88ThoX5x4ftoIXD27fXAngK_fgENTaE0EUWaq6rq3kIa99unJeHEoEKNA4cMu_xgLlTKeSC1SUGQUM8Fy5EU14-2uo9FWCNEV4q_2DATHTk0_MfuZethgHP0YWrScQ_P2IuN3pqkmcCmPU9WGflkUDM0Q80PU62LsagE658lSz4CRSg6mVxLWS1XNlYeHfclJe0pG4yv5_8SwrhmYTcmJPPQaUtKBue6uOlMoNQjzBPGDCj2YoKhlPOS1lTnd4kRHpnBpP8QVXV7e3gQep8I3tTPa_JobcHhJh15gmEHAK7sn0CeQRiX6F8VQycqrfaKOJCEuv1UJjDCXx_mkDipJMMGoJr51z9G47w5apdDX3TvPbcmZo0pwyQgwEgdT1pvJkk41cMn27OHRYNCDl4=w254-h252-s-no?authuser=0)"></td>
  </tr>
</table>


and three photos that were correctly predicted as women.
<table>
  <tr>
    <td><img src="[https://drive.google.com/file/d/1r0gU3uVjXkp0owf38v3PuwjqfdA-yUZa/view?usp=sharing](https://lh3.googleusercontent.com/7hFBczdt_c8KtKvPVKkjcs8KHOjLjOc_WiqvQdm3luT5ziYqJW18u_8lNETj7RVgamovFdu-pkOIiUpdbxgLsK8AyrBkOvDvfQRT6a-kFjCd-uOMCRwkriJMnFjRcxPOwSeGsKGMThkYO6AmcsyBoqQDvAYvVHp3SjBRKGGckgvWzrMAdkeO4mzrxX4QeDyBgp3XycIKBFCoozDxZpfAs9oPjRaALlPNW1xEcF_AYmQvwKXn_g4E1Dodx8_83zHYWM43_0q2OZl5ipcO7i5hmB5OXz-z28FELprC_AxbAwlqMXRjj6DXzA3sFpNKA4A2T3INuqOT6w8ZHI_GW7-MN6tCH_L_RFpOJdalnlyQNH5Onr5s0ftRJ97YEoWllmt3mjtf4hsLdtATXemOUPF0maPubq_KQ01d0pQON-1nLXBF48Tkw1pJQs18XAIw1ZqXCK-lIcqJU-jCox5aZLnOHSL4a51i6gcIrdfInimJDwiVeXlh3BESg0d7jygsPeMm9IC4qA5twRsEJzbuUjYmPmeGQyU-beBDRvaKoeCDdSe-Kw9_M_Ejceg8UbjBRVv3DCgCVhAoEmlcbBnqQ6Dh5HK0d8SMLBN6SURLxYymZmbLB0xZpdyD8aPhs_3pNHJlDgFprsyFd8CMAEa_xxI-6Bp75u8OMFCFh9N9qLOdtjlmFguV_TGe-izfp0DmYXzAtdDcWxc0cERgDQsWSBaiJA_4dn7xoQGF6Qg8EX70iY3IT80_poDO9QNgAxyk5DYFFr4oqroAD1YT-b2PWuCxTnQwkgi1VYyYlrbWK9oDb873NJ_q6ccR5JkVsm2fS5oUFPZCR1aLhZjsgzdqqXRgmKJOmdO1xAsVmoDD2edlzExKpTGnu6z44F1hVFNKNlKaj7p5dg8YdwIH7bEXi04KFyMZPomDrXSC4ZrjaIBfMFEGkmR30NJJWMqH_wJNP5WNV3Gn1P1PF3Ay7JE3o7I=w256-h252-s-no?authuser=0)"></td>
    <td><img src="[https://drive.google.com/file/d/1ojNCZ53Lp4sh8zWdfQvQq0Zsc0adkW4x/view?usp=sharing](https://lh3.googleusercontent.com/GO_IB6kI7DXzTCTIz-pUQfSPDDAr3jUsKbWzm1WIPOqpSuvxqId8cWGfIkqOvGTMaGsmUreTdTNIz4KwJ7N9tQ5K670rDP-ddshwederCN1SjxuYWvuLKqlzYU-7qiBM_EfmTqnPG0fAGIvnz5_lHC2uLcI4itLUg4g140DE-eU9GtxetBGLdRvIxx7tQ62xO97sPJLba6fekSuWqxFQWXAYs4_TjHzX83jSvHi4mP7m_SRbzofBWvz9OPwCCKfaKlSkF9bkQqxqC4Val_xJl3kfauv1UmRyWI3zllDRGaiRUaXuFtvTfGQD4EkTdJpFlfHs0tBGZ8r1U5C7F8N1MHUya_qGLjnYohai8jjcDLWDa6qXchbY6X6dWxQ9kBR7yrZPAOH2vloTznBtiZN6_eYjufGWSF0sHgXGYwaqYpZCioonckaBIRHs2lsv7SB_iaPqCSL3pjwh72NB_o2bCZqSt1OdFUP27LWos5IQQLe174ST7LftYOtHMy8aFLmcgae80WuH0PTLEM4wVM61E2fq8I--Vb60XuX7juoi8YpK1U5Z7fcRN7N2FFyFU2S0mp7om1eFYVHeoBMNRn0eDLOpstortJHYsZdoFQWJr6aTS7VPIPbZlMa3HucyuOPrZTU-_-demPNDMeMBQA6LpuPO_JfgmHN2tgg9ciN7Qz_9YvZT6Oh5NXmfsJlmnxZOEjpidy7UH2mYDZdHqHrSkwwxemYECkyv2XSjIHRbfuuRW0fuObR1ydkg1T2WJUcYlBKLoLYKT5S0R91DnqRbovokjsFvxI_BR6OLDCpjF4HfZUD7q3m2J0DdAChhz6MuVx-2e9Qu7QtsDdSJg8yivMKg778a-82W9qs9O4LEC2_gMtc52CQtms2T_fKA-KW6SnWUuJQKqdynS4pHfI8a8yEmBZ151_BZppVFNWSS1b_qEpDCMtIlQ6JpMLaJdeDEkccix59CG96fCKAVwf8=w252-h250-s-no?authuser=0)"></td>
    <td><img src="[https://drive.google.com/file/d/1gh3viQ8X89L8dC97zqjBmKDTvNFpGMEn/view?usp=sharing](https://lh3.googleusercontent.com/Wk8sdGz1BWMx-Q-aPKEXlXzEyBmQk3w9V_m6BJVg03JezR0aILh16Sbg0RIAWkA7ZOS5G3Zg0asUotQPA31zDX8TxryjhqYcvea5ZIMvZ7qauNYvdX4BCC8K-oERj9A93xKu3ctRj0yEEgp9eGOZMgjjFxPu6pUa9G5bs7mv44jgC3CCGqTvc81AUamvoLu5Ih-uFqFTWpoM8dag6s19odz-lv-OUKd5i5k-IR_dHfbj4-f5Tw3fWdnXOCrA7TX30LVYeGWwLLnMAdidM-b_LW9HXaC2V3MudVHxQR9H2Qypapw46NTt2OkPCBvXi5W6qnPfQgyomLzZG9eNBk4p3nPud9KzqqU-mmL1zHnoArrnWhCbQpj7wGYb3renx8O6b08LvRexi-Ev2FaSWSWb8yXzIHacU-3qfLu6J50-CB8aaKsDBqcgRCjIWLyDGJoo8b0DkkE1Vngyh2uTzsQI4T_n0WnyhhNpHfEQtQJ_fFngWZDlUegTXGd1WqY_MouYXt7Azc1jQxhgi884Q7XLse3Gwr7YsXqLp4u1YiuxwTBSfEHNSWsjtYVpOR2nfJVD2Bn1fiCdjvXRBcu0hHxOUFczRViHdn1-IDzJRdFLwNI1WfzGDm4JbIsAY5h0bZC6MFzkMAIQ3ykAeUtrEDHsm6Y9XgTZNHsZc6gkVeY33vAGR6WN93p4Nu-AbmnoBfgPPn4EAcW5CS_m9xIOlH2gihyO9MOvPpJqJEd2NoepEnApPn-XcUCeII47p75Kjx0aPHGukslSMMcQ340UZ0_BxDTaUg6rrxuaEtq_V0wXE4yiJkR-y9MmreIo5BGO3juFc9QzBtROI2bwHN-jyZF4WSN8dKHVN_ADk9Lq7AVHY-NRDSdlfsfDPIWhRUT_208m096lTUFgXjumF92kAMsPzSTX4Sht4TYw6dKvjiygB9E_5kLaY_YtC5UdaXmjRfd_Vr_7kF4e8NL_hMjlmpU=w251-h250-s-no?authuser=0)"></td>
  </tr>
</table>

##Conclusion 
In conclusion, we have developed a Convolutional Neural Network model using various architectures and optimizers to classify male and female images. The best accuracy was achieved using the RMSprop optimizer. We also experimented with transfer learning using VGG16 and saw a slight improvement in performance. The model was able to accurately predict gender even with varying facial expressions and the presence of glasses. This project can be further improved by exploring additional techniques such as data augmentation and fine-tuning
